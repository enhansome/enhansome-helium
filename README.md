# Awesome helium with stars

![](https://raw.githubusercontent.com/dansku/awesome-helium/master/src/awesome_helium_logo.jpg)

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of all helium projects, tutorials, and resources.

## Contents

* [Community](#community)
* [Software](#software)
* [Hardware](#hardware)
* [Exchanges](#exchanges)
* [Education](#education)
* [Network Operators](#network-operators)
* [Network Servers](#network-servers)

***

## Community

* [Discord](http://discord.gg/helium) - Official Helium Community Discord; many people, very busy
* [Monthly Community Calls](https://docs.google.com/document/d/1bMm2alBigBj3detA775Dn0Gz9UM5XczAeK9vnjBB3l0/edit#) - Noon ET on the last Wednesday of the month
* [Weekly Helium Hacks Happy Hour](https://tinyurl.com/3kjrv9z5) - Every Wednesday at 2p PT

## Software

### Docker Miner

* [Blockchain Sync Progress Script](https://github.com/Doginal/helium-network-scripts) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2020-10-29 - Bash script to get the current progress of your Helium miner running via docker

### End Node Device App Development

#### Development Environments

* [WisBlock Helium Mapper](https://github.com/arkieguy/RAK4631-Helium-Mapper) ⭐ 16 | 🐛 0 | 🌐 C++ | 📅 2021-08-11 - Fork of LoRaWAN Tracker modified to work with Helium Cargo and Mapper Ingest.
* [LoRaWAN Tracker Example Code](https://github.com/beegee-tokyo/RAK4631-LPWAN-Tracker) ⭐ 10 | 🐛 0 | 🌐 C++ | 📅 2021-04-10 - Really good example using WisBlocks
* [Leroy's Updated & Unofficial CubeCell repo](https://github.com/leroyle/ASR650x-Arduino) ⭐ 7 | 🐛 1 | 🌐 C | 📅 2021-03-25 - Heltec ASR650x; Heavily improved.
* [Leroy's WisBlock sample code](https://github.com/leroyle/longfi-platformio/tree/master/RAKWireless-WisBlock) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2021-05-22

#### Developer Best Practices

NOTE: These best practices are written targeting non Helium LoRa network providers. Not all of these suggestions necessarily apply to the Helium network but they area probably worth noting. (disclaimer: In no particular order, with no particular recommendation, not all are fully vetted)

* [SemTech: Things to Know](https://lora-developers.semtech.com/library/tech-papers-and-guides/the-book)
* [Best Practices: The Things Industries](https://www.thethingsindustries.com/docs/devices/best-practices)
* [The Things Network: Best practices for device development](https://www.thethingsnetwork.org/docs/devices/bestpractices.html)
* [The Things Network: Best practices to limit application payloads](https://www.thethingsnetwork.org/forum/t/best-practices-to-limit-application-payloads/1302)
* [3 best practices for long LoRaWAN battery life: video](https://www.youtube.com/watch?v=3d8lBmkzgfo)

### Explorers/Analytics/Hotspot Analysis/Monitoring

* [WioHeliumMonitor](https://github.com/disk91/WioHeliumMonitor) ⭐ 8 | 🐛 0 | 🌐 C++ | 📅 2022-05-15 - Monitor your network and your hotspot with a hardware device based on WioTerminal
* [Mock sensor code to send lorawan otta join](https://github.com/gradoj/sensor) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2020-09-25
* [Helium Explorer](https://explorer.helium.com) Open-source helium explorer
* [Hotspotty](https://hotspotty.net) - Hotspotty your all-in-one tool for building the Helium network
  Understand your hotspot data, plan and manage your hotspots and payouts, collaborate with the community and your team, optimize network performance and HNT earnings.
* [HNTScan](https://hntscan.io) - Snappy helium block explorer
* [Helium Coverage Mapping](https://mappers.helium.com)
* [Cargo Live Mapper](https://cargo.helium.com/)
* [Line of sight measurement](https://www.scadacore.com/tools/rf-path/rf-line-of-sight/)
* [Helium Chain Variables](https://helium.plus/chain-vars)
* [LoRa documentation](https://lora.readthedocs.io/en/latest/)
* [HotspotRF](https://hotspotrf.com) - Improve and optimize Helium hotspot placement using Radio Frequency (RF) modeling.
* [Cloud-RF](https://cloudrf.com/) - RF coverage modeling and mapping utility
* [Patrium](https://patrium.app/) - Another hotspot management platform
* [Helium+](https://helium.plus/) Helium hotspot earnings calculator
* [Nebra Region Tool](https://region.nebra.com/) - Check the LoRa frequency of a region
* [Heliumbot.io](https://heliumbot.io) - Managed hotspot monitoring and profit calculation service providing push notifications
* [Watchium](https://watchium.disk91.com) - Monitor hotspots failure and anormal states
* [Sitebot](https://sitebot.com/helium) - Helium network explorer **discontinued**
* [Mylar](https://mylar.app) - Great helium analytics **discontinued**
* [Helium.place](https://helium.place/) - Hotspot placement visualization tool **discontinued**

### Dashboards

* [Datacake.co](https://datacake.co/) Enterprise IoT platform
* Cayenne
* [Adafruit.io](https://learn.adafruit.com/welcome-to-adafruit-io) - Adafruit.io is a cloud service - that just means we run it for you and you don't have to manage it. You can connect to it over the Internet. It's meant primarily for storing and then retrieving data but it can do a lot more than just that!
* [Ubidots](https://ubidots.com/) - [blog post](https://ubidots.com/blog/helium-and-ubidots-announce-a-next-level-plug-n-play-partnership-simple-customizable-and-scalable/) - Dashboard for IoT projects.
* Thingsboard
* [Node Red](https://nodered.org/)
* [Tago.io](https://admin.tago.io) - Up to 5 dashboards for free, really easy to integrate and build with Helium

### Home Automation

* [Helium for Home Assistant](https://github.com/rsnodgrass/hass-helium) ⭐ 39 | 🐛 2 | 🌐 Python | 📅 2023-04-11

### Mobile Apps

* [Unofficial Hotspot Utility](https://github.com/kent-williams/hotspot-utility) ⚠️ Archived - Unofficial Android/iPhone Hotspot Utility

### DIY Hotspots

Build tutorials

* [maco2035/DiyHeliumHotspots](https://github.com/maco2035/DiyHeliumHotspots) ⭐ 100 | 🐛 7 | 📅 2021-08-11 - Collection of guides for setting up various builds

* [just4give/helium-dyi-hotspot-balena-pi4](https://github.com/just4give/helium-dyi-hotspot-balena-pi4) ⭐ 86 | 🐛 10 | 🌐 C | 📅 2024-01-11 - "Build your own helium hotspot ( miner + packet forwader ) on Raspberry pi 4 using BalenaOS"

* [DIY Hotspot auto update automation scripts](https://github.com/Wheaties466/helium_miner_scripts) ⭐ 46 | 🐛 0 | 🌐 Shell | 📅 2021-09-28 - Wheaties466/helium\_miner\_scripts, automation for setting up DIY hotspots. All things DIY.

* [meshferg/lorawan-helium-diy-gateway\_miner](https://github.com/meshferg/lorawan-helium-diy-gateway_miner) ⭐ 23 | 🐛 2 | 📅 2020-10-22 - RAK2245 & rPi4 gateway miner collecting wetlands data

* [bottxrnife/helium-2287](https://github.com/bottxrnife/helium-2287) ⭐ 15 | 🐛 3 | 🌐 Rust | 📅 2021-06-17 - Above but for RAK2287-based builds, like the RAK Discover Kit 2 (SX1302-based chip)

* [disk91/helium-gateway-rs-docker](https://github.com/disk91/helium-gateway-rs-docker) ⭐ 12 | 🐛 1 | 🌐 Shell | 📅 2026-06-04 Manage DiY hotspot deployment at scale.

* [23RoMax/h2b](https://github.com/23RoMax/h2b) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2020-05-31 - Helium DIY Hotspot Bootstrapping script with a few utilities

* [jamiew/helium-diy-hotspot](https://github.com/jamiew/helium-diy-hotspot) ⚠️ Archived - Collection of shell scripts for setting up, updating, and monitoring a DIY hotspot

* [bottxrnife/helium-2245](https://github.com/bottxrnife/helium-2245) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2020-10-01 - Forked from PastaGringo, BelanaCloud + docker-conmpose configuration for RAK2245-based builds, like the RAK Pilot Gateway (SX1301-based chip)

* [dansku/helium-rak833-pisupply](https://github.com/dansku/helium-rak833-pisupply) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2020-09-02 PiSupply LoRa Gateway with the RAK833 for Helium.
  Video tutorials

* [Helium developer docs guide](https://developer.helium.com/hotspot/developer-setup) - Pilot Gateway (sx1301-based)

* [PastaGringo/balenaos-helium-gtw](https://github.com/PastaGringo/balenaos-helium-gtw) - BelanaCloud-based build with docker-compose

* [Setting up a Helium miner on DigitalOcean](https://www.youtube.com/watch?v=rR2Z0vOufLM)

* [Adding a DIY Hotspot to the Helium Blockchain](https://www.youtube.com/watch?v=SzFWSv6UcIE)

### Payload Decoders

* [Helium Decoder Repo](https://github.com/helium/console-decoders) ⭐ 62 | 🐛 19 | 🌐 JavaScript | 📅 2023-12-01
* [Helium Mapper Decoder](https://github.com/arkieguy/RAK4631-Helium-Mapper/tree/main/.vscode/HeliumDecoder) ⭐ 16 | 🐛 0 | 🌐 C++ | 📅 2021-08-11
* [VolleyBoast VoBo GP1](https://github.com/VolleyBoast/Decoder) - Decodes standard payload

## Hardware

### Hotspots

* [DeWi Announcement](https://dewialliance.medium.com/accelerating-network-growth-with-three-new-hotspot-manufacturers-3a14b116faca)
* Helium official hotspot
* [RAK Hotspot Miner](https://www.calchipconnect.com/products/rak-hotspot-miner)
* Nebra Miners [Nebra.com](https://www.nebra.com/collections/helium-hotspot-miners-hnt) | [North America (Parley Labs)](https://shop.parleylabs.com/collections/helium-hotspots)
* Dragino LPS8
* DIY gateway builds
* ...

### Outdoor Enclosures

* RAK Outdoor Enclosure [RAKWireless Shenzhen](https://store.rakwireless.com/products/outdoor-gateway-enclosure?variant=29748845051949), [Parley Labs (RAK VAR - North America)](https://shop.parleylabs.com/collections/accessories/products/outdoor-gateway-enclosure?variant=37786576781491)

### Sensor Guides and Tutorial

* [Browan TBHV110 Quickstart](https://github.com/mikedsp/helium/blob/master/MyDocuments/BrowanTBHV110_HeliumQuickStart-SHARE.pdf) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2024-02-05
* [Browan TBHH100 Quickstart](https://github.com/mikedsp/helium/blob/master/MyDocuments/HowTo_BrowanTBHH100_to_GoogleSheet-SHARE.pdf) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2024-02-05
* [Dragino LT-22222-L- Helium 'Smart-Plug'](https://github.com/ilovespectra/ilovespectra/tree/main/LT-22222-L) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2025-03-08
* [RAK Weather Monitor- US915 Setup](https://github.com/ilovespectra/ilovespectra/tree/main/RAK4631/Weather-Monitor) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2025-03-08
* [KiCAD version of WisBlock-Sensor-RTC-Example](https://github.com/ManuIoT/WisBlock-Sensor-RTC-Example) ⭐ 1 | 🐛 1 | 📅 2020-11-27
* [Connect a RAK7204 to Helium and forward its data to Ubidots](https://www.hackster.io/mariacarlinahernandez/connect-a-rak7204-to-helium-and-forward-its-data-to-ubidots-073793)

### Coverage Mapping

* [WioLoRaWanFieldTester](https://github.com/disk91/WioLoRaWANFieldTester) ⭐ 90 | 🐛 17 | 🌐 C++ | 📅 2024-06-09 - Mapper using the Wio Terminal.
* [CubeCell Helium Coverage Mapper](https://github.com/jas-williams/CubeCell-Helium-Mapper) ⭐ 49 | 🐛 3 | 🌐 C++ | 📅 2022-05-24 - Mapper using the [CubeCell w/ GPS/OLED](https://shop.parleylabs.com/collections/heltec-cubecell/products/cubecell-gps-6502-by-heltec-htcc-ab02s) by jas-williams

### Antennas

* [OG Stock Hotspot Antenna](https://www.mouser.com/datasheet/2/238/ant-916-cw-hwr-1633319.pdf) - (pdf datasheet)
* 3dBi RAK Stock Replacement Antenna - [RAKWireless Shenzhen](https://store.rakwireless.com/collections/accessories/products/3-dbi-lora-antenna?variant=32429030637613), [Parley Labs (RAK VAR - North America)](https://shop.parleylabs.com/collections/accessories/products/3-dbi-lora-antenna)
* RAK 5.8dBi [RAKWireless Shenzhen](https://store.rakwireless.com/products/fiber-glass-antenna), [Parley Labs (RAK VAR - North America)](https://shop.parleylabs.com/products/rak-fiber-glass-lorawan-antenna-us915?variant=37264623468723)
  * [5.8 dBi Base support 3D STL File](https://www.thingiverse.com/thing:4607962)
* RAK 8dBi [RAKWireless Shenzhen](https://store.rakwireless.com/products/fiber-glass-antenna), [Parley Labs (RAK VAR - North America)](https://shop.parleylabs.com/products/rak-fiber-glass-lorawan-antenna-us915?variant=37563940733107)
* Nearson 9dBi
* [ANT-916-MHW-RPS-S](https://linxtechnologies.com/wp/wp-content/uploads/ant-916-mhw-fff-x.pdf) - Indoor antenna - pdf
* ...

### Cables & adapters

* [LMR-400 from USACoax](https://usacoax.com/custom/custom-lmr-400-cable-build.html) - For RAK/Nebra miners to RAK/LorRaWAN antennas use RP-SMA Male to N-Type Female connectors.
* ...

## Exchanges

* [Binance US](https://www.binance.us)
* [Binance](https://www.binance.com/)
* [Bilaxy](https://bilaxy.com/)
* OTC Telegram groups
* [HotBit](hotbit.io/)

## Education

* [LoRaWAN Academy](https://lora-developers.semtech.com/resources/lorawan-academy/) - self-paced on-demand LoRaWAN training course
* [Helium Hub](https://tanny.gitbook.io/tannys-helium-support/) - Helium Knowledgebase / New articles regularly!
* [Disk91.com](https://www.disk91.com/all-about-helium/) - Helium technical blog posts

## Network Operators

Interested in hosting a hotspot? Get in touch with one of these companies:

* [Buildmesh.io](https://www.buildmesh.io/) - 20% of HNT earnings plus $10 donation to STEM non-profit
* [Emrit](https://emrit.io/) – 20% of HNT earnings
* [Flywheel Systems](https://flywheel.systems) – 50% of HNT earnings + referrals. Plus cryptocurrency consulation.
* [IoWe (Internet of We)](https://www.InternetOfWe.net) - 20% Partner referrals. 50% of HNT earnings after referral \[where applicable].
* [Loris.club](https://www.loris.club) - 25% of HNT earnings

## Network Servers

Want to connect your devices to an Helium network server (console)

* [Nova console](https://console.helium.com) - up to 10 devices, 250 Dcs
* [Helium IoT](https://console.helium-iot.eu) - unlimited devices, $0.00005 per DCs

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-14._
