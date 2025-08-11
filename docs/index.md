---
title: Biased SD Video Generation
---

# Biased SD Video Generation
_Ajitesh Bankula • RPI_

> Measuring and mitigating visual drift in diffusion pipelines using optical flow and activation/“neural noise” tracking.

**Quick links:** [Code](https://github.com/ajiteshbankulaa/BiasedSDVideoGeneration) · [Data](./data/) · [Results](./results/) · [License](#license)

---

## Overview
This project investigates consistency issues in diffusion-based video generation and proposes metrics and interventions to reduce visual drift. We explore optical-flow-based stability measures and neuron/activation probes that correlate with cinematic style features, then test targeted adjustments to improve temporal coherence.

## Data
Small sample files live in **Data → samples** (kept under Git LFS). Full datasets are linked on the Data page and Releases. (go to quick links at top to access)

## Results
Key figures, tables, and short reports are listed on the Results page. (go to quick links at top to access)

## Cite
```bibtex
@misc{bankula2025biasedsd,
  title={Biased SD Video Generation: Measuring and Mitigating Visual Drift in Diffusion Pipelines},
  author={Bankula, Ajitesh},
  year={2025},
  howpublished={\url{https://ajiteshbankulaa.github.io/BiasedSDVideoGeneration/}},
  note={Version 0.1}
}
```

## License
This project is licensed under the **Apache License 2.0**. See the
[LICENSE file on GitHub](https://github.com/ajiteshbankulaa/BiasedSDVideoGeneration/blob/main/LICENSE).

---
_Last updated: {{ site.time | date: "%Y-%m-%d" }}_
