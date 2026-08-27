---
layout: archive
title: "NEXQ Lab"
permalink: /nexq/
author_profile: true
---

The <strong>Next-generation EXascale and Quantum systems (NEXQ) lab</strong> works on Quantum Computing Systems, and Resilient HPC and AI Systems.

The NEXQ lab has openings for <strong>self-motivated Ph.D. students</strong>, <strong>M.S. students working towards a thesis</strong>, and <strong>motivated undergraduate students</strong>. If you are interested, please send your CV and transcript to bo.fang@uta.edu.

## Research Directions

### Quantum-HPC Driven Scientific Discovery

<figure style="margin:16px 0 20px;overflow-x:auto;">
  <img src="../images/quantum_hpc_workflow.svg"
       alt="Closed-loop quantum and HPC workflow. Application problems in chemistry and materials, spin and lattice models, and combinatorial optimization are encoded as a Hamiltonian H. Step 1, on the QPU, samples a parameterized circuit to draw basis configurations spanning a low-dimensional candidate subspace. Step 2, on the classical HPC system, projects H onto that subspace and diagonalizes it for the lowest eigenvalue E(theta). Step 3, also on HPC, uses E(theta) as the objective for a classical optimizer, which updates the circuit parameters for the next iteration."
       loading="lazy"
       style="width:100%;min-width:720px;height:auto;display:block;">
</figure>

Quantum processors are best understood not as replacements for classical computing but as a new class of accelerator in the heterogeneous HPC stack — one whose comparative advantage is sampling from classically intractable probability distributions. We build closed-loop workflows around that division of labor: the QPU proposes a compact candidate subspace, and the classical HPC system solves and refines it at scale.

<!--
### Second Research Direction

Add the title, figure, and description for the second direction here,
following the same pattern as above.
-->

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
