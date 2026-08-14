# Awesome-Voyage-Optimization

## Top Voyage Optimization Tools Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Weather Routing, Fuel Efficiency, Route Planning, CII Compliance & Maritime Performance*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Voyage Optimization**. These systems optimize ship routes and speeds using weather, ocean conditions, vessel performance models, fuel consumption curves, and commercial constraints to reduce fuel use, emissions, and improve ETA reliability.

**Examples** include StormGeo, Bearing AI, NAPA Fleet Intelligence, OrbitMI, Weathernews Optimum Route, Blue Visby, Navtor, ZeroNorth, DTN Marine, and ShipIn Systems (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, weather routing algorithms, A*/genetic optimizers, and open maritime pathfinding libraries — ideal for shipping companies, researchers, naval architects, and developers building transparent, customizable voyage optimization solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[StormGeo](https://www.stormgeo.com/)**  
  Leading weather routing and voyage optimization platform (part of Alfa Laval) providing route advice, fuel savings, and fleet decision support based on advanced weather and performance models.

- **[Bearing AI](https://www.bearing.ai/)**  
  AI-driven maritime platform focused on voyage optimization, performance prediction, and operational efficiency for commercial shipping.

- **[NAPA Fleet Intelligence](https://www.napa.fi/)**  
  Comprehensive fleet and voyage optimization suite offering weather routing, fuel analysis, performance monitoring, and decision support for ship and shore teams.

- **[OrbitMI](https://www.orbitmi.com/)**  
  Voyage management and optimization platform that integrates commercial, operational, and performance data for efficient fleet operations.

- **[Weathernews Optimum Route](https://global.weathernews.com/)**  
  Weather-based route optimization and AI-assisted voyage planning services leveraging extensive maritime weather data and vessel performance insights.

- **[Blue Visby](https://www.bluevisby.com/)**  
  Collaborative platform addressing the “hurry-up-and-wait” problem through just-in-time arrival coordination and voyage optimization for reduced emissions.

- **[Navtor](https://www.navtor.com/)**  
  Digital navigation and voyage planning solutions including electronic chart systems, route optimization, and compliance tools for modern fleets.

- **[ZeroNorth](https://zeronorth.com/)**  
  Data-driven voyage optimization platform focused on fuel efficiency, emissions reduction, and commercial voyage decision-making.

- **[DTN Marine](https://www.dtn.com/)**  
  Weather intelligence and marine decision-support services supporting route optimization and operational safety for shipping.

- **[ShipIn Systems](https://www.shipin.ai/)**  
  AI-powered fleet performance and voyage insights platform using computer vision and operational data for optimization and safety.

## Open-Source GitHub Projects
- **[Weather Routing Tool (52°North)](https://github.com/52North/WeatherRoutingTool)**  
  Python package for optimizing ship routes based on fuel consumption under varying weather conditions, featuring isofuel and genetic algorithms plus weather data handling.

- **[WindMar](https://github.com/windmar-nav)**  
  Open-source maritime route optimization platform with weather-aware A*/Dijkstra routing, vessel performance modeling, and Copernicus weather data integration.

- **[SIMROUTE](https://github.com/ManelGrifoll/SIMROUTE)**  
  Weather ship routing code using Copernicus Marine wave predictions and A* algorithm for optimized routes, emissions estimation, and safety monitoring.

- **[libweatherrouting + GWeatherRouting](https://github.com/dakk/libweatherrouting)**  
  Python weather routing library for sailing and the related open-source GTK navigation/routing application supporting GRIBs, polars, and multi-point routing.

- **[maritime-routing (ArcNautical)](https://github.com/SaltyTaro/maritime-routing)**  
  Production-grade TypeScript maritime routing engine with A* ocean pathfinding, port database, weather-aware ETA, and land-avoidance guarantees.

- **[cms_routing](https://github.com/jsten07/cms_routing)**  
  Genetic algorithm implementations for just-in-time and energy-efficient ship routing considering weather, engine power, and schedule constraints.

- **[searoute / searoute-py ecosystem](https://github.com/Project-Harrison/searoute_mcp)**  
  Open libraries and MCP servers for computing realistic ocean routes, distances, and waypoints between ports while avoiding land.

- **[weather-engine-maritime](https://github.com/savetree-1/weather-engine-maritime)**  
  AI-powered maritime weather intelligence project aiming at route optimization, fuel efficiency, and safety alerts using forecast data.

- **[OpenCPN + weather routing plugins](https://opencpn.org/)**  
  Popular open-source chart plotter and navigation software with community weather routing and voyage planning plugins.

- **[Community A* / isochrone / genetic routing notebooks](https://github.com/)**  
  Numerous research and educational repositories implementing classic weather routing algorithms, fuel models, and multi-objective optimizers.

### Additional Strong Open-Source Options
- Copernicus Marine / NOAA GRIB data pipelines and open weather field processors.
- Holtrop-Mennen and other open vessel resistance/fuel models for performance prediction.
- AIS + weather fusion projects for validating optimized routes against real voyages.
- Academic multi-objective optimizers (NSGA-II based) for fuel vs. time trade-offs.
- Integration examples with Signal K, Node-RED, and InfluxDB/Grafana for onboard decision support.

**Frameworks for building custom systems**: Combine **Weather Routing Tool** or **WindMar** for core optimization, **maritime-routing** or **searoute** for baseline ocean paths, Copernicus/NOAA data feeds for weather, vessel performance models (Holtrop or custom), and visualization with OpenCPN or web maps. Add local LLMs (Ollama) for natural-language route briefings and constraint handling.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Voyage optimization tools influence safety-critical navigation decisions and must be validated against official charts, company SMS, and regulatory requirements (SOLAS, COLREGs, CII, etc.).
- Self-hosted open-source solutions require accurate weather data, realistic vessel models, proper quality control, and qualified human oversight before operational use.

---
**Made for shipping companies, fleet managers, naval architects, maritime researchers, and voyage planners.**
Let's make voyage optimization more open, data-driven, and fuel-efficient.
