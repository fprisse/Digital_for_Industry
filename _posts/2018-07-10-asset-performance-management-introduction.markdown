---
layout: "post"
title: "Asset Performance Management Introduction"
date: "2018-07-07 18:37"
---

## Introduction
### What is it ?
Asset performance management is a set of capabilties. Namely: data capture, integration, visualization and analytics. Tied together with the **primary goal of optimising reliability and availability of physical assets** and/or reducing maintenance cost. However as time and technology progresses we have come to expect systems and application to not only extract from it's ecosysystem. We today expect APM methodology and solutions to contribute to the **optimisation production and product quality too**. Thus forming an intergral part of what we at Capgemini have dubbed the Digital Factory Platform.

{IMAGE: Data, Metrics and Reporting Graph}

Core of the concept is creating a comprehensive view across operations and maintenance, by making use of the same base information and performance metrics. Rather than reporting to each other.

This does not require fully Integrating production management and asset management in terms of business processes and organization. APM when done right does however fascilitate further intergration of activies in the production and nmaintenance realm.

| Benefits |
| --- |
| Maximize output. Fewer unplanned disruptions due to equipment breakdowns increases your OEE and means you can consistently meet production targets and achieve or exceed revenue goals.|
| Optimize maintenance cycles. Move toward predictive and prescriptive maintenance strategies to address known sources of failure and performance degradation without driving up costs due to just-in-case preventative part replacements. |
| Improve root-cause analysis. Advanced analytics, data mining and data visualization tools enable engineers to identify real root causes and develop ideal corrective action plans faster and more effectively.|
| Maintenance Cost:    |
| Help comply with regulations: EG: ISO 55001 |
| Longer interval with confidence: ... |


APM:
- includes the concepts of condition monitoring, predictive forecasting and reliability-centered maintenance (RCM).
- Is a manner to run maintenance operations as an intergrale part of your daily (prodution) operations
- It is not about *switching* from preventive maintenance to condition monitoring but it aims to add **sensory and operational data** to the equasion.

{IMAGE:  How APM is not just the next step in the Maintenenance Ladder: USE BELOW TABLE }

| **Strategy**         | **Description**                                              | **Asset Attributes**                                         |
| -------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Reactive             | Run to failure, and then repair                              | Failure is unlikely, easily fixed/replaced, or non-critical  |
| Preventive           | Service in a fixed time or cycle interval                    | Probability of failure increases with asset use or time      |
| Condition Monitoring | Alerts for bad trends or other rules-based logic using a single data value | Assets where a component failure cascades into big $ losses  |
| Predictive (PdM)     | Equipment specific algorithms or machine learning. Multivariable | Critical assets where unplanned downtime has business impact |
| Prescriptive         | Model and knowledgebase identifies an issue and what to do for repair | Complex assets requiring advanced skills                     |

**History:** The methodology and terminology originates mainly from asset intensive continuous process industry with a homgenous product such as upstream oil & gas / electricity production and utilities. Industries Where the uptime component was the most important of the OEE equasion.

```
NOTE:  Maybe BRIEFLY DESCRIBE THE EQUIVALENT OF DOING THIS FROM AN PRODUCTION OPERATION POINT OF VIEW
EG: making production and quality a part of the asset management dashboard but also by using production data on board in estimating the likelyhood of equipment failure
```

|   | In context with other Maintenance and Asset Management systems |
| --- | --- |
| APM | APM is designed for data drive decision making and planning to realize safe, reliable, and efficient operation of equipment and  infrastructure |
| EAM | EAM is designed for maintenance execution. A two-way link between the two is key for 1) Using maintenance execution history to gauage likelihood of failure 2) To trigger the creation or re-scheduling of work-orders |
| AIP | Asset investment planning (AIP) AIP takes data on asset condition, maintenance costs, criticality,  budgets and risks, to produce a CAPEX forecast for asset replacement or decommissioning |


