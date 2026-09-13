---
title: 'cuEvo: Massively Parallel Interaction-Aware Evolutionary Planning on GPUs for Real-Time Urban Driving'
date: '2026-09-13'
publishDate: '2026-09-13'
authors:
- Yandong Luo
- Sen Na
- Lu Gan
publication_types:
- '4'
abstract: >-
  Real-time trajectory optimization for autonomous driving requires reasoning over
  non-convex vehicle constraints and interactions with multiple traffic
  participants, making long-horizon planning computationally demanding. Although
  population-based evolutionary methods can handle non-smooth objectives without
  analytical gradients, their large-scale candidate evaluation and irregular
  operations limit real-time deployment. We present cuEvo, a CUDA-native
  evolutionary planner that combines interpretable behavior reasoning with
  massively parallel continuous trajectory optimization. An intention graph and a
  lane-level Markov decision process generate admissible maneuver tasks, which are
  optimized concurrently on the GPU. Each candidate represents steering and
  acceleration profiles using compact B&eacute;zier parameterization and is rolled
  out through a kinematic vehicle model. cuEvo exposes hierarchical parallelism
  across maneuver tasks, population candidates, trajectory timesteps, and
  surrounding agents. It further redesigns evolutionary operators through
  warp-coherent crossover, fused GPU kernels, and parallel population ranking,
  keeping the complete optimization loop resident on the GPU. On the nuPlan
  benchmark, cuEvo optimizes a 10s horizon at 0.2s resolution in less than 10ms per
  planning cycle. It outperforms all evaluated learning-based baselines, while
  remaining competitive with state-of-the-art model-based planners. These results
  establish cuEvo as an efficient framework for interpretable, long-horizon, and
  real-time urban driving.
featured: false
draft: false
publication: '*A short version has been accepted in IROS 2026 PPNIV Workshop*'
tags: [cs.RO]
---
