---
theme: default
title: Pandoro - Sustainable GPU Infrastructure
info: |
  ## Pandoro
  GPU Infrastructure for ML Research Teams

  Sustainable AI presentation by Keenan Johnson
class: text-center bg-pan
colorSchema: light
highlighter: shiki
drawings:
  persist: false
transition: slide-left
mdc: true
fonts:
  sans: 'Inter'
  serif: 'Spectral'
  mono: 'Fira Code'
---

<style>
@import './style.css';
</style>

# Pandoro

## GPU Infrastructure for ML Research Teams

<div class="pt-12">
  <span class="px-2 py-1 rounded text-sm btn-crust">
    Powered by Clean Energy
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://pandoro.today" target="_blank" class="text-sm text-crust opacity-70 hover:opacity-100">
    pandoro.today
  </a>
</div>

---
class: bg-bright
---

# Enterprise GPU Infrastructure

<div class="grid grid-cols-2 gap-8 pt-2">
  <div>
    <img src="/h100-server-rack.png" class="rounded-lg shadow-lg w-full object-contain" />
    <ul class="pt-3 text-dark text-lg list-disc pl-4">
      <li><strong>NVIDIA DGX H100</strong>: $200,000 - $300,000+</li>
      <li><strong>Power draw</strong>: 10kW per system</li>
      <li><strong>Cooling</strong>: Specialized data center required</li>
    </ul>
  </div>
  <div class="flex items-center justify-center">
    <img src="/nvidia-dgx-h100-angle4.jpg" class="rounded-lg shadow-lg w-full max-h-96 object-contain" />
  </div>
</div>

---
class: bg-bright
---

# Science

<img src="/underwater-ml.png" class="rounded-lg shadow-lg w-full max-h-96 object-contain mx-auto" />

---
layout: two-cols
class: bg-bright
---

# The Problem

Research teams conducting ML experiments face an impossible situation:

<v-clicks>

- The upsides of Machine Learning for science are too good to be ignored
- **Experiments that should take hours take months** without GPU acceleration
- Navigating **financial uncertainty** with usage-based pricing
- **Institutional red tape** and IT approval delays
- Proprietary infrastructure that **undermines reproducibility**

</v-clicks>

::right::

<div class="pl-8 pt-8 bg-bright h-full">

<div class="p-6 text-dark">

**What you need:**

- GPUs
- High RAM
- Substantial storage

**What's unclear:**

- How to access it affordably
- How to avoid queue delays
- How to ensure reproducibility

</div>

</div>

---
class: bg-dark
---

# The Four Barriers Researchers Face

<div class="grid grid-cols-2 gap-8 pt-4">

<div v-click>

### Financial Barriers
- Usage-based pricing creates unpredictable costs
- Hidden data transfer and storage fees
- Hardware purchases hard to justify early-stage

</div>

<div v-click>

### Institutional Barriers
- IT approval processes delay acquisition
- Multi-week queue delays for shared resources
- Mandated environments vs. research needs

</div>

<div v-click>

### Reproducibility Barriers
- Cloud providers hide hardware specs
- Results can't be validated without environment info
- Inconsistent hardware across institutions

</div>

<div v-click>

### Operational Barriers
- Vendor lock-in with proprietary configs
- Data transfer fees block migration
- No clear path to scale

</div>

</div>

---
layout: center
class: text-center bg-bright
---

# Pandoro: The Solution

<div class="text-2xl pt-4 pb-8 text-dark">
Dedicated consumer GPU systems at <span class="text-crust font-semibold">fixed monthly pricing</span><br/>
with <span class="text-crust font-semibold">complete hardware transparency</span>
</div>

<div class="grid grid-cols-2 gap-4 text-left">

<div class="card-pan">

### Dedicated Access
No shared queues, no IT approval, immediate access

</div>

<div class="card-pan">

### Full Transparency
Complete specs disclosed for reproducible research

</div>

<div class="card-pan">

### Fixed Pricing
Run unlimited experiments without tracking usage

</div>

<div class="card-pan">

### Clean Energy
Powered by Seattle's ~90% renewable grid

</div>

</div>

---
class: bg-dark
---

# Why This Approach Works

<v-clicks>

## **Hyperscalers sell infrastructure. We provide access to computers.**

You don't need deployment pipelines, auto-scaling groups, or infrastructure orchestration. You need to run ML experiments on reliable hardware with known specifications.

## **Fixed pricing solves the prediction problem.**

