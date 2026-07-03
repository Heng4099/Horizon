---
layout: default
title: "Horizon Summary: 2026-07-04 (ZH)"
date: 2026-07-04
lang: zh
---

> 从 36 条内容中筛选出 12 条重要资讯。

---

1. [本地运行最先进大模型指南](#item-1) ⭐️ 8.0/10
2. [谷歌 DeepMind 与 A24 启动 AI 研究合作](#item-2) ⭐️ 8.0/10
3. [Vercel 的代理框架 Eve](#item-3) ⭐️ 8.0/10
4. [DeepSeek V4 Flash 在 RTX 5090 上运行百万上下文](#item-4) ⭐️ 8.0/10
5. [PostgreSQL 内存管理与 OOM 杀手](#item-5) ⭐️ 7.0/10
6. [Fable 判断力最佳实践](#item-6) ⭐️ 7.0/10
7. [Meta 西瓜，Anthropic 三星芯片，自主研究](#item-7) ⭐️ 7.0/10
8. [448GB 显存 AI 系统令人惊叹](#item-8) ⭐️ 7.0/10
9. [Deepseek 发布 DSpark 重大突破](#item-9) ⭐️ 7.0/10
10. [葡萄牙发布开源大语言模型 Amalia](#item-10) ⭐️ 7.0/10
11. [美团发布量化版 LongCat 2 模型](#item-11) ⭐️ 7.0/10
12. [AI 安全工具 Strrix 快速获得采用](#item-12) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [本地运行最先进大模型指南](https://github.com/jamesob/local-llm) ⭐️ 8.0/10

Jamesob 发布了一份全面的指南，介绍如何在本地运行最先进的大语言模型，包括详细的硬件建议和成本考量。 这份指南帮助用户就投资本地 AI 基础设施做出明智决定，解决了对隐私、定制化和避免持续云订阅成本日益增长的需求。 该指南建议从 4 万美元的硬件设置开始，每块 GPU 成本 1.2 万美元（总计 5-5.5 万美元），并涵盖量化技术和云提供商等替代方案。

hackernews · livestyle · 7月3日 15:03 · [社区讨论](https://news.ycombinator.com/item?id=48775921)

**背景**: 最先进（SOTA）AI 模型代表了目前最先进和创新的模型，为性能和能力设定了新标准。大语言模型（LLM）是在大量文本数据上训练的深度学习系统，能够理解和生成类人文本。在本地运行 LLM 可提供隐私、定制化和避免持续云成本等优势，有多种框架可用，包括 Ollama、LM Studio、vLLM 和 llama.cpp。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://acecloud.ai/blog/state-of-the-art-models/">State-of-the-Art (SOTA) AI Models: The Complete Guide</a></li>
<li><a href="https://www.ibm.com/think/topics/large-language-models">What Are Large Language Models ( LLMs )? | IBM</a></li>
<li><a href="https://www.datacamp.com/tutorial/run-llms-locally-tutorial">Run LLMs Locally: 6 Simple Methods | DataCamp</a></li>

</ul>
</details>

**社区讨论**: 社区成员分享不同硬件配置的实际经验，辩论本地设置与云服务之间的成本效益。用户推荐 RTX 3090 或 Intel Arc B70 等替代方案，有人指出配备 48GB 共享内存的 MacBook Pro 可能是比多 GPU 更紧凑的解决方案。

**标签**: `#local-llm`, `#hardware`, `#ai-deployment`, `#practical-guide`, `#cost-analysis`

---

<a id="item-2"></a>
## [谷歌 DeepMind 与 A24 启动 AI 研究合作](https://deepmind.google/blog/google-deepmind-and-a24-announce-first-of-its-kind-research-partnership/) ⭐️ 8.0/10

谷歌 DeepMind 与 A24 宣布了一项开创性的研究合作，旨在探索 AI 在娱乐和创意产业中的应用，这是 AI 研究组织与电影制作公司之间的首次合作。 这项合作代表了 AI 在娱乐和创意产业中的一个重要新应用领域，可能为 AI 增强型创作者开辟新的内容创作可能性和商业模式。 这项合作结合了谷歌 DeepMind 先进的 AI 研究能力和 A24 在制作和发行独立电影方面的专业知识，可能为内容创作、故事叙述和观众互动带来创新的 AI 工具。

rss · Google DeepMind · 7月3日 14:25

**背景**: A24 是一家总部位于纽约的美国独立电影制作和发行公司，由电影高管丹尼尔·卡茨、大卫·芬克尔和约翰·霍奇斯于 2012 年创立。该公司凭借《春假》等影片获得认可，此后以制作和发行备受好评的独立电影和电视节目而闻名。谷歌 DeepMind 于 2014 年被谷歌收购，是一家领先的 AI 研究组织，以在人工智能和机器学习方面的突破性成果而闻名。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/A24">A24 - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/List_of_A24_films">List of A24 films - Wikipedia</a></li>
<li><a href="https://www.britannica.com/topic/A24">A24 | Production Company, History, Films, & Television Shows | Britannica</a></li>

</ul>
</details>

**标签**: `#AI partnerships`, `#Entertainment industry`, `#Creative applications`, `#Google DeepMind`, `#A24`

---

<a id="item-3"></a>
## [Vercel 的代理框架 Eve](https://www.latent.space/p/vercel-agents-new-software) ⭐️ 8.0/10

Vercel 的首席软件工程师介绍了公司的代理框架'eve'，解释了技能、沙箱和代理可读网站如何代表软件开发的新范式。 这很重要，因为它代表了软件设计和与网络交互方式的根本转变，可能改变开发者构建能够自主理解和导航数字环境的应用程序的方式。 该框架专注于三个关键组件：技能（代理可以执行的能力）、沙箱（安全执行的隔离环境）和代理可读网站（为机器理解而结构化的网络内容）。

rss · Latent Space · 7月3日 00:08

**背景**: AI 代理是能够通过理解和与数字环境交互来代表用户执行任务的自主程序。Vercel 以其前端开发平台而闻名，正在扩展到 AI 驱动的开发工具。'eve'框架代表了他们创建更智能、自主软件组件的方法。

**标签**: `#AI agents`, `#Vercel`, `#software development`, `#eve framework`, `#paradigm shift`

---

<a id="item-4"></a>
## [DeepSeek V4 Flash 在 RTX 5090 上运行百万上下文](https://www.reddit.com/r/LocalLLaMA/comments/1ulymml/llamacpp_patch_deepseek_v4_flash_running_with/) ⭐️ 8.0/10

一名开发者为 llamacpp 实现了一个 CUDA 内核补丁，使 DeepSeek V4 Flash 能够在 RTX 5090 上本地运行百万令牌上下文，将 VRAM 需求从约 256GB 降低到约 3.75GB。 这一突破显著改善了本地 AI 部署能力，使大上下文窗口在消费级硬件上变得可行，实现了之前需要大型服务器基础设施才能应用的实用功能。 该补丁实现了 DSA lightning indexer 的 CUDA 内核支持，该功能之前缺乏适当的 llamacpp 集成。性能指标显示，在 256K 上下文中，预填充速度从 56 t/s 提高到 263 t/s，而解码速度保持在约 14 t/s。

reddit · r/LocalLLaMA · /u/da_dragon321 · 7月2日 23:54

**背景**: llama.cpp 是一个开源软件库，用于在各种大型语言模型上进行推理，与 GGML 张量库共同开发。它被认为是本地推理工具的实际标准。CUDA 内核是程序员编写的 CUDA 代码单元，在 GPU 上运行，实现并行处理。DSA（DeepSeek Attention）lightning indexer 是一种技术，降低了注意力机制的计算复杂度，使其对大上下文窗口更高效。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Llama.cpp">Llama.cpp</a></li>
<li><a href="https://modal.com/gpu-glossary/device-software/kernel">What is a CUDA Kernel ? | GPU Glossary</a></li>
<li><a href="https://deepseekv4.app/features/lightning-indexer">DeepSeek Lightning Indexer - Repo-Level Context</a></li>

</ul>
</details>

**标签**: `#LocalLLaMA`, `#DeepSeek`, `#CUDA`, `#llamacpp`, `#Context window`

---

<a id="item-5"></a>
## [PostgreSQL 内存管理与 OOM 杀手](https://www.ubicloud.com/blog/postgresql-and-the-oom-killer-why-we-use-strict-memory-overcommit) ⭐️ 7.0/10

文章解释了为什么 PostgreSQL 提供商使用严格的内存过度提交而非 Linux 默认设置，以避免在内存压力下出现 OOM 杀手问题。 这种方法可以防止系统不稳定和意外的进程终止，对于在生产环境中管理 PostgreSQL 部署的数据库管理员和 DevOps 专业人员至关重要。 Linux 支持三种过度提交处理模式（0、1、2），其中模式 2（严格）是 PostgreSQL 的首选方法，因为它跟踪所有进程的总提交虚拟内存并强制执行称为 CommitLimit 的上限。

hackernews · furkansahin · 7月3日 13:00 · [社区讨论](https://news.ycombinator.com/item?id=48774509)

**背景**: Linux 内存不足（OOM）杀手是内核进程，当系统内存严重不足时终止应用程序。默认情况下，Linux 使用启发式过度提交处理（模式 0），它拒绝明显的地址空间过度提交，同时允许一些过度提交以减少交换使用。这种默认行为可能导致 OOM 杀手在内存压力下意外终止 PostgreSQL 进程。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.ubicloud.com/blog/postgresql-and-the-oom-killer-why-we-use-strict-memory-overcommit">PostgreSQL and the OOM Killer: Why We Use Strict Memory Overcommit</a></li>
<li><a href="https://www.kernel.org/doc/Documentation/vm/overcommit-accounting">The Linux kernel supports the following overcommit handling modes</a></li>
<li><a href="https://www.postgresql.org/docs/current/kernel-resources.html">PostgreSQL: Documentation: 18: 18.4. Managing Kernel Resources</a></li>

</ul>
</details>

**社区讨论**: 技术专家普遍同意博客的内容，但警告说严格的内存过度提交在某些情况下可能产生意想不到的副作用。一些人建议在 PostgreSQL 中实现自定义内存管理，而不是仅仅依赖内核设置，而另一些人建议在生产环境中实施严格过度提交之前进行仔细测试。

**标签**: `#PostgreSQL`, `#Memory Management`, `#Linux Kernel`, `#Database Administration`, `#DevOps`

---

<a id="item-6"></a>
## [Fable 判断力最佳实践](https://simonwillison.net/2026/Jul/3/judgement/#atom-everything) ⭐️ 7.0/10

Simon Willison 分享了更有效使用 Fable 的最佳实践，让 Fable 行使其自己的判断力而不是规定具体工作流程，并为小任务使用替代模型以在价格上涨前节省代币。 这些实践帮助开发者优化工作流程效率并降低成本，随着 Fable 定价上涨，让他们能够完成更多工作同时节省代币配额。 该方法涉及告诉 Fable 在决定编写测试时使用自己的判断力，并将编码任务委托给运行较低功率模型的子代理，例如用于实质性实现的 Sonnet 和用于琐碎编辑的 Haiku。

rss · Simon Willison · 7月3日 18:51

**背景**: Fable 是 Anthropic 开发的 AI 编码工具，擅长长期推理和适应不熟悉的工具。Claude Code 是 Anthropic 的代理编码系统，可在整个项目中运行，理解代码库并自主完成开发任务。随着 AI 工具变得更加复杂，开发者正在学习与它们的判断能力协作，而不是施加严格的限制。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/claude/fable">Claude Fable \ Anthropic</a></li>
<li><a href="https://www.anthropic.com/product/claude-code">Claude Code | Anthropic's agentic coding system \ Anthropic</a></li>

</ul>
</details>

**标签**: `#AI coding tools`, `#Fable`, `#Claude Code`, `#AI efficiency`, `#token optimization`

---

<a id="item-7"></a>
## [Meta 西瓜，Anthropic 三星芯片，自主研究](https://tldr.tech/ai/2026-07-03) ⭐️ 7.0/10

Meta 的西瓜 AI 模型已赶上 OpenAI 的 GPT-5.5 在关键基准测试上的表现，据 Meta 的超级智能主管 Alexandr Wang 称。Anthropic 正与三星洽谈制造定制 AI 芯片，这是其他 AI 公司为控制其计算基础设施而采取的类似举措。 这些发展凸显了 AI 模型能力和硬件基础设施竞争的加剧。先进 AI 模型与专用硬件的结合可能会加速创新，同时可能重塑 AI 行业的竞争格局。 Meta 的西瓜模型仍在训练中，尚未公开发布。Anthropic 的芯片开发处于早期阶段，三星被视为 2nm 芯片的潜在制造合作伙伴。

rss · TLDR AI · 7月3日 00:00

**背景**: 像 GPT-5.5 这样的 AI 模型代表了当前大型语言模型的最先进水平，基准测试是评估其能力的一种标准方式。定制 AI 芯片正变得越来越重要，因为公司寻求优化性能并降低 AI 运营成本。自主研究系统是一个新兴领域，AI 可以独立进行研究、分析数据和生成见解。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://tldr.tech/ai/2026-07-03">Meta Watermelon , Anthropic Samsung chips, autoresearch in...</a></li>
<li><a href="https://www.businessinsider.com/meta-ai-model-catches-up-openai-gpt-5-says-2026-7">Meta 's Watermelon AI Model Has Caught up to... - Business Insider</a></li>
<li><a href="https://finance.yahoo.com/technology/ai/articles/anthropic-explores-samsung-2nm-chip-144844786.html">Anthropic explores Samsung 2nm chip partnership - The Information</a></li>

</ul>
</details>

**标签**: `#AI Models`, `#Hardware Partnerships`, `#Research Automation`, `#Meta AI`, `#Anthropic`

---

<a id="item-8"></a>
## [448GB 显存 AI 系统令人惊叹](https://www.reddit.com/r/LocalLLaMA/comments/1umokhj/uh_honey_how_do_you_feel_about_takeout/) ⭐️ 7.0/10

一位用户展示了他们令人印象深刻的 448GB 显存 AI 系统，该系统运行 MiniMax M3 模型，使用 AWQ-INT4 量化，通过 vLLM 和流水线并行实现，每流达到 30 个 token/秒，批处理达到 960 个 token/秒的强大性能指标。 这个高性能 AI 系统展示了大规模运行大型语言模型的实际实现细节，为构建系统的 AI 专业人士提供了宝贵的见解，并突出了前沿 LLM 部署所需的硬件要求。 该系统包括 2 个 RTX Pro 6000 Max-Q（96GB）、8 个 RTX 3090（24GB）、2 个 RTX 5090（32GB）、128GB DDR5 内存和 Threadripper 9960x CPU，在 vLLM 上以 AWQ-INT4 格式运行 MiniMax M3，使用 2 个张量并行组的流水线并行。

reddit · r/LocalLLaMA · /u/MotorcyclesAndBizniz · 7月3日 20:02

**背景**: vLLM 是一个开源软件框架，用于高效推理和服务大型语言模型，基于 PagedAttention 内存管理方法。AWQ-INT4 是一种量化技术，可将 GPU 内存使用减少约 50%，同时保持最小的质量损失。流水线并行将模型分割为多个阶段以并发处理更多请求，而张量并行则将操作分割到多个 GPU 上以更快完成。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/VLLM">VLLM</a></li>
<li><a href="https://medium.com/data-science-at-microsoft/a-practical-guide-to-int4-quantization-for-slms-gptq-vs-awq-olive-and-real-world-results-2f63d6963d1d">A practical guide to INT4 quantization for SLMs: GPTQ vs AWQ, Olive, and ...</a></li>
<li><a href="https://www.peakinfer.com/blog/tensor-vs-pipeline-parallelism-when-each-wins">Tensor vs Pipeline Parallelism : When Each Wins | PeakInfer Blog</a></li>

</ul>
</details>

**社区讨论**: 帖子中包含关于此类昂贵硬件'婚姻成本'的幽默评论，暗示围绕高端 AI 设置的经济和个人影响的社区讨论。

**标签**: `#AI hardware`, `#GPU computing`, `#Large language models`, `#Model deployment`, `#Performance benchmarking`

---

<a id="item-9"></a>
## [Deepseek 发布 DSpark 重大突破](https://www.reddit.com/r/LocalLLaMA/comments/1um9j5q/deepseek_drops_another_huge_breakthrough_dspark/) ⭐️ 7.0/10

Deepseek 推出了 DSpark，一种推测解码框架，声称可以使现有的 DeepSeek 模型在保持相同输出质量的情况下，生成响应的速度提高 60-85%。 这一突破可能会显著提高大语言模型推理的效率，使 AI 应用响应更快，并可能降低企业和开发者的计算成本。 DSpark 被描述为一种使用推测解码来加速 LLM 推理的开源框架，并且可以在 Hugging Face 上作为 DeepSeek-V4-Flash-DSpark 获取。

reddit · r/LocalLLaMA · /u/BringTea_666 · 7月3日 09:19

**背景**: 推测解码是一种在大语言模型中使用的技术，通过让较小的模型在主模型之前预测多个标记，然后验证这些预测，从而加速推理。这种方法可以在不降低输出质量的情况下显著减少延迟。混合专家(MoE)是一种使用多个专业神经网络的架构，其中只有一部分"专家"被激活以处理每个输入，从而实现更高效的计算。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://medium.com/data-science-in-your-pocket/deepseek-dspark-85-faster-llm-inferencing-866b93781769">DeepSeek DSpark : 85% faster LLM inferencing | by Mehul... | Medium</a></li>
<li><a href="https://www.youtube.com/watch?v=IQriB7ONDnQ">DeepSeek DSpark Explained: 85% Faster LLM Inference - YouTube</a></li>
<li><a href="https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash-DSpark">deepseek -ai/ DeepSeek -V4-Flash- DSpark · Hugging Face</a></li>

</ul>
</details>

**标签**: `#Deepseek`, `#DSpark`, `#AI models`, `#breakthrough`, `#performance`

---

<a id="item-10"></a>
## [葡萄牙发布开源大语言模型 Amalia](https://www.reddit.com/r/LocalLLaMA/comments/1umhrn8/portugal_just_released_their_own_llm_amalia_9b/) ⭐️ 7.0/10

葡萄牙发布了自己的 90 亿参数开源大语言模型 Amalia，采用 Apache 2.0 许可证，并在 Hugging Face 上提供了 SFT 和 DPO 两个版本。 这是葡萄牙政府支持的开源大语言模型的重要发布，为全球开源 AI 生态系统做出了贡献，并为研究人员和开发者提供了区域语言模型的另一个选择。 Amalia 提供两个版本 - SFT（监督微调）用于特定任务适应，DPO（直接偏好优化）用于与人类偏好对齐，但目前尚未发布简洁的编码基准测试。

reddit · r/LocalLLaMA · /u/EveningIncrease7579 · 7月3日 15:38

**背景**: Apache 2.0 是一种宽松的开源许可证，允许用户自由使用、修改和分发软件，同时保留版权声明。监督微调（SFT）是一种使用人工标注的输入-输出对来使预训练语言模型适应特定任务的过程，而直接偏好优化（DPO）是一种无需大量人工标注即可使大语言模型与人类偏好对齐的方法。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.apache.org/licenses/LICENSE-2.0">Apache License , Version 2 . 0 | Apache Software Foundation</a></li>
<li><a href="https://cameronrwolfe.substack.com/p/understanding-and-using-supervised">Understanding and Using Supervised Fine - Tuning ( SFT ) for...</a></li>
<li><a href="https://medium.com/mantisnlp/supervised-fine-tuning-customizing-llms-a2c1edbf22c3">Supervised Fine - tuning : customizing LLMs | by Juan Martinez | Medium</a></li>

</ul>
</details>

**社区讨论**: Reddit 帖子表明这最初由用户 EveYogaTech 在另一个子版块发布，感谢用户 EveningIncrease7579 分享。内容中没有提供重要的社区讨论。

**标签**: `#open-source`, `#LLM`, `#Portugal`, `#government-AI`, `#HuggingFace`

---

<a id="item-11"></a>
## [美团发布量化版 LongCat 2 模型](https://www.reddit.com/r/LocalLLaMA/comments/1umo8zu/longcat_2_model_weights_have_been_published/) ⭐️ 7.0/10

美团已在 Hugging Face 上发布了 LongCat 2.0 模型的 INT8 和 FP8 量化版本，这使得拥有 1.6 万亿参数的专家混合模型对具有不同硬件能力的开发者更加友好。 这次发布使得之前只能通过 OpenRouter 以'Owl Alpha'身份访问的巨型 AI 模型变得民主化，使研究人员和开发者能够使用这种最先进的语言模型进行实验和构建应用程序，而无需昂贵的硬件设施。 LongCat 2.0 模型采用专家混合架构，在 1.6 万亿总参数中约有 480 亿活跃参数，支持 100 万 token 的上下文长度，使其特别适合长上下文应用场景。

reddit · r/LocalLLaMA · /u/RhubarbSimilar1683 · 7月3日 19:49

**背景**: LongCat 2.0 是中国科技公司美团开发的大型语言模型，在 6 月 30 日正式发布前，曾以'Owl Alpha'的匿名身份在 OpenRouter 上运行了两个月。量化是一种将模型权重从 FP32 等高精度格式降低到 INT8 或 FP8 等低精度格式的技术，可以显著减小模型大小，同时保持大部分性能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://decrypt.co/372579/longcat-2-0-meituan-ai-stealth-model-openrouter">LongCat - 2 .0: The Stealth AI Model That Was Quietly... - Decrypt</a></li>
<li><a href="https://digg.com/tech/wm4yt33n">LongCat - 2 .0 releases a 1.6-trillion-parameter open-source MoE model ...</a></li>
<li><a href="https://systeminternals.dev/llm/quantization/">LLM Quantization — int 8 , int4, fp 8 , GPTQ, AWQ, BitNet</a></li>

</ul>
</details>

**标签**: `#AI models`, `#language models`, `#LongCat`, `#model weights`, `#quantization`

---

<a id="item-12"></a>
## [AI 安全工具 Strrix 快速获得采用](https://github.com/usestrix/strix) ⭐️ 7.0/10

开源 AI 安全工具 Strrix 在短短 24 小时内获得了 50 个 GitHub 星标，表明社区对其使用 AI 进行漏洞检测和修复的方法产生了浓厚兴趣。 Strrix 代表了 AI 增强安全测试的重要进展，可能通过自动化传统上耗时的手动流程，改变开发人员识别和修复应用程序漏洞的方式。 Strrix 是一个基于 Python 的开源工具，通过运行代码、探测端点并通过实际利用确认漏洞来充当'AI 黑客'，提供带有概念验证和重现步骤的验证结果。

ossinsight · usestrix · 7月3日 21:11

**背景**: 应用程序漏洞检测传统上依赖于手动代码审查和自动化扫描工具，这些工具通常会产生嘈杂的结果。AI 驱动的安全测试正在作为一种解决方案出现，通过更有效地模拟真实攻击者行为来克服这些限制。传统方法难以跟上现代应用程序日益增长的复杂性，从而需要像 Strix 这样更先进的方法。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/usestrix/strix">GitHub - usestrix/ strix : Open-source AI penetration testing tool to find...</a></li>
<li><a href="https://medium.com/data-science-collective/strix-the-open-source-ai-agent-for-security-testing-44e1ed244a9d">Strix : The Open-Source AI Agent for Security Testing | Medium</a></li>
<li><a href="https://www.strix.ai/">Strix - Autonomous Security for the AI Era</a></li>

</ul>
</details>

**社区讨论**: 搜索结果中未提供具体的社区评论，但星标的快速积累表明对 AI 驱动安全解决方案感兴趣的开发者社区有强烈的积极反响。

**标签**: `#AI-security`, `#vulnerability-detection`, `#open-source`, `#Python`, `#app-security`

---