# cmdfu

Queries commandlinefu.com

## Overview

Queries https://commandlinefu.com and presents the user with a list from which she can select a command. Alternatively one can display/download the content to a file.

Usage: `cmdlfu -t -d <search_string>``
-d display full context, no selection
-t show text file instead json

Below you see the internal functions used, they can also be called separately. However the script actually presents the found commands in a searchable list using fzf.

## Index

* [cmdfu](#cmdfu)
* [cmdfuj](#cmdfuj)
* [fuman](#fuman)
* [fur](#fur)

### cmdfu

Search commandlinefu.com from the command line using the API and returns text output

#### Arguments

* **$1** (string): text to search

### cmdfuj

Search commandlinefu.com from the command line using the API and returns json output

#### Arguments

* **$1** (string): text to search

### fuman

fuman, an alternative to the 'man' command that shows commandlinefu.com examples

#### Arguments

* **$1** (string): command

### fur

Random Commandlinefu command

_Function has no arguments._