### Why is it good ?
In Capital-intensive industries success is for the greater part defined by the balancing act of risk of undesirable events and the cost of preventing them. Today most organizations rely on preventive maintenance regimes and basic monitoring (mostly alarm systems provided by OEM's) for realizing safety, uptime and reliability at acceptable cost. Based on failures specific components may be prioritized for overhauls. Some do even adopt the maintenance and inspections intervals to take into account deviations in load & runtime based on reports provided by operations.

Asset performance management is first and foremost about doing the above in a more data-drive manner and making use of advanced analytics to improve failure-mode modeling to improve maintenance regimes.

Furthermore: accurate determination of the likelihood of failure is possible by structurally broadening the scope of real-time data that is taken into account such as:
- Get load and runtime data from the machines
- Add raw material and product specifications
- Relate product quality reporting to machine performance

When well translated into component specific agenda's this allows for (on average) longer intervals for inspections and overhauls AND prevention of undesirable events (failure, contamination or quality issues) by advancing maintenance work when models indicate a heightened likelihood of failure

## How does APM work ?
APM is not one *thing*. APM is a set of well **orchestrated capabilties, technology and procured services**

**A comprehensive set of metrics (cross discipline)**
{Image: Overarching KPI tree: USE CCT-TREE AS BASIS}

| functional silos | Key Metrics | Outcomes |
| --- | --- | --- |
|  operations, maintenance and quality management | uptime, mean time to repair (MTTR), asset longevity, cost, quality/yield and safety | revenue, margin, customer satisfaction, and work-in-process (WIP) inventory  |

**Data Model: Collect and Make Available**
- Cross discipline:
  - Maintenance: WO records, Regimes, Inspection reports
  - Operations: Performance, Raw Materials, Product Specs.
  - Quality Management: Quality reports, Rejects
  - Machine data eg. RPM, Amps, Vibration
  - Extra sensor data
- Provided in both event as stored format
- Environmental Data

**Static data repository** : Shared or synchronized
- Asset tree
- As-built documentation
- Asset dependency tables*

**Predictive Analysis Workbench**
- Tools to build prediction models
- Correlation, Regression & Clustering

**Advanced Analystics Capability**
- Inhouse Training
- Procured Specialist Support

**Asset Health Dashboard**
- Display geographic dispersion of assets
- Health: Likelihood of Failure (incl. forecast)
- Criticality: Impact of undesirable event

**Reporting and Publishing Tools**
- Customizable Templates
- Web-based & Interactive
- Distributable format

**Model implementation tool** (automated analysis & alarms)
- Database: Asset Health (LOF)
- Act on Events: Alarms
- Create Events: Workorders & Re-scheduling
- Attribution of Alarms to relevant discipline

**Connectivity**
- Enterprise systems
- Machine Bus
- External Sensors (IOT)
- EAM (Maintenance planning & execution)
- Performance mgt Systems (OEE, Product data & Quality)
- Environmental data (API)

Two phased approach:
1st: functional improvement making use of broader data set (improve maintenance taking operating paramaters into account) and vice versa: (improving the operating window by making use of asset health information)

2nd: Intrated view and intergtaion of opartional and maintenance crew


### Highlight: Asset health Dashboard
The end result is an overall overview (timeline) that shows the development of the overall likelyhood of failure (and other undesirable outcomes)
- considering the planned preventive work and production
- A correction for Alarms, Operator reports, Inspections report
- A coorection for condition monitoring data

{IMAGE: Example of Asset Health Dashboard}

## Extra: IOT Agenda:
As the APM dashboard provides such a broad view it is the most appropraite starting poin for pinpointing where adding datasources have the most value. Thereby setting the priorities fot an IOT agenda based on a balanced view upon opeartional and asset management priorities

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
- Dont throw preventive maintenance or workorder optimalistaion overboard
- JOINT PERFORMANCE DASHBOARD ! if you want a coordinated effort for a balance optimsiation of production, asset performance, product quality and cost, you better have a shared measure for these
- Make data relateable (tiem stamped performance data)

### Capgemini end to end Asset Performance Mgt Appoach & Suite

Governance and consultancy
- Platform and Software selection
- Bespoke Data Model
- Cross discipline alignment of logic and Metrics
- Asset registration (application and support)
- Risk dependency calculations
Impementation & Support
- Platform and Software
- Bespoke Applications
- Inspection & Reporting apps
Connectivity & Sensoring (sogeti)
- Machine Connectivity
- Sensoring
Advanced Analysitcs
- Training &  Support
- (complex) Failure mode modeling

{IMAGE: Use Picture e2e from Stephane Blanda}

## EXECUTIVE SUMMERAY (DRAFT)
1) Shared metrics and measures (agreed optimal outcome)
2) Intergal availablitly of indormation : note: sensory & environmental data is relatively easy, the hard part is getting operator interventions/ maintenance activities and quality data in 1) ASSET HEALTH DASHBOARD MUST ALOOW FOR THIS 2) SMART SOLUTIONS FOR GETTONG DATA IN (SMART KNOB AND REPORTINMG APPS)
3) Data must be relateable from the start (product, raw materials, assets/machines, quality data)
4)

Note: score is constantly bein influenced by the reliabilty of other parts of the assets
The need for indexed contribution (and a mechanisme to review it)

### Wat is nu de grote crux ?

1) Samen naar hetzelfde kijken (data and metrics)
2) Agreed Asset dependency metrics !! make good description. Example rail: No# of Impacted travelers
a simple example from the rail industry, a failure of a switch in the track at your your national rail hub has a far more negative impact on the overall performance that one that only serves 4 shorthaul trains a day.

3) Adaptive regimes (niet wait till it is all about to fail) (dont throw overboard your achievements)
4) Het gaat niet per se over nieuwe data, het gaat over de structuur en het mechanisme om data te kunnen combineren
5) Must be able take on board intervention & prodcution data (early warning is not good enough) you need that thing that you can improve upon as part of your data set. Allow for early warning and impriovemetn measures

- Unified reporting
- Unified Staus Quo !! Relateable
- Predictive information

## SCRAP:
Wat kan er allemaal als je dat doet ?

Preventive maintenance
Preventive maintenance schedules inspections and/or repairs are typically based on calendar time, run time, or cycle count. (please realize that many asset owners do not have this in place in a proper manner)

Predictive Maintenance: (conditon monitoring  : based on likelihood of failure: broadening the set of parameters with continuously (or in short interval) monitored datapoints such as vibration. tension, temperature out of bounds operating window (RPM, weather) : TO tweat the intervals as described above to be asset specific. In its simplest form: a well organized operator- inspection scheme

Inspections for stationary equipment (piping, presure relieve valves, and heat exchangers) visual, ultrasonic, oil analysis or corrosion typically used
Process data with trend charts, out of bound registration of rpm / torque / presure etc
Sensory data for manupalive equipment (rotary, curing etc) vibration / amp curve etc.
