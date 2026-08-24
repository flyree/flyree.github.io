---
layout: archive
title: "Research"
permalink: /projects/
author_profile: true
---

<style>
  .pillars-grid{
    display:grid;
    gap:24px;
    grid-template-columns:1fr;
    margin:16px 0 32px;
    align-items:start;
  }
  @media (min-width:900px){
    .pillars-grid{ grid-template-columns:repeat(2,minmax(0,1fr)); }
  }
  .pillar-card{
    border:1px solid #e3e3e3;
    border-radius:10px;
    padding:20px 22px;
    background:#fff;
  }
  .pillar-card.resilient{ border-top:4px solid #2b6cb0; }
  .pillar-card.quantum{ border-top:4px solid #b83280; }
  .pillar-card h3{ margin-top:0; }
  .pillar-tag{
    display:inline-block;
    font-size:0.75em;
    font-weight:600;
    letter-spacing:0.03em;
    text-transform:uppercase;
    padding:2px 8px;
    border-radius:12px;
    margin-bottom:8px;
  }
  .pillar-card.resilient .pillar-tag{ background:#ebf4ff; color:#2b6cb0; }
  .pillar-card.quantum .pillar-tag{ background:#fbe8f4; color:#b83280; }
</style>

My research spans two connected pillars: <strong>Resilient HPC and AI Systems</strong>, which makes large-scale computing and learning systems dependable in the presence of faults, and <strong>Quantum Computing Systems</strong>, which makes quantum computation practical to simulate, characterize, and apply.

<div class="pillars-grid" markdown="1">

<div class="pillar-card resilient" markdown="1">
<span class="pillar-tag">Pillar 1</span>

### Resilient HPC and AI Systems

Silent data corruption, soft errors, and storage faults quietly undermine the correctness of large-scale scientific and machine learning workloads. This pillar builds methodologies and tools that measure, predict, and tolerate those failures across the stack: <strong>error resilience characterization</strong> for GPU and HPC applications, <strong>fault injection frameworks</strong> from the IR level to mixed-precision accelerators, <strong>fault tolerance for LLM training and inference</strong>, and <strong>precision-aware recovery</strong>.

<span style="color:blue">Publications</span>: Demystifying LLM Inference Resilience (SC '25), FT2 (HPDC '25), ATTNChecker (PPoPP '25), Parallel File System Metadata Corruption (IPDPS '25), MPGemmFI (Cluster '24), Storage Faults in HPC (Cluster '21), BonVoision (ICS '19), LetGo (HPDC '17), ePVF (DSN '16), GPU-Qin (ISPASS '14)

</div>

<div class="pillar-card quantum" markdown="1">
<span class="pillar-tag">Pillar 2</span>

### Quantum Computing Systems

Quantum hardware is noisy and quantum state spaces are enormous, so understanding what a quantum program actually does requires systems research. This pillar covers <strong>scalable quantum circuit simulation</strong> on HPC platforms, <strong>quantum noise characterization and mitigation</strong> on NISQ devices, <strong>reproducibility of quantum results</strong>, and <strong>quantum machine learning and applications</strong>.

<span style="color:blue">Publications</span>: Quantum Sampling for Protein Structure (SC '26), QDockBench (SC '25), BMQSim (ICS '25), Red-QAOA (ASPLOS '24), PQML (QCE '24), Reproducibility on NISQ Devices (QCE '23), Hierarchical State Vector Simulation (Cluster '22), NISQ Reliability Degradation (QCE '22), SV-Sim (SC '21), QuGAN (QCE '21)

</div>

</div>
