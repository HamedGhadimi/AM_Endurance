---
title: "Mapping Defects and Flaws in Metal Additive Manufacturing (L-PBF & EBM)"
excerpt: "This project maps the defects and flaws found in printed metal parts from Laser Powder Bed Fusion (L-PBF) and Electron Beam Powder Bed Fusion (EB-PBF or EBM) — connecting each defect's manifestation, root cause, and relationship to other defects into a single, navigable reference."
date: 2026-06-29
permalink: /defects-and-flaws/
categories: [Defects]
tags: [AM, defects, flaws, L-PBF, EBM, EB-LPBF, Additive-Manufacturing]
toc: true
toc_label: "Contents"
header:
  <!-- overlay_image: /assets/images/Additive Manufacturing Metal Powder Characteristics and Tests-Header1.jpg-->
  overlay_image: /assets/images/am_endurance_powder_network_wallpaper.svg
  overlay_filter: 0.55
  caption: "Metal AM Defects & Flaws Map — AM Endurance"
---

## Introduction
------

Defects determine whether an L-PBF or EB-PBF part is qualification-ready or scrap, and every defect carries two separate stories: what it looks like, and why it happened. Most taxonomies in the literature classify defects by the first story alone — porosity, cracking, rough surface — without consistently tracing the second.

That gap matters because most defects in powder bed fusion are multi-causal. A pore can be a parameter artifact, a contamination artifact, and a thermal artifact at once, and forcing it into a single category erases exactly the information an engineer needs to act on.

## Scope
------

This map focuses specifically on:

* Defects and flaws found in printed L-PBF and EB-PBF metal parts, from the as-built state through initial post-build handling and support removal

* Each defect's manifestation — where it appears and how it's typically detected — tracked separately from its root cause(s)

* L-PBF and EB-PBF processes exclusively

> This is a living reference, refined through ongoing review — defect terminology and root-cause attribution will continue to evolve as new failure data and literature emerge.

## Objectives
------

This project maps the defects and flaws found in printed metal parts from Laser Powder Bed Fusion (L-PBF) and Electron Beam Powder Bed Fusion (EBM) — connecting each defect's manifestation, root cause, and relationship to other defects into a single, navigable reference. The objective of this project is to create a practical, decision-oriented reference that connects:

* Each defect or flaw — what it is, where it manifests (surface, bulk, geometrical, or layer-level), and its engineering significance

* Its root cause(s) — tagged explicitly across every applicable category rather than forced into one bucket, since most defects here are multi-causal

* Its relationships to other defects — which defects trigger, compound, or co-occur with which, mapped as causal connections rather than left implicit

## Explore the Interactive Map
------ 
<p style="text-align:left;">
  <a href="https://embed.kumu.io/d65b2ab0fd97ecb72e94a6d9b0a08d0b"
     target="_blank"
     class="btn">
     🔍 Open Fullscreen Interactive Map
  </a>
</p>

<iframe
    src="https://embed.kumu.io/d65b2ab0fd97ecb72e94a6d9b0a08d0b"
    width="940"
    height="600"
    frameborder="0">
</iframe>

## Executive Summary
------

The map organizes 26 defects and flaws — plus 2 contributing process phenomena — into 6 root-cause categories:

* __Energy & Process Parameter-Induced__: The largest category. Laser/beam power, scan speed, hatch spacing, and layer thickness drive defects such as Porosity, Lack of Fusion, and Balling.

* __Geometry & Design-Induced (DfAM)__: Overhang angle, feature size, and part orientation drive defects such as Drooping, Trapped Powder, and Missing Features.

* __Contamination & Environment-Induced__: Oxygen, moisture, and build-atmosphere quality drive defects such as Inclusion, Oxide Film / Interlayer Oxidation, and Surface Discoloration.

* __Thermal & Residual Stress-Induced__: Thermal gradients and differential contraction drive defects such as Hot and Cold Cracking, Warping/Distortion, and Delamination & Layer Separation.

* __Mechanical & Equipment-Induced__: Recoater/rake hardware and platform stability drive defects such as Recoater/Rake Streak Marks, Layer Shift, and Skipped Layer.

* __Post-Processing-Induced__: Support removal and part handling drive defects such as Residual Support Material and Scratch, Tool Marks, Dents & Burrs.

Two entries — __Spattering & Splattering__ and __Vapor Plume Attenuation & Laser Window Contamination__ — are tracked as process phenomena rather than defects in their own right. Both recur as the shared root cause behind several entries above (Inclusion, Lack of Fusion, Porosity, Oxide Film) and are referenced explicitly rather than only described inline.
