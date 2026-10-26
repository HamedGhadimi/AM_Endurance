---
title: "Characterizing the Printed Part in Metal Additive Manufacturing (L-PBF & EBM) - Overview: What to Measure and How"
excerpt: "This project maps what has to be known about a printed powder bed fusion part — its geometry, surface, internal integrity, microstructure, chemistry and residual stress — and which techniques can measure each quantity, organised by measurand rather than by instrument, into a single, navigable reference."
date: 2026-10-25
permalink: /characterizing-printed-part-overview/
categories: [Characterization]
tags: [AM,characterization,metrology,NDE,metallography,L-PBF,EBM,Additive-Manufacturing]
toc: true
toc_label: "Contents"
header:
  <!-- overlay_image: /assets/images/Additive Manufacturing Metal Powder Characteristics and Tests-Header1.jpg-->
  overlay_image: /assets/images/am_endurance_powder_network_wallpaper.svg
  overlay_filter: 0.55
  caption: "Characterizing the Printed Part in Metal Additive Manufacturing (L-PBF & EBM) - Overview: What to Measure and How"
---

<!-- This is a comment — invisible on the website -->
<!-- 
Comment
Commetn
-->

## Introduction
------

Every qualified AM part comes down to a set of measurements. Is the shape right? Is the surface acceptable? Is the part sound inside? Is the microstructure the one the process was meant to produce, is the chemistry within specification, and what stress state does the part carry? Each of these questions can be answered by several techniques — and on an as-built powder bed fusion part, those techniques frequently disagree.

Characterization is usually organised by instrument: a CT report, a metallography section, a CMM printout. That is how laboratories are organised, but it is not how engineering questions arrive. Porosity is the clearest case: Archimedes, a polished section and X-ray CT all report it, each samples a different volume at a different resolution, and their numbers rarely match. Knowing which quantity you actually need — and why valid methods give different answers for it — comes before choosing the instrument.

## Scope
------

This map focuses specifically on:

* The as-built printed part — what has to be known about it and which techniques can measure it, with notes on how heat treatment, HIP and surface finishing change what is measured.
* Laser Powder Bed Fusion (L-PBF) and Electron Beam Powder Bed Fusion (EB-PBF), with Ti-6Al-4V as the priority alloy for worked examples, followed by the stainless steels.
* Six measurand families — geometry, surface, internal integrity, microstructure, chemistry and residual stress — each tied to the ASTM and ISO standards that define or govern it.

In-situ process monitoring, mechanical testing and powder characterization are outside this map, and lattice structures are treated as notes inside the relevant nodes rather than as a branch of their own. Techniques appear here only as short pointer nodes; their full treatment belongs to the four technique maps that follow in this sub-series.

> This is a live project — built to the best of my current knowledge and intended to evolve. There may be inaccuracies, and there is always room for improvement.

## Objectives
------

The objective of this project is to organise part characterization by measurand — what you want to know — rather than by instrument, so that an engineer can trace the chain from a question about the part → the quantity that answers it → the techniques that can measure it → the standard that defines it, and understand why two valid techniques can report different numbers for the same feature. The map connects:

* Each measurand — what the quantity is, why it matters in a powder bed fusion part, and, where relevant, how acceptance limits are reasoned — explained in depth, with an everyday comparison alongside the technical explanation wherever one clarifies it
* Each measurand to the techniques that can measure it, and each technique to what it can and cannot see — sampled volume, resolution, surface versus bulk, destructive versus non-destructive
* Each claim to its source — every node carries its peer-reviewed or standards reference directly in the description, and every quantitative value is tied to the alloy and condition it came from

## Explore the Interactive Map
------ 
<p style="text-align:left;">
  <a href="https://embed.kumu.io/103581ee55f29e015189fc95c5ea5c1e"
     target="_blank"
     class="btn">
     🔍 Open Fullscreen Interactive Map
  </a>
</p>

<iframe
    src="https://embed.kumu.io/103581ee55f29e015189fc95c5ea5c1e"
    width="940"
    height="600"
    frameborder="0">
</iframe>

## Executive Summary
------

The map organizes 63 elements around a single root question — what do we need to know about a printed part? — through 6 branches comprising 29 measurands, 21 technique pointers and 6 standards, connected through 113 relationships. Colour marks the branch and shape marks the role, so the difference between a quantity to be known, a technique that measures it and a standard that defines it is visible at a glance:

* __Geometry — Dimensional Metrology__: Whether the part has the right shape — its size, form, orientation and location of features, distortion, smallest printable features, and internal channels. It matters because AM parts shrink and distort, and a rough as-built surface makes even "where the surface is" depend on the instrument used.
* __Surface — Surface Metrology__: What the as-built surface looks like — roughness, waviness, areal texture, adhered particles and spatter, and the difference between up-facing and down-facing surfaces. It matters because surface notches are where fatigue cracks start in as-built parts, and because the surface controls cleaning, coating and, for implants, contact with bone.
* __Internal Integrity — NDE__: Whether the part is sound inside — density, pores, cracks, inclusions and trapped powder, and the non-destructive methods that find them. It matters because internal and near-surface flaws drive fatigue scatter, and because different methods report different values for the same porosity.
* __Microstructure — Metallography & Microscopy__: What the material is made of at the micro scale — grains, crystallographic texture, phases, melt pool boundaries, sub-grain cells and precipitates. It matters because AM microstructures are far from those of wrought or cast material, and they set the strength, ductility and anisotropy of the part.
* __Composition — Chemical Analysis__: Whether the part's chemistry meets specification — major alloying elements, oxygen, nitrogen and hydrogen, carbon and sulfur, and elements lost during the build. It matters because part chemistry can drift from the powder certificate through evaporation and powder reuse.
* __Residual Stress — Stress Measurement__: What stress the part carries with no load applied — from stresses across the whole component down to stresses within single grains. It matters because residual stress distorts and cracks parts and lowers fatigue life, and because each measurement method sees only part of it.

This is the overview map of the AM Endurance sub-series Characterizing the Printed Part. Four technique maps follow, each giving full treatment to the instruments that appear here only as pointers: geometry and surface metrology; non-destructive evaluation; metallography, microscopy and residual stress; and chemical analysis.
