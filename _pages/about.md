---
permalink: /
title:
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>

I am **Benxiang Xiao**, a junior undergraduate student majoring in **Data Science** at the **Southern University of Science and Technology (SUSTech)**.

My work centers on **machine learning systems**, **efficient LLM inference**, **distributed systems**, and **high performance computing**. I focus on large-model inference, distributed training, GPU kernel optimization, profiling, and performance engineering.

**Research keywords:** ML Systems / Efficient LLM Inference / Distributed Systems / HPC / GPU Computing / Performance Optimization

<span class="anchor" id="news"></span>

# News

* *2026.05*: Received Honorable Mention in the 2026 Mathematical Contest in Modeling.
* *2026.02*: Received Second Class Prize in the 2026 ASC Student Supercomputer Challenge.
* *2025.11*: Received Second Class Prize and Excellent AI Performance in the 2025 APAC HPC-AI Competition.
* *2025.11*: Received the Achievement Prize in the MindSpore Model Development Competition.
* *2025.08*: Won First Prize in the SUSTech SuperComputing Competition.
* *2025.03*: Received Third Class Prize in the 9th Huawei ICT Competition Chinese National Finals.

<span class="anchor" id="publications"></span>

# Publications

<div class="paper-box" id="semantic-guided-eeg-decoding">
  <div class="paper-box-image">
    <div>
      <div class="badge">Publication</div>
      <img src="{{ '/images/publication.png' | relative_url }}" alt="Semantic-guided contrastive learning framework for EEG decoding" />
    </div>
  </div>
  <div class="paper-box-text">
    <p><strong>Semantic-guided Contrastive Learning for EEG Decoding of Video Semantics</strong></p>
    <p>Joint work with Jiahao Fan, Zongsheng Li, Qingzhu Zhang, Xinke Shen, and Quanying Liu. This work studies EEG-based decoding of video semantics with semantic-guided contrastive learning.</p>
    <ul>
      <li>Venue: to appear in <strong>CAC 2025</strong>.</li>
      <li>Focus: EEG decoding, semantic representation learning, and contrastive learning.</li>
      <li>Link: <a href="https://doi.org/10.1109/CAC67268.2025.11487820">DOI</a>.</li>
    </ul>
  </div>
</div>

<span class="anchor" id="experience"></span>

# Research & Internship Experience

My current work spans research internships and systems-oriented engineering on large-model inference, distributed training, and GPU sharing. I prefer work that connects model design with concrete performance bottlenecks, profiling traces, and deployable systems.

**GPU Sharing** | Research Intern  
*With the group of Prof. Dingwen Tao, Institute of Computing Technology, Chinese Academy of Sciences (ICT)*  
*Apr. 2026 - Present*

I am working on GPU sharing and resource management for deep learning inference workloads in multi-tenant environments. The goal is to understand shared-GPU bottlenecks and guide better workload placement and scheduling.

**Efficient Inference for Large Models** | Research Intern  
*With the group of Prof. Tianwei Zhang, Nanyang Technological University (NTU)*  
*Oct. 2025 - Present*

I investigate inference-efficient methods for large models, including token compression for video large models and parallel decoding strategies for diffusion language models.

**Distributed Training Theory** | Research Intern  
*With the group of Prof. Zhi Wang, Tsinghua Shenzhen International Graduate School (Tsinghua SIGS)*  
*Jun. 2025 - Feb. 2026*

I study theoretical aspects of efficient distributed training in cloud-edge-end architectures, including derivations for optimization behavior and convergence-related analysis. I also explored the rationality of Adam convergence.

<span class="anchor" id="competitions-projects"></span>

# Competitions & Projects

<div class="paper-box" id="financial-factor-computing">
  <div class="paper-box-image">
    <div>
      <div class="badge">Distributed Computing</div>
      <img src="{{ '/images/高频因子.png' | relative_url }}" alt="High-frequency financial factor distributed computing workflow" />
    </div>
  </div>
  <div class="paper-box-text">
    <p><strong>High-Frequency Financial Data Distributed Computing</strong></p>
    <p>Built a high-concurrency quantitative factor calculation system for limit order book data on HDFS and MapReduce.</p>
    <ul>
      <li>Course project, ranked <strong>Top 1%</strong> in the performance benchmark.</li>
      <li>Optimized key compression, shuffle, object reuse, and custom CSV parsing.</li>
      <li>Achieved a <strong>13x speedup</strong> over the baseline while preserving numerical precision.</li>
    </ul>
  </div>
</div>

