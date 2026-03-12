---
layout: single
title: Models
permalink: /models/
---

## ECOSMO_E2E-MERCY-GOTM
<div style="display: flex; align-items: flex-start; gap: 20px; flex-wrap: wrap;">
  <div style="flex: 1; min-width: 300px;">
    <p>
      ECOSMO_E2E-MERCY-GOTM couples the ECOSMO E2E ecosystem model with GOTM hydrodynamics and the MERCY mercury module to study mercury cycling in marine ecosystems. This configuration explicitly resolves both inorganic Hg (iHg) and methylmercury (MeHg) speciation, connecting atmospheric deposition to bioaccumulation in mid-trophic level fish. The model can capture key ecosystem processes, including DOM cycling, benthic-pelagic coupling, and trophic transfer of mercury across multiple species and compartments. It is validated against observations from the Baltic and Mediterranean Seas.  
      <br><em>Refs:</em> <a href="https://bg.copernicus.org/articles/22/7929/2025/bg-22-7929-2025.pdf">Baltic Hg cycling</a>, <a href="https://bg.copernicus.org/articles/22/7425/2025/bg-22-7425-2025.pdf">Mediterranean Hg modelling</a>
    </p>
  </div>
  <div style="flex: 1; min-width: 300px; text-align: center;">
    <img src="/assets/images/Nioz.jpg" alt="ECOSMO_E2E-MERCY-GOTM Model" style="max-width: 100%; height: auto;"/>
  </div>
</div>

## ECOSMO_FS-MERCY-GOTM
<div style="display: flex; align-items: flex-start; gap: 20px; flex-wrap: wrap;">
  <div style="flex: 1; min-width: 300px; order: 2;">
    <p>
      ECOSMO_FS-MERCY-GOTM builds on the previous configuration by incorporating explicit **feeding strategy dynamics**. This model explores how different trophic behaviors and prey selection influence MeHg bioaccumulation across mid-trophic fish and benthic consumers. By linking prey composition, DOM uptake, and demethylation rates to mercury accumulation, the model provides insight into how biological interactions can amplify or dampen Hg transfer in marine food webs.  
      <br><em>Ref:</em> <a href="https://bg.copernicus.org/articles/22/7483/2025/bg-22-7483-2025.pdf">Feeding strategy model</a>
    </p>
  </div>
  <div style="flex: 1; min-width: 300px; text-align: center; order: 1;">
    <img src="/assets/images/Nioz.jpg" alt="ECOSMO_FS-MERCY-GOTM Model" style="max-width: 100%; height: auto;"/>
  </div>
</div>

## **ECOSMO-Sponge**
<div style="display: flex; align-items: flex-start; gap: 20px; flex-wrap: wrap;">
  <div style="flex: 1; min-width: 300px;">
    <p>
      The ECOSMO‑Sponge configuration couples a one‑dimensional hydrodynamic model (GOTM) with an ecosystem model (ECOSMO E2E) and a mercury cycling and speciation module (MERCY v2.0) to simulate bioaccumulation of Hg in marine food webs. It explicitly resolves iHg and MeHg speciation across trophic levels and links atmospheric Hg deposition to concentrations in mid-trophic fish. The model uniquely incorporates sponge feeding strategies, including DOM uptake, to explore how varying sponge communities modulate Hg transfer. This setup captures both water bioconcentration and trophic biomagnification in benthic ecosystems.
    </p>
  </div>
  <div style="flex: 1; min-width: 300px; text-align: center;">
    <img src="/assets/images/Nioz.jpg" alt="ECOSMO-Sponge Model" style="max-width: 100%; height: auto;"/>
  </div>
</div>
