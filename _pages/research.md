---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---
## Research

<div markdown="0">

<style>
img{
  border-radius: 10px;
}
.col-md-3 {
  margin-top:10px;
  margin-bottom:10px;
  padding:0px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  background: white;
  border-radius: 20px;
  height: auto;
}
iframe {
  margin:0;
  padding:0;
  width: 175px;
  display: inline;
  vertical-align: middle;
}
.research-item {
  display: flex;
  gap: 20px;
  padding: 20px 0;
  border-bottom: 1px solid #e0e0e0;
}

.research-item:last-child {
  border-bottom: none;
}

.research-thumb {
  flex: 0 0 180px;
}

.research-thumb img {
  width: 120%;
  border-radius: 15px;
}

.research-content {
  flex: 1;
}

.research-content h4 {
  margin-top: 0;
  margin-bottom: 8px;
}

.research-content p {
  margin-bottom: 0;
  text-align: justify;
}

@media (max-width: 768px) {
  .research-item {
    flex-direction: column;
  }
  .research-thumb {
    max-width: 100%;
  }
}

.research-thumb video {
  width: 100%;
  border-radius: 10px;
  display: block;
  background: #000;
}

.research-thumb video[poster] {
  object-fit: cover;
}
</style>

<div class="research-item">
  <div class="research-thumb">
    <video autoplay muted loop playsinline>
      <source src="{{ site.url }}{{ site.baseurl }}/images/research_1/3Dearplug_1kHz_KE.mp4"
              type="video/mp4">
    </video>
  </div>

  <div class="research-content">
    <h4>Leakage in ill-fitting earplugs</h4>
    <p>
      High sound pressure levels (SPL) pose notable risks in loud environments, particularly due to noise-induced hearing loss. Ill-fitting earplugs often lead to sound leakage, a phenomenon this study seeks to investigate.
    </p>
    <details class="abstract-details">
      <summary>Read full abstract</summary>
      To validate our methodology, we first obtained computational and experimental acoustic transmission data for stand-alone slit resonators and orifices, for which extensive published data are readily available for comparison. We then examined the frequency-dependent acoustic power absorption coefficient and transmission loss (TL) across various leakage geometries, modeled using different orifice diameters. Experimental approaches spanned a frequency range of 1–5 kHz under SPL conditions of 120–150 dB. Key findings reveal that unsealed silicone rubber earplugs demonstrate an average TL reduction of approximately 18 dB at an overall incident SPL (OISPL) of 120 dB. Direct numerical simulations further highlight SPL-dependent acoustic dissipation mechanisms, showing the conversion of acoustic energy into vorticity in ill-fitting earplug models at an OISPL of 150 dB. These results highlight the role of earplug design for high-sound-pressure-level environments.
    </details>
  </div>
</div>

<div class="research-item">
  <div class="research-thumb">
    <video autoplay muted loop playsinline>
      <source src="{{ site.url }}{{ site.baseurl }}/images/research_2/Slit.mp4"
              type="video/mp4">
    </video>
  </div>

  <div class="research-content">
    <h4>Dissipation mechanism of acoustically-driven slit</h4>
    <p>
      We quantify how incident acoustic energy is converted into vortical motion and viscous dissipation for a two-dimensional plane-wave passing through a slit geometry. 
    </p>
    <details class="abstract-details">
      <summary>Read full abstract</summary>
      We perform direct numerical simulations over a broad parameter space in incident sound pressure level (ISPL), Strouhal number (St), and Reynolds number (Re). Spectral proper orthogonal decomposition (SPOD) yields energy-ranked coherent structures at each frequency, from which we construct mode-by-mode fields for spectral kinetic energy (KE) and viscous loss (VL) components to examine the mechanisms of acoustic absorption. At ISPL=150dB, the acoustic-hydrodynamic energy conversion is highest when the acoustic displacement amplitude is comparable to the slit thickness, corresponding to a Keulegan-Carpenter number of order unity. In this regime, the oscillatory boundary layer undergoes periodic separation, resulting in vortex shedding that dominates acoustic damping. VL accounts for 20-60% of the KE contribution. For higher acoustic frequencies, the confinement of the Stokes layer produces X-shaped near-slit modes, reducing the total energy input by approximately 50%. The influence of Re depends on amplitude. At ISPL=150dB, larger Re values correspond to suppressed broadband fluctuations and sharpened harmonic peaks. At ISPL = 120dB, the boundary layers remain attached, vortex shedding is weak, absorption monotonically scales with viscosity, and the Re- and St-dependencies become comparable. Across all conditions, more than 99% of the VL is confined to a compact region surrounding the slit mouth. The KE-VL spectra describe parameter regimes that enhance or suppress acoustic damping in slit geometries, providing a physically interpretable basis for acoustic-based design.
    </details>
  </div>