<div class="paper-box" id="apac-hpc-ai">
  <div class="paper-box-image">
    <div>
      <div class="badge">HPC-AI Competition</div>
      <img src="{{ '/images/APAC.png' | relative_url }}" alt="APAC HPC-AI optimization roadmap" />
    </div>
  </div>
  <div class="paper-box-text">
    <p><strong>2025 APAC HPC-AI Competition</strong></p>
    <p>Core member for NWChem optimization and DeepSeek-R1 multi-node GPU profiling.</p>
    <ul>
      <li>Optimized NWChem through compilation refactoring and communication tuning.</li>
      <li>Profiled DeepSeek-R1 on multi-node GPU clusters with Nsight Systems and SGLang Profiler.</li>
      <li>Achieved a <strong>4.82x speedup</strong> on NWChem and about <strong>70%</strong> throughput improvement on DeepSeek-R1.</li>
    </ul>
  </div>
</div>

<div class="paper-box" id="mindspore-moe">
  <div class="paper-box-image">
    <div>
      <div class="badge">MoE Optimization</div>
      <img src="{{ '/images/MoE.png' | relative_url }}" alt="MoE optimization framework" />
    </div>
  </div>
  <div class="paper-box-text">
    <p><strong>MindSpore Model Development Competition</strong></p>
    <p>Led optimization for DeepSeek-MoE-16B and Qwen1.5-MoE inference on MindSpore.</p>
    <ul>
      <li>Optimized expert routing, sparse GEMM, and memory fragmentation bottlenecks.</li>
      <li>Implemented a fused Softmax + TopK operator.</li>
      <li>Reduced decoding latency by about <strong>80%</strong> with a dual-path inference engine.</li>
    </ul>
  </div>
</div>

<div class="paper-box" id="hgemm-optimization">
  <div class="paper-box-image">
    <div>
      <div class="badge">GPU Kernel</div>
      <img src="{{ '/images/hgemm.png' | relative_url }}" alt="HGEMM optimization framework" />
    </div>
  </div>
  <div class="paper-box-text">
    <p><strong>2nd SUSTech SuperComputing Competition</strong></p>
    <p>Built a high-performance HGEMM kernel with CUDA Tensor Core optimization.</p>
    <ul>
      <li>Used WMMA, size-specific tiling, double buffering, and asynchronous caching.</li>
      <li>Applied register swizzling and loop unrolling for small-to-medium matrix settings.</li>
      <li>Achieved performance competitive with or exceeding cuBLAS in selected cases.</li>
    </ul>
  </div>
</div>

**2025 ASC Student Supercomputer Challenge** | Core Member  
*Jan. 2025 - Feb. 2025*

* Profiled the baseline workflow for m5C site detection.
* Identified `hisat-3n-table` as the major bottleneck.
* Optimized synchronization, threading strategy, and MPI-based pipeline execution.
* Reduced overall runtime by **7.0x** while preserving accuracy and reliability.

**9th Huawei ICT Competition Chinese National Finals** | Team Leader  
*Feb. 2025 - Mar. 2025*

* Profiled the Hypre library with Kunpeng DevKit.
* Optimized sparse solver kernels with SVE intrinsics.
* Improved PCG convergence behavior within the BoomerAMG framework.
* Improved computational efficiency by about **30%** for large-scale sparse matrix solving on Kunpeng.

<span class="anchor" id="honors-awards"></span>

# Honors & Awards

* *2026.05*: Honorable Mention, 2026 Mathematical Contest in Modeling.
* *2026.02*: Second Class Prize, 2026 ASC Student Supercomputer Challenge.
* *2025.11*: Second Class Prize; Excellent AI Performance, 2025 APAC HPC-AI.
* *2025.11*: Achievement Prize, MindSpore Model Development Competition.
* *2025.08*: First Prize, SUSTech SuperComputing Competition.
* *2025.03*: Third Class Prize, 9th Huawei ICT Competition Chinese National Finals.
* *2025.06*: Achievement Prize, ISC25 Student Cluster Competition.
* *2024.12*: Bronze Prize, 2024 Kunpeng Application Innovation Competition.
* *2024.08*: Bronze Prize, MindSpore Model Fine-tuning Track.
* *2024.09*: Campus Academic Star, Southern University of Science and Technology.
* *2025.09*: Outstanding Student, Southern University of Science and Technology.
* *2025.11*: 3rd Place (Onsite), 8th Place (Overall), IndySCC25.

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
* Google Scholar: [scholar.google.com/citations?user=6PDGOX8AAAAJ](https://scholar.google.com/citations?hl=en&user=6PDGOX8AAAAJ)
* CV: [Web CV](/cv/) / [PDF CV](/files/Benxiang_Xiao_CV.pdf)
