---
layout: page
title: NYSolarForecastLab
description: Reproducible machine-learning benchmarks for day-ahead photovoltaic power forecasting.
importance: 1
category: research
related_publications: true
---

NYSolarForecastLab is the reference implementation for a day-ahead photovoltaic power forecasting benchmark covering solar plants in New York State.

The repository provides a reproducible command-line workflow for preparing plant configurations, running model benchmarks, resuming interrupted experiments, monitoring progress, and exporting results. It includes linear, tree-based, recurrent, convolutional, and Transformer baselines across multiple weather and numerical weather prediction feature sets.

- [Source code](https://github.com/zhesun-0209/NYSolarForecastLab)
- [Paper](https://doi.org/10.1016/j.tra.2026.105040)
- [Research dataset](https://doi.org/10.7910/DVN/3VKAGM)

The code is released under the MIT License. Three example plants are included so the benchmark can be reproduced without downloading the full research dataset.
