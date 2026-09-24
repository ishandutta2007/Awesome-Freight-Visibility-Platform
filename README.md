# Awesome-Freight-Visibility-Platform

# Top Freight Visibility Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Real-Time Transportation Visibility, Predictive ETA, Multimodal Tracking & Supply-Chain Control Towers*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Freight Visibility**. These systems aggregate carrier, telematics, and milestone data to provide real-time shipment status, predictive ETAs, exception alerts, and multimodal visibility across road, ocean, air, and rail.

**Examples** include project44, FourKites, Shippeo, Overhaul, GoComet, FarEye, Everstream Analytics, Descartes MacroPoint, Roambee, and Turvo (the category leaders).

**Open-source emphasis**: Network-scale freight visibility is almost entirely commercial. Practical open options include GPS tracking cores (**Traccar**), experimental TMS projects, and package-tracking prototypes. This section lists the strongest available open resources and is realistic about the large commercial gap.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[project44](https://www.project44.com/)**  
  Enterprise real-time transportation visibility platform covering road, ocean, air, and rail with strong developer APIs and multimodal control-tower capabilities.

- **[FourKites](https://www.fourkites.com/)**  
  Leading real-time supply-chain visibility platform known for predictive ETAs, North American truckload strength, and expanding multimodal and yard/inventory-in-motion workflows.

- **[Shippeo](https://www.shippeo.com/)**  
  European real-time transportation visibility platform with strong multimodal coverage and carrier network focus.

- **[Overhaul](https://www.overhaul.com/)**  
  Visibility and security platform emphasizing cargo protection, theft prevention, and high-value or sensitive shipment tracking.

- **[GoComet](https://www.gocomet.com/)**  
  Freight and logistics platform offering visibility, rate management, and shipment tracking for shippers and forwarders.

- **[FarEye](https://www.fareye.com/)**  
  Delivery and logistics execution platform with visibility, last-mile, and operational orchestration capabilities.

- **[Everstream Analytics](https://www.everstream.ai/)**  
  Supply-chain risk and visibility analytics platform combining tracking with disruption intelligence.

- **[Descartes MacroPoint](https://www.descartes.com/)**  
  Real-time freight tracking and visibility solution widely used for North American track-and-trace and carrier connectivity.

- **[Roambee](https://www.roambee.com/)**  
  Sensor-based and visibility platform for shipment condition monitoring and supply-chain tracking.

- **[Turvo](https://turvo.com/)**  
  Collaborative logistics platform with visibility, execution, and multi-party workflow features for shippers and carriers.

## Open-Source GitHub Projects
- **[Traccar](https://github.com/traccar/traccar)**  
  Open-source GPS tracking platform supporting many device protocols—usable as a foundation for vehicle and asset visibility in private fleets.

- **[Kaporeal TMS and open transportation management projects](https://kaporeal.com/)**  
  Emerging open-source TMS concepts covering loads, dispatch, shipment tracking, and logistics operations with self-hosting in mind.

- **[ATLAS and logistics MCP / AI agent open servers](https://github.com/cargofy/ATLAS)**  
  Open tools that expose shipments, carriers, tracking events, and logistics data to AI agents while keeping data under your control.

- **[Package and multi-carrier tracking open front-ends](https://github.com/)**  
  Community projects that aggregate tracking events from multiple parcel and freight carriers into a single view.

- **[OpenStreetMap routing and map open engines](https://github.com/)**  
  OSRM, GraphHopper, and related open routing engines useful for ETA prototypes and route visualization.

- **[Event-streaming open pipelines for logistics](https://github.com/)**  
  Kafka and similar stacks used to ingest telematics and milestone events into custom visibility dashboards.

- **[Geofencing and exception open libraries](https://github.com/)**  
  Spatial and rule libraries for detecting arrivals, delays, and route deviations.

- **[Sensor and IoT open collectors](https://github.com/)**  
  Tools for ingesting temperature, shock, and location sensors that can complement visibility platforms.

- **[TMS / WMS integration open adapters](https://github.com/)**  
  Community connectors for pulling shipment status from internal systems into open dashboards.

- **[Documentation and control-tower open playbooks](https://github.com/)**  
  Guides for building lightweight visibility layers on top of carrier APIs and GPS data.

### Additional Strong Open-Source Options
- Using **Traccar** for private fleet and asset GPS visibility when you control the devices.
- Prototyping shipment event aggregation with open tracking front-ends and streaming pipelines.
- Accepting that global carrier networks, multimodal predictive ETAs at scale, yard integration, and enterprise control-tower SLAs still require commercial platforms (project44, FourKites, Shippeo, MacroPoint, Overhaul, etc.).
- Focusing open-source efforts on data ownership, private telematics, and avoiding lock-in for internal fleets.

**Frameworks for building custom systems**: Collect GPS/telematics via Traccar or carrier APIs → stream events into a warehouse or message bus → compute simple ETAs and exceptions → display in an open dashboard → escalate critical shipments to commercial visibility networks when needed. Suitable for private fleets and limited-scope tracking. Most large shippers and 3PLs rely on commercial freight visibility platforms for network coverage and predictive accuracy.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Freight visibility systems process location and shipment data that may be commercially sensitive. Proper access control and data agreements with carriers are required. This list is not operational or legal advice.

---
**Made for supply-chain, logistics, and transportation visibility teams.**
Let's keep shipments visible, data-owned, and as open as practical.
