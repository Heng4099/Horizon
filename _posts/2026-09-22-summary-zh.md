---
layout: default
title: "Horizon Summary: 2026-09-22 (ZH)"
date: 2026-09-22
lang: zh
---

> 从 52 条内容中筛选出 13 条重要资讯。

---

1. [16GB 显存：大多数 AI 用户的实际上限](#item-1) ⭐️ 8.0/10
2. [Yandex 发布定制 80B AI 模型](#item-2) ⭐️ 8.0/10
3. [Supra2-IMG：微型 100M 文本到图像模型](#item-3) ⭐️ 8.0/10
4. [X.AI 发布 Grok 4.7，权重增加 40%](#item-4) ⭐️ 7.0/10
5. [Kev：轻量级 Jev 式决策模型](#item-5) ⭐️ 7.0/10
6. [在 Mac 上禁用 Apple Intelligence 指南](#item-6) ⭐️ 7.0/10
7. [Python Workers 现已正式发布](#item-7) ⭐️ 7.0/10
8. [OpenAI 提出全球 AI 标准](#item-8) ⭐️ 7.0/10
9. [基于伊辛优化的物理大语言模型剪枝](#item-9) ⭐️ 7.0/10
10. [OceanBase 登顶国际 Data Agent 榜单](#item-10) ⭐️ 7.0/10
11. [M5 Ultra Mac Studio：本地 AI 的理想选择](#item-11) ⭐️ 7.0/10
12. [通义万象 2.1 许可证澄清](#item-12) ⭐️ 7.0/10
13. [DeepSeek 扩展至 2T 参数，计划 8T 模型](#item-13) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [16GB 显存：大多数 AI 用户的实际上限](https://www.reddit.com/r/LocalLLaMA/comments/1wmb875/16gb_and_in_many_cases_12gb_is_the_max_vram_most/) ⭐️ 8.0/10

该帖指出 16GB 是大多数 AI 用户的实际最大显存容量，最近的进展使得在配备此配置的消费级硬件上进行智能代理编程也成为可能。 这一见解有助于在消费级硬件上设定 AI 实现的合理预期，指导实践者在实际显存限制内优化工作流程，而不是追求价格高昂的多 GPU 配置。 作者指出，即使是 24GB 显存，大多数人在经济上也难以企及，而在世界上许多地区，12GB 甚至被视为奢侈品；最近的改进使得在 16GB 显卡上使用量化模型（如 Qwen 27B）进行智能代理编程成为可能。

reddit · r/LocalLLaMA · /u/ECrispy · 9月21日 12:21

**背景**: 模型量化是一种减少 AI 模型中数值精度的技术，使其更高效并降低内存需求。智能代理编程是指 AI 辅助软件开发，其中 AI 代理驱动代码编写循环，规划更改、编辑文件、运行测试并迭代直到任务完成。Transformer 架构是一种神经网络设计，已成为现代 AI 系统的基础，特别是在处理序列数据方面。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developer.nvidia.com/blog/model-quantization-concepts-methods-and-why-it-matters/">Model Quantization: Concepts, Methods, and Why It Matters</a></li>
<li><a href="https://en.wikipedia.org/wiki/Agentic_coding">Agentic coding</a></li>
<li><a href="https://en.wikipedia.org/wiki/Transformer_(deep_learning)">Transformer (deep learning) - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 这篇帖子来自一个偏向高端 AI 配置的 Reddit 社区（LocalLLaMA），但作者为普通用户提供了一个更现实的视角。在提供的内容摘录中没有具体评论。

**标签**: `#VRAM limitations`, `#AI hardware`, `#Model quantization`, `#Practical AI`, `#Consumer-grade AI`

---

<a id="item-2"></a>
## [Yandex 发布定制 80B AI 模型](https://www.reddit.com/r/LocalLLaMA/comments/1wmmnrt/yandexaliceaifoundation80ba3bbase/) ⭐️ 8.0/10

Yandex 发布了 AliceAI-Foundation-80B-A3B-Base，一个拥有完全定制架构的 800 亿参数模型，与 Qwen 35B 和 DeepSeek V4 Flash 竞争。 这一发布代表了俄罗斯主要科技公司的重大技术创新，可能影响开源 AI 模型的竞争格局，为中国开发者的成熟模型提供替代选择。 该模型具有 800 亿参数，其中 30 亿为活跃参数，上下文窗口为 256K，但目前不支持 Llama.cpp，且不像 Qwen3.5/3.6 模型那样经过后训练。

reddit · r/LocalLLaMA · /u/Iwaku_Real · 9月21日 19:24

**背景**: AliceAI-Foundation-80B-A3B-Base 是一个基础模型，意味着它已经进行了预训练以建立通用语言理解能力，但没有经过后训练来完善特定功能。后训练是将原始模型能力转化为特定任务技能的关键步骤，使模型更加有用、安全和专业化。Llama.cpp 是一个流行的 C/C++实现，用于高效的 LLM 推理，支持各种模型，但目前还不兼容这个新的 Yandex 模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/yandex/AliceAI-Foundation-80B-A3B-Base/tree/main">yandex/AliceAI-Foundation-80B-A3B-Base at main - Hugging Face</a></li>
<li><a href="https://www.reddit.com/r/LocalLLaMA/comments/1wmmnrt/yandexaliceaifoundation80ba3bbase/">yandex/AliceAI-Foundation-80B-A3B-Base: Russian-developed competitor to Qwen 35B and DeepSeek V4 Flash : r/LocalLLaMA - Reddit</a></li>
<li><a href="https://www.linkedin.com/posts/mazitovs_a-bit-of-a-milestone-for-me-yandex-released-activity-7506807225194123264-b64U">Yandex released AliceAI-Foundation-80B-A3B-Base, the last model whose pretrain architecture I built and trained (H1 2026) before moving on. 80B params, 3B active, 256K… - LinkedIn</a></li>

</ul>
</details>

**社区讨论**: Reddit 讨论指出该模型与其他预训练模型竞争，但警告这并不代表最终质量，因为后训练对模型性能有重大影响。

**标签**: `#new-models`, `#yandex`, `#open-source`, `#ai-architecture`, `#russian-ai`

---

<a id="item-3"></a>
## [Supra2-IMG：微型 100M 文本到图像模型](https://www.reddit.com/r/LocalLLaMA/comments/1wmftr3/massive_release_supra2img_a_tiny_100m_texttoimage/) ⭐️ 8.0/10

SupraLabs 发布了 Supra2-IMG，这是一个在单个 H100 GPU 上用不到 10 小时从头训练的 100M 参数 DiT 文本到图像模型，在 256x256 分辨率下实现了最先进的质量。 这一突破使高质量图像生成变得更加便捷，推理速度极快（CPU 约 20 秒，GPU 约 2 秒），为资源有限的内容创作者和开发者普及了 AI 图像创作。 该模型使用 DiT（扩散 Transformer）架构，可以通过简单命令在本地运行；它使用 50 个采样步长和 3.0 的 CFG 比例生成图像，所有示例图像均使用相同设置生成，未经过挑选。

reddit · r/LocalLLaMA · /u/LH-Tech_AI · 9月21日 15:21

**背景**: DiT（扩散 Transformer）是一类利用 Transformer 架构进行文本到图像生成的新型扩散模型。扩散模型通过学习反转向图像添加噪声的过程工作，从随机噪声开始，并根据文本提示逐步去噪。H100 GPU 是 NVIDIA 的高性能数据中心 GPU，具有 Transformer 加速功能，非常适合高效训练 AI 模型。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://encord.com/blog/diffusion-models-with-transformers/">Diffusion Transformer (DiT) Models: A Beginner’s Guide</a></li>
<li><a href="https://en.wikipedia.org/wiki/Diffusion_model">Diffusion model</a></li>
<li><a href="https://www.nvidia.com/en-us/data-center/h100/">H 100 GPU | NVIDIA</a></li>

</ul>
</details>

**社区讨论**: 原始的 Reddit 帖子邀请社区对模型提供反馈和提问，创作者表示愿意分享用于示例图像的提示词。社区对该模型在消费级硬件上的可访问性和性能表现感到兴奋。

**标签**: `#text-to-image`, `#diffusion-models`, `#efficient-ai`, `#model-release`, `#ai-applications`

---

<a id="item-4"></a>
## [X.AI 发布 Grok 4.7，权重增加 40%](https://x.ai/news/grok-4-7) ⭐️ 7.0/10

X.AI 发布了 Grok 4.7，相比前代版本增加了 40%的神经网络权重，同时保持相同的价格结构，输出 token 价格为 6 美元，输入 token 价格为 2 美元。 这次重大升级展示了 X.AI 改进其旗舰模型的承诺，同时保持有竞争力的定价，可能使他们在日益激烈的 AI 竞争中更好地对抗 OpenAI 的 Opus 5.5 等竞争对手。 Grok 4.7 被描述为具有'最小幻觉'和'可配置推理'能力，上下文窗口为 50 万 token，特别适合编码和代理工作流程，尽管一些用户报告了性能较慢的问题。

hackernews · meetpateltech · 9月21日 15:50 · [社区讨论](https://news.ycombinator.com/item?id=49788838)

**背景**: Grok 是由 X.AI 开发的一系列生成式 AI 大语言模型，由埃隆·马斯克于 2023 年 11 月推出。神经网络权重是确定每个输入对输出有多大影响的数值，更多的权重通常意味着更大、更复杂的模型，能够处理更细微的任务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://docs.x.ai/developers/models">Grok Models & Pricing | SpaceXAI Docs</a></li>
<li><a href="https://en.wikipedia.org/wiki/Grok_(chatbot)">Grok (chatbot) - Wikipedia</a></li>
<li><a href="https://grok.com/">Grok</a></li>

</ul>
</details>

**社区讨论**: 社区反应不一，一些用户对增加的权重是否能转化为比 Opus 5.5 等竞争对手更好的性能持怀疑态度，而其他人则欣赏持续的改进和日益加快的发布节奏，对 Grok 5 等未来版本表示乐观。

**标签**: `#AI models`, `#Grok`, `#model updates`, `#pricing`, `#benchmarking`

---

<a id="item-5"></a>
## [Kev：轻量级 Jev 式决策模型](https://github.com/jaredpalmer/kev/tree/main) ⭐️ 7.0/10

Kev 推出了一系列基于 Qwen3.5 构建的 Jev 式决策模型，专为轻量级决策实现而设计，能够处理类型化问题并输出校准概率。 这种方法为传统聊天模型在决策任务上提供了更高效的替代方案，可能实现更快、更专注的 AI 应用，避免生成不必要的 token。 Kev 作为 Qwen2.5-0.5B 上的 LoRA 适配器和小型读取头实现，能够一次性读取文档并在单次预填充过程中并行回答多个类型化问题，无需解码。

hackernews · tosh · 9月21日 07:11 · [社区讨论](https://news.ycombinator.com/item?id=49783999)

**背景**: Jev AI 代表了一种称为'系统一模型'的新型 AI 类别，专为机器而非对话设计。与生成文本 token 的聊天模型不同，Jev 能够从非结构化输入中生成类型安全的概率决策。Qwen3.5 是阿里巴巴的开源多模态模型系列，在推理、编码和多模态理解等多个基准测试中表现出色。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/jaredpalmer/kev/tree/main">GitHub - jaredpalmer/kev: tiny Jev-like family of decision ...</a></li>
<li><a href="https://jevai.net/">Jev AI — Decisions at machine speed</a></li>
<li><a href="https://qwen.ai/blog?id=qwen3.5">Qwen3.5: Towards Native Multimodal Agents</a></li>

</ul>
</details>

**社区讨论**: 社区反应不一，一些人表达了对'Jev 热潮'的疲劳和对机会主义实现的怀疑，而其他人则欣赏轻量级决策模型的效率。技术问题被提出，考虑到不同的训练方法（RLCD 与 RLHF），Kev 如何能真正被视为 Jev 式模型尚存疑问，同时有人建议使用嵌入和逻辑分类器作为分类任务的替代方案。

**标签**: `#AI models`, `#decision models`, `#Qwen3.5`, `#Jev-like`, `#lightweight AI`

---

<a id="item-6"></a>
## [在 Mac 上禁用 Apple Intelligence 指南](https://support.apple.com/guide/mac-help/turn-restrict-access-apple-intelligence-mchlb2e44f94/mac) ⭐️ 7.0/10

苹果发布了一份指南，解释用户如何在 Mac 电脑上禁用和限制对 Apple Intelligence 功能的访问，解决隐私问题并让用户对 AI 功能有更多控制权。 这很重要，因为 Apple Intelligence 处理用户数据并实现一些用户可能不需要的 AI 功能，该指南在 AI 日益融入日常技术的时代提供了必要的隐私控制。 指南显示，Apple Intelligence 功能可以通过"设置"→"屏幕使用时间"→"内容与隐私限制"→"Siri"→"书写辅助"来禁用，并且该功能仅在配备 Apple 芯片的 Mac 电脑上可用，不支持 Intel-based Mac。

hackernews · alwillis · 9月21日 17:30 · [社区讨论](https://news.ycombinator.com/item?id=49790409)

**背景**: Apple Intelligence 是苹果在 2024 年 6 月 10 日的 WWDC 2024 上发布的一系列 AI 功能，专为 iOS 18、iPadOS 18 和 macOS Sequoia 设计。它结合了设备端和服务器处理，包括写作工具、图像生成、通知摘要和 ChatGPT 集成等功能。在 macOS 上，它仅在配备 Apple 芯片的 Mac 上可用，不支持 Intel-based 机器。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Apple_Intelligence">Apple Intelligence - Wikipedia</a></li>
<li><a href="https://www.apple.com/apple-intelligence/">Apple Intelligence and Siri</a></li>
<li><a href="https://support.apple.com/en-us/121115">How to get the next generation of Apple Intelligence</a></li>

</ul>
</details>

**社区讨论**: 社区评论揭示了用户对苹果实施的强烈不满，批评 AI 控制放置在"屏幕使用时间"设置中（许多非家长用户不会想到查看这一点），抱怨某些 AI 功能"愚蠢"，如不必要的表情符号建议，并表达了对被他们不使用的 AI 模型占用的磁盘空间的担忧。

**标签**: `#apple-ai`, `#privacy`, `#user-controls`, `#macos`, `#ai-implementation`

---

<a id="item-7"></a>
## [Python Workers 现已正式发布](https://blog.cloudflare.com/python-workers-ga/) ⭐️ 7.0/10

Cloudflare 已正式发布 Python Workers 服务，使开发者能够通过 WebAssembly 技术在 Cloudflare 的全球边缘网络上运行 Python 代码。 这一发展具有重要意义，它使 Python 开发者能够利用边缘计算能力，创建新的部署可能性，并代表了 Python、WebAssembly 和边缘计算技术的重要融合。 Python Workers 通过 Pyodide 在 Workers 运行时内运行 CPython，HTTP 客户端通过 JavaScript 的 fetch API 路由请求。该发布经历了两年的预览期，并通过 PEP 783 (PyEmscripten)包含标准化的包支持。

hackernews · torutofu · 9月21日 13:38 · [社区讨论](https://news.ycombinator.com/item?id=49787142)

**背景**: Cloudflare Workers 是一个无服务器平台，使代码能够在 Cloudflare 的全球边缘网络上执行。WebAssembly (WASM)是一种二进制指令格式，允许用各种语言编写的代码在 Web 浏览器中以接近本机的速度运行。Pyodide 是 WebAssembly 的 Python 发行版，将 Python 带到浏览器。无服务器架构代表了一种云服务模型，客户可以在不管理基础设施的情况下使用云能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developers.cloudflare.com/workers/languages/python/how-python-workers-work/">How Python Workers Work · Cloudflare Workers docs</a></li>
<li><a href="https://github.com/cloudflare/python-workers-examples">GitHub - cloudflare / python - workers -examples · GitHub</a></li>
<li><a href="https://wasmedge.org/">WasmEdge</a></li>

</ul>
</details>

**社区讨论**: 社区成员讨论了技术方面，包括通过 WebAssembly 环境中 JavaScript 的 fetch API 进行 HTTP 客户端路由。提到了对 urllib3 的 Pyodide/Emscripten 支持的贡献，并对 Cloudflare 的工作表示兴奋，尽管有竞争产品。有人询问了 Pyodide 版本和冷启动性能。

**标签**: `#python`, `#edge-computing`, `#webassembly`, `#cloudflare`, `#serverless`

---

<a id="item-8"></a>
## [OpenAI 提出全球 AI 标准](https://openai.com/index/building-standards-next-phase-ai) ⭐️ 7.0/10

OpenAI 概述了建立共享全球 AI 标准的路径，呼吁进行协调的评估、报告和治理，以提高整个行业的 AI 安全性。 这一来自领先 AI 公司的倡议可能会塑造未来的监管格局，并影响 AI 系统在全球范围内的开发和部署，可能为行业范围内的安全实践设定先例。 该提议强调对 AI 模型的协调评估，当模型未能通过安全评估时可能暂停开发，并呼吁各组织之间建立标准化的报告机制。

rss · OpenAI News · 9月21日 10:00

**背景**: 随着 AI 系统变得更加强大和普及，AI 治理框架变得越来越重要。这些框架通常解决 AI 系统中的自动化、准确性和问责制问题。国际先进 AI 测量、评估和科学网络一直在制定衡量 AI 能力的关键实践。像 AI 安全中心这样的组织专注于减少先进 AI 系统带来的社会规模风险。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openai.com/index/building-standards-next-phase-ai/">Building standards for the next phase of AI - OpenAI</a></li>
<li><a href="https://www.nist.gov/news-events/news/2026/02/international-network-advanced-ai-measurement-evaluation-and-science">International Network for Advanced AI Measurement, Evaluation ...</a></li>
<li><a href="https://safe.ai/">Center for AI Safety (CAIS)</a></li>

</ul>
</details>

**标签**: `#AI governance`, `#AI safety`, `#OpenAI`, `#AI standards`, `#AI policy`

---

<a id="item-9"></a>
## [基于伊辛优化的物理大语言模型剪枝](https://huggingface.co/blog/MultiverseComputingCAI/pruning-llms-like-a-physicist-block-removal-as-an) ⭐️ 7.0/10

该博客介绍了一种新颖的大语言模型剪枝方法，通过将块移除视为伊辛优化问题，与现有单独评估每个块的方法相比，能够更系统地选择要移除的块。 这种物理启发的方法可以通过在不显著降低性能的情况下实现更有效的模型压缩，显著提高大语言模型的效率，使 AI 模型在资源受限设备上更易于部署和使用。 该方法利用伊辛模型映射组合优化问题的能力，将块移除决策视为优化问题中的变量，目标是找到在最大化压缩的同时最小化性能损失的最佳配置。

rss · Hugging Face Blog · 9月21日 13:44

**背景**: 大语言模型剪枝是一种模型压缩技术，通过从大语言模型中移除不必要的组件来减少模型大小和计算需求。伊辛模型是统计力学中描述铁磁性的数学模型，可以通过将组合优化问题表示为自旋系统来解决。物理启发的 AI 方法将物理学原理与机器学习技术相结合，以更高效地解决复杂问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/blog/MultiverseComputingCAI/pruning-llms-like-a-physicist-block-removal-as-an">Pruning LLMs Like a Physicist: Block Removal as an Ising Optimization Problem</a></li>
<li><a href="https://en.wikipedia.org/wiki/Ising_model">Ising model - Wikipedia</a></li>
<li><a href="https://arxiv.org/html/2605.27786v1">Locality-Aware Redundancy Pruning for LLM Depth Compression - arXiv</a></li>

</ul>
</details>

**标签**: `#LLM pruning`, `#Model optimization`, `#Physics-inspired AI`, `#Ising model`, `#Hugging Face`

---

<a id="item-10"></a>
## [OceanBase 登顶国际 Data Agent 榜单](https://www.qbitai.com/2026/09/493231.html) ⭐️ 7.0/10

OceanBase 的 Data Agent 方案登顶国际 Data Agent 基准测试，展示了国产数据库技术的先进 AI 能力。 这一成就标志着中国数据库技术的重要里程碑，展示了在 AI 数据库集成领域的竞争能力，可能影响 AI 增强型开发者与数据库系统的交互方式。 OceanBase 的 Data Agent 方案在复杂真实世界数据任务中表现出色，通过专注于端到端数据问题而非孤立 SQL 生成的 Data Agent 基准测试进行评估，突显了其对 AI 增强数据管理的全面方法。

rss · 量子位 · 9月21日 07:31

**背景**: OceanBase 是一个为关键任务工作负载设计的可扩展分布式数据库，以其高性能和可靠性而闻名。数据代理是 AI 领域的一个新兴范式，利用大语言模型来自主收集、处理和操作企业数据。Data Agent 基准测试评估这些系统在复杂真实世界数据任务中的表现，而非孤立功能，这使得 OceanBase 的排名第一是一项重要的技术成就。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.oceanbase.com/product/oceanbase">OceanBase Enterprise | Distributed Database for... | OceanBase</a></li>
<li><a href="https://sema4.ai/learning-center/what-is-an-ai-data-agent/">What is an AI data agent? - Sema4.ai</a></li>
<li><a href="https://ucbepic.github.io/DataAgentBench/">DAB ( Data Agent Benchmark ): leaderboard, benchmark overview...</a></li>

</ul>
</details>

**标签**: `#Database`, `#AI`, `#Benchmark`, `#OceanBase`, `#Data Agent`

---

<a id="item-11"></a>
## [M5 Ultra Mac Studio：本地 AI 的理想选择](https://www.reddit.com/r/LocalLLaMA/comments/1wmec1y/m5_ultra_mac_studio_review_the_dream_mac_for/) ⭐️ 7.0/10

一篇评测文章评估了 M5 Ultra Mac Studio 作为专为运行本地 AI 代理设计的强大硬件解决方案，强调了其在无需云依赖的情况下处理 AI 工作负载的能力。 这很重要，因为 M5 Ultra Mac 代表了 AI 工作负载消费级硬件的重大进步，使需要强大设备处理能力的开发者和创作者能够更轻松地使用本地 AI。 M5 Ultra 采用四芯片架构，拥有 36 核 CPU，是苹果迄今为止最强大的芯片，而 Mac Studio 是一款小型工作站计算机，在苹果专业产品线中位于消费级 Mac 之上。

reddit · r/LocalLLaMA · /u/themixtergames · 9月21日 14:26

**背景**: 本地 AI 代理是能够追求目标、使用软件或其他工具并以一定自主程度采取行动的人工智能程序，完全在它们运行的设备上运行，无需云连接。Mac Studio 是苹果的专业台式计算机，位于消费级 Mac Mini 和 iMac 之上，可配置 M5 Max 或 M5 Ultra 系统芯片。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/AI_agent">AI agent - Wikipedia</a></li>
<li><a href="https://medium.com/@shanrasool/local-ai-agents-what-they-actually-are-and-why-most-tools-are-getting-it-wrong-ff87ae424d9b">Local AI Agents: What They Actually Are and Why Most Tools Are Getting It Wrong - Medium</a></li>
<li><a href="https://www.apple.com/mac-studio/">Mac Studio - Apple</a></li>

</ul>
</details>

**社区讨论**: 该帖子发布在 r/LocalLLaMA 社区，这是一个专注于本地 AI 的社区，表明可能有相关讨论，但从提供的片段中无法看到实际评论内容。

**标签**: `#AI hardware`, `#Apple Silicon`, `#Local AI`, `#Mac Studio`, `#M5 Ultra`

---

<a id="item-12"></a>
## [通义万象 2.1 许可证澄清](https://www.reddit.com/r/LocalLLaMA/comments/1wm4o8x/clarification_on_the_qwenimage21_license/) ⭐️ 7.0/10

通义万象开发者团队澄清了通义万象 2.1 模型的许可证条款，解决了关于使用权限和商业应用的疑问。 对于希望在商业应用中使用通义万象 2.1 的开发者和企业来说，这次澄清至关重要，因为它明确了实施的法律边界和要求。 通义万象 2.1 模型采用 70 亿参数架构，包含 32 个单流 DiT 层，原生生成透明 RGBA 图像，其许可证条款要求用户请求使用权限。

reddit · r/LocalLLaMA · /u/Bestlife73 · 9月21日 06:17

**背景**: 通义万象 2.1 是阿里巴巴达摩院开发的通义系列 AI 模型的一部分。它是一个开源权重图像生成模型，结合了文本到图像生成和图像编辑功能。该模型采用多模块架构，集成视觉语言编码和基于扩散的生成，使其适用于复杂文本渲染和精确图像编辑任务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://modelscope.ai/models/Qwen/Qwen-Image-2.1">Qwen - Image - 2 . 1 - ModelScope</a></li>
<li><a href="https://github.com/QwenLM/Qwen/blob/main/LICENSE">Qwen/LICENSE at main - GitHub</a></li>
<li><a href="https://github.com/aboutcode-org/scancode-toolkit/issues/4527">New license request: Qwen LICENSE AGREEMENT · Issue #4527 · aboutcode-org/scancode-toolkit - GitHub</a></li>

</ul>
</details>

**社区讨论**: Reddit 帖子表明用户对通义万象 2.1 的许可证条款存在困惑，特别是关于商业使用权限的问题。通义万象开发者的澄清似乎直接解决了这些担忧。

**标签**: `#AI models`, `#license`, `#Qwen`, `#image generation`, `#legal`

---

<a id="item-13"></a>
## [DeepSeek 扩展至 2T 参数，计划 8T 模型](https://www.reddit.com/r/LocalLLaMA/comments/1wmblx1/deepseek_training_2t_and_plans_8t_model/) ⭐️ 7.0/10

DeepSeek 目前正在训练一个 2 万亿参数的模型，并宣布最终将开发一个 8 万亿参数的模型，加入了日益增长的大型语言模型竞赛。 这一扩展代表了持续模型竞赛中的重要一步，可能推动 AI 能力的边界，并为行业中的大型语言模型设定新的基准。 DeepSeek 当前的模型包括拥有 5520 亿参数的 Flash 和拥有 1.6 万亿总参数但每代仅激活 490 亿权重的 Pro，表明采用了高效的稀疏激活方法。

reddit · r/LocalLLaMA · /u/Terminator857 · 9月21日 12:38

**背景**: 大型语言模型中的参数是训练期间学习的内部权重，用于捕获语言中的模式，如语法、上下文和单词之间的关系。这些参数通常以数十亿或数万亿计，决定了模型理解和生成文本的能力。模型扩展是指增加参数数量的过程，以可能提高性能，但研究表明更大并不总是更好，扩展已达到实际限制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.geeksforgeeks.org/artificial-intelligence/what-are-llm-parameters/">LLM Parameters - GeeksforGeeks</a></li>
<li><a href="https://ingramhaus.com/llm-parameter-counts-explained-why-size-scale-and-architecture-matter">LLM Parameter Counts Explained: Why Size, Scale, and ...</a></li>
<li><a href="https://www.explainx.ai/blog/llm-model-parameters-billions-explained">What are parameters in a large language model? Billions ...</a></li>

</ul>
</details>

**标签**: `#Large Language Models`, `#Model Scaling`, `#DeepSeek`, `#AI Research`, `#Parameter Count`

---