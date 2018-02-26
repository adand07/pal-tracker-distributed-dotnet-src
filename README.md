# PAL Tracker Distributed Dotnet source code

## Quick Start

1. Clone this repo and `cd` into directory
1. Create empty working repository via `mkdir repo && cd repo && git init && cd .."
1. Hydrate patches via `git repo && git am patches/* && cd .."
1. *Make changes to code, rebase, etc etc*
1. Sync patch files with repo via `rm patches/*.patch && cd repo && git format-patch --root -o ../patches && cd ..`

