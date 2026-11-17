Welcome to FreeTAKTeam, we are a group of developers passionate about democratizing situational awareness.

FreeTAKTeam manages the following repositories:

## **R3AKT**
[Reticulum Resilient Response Tactical Kit](https://freetakteam.github.io/R3AKT/)
- **LXMF-rs** — Rust porting  of Reticulum + LXMF messaging , the shared stack that REM and YARA ship with.
- **Reticulum Community Hub (RCH)** — Community-owned hub for messaging, shared map, missions, checklists and files over Reticulum/LXMF.
- **Reticulum Emergency Management (REM)** — Android field app for team status, chat, checklists and map positions over Reticulum mesh, with optional RCH support.
- **YARA** — Yet Another Reticulum Application: a fast, lightweight LXMF chat client built on the Rust Reticulum stack.
- **R3AKT UAS** — Android DJI flying app feeding aircraft telemetry, markers and video into RCH/REM (specification and scaffold stage).
- **TRex plugin for REM** — Tactical REM plugin (rem-tactical-trex2) that adds a radar view of nearby team members and markers.
- **ATN Rangefinder** — Rust core and Android REM plugin that links ATN rangefinders and binoculars to the REM map over Bluetooth.

## TAK Situational Awareness
- FreeTakServer: Situational Awareness Server compatible with TAK clients
- UI: FreeTAKServer Web User Interface project
- FreeTAKHub-Installation: this repository contains the Ansible code that is used by the ZeroTouch installer
-  FreeTAKServer-User-Docs: FreeTAKServer documentation for end users
-  FreeTAKTest: this repository contains data and utilities to test TAK servers and clients
-  FreeTAKMumla_Plugin: A project that host a ATAK plugin that display a PPT button for Mumla Android
-  FreeTAKUAS: DJI drone flying app with integrations for FreeTAKServer
-  openTAKpickList: collection of useful TAK links


  ## FreeTAKHub
  repositories with integration between FTS and other systems
  - FreeTAKHub_meshtastic: integration between FreeTAKServer and Meshtastic using MQTT and Node red
  - FreeTAKHub-Webmap: a webmap that can show and create messages for FreeTAKServer
  - FreeTAKHub_Forms_SALUTE: Create a Salute report in FreeTAK Server
  - FreeTAKHub_VideoChecker: integrates the Media server with TAK server and connected clients
  - FreeTAK_Hub_Telegram: Connects telegram to FTS
  - FreeTAKHUB_UkraineMap: A live map of the Russian position in Ukraine
  - FreeTAKHUB-GlobalEmergencies: connects to a EMS global alerts, transforms into COT and pushes to FTS


## Digital Engineering
repositories that support DE, not all are public, ask the team for access
  - DigitalArchitectureFramework: The Digital Architecture Framework (DAF), is a set modeling tools for Digital Engineering.
  - DAF_DP_Component_Generator: Digitalpy Component Generator from DAF model.
  - DAF_OAS_Generator: Generator to generate OAS files from a DAF model
  -  DAF_DP_UI_Generator: Digitalpy Component Generator from OAS API specification
  -  LSO_API_Importer: This Repository enables the imports of MEF LSO API's
  -  OAS3_JSON_Parser: This repository is responsible for parsing OAS3 JSON specifications using XText
  -  DAF_relationshipManager: manages set of relationships using AI 
  -  DigitalPy: A framework to support digital engineering in the python language
  -  DigitalPyHelloWorld: a minimal application running DigitalPy
  -  Nest.JS OpenAPI Generator: a nest JS generator that support AI
