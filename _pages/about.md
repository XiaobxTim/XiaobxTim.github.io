---
permalink: /
title: "Homepage"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>

I am **Benxiang Xiao**, a junior undergraduate student majoring in **Data Science** at the **Southern University of Science and Technology (SUSTech)**.

My interests lie in **machine learning systems**, **efficient LLM inference**, **distributed systems**, and **high performance computing**. I work on systems-oriented problems around large-model inference, distributed training, GPU kernel optimization, profiling, and performance engineering.

**Research keywords:** ML Systems / Efficient LLM Inference / Distributed Systems / HPC / GPU Computing / Performance Optimization

<span class="anchor" id="news"></span>

# News

* *2026.06*: Launched this academic homepage for research, engineering projects, competitions, awards, and CV.
* *2025.11*: Received Second Class Prize and Excellent AI Performance in the 2025 APAC HPC-AI Competition.
* *2025.11*: Received the Achievement Prize in the MindSpore Model Development Competition.
* *2025.08*: Won First Prize in the SUSTech SuperComputing Competition.
* *2025.03*: Received Third Class Prize in the 9th Huawei ICT Competition Chinese National Finals.
* *2025.02*: Received Second Class Prize in the 2025 ASC Student Supercomputer Challenge.
* *2024.09*: Named Campus Academic Star at Southern University of Science and Technology.

<span class="anchor" id="publications"></span>

# Publications

1. Jiahao Fan, Zongsheng Li, **Benxiang Xiao**, Qingzhu Zhang, Xinke Shen, and Quanying Liu. "Semantic-guided Contrastive Learning for EEG Decoding of Video Semantics." To appear in *Proceedings of the 2025 China Automation Congress (CAC)*. IEEE, 2025. Paper ID: CCHI2025-121657.

<span class="anchor" id="research-engineering"></span>

# Research & Engineering

## Efficient Inference for Large Models

**Research Intern**, with the group of Prof. Tianwei Zhang, Nanyang Technological University (NTU)  
*Oct. 2025 - Present*

I investigate inference-efficient methods for large models, including token compression for video large models and parallel decoding strategies for diffusion language models. My focus is on systems-oriented acceleration methods that preserve model quality while reducing dynamic inference cost.

* Topics: efficient inference, token compression, video large models, diffusion language models.
* Focus: model quality preservation under reduced inference cost.
* Direction: practical acceleration strategies for dynamic large-model workloads.

## Distributed Training Theory

**Research Intern**, with the group of Prof. Zhi Wang, Tsinghua Shenzhen International Graduate School (Tsinghua SIGS)  
*Jun. 2025 - Feb. 2026*

I studied theoretical aspects of efficient distributed training in cloud-edge-end architectures, including derivations for optimization behavior and convergence-related analysis.

* Topics: distributed training, cloud-edge-end systems, optimization behavior.
* Work: convergence-related derivations and analysis.
* Additional exploration: rationality of Adam convergence.

## High-Frequency Financial Data Distributed Computing

**Developer**, course project ranked Top 1% in performance benchmark  
*Sep. 2025 - Dec. 2025*

I built a high-concurrency quantitative factor calculation system for limit order book data on HDFS and MapReduce.

* Optimized key compression, shuffle, object reuse, and custom CSV parsing.
* Reduced network I/O and garbage collection overhead.
* Achieved a **13x speedup** over the baseline while preserving numerical precision.

<span class="anchor" id="competitions-projects"></span>

# Competitions & Projects

## 2025 APAC HPC-AI Competition

**Core Member**  
*Jun. 2025 - Nov. 2025*

* Optimized NWChem through compilation refactoring and communication tuning.
* Profiled DeepSeek-R1 (671B) on multi-node GPU clusters with Nsight Systems and SGLang Profiler.
* Achieved a **4.82x speedup** for NWChem on a single node.
* Improved DeepSeek-R1 throughput by about **70%** through TP/DP/PP tuning and backend benchmarking.

## MindSpore Model Development Competition

**Team Leader**  
*Oct. 2025 - Nov. 2025*

* Profiled DeepSeek-MoE-16B and Qwen1.5-MoE using MindSpore Profiler.
* Optimized expert routing, sparse GEMM, and memory fragmentation bottlenecks.
* Implemented a fused Softmax + TopK operator.
* Designed a dual-path inference engine for Prefill and Decode, reducing decoding latency by about **80%**.

