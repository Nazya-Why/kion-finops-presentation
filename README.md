# Kion FinOps+ · Design CAB

An English, 20-slide technical design presentation for the Cloud FinOps & Governance service. It covers the platform deployment, network, identity, cloud integrations, account lifecycle, allocation, governance and service handover.

The original animated ribbon and embedded deployment, network and dataflow figures are retained. Business Case budgets and metric slides belong to the separate Business Case presentation.

## Controls

| Action | Input |
| --- | --- |
| Next slide | Right / Down arrow, PageDown, Space, scroll |
| Previous slide | Left / Up arrow, PageUp |
| First / last slide | Home / End |
| Full screen | F |
| Enlarge diagram | Select a diagram |
| Close diagram | Escape |

Keyboard navigation responds immediately. Wheel navigation retains the original transition. On touch devices the deck becomes a vertical document, with keyboard controls also supported.

## Implementation

One self-contained index.html with embedded diagrams and a WebGL ribbon background. Typography uses the platform system font stack without a remote font dependency. All panels and tables share one CSS glass material; SVG displacement is disabled to avoid distorted panel edges. See DESIGN.md for the layout and material rules.
