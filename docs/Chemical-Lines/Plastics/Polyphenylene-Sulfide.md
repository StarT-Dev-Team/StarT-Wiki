---
title: Polyphenylene Sulfide
author: ME Item Storage Cell
description: A plastic made in LUV, to reach ZPM.
---

# Polyphenylene Sulfide (PPS)
<small>**Guide by:** ME Item Storage Cell</small>

!!! quote ""

A plastic you will need to make in <LUV>Luv</LUV> to make <ZPM>ZPM</ZPM> energy hatches. Compared to other mid-game plastics, PPS is pretty simple to make.

## How to make PPS

### LCR

```mermaid { data-search-exclude }
flowchart TD
    %%{init: { 'theme': 'neutral', 'themeVariables': { 'edgeLabelBackground': 'transparent', 'secondaryColor': 'transparent', 'tertiaryColor': 'transparent', 'labelBkgBackground' : 'transparent' }}}%%

    A@{ img: "https://start-dev-team.github.io/StarT-Wiki/Chemical-Lines/Plastics/PPS_img/large_chemical_reactor_sodium_sulfide.png", label: "LCR", pos: "t", w: 200, h: 200, constraint: "on" }

    B@{ img: "https://start-dev-team.github.io/StarT-Wiki/Chemical-Lines/Plastics/PPS_img/large_chemical_reactor_dichlorobenzene.png", label: "LCR", pos: "t", w: 200, h: 200, constraint: "on" }

    C@{ img: "https://start-dev-team.github.io/StarT-Wiki/Chemical-Lines/Plastics/PPS_img/large_chemical_reactor_polyphenylene_sulfide_from_oxygen.png", label: "LCR", pos: "t", w: 200, h: 200, constraint: "on" }

    D@{ shape: lean-r, label: "1x Sulfur Dust" }

    F@{ shape: lean-r, label: "2b Chlorine" }

    G@{ shape: lean-r, label: "1b Benzene" }

    H@{ shape: lean-l, label: "2b Hydrochloric Acid" }

    I@{ shape: lean-r, label: "6b Oxygen" }

    J@{ shape: lean-l, label: "1.5b Polyphenylene Sulfide" }

    K@{ img: "https://start-dev-team.github.io/StarT-Wiki/Chemical-Lines/Plastics/PPS_img/electrolyzer_decomposition_electrolyzing_salt.png", label: "LCR", pos: "t", w: 200, h: 200, constraint: "on" }

    D --> A
    K --2x Sodium Dust--> A
    A --3x Sodium Sulfide Dust--> C

    F --> B
    G --> B
    B --> H
    B --2b Dichlorobenzene--> C

    I --> C
    C --> J
    C --4x Salt--> K
    K --2b Chlorine-->B

```
Looping is optional. For the final step you can use air instead of oxygen, but it is less efficient, and at this stage you should have no issues sourcing oxygen.

### Chem Plant

In <ZPM>ZPM</ZPM>, you can make use of the Chem Plant to make PPS in 1 step, taking Sulfur, Oxygen, Benzene, and Chlorine as inputs, and giving a byproduct of Hydrochloric Acid.

![PPS_ChemPlant](PPS_img/chemical_skip_polyphenylene_sulfide_skip.png)

!!! tip ""
    === "Inputs"
        - Sulfur
        - Oxygen
        - Benzene
        - Chlorine

    === "Outputs"
        - PPS
        - Hydrochloric Acid

## Uses of PPS

PPS is required to enter <ZPM>ZPM</ZPM>. The <ZPM>ZPM</ZPM> energy hatch and machine hull requires Vanadium Gallium Cable, which requires PPS foil to make.

![VanadiumGalliumCable_1x](PPS_img/assembler_cover_vanadium_gallium_wire_gt_single_silicone.png)

PPS is also required for other cables, among other things. But mainly cables.