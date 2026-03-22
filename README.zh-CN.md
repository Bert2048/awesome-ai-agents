# 🤖 Awesome AI Agents 🤖


**语言：** [English](README.md) | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md) | [Français](README.fr.md)

精选开源框架、工具与项目合集，涵盖 AI Agent 构建所需的一切资源。包括 Agent 编排、工具调用、多智能体协作、RAG、浏览器自动化、语音界面等——探索并构建智能体生态系统的完整指南。

## 目录

- [🤖 Awesome AI Agents 🤖](#-awesome-ai-agents-)
  - [目录](#目录)
  - [框架与 SDK](#框架与-sdk)
  - [大语言模型与模型工具](#大语言模型与模型工具)
  - [提示词与技能库](#提示词与技能库)
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

- [LangChain](https://github.com/hwchase17/langchain): 行业领先的框架，用于构建逻辑驱动的 LLM 应用程序。![GitHub Repo stars](https://img.shields.io/github/stars/hwchase17/langchain?style=plastic&color=lightgrey&logo=github)
- [Autogen](https://github.com/microsoft/autogen): 支持开发下一代多智能体应用的开源框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/autogen?style=plastic&color=lightgrey&logo=github)
- [LlamaIndex](https://github.com/jerryjliu/llama_index): 为大语言模型提供外部数据连接的核心数据框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/jerryjliu/llama_index?style=plastic&color=lightgrey&logo=github)
- [Vercel AI SDK](https://github.com/vercel/ai): 用于在 React、Next.js、Vue 等框架中构建 AI 驱动流式界面的完整工具包。 ![GitHub Repo stars](https://img.shields.io/github/stars/vercel/ai?style=plastic&color=lightgrey&logo=github)
- [CrewAI](https://github.com/joaomdmoura/crewai): 先进的角色扮演自主 AI 智能体编排框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/joaomdmoura/crewai?style=plastic&color=lightgrey&logo=github)
- [Phidata](https://github.com/phidatahq/phidata): 构建具备记忆、知识和工具调用能力的 AI 助手。 ![GitHub Repo stars](https://img.shields.io/github/stars/phidatahq/phidata?style=plastic&color=lightgrey&logo=github)
- [DSPy](https://github.com/stanfordnlp/dspy): 通过编程（而非提示词）来优化基础模型的学术框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/stanfordnlp/dspy?style=plastic&color=lightgrey&logo=github)
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel): 微软推出的 C# SDK，可快速将 LLM 技术集成到各类应用中。 ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/semantic-kernel?style=plastic&color=lightgrey&logo=github)
- [Haystack](https://github.com/deepset-ai/haystack): 使用 Transformer 模型和 LLM 构建定制化搜索与问答系统的框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/deepset-ai/haystack?style=plastic&color=lightgrey&logo=github)
- [Mastra](https://github.com/mastra-ai/mastra): 有主见的 TypeScript 框架，专为快速构建 AI 应用而设计。 ![GitHub Repo stars](https://img.shields.io/github/stars/mastra-ai/mastra?style=plastic&color=lightgrey&logo=github)
- [Swarm](https://github.com/openai/swarm): OpenAI 推出的轻量级、教育导向的多智能体编排框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/openai/swarm?style=plastic&color=lightgrey&logo=github)
- [AgentScope](https://github.com/modelscope/agentscope): 旨在降低多智能体应用开发门槛的高性能框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/modelscope/agentscope?style=plastic&color=lightgrey&logo=github)
- [Claude Agent SDK](https://github.com/anthropics/anthropic-sdk-typescript): Anthropic 官方推出的 TypeScript SDK，支持高级智能体交互。
- [Botpress](https://github.com/botpress/botpress): 用于构建生产级聊天机器人的开源对话 AI 平台。 ![GitHub Repo stars](https://img.shields.io/github/stars/botpress/botpress?style=plastic&color=lightgrey&logo=github)
- [Upsonic](https://github.com/upsonic/upsonic): 支持 MCP 协议的可靠 Agent 构建框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/upsonic/upsonic?style=plastic&color=lightgrey&logo=github)
- [VoltAgent](https://github.com/VoltAgent/voltagent): 内置 LLM 可观测性的开源 TypeScript Agent 框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/voltagent/voltagent?style=plastic&color=lightgrey&logo=github)
- [PraisonAI](https://github.com/MervinPraison/PraisonAI): 极速实例化的生产级多智能体框架，支持自我反思。 ![GitHub Repo stars](https://img.shields.io/github/stars/MervinPraison/PraisonAI?style=plastic&color=lightgrey&logo=github)
- [Swarms Framework](https://github.com/kyegomez/swarms): 面向企业级应用的前沿多智能体协作框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/kyegomez/swarms?style=plastic&color=lightgrey&logo=github)
- [Strands Agents SDK](https://github.com/strands-agents/sdk-python): 模型驱动的 Agent 开发工具，提供简洁的编排逻辑。 ![GitHub Repo stars](https://img.shields.io/github/stars/strands-agents/sdk-python?style=plastic&color=lightgrey&logo=github)
- [AgentVerse](https://github.com/openbmb/agentverse): 简化 LLM 自定义多智能体环境构建的灵活框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/openbmb/agentverse?style=plastic&color=lightgrey&logo=github)
- [Maestro](https://github.com/Doriandarko/maestro): 基于 Claude Opus 的子智能体编排框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/Doriandarko/maestro?style=plastic&color=lightgrey&logo=github)
- [llama-agentic-system](https://github.com/meta-llama/llama-agentic-system): Llama Stack APIs 的核心智能体组件。 ![GitHub Repo stars](https://img.shields.io/github/stars/meta-llama/llama-agentic-system?style=plastic&color=lightgrey&logo=github)
- [AG2](https://github.com/ag2ai/ag2): AutoGen 原创团队打造的开源智能体编程框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/ag2ai/ag2?style=plastic&color=lightgrey&logo=github)
- [agency-swarm](https://github.com/VRSEN/agency-swarm): 基于 OpenAI Assistants API 构建的可靠编排库。 ![GitHub Repo stars](https://img.shields.io/github/stars/VRSEN/agency-swarm?style=plastic&color=lightgrey&logo=github)
- [Agent-LLM](https://github.com/Josh-XT/Agent-LLM): 提供全方位自动化的 AI 智能体管理平台。 ![GitHub Repo stars](https://img.shields.io/github/stars/Josh-XT/Agent-LLM?style=plastic&color=lightgrey&logo=github)
- [Lagent](https://github.com/InternLM/lagent): 简洁轻量的大语言模型智能体构建工具。 ![GitHub Repo stars](https://img.shields.io/github/stars/InternLM/lagent?style=plastic&color=lightgrey&logo=github)
- [Agentic Context Engine](https://github.com/kayba-ai/agentic-context-engine): 能够从反馈中持续学习并优化上下文的 Agent。 ![GitHub Repo stars](https://img.shields.io/github/stars/kayba-ai/agentic-context-engine?style=plastic&color=lightgrey&logo=github)
- [AgentDock](https://github.com/AgentDock/AgentDock): 轻量级的生产级 AI 智能体部署与管理底座。 ![GitHub Repo stars](https://img.shields.io/github/stars/agentdock/agentdock?style=plastic&color=lightgrey&logo=github)
- [Dust](https://github.com/dust-tt/dust): 专为设计和部署大规模 LLM 应用而优化的平台。 ![GitHub Repo stars](https://img.shields.io/github/stars/dust-tt/dust?style=plastic&color=lightgrey&logo=github)
- [LLM Agents](https://github.com/mpaepper/llm_agents): 专注于开发由 LLM 控制的任务执行智能体。 ![GitHub Repo stars](https://img.shields.io/github/stars/mpaepper/llm_agents?style=plastic&color=lightgrey&logo=github)
- [ConnectOnion](https://github.com/openonion/connectonion): 支持多智能体信任网络的极简 Python 框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/openonion/connectonion?style=plastic&color=lightgrey&logo=github)
- [Agency](https://github.com/neurocult/agency): 🕵️‍♂️ 采用 Go 语言风格实现的简洁高效 LLM 扩展库。 ![GitHub Repo stars](https://img.shields.io/github/stars/neurocult/agency?style=plastic&color=lightgrey&logo=github)
- [Modus](https://github.com/hypermodeinc/modus): 支持 Go 或 AssemblyScript 的开源无服务器 Agent 框架。
- [LoongFlow](https://github.com/baidu-baige/LoongFlow): 百度出品的进化式开发框架，涵盖原子组件到核心场景。 ![GitHub Repo stars](https://img.shields.io/github/stars/baidu-baige/LoongFlow?style=plastic&color=lightgrey&logo=github)
- [AgentFlow](https://github.com/simonmesmith/agentflow): 通过 JSON 配置来定义复杂 LLM 工作流。 ![GitHub Repo stars](https://img.shields.io/github/stars/simonmesmith/agentflow?style=plastic&color=lightgrey&logo=github)
- [FIM Agent](https://github.com/fim-ai/fim-agent): 动态 DAG 规划的多功能智能体连接中心。 ![GitHub Repo stars](https://img.shields.io/github/stars/fim-ai/fim-agent?style=plastic&color=lightgrey&logo=github)
- [hcom](https://github.com/aannoo/hcom): 实现跨终端智能体通信与协同的工具。 ![GitHub Repo stars](https://img.shields.io/github/stars/aannoo/hcom?style=plastic&color=lightgrey&logo=github)
- [Ailoy](https://github.com/brekkylab/ailoy): 完全支持本地运行和 WASM 的全能 Agent 框架。
- [NeuroLink](https://github.com/juspay/neurolink): 支持多步循环、持久记忆和 MCP 客户端的 TypeScript 框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/juspay/neurolink?style=plastic&color=lightgrey&logo=github)
- [Vectara-agentic](https://github.com/vectara/py-vectara-agentic): 基于 Vectara 的 RAG 智能体构建工具。
- [AgentUp](https://github.com/RedDotRocket/AgentUp): 配置驱动的、可扩展的加密智能体生态系统架构。 ![GitHub Repo stars](https://img.shields.io/github/stars/RedDotRocket/AgentUp?style=plastic&color=lightgrey&logo=github)
- [Pilot Protocol](https://github.com/TeoSlayer/pilotprotocol): 为智能体通信提供虚拟身份和加密隧道的去中心化协议。 ![GitHub Repo stars](https://img.shields.io/github/stars/TeoSlayer/pilotprotocol?style=plastic&color=lightgrey&logo=github)
- [Portia AI](https://github.com/portiaAI/portia-sdk-python/): 专为生产环境中的高可靠性智能体设计的 Python 框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/portiaAI/portia-sdk-python?style=plastic&color=lightgrey&logo=github)
- [Transformers Agents](https://huggingface.co/docs/transformers/transformers_agents): 基于 Transformers 库的自然语言工具调用 API。

## 大语言模型与模型工具

构建 AI 智能体的核心驱动力：大语言模型、服务提供商和本地推理平台。

- [Claude](https://claude.ai/): Anthropic 出品的高性能 AI 助手，搭载 Claude 3.5 系列模型。
- [Gemini](https://gemini.google.com/): Google 统一 AI 平台，提供多模态模型套件。
- [ChatGPT](https://chatgpt.com/): OpenAI 基于 GPT 系列的对话 AI。
- [DeepSeek](https://www.deepseek.com/): 领先的中国 AI 实验室，拥有 DeepSeek-R1、DeepSeek-V3 等强大开源模型。
- [Ollama](https://github.com/ollama/ollama): 在 macOS、Linux 和 Windows 本地运行开源 LLM（Llama 3、Mistral、Gemma）的最简方式。 ![GitHub Repo stars](https://img.shields.io/github/stars/ollama/ollama?style=plastic&color=lightgrey&logo=github)
- [Hugging Face](https://huggingface.co/): 机器学习社区分享和下载模型、数据集和应用的核心枢纽。
- [ModelScope](https://modelscope.cn/): 阿里云出品的下一代开源 AI 模型与数据集协同平台。
- [LM Studio](https://lmstudio.ai/): 功能完整的桌面应用，用于发现、下载和运行本地 LLM。

## 提示词与技能库

提示工程指南、结构化生成工具、MCP 技能服务器及 LLM 实用工具库，按 GitHub Star 数量排序。

- [Awesome ChatGPT Prompts](https://github.com/f/awesome-chatgpt-prompts): 大规模社区精选的 ChatGPT 提示词模板合集，覆盖数百种角色扮演和任务场景。 ![GitHub Repo stars](https://img.shields.io/github/stars/f/awesome-chatgpt-prompts?style=plastic&color=lightgrey&logo=github)
- [MCP Servers](https://github.com/modelcontextprotocol/servers): MCP 官方参考服务器合集，让智能体能够连接文件系统、数据库、API 及外部服务。 ![GitHub Repo stars](https://img.shields.io/github/stars/modelcontextprotocol/servers?style=plastic&color=lightgrey&logo=github)
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook): OpenAI API 的官方示例代码与指南，涵盖 RAG、微调、函数调用及生产部署模式。 ![GitHub Repo stars](https://img.shields.io/github/stars/openai/openai-cookbook?style=plastic&color=lightgrey&logo=github)
- [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide): 全面的提示工程技巧指南，涵盖思维链、少样本学习、RAG 等高级提示策略。 ![GitHub Repo stars](https://img.shields.io/github/stars/dair-ai/Prompt-Engineering-Guide?style=plastic&color=lightgrey&logo=github)
- [LiteLLM](https://github.com/BerriAI/litellm): 统一 100+ LLM 提供商的 API 网关，提供 OpenAI 兼容接口、负载均衡和成本追踪。 ![GitHub Repo stars](https://img.shields.io/github/stars/BerriAI/litellm?style=plastic&color=lightgrey&logo=github)
- [Anthropic Cookbook](https://github.com/anthropics/anthropic-cookbook): 使用 Claude 构建应用的官方代码示例与指南，包含智能体模式、工具调用和多模态工作流。 ![GitHub Repo stars](https://img.shields.io/github/stars/anthropics/anthropic-cookbook?style=plastic&color=lightgrey&logo=github)
- [Guidance](https://github.com/guidance-ai/guidance): 一种结构化提示语言，用于精确控制 LLM 的输出格式、约束条件和生成流程。 ![GitHub Repo stars](https://img.shields.io/github/stars/guidance-ai/guidance?style=plastic&color=lightgrey&logo=github)
- [Promptfoo](https://github.com/promptfoo/promptfoo): 开源的 LLM 提示词与智能体测试、评估和红队工具，支持多模型对比。 ![GitHub Repo stars](https://img.shields.io/github/stars/promptfoo/promptfoo?style=plastic&color=lightgrey&logo=github)
- [Outlines](https://github.com/outlines-dev/outlines): 通过 JSON Schema 和正则约束实现可靠结构化文本生成的框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/outlines-dev/outlines?style=plastic&color=lightgrey&logo=github)
- [Instructor](https://github.com/jxnl/instructor): 基于 Pydantic 的 Python 库，用于从多家 LLM 提供商获取结构化、经过验证的输出。 ![GitHub Repo stars](https://img.shields.io/github/stars/jxnl/instructor?style=plastic&color=lightgrey&logo=github)
- [Promptflow](https://github.com/microsoft/promptflow): 微软出品的 LLM 流程构建、测试、评估与生产发布一体化工具套件。 ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/promptflow?style=plastic&color=lightgrey&logo=github)
- [Brex's Prompt Engineering Guide](https://github.com/brexhq/prompt-engineering): Brex 工程团队出品的面向生产环境的 LLM 实用提示工程指南。 ![GitHub Repo stars](https://img.shields.io/github/stars/brexhq/prompt-engineering?style=plastic&color=lightgrey&logo=github)

## 编程与开发 Agent

专注于软件开发、代码生成和 DevOps 的 AI 智能体与工具，按 GitHub Star 数量排序。

- [OpenCode](https://github.com/sst/opencode): 专为终端工作流优化的 AI 编程助手。 ![GitHub Repo stars](https://img.shields.io/github/stars/sst/opencode?style=plastic&color=lightgrey&logo=github)
- [OpenHands](https://github.com/All-Hands-AI/OpenHands): 🙌 协作式软件开发智能体平台（前身为 OpenDevin）。 ![GitHub Repo stars](https://img.shields.io/github/stars/All-Hands-AI/OpenHands?style=plastic&color=lightgrey&logo=github)
- [MetaGPT](https://github.com/geekan/MetaGPT): 旨在模仿虚拟 AI 软件公司的多智能体协作框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/geekan/MetaGPT?style=plastic&color=lightgrey&logo=github)
- [Cline](https://github.com/cline/cline): 开源 AI 编程助手，让开发者透明地调用顶尖大模型。 ![GitHub Repo stars](https://img.shields.io/github/stars/cline/cline?style=plastic&color=lightgrey&logo=github)
- [Aider](https://github.com/Aider-AI/aider): 强大的终端 AI 结对编程助手，可直接修改本地代码库。 ![GitHub Repo stars](https://img.shields.io/github/stars/Aider-AI/aider?style=plastic&color=lightgrey&logo=github)
- [GPT Pilot](https://github.com/Pythagora-io/gpt-pilot): 致力于打造首个真正的 AI 开发者伴侣，助力构建可扩展应用。 ![GitHub Repo stars](https://img.shields.io/github/stars/Pythagora-io/gpt-pilot?style=plastic&color=lightgrey&logo=github)
- [Devika](https://github.com/stitionai/devika): 支持自主研究、规划和代码编写的高级 Agentic AI 开发工程师。 ![GitHub Repo stars](https://img.shields.io/github/stars/stitionai/devika?style=plastic&color=lightgrey&logo=github)
- [SWE Agent](https://github.com/princeton-nlp/swe-agent): 能够自主导航 GitHub 问题并提交修复补丁的自主智能体。 ![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/swe-agent?style=plastic&color=lightgrey&logo=github)
- [SuperAGI](https://github.com/TransformerOptimus/SuperAGI): 开发者优先的自主 AI 智能体构建与部署框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/TransformerOptimus/SuperAGI?style=plastic&color=lightgrey&logo=github)
- [Plandex](https://github.com/plandex-ai/plandex): 能够处理复杂、多文件代码生成与重构任务的 AI 引擎。 ![GitHub Repo stars](https://img.shields.io/github/stars/plandex-ai/plandex?style=plastic&color=lightgrey&logo=github)
- [Claude Engineer](https://github.com/Doriandarko/claude-engineer): 利用 Claude-3.5-Sonnet 协助处理开发任务的交互式 CLI。
- [TaskWeaver](https://github.com/microsoft/TaskWeaver): 实现数据分析任务无缝规划与执行的代码优先框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/TaskWeaver?style=plastic&color=lightgrey&logo=github)
- [Vision agent](https://github.com/landing-ai/vision-agent): 利用 Agent 框架为计算机视觉任务生成代码解决方案。 ![GitHub Repo stars](https://img.shields.io/github/stars/landing-ai/vision-agent?style=plastic&color=lightgrey&logo=github)
- [Codel](https://github.com/semanser/codel): ✨ 跨终端、浏览器和编辑器的全自主 AI 任务执行专家。 ![GitHub Repo stars](https://img.shields.io/github/stars/semanser/codel?style=plastic&color=lightgrey&logo=github)
- [ThinkGPT](https://github.com/alaeddine-13/thinkgpt): 提供前沿技术以增强 LLM 能力，突破其标准界限。 ![GitHub Repo stars](https://img.shields.io/github/stars/alaeddine-13/thinkgpt?style=plastic&color=lightgrey&logo=github)
- [Nous](https://github.com/TrafficGuard/nous): 包含自主代码审查与开发智能体的 TypeScript 平台。 ![GitHub Repo stars](https://img.shields.io/github/stars/TrafficGuard/nous?style=plastic&color=lightgrey&logo=github)
- [Stakpak](https://github.com/stakpak/agent): 开源 DevOps Agent，负责生产级基础设施的安全部署与维护。 ![GitHub Repo stars](https://img.shields.io/github/stars/stakpak/agent?style=plastic&color=lightgrey&logo=github)
- [RepoAgent](https://github.com/OpenBMB/RepoAgent): 加速仓库文档生成并加深代码库理解的 LLM 助手。 ![GitHub Repo stars](https://img.shields.io/github/stars/OpenBMB/RepoAgent?style=plastic&color=lightgrey&logo=github)
- [MicroAgent](https://github.com/aymenfurter/microagents): 极致轻量，能够自我优化提示词和 Python 代码的智能体。 ![GitHub Repo stars](https://img.shields.io/github/stars/aymenfurter/microagents?style=plastic&color=lightgrey&logo=github)
- [AgentRun](https://github.com/Jonathan-Adly/AgentRun): 在隔离环境中安全、极速运行 AI 生成代码的利器。 ![GitHub Repo stars](https://img.shields.io/github/stars/Jonathan-Adly/AgentRun?style=plastic&color=lightgrey&logo=github)
- [Dorothy](https://github.com/Charlie85270/Dorothy): 通过看板式管理，同时编排并控制多个终端智能体。 ![GitHub Repo stars](https://img.shields.io/github/stars/Charlie85270/Dorothy?style=plastic&color=lightgrey&logo=github)
- [PyCodeAGI](https://github.com/chakkaradeep/pyCodeAGI): 根据自然语言提示词自动生成 Python 应用的实验性 AGI。 ![GitHub Repo stars](https://img.shields.io/github/stars/chakkaradeep/pyCodeAGI?style=plastic&color=lightgrey&logo=github)
- [VibeGrid](https://github.com/jcanizalez/vibegrid): 集成多智能体网格与工作流自动化的终端管理系统。 ![GitHub Repo stars](https://img.shields.io/github/stars/jcanizalez/vibegrid?style=plastic&color=lightgrey&logo=github)
- [Greywall](https://github.com/GreyhavenHQ/greywall): 为编程智能体设计的默认拒绝式安全沙箱，支持文件与网络隔离。 ![GitHub Repo stars](https://img.shields.io/github/stars/GreyhavenHQ/greywall?style=plastic&color=lightgrey&logo=github)
- [ReviewCerberus](https://github.com/Kirill89/reviewcerberus): 专注于安全、性能与代码质量的开源 AI 审查工具。
- [Hivemoot Colony](https://github.com/hivemoot/colony): 去中心化治理平台，由智能体自主协作与发布软件功能。 ![GitHub Repo stars](https://img.shields.io/github/stars/hivemoot/colony?style=plastic&color=lightgrey&logo=github)

## 自动化与工作流

用于任务自动化、工作流编排和通用自主操作的 Agent 与平台，按 GitHub Star 数量排序。

- [Astron](https://github.com/iflytek/astron-agent): 企业级、商业友好的 Agentic 工作流平台，用于构建下一代 SuperAgent。
- [Hive](https://github.com/aden-hive/hive): 开源 AI Agent 框架，用于构建目标驱动、自我改进的自主 Agent。用自然语言定义目标，自动生成 Agent 图，内置进化循环、MCP 集成和 100+ 工具。 ![GitHub Repo stars](https://img.shields.io/github/stars/aden-hive/hive?style=plastic&color=lightgrey&logo=github)
- [XAgent](https://github.com/OpenBMB/XAgent): 用于解决复杂任务的自主 LLM Agent。 ![GitHub Repo stars](https://img.shields.io/github/stars/OpenBMB/XAgent?style=plastic&color=lightgrey&logo=github)
- [llama-agents](https://github.com/run-llama/llama-agents): 异步优先的多智能体系统构建框架，支持多智能体通信、分布式工具执行、人机协作等。 ![GitHub Repo stars](https://img.shields.io/github/stars/run-llama/llama-agents?style=plastic&color=lightgrey&logo=github)
- [DemoGPT](https://github.com/melih-unsal/DemoGPT): 仅通过提示即可快速创建演示，在 LangChain 文档树上应用 ToT 方法。 ![GitHub Repo stars](https://img.shields.io/github/stars/melih-unsal/DemoGPT?style=plastic&color=lightgrey&logo=github)
- [uAgents](https://github.com/fetchai/uAgents): 快速轻量的去中心化 Agent 创建框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/fetchai/uAgents?style=plastic&color=lightgrey&logo=github)
- [ADAS](https://github.com/ShengranHu/ADAS): 自动化 Agentic 系统设计。 ![GitHub Repo stars](https://img.shields.io/github/stars/ShengranHu/ADAS?style=plastic&color=lightgrey&logo=github)
- [RestGPT](https://github.com/Yifan-Song793/RestGPT): 通过 RESTful API 控制现实世界应用的 LLM 自主 Agent。 ![GitHub Repo stars](https://img.shields.io/github/stars/Yifan-Song793/RestGPT?style=plastic&color=lightgrey&logo=github)
- [AgentK](https://github.com/mikekelly/AgentK): 自我进化且模块化的自代理 AGI。 ![GitHub Repo stars](https://img.shields.io/github/stars/mikekelly/AgentK?style=plastic&color=lightgrey&logo=github)
- [Giselle](https://github.com/giselles-ai/giselle): Agentic 工作流构建器，助你轻松创建 AI 驱动的解决方案。 ![Github Repo stars](https://img.shields.io/github/stars/giselles-ai/giselle?style=plastic&color=lightgrey&logo=github)
- [Multi-Modal LangChain agents in Production](https://github.com/steamship-packages/langchain-agent-production-starter): 部署 LangChain Agent 并将其连接到 Telegram。 ![GitHub Repo stars](https://img.shields.io/github/stars/steamship-packages/langchain-agent-production-starter?style=plastic&color=lightgrey&logo=github)
- [Untether](https://github.com/littlebearapps/untether): AI 编程 Agent 的 Telegram 桥接器——支持远程任务控制、进度流式传输、交互式权限、语音输入和成本追踪。支持 Claude Code、Codex、OpenCode、Pi、Gemini CLI 和 Amp。 ![GitHub Repo stars](https://img.shields.io/github/stars/littlebearapps/untether?style=plastic&color=lightgrey&logo=github)

## 研究与分析

专注于研究、科学发现和数据分析的 AI 智能体，按 GitHub Star 数量排序。

- [Storm](https://github.com/stanford-oval/storm): LLM 驱动的知识整理系统，研究一个主题并生成带引用的完整报告。 ![GitHub Repo stars](https://img.shields.io/github/stars/stanford-oval/storm?style=plastic&color=lightgrey&logo=github)
- [GPT Researcher](https://github.com/assafelovic/gpt-researcher): 自主 Agent，针对各类任务进行全面的在线研究。 ![GitHub Repo stars](https://img.shields.io/github/stars/assafelovic/gpt-researcher?style=plastic&color=lightgrey&logo=github)
- [AI Scientist](https://github.com/SakanaAI/AI-Scientist): AI 科学家：迈向完全自动化的开放式科学发现。 ![GitHub Repo stars](https://img.shields.io/github/stars/SakanaAI/AI-Scientist?style=plastic&color=lightgrey&logo=github)
- [DeepAnalyze](https://github.com/ruc-datalab/DeepAnalyze): 首个用于自主数据科学的 Agentic LLM，支持数据准备、分析、建模、可视化和洞察，以及面向数据的深度研究（生成分析师级研究报告）。 [![GitHub Repo stars](https://img.shields.io/github/stars/ruc-datalab/DeepAnalyze?style=plastic&color=lightgrey&logo=github&label=Code+Stars)](https://github.com/ruc-datalab/DeepAnalyze)
- [data-to-paper](https://github.com/Technion-Kishony-lab/data-to-paper): AI 驱动的研究，从数据到人类可验证的研究论文。 ![GitHub Repo stars](https://img.shields.io/github/stars/Technion-Kishony-lab/data-to-paper?style=plastic&color=lightgrey&logo=github)
- [BlockAGI](https://github.com/blockpipe/blockagi): 迭代式、特定领域研究，输出详细的叙述性报告以展示其发现。 ![GitHub Repo stars](https://img.shields.io/github/stars/blockpipe/blockagi?style=plastic&color=lightgrey&logo=github)
- [OpenLens AI](https://github.com/jarrycyx/openlens-ai): 面向健康信息学的完全自主研究 Agent。 ![GitHub Repo stars](https://img.shields.io/github/stars/jarrycyx/openlens-ai?style=plastic&color=lightgrey&logo=github)
- [GenoMAS](https://github.com/Liu-Hy/GenoMAS): 面向科学发现的多智能体框架，通过代码驱动工作流自动化基因表达分析。 ![GitHub Repo stars](https://img.shields.io/github/stars/Liu-Hy/GenoMAS?style=plastic&color=lightgrey&logo=github)

## 对话与个人助理 Agent

面向对话、个人助理和会话场景的 AI 智能体，按 GitHub Star 数量排序。

- [OpenClaw](https://github.com/openclaw/openclaw): 开源 AI Agent 框架，将 LLM 转化为持久、主动的个人 AI 智能体，支持多渠道消息（Signal、Telegram、Discord、WhatsApp）、定时调度、记忆系统、MCP 集成、技能插件、子 Agent 派生和浏览器自动化。 ![GitHub Repo stars](https://img.shields.io/github/stars/openclaw/openclaw?style=plastic&color=lightgrey&logo=github)
- [CollosalAI Chat](https://github.com/hpcaitech/ColossalAI/tree/main/applications/Chat): 用 RLHF 实现 LLM，由 Colossal-AI 项目驱动。 ![GitHub Repo stars](https://img.shields.io/github/stars/hpcaitech/ColossalAI?style=plastic&color=lightgrey&logo=github)
- [nanobot](https://github.com/HKUDS/nanobot): 超轻量级个人 AI 助手框架（约 4,000 行 Python 代码），支持 MCP、9+ 聊天频道和可扩展技能系统。 ![GitHub Repo stars](https://img.shields.io/github/stars/HKUDS/nanobot?style=plastic&color=lightgrey&logo=github)
- [Memgpt](https://github.com/cpacker/memgpt): 创建具有长期记忆和自定义工具的 LLM 智能体。 ![Github Repo stars](https://img.shields.io/github/stars/cpacker/memgpt?style=plastic&color=lightgrey&logo=github)
- [SuperAgent](https://github.com/homanp/superagent): 将 LLM 智能体部署到生产环境。 ![GitHub Repo stars](https://img.shields.io/github/stars/homanp/superagent?style=plastic&color=lightgrey&logo=github)
- [RasaGPT](https://github.com/paulpierre/RasaGPT): 首个基于 Rasa 和 LangChain 构建的无头 LLM 聊天机器人平台。 ![GitHub Repo stars](https://img.shields.io/github/stars/paulpierre/RasaGPT?style=plastic&color=lightgrey&logo=github)
- [Awesome OpenClaw Agents](https://github.com/mergisi/awesome-openclaw-agents): 精选 100+ 个生产就绪的 OpenClaw SOUL.md Agent 模板，涵盖生产力、开发、营销和业务自动化。 ![GitHub Repo stars](https://img.shields.io/github/stars/mergisi/awesome-openclaw-agents?style=plastic&color=lightgrey&logo=github)
- [BabyAGI UI](https://github.com/miurla/babyagi-ui): 更便捷地在 Web 应用中运行和开发 babyagi，类似 ChatGPT。 ![GitHub Repo stars](https://img.shields.io/github/stars/miurla/babyagi-ui?style=plastic&color=lightgrey&logo=github)
- [ix](https://github.com/kreneskyp/ix): 自主 GPT-4 智能体平台。 ![GitHub Repo stars](https://img.shields.io/github/stars/kreneskyp/ix?style=plastic&color=lightgrey&logo=github)
- [LLama Cpp Agent](https://github.com/Maximilian-Winter/llama-cpp-agent): 专为简化与大语言模型交互而设计的工具。 ![GitHub Repo stars](https://img.shields.io/github/stars/Maximilian-Winter/llama-cpp-agent?style=plastic&color=lightgrey&logo=github)
- [Autonomous HR Chatbot](https://github.com/stepanogil/autonomous-hr-chatbot): 自主解答 HR 相关问题的 Agent，利用其手头的工具。 ![GitHub Repo stars](https://img.shields.io/github/stars/stepanogil/autonomous-hr-chatbot?style=plastic&color=lightgrey&logo=github)
- [ClaudeClaw](https://github.com/sbusso/claudeclaw): Claude Code 的持久化 Agent 编排插件——多渠道路由（Slack、WhatsApp、Telegram）、OS 级沙箱隔离、可组合扩展、结构化记忆、Webhook 触发器。 ![GitHub Repo stars](https://img.shields.io/github/stars/sbusso/claudeclaw?style=plastic&color=lightgrey&logo=github)

## 知识管理与 RAG

用于文档检索、私有知识库和 RAG 管道的智能体与工具，按 GitHub Star 数量排序。

- [Private GPT](https://github.com/imartinez/privateGPT): 利用 GPT 的强大功能与文档私密交互，100% 私密，零数据泄露。 ![GitHub Repo stars](https://img.shields.io/github/stars/imartinez/privateGPT?style=plastic&color=lightgrey&logo=github)
- [Local GPT](https://github.com/PromtEngineer/localGPT): 受 Private GPT 启发，用 GPT4ALL 模型替换 Vicuna-7B，使用 InstructorEmbeddings 代替 LlamaEmbeddings。 ![GitHub Repo stars](https://img.shields.io/github/stars/PromtEngineer/localGPT?style=plastic&color=lightgrey&logo=github)
- [DB GPT](https://github.com/csunny/DB-GPT): 使用本地 GPT 与数据和环境交互，零数据泄露，100% 私密，100% 安全。 ![GitHub Repo stars](https://img.shields.io/github/stars/csunny/DB-GPT?style=plastic&color=lightgrey&logo=github)
- [LLocalSearch](https://github.com/nilsherzig/LLocalSearch): 完全本地运行的 LLM Agent 搜索聚合器。用户提问，系统使用 LLM 链找到答案。无需 OpenAI 或 Google API 密钥。 ![GitHub Repo stars](https://img.shields.io/github/stars/nilsherzig/LLocalSearch?style=plastic&color=lightgrey&logo=github)
- [Agentset](https://github.com/agentset-ai/agentset): 开源生产就绪的 RAG 平台，内置 Agentic 推理、混合搜索和多模态支持。 ![GitHub Repo stars](https://img.shields.io/github/stars/agentset-ai/agentset?style=plastic&color=lightgrey&logo=github)
- [Second Brain AI Agent](https://github.com/flepied/second-brain-agent): 使用 OpenAI 和 ChromaDB 本地对话笔记的 Streamlit 应用。 ![GitHub Repo stars](https://img.shields.io/github/stars/flepied/second-brain-agent?style=plastic&color=lightgrey&logo=github)
- [Cortex Memory](https://github.com/sopaco/cortex-mem): 智能体记忆的完整解决方案，涵盖提取、向量搜索到自动优化，开箱即用提供 REST API、MCP、CLI 和洞察仪表板。
- [SAGE](https://github.com/l33tdawg/sage): AI 智能体的机构记忆——每条记忆在提交前都经过 BFT 共识。4 个应用验证器、13 个 MCP 工具，本地运行。 ![GitHub Repo stars](https://img.shields.io/github/stars/l33tdawg/sage?style=plastic&color=lightgrey&logo=github)

## 浏览器与 Web Agent

用于浏览器自动化和 Web 交互的 Agent 与基础设施，按 GitHub Star 数量排序。

- [AgentGPT](https://github.com/reworkd/AgentGPT): 使用 LangChain 和 OpenAI 构建的 AI 智能体（Vercel / Nextjs）。 ![GitHub Repo stars](https://img.shields.io/github/stars/reworkd/AgentGPT?style=plastic&color=lightgrey&logo=github)
- [Steel Browser](https://github.com/steel-dev/steel-browser): AI 智能体的开源浏览器基础设施，支持会话自动化、提取、截图/PDF、AI 原生 CLI 和可复用的 steel-browser 技能。 ![GitHub Repo stars](https://img.shields.io/github/stars/steel-dev/steel-browser?style=plastic&color=lightgrey&logo=github)
- [OpenAgents](https://github.com/xlang-ai/OpenAgents): 现实世界中语言智能体的开放平台。 ![GitHub Repo stars](https://img.shields.io/github/stars/xlang-ai/OpenAgents?style=plastic&color=lightgrey&logo=github)
- [Gobii](https://github.com/gobii-ai/gobii-platform): 开源平台，以对话界面和 API 大规模部署和管理浏览器使用 Agent。 ![GitHub Repo stars](https://img.shields.io/github/stars/gobii-ai/gobii-platform?style=plastic&color=lightgrey&logo=github)

## 语音与多模态

用于语音、音频和多模态交互的 Agent 与框架，按 GitHub Star 数量排序。

- [Pipecat](https://github.com/pipecat-ai/pipecat): 开源的语音和多模态对话 AI 框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/pipecat-ai/pipecat?style=plastic&color=lightgrey&logo=github)
- [joinly](https://github.com/joinly-ai/joinly): 语音优先的在线会议 AI 助手，可主动参与会议并实时解决任务。 ![GitHub Repo stars](https://img.shields.io/github/stars/joinly-ai/joinly?style=plastic&color=lightgrey&logo=github)

## 测试与评估

用于测试、评估和观测 AI 智能体的框架与工具，按 GitHub Star 数量排序。

- [Arize-Phoenix](https://github.com/Arize-ai/phoenix): 开源的 Agent 测试、评估和可观测性库。 ![GitHub Repo stars](https://img.shields.io/github/stars/Arize-ai/phoenix?style=plastic&color=lightgrey&logo=github)
- [Manifest](https://github.com/mnfst/manifest): AI 智能体的开源实时成本可观测平台。追踪 Token、成本、消息和模型使用情况，提供本地优先仪表板。支持 28+ LLM 模型、OTLP 摄入、自托管。 ![GitHub Repo stars](https://img.shields.io/github/stars/mnfst/manifest?style=plastic&color=lightgrey&logo=github)
- [EvoAgentX](https://github.com/EvoAgentX/EvoAgentX): 构建自我进化的 AI 智能体生态系统，提供自动化评估和进化 Agentic 工作流的框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/EvoAgentX/EvoAgentX?style=plastic&color=lightgrey&logo=github)
- [Open-RAG-Eval](https://github.com/vectara/open-rag-eval): 开源 RAG 评估框架，无需标准答案，可用于评估连接到 AI Agent 的 RAG 工具性能（Agentic RAG）。
- [Voice Lab](https://github.com/saharmor/voice-lab): 全面的语音 Agent 测试和评估框架，支持跨语言模型、提示词和 Agent 角色的评估。 ![GitHub Repo stars](https://img.shields.io/github/stars/saharmor/voice-lab?style=plastic&color=lightgrey&logo=github)
- [voicetest](https://github.com/voicetestdev/voicetest): 语音 Agent 的开源测试工具，支持 Retell、VAPI、Bland 和 LiveKit。运行自主模拟并使用 LLM 评判器评估。 ![GitHub Repo stars](https://img.shields.io/github/stars/voicetestdev/voicetest?style=plastic&color=lightgrey&logo=github)

## 基础设施与安全

用于智能体部署、沙箱隔离和安全防护的平台与工具，按 GitHub Star 数量排序。

- [e2b](https://github.com/e2b-dev/e2b): 构建和部署虚拟开发者 Agent 的开源平台。
- [AgentField](https://github.com/Agent-Field/agentfield): AI 后端的开源基础设施。Kubernetes 用于编排，Okta 用于身份管理——从第一天起就生产就绪。 ![GitHub Repo stars](https://img.shields.io/github/stars/Agent-Field/agentfield?style=plastic&color=lightgrey&logo=github)

## 游戏与模拟

面向游戏、仿真模拟和人类行为建模的 AI 智能体，按 GitHub Star 数量排序。

- [Voyager](https://github.com/MineDojo/Voyager): 基于大语言模型的开放式具身 Agent。 ![GitHub Repo stars](https://img.shields.io/github/stars/MineDojo/Voyager?style=plastic&color=lightgrey&logo=github)
- [Camel-AutoGPT](https://github.com/SamurAIGPT/Camel-AutoGPT): LLM 和自主 Agent（如 BabyAGI 和 AutoGPT）的角色扮演方法。 ![GitHub Repo stars](https://img.shields.io/github/stars/SamurAIGPT/Camel-AutoGPT?style=plastic&color=lightgrey&logo=github)
- [SkyAGI](https://github.com/litanlitudan/skyagi): LLM 智能体中涌现的人类行为模拟能力。 ![GitHub Repo stars](https://img.shields.io/github/stars/litanlitudan/skyagi?style=plastic&color=lightgrey&logo=github)
