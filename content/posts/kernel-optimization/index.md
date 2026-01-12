---
title: "Kernel Optimization"
date: 2026-01-12T00:02:05-08:00
# bookComments: false
draft: false
bookSearchExclude: false
# bookPostThumbnail: thumbnail.*
---

# Resources

- KernelEvolve: Scaling Agentic Kernel Coding for Heterogeneous AI Accelerators at Meta
 [url](https://arxiv.org/abs/2512.23236) - This document introduces KernelEvolve, an agentic framework designed to automate the generation and optimization of high-performance AI kernels across diverse hardware. The system addresses the "curse of dimensionality" in modern recommendation models, where a massive variety of operators must be manually tuned for heterogeneous chips like NVIDIA GPUs, AMD GPUs, and Meta’s MTIA. By utilizing a universal operator and a hierarchical knowledge base, the agent iteratively refines code based on real-time execution feedback to maximize efficiency. Performance case studies demonstrate that KernelEvolve can achieve significant speedups, sometimes exceeding 2x, by identifying non-obvious operator fusion and tiling strategies. Ultimately, this automation reduces the development cycle from weeks to hours, ensuring that software maturity keeps pace with rapid AI hardware innovation.
  - [NotebookLM](https://notebooklm.google.com/notebook/3036d48d-4d03-452f-8051-af44d9924a38)
- [AMD vs NVIDIA Inference Benchmark: Who Wins? - Performance &amp; Cost Per Million Tokens](https://newsletter.semianalysis.com/p/amd-vs-nvidia-inference-benchmark-who-wins-performance-cost-per-million-tokens)
- [HIPIFY](https://github.com/ROCm/HIPIFY) - AMD's CUDA
- [CUDA-L1: Improving CUDA Optimization via Contrastive Reinforcement Learning](https://arxiv.org/abs/2507.14111)
- GPU Programming Specialization from [Coursera](https://www.coursera.org/specializations/gpu-programming/paidmedia?utm_medium=sem&utm_source=gg&utm_campaign=b2c_namer_gpu-programming_jhu_ftcof_specializations_px_dr_bau_gg_sem_pr_us-ca_en_m_hyb_24-11_x&campaignid=21876399000&adgroupid=168462627045&device=c&keyword=software%20architecture%20courses&matchtype=b&network=g&devicemodel=&creativeid=720221719408&assetgroupid=&targetid=kwd-321200694434&extensionid=&placement=&gad_source=1&gad_campaignid=21876399000&gbraid=0AAAAADdKX6aNiV6YBT1cvv84MMojRhsbm&gclid=Cj0KCQiA1JLLBhCDARIsAAVfy7iOqtCvII_9eQKqkEu1gEJCx1WVOWe0qZVbuqr7PhsOMtd7lL8z-lQaAkSJEALw_wcB) - There are many similar online courses provided by others too, just Google it.
- I used Manus to create a [CUDA & PyTorch Optimization Learning website](https://cudapylearn-g7brkjlh.manus.space/)