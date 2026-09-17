<div align="center">

<h1>BioNode</h1>

<p><strong>AIoT BioCNG Micro-Refinery</strong></p>

<p><em>Water hyacinth in. 200-bar BioCNG out.</em><br>
<em>Autonomously. At the bus terminal.</em></p>

<p><strong>No pipeline. No import. No chemist.</strong></p>

<p>
  <a href="https://mdtasfiquenoor-dev.github.io/BioNode/">Live demo</a>
  ·
  <a href="#overview">Overview</a>
  ·
  <a href="#architecture">Architecture</a>
  ·
  <a href="#impact">Impact</a>
  ·
  <a href="#roadmap">Roadmap</a>
</p>

</div>

---

## Overview

BioNode is an AIoT-powered BioCNG micro-refinery designed to convert locally available biomass, especially water hyacinth, into compressed biomethane for transportation use. The concept combines feedstock handling, anaerobic digestion, gas cleaning, methane enrichment, and high-pressure compression into a compact, distributed energy system.

The system is intended for local deployment near demand centers, reducing reliance on long-distance fuel supply chains while creating a practical pathway for biomass recovery and clean transport fuel generation.

---

## Architecture

<div align="center">

<svg width="960" height="270" viewBox="0 0 960 270" fill="none" xmlns="http://www.w3.org/2000/svg" role="img" aria-labelledby="title desc">
  <title id="title">BioNode architecture overview</title>
  <desc id="desc">Water hyacinth enters the system, feeds the digester, then passes through scrubbing, methane separation, and high-pressure compression to produce 200-bar BioCNG.</desc>
  <rect width="960" height="270" rx="18" fill="#F3F7F4"/>
  <rect x="30" y="82" width="140" height="78" rx="16" fill="#DDEFE2" stroke="#2C7A5B" stroke-width="2"/>
  <text x="100" y="110" text-anchor="middle" font-size="20" font-family="Arial, Helvetica, sans-serif" fill="#1B3A2F" font-weight="700">Water</text>
  <text x="100" y="136" text-anchor="middle" font-size="20" font-family="Arial, Helvetica, sans-serif" fill="#1B3A2F" font-weight="700">Hyacinth</text>

  <rect x="215" y="82" width="150" height="78" rx="16" fill="#E8F0F7" stroke="#3C5E79" stroke-width="2"/>
  <text x="290" y="110" text-anchor="middle" font-size="20" font-family="Arial, Helvetica, sans-serif" fill="#1A2E3B" font-weight="700">Anaerobic</text>
  <text x="290" y="136" text-anchor="middle" font-size="20" font-family="Arial, Helvetica, sans-serif" fill="#1A2E3B" font-weight="700">Digestion</text>

  <rect x="410" y="82" width="150" height="78" rx="16" fill="#F7EBD8" stroke="#B78438" stroke-width="2"/>
  <text x="485" y="110" text-anchor="middle" font-size="20" font-family="Arial, Helvetica, sans-serif" fill="#4C3720" font-weight="700">H₂S</text>
  <text x="485" y="136" text-anchor="middle" font-size="20" font-family="Arial, Helvetica, sans-serif" fill="#4C3720" font-weight="700">Scrubbing</text>

  <rect x="605" y="82" width="170" height="78" rx="16" fill="#E5F0EA" stroke="#2C7A5B" stroke-width="2"/>
  <text x="690" y="110" text-anchor="middle" font-size="20" font-family="Arial, Helvetica, sans-serif" fill="#1B3A2F" font-weight="700">CO₂</text>
  <text x="690" y="136" text-anchor="middle" font-size="20" font-family="Arial, Helvetica, sans-serif" fill="#1B3A2F" font-weight="700">Separation</text>

  <rect x="820" y="82" width="110" height="78" rx="16" fill="#D9EDE7" stroke="#2C7A5B" stroke-width="2"/>
  <text x="875" y="110" text-anchor="middle" font-size="20" font-family="Arial, Helvetica, sans-serif" fill="#1B3A2F" font-weight="700">200 bar</text>
  <text x="875" y="136" text-anchor="middle" font-size="18" font-family="Arial, Helvetica, sans-serif" fill="#1B3A2F" font-weight="700">BioCNG</text>

  <path d="M170 121H215" stroke="#2C7A5B" stroke-width="4" stroke-linecap="round"/>
  <path d="M365 121H410" stroke="#2C7A5B" stroke-width="4" stroke-linecap="round"/>
  <path d="M560 121H605" stroke="#2C7A5B" stroke-width="4" stroke-linecap="round"/>
  <path d="M775 121H820" stroke="#2C7A5B" stroke-width="4" stroke-linecap="round"/>

  <path d="M270 160V200H690V160" stroke="#3C5E79" stroke-width="3" stroke-dasharray="6 8" fill="none"/>
  <rect x="628" y="180" width="136" height="46" rx="12" fill="#FFFFFF" stroke="#3C5E79" stroke-width="2"/>
  <text x="696" y="209" text-anchor="middle" font-size="16" font-family="Arial, Helvetica, sans-serif" fill="#1A2E3B" font-weight="700">AIoT control</text>
