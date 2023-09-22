# Catenary Maps

Catenary Maps is an open-source, no-ads, no-paywall public transport map software. We're a team of students, computer scientists, and transit enthusists. We are providing transit riders with quality-of-life information by innovating and designing routing, ETA, and other algorithms, curating and displaying high quality realtime data.

Catenary Maps's supporting foundation is Catenary Transit Initative, Inc (a registered nonprofit public benefit corporation of California.

## Current Maintainers

- Kyler Chin<sup>1</sup> (he/him) - Founder, Director, Boardmember, Systems Programmer, Algorithms, Frontend, Design
- Josh Wong<sup>2 3</sup> (he/him) - Sysadmin, Systems Programmer, Algorithms
- Kin Tsang (he/him) <sup>3</sup> - Systems Architecture, Boardmember, Algorithms
- Andrew Shen (he/him) <sup>1</sup> - Frontend/Flutter, Boardmember
- Samuel Sharp (he/him) <sup>4</sup> - Frontend/Flutter, Design, UX/UI

1. University of California, Irvine
2. Santa Monica College
3. Don Bosco Technical Institute, Rosemead
4. San Diego High School

Join us on Discord! https://discord.gg/6BjnxthQ

## Guide to repositories
Svelte Frontend: [catenary-frontend](https://github.com/CatenaryMaps/catenary-frontend)
Rust Backend for routing algorithms and data processing and ingest: [catenary-backend](https://github.com/CatenaryMaps/catenary-backend)
Rust Cache Server for GTFS-rt caching: [kactus-gtfs-rt](https://github.com/CatenaryMaps/kactus-gtfs-rt)
Flutter Cross-platform Frontend (literally progress at snails pace) [catenary-flutter](https://github.com/CatenaryMaps/catenary-flutter)
ZotGTFS, Making GTFS-rt and static data from Transloc [zotgtfs](https://github.com/CatenaryMaps/zotgtfs)

Notes: https://github.com/CatenaryMaps/cantenarymaps

## Developer Guide / Getting Started

Join the discord. Also, all the notes are here https://github.com/CatenaryMaps/cantenarymaps and here 

Roadmap:
https://github.com/orgs/CatenaryMaps/projects/1/

Also we try to use Rust as much as possible. 

## Lore

In 2023 June, Kyler began writing software to cache GTFS realtime data. https://github.com/CatenaryMaps/kactus-gtfs-rt. After several weeks. he then started to work on a Svelte realtime map demo. He began to share his work in several Discord servers around computer science at UC Irvine and LA Metro enthusiast Discord servers. The temporary name, "Kyler's Transit Map" held until 2023 Sep 22, while "Catenary" was the project codename. Several people began contributing code and server resources, and the codebase, community, and computer infrastructure began to grow.  

On 2023-09-22, several maintainers decided to formally rename it "Catenary Maps", and create a supporting foundation.

## What's next for us?

We want to create a deliverable product over the next several weeks. We want to add Geocoding, Departure and Arrival Algorithms and info, Transfer and Route information, Routing algorithms for Bike, Pedestrian, and wheelchairs, etc. We want to also launch a mobile app using Flutter.
