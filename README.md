# Kion FinOps+ · Design CAB

An English, 20-slide technical design presentation for the Cloud FinOps & Governance service. It covers the platform deployment, network, identity, cloud integrations, account lifecycle, allocation, governance and service handover.

The deployment, network and dataflow slides hold empty slots for the diagrams. Business Case budgets and metric slides belong to the separate Business Case presentation.

## Controls

| Action | Input |
| --- | --- |
| Next slide | Right / Down arrow, PageDown, Space, scroll, swipe |
| Previous slide | Left / Up arrow, PageUp |
| First / last slide | Home / End |
| Full screen | F |
| Enlarge diagram | Select a diagram |
| Close diagram | Escape |
| Jump to a section | Bottom navigation |

Below 900px wide, or on very short screens, the deck becomes a single scrolling column.

## Diagrams

Save the files next to index.html as `diagrams/deployment.png`, `diagrams/network.png` and `diagrams/dataflow.png`. Each one appears in its slot automatically and enlarges on selection.

## Implementation

One self-contained index.html with embedded Inter font files. The animated background is written in WebGL2: particle shapes are generated in Web Workers and rendered with bloom. It reduces its quality on slower graphics hardware and respects the reduced-motion setting. See DESIGN.md for the design rules.
