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

List all tracks added in September 2021:

    beet ls 'added:2021-09'

Remove all tracks added in September 2021:

    beet remove -d 'added:2021-09'

Set rating of tracks added in September 2021 to 4:

    beet modify 'added:2021-09' rating=4

List all tracks with rating of 4 or above:

    beet ls rating:4..

## Links

- [beets docs](https://beets.readthedocs.io/)
