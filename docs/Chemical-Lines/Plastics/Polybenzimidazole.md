---
title: Polybenzimidazole
author: ME Item Storage Cell
---

# Polybenzimidazole (PBI)
<small>**Guide by:** ME Item Storage Cell</small>

!!! quote ""

PBI is the <ZPM>ZPM</ZPM> plastic, which you will use until <Uv>UV</UV>.

## How to make PBI

```mermaid
flowchart TD
    %%{init: { 'theme': 'neutral', 'themeVariables': { 'edgeLabelBackground': 'transparent', 'secondaryColor': 'transparent', 'tertiaryColor': 'transparent', 'labelBkgBackground' : 'transparent' }}}%%

    classDef invisible fill:none,stroke:none,color:none,stroke-width:0px

    subgraph SubDiaminobenzidine [" "]
        direction TD
        NitricNM@{ shape: lean-r, label: "Nitric Acid" }
        SulfuricNM@{ shape: lean-r, label: "Sulfuric Acid" }
        NMProcess@{ img: "https://start-dev-team.github.io/StarT-Wiki/Chemical-Lines/Plastics/PBI_img/mixer_nitration_mixture.png", label: "Mixer", pos: "t", w: 200, h: 200, constraint: "on" }

        ChlorineCB@{ shape: lean-r, label: "Chlorine" }
        BenzeneCB@{ shape: lean-r, label: "Benzene" }
        CBProcess@{ img: "https://start-dev-team.github.io/StarT-Wiki/Chemical-Lines/Plastics/PBI_img/large_chemical_reactor_chlorobenzene.png", label: "LCR", pos: "t", w: 200, h: 200, constraint: "on" }
        CBHydrochloric@{ shape: lean-l, label: "Hydrochloric Acid" }

        NCBProcess@{ img: "https://start-dev-team.github.io/StarT-Wiki/Chemical-Lines/Plastics/PBI_img/large_chemical_reactor_nitrochlorobenzene.png", label: "LCR", pos: "t", w: 200, h: 200, constraint: "on" }

        CopperDCB@{ shape: lean-r, label: "Copper Dust" }
        HydrogenDCB@{ shape: lean-r, label: "Hydrogen" }
        DCBProcess@{ img: "https://start-dev-team.github.io/StarT-Wiki/Chemical-Lines/Plastics/PBI_img/large_chemical_reactor_dichlorobenzidine_9.png", label: "LCR", pos: "t", w: 200, h: 200, constraint: "on" }

        AmmoniaDAB@{ shape: lean-r, label: "Ammonia"}
        DABProcess@{ img: "https://start-dev-team.github.io/StarT-Wiki/Chemical-Lines/Plastics/PBI_img/large_chemical_reactor_diaminobenzidine.png", label: "LCR (Zinc NC)", pos: "t", w: 200, h: 200, constraint: "on" }
        DABHydrochloric@{ shape: lean-l, label: "Hydrochloric Acid"}

        DSProcess@{ img: "http://127.0.0.1:8000/StarT-Wiki/Chemical-Lines/Plastics/PBI_img/distillery_distill_dilute_sulfuric_to_sulfuric_acid_2.png", label: "Distillery", pos: "t", w: 200, h: 200, constraint: "on" }

        NitricNM --> NMProcess
        SulfuricNM --> NMProcess

        ChlorineCB --> CBProcess
        BenzeneCB --> CBProcess
        CBProcess --> CBHydrochloric

        NMProcess --Nitration Mixture--> NCBProcess
        CBProcess --Chlorobenzene--> NCBProcess
        NCBProcess --Diluted Sulfuric Acid--> DSProcess

        CopperDCB --> DCBProcess
        HydrogenDCB --> DCBProcess
        NCBProcess --Nitrochlorobenzene--> DCBProcess

        AmmoniaDAB --> DABProcess
        DCBProcess --Dichlorobenzidine--> DABProcess
        DABProcess --> DABHydrochloric

        DSProcess --> NMProcess
    end
    class SubDiaminobenzidine invisible

    subgraph 

    subgraph SubPolybenzimidazole [" "]
        direction TD
    end
    class SubPolybenzimidazole invisible

```