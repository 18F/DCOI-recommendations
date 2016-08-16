```
Note: this language does not represent definitive contract language and should be reviewed by each agency procurement and contracting officials.
```

--------------------------------------------------------

## General

All data center infrastructure and services, including contracts for third-party, shared-service, and cloud data centers and services, will be managed in a manner consistent with FITARA and other OMB Memorandum including M-15-14, and M-16-19. Contracted services will be responsible for implementing and measuring progress toward meeting the agency goals. These optimization, cost-savings, and closure metrics and goals apply to all data centers at agency facilities.

## Inventory

Private sector-provided cloud services are not considered data centers for the purposes of the full reporting requirement (e.g. PUE), but must continue to be included in inventory submissions in order to support agency required quarterly submissions to OMB and other metrics (e.g. virtual system inventory) continue to be required to meet security standards such as FISMA.

**Inventory and Configuration**: The contractor shall provide facilities, system, energy, and environmental inventories and information to support ongoing FISMA and FITARA reporting requirements. This includes information operated by support staff as well as those that may be acquired (e.g. cloud or cross-agency shared service - although not all information may be required) in the execution of performance. 

At a minimum, required reporting for contractor operated facilities elements include:

    * *Type of Facility* - e.g. GOCO, Cloud, Shared Service, Telecom, 

    * *Classification Tier* - Facilities shall be categorized into two groups: tiered and non-tiered; tiered being defined as those that utilize each of the following: 1) a separate physical space for IT infrastructure; 2) an uninterruptible power supply; 3) a dedicated cooling system or zone; and 4) a backup power generator for prolonged power outages, all other facilities shall be considered non-tiered data centers.

    * *Services Provided* - for example print, email, hosting, etc. This is critical as data centers containing **only** print servers that were previously reported as “closed” shall remain classified as closed data centers in agencies’ data center reporting and the agency must ensure this condition continues to be met. 

    * *Energy Measurements* - measurements shall be provided on energy usage (both facilities and system consumption) to allow the agency to meter and monitor energy consumption and efficiency including:
        - Total gross floor area in tiered data canters that have power metering
        - Total gross floor area in tiered data canters without power metering
        - Percent of data centers fully equippet with automated monitoring [Automated Moitoring]
        - Total Energy Used, including by facilities (e.g. cooling, lighting, etc)
        - Total Energy Utilized for IT Equipment
        - Total Server Count (by physical server)
        - Total Virtual Server Count (by OS)
        - Average Server Utilization [Server Utilization]
        - Total Active Rack Count
        - Total Racks

    * *Cost Measurement* - the contractor is required to report cost / spending levels for the datacenter as a whole (i.e. all facilities, power, and equipment costs) and spending should also be broken down to coincide with practices such as [Category Management](http://www.gsa.gov/portal/content/246415).

    * *Enviornmental Factors* - the contractor shall provide similar metrics in order to support agency requirements under [EO 13693](https://www.gpo.gov/fdsys/pkg/FR-2015-03-25/pdf/2015-07016.pdf) including green house gas emissions, water consumption (measured in gallons per gross square foot), and vehicle fleet information (number and fuel type).

Only the Server Utilization & Automated Monitoring optimization metric shall apply to nontiered data centers. High-performance computing (HPC) nodes can be excluded from calculations of Virtualization and Server Utilization & Automated Monitoring

For non-contractor operated facilities, such as cloud or shared services, that may be acquired in the support of services to the government, at a minimum the following must be reported:

    * Name of Provider
    * Acquisition Method, including all relevant contracts
    * Point of Contact
    * Security Authorization
    * System Inventory (by OS)
    * Cost / Spending

    For an example of the data call format and fields please review the [sample inventory](sample_inventory_schema.csv)

All information should be provided in machine readable formats, such as CSV or JSON, and be delivered electronically (not via printed documentation).

## Efficiency Targets

To the extent permissible under the Federal Acquisition Regulation (FAR), the contractor shall report quarterly average PUE of the facility to the contracting agency, except where that data center’s PUE is already being reported directly to OMB or GSA through participation in a multi-agency service program or via existing vehicles. PUE reporting is not required for cloud services

In addition, consistent with agency implemention instructions, contractors are also required to ensure that existing tiered data centers achieve and maintain a PUE of less than 1.5 by September 30, 2018. The agency CIO will evaluate options for consolidation or closure of existing data centers in which a PUE target of less than 1.5 is not cost-effective, such as through transition to cloud services or migration to inter-agency shared services data centers.

Effective immediately, all new data centers must implement energy metering capable of measuring PUE and must be designed and operated to maintain a PUE no greater than 1.4, and are encouraged to be designed and operated to achieve a PUE no greater than 1.2.

The agency will measure progress for this requirement on a quarterly basis. 

## Automation

To the extent permissible under the FAR, the contractor must include automated infrastructure manaement requirements for new and existing data center service. The contractor shall install and operate automated energy metering tools on behalf of the agency and and shall use these to collect and report energy usage data in their data centers. Contractors are required to install and monitor advanced energy meters in data centers by September 30, 2018.19

Energy metering tools shall enable the active tracking of PUE for the data center and shall be installed in all tiered federal data centers, including those operated by industry on behalf of the government, by September 30, 2018.20 

## Key Personnel

All existing and new data centers shall have at least one personnel certified as a Data Center Energy Practitioner (DCEP) assigned to manage performance of each facility.
