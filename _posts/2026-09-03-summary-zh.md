---
layout: default
title: "Horizon Summary: 2026-09-03 (ZH)"
date: 2026-09-03
lang: zh
---

> 从 44 条内容中筛选出 14 条重要资讯。

---

1. [谷歌发布 Gemini 3.8 Flash 模型](#item-1) ⭐️ 8.0/10
2. [AI 系统引用制造来源](#item-2) ⭐️ 8.0/10
3. [DeepMind AI 政府网络安全防御](#item-3) ⭐️ 8.0/10
4. [Claude Fable 5.1 展示科学基准改进](#item-4) ⭐️ 8.0/10
5. [重大 AI 发展：Fable 5.1、Atlas 和 Cognition 融资](#item-5) ⭐️ 8.0/10
6. [蚂蚁 OmniTable 系统获 VLDB 2026 最佳论文](#item-6) ⭐️ 8.0/10
7. [阿里更新 Qwen3.8-Max，前端编程能力全球第一](#item-7) ⭐️ 8.0/10
8. [李飞飞发布全球首个多模态世界模型](#item-8) ⭐️ 8.0/10
9. [GLM 5.3 Flash 创造黑洞 Minecraft 模组](#item-9) ⭐️ 8.0/10
10. [Meta 发布 Muse Spark 1.3](#item-10) ⭐️ 7.0/10
11. [Qwen 的 AI 霸主潜力](#item-11) ⭐️ 7.0/10
12. [Q8 N-gram 集成保持 Qwen 速度](#item-12) ⭐️ 7.0/10
13. [MLX 与 llama.cpp 在苹果 M5 上的性能对比](#item-13) ⭐️ 7.0/10
14. [Perplexity 开源 Qwen 3.6 Mac 推理服务器](#item-14) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [谷歌发布 Gemini 3.8 Flash 模型](https://blog.google/innovation-and-ai/models-and-research/gemini-models/3-8-flash-and-3-8-flash-cyber/) ⭐️ 8.0/10

谷歌发布了 Gemini 3.8 Flash 和 3.8 Flash Cyber 模型，这些模型展现出与顶级模型相竞争的性能，同时在 HTML/JavaScript 生成和现实世界知识方面提供了改进的功能。 这次发布具有重要意义，它代表了谷歌在 AI 模型能力方面的持续进步，可能会影响软件开发工作流程和现实世界的应用，如旅行规划和文档解析。 3.8 Flash 模型定价为每百万输入令牌 0.75 美元，每百万输出令牌 3.75 美元，与之前的 3.7 Flash 相同，并支持可定制的努力级别来控制质量、成本和延迟的平衡。

hackernews · bratao · 9月2日 15:12 · [社区讨论](https://news.ycombinator.com/item?id=49537553)

**背景**: Gemini 是谷歌的 AI 模型系列，包含针对不同任务优化的各种版本。Flash 模型旨在提供更具成本效益的性能，同时保持强大的能力。AI 基准测试是通过使用标准化任务和数据集来评估和比较 AI 模型以建立相对性能的做法。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://blog.google/innovation-and-ai/models-and-research/gemini-models/3-8-flash-and-3-8-flash-cyber/">Introducing Gemini 3.8 Flash and 3.8 Flash Cyber - The Keyword</a></li>
<li><a href="https://deepmind.google/models/model-cards/gemini-3-8-flash/">Gemini 3.8 Flash - Model Card — Google DeepMind</a></li>

</ul>
</details>

**社区讨论**: 社区成员对模型的速度和 HTML/JavaScript 生成能力感到兴奋，有用户仅用 1.8 美分和 13 秒就创建了一个功能性的网络应用程序。用户报告称该模型在旅行规划、照片排名和文档解析等现实世界知识应用方面表现出色。

**标签**: `#AI models`, `#Google Gemini`, `#model release`, `#benchmarking`, `#AI applications`

---

<a id="item-2"></a>
## [AI 系统引用制造来源](https://trellner.com/reports/manufactured-sources-behind-ai-recommendations/) ⭐️ 8.0/10

三个网站创建了超过 21.5 万个制造出来的"最佳软件"页面，这些页面被 Perplexity 等 AI 系统引用，可能传播低质量推荐。 这揭示了 AI 推荐系统引用制造来源的重大问题，对 AI 内容质量和可靠性有重要影响，可能用虚假信息误导用户。 这些制造页面专门针对 AI 系统设计，旨在被 AI 引用，形成了一个反馈循环，其中 AI 系统推荐专门为被 AI 推荐而创建的低质量内容。

hackernews · jakobgreenfeld · 9月2日 13:59 · [社区讨论](https://news.ycombinator.com/item?id=49536375)

**背景**: Perplexity AI 是一个 AI 驱动的搜索引擎，使用大型语言模型处理用户查询并合成响应，结合实时网络搜索功能并引用使用的来源。内容农场是指生成大量网络内容的组织，这些内容专门设计用于满足搜索引擎算法以获得最大检索量，自 2022 年以来通常使用生成式 AI 工具。这种做法优先考虑数量而非质量，可能传播错误信息。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Perplexity_AI">Perplexity AI</a></li>
<li><a href="https://en.wikipedia.org/wiki/Content_farming">Content farming</a></li>

</ul>
</details>

**社区讨论**: 社区成员讨论了 LLM 如何偏爱自己生成的内容而非人类编写的内容，一位用户指出 Claude 始终偏爱自己生成的代码片段。其他人报告了 AI 系统的问题，包括虚假信息，例如被推荐为拥有"最佳街头食品"的不存在的地点，以及关于 AI 系统为速度而非结果质量进行优化的担忧。

**标签**: `#AI-recommendations`, `#content-quality`, `#AI-sourcing`, `#misinformation`, `#Perplexity`

---

<a id="item-3"></a>
## [DeepMind AI 政府网络安全防御](https://deepmind.google/blog/proactive-cyber-defense-for-governments-and-enterprises/) ⭐️ 8.0/10

Google DeepMind 推出了专门用于保护政府和企事业系统的人工智能主动网络防御方法，以应对不断演变的网络威胁。 这一发展具有重要意义，因为它针对针对关键基础设施和敏感数据的日益复杂的网络攻击，可能通过从被动防御转向主动防御策略，彻底改变政府和企事业机构处理网络安全的方式。 DeepMind 的方法利用先进的人工智能和机器学习技术来预测和防止网络威胁在形成之前发生，尽管具体的技术实施细节和性能指标在现有信息中仍然有限。

rss · Google DeepMind · 9月2日 16:24

**背景**: 主动网络防御代表了从传统被动安全措施的转变，专注于在威胁造成损害之前预测和防止它们。与在事件发生后做出响应的传统方法不同，主动防御涉及采取先发制人的行动来识别、分析和减轻潜在风险。Google DeepMind 是一家英美 AI 研究实验室，也是 Alphabet Inc.的子公司，一直处于将 AI 应用于复杂挑战的前沿，包括现在关键领域的网络安全。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Google_DeepMind">Google DeepMind - Wikipedia</a></li>
<li><a href="https://en.wikipedia.org/wiki/Proactive_cyber_defence">Proactive cyber defence - Wikipedia</a></li>

</ul>
</details>

**标签**: `#cybersecurity`, `#AI applications`, `#enterprise security`, `#government technology`, `#proactive defense`

---

<a id="item-4"></a>
## [Claude Fable 5.1 展示科学基准改进](https://simonwillison.net/2026/Sep/1/claude-fable-5-1/) ⭐️ 8.0/10

Anthropic 发布了 Claude Fable 5.1，在 Terminal-Bench-Science 0.1 基准测试中取得了 52.6% 的分数，显著优于之前的版本和竞争模型。作者通过在不同推理级别下生成骑自行车的鹈鹕 SVG 插图来测试其图像生成能力。 科学基准测试的显著改进表明 Fable 5.1 在知识工作和长期问题解决任务方面增强了能力，可能加速科学研究工作流程。模型在图像生成等创意任务上的表现也展示了其超越纯分析工作的多功能性。 Fable 5.1 有五个推理级别：低、中、高、xhigh 和 max，没有完全关闭推理的选项。作者发现，在低和中设置下，模型似乎完全跳过了鹈鹕提示的推理，而高推理级别产生了更详细的结果，具有更高的标记数和成本。

rss · Simon Willison · 9月1日 23:57

**背景**: Terminal-Bench-Science 是一个基准测试，用于评估 AI 模型在终端环境中执行复杂真实世界科学工作流程的能力。鹈鹕基准测试测试 AI 模型创建骑自行车的鹈鹕 SVG 图像的能力，作为对模糊环境下多步推理的创意评估。Claude Fable 是 Anthropic 供一般使用的标准模型，而 Mythos 是一个功能更强大的变体，具有解除的安全保障，适用于网络防御等特定应用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.terminal-bench-science.ai/">TERMINAL - BENCH - SCIENCE</a></li>
<li><a href="https://huggingface.co/spaces/victor/pelican-benchmark">Pelican Benchmark - a Hugging Face Space by victor</a></li>
<li><a href="https://www.hackaigc.com/blog/claude-fable-5-vs-5-1-mythos-comparison-2026">Claude Fable 5 vs 5.1 vs Mythos 5 vs 5.1: Full Version Comparison — Should You Upgrade or Leave?</a></li>

</ul>
</details>

**标签**: `#AI models`, `#Claude`, `#benchmarking`, `#scientific AI`, `#AI coding`

---

<a id="item-5"></a>
## [重大 AI 发展：Fable 5.1、Atlas 和 Cognition 融资](https://tldr.tech/ai/2026-09-02) ⭐️ 8.0/10

Anthropic 发布了 Claude Fable 5.1 和 Mythos 5.1，这是用于编程和知识工作的先进 AI 模型，具有更快的推理能力和 50%更低的代币成本。World Labs 推出了 Atlas，这是一个能够处理文本、图像、视频和 3D 的通用模型，用于空间智能。Cognition AI 以 470 亿美元的估值获得了 10 亿美元融资。 这些发展标志着在编程、空间智能和融资方面的 AI 能力取得了重大进展，可能加速 AI 在各行业的应用。Cognition 的巨大估值反映了投资者对专业 AI 解决方案的日益增长的信心，而 Fable 5.1 和 Atlas 则展示了向更通用、更高效的 AI 系统迈进的进展。 Fable 5.1 和 Mythos 5.1 本质上是同一模型，但具有不同的安全级别，专门为编程和知识工作设计。Atlas 是 World Labs 继 Marble 之后的第二个主要世界模型，为空间智能应用提供原生多模态能力。Cognition 的 470 亿美元估值使其成为最有价值的 AI 初创公司之一，超过了该行业的许多成熟企业。

rss · TLDR AI · 9月2日 00:00

**背景**: Anthropic 是一家以 AI 安全闻名的公司，开发了 Claude，这是一个专注于有用、诚实和无害的大型语言模型。World Labs 专门为空间智能创建世界模型，其先前产品包括 Marble 和 World API。Cognition AI 凭借 Devin 而成为引人注目的参与者，Devin 是一个可以自主完成工程任务的 AI 软件开发者。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/claude-fable-and-mythos-5-1">Introducing Claude Fable 5.1 and Claude Mythos 5.1 ...</a></li>
<li><a href="https://www.worldlabs.ai/blog/atlas">Atlas : A World Model for Spatial Intelligence | World Labs</a></li>
<li><a href="https://www.bloomberg.com/news/articles/2026-09-02/ai-startup-cognition-set-to-raise-around-1-billion-at-a-47-billion-value">AI Startup Cognition Set to Raise Around $1 Billion at a $ 47 Billion...</a></li>

</ul>
</details>

**标签**: `#AI funding`, `#AI tools`, `#model updates`, `#industry news`

---

<a id="item-6"></a>
## [蚂蚁 OmniTable 系统获 VLDB 2026 最佳论文](https://www.qbitai.com/2026/09/483104.html) ⭐️ 8.0/10

蚂蚁集团的 OmniTable 系统在 VLDB 2026 上获得工业赛道最佳论文奖，该系统采用统一宽表架构，能够处理 35PB 的大模型数据，效率提升 5.6 倍。 这一突破之所以重要，是因为它解决了 AI 开发中的一个关键瓶颈 - PB 级规模的数据预处理。5.6 倍的效率提升可以显著减少准备大语言模型训练数据所需的时间和资源。 OmniTable 是一种基于哈希的数据结构，即使在极端负载下也能为插入、查找、删除和遍历提供一致的 O(1)复杂度。它通过统一宽表架构处理分散在数百个物理表中的 PB 级非结构化语料。

rss · 量子位 · 9月2日 06:20

**背景**: VLDB（超大型数据库）是数据库管理和信息系统研究领域最负盛名的国际会议之一。大语言模型需要海量数据进行训练，而预处理这些数据是一个重大挑战，因为其规模和复杂性都很高。传统数据库方法通常难以处理现代 AI 系统所需的 PB 级数据量。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://zglg.work/en/ai/news/2026-09-02-ant-group-s-omnitable-wins-vldb-2026-industrial-best-paper-handling-35pb-of-l">Ant Group's OmniTable wins VLDB 2026 industrial best paper ...</a></li>
<li><a href="https://www.vldb.org/pvldb/vol19/p4276-fu.pdf">OmniTable: A Unified Wide-Table System for Petabyte-Scale LLM ...</a></li>
<li><a href="https://github.com/supersaga1/OmniTable/blob/main/README.md">OmniTable/README.md at main · supersaga1/OmniTable · GitHub</a></li>

</ul>
</details>

**标签**: `#AI infrastructure`, `#data processing`, `#large language models`, `#database systems`, `#Ant Group`

---

<a id="item-7"></a>
## [阿里更新 Qwen3.8-Max，前端编程能力全球第一](https://www.qbitai.com/2026/09/483101.html) ⭐️ 8.0/10

阿里巴巴已更新其旗舰 Qwen3.8-Max AI 模型，据称根据基准测试，其前端编程能力现已排名全球第一。 这一重大升级将阿里的 AI 模型定位为编码辅助领域的领导者，特别是在前端开发方面，这可能影响开发者创建 Web 应用的方式，并可能缩短开发时间。 Qwen3.8-Max 是一个多模态推理模型，于 2026 年 8 月 3 日发布，专为复杂推理、视觉理解、编码和智能体工作流程而设计，其推理成本显著低于竞争性的商业 AI 系统。

rss · 量子位 · 9月2日 06:10

**背景**: Qwen 是阿里巴巴的一系列大型语言模型，一直在不断发展以与其他主要 AI 系统竞争。前端编程涉及使用 HTML、CSS 和 JavaScript 等技术创建网站和 Web 应用程序的用户界面和用户体验。AI 模型越来越多地被评估其协助编码任务的能力，并有专门的基准测试来衡量不同编程领域的性能。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://openrouter.ai/qwen/qwen3.8-max">Qwen 3 . 8 Max - API Pricing & Benchmarks | OpenRouter</a></li>
<li><a href="https://news.google.com/stories/CAAqNggKIjBDQklTSGpvSmMzUnZjbmt0TXpZd1NoRUtEd2pHMTl6YUVSRTBhY2lFRVJGU2tDZ0FQAQ?hl=en-IN&gl=IN&ceid=IN:en">Alibaba unveils 2.4-trillion-parameter Qwen 3 . 8 - Max AI model - Overview</a></li>
<li><a href="https://medium.com/data-science-in-your-pocket/qwen-3-8-max-vs-kimi-k3-e55d61b32a9c">Qwen 3 . 8 Max vs Kimi K3. How to use Qwen 3 . 8 Max ? | Medium</a></li>

</ul>
</details>

**标签**: `#AI models`, `#coding tools`, `#frontend development`, `#Alibaba AI`, `#Qwen`

---

<a id="item-8"></a>
## [李飞飞发布全球首个多模态世界模型](https://www.qbitai.com/2026/09/482586.html) ⭐️ 8.0/10

李飞飞发布了一个据称是全球首个多模态世界模型，能够从单张图像补全 3D 世界，并为机器人创建训练环境。 这一突破代表了 AI 理解和生成 3D 环境能力的重大进步，通过提供逼真的模拟功能，可能加速机器人开发和沉浸式 3D 内容创建。 该模型可以将单张图像转换为完整的 3D 世界，并为机器人生成训练环境，解决了为机器人学习和发展创建逼真模拟空间的挑战。

rss · 量子位 · 9月2日 01:07

**背景**: 多模态世界模型是能够处理和生成不同类型数据（如文本、图像和视频）的 AI 系统。这些模型旨在创建物理世界的全面表示，可用于机器人训练、3D 内容生成和模拟环境等各种应用。该领域的最新发展包括 Marble、HY-World 2.0 和 Puffin-World 等方法，它们探索了从各种输入模态重建和生成 3D 世界的不同方法。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.worldlabs.ai/blog/marble-world-model">Marble: A Multimodal World Model | World Labs</a></li>
<li><a href="https://arxiv.org/abs/2407.00118">[2407.00118] From Efficient Multimodal Models to World Models ... From Efficient Multimodal Models to World Models: A Survey HY-World 2.0: A Multi-Modal World Model for Reconstructing ... A Multimodal World · Hugging Face Puffin-World: Scaling a Unified Multimodal Model with Native ... Top 15 Multimodal Models in 2026 (Open Source & Proprietary)</a></li>
<li><a href="https://arxiv.org/abs/2503.16611">[2503.16611] A Recipe for Generating 3D Worlds From a Single Image</a></li>

</ul>
</details>

**标签**: `#multimodal AI`, `#world models`, `#3D generation`, `#robotics`, `#Fei-Fei Li`

---

<a id="item-9"></a>
## [GLM 5.3 Flash 创造黑洞 Minecraft 模组](https://www.reddit.com/r/LocalLLaMA/comments/1w5gk2b/glm_53_flash_makes_a_black_hole_minecraft_mod/) ⭐️ 8.0/10

开发者成功使用 GLM 5.3 Flash 通过迭代改进创建了一个黑洞步枪 Minecraft 模组，在 9 小时的开发过程中生成了 760 万个 token。 这展示了本地大语言模型在游戏开发创意编码中的实际应用，表明 AI 如何能够协助开发者完成复杂的模组创建任务，而无需依赖云服务。 该模型在租用的 4x RTX PRO 6000 工作站上以 Q4 量化运行，平均解码速度约为 96 token/秒，并使用了 Minecraft 模组的 Fabric API。

reddit · r/LocalLLaMA · /u/Top-Eye-8104 · 9月2日 17:13

**背景**: GLM 5.3 Flash 是由 Z.ai 开发的语言模型，与前版本相比具有更低的延迟和更高的吞吐量。Q4 量化是一种减少模型权重精度的技术，可在保持合理性能的同时减少内存使用。Fabric API 是一个轻量级、模块化的库，为 Minecraft 模组开发提供通用钩子和兼容性措施。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/zai-org/GLM-5.3-Flash">zai-org/ GLM - 5 . 3 - Flash · Hugging Face</a></li>
<li><a href="https://deepintellica.com/ai-work/glm-5-3-flash/">GLM - 5 . 3 - Flash - Deep Intellica</a></li>
<li><a href="https://fabricmc.net/">Fabric | The home of the Fabric mod development toolchain.</a></li>

</ul>
</details>

**社区讨论**: Reddit 帖子显示了社区对游戏开发中 AI 实际应用的兴趣，包括关于硬件要求、实现细节以及与其他模型比较的问题。开发者鼓励在评论中分享其他本地模型模组实验。

**标签**: `#AI-assisted development`, `#Game modding`, `#Local LLMs`, `#Code generation`, `#Practical AI applications`

---

<a id="item-10"></a>
## [Meta 发布 Muse Spark 1.3](https://developer.meta.com/ai/models/muse-spark/) ⭐️ 7.0/10

Meta 发布了 Muse Spark 1.3，这是他们 AI 模型的更新版本，具有改进的功能和对开发者更实惠的定价。新版本增强了多模态推理能力，改进了上下文跟踪，并在编码任务上表现更好。 Muse Spark 1.3 代表了 Meta 在 AI 开发领域的持续投入，为开发者提供了强大且实惠的工具来构建应用程序。其具有竞争力的定价和多模态能力使其成为开发者寻求将 AI 集成到工作流程中的理想选择，而无需超出预算。 Muse Spark 1.3 的定价为每百万输入 token 1.25 美元，每百万输出 token 4.25 美元，上下文窗口为 1,048,576 个 token。该模型在人工智能分析智能指数上得分为 62，在同类模型中远高于平均水平，专为长期代理和编码工作流程而设计。

hackernews · bvaldivielso · 9月2日 19:35 · [社区讨论](https://news.ycombinator.com/item?id=49541256)

**背景**: Muse Spark 是由 Meta 通过其 Meta Superintelligence Labs (MSL)开发的大型语言模型(LLM)。它最初于 2026 年 4 月推出，并于 2026 年 7 月 9 日以 Muse Spark 1.1 版本发布。Muse Spark 专为多模态推理、编码和 AI 辅助软件开发而设计，代表了 Meta 在 AI 开发'扩展阶梯'上的第一步。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://developer.meta.com/ai/models/muse-spark/">Muse Spark 1.3 | Meta</a></li>
<li><a href="https://commandcode.ai/models/muse-spark-1-3">Muse Spark 1 . 3 — pricing, benchmarks & speed - Command Code</a></li>

</ul>
</details>

**社区讨论**: 社区反应不一，一些用户称赞该模型在开发工作中的性能和成本效益，而其他人则对 Meta 的数据实践和领导层表示伦理担忧。技术用户分享了该模型能力的积极体验及其遵循指令而不越界的能力，尽管一些人仍然警惕潜在的监控成本。

**标签**: `#AI models`, `#Meta AI`, `#Muse Spark`, `#AI development`, `#AI ethics`

---

<a id="item-11"></a>
## [Qwen 的 AI 霸主潜力](https://www.reddit.com/r/LocalLLaMA/comments/1w53ti8/qwen_will_be_the_king/) ⭐️ 7.0/10

中国 AI 模型如 Qwen、DeepSeek 和 GLM 正在利用扩展推理和后训练技术，有望超越更大的模型，而 Qwen 4 尚未发布。 这一发展标志着竞争 AI 格局的重大转变，即具有先进技术的小型模型可能超越更大参数的模型，可能使高性能 AI 民主化。 该帖子强调这些模型使用更高的令牌数量，并推测'engrams'——一种新方法，可以帮助未来的模型在特定任务上匹配或超过 2.4T 参数的模型。

reddit · r/LocalLLaMA · /u/LegacyRemaster · 9月2日 07:53

**背景**: AI 中的扩展推理指的是能够为每个问题分配更多计算资源的模型，可以进行超越简单模式匹配的多步问题解决。后训练是预训练模型在专门数据集上进一步训练以学习特定行为（如遵循指令）的阶段。Engram 是一种使用 N 嵌入表的新方法，通过将记忆卸载到 O(1)查找来重塑小型模型的推理方式。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://medium.com/@jelkhoury880/advancing-ai-reasoning-a-comprehensive-report-4982b7c19bdc">Advancing AI Reasoning: An Intro From StaR to DeepSeek | by Joe El Khoury | Medium</a></li>
<li><a href="https://pytorch.org/blog/a-primer-on-llm-post-training/">A Primer on LLM Post-Training – PyTorch</a></li>
<li><a href="https://www.banandre.com/blog/engrams-vs-transformers-efficient-inference-paradigm">Engrams Won’t Let You Run 1T Models Locally, But... - Banandre</a></li>

</ul>
</details>

**社区讨论**: 该 Reddit 帖子由/u/LegacyRemaster 提交，但内容中未提供具体的社区评论。

**标签**: `#AI models`, `#Qwen`, `#DeepSeek`, `#GLM`, `#Model performance`

---

<a id="item-12"></a>
## [Q8 N-gram 集成保持 Qwen 速度](https://www.reddit.com/r/LocalLLaMA/comments/1w5isz3/confirmed_bolting_q8_ngram_into_iq4_qwen_no_speed/) ⭐️ 7.0/10

一位用户成功将 Qwen 3.8 Next 中的 510 亿 N-gram 层替换为更高精度的 Q8 权重，且没有显著的速度下降。修改后模型的 state_dict 从 90GB 增长到 115GB。 这表明可以在不牺牲性能的情况下修改模型特定组件的精度，为优化大型语言模型提供了见解。这种方法可能适用于其他模型和量化技术。 由于存储限制，用户将 IQ4_XS Qwen 模型的 N-gram 部分替换为 Q8 权重而非 BF16。推理速度测量显示原始版本和修改版本之间的差异很小，两者都稳定在约 10.1 个 token 每秒。

reddit · r/LocalLLaMA · /u/Altruistic_Heat_9531 · 9月2日 18:32

**背景**: N-gram 层是语言模型中的组件，基于前面的词预测下一个词。量化降低模型权重的精度以减少内存使用并可能提高推理速度。Qwen 是由阿里云开发的大型语言模型系列，Qwen 3.8 是其最新版本之一。Q8 量化使用每权重 8 位，而 BF16 使用 16 位，在精度和性能之间提供不同的权衡。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/pdf/2401.12973">In-Context Language Learning: Architectures and Algorithms</a></li>
<li><a href="https://ai-muninn.com/en/blog/llm-101-what-is-quantization">[LLM 101 #4] What Is Quantization? Q4, Q8, FP16 Explained — ai-muninn</a></li>
<li><a href="https://en.wikipedia.org/wiki/Qwen">Qwen - Wikipedia</a></li>

</ul>
</details>

**社区讨论**: 帖子提到用户忘记包含拼接 N-gram 层的代码，稍后会上传。原始帖子中没有可见的评论，无法评估社区情绪或额外见解。

**标签**: `#model optimization`, `#quantization`, `#Qwen`, `#N-gram`, `#performance tuning`

---

<a id="item-13"></a>
## [MLX 与 llama.cpp 在苹果 M5 上的性能对比](https://www.reddit.com/r/LocalLLaMA/comments/1w5kau3/mac_heads_is_there_any_point_to_mlx_in_september/) ⭐️ 7.0/10

性能测试显示，在苹果 M5 芯片上，llama.cpp 与 Metal 现在匹配或超过了 MLX 的预填充性能，Qwen3.8 27b 模型达到约 300-350t/s 的预填充速度和约 19t/s 的生成速度。 这一对比对运行大型语言模型的苹果硅用户具有重要意义，因为它表明 MLX 和 llama.cpp 之间的性能差距已经缩小，可能简化部署选择，减少根据工作负载在框架间切换的需要。 测试特别针对 M5 Pro 上的 Q8/8 位量化的 Qwen3.8 27b 模型，显示 llama.cpp 的 Metal 实现现在支持 M5 矩阵运算/'神经加速器'，这之前使 MLX 在预填充性能方面具有优势。

reddit · r/LocalLLaMA · /u/MrPecunius · 9月2日 19:23

**背景**: MLX 是苹果为苹果硅设计的开源机器学习框架，于 2023 年 12 月发布，旨在提供类似 NumPy API 的高效数组运算。llama.cpp 是用于 LLM 推理的 C/C++实现，支持包括 GGUF 在内的多种模型格式，GGUF 是广泛用于存储量化模型的格式。这些框架之间的性能对比一直是运行大型语言模型的苹果硅用户感兴趣的话题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://grokipedia.com/page/MLX_machine_learning_framework">MLX ( machine learning framework ) — Grokipedia</a></li>
<li><a href="https://ml-explore.github.io/mlx/build/html/index.html">MLX — MLX 0.32.2 documentation</a></li>
<li><a href="https://github.com/ggml-org/llama.cpp">GitHub - ggml-org/llama.cpp: LLM inference in C/C++</a></li>

</ul>
</details>

**社区讨论**: 该帖子寻求对作者观察结果的验证，并询问他们是否遗漏了某些内容，或者是否有改进 MLX 性能的方法。作者特别质疑主流 MLX MTP（多进程令牌处理）是否正常工作，或者性能差异是否特定于 Qwen3.8 27b 模型。

**标签**: `#Apple Silicon`, `#MLX`, `#llama.cpp`, `#AI deployment`, `#performance optimization`

---

<a id="item-14"></a>
## [Perplexity 开源 Qwen 3.6 Mac 推理服务器](https://www.reddit.com/r/LocalLLaMA/comments/1w5ozl4/perplexity_opensourced_their_mac_inference_server/) ⭐️ 7.0/10

Perplexity 已经开源了他们为 Qwen 3.6 定制的推理服务器，专门针对苹果硅硬件进行了优化，以提供最佳性能。 这种专门的优化可以显著提升在苹果设备上使用 Qwen 3.6 的开发者和研究人员的工作效率，解决了在消费级硬件上高效 AI 推理的日益增长的需求。 该推理服务器是 Perplexity 的 pplx-garden 仓库的一部分，专门为 Qwen 3.6 优化，以在苹果硅上最大化性能，而不是通用解决方案。

reddit · r/LocalLLaMA · /u/Specter_Origin · 9月2日 22:13

**背景**: 推理服务器是专门设计用于高效运行已训练 AI 模型的系统，专注于低延迟而非训练。苹果硅凭借其统一内存架构和神经网络引擎，为 AI 工作负载提供了与传统 CPU 相比的独特优化机会。Qwen 3.6 是由阿里巴巴开发的语言模型，有不同的变体，包括 35B 稀疏专家混合(MoE)模型和 27B 密集模型，两者都旨在增强代理编码和思维保留能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.servnetuk.com/learn/inference-server-explained">Inference Server Explained: Training vs Inference 2026 | Servnet UK</a></li>
<li><a href="https://deepwiki.com/QwenLM/Qwen3.6/1.1-qwen3.6-models">Qwen3.6 Models | QwenLM/Qwen3.6 | DeepWiki</a></li>
<li><a href="https://blog.starmorph.com/blog/apple-silicon-llm-inference-optimization-guide">Apple Silicon LLM Inference Optimization: The Complete Guide ...</a></li>

</ul>
</details>

**社区讨论**: Reddit 讨论包含了实质性技术评论，比较了不同的苹果硅推理优化方法并讨论了性能影响，尽管新闻摘要中没有提供具体的评论内容。

**标签**: `#Apple Silicon`, `#Qwen`, `#Inference Optimization`, `#Open Source`, `#Mac AI`

---