# Polycaprolactam (Nylon 6)

Another optional plastic you can make in <hv>HV</hv>. The only real use for it is to make lots of string very quickly. Especially useful if you don't have flax automated.

## How to make Nylon 6

### Caprolactam

#### LCR
```mermaid
flowchart TD
    %%{init: { 'theme': 'neutral', 'themeVariables': { 'edgeLabelBackground': 'transparent', 'secondaryColor': 'transparent', 'tertiaryColor': 'transparent', 'labelBkgBackground' : 'transparent' }}}%%

    A@{ img: "https://start-dev-team.github.io/StarT-Wiki/Chemical-Lines/Plastics/PCL_img/large_chemical_reactor_cyclohexane.png", label: "LCR (Nickel Catalyst)", pos: "t", w: 200, h: 200, constraint: "on" }

    B@{ img: "https://start-dev-team.github.io/StarT-Wiki/Chemical-Lines/Plastics/PCL_img/large_chemical_reactor_nitric_oxide_from_ammonia.png", label: "LCR", pos: "t", w: 200, h: 200, constraint: "on" }

    C@{ img: "https://start-dev-team.github.io/StarT-Wiki/Chemical-Lines/Plastics/PCL_img/large_chemical_reactor_nitrosyl_chloride.png", label: "LCR", pos: "t", w: 200, h: 200, constraint: "on" }

    D@{ img: "https://start-dev-team.github.io/StarT-Wiki/Chemical-Lines/Plastics/PCL_img/large_chemical_reactor_cyclohexanone_oxime.png", label: "LCR", pos: "t", w: 200, h: 200, constraint: "on" }

    E@{ img: "https://start-dev-team.github.io/StarT-Wiki/Chemical-Lines/Plastics/PCL_img/large_chemical_reactor_caprolactam.png", label: "LCR", pos: "t", w: 200, h: 200, constraint: "on" }

    F@{ shape: lean-r, label: "Benzene" }

    G@{ shape: lean-r, label: "Hydrogen" }

    H@{ shape: lean-r, label: "Nitrogen Oxide" }

    I@{ shape: lean-r, label: "Ammonia" }

    J@{ shape: lean-r, label: "Chlorine" }

    K@{ shape: lean-r, label: "Sulfuric Acid" }

    L@{ shape: lean-l, label: "Caprolactam dust" }

    M@{ shape: lean-l, label: "Hydrochloric Acid" }

    N@{ shape: lean-l, label: "Diluted Sulfuric Acid" }

    O@{ shape: lean-l, label: "Water" }

    F --> A
    G --> A
    H --> B
    I --> B
    B --> O
    B --Nitric Oxide--> C
    J ---> C
    A --Cyclohexane--> D
    C --Nitrosyl Chloride--> D
    D --> M
    D --Cyclohexanone Oxime Dust--> E
    K --> E
    E --> N
    E --> L
```

#### Chem Plant Skip
In <zpm>ZPM</zpm>, you can use the chemical plant to make Caprolactam in 1 step. Then you just have to smelt it

![Caprolactam_ChemPlant](Nylong6_img/chemical_skip_caprolactam_skip.png)

### Polymerisation

## Uses of Nylon 6
Streeeng