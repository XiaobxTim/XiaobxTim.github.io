---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

[Download PDF CV](/files/Benxiang_Xiao_CV.pdf)

Education
======
**Southern University of Science and Technology**, Shenzhen, Guangdong, China  
*B.S. in Data Science, Junior Year*  
2023 - Present

* Cumulative GPA: 3.45/4.0 (Rank: 58/74); Major GPA: 3.56/4.0 (Rank: 47/74)
* Courses: Discrete Mathematics, Probability Theory and Mathematical Statistics, Data Structures and Algorithms, Operations Research and Optimization, Advanced Natural Language Processing, Distributed Storage and Parallel Computing
* Research Interests: ML Systems, Efficient LLM Inference, Distributed Systems, HPC

Publication
======
* Jiahao Fan, Zongsheng Li, **Benxiang Xiao**, Qingzhu Zhang, Xinke Shen, and Quanying Liu. "Semantic-guided Contrastive Learning for EEG Decoding of Video Semantics." To appear in *Proceedings of the 2025 China Automation Congress (CAC)*. IEEE, 2025. Paper ID: CCHI2025-121657.

Skills
======
* Programming: Python, C/C++, Java, Shell, CUDA, SIMD, OpenMP
* Frameworks: PyTorch, TensorFlow, PyTorch Lightning, MindSpore
* Profiling: Kunpeng DevKit, VTune, PyTorch Profiler, IPM, HipProf, MindSpore Profiler, Nsight Systems
* Languages: English, Chinese (native)

Research & Engineering Experience
======
**Efficient Inference for Large Models** | Research Intern  
*With the group of Prof. Tianwei Zhang, Nanyang Technological University (NTU)*  
Oct. 2025 - Present

* Investigating inference-efficient methods for large models, including token compression for video large models and parallel decoding strategies for diffusion language models.
* Investigated systems-oriented approaches for accelerating dynamic inference workloads while preserving model quality.

**Distributed Training Theory** | Research Intern  
*With the group of Prof. Zhi Wang, Tsinghua Shenzhen International Graduate School (Tsinghua SIGS)*  
Jun. 2025 - Feb. 2026

* Studied theoretical aspects of efficient distributed training in cloud-edge-end architectures, including derivations for optimization behavior and convergence-related analysis.
* Explored the rationality of Adam convergence.

**High-Frequency Financial Data Distributed Computing** | Developer  
*Course Project, Ranked Top 1% in Performance Benchmark*  
Sep. 2025 - Dec. 2025

* Built a high-concurrency quantitative factor calculation system for limit order book data on HDFS and MapReduce, optimizing key compression, shuffle, object reuse, and custom CSV parsing to reduce network I/O and GC overhead.
* Achieved a 13x speedup over the baseline with near C/C++-level efficiency in course evaluation while preserving numerical precision.

**2025 APAC HPC-AI Competition** | Core Member  
Jun. 2025 - Nov. 2025

* Optimized NWChem through compilation refactoring and communication tuning; profiled DeepSeek-R1 (671B) on multi-node GPU clusters with Nsight Systems and SGLang Profiler to identify scaling bottlenecks.
* Achieved a 4.82x speedup for NWChem on a single node and improved DeepSeek-R1 throughput by about 70% through TP/DP/PP tuning and backend benchmarking.

**MindSpore Model Development Competition** | Team Leader  
Oct. 2025 - Nov. 2025

* Profiled DeepSeek-MoE-16B and Qwen1.5-MoE using MindSpore Profiler; optimized expert routing, sparse GEMM, and memory fragmentation bottlenecks; implemented a fused Softmax + TopK operator.
* Designed a dual-path inference engine for Prefill and Decode, reducing decoding latency by about 80% and improving end-to-end MoE inference throughput.

**2nd SUSTech SuperComputing Competition** | Team Leader  
Jul. 2025 - Aug. 2025

* Implemented a high-performance HGEMM kernel using WMMA on Tensor Cores, with size-specific tiling, double buffering, asynchronous caching, register swizzling, and loop unrolling.
* Achieved performance competitive with or exceeding cuBLAS in selected small-to-medium matrix settings while maintaining numerical accuracy.

**2025 ASC Student Supercomputer Challenge** | Core Member  
Jan. 2025 - Feb. 2025

* Profiled the baseline workflow for m5C site detection, identified `hisat-3n-table` as the major bottleneck, and optimized synchronization, threading strategy, and MPI-based pipeline execution.
* Reduced overall runtime by 7.0x while preserving the accuracy and reliability of the detection workflow.

**9th Huawei ICT Competition Chinese National Finals** | Team Leader  
Feb. 2025 - Mar. 2025

* Profiled the Hypre library with Kunpeng DevKit, optimized sparse solver kernels with SVE intrinsics, and improved PCG convergence behavior within the BoomerAMG framework.
* Improved computational efficiency by about 30% for large-scale sparse matrix solving on the Kunpeng platform.

Selected Academic Engagements
======
**SupercomputingAsia (SCA)**  
Mar. 2025 & Jan. 2026

Participated in the Student Cluster Competition Workshop at SCA, broadening exposure to HPC systems, large-scale computing, and performance engineering.

**Huawei Kunpeng Technical Exchange Activities**  
Dec. 2024

Attended Huawei Kunpeng technical exchange activities related to ARM-based HPC software optimization and performance tuning.

Leadership & Community
======
**SuperComputing Club Leader, SUSTech**  
Jun. 2025 - Present

Organized training and project collaboration for students interested in AI systems and HPC, covering CUDA, profiling, and competition-oriented system optimization.

Honors and Awards
======
* 3rd Place (Onsite), 8th Place (Overall), IndySCC25, Nov. 2025
* Achievement Prize, ISC25 Student Cluster Competition, Jun. 2025
* Second Class Prize, 2025 ASC Student Supercomputer Challenge, Feb. 2025
* Second Class Prize; Excellent AI Performance, 2025 APAC HPC-AI, Nov. 2025
* Third Class Prize, 9th Huawei ICT Competition Chinese National Finals, Mar. 2025
* Achievement Prize, MindSpore Model Development Competition, Nov. 2025
* Bronze Prize, MindSpore Model Fine-tuning Track, Aug. 2024
* Bronze Prize, 2024 Kunpeng Application Innovation Competition, Dec. 2024
* First Prize, SUSTech SuperComputing Competition, Aug. 2025
* Campus Academic Star, Southern University of Science and Technology, Sep. 2024
* Outstanding Student, Southern University of Science and Technology, Sep. 2025
