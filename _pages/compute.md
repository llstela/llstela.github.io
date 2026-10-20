---
permalink: /compute/
title: "Research Compute Resources"
excerpt: "H100 compute access and the training budget available for research collaborations."
author_profile: true
---

<a class="compute-back" target="_self" href="{{ '/' | relative_url }}">&larr; Back to homepage</a>

# Research Compute Resources

I have access to up to **128 NVIDIA H100 GPUs on TSUBAME4.0** at the Institute of Science Tokyo for independent, open-ended research and collaborations.

<div class="compute-summary">
  <div class="compute-summary__item"><strong>128 H100s</strong><span>Up to approximately 128 days of equivalent continuous use at standard priority.</span></div>
  <div class="compute-summary__item"><strong>4&times; usage</strong><span>Highest-priority jobs consume four times the points of otherwise identical standard-priority jobs.</span></div>
  <div class="compute-summary__item"><strong>24 H100s, 24/7</strong><span>A sustainable highest-priority training budget through March 31, 2027.</span></div>
</div>

## How the allocation works

The current compute-point allocation can support roughly **128 H100s running continuously for 128 days at standard priority** (`-5`). This is an equivalent compute budget, rather than a dedicated reservation of 128 GPUs.

At the **highest priority** (`-3`), point consumption is **4&times;** that of the same job at standard priority. Spread across the remaining allocation period, the budget supports approximately **24 H100s running continuously each day through March 31, 2027**, with a small margin for other usage. Larger runs can use the same budget over a shorter period.

GPU access is scheduled: both ordinary and highest-priority jobs may queue. The estimates assume full-node GPU allocations and requested wall times close to actual runtimes. They reflect the shared group's remaining budget as of **October 21, 2026**, and will change with usage. These estimates apply only to the current allocation, **through March 31, 2027**. **The allocation will be renewed after March 31, 2027**; the available training budget will then be recalculated against the new allocation.

For scheduling and accounting details, see the [TSUBAME4.0 job guide](https://www.t4.cii.isct.ac.jp/docs/all/handbook.en/jobs/) and [official charging rules](https://www.t4.cii.isct.ac.jp/sites/default/files/2026-03/Charging_Rules.pdf).

Interested in collaborating on world models or multimodal learning? Please get in touch using the contact links on my profile.
