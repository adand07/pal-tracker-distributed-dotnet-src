# PAL Tracker Distributed Dotnet source code

## Quick Start

1. Clone this repo and `cd` into directory
1. Create empty working repository via `mkdir repo && cd repo && git init && cd .."
1. Hydrate patches via `git repo && git am patches/* && cd .."
1. *Make changes to code, rebase, etc etc*
1. Sync patch files with repo via `rm patches/*.patch && cd repo && git format-patch --root -o ../patches && cd ..`
1. Fix tags via `cd repo && java -jar ../git-revisionist-historian-1.5.0.jar --processor cli --config ../grh-config.json --skip-push --remote git@github.com:platform-acceleration-lab/pal-tracker-distributed-dotnet.git && cd ..`

## Installation

1. Obtain Revision Historian via `curl -O https://s3.amazonaws.com/git-revisionist-historian/com/thewoolleyweb/grh/git-revisionist-historian/1.5.0/git-revisionist-historian-1.5.0.jar`


