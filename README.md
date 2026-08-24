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

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform / Product | Focus & Capabilities | Starting Pricing Tier | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Accedian (Cisco PCA)](https://www.accedian.com/)** | Active network & service performance monitoring, microsecond-level latency analytics, and synthetic experience testing across telco and cloud domains. | Starting at **~$1,500/month** (~$18,000/year) for Cisco Crosswork Assurance Essentials / Skylight base sensor pack. | **30-day free trial / PoC** with up to 25 virtual test sensor endpoints and synthetic traffic generation. |
| **[Viavi Solutions](https://www.viavisolutions.com/)** | End-to-end test, packet analysis, and automated assurance (Observer, TeraVM, NITRO) across fiber, 5G RAN, and transport networks. | Starting at **~$450/month per probe** (~$3,500 perpetual/instance entry license for Observer Apex). | **14 to 30-day evaluation trial** on request, providing full lab access to Observer Suite and TeraVM virtual test agents. |
| **[Nokia Deepfield](https://www.nokia.com/)** | Real-time big data network analytics, IP network intelligence, DDoS mitigation (Defender), and carrier-scale traffic assurance (Genome). | Starting at **~$2,000/month** (~$24,000/year) base subscription scaling by monitored flow throughput (Gbps/Mpps). | **30-day guided Proof of Concept (PoC)** sandbox trial with live flow analysis and threat telemetry. |
| **[EXFO](https://www.exfo.com/)** | Automated service assurance (Nova SensAI, Adaptive Service Assurance) and fiber/5G active test orchestration (EXFO Exchange). | Starting at **~$1,200/month** (~$14,400/year) for EXFO Exchange and Nova Context starter licenses. | **30-day free trial / sandbox** for EXFO Exchange and Nova Active virtual agents with sample telemetry datasets. |
| **[Infovista](https://www.infovista.com/)** | Multi-domain 5G/RAN and core assurance (Ativa suite), RF network planning (Planet SaaS), and automated drive/bench testing (TEMS / VistaTest). | Starting at **~$2,000/month** (~$24,000/year) for entry Ativa / Planet SaaS starter module. | **14-day guided cloud demo / sandbox** with pre-configured telco network slices and KPI analytics templates. |
| **[NETSCOUT](https://www.netscout.com/)** | Deep packet inspection (Smart Data), carrier-scale service visibility, and cyber/assurance telemetry (nGeniusONE, Omnis, vSTREAM). | Starting at **~$0.95/hour** (~$690/month PAYG on AWS) or **~$15,000/year** for base vSTREAM virtual appliance subscription. | **14-day free trial** for vSTREAM virtual probes on AWS Marketplace; **30-day guided PoC** for nGeniusONE virtual appliances. |
| **[RADCOM](https://radcom.com/)** | Cloud-native automated assurance, 5G network intelligence, and containerized probe telemetry (RADCOM ACE) for virtualized carrier networks. | Starting at **~$3,000/month** (~$36,000/year) for entry cloud-native probe and network telemetry tier. | **30-day lab PoC / trial** deployment on AWS/Azure supporting up to 10 Gbps monitored interface capacity. |
| **[Roamware (Mobileum)](https://www.roamware.com/)** | Roaming service assurance, interconnect steering, fraud protection, and subscriber experience analytics (Active Intelligence platform). | Starting at **~$2,500/month** (~$30,000/year) for core roaming quality assurance & test monitoring module. | **30-day guided evaluation pilot** for roaming QoS verification and automated synthetic test call generation. |
| **[Amdocs Service Assurance](https://www.amdocs.com/)** | End-to-end service assurance, fault & performance correlation (Smart End-to-End Assurance), and automated root-cause orchestration. | Starting at **~$4,000/month** (~$48,000/year) base subscription for digital assurance & fault management modules. | **30-day PoC / sandbox environment** with pre-populated multi-layer topology and network fault data. |
| **[MYCOM OSI](https://www.mycom-osi.com/)** | Cloud-native Experience Assurance & Analytics (EAA) SaaS, multi-vendor performance and fault management for Tier-1 CSPs. | Starting at **~$3,500/month** (~$42,000/year) for entry EAA SaaS cloud deployment package. | **30-day enterprise trial / PoC** via AWS Marketplace for CSPs (monitoring up to 5,000 network entities). |



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
