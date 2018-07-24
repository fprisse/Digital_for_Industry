---
layout: "post"
title: "Asset Performance Management Introduction"
date: "2018-07-23 23:37"
---

## 1. What is it ?
Asset performance management is a set of capabilties. Namely: data capture, integration, visualization and analytics. Tied together with the **primary goal of optimising reliability and availability of physical assets** and/or reducing maintenance cost. However as time and technology progresses we have come to expect systems and application to not only extract from it's ecosysystem. We today expect APM methodology and solutions to contribute to the **optimisation production and product quality too**. Thus forming an integral part of what we at Capgemini have dubbed the Digital Factory Platform.

![APM Elements](https://fprisse.github.io/Digital_for_Industry/images/APM-Solution-Elements.PNG)

Core of the concept is creating a comprehensive view across operations and maintenance, by making use of the same base information and performance metrics. Rather than reporting to each other.

This does not require fully Integrating production management and asset management in terms of business processes and organization. APM when done right does however fascilitate further intergration of activies in the production and maintenance realm.

APM:
- includes the concepts of condition monitoring, predictive forecasting and reliability-centered maintenance (RCM).
- is a manner to run maintenance operations as an intergral part of your daily (prodution) operations
- is not about *switching* from preventive maintenance to condition monitoring but it aims to add **sensory and operational data** to the equasion.

![Capgemini Digital Maturity](https://fprisse.github.io/Digital_for_Industry/images/Digital_Maturity.PNG)

**History:** The methodology and terminology originates mainly from asset intensive continuous process industry with a homgenous product such as upstream oil & gas / electricity production and utilities. Industries Where the uptime component was the most important of the OEE equasion.

|   | In context with other Maintenance and Asset Management systems |
| --- | --- |
| APM | APM is designed for data drive decision making and planning to realize safe, reliable, and efficient operation of equipment and  infrastructure |
| EAM | EAM is designed for maintenance execution. A two-way link between the two is key for 1) Using maintenance execution history to gauage likelihood of failure 2) To trigger the creation or re-scheduling of work-orders |
| AIP | Asset investment planning (AIP) AIP takes data on asset condition, maintenance costs, criticality,  budgets and risks, to produce a CAPEX forecast for asset replacement or decommissioning |

