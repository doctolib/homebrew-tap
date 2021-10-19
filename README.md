# Doctolib Homebrew Tap

## What is Homebrew?

Package manager for macOS (or Linux), see more at https://brew.sh

## What is a Tap?

A third-party (in relation to Homebrew) repository providing installable
packages (formulae) on macOS and Linux.

See more at https://docs.brew.sh/Taps

## How do I install packages from here?

```sh
brew install doctolib/tap/name
```

You can also only add the tap which makes formulae within it
available in search results (`brew search` output):

```sh
brew tap doctolib/tap
```

Note: to clone the tap via SSH you will need to use:

```sh
brew tap doctolib/tap git@github.com:doctolib/homebrew-tap.git
```

While you may search across taps, it is necessary to always use
fully qualified name (incl. the `doctolib/tap/` prefix)
when refering to formulae in external taps such as this one
outside of search.

## What packages are available?

- libpq: PostgreSQL 11 command line client and C headers required to build  Ruby Gem `pg`, without the need to install a full-featured postgre server
