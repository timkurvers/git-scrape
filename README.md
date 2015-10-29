# git scrape

Scrapes local git repos and reports:

- Untracked, modified, deleted files and their staging state
- Whether changes should be pushed to a remote tracking branch

Licensed under the **MIT** license, see LICENSE for more information.

![git-scrape](http://office.moonsphere.net/git-scrape.png)

## Installation

Add as a bundle through [Antigen]:

```shell
antigen bundle timkurvers/git-scrape
```

## Usage

Defaults to current working directory:

```shell
git scrape
```

Or may be given a directory to search under:

```shell
git scrape ~/repos
```

[Antigen]: https://github.com/zsh-users/antigen
