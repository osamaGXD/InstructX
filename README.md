# InstructX

Official implementation of **[InstructX: Towards Unified Visual Editing with MLLM Guidance](https://arxiv.org/pdf/2510.08485)**

> [Chong Mou](https://scholar.google.com/citations?user=SYQoDk0AAAAJ&hl=zh-CN), [Qichao Sun](https://huggingface.co/Simons212), [Yanze Wu](https://scholar.google.com/citations?user=FdHiVvkAAAAJ&hl=zh-CN)<sup>&dagger;</sup><sup>&ddagger;</sup>, [Pengze Zhang](https://openreview.net/profile?id=%7EPengze_Zhang1), [Xinghui Li](https://crayon-shinchan.github.io/xinghui99.github.io/), [Fulong Ye](https://scholar.google.com/citations?user=-BbQ5VgAAAAJ&hl=zh-CN), [Songtao Zhao](https://openreview.net/profile?id=~Songtao_Zhao1)<sup>&ddagger;</sup>, [Qian He](https://scholar.google.com/citations?user=9rWWCgUAAAAJ)<br>
> <sup>&dagger;</sup> Corresponding author, <sup>&ddagger;</sup> Project lead;
> Intelligent Creation Lab, Bytedance

<p align="center">
  <a href="https://mc-e.github.io/project/InstructX/">🌐 Project Page</a> |
  <a href="https://arxiv.org/pdf/2510.08485">📜 Arxiv</a> |
  <a href="https://huggingface.co/datasets/Simons212/VIE-Bench">🤗 Benchmark</a> |
</p>

### :triangular_flag_on_post: Updates
* **2025.10.10**: Release VIE-Bench.
* **2025.10.10**: Release InstructX tech report.

https://github.com/user-attachments/assets/06030093-53f2-4c75-a7e8-ac6cc8455870

### VIE-Bench

We introduce VIE-Bench (Video Instruction-Based Editing Benchmark), which comprises 140 high-quality instances across eight editing categories.

| Edit Task            | Sub Edit Task               | Number |
|:---------------------|:---------------------------:|------:|
| Total                |                             |   140 |
| Local Edit           | Object Swap                 |    25 |
|                      | Color Change                |    10 |
|                      | Add                         |    30 |
|                      | Remove                      |    30 |
| Global Edit          | Style Change                |    10 |
|                      | Tone / Weather Change       |     5 |
| Hybrid Edit          | -                           |    10 |
| Reference Base Edit  | Reference Base Swap         |    10 |
|                      | Reference Base Add          |    10 |
