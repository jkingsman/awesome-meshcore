# Awesome MeshCore [![Awesome list badge](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome MeshCore resources. Pull requests welcome!

MeshCore is a multi-platform system for enabling secure text based
communications utilising LoRa radio hardware. It can be used for off-grid
communication, emergency response & disaster recovery, outdoor activities,
or IoT sensor networks.

## Table of contents

- [Official Resources](#official-resources)
- [Social Media](#social-media)
- [Open Source apps](#free-and-open-source-apps)
- [Open Source Firmware](#free-and-open-source-firmware)
- [Maps and Diagnostics](#maps-and-diagnostics)
- [Preinstalled devices](#preinstalled-devices)
- [Bots](#bots)
- [Country / region Websites](#country--region-websites)
- [Chatgroups/ forums/ ...](#chatgroups-forums-)

--------------------

## Official Resources

- [MeshCore.co.uk](https://meshcore.co.uk/) - The homepage & official documentation
- [The FAQ](https://github.com/meshcore-dev/MeshCore/blob/main/docs/faq.md)
- [MeshCore Web Flasher](https://flasher.meshcore.co.uk/)
- [Video: How to get started ](https://redirect.invidious.io/watch?v=t1qne8uJBAc) with MeshCore (Also on [youtube](https://youtu.be/t1qne8uJBAc))

## Social Media

- [Official Discord](https://discord.gg/ZVH2ujy9ex)
- [Reddit r/MeshCore](https://www.reddit.com/r/meshcore/)
- [Facebook](https://www.facebook.com/MeshCoreOfficial)
- [YouTube](https://www.youtube.com/@meshcore-official)
- [YouTube - Andy Kirby](https://www.youtube.com/@andykirby)

## Free and Open Source apps

| Project Name | Description | First Commit |
| :--- | :--- | :---: | 
| [Meshcore Open](https://github.com/zjs81/meshcore-open) ![GitHub Repo stars](https://img.shields.io/github/stars/zjs81/meshcore-open?style=social) | Client app (Flutter) for phones and desktop computers (Android, iOS, GNU/Linux, Windows, macOS) |  Dec 25 |
| [MeshMonitor](https://github.com/Yeraze/meshmonitor) ![GitHub Repo stars](https://img.shields.io/github/stars/Yeraze/meshmonitor?style=social)  | Web tool for monitoring a Meshtastic and Meshcore Node Deployment over TCP/HTTP |  Sep 25 |
| [Potato Mesh](https://github.com/l5yth/potato-mesh) ![GitHub Repo stars](https://img.shields.io/github/stars/l5yth/potato-mesh?style=social) | Federated web frontend to networks |  Sep 25 |
| [Meshcore-HA](https://github.com/meshcore-dev/meshcore-ha) ![GitHub Repo stars](https://img.shields.io/github/stars/meshcore-dev/meshcore-ha?style=social) | Home Assistant integration for MeshCore | Mar 25 |
| [pyMC_Repeater](https://github.com/rightup/pyMC_Repeater) ![GitHub Repo stars](https://img.shields.io/github/stars/rightup/pyMC_Repeater?style=social)  | Repeater Daemon in Python (pymc_core) |  Oct 25 |
| [RemoteTerm](https://github.com/jkingsman/Remote-Terminal-for-MeshCore) ![GitHub Repo stars](https://img.shields.io/github/stars/jkingsman/Remote-Terminal-for-MeshCore?style=social)  | Server and web-frontend for static companions |  Jan 26 |
| [Meshcore-Wardrive](https://github.com/mintylinux/Meshcore-Wardrive-Android) ![GitHub Repo stars](https://img.shields.io/github/stars/mintylinux/Meshcore-Wardrive-Android?style=social)  | Android wardriving and mapping app | Jan 26 |
| [MeshFirmware](https://github.com/mikecarper/meshfirmware) ![GitHub Repo stars](https://img.shields.io/github/stars/mikecarper/meshfirmware?style=social)  | Windows/Linux USB firmware updater |  Feb 25 |
| [MC-WebUI](https://github.com/MarekWo/mc-webui) ![GitHub Repo stars](https://img.shields.io/github/stars/MarekWo/mc-webui?style=social)  | WebUI for meshcore-cli |  Dec 25 |
| [PocketMesh](https://github.com/Avi0n/PocketMesh) ![GitHub Repo stars](https://img.shields.io/github/stars/Avi0n/PocketMesh?style=social)  | Native MeshCore client for iOS & iPadOS |  Dec 25 |
| [MeshCore MQTT Live Map](https://github.com/yellowcooln/meshcore-mqtt-live-map) ![GitHub Repo stars](https://img.shields.io/github/stars/yellowcooln/meshcore-mqtt-live-map?style=social) | Real-time live map for MeshCore using MQTT packet/log topics. |  Dec 25 |
| [pyMC Console](https://github.com/dmduran12/pymc_console-dist) ![GitHub Repo stars](https://img.shields.io/github/stars/dmduran12/pymc_console-dist?style=social)  | Real-time web dashboard for repeaters |  Dec 25 |
| [Meshcore Hub](https://github.com/ipnet-mesh/meshcore-hub) ![GitHub Repo stars](https://img.shields.io/github/stars/ipnet-mesh/meshcore-hub?style=social)  | Web frontend for Meshcore stats |  Dec 25 |
| [Meshcore Web Keygen](https://github.com/agessaman/meshcore-web-keygen) ![GitHub Repo stars](https://img.shields.io/github/stars/bliksemlabs/PyMeshCoreGUI?style=social)  | Generate keys with custom hex prefixes [public instance](https://gessaman.com/mc-keygen/) |  Aug 25 |
| [PyMeshCore GUI](https://github.com/bliksemlabs/PyMeshCoreGUI) ![GitHub Repo stars](https://img.shields.io/github/stars/bliksemlabs/PyMeshCoreGUI?style=social)  | Desktop application for MeshCore | Jan 26 |
| [Sestriere](https://github.com/atomozero/Sestriere) ![GitHub Repo stars](https://img.shields.io/github/stars/atomozero/Sestriere?style=social) | Native MeshCore client for Haiku OS. | Feb 26 |
| [Tactical Emergency Area Messaging](https://github.com/tmacinc/meshcore-team-alpha) ![GitHub Repo stars](https://img.shields.io/github/stars/tmacinc/meshcore-team-alpha?style=social)  | Android application for position tracking and messaging | Jan 26 |
| [Tui-Meshcore](https://github.com/guax/tui-meshcore) ![GitHub Repo stars](https://img.shields.io/github/stars/guax/tui-meshcore?style=social)  | A TUI based meshcore client for linux hosts |  Feb 26 |
| [Meshcore Drone Updater](https://github.com/lucidnx/meshcore-drone-updater) ![GitHub Repo stars](https://img.shields.io/github/stars/lucidnx/meshcore-drone-updater?style=social)  | updates meshcore nodes via drones to upgrade firmware on physically unreachable nodes |  Dec 25 |
| [Meshcore GUI Linux](https://github.com/pe1hvh/meshcore-gui) ![GitHub Repo stars](https://img.shields.io/github/stars/pe1hvh/meshcore-gui?style=social)  | Desktop Linux GUI via BLE |  Feb 26 |

## Free and Open Source firmware

| Project Name | Description | Stars | First Commit |
| :--- | :--- | :---: | :--- |
| [Cardputer ADV (Stachugit ver)](https://github.com/Stachugit/MeshCore-Cardputer-ADV) | Cardputer ADV Specialized UI | 59 | Jan 26 |
| [Lunacore](https://github.com/STCisGOOD/lunarcore) | ESP32 Multi-protocol firmware (MeshCore/MT/Reticulum) | 58 | Jan 26 |
| [MC Term (Dabeani)](https://github.com/dabeani/meshcore) | T-Deck/ T-Deck + & SenseCap Indicator firmware with UI | 50 | Jan 26 |
| [Wio Tracker L1 Pro](https://github.com/sosprz/Meshcore-Wio-Tracker-L1-Pro) | Wio Tracker L1 Pro Custom firmware | 28 | Jan 26 |
| [Cardputer ADV (Sosprz ver)](https://github.com/sosprz/meshcore-cardputer-adv) | Cardputer ADV Specialized UI | 17 | Feb 26 |
| [CubeCellMeshCore](https://github.com/atomozero/CubeCellMeshCore) | A minimal MeshCore-compatible repeater firmware for Heltec CubeCell boards | 6 | Jan 26 |
| [Meck](https://github.com/pelgraine/Meck) | T-Deck pro | 3 | Jan 25 |
| [TapTap (T1000-E)](https://github.com/mtoolstec/TapTapFW) | T1000-E & WisMesh Tag. enhanced messaging capabilities and specific button interactions | 3 | Feb 26 |
| [MeshCore Evo](https://github.com/mattzzw/MeshCore-Evo/releases) | Repeater firmware based on the official firmware with adaptions and improvements for big or high density areas, e.g. dealing with flood advert traffic, duty cycle handling, &hellip; See [release notes](https://github.com/mattzzw/MeshCore/releases) for information; also [hansemesh](https://hansemesh.de/repeater#firmware) (in German). | 10 (as of 2026-02-26) | ?? (fork of [official firmware](https://github.com/meshcore-dev/MeshCore), kept in sync (as of 2026-02-26)) |


## Maps and Diagnostics

| Project / URL | Description |
| :--- | :--- |
| [mapme.sh](https://mapme.sh/) | Community map for reporting signal reports and coverage footprints from users. |
| [meshrank.net](https://meshrank.net/) | Leaderboard and analytics site ranking MeshCore repeaters and routes, primarily in the UK. |
| [meshcoresim.com](https://www.meshcoresim.com/) | Simulation tool for modeling message propagation and testing network scalability. |
| [map.meshradio.uk](https://map.meshradio.uk/) | Network analysis and visualization tool specifically for the UK MeshRadio community. |
| [analyzer.letsmesh.net](https://analyzer.letsmesh.net/) | Packet analyzer for debugging MeshCore traces, paths, and real-time network traffic. |
| [meshmapper.net](https://meshmapper.net) | Regionally segmented mapping tool for signal quality and noise floor data. |
| [map.meshcore.dev](https://map.meshcore.dev/) | Official global map displaying static user uploads for repeaters and room servers. |
| [m3sh.uk](https://m3sh.uk) | Regional map portal showing the UK network topology as seen from Oxfordshire. |
| [meshrf.net](https://meshrf.net/) | RF propagation and link analysis tool designed for LoRa Mesh |
| [Mesh Utility](https://mesh-utility.org/) | Progressive Web App for mapping MeshCore LoRa coverage with optional cloud ingestion |
| [MCSim](https://github.com/Brent-A/mcsim) | Simulation framework for MeshCore LoRa mesh networking firmware |


## Preinstalled devices
| Product | Description |
| :--- | :--- |
| [T-Deck + (Lilygo)](https://lilygo.cc/products/t-deck-plus-1?variant=51618502017205) |  2.8" screen, Qwerty, GPS, ESP32-s3 |
| [T-Lora pager (Lilygo)](https://lilygo.cc/products/t-lora-pager?pr_prod_strat=jac&pr_rec_id=0c4d477a3&pr_rec_pid=8223446597813&pr_ref_pid=8115572179125&pr_seq=uniform)|  2.3" screen, Qwerty, GPS, ESP32-s3 |


## Bots

| Project / URL | Connection | Description |
| :--- | :--- | :--- |
| [Agessaman's Meshcore bot](https://github.com/agessaman/meshcore-bot) | Serial, BLE or TCP/IP | Responds to commands |
| [CycleNerd's Meshcore bot](https://github.com/Cyclenerd/meshcore-bot) | Serial | Responds to commands |
| [Map Auto Uploader](https://github.com/recrof/map.meshcore.dev-uploader) | Serial | Bot will upload every repeater or room server to the map when companion hears new advert|
| [UK Mesh WX](https://github.com/hostyorkshire/UKmeshWX) |  | A Python utility for broadcasting UK weather data using real-time weather data from Open-Meteo API |


## Country / region Websites

### Europe
- Austria
   - [Meshcore Austria](https://www.meshcore-austria.at/doku.php?id=start)
- Czech Republic
  - [Meshcore Czechia](https://meshcore.cz/)
- France
  - [Meshcore France](https://www.meshcore.fr/) 
- Germany
  - German MeshCore wiki: [meshcore-de.fyi](https://meshcore-de.fyi/)
  - [Braunschweig Mesh](https://bsmesh.de/)
  - [Hansemesh](https://hansemesh.de/) (greater Hamburg region)
  - [Mesh Rheinland](https://www.meshrheinland.de/)
  - [Taunus Mesh](https://www.taunus-mesh.de/) (area enclosed by Frankfuurt(Main), Bingen, Koblenz, Giessen)
  - [Sachsen (mostly Leipzig)](https://mesh-sn.de)
  - [VoyagerMesh Dresden](https://loramesh-dresden.de/)
- Great Britain
  - [MeshCore UK](https://meshcore.co.uk/)
  - [Ipswich Net](https://ipnt.uk/)
- Hungary
  - [Meshcore Hungary](https://mc868.hu/) 
- Ireland
  - [Meshcore Ireland](https://loraproject.ie/)
  - [Mayo Mesh](https://mayomesh.net/)
- Italy
  - [Meshcore Italia](https://www.meshcoreitalia.it) 
- Latvia
  - [MeshCore Latvia](https://apraide.lv/)
- Netherlands
  - [Meshcore Netherlands ](https://www.localmesh.nl/en/)
- Poland
  - [Meshcore Poland](https://lorameshcore.pl/)
- Portugal
  - [MeshCore Portugal](https://meshcore.pt/)
- Romania
  - [Brașov Mesh](https://brasovmesh.com/)
- Slovak Republic
  - [Meshcore Slovakia](https://mesh.om3kff.sk/) 
- Spain
  - [NomadMesh Alpujarras, Spain](https://nomadmesh.org/)
  - [Meshcore Catalonia (Spain)](https://meshcore.cat/)
  - [Meshcore Jaén (Spain)](https://sierrasur.github.io/)
- Switzerland
  - [MeshCore Switzerland](https://www.meshcore.ch/)
- Ukraine
  - [MeshCore UA](https://meshcore.kiev.ua/) 



### North America

- Canada
  - [Greater Ottowa Mesh](https://ottawamesh.ca/)
  - [Puget Mesh](https://pugetmesh.org/)
  - [Salish Mesh](https://salishmesh.net/)
  - [West Cost Mesh](https://www.wcmesh.com/)
- USA
  - [Austin, TX](https://www.austinmesh.org/)
  - [Bay Area Meshcore](https://bayareameshcore.org/)
  - [Boston Mesh](https://bostonme.sh/)
  - [CT Mesh](https://ctmesh.org/)
  - [Florida Mesh](https://mc.flmesh.us/)
  - [Idaho Mesh](https://idahomesh.org/)
  - [Minnesota/St Paul Mesh](https://mspmesh.org/)
  - [Meshcore Texas](https://meshcoretx.net/)
  - [Nevada Mesh](https://nvme.sh/)
  - [North Dakota Mesh](https://nodakmesh.org/)
  - [RDUmesh North Carolina Piedmont](https://rdumesh.org/)
  - [Silicon Valley 73 Mesh](https://73mesh.com/)
  - [Spokane Mesh](https://www.spokanemesh.net/)
  - [West coast Mesh](https://www.wcmesh.com/)

### Oceania

- Australia
  - [Brisbane and SEQ](https://wiki.mbug.com.au/en/Meshcore/Settings)
  - [East Mesh](https://eastmesh.au/)
  - [MeshCore Western Australia](https://perth.meshcore.au/)
  - [NSW Mesh](https://nswmesh.au/)


## Chatgroups/ forums/ ...

### Global

- [Official Discord](https://discord.gg/mt7NNZ86RS)
  Many regional channels exist within this discord server
- [Reddit r/meshcore](https://www.reddit.com/r/meshcore/)
- [Forum forum.letsmesh.net](https://forum.letsmesh.net/)
  - with some regional sub-forums

In addition, there are e.g.:

### Europe

#### France
- [MeshCore France Discord](https://discord.gg/GNAfMf7nVw)

#### Ireland
- [Mesh Radio Ireland (N&S) Discord](https://discord.gg/kraQFkpU)

#### Germany
- Matrix room "[MeshCore DE](https://matrix.to/#/#meshcore-netzwerk-de:matrix.org)" inside matrix space "[Mesh Netzwerke DE](https://matrix.to/#/#mesh-netzwerke-de:matrix.org)"
- Signal group "[MeshCore-DE](https://signal.group/#CjQKIFhhdRM1Aeju45MYU8CWOkytMM8E741caAtrSvkDRaJ3EhBu5zU7KUA4w3ad35lIi8Su)"
- Telegram group "[MeshCore DE](https://t.me/meshcorede)"
- Discord "[MeshCore DE](https://discord.gg/uTMJQhh2P5)"
- [WhatsApp group](https://chat.whatsapp.com/KDintomf4QoCu2GkPrnIn1)

### North America

#### USA
- [Boston Mesh Discord](https://discord.gg/MUVASVEEES)
- [CT Mesh Discord](https://discord.gg/m4F328as3K)
- [West coast Mesh Discord](https://discord.gg/wcmesh)

### Oceania
 - [Meshore Australia](https://discord.gg/2NxehNDGT)
 - [Canberra Mesh Community](https://discord.gg/YeGhbsWhQD) (ATC and south NSW)



