# git scrape

Scrapes git repos and reports on their current state:

- Dirty working directory (soon)
- Changes to be pushed to origin (soon)


## Installation

Add as a bundle through [Antigen](https://github.com/zsh-users/antigen):

    antigen bundle timkurvers/git-scrape


## Usage

Defaults to current working directory:

    git scrape

Or may be given a directory to search under:

    git scrape ~/repos
