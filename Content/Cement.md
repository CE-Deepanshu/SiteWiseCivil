# CEMENT
A cement is a binder used for construction that sets, hardens, and adheres to other materials to bind them together. Cement is seldom used on its own, but rather to bind sand and gravel (aggregate) together. Cement mixed with fine aggregate produces mortar for masonry, or with sand and gravel, produces concrete.

## Manufacturing of Cement

### Dry Process

<div class="mermaid">
flowchart TD

    A[Calcareous Material<br/>Limestone] --> B[Crushing]
    B --> C[Fine Grinding in Ball Mills<br/>and Tube Mills]
    C --> D[Storage]

    E[Argillaceous Material<br/>Clay] --> F[Washing]
    F --> G[Fine Grinding in Ball Mills<br/>and Tube Mills]
    G --> H[Storage]

    D --> I[Mixing in Correct Proportion]
    H --> I

    I --> J[Storage Tank for Raw Mix]
    J --> K[Rotary Kiln]

    L[Coal Dust] --> K

    K --> M[Formation of Clinkers]
    M --> N[Coolers]
    N --> O[Grinding of Clinkers in Ball Mills<br/>and Tube Mills]

    P[Gypsum 2 to 3%] --> O

    O --> Q[Storage in Silos]
    Q --> R[Weighing & Packing in Bags]
    R --> S[Distribution]
</div>

<script type="module">
  import mermaid from "https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs";
  mermaid.initialize({ startOnLoad: true });
</script>

### Wet Process

<div class="mermaid">
flowchart TD

    A[Calcareous Materials<br/>Limestone/Marl]
    B[Preliminary Crushing<br/>Crushers-Roll Mills]
    C[Elevators<br/>Storage Bins]

    D[Argillaceous Materials<br/>Clay/Shale]
    E[Washing<br/>Wash Mills]
    F[Elevators<br/>Storage Tanks]

    W[Water]

    A --> B
    B --> C

    D --> E
    E --> F

    C --> G[Hoppers]
    F --> G

    G --> H[Wet Grinding<br/>Ball Mills]
    W --> H

    H --> I[Raw Slurry]

    J[Lime Slurry]
    K[Clay Slurry]

    I --> L[Elevators]
    J --> L
    K --> L

    L --> M[Correction Silos]
    M --> N[Rotary Kiln]

    O[Fuel Coal]
    P[Crushing and Grinding<br/>Ball Mills]
    Q[Pulverized Coal]

    O --> P
    P --> Q
    Q --> N

    N --> R[Clinker]

    S[Gypsum]
    T[Gypsum Hoppers]

    S --> T

    R --> U[Clinker Grinding<br/>Tube Mills]
    T --> U

    U --> V[Elevators<br/>Cement Silos]
    V --> X[Weighing and Packing]
    X --> Y[Supply]
</div>

<script type="module">
  import mermaid from "https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs";
  mermaid.initialize({ startOnLoad: true });
</script>

## IS 10262 – Water Cement Ratio vs Strength

<svg width="800" height="500" viewBox="0 0 800 500" xmlns="http://www.w3.org/2000/svg">
  <rect width="100%" height="100%" fill="white"/>
  <text x="400" y="35" text-anchor="middle" font-size="22" font-family="Arial">
    Figure 1: IS 10262 - w/c Ratio vs Strength
  </text>

  <line x1="90" y1="420" x2="730" y2="420" stroke="black"/>
  <line x1="90" y1="60" x2="90" y2="420" stroke="black"/>

  <text x="410" y="470" text-anchor="middle" font-size="16" font-family="Arial">
    Free Water-Cement Ratio
  </text>
  <text x="25" y="250" text-anchor="middle" font-size="16" font-family="Arial" transform="rotate(-90 25 250)">
    28-Day Compressive Strength (MPa)
  </text>

  <polyline points="110,100 190,170 270,230 350,280 430,320 510,350 590,380 690,410"
            fill="none" stroke="#1f77b4" stroke-width="3"/>
  <polyline points="110,75 190,145 270,205 350,255 430,295 510,330 590,360 690,390"
            fill="none" stroke="#ff7f0e" stroke-width="3"/>
  <polyline points="110,50 190,120 270,180 350,230 430,270 510,305 590,335 690,365"
            fill="none" stroke="#2ca02c" stroke-width="3"/>

  <text x="565" y="90" font-size="15" font-family="Arial" fill="#1f77b4">Curve 1 (OPC 33)</text>
  <text x="565" y="115" font-size="15" font-family="Arial" fill="#ff7f0e">Curve 2 (OPC 43 / PPC / PSC)</text>
  <text x="565" y="140" font-size="15" font-family="Arial" fill="#2ca02c">Curve 3 (OPC 53)</text>
</svg>
