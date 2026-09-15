---
layout: single
title: "Gallery"
permalink: /gallery/
author_profile: true
---

## Rotating-disk turbulent boundary layer

The following are two visualizations from direct numerical simulations (DNS) of the rotating-disk (von Kármán) three-dimensional turbulent boundary layer, performed using <a href="https://neko.cfd">Neko</a>

<div class="gallery-video-col" style="display:flex;flex-direction:column;gap:2rem;">
  <div style="width:100%;max-width:900px;margin:0 auto;">
    <div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;max-width:100%;">
      <iframe
        src="https://www.youtube.com/embed/0UHivhiAfdY?si=IxYcC4ZzxVSLL9E"
        title="High Re_tau turbulent boundary layer simulation"
        style="position:absolute;top:0;left:0;width:100%;height:100%;border:0;"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        referrerpolicy="strict-origin-when-cross-origin"
        allowfullscreen>
      </iframe>
    </div>
    <p style="text-align:center;">APS Gallery of Fluid Motion 2026 submission for an extreme-scale DNS of the rotating-disk turbulent boundary layer up to $Re_\tau = 2300$ with 52 million spectral elements (18 billion grid points), performed using 3072 GH200 superchips on JUPITER</p>
  </div>

  <div style="width:100%;max-width:900px;margin:0 auto;">
    <div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;max-width:100%;">
      <iframe
        src="https://www.youtube.com/embed/OjCGm2uygX8"
        title="Low Re_tau turbulent boundary layer simulation"
        style="position:absolute;top:0;left:0;width:100%;height:100%;border:0;"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        referrerpolicy="strict-origin-when-cross-origin"
        allowfullscreen>
      </iframe>
    </div>
    <p style="text-align:center;">DNS of the rotating-disk turbulent boundary layer with 3.75 million spectral elements, performed on LUMI</p>
  </div>
</div>


## Jets in cross-flow

Visualizations (Q-criterion isocontours colored by spanwise vorticity) from direct numerical simulations (DNS) of a laminar tabbed jet in cross-flow, for jet-to-cross-flow velocity ratios of $R = 2$ and $R = 4$ and tab positions of $\phi = 0^\circ$ (upstream) and $\phi = 45^\circ$, performed using MPCUGLES-Overset

<div class="gallery-video-row" style="display:flex;flex-wrap:nowrap;gap:1rem;justify-content:center;">
  <div style="flex:1 1 50%;min-width:0;">
    <video controls style="width:100%;height:auto;">
      <source src="/videos/JICF_R2_upstream.mp4" type="video/mp4">
    </video>
    <p style="text-align:center;">$R = 2$, $\phi = 0^\circ$</p>
  </div>

  <div style="flex:1 1 50%;min-width:0;">
    <video controls style="width:100%;height:auto;">
      <source src="/videos/JICF_R2_45deg.mp4" type="video/mp4">
    </video>
    <p style="text-align:center;">$R = 2$, $\phi = 45^\circ$</p>
  </div>
</div>

<div class="gallery-video-row" style="display:flex;flex-wrap:nowrap;gap:1rem;justify-content:center;margin-top:2rem;">
  <div style="flex:1 1 50%;min-width:0;">
    <video controls style="width:100%;height:auto;">
      <source src="/videos/JICF_R2_upstream.mp4" type="video/mp4">
    </video>
    <p style="text-align:center;">$R = 4$, $\phi = 0^\circ$</p>
  </div>

  <div style="flex:1 1 50%;min-width:0;">
    <video controls style="width:100%;height:auto;">
      <source src="/videos/JICF_R4_45deg.mp4" type="video/mp4">
    </video>
    <p style="text-align:center;">$R = 4$, $\phi = 45^\circ$</p>
  </div>
</div>
