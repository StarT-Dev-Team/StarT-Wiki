# Polyvinyl Chloride (PVC)

An entirely optional plastic that you can make in <mv>MV</mv>, immediately as you make Polyethylene.

## How to make PVC

### Vinyl Chloride

!!! note ""

    === "Chlorine"
        ```mermaid
        flowchart LR
            %%{init: { 'theme': 'neutral', 'themeVariables': { 'edgeLabelBackground': 'transparent', 'secondaryColor': 'transparent', 'tertiaryColor': 'transparent', 'labelBkgBackground' : 'transparent' }}}%%

            A@{ img: "http://127.0.0.1:8000/StarT-Wiki/Chemical-Lines/Plastics/PVC_img/chemical_reactor_vinyl_chloride_from_chlorine.png", label: "Chemical Reactor (LV)", pos: "t", w: 200, h: 200, constraint: "on" }

            B@{ img: "http://127.0.0.1:8000/StarT-Wiki/Chemical-Lines/Plastics/PVC_img/electrolyzer_decomposition_electrolyzing_hydrochloric_acid.png", label: "Electrolyser", pos: "t", w: 200, h: 200, constraint: "on" }

            C@{ shape: lean-r, label: "1/2b Chlorine" }

            D@{ shape: lean-l, label: "1b Hydrochloric Acid" }

            E@{ shape: lean-r, label: "1b Ethylene"}

            F@{ shape: lean-r, label: "1b Chlorine"}

            G@{ shape: lean-l, label: "1b Hydrogen"}

            H@{ shape: lean-l, label: "1b Vinyl Chloride"}

            C --> A
            E --> A
            A --> D
            A --> H
            D --> B
            B --1b Chlorine--> A
            F --> A
            B --> G
        ```

        This is the recommended way to make Vinyl Chloride. You don't have to electrolyse the hydrochloric acid, you can simply use it. Recycling Chlorine isn't important, you more often than not have a surplus of it.

    === "Oxygen + Hydrochloric acid"
        ```mermaid
        flowchart LR
            %%{init: { 'theme': 'neutral', 'themeVariables': { 'edgeLabelBackground': 'transparent', 'secondaryColor': 'transparent', 'tertiaryColor': 'transparent', 'labelBkgBackground' : 'transparent' }}}%%

            A@{ img: "http://127.0.0.1:8000/StarT-Wiki/Chemical-Lines/Plastics/PVC_img/chemical_reactor_vinyl_chloride_from_hydrochloric.png", label: "Chemical Reactor (LV)", pos: "t", w: 200, h: 200, constraint: "on" }

            B@{ img: "http://127.0.0.1:8000/StarT-Wiki/Chemical-Lines/Plastics/PVC_img/electrolyzer_water_electrolysis.png", label: "Electrolyser", pos: "t", w: 200, h: 200, constraint: "on" }

            C@{ shape: lean-r, label: "1b Oxygen" }

            D@{ shape: lean-r, label: "1b Hydrochloric Acid" }

            E@{ shape: lean-r, label: "1b Ethylene"}

            F@{ shape: lean-r, label: "2b Hydrogen"}

            G@{ shape: lean-l, label: "1b Water"}

            H@{ shape: lean-l, label: "1b Vinyl Chloride"}

            C --> A
            E --> A
            D --> A
            A --> G
            A --> H
            G --> B
            B --1b Oxygen--> A
            B --> F
        ```

        Would not recommend using this method. Electrolysing water is much slower than the Chemical Reactor, and uses a lot of energy. The only potential upside of this method is the low usage of chlorine, but you can get the same result by electrolysing the Hydrochloric Acid you get from method 1.

### Polymerisation

!!! note ""

    === "Air"

        ![PVC_Air](PVC_img/chemical_reactor_polyvinyl_chloride_from_air_2.png)

    === "Oxygen"

        ![PVC_Oxygen](PVC_img/chemical_reactor_polyvinyl_chloride_from_oxygen_2.png)

        ***Most efficient**

## 