## 2nd SUSTech SuperComputing Competition

**Team Leader**  
*Jul. 2025 - Aug. 2025*

* Implemented a high-performance HGEMM kernel using WMMA on Tensor Cores.
* Used size-specific tiling, double buffering, asynchronous caching, register swizzling, and loop unrolling.
* Achieved performance competitive with or exceeding cuBLAS in selected small-to-medium matrix settings.

## 2025 ASC Student Supercomputer Challenge

**Core Member**  
*Jan. 2025 - Feb. 2025*

* Profiled the baseline workflow for m5C site detection.
* Identified `hisat-3n-table` as the major bottleneck.
* Optimized synchronization, threading strategy, and MPI-based pipeline execution.
* Reduced overall runtime by **7.0x** while preserving accuracy and reliability.

## 9th Huawei ICT Competition Chinese National Finals

**Team Leader**  
*Feb. 2025 - Mar. 2025*

* Profiled the Hypre library with Kunpeng DevKit.
* Optimized sparse solver kernels with SVE intrinsics.
* Improved PCG convergence behavior within the BoomerAMG framework.
* Improved computational efficiency by about **30%** for large-scale sparse matrix solving on Kunpeng.

<span class="anchor" id="honors-awards"></span>

# Honors & Awards

* *2025.11*: 3rd Place (Onsite), 8th Place (Overall), IndySCC25.
* *2025.06*: Achievement Prize, ISC25 Student Cluster Competition.
* *2025.02*: Second Class Prize, 2025 ASC Student Supercomputer Challenge.
* *2025.11*: Second Class Prize; Excellent AI Performance, 2025 APAC HPC-AI.
* *2025.03*: Third Class Prize, 9th Huawei ICT Competition Chinese National Finals.
* *2025.11*: Achievement Prize, MindSpore Model Development Competition.
* *2024.08*: Bronze Prize, MindSpore Model Fine-tuning Track.
* *2024.12*: Bronze Prize, 2024 Kunpeng Application Innovation Competition.
* *2025.08*: First Prize, SUSTech SuperComputing Competition.
* *2024.09*: Campus Academic Star, Southern University of Science and Technology.
* *2025.09*: Outstanding Student, Southern University of Science and Technology.

<span class="anchor" id="academic-engagements"></span>

# Selected Academic Engagements

* *Mar. 2025 & Jan. 2026*: Participated in the Student Cluster Competition Workshop at SupercomputingAsia (SCA), broadening exposure to HPC systems, large-scale computing, and performance engineering.
* *Dec. 2024*: Attended Huawei Kunpeng technical exchange activities related to ARM-based HPC software optimization and performance tuning.

<span class="anchor" id="leadership"></span>

# Leadership

**SuperComputing Club Leader, SUSTech**  
*Jun. 2025 - Present*

I organize training and project collaboration for students interested in AI systems and HPC, covering CUDA, profiling, and competition-oriented system optimization.

<span class="anchor" id="education"></span>

# Education

**Southern University of Science and Technology**, Shenzhen, Guangdong, China  
*B.S. in Data Science, Junior Year*  
2023 - Present

* Cumulative GPA: **3.45/4.0** (Rank: 58/74)
* Major GPA: **3.56/4.0** (Rank: 47/74)
* Selected courses: Discrete Mathematics, Probability Theory and Mathematical Statistics, Data Structures and Algorithms, Operations Research and Optimization, Advanced Natural Language Processing, Distributed Storage and Parallel Computing

<span class="anchor" id="skills"></span>

# Skills

* **Programming:** Python, C/C++, Java, Shell, CUDA, SIMD, OpenMP
* **Frameworks:** PyTorch, TensorFlow, PyTorch Lightning, MindSpore
* **Profiling:** Kunpeng DevKit, VTune, PyTorch Profiler, IPM, HipProf, MindSpore Profiler, Nsight Systems
* **Languages:** English, Chinese (native)

<span class="anchor" id="contact"></span>

# Contact

* Email: [12312422@mail.sustech.edu.cn](mailto:12312422@mail.sustech.edu.cn)
* GitHub: [github.com/XiaobxTim](https://github.com/XiaobxTim)
* CV: [Web CV](/cv/) / [PDF CV](/files/Benxiang_Xiao_CV.pdf)
