# Industrial Automation

Repos and projects focused on PLCs, SCADA, and control systems.

Labels: 🟩 [OSS] open-source licence, 🟥 [No licence] no licence, 🟧 [Maintained?] no push in ~12 months, 🟦 [Popular] >1,000 stars or >500 forks.

## VS Code extensions

- [ControlForge Structured Text](https://github.com/ControlForge-Systems/controlforge-structured-text) — VS Code Structured Text IDE with LSP, diagnostics, refactors, formatting, and strong IEC 61131-3 tooling; the most full‑stack ST extension here. 🟩 [OSS]
- [vscode-st](https://github.com/Serhioromano/vscode-st) — Broad Structured Text support for VS Code with syntax highlighting, snippets, outline, and a beta formatter; one of the most complete ST extensions. 🟩 [OSS]

## Soft PLCs and runtimes

- [IronPLC](https://github.com/ironplc/ironplc) — Rust SoftPLC project focused on an IEC 61131-3 parser, semantic analyser, and VS Code extension; runtime execution is still the missing piece. 🟩 [OSS]
- [Gipop](https://github.com/andergisomon/Gipop) — Rust SoftPLC with Modbus and OPC UA modules plus EtherCAT via Ethercrab; early-stage, but a concrete protocol-first build. 🟩 [OSS]
- [OpenPLC Runtime v4](https://github.com/Autonomy-Logic/openplc-runtime) — MIT headless PLC runtime with a C/C++ core and Flask API; compiles uploaded IEC 61131-3 programs, runs deterministic scans, and exposes WebSocket debugging plus a plugin system, but only makes sense paired with the OpenPLC Editor. 🟩 [OSS]
- [OpenPLC Runtime v3](https://github.com/thiagoralves/OpenPLC_v3) — GPL runtime for OpenPLC with an install script, webserver UI, and optional EtherCAT support; widely used in research and training, but still a hands-on build. 🟩 [OSS]🟦 [Popular]

## PLC frameworks and developer tooling

- [AXOpen](https://github.com/Inxton/AXOpen) — Industrial automation framework built on SIMATIC AX and AX#, bridging PLC runtime with .NET twins, OOP components, and HMI tooling. 🟩 [OSS]
- [AxSharp](https://github.com/Inxton/axsharp) — Active AX# toolchain that compiles SIMATIC AX PLC data into .NET “twins” and UI scaffolding; powerful but gated by SIMATIC AX licensing and still in pre‑1.0 churn. 🟩 [OSS]
- [Beremiz](https://github.com/beremiz/beremiz) — Free software IEC 61131‑3 IDE + runtime with CLI, HMI tooling, and multiple runtimes (Python/C); heavy but genuinely open and vendor‑neutral. 🟩 [OSS]
- [OpenPLC Editor v4](https://github.com/Autonomy-Logic/openplc-editor) — GPL Electron/TypeScript IDE for IEC 61131-3 with a fast release cadence and built‑in build pipeline; great if on OpenPLC Runtime, heavier if not. 🟩 [OSS]
- [OpenPLC Editor (classic)](https://github.com/thiagoralves/OpenPLC_Editor) — GPL IDE built on Beremiz and MatIEC, updated for Python 3 and wxPython; the legacy OpenPLC editor that still matters for v3 stacks. 🟩 [OSS]
- [4diac IDE](https://github.com/eclipse-4diac/4diac-ide) — Eclipse IDE for IEC 61499 distributed automation, actively maintained and good for IPMCS workflows; a different mental model than classic IEC 61131-3. 🟩 [OSS]
- [TwinCatChangelog](https://github.com/Roald87/TwinCatChangelog) — MIT community‑maintained TwinCAT changelog site, filling the gap left by missing official release notes; high value for upgrade planning and regression tracking. 🟩 [OSS]
- [Twinpack](https://github.com/zeugwerk/twinpack) — GPL TwinCAT package manager with IDE integration and multiple package sources (Twinpack server, NuGet, Beckhoff repo); great idea, but depends on a new ecosystem. 🟩 [OSS]
- [Acceleer CLI](https://github.com/acceleer/acceleer-cli) — Windows‑only CLI for Acceleer blueprints (Linux “later”), with almost no docs; only useful if already on their stack. 🟥 [No licence]
- [Reflect](https://github.com/Joshpolansky/reflect) — MIT C++20 JSON reflection library built on Boost.PFR and nlohmann/json; convenient for schemas and tooling, but heavy deps and still early. 🟩 [OSS]
- [x-tools](https://github.com/x-tools-author/x-tools) — LGPL Qt toolbox for serial/HID/BLE/UDP/TCP/WebSocket/Modbus/CAN/MQTT, with Lua/JS scripting and charts; busy UI but a Swiss‑army debug kit. 🟩 [OSS]🟦 [Popular]
- [truST Platform](https://github.com/johannesPettersson80/trust-platform) — Rust‑heavy IEC 61131-3 toolchain with LSP, runtime, and debugger plus VS Code/Neovim/Zed setup; ambitious full‑stack ST platform, not a light plugin. 🟩 [OSS]
- [TIA Portal Openness Code Snippets](https://github.com/siemens/tia-portal-openness-code-snippets) — Siemens-authored examples for the TIA Portal Openness API (V20), showing how to automate engineering workflows and project manipulation. 🟩 [OSS]

## Analysis and verification

- [blark](https://github.com/klauer/blark) — GPL‑2.0 Python parser for TwinCAT ST and project files using Lark; powerful for AST/refactor workflows but the grammar is explicitly imperfect. 🟩 [OSS]
- [IEC Checker](https://github.com/jubnzv/iec-checker) — LGPL static analyser for IEC 61131-3 ST/PLCopen XML with PLCopen guideline rules and JSON IR export; development is paused, so treat it as stable‑ish tooling. 🟩 [OSS]

## CODESYS tooling

- [CodesysV3Driver](https://github.com/lircy/CodesysV3Driver) — LGPL .NET 4 driver that speaks the proprietary CODESYS V3 protocol (PLCHandler‑like), with symbol list download and batch reads; dev/test only and not production‑ready. 🟩 [OSS]

## OPC UA

- [open62541](https://github.com/open62541/open62541) — C OPC UA stack with client/server, plugin‑based portability, and a single‑file amalgamation option; MPL‑2.0 is easy to ship, and it’s the de‑facto open baseline. 🟩 [OSS]🟦 [Popular]
- [node-opcua](https://github.com/node-opcua/node-opcua) — Full OPC UA stack in Node.js/TypeScript with client, server, and browser support; fast to prototype, but depends on a heavy JS toolchain and paid support for enterprise features. 🟩 [OSS]🟦 [Popular]
- [Eclipse Milo](https://github.com/eclipse-milo/milo) — Java OPC UA stack and SDK (targeting spec 1.05) with high‑performance core and client/server layers; rock‑solid, but Java 17+ is a hard requirement. 🟩 [OSS]🟦 [Popular]
- [opcilloscope](https://github.com/SquareWaveSystems/opcilloscope) — C#/.NET terminal‑first OPC UA client for browse/subscribe, live trend/scope views, and CSV capture; fast to install and great for commissioning and diagnostics. 🟩 [OSS]

## EtherCAT

- [SOEM](https://github.com/OpenEtherCATsociety/SOEM) — RT‑Labs‑backed C EtherCAT master library aimed at real‑time embedded use; lightweight and widely used, but still a low‑level API. 🟩 [OSS]🟦 [Popular]
- [SOES](https://github.com/OpenEtherCATsociety/SOES) — Compact C EtherCAT slave stack focused on learning and embedded use, with CoE, PDO mapping, FoE template, and DC sync; docs are thin and last release is 2021. 🟩 [OSS]
- [ethercrab](https://github.com/ethercrab-rs/ethercrab) — Pure Rust async‑first EtherCAT MainDevice with std and no_std support, plus distributed clocks and SDO tooling; modern and safe, but still evolving. 🟩 [OSS]
- [KickCAT](https://github.com/leducp/KickCAT) — Active C++ EtherCAT master/slave stack with CoE SDO support, redundancy, Python bindings, and a built‑in simulator; licence is CeCILL‑C, so check compatibility. 🟩 [OSS]

## Modbus

- [libmodbus](https://github.com/stephane/libmodbus) — LGPL C library for Modbus RTU/TCP across Linux, macOS, Windows, and embedded targets; the canonical baseline, but the API feels old‑school compared to newer stacks. 🟩 [OSS]🟦 [Popular]
- [digitalpetri/modbus](https://github.com/digitalpetri/modbus) — Modern Java 17+ Modbus client/server stack with TCP, RTU on serial, RTU on TCP, and Modbus TCP Security; strong API, but needs a JVM and Maven‑style tooling. 🟩 [OSS]
- [nanoMODBUS](https://github.com/debevv/nanoMODBUS) — Compact C Modbus RTU/TCP library for embedded targets: ~2k LOC, no dynamic allocation, optional client/server, and easy porting with user‑supplied transport hooks. 🟩 [OSS]
- [modbus-go](https://github.com/adibhanna/modbus-go) — Go Modbus stack that goes beyond the basics: all 19 function codes, TCP/TLS/UDP/RTU/ASCII, client+server, JSON config profiles, and solid test coverage; ambitious but early‑stage. 🟩 [OSS]
- [pymodbus](https://github.com/pymodbus-dev/pymodbus) — Full Python Modbus stack with client, server, and web‑based simulator, plus sync/async APIs and strong test coverage; the default choice but API changes can be sharp between major versions. 🟩 [OSS]🟦 [Popular]
- [Modbux](https://github.com/ploxc/modbux) — Electron + React Modbus client/server simulator built from commissioning pain; rich datatype decoding, scan tools, split client/server mode, and an opinionated UX that makes Modbus less miserable. 🟩 [OSS]

## EtherNet/IP and CIP

- [pylogix](https://github.com/dmroeder/pylogix) — Python driver for Rockwell ControlLogix/CompactLogix/Micro8xx over EtherNet/IP, focused on easy tag read/write; explicitly not for PLC‑5/SLC/MicroLogix. 🟩 [OSS]
- [pycomm3](https://github.com/ottowayi/pycomm3) — Python 3 Ethernet/IP library for Allen‑Bradley PLCs with CIP, Logix, and legacy drivers; explicitly not actively developed, but still a solid reference for quick tag access. 🟩 [OSS]
- [libplctag](https://github.com/libplctag/libplctag) — Dual‑licensed (MPL 2.0 / LGPL 2+) C library for EtherNet/IP and Modbus TCP tag access; stable API since 2012 and widely wrapped in .NET, Go, Java, and more. 🟩 [OSS]

## PROFINET

- [p-net](https://github.com/rtlabs-com/p-net) — RT‑Labs PROFINET device stack in C; this repo is an evaluation build only, with full source and ports behind a commercial licence. 🟥 [No licence]

## CAN

- [can-utils](https://github.com/linux-can/can-utils) — Linux SocketCAN user‑space toolkit with candump/cansend/cangen, ISO‑TP and J1939 utilities, and log converters; the standard CAN debug suite. 🟩 [OSS]🟦 [Popular]

## ADS (TwinCAT)

- [ads-client](https://github.com/jisotalo/ads-client) — Unofficial Node.js ADS client for Beckhoff TwinCAT 2/3; v2 was a TypeScript rewrite with subscriptions, RPC calls, and automatic PLC↔JS type conversion. 🟩 [OSS]

## PLC access stacks

- [PLC4X](https://github.com/apache/plc4x) — Apache Industrial IoT adapter that provides unified PLC protocol access across Java, Go, C, and Python, plus tooling like OPC UA and PLC4X servers for bridging legacy devices; broad coverage but protocol maturity is uneven. 🟩 [OSS]🟦 [Popular]

## MQTT

- [VerneMQ](https://github.com/vernemq/vernemq) — Erlang/OTP distributed MQTT broker built for reliability, clustering, and industrial workloads, with strong auth and plugin support. 🟩 [OSS]🟦 [Popular]
- [Mosquitto](https://github.com/eclipse-mosquitto/mosquitto) — Eclipse MQTT broker with C/C++ client libs and CLI tools (mosquitto_pub/sub), the default workhorse for lightweight MQTT deployments. 🟩 [OSS]🟦 [Popular]
- [mqtt-sim](https://github.com/marcelo-6/mqtt-sim) — Python MQTT simulator for generating configurable payload streams and device patterns, with JSON configs, CLI, and Docker Compose for quick broker testing. 🟩 [OSS]

## Multi-protocol clients

- [TouchSocket](https://github.com/RRQM/TouchSocket) — Chinese‑first Apache‑2.0 .NET networking framework with TCP/UDP/SSL, WebSocket, RPC, Modbus, and MQTT modules; designed for high‑performance protocol handling and gateway adapters. 🟩 [OSS]🟦 [Popular]
- [HslCommunication](https://github.com/dathlin/HslCommunication) — Chinese‑first C# industrial comms library with wide PLC vendor support plus Redis/MQTT/WebSocket bridges; public repo but source is not open‑source and commercial licensing is required. 🟥 [No licence]

## Siemens S7

- [python-snap7](https://github.com/gijzelaerr/python-snap7) — Python wrapper for Snap7 that exposes Siemens S7 PLC Ethernet access via a clean, cross‑platform API and prebuilt wheels; the go‑to choice for Python‑based S7 integration. 🟩 [OSS]
- [snap7-gui](https://github.com/Autonomy-Logic/snap7-gui) — Python/PySide6 desktop GUI for S7Comm with live tag monitoring and quick read/write; small tool but handy for field checks. 🟩 [OSS]
- [SIMATIC S7 Webserver API (.NET)](https://github.com/siemens/simatic-s7-webserver-api) — Siemens official .NET client for the SIMATIC S7 PLC Webserver API, useful for diagnostics and data access over HTTP. 🟩 [OSS]
- [SIMATIC S7 Webserver API (TypeScript)](https://github.com/siemens/typescript-simatic-s7-webserver-api) — Siemens TypeScript client bindings for the SIMATIC S7 Webserver API. 🟩 [OSS]

## SCADA and HMI

- [FUXA](https://github.com/frangoteam/FUXA) — Web-based SCADA/HMI with a full browser editor, multi‑protocol connectivity (Modbus, S7, OPC UA, BACnet, MQTT, EtherNet/IP), and a Node + Angular stack; strong community and rapid releases. 🟩 [OSS]🟦 [Popular]
- [scada.js](https://github.com/aktos-io/scada.js) — JavaScript framework for distributed, real‑time SCADA and MRP/ERP apps across web, desktop (Electron), and mobile, with microservices support and broad driver coverage. 🟥 [No licence]

## Data collection and observability

- [Telegraf](https://github.com/influxdata/telegraf) — InfluxData’s MIT-licensed agent with 300+ plugins for collecting, processing, and forwarding metrics, logs, and industrial protocol data (OPC UA, Modbus, MQTT), widely deployed at the edge. 🟩 [OSS]🟦 [Popular]
- [EdgeShark](https://github.com/siemens/edgeshark) — Siemens tooling to discover and live‑capture container network traffic from desktop Wireshark via a containerised service and extcap plugin; strong fit for debugging industrial edge stacks. 🟩 [OSS]🟦 [Popular]

## Simulation, digital twin, and CAD

- [ProcessSimulatePlugin](https://github.com/deusXmachina-dev/ProcessSimulatePlugin) — GPL-3.0 Siemens Process Simulate plugin that prototypes energy‑optimisation heuristics for robot cells, built as a lightweight proof‑of‑concept by a two‑person team. 🟩 [OSS]
- [PartCAD](https://github.com/partcad/partcad) — “Package manager for hardware” focused on digital-thread documentation and manufacturability, with a CLI and VS Code extension; not a drawing CAD tool, but a system for versioned product specs, BOMs, and outputs. 🟩 [OSS]

## OT security labs

- [GRFICSv3](https://github.com/Fortiphyd/GRFICSv3) — Fully containerised OT/ICS cyber-physical lab simulating a chemical plant with PLCs, HMI, realistic networking, and a 3D process visualisation for hands‑on security training. 🟩 [OSS]

## Testing and quality

- [TcUnit](https://github.com/tcunit/TcUnit) — xUnit-style test framework for Beckhoff TwinCAT 3, with a verifier tool, docs site, examples, and regular releases. 🟩 [OSS]

## Robotics and integration

- [ethercat_driver_ros2](https://github.com/ICube-Robotics/ethercat_driver_ros2) — ROS 2 driver that plugs EtherCAT fieldbus devices into the ros2_control hardware interface layer for robot control. 🟩 [OSS]

## Edge and platform stacks

- [ThingsGateway](https://github.com/ThingsGateway/ThingsGateway) — Chinese-first, active .NET 8 IIoT edge gateway with plugin-based drivers, edge processing, protocol conversion, and web UI; supports Modbus, OPC, MQTT, S7 and offers paid PRO protocol packs. 🟩 [OSS]🟦 [Popular]
- [IoTGateway](https://github.com/iioter/iotgateway) — Chinese-first .NET 8 gateway with a web UI, rich southbound drivers (PLC, OPC UA/DA, CNC, serial), and northbound connectors to clouds like ThingsBoard and Huawei; active, with enterprise docs and paid edition. 🟩 [OSS]🟦 [Popular]
- [SagooIOT](https://github.com/sagoo-cloud/sagooiot) — Chinese-first Go-based enterprise IoT platform with multi-protocol access (MQTT, CoAP, HTTP, OPC UA, Modbus), plugin architecture, and a full web UI stack; GPL-3.0 with commercial licensing for proprietary use. 🟩 [OSS]🟦 [Popular]
- [DGIOT](https://github.com/dgiot/dgiot) — China-based, very active industrial IoT platform with device access, protocol adapters, object models, rule engine, and low-code configuration pages; Erlang-heavy core aiming at high device counts and carrier-grade stability. 🟩 [OSS]🟦 [Popular]
- [orchestrator-agent](https://github.com/Autonomy-Logic/orchestrator-agent) — Python edge daemon that mTLS‑connects to Autonomy Edge Cloud and orchestrates OpenPLC v4 containers with MACVLAN networking; useful if running their cloud, irrelevant otherwise. 🟩 [OSS]
- [SIMATIC IOT2050 BSP](https://github.com/siemens/meta-iot2050) — Siemens Debian/Isar board support package for SIMATIC IOT2050 edge devices. 🟩 [OSS]

## UI and design systems

- [Siemens Industrial Experience (ix)](https://github.com/siemens/ix) — Siemens MIT‑licensed design system and Web Components library for industrial software UIs, with React, Angular, and Vue bindings plus design guidelines. 🟩 [OSS]

## Archive

Cut-off: last push before 2025-02-27.

- [OpenPLC v2](https://github.com/thiagoralves/OpenPLC_v2) — GPL virtual PLC with ST to C compilation and a Node.js web UI for program uploads; older, but still clear and hackable. 🟩 [OSS] 🟧 [Maintained?]
- [OpenPLC (legacy)](https://github.com/thiagoralves/OpenPLC) — Early GPL OpenPLC stack focused on ladder diagrams and Modbus/TCP with a Node.js HTTP server; useful for archaeology and small experiments. 🟩 [OSS] 🟧 [Maintained?]
- [SoftBeckhoff](https://github.com/fbarresi/SoftBeckhoff) — MIT C# “virtual Beckhoff” ADS server with Docker and a REST API; useful for local testing, but still heavy‑dev and not a full PLC. 🟩 [OSS] 🟧 [Maintained?]
- [TcOpen](https://github.com/TcOpenGroup/TcOpen) — MIT TwinCAT 3 + .NET application framework with deep docs, sequencers, data layer, and components; archived in 2025, but still a gold‑standard reference. 🟩 [OSS] 🟧 [Maintained?]
- [PLC2Skill](https://github.com/CaSkade-Automation/PLC2Skill) — Java toolchain that maps PLCopen XML into semantic skill models (OWL) with CLI and REST API; academically grounded and useful for ISA‑88/skill‑based control, but heavy and niche. 🟩 [OSS] 🟧 [Maintained?]
- [ladder_parser](https://github.com/AnthonyMujic/ladder_parser) — Elixir tool that converts 2D ASCII ladder logic into AST and executable expressions; bare‑bones but conceptually interesting for migration and documentation workflows. 🟩 [OSS] 🟧 [Maintained?]
- [OpenPLC Ladder Editor](https://github.com/thiagoralves/OpenPLC-Ladder-Editor) — CC BY-SA ladder editor for OpenPLC and Arduino, bundled as a light fork of LDmicro; simple and dated, but still handy for small demos. 🟩 [OSS] 🟧 [Maintained?]
- [TwinCatAdsTool](https://github.com/fbarresi/TwinCatAdsTool) — MIT TwinCAT ADS utility for backing up and comparing persistent variables, symbol exploration, and a lighter alternative to Visual Studio; last release 2021. 🟩 [OSS] 🟧 [Maintained?]
- [PLCreX](https://github.com/marwern/PLCreX) — GPL‑3.0 Python toolkit for ST/FBD parsing, transformation, and validation with CLI converters (ST↔SCL/SCCharts/Quartz) and model checking hooks; powerful but heavy on dependencies. 🟩 [OSS] 🟧 [Maintained?]
- [OOP Concept Examples in CODESYS V3](https://github.com/Aliazzzz/OOP-Concept-Examples-in-CODESYS-V3) — Unlicense repo with bite‑size CODESYS OOP examples (inheritance, interfaces, polymorphism, pointers); light on docs but easy to skim. 🟩 [OSS] 🟧 [Maintained?]
- [structured-text-utilities](https://github.com/WengerAG/structured-text-utilities) — MIT collection of pure IEC 61131-3 ST utility functions (arrays, strings, time, stats) that deliberately avoids vendor extensions; small but clean. 🟩 [OSS] 🟧 [Maintained?]
- [minimalmodbus](https://github.com/pyhys/minimalmodbus) — Apache‑2.0 Python module for Modbus RTU/ASCII over serial, focused on simplicity with pySerial as the only dependency; a clean, no‑nonsense choice for instrument access. 🟩 [OSS] 🟧 [Maintained?]
- [EasyModbusTCP.NET](https://github.com/rossmann-engineering/EasyModbusTCP.NET) — C#/.NET Modbus TCP/UDP/RTU client/server library with a simple API and extra tools like a server simulator; very popular but last release is 2021. 🟩 [OSS]🟦 [Popular] 🟧 [Maintained?]
- [EEIP.NET](https://github.com/rossmann-engineering/EEIP.NET) — MIT‑licensed C# EtherNet/IP library with explicit/implicit messaging and CIP object support; docs are decent but the API is low‑level and example‑heavy. 🟩 [OSS] 🟧 [Maintained?]
- [EIPScanner](https://github.com/nimbuscontrols/EIPScanner) — MIT‑licensed C++ EtherNet/IP scanner with explicit/implicit messaging, device discovery, and a vendor object catalog; solid but last release is 2021. 🟩 [OSS] 🟧 [Maintained?]
- [openPOWERLINK_V2](https://github.com/OpenAutomationTechnologies/openPOWERLINK_V2) — Open‑source POWERLINK stack (Master and Slave) with dynamic/static PDO mapping and SDO over UDP; BSD‑licensed core with some GPL‑licensed platform parts. 🟩 [OSS] 🟧 [Maintained?]
- [OpenPLC Simulink Interface](https://github.com/thiagoralves/OpenPLC_Simulink-Interface) — Small C++ UDP bridge between OpenPLC and Simulink models using Send/Receive blocks; useful for control co-simulation, not a full integration layer. 🟩 [OSS] 🟧 [Maintained?]
- [EtherSploit/IP](https://github.com/thiagoralves/EtherSploit-IP) — Offensive CLI targeting Rockwell MicroLogix EtherNet/IP weaknesses with start/stop, password read/write, and destructive commands; a sharp-edged research tool. 🟥 [No licence] 🟧 [Maintained?]
- [defcon26](https://github.com/thiagoralves/defcon26) — Code and examples from the DEF CON 26 talk on PLC hacking, including Rockwell and Modbus Unity tester exploits; useful for study and demos. 🟥 [No licence] 🟧 [Maintained?]
- [coUnit](https://github.com/Aliazzzz/coUnit) — CODESYS v3.5 fork of TcUnit; useful for basic TDD workflows, but thin README and points to the upstream CODESYS Forge project. 🟩 [OSS] 🟧 [Maintained?]
- [OpenPLC-Neo](https://github.com/thiagoralves/OpenPLC-Neo) — OpenPLC hardware reference with CPU and digital I/O card designs; cool concept, but no licence and sparse documentation. 🟥 [No licence] 🟧 [Maintained?]
- [SIMATIC S7 Webserver API (Python)](https://github.com/siemens/python-simatic-s7-webserver-api) — Siemens Python client bindings for the SIMATIC S7 Webserver API. 🟩 [OSS] 🟧 [Maintained?]
