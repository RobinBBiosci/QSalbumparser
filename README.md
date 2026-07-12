# QuickStatements Album & Track Parser
> Build QuickStatements 3.0 V1 commands for Wikidata album & audio track items, populated from Discogs or Bandcamp entries.

*Last updated 10 June 2026* 

## Introduction

This is a simple tool to produce [QuickStatements 3.0](https://qs-dev.toolforge.org/)-friendly V1 commands to create new [Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page) items for audio tracks of musical albums, add those tracks as a tracklist for the album's Wikidata item, and add additional album information. You can add tracks based on an album's [Discogs](https://www.discogs.com/) page, [Bandcamp](https://bandcamp.com/) page, or manually.

* Tracks will have **shared** properties: Description in English, instance of (P31), performer (P175), and title (P1476) language.

* Tracks will have **unique** properties: Label in English, title (P1476), and duration (P2047) in seconds.

* When adding tracks to an album's tracklist property (P658), tracks will be given the **qualifiers** of series ordinal (P1545) in the order in which they are listed and duration (P2047) in seconds.

## Before You Begin
* Be familiar with [Wikidata's policies and editing guidelines](https://www.wikidata.org/wiki/Wikidata:Introduction).
* Identify or create Wikidata items for the album of interest and its artist/band/performers.
* Log in to your Wiki account and be comfortable with using QuickStatements.

## Note
There is no proof-reading or checks, confirm all information is accurate before submitting to QuickStatements!

Example item: [*IOWA* (2026 album by OHYUNG)](https://www.wikidata.org/wiki/Q138664890)

See [Wikidata:WikiProject Music](https://www.wikidata.org/wiki/Wikidata:WikiProject_Music/en) for data model guidelines and discussions.

## Miscellaneous
This is a free tool created by **Robin Isadora Brown** as [part of her work](https://meta.wikimedia.org/wiki/Trans_Music_Archive) with [Trans Music Archive](https://www.transmusicarchive.org/). If you have any questions, please visit her [Wikipedia User page](https://en.wikipedia.org/wiki/User:RobinIsadorable).

[Vibe-coded](https://www.wikidata.org/wiki/Q133150082) with Anthropic's [Claude AI](https://www.wikidata.org/wiki/Q118876059).

## License
[GPL-3.0 license](https://github.com/RobinBBiosci/QSalbumparser/blob/main/LICENSE) for code

The Robin logo is copyrighted. I retain all rights to it and its derivations.
