# Europe Solar Energy

**Main Question**:
To satisfy Europe's energy, how much area needs to be covered by Solar Panels, and where? 

**Sub questions of the main question**:
* How much energy does covering Europe with panels would produce
* How much energy yearly does europe consume
* How much area would need to be covered
* Where should we put the solar panels?

Follow-up questions:
* Can we make the count accounting for months of max usage and least radiation
* Can we account for energy accumulation?

### How much energy does covering Europe with panels would produce
Upper bound: How much energy can we produce if we fill Europe with solar panels

* Version 1: Use spatial mean of Europe's box pvpot times the area of Europe
* Version 2: Use Europe's box and get the area per box times its own pvpot(use cosines)
    

### How much energy yearly does europe consume
Find a resource for Europe's energy needs, a yearly and monthly value would useful


### How much area would need to be covered



### Where should we put the solar panels?

* For this we need the energy production per grid box, and the area of the boxes



### Phase 1
Get a rough upper bound of possible energy production when covering all Europe
with solar panels


For this purpose we need:

* An estimate of Europe energy needs
    Steps:
        1. A yearly sum
        2. A monthly sum
        3. A daily sum


* A way to decide what counts as Europe:
    Steps:
        1. Use a box for coordinates: lat(35,70) long(-10, 30)
        2. Use spacial mean of the box times the area of Europe
        3. Cut the border of coordinates


* Estimate how much energy a panel produces in a specific place
    Steps:
        1. Calculate pvpot
        2. Decide for a standard panel to use: 


## Maths
###  Energy Required:

## Energy produced:

### Energy produced per $m^2$

Our model solar panel has a specification
of  $237W/m^2$ 

If we multiply that by the pvpot we get the W/m^2 that can be generated in a 
specific spot.

### Energy produces in Europe
Europe's Area: $10.53 \times 10^6 km^2$



## Next steps:

* Do code for storing pvpot per month over 10 years:
    * mean
    * max
    * min
    * sum ? 

* Do code for loading pvpot from our files

* Write script to compute pvpot and store its

* 