---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

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
</style>

## Research

<style>
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
  width: 100%;
  border-radius: 10px;
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
    <video
      autoplay
      muted
      loop
      playsinline
      poster="{{ site.url }}{{ site.baseurl }}/images/research/poster_1.png">
      <source src="{{ site.url }}{{ site.baseurl }}/images/research/3Dearplug_1kHz_KE.mp4"
              type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>

  <div class="research-content">
    <h4>Example Research Project (Video)</h4>
    <p>
        High sound pressure levels (SPL) pose notable risks in loud environments, particularly due to noise-induced hearing loss. Ill-fitting earplugs often lead to sound leakage, a phenomenon this study seeks to investigate. To validate our methodology, we first obtained computational and experimental acoustic transmission data for stand-alone slit resonators and orifices, for which extensive published data are readily available for comparison. We then examined the frequency-dependent acoustic power absorption coefficient and transmission loss (TL) across various leakage geometries, modeled using different orifice diameters. Experimental approaches spanned a frequency range of 1–5 kHz under SPL conditions of 120–150 dB. Key findings reveal that unsealed silicone rubber earplugs demonstrate an average TL reduction of approximately 18 dB at an overall incident SPL (OISPL) of 120 dB. Direct numerical simulations further highlight SPL-dependent acoustic dissipation mechanisms, showing the conversion of acoustic energy into vorticity in ill-fitting earplug models at an OISPL of 150 dB. These results highlight the role of earplug design for high-sound-pressure-level environments.
    </p>
  </div>
</div>

<div class="research-item">
  <div class="research-thumb">
    <img src="{{ site.url }}{{ site.baseurl }}/images/research/example2.png"
         alt="Example Research 2">
  </div>
  <div class="research-content">
    Example Research Project Two
    <p>
      We focus on data-driven approaches and interdisciplinary methods to
      explore complex interactions across multiple scales, with applications
      in science and engineering.
    </p>
  </div>
</div>

<div class="research-item">
  <div class="research-thumb">
    <img src="{{ site.url }}{{ site.baseurl }}/images/research/example3.png"
         alt="Example Research 3">
  </div>
  <div class="research-content">
    <h4>Example Research Project Three</h4>
    <p>
      This research develops new frameworks for analysis and simulation,
      enabling improved accuracy and efficiency in large-scale systems.
    </p>
  </div>
</div>

<div class="research-item">
  <div class="research-thumb">
    <img src="{{ site.url }}{{ site.baseurl }}/images/research/example1.png"
         alt="Example Research 1">
  </div>
  <div class="research-content">
    <h4>Example Research Project One</h4>
    <p>
      This project studies example phenomena using advanced theoretical
      and computational techniques. The goal is to understand underlying
      mechanisms and develop predictive models applicable to real-world systems.
    </p>
  </div>
</div>
