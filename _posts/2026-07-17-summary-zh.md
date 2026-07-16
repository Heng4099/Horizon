---
layout: default
title: "Horizon Summary: 2026-07-17 (ZH)"
date: 2026-07-17
lang: zh
---

> 从 57 条内容中筛选出 12 条重要资讯。

---

1. [NVIDIA Nemotron 3 嵌入模型 RTEB 榜首](#item-1) ⭐️ 8.0/10
2. [月之暗面发布 Kimi K3 大模型](#item-2) ⭐️ 8.0/10
3. [思维机器实验室发布 Inkling 开源权重模型](#item-3) ⭐️ 8.0/10
4. [DeepSeek V4 Flash 在消费级硬件上的性能提升](#item-4) ⭐️ 8.0/10
5. [诱饵字体：AI 抗性排版术](#item-5) ⭐️ 7.0/10
6. [传统机器学习检测 AI 生成文本](#item-6) ⭐️ 7.0/10
7. [DeepMind 和 Isomorphic Labs 分享生物韧性 AI 方法](#item-7) ⭐️ 7.0/10
8. [新模型，相同优势](#item-8) ⭐️ 7.0/10
9. [xAI 开源 Grok Build 以回应隐私争议](#item-9) ⭐️ 7.0/10
10. [中国移动投资工业 AI 基础设施](#item-10) ⭐️ 7.0/10
11. [RLinf v0.3 发布，五大能力升级](#item-11) ⭐️ 7.0/10
12. [开源法语多语言大模型发布](#item-12) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [NVIDIA Nemotron 3 嵌入模型 RTEB 榜首](https://huggingface.co/blog/nvidia/nemotron-3-embed-wins-rteb) ⭐️ 8.0/10

NVIDIA 的 Nemotron 3 嵌入模型在 RTEB 基准测试中排名第一，展示了在文本嵌入和检索任务中的卓越性能。 这一突破之所以重要，是因为嵌入模型是 AI 系统的基础组件，特别是对于检索增强生成和智能体系统。在 RTEB 上的排名第一表明 Nemotron 3 嵌入模型可以显著提高这些系统的准确性和效率。 Nemotron 3 嵌入模型基于 Ministral-3-8B 架构，将文本映射为 4096 维密集向量，用于检索和语义相似性任务。该模型提供强大的多语言和跨语言检索能力。

rss · Hugging Face Blog · 7月16日 16:01

**背景**: 嵌入模型是将文本转换为捕获语义含义的数值向量的 AI 系统。RTEB（检索聚焦文本嵌入基准）是一个新的基准测试，旨在评估嵌入模型的检索准确性，同时使用开放和私有数据集来防止基准测试过拟合。智能检索是指 AI 智能体使用检索机制来增强其响应的系统，特别适用于能从外部知识中受益的复杂查询。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/blog/rteb">Introducing RTEB : A New Standard for Retrieval Evaluation</a></li>
<li><a href="https://github.com/embedding-benchmark/rteb">GitHub - embedding- benchmark / rteb : Retrieval Embedding Benchmark</a></li>
<li><a href="https://deepinfra.com/nvidia/Nemotron-3-Embed-8B">nvidia / Nemotron - 3 - Embed -8B - Demo - DeepInfra</a></li>

</ul>
</details>

**标签**: `#embedding-models`, `#nvidia`, `#benchmarks`, `#retrieval-augmented`, `#ai-agents`

---

<a id="item-2"></a>
## [月之暗面发布 Kimi K3 大模型](https://simonwillison.net/2026/Jul/16/kimi-k3/#atom-everything) ⭐️ 8.0/10

月之暗面宣布推出 Kimi K3，一个拥有 2.8 万亿参数的模型，声称在性能上可与 Claude 和 GPT 等顶级闭源模型竞争，并计划于 2026 年 7 月 27 日发布开源权重。 这具有重要意义，因为它代表了开源 AI 的重大进展，可能使尖端技术民主化，并为研究人员和开发者提供替代专有模型的强大选择。 Kimi K3 的定价为每百万输入 token 3 美元，每百万输出 token 15 美元，使其成为中国 AI 实验室发布的迄今为止最昂贵的模型，并且目前领先于 Arena.ai 的前端代码竞技场，甚至超过了 Claude Fable 5。

rss · Simon Willison · 7月16日 20:19

**背景**: 万亿参数模型代表了 AI 开发的尖端，尽管有效率优化，其计算需求仍然巨大。开源权重模型与开源模型不同，其核心组件是公开发布的，允许用户在自己的计算机上运行模型、研究其工作原理并根据特定需求进行修改。AI 基准测试是标准化测试，用于衡量模型在各种任务上的性能，通过评估语言理解、生成、推理和编码能力，帮助在公平的竞争环境中比较模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/kimi-k2-trillion-parameter-open-source-ai-model-thats-ahmed-albadri-p1mgf">Kimi K2: The Trillion - Parameter Open-Source AI Model ...</a></li>
<li><a href="https://hai.stanford.edu/ai-definitions/what-is-an-open-weight-model">What is an Open-Weight Model? - Stanford HAI</a></li>
<li><a href="https://grokipedia.com/page/Large_Language_Model_Benchmarks">Large Language Model Benchmarks</a></li>

</ul>
</details>

**标签**: `#Large Language Models`, `#Open Source AI`, `#Model Releases`, `#AI Benchmarking`, `#Chinese AI`

---

<a id="item-3"></a>
## [思维机器实验室发布 Inkling 开源权重模型](https://simonwillison.net/2026/Jul/16/inkling/#atom-everything) ⭐️ 8.0/10

思维机器实验室发布了 Inkling，这是一个拥有 9750 亿参数的开源权重多模态模型，在 450 万亿个多样化数据（包括文本、图像、音频和视频）上进行训练。他们还宣布了 Inkling-Small，一个拥有 2760 亿参数的模型，目前正在测试中。 Inkling 的发布通过提供与闭源模型和中国开源权重模型相竞争的替代品，加强了开源 AI 生态系统。其 Apache-2.0 许可使其特别适合构建商业产品和微调应用，对 AI 开发者和企业具有重要意义。 Inkling 采用专家混合架构，拥有 9750 亿个总参数，但在任何给定时间只有 410 亿个参数处于活跃状态，使其计算效率更高。该模型被设计为一个强大的基础模型用于微调，而非前沿模型，具有多模态能力并可使用 Tinker 训练平台。

rss · Simon Willison · 7月16日 15:35

**背景**: 开源权重 AI 模型共享训练好的最终参数，为开发者提供透明度和控制权。专家混合架构使用多个专业化的神经网络协同工作解决复杂问题，同时保持计算效率。多模态 AI 模型能够处理和生成不同类型的数据，如文本、图像、音频和视频，使 AI 应用更加全面。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.emergentmind.com/topics/mixture-of-neuron-experts-mone">Mixture of Neuron Experts (MoNE)</a></li>
<li><a href="https://openai.com/global-affairs/open-weights-and-ai-for-all/">Open weights and AI for all | OpenAI</a></li>
<li><a href="https://www.oracle.com/artificial-intelligence/ai-open-weights-models/">"Open-weights" AI models offer transparency and control. - Oracle</a></li>

</ul>
</details>

**标签**: `#open-source-ai`, `#large-language-models`, `#multimodal-ai`, `#mixture-of-experts`, `#ai-models`

---

<a id="item-4"></a>
## [DeepSeek V4 Flash 在消费级硬件上的性能提升](https://www.reddit.com/r/LocalLLaMA/comments/1uy33fw/deepseek_v4_flash_98gb_on_1x_4060ti_cpu_got_300/) ⭐️ 8.0/10

一名用户报告称，在消费级硬件上运行 98GB 的 DeepSeek-V4-Flash 模型性能提升了 300%，令牌生成速度从 2t/s 提升到 7t/s，这是 llamacpp 在 b9986 和 b10034 版本之间优化后的结果。 这一显著的性能提升表明软件优化如何使大型 AI 模型在消费级硬件上更易于使用，可能使研究人员和爱好者无需昂贵的企业基础设施就能接触到先进的 AI 能力，从而实现 AI 民主化。 用户在配备 12 核 AMD Ryzen 5 9600X CPU、138GB RAM 和 16GB 显存的 NVIDIA GeForce RTX 4060 Ti GPU 的硬件上实现了这一性能，使用了需要 98GB 显存的 DeepSeek-V4-Flash-UD-Q2_K_XL 量化模型，并利用 CPU 生成，启用了 flash-attention 等特定优化。

reddit · r/LocalLLaMA · /u/Chuyito · 7月16日 13:35

**背景**: Llama.cpp 是一个开源软件库，用于在各种大型语言模型上进行推理，被认为是本地推理工具的事实标准。DeepSeek V4 Flash 是一个包含 284B 总参数但仅激活 13B 参数的专家混合(Mixture-of-Experts)模型，设计用于在大型 100 万令牌上下文窗口中进行高效推理。本案例中使用的 Q2_K 量化格式提供最大压缩和最小资源使用，使其适合在显存有限的硬件上运行大型模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Llama.cpp">Llama.cpp</a></li>
<li><a href="https://ollama.com/library/deepseek-v4-flash">deepseek - v 4 - flash</a></li>
<li><a href="https://local-ai-zone.github.io/guides/what-is-ai-quantization-q4-k-m-q8-gguf-guide-2025.html">AI Model Quantization 2025: Master Compression Techniques for Maximum Performance & Efficiency - Local AI Zone</a></li>

</ul>
</details>

**社区讨论**: Reddit 帖子包含额外的社区见解，比较了 Qwen3.6-27B 模型的不同推理方法，显示 DFlash 达到 98 tok/s（基线的 2.20 倍），但接受率仅为 30%，使其更适合编码任务，而 MTP 达到 65 tok/s（基线的 1.45 倍），接受率为 71%，更适合聊天或创意写作。

**标签**: `#AI optimization`, `#Large language models`, `#Consumer hardware`, `#Inference performance`, `#llamacpp`

---

<a id="item-5"></a>
## [诱饵字体：AI 抗性排版术](https://www.mixfont.com/experiments/decoy-font) ⭐️ 7.0/10

诱饵字体是一种排版实验，创造出人类与 AI 系统视觉文本解读不同的效果，揭示了不同模型如何处理视觉信息。 这个实验突显了 AI 视觉感知的局限性，可能导致创建 AI 抗性内容的新方法，对数字安全、水印技术和内容真实性验证具有影响。 实验表明，不同的 AI 模型（GPT、Claude、Gemini）对相同的视觉文本有不同的解读，有些模型仅在提示时检测到隐藏信息，而其他模型则根据图像分辨率改变其解读。

hackernews · ray__ · 7月16日 16:18 · [社区讨论](https://news.ycombinator.com/item?id=48936584)

**背景**: 对抗样本是通过微小修改设计的输入，旨在欺骗 AI 模型做出错误预测。排版术是安排文字使其在显示时清晰、易读且具有吸引力的艺术和技术。统觉概念涉及感知和意识如何在不同个体和系统中处理信息。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Adversarial_examples">Adversarial examples</a></li>
<li><a href="https://christophm.github.io/interpretable-ml-book/adversarial.html">30 Adversarial Examples – Interpretable Machine Learning</a></li>
<li><a href="https://deeplibs.gitlab.io/appendix/adversarial_examples.html">Adversarial examples</a></li>

</ul>
</details>

**社区讨论**: 社区评论反应不一，有人质疑其实用性，同时承认其酷炫因素。讨论揭示了不同 AI 模型如何对相同的视觉内容有不同的解读，例子显示有些模型仅在提示时检测到隐藏信息，而其他模型则根据图像分辨率改变解读。还有人担心对视力障碍人士的可访问性问题。

**标签**: `#AI perception`, `#typography`, `#content creation`, `#AI limitations`, `#visual design`

---

<a id="item-6"></a>
## [传统机器学习检测 AI 生成文本](https://blog.lyc8503.net/en/post/llm-classifier/) ⭐️ 7.0/10

这篇博客文章展示了如何使用传统机器学习技术检测大型语言模型生成的文本，为深度学习方法提供了替代方案。 这种方法为检测 AI 生成内容提供了更可解释、更高效的途径，在先进 AI 时代对抗虚假信息和维护内容真实性方面变得越来越重要。 作者使用传统机器学习方法而非深度学习构建了分类器，这种方法似乎相对轻量，可能适合浏览器扩展以实时检测 AI 生成的文本。

hackernews · uneven9434 · 7月16日 16:41 · [社区讨论](https://news.ycombinator.com/item?id=48936880)

**背景**: 传统机器学习指的是不使用深度神经网络的经典算法，当数据结构化且有限或可解释性重要时通常被优先使用。相比之下，深度学习使用具有多层神经网络的神经网络来处理大型非结构化数据集中的复杂模式。随着像 GPT 这样的大型语言模型生成越来越像人类的内容，检测 AI 生成文本的挑战变得越来越重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.geeksforgeeks.org/artificial-intelligence/difference-between-machine-learning-and-deep-learning/">Difference Between Machine Learning and Deep Learning</a></li>
<li><a href="https://arxiv.org/abs/2601.03812">[2601.03812] AI Generated Text Detection</a></li>
<li><a href="https://pub.towardsai.net/demystifying-how-ai-text-detection-works-acca1c139916?gi=532a7fadd5f0">Demystifying How AI Text Detection Works | by Ayo Akinkugbe | Towards AI</a></li>

</ul>
</details>

**社区讨论**: 社区讨论揭示了人们对文本检测方法长期有效性的怀疑，有人将其比作'塔罗牌占卜'。还有人建议关注衡量写作努力而非作者身份可能更有效。一位评论者提议构建浏览器扩展来自动检测 AI 生成的文本，类似于广告拦截器。

**标签**: `#AI detection`, `#LLM`, `#machine learning`, `#text analysis`, `#content verification`

---

<a id="item-7"></a>
## [DeepMind 和 Isomorphic Labs 分享生物韧性 AI 方法](https://deepmind.google/blog/our-approach-to-bioresilience/) ⭐️ 7.0/10

Google DeepMind 和 Isomorphic Labs 联合宣布了他们使用 AI 模型处理生物韧性的方法，标志着在将人工智能应用于生物韧性挑战方面迈出了重要一步。 这种方法可能会彻底改变我们应对生物韧性挑战的方式，可能导致医学、环境保护和了解物种如何适应变化条件方面的突破。 该合作利用了 Isomorphic Labs 在 AI 驱动的药物发现方面的专长和 DeepMind 的高级 AI 能力，特别是通过 AlphaFold 等技术进行蛋白质结构预测。

rss · Google DeepMind · 7月16日 09:30

**背景**: 生物韧性指的是物种或个体生物适应变化和环境压力的能力。Isomorphic Labs 于 2021 年作为 DeepMind 的子公司成立，专注于将 AI 应用于药物发现和生物研究。该公司利用 DeepMind 的 AlphaFold 技术，该技术可以高精度预测蛋白质结构，使研究人员能够识别新的药物递送途径。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Bioresilience">Bioresilience - Wikipedia</a></li>
<li><a href="https://en.wiktionary.org/wiki/bioresilience">bioresilience - Wiktionary, the free dictionary</a></li>
<li><a href="https://en.wikipedia.org/wiki/Isomorphic_Labs">Isomorphic Labs</a></li>

</ul>
</details>

**标签**: `#AI`, `#Bioresilience`, `#DeepMind`, `#Biological Applications`, `#Isomorphic Labs`

---

<a id="item-8"></a>
## [新模型，相同优势](https://huggingface.co/blog/Dharma-AI/newer-models-same-advantages) ⭐️ 7.0/10

Hugging Face 博客文章分析了新的人工智能模型如何保持或建立在先前模型的优势之上，为从业者提供了关于模型选择和优化策略的见解。 这种分析很重要，因为它可以帮助人工智能从业者就使用哪些模型来完成特定任务做出明智的决策，从而在保持应用程序性能的同时节省时间和资源。 该文章可能检查各种 Transformer 模型架构（仅编码器、仅解码器和编码器-解码器），并在多个维度上比较它们，包括智能程度、定价、输出速度、延迟和上下文窗口大小，以确定它们的相对优势。

rss · Hugging Face Blog · 7月16日 11:49

**背景**: Hugging Face 是一家开发机器学习应用程序计算工具的美国公司，特别是其用于自然语言处理的 transformers 库。Transformer 模型于 2017 年推出，是基于多头注意力机制的神经网络架构，比早期的 RNN 和 LSTM 架构在训练效率和性能方面具有优势。模型比较涉及评估 AI 模型在各种指标上的表现，以确定它们对特定应用的适用性，从业者通常需要在速度、准确性和资源需求等性能因素之间取得平衡。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Hugging_Face">Hugging Face</a></li>
<li><a href="https://en.wikipedia.org/wiki/Transformer_models">Transformer models</a></li>
<li><a href="https://artificialanalysis.ai/models">Comparison of AI Models across Intelligence, Performance, and Price</a></li>

</ul>
</details>

**标签**: `#AI models`, `#model comparison`, `#Hugging Face`, `#machine learning`, `#AI performance`

---

<a id="item-9"></a>
## [xAI 开源 Grok Build 以回应隐私争议](https://simonwillison.net/2026/Jul/15/grok-build/#atom-everything) ⭐️ 7.0/10

在因未经用户同意将整个目录上传到 Google Cloud 存储桶而面临严重社区反弹后，xAI 已将其 Grok CLI 工具在 Apache 2.0 许可证下开源。 这一事件凸显了 AI 工具中的关键隐私问题，并展示了在数据隐私违规后，如何通过开源作为透明度措施来重新获得用户信任。 Grok Build 代码库包含 844,530 行 Rust 代码，其中只有约 3%是第三方依赖，xAI 已禁用数据上传功能并删除了所有先前上传的用户数据作为预防措施。

rss · Simon Willison · 7月15日 23:59

**背景**: Grok 是由 xAI（埃隆·马斯克的 AI 公司）开发的 AI 助手。Grok CLI 工具是与 Grok AI 模型交互的命令行界面。Google Cloud 存储桶是 Google Cloud Platform 中存储和检索数据的容器。Apache 2.0 许可证是一个宽松的开源许可证，允许用户自由使用、修改和分发软件。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://x.ai/cli">Grok Build | SpaceXAI</a></li>
<li><a href="https://docs.cloud.google.com/storage/docs/buckets">About Cloud Storage buckets | Google Cloud Documentation</a></li>

</ul>
</details>

**社区讨论**: 社区对隐私侵犯反应强烈，有用户报告称该工具上传了其主目录中的 SSH 密钥、密码管理器数据库、文档、照片、视频和所有内容。xAI 通过禁用该功能、删除所有上传的数据并开源代码库来回应，以重新获得信任。

**标签**: `#AI tools`, `#open source`, `#data privacy`, `#security`, `#Grok`

---

<a id="item-10"></a>
## [中国移动投资工业 AI 基础设施](https://www.qbitai.com/2026/07/451371.html) ⭐️ 7.0/10

中国移动投资友机技术，押注工业 AI 下一代基础设施，标志着工业母机进入"计算化时刻"。 中国移动的这项重要投资凸显了 AI 基础设施在工业领域日益增长的重要性，代表了 AI 领域的重要商业发展，可能加速制造业的数字化转型。 这项投资聚焦于友机技术，该公司似乎正在开发工业 AI 应用的基础设施，特别针对传统工业机械与计算能力和 AI 功能更加融合的"计算化时刻"。

rss · 量子位 · 7月16日 09:29

**背景**: 工业母机是制造几乎所有工业产品的基本工具，从汽车零部件到电子元件。随着 AI 和计算能力更多地融入其运营，这些机器正在经历转型。工业 AI 指的是在工业环境中应用人工智能，使机器能够理解工业流程、做出决策和优化生产。

<details><summary>参考链接</summary>
<ul>
<li><a href="http://www.news.cn/finance/20251118/541b0cce18b24d56954f787edeae0525/c.html">“十五五”规划建议中提及的“工业母机”是什么？-新华网</a></li>
<li><a href="https://gongkong.ofweek.com/2021-08/ART-310045-11000-30520656.html">什么是工业母机？工业母机的结构和作用介绍 - OFweek工控网</a></li>
<li><a href="https://grokipedia.com/page/ET_Industrial_Brain">ET Industrial Brain</a></li>

</ul>
</details>

**标签**: `#industrial AI`, `#AI infrastructure`, `#China Mobile`, `#investment`, `#manufacturing AI`

---

<a id="item-11"></a>
## [RLinf v0.3 发布，五大能力升级](https://www.qbitai.com/2026/07/451379.html) ⭐️ 7.0/10

RLinf v0.3 由清华大学联合开发，引入五大能力升级，推动具身智能从模型生态系统到真实机器部署的进步，解决了关键行业瓶颈。 这一重要平台更新对从事具身 AI 应用的 AI 从业者高度相关，因为它弥合了理论模型与实际部署之间的差距，加速了能够与物理环境交互的自主系统的发展。 RLinf 平台是一个分布式强化学习基础设施，已在 256 个 GPU 的 H100 集群上验证，展示了其在下一代具身 AI 训练中的可扩展性和稳健性。

rss · 量子位 · 7月16日 09:25

**背景**: 具身 AI 指的是能够使用传感器、电机、机器学习和自然语言处理技术与环境交互并从中学习的 AI 系统。RLinf 的名称代表'强化学习基础设施'，为训练这些具身和智能体 AI 系统提供了强大的基础。RLinf 与清华大学的合作代表了在推进这一关键 AI 领域中产业与学术界的重要合作。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/RLinf/RLinf">GitHub - RLinf/RLinf: RLinf: Reinforcement Learning Infrastructure for Embodied and Agentic AI · GitHub</a></li>
<li><a href="https://www.spheron.network/blog/deploy-rlinf-gpu-cloud-reinforcement-learning-embodied-agentic-ai/">Deploy RLinf on GPU Cloud: Scalable RL Infrastructure for Embodied and Agentic AI (2026 Guide) | Spheron Blog</a></li>
<li><a href="https://www.techtarget.com/searchenterpriseai/definition/embodied-AI">What Is Embodied AI? How It Powers Autonomous Systems | TechTarget</a></li>

</ul>
</details>

**标签**: `#embodied-intelligence`, `#AI-platform`, `#RLinf`, `#machine-learning`, `#deployment`

---

<a id="item-12"></a>
## [开源法语多语言大模型发布](https://www.reddit.com/r/LocalLLaMA/comments/1uy9a8f/openllmfranceluciole23binstruct11_apache_20/) ⭐️ 7.0/10

OpenLLM-France 发布了 Luciole-23B-Instruct-1.1，这是一个采用 Apache 2.0 许可证的多语言指令遵循模型，具有三阶段训练方法和多种模型尺寸（23B、8B、1B）。 这次发布具有重要意义，因为它提供了一个政府资助的开源替代方案，可以替代专有多语言模型，Apache 2.0 许可证允许更广泛的商业采用，而新颖的三阶段训练方法可以提高指令遵循能力。 该模型分三个阶段训练：带思考轨迹的监督微调、不带思考轨迹的监督微调，以及直接偏好优化（DPO），涵盖数学、科学、编程、一般聊天、RAG 和翻译等主题。

reddit · r/LocalLLaMA · /u/Balance- · 7月16日 17:23

**背景**: 直接偏好优化（DPO）是一种帮助语言模型更好地匹配人类偏好的方法，在微调过程中不需要从模型中采样。因果语言模型仅基于前面的标记序列预测下一个标记，模仿人类处理语言的自然方式。检索增强生成（RAG）是一种技术，使语言模型能够在响应用户查询之前从外部数据源检索并整合新信息。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/LoRA_(machine_learning)">LoRA (machine learning) - Wikipedia</a></li>
<li><a href="https://arxiv.org/abs/2305.18290">[2305.18290] Direct Preference Optimization: Your Language Model is Secretly a Reward Model</a></li>
<li><a href="https://en.wikipedia.org/wiki/Retrieval-augmented_generation">Retrieval - augmented generation - Wikipedia</a></li>

</ul>
</details>

**标签**: `#open-source-models`, `#multilingual-ai`, `#instruction-following`, `#french-ai`, `#model-release`

---