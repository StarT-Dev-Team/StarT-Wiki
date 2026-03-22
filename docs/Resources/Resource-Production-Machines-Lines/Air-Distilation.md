---
title: Air Distillation
author: Jkj3000
---
# Air Distillation
<small>**Guide By:** Jkj3000</small>

!!! quote ""

Air distillation is available as soon as <HV>**HV**</HV>, and continues into <EV>**EV**</EV> and <IV>**IV**</IV> with the use of a **Distillation Tower**, or **DT** for short. 

There are 3 airs you can distill, which must be in liquid form:

- Liquid Air Distillation
- Liquid Nether Air Distillation
- Liquid Ender Air Distillation

## Liquid Air

Liquid Air is available at <HV>**HV**</HV> and is the easiest one to get as air can be gathered with a gas collector. Then put into any multiblock that can do freezing recipes, such as a **Vacuum Freezer**, and then distilled in a **DT**
```mermaid
flowchart LR
    %%{init: { 'theme': 'neutral', 'themeVariables': { 'edgeLabelBackground': 'transparent', 'secondaryColor': 'transparent', 'tertiaryColor': 'transparent', 'labelBkgBackground' : 'transparent' }}}%%

    A@{shape: lean-r, label: Air}
    B@{img: "https://github.com/StarT-Dev-Team/StarT-Wiki/blob/7d9c51003415e9a037184d338acf80c3aadce7fb/docs/Resources/Resource-Production-Machines-Lines/AirDistillation_img/vacuum_freezer_liquid_air.png?raw=true", pos: "t", label: "Vacuum Freezer", h: 200, constraint: "on"}
    C@{img: "https://github.com/StarT-Dev-Team/StarT-Wiki/blob/7d9c51003415e9a037184d338acf80c3aadce7fb/docs/Resources/Resource-Production-Machines-Lines/AirDistillation_img/distillation_tower_distill_liquid_air.png?raw=true", pos: "t", label: "Distillation Tower", h: 400, constraint: "on"}
    A-- Air 4B -->B
    B-- Liquid Air 50B -->C
```
This recipe produces:

- Nitrogen **35B**
- Oxygen **11B**
- Carbon Dioxide **2.5B**
- Helium **1B**
- Argon **0.5B**

## LIquid Nether Air

Liquid Nether air is available at <HV>**HV**</HV> with overclocking or at <EV>**EV**</EV> without.
Nether air cannot be easily collected so you need to create it from scratch. 

```mermaid
flowchart TD
    %%{init: { 'theme': 'neutral', 'themeVariables': { 'edgeLabelBackground': 'transparent', 'secondaryColor': 'transparent', 'tertiaryColor': 'transparent', 'labelBkgBackground' : 'transparent' }}}%%

    A@{img: "https://github.com/StarT-Dev-Team/StarT-Wiki/blob/7d9c51003415e9a037184d338acf80c3aadce7fb/docs/Resources/Resource-Production-Machines-Lines/AirDistillation_img/large_chemical_reactor_easy_netherrack.png?raw=true", pos: "t", label: "Large Chemical Reactor", h: 200, constraint: "on"}
    B@{img: "https://github.com/StarT-Dev-Team/StarT-Wiki/blob/7d9c51003415e9a037184d338acf80c3aadce7fb/docs/Resources/Resource-Production-Machines-Lines/AirDistillation_img/macerator_macerate_netherrack.png?raw=true", pos: "t", label: "Macerator", h: 200, constraint: "on"}
    C@{img: "https://github.com/StarT-Dev-Team/StarT-Wiki/blob/7d9c51003415e9a037184d338acf80c3aadce7fb/docs/Resources/Resource-Production-Machines-Lines/AirDistillation_img/extractor_nether_agglomeration.png?raw=true", pos: "t", label: "Extractor", h: 200, constraint: "on"}
    D@{shape: lean-l, label: "Gold Nugget"}
    E@{img: "https://github.com/StarT-Dev-Team/StarT-Wiki/blob/7d9c51003415e9a037184d338acf80c3aadce7fb/docs/Resources/Resource-Production-Machines-Lines/AirDistillation_img/mixer_nether_air_mix.png?raw=true", pos: "t", label: "Mixer", h: 200, constraint: "on" }
    F@{shape: lean-r, label: "Air"}
    G@{img: "https://github.com/StarT-Dev-Team/StarT-Wiki/blob/7d9c51003415e9a037184d338acf80c3aadce7fb/docs/Resources/Resource-Production-Machines-Lines/AirDistillation_img/vacuum_freezer_liquid_nether_air.png?raw=true", pos: "t", label: "Vacuum Freezer", h: 200, constraint: "on"}
    H@{img: "https://github.com/StarT-Dev-Team/StarT-Wiki/blob/7d9c51003415e9a037184d338acf80c3aadce7fb/docs/Resources/Resource-Production-Machines-Lines/AirDistillation_img/distillation_tower_distill_liquid_nether_air.png?raw=true", pos: "t", label: "Distillation Tower", h: 400, constraint: "on"}

    A-- Netherrack -->B
    B-- Netherrack Dust -->C
    B-- Gold Nugget -->D
    C-- Nether Agglomeratio -->E
    F-- Air 12B-->E
    E-- Nether Air 4B -->G
    G-- Liquid nether Air 100B -->H
    
```
This recipe produces:

