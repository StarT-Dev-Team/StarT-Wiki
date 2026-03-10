---
title: Dynamos
author: humanoferth
---

# Dynamos
<small>**Guide by:** humanoferth</small>

Dynamos are a type of block added by Thermal that can generate power. They are often used from <LV>**LV**</LV> to <EV>**EV**</EV> or early <IV>**IV**</IV>. There are 3 types of dynamos:

!!! example ""

    === "Stirling Dynamo"
    
        Stirling Dynamos use furnace fuel as an input. This is the first dynamo that you can use and are a good choice for an intial power source, though I advise against relying on these long term since these do not have as high of a power capacity as steam engines <!-- link to SU gen / create power --> which take the same fuel input. There are also better options for dynamos.

    === "Compression Dynamo"
        
        Compression Dynamos take fluid fuels as their input. While these can be better then the singleblock turbines from gregtech, they are difficult to set up early on and you have much better options. By the time your able to easily make good fuels for the compression dynamo, you have access to the large gas turbine,  where the rotor bonuses outscale the thermal upgrades.

    === "Lapidary Dynamo"
    
        Lapidary Dynamos use gems as an input to generate power. Out of the three dynamo options, these are the best in terms of ease of setup and maximum power output. These are gated by the assembler and require cobalt brass to craft. These are far and away the best form of dynamo in terms of setup time and power output, as precious gems are easy to obtain thanks to sieving.
        
## Calculating Fuel Consumption and FE/t

Without augments, dynamos produce 200 FE/t (4000 FE/s). Fuel consumption can be calculated by dividing the total FE produced by one item (Found in EMI) or bucket of fuel by the FE/s your dynamo is currently producing (factoring in augments). For example, a diamond produces a total of 300,000 FE, as found in EMI. Dividing this by 4000 (FE/s produced by a lapidary dynamo with no augments) gives 1 diamond consumed every 75 seconds. Below are a list of augments and how they effect fuel consumption and power production.

!!! example ""

    === "Upgrade Kits"
    
        Upgrade kits multiply power production at the same rate they multiply fuel consumption. If, for example, a lapidary dynamo is being fueled by diamonds (produces 300,000 RF each) had an EV upgrade kit (48x scale factor), the dynamo would produce 9,600 RF/t (200 RF/t * 48) while consuming a diamond every 1.5625 seconds (300,000 RF / (9,600 RF/t / 20 t/s)). While you can put multiple upgrade kits in a dynamo, only one of the highest tier one will do anything.

    === "ARC Kits"
        
        Auxillery Reaction Chamber Kits (ARC's) **additively** increase power output at the cost of a **multiplicative** increase in fuel energy. Its really important to keep in mind that these effects are compounding. If, for example, a lapidary dynamo is being fueled by diamonds (produces 300,000 RF each) had an EV ARC (.6x fuel energy, +300% power output), the dynamo would produce 800 RF/t (200 RF/t + (300% * 200 RF/t)) and it would consume a diamond every 11.25 seconds ((300,000 RF * .6)/(800 RF/t * 20 t/s)). A dynamo can take multiple ARC's, where fuel energy is multipled, and  power output is added for each ARC. If, for example, a lapidary dynamo is being fueled by diamonds (produces 300,000 RF each) had 3 EV ARC's (.216x fuel energy (.6 ^ 3), +900% power output (300 * 3)), the dynamo would produce 2000 RF/t (200 RF/t + (900% * 200 RF/t)) and it would consume a diamond every 1.62 seconds ((300,000 RF * .216)/(2000 RF/t * 20 t/s)).

    === "MCI Kits"

        Multi-cycle Injector Kits (MCI's)  **multaplicatively** decrease fuel consumption without affecting power output.  If, for example, a lapidary dynamo is being fueled by diamonds (produces 300,000 RF each) had an EV MCI (1.6x fuel energy), the dynamo would produce 200 RF/t and it would consume a diamond every 120 seconds ((300,000 RF * 1.6)/(200 RF/t * 20 t/s)). A dynamo can take multiple MCI's, where fuel energy is multipled for each ARC. If, for example, a lapidary dynamo is being fueled by diamonds (produces 300,000 RF each) had 3 EV ARC's (4.096x fuel energy (1.6 ^ 3)), the dynamo would produce 200 RF/t and it would consume a diamond every 307.2 seconds ((300,000 RF * 4.096)/(2000 RF/t * 20 t/s)).
        
MCI's are better than ARC's since you MCI's just gives fuel more energy at no cost. While ARC's output more power, this increase in power also increases the speed at which fuel is consumed on top of the decrease in fuel. Using the numbers above, a lapidary dynamo with three EV ARC's would consume a diamond every 1.62 seconds and produce 2000 RF/t. To do the same with lapidary dynamos with three MCI's (which consume a diamond every 307.2 seconds and produces 200 RF/t), you could put down 10 lapidary dynamos with three MCI's and get the same power output (200 RF/t * 10) while consuming a diamond every 30.72 seconds (307.2 s / 10).


Optimally, for a dynamo you'll want to have an upgrade kit and three MCI's of the highest tier you can afford in your dynamos. The upgrade kit will increase power output so that it can scale with your power needs without spamming while the MCI's will help alleviate the increases in fuel consumption.

## Example Setups

<!-- Do tabs for all -->

<!-- 40,000 Nether quartz, 300,000 for diamonds, 40,000 for lapis, 40,000 for amathyst, 125,000 for amathyst. Produces 16 of each every 40 seconds at LV -->


