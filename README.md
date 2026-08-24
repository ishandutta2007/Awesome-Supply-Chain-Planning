# Awesome-Supply-Chain-Planning

## Top Supply Chain Planning Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Demand Planning, Supply Planning, S&OP/IBP, Advanced Planning & Scheduling (APS), Inventory Optimization & Scenario Planning*

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Supply Chain Planning**. These tools help organizations forecast demand, plan supply and production, balance inventory, run what-if scenarios, and support Sales & Operations Planning (S&OP) or Integrated Business Planning (IBP) processes.



**Examples** include Kinaxis, o9 Solutions, Blue Yonder, Logility, ToolsGroup, OMP, RELEX Solutions, FuturMaster, Anaplan, and Arkieva (the category leaders).



**Open-source emphasis**: Fully featured enterprise S&OP platforms are rare in pure open source, but strong APS and planning engines exist. **frePPLe** is the leading open-source supply chain planning tool, complemented by optimization solvers, forecasting libraries, and related projects. This section is heavily expanded with practical open alternatives.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Kinaxis](https://www.kinaxis.com/)**  

  Concurrent planning platform (Maestro / RapidResponse) enabling rapid scenario analysis and synchronized planning across demand, supply, and inventory for complex multi-site operations.



- **[o9 Solutions](https://o9solutions.com/)**  

  AI- and knowledge-graph-powered planning platform supporting supply chain, demand, and integrated business planning for large global enterprises.



- **[Blue Yonder](https://blueyonder.com/)**  

  Comprehensive supply chain planning and execution suite with particular strength in CPG, retail, and demand sensing, often paired with fulfillment capabilities.



- **[Logility](https://www.logility.com/)**  

  AI-driven supply chain planning platform serving mid-market and larger manufacturers and distributors with demand, supply, and inventory planning.



- **[ToolsGroup](https://www.toolsgroup.com/)**  

  Specialist in demand forecasting, inventory optimization, and service-level-driven planning, frequently used for complex multi-echelon networks.



- **[OMP](https://www.omp.com/)**  

  Advanced planning and scheduling solutions focused on detailed production and supply chain optimization for process and discrete industries.



- **[RELEX Solutions](https://www.relexsolutions.com/)**  

  Retail and CPG-oriented planning platform strong in demand forecasting, replenishment, and promotion-aware planning.



- **[FuturMaster](https://www.futurmaster.com/)**  

  Demand and supply planning solutions with capabilities spanning forecasting, S&OP, and related planning processes.



- **[Anaplan](https://www.anaplan.com/)**  

  Connected planning platform widely used for S&OP, demand planning, and financial-supply chain integration through flexible modeling.



- **[Arkieva](https://arkieva.com/)**  

  Supply chain planning software focused on demand, supply, and inventory planning with scenario and optimization features.



## Open-Source GitHub Projects

- **[frePPLe](https://github.com/frePPLe/frepple)**  

  Leading open-source demand forecasting and advanced planning & scheduling (APS) tool for manufacturing. Supports constraint-based planning, multi-level BOMs, material and capacity planning, and ERP integration via API. Community Edition is MIT-licensed.



- **[Timefold Solver (formerly OptaPlanner)](https://github.com/TimefoldAI)**  

  Powerful open-source constraint solver for planning and scheduling problems (job-shop, resource allocation, vehicle routing, etc.) that can underpin custom APS solutions.



- **[Python-based APS and scheduling libraries](https://github.com/)**  

  Projects such as python-lekin and similar frameworks offering flexible job-shop and production scheduling algorithms, heuristics, and optimization methods.



- **[planr and R/Python planning toolkits](https://github.com/)**  

  Open packages providing functions for projected inventory, coverage analysis, DRP (distribution requirements planning), and S&OP support.



- **[Scenario planning and what-if tools](https://github.com/)**  

  Open projects focused on supply chain scenario modeling, sensitivity analysis, and strategy evaluation.



- **[Open mSupply and logistics management systems](https://github.com/msupply-foundation/open-msupply)**  

  Open-source logistics and inventory management platforms (especially strong in health supply chains) that include planning and replenishment capabilities.



- **[Forecasting libraries (Prophet, statsmodels, Nixtla, etc.)](https://github.com/)**  

  Mature open-source time-series forecasting tools commonly used as the demand-planning engine in custom supply chain stacks.



- **[Inventory optimization and multi-echelon models](https://github.com/)**  

  Academic and community implementations of safety-stock, MEIO, and network optimization algorithms.



- **[ERPNext / Odoo manufacturing and planning modules](https://github.com/)**  

  Open ERP systems with MRP, production planning, and basic scheduling features that can serve as lighter planning foundations.



- **[OR-Tools and other optimization engines](https://github.com/google/or-tools)**  

  Google’s open optimization suite frequently applied to production scheduling, routing, and supply chain network problems.



### Additional Strong Open-Source Options

- Jupyter / notebook-based planning environments combining forecasting, optimization, and visualization.

- Apache Airflow or Prefect pipelines for orchestrating demand and supply planning workflows.

- Graph databases and knowledge-graph experiments for modeling complex supply networks.

- Open data sets and benchmarks for testing planning algorithms.

- Integration examples connecting frePPLe or custom solvers to ERP systems via REST or file-based interfaces.



**Frameworks for building custom systems**: Use **frePPLe** as the core APS and forecasting engine, feed it sales history and master data from an ERP or data warehouse, and extend with **Timefold**/OR-Tools for specialized scheduling problems. Layer open forecasting libraries for demand sensing and surface plans in open dashboards (Superset, Metabase). For lighter needs, combine ERPNext/Odoo MRP with custom Python optimization scripts. This approach delivers transparent, low-cost planning capability suitable for mid-market manufacturers and plants, while large global S&OP transformations still typically rely on commercial concurrent-planning platforms for scale, collaboration, and pre-built industry models.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Supply chain planning systems influence inventory, production, and customer service levels. Open-source tools provide excellent transparency and cost control but require solid data quality, modeling expertise, and process integration to deliver reliable plans. Always validate plans against operational constraints before execution.

- Planning accuracy depends heavily on master data, demand signals, and organizational S&OP maturity.



---

**Made for supply chain planners, S&OP leaders, and operations teams seeking practical, open planning capabilities.**

Let's make advanced planning more accessible, transparent, and adaptable.
