# Energy storage

* Summary of available energy storage mechanisms, from [Pattison]:

|         mechanism        | requirements of system |
| -------------------------|------------------------|
| concentrated solar power | water                  |
| supercapacitors          | voltage control        |
| hydrogen                 | tanks & water          |
| pumped hydroelectrics    | large amount of water  |
| compressed air           | temperature & geography|
| flywheels                | short storage duration |
| batteries                | several..              |

* Energy can be stored at multiple levels:

| System level | Voltage range | Sites | Companies |
|--------------|---------------|-------|-----------|
| transmission level (maximally upstream) | 115-765 kV | central generation stations, transmission lines, transmission substations | | AES, Eos Energy Storage |
| distribution level | 4-69 kV| medium voltage distribution lines, distribution substations, commercial/industrial customers | |
| behind the meter (consumer/maximally downstream) | lower | home batteries, electric vehicles, laptop batteries, etc. | Tesla, Stem, Sunverge, Coda |
[Fitzgerald, 18][Fitzgerald]

* Storage maximally downstream offers the highest system-wide benefits because it has the most flexibility of use [Fitzgerald, 18-20][Fitzgerald]
* Economic value of various energy storage capabilities (note that this is theoretical and assumes no regulatory barriers, but is otherwise highly conservative):
![screen shot 2017-03-23 at 4 45 06 pm](https://cloud.githubusercontent.com/assets/454690/24274825/1fb9bf9a-0fe8-11e7-909d-481d782b3231.png)
[Fitzgerald, 22][Fitzgerald]

## Batteries
* Batteries can provide services to ISO/RTO's, utilities, and customers. For ISO/RTO's: energy arbitrage, frequency regulation, spinning reserve and non-spinning reserve, voltage support, black start. For utility: resource adequacy, distribution deferral, transmission congestion relief, transmission deferral. For customers: TOU bill management, self-consumption from PV, demand charge reduction, backup power [Fitzgerald, 3][Fitzgerald]
* Batteries providing multiple services (e.g. demand response + backup power) are much more worthwhile than batteries used for a single purpose– RMI estimates a single-use battery system is only 5-50% utilized. Several examples are given at [Fitzgerald, 6][Fitzgerald] [Fitzgerald, 5][Fitzgerald]
* A current regulatory barrier: DER's on the grid are often treated as either a sink or a source, but not flexible. CAISO is looking into changing that. [Fitzgerald, 8][Fitzgerald]
* For a residential load regulation battery pack to make economic sense (assuming stacked services but mostly keeping home energy use local to home solar), the up-front capital would have to be around $300/kWh or $1,111/kW to be cash positive without the tax incentive [Fitzgerald, 32][Fitzgerald]
* Home battery might need replacement every 7 years [Fitzgerald, 33][Fitzgerald]

### Characteristics
* Lithium-Ion batteries die out after ~1k cycles & are better to discharge only 70%; Flow can be used for 5-10k cycles, CAES for 10k+ with full discharge [Naam][NaamStorage]
* CAES (compressed air) batteries don't leak the way traditional Lithium-Ion batteries do. CAES batteries can be stored for years [Naam][NaamStorage]
* Battery performance is sub-par and degrades quickly. Lithium ion batteries lose power even when idle and their performance degrades over time and with temperature. Tesla engineers expect the car battery pack to degrade by as much as 30% in 5 years [Smil, 29][Smil]
* Flow batteries exchange negatively and positively charged fluids to create current– longer discharge cycles and longer lifespans, safer, more easily scaled capacities than Li-Ion [Maloney]
* Flow batteries can use expensive, corrosive, and/or toxic fluids (vanadium is market leader); on-site load to power pumps can be high [Maloney]
* Zinc-air batteries have a longer life span, greater safety and lower costs than li-ion batteries [Maloney]
* Li-ion might not be the most technically appropriate technology for grid storage, but its economies of scale might make it the most cost-effective [Maloney]

### In load balancing
* 1,280 MWh of battery storage added to the grid 2010-2017 [Maloney]
* Lithium-Ion (Li-Ion) batteries are dominant in the market, more than half of the battery storage added to the power grid 2010-2017. Sodium batteries are about 30% of the global grid storage market, flow: 7% [Maloney]
* Lithium-Ion batteries are in the 10-25c/kwH range (compared with 7c/kwH for natural gas) for the forseeable future, but this is not a whole accounting. Batteries are a load flattener, so we can use any existing & new generators more evenly + reduce need for peaker plants. This graph makes even the 25c/kwH price look plausible: ![](http://rameznaam.com/wp-content/uploads/2015/04/CA-Time-of-Use-Pricing-Model-400x134.png) [Naam][NaamStorage]
* Energy storage in large Lithium-Ion batteries: ![](http://rameznaam.com/wp-content/uploads/2015/10/How-Cheap-Can-Lithium-Ion-Batteries-Get-Energy-Storage-800x422.jpg) [Naam][NaamStorage]

#### Further reading
* [Battery storage in office/industrial buildings to load balance grid pull](http://www.ee.ucr.edu/~stan/papers/dac14_bat.pdf)
* [NREL's Battery Lifetime Analysis and Simulation Tool (BLAST) for behind-the-meter batteries](https://www.nrel.gov/transportation/blast-btm-lite.html)
* [North American Electric Reliability Corporation: Balancing and Frequency Control (technical document)](http://www.nerc.com/docs/oc/rs/NERC%20Balancing%20and%20Frequency%20Control%20040520111.pdf)
* [Expanded Metering and Telemetry Options Phase 2 Distributed Energy Resource Provider (DERP) Draft Final Proposal (2015)](http://www.caiso.com/Documents/DraftFinalProposal_ExpandedMetering_TelemetryOptionsPhase2_DistributedEnergyResourceProvider.pdf)
* [SCE's Preferred Resources Pilot (2016)](http://www.caiso.com/Documents/DraftFinalProposal_ExpandedMetering_TelemetryOptionsPhase2_DistributedEnergyResourceProvider.pdf)
* [The Integrated Grid: Realizing the Full Value of Central and Distributed Energy Resources](https://www.epri.com/#/pages/product/000000003002002733/)
* [The Future of US Electric Distribution (2012) EEI](http://gridarchitecture.pnnl.gov/media/white-papers/2012%20Jul-Future%20of%20Electric%20Distribution.pdf)
* [What the duck curve tells us about managing a green grid (CAISO, 2016)](https://www.caiso.com/Documents/FlexibleResourcesHelpRenewables_FastFacts.pdf)
* [21st century electric distribution system operations](http://smart.caltech.edu/papers/21stCElectricSystemOperations050714.pdf)
* [2018 Demand Response Auction Mechanism (DRAM) - currently active](http://www.sdge.com/procurement/2018-demand-response-auction-mechanism-dram)
* [Energy Storage for the Electric Grid: Benefits and Market Potential Assessment Guide (Sandia, 2010)](http://www.sandia.gov/ess/publications/SAND2010-0815.pdf)
* [Demand Response 2.0, A Future of Customer Response (DoE, 2013)](https://s3.amazonaws.com/fonteva-customer-media/00Do0000000Yi66EAC/DR%202.0%20A%20Future%20of%20Customer%20Response.pdf)
* [ISO basics, a CAISO how-to guide for getting interconnected](http://www.caiso.com/Documents/ResourceInterconnectionFAQs.pdf)
* [Demand Response User Guide (CAISO, 2016)](http://www.caiso.com/Documents/DemandResponseResourceParticipationGuide.pdf)

{% include "../../BIBLIOGRAPHY.md" %}