## 2. Why is it good ?
In Capital-intensive industries success is for the greater part defined by the balancing act of risk of undesirable events and the cost of preventing them. Today most organizations rely on preventive maintenance regimes and basic monitoring (mostly alarm systems provided by OEM's) for realizing safety, uptime and reliability at acceptable cost. Based on failures specific components may be prioritized for overhauls. Some do even adopt the maintenance and inspections intervals to take into account deviations in load & runtime based on reports provided by operations.

Asset performance management is first and foremost about doing the above in a more data-drive manner and making use of advanced analytics to improve failure-mode modeling to improve maintenance regimes.

Furthermore: accurate determination of the likelihood of failure is possible by structurally broadening the scope of real-time data that is taken into account such as:
- Get load and runtime data from the machines
- Add raw material and product specifications
- Relate product quality reporting to machine performance

When well translated into component specific agenda's this allows for (on average) longer intervals for inspections and overhauls AND prevention of undesirable events (failure, contamination or quality issues) by advancing maintenance work when models indicate a heightened likelihood of failure

| Benefits |
| --- |
| Maximize output, Longer production runs with confidence: Fewer unplanned disruptions due to equipment breakdowns increases your OEE and means you can consistently meet production targets and achieve or exceed revenue goals.|
| Optimize maintenance cycles. Move toward predictive and prescriptive maintenance strategies to address known sources of failure and performance degradation without driving up costs due to just-in-case preventative part replacements. |
| Reduce overall cost of ownership: Drive down maintenance cost due reduced unplanned work, improved sparepart inventory and longer lead times for contracted work |
| Improve root-cause analysis. Advanced analytics, data mining and data visualization tools enable engineers to identify real root causes and develop ideal corrective action plans faster and more effectively.|
| Help comply with regulations: EG: ISO 55001 |

## 3. How does APM work ?
APM is not one *thing*. APM is a set of well **orchestrated capabilties, involving business logic, governance, technology and procured services**

### 3.1  A comprehensive set of metrics (cross discipline)

![APM_KPI_TREE](https://fprisse.github.io/Digital_for_Industry/images/APM_KPI_TREE.PNG)

### 3.2 Data Model: Collect and Make Available
- Cross discipline:
  - Maintenance: WO records, Regimes, Inspection reports
  - Operations: Performance, Raw Materials, Product Specs.
  - Quality Management: Quality reports, Rejects
  - Machine data eg. RPM, Amps, Vibration
  - Extra sensor data
- Provided in both event as stored format
- Environmental Data

### 3.3 Static data repository : Shared or synchronized
In order for data to be relate-able a foundation of well maintained registry of assets and individual products is needed.
- Asset tree
- As-built documentation
- Asset dependency tables

Good thing about running real live data through these registries is that faulty entries become very apparent. In fact there are APM solution providers that have (partly) automated the work flow for correcting anomalies.

### 3.4 Predictive Analysis Workbench
- Tools to build predictive models
- Correlation, Regression & Clustering
- Exportable Probality Models

Image: Example of analytical toolbox - IBM - Predictive Solutions
![Example of Analytical Toolbox by IBM](https://fprisse.github.io/Digital_for_Industry/images/IBM_Prescriptive_Maintenance.PNG)

### 3.6 Asset Health Dashboard
- Display geographic dispersion of assets
- Health: Likelihood of Failure (incl. forecast)
- Criticality: Impact of undesirable event

Image: Example of asset health dashboard - Capgemni APM on MS-Azure
![Example asset Health dashboard](/images/CapgeminiAPM5.PNG)

### 3.7 Reporting and Publishing Tools
- Customizable Templates
- Web-based & Interactive
- Distributable format

### 3.8 Model implementation (automated analysis & alarms)
- Database: Asset Health (LOF)
- Act on Events: Alarms
- Attribution of Alarms to relevant discipline
- Create Events: Workorders & Re-scheduling

### 3.9 Advanced Analytics Capability
- Platform & Application Governance
- Multivariate Analysis Skills
- Procured Training & Specialist Support

Example of Advanced analytics support framework - Capgemini Consulting
![Advanced Analytics Capabilities](https://fprisse.github.io/Digital_for_Industry/images/Data_Capabilty.PNG)

### 4.0 Connectivity
- Enterprise systems
- Machine Bus
- External Sensors (IOT)
- EAM (Maintenance planning & execution)
- Performance mgt Systems (OEE, Product data & Quality)
- Environmental data (API)

Example of sensoring and connectivity solution - Sogeti High Tech
![Sogeti Smart Knob](https://fprisse.github.io/Digital_for_Industry/images/Smart_Knob.PNG)


## Extra: IOT Agenda:
As the APM dashboard provides such a broad view it is a very appropriate starting point for pinpointing for determining where adding datasources will have the most value. Thereby setting the priorities for an IOT agenda based on a balanced view upon opeartional and asset management priorities

IoT is a gamechanger especially for older assets: whereas intergrating and acting such a wide breadth of data and cross-discipline was deemed to be only for copmpanies with newer facilities now teh upgrading of sensors and such has become a relatively small investmetn

## What makes it hard ?
- imperfection of information (at start) base data such as asset registries
- choosing the right level of detail
- making it work as a managemetn tool or making it work at shop floor level
- Must delvier a plan/agenda / schedule
- right breadth of scope and level of detail

It thus requires a mix of
1) top down standard
2) bottom up Analysics & Learning exercises
3) Networked development

## Critical succes factors
- Approach: non isolated approach: part of the concept
- manner to deal with inconsistency
- Tooling: use available data First (must be able to take on board reported input such as visual inspections)
- Must track execution !!
- Dont throw _preventive maintenance_ or _workorder optimization_ overboard
- JOINT PERFORMANCE DASHBOARD ! if you want a coordinated effort for a balance optimsiation of production, asset performance, product quality and cost, you better have a shared measure for these
- Make data relateable (tiem stamped performance data)
- Take on board wide breadt of newly available information without throwing the basis overboard
- Should not only integrate but also allow itseld to be intergrated
