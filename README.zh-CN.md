# 🤖 Awesome AI Agents 🤖


**语言：** [English](README.md) | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md) | [Français](README.fr.md)

精选开源框架、工具与项目合集，涵盖 AI Agent 构建所需的一切资源。包括 Agent 编排、工具调用、多智能体协作、RAG、浏览器自动化、语音界面等——探索并构建智能体生态系统的完整指南。

## 目录

- [🤖 Awesome AI Agents 🤖](#-awesome-ai-agents-)
  - [目录](#目录)
  - [框架与 SDK](#框架与-sdk)
  - [大语言模型与模型工具](#大语言模型与模型工具)
  - [编程与开发 Agent](#编程与开发-agent)
  - [自动化与工作流](#自动化与工作流)
  - [研究与分析](#研究与分析)
  - [对话与个人助理 Agent](#对话与个人助理-agent)
  - [知识管理与 RAG](#知识管理与-rag)
  - [浏览器与 Web Agent](#浏览器与-web-agent)
  - [语音与多模态](#语音与多模态)
  - [测试与评估](#测试与评估)
  - [基础设施与安全](#基础设施与安全)
  - [游戏与模拟](#游戏与模拟)

## 框架与 SDK

构建 AI 智能体的通用框架与 SDK，按 GitHub Star 数量排序。

- [LangChain](https://github.com/hwchase17/langchain): 开发由语言模型驱动的应用程序的框架。![GitHub Repo stars](https://img.shields.io/github/stars/hwchase17/langchain?style=social)
- [Autogen](https://github.com/microsoft/autogen): 支持下一代大语言模型应用开发。 ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/autogen?style=social)
- [LlamaIndex](https://github.com/jerryjliu/llama_index): 为 LLM 提供与外部数据连接的核心接口。 ![GitHub Repo stars](https://img.shields.io/github/stars/jerryjliu/llama_index?style=social)
- [CrewAI](https://github.com/joaomdmoura/crewai): 前沿的角色扮演自主 AI 智能体编排框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/joaomdmoura/crewai?style=social)
- [Phidata](https://github.com/phidatahq/phidata): 构建具备记忆、知识和工具的 AI 助手。 ![GitHub Repo stars](https://img.shields.io/github/stars/phidatahq/phidata?style=social)
- [DSPy](https://github.com/stanfordnlp/dspy): 用于编程（而非提示）基础模型的框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/stanfordnlp/dspy?style=social)
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel): 微软 C# SDK，快速轻松地将前沿 LLM 技术集成到应用中。 ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/semantic-kernel?style=social)
- [Haystack](https://github.com/deepset-ai/haystack): 使用 Transformer 模型和 LLM 与数据交互的 NLP 框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/deepset-ai/haystack?style=social)
- [Mastra](https://github.com/mastra-ai/mastra): 有主见的 TypeScript 框架，帮助你快速构建 AI 应用和功能。 ![GitHub Repo stars](https://img.shields.io/github/stars/mastra-ai/mastra?style=social)
- [Swarm](https://github.com/openai/swarm): OpenAI 出品的轻量级多智能体编排教育框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/openai/swarm?style=social)
- [AgentScope](https://github.com/modelscope/agentscope): 更便捷地构建 LLM 驱动的多智能体应用。 ![GitHub Repo stars](https://img.shields.io/github/stars/modelscope/agentscope?style=social)
- [Botpress](https://github.com/botpress/botpress): 构建聊天机器人的基础模块。 ![GitHub Repo stars](https://img.shields.io/github/stars/botpress/botpress?style=social)
- [Upsonic](https://github.com/upsonic/upsonic): 支持 MCP 的可靠 Agent 框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/upsonic/upsonic?style=social)
- [VoltAgent](https://github.com/VoltAgent/voltagent): 开源 TypeScript Agent 框架，内置 LLM 可观测性。 ![GitHub Repo stars](https://img.shields.io/github/stars/voltagent/voltagent?style=social)
- [Swarms Framework](https://github.com/kyegomez/swarms): 面向企业应用的前沿多智能体编排框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/kyegomez/swarms?style=social)
- [PraisonAI](https://github.com/MervinPraison/PraisonAI): 生产就绪的多 AI 智能体框架，支持自我反思。最快的 Agent 实例化速度（3.77μs），支持 100+ LLM、MCP、工作流、记忆，提供 Python 和 JavaScript SDK。 ![GitHub Repo stars](https://img.shields.io/github/stars/MervinPraison/PraisonAI?style=social)
- [Strands Agents SDK](https://github.com/strands-agents/sdk-python): 通过模型驱动的方式，仅需几行代码即可构建 AI 智能体。 ![GitHub Repo stars](https://img.shields.io/github/stars/strands-agents/sdk-python?style=social)
- [AgentVerse](https://github.com/openbmb/agentverse): 灵活的框架，简化为 LLM 构建自定义多智能体环境的流程。 ![GitHub Repo stars](https://img.shields.io/github/stars/openbmb/agentverse?style=social)
- [Maestro](https://github.com/Doriandarko/maestro): Claude Opus 智能编排子智能体的框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/Doriandarko/maestro?style=social)
- [llama-agentic-system](https://github.com/meta-llama/llama-agentic-system): Llama Stack APIs 的 Agent 组件。 ![GitHub Repo stars](https://img.shields.io/github/stars/meta-llama/llama-agentic-system?style=social)
- [AG2](https://github.com/ag2ai/ag2): AutoGen 原创团队打造的开源 AI 智能体编程框架，支持多智能体协作。 ![GitHub Repo stars](https://img.shields.io/github/stars/ag2ai/ag2?style=social)
- [agency-swarm](https://github.com/VRSEN/agency-swarm): 基于最新 OpenAI Assistants API 构建的可靠 Agent 框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/VRSEN/agency-swarm?style=social)
- [Agent-LLM](https://github.com/Josh-XT/Agent-LLM): 人工智能自动化平台。 ![GitHub Repo stars](https://img.shields.io/github/stars/Josh-XT/Agent-LLM?style=social)
- [Lagent](https://github.com/InternLM/lagent): 轻量级 LLM 智能体构建框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/InternLM/lagent?style=social)
- [Agentic Context Engine](https://github.com/kayba-ai/agentic-context-engine): 自我改进的 Agent，从执行反馈中学习。集成 LangChain，支持 Agent 自主管理上下文。 ![GitHub Repo stars](https://img.shields.io/github/stars/kayba-ai/agentic-context-engine?style=social)
- [AgentDock](https://github.com/AgentDock/AgentDock): 摆脱繁琐的 API 集成，AgentDock 提供开源基础，可无摩擦地构建、管理和部署生产级 AI 智能体与工作流。 ![GitHub Repo stars](https://img.shields.io/github/stars/agentdock/agentdock?style=social)
- [Dust](https://github.com/dust-tt/dust): 设计并部署大语言模型应用。 ![GitHub Repo stars](https://img.shields.io/github/stars/dust-tt/dust?style=social)
- [LLM Agents](https://github.com/mpaepper/llm_agents): 构建由 LLM 控制的智能体。 ![GitHub Repo stars](https://img.shields.io/github/stars/mpaepper/llm_agents?style=social)
- [ConnectOnion](https://github.com/openonion/connectonion): 面向生产环境的简洁 Python 框架——两行代码创建 Agent、函数即工具、12 个生命周期钩子、插件系统、支持信任机制的多智能体网络。 ![GitHub Repo stars](https://img.shields.io/github/stars/openonion/connectonion?style=social)
- [Agency](https://github.com/neurocult/agency): 🕵️‍♂️ 为热衷探索 LLM 潜力的开发者设计的库，采用简洁、高效、Go 风格的实现方式。 ![GitHub Repo stars](https://img.shields.io/github/stars/neurocult/agency?style=social)
- [Modus](https://github.com/hypermodeinc/modus): 用 Go 或 AssemblyScript 构建智能 Agent 和 API 的开源无服务器框架。
- [LoongFlow](https://github.com/baidu-baige/LoongFlow): 进化式 Agent 开发框架，从原子组件到核心场景 Agent 全覆盖。 ![GitHub Repo stars](https://img.shields.io/github/stars/baidu-baige/LoongFlow?style=social)
- [AgentFlow](https://github.com/simonmesmith/agentflow): 通过简单 JSON 定义复杂 LLM 工作流。 ![GitHub Repo stars](https://img.shields.io/github/stars/simonmesmith/agentflow?style=social)
- [FIM Agent](https://github.com/fim-ai/fim-agent): AI 驱动的连接器中枢——支持动态 DAG 规划、ReAct Agent、MCP 客户端、有依据的 RAG 生成，以及将任意 API 转化为 Agent 工具的连接器平台。 ![GitHub Repo stars](https://img.shields.io/github/stars/fim-ai/fim-agent?style=social)
- [hcom](https://github.com/aannoo/hcom): 让 AI 智能体跨终端互发消息、互相监控和派生。支持 Claude Code、Gemini CLI、Codex、OpenCode。 ![GitHub Repo stars](https://img.shields.io/github/stars/aannoo/hcom?style=social)
- [Ailoy](https://github.com/brekkylab/ailoy): 全面的 AI Agent 构建框架，支持随处运行，完全支持本地 AI 和 WASM。
- [NeuroLink](https://github.com/juspay/neurolink): TypeScript Agent 框架，支持多步骤 Agent 循环、逐步工具执行控制（`prepareStep`）、持久记忆（Redis/S3/SQLite）、HITL 工作流、MCP 客户端集成和 13 个 LLM 提供商。 ![GitHub Repo stars](https://img.shields.io/github/stars/juspay/neurolink?style=social)
- [Vectara-agentic](https://github.com/vectara/py-vectara-agentic): 使用 Vectara 创建 AI 助手和智能体的框架。
- [AgentUp](https://github.com/RedDotRocket/AgentUp): 以安全、可扩展性和可延展性为基础设计，通过配置驱动架构和丰富的插件生态加速开发。 ![GitHub Repo stars](https://img.shields.io/github/stars/RedDotRocket/AgentUp?style=social)
- [Pilot Protocol](https://github.com/TeoSlayer/pilotprotocol): 为 AI 智能体提供虚拟地址、加密 UDP 隧道、NAT 穿透和互信机制的叠加网络栈。零依赖，Go 语言编写。 ![GitHub Repo stars](https://img.shields.io/github/stars/TeoSlayer/pilotprotocol?style=social)
- [Portia AI](https://github.com/portiaAI/portia-sdk-python/): 全新开源 Python Agentic 框架，专为生产环境中的可靠 Agent 设计。 ![GitHub Repo stars](https://img.shields.io/github/stars/portiaAI/portia-sdk-python?style=social)
- [Transformers Agents](https://huggingface.co/docs/transformers/transformers_agents): 在 Transformers 之上提供自然语言 API。

## 大语言模型与模型工具

构建 AI 智能体的核心驱动力：大语言模型、服务提供商和本地推理平台。

- [Claude](https://claude.ai/): Anthropic 出品的高性能 AI 助手，搭载 Claude 3.5 系列模型。
- [Gemini](https://gemini.google.com/): Google 统一 AI 平台，提供多模态模型套件。
- [ChatGPT](https://chatgpt.com/): OpenAI 基于 GPT 系列的对话 AI。
- [DeepSeek](https://www.deepseek.com/): 领先的中国 AI 实验室，拥有 DeepSeek-R1、DeepSeek-V3 等强大开源模型。
- [Ollama](https://github.com/ollama/ollama): 在 macOS、Linux 和 Windows 本地运行开源 LLM（Llama 3、Mistral、Gemma）的最简方式。 ![GitHub Repo stars](https://img.shields.io/github/stars/ollama/ollama?style=social)
- [Hugging Face](https://huggingface.co/): 机器学习社区分享和下载模型、数据集和应用的核心枢纽。
- [ModelScope](https://modelscope.cn/): 阿里云出品的下一代开源 AI 模型与数据集协同平台。
- [LM Studio](https://lmstudio.ai/): 功能完整的桌面应用，用于发现、下载和运行本地 LLM。

## 编程与开发 Agent

专注于软件开发、代码生成和 DevOps 的 AI 智能体与工具，按 GitHub Star 数量排序。

- [OpenCode](https://github.com/sst/opencode): 专为终端打造的 AI 编程 Agent。 ![GitHub Repo stars](https://img.shields.io/github/stars/sst/opencode?style=social)
- [OpenHands](https://github.com/All-Hands-AI/OpenHands): 🙌 少写代码，多做事。（前身为 OpenDevin）AI 驱动的软件开发 Agent 平台。 ![GitHub Repo stars](https://img.shields.io/github/stars/All-Hands-AI/OpenHands?style=social)
- [MetaGPT](https://github.com/geekan/MetaGPT): 多智能体框架：首个 AI 软件公司，迈向自然语言编程。 ![GitHub Repo stars](https://img.shields.io/github/stars/geekan/MetaGPT?style=social)
- [Cline](https://github.com/cline/cline): 开源 AI 编程 Agent，让开发者直接透明地访问前沿模型。 ![GitHub Repo stars](https://img.shields.io/github/stars/cline/cline?style=social)
- [Aider](https://github.com/Aider-AI/aider): 终端中的 AI 结对编程工具。 ![GitHub Repo stars](https://img.shields.io/github/stars/Aider-AI/aider?style=social)
- [GPT Pilot](https://github.com/Pythagora-io/gpt-pilot): Pythagora VS Code 扩展的核心技术，致力于打造首个真正的 AI 开发者伴侣。 ![GitHub Repo stars](https://img.shields.io/github/stars/Pythagora-io/gpt-pilot?style=social)
- [Devika](https://github.com/stitionai/devika): 能理解高层指令、分解步骤、研究信息并编写代码的 Agentic AI 软件工程师。 ![GitHub Repo stars](https://img.shields.io/github/stars/stitionai/devika?style=social)
- [SWE Agent](https://github.com/princeton-nlp/swe-agent): 自动抓取 GitHub Issue 并尝试使用 GPT-4 或你选择的语言模型修复它。 ![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/swe-agent?style=social)
- [SuperAGI](https://github.com/TransformerOptimus/SuperAGI): 面向开发者的开源自主 AI Agent 框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/TransformerOptimus/SuperAGI?style=social)
- [Plandex](https://github.com/plandex-ai/plandex): 面向复杂任务的 AI 编程引擎。 ![GitHub Repo stars](https://img.shields.io/github/stars/plandex-ai/plandex?style=social)
- [Claude Engineer](https://github.com/Doriandarko/claude-engineer): 交互式命令行工具，利用 Claude-3.5-Sonnet 协助软件开发任务。
- [TaskWeaver](https://github.com/microsoft/TaskWeaver): 无缝规划和执行数据分析任务的代码优先 Agent 框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/TaskWeaver?style=social)
- [Vision agent](https://github.com/landing-ai/vision-agent): 帮助利用 Agent 框架生成代码解决视觉任务的库。 ![GitHub Repo stars](https://img.shields.io/github/stars/landing-ai/vision-agent?style=social)
- [Codel](https://github.com/semanser/codel): ✨ 完全自主的 AI Agent，可使用终端、浏览器和编辑器完成复杂任务。 ![GitHub Repo stars](https://img.shields.io/github/stars/semanser/codel?style=social)
- [ThinkGPT](https://github.com/alaeddine-13/thinkgpt): 增强 LLM 并突破其极限的 Agent 技术。 ![GitHub Repo stars](https://img.shields.io/github/stars/alaeddine-13/thinkgpt?style=social)
- [Nous](https://github.com/TrafficGuard/nous): TypeScript AI Agent 平台，包含自主 Agent、软件开发 Agent、AI 代码审查 Agent 等。 ![GitHub Repo stars](https://img.shields.io/github/stars/TrafficGuard/nous?style=social)
- [Stakpak](https://github.com/stakpak/agent): 开源 DevOps Agent，帮助保护、部署和维护生产就绪的基础设施。 ![GitHub Repo stars](https://img.shields.io/github/stars/stakpak/agent?style=social)
- [RepoAgent](https://github.com/OpenBMB/RepoAgent): LLM 驱动的仓库 Agent，帮助开发者和团队快速生成文档、理解代码库。 ![GitHub Repo stars](https://img.shields.io/github/stars/OpenBMB/RepoAgent?style=social)
- [MicroAgent](https://github.com/aymenfurter/microagents): 能够自我编辑提示词和 Python 代码的 Agent。 ![GitHub Repo stars](https://img.shields.io/github/stars/aymenfurter/microagents?style=social)
- [AgentRun](https://github.com/Jonathan-Adly/AgentRun): 最简单、最快速地安全运行 AI 生成的 Python 代码。 ![GitHub Repo stars](https://img.shields.io/github/stars/Jonathan-Adly/AgentRun?style=social)
- [Dorothy](https://github.com/Charlie85270/Dorothy): 开源桌面应用，同时编排多个 AI CLI Agent（Claude Code、Codex、Gemini），支持自动化、看板管理、远程控制和 MCP 服务器。 ![GitHub Repo stars](https://img.shields.io/github/stars/Charlie85270/Dorothy?style=social)
- [PyCodeAGI](https://github.com/chakkaradeep/pyCodeAGI): 根据用户需求生成 Python 应用的小型 AGI 实验。 ![GitHub Repo stars](https://img.shields.io/github/stars/chakkaradeep/pyCodeAGI?style=social)
- [VibeGrid](https://github.com/jcanizalez/vibegrid): AI 编程 Agent 终端管理器，支持多 Agent 网格、任务队列、工作流自动化、无头执行、内联差异审查和 Claude Code 钩子。 ![GitHub Repo stars](https://img.shields.io/github/stars/jcanizalez/vibegrid?style=social)
- [Greywall](https://github.com/GreyhavenHQ/greywall): AI 编程 Agent 的默认拒绝命令沙箱，支持文件系统隔离、透明代理网络控制、内置 Agent 配置文件和自动生成配置的学习模式。 ![GitHub Repo stars](https://img.shields.io/github/stars/GreyhavenHQ/greywall?style=social)
- [ReviewCerberus](https://github.com/Kirill89/reviewcerberus): 100% 免费的开源 AI 代码审查工具，分析 git 分支差异，提供全面的安全、性能和质量分析。
- [Hivemoot Colony](https://github.com/hivemoot/colony): 自主 Agent 治理平台，AI 智能体对功能进行投票、代码审查并发布版本，无需人工干预。附带实时治理仪表板。 ![GitHub Repo stars](https://img.shields.io/github/stars/hivemoot/colony?style=social)

## 自动化与工作流

用于任务自动化、工作流编排和通用自主操作的 Agent 与平台，按 GitHub Star 数量排序。

- [Astron](https://github.com/iflytek/astron-agent): 企业级、商业友好的 Agentic 工作流平台，用于构建下一代 SuperAgent。
- [Hive](https://github.com/aden-hive/hive): 开源 AI Agent 框架，用于构建目标驱动、自我改进的自主 Agent。用自然语言定义目标，自动生成 Agent 图，内置进化循环、MCP 集成和 100+ 工具。 ![GitHub Repo stars](https://img.shields.io/github/stars/aden-hive/hive?style=social)
- [XAgent](https://github.com/OpenBMB/XAgent): 用于解决复杂任务的自主 LLM Agent。 ![GitHub Repo stars](https://img.shields.io/github/stars/OpenBMB/XAgent?style=social)
- [llama-agents](https://github.com/run-llama/llama-agents): 异步优先的多智能体系统构建框架，支持多智能体通信、分布式工具执行、人机协作等。 ![GitHub Repo stars](https://img.shields.io/github/stars/run-llama/llama-agents?style=social)
- [DemoGPT](https://github.com/melih-unsal/DemoGPT): 仅通过提示即可快速创建演示，在 LangChain 文档树上应用 ToT 方法。 ![GitHub Repo stars](https://img.shields.io/github/stars/melih-unsal/DemoGPT?style=social)
- [uAgents](https://github.com/fetchai/uAgents): 快速轻量的去中心化 Agent 创建框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/fetchai/uAgents?style=social)
- [ADAS](https://github.com/ShengranHu/ADAS): 自动化 Agentic 系统设计。 ![GitHub Repo stars](https://img.shields.io/github/stars/ShengranHu/ADAS?style=social)
- [RestGPT](https://github.com/Yifan-Song793/RestGPT): 通过 RESTful API 控制现实世界应用的 LLM 自主 Agent。 ![GitHub Repo stars](https://img.shields.io/github/stars/Yifan-Song793/RestGPT?style=social)
- [AgentK](https://github.com/mikekelly/AgentK): 自我进化且模块化的自代理 AGI。 ![GitHub Repo stars](https://img.shields.io/github/stars/mikekelly/AgentK?style=social)
- [Giselle](https://github.com/giselles-ai/giselle): Agentic 工作流构建器，助你轻松创建 AI 驱动的解决方案。 ![Github Repo stars](https://img.shields.io/github/stars/giselles-ai/giselle?style=social)
- [Multi-Modal LangChain agents in Production](https://github.com/steamship-packages/langchain-agent-production-starter): 部署 LangChain Agent 并将其连接到 Telegram。 ![GitHub Repo stars](https://img.shields.io/github/stars/steamship-packages/langchain-agent-production-starter?style=social)
- [Untether](https://github.com/littlebearapps/untether): AI 编程 Agent 的 Telegram 桥接器——支持远程任务控制、进度流式传输、交互式权限、语音输入和成本追踪。支持 Claude Code、Codex、OpenCode、Pi、Gemini CLI 和 Amp。 ![GitHub Repo stars](https://img.shields.io/github/stars/littlebearapps/untether?style=social)

## 研究与分析

专注于研究、科学发现和数据分析的 AI 智能体，按 GitHub Star 数量排序。

- [Storm](https://github.com/stanford-oval/storm): LLM 驱动的知识整理系统，研究一个主题并生成带引用的完整报告。 ![GitHub Repo stars](https://img.shields.io/github/stars/stanford-oval/storm?style=social)
- [GPT Researcher](https://github.com/assafelovic/gpt-researcher): 自主 Agent，针对各类任务进行全面的在线研究。 ![GitHub Repo stars](https://img.shields.io/github/stars/assafelovic/gpt-researcher?style=social)
- [AI Scientist](https://github.com/SakanaAI/AI-Scientist): AI 科学家：迈向完全自动化的开放式科学发现。 ![GitHub Repo stars](https://img.shields.io/github/stars/SakanaAI/AI-Scientist?style=social)
- [DeepAnalyze](https://github.com/ruc-datalab/DeepAnalyze): 首个用于自主数据科学的 Agentic LLM，支持数据准备、分析、建模、可视化和洞察，以及面向数据的深度研究（生成分析师级研究报告）。 [![GitHub Repo stars](https://img.shields.io/github/stars/ruc-datalab/DeepAnalyze?style=social&label=Code+Stars)](https://github.com/ruc-datalab/DeepAnalyze)
- [data-to-paper](https://github.com/Technion-Kishony-lab/data-to-paper): AI 驱动的研究，从数据到人类可验证的研究论文。 ![GitHub Repo stars](https://img.shields.io/github/stars/Technion-Kishony-lab/data-to-paper?style=social)
- [BlockAGI](https://github.com/blockpipe/blockagi): 迭代式、特定领域研究，输出详细的叙述性报告以展示其发现。 ![GitHub Repo stars](https://img.shields.io/github/stars/blockpipe/blockagi?style=social)
- [OpenLens AI](https://github.com/jarrycyx/openlens-ai): 面向健康信息学的完全自主研究 Agent。 ![GitHub Repo stars](https://img.shields.io/github/stars/jarrycyx/openlens-ai?style=social)
- [GenoMAS](https://github.com/Liu-Hy/GenoMAS): 面向科学发现的多智能体框架，通过代码驱动工作流自动化基因表达分析。 ![GitHub Repo stars](https://img.shields.io/github/stars/Liu-Hy/GenoMAS?style=social)

## 对话与个人助理 Agent

面向对话、个人助理和会话场景的 AI 智能体，按 GitHub Star 数量排序。

- [OpenClaw](https://github.com/openclaw/openclaw): 开源 AI Agent 框架，将 LLM 转化为持久、主动的个人 AI 智能体，支持多渠道消息（Signal、Telegram、Discord、WhatsApp）、定时调度、记忆系统、MCP 集成、技能插件、子 Agent 派生和浏览器自动化。 ![GitHub Repo stars](https://img.shields.io/github/stars/openclaw/openclaw?style=social)
- [CollosalAI Chat](https://github.com/hpcaitech/ColossalAI/tree/main/applications/Chat): 用 RLHF 实现 LLM，由 Colossal-AI 项目驱动。 ![GitHub Repo stars](https://img.shields.io/github/stars/hpcaitech/ColossalAI?style=social)
- [nanobot](https://github.com/HKUDS/nanobot): 超轻量级个人 AI 助手框架（约 4,000 行 Python 代码），支持 MCP、9+ 聊天频道和可扩展技能系统。 ![GitHub Repo stars](https://img.shields.io/github/stars/HKUDS/nanobot?style=social)
- [Memgpt](https://github.com/cpacker/memgpt): 创建具有长期记忆和自定义工具的 LLM 智能体。 ![Github Repo stars](https://img.shields.io/github/stars/cpacker/memgpt?style=social)
- [SuperAgent](https://github.com/homanp/superagent): 将 LLM 智能体部署到生产环境。 ![GitHub Repo stars](https://img.shields.io/github/stars/homanp/superagent?style=social)
- [RasaGPT](https://github.com/paulpierre/RasaGPT): 首个基于 Rasa 和 LangChain 构建的无头 LLM 聊天机器人平台。 ![GitHub Repo stars](https://img.shields.io/github/stars/paulpierre/RasaGPT?style=social)
- [Awesome OpenClaw Agents](https://github.com/mergisi/awesome-openclaw-agents): 精选 100+ 个生产就绪的 OpenClaw SOUL.md Agent 模板，涵盖生产力、开发、营销和业务自动化。 ![GitHub Repo stars](https://img.shields.io/github/stars/mergisi/awesome-openclaw-agents?style=social)
- [BabyAGI UI](https://github.com/miurla/babyagi-ui): 更便捷地在 Web 应用中运行和开发 babyagi，类似 ChatGPT。 ![GitHub Repo stars](https://img.shields.io/github/stars/miurla/babyagi-ui?style=social)
- [ix](https://github.com/kreneskyp/ix): 自主 GPT-4 智能体平台。 ![GitHub Repo stars](https://img.shields.io/github/stars/kreneskyp/ix?style=social)
- [LLama Cpp Agent](https://github.com/Maximilian-Winter/llama-cpp-agent): 专为简化与大语言模型交互而设计的工具。 ![GitHub Repo stars](https://img.shields.io/github/stars/Maximilian-Winter/llama-cpp-agent?style=social)
- [Autonomous HR Chatbot](https://github.com/stepanogil/autonomous-hr-chatbot): 自主解答 HR 相关问题的 Agent，利用其手头的工具。 ![GitHub Repo stars](https://img.shields.io/github/stars/stepanogil/autonomous-hr-chatbot?style=social)
- [ClaudeClaw](https://github.com/sbusso/claudeclaw): Claude Code 的持久化 Agent 编排插件——多渠道路由（Slack、WhatsApp、Telegram）、OS 级沙箱隔离、可组合扩展、结构化记忆、Webhook 触发器。 ![GitHub Repo stars](https://img.shields.io/github/stars/sbusso/claudeclaw?style=social)

## 知识管理与 RAG

用于文档检索、私有知识库和 RAG 管道的智能体与工具，按 GitHub Star 数量排序。

- [Private GPT](https://github.com/imartinez/privateGPT): 利用 GPT 的强大功能与文档私密交互，100% 私密，零数据泄露。 ![GitHub Repo stars](https://img.shields.io/github/stars/imartinez/privateGPT?style=social)
- [Local GPT](https://github.com/PromtEngineer/localGPT): 受 Private GPT 启发，用 GPT4ALL 模型替换 Vicuna-7B，使用 InstructorEmbeddings 代替 LlamaEmbeddings。 ![GitHub Repo stars](https://img.shields.io/github/stars/PromtEngineer/localGPT?style=social)
- [DB GPT](https://github.com/csunny/DB-GPT): 使用本地 GPT 与数据和环境交互，零数据泄露，100% 私密，100% 安全。 ![GitHub Repo stars](https://img.shields.io/github/stars/csunny/DB-GPT?style=social)
- [LLocalSearch](https://github.com/nilsherzig/LLocalSearch): 完全本地运行的 LLM Agent 搜索聚合器。用户提问，系统使用 LLM 链找到答案。无需 OpenAI 或 Google API 密钥。 ![GitHub Repo stars](https://img.shields.io/github/stars/nilsherzig/LLocalSearch?style=social)
- [Agentset](https://github.com/agentset-ai/agentset): 开源生产就绪的 RAG 平台，内置 Agentic 推理、混合搜索和多模态支持。 ![GitHub Repo stars](https://img.shields.io/github/stars/agentset-ai/agentset?style=social)
- [Second Brain AI Agent](https://github.com/flepied/second-brain-agent): 使用 OpenAI 和 ChromaDB 本地对话笔记的 Streamlit 应用。 ![GitHub Repo stars](https://img.shields.io/github/stars/flepied/second-brain-agent?style=social)
- [Cortex Memory](https://github.com/sopaco/cortex-mem): 智能体记忆的完整解决方案，涵盖提取、向量搜索到自动优化，开箱即用提供 REST API、MCP、CLI 和洞察仪表板。
- [SAGE](https://github.com/l33tdawg/sage): AI 智能体的机构记忆——每条记忆在提交前都经过 BFT 共识。4 个应用验证器、13 个 MCP 工具，本地运行。 ![GitHub Repo stars](https://img.shields.io/github/stars/l33tdawg/sage?style=social)

## 浏览器与 Web Agent

用于浏览器自动化和 Web 交互的 Agent 与基础设施，按 GitHub Star 数量排序。

- [AgentGPT](https://github.com/reworkd/AgentGPT): 使用 LangChain 和 OpenAI 构建的 AI 智能体（Vercel / Nextjs）。 ![GitHub Repo stars](https://img.shields.io/github/stars/reworkd/AgentGPT?style=social)
- [Steel Browser](https://github.com/steel-dev/steel-browser): AI 智能体的开源浏览器基础设施，支持会话自动化、提取、截图/PDF、AI 原生 CLI 和可复用的 steel-browser 技能。 ![GitHub Repo stars](https://img.shields.io/github/stars/steel-dev/steel-browser?style=social)
- [OpenAgents](https://github.com/xlang-ai/OpenAgents): 现实世界中语言智能体的开放平台。 ![GitHub Repo stars](https://img.shields.io/github/stars/xlang-ai/OpenAgents?style=social)
- [Gobii](https://github.com/gobii-ai/gobii-platform): 开源平台，以对话界面和 API 大规模部署和管理浏览器使用 Agent。 ![GitHub Repo stars](https://img.shields.io/github/stars/gobii-ai/gobii-platform?style=social)

## 语音与多模态

用于语音、音频和多模态交互的 Agent 与框架，按 GitHub Star 数量排序。

- [Pipecat](https://github.com/pipecat-ai/pipecat): 开源的语音和多模态对话 AI 框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/pipecat-ai/pipecat?style=social)
- [joinly](https://github.com/joinly-ai/joinly): 语音优先的在线会议 AI 助手，可主动参与会议并实时解决任务。 ![GitHub Repo stars](https://img.shields.io/github/stars/joinly-ai/joinly?style=social)

## 测试与评估

用于测试、评估和观测 AI 智能体的框架与工具，按 GitHub Star 数量排序。

- [Arize-Phoenix](https://github.com/Arize-ai/phoenix): 开源的 Agent 测试、评估和可观测性库。 ![GitHub Repo stars](https://img.shields.io/github/stars/Arize-ai/phoenix?style=social)
- [Manifest](https://github.com/mnfst/manifest): AI 智能体的开源实时成本可观测平台。追踪 Token、成本、消息和模型使用情况，提供本地优先仪表板。支持 28+ LLM 模型、OTLP 摄入、自托管。 ![GitHub Repo stars](https://img.shields.io/github/stars/mnfst/manifest?style=social)
- [EvoAgentX](https://github.com/EvoAgentX/EvoAgentX): 构建自我进化的 AI 智能体生态系统，提供自动化评估和进化 Agentic 工作流的框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/EvoAgentX/EvoAgentX?style=social)
- [Open-RAG-Eval](https://github.com/vectara/open-rag-eval): 开源 RAG 评估框架，无需标准答案，可用于评估连接到 AI Agent 的 RAG 工具性能（Agentic RAG）。
- [Voice Lab](https://github.com/saharmor/voice-lab): 全面的语音 Agent 测试和评估框架，支持跨语言模型、提示词和 Agent 角色的评估。 ![GitHub Repo stars](https://img.shields.io/github/stars/saharmor/voice-lab?style=social)
- [voicetest](https://github.com/voicetestdev/voicetest): 语音 Agent 的开源测试工具，支持 Retell、VAPI、Bland 和 LiveKit。运行自主模拟并使用 LLM 评判器评估。 ![GitHub Repo stars](https://img.shields.io/github/stars/voicetestdev/voicetest?style=social)

## 基础设施与安全

用于智能体部署、沙箱隔离和安全防护的平台与工具，按 GitHub Star 数量排序。

- [e2b](https://github.com/e2b-dev/e2b): 构建和部署虚拟开发者 Agent 的开源平台。
- [AgentField](https://github.com/Agent-Field/agentfield): AI 后端的开源基础设施。Kubernetes 用于编排，Okta 用于身份管理——从第一天起就生产就绪。 ![GitHub Repo stars](https://img.shields.io/github/stars/Agent-Field/agentfield?style=social)

## 游戏与模拟

面向游戏、仿真模拟和人类行为建模的 AI 智能体，按 GitHub Star 数量排序。

- [Voyager](https://github.com/MineDojo/Voyager): 基于大语言模型的开放式具身 Agent。 ![GitHub Repo stars](https://img.shields.io/github/stars/MineDojo/Voyager?style=social)
- [Camel-AutoGPT](https://github.com/SamurAIGPT/Camel-AutoGPT): LLM 和自主 Agent（如 BabyAGI 和 AutoGPT）的角色扮演方法。 ![GitHub Repo stars](https://img.shields.io/github/stars/SamurAIGPT/Camel-AutoGPT?style=social)
- [SkyAGI](https://github.com/litanlitudan/skyagi): LLM 智能体中涌现的人类行为模拟能力。 ![GitHub Repo stars](https://img.shields.io/github/stars/litanlitudan/skyagi?style=social)
