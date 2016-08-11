![logo small][logo-s]

# 18F DCOI Review and Recommendations 

## Purpose
This document captures the output from a single specific review and partner recommendations, regarding OMB's *Data Center Optimization Initiative* (DCOI) [OMB M-16-19](https://www.whitehouse.gov/sites/default/files/omb/memoranda/2016/m_16_19_1.pdf). Although it may not represent a complete or comprehensive approach for all agencies, the hope is that this document can inform continued iterations of agency approaches.

### Background

In February 26, 2010, the Federal Chief Information Officer established the *Federal Data Center Consolidation Initiative* (FDCCI) in [a memo](https://www.whitehouse.gov/sites/default/files/omb/assets/egov_docs/federal_data_center_consolidation_initiative_02-26-2010.pdf) to agency Chief Information Officers, indicating the need to reduce the footprint and environmental impact of legacy data centers. In 2012, FDCCI [was updated](https://www.whitehouse.gov/sites/default/files/omb/assets/egov_docs/cio_memo_fdcci_deliverables_van_roekel_3-19-12.pdf) to provide further implementation guidance, including [FAQs](https://cio.gov/wp-content/uploads/downloads/2012/09/FAQ-May-2012-Update-V1.pdf) and an updated schedule of deliverables under the FDCCI. Under FDCCI initial inventories of federal data centers were taken, and agencies were required to publicly provide regular reports on their consolidation plans and progress. 

Most recently, on August 1st 2016, OMB released updated guidance for federal data center consolidation activities under the updated term *Data Center Consolidation Initiative* (DCOI) that establishes guidance, which supersedes previous FDCCI guidance as amended. 

### Assessments

The DCOI guidance confirms and builds upon other CIO responsibilities, particularly those outlined under the Federal Information Technology Acquisition Reform Act (FITARA) and further clarified through [OMB Memorandum M-15-14: Management and Oversight of Federal Information Technology](https://management.cio.gov/implementation/#OMB-Memorandum-M-15-14).

The highlights outlined below do not represent comprehensive guidance on FITARA and DCOI implementation, but rather point out distinct key areas and activities for CIO's to initiate in order to build a stronger foundation for delivery upon those goals. In addition, other Executive Orders, including EO 13514 - since revoked and superseded - by the publication of [EO 13693](https://www.fedcenter.gov/programs/eo13693/).

From our assessment, under DCOI, agencies should focus on the following key execution items:

* **Update Inventories** - agency inventories and definitions may have changed since DCCI reporting, and an accurate assessment of both of data centers and non-datacenters, is critical for proper planning and management.

* **Revise Contracts** - number of contractual updates may be required to support areas such as:
    * *Metrics Reporting* - Agencies are required to provide a number of environmental and efficiency metrics, including power and water consumption, and existing operations may need to be updated to support measurement and reporting. 
    * *Key Personnel* - DCOI states that all *"existing and new data centers shall have at least one certified Data Center Energy Practitioner (DCEP) assigned"*, which may necessitate contractor staffing if the role cannot be fulfilled by a federal point-of-contact
    * *Ongoing Reports* - ensure contractors submit timely reports of their environmentally certified purchases

    Language updates should also be considered in accordance with M-15-14, EO 13693, and the FITARA implementation guidance.

* **Confirm Spending** - Enterprise Architecture (EA) and Capital Planning and Investment Control (CPIC) track and submit "Steady State" (SS) vs. "Development, Modernization, and Enhancement" (DME) and M-16-19 explicitly states that *"Any data center initiation, significant expansion, or migration project that receives Development, Modernization, and Enhancement (DM&E) funds in fiscal year 2017 and beyond must immediately implement automated monitoring and management tools"*.
 
* **Review Reporting** - Executive Order 13693 and DCOI both require agencies to monitor a number of environmental and efficiency metrics that may require additional activities and agencies should be prepared to establish the components necessary to deliver on these metrics.
    - Sample metrics include: Gross Floor Area, Energy Consumption, Power Usage Effectiveness, Virtualization Ratio, Server Utilization, Facility utilization, Server Utilization, Automated Monitoring Adoption, Water Consumption, Fleet Efficiency, Greenhouse Gas Emissions, Compliance with the adoption of certified products such as EnergyStar, WaterSense, Safer Choice, SmartWay, etc., and Ratios of Renewable Energy Utilization

* **Establish Automation** - effective and efficient delivery at scale requires deployment of automated infrastructure management and reporting systems. These goals coincide with CIO activities to develop agile and DevOps capabilities, and should be met through:
    - Replace manual collections and reporting of systems, software, and hardware inventory with automated monitoring, inventory, and management tools, including those for reporting virtualization and utilization metrics
    - Install automated energy metering tools and to collect and report energy usage data in their data centers

    Both of these capabilities are encouraged and explicitly required by DCOI and EO 13693.


### Recommendations

Based on the earlier Assessment, agencies should initiate the following activities:
* **Before August 31st** - Review the reporting instructions and schema OMB has provided agencies and take steps to ensure the requisite public URLs are available, ideally secured according to [M-15-13](https://www.whitehouse.gov/sites/default/files/omb/memoranda/2015/m-15-13.pdf), these URLs include:
    -  \[agency\].gov/digitalstrategy
    -  \[agency\].gov/digitalstrategy/datacenteroptimizationstrategicplan.json
    -  \[agency\].gov/digitalstrategy/FITARAmilestones.json

    Note, the government maintains a list of [Public FITARA Implementations Plans](https://github.com/WhiteHouse/CIOmanagement/blob/gh-pages/pages/plans.md) via [github](https://github.com/).

* **Before August 31st** - Identify an agency point-of-contact to engage with OMB as to DCOI targets, that are anticipated being published by OMB on August 31st, 2016. This individual should work with the *Chief Sustainability Officer* appointed under EO 13693.

* **By August 31st** - Complete an inventory of data center and non-data center environments including fields such as location, point-of-contact, footprint - (physical space as well as physical server count), power consumption, etc.
    - Note, in conjunction with OMB, agencies may exclude data centers that are *"physically inseparable from non-IT hardware ... and that perform a specific, non-standard set of tasks"*.

* **By October 1st** - Publish, according to FITARA and DCOI, a strategic plan and milestones describing the agency's consolidation and optimization strategy for FY2016, FY2017, and FY2018. including various year-by-year calculations and 
    - At a minimum, 5 achievable milestones per fiscal year should be identified
    - These milestones should be updated `quarterly`
    - Milestones should be reviewed in regular PortfolioStat sessions with agencies’ OMB desk officers.

### Next Steps

1. **Review Previous Plans** - although previous DCCOI commitments may be largely superseded, a background in previous strategy would limit redundant discovery, in addition DCOI activities are required to align with FITARA strategic planning and milestones.

2. **Update Inventories** - review and update datacenter and non-datacenter (e.g. telecom rooms) inventories according to the new DCOI definition, not even if environments are excluded they may still be required for reporting so agencies should not limit inventories to "data centers only".

3. **Deploy Base Reports** - agencies should review publishing and schema reports and make `blank` reports available at prescribed locations. In addition to establishing baseline communication, these `blank` reports will enable agencies to iteratively publish information as it becomes available.

4. **Modernization Commitments** - many agencies already have a number of IT transformation activities underway, such as BYOD and cloud computing, that will help assist in meeting these goals. Continued commitment to these initiatives, as well as incorporating them into FITARA and DCOI reporting will strengthen and accelerate the transformation benefits. Strategic planning should become routine elements of CIO management activities and as milestones are identified and updated they can be published according to the reporting requirements.

[logo-s]: https://18f.gsa.gov/assets/images/18F-Logo-S.png

