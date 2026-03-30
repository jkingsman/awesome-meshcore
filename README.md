# Awesome MeshCore [![Awesome list badge](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome MeshCore resources. Pull requests welcome!

MeshCore is a multi-platform system for enabling secure text based
communications utilising LoRa radio hardware. It can be used for off-grid
communication, emergency response & disaster recovery, outdoor activities,
or IoT sensor networks.

## Table of contents

- [Official Resources](#official-resources)
- [Other Resources](#other-resources)
- [Open Source apps](#free-and-open-source-apps)
- [Open Source Firmware](#free-and-open-source-firmware)
- [Software Libraries](#software-libraries)
- [Maps and Diagnostics](#maps-and-diagnostics)
- [Preinstalled devices](#preinstalled-devices)
- [BBS](#bbs)
- [Bots](#bots)
- [Country / region Websites](#country--region-websites)
- [Chatgroups/ forums/ ...](#chatgroups-forums-)

--------------------

## Official Resources

- [MeshCore.co.uk](https://meshcore.co.uk/) - The homepage & official documentation
- [MeshCore.io](https://meshcore.io/) - The new homepage & official documentation
- [The FAQ](https://github.com/meshcore-dev/MeshCore/blob/main/docs/faq.md)
- [MeshCore Web Flasher](https://flasher.meshcore.co.uk/)
- [Official Discord](https://discord.gg/ZVH2ujy9ex)
- [Reddit r/MeshCore](https://www.reddit.com/r/meshcore/)
- [Facebook](https://www.facebook.com/MeshCoreOfficial)
- [YouTube](https://www.youtube.com/@meshcore-official)
- [Video: How to get started ](https://redirect.invidious.io/watch?v=t1qne8uJBAc) with MeshCore (Also on [youtube](https://youtu.be/t1qne8uJBAc))
- [Current state of Meshcore encryption](https://github.com/meshcore-dev/MeshCore/issues/259)

## Other Resources

- [YouTube - Andy Kirby](https://www.youtube.com/@andykirby) (core meshcore / meshos / rippleUI developer)
- [Video: MeshCore Companion Flashing (the comms channel)](https://redirect.invidious.io/watch?v=ems9_XvdPX8) (Also on [youtube](https://youtu.be/ems9_XvdPX8))
- [Video: Using the official Meshcore App (the comms channel)](https://redirect.invidious.io/watch?v=PeThXmxLE4k) (Also on [youtube](https://youtu.be/PeThXmxLE4k))
- [LitBomb's Meshcore FAQ](https://github.com/LitBomb/MeshCore-FAQ) (English and German)
- [Meshcore region info](https://github.com/luckystriike22/meshcore_region_info)
- [MeshCore OTA Firmware Update Guide](https://github.com/Mraanderson/meshcore-ota)


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
| [MC-WebUI](https://github.com/MarekWo/mc-webui) ![GitHub Repo stars](https://img.shields.io/github/stars/MarekWo/mc-webui?style=social)  | WebUI for meshcore-cli (AI code) |  Dec 25 |
| [MeshcoreOne](https://github.com/Avi0n/MeshCoreOne) ![GitHub Repo stars](https://img.shields.io/github/stars/Avi0n/PocketMesh?style=social)  | A MeshCore client built for iOS in Swift. (AI code)|  Dec 25 |
| [Meshcore SAR](https://github.com/dz0ny/meshcore-sar) ![GitHub Repo stars](https://img.shields.io/github/stars/dz0ny/meshcore-sar?style=social) | Helps teams coordinate in low-connectivity or no-connectivity environments with messaging, voice, images, maps, and live location context in one app. (AI code) | Feb 26 |
| [MeshCore MQTT Live Map](https://github.com/yellowcooln/meshcore-mqtt-live-map) ![GitHub Repo stars](https://img.shields.io/github/stars/yellowcooln/meshcore-mqtt-live-map?style=social) | Real-time live map for MeshCore using MQTT packet/log topics. |  Dec 25 |
| [pyMC Console](https://github.com/dmduran12/pymc_console-dist) ![GitHub Repo stars](https://img.shields.io/github/stars/dmduran12/pymc_console-dist?style=social)  | Real-time web dashboard for repeaters |  Dec 25 |
| [Meshcore Hub](https://github.com/ipnet-mesh/meshcore-hub) ![GitHub Repo stars](https://img.shields.io/github/stars/ipnet-mesh/meshcore-hub?style=social)  | Web frontend for Meshcore stats (AI code) |  Dec 25 |
| [Meshcore Web Keygen](https://github.com/agessaman/meshcore-web-keygen) ![GitHub Repo stars](https://img.shields.io/github/stars/bliksemlabs/PyMeshCoreGUI?style=social)  | Generate keys with custom hex prefixes [public instance](https://gessaman.com/mc-keygen/) |  Aug 25 |
| [PyMeshCore GUI](https://github.com/bliksemlabs/PyMeshCoreGUI) ![GitHub Repo stars](https://img.shields.io/github/stars/bliksemlabs/PyMeshCoreGUI?style=social)  | Desktop application for MeshCore | Jan 26 |
| [Sestriere](https://github.com/atomozero/Sestriere) ![GitHub Repo stars](https://img.shields.io/github/stars/atomozero/Sestriere?style=social) | Native MeshCore client for Haiku OS. (AI code) | Feb 26 |
| [Tactical Emergency Area Messaging](https://github.com/tmacinc/meshcore-team-alpha) ![GitHub Repo stars](https://img.shields.io/github/stars/tmacinc/meshcore-team-alpha?style=social)  | Android application for position tracking and messaging | Jan 26 |
| [Meshcore Drone Updater](https://github.com/lucidnx/meshcore-drone-updater) ![GitHub Repo stars](https://img.shields.io/github/stars/lucidnx/meshcore-drone-updater?style=social)  | updates meshcore nodes via drones to upgrade firmware on physically unreachable nodes |  Dec 25 |
| [Tui-Meshcore](https://github.com/guax/tui-meshcore) ![GitHub Repo stars](https://img.shields.io/github/stars/guax/tui-meshcore?style=social)  | A TUI based meshcore client for linux hosts |  Feb 26 |
| [Meshcore GUI Linux](https://github.com/pe1hvh/meshcore-gui) ![GitHub Repo stars](https://img.shields.io/github/stars/pe1hvh/meshcore-gui?style=social)  | Desktop Linux GUI via BLE |  Feb 26 |
| [MeshCore Email Gateway](https://github.com/MGJ520/MeshCore-Email-Gateway) ![GitHub Repo stars](https://img.shields.io/github/stars/MGJ520/MeshCore-Email-Gateway?style=social)  | This gateway allows you to send and receive messages from MeshCore RF nodes using ordinary email, and comes with a web‑based management interface | Mar 26 |
| [MC-Keygen](https://github.com/samschlegel/meshcore-utils)  ![GitHub Repo stars](https://img.shields.io/github/stars/samschlegel/meshcore-utils?style=social) | Vanity Ed25519 key generator for MeshCore. (AI Code) | Feb 26 |
| [Esphome Meshcore (sensor) Component](https://github.com/netmilk/esphome-meshcore) ![GitHub Repo stars](https://img.shields.io/github/stars/netmilk/esphome-meshcore?style=social) | Control anything ESPHome can touch — switches, sensors, fans, lights — over long-range LoRa mesh, managed from MeshCore Companion. | Mar 26 |
| [MeshCore Wireshark Dissector](https://github.com/aaronb/wireshark-meshcore) ![GitHub Repo stars](https://img.shields.io/github/stars/aaronb/wireshark-meshcore?style=social) | Wireshark protocol dissector and pcapng converter for MeshCore LoRa mesh networking | Mar 26 |
| [MeschaTUI](https://github.com/g-d-j-evans/MeschaTUI) ![GitHub Repo stars](https://img.shields.io/github/stars/g-d-j-evans/MeschaTUI?style=social) | A textual TUI wrapper over Meshcore_py | Jan 26 |
| [Spectra](https://forge.hackers.town/Wrewdison/Spectra) | Spectra is a bridge for Mesh Radios like MeshCore and Meshtastic, powered by Veilid. | Mar 26 | 
| [MeshCore Insights](https://github.com/BomBefok/MeshcoreInsights)  ![GitHub Repo stars](https://img.shields.io/github/stars/BomBefok/MeshcoreInsights?style=social) | A Graphical software interface to interact with Meshcore companion nodes. | Mar 26 | 
| [Yours](https://github.com/STCisGOOD/yours-x-lunarcore)  ![GitHub Repo stars](https://img.shields.io/github/stars/STCisGOOD/yours-x-lunarcore?style=social) | Encrypted P2P messaging over LoRa mesh, using Lunacore firmware | Mar 26 | 
| [MeshOS for Android](https://github.com/andymux/meshos-releases) ![GitHub Repo stars](https://img.shields.io/github/stars/andymux/meshos-releases?style=social) | MeshOS for Android - An official MeshCore App  | Mar 26  | 
| [Meshy](https://codeberg.org/sesivany/meshy) | a GTK4/libadwaita client for MeshCore. The goal, to provide the best Linux experience | Mar 26 | 
| [Roadstr](https://github.com/jooray/roadstr) ![GitHub Repo stars](https://img.shields.io/github/stars/jooray/roadstr?style=social) | Decentralized road-event reporting using Nostr and MeshCore. Web and Android - "Waze without the centralized tracking" | Mar 26 |
| [MeshCore HA UI](https://github.com/Ratty7198/MeshCore-HA-UI) ![GitHub Repo stars](https://img.shields.io/github/stars/Ratty7198/MeshCore-HA-UI?style=social)| A companion HACS integration that adds a full-featured dashboard for your MeshCore mesh network in Home Assistant (requires meshcore-ha) | Mar 26 | 
| [Meshcute](https://github.com/MadScientistCH/meshcute) ![GitHub Repo stars](https://img.shields.io/github/stars/MadScientistCH/meshcute?style=social) | Meshcute is a universal toolbox for what you need when having a Meshcore or Meshtastic meeting  | Mar 26 |
| [Pico Meshcore](https://github.com/Vigoleis912/PicoMeshCore) ![GitHub Repo stars](https://img.shields.io/github/stars/Vigoleis912/PicoMeshCore?style=social) | A lightweight MeshCore Companion client written in MMBasic for the PicoMite (Raspberry Pi Pico). | Mar 26  |

## Free and Open Source firmware

| Project Name | Description | First Commit |
| :--- | :--- | :---: |
| [Lunacore](https://github.com/STCisGOOD/lunarcore) ![GitHub Repo stars](https://img.shields.io/github/stars/STCisGOOD/lunarcore?style=social) | ESP32 Multi-protocol firmware (MeshCore/MT/Reticulum) | Jan 26 |
| [Cardputer ADV (Stachugit ver)](https://github.com/Stachugit/MeshCore-Cardputer-ADV) ![GitHub Repo stars](https://img.shields.io/github/stars/Stachugit/MeshCore-Cardputer-ADV?style=social) | Cardputer ADV Specialized UI | Jan 26 |
| [MC Term (Dabeani)](https://github.com/dabeani/meshcore) ![GitHub Repo stars](https://img.shields.io/github/stars/dabeani/meshcore?style=social) | T-Deck/ T-Deck + & SenseCap Indicator firmware with UI | Jan 26 |
| [Wio Tracker L1 Pro](https://github.com/sosprz/Meshcore-Wio-Tracker-L1-Pro) ![GitHub Repo stars](https://img.shields.io/github/stars/sosprz/Meshcore-Wio-Tracker-L1-Pro?style=social) | Wio Tracker L1 Pro Custom firmware | Jan 26 |
| [MeshCore Evo](https://github.com/mattzzw/MeshCore-Evo/) ![GitHub Repo stars](https://img.shields.io/github/stars/mattzzw/MeshCore-Evo?style=social) | Repeater firmware based on the official firmware with adaptions and improvements for big or high density areas, e.g. dealing with flood advert traffic, duty cycle handling. See [release notes](https://github.com/mattzzw/MeshCore/releases) for information; also [hansemesh](https://hansemesh.de/repeater#firmware) (in German). | Feb 26 |
| [Cardputer ADV (Sosprz ver)](https://github.com/sosprz/meshcore-cardputer-adv) ![GitHub Repo stars](https://img.shields.io/github/stars/sosprz/meshcore-cardputer-adv?style=social) | Cardputer ADV Specialized UI | Feb 26 |
| [Trail Mate](https://github.com/vicliu624/trail-mate) ![GitHub Repo stars](https://img.shields.io/github/stars/vicliu624/trail-mate?style=social)| offline‑first handheld system for GPS navigation, LoRa communication, and real‑time team situational awareness in no‑network environments. | Jan 26 |
| [ZephCore](https://github.com/liquidraver/ZephCore) ![GitHub Repo stars](https://img.shields.io/github/stars/liquidraver/ZephCore?style=social) | A port of MeshCore LoRa mesh firmware from Arduino to Zephyr RTOS | Mar 26 | 
| [CubeCellMeshCore](https://github.com/atomozero/CubeCellMeshCore) ![GitHub Repo stars](https://img.shields.io/github/stars/atomozero/CubeCellMeshCore?style=social) | A minimal MeshCore-compatible repeater firmware for Heltec CubeCell boards | Jan 26 |
| [Meck](https://github.com/pelgraine/Meck) ![GitHub Repo stars](https://img.shields.io/github/stars/pelgraine/Meck?style=social) | T-Deck pro | Jan 25 |
| [TapTap (T1000-E)](https://github.com/mtoolstec/TapTapFW) ![GitHub Repo stars](https://img.shields.io/github/stars/mtoolstec/TapTapFW?style=social) | T1000-E & WisMesh Tag — enhanced messaging capabilities and specific button interactions | Feb 26 |
| [Mesh Loader](https://github.com/eliahreeves/mesh-loader) ![GitHub Repo stars](https://img.shields.io/github/stars/eliahreeves/mesh-loader?style=social) | "Dual Boot" firmware for running Meshcore and Meshtastic on a single ESP32 based device without re-flashing. | Feb 26 |
| [Meshcomod](https://github.com/ALLFATHER-BV/meshcomod) ![GitHub Repo stars](https://img.shields.io/github/stars/ALLFATHER-BV/meshcomod?style=social) | MeshCore addon for Heltec WiFi LoRa 32 V4 | Feb 26 |
| [Aurora](https://forge.hackers.town/wrewdison/aurora) | Meshcore firmware for the Lilygo T-Deck, as an alternative to Ripple. | Jan 26 |
| [MCLite](https://github.com/laserir/MCLite) ![GitHub Repo stars](https://img.shields.io/github/stars/laserir/MCLite?style=social) | Lightweight off-grid communicator firmware for the LilyGo T-Deck Plus - perfect for kids, older family members, or anyone who just needs it to work.| Mar 26 |
| [Meshcore custom firmware builder](https://github.com/christian45410/meshcore-cfw-builder) ![GitHub Repo stars](https://img.shields.io/github/stars/christian45410/meshcore-cfw-builder?style=social) | A web-based firmware builder for MeshCore. Select your board, firmware type, and custom flags — get a compiled .bin back. | Mar 26 |
| [MeshcoreGRID](https://github.com/Quark1980/MeshcoreGRID)  ![GitHub Repo stars](https://img.shields.io/github/stars/Quark1980/MeshcoreGRID?style=social) | MeshcoreGRID is a touch-first handheld firmware built on MeshCore | Jan 26 |
| [weebl2000's MeshCore Firmware Builder](https://mcimages.weebl.me/) | Build and download firmware images for your device.|  |
| [Heltec V4.2 Multi-Boot Selector](https://github.com/Finmacjones/HeltecV4.2MultiBoot)  ![GitHub Repo stars](https://img.shields.io/github/stars/Finmacjones/HeltecV4.2MultiBoot?style=social) | Multi-firmware boot selector for Heltec WiFi LoRa 32 V4.2 (ESP32-S3) | Mar 26 |
| [Meshcore T-beam-1W](https://github.com/mintylinux/Meshcore-T-beam-1W-Firmware) ![GitHub Repo stars](https://img.shields.io/github/stars/mintylinux/Meshcore-T-beam-1W-Firmware?style=social) | Meshcore firmware for the Lilygo T-beam 1 Watt | Feb 26 | 
| [Chiyocore](https://github.com/kore-signet/chiyocore) ![GitHub Repo stars](https://img.shields.io/github/stars/kore-signet/chiyocore?style=social) | an implementation of meshcore for ESP32s, written in rust | Mar 26 |

## Software Libraries

| Project Name | Description | First Commit |
| :--- | :--- | :---: |
| [MeshCoreKmp](https://github.com/Wavesonics/MeshCoreKmp) ![GitHub Repo stars](https://img.shields.io/github/stars/Wavesonics/MeshCoreKmp?style=social) | A Kotlin Multiplatform library for connecting to and communicating with MeshCore companion nodes. | Feb 26 |
| [Meshcore Client](https://github.com/dz0ny/meshcore_client) ![GitHub Repo stars](https://img.shields.io/github/stars/dz0ny/meshcore_client?style=social) | Flutter/Dart package implementing the MeshCore BLE companion protocol | Feb 26 |
| [Meshcore Decoder](https://github.com/michaelhart/meshcore-decoder) ![GitHub Repo stars](https://img.shields.io/github/stars/michaelhart/meshcore-decoder?style=social) | A TypeScript library for decoding MeshCore mesh networking packets with full cryptographic support.  | Sep 25  |


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
| [Meshcore Geo Prune](https://static.pixelentry.de/meshcore/geo-prune/) | Clean up your contact list based on geofencing |
| [UK Mesh Network](https://www.ukmesh.com/) | UK-wide public site for MeshCore traffic, repeater coverage, observer ingestion, and the supporting documentation behind the live map. [github](https://github.com/gadgethd/ukmesh) |
| [Mesh Community Planner](https://github.com/PapaSierra555/MeshCommunityPlanner/) | Desktop application for planning LoRa mesh network deployments with terrain-aware RF propagation, hardware selection, and bill of materials generation. |
| [MeshCore Wall of Shame](https://advertrank.com/) | Who's flooding the mesh today? a lighthearted look at mesh traffic, not a witch hunt. | 
| [CoreScope](https://github.com/Kpa-clawbot/CoreScope) | network analyzer — live packet visualization, VCR replay, channel decryption, node health, analytics |
| [Map Tiles Downloader](https://github.com/tekk/map-tiles-downloader) | This app helps you fetch map tiles quickly, for offline use with meshcore and other mesh networks |
| [uMap "Meshcore Regionen Deutschland"](https://umap.openstreetmap.de/de/map/meshcore-regionen-deutschland_122026#6/51.896834/9.843750) | Editable map of regions, mainly Germany. (Please also read [this context info](https://meshcore-de.fyi/meshcore:allgemeines:regions:reale-regions-in-repeatern).) |


## Preinstalled devices

| Product | Description |
| :--- | :--- |
| [T-Deck + (Lilygo)](https://lilygo.cc/products/t-deck-plus-1?variant=51618502017205) |  2.8" screen, Qwerty, GPS, ESP32-s3 |
| [T-Lora pager (Lilygo)](https://lilygo.cc/products/t-lora-pager?pr_prod_strat=jac&pr_rec_id=0c4d477a3&pr_rec_pid=8223446597813&pr_ref_pid=8115572179125&pr_seq=uniform)|  2.3" screen, Qwerty, GPS, ESP32-s3 |


## BBS

| Project Name | Description | First Commit |
| :--- | :--- | :---: |
| [Mesh Citadel](https://github.com/taedryn/mesh-citadel) ![GitHub Repo stars](https://img.shields.io/github/stars/taedryn/mesh-citadel?style=social) | A MeshCore-first BBS, inspired by the Citadel BBSes of the 80s | Sep 25 | 

## Bots

| Project / URL | Connection | Description |
| :--- | :--- | :--- |
| [Agessaman's Meshcore bot](https://github.com/agessaman/meshcore-bot) ![GitHub Repo stars](https://img.shields.io/github/stars/agessaman/meshcore-bot?style=social) | Serial, BLE or TCP/IP | Responds to commands |
| [CycleNerd's Meshcore bot](https://github.com/Cyclenerd/meshcore-bot) ![GitHub Repo stars](https://img.shields.io/github/stars/Cyclenerd/meshcore-bot?style=social) | Serial | Responds to commands |
| [Map Auto Uploader](https://github.com/recrof/map.meshcore.dev-uploader) ![GitHub Repo stars](https://img.shields.io/github/stars/recrof/map.meshcore.dev-uploader?style=social) | Serial | Bot will upload every repeater or room server to the map when companion hears new advert|
| [Meshcore to Discord Bridge](https://github.com/Hude06/MeshCoreDiscordBridge) ![GitHub Repo stars](https://img.shields.io/github/stars/Hude06/MeshCoreDiscordBridge?style=social) | Serial | provides a bridge between MeshCore and Discord. |


---


## Country / region Websites

### Europe
- Austria
   - [Meshcore Austria](https://www.meshcore-austria.at/doku.php?id=start)
- Czech Republic
  - [Meshcore Czechia](https://meshcore.cz/)
- Finland
  - [Mesh Pirkanmaa](https://meshpirkanmaa.org/) (Tampere region, including Nokia, Pirkkala, and Ylöjärvi) 
- France
  - [Meshcore France](https://www.meshcore.fr/)
  - [Île-de-France Mesh](https://wiki.mesh-idf.fr)
- Germany
  - German MeshCore wiki: [meshcore-de.fyi](https://meshcore-de.fyi/)
  - [BSmesh](https://bsmesh.de/) (area surrounding Braunschweig, includes several cities)
  - [Hansemesh](https://hansemesh.de/) (greater Hamburg region)
  - [Mesh Rheinland](https://www.meshrheinland.de/)
  - [Taunus Mesh](https://www.taunus-mesh.de/) (area enclosed by Frankfuurt(Main), Bingen, Koblenz, Giessen)
  - [Sachsen (mostly Leipzig)](https://mesh-sn.de)
  - [VoyagerMesh Dresden](https://loramesh-dresden.de/)
- Great Britain
  - [MeshCore UK](https://meshcore.co.uk/)
  - [Ipswich Net](https://ipnt.uk/)
  - [MeshCore Wales](https://meshcore.wales/)
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
  - [Wiki](https://meshwiki.nl/)
- Poland
  - [Meshcore Poland](https://lorameshcore.pl/)
- Portugal
  - [MeshCore Portugal](https://meshcore.pt/)
- Romania
  - [Brașov Mesh](https://brasovmesh.com/)
  - [MeshCore Iasi](https://meshcore-iasi.ro/)
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
  - [CascadiaMesh](https://cascadiamesh.org) - Pacific Northwest, currently covers British Columbia, Western Washington, and Western Oregon.  
  - [Greater Ottowa Mesh](https://ottawamesh.ca/)
  - [Puget Mesh](https://pugetmesh.org/)
  - [Salish Mesh](https://salishmesh.net/)
  - [West Cost Mesh](https://www.wcmesh.com/)
- USA
  - [Austin, TX](https://www.austinmesh.org/)
  - [Bay Area Meshcore](https://bayareameshcore.org/)
  - [Boston Mesh](https://bostonme.sh/)
  - [CascadiaMesh](https://cascadiamesh.org) - Pacific Northwest, currently covers British Columbia, Western Washington, and Western Oregon. 
  - [Colorado Mesh](https://coloradomesh.org/)
  - [CT Mesh](https://ctmesh.org/)
  - [Florida Mesh](https://mc.flmesh.us/)
  - [Idaho Mesh](https://idahomesh.org/)
  - [Kentucky Mesh](https://mesh-ky.org/)
  - [Lexington, KY Mesh](https://meshcorelexington.com/)
  - [Louisiana Mesh](https://louisianamesh.org/)
  - [Minnesota/St Paul Mesh](https://mspmesh.org/)
  - [Meshcore Texas](https://meshcoretx.net/)
  - [Nevada Mesh](https://nvme.sh/)
  - [North Dakota Mesh](https://nodakmesh.org/)
  - [Pioneer Valley Mesh](https://pvmesh.org/) 
  - [RDUmesh North Carolina Piedmont](https://rdumesh.org/)
  - [Silicon Valley 73 Mesh](https://73mesh.com/)
  - [Spokane Mesh](https://www.spokanemesh.net/)
  - [TennMesh](https://tennmesh.com/)
  - [West coast Mesh](https://www.wcmesh.com/)

### Oceania

- Australia
  - [Brisbane and SEQ](https://wiki.mbug.com.au/en/Meshcore/Settings)
  - [East Mesh](https://eastmesh.au/)
  - [MeshCore Western Australia](https://perth.meshcore.au/)
  - [Mesh Sydney](https://meshsydney.com/)
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

#### Netherlands
- [Forum](https://forum.meshcore-net.nl/)
- [Telegram](https://t.me/meshcorenet)
- [Discord](https://discord.com/channels/1343693475589263471/1345472768669384714)

#### Russia
- [Moscow Telegram group](https://t.me/meshcoremoscow)

### North America

#### USA
- [Boston Mesh Discord](https://discord.gg/MUVASVEEES)
- [CascadiaMesh Discord](https://discord.gg/m9yarB3p2E)
- [CT Mesh Discord](https://discord.gg/m4F328as3K)
- [Spokane Mesh Discord](https://discord.gg/VzFcvSxxyr)
- [West coast Mesh Discord](https://discord.gg/wcmesh)

### Oceania
 - [Meshore Australia](https://discord.gg/2NxehNDGT)
 - [Canberra Mesh Community](https://discord.gg/YeGhbsWhQD) (ATC and south NSW)