</svg>

</div>

The process can be summarized as: biomass feedstock → anaerobic digestion → raw biogas → H₂S scrubbing → CO₂ separation → biomethane → high-pressure compression → 200-bar BioCNG.

---

## Problem statement

- Bangladesh has more than 500,000 CNG vehicles and a strong dependence on imported fuel.
- Water hyacinth is a recurring environmental and economic burden in waterways across the country.
- The challenge is to connect local biomass recovery with reliable transport fuel production without building a large centralized chemical-processing system.

## Target users

- CNG fleet operators and drivers in Dhaka, Chattogram, Sylhet, and Barishal
- Urban transport and logistics operators
- Rural and peri-urban fuel demand centers
- National and regional transport systems looking for local energy resilience

## Proposed solution

BioNode is designed as a compact, site-ready fuel system with the following stages:

1. Feedstock intake using locally available water hyacinth
2. Anaerobic digestion to generate raw biogas
3. H₂S scrubbing to reduce sulfur contamination
4. CO₂ separation to target biomethane quality
5. High-pressure compression to deliver 200-bar BioCNG output

The configuration is intended to operate close to the point of demand, reducing transport losses and avoiding reliance on long-distance fuel supply chains.

---

## Why BioNode matters

### Key differentiators

- Edge-AI autonomy with 24/7 pH, temperature, and gas monitoring
- Zero supply chain: feedstock can be harvested from adjacent canals and waterways
- Compact, end-to-end process in a single containerized system
- Solar-water symbiosis for auxiliary power and monitoring support
- Local fuel generation for transport use near the point of demand

### Potential impact

BioNode aims to address several linked needs in one integrated platform:

- Water hyacinth management
- Local renewable fuel production
- Reduced dependence on imported fuel
- Waste-to-energy conversion
- Automated energy infrastructure
- Renewable-powered auxiliary systems
- Local energy-service opportunities

---

## AIoT control system

BioNode is designed around an intelligent monitoring and control layer that supports safe operation and process optimization.

Sensors → Edge controller → AI-based monitoring → Process optimization → Automated actuation → Gas quality and pressure monitoring

### Monitored parameters

- Temperature
- pH
- Biogas composition
- H₂S concentration
- CH₄ concentration
- Gas pressure
- Electrical load
- Digester conditions

---

## Current development status

- System architecture & AI control design: done
- Functional Edge-AI dashboard prototype: LIVE
- Component BOM (13 items): finalised
- Napkin procurement: in progress
- Dholakhali fabrication order: placed
- Phase 1 CAPEX: BDT 1,46,500 (~$1,330 USD)

---

## Expected impact

- 20% cheaper fuel for 500,000+ drivers
- Eliminates fuel tax burden on CNG imports
- Free waterways remediation (hyacinth removal)
- 30%+ of Bangladesh's waterways affected by hyacinth
- Potential for distributed biomass-to-fuel infrastructure at scale

---

## Market opportunity

- Bangladesh TAM: ~$880M/year (CNG vehicle fuel)
- BioNode EaaS target: 5% share by Year 5 = $44M ARR
- Global TAM (waste biomass markets): $2.6B by 2032
- Carbon credits: $225M-$3.5B/year at a high scale model

This is a practical infrastructure opportunity that combines waste recovery, transport fuel supply, and local energy service delivery.

---

## Roadmap

- Jun 2026: Prototype demo — BEAR Summit, Dhaka
- Jan 2027: 3-unit pilot live — Daily revenue: CES 2027
- 2027: 20-unit Dhaka rollout — Series A raise
- 2028: Regional deployment — Myanmar, Vietnam, Nepal, Pakistan
- 2030: 500 units — Carbon platform and integrated service model
- 2036: BioCNG infrastructure for 1 billion people

---

## Vision

BioNode is not a stand-alone biogas plant. It is an intelligent, distributed biomass-to-fuel infrastructure concept for converting locally available biomass into usable transportation fuel close to where it is needed.

<div align="center">

### Clear the waterways.
### Produce the fuel.
### Power the future.

</div>

---

<div align="center">

<table>
  <tr>
    <td><strong>500K+</strong><br>CNG vehicles in Bangladesh</td>
    <td><strong>95%</strong><br>Fuel import dependency</td>
    <td><strong>200 bar</strong><br>BioCNG output</td>
    <td><strong>≥95%</strong><br>CH₄ target</td>
    <td><strong>$880M</strong><br>Bangladesh fuel market</td>
    <td><strong>Day 1</strong><br>Revenue model</td>
  </tr>
</table>

<p><em>BioNode · Built in Bangladesh. Fuel for the world.</em></p>

</div>

---

<div align="center">

<p><strong>BEAR Summit 2026</strong> · <em>Built for local energy, local mobility, and a cleaner operating model.</em></p>

</div>
