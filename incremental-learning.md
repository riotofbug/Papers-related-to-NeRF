
[1] **CLNeRF: Continual Learning Meets NeRF**  
  - **摘要:**
    - Novel view synthesis aims to render unseen views given a set of calibrated images. In practical applications, the coverage, appearance or geometry of the scene may change over time, with new images continuously being captured. Efficiently incorporating such continuous change is an open challenge. Standard NeRF benchmarks only involve scene coverage expansion. To study other practical scene changes, we propose a new dataset, World Across Time (WAT), consisting of scenes that change in appearance and geometry over time. We also propose a simple yet effective method, CLNeRF, which introduces continual learning (CL) to Neural Radiance Fields (NeRFs). CLNeRF combines generative replay and the Instant Neural Graphics Primitives (NGP) architecture to effectively prevent catastrophic forgetting and efficiently update the model when new data arrives. We also add trainable appearance and geometry embeddings to NGP, allowing a single compact model to handle complex scene changes. Without the need to store historical images, CLNeRF trained sequentially over multiple scans of a changing scene performs on-par with the upper bound model trained on all scans at once. Compared to other CL baselines CLNeRF performs much better across standard benchmarks and WAT. The source code and the WAT dataset are available at this https URL. Video presentation is available at: this https URL
    - 新颖的视图合成旨在在给定一组校准图像的情况下渲染看不见的视图。 在实际应用中，场景的覆盖范围、外观或几何形状可能会随着时间的推移而变化，并不断捕获新的图像。 有效地整合这种持续的变化是一个公开的挑战。 标准 NeRF 基准测试仅涉及场景覆盖范围扩展。 为了研究其他实际场景的变化，我们提出了一个新的数据集，World Across Time (WAT)，由外观和几何形状随时间变化的场景组成。 我们还提出了一种简单而有效的方法，CLNeRF，它将持续学习（CL）引入神经辐射场（NeRF）。 CLNeRF 结合了生成重放和即时神经图形基元 (NGP) 架构，可有效防止灾难性遗忘，并在新数据到达时高效更新模型。 我们还在 NGP 中添加了可训练的外观和几何嵌入，允许单个紧凑模型处理复杂的场景变化。 不需要存储历史图像，在不断变化的场景的多次扫描上顺序训练的 CLNeRF 与同时在所有扫描上训练的上限模型表现不相上下。 与其他 CL 基线相比，CLNeRF 在标准基准测试和 WAT 上的表现要好得多。 源代码和 WAT 数据集可从此 https URL 获取。 视频演示可在以下位置找到：此 https URL
  - **链接:** [[PDF]](https://arxiv.org/pdf/2308.14816.pdf), [[CODE]](https://github.com/IntelLabs/CLNeRF),[[VIDEO]](https://youtu.be/nLRt6OoDGq0?si=8yD6k-8MMBJInQPs)
  - **说明:**

[2] **CL-NeRF: Continual Learning of Neural Radiance Fields for Evolving Scene Representation**  
  - **摘要:**
    - Existing methods for adapting Neural Radiance Fields (NeRFs) to scene changes require extensive data capture and model retraining, which is both time-consuming and labor-intensive. In this paper, we tackle the challenge of efficiently adapting NeRFs to real-world scene changes over time using a few new images while retaining the memory of unaltered areas, focusing on the continual learning aspect of NeRFs. To this end, we propose CL-NeRF, which consists of two key components: a lightweight expert adaptor for adapting to new changes and evolving scene representations and a conflict-aware knowledge distillation learning objective for memorizing unchanged parts. We also present a new benchmark for evaluating Continual Learning of NeRFs with comprehensive metrics. Our extensive experiments demonstrate that CL-NeRF can synthesize high-quality novel views of both changed and unchanged regions with high training efficiency, surpassing existing methods in terms of reducing forgetting and adapting to changes. Code and benchmark will be made available.
    - 现有的使神经辐射场（NeRF）适应场景变化的方法需要大量的数据捕获和模型重新训练，这既耗时又费力。 在本文中，我们解决了使用一些新图像有效地使 NeRF 适应现实世界场景随时间变化的挑战，同时保留未改变区域的记忆，重点关注 NeRF 的持续学习方面。 为此，我们提出了 CL-NeRF，它由两个关键组件组成：一个用于适应新变化和不断发展的场景表示的轻量级专家适配器，以及一个用于记忆未变化部分的冲突感知知识蒸馏学习目标。 我们还提出了一个新的基准，用于通过综合指标评估 NeRF 的持续学习。 我们大量的实验表明，CL-NeRF 可以以高训练效率合成变化区域和未变化区域的高质量新颖视图，在减少遗忘和适应变化方面超越了现有方法。 将提供代码和基准。
  - **链接:** [[PDF]](https://openreview.net/pdf?id=uZjpSBTPik), [[CODE]]()
  - **说明:**

[] ****  
  - **摘要:**
    - 
    - 
  - **链接:** [[PDF]](), [[CODE]]()
  - **说明:**

[] ****  
  - **摘要:**
    - 
    - 
  - **链接:** [[PDF]](), [[CODE]]()
  - **说明:**

[] ****  
  - **摘要:**
    - 
    - 
  - **链接:** [[PDF]](), [[CODE]]()
  - **说明:**

[] ****  
  - **摘要:**
    - 
    - 
  - **链接:** [[PDF]](), [[CODE]]()
  - **说明:**
