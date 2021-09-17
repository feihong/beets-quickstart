# Feihong's beets quickstart

## Prerequisites

    pip3 install requests pylast beautifulsoup4
    pip3 install beets

## Sample config file

```
directory: ~/work/beets-quickstart/music
library: ~/work/beets-quickstart/library.db

import:
  move: yes
  write: yes

plugins: types lyrics lastgenre web

types:
  rating: int
```

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
