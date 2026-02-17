---
layout: paper
title: Modeling and Optimizing the Provisioning of Exhaustible Capabilities for Simultaneous Task Allocation and Scheduling
image: /papers/images/2026-park-TRAITS.png
authors: Jinwoo Park, Harish Ravichandar, Seth Hutchinson
year: 2026
ref: Park et al., AAMAS 2026.
journal: Autonomous Agents and Multi-Agent Systems (AAMAS) - Oral
arxiv: https://arxiv.org/abs/2602.13866
github: GT-STAR-Lab/TRAITS

---

## TL;DR

We introduce a new simulatenous task allocation and scheduling algorithm that can handle the provisioning of exhaustible resources (e.g., fire suppressant, fuel, etc.) under both spatio-temporal and battery constraints.


## Abstract

Deploying heterogeneous robot teams to accomplish multiple tasks over extended time horizons presents significant computational challenges for task allocation and planning. In this paper, we present a comprehensive, time-extended, offline heterogeneous multi-robot task allocation framework, TRAITS, which we believe to be the first that can cope with the provisioning of exhaustible traits under battery and temporal constraints. Specifically, we introduce a nonlinear programming-based trait distribution module that can optimize the trait provisioning rate of coalitions to yield feasible and time-efficient solutions. TRAITS provides a more accurate feasibility assessment and estimation of task execution durations and makespan by leveraging trait provisioning rates while optimizing battery consumption --- an advantage that state-of-the-art frameworks lack. We evaluate TRAITS against two state-of-the-art frameworks, with results demonstrating its advantage in satisfying complex trait and battery requirements while remaining tractable.
