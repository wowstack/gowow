# WowStack: MPQ archive support

[![AppVeyor Build status][appveyor-image]][appveyor-url]
[![godoc reference][godoc-image]][godoc-url]
[![Go Report Card][gorep-image]][gorep-url]
[![Travis CI Build status][travis-image]][travis-url]

## What gomopaq is

`gomopaq` implements access to Mo'PaQ archives.

Mo'PaQ archives (mpq) are a file format for storing data files, images, sounds,
music and videos for games produced by [Blizzard Entertainment Inc.][blizzard]
It provides content encryption, quick access, various compression methods,
localization of content and content signing.

## What is WowStack?

[WowStack][wowstack] Classic Server implements tools and server runtimes
allowing you to relive the original [World of Warcraft][wow-1] experience using
original game clients for version 1.12.

Our project goals are to preserve this piece of gaming history in the most
complete state for you to enjoy!

## Status

This library is under active development. Our goal is to have a version covered
with tests supporting all World of Warcraft releases that shipped with MPQ
archives.

## Support

Meanwhile we are on [Discord][discord-url], so come chat with us.

Like our work and want to show appreciation? Give the repository a star, visit
our [Patreon][patreon-url] and become an supporter. :heart_eyes:

[![Become a patreon][patreon-image]][patreon-url]

## Legal notice

This project is licensed under the terms of a 3-clause [BSD license](LICENSE.md)
as we strongly believe in sharing.

If you are new to Open Source licensing, you can examine a [detailed][license-url]
description of what the license allows, requires and what is not accepted.

Additional licenses may apply to the 3rd party libraries supplied within the
go `vendor` directory.

> World of Warcraft, and all World of Warcraft or Warcraft art, images, and lore
> are copyrighted by [Blizzard Entertainment, Inc.][blizzard]

[appveyor-image]: https://ci.appveyor.com/api/projects/status/354i6ay0484ww35q?svg=true
[appveyor-url]: https://ci.appveyor.com/project/wowstack/gomopaq
[travis-image]: https://travis-ci.com/wowstack/gomopaq.svg
[travis-url]: https://travis-ci.com/wowstack/gomopaq

[godoc-image]: https://godoc.org/github.com/wowstack/gomopaq?status.png
[godoc-url]: https://godoc.org/github.com/wowstack/gomopaq
[gorep-image]: https://goreportcard.com/badge/github.com/wowstack/gomopaq
[gorep-url]: https://goreportcard.com/report/github.com/wowstack/gomopaq
[license-image]: https://img.shields.io/github/license/wowstack/gomopaq.svg
[license-url]: https://choosealicense.com/licenses/bsd-3-clause/
[coverage-shield]: https://coveralls.io/repos/github/wowstack/gomopaq/badge.svg?branch=master
[coverage-status]: https://coveralls.io/github/wowstack/gomopaq

[patreon-image]: https://c5.patreon.com/external/logo/become_a_patron_button.png
[patreon-url]: https://www.patreon.com/bePatron?u=10897042
[discord-url]: https://discord.gg/TttsRMp

[wowstack]: https://wowstack.io/
[blizzard]: http://blizzard.com/ "Blizzard Entertainment Inc."
[wow-1]: http://blizzard.com/games/wow/ "World of Warcraft"
