# Leonardo Merza

**Senior Software Engineer** | Raleigh, NC

[![Website](https://img.shields.io/badge/Website-lmerza.com-blue?style=for-the-badge&logo=googlechrome&logoColor=white)](https://lmerza.com)
[![GitHub](https://img.shields.io/badge/GitHub-ljmerza-181717?style=for-the-badge&logo=github)](https://github.com/ljmerza)
[![Email](https://img.shields.io/badge/Email-ljmerza%40gmail.com-red?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ljmerza@gmail.com)
[![Followers](https://img.shields.io/github/followers/ljmerza?style=for-the-badge&label=Followers&color=orange)](https://github.com/ljmerza?tab=followers)

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://www.buymeacoffee.com/JMISm06AD)

## About Me

Backend engineer with 10+ years building distributed, asynchronous systems, mostly in Python with some Go and Java. I work on the server side: event pipelines, task queues, cache layers, and the concurrency and backpressure controls that keep them correct under load.

Right now I build B2B backend services for a network of RF sensors that produces 100k+ events a day, running on ECS and EKS with Terraform on AWS. Day to day that means asyncio and FastAPI services, Celery workers on SQS with retry and dead-letter queues, Kafka consumers, Redis/Valkey and Memcached for caching, DynamoDB for high-write access patterns, and Elasticsearch/OpenSearch for search and event indexing at that volume.

I spent a good chunk of those years in React and TypeScript, so I can own a feature end to end. The problems I go looking for are the distributed ones, though. Outside of work I write Home Assistant integrations and cards and run a self-hosted home lab.

## Tech Stack

```
Languages           │ Python, Go, TypeScript, Java, SQL
Distributed & Async │ asyncio, Celery, AWS SQS, Kafka
Caching & Search    │ Redis/Valkey, Memcached, Elasticsearch/OpenSearch
Data Stores         │ PostgreSQL, MySQL, DynamoDB, InfluxDB
Services & APIs     │ FastAPI, Django, Flask, NestJS, OpenAPI/Swagger
Infrastructure      │ Docker, AWS ECS & EKS, Terraform, GitHub Actions, Prometheus
Testing             │ Pytest, Playwright, Jest, React Testing Library
Frontend            │ React, Redux, TypeScript, Angular, Tailwind, Storybook
```

## Featured Projects

### [Home Assistant](https://www.home-assistant.io/) Ecosystem

| Project | Description | Stars |
|---------|-------------|-------|
| [ac-infinity-airtap-ble](https://github.com/ljmerza/ac-infinity-airtap-ble) | Local BLE control of AC Infinity AirTap register vents from Home Assistant. Sets fan speed and temperature without the vendor cloud | ![Stars](https://img.shields.io/github/stars/ljmerza/ac-infinity-airtap-ble?style=flat-square) |
| [calendar-card](https://github.com/ljmerza/calendar-card) | Google Calendar card for Lovelace UI (archived) | ![Stars](https://img.shields.io/github/stars/ljmerza/calendar-card?style=flat-square) |
| [fitbit-card](https://github.com/ljmerza/fitbit-card) | Fitbit health metrics dashboard card | ![Stars](https://img.shields.io/github/stars/ljmerza/fitbit-card?style=flat-square) |
| [FrigateClassifier](https://github.com/ljmerza/FrigateClassifier) | Dog breed and bird species classification for Frigate detections | ![Stars](https://img.shields.io/github/stars/ljmerza/FrigateClassifier?style=flat-square) |
| [ha-our-groceries](https://github.com/ljmerza/ha-our-groceries) | Our Groceries shopping list integration (archived) | ![Stars](https://img.shields.io/github/stars/ljmerza/ha-our-groceries?style=flat-square) |
| [harmony-remote-card](https://github.com/ljmerza/harmony-remote-card) | Logitech Harmony Hub remote-control card for Lovelace | ![Stars](https://img.shields.io/github/stars/ljmerza/harmony-remote-card?style=flat-square) |
| [irrigation_manager](https://github.com/ljmerza/irrigation_manager) | Scheduled watering for valve and switch entities in Home Assistant. Conditions on rain, forecast, temperature, wind, moisture and occupancy, plus a sidebar panel | ![Stars](https://img.shields.io/github/stars/ljmerza/irrigation_manager?style=flat-square) |
| [light-entity-card](https://github.com/ljmerza/light-entity-card) | Card for controlling any light or switch entity | ![Stars](https://img.shields.io/github/stars/ljmerza/light-entity-card?style=flat-square) |
| [orbit-bhyve-ble](https://github.com/ljmerza/orbit-bhyve-ble) | Local BLE control of Orbit B-Hyve sprinkler timers from Home Assistant. Works without the cloud after setup | ![Stars](https://img.shields.io/github/stars/ljmerza/orbit-bhyve-ble?style=flat-square) |
| [soil-temp](https://github.com/ljmerza/soil-temp) | HACS integration exposing soil temperature and moisture sensors via ClearAPI | ![Stars](https://img.shields.io/github/stars/ljmerza/soil-temp?style=flat-square) |
| [tracking-number-card](https://github.com/ljmerza/tracking-number-card) | Display package tracking information | ![Stars](https://img.shields.io/github/stars/ljmerza/tracking-number-card?style=flat-square) |
| [tracking-numbers](https://github.com/ljmerza/tracking-numbers) | Home Assistant integration that pulls tracking numbers from 40+ shipping providers | ![Stars](https://img.shields.io/github/stars/ljmerza/tracking-numbers?style=flat-square) |
| [utilities_email_tracker](https://github.com/ljmerza/utilities_email_tracker) | Polls IMAP and parses utility-bill emails into a Home Assistant sensor | ![Stars](https://img.shields.io/github/stars/ljmerza/utilities_email_tracker?style=flat-square) |
| [utilities_email_tracker_card](https://github.com/ljmerza/utilities_email_tracker_card) | Lovelace card for displaying parsed utility-bill emails | ![Stars](https://img.shields.io/github/stars/ljmerza/utilities_email_tracker_card?style=flat-square) |

### Open Source Projects I Maintain

| Project | Description | Language |
|---------|-------------|----------|
| [billy-bass](https://github.com/ljmerza/billy-bass) | Sound-reactive Big Mouth Billy Bass on an Arduino Uno and Adafruit Motor Shield v2. A microphone module drives the mouth, head, and tail | C++ |
| [checkpoint-pihole](https://github.com/checkpoint-pihole/checkpoint-pihole) | Web application for backing up Pi-hole v6 instances via the Teleporter API | Python |
| [cradlewise-rtsp-bridge](https://github.com/ljmerza/cradlewise-rtsp-bridge) | Turns every Cradlewise Smart Crib on an account into a local RTSP stream for Frigate, Blue Iris, Scrypted, or any other NVR. Holds one WebRTC subscriber per crib and feeds it into mediamtx | Python |
| [FlowHistory](https://github.com/FlowHistory/FlowHistory) | Backup and restore tool for Node-RED flow files, with scheduled backups, visual diffs, multi-instance support, and notifications | Python |
| [frigate_plate_recognizer](https://github.com/ljmerza/frigate_plate_recognizer) | License plate recognition integration for Frigate NVR | Python |
| [latchpoint](https://github.com/latchpoint/latchpoint) | Self-hosted alarm system that integrates with Home Assistant, MQTT, Z-Wave JS, and Frigate. Includes a rules engine for automated responses and live status updates | Python |
| [nodered-mcp](https://github.com/ljmerza/nodered-mcp) | MCP server for reading, querying, and editing a Node-RED flows.json. Canvas aware, with a layout gate that refuses edits that would collide with existing nodes or groups | Python |
| [unifi_firmware](https://github.com/ljmerza/unifi_firmware) | Weekly scraper and web UI for UniFi firmware releases. Reads the download JSON backend directly, groups releases by device, and stores everything in SQLite | Python |
| [wifi-shepard](https://github.com/ljmerza/wifi-shepard) | Docker daemon that watches a wireless network and re-roams misbehaving 2.4 GHz IoT clients across APs through a brand-agnostic controller interface, UniFi first | Python |

### DevOps & Infrastructure

| Project | Description |
|---------|-------------|
| [rsync-exporter](https://github.com/ljmerza/rsync-exporter) | Export rsync statistics to Prometheus |
| [snapraid-collector](https://github.com/ljmerza/snapraid-collector) | Prometheus metrics exporter for SnapRAID |

## Open Source Contributions

Most of my open source work is in the Home Assistant ecosystem. That includes integrations for third-party services, Lovelace cards for dashboards, and a few tools around Frigate NVR for license plate recognition and object classification.


## Experience

- **Senior Software Engineer** @ Epiq Solutions *(2022 - 2024)*
  - Full-stack development with React, TypeScript, Python, and Go
  - Kubernetes cluster management and AWS infrastructure with Terraform
  - Led JavaScript to TypeScript migration and modernized build tooling

- **Senior Software Engineer** @ Vaco *(2019 - 2022)*
  - Built donation platform processing $1B+ annually
  - Implemented canary release management and E2E testing with Playwright

- **Software Engineer** @ AT&T *(2016 - 2019)*
  - Led application modernization from legacy stack to React and Python
  - Built developer productivity tools integrating Jira and Bitbucket APIs

## Education

**B.S. Electrical Engineering** - University of South Carolina