</div>

<div class="research-item">
  <div class="research-thumb">
    <img
      src="{{ site.baseurl }}/images/research_3/Exp_img.png"
      alt="O-ring seal experiment setup"
      style="width:100%; height:auto;"
    />
  </div>

  <div class="research-content">
    <h4>High-amplitude Impedance Measurements</h4>
    <p>
    This study introduces an impulse technique for measuring acoustic transmission loss. A two-sided impedance tube is crafted for the effort.
    </p>
    <details class="abstract-details">
      <summary>Read full abstract</summary>
      Compared to wave-decomposition methods, the approach reduces complexity and cost, particularly at sound pressure levels (SPL=120dB).
      The tube's O-ring sealing minimizes leakage, yielding facility-related and thermoviscous losses below 1.5dB for 1-5kHz. Experiments on steel plates with circular orifices (area ratios 0.5--100%) at 120dB agree with analytical predictions, with discrepancies less than 4dB. These results demonstrate the practical effectiveness of the impulse-based measurement on this impedance tube.
    </details>
  </div>
</div>


<div class="research-item">
  <div class="research-thumb">
  <video autoplay muted loop playsinline>
    <source src="{{ site.url }}{{ site.baseurl }}/images/research_4/seed.mp4"
            type="video/mp4">
  </video>
  </div>

  <div class="research-content">
    <h4>Biodegradable seed carrier</h4>
    <p>
    A bio-inspired, sustainable seed carrier designed for electronic-free seed dispersal, triggered only by a user-defined wind direction and speed, offers a novel approach to autonomous and eco-friendly agriculture. 
    </p>
    <details class="abstract-details">
      <summary>Read full abstract</summary>
      Fabricated using biodegradable PLA filaments via 3D printing, the system features a bistable seed holder with a carefully engineered geo-metrical design capable of securely storing seeds with preloaded elastic energy.
      When deployed in environments, natural wind generates torque in the seed carrier, altering the energy landscape of the holder. Upon reaching a critical torque, the bistable interaction transitions to a monostable state, enabling precise and controlled seed ejection at a prescribed wind speed and direction. The entire process is governed by the geometry of the seed carrier and holder, with behavior accurately modeled using high- fidelity numerical simulations. Thousands of geometric designs are simulated to compute critical torque and ejection energy, enabling inverse design optimization for targeted deployment performance. Wind tunnel experiments validate the model and confirm the effectiveness of the design. Inspired by natural seed dispersal strategies and leveraging bistable principles, this system offers diverse applications, including fertilizer distribution, environmental sensing using color-changing materials, and passive tagging with embedded QR codes, providing a scalable and eco-friendly solution for precision agriculture and ecological restoration.
    </details>
  </div>
</div>

<div class="research-item">
  <div class="research-thumb">
    <video autoplay muted loop playsinline>
      <source src="{{ site.url }}{{ site.baseurl }}/images/research_5/flapping_trim.mp4"
              type="video/mp4">
    </video>
  </div>

  <div class="research-content">
    <h4>Flapping wing micro air vehicle</h4>
    <p>
    Vibrational stability is a natural phenomenon where a system if vibrating at sufficiently high frequencies, can bring itself back into a stable state if perturbed.
    </p>
    <details class="abstract-details">
      <summary>Read full abstract</summary>
      This is akin to the high frequency flapping that hummingbirds and insects employ to maintain a hovering position and fly. Micro Air Vehicles (MAV) are a subset of air vehicles that have a size restriction and are commonly used for commercial, military, and reconnaissance purposes where larger devices are not feasible. With the idea of combining vibrational stability with micro air vehicle restrictions, we aim to study and manufacture a mechanism capable of producing this flapping motion and conduct performance testing to compare a manufactured “quadflapper” with more conventional quadcopters/drones. Preliminary performance testing between a “quadflapper” utilizing a passive pitching, flapping mechanism found in a toy and a similar set-up that replaced the toy mechanism with propellors was conducted. These two set-ups differed only in their lift mechanism and a circuit board. 
    </details>
  </div>
</div>


</div>