AWS, Google Cloud, and Azure offer reserved instances requiring accurate future capacity predictions. You cannot predict experiment duration when exploring new methodologies.

## **Research needs transparency, not abstraction.**

Hyperscalers abstract hardware behind instance types and virtualization layers. We provide complete hardware specifications because scientific publication requires reproducible computational environments.

</v-clicks>

---
class: bg-light
---

# Clean Energy Computing

<div class="grid grid-cols-2 gap-8 pt-8">

<div>

## Pacific Northwest Renewable Energy

Our infrastructure runs on Washington state's electrical grid, one of the cleanest in the United States.

<v-clicks>

- **~90% hydroelectric and renewable**
- Minimize environmental impact of compute-intensive research
- Sustainability without premium pricing

</v-clicks>

</div>

<div class="flex flex-col items-center justify-center">

<img src="/PowerMixSeattle.png" class="rounded-lg shadow-lg max-h-72 object-contain" />

<a href="https://www.seattle.gov/city-light/energy/power-supply-and-delivery" target="_blank" class="text-xs opacity-60 pt-2">Source: Seattle City Light</a>

</div>

</div>

---
class: bg-bright
---

# How Pandoro Compares

| | Cloud Providers | University Computing | Hardware Purchase | **Pandoro** |
|---|---|---|---|---|
| **Cost Model** | Usage-based, unpredictable | Free but limited | High upfront | Fixed monthly |
| **Access** | Immediate | Weeks of queue delay | IT approval needed | Immediate |
| **Hardware Specs** | Hidden/abstracted | Often outdated | Known | Fully disclosed |
| **Reproducibility** | Difficult | Inconsistent | Good | Publication-ready |
| **Migration Path** | Vendor lock-in | N/A | N/A | Easy onsite transition |

---
layout: two-cols
class: bg-dark
---

# Who We Support

<v-clicks>

### Domain Scientists
- Visual imaging ML projects
- Teams without ML engineering backgrounds
- Need hardware transparency for publishable results

### Robotics Teams
- Computer vision experiments
- Sensor fusion and autonomous systems
- Need reliable compute without cloud unpredictability

</v-clicks>

::right::

<div class="pl-8 pt-16">

## Common Constraints

<v-clicks>

- Small teams without capital for hardware
- Institutional IT barriers
- Need for reproducible environments
- Must scale with project growth

</v-clicks>

</div>

---
layout: center
class: text-center bg-bright
---

# Onsite Migration Path

<div class="text-xl pt-4 pb-8 text-shade">
Consumer-grade GPU systems enable easy transition to in-house infrastructure
</div>

```mermaid {theme: 'base', themeVariables: {primaryColor: '#EBBC6C', primaryTextColor: '#3D3020', lineColor: '#958A78'}}
flowchart LR
    A[Start with Pandoro] --> B[Validate methodology]
    B --> C[Scale experiments]
    C --> D[Purchase same components]
    D --> E[Deploy locally]

    style A fill:#EBBC6C,color:#3D3020
    style E fill:#3D3020,color:#FBEEDA
```

<div class="pt-4">
<v-click>

**No vendor lock-in. No workflow rewrites. No proprietary configurations.**

</v-click>
</div>

---
class: bg-light
---

# About Bread Board Foundry

<div class="grid grid-cols-2 gap-8 pt-4">

<div>

Pandoro is developed by **Bread Board Foundry** — we build specialized tools for teams working on meaningful, impactful projects.

<v-clicks>

### Our Products
- **Pretzel** — Manufacturing optimization for hardware teams
- **Souffle** — Goal-based planning for hardware leaders
- **Pandoro** — GPU compute for ML research

</v-clicks>

</div>

<div class="flex flex-col justify-center items-center">

<div class="text-4xl pb-4 text-crust font-bold" style="font-family: Spectral, serif;">BBF</div>

*"Forging Software That Speaks Hardware"*

<div class="pt-4">
  <a href="https://breadboardfoundry.com" target="_blank" class="btn-crust">breadboardfoundry.com</a>
</div>

</div>

</div>

---
layout: center
class: text-center bg-crust
---

# Questions?

<div class="pt-8">

Thanks for listening!

<div class="pt-4">
  <a href="https://pandoro.today" target="_blank" class="btn-pan">
    pandoro.today
  </a>
</div>

Full hardware details, pricing structure, and technical specifications.

</div>

<div class="pt-8 text-bright opacity-80">

</div>
