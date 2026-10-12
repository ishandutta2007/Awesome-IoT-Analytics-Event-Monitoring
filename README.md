# Awesome-IoT-Analytics-Event-Monitoring

# Top IoT Analytics & Event Monitoring Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Device Telemetry, Real-Time Event Processing & Industrial Intelligence*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **IoT Analytics & Event Monitoring Tools**. These tools ingest telemetry from connected devices, process streaming events at the edge and in the cloud, detect anomalies, and surface actionable insights — enabling predictive maintenance, operational efficiency, and real-time decisioning across industrial, commercial, and consumer IoT deployments.

**Examples** include Salesforce IoT Cloud, AWS IoT SiteWise, Azure IoT Hub, Google Cloud IoT, PTC ThingWorx, Software AG Cumulocity IoT, Samsara, Datadog IoT, Particle Cloud, and Losant (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom event processing, and transparent device data — ideal for industrial operators, smart building managers, and developers building data-sovereign IoT platforms.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[AWS IoT SiteWise](https://aws.amazon.com/iot-sitewise/)**  
  Managed service for collecting, organizing, and analyzing industrial equipment data at scale. Features asset modeling, OPC UA ingestion, edge processing via SiteWise Edge, and real-time monitoring dashboards . Computes industrial performance metrics like OEE and mean time between failures.

- **[Azure IoT Hub](https://azure.microsoft.com/en-us/products/iot-hub/)**  
  Fully managed service enabling secure bi-directional communication between millions of devices and cloud backends. Supports device-to-cloud and cloud-to-device messaging, device twins, direct methods, and per-device authentication .

- **[Google Cloud IoT Core](https://cloud.google.com/iot-core)**  
  Fully managed service for securely connecting and managing IoT devices, from a few to millions. Integrates with Google Cloud's big data services for analytics and application development .

- **[PTC ThingWorx](https://www.ptc.com/en/products/thingworx)**  
  Industrial IoT platform purpose-built for manufacturing, service, and engineering use cases. Now part of Velotic, offering pre-built applications, developer tools, and AI-ready workflows for digital transformation .

- **[Software AG Cumulocity IoT](https://www.softwareag.com/en_corporate/platform/iot/iot-analytics-platform.html)**  
  Distributed, open architecture IoT platform with edge, on-premises, and cloud deployment. Features self-service analytics, streaming analytics builder, and OT-IT integration tools . Forrester TEI study reported 339% ROI and $8.1M in business benefits over three years.

- **[Samsara](https://www.samsara.com/products/platform)**  
  Connected operations platform for fleet, equipment, and site monitoring. Features 15,000+ connected assets, 99.99% uptime SLA, 350+ integrations, and AI agents that act on operational insights .

- **[Datadog IoT Agent](https://docs.datadoghq.com/agent/iot/)**  
  Optimized Agent version for monitoring IoT devices and embedded applications. Supports system, disk, network, Systemd, and NTP checks with custom metrics via DogStatsD and log collection . Minimal footprint: ~36 MB memory, ~0.5% CPU.

- **[Particle Cloud](https://www.particle.io/)**  
  Central hub for managing IoT devices, applications, and data. Features OTA application deployment, event streaming, cloud functions, device groups, and secure authentication .

- **[Losant](https://www.losant.com/)**  
  Low-code Industrial IoT platform acquired by SUSE in February 2026. Recognized in 2025 Gartner Magic Quadrant for Global IIoT Platforms. Features visual workflow engine and customizable dashboards for operational technology teams .

- **[Salesforce IoT Cloud](https://www.salesforce.com/)**  
  IoT event processing platform within Salesforce ecosystem for ingesting device data, triggering business rules, and integrating with CRM workflows.

## Open-Source GitHub Projects

- **[Magistrala](https://github.com/absmach/magistrala)**  
  Open-source IoT middleware and platform written in Go. Provides device management, messaging, alarms, bootstrap service, rules engine, and multi-protocol support via microservices architecture. Apache 2.0 licensed . Includes SDK, CLI, and integrations for Timescale, Redis, Prometheus, and Jaeger.

- **[Contexus IoTHub](https://build-up.ec.europa.eu/)**  
  Open-source platform for managing IoT devices and data, developed for smart building and connected infrastructure projects. Features remote device management, configurable dashboards, business rule definition, and event-based alerts . Modular architecture enables domain-specific applications without proprietary lock-in.

- **[Mainflux](https://github.com/mainflux/mainflux)**  
  Open-source IoT platform and messaging system. Provides device management, data collection, and application enablement with multi-protocol support (HTTP, MQTT, WebSocket, CoAP). Apache 2.0 licensed.

- **[ThingsBoard](https://github.com/thingsboard/thingsboard)**  
  Open-source IoT platform for data collection, processing, visualization, and device management. Features rule engine, dashboards, alarms, and multi-tenancy. Apache 2.0 licensed.

- **[Home Assistant](https://github.com/home-assistant/core)**  
  Open-source home automation platform with extensive IoT device integration. Features automation engine, dashboards, and 2,000+ integrations. Apache 2.0 licensed. While consumer-focused, provides patterns for event-driven IoT monitoring.

- **[Node-RED](https://github.com/node-red/node-red)**  
  Flow-based programming tool for wiring together IoT devices, APIs, and services. Massive node ecosystem for event-driven automation and data transformation. Apache 2.0 licensed.

- **[Eclipse Mosquitto](https://github.com/eclipse/mosquitto)**  
  Lightweight MQTT broker for IoT messaging. Supports MQTT 5.0, TLS, WebSockets, and bridge connections. EPL-2.0 licensed.

- **[Eclipse Ditto](https://github.com/eclipse-ditto/ditto)**  
  Digital twin framework for IoT devices. Provides abstraction layer for managing device state and capabilities. EPL-2.0 licensed.

- **[Apache PLC4X](https://github.com/apache/plc4x)**  
  Universal protocol adapter for industrial PLCs. Connects to Modbus, OPC UA, Siemens S7, and more for industrial IoT data ingestion. Apache 2.0 licensed.

- **[OpenEMS](https://github.com/OpenEMS/openems)**  
  Open-source energy management system for optimizing renewable energy, storage, and grid interaction. Features real-time monitoring and control. AGPL-3.0 licensed.

- **[Telegraf](https://github.com/influxdata/telegraf)**  
  Plugin-driven server agent for collecting and reporting metrics from IoT devices, sensors, and systems. MIT licensed.

- **[InfluxDB](https://github.com/influxdata/influxdb)**  
  Time-series database optimized for IoT telemetry and event data. Features downsampling, retention policies, and Flux query language. MIT licensed.

- **[Grafana](https://github.com/grafana/grafana)**  
  Open-source analytics and monitoring platform for visualizing IoT telemetry. AGPL-3.0 licensed.

- **[Thingspeak](https://github.com/iobridge/thingspeak)**  
  Open-source IoT analytics platform (MATLAB-based) for collecting, analyzing, and visualizing sensor data. GPL-3.0 licensed.

### Additional Strong Open-Source Options

- **[OpenRemote](https://github.com/openremote/openremote)** — Open-source IoT platform for asset management, monitoring, and automation. AGPL-3.0 licensed.
- **[SiteWhere](https://github.com/sitewhere/sitewhere)** — Open-source IoT application enablement platform. CPAL-1.0 licensed.
- **[DeviceHive](https://github.com/devicehive/devicehive)** — Open-source IoT platform with REST, WebSocket, and MQTT APIs. Apache 2.0 licensed.
- **[Kaa IoT Platform](https://github.com/kaaproject/kaa)** — Open-source middleware for IoT device management and data analytics. Apache 2.0 licensed.
- **[OpenHAB](https://github.com/openhab/openhab-core)** — Open-source automation bus for smart home and industrial IoT. EPL-2.0 licensed.
- **[Zeek](https://github.com/zeek/zeek)** — Network security monitor adaptable for IoT traffic analysis. BSD-3-Clause licensed.
- **Stream Processing** — Apache Flink, Apache Kafka Streams, RisingWave for real-time IoT event processing.

**Frameworks for building custom systems**: Combine **Magistrala** or **ThingsBoard** for device management, **Eclipse Mosquitto** for MQTT messaging, **Node-RED** for flow-based event processing, **InfluxDB + Grafana** for telemetry visualization, and **Apache PLC4X** for industrial protocol integration to build a complete self-hosted IoT analytics stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- IoT analytics tools must comply with data protection regulations (GDPR, CCPA), industry standards (IEC 62443, ISO 27001), and device security best practices.
- Self-hosted open-source solutions require proper security hardening, network isolation, and ongoing maintenance.

---

**Made for industrial engineers, IoT architects, operations managers, and developers building IoT analytics and event monitoring platforms.**  
Let's make IoT analytics more open, interoperable, and operator-friendly.
