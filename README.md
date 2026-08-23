# Awesome-Telecom-Service-Assurance

## Top Telecom Service Assurance Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Network Performance Monitoring, QoS/QoE, Fault & Performance Management, 5G/RAN Assurance, Probe Analytics & Closed-Loop Assurance*

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Telecom Service Assurance**. These systems help mobile and fixed operators monitor network and service quality, detect degradations, assure SLAs, analyze customer experience, and support closed-loop automation across RAN, core, transport, and IP layers.



**Examples** include Accedian, Viavi Solutions, Nokia Deepfield, EXFO, Infovista, NETSCOUT, RADCOM, Roamware, Amdocs Service Assurance, and MYCOM OSI (the category leaders).



**Open-source emphasis**: Fully featured commercial-grade telecom service assurance suites are rare in pure open source. This section is expanded with the strongest available open-source network management, ISP traffic management, telecom inventory/CM platforms, and monitoring stacks that operators and private networks can adapt for assurance use cases.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Accedian](https://www.accedian.com/)**  

  Service assurance and performance monitoring solutions focused on precise metrics, active testing, and experience assurance for telecom and enterprise networks.



- **[Viavi Solutions](https://www.viavisolutions.com/)**  

  Broad portfolio of network test, monitoring, and service assurance tools spanning fiber, 5G, and end-to-end visibility for operators.



- **[Nokia Deepfield](https://www.nokia.com/)**  

  Network intelligence and security analytics platform used for traffic analysis, DDoS detection, and service assurance insights at scale.



- **[EXFO](https://www.exfo.com/)**  

  Test, monitoring, and analytics solutions strong in fiber, 5G, and real-time service assurance for communications service providers.



- **[Infovista](https://www.infovista.com/)**  

  Network and service assurance portfolio covering radio, core, and customer experience analytics for mobile and fixed operators.



- **[NETSCOUT](https://www.netscout.com/)**  

  Service assurance and cybersecurity visibility platforms (including nGenius) providing deep packet and session-level insight for carriers and large enterprises.



- **[RADCOM](https://radcom.com/)**  

  Cloud-native service assurance and network intelligence solutions focused on 5G and virtualized environments.



- **[Roamware](https://www.roamware.com/)**  

  Solutions historically associated with roaming and related service management (context-dependent in modern assurance stacks).



- **[Amdocs Service Assurance](https://www.amdocs.com/)**  

  Service assurance capabilities within the broader Amdocs portfolio, supporting operator operational and customer experience processes.



- **[MYCOM OSI](https://www.mycom-osi.com/)**  

  Service assurance and performance management platform used by operators for multi-vendor, multi-technology network monitoring and analytics.



## Open-Source GitHub Projects

- **[OpenNMS](https://github.com/OpenNMS/opennms)**  

  Enterprise-grade open-source network management platform providing fault, performance, and traffic monitoring, event correlation, and extensible data collection — widely usable as an assurance foundation.



- **[LibreQoS](https://github.com/LibreQoE/LibreQoS)**  

  Self-hosted traffic management and network operations platform for ISPs that reduces bufferbloat, enforces plans, and gives topology-aware subscriber and congestion visibility.



- **[Boda Telecom Suite Community Edition (BTS-CE)](https://github.com/bodastage/bts-ce)**  

  Open-source, vendor- and technology-agnostic telecommunication network management platform with topology generation, CM browsing, RAN audit, and reporting capabilities.



- **[LibreNMS](https://github.com/librenms/librenms)**  

  Popular open-source network monitoring system with auto-discovery, extensive device support, and performance/availability data useful for service assurance inputs.



- **[Prometheus + Grafana + telecom exporters](https://github.com/)**  

  De-facto open observability stack frequently used by operators and private networks for metrics, alerting, and custom assurance dashboards.



- **[Zeek / Suricata + flow tools](https://github.com/)**  

  Open network security and traffic analysis tools that can feed deep visibility into custom assurance and anomaly-detection pipelines.



- **[osquery / Fleet and endpoint telemetry](https://github.com/)**  

  Open endpoint and infrastructure visibility tools adaptable for certain telco infrastructure monitoring use cases.



- **[Telecom inventory and CM open projects](https://github.com/)**  

  Community tools for parsing vendor configuration dumps, building topology, and performing baseline/parameter audits.



- **[Bandwidth and active testing open tools](https://github.com/)**  

  Open frameworks for scheduled speed tests, latency probes, and SLA-style measurements (iperf, Ookla integrations, custom probes).



- **[Private 5G / core open monitoring stacks](https://github.com/)**  

  Observability and management components from open 5G core and private network projects that include performance and health monitoring.



### Additional Strong Open-Source Options

- NetBox or similar for source-of-truth inventory that feeds assurance systems.

- Kafka / Flink / Spark pipelines for real-time KPI and event processing.

- Custom closed-loop automation using open orchestration (ONAP components where applicable, or lighter workflow engines).

- OpenTSDB / VictoriaMetrics / InfluxDB for long-term KPI storage.

- Community detection and anomaly libraries applied to network time-series data.



**Frameworks for building custom systems**: Use **OpenNMS** or **LibreNMS** + **Prometheus/Grafana** as the monitoring core, enrich with flow and active-test data, maintain inventory/topology in an open source-of-truth, and layer custom analytics or simple closed-loop actions via open workflow tools. For ISP-focused access networks, **LibreQoS** provides strong subscriber-level visibility and traffic management. These stacks give operators and private-network owners full data ownership and lower cost, but lack the deep multi-vendor probe ecosystems, pre-built 5G/RAN assurance models, and carrier-scale support of commercial service assurance platforms.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Telecom service assurance systems handle critical operational data and can influence network changes. Open-source solutions provide transparency and cost advantages but require careful integration, scaling, and operational processes to meet carrier-grade reliability and multi-vendor coverage expectations.

- Always validate any assurance or automation logic in non-production environments before impacting live services.



---

**Made for network operations, assurance, and engineering teams in telecom and private networks.**

Let's make service quality visibility more open, adaptable, and under operator control.
