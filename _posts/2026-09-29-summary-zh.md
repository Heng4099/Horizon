---
layout: default
title: "Horizon Summary: 2026-09-29 (ZH)"
date: 2026-09-29
lang: zh
---

> 从 42 条内容中筛选出 13 条重要资讯。

---

1. [Holo4 赋能通用计算机使用智能体](#item-1) ⭐️ 8.0/10
2. [Anthropic 发布 Claude Sonnet 5.5](#item-2) ⭐️ 8.0/10
3. [NVIDIA 推出 OpenShell AI 安全沙箱](#item-3) ⭐️ 8.0/10
4. [Swift 1.5 + HyperQwen 性能提升](#item-4) ⭐️ 8.0/10
5. [通义千问 3.8 作为子代理表现出色](#item-5) ⭐️ 8.0/10
6. [Jeff：小型快速 Jev 兼容决策模型](#item-6) ⭐️ 7.0/10
7. [MicroLLM 实验室：浏览器 AI 测试](#item-7) ⭐️ 7.0/10
8. [AMD 以 80 亿美元收购 World Labs](#item-8) ⭐️ 7.0/10
9. [呼吁调查 AI 实验室](#item-9) ⭐️ 7.0/10
10. [Scrimba 推出 HN.watch 视频平台](#item-10) ⭐️ 7.0/10
11. [AI 能力跃升带来安全挑战](#item-11) ⭐️ 7.0/10
12. [ToMoE v2 实现近乎无损密集模型转 MoE](#item-12) ⭐️ 7.0/10
13. [调试 x8/x8 分频器上的 PCIe 链路重训练与双 RTX 3090](#item-13) ⭐️ 7.0/10

---

<a id="item-1"></a>
## [Holo4 赋能通用计算机使用智能体](https://huggingface.co/blog/Hcompany/holo4) ⭐️ 8.0/10

Holo4 是 2026 年 9 月 28 日发布的新型智能体 AI 系统，能够使用相同的权重在图形界面、原始代码、机器可验证协议和传统 API 上运行。 Holo4 代表了通用计算机使用智能体的重要进步，使 AI 能够以更复杂的方式与计算机交互，为各行各业的 AI 自动化和生产力工具提供直接应用。 Holo4 提供 27B 密集型和 35B-A3B 混合专家模型两种规格，在 Hugging Face 上开放权重并提供 API，在 Agentic Task Factory 的环境和任务上训练，擅长专业软件操作。

rss · Hugging Face Blog · 9月28日 09:44

**背景**: 通用计算机使用 AI 代表了人工智能的重要前沿，有望改变各行各业的生产力、工作流程、自动化和决策方式。这些系统将最先进的智能体 AI 技术与系统化的评估、分析和改进方法相结合。人机交互已从社会心理学中的理论概念发展为促进人与计算机之间通信的实际技术接口。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://huggingface.co/blog/Hcompany/holo4">Holo4: powering generalist computer-use agents - Hugging Face</a></li>
<li><a href="https://www.globai.org/blog/holo4-models-bring-versatile-ai-agents-to-everyday-workflows">Holo4 models bring versatile AI agents to everyday workflows</a></li>
<li><a href="https://www.unite.ai/h-company-releases-holo4-open-weight-models-for-computer-use-agents/">H Company Releases Holo4, Open-Weight Models for ... - Unite.AI</a></li>
<li><a href="https://arxiv.org/html/2503.01861v1">Towards Enterprise-Ready Computer Using Generalist Agent</a></li>
<li><a href="https://en.wikipedia.org/wiki/Human–AI_interaction">Human–AI interaction - Wikipedia</a></li>

</ul>
</details>

**标签**: `#AI agents`, `#computer automation`, `#Holo4`, `#productivity tools`, `#human-computer interaction`

---

<a id="item-2"></a>
## [Anthropic 发布 Claude Sonnet 5.5](https://simonwillison.net/2026/Sep/28/claude-sonnet-5-5/) ⭐️ 8.0/10

Anthropic 发布了 Claude Sonnet 5.5，它比前代产品运行速度快 30%以上，成本降低高达 30%，同时保持相同的价格结构。 此次更新使 Claude 的免费版比 OpenAI 的 ChatGPT 免费版（目前使用 Luna 5.6）更强大，可能使 Anthropic 在 AI 市场获得竞争优势。 Sonnet 5.5 拥有 100 万 token 的上下文窗口，定价为每 Mtoken 2 美元/10 美元，缓存读取为每 Mtoken 0.20 美元，但与 Opus 5.5 存在相同的"最大"思考努力 bug，可能导致过度消耗 token。

rss · Simon Willison · 9月28日 22:07

**背景**: Claude Sonnet 是 Anthropic 的 AI 语言模型之一，定位为更强大的 Opus 和更快的 Haiku 模型之间的中级选项。Token 是 AI 模型处理的基本文本单位，1 个 token 约等于 4 个英文字符。"努力"参数允许用户控制模型在生成响应前投入多少计算资源来思考问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.anthropic.com/claude-sonnet-5-5">Introducing Claude Sonnet 5.5 \ Anthropic</a></li>
<li><a href="https://www.grube.ai/thinking-in-llms">Thinking in LLMs | grube. ai</a></li>
<li><a href="https://blogs.nvidia.com/blog/ai-tokens-explained/">What Are AI Tokens? The Language and Currency Powering Modern AI</a></li>

</ul>
</details>

**标签**: `#AI models`, `#Claude`, `#Anthropic`, `#Performance improvements`, `#AI tools`

---

<a id="item-3"></a>
## [NVIDIA 推出 OpenShell AI 安全沙箱](https://www.reddit.com/r/LocalLLaMA/comments/1ws9ydg/nvidia_shipped_openshell_an_open_source_sandbox/) ⭐️ 8.0/10

NVIDIA 发布了 OpenShell，一个开源沙箱，为自主 AI 代理提供运行时限制，而不是依赖提示规则。已有 100 多家公司加入了安全堆栈计划，而 OpenAI 没有参与。 这代表了 AI 安全方法从基于提示的限制转向运行时限制的重大转变，可能为防止有害 AI 行为提供更强大的保护。超过 100 家公司的广泛采用表明，随着自主代理变得越来越普遍，业界认识到需要更复杂的 AI 安全措施。 OpenShell 提供内核级隔离，并使用声明性 YAML 策略来执行安全控制，为每个代理和子代理创建独立的沙箱。沙箱包括资源核算，具有 CPU/时间限制、内存限制和网络隔离，以防止进程失控并确保代理在定义的边界内运行。

reddit · r/LocalLLaMA · /u/InternationalGap3698 · 9月28日 09:27

**背景**: AI 安全传统上依赖于提示规则和限制来防止有害输出。然而，随着 AI 代理变得更加自主并能够修改自己的环境，这些方法已变得不足。像 OpenShell 这样的运行时沙箱代表了更全面的安全方法，它隔离代理并执行资源限制，解决无限循环、过度资源消耗和未授权系统访问等潜在问题。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://grokipedia.com/page/NVIDIA_OpenShell">NVIDIA OpenShell</a></li>
<li><a href="https://github.com/NVIDIA/openshell">GitHub - NVIDIA/OpenShell: OpenShell is the safe, private runtime for autonomous AI agents. · GitHub</a></li>
<li><a href="https://build.nvidia.com/openshell">NVIDIA OpenShell</a></li>

</ul>
</details>

**社区讨论**: Reddit 帖子显示社区对 NVIDIA AI 安全方法的兴趣，特别关注 OpenAI 没有加入这一倡议的事实。一些评论者推测 OpenAI 缺席的潜在竞争原因，而其他人讨论了运行时限制与基于提示的限制的技术优势。

**标签**: `#AI Safety`, `#NVIDIA`, `#Open Source`, `#AI Governance`, `#Agent Safety`

---

<a id="item-4"></a>
## [Swift 1.5 + HyperQwen 性能提升](https://www.reddit.com/r/LocalLLaMA/comments/1wsqjku/swift_15_hyperqwen_37_less_task_completion_time/) ⭐️ 8.0/10

Swift 1.5 结合 HyperQwen 量化技术在 RTX 3090 GPU 上实现了 37% 更快的任务完成时间，同时保持相似的输出质量，比原始模型生成更少的 token。 这一优化对于在消费级硬件上部署大型语言模型的 AI 从业者具有重要意义，它展示了如何将模型微调与量化技术结合，可以在不牺牲质量的情况下显著提高性能。 基准测试结果显示，Swift 1.5 + HyperQwen INT4 头部模型比基线 HyperQwen 模型快 37% 完成任务，同时生成更少的 token，并在 GSM8K、IFBench、LiveCodeBench 和自定义工具调用评估等多个基准测试中保持相当的准确性。

reddit · r/LocalLLaMA · /u/KingGongzilla · 9月28日 20:52

**背景**: Swift 是一种模型优化技术，可在推理过程中减少生成的 token 数量，同时保持性能。HyperQwen 是一种量化方法，专门设计用于在 RTX 3090 等消费级 GPU 上高效运行大型 Qwen 模型。这种组合利用了 Swift 的 token 效率和 HyperQwen 的高吞吐能力。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/modelscope/ms-swift">GitHub - modelscope/ms-swift: Use PEFT or Full-parameter to ...</a></li>
<li><a href="https://github.com/syv-ai/HyperQwen">GitHub - syv-ai/ HyperQwen : Serve large Qwen models fast on the...</a></li>
<li><a href="https://github.com/vishvaRam/AutoRound-Quantaization">GitHub - vishvaRam/AutoRound-Quantaization: Comprehensive ...</a></li>

</ul>
</details>

**社区讨论**: 该帖子发布在 LocalLLaMA 子版块，但内容中未提供具体的社区评论。

**标签**: `#model-optimization`, `#quantization`, `#performance-benchmark`, `#gpu-optimization`, `#llm-deployment`

---

<a id="item-5"></a>
## [通义千问 3.8 作为子代理表现出色](https://www.reddit.com/r/LocalLLaMA/comments/1wso6gn/qwen_38_is_a_workhorse/) ⭐️ 8.0/10

一位 Reddit 用户展示了如何使用通义千问 3.8 27B 作为子代理，配合 DeepSeek v4.1 Flash 作为编排器在 llama.cpp 中运行，展示了这种多代理系统的实际应用。 这一实现很重要，因为它展示了结合多个 AI 模型以增强性能的实用方法，可能实现更高效的本地 AI 工作流程和专业化任务分配。 该设置使用通义千问 3.8 27B 配合 GSQ RCO（分组量化与递归上下文优化）在 llama.cpp 中运行，由 DeepSeek v4.1 Flash 编排，表明在性能和资源效率之间取得了平衡。

reddit · r/LocalLLaMA · /u/lordekeen · 9月28日 19:24

**背景**: 子代理是处理特定任务的专门 AI 助手，比单一单体模型能实现更高效的处理。llama.cpp 是一个开源库，能够在本地运行大型语言模型，设置简单且性能先进。DeepSeek 提供编排功能，可以协调多个 AI 代理共同处理复杂任务。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.linkedin.com/pulse/stop-stuffing-your-ai-context-window-start-using-subagents-anand-dxb2f">Stop Stuffing Your AI Context Window. Start Using Subagents .</a></li>
<li><a href="https://llama.app/docs/introduction">Introduction - llama.app - Official home for llama.cpp</a></li>
<li><a href="https://www.mindstudio.ai/blog/deepseek-harness-agentic-coding">What Is DeepSeek Harness? The Plug-In Coding Agent Explained | MindStudio</a></li>

</ul>
</details>

**社区讨论**: Reddit 评论区包含关于模型性能和实现细节的实质性技术讨论，但新闻摘要中未提供具体评论内容。

**标签**: `#Qwen`, `#LLM`, `#open-source`, `#implementation`, `#subagent`

---

<a id="item-6"></a>
## [Jeff：小型快速 Jev 兼容决策模型](https://github.com/firelex/jeff) ⭐️ 7.0/10

Jeff 是一个新的 0.8B 参数决策模型，与 Jev 兼容，在个人硬件上训练，响应时间约为 30 毫秒，使其适合边缘 AI 应用。 Jeff 之所以重要，是因为它提供了一个轻量级、快速的决策模型替代方案，可能减少企业的计算需求和成本，同时使资源受限的边缘设备能够运行 AI 应用。 Jeff 的响应时间约为 30 毫秒，拥有 0.8B 参数，与 Jev 兼容，并且在个人硬件上训练，而非昂贵的基础设施，使其对个人开发者和小型组织来说易于访问。

hackernews · firelex · 9月28日 20:23 · [社区讨论](https://news.ycombinator.com/item?id=49883844)

**背景**: Jev 是一个托管的 System One 模型，专注于校准的、类型化的决策。AI 中的决策模型是帮助组织数据以基于事实做出有意义决策的模板。边缘 AI 是指在物理世界中的设备上部署 AI 应用，在网络边缘靠近用户的位置执行计算，而不是在集中式云服务器中。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://jevbest.com/projects/jev-like-models/">Awesome Jev -like models Jev Projects | bestjev</a></li>
<li><a href="https://www.jev-tutorial.org/models">System One Model Directory · Jev Tutorial</a></li>
<li><a href="https://blogs.nvidia.com/blog/what-is-edge-ai/">What Is Edge AI and How Does It Work? | NVIDIA Blog</a></li>

</ul>
</details>

**社区讨论**: 社区评论反应不一——一些人质疑何时会将类似 Jev 的功能构建到前沿模型中，而其他人报告了准确性问题（与 Jev 相比为 70%对 94%）。还有人讨论了商业 LLM 使用中涉及分类的比例，以及这可能如何影响企业 AI 支出和数据中心使用。

**标签**: `#efficient-ai`, `#decision-models`, `#edge-ai`, `#model-optimization`, `#practical-ai`

---

<a id="item-7"></a>
## [MicroLLM 实验室：浏览器 AI 测试](https://stateofutopia.com/experiments/microllmlab/) ⭐️ 7.0/10

MicroLLM 实验室是一个网络应用程序，允许用户直接在浏览器中测试 7 种不同的小型语言模型，无需强大的硬件或云服务。 这展示了可直接在浏览器中运行的实用 AI 应用程序的实现，降低了延迟，保护了隐私，并支持离线环境中的 AI 应用。 该应用程序包含 7 种不同的小型语言模型，但用户反馈显示 UI 存在问题，文本太小且信息过于密集。一位用户还展示了模型对简单算术问题的错误回答。

hackernews · logicallee · 9月28日 18:58 · [社区讨论](https://news.ycombinator.com/item?id=49882781)

**背景**: 大型语言模型（LLM）是在大量文本上训练的 AI 模型，用于自然语言处理任务。小型语言模型（SLM）通常具有不到四百亿个参数，使其可以在消费电子设备上运行。设备端模型直接在用户设备上运行，而不是在云端，提供降低延迟、数据本地化和个性化用户体验等优势。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Small_language_model">Small language model</a></li>
<li><a href="https://arxiv.org/abs/2409.00088">On-Device Language Models: A Comprehensive Review On-Device LLMs: State of the Union, 2026 – Vikas Chandra ... Models on-device | Ai2 What Is On-Device AI? A Complete Guide for 2026 Introducing Apple’s On-Device and Server Foundation Models Edge AI: Running AI Models On-Device in 2026 — Hardware ...</a></li>
<li><a href="https://github.com/sps014/MicroLLM">GitHub - sps014/MicroLLM: A ~40 million Parameter LLM trained ...</a></li>

</ul>
</details>

**社区讨论**: 社区反馈强调了 UI 设计问题，文本太小且信息密度过高。还有关于模型性能的讨论，一位用户展示了简单算术问题的错误答案。此外，还提到了一个名为 Web Models API 的相关提案，用于浏览器标准的设备端模型运行。

**标签**: `#LLM`, `#browser-based AI`, `#on-device models`, `#web applications`, `#AI tools`

---

<a id="item-8"></a>
## [AMD 以 80 亿美元收购 World Labs](https://www.worldlabs.ai/blog/amd-announcement) ⭐️ 7.0/10

AMD 以 reportedly 80 亿美元的价格收购了成立仅 2 年的 AI 公司 World Labs，这标志着对 AI 推理基础设施的重大投资。 这次收购表明，大型科技公司愿意为专业 AI 初创公司支付溢价，突显了在 AMD 与 NVIDIA 竞争的 AI 芯片市场中，推理基础设施的战略重要性。 对一家仅成立 2 年的公司给予 80 亿美元的估值，表明其要么拥有极具价值的技术，要么对 AMD 的 AI 雄心（尤其是在推理领域）具有重大战略意义，因为专用硬件可以提供竞争优势。

hackernews · mfiguiere · 9月28日 20:18 · [社区讨论](https://news.ycombinator.com/item?id=49883760)

**背景**: AI 推理是使用训练好的 AI 模型根据新输入数据做出预测或决策的过程，这与训练阶段不同。推理基础设施指的是在生产环境中高效运行 AI 模型所需的硬件和软件系统，AMD 和 NVIDIA 等公司的专用芯片在优化性能和成本方面发挥着关键作用。随着 AI 应用从研究实验室转向实际部署，推理市场正在快速增长。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://gcore.com/learning/what-is-ai-inference">What is AI inference and how does it work? | Gcore</a></li>
<li><a href="https://www.astuteanalytica.com/industry-report/ai-inference-infrastructure-market">AI Inference Infrastructure Market Size, Forecast [2035]</a></li>
<li><a href="https://www.mooglelabs.com/blog/scaling-ai-inference-infrastructure">AI Inference Infrastructure : Overcoming Enterprise</a></li>

</ul>
</details>

**社区讨论**: 社区成员对收购的速度和规模表示惊讶，质疑一家成立仅 2 年的公司是否真的值 80 亿美元。一些人推测 AMD 正在为超快速推理和具身 AI 做准备，而另一些人注意到芯片制造商越来越多地从事 AI 实验室传统工作的趋势。

**标签**: `#AI-acquisition`, `#AMD`, `#AI-inference`, `#AI-business`, `#startup-exit`

---

<a id="item-9"></a>
## [呼吁调查 AI 实验室](https://calnewport.com/its-time-to-investigate-the-ai-labs/) ⭐️ 7.0/10

文章呼吁调查 AI 实验室及其做法，社区成员讨论了监管方法、安全问题，并将多智能体 AI 系统与公司结构进行类比。 这很重要，因为随着能够自主运行的多智能体系统的进步，AI 治理和安全变得日益关键，需要适当的监督和监管来降低潜在风险。 评论强调了具体问题，包括智能体拥有计算机完全访问权限、需要隔离系统，以及建议禁止某些危险信息进入训练数据和递归自我改进功能。

hackernews · ibobev · 9月28日 19:53 · [社区讨论](https://news.ycombinator.com/item?id=49883471)

**背景**: 多智能体系统是由多个交互式智能体组成的计算系统，能够解决单个系统难以处理的问题。AI 治理涉及制定促进和监管 AI 系统的政策和法律，自 2016 年以来已发布了大量 AI 伦理指南。监管格局正在全球范围内形成，欧盟在 2024 年通过 AI 法案采用了共同的法律框架。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Multi-agent_system">Multi-agent system</a></li>
<li><a href="https://en.wikipedia.org/wiki/AI_governance">AI governance</a></li>
<li><a href="https://www.ibm.com/think/topics/ai-governance">What is AI governance? - IBM</a></li>

</ul>
</details>

**社区讨论**: 社区评论展现了多样化的观点，一些人主张对有问题的 AI 系统进行更具体的监管，而不是笼统地讨论 AI 能力。其他人将多智能体系统与公司结构进行类比，指出内部通信类似于公司电子邮件。安全问题备受关注，有人质疑为什么智能体不在没有互联网访问权限的隔离计算机上运行。

**标签**: `#AI governance`, `#AI security`, `#AI regulation`, `#multi-agent systems`, `#AI ethics`

---

<a id="item-10"></a>
## [Scrimba 推出 HN.watch 视频平台](https://hn.watch/) ⭐️ 7.0/10

Scrimba 创建了 HN.watch，一个使用其基于 HTML 的视频格式集成 LLM 技术，将 Hacker News 文章转换为解释性视频的平台，在用户点击链接时即时生成视频。 这项技术将视频创作的成本和时间从'美元和分钟'大幅降低到'美分和秒'，可能为寻求利用 AI 进行内容转换的内容创作者和企业开辟新的用例。 该平台只需几秒钟即可生成视频，每视频成本约 0.04 美元，使用基于开源 Imba 编程语言构建的自定义堆栈，模型包括 Gemini、GPTs、Inworld 和 ElevenLabs。

hackernews · mrborgen · 9月28日 15:16 · [社区讨论](https://news.ycombinator.com/item?id=49879401)

**背景**: 基于 HTML 的视频格式使用网络技术创建和显示视频内容，相比 MP4 或 WebM 等传统基于像素的格式，提供更快的渲染和更简单的编辑。相比之下，扩散模型是 AI 方法，通过将随机噪声逐步细化为连贯的视觉效果来生成视频，通常能产生更高质量，但需要更高的计算成本和时间。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/HTML_video">HTML video - Wikipedia</a></li>
<li><a href="https://github.com/showlab/Awesome-Video-Diffusion">GitHub - showlab/Awesome-Video-Diffusion: A curated list of ...</a></li>
<li><a href="https://www.kapwing.com/tools/video-enhancer">Video Quality Enhancer — Improve With AI For Free</a></li>

</ul>
</details>

**社区讨论**: 社区反应褒贬不一，一些人欣赏技术成就和低成本，而其他人则表示更喜欢文本而非视频。有人担心单调的 AI 语音会使视频变得无聊，也有人承认这个工具不适合所有人，但对那些更喜欢视频的人（尤其是年轻一代）来说很有价值。

**标签**: `#AI-content-creation`, `#video-generation`, `#LLM-applications`, `#content-transformation`, `#HackerNews`

---

<a id="item-11"></a>
## [AI 能力跃升带来安全挑战](https://simonwillison.net/2026/Sep/28/joedaroo/) ⭐️ 7.0/10

OpenAI 安全专家 joedaroo 警告，在网络安全、群体智能和信息板相关领域，AI 能力突然且意外的跃升正在为组织带来极其困难的安全挑战。 这些突然的 AI 能力跃升正在超越传统的安全开发生命周期，迫使组织重新评估其安全态势、文化准备和事件响应能力，以应对意外的 AI 进步。 安全专业人员不仅要开发加固的系统，还要培养文化韧性，确保组织内部的人员能够在 AI 能力突然超越当前安全措施时迅速适应。

rss · Simon Willison · 9月28日 19:11

**背景**: 群体智能指的是去中心化、自组织系统的集体行为，可以通过算法和机器人技术应用于 AI。AI 能力跃升描述了智能如何不是线性扩展而是突然跃进，经常比传统软件发布更快地改变运营风险状况。网络安全事件响应涉及检测和应对网络威胁的流程和技术，正式的计划有助于限制安全漏洞造成的损害。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Swarm_intelligence">Swarm intelligence - Wikipedia</a></li>
<li><a href="https://www.mindstudio.ai/blog/what-is-intelligence-staircase-ai-capability-jumps">What Is the Intelligence Staircase? How AI Capability Jumps ...</a></li>
<li><a href="https://www.ibm.com/think/topics/incident-response">What is incident response? - IBM</a></li>

</ul>
</details>

**标签**: `#AI security`, `#organizational preparedness`, `#AI capability jumps`, `#risk management`, `#AI safety`

---

<a id="item-12"></a>
## [ToMoE v2 实现近乎无损密集模型转 MoE](https://www.reddit.com/r/LocalLLaMA/comments/1wsmsnx/what_do_you_think_about_tomoe_v2_paper_converting/) ⭐️ 7.0/10

ToMoE v2 论文提出了一种新颖算法，通过动态结构剪枝将密集大语言模型转换为专家混合(MoE)架构，在保持计算效率的同时实现近乎无损的精度。 这种方法通过在不显著降低性能的情况下减少计算需求，解决了大语言模型的部署挑战，可能使 Qwen3.8-27B 等模型具备 MoE 架构，实现更高效的专门化模型。 ToMoE v2 使用可微分动态剪枝方法将密集 MLP 层转换为 MoE 架构，减轻性能损失并解决高计算成本问题，其性能优于最先进的结构剪枝方法，同时使用相似或更低的训练成本。

reddit · r/LocalLLaMA · /u/jinnyjuice · 9月28日 18:35

**背景**: 专家混合(MoE)是一种神经网络架构，动态选择不同的专门子网络(专家)来处理每个输入，提高效率和专业化程度。传统的剪枝方法通过永久移除参数来减少计算成本，但这不可避免地导致性能下降。ToMoE 方法通过将密集模型转换为 MoE 同时保持接近原始的性能，解决了大语言模型部署中的一个关键挑战。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://arxiv.org/abs/2501.15316">[2501.15316] ToMoE: Converting Dense Large Language Models to ... ToMoE v2: Near-Lossless Dense-to-MoE Conversion… · AGI Hunt GitHub - gaosh/ToMoE: [TMLR] Offical Implementation of ToMoE ... Paper page - ToMoE: Converting Dense Large Language Models to ... ToMoE: Converting Dense Large Language Models to Mixture-of ... ToMoE: Converting Dense Large Language Models to Mixture-of ...</a></li>
<li><a href="https://arxiv.org/html/2501.15316v2">ToMoE: Converting Dense Large Language Models to Mixture-of ...</a></li>
<li><a href="https://agihunt.info/en/p/1a0e957c1dc65bbf9a514a05be6">ToMoE v2: Near-Lossless Dense-to-MoE Conversion… · AGI Hunt</a></li>

</ul>
</details>

**社区讨论**: Reddit 帖子对将 ToMoE v2 应用于 Qwen3.8-27B-A16B 等模型表示热情，同时承认实现这种转换存在架构障碍和适当的训练数据需求。

**标签**: `#Mixture of Experts`, `#Model Architecture`, `#AI Efficiency`, `#ToMoE`, `#Model Conversion`

---

<a id="item-13"></a>
## [调试 x8/x8 分频器上的 PCIe 链路重训练与双 RTX 3090](https://www.reddit.com/r/LocalLLaMA/comments/1wsscrw/debugging_pcie_link_retraining_on_an_x8x8/) ⭐️ 7.0/10

创建了一份详细的技术指南，帮助用户诊断和解决在使用 x8/x8 分频器配置双 RTX 3090 显卡时的 PCIe 链路重训练问题。 这份故障排除指南对使用高端 GPU 设置的 AI 从业者和专业人员至关重要，因为 PCIe 链路重训练问题会显著影响 AI 工作负载中的多 GPU 性能和系统稳定性。 该指南解决了 PCIe 链路重训练的特定症状，提供了诊断方法，并为 RTX 3090 GPU 的 x8/x8 分频器配置提供解决方案，这些配置在 AI 和机器学习工作站中常用。

reddit · r/LocalLLaMA · /u/bolts98 · 9月28日 22:02

**背景**: PCIe（PCI Express）是一种高速串行计算机扩展标准，用于连接硬件设备。链路重训练是 PCIe 设备定期重新建立最佳通信参数以在更高数据速率下保持稳定连接的过程。x8/x8 分频器是一种硬件组件，允许单个 x16 PCIe 插槽分成两个 x8 插槽，使原本需要两个独立 x16 插槽的两张 GPU 能够使用。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://www.ti.com/lit/pdf/snla415">PCIe Link Training Overview - Texas Instruments</a></li>
<li><a href="https://vlsitrainers.com/pcie-link-training-and-ltssm/">PCIe LTSSM Explained — Link Training and All 11 States – Your ...</a></li>
<li><a href="https://adaptivesupport.amd.com/s/question/0D52E00006hpPWUSA2/pcie-link-starts-retraining-during-pcie-configurationenumeration?language=en_US">PCIe link starts retraining during PCIe Configuration/Enumeration</a></li>

</ul>
</details>

**社区讨论**: Reddit 讨论包括用户分享类似 PCIe 问题的经验，确认故障排除步骤的有效性，并询问有关特定配置的额外问题。

**标签**: `#PCIe`, `#GPU`, `#hardware`, `#troubleshooting`, `#RTX3090`

---