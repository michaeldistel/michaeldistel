# Industrial Automation

Repos and projects focused on PLCs, SCADA, and control systems.

Labels: [OSS] open-source licence detected, [No licence] no licence detected, [Archived] archived, [Maintained?] no push in ~18 months.

## VS Code extensions

- [ControlForge Structured Text](https://github.com/ControlForge-Systems/controlforge-structured-text) — VS Code extension for IEC 61131-3 Structured Text, with LSP, diagnostics, formatting, and rich editor tooling for PLC developers. [OSS]
- [vscode-st](https://github.com/Serhioromano/vscode-st) — Broad Structured Text language support for VS Code, with syntax highlighting, snippets, navigation, and formatting aimed at IEC 61131-3 workflows. [OSS]

## Soft PLCs and runtimes

- [IronPLC](https://github.com/ironplc/ironplc) — Prototype Rust-based SoftPLC aiming at IEC 61131-3; today it ships a parser, semantic analyser, and VS Code extension as the foundation for a full runtime. [OSS]
- [Gipop](https://github.com/andergisomon/Gipop) — Rust SoftPLC project with protocol modules and a focus on embedded-grade control logic. [OSS]
- [OpenPLC](https://github.com/thiagoralves/OpenPLC) — Open-source SoftPLC runtime that executes ladder logic and exposes Modbus/TCP, with a simple web UI for uploading programs and a Raspberry Pi hardware layer option. [OSS][Maintained?]
- [OpenPLC Runtime v4](https://github.com/Autonomy-Logic/openplc-runtime) — Headless PLC runtime with a REST API and WebSocket debug interface, designed to run OpenPLC Editor v4 programs with deterministic scan cycles and plugin-based I/O. [OSS]
- [SoftBeckhoff](https://github.com/fbarresi/SoftBeckhoff) — Virtual Beckhoff PLC environment for local TwinCAT testing, with Docker support to simulate runtime without hardware. [OSS][Maintained?]

## PLC frameworks and developer tooling

- [AXOpen](https://github.com/Inxton/AXOpen) — Industrial automation framework built on SIMATIC AX and AX#, bridging PLC runtime with .NET twins, OOP components, and HMI tooling. [OSS]
- [AxSharp](https://github.com/Inxton/axsharp) — AX# toolchain that binds SIMATIC AX projects to the .NET ecosystem via PLC “twin” types and tooling. [OSS]
- [Beremiz](https://github.com/beremiz/beremiz) — Open-source IEC 61131-3 IDE and runtime toolchain that lets you build PLC programs with open standards, ship to multiple targets, and avoid vendor lock-in. [OSS]
- [TcOpen](https://github.com/TcOpenGroup/TcOpen) — TwinCAT 3 and .NET automation application framework with OOP‑first components, data abstractions, and coordinated sequencing, now archived but still a rich reference stack. [OSS][Archived]
- [OpenPLC Editor v4](https://github.com/Autonomy-Logic/openplc-editor) — Cross-platform desktop IDE for IEC 61131-3 languages that compiles and deploys programs to the OpenPLC Runtime v4 stack. [OSS]
- [4diac IDE](https://github.com/eclipse-4diac/4diac-ide) — Eclipse IDE for IEC 61499 distributed automation, useful when you want event‑driven function block systems rather than classic IEC 61131-3 PLC programs. [OSS]
- [PLC2Skill](https://github.com/CaSkade-Automation/PLC2Skill) — Research-grade pipeline that converts PLCopen XML into semantic skill models, enabling machine skills discovery, reasoning, and orchestration via ontologies. [No licence][Maintained?]
- [ladder_parser](https://github.com/AnthonyMujic/ladder_parser) — Converts ASCII ladder diagrams into Elixir AST and code, useful for documentation, simulation, and migration workflows. [No licence][Maintained?]
- [TcBlack](https://github.com/Roald87/TcBlack) — Opinionated formatter for TwinCAT Structured Text, designed to keep PLC code consistent and reviewable across teams. [OSS][Maintained?]
- [TwinCatAdsTool](https://github.com/fbarresi/TwinCatAdsTool) — ADS variable backup, diff, and compare tooling for TwinCAT projects, useful for audits and regression checks. [OSS][Maintained?]
- [TwinCatChangelog](https://github.com/Roald87/TwinCatChangelog) — Unofficial changelog tracker for TwinCAT releases, helpful for upgrade planning and regression triage. [OSS]
- [Twinpack](https://github.com/zeugwerk/twinpack) — Package manager for TwinCAT libraries with IDE integration and CI-friendly distribution. [OSS]
- [Acceleer CLI](https://github.com/acceleer/acceleer-cli) — CLI for Acceleer blueprints and automation workflows, currently Windows-first. [No licence]
- [Reflect](https://github.com/Joshpolansky/reflect) — C++20 JSON reflection library; not PLC-specific but useful for industrial codebases that need schema-aware serialisation. [OSS]
- [x-tools](https://github.com/x-tools-author/x-tools) — Cross-platform Qt debugging toolbox for serial, Modbus, CAN, MQTT, WebSocket, and more, with scripting hooks and charting for lab and field work. [OSS]
- [truST Platform](https://github.com/johannesPettersson80/trust-platform) — Structured Text tooling suite aimed at IEC 61131-3 workflows, including language tooling and developer utilities. [OSS]

## Analysis and verification

- [IEC Checker](https://github.com/jubnzv/iec-checker) — Static analysis tool for IEC 61131-3 Structured Text and PLCopen XML, with rules aligned to PLCopen guidelines and a JSON‑emitting IR for deeper audits. [OSS]
- [PLCreX](https://github.com/marwern/PLCreX) — CLI toolkit for parsing, transforming, and validating IEC 61131-3 code, including ST parsers, XML validation, and model‑checking‑ready transformations. [OSS][Maintained?]
- [blark](https://github.com/klauer/blark) — Python parser for TwinCAT Structured Text and project files, built on Lark for AST extraction, refactoring, and code‑introspection tooling. [OSS]

## Structured Text libraries

- [structured-text-utilities](https://github.com/WengerAG/structured-text-utilities) — Portable ST utility library for arrays, strings, math, time, and statistics, designed to compile across strict IEC 61131-3 targets without vendor extensions. [OSS][Maintained?]

## Patterns and training

- [Applied Design Patterns in CODESYS V3](https://github.com/Aliazzzz/Applied-Design-Patterns-in-CODESYS-V3) — A collection of classic software patterns rewritten in CODESYS V3, useful as reference implementations and teaching material. [OSS][Maintained?]
- [OOP Concept Examples in CODESYS V3](https://github.com/Aliazzzz/OOP-Concept-Examples-in-CODESYS-V3) — Practical examples of IEC 61131-3 third‑edition OOP features in CODESYS, covering inheritance, interfaces, polymorphism, and advanced types. [OSS][Maintained?]
- [OOP IEC61131-3 Curso YouTube](https://github.com/runtimevic/OOP-IEC61131-3--Curso-Youtube) — Full course repo with PLCopen XML, TwinCAT projects, and multilingual documentation for IEC 61131-3 OOP patterns. [No licence][Maintained?]

## OPC UA

- [open62541](https://github.com/open62541/open62541) — Lightweight C OPC UA stack (IEC 62541) with client/server support and strong embedded adoption. [OSS]
- [node-opcua](https://github.com/node-opcua/node-opcua) — OPC UA client and server stack in Node.js for rapid prototyping and integration tooling. [OSS]
- [Eclipse Milo](https://github.com/eclipse-milo/milo) — Java OPC UA stack with full client/server implementations and industrial-grade security features. [OSS]

## EtherCAT

- [SOEM](https://github.com/OpenEtherCATsociety/SOEM) — Simple Open EtherCAT Master for real-time fieldbus integration and embedded control. [No licence]
- [SOES](https://github.com/OpenEtherCATsociety/SOES) — Simple Open EtherCAT Slave stack for building EtherCAT-compatible devices. [No licence]
- [ethercrab](https://github.com/ethercrab-rs/ethercrab) — Pure Rust EtherCAT master targeting both std and no_std environments. [No licence]
- [KickCAT](https://github.com/leducp/KickCAT) — C++ EtherCAT master/slave stack used in robotics and embedded control projects. [No licence]

## Modbus

- [libmodbus](https://github.com/stephane/libmodbus) — C library for Modbus RTU and TCP across Linux, macOS, Windows, and embedded targets, widely used as a low-level building block for device drivers. [OSS]
- [digitalpetri/modbus](https://github.com/digitalpetri/modbus) — Modern Java 17+ Modbus client and server stack with Modbus TCP, RTU, and TLS-secured Modbus TCP. [OSS]
- [nanoMODBUS](https://github.com/debevv/nanoMODBUS) — Compact C Modbus RTU/TCP stack for embedded and MCU targets, designed for tiny footprints and zero dynamic allocation. [OSS]
- [modbus-go](https://github.com/adibhanna/modbus-go) — Production-grade Modbus implementation in Go with client/server support. [OSS]
- [pymodbus](https://github.com/pymodbus-dev/pymodbus) — Full Modbus stack in Python with client, server, and simulator support, plus sync and async APIs for test rigs and production gateways. [No licence]
- [minimalmodbus](https://github.com/pyhys/minimalmodbus) — Lightweight Modbus RTU/ASCII library in Python for quick device integration. [OSS][Maintained?]
- [EasyModbusTCP.NET](https://github.com/rossmann-engineering/EasyModbusTCP.NET) — .NET Modbus client/server library covering TCP, UDP, and RTU with a simple API, commonly used for quick PLC integrations and test benches. [No licence][Maintained?]
- [Modbux](https://github.com/ploxc/modbux) — Modbus client/server simulator with rich data type handling, scan tools, and a desktop UI for commissioning. [OSS]

## EtherNet/IP and CIP

- [EIPScanner](https://github.com/nimbuscontrols/EIPScanner) — C++ EtherNet/IP stack for communicating with Rockwell and ODVA-compliant devices. [OSS]
- [pylogix](https://github.com/dmroeder/pylogix) — Python driver for Rockwell ControlLogix, CompactLogix, and Micro800 PLCs over EtherNet/IP, focused on simple tag read/write workflows. [OSS]
- [pycomm3](https://github.com/ottowayi/pycomm3) — Python Ethernet/IP library for Allen‑Bradley devices with CIP, Logix, and legacy drivers, now in maintenance‑only mode. [OSS]
- [libplctag](https://github.com/libplctag/libplctag) — Portable C library for Allen-Bradley EtherNet/IP tag access plus Modbus TCP, designed as a stable core for multi-language wrappers. [OSS]

## PROFINET

- [p-net](https://github.com/rtlabs-com/p-net) — PROFINET device stack for embedded targets, focused on deterministic industrial Ethernet. [No licence]

## POWERLINK

- [openPOWERLINK_V2](https://github.com/OpenAutomationTechnologies/openPOWERLINK_V2) — Open-source POWERLINK protocol stack for real-time Ethernet fieldbus networks. [No licence][Maintained?]

## CAN

- [can-utils](https://github.com/linux-can/can-utils) — Linux SocketCAN utilities for CAN bus diagnostics and test tooling. [No licence]

## ADS (TwinCAT)

- [ads-client](https://github.com/jisotalo/ads-client) — Unofficial Node.js ADS client for Beckhoff TwinCAT, with a modern API for reading and writing PLC variables from JavaScript stacks. [OSS]

## PLC protocol stacks

- [PLC4X](https://github.com/apache/plc4x) — Apache multi-language PLC protocol stack that unifies access to industrial controllers across Java, Go, C, and Python, with a large protocol catalogue and integration hooks. [OSS]

## MQTT

- [VerneMQ](https://github.com/vernemq/vernemq) — High-reliability MQTT broker used in industrial deployments where uptime and horizontal scale matter. [OSS]
- [mqtt-sim](https://github.com/marcelo-6/mqtt-sim) — MQTT simulator that generates configurable payload streams for testing brokers, device fleets, and dashboards. [OSS]

## Multi-protocol clients

- [TouchSocket](https://github.com/RRQM/TouchSocket) — High-performance .NET networking framework that includes Modbus, MQTT, WebSocket, TCP/UDP, and RPC modules, useful for building industrial gateways and custom protocol adapters. [OSS]
- [HslCommunication](https://github.com/dathlin/HslCommunication) — C# industrial comms library with wide PLC brand support plus Redis, MQTT, and WebSocket bridges, packaged for rapid data acquisition in .NET stacks. [No licence]

## Siemens S7

- [python-snap7](https://github.com/gijzelaerr/python-snap7) — Python wrapper for Snap7, providing Siemens S7 PLC Ethernet access with a well‑maintained Python API and cross‑platform wheels. [OSS]

## Simulators and diagnostics

- [opcilloscope](https://github.com/SquareWaveSystems/opcilloscope) — Terminal-based OPC UA client for browse, monitor, trend, and CSV capture without heavy GUI tooling. [OSS]

## SCADA and HMI

- [FUXA](https://github.com/frangoteam/FUXA) — Web-based SCADA/HMI platform with a browser editor, multi-protocol device connectivity, and a full-stack Node and Angular runtime for live process visualisation. [OSS]
- [SharpSCADA](https://github.com/GavinYellow/SharpSCADA) — C# SCADA and lightweight gateway stack with OPC/Modbus support, data acquisition, alarms, and an HMI designer workflow. [OSS][Maintained?]
- [scada.js](https://github.com/aktos-io/scada.js) — Distributed SCADA and MRP framework with web, desktop, and mobile clients. [No licence]

## Data collection and observability

- [Telegraf](https://github.com/influxdata/telegraf) — Metrics agent with 300+ plugins for industrial telemetry ingestion, transformation, and forwarding into time-series backends. [OSS]
- [EdgeShark](https://github.com/siemens/edgeshark) — Container network traffic capture and Wireshark integration for inspecting industrial edge and gateway traffic. [OSS]

## Simulation, digital twin, and CAD

- [ProcessSimulatePlugin](https://github.com/deusXmachina-dev/ProcessSimulatePlugin) — Siemens Process Simulate plugin focused on energy optimisation heuristics for robot cells. [OSS]
- [PartCAD](https://github.com/partcad/partcad) — Hardware package manager and digital-thread tooling for modular product data, BOMs, and manufacturability workflows. [OSS]

## OT security labs

- [GRFICSv3](https://github.com/Fortiphyd/GRFICSv3) — Fully containerised OT/ICS cyber-physical lab simulating a chemical plant with PLCs, HMI, realistic networking, and a 3D process visualisation for hands‑on security training. [OSS]

## DevOps and delivery

- [AX Azure DevOps Pipeline Example](https://github.com/loupeteam/AX-Azure-Devops-Pipeline-Example) — Reference CI/CD pipeline for SIMATIC AX libraries using Apax build, test, signing, and packaging. [No licence]
- [git2prompt](https://github.com/fabiomolinar/git2prompt) — CLI that packages GitHub repos into LLM-friendly prompt files, handy for automation code review and analysis workflows. [OSS]

## Testing and quality

- [TcUnit](https://github.com/tcunit/TcUnit) — Unit testing framework for TwinCAT 3 with test discovery, execution tooling, and reporting patterns for PLC code. [No licence]

## Robotics and integration

- [robin](https://github.com/ScalABLE40/robin) — ROS‑CODESYS shared‑memory bridge that maps CODESYS variables to ROS topics, enabling PLCs to interface with ROS stacks and robotics workflows. [OSS][Maintained?]
- [ethercat_driver_ros2](https://github.com/ICube-Robotics/ethercat_driver_ros2) — ROS 2 hardware interface for EtherCAT, connecting industrial fieldbus devices into robot control stacks. [OSS]

## Guides and reference stacks

- [IoT Technical Guide](https://github.com/IoT-Technology/IoT-Technical-Guide) — Large, opinionated IoT systems guide covering MQTT, CoAP, Modbus, OPC UA, gateways, rule engines, and ThingsBoard internals, aimed at building full-stack IoT platforms from scratch. [OSS][Maintained?]

## Platforms and ecosystems

- [ThingsGateway](https://github.com/ThingsGateway/ThingsGateway) — Cross-platform .NET 8 edge gateway for industrial data acquisition, protocol conversion, and northbound forwarding, with a modular plugin architecture. [OSS]
- [IoTGateway](https://github.com/iioter/iotgateway) — Industrial IoT gateway with a web UI, southbound PLC and protocol drivers, and northbound connectors to cloud platforms for bidirectional data flow. [OSS]
- [SagooIOT](https://github.com/sagoo-cloud/sagooiot) — Go-based enterprise IoT platform with device and protocol management, multi-protocol access, and a plugin-driven architecture for building full IoT business systems. [OSS]
- [DGIOT](https://github.com/dgiot/dgiot) — Large-scale industrial IoT platform with low-code modelling, rule engine, protocol adapters, and high connection density claims for carrier-grade deployments. [OSS]