- Carbon Monoxide **72B**
- Coal Gas **10B**
- Hydrogen Sulfide **7.5B**
- Sulfur Dioxide **7.5B**
- Helium 3 **2.5B**
- Neon **0.5B**

## Liquid Ender Air

Liquid Ender Air is available at <EV>**EV**</EV> with overclocking or at <IV>**IV**</IV> without, but you need an <IV>**IV**</IV> input hatch as the recipe requires 200B to start.
Ender Air is made by mixing Nether Air with End Agglormoratio.

```mermaid
flowchart TD
    %%{init: { 'theme': 'neutral', 'themeVariables': { 'edgeLabelBackground': 'transparent', 'secondaryColor': 'transparent', 'tertiaryColor': 'transparent', 'labelBkgBackground' : 'transparent' }}}%%

    A@{img: "https://github.com/StarT-Dev-Team/StarT-Wiki/blob/7d9c51003415e9a037184d338acf80c3aadce7fb/docs/Resources/Resource-Production-Machines-Lines/AirDistillation_img/large_chemical_reactor_easy_endstone.png?raw=true", pos: "t", label: "Large Chemical Reactor", h: 200, constraint: "on"}
    B@{img: "https://github.com/StarT-Dev-Team/StarT-Wiki/blob/7d9c51003415e9a037184d338acf80c3aadce7fb/docs/Resources/Resource-Production-Machines-Lines/AirDistillation_img/macerator_macerate_end_stone.png?raw=true", pos: "t", label: "Macerator", h: 200, constraint: "on"}
    C@{img: "https://github.com/StarT-Dev-Team/StarT-Wiki/blob/7d9c51003415e9a037184d338acf80c3aadce7fb/docs/Resources/Resource-Production-Machines-Lines/AirDistillation_img/extractor_end_agglomeration.png?raw=true", pos: "t", label: "Extractor", h: 200, constraint: "on"}
    D@{img: "https://github.com/StarT-Dev-Team/StarT-Wiki/blob/7d9c51003415e9a037184d338acf80c3aadce7fb/docs/Resources/Resource-Production-Machines-Lines/AirDistillation_img/mixer_ender_air_mix.png?raw=true", pos: "t", label: "Mixer", h: 200, constraint: "on"}
    E@{img: "https://github.com/StarT-Dev-Team/StarT-Wiki/blob/7d9c51003415e9a037184d338acf80c3aadce7fb/docs/Resources/Resource-Production-Machines-Lines/AirDistillation_img/vacuum_freezer_liquid_ender_air.png?raw=true", pos: "t", label: "Vacuum Freezer", h: 200, constraint: "on"}
    F@{img: "https://github.com/StarT-Dev-Team/StarT-Wiki/blob/7d9c51003415e9a037184d338acf80c3aadce7fb/docs/Resources/Resource-Production-Machines-Lines/AirDistillation_img/distillation_tower_distill_liquid_ender_air.png?raw=true", pos: "t", label: "Distillation Tower", h: 400, constraint: "on"}
    G@{shape: lean-r, label: "Nether Air"}

    A-->B
    B-->C
    C-- End Agglomeratio -->D
    G-- Nether Air 6B -->D
    D-- Ender Air 6B -->E
    E-- Liquid Ender Air 200B --> F
```
This recipe produces:

- Nitrogen Dioxide **122B**
- Deuterium **50B**
- Helium **15B**
- Tritium **10B**
- Krypton **1B**
- Xenon **1B**
- Radon **1B**

## Later Upgrades

When you get to parallel multiblocks \(around <IV>**IV**</IV>\), you can unlock the **Large Fractionating Distillery** which accepts parallel hatches, greatly speeding up the distillation. 

When you reach <IV>**IV**</IV> and <UV>**UV**</UV>, you will gain access to the **Arctic Chilling Unit** and **Bulk Blast Chiller** respectively speed up freezing airs. 

And when you get to Abydos \(post <UHV>**UHV**</UHV>\) you will unlock the **Exotic Gas Syphon** which allows you to skip all of these production lines all together.