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
* Battery storage in office/industrial buildings to load balance grid pull: http://www.ee.ucr.edu/~stan/papers/dac14_bat.pdf

{% include "../../BIBLIOGRAPHY.md" %}
