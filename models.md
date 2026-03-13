---
layout: splash
title: Models
permalink: /models/
header:
  overlay_image: /images/SouthernOcean.jpg
  overlay_filter: 0.35
---

<style>
.model-row {
  display: flex;
  flex-wrap: wrap;
  align-items: flex-start;
  gap: 40px;       /* space between text and image */
  margin-bottom: 60px;
}

.model-text, .model-image {
  flex: 1 1 45%;   /* roughly half the row each */
  min-width: 300px; /* ensures stacking on small screens */
}

.model-image img {
  width: 100%;
  height: auto;
  display: block;
}
</style>

## [ECOSMO_E2E-MERCY-GOTM](https://bg.copernicus.org/articles/22/7929/2025/bg-22-7929-2025.pdf)
<div class="model-row">
  <div class="model-text">
    <p>
      ECOSMO_E2E-MERCY-GOTM couples the ECOSMO E2E ecosystem model with GOTM hydrodynamics and the MERCY mercury module to study mercury cycling in marine ecosystems. Explicitly resolves iHg and MeHg speciation, linking atmospheric deposition to bioaccumulation in mid-trophic level fish. Captures DOM cycling, benthic-pelagic coupling, and trophic Hg transfer.
    </p>
  </div>
  <div class="model-image">
    <img src="/images/Ecosmo.png" alt="ECOSMO_E2E-MERCY-GOTM Model"/>
  </div>
</div>

## [ECOSMO_FS-MERCY-GOTM](https://bg.copernicus.org/articles/22/7483/2025/bg-22-7483-2025.pdf)
<div class="model-row">
  <div class="model-image">
    <img src="/images/Model.png" alt="ECOSMO_FS-MERCY-GOTM Model"/>
  </div>
  <div class="model-text">
    <p>
      ECOSMO_FS-MERCY-GOTM adds feeding strategy dynamics, exploring how prey selection and trophic behavior influence MeHg bioaccumulation. Focuses on linking MeHg bioaccumulation at higher trophic levels to feeding strategy at the base of the food web.
    </p>
  </div>  
</div>

## [ECOSMO-Sponge](https://egusphere.copernicus.org/preprints/2025/egusphere-2025-5377/egusphere-2025-5377.pdf)
<div class="model-row">
  <div class="model-text">
    <p>
      ECOSMO‑Sponge couples GOTM, ECOSMO E2E, and MERCY v2.0 to simulate Hg bioaccumulation. Resolves iHg and MeHg across trophic levels and links atmospheric deposition to mid-trophic fish concentrations. Incorporates sponge feeding strategies including DOM uptake to study how sponge communities modulate Hg transfer. Captures both water bioconcentration and trophic biomagnification in benthic ecosystems.
    </p>
  </div>
  <div class="model-image">
    <img src="/images/SpongeGraphicalAbstract.png" alt="ECOSMO-Sponge Model"/>
  </div>
</div>
