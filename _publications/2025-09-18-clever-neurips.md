---
title: "CLEVER: A Curated Benchmark for Formally Verified Code Generation"
collection: publications
category: conferences
permalink: /publication/2025-09-18-clever-neurips
excerpt: 'We introduce CLEVER, a high-quality, manually curated benchmark of 161 problems for end-to-end verified code generation in Lean.'
date: 2025-09-18
venue: 'NeurIPS 2025 Datasets and Benchmarks Track'
paperurl: 'https://openreview.net/forum?id=IbOacMF5qd'
citation: 'Amitayush Thakur, Jasper Lee, George Tsoukalas, Meghana Sistla, Matthew Zhao, Stefan Zetzsche, Greg Durrett, Yisong Yue, and Swarat Chaudhuri. CLEVER: A Curated Benchmark for Formally Verified Code Generation. In NeurIPS 2025 Datasets and Benchmarks Track, 2025. URL https://openreview.net/forum?id=IbOacMF5qd.'
---

We introduce CLEVER, a high-quality, manually curated benchmark of 161 problems for end-to-end verified code generation in Lean. Each problem consists of (1) the task of generating a specification that matches a held-out ground-truth specification, and (2) the task of generating a Lean implementation that provably satisfies this specification. Unlike prior benchmarks, CLEVER avoids test-case supervision, LLM-generated annotations, and specifications that leak implementation logic or allow vacuous solutions. All outputs are verified post-hoc using Lean's type checker to ensure machine-checkable correctness. We use CLEVER to evaluate several few-shot and agentic approaches based on state-of-the-art language models. These methods all struggle to achieve full verification, establishing it as a challenging frontier benchmark for program synthesis and formal reasoning. Our benchmark can be found on GitHub as well as HuggingFace. All our evaluation code is also available (online)[https://github.com/trishullab/clever-prover]. <!-- TODO: link this -->
