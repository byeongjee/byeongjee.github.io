---
permalink: /
author_profile: true
title: "About"
---


I am a Software Engineering PhD student at Carnegie Mellon University
advised by [Prof. Limin Jia](https://www.andrew.cmu.edu/user/liminjia/).
I develop programming languages and compilers for writing safe and efficient
programs on heterogeneous, resource-constrained devices.


## Publications

{% bibliography --query @inproceedings,@article %}

## Under Review
{% bibliography --query @misc %}

## Preprints
{% bibliography --query @unpublished %}

## Education
- Ph.D. in Software Engineering, [Carnegie Mellon University](https://www.cmu.edu/),
*Aug 2023 — Present*
- B.S. in Computer Science and Engineering & Mathematics,
[Pohang University of Science and Technology (POSTECH)](https://www.postech.ac.kr/eng/),
*Feb 2018 — Feb 2023*
- High school diploma, [Korea Science Academy of KAIST](https://ksa.hs.kr/Eng), *Feb 2015 — Feb 2018*


## Experiences

- Research intern at [Microsoft Research](https://www.microsoft.com/en-us/research/group/datasystems/), *May 2025 -- Aug 2025*
- Research intern at [POSTECH Software Verification Laboratory](http://sv.postech.ac.kr/), *Feb 2022 -- Dec 2022*
- Software engineer at [Kodebox](https://kodebox.io/), *Jan 2020 -- Dec 2021*
- Research intern at [POSTECH Programming Language Laboratory](http://pl.postech.ac.kr/), *Jun 2018 -- Jun 2019*

See my [CV](https://byeongjee.me/assets/cv.pdf) for more information.

## Ongoing Research Projects
- **Automatic Program Rescaling and Migration**: Programming language and runtime
support for automatically rescaling programs for resource-constrained systems
- **Probabilistic Modeling and Analysis Tools for Intermittent System**:
Probabilistic modeling of resource usage in intermittent systems

## Software
- [**Bao**](https://github.com/byeongjee/bao): LLVM toolchain that instruments
programs for batteryless devices by solving a mixed-integer linear program
- [**WAMI**](https://github.com/CMUAbstract/mlir-wasm-dialect): MLIR-based
compilation pipeline for WebAssembly
- [**OCaMI**](https://github.com/byeongjee/ocami): Compiler from a functional
subset of OCaml to WebAssembly through WAMI
- [**rustlane**](https://github.com/byeongjee/rustlane): ISPC-style SPMD
programming for Rust, lowering scalar control flow to masked SIMD
- [**Fray**](https://github.com/cmu-pasta/fray): Controlled concurrency testing
framework for the JVM
- [**heuristic-narrowing-search**](https://github.com/byeongjee/heuristic-narrowing-search):
Maude implementation of narrowing-based symbolic reachability analysis
- [**CodeChain Foundry**](https://github.com/CodeChain-io/foundry): Open-source
blockchain engine based on composable module system

## Talks
- [An MLIR Dialect for WebAssembly (WAW'25)](https://www.youtube.com/watch?v=z2xmzf8f5Ac)

## Honors and Scholarships
- ILJU Fellowship, ILJU Academy and Culture Foundation, *Aug 2023 — Jul 2028*
- Program for Highly Dedicated Students, POSTECH, *Feb 2018 — Feb 2023*
- Presidential Science Scholarship, Ministry of Education of Korea,
*Feb 2018 — Feb 2023*
