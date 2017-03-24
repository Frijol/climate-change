# Infrastructure

## How the American energy grid works
* An excellent introduction to terms and organization of the electric grid can be found in [Caspary].
* Current grid paradigm: ![screen shot 2017-03-23 at 2 12 10 pm](https://cloud.githubusercontent.com/assets/454690/24270548/d479a0aa-0fd2-11e7-90cd-f02d92aa5ff4.png) [Hiskens, 4][Hiskens]
* Modern grid has 99.97% energy availability reliability in the United States [EPRI, 9][EPRI]
* Transmission systems mostly take place through organized markets (ISO's/RTO's). Other agreements are often called bilateral (2-way agreement between energy supplier and distributor) [Caspary, 13][Caspary]
* Current American grids: Texas (ERCOT), East, and West. They are separately managed. [Chabot]
* The United States has very few HVDC lines. "The cost of high voltage DC (HVDC) transmission lines is roughly 1 cents per kwh for 500 miles, or 1.5 cents per kwh for 1,000 miles transmitted. Over 1,000 miles, an HVDC line may lose 5% or so of the electricity it transmits." [Naam][NaamWind]
* ![](http://rameznaam.com/wp-content/uploads/2015/08/Cost-of-AC-and-HVDC-Transmission-Lines-From-HandlemanPost-800x544.jpg) Cost of transmission lines by type & voltage [Naam][NaamWind]
* FERC is officially voluntary, 1/3 of US transmission is outside of FERC and RTO's (mostly Texas) [Caspary, 7-8][Caspary]

### Load profiles
* Trends in when energy demand is high/low in the United States: ![screen shot 2017-03-23 at 2 12 44 pm](https://cloud.githubusercontent.com/assets/454690/24270554/d812fe6e-0fd2-11e7-9be9-8a7590237177.png) [Hiskens, 5][Hiskens]
* [Hiskens] is an excellent engineering information source for how frequency is kept within bounds on the grid

## Changing the system
* It takes ~10 years (software) ~18 years (hardware) to go from research, through development and demonstration, then regulation, to roll out new operational technology to the grid. It's a waterfall-style development structure of sequential operations. [More than Smart, 15][More than Smart]

### Transition in major energy sources
* Energy transitions are slow by nature. Oil took 50 years to climb from first commercial production to a 10% market share, and we continue to depend on prior dominant energy forms: coal, wood [Smil, 138][Smil]
* Quick energy transitions destabilize economies. Any new technology adoption requires a heavy up-front investment (estimated by Smil at at least $3 trillion). This is needed both in the energy sourcing and transport infrastructures, and in the “primary movers”, the major users of the new energy (such as cars). Primary movers take years to become efficient [Smil, 138][Smil].
* Quick changes in primary energy sources leaves less time to build infrastructure and primary movers. Transition also requires people who had invested in the old system to write off of that infrastructure investment [Smil, 142][Smil]
* From data up to 2008, we are not currently transitioning off of oil. In 2008, energy from new renewable energy sources was less than 2.4% in the United States. [Smil, 135][Smil]

## Distributed Energy Resources (DER)
* What is DER and how does it work, from CAISO: https://www.caiso.com/Documents/InterconnectionOptionsBasics.pdf
* The current power grid is not set up to support distributed power; it works through a few sources providing great amounts of energy. [Victor]
* 2014 report makes careful distinction between the many, many DER *connected* to the grid but not *integrated with* the grid – a situation which can cause grid instability if not corrected [EPRI, 7][EPRI]
* Grid and DER can be complementary, several reports stress that they should not be phrased as 'in competition'. DER can efficiently supply the grid with (in aggregate) a stable, cost-effective power source. Grid is a distribution and storage mechanism that can ensure reliability of energy delivery by intelligently routing supplies to demands [EPRI, 7][EPRI]
* Power transmission lines are expensive and inefficient - local solar & wind reduces cost and energy production need [Lovins, 72][Lovins]

### In California
* California is generally considered the pilot/leader for the United States on DER
* Vision for DER in California: ![screen shot 2017-03-22 at 4 12 55 pm](https://cloud.githubusercontent.com/assets/454690/24224796/76d47bf4-0f1a-11e7-817a-cf477c60c9d4.png) [More than Smart, 17][More than Smart]
* There is an effort underway to better integrate DER within CAISO. Guiding principles include work to evolve the grid to an open network platform that is based on energy nodes with high transparency and resiliency. Pieces of the strategy include flexible technologies that should be able to interoperate with future unforeseen innovations and better align timing of power resources with customer needs. [More than Smart, 16][More than Smart]
* P-nodes, or pricing nodes, are a pricing structure for distributed energy resources. Essentially, a price is set by balancing the supply and demand at each point where two wires cross. As of 2015, there were 4,900 of these in California. [StJohn]

### In Germany
* Germany's DER adoption was spurred in part by EEG but didn't pre-plan to integrate the new distributed resources with the grid– so they have been learning how to integrate the existing already-connected resources [EPRI, 12][EPRI]
* In initial rollout, PV generators were not required to respond to grid operating requirements or support the grid (with e.g. frequency control or demand response) [EPRI, 13][EPRI]

## Siting: colocation of wind + solar
* Colocation of wind & solar might make sense for renewables because they have ~opposite peaks. It also lets both farms use the same infrastructure [Cuff]
* Colocation of wind and solar in practice [Pattison]: ![https://vtechworks.lib.vt.edu/bitstream/handle/10919/54690/3_Pattison_etal.pdf?sequence=2&isAllowed=y](http://i.imgur.com/iCQ3M4l.png)


{% include "../../BIBLIOGRAPHY.md" %}
