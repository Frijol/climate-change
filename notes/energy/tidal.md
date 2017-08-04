# Tidal Power

Tides cycle twice a day, consistently creating a harvestable energy source at the coast– which is where the majority of the world's population can be found. However, tidal power has not taken off as a major renewable resource. Partly, this is because the technology is still considered early-stage– and thus both expensive and risky. Partly, it's because not all tidal flows are created equal– greater tidal flows can be found in Norway, Alaska, New Zealand, and Scotland than in other parts of the world.

*Questions: Why are those sites best– what is unique about their terrain? What is the exact argument for useful vs. not useful globally?*

Most analysts discount tidal power as a solution to global renewable energy, citing tidal changes that are too small to be useful at population centers.

There are two main implementations of tidal power. The older technology is a "tidal barrage", essentially a hydroelectric dam designed to flood an area as the tide rises, and slowly release the held water as the tide recedes. This is effective at generating power from existing technologies, but necessarily changes the environment (particularly disrupting the intertidal zone).

The newer tidal technology is an underwater turbine called a tidal turbine, essentially a small, stout wind turbine analog. It turns with the in-and-out flow of the tides. A single tidal turbine generates much less electricity than a tidal barrage; the design intentionally leaves most of the water flow (and thus harvestable energy) undisturbed. One solution to generate more power is by creating "tidal fences", turbines side by side to multiply the energy generated.

I posit that another approach to tidal turbines is to deploy them in smaller coastal communities– towns of a few hundred, in the remote areas which are most appropriate for tidal power from the perspective of tide height. These towns are often highly energy-dependent on expensive imported oil used to generate electricity locally; due to the high price of existing energy and potentially low expense of one or two tidal turbines, there is potential for greater energy independence and cost savings for residents.

## How it works

- Major methods are tidal barrage (essentially a hydroelectric dam: open for inflow, close & run generator on outflow), tidal stream generator (underwater turbine), and dynamic tidal power (not defined but perhaps similar to wave mechanisms?) [Maehlum]
- Tidal stream generators do not generate the high power that tidal barrage can, but are typically less environmentally destructive [Helston]
- Peak-to-trough amplitude of tides would be theoretically ~1m due to solar + lunar gravity on a perfectly fluid Earth. We see more extreme tides (e.g. 4m in Puget Sound) where there are geographical restrictions or shallower water. In an _inlet_, water has to _flow_ in & out to accommodate the tide change [Murphy-tides]

### Tidal harvest mechanisms
* Tide mill: a medieval technology where tides push water up an estuary into a retaining basin; sluices direct the draining water through a run-of-the-river waterwheel to turn a grindstone [Charlier, 80][Charlier]
* Tidal power plant (TPP): a tidal barrage using one or more basins. Single or double effect (can power on ebb tide, flood tide, or both). Might or might not have pumping to even out flow across tides. Uses bulb, straflo, or other turbines [Charlier, 80][Charlier]
* Tidal stream/tidal current: uses the horizontal movement (flow) of tides rather than the vertical up & down movement [Charlier, 80][Charlier]
* Pulse stream: A converter uses a pair of hydrofoils oscillating across the flow of the tide, useful to harvest tidal energy in shallow water. There's a 100kW prototype in progress. [Charlier, 80][Charlier]
* Gorlov: a tidal power scheme using a helicoidal turbine that needs no dam. He works at Northeastern University in Boston [Charlier, 80][Charlier]
*

## Tidal barrage

