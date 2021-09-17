# Feihong's beets quickstart

## Prerequisites

    pip3 install requests flask pylast beautifulsoup4

# Installation

    pip3 install beets

Add `export BEETSDIR=~/work/beets-quickstart` to `~/.bash_profile`

## Commands

Get location of beets config file:

    beet config -p

See stats about your music collection:

    beet stats

Start web server to browse and play your music (visit http://localhost:8337):

    beet web

Import some music:

    beet import ~/chinese-music-processors/youtube/output

List all tracks added in 2021:

    beet ls 'added:2021'

## Links

- [beets docs](https://beets.readthedocs.io/)
