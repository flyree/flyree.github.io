---
layout: archive
title: "NEXQ Lab"
permalink: /nexq/
author_profile: false
---

The <strong>Next-generation EXascale and Quantum systems (NEXQ) lab</strong> works on Quantum Computing Systems, and Resilient HPC and AI Systems.

## Research Directions

### Quantum-HPC Driven Scientific Discovery

<style>
  .direction-split{
    display:grid;
    gap:28px;
    grid-template-columns:1fr;
    align-items:center;
    margin:16px 0 24px;
  }
  @media (min-width:900px){
    /* Give the wide figure the larger share; the summary is short */
    .direction-split{ grid-template-columns:minmax(0,1.35fr) minmax(0,1fr); }
  }
  .direction-split__figure{ overflow-x:auto; margin:0; }
  .direction-prose{ max-width:68ch; }
  .direction-split__figure img{ width:100%; height:auto; display:block; }
</style>

<div class="direction-split">

<figure class="direction-split__figure">
  <img src="../images/quantum_hpc_workflow.svg"
       alt="Closed-loop quantum and HPC workflow. Application problems in chemistry and materials, spin and lattice models, and combinatorial optimization are encoded as a Hamiltonian H. Step 1, on the QPU, samples a parameterized circuit to draw basis configurations spanning a low-dimensional candidate subspace. Step 2, on the classical HPC system, projects H onto that subspace and diagonalizes it for the lowest eigenvalue E(theta). Step 3, also on HPC, uses E(theta) as the objective for a classical optimizer, which updates the circuit parameters for the next iteration."
       loading="lazy">
</figure>

<div markdown="1">
A quantum processor is not a replacement for a classical computer — it is a new kind of accelerator. What it does best is sample from probability distributions that classical machines cannot reach. We design workflows that let each machine do what it is good at: the quantum processor proposes a small, promising subspace, and the HPC system solves and refines it at scale.
</div>

</div>

### AI–HPC Co-Design

<!--
When a figure is ready, wrap this section in a <div class="direction-split">
with a <figure class="direction-split__figure"> ahead of the text, exactly as
the first direction does above.
-->

<div class="direction-prose" markdown="1">
AI workloads have distinctive properties — predictable scaling, precision tolerance, structured communication, fault sensitivity — that should guide HPC system design. In return, well-designed systems make AI faster, more reliable, and more reproducible. This co-design loop determines how fast and how trustworthy AI-driven discovery can be.
</div>

## PhD Students

<style>
  .students-grid{
    display:grid;
    gap:18px;
    align-items:start;
    margin:12px 0 28px;
    grid-template-columns:repeat(2,minmax(0,1fr));
  }
  @media (min-width:700px){
    .students-grid{ grid-template-columns:repeat(3,minmax(0,1fr)); }
  }
  @media (min-width:1000px){
    .students-grid{ grid-template-columns:repeat(4,minmax(0,1fr)); }
  }
</style>

<!--
To add a student, copy one block below, drop the headshot in /images/, and
point its src at the new file.
-->

<div class="students-grid">

  <div style="text-align:center;">
    <img src="../images/avatar-placeholder.svg" alt="Mark Dubynskyi" style="width:128px;height:128px;object-fit:cover;border-radius:50%;display:block;margin:0 auto 10px;">
    <div><strong>Mark Dubynskyi</strong></div>
    <ul style="list-style:disc;margin:4px auto 0;padding-left:18px;text-align:left;display:inline-block;line-height:1.1;">
      <li style="margin:0;"><small>Also affiliated with the Department of Mathematics</small></li>
    </ul>
  </div>

  <div style="text-align:center;">
    <img src="../images/Zubair.jpg" alt="Zubair Faruqui" style="width:128px;height:128px;object-fit:cover;border-radius:50%;display:block;margin:0 auto 10px;">
    <div><strong>Zubair Faruqui</strong></div>
    <ul style="list-style:disc;margin:4px auto 0;padding-left:18px;text-align:left;display:inline-block;line-height:1.1;">
      <li style="margin:0;"><small><a href="https://zubairfaruqui10.github.io/">Website</a></small></li>
    </ul>
  </div>

</div>
