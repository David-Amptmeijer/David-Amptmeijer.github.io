---
layout: single
title: Models
permalink: /models/
---

<style>
.model-row {
  display: flex;
  flex-wrap: wrap;
  align-items: flex-start;
  gap: 40px;
  margin-bottom: 60px;
  width: 100vw; /* full viewport width */
  max-width: 1200px; /* optional max width for readability */
  margin-left: calc(-50vw + 50%); /* center the row */
}

.model-text, .model-image {
  flex: 1 1 45%; /* expand to almost half the container */
  min-width: 300px;
}

.model-image img {
  width: 100%;
  height: auto;
  display: block;
}
</style>

## ECOSMO_E2E-MERCY-GOTM
<div class="model-row">
  <div class="model-text">
    <p>
      ECOSMO_E2E-MERCY-GOTM couples the ECOSMO E2E ecosystem model with GOTM hydrodynamics and the MERCY mercury module to study mercury cycling in marine ecosystems. This configuration explicitly resolves both inorganic Hg (iHg) and methylmercury (MeHg) speciation, connecting atmospheric deposition to bioaccumulation in mid-trophic level fish. It captures key ecosystem processes, including DOM cycling, benthic-pelagic coupling, and trophic transfer of mercury across multiple species and compartments. Validated against observations from the Baltic and Mediterranean Seas.  
      <br><em>Refs:</em> <a href="https://bg.copernicus.org/articles/22/7929/2025/bg-22-7929-2025.pdf">Baltic Hg cycling</a>, <a href="https://bg.copernicus.org/articles/22/7425/2025/bg-22-7425-2025.pdf">Mediterranean Hg modelling</a>
    </p>
  </div>
  <div class="model-image">
    <img src="/assets/images/Ecosmo.png" alt="ECOSMO_E2E-MERCY-GOTM Model"/>
  </div>
</div>

## ECOSMO_FS-MERCY-GOTM
<div class="model-row">
  <div class="model-image">
    <img src="/assets/images/Models.png" alt="ECOSMO_FS-MERCY-GOTM Model"/>
  </div>
  <div class="model-text">
    <p>
      ECOSMO_FS-MERCY-GOTM incorporates explicit **feeding strategy dynamics**. This model explores how trophic behaviors and prey selection influence MeHg bioaccumulation in mid-trophic fish and benthic consumers. By linking prey composition, DOM uptake, and demethylation rates to Hg accumulation, it shows how biological interactions amplify or dampen Hg transfer in marine food webs.  
      <br><em>Ref:</em> <a href="https://bg.copernicus.org/articles/22/7483/2025/bg-22-7483-2025.pdf">Feeding strategy model</a>
    </p>
  </div>
</div>

## ECOSMO-Sponge
<div class="model-row">
  <div class="model-text">
    <p>
      The ECOSMO‑Sponge configuration couples GOTM hydrodynamics, the ECOSMO E2E ecosystem model, and MERCY v2.0 to simulate Hg bioaccumulation in marine food webs. It explicitly resolves iHg and MeHg across trophic levels and links atmospheric Hg deposition to mid-trophic fish concentrations. Incorporates sponge feeding strategies including DOM uptake, exploring how sponge communities modulate Hg transfer. Captures water bioconcentration and trophic biomagnification in benthic ecosystems.
    </p>
  </div>
  <div class="model-image">
    <img src="/assets/images/SpongeGraphicalAbstract.png" alt="ECOSMO-Sponge Model"/>
  </div>
</div>
