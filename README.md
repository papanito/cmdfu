# cmdfu

Queries commandlinefu.com

## Overview

Queries https://commandlinefu.com and presents the user with a list from which she can select a command. Alternatively one can display/download the content to a file.

Usage: `cmdlfu -t -d <search_string>`

* -d display full context, no selection
* -p show text file instead json
* -t show results tagged with <search_string>
* -r displays random commands in json, or as text using -t

Below you see the internal functions used, they can also be called separately. However the script actually presents the found commands in a searchable list using fzf.



