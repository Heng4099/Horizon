---
layout: default
title: "Horizon Summary: 2026-07-07 (ZH)"
date: 2026-07-07
lang: zh
---

> 从 45 条内容中筛选出 15 条重要资讯。

---

1. [Ternlight：7MB 浏览器嵌入模型](#item-1) ⭐️ 8.0/10
2. [语言模型中的全局工作空间](#item-2) ⭐️ 8.0/10
3. [AI 时代编程学习仍有价值](#item-3) ⭐️ 8.0/10
4. [LeRobot v0.6.0：想象、评估、改进](#item-4) ⭐️ 8.0/10
5. [AI4S 转向自主发现](#item-5) ⭐️ 8.0/10
6. [极简方案刷新扩散模型推理纪录](#item-6) ⭐️ 8.0/10
7. [Kyutai 的 Pocket TTS：5 秒 CPU 语音克隆](#item-7) ⭐️ 8.0/10
8. [HOLA：海马体线性注意力模型](#item-8) ⭐️ 8.0/10
9. [俄罗斯银行发布支持 GGUF 的 GigaChat3.5](#item-9) ⭐️ 8.0/10
10. [OfficeCLI：AI 代理办公套件](#item-10) ⭐️ 7.0/10
11. [Hugging Face 详细介绍 PRX 数据策略](#item-11) ⭐️ 7.0/10
12. [腾讯发布 Hy3 MoE 模型](#item-12) ⭐️ 7.0/10
13. [首个空间原生具身视觉模型开源](#item-13) ⭐️ 7.0/10
14. [蚂蚁发布灵波深度 2.0 机器人视觉模型](#item-14) ⭐️ 7.0/10
15. [中国企业为机器人开发类脑 AI 系统](#item-15) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Ternlight：7MB 浏览器嵌入模型](https://ternlight-demo.vercel.app/) ⭐️ 8.0/10

Ternlight 是一个 7MB 的嵌入模型，完全通过 WebAssembly(WASM)在浏览器中运行，无需外部依赖即可实现本地文本相似性比较。 这项技术支持隐私保护的搜索和本地 AI 处理，使开发者能够创建不依赖外部 API 或云服务进行文本相似性任务的应用程序。 该模型通过三元量化感知训练从 MiniLM 蒸馏而来，推理引擎用 Rust 编写并编译为 WASM SIMD。它为文本输入输出 384 维向量，支持余弦相似性比较。

hackernews · soycaporal · 7月6日 23:06 · [社区讨论](https://news.ycombinator.com/item?id=48811644)

**背景**: WebAssembly(WASM)是一种低级二进制指令格式，旨在以接近原生的速度在浏览器中运行。嵌入模型将文本转换为捕获语义的数值向量，实现不依赖共享单词的相似性比较。量化是一种模型优化技术，通过降低精度来减少内存占用并提高推理速度，同时保持准确性。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.youtube.com/watch?v=cbB3QEwWMlA">Web Assembly ( WASM ) in 100 Seconds - YouTube</a></li>
<li><a href="https://www.linkedin.com/pulse/webassembly-wasm-future-web-performance-beyond-thisuri-bandaranayake-lhchc">WebAssembly ( Wasm ): The Future of Web Performance Beyond...</a></li>
<li><a href="https://grokipedia.com/page/Quantization_machine_learning">Quantization (machine learning)</a></li>

</ul>
</details>

**社区讨论**: 社区成员赞扬该项目在隐私保护搜索和本地 AI 处理方面的实际应用。一些建议添加演示触发按钮等 UI 改进，同时其他人讨论了与 DuckDB HNSW 搜索和离线搜索引擎等项目的集成可能性。整体情绪积极，开发者分享了实际用例和集成想法。

**标签**: `#AI embeddings`, `#browser AI`, `#WASM`, `#quantization`, `#local AI`

---

<a id="item-2"></a>
## [语言模型中的全局工作空间](https://www.anthropic.com/research/global-workspace) ⭐️ 8.0/10

Anthropic 发布了研究，探索语言模型如何维护全局工作空间，使早期 token 的信息能够影响序列中的未来预测。 理解这种全局工作空间机制对于改进 AI 内容创作至关重要，因为它揭示了模型如何处理和维持序列中的信息，这将显著影响提示工程和模型行为解释。 该研究考察了语言模型中的残差流如何使所有过去 token 的信息影响未来预测，而不仅仅是下一个 token，这是由于训练过程中对整个序列的损失进行求和/平均所致。

hackernews · in-silico · 7月6日 17:44 · [社区讨论](https://news.ycombinator.com/item?id=48808002)

**背景**: 语言模型逐个处理 token，基于先前上下文生成预测。"全局工作空间"概念源于认知科学和神经科学，在脑科学中指代一种理论机制，能够整合来自不同专门系统的信息。在 AI 领域，这个工作空间指的是信息如何在序列的不同部分保持并影响预测。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/research/global-workspace">A global workspace in language models \ Anthropic</a></li>
<li><a href="https://transformer-circuits.pub/2026/workspace/index.html">Verbalizable Representations Form a Global Workspace in Language ...</a></li>
<li><a href="https://biodivert.com/ai-tooling/a-global-workspace-in-language-models/">A Global Workspace In Language Models - BioDivert</a></li>

</ul>
</details>

**社区讨论**: 社区成员讨论了 LLM 中的残差流如何被训练以预测整个序列中的未来 token，而不仅仅是下一个。一位用户质疑了与意识的比较，解释说 J-Space 概念更多是关于跨上下文共享的抽象推理子空间，而非直接的人类认知平行。

**标签**: `#language-models`, `#AI-research`, `#model-architecture`, `#prompt-engineering`, `#anthropic`

---

<a id="item-3"></a>
## [AI 时代编程学习仍有价值](https://stevekrouse.com/learn-to-code) ⭐️ 8.0/10

文章认为尽管有 AI 进步，学习编程仍然有价值，编程正在从手动编码演变为监督 AI 工具。 这一讨论探讨了 AI 时代编程职业的未来，帮助开发者理解他们的角色将如何转变，以及哪些技能将继续保持重要性。 评论显示，虽然 LLM 可以生成代码，但人类程序员越来越需要监督和验证 AI 生成的代码，这创造了一个新的范式，即编程技能会演变而非过时。

hackernews · stevekrouse · 7月6日 20:59 · [社区讨论](https://news.ycombinator.com/item?id=48810439)

**背景**: 大型语言模型（如 GPT-4）在生成多种编程语言的代码方面展示了令人印象深刻的能力。这些 AI 工具可以创建 SQL 查询、编写 shell 命令并协助网站设计。然而，它们引入了'监督悖论'——AI 生成代码的速度越快，人类工程师就必须花费更多时间仔细检查，以确保代码不会破坏生产系统。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://aws.amazon.com/what-is/large-language-model/">What is LLM? - Large Language Models Explained - AWS</a></li>
<li><a href="https://www.linkedin.com/pulse/supervision-paradox-why-shipping-ai-generated-code-still-hyajf">AI Code Supervision Paradox: Solving the Validation Crisis</a></li>
<li><a href="https://medium.com/@josh-hall/working-with-lennie-the-reality-of-ai-code-supervision-bb49cbb7539e">The Reality of AI Code Supervision | Joshua Hall | Medium</a></li>

</ul>
</details>

**社区讨论**: 社区讨论呈现了多种观点，有人将编程比作'管道工程'而非创意表达，有人将其与数学类比——尽管有计算器，基本技能仍然必要，资深程序员指出他们的角色越来越像'监督模型，就像对待初级贡献者'。一些开发者主动选择不使用 LLM 辅助来构建项目，以保持他们的编程技能。

**标签**: `#AI and programming`, `#future of work`, `#coding education`, `#LLM impact`, `#tech career`

---

<a id="item-4"></a>
## [LeRobot v0.6.0：想象、评估、改进](https://huggingface.co/blog/lerobot-release-v060) ⭐️ 8.0/10

LeRobot v0.6.0 引入了新的'想象、评估、改进'方法论，使机器人能够将想象未来状态作为其训练过程的一部分，每个模型采用不同的方法来实现可负担的想象能力。 这次更新代表了人工智能驱动机器人的重要进展，通过提供结构化的机器人行为改进方法，使先进的机器人功能对开发人员和研究人员更加易于访问。 该框架包含预训练模型、人工收集的演示数据集和模拟环境，特别提到了 VLA-JEPA 架构，它在训练过程中学习想象未来。

rss · Hugging Face Blog · 7月7日 00:00

**背景**: LeRobot 是 Hugging Face 的开源机器人框架，旨在简化机器人系统的数据收集、训练和评估。该框架提供标准化格式和工具，使研究人员和开发人员能够更高效地构建机器人 AI。Hugging Face 计划在价格合理且功能强大的机器人上扩展对现实世界机器人应用的支持。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/blog/lerobot-release-v060">LeRobot v0.6.0: Imagine , Evaluate , Improve</a></li>
<li><a href="https://github.com/huggingface/lerobot">GitHub - huggingface/lerobot: LeRobot: Making AI for Robotics ...</a></li>
<li><a href="https://claru.ai/formats/lerobot-format">LeRobot Format for Robotics Data | Claru</a></li>

</ul>
</details>

**标签**: `#robotics`, `#AI applications`, `#Hugging Face`, `#open-source`, `#machine learning`

---

<a id="item-5"></a>
## [AI4S 转向自主发现](https://www.qbitai.com/2026/07/445067.html) ⭐️ 8.0/10

AI4S 正从辅助计算转向自主发现，标志着科研方法的范式转变。 这一转变可能加速所有领域的科学发现，重塑全球科研格局，并使中国成为 AI 驱动科学创新的领导者。 AI 现在正在生成假设、设计实验、分析数据，并在地球和气候科学等领域用高速模拟器取代计算密集型模拟。

rss · 量子位 · 7月7日 03:24

**背景**: AI for Science (AI4S)代表了 AI 创新与 AI 驱动科学发现的融合。它利用 AI 在模式识别、复杂系统建模和大规模数据分析方面的能力，加速科学领域的发现。这标志着从传统计算方法向更自主的科学发现过程的重大转变。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.nature.com/articles/d42473-025-00161-3">AI for Science 2025 - Nature</a></li>
<li><a href="https://hai.stanford.edu/news/how-ai-is-transforming-scientific-discovery-while-keeping-humans-at-the-center">How AI is Transforming Scientific Discovery While Keeping ...</a></li>
<li><a href="https://arxiv.org/html/2510.09901v1">Autonomous Agents for Scientific Discovery: Orchestrating Scientists, Language, Code, and Physics</a></li>

</ul>
</details>

**标签**: `#AI4S`, `#Scientific Discovery`, `#China AI Strategy`, `#Research Transformation`, `#Autonomous AI`

---

<a id="item-6"></a>
## [极简方案刷新扩散模型推理纪录](https://www.qbitai.com/2026/07/444721.html) ⭐️ 8.0/10

阿里巴巴和清华大学的研究人员开发了一种极简方案，显著提高了扩散模型的推理速度，在领域内创造了新纪录。 这一突破通过降低计算需求和提高效率，使扩散模型在实际应用中更加实用，可能加速 AI 生成内容的创建过程。 该研究论文被 ICML（国际机器学习会议）评为杰出论文，这是机器学习领域的三大顶级会议之一，凸显了其在领域内的重要性。

rss · 量子位 · 7月6日 10:33

**背景**: 扩散模型是一类生成模型，学习逆转向数据添加噪声的扩散过程，实现高质量图像生成。它们包含前向扩散过程和反向采样过程。这些模型广泛应用于计算机视觉任务，如图像生成、去噪和超分辨率。然而，它们的推理过程计算成本高，需要多次迭代生成输出，这限制了它们的实际应用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Diffusion_model">Diffusion model</a></li>
<li><a href="https://www.ibm.com/think/topics/diffusion-models">What are Diffusion Models? | IBM</a></li>
<li><a href="https://en.wikipedia.org/wiki/ICML">ICML</a></li>

</ul>
</details>

**标签**: `#diffusion-models`, `#inference-optimization`, `#icml`, `#ai-research`, `#generative-ai`

---

<a id="item-7"></a>
## [Kyutai 的 Pocket TTS：5 秒 CPU 语音克隆](https://www.reddit.com/r/LocalLLaMA/comments/1up07mk/kyutais_pocket_tts_clones_a_voice_from_5_seconds/) ⭐️ 8.0/10

Kyutai 的 Pocket TTS 引入了一种流式语言模型方法进行文本转语音，只需 5 秒音频参考就能克隆任何人的声音，完全在 CPU 上运行，且无论文本长度如何，延迟都保持一致。 这一突破使开发者能够在消费级硬件上实现零样本语音克隆，无需 GPU 要求，为开发者和创作者普及高质量语音合成，同时保持 MIT 许可用于商业用途。 Pocket TTS 使用约 1 亿参数的流式语言模型，在 Kyutai 的 Mimi 神经编解码器上生成音频令牌，无论文本长度如何，都能实现 0.69-0.76 的一致 RTF，在流式能力上优于传统 TTS 架构，但在速度上目前落后于 Kokoro 和 Supertonic 等替代方案。

reddit · r/LocalLLaMA · /u/gvij · 7月6日 15:14

**背景**: 文本转语音(TTS)技术将书面文本转换为语音，传统系统通常使用声学模型与声码器相结合。语音克隆允许 TTS 系统模仿特定声音，通常需要微调或大量计算资源。流式语言模型是一种较新的方法，能够增量生成输出，实现实时应用，且无论输入大小如何，延迟都保持一致。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/kyutai/mimi">kyutai/mimi · Hugging Face</a></li>
<li><a href="https://huggingface.co/docs/transformers/model_doc/mimi">Mimi · Hugging Face</a></li>
<li><a href="https://www.emergentmind.com/topics/ualm-gen">UALM-Gen: Unified Text-to- Audio Model</a></li>

</ul>
</details>

**社区讨论**: Reddit 帖子包含将 Pocket TTS 与其他 CPU TTS 模型(Kokoro、Supertonic、Inflect-Nano)的基准测试结果，作者指出尽管速度最慢，但由于其独特的语音克隆能力，Pocket TTS 仍然是最有趣的模型。社区特别感兴趣于使用不同类型声音进行语音克隆的实地测试。

**标签**: `#text-to-speech`, `#voice-cloning`, `#AI-models`, `#streaming-LLM`, `#benchmarking`

---

<a id="item-8"></a>
## [HOLA：海马体线性注意力模型](https://www.reddit.com/r/LocalLLaMA/comments/1upjq05/a_hippocampus_for_linear_attention_an_exact/) ⭐️ 8.0/10

研究人员开发了 HOLA（海马体线性注意力），一种新颖的方法，将线性注意力与受神经科学互补学习系统启发的精确内存缓存相结合，以解决语言模型中的信息丢失问题。 HOLA 解决了当前语言模型中的一个关键限制，防止在长上下文中丢失重要信息，可能需要长期记忆和上下文保留的任务的性能提升。 HOLA 将 delta-rule 状态保持为压缩内存，同时添加有界精确 KV 缓存，使用解耦的 RMSNorm-gamma 缓存读取进行精确检索而非软平均，并在 Wikitext 困惑度（-16.1%）和 LAMBADA 困惑度测试中取得卓越性能。

reddit · r/LocalLLaMA · /u/Thrumpwart · 7月7日 03:46

**背景**: 线性注意力和状态空间语言模型将输入序列压缩为固定大小的循环状态，以 O(1)内存复杂度为代价实现信息损失。这种压缩导致当多个键值关联竞争时，较早的事实被覆盖，导致长上下文任务性能下降。该方法受神经科学互补学习系统的启发，该系统表明海马体和大脑皮层协同工作以形成和存储记忆。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://haileyschoelkopf.github.io/blog/2024/linear-attn/">Linear Attention Fundamentals | Hailey Schoelkopf</a></li>
<li><a href="https://arxiv.org/html/2607.02303">A Hippocampus for Linear Attention An Exact Memory for What the...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Attention_(machine_learning)">Attention (machine learning) - Wikipedia</a></li>

</ul>
</details>

**标签**: `#attention-mechanisms`, `#language-models`, `#memory-systems`, `#neural-networks`, `#AI-research`

---

<a id="item-9"></a>
## [俄罗斯银行发布支持 GGUF 的 GigaChat3.5](https://www.reddit.com/r/LocalLLaMA/comments/1uotkm7/new_model_gigachat35432ba28b_with_day0_gguf/) ⭐️ 8.0/10

俄罗斯银行发布了 GigaChat3.5-432B-A28B，这是一款新的大型语言模型，并立即提供了 GGUF 格式支持，用于本地推理。 这具有重要意义，因为它为 AI 创作者提供了一个可以在本地运行而无需依赖云服务的强大模型，而第 0 天 GGUF 可用性对本地部署社区尤其有价值。 该模型有三个版本可用：基础版、标准版和 GGUF 版，GGUF 版本可通过特定拉取请求访问，因为它尚未进入主分支。

reddit · r/LocalLLaMA · /u/unbannedfornothing · 7月6日 10:34

**背景**: GGUF 是一种用于通过 GGML 存储模型以进行推理的文件格式，支持 2-8 位的各种量化选项。llama.cpp 是一个开源库，用于执行大型语言模型的推理，被认为是本地推理工具的事实标准。本地推理允许直接在边缘设备或本地服务器上运行模型，而无需依赖基于云的处理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/docs/diffusers/quantization/gguf">GGUF · Hugging Face</a></li>
<li><a href="https://en.wikipedia.org/wiki/Llama.cpp">Llama.cpp</a></li>
<li><a href="https://grokipedia.com/page/Local_inference">Local inference</a></li>

</ul>
</details>

**标签**: `#large-language-models`, `#gguf`, `#sberbank`, `#local-deployment`, `#model-release`

---

<a id="item-10"></a>
## [OfficeCLI：AI 代理办公套件](https://github.com/iOfficeAI/OfficeCLI) ⭐️ 7.0/10

OfficeCLI 是一个开源命令行工具，使 AI 代理能够读取、编辑和自动化 Microsoft Word、Excel 和 PowerPoint 文件，无需安装 Microsoft Office。 这款工具弥合了 AI 能力和文档处理之间的差距，使 AI 代理能够处理广泛使用的 Office 格式，这可以大大提高 AI 增强型内容创作者的生产力并自动化文档工作流程。 OfficeCLI 作为单个二进制文件运行，无依赖项，支持 CI/CD 环境和 Docker 容器的无头操作，并能将 Office 文件渲染为 HTML、SVG、截图和实时浏览器预览。

hackernews · maxloh · 7月6日 16:47 · [社区讨论](https://news.ycombinator.com/item?id=48807225)

**背景**: AI 代理越来越需要与文档格式交互，但 Microsoft Office 文件传统上需要安装完整的 Office 套件。这为自动化工作流程和服务器环境带来了挑战。命令行界面文档处理已成为无头文档操作的解决方案，使 AI 系统能够以编程方式与 Office 文档交互，无需图形界面。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/iOfficeAI/OfficeCLI">GitHub - iOfficeAI/OfficeCLI: OfficeCLI is the first and best Office suite...</a></li>
<li><a href="https://www.scriptbyai.com/office-cli-ai-agent/">OfficeCLI: Create & Edit Word, Excel, and PowerPoint Files with AI...</a></li>
<li><a href="https://office-cli.onl/">Office CLI</a></li>

</ul>
</details>

**社区讨论**: 社区讨论包括替代方案如 SmallDocs，关于 ECMA 376 标准的合规性问题，"Office"一词的商标问题，以及企业文档生成的挑战，包括验证和归因问题。

**标签**: `#AI-agents`, `#document-processing`, `#office-automation`, `#open-source`, `#productivity-tools`

---

<a id="item-11"></a>
## [Hugging Face 详细介绍 PRX 数据策略](https://huggingface.co/blog/Photoroom/prx-part4-data) ⭐️ 7.0/10

Hugging Face 发布了 PRX 系列的第四部分，专门介绍其计算机视觉项目背后的数据策略。 这份文档为真实世界的 AI 开发工作流程提供了宝贵的见解，特别是对于计算机视觉项目，帮助从业者理解如何在自己的实施中处理数据策略。 PRX 项目代表了 Hugging Face 将计算机视觉集成到视觉语言模型中的方法，本部分专门介绍数据收集、准备和管理策略。

rss · Hugging Face Blog · 7月6日 15:30

**背景**: Hugging Face 是机器学习和 AI 的领先平台，托管众多模型和数据集。PRX 项目似乎是他们在计算机视觉领域的举措，计算机视觉正越来越多地整合到视觉语言模型中。随着计算机视觉技术的发展，有效的数据策略对于模型开发和性能变得至关重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://groundy.com/articles/hugging-face-is-absorbing-computer-vision-into-vision-language-models/">Hugging Face Is Absorbing Computer Vision Into Vision ...</a></li>
<li><a href="https://github.com/huggingface/computer-vision-course">GitHub - huggingface/computer-vision-course: This repo is the ...</a></li>
<li><a href="https://github.com/maryammagy/huggingface-CV">Community-led Computer Vision Community Course - GitHub</a></li>

</ul>
</details>

**社区讨论**: 根据搜索结果，Hugging Face 的 Discord 服务器上似乎有一个活跃的计算机视觉社区，有专门的频道讨论计算机视觉课程和项目。这表明围绕 Hugging Face 的计算机视觉倡议有很强的社区参与度。

**标签**: `#data-strategy`, `#computer-vision`, `#hugging-face`, `#ai-implementation`, `#case-study`

---

<a id="item-12"></a>
## [腾讯发布 Hy3 MoE 模型](https://simonwillison.net/2026/Jul/6/hy3/#atom-everything) ⭐️ 7.0/10

腾讯发布了 Hy3，一个拥有 295B 参数的专家混合模型，其中只有 21B 是活跃参数，其性能超越同类规模模型，并能胜过参数量是其 2-5 倍的更大模型。 这一发布代表了中国科技公司在开源 AI 模型领域的重要进展，为研究人员和开发者提供了强大的专家混合架构，可能加速 AI 应用和生产力工具的创新。 Hy3 模型提供两个版本 - 完整的 598GB 版本和 300GB 的 FP8 量化版本 - 支持 256K tokens 的上下文长度，目前在 OpenRouter 上免费使用直至 7 月 21 日。

rss · Simon Willison · 7月6日 23:57

**背景**: 专家混合(MoE)是一种神经网络架构，将模型参数划分为较小的"专家"子网络，通过路由机制将每个输入 token 导向最相关的专家。这种方法允许模型容量更大而不会成比例增加计算成本。FP8 量化是一种通过 8 位浮点格式表示权重来减小模型大小的技术，能在几乎不损失精度的情况下实现更快的推理。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/blog/moe">Mixture of Experts Explained - Hugging Face</a></li>
<li><a href="https://www.spheron.network/blog/fp8-quantization-inference-performance-hardware-explained/">What is FP8 Quantization? AI Inference Performance, Accuracy, and Hardware Support Explained (2026) | Spheron Blog</a></li>
<li><a href="https://openrouter.ai/">OpenRouter</a></li>

</ul>
</details>

**标签**: `#AI models`, `#Mixture-of-Experts`, `#Tencent`, `#Large language models`, `#Open source`

---

<a id="item-13"></a>
## [首个空间原生具身视觉模型开源](https://www.qbitai.com/2026/07/445230.html) ⭐️ 7.0/10

蚂蚁灵波发布了首个空间原生的具身视觉开源模型，旨在提升机器人对物理世界的感知能力。 这一突破可能显著提升机器人的感知能力，实现更复杂的人机交互和在真实环境中的应用。 该模型结合了空间计算原理与具身人工智能，创建了一个能够以三维方式理解和与物理世界交互的视觉系统。

rss · 量子位 · 7月7日 04:48

**背景**: 具身人工智能被普遍认为是通用人工智能的关键组成部分，专注于控制实体在物理世界中执行任务。空间计算实现了在真实世界而非屏幕背后的三维人机交互技术。通过视觉-语言-动作模型整合这些领域代表了机器人能力的重大进步。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2405.14093">A Survey on Vision-Language-Action Models for Embodied AI Frontiers | A review of embodied intelligence systems: a ... A Survey on Vision-Language-Action Models for Embodied AI A Survey on Vision–Language–Action Models for Embodied AI Embodied AI 2026: From Robot Foundation Models to Industrial ... Alibaba's Qwen Team Enters Embodied AI With Qwen-VLA Model LAECIPS: Large vision model assisted adaptive edge–cloud ...</a></li>
<li><a href="https://en.wikipedia.org/wiki/Spatial_computing">Spatial computing - Wikipedia</a></li>
<li><a href="https://www.meegle.com/en_us/topics/spatial-computing/spatial-computing-in-robotics">Spatial Computing In Robotics</a></li>

</ul>
</details>

**标签**: `#AI vision`, `#robotics`, `#open-source`, `#embodied AI`, `#spatial computing`

---

<a id="item-14"></a>
## [蚂蚁发布灵波深度 2.0 机器人视觉模型](https://www.qbitai.com/2026/07/445184.html) ⭐️ 7.0/10

蚂蚁集团正式发布了灵波深度 2.0，这是一个更新的机器人视觉空间感知模型，在机器人视觉理解方面取得了突破，特别是在涉及镜子和玻璃的挑战性场景中表现优异。 这一进展具有重要意义，因为它增强了机器人感知和与复杂 3D 环境交互的能力，这对于自主导航、物体操作和现实环境中的人机交互等应用至关重要。 灵波深度 2.0 已通过奥比中光深度视觉实验室认证，可将不完整、有噪声的深度传感器数据转换为高质量、度量准确的 3D 测量结果，预计年底前推出集成相机产品。

rss · 量子位 · 7月7日 03:35

**背景**: 空间感知对机器人有效感知和与周围环境交互至关重要。它涉及感知 3D 结构、推理物体关系以及在物理约束下行动的能力。灵波深度 2.0 建立在视觉基础模型灵波视觉之上，构建了从'理解'到'精确感知'的能力链，以解决机器人视觉中的核心挑战。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://news.aibase.com/news/29432">Robot Vision Achieves New Breakthrough! Ant Group's LingBot-Depth...</a></li>
<li><a href="https://xix.ai/live/5700">Ant Group’s Lingbo Tech launched LingBot - Depth 2 . 0 , a spatia - xix.ai</a></li>
<li><a href="https://github.com/Robbyant/lingbot-depth">GitHub - Robbyant/ lingbot - depth : Masked Depth Modeling for Spatial...</a></li>

</ul>
</details>

**标签**: `#robot-vision`, `#computer-vision`, `#ai-models`, `#spatial-perception`, `#robotics`

---

<a id="item-15"></a>
## [中国企业为机器人开发类脑 AI 系统](https://www.qbitai.com/2026/07/444733.html) ⭐️ 7.0/10

一家中国公司在联合国展示了一种为机器人设计的类脑 AI 系统，该系统通过模仿神经处理而非依赖大量计算能力来减少计算需求。 这种方法可以显著减少 AI 系统的能源消耗，使机器人技术更加可持续和可及，同时可能解决与大量 AI 计算需求相关的日益增长的环境问题。 类脑 AI 系统似乎利用了神经形态计算原理，该原理通过小型计算元素模拟人脑的分布式处理，优先考虑鲁棒性和适应性而非原始计算能力。

rss · 量子位 · 7月6日 10:40

**背景**: 神经形态计算是一种受人类大脑结构和功能启发的计算方法，使用人工神经元执行计算。该领域整合了生物学、物理学、数学、计算机科学和电子工程，以开发模拟大脑形态和计算策略的系统。随着传统 AI 系统需要大量计算资源和能源消耗，开发节能 AI 变得越来越重要。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Neuromorphic_computing">Neuromorphic computing</a></li>
<li><a href="https://www.mdpi.com/2079-9292/13/19/3836">Energy Efficiency Evaluation of Artificial Intelligence ...</a></li>
<li><a href="https://garijohnson.substack.com/p/learning-from-asia-what-global-ai">Learning from Asia: What Global AI Development Can Gain from...</a></li>

</ul>
</details>

**标签**: `#AI applications`, `#robotics`, `#brain-like AI`, `#Chinese AI`, `#efficient AI`

---