- Energy harvest can be ebb (high tide is trapped in, allowed to outflow through turbines), flood (high tide is trapped out, allowed to inflow through turbines- less popular than ebb because it reduces the size of the basin, impacting shipping and the environment), or two-way (both, with a smaller hydrostatic head & thus a gentler peak generation over more time). [O Rourke, 4][ORourke]
- Essentially a hydroelectric dam where sluice gates create the hydrostatic head, thus generating a head differential which can be harvested
- Tidal barrage functions best in inlets/similar places where the water can be trapped and tidal amplitude is high [Murphy-tides]
- Double basin tidal barrage: ebb system where some of the electricity generated is used to pump water into a second basin & thus save generating capacity for when it is needed. Economically unfeasible (in 2009) because of generator inefficiencies and higher construction costs [O Rourke, 5][ORourke]
- Tidal barrage power calculations: P=ρFgh, where ρ = 1000 kg/m³, g = 10 m/s² (surface gravity), F is the flow rate of water in (m³/s), and h is the height of the water behind the dam. **h** is very small in a tidal installation compared with river hydroelectric (often 200m+). Accounting for timing (outer water has to be higher to create inflow, so you can't harvest the whole tide), ideal power is P = (1/8)πρgAH²/T, where A is the area impounded, H is the peak-to-peak tidal amplitude, and T is the period (about 12 hours) [Murphy-tides]
- UK is interested in taking a lead with tidal power [Helston]

### Turbine design

- Bulb turbines incorporate the generator-motor unit with the propellor. A drawback: because the whole unit is in the flow of water, maintenance is difficult. [Klossner, 20][Klossner]
- Rim turbines incorporate the generator in the barrage unit, perpendicular to the blades [Klossner, 21][Klossner]
- Tubular turbines are incorporated at an angle so that the shaft between turbine and motor allows the motor to be above the turbine, allowing for maintenance [Klossner, 21][Klossner]

## Tidal stream generators

- Essentially an underwater turbine in a tidal current
- Estimation of extractable power (in W/m^2): Px = 1/2u * w * Ks * Kn * V^3 = 0.3 * w * V^3 where u is the efficiency factor (0.25), Ks is the velocity profile factor (0.424), and Kn is the spring/neap tide factor (0.57), and w is the fluid density in kg/m^3 [Charlier, 144][Charlier]
- Tidal fences/tidal farms: a row of turbines through which water flows [Helston]

### Siting

- At least 7m tidal difference [Helston]
- Ideal flow rate is 7-11 kmh [Helston] 9+ kmh suggested in [O Rourke, 14][ORourke]
- Stable underwater site for installation [Helston]
- Typically sunk 20-30 meters, anywhere with a strong tidal flow [Helston]
- Environmental disturbances should be minimal [Helston]

### Turbine design

- Two styles: horizontal axis (rotation of blades is parallel to the flow of water) or vertical axis (rotation of blades is perpendicular to the flow of water) [O Rourke, 8][ORourke]
- Simplest design: blades on a hub connected to a gearbox, connected to a generator. Generated electricity is transmitted to land with cables. [O Rourke, 9][ORourke]
- Support structure: three main types. Gravity structure: a large mass (concrete + steel) steadies the turbine. Piled structure: steel or concrete beams pin the turbine to the seabed. Floating structure: turbine is moored to the seafloor (often with wire or chains) and held in position with a downward pointing vertical beam [O Rourke, 9][ORourke]
- Must be able to generate on both ebb and flood (a moving turbine is better at withstanding structural stress than one held still/not generating) [O Rourke, 8][ORourke]
- Water is ~800x denser than air, so turbines are sturdier than wind turbines, with smaller diameters to generate the same power (10-15m rotor diameter can produce 200-700kW) [Helston]

### Technology readiness

- Still in demonstration phase (2011) [Helston]
- As of 2009, main research focused on work reliability of the technology [O Rourke, 9][ORourke]
- There has been a dedicated test site in operation at the European Marine Energy Center (EMEC) in Orkney, Scotland since 2005 [O Rourke, 9][ORourke]
- Major challenges as of 2009: installation, maintenance, electricity transmission, loading conditions, environmental impact [O Rourke, 15][ORourke]
- If transmission distance is long, higher voltage transmission is needed. Ideally, there would be no transformers below sea level, so generators should run at high voltages [O Rourke, 15][ORourke]
- In a calm Puget Sound test at peak biofouling, it was found that an optical port could be minimally biofouled after ~3 months with the measures of a copper ring and a wiper. This is promising for long-term optical sensor deployment at real sites [Joslin]

### Environmental considerations

- A few turbines in a row have a minimal environmental effect, but tidal fences can be susceptible to similar environmental problems as tidal barrage as they can impact the tidal flow [Helston]
- Turbines are designed for low rotation speeds, so they are not a significant danger to aquatic life. Turbines are also sometimes screened to prevent entry by aquatic life. [Helston]
- BC/Southeast Alaska has some of the best tidal current opportunity in the world. Fishing is a major industry, so it is extremely important that any technology is environmentally sound [Helston]

## Benefits

- Highly consistent power sources
- Operation & maintenance costs are typically less than 0.5% of initial capital costs [Helston]
- Mostly emissions-free (installation has some emissions), and as a general trend displaces conventional generation in the area, thus reducing overall emissions [Helston]

## Drawbacks

- Tidal barrage systems (originally the preferred way to harness tidal power) can negatively effect the environment/aquatic life [Helston]
- Tidal turbines might in some sites reduce tidal velocity and therefore the motion of sediment/erosion [Helston]
- The sound generated by tidal turbines can cause changes in water pressure, which could result in tissue damage to fish [Helston] // Read more on this: [DoE report on the subject](http://www.energybc.ca/cache/tidal/PNNL-20786.pdf) "low level of tissue damage" on what they term "worst case" exposure for juvenile Chinook
- For tidal turbines, fluctuations in velocity of flow can cause blade vibrations which lead to fatigue failure

## Economic Feasibility

- La Rance provides at the cost of 3.7c/kWh, BC gvt estimates 11-25c/kWh dropping to 5-7c/kWh for new tidal installations on the BC coast [Helston]
- Higher thrust & thus higher material cost than wind turbines [O Rourke, 15][ORourke]
- Impractical in most of the world [Murphy-tides]
- Depends in part on availability of research funding. In a 2016 survey [Polis] it was found that WA state residents would be willing to pay $57 million annually for tidal energy R&D (comparable to the federal $60m budget for marine hydrokinetic and hydropower in 2015)
- There is massive potential for power generation in Australian sites (Turnagain Inlet is notable), but they are far from population centers and thus have not been pursued [Charlier, 82][Charlier]

### Alaska

- Alaska has 90% of the United States' potential for tidal power [Palomino]
- Map of hydropower and hydrokinetic projects in Alaska [Palomino] ![http://www.alaskapublic.org/wp-content/uploads/2014/07/Hydro-Projects-Alaska.png](http://www.alaskapublic.org/wp-content/uploads/2014/07/Hydro-Projects-Alaska.png)
- Energy is expensive in rural Alaska regardless of its source, so new technologies like tidal turbines might be close to economic parity with imported energy sources (e.g. diesel) [Palomino]
- Cook Inlet near Anchorage is the second biggest source of tidal power in the United States. The city currently depends on nearby natural gas reserves, but the inlet has enough power to supply the city. Ocean Renewable Power Company is currently investigating connecting tidal generators from Cook Inlet to the Railbelt (80% of power supply in Alaska) [Palomino]

#### Questions

- What is the typical power draw of a rural community in Southeast Alaska? Is this a good match for one or two tidal turbines?
- What is the interplay between a tidal turbine site and fishing? Fish also like fast currents at 20-30m deep. Would this interfere? Would it help if it were shut off at slack tide (least flow anyway)? Would it help if it were close to town (shorter wires & presumably less good fishing, but possibly an issue for the turbine itself getting disturbed?)
- Who is behind the current diesel generation systems for rural communities? If local, can these people be retrained to service a tidal turbine? What are the economic impacts of shutting down the diesel plant?

### Golden Gate

- Peter O'Donnell of the DoE SF interested in installing a tidal fence under the golden gate bridge from the west tower to Fort Point (substation), Shag Rock (single turbine), the Potato Patch (turbine farm). Just the Golden Gate piece could be up to 1500 MW electricity [McCarthy]
- 400b gallons per tide at up to 6 knots [McCarthy]
- In 2000 SF passed two renewable energy bond measures totaling over $100m
- "To generate one megawatt of electricity from tidal turbines in the Golden Gate right now," says O'Donnell, "would require an initial investment of $1.3 million." [McCarthy]
- Potential blockers: (1) political support. Does city council see this as progress or overreaching development? (2) technical. Tidal turbines are custom-built, and there are none in operation similar to the Bay (3) environmental concerns. What is the impact on marine life? What is the impact on sedimentary deposit? (4) visual blight. Is it attractive? (5) commerce. Does it interfere with existing business operations e.g. shipping? (6) Bay fill. If this constitutes bay fill, what remediation projects will be needed? [McCarthy]

## Existing installations

### Tidal barrage

- Sihwa in South Korea: biggest in the world with 254 MW of peak capacity, 30 km² of impound [Murphy-tides]
- Rance installation in France: built 1966, peak capacity of 240 MW, impounds 22.5 km² on an average tidal amplitude of 8 m. Typical generation of 96 MW [Murphy-tides]
- Annapolis Royal tidal barrage in Nova Scotia's Bay of Fundy is the third largest, at 20 mW [Helston]
- Kislaya Guba in Russia: 1968-present, 400 kW, has a UNESCO ecological monitoring site [Helston]
- Severn Barrage in the UK [Helston]

### Tidal stream generator

- [Race Rocks in British Columbia](https://tethys.pnnl.gov/annex-iv-sites/race-rocks-tidal-energy-project) (installed 2006) generates 65 kW. Cost $4m 2006 CAD to install [Helston]

Name                            | Developed by                                   | Key specs                                                                                                                                                            | Stage of development
------------------------------- | ---------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
DeltaStream Turbine device      | Tidal Energy Ltd. (UK)                         | 1.2 MW, three 3-blade (15m radius) horizontal turbines, gravity mounted on a triangular frame                                                                        | Full production was expected for summer 2009, hadn't been tested yet as of [ORourke]
EvoPod Tidal Turbine            | Ocean Flow Energy Ltd. (UK)                    | 5-blade horizontal axis floating structure, mooring designed to maintain optimal heading                                                                             | 1/10 scale model undergoing tests in Strangford Lough in Northern Ireland as of 2009
Free Flow Turbines              | Verdant Power Ltd (US/CA)                      | 3-blade horizontal axis turbine, 4.68m diameter, piled structure                                                                                                     | Prototype in NYC's East River was generating 1 MWh/day as of 2009, 2008 $1.15m contract from Sustainable Development Technology Canada to develop phase one of the Cornwall Ontario River Energy Project
Gorlov Helical Turbine          | GCK Technology Inc (USA)                       | 3 helical blades on a vertical turbine (efficient, minimal vibration) based on Darrieus Windmill concept                                                             | Scale model 1m version built and in testing since 7/10/2002
Lunar Energy Tidal Turbine      | Lunar Energy Ltd (UK)                          | Horizontal axis, gravity base, 1 MW bidirectional turbine (11.5m diameter) in a 19.2m length x 15m diameter duct, hydraulic motor & generator                        | As of [ORourke], nothing built, but £500m contract in place to install 300 turbines off the coast of Korea
Neptune Tidal Stream Device     | Aquamarine Power Ltd (UK)                      | 2.4 MW, twin 3-blade horizontal turbines mounted to monopole structure, bidirectional generation                                                                     | ABB commissioned the electrical system of the device in Jan. 2009\. Planned to test at EMEC by 2012
Nereus Tidal Turbine            | Atlantis Resource Corporation Ltd. (Singapore) | Shallow-water horizontal turbine, rated to 400 kW, robust against lots of debris                                                                                     | Successfully tested in July 2008, has been grid connected in Australia
Solon Tidal Turbine             | Atlantis Resource Corporation Ltd. (Singapore) | Deep-water ducted horizontal turbine (500 kW)                                                                                                                        | Successfully tested August 2008
Open Centre Turbine             | Open-Hydro Ltd. (Ireland)                      | 6m diameter slow rotor, stator, duct, and generator. 250 kW.                                                                                                         | First tidal current energy company to connect to the UK national grid. Installed at EMEC. 8/2008 selected by EDF electricity suppliers in France to develop a demonstration farm. They are developing a specialist barge to install the turbines.
Pulse Tidal Hydrofoil           | Pulse Generation Ltd (UK)                      | Efficient in shallow water                                                                                                                                           | Design phase as of 2009 with nothing built, but permission granted to deploy a prototype in Humber Estuary in Northern England
SeaGen                          | Marine Current Turbines Ltd. (UK)              | 1.2 MW, a pair of two-bladed horizontal axis rotors (16m diameter). Rotor blades are pitch controlled to work bidirectionally and to use for braking for maintenance | Successfully operated at full power 1/18/2009 at trial deployment (grid connected) in Strangford Lough in Norther Ireland
Seaflow                         | Marine Current Turbines Ltd. (UK)              | 300 kW                                                                                                                                                               | Successfully installed off the coast of Devon in 1993
Stingray Tidal Energy Converter | Engineering Business Ltd. (UK)                 | No rotor; parallel linkage holds large hydroplanes which create hydraulic power                                                                                      | Deployed 9/2002 in Yell Sound off Shetland but removed several weeks later, development stalled
TidEl Stream Generator          | SMD Hydrovision Ltd (UK)                       | Two contra-rotating 500 kW rotors, 15m diameter each, buoyant and moored with chains to align to tidal current flow                                                  | 1/10th scale model has been tested
Tidal Stream Turbine            | Hammerfest Strom AS (Norway)                   | 300 kW three-blade horizontal                                                                                                                                        | World's first grid-connected tidal turbine as of 11/2003 installed in Kvalsundet on Norway's north coast
Race Rocks Tidal Energy Project | EnCana Corporation                             | Horizontal axis bi-directional ducted turbine, 65 kW                                                                                                                 | _Testing_ 1:5 scale prototype installed at Race Rocks B.C. 2006-2011 as a research project

[O Rourke, 10-14][ORourke]

## Further reading

- [The economics of tidal power](http://ieeexplore.ieee.org/document/5589558/) an IEEE study on the break-even costs of tidal power. Super useful probably but because obviously science doesn't belong in the public domain it's behind a paywall

{% include "../../BIBLIOGRAPHY.md" %}
