# git scrape

[![MIT License](https://badgen.net/github/license/timkurvers/git-scrape)](LICENSE.md)

Scrapes local git repos and reports:

- Untracked, modified, deleted files and their staging state
- Whether changes should be pushed to a remote tracking branch

![git-scrape](https://user-images.githubusercontent.com/378235/27263692-0f7c732c-546f-11e7-8aaa-25937d46f50e.png)

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
