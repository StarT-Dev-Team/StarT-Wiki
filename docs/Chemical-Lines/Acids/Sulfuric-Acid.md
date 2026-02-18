# Sulfuric Acid

## How to make Sulfuric Acid


```mermaid
flowchart LR;
    %%{init: { 'theme': 'neutral', 'themeVariables': { 'edgeLabelBackground': 'transparent', 'secondaryColor': 'transparent', 'tertiaryColor': 'transparent' }}}%%

    A@{ img: "https://start-dev-team.github.io/StarT-Wiki/Chemical-Lines/Acids/H2SO4_img/large_chemical_reactor_sulfur_dioxide_from_sulfur.png", label: "React sulfur and oxygen", pos: "t", w: 120, h: 120, constraint: "on" }

    B@{ img: "https://start-dev-team.github.io/StarT-Wiki/Chemical-Lines/Acids/H2SO4_img/large_chemical_reactor_sulfur_trioxide.png", label: "React sulfur dioxide and oxygen", pos: "t", w: 120, h: 120, constraint: "on" }

    C@{ img: "https://start-dev-team.github.io/StarT-Wiki/Chemical-Lines/Acids/H2SO4_img/large_chemical_reactor_sulfuric_acid_from_trioxide.png", label: "Wet sulfur trioxide", pos: "t", w: 120, h: 120, constraint: "on" }

    D[Oxygen]

    E[Water]

    F[Sulfur]

    G[Sulfuric Acid]

    A --Sulfur Dioxide--> B --Sulfur Trioxide--> C;

    D --> A
    F --> A
    D --> B
    E --> C
    C --> G
```

#### Option 2: Combine Hydrogen Sulfide and Oxygen (LCR Cir 2)

![hso](H2SO4_img/large_chemical_reactor_sulfuric_acid_from_sulfide.png)

#### Option 3: Combine Water and Sulfur Dust <hv>(HV LCR Cir 24)</hv>

![sh2o](H2SO4_img/large_chemical_reactor_sulfuric_acid_from_sulfur.png)
