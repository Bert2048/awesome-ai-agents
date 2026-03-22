# 🤖 Awesome AI Agents 🤖

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**語言：** [English](README.md) | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md) | [Français](README.fr.md)

精選開源框架、工具與專案合集，涵蓋 AI Agent 構建所需的一切資源。包括 Agent 編排、工具調用、多智能體協作、RAG、瀏覽器自動化、語音介面等——探索並構建智能體生態系統的完整指南。

## 目錄

- [🤖 Awesome AI Agents 🤖](#-awesome-ai-agents-)
  - [目錄](#目錄)
  - [框架與 SDK](#框架與-sdk)
  - [大型語言模型與模型工具](#大型語言模型與模型工具)
  - [提示詞與技能庫](#提示詞與技能庫)
  - [編程與開發 Agent](#編程與開發-agent)
  - [自動化與工作流](#自動化與工作流)
  - [研究與分析](#研究與分析)
  - [對話與個人助理 Agent](#對話與個人助理-agent)
  - [知識管理與 RAG](#知識管理與-rag)
  - [瀏覽器與 Web Agent](#瀏覽器與-web-agent)
  - [語音與多模態](#語音與多模態)
  - [測試與評估](#測試與評估)
  - [基礎設施與安全](#基礎設施與安全)
  - [遊戲與模擬](#遊戲與模擬)

## 框架與 SDK

構建 AI 智能體的通用框架與 SDK，按 GitHub Star 數量排序。

- [LangChain](https://github.com/hwchase17/langchain): 構建開發由語言模型驅動的應用程序的框架。![GitHub Repo stars](https://img.shields.io/github/stars/hwchase17/langchain?style=flat&color=lightgrey&logo=github)
- [Autogen](https://github.com/microsoft/autogen): 支援下一代大型語言模型應用開發。 ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/autogen?style=flat&color=lightgrey&logo=github)
- [LlamaIndex](https://github.com/jerryjliu/llama_index): 為 LLM 提供與外部資料連接的核心介面。 ![GitHub Repo stars](https://img.shields.io/github/stars/jerryjliu/llama_index?style=flat&color=lightgrey&logo=github)
- [CrewAI](https://github.com/joaomdmoura/crewai): 前沿的角色扮演自主 AI 智能體編排框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/joaomdmoura/crewai?style=flat&color=lightgrey&logo=github)
- [Phidata](https://github.com/phidatahq/phidata): 構建具備記憶、知識和工具的 AI 助手。 ![GitHub Repo stars](https://img.shields.io/github/stars/phidatahq/phidata?style=flat&color=lightgrey&logo=github)
- [DSPy](https://github.com/stanfordnlp/dspy): 用於編程（而非提示）基礎模型的框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/stanfordnlp/dspy?style=flat&color=lightgrey&logo=github)
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel): 微軟 C# SDK，快速輕鬆地將前沿 LLM 技術整合到應用中。 ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/semantic-kernel?style=flat&color=lightgrey&logo=github)
- [Haystack](https://github.com/deepset-ai/haystack): 使用 Transformer 模型和 LLM 與資料互動的 NLP 框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/deepset-ai/haystack?style=flat&color=lightgrey&logo=github)
- [Mastra](https://github.com/mastra-ai/mastra): 有主見的 TypeScript 框架，幫助你快速構建 AI 應用和功能。 ![GitHub Repo stars](https://img.shields.io/github/stars/mastra-ai/mastra?style=flat&color=lightgrey&logo=github)
- [Swarm](https://github.com/openai/swarm): OpenAI 出品的輕量級多智能體編排教育框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/openai/swarm?style=flat&color=lightgrey&logo=github)
- [AgentScope](https://github.com/modelscope/agentscope): 更便捷地構建 LLM 驅動的多智能體應用。 ![GitHub Repo stars](https://img.shields.io/github/stars/modelscope/agentscope?style=flat&color=lightgrey&logo=github)
- [Botpress](https://github.com/botpress/botpress): 構建聊天機器人的基礎模組。 ![GitHub Repo stars](https://img.shields.io/github/stars/botpress/botpress?style=flat&color=lightgrey&logo=github)
- [Upsonic](https://github.com/upsonic/upsonic): 支援 MCP 的可靠 Agent 框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/upsonic/upsonic?style=flat&color=lightgrey&logo=github)
- [VoltAgent](https://github.com/VoltAgent/voltagent): 開源 TypeScript Agent 框架，內建 LLM 可觀測性。 ![GitHub Repo stars](https://img.shields.io/github/stars/voltagent/voltagent?style=flat&color=lightgrey&logo=github)
- [Swarms Framework](https://github.com/kyegomez/swarms): 面向企業應用的前沿多智能體編排框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/kyegomez/swarms?style=flat&color=lightgrey&logo=github)
- [PraisonAI](https://github.com/MervinPraison/PraisonAI): 生產就緒的多 AI 智能體框架，支援自我反思。最快的 Agent 實例化速度（3.77μs），支援 100+ LLM、MCP、工作流、記憶，提供 Python 和 JavaScript SDK。 ![GitHub Repo stars](https://img.shields.io/github/stars/MervinPraison/PraisonAI?style=flat&color=lightgrey&logo=github)
- [Strands Agents SDK](https://github.com/strands-agents/sdk-python): 通過模型驅動的方式，僅需幾行程式碼即可構建 AI 智能體。 ![GitHub Repo stars](https://img.shields.io/github/stars/strands-agents/sdk-python?style=flat&color=lightgrey&logo=github)
- [AgentVerse](https://github.com/openbmb/agentverse): 靈活的框架，簡化為 LLM 構建自定義多智能體環境的流程。 ![GitHub Repo stars](https://img.shields.io/github/stars/openbmb/agentverse?style=flat&color=lightgrey&logo=github)
- [Maestro](https://github.com/Doriandarko/maestro): Claude Opus 智能編排子智能體的框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/Doriandarko/maestro?style=flat&color=lightgrey&logo=github)
- [llama-agentic-system](https://github.com/meta-llama/llama-agentic-system): Llama Stack APIs 的 Agent 組件。 ![GitHub Repo stars](https://img.shields.io/github/stars/meta-llama/llama-agentic-system?style=flat&color=lightgrey&logo=github)
- [AG2](https://github.com/ag2ai/ag2): AutoGen 原創團隊打造的開源 AI 智能體編程框架，支援多智能體協作。 ![GitHub Repo stars](https://img.shields.io/github/stars/ag2ai/ag2?style=flat&color=lightgrey&logo=github)
- [agency-swarm](https://github.com/VRSEN/agency-swarm): 基於最新 OpenAI Assistants API 構建的可靠 Agent 框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/VRSEN/agency-swarm?style=flat&color=lightgrey&logo=github)
- [Agent-LLM](https://github.com/Josh-XT/Agent-LLM): 人工智能自動化平台。 ![GitHub Repo stars](https://img.shields.io/github/stars/Josh-XT/Agent-LLM?style=flat&color=lightgrey&logo=github)
- [Lagent](https://github.com/InternLM/lagent): 輕量級 LLM 智能體構建框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/InternLM/lagent?style=flat&color=lightgrey&logo=github)
- [Agentic Context Engine](https://github.com/kayba-ai/agentic-context-engine): 自我改進的 Agent，從執行反饋中學習。整合 LangChain，支援 Agent 自主管理上下文。 ![GitHub Repo stars](https://img.shields.io/github/stars/kayba-ai/agentic-context-engine?style=flat&color=lightgrey&logo=github)
- [AgentDock](https://github.com/AgentDock/AgentDock): 擺脫繁瑣的 API 整合，AgentDock 提供開源基礎，可無摩擦地構建、管理和部署生產級 AI 智能體與工作流。 ![GitHub Repo stars](https://img.shields.io/github/stars/agentdock/agentdock?style=flat&color=lightgrey&logo=github)
- [Dust](https://github.com/dust-tt/dust): 設計並部署大型語言模型應用。 ![GitHub Repo stars](https://img.shields.io/github/stars/dust-tt/dust?style=flat&color=lightgrey&logo=github)
- [LLM Agents](https://github.com/mpaepper/llm_agents): 構建由 LLM 控制的智能體。 ![GitHub Repo stars](https://img.shields.io/github/stars/mpaepper/llm_agents?style=flat&color=lightgrey&logo=github)
- [ConnectOnion](https://github.com/openonion/connectonion): 面向生產環境的簡潔 Python 框架——兩行程式碼創建 Agent、函數即工具、12 個生命週期鉤子、插件系統、支援信任機制的多智能體網路。 ![GitHub Repo stars](https://img.shields.io/github/stars/openonion/connectonion?style=flat&color=lightgrey&logo=github)
- [Agency](https://github.com/neurocult/agency): 🕵️‍♂️ 為熱衷探索 LLM 潛力的開發者設計的庫，採用簡潔、高效、Go 風格的實作方式。 ![GitHub Repo stars](https://img.shields.io/github/stars/neurocult/agency?style=flat&color=lightgrey&logo=github)
- [Modus](https://github.com/hypermodeinc/modus): 用 Go 或 AssemblyScript 構建智能 Agent 和 API 的開源無服務器框架。
- [LoongFlow](https://github.com/baidu-baige/LoongFlow): 進化式 Agent 開發框架，從原子組件到核心場景 Agent 全覆蓋。 ![GitHub Repo stars](https://img.shields.io/github/stars/baidu-baige/LoongFlow?style=flat&color=lightgrey&logo=github)
- [AgentFlow](https://github.com/simonmesmith/agentflow): 通過簡單 JSON 定義複雜 LLM 工作流。 ![GitHub Repo stars](https://img.shields.io/github/stars/simonmesmith/agentflow?style=flat&color=lightgrey&logo=github)
- [FIM Agent](https://github.com/fim-ai/fim-agent): AI 驅動的連接器中樞——支援動態 DAG 規劃、ReAct Agent、MCP 客戶端、有依據的 RAG 生成，以及將任意 API 轉化為 Agent 工具的連接器平台。 ![GitHub Repo stars](https://img.shields.io/github/stars/fim-ai/fim-agent?style=flat&color=lightgrey&logo=github)
- [hcom](https://github.com/aannoo/hcom): 讓 AI 智能體跨終端互發消息、互相監控和派生。支援 Claude Code、Gemini CLI、Codex、OpenCode。 ![GitHub Repo stars](https://img.shields.io/github/stars/aannoo/hcom?style=flat&color=lightgrey&logo=github)
- [Ailoy](https://github.com/brekkylab/ailoy): 全面的 AI Agent 構建框架，支援隨處運行，完全支援本地 AI 和 WASM。
- [NeuroLink](https://github.com/juspay/neurolink): TypeScript Agent 框架，支援多步驟 Agent 循環、逐步工具執行控制（`prepareStep`）、持久記憶（Redis/S3/SQLite）、HITL 工作流、MCP 客戶端整合和 13 個 LLM 提供商。 ![GitHub Repo stars](https://img.shields.io/github/stars/juspay/neurolink?style=flat&color=lightgrey&logo=github)
- [Vectara-agentic](https://github.com/vectara/py-vectara-agentic): 使用 Vectara 創建 AI 助手和智能體的框架。
- [AgentUp](https://github.com/RedDotRocket/AgentUp): 以安全、可擴展性和可延展性為基礎設計，通過配置驅動架構和豐富的插件生態加速開發。 ![GitHub Repo stars](https://img.shields.io/github/stars/RedDotRocket/AgentUp?style=flat&color=lightgrey&logo=github)
- [Pilot Protocol](https://github.com/TeoSlayer/pilotprotocol): 為 AI 智能體提供虛擬地址、加密 UDP 隧道、NAT 穿越和互信機制的叠加網路棧。零依賴，Go 語言編寫。 ![GitHub Repo stars](https://img.shields.io/github/stars/TeoSlayer/pilotprotocol?style=flat&color=lightgrey&logo=github)
- [Portia AI](https://github.com/portiaAI/portia-sdk-python/): 全新開源 Python Agentic 框架，專為生產環境中的可靠 Agent 設計。 ![GitHub Repo stars](https://img.shields.io/github/stars/portiaAI/portia-sdk-python?style=flat&color=lightgrey&logo=github)
- [Transformers Agents](https://huggingface.co/docs/transformers/transformers_agents): 在 Transformers 之上提供自然語言 API。

## 大型語言模型與模型工具

構建 AI 智能體的核心驅動力：大型語言模型、服務提供商和本地推理平台。

- [Claude](https://claude.ai/): Anthropic 出品的高效能 AI 助手，搭載 Claude 3.5 系列模型。
- [Gemini](https://gemini.google.com/): Google 統一 AI 平台，提供多模態模型套件。
- [ChatGPT](https://chatgpt.com/): OpenAI 基於 GPT 系列的對話 AI。
- [DeepSeek](https://www.deepseek.com/): 領先的中國 AI 實驗室，擁有 DeepSeek-R1、DeepSeek-V3 等強大開源模型。
- [Ollama](https://github.com/ollama/ollama): 在 macOS、Linux 和 Windows 本地運行開源 LLM（Llama 3、Mistral、Gemma）的最簡方式。 ![GitHub Repo stars](https://img.shields.io/github/stars/ollama/ollama?style=flat&color=lightgrey&logo=github)
- [Hugging Face](https://huggingface.co/): 機器學習社群分享和下載模型、資料集和應用的核心樞紐。
- [ModelScope](https://modelscope.cn/): 阿里雲出品的下一代開源 AI 模型與資料集協同平台。
- [LM Studio](https://lmstudio.ai/): 功能完整的桌面應用，用於發現、下載和運行本地 LLM。

## 提示詞與技能庫

提示工程指南、結構化生成工具、MCP 技能伺服器及 LLM 實用工具庫，按 GitHub Star 數量排序。

- [Awesome ChatGPT Prompts](https://github.com/f/awesome-chatgpt-prompts): 大規模社群精選的 ChatGPT 提示詞模板合集，涵蓋數百種角色扮演和任務場景。 ![GitHub Repo stars](https://img.shields.io/github/stars/f/awesome-chatgpt-prompts?style=flat&color=lightgrey&logo=github)
- [MCP Servers](https://github.com/modelcontextprotocol/servers): MCP 官方參考伺服器合集，讓智能體能連接檔案系統、資料庫、API 及外部服務。 ![GitHub Repo stars](https://img.shields.io/github/stars/modelcontextprotocol/servers?style=flat&color=lightgrey&logo=github)
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook): OpenAI API 的官方範例程式碼與指南，涵蓋 RAG、微調、函數呼叫及生產部署模式。 ![GitHub Repo stars](https://img.shields.io/github/stars/openai/openai-cookbook?style=flat&color=lightgrey&logo=github)
- [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide): 全面的提示工程技巧指南，涵蓋思維鏈、少樣本學習、RAG 等高級提示策略。 ![GitHub Repo stars](https://img.shields.io/github/stars/dair-ai/Prompt-Engineering-Guide?style=flat&color=lightgrey&logo=github)
- [LiteLLM](https://github.com/BerriAI/litellm): 統一 100+ LLM 提供商的 API 閘道，提供 OpenAI 相容介面、負載平衡和成本追蹤。 ![GitHub Repo stars](https://img.shields.io/github/stars/BerriAI/litellm?style=flat&color=lightgrey&logo=github)
- [Anthropic Cookbook](https://github.com/anthropics/anthropic-cookbook): 使用 Claude 建構應用的官方程式碼範例與指南，包含智能體模式、工具調用和多模態工作流。 ![GitHub Repo stars](https://img.shields.io/github/stars/anthropics/anthropic-cookbook?style=flat&color=lightgrey&logo=github)
- [Guidance](https://github.com/guidance-ai/guidance): 一種結構化提示語言，用於精確控制 LLM 的輸出格式、約束條件和生成流程。 ![GitHub Repo stars](https://img.shields.io/github/stars/guidance-ai/guidance?style=flat&color=lightgrey&logo=github)
- [Promptfoo](https://github.com/promptfoo/promptfoo): 開源的 LLM 提示詞與智能體測試、評估和紅隊工具，支援多模型對比。 ![GitHub Repo stars](https://img.shields.io/github/stars/promptfoo/promptfoo?style=flat&color=lightgrey&logo=github)
- [Outlines](https://github.com/outlines-dev/outlines): 透過 JSON Schema 和正則約束實現可靠結構化文字生成的框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/outlines-dev/outlines?style=flat&color=lightgrey&logo=github)
- [Instructor](https://github.com/jxnl/instructor): 基於 Pydantic 的 Python 函式庫，用於從多家 LLM 提供商獲取結構化、經過驗證的輸出。 ![GitHub Repo stars](https://img.shields.io/github/stars/jxnl/instructor?style=flat&color=lightgrey&logo=github)
- [Promptflow](https://github.com/microsoft/promptflow): 微軟出品的 LLM 流程建構、測試、評估與生產發布一體化工具套件。 ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/promptflow?style=flat&color=lightgrey&logo=github)
- [Brex's Prompt Engineering Guide](https://github.com/brexhq/prompt-engineering): Brex 工程團隊出品的面向生產環境的 LLM 實用提示工程指南。 ![GitHub Repo stars](https://img.shields.io/github/stars/brexhq/prompt-engineering?style=flat&color=lightgrey&logo=github)

## 編程與開發 Agent

專注於軟體開發、程式碼生成和 DevOps 的 AI 智能體與工具，按 GitHub Star 數量排序。

- [OpenCode](https://github.com/sst/opencode): 專為終端打造的 AI 編程 Agent。 ![GitHub Repo stars](https://img.shields.io/github/stars/sst/opencode?style=flat&color=lightgrey&logo=github)
- [OpenHands](https://github.com/All-Hands-AI/OpenHands): 🙌 少寫程式碼，多做事。（前身為 OpenDevin）AI 驅動的軟體開發 Agent 平台。 ![GitHub Repo stars](https://img.shields.io/github/stars/All-Hands-AI/OpenHands?style=flat&color=lightgrey&logo=github)
- [MetaGPT](https://github.com/geekan/MetaGPT): 多智能體框架：首個 AI 軟體公司，邁向自然語言程式設計。 ![GitHub Repo stars](https://img.shields.io/github/stars/geekan/MetaGPT?style=flat&color=lightgrey&logo=github)
- [Cline](https://github.com/cline/cline): 開源 AI 編程 Agent，讓開發者直接透明地存取前沿模型。 ![GitHub Repo stars](https://img.shields.io/github/stars/cline/cline?style=flat&color=lightgrey&logo=github)
- [Aider](https://github.com/Aider-AI/aider): 終端中的 AI 結對程式設計工具。 ![GitHub Repo stars](https://img.shields.io/github/stars/Aider-AI/aider?style=flat&color=lightgrey&logo=github)
- [GPT Pilot](https://github.com/Pythagora-io/gpt-pilot): Pythagora VS Code 擴充功能的核心技術，致力於打造首個真正的 AI 開發者伴侶。 ![GitHub Repo stars](https://img.shields.io/github/stars/Pythagora-io/gpt-pilot?style=flat&color=lightgrey&logo=github)
- [Devika](https://github.com/stitionai/devika): 能理解高層指令、分解步驟、研究資訊並編寫程式碼的 Agentic AI 軟體工程師。 ![GitHub Repo stars](https://img.shields.io/github/stars/stitionai/devika?style=flat&color=lightgrey&logo=github)
- [SWE Agent](https://github.com/princeton-nlp/swe-agent): 自動抓取 GitHub Issue 並嘗試使用 GPT-4 或你選擇的語言模型修復它。 ![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/swe-agent?style=flat&color=lightgrey&logo=github)
- [SuperAGI](https://github.com/TransformerOptimus/SuperAGI): 面向開發者的開源自主 AI Agent 框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/TransformerOptimus/SuperAGI?style=flat&color=lightgrey&logo=github)
- [Plandex](https://github.com/plandex-ai/plandex): 面向複雜任務的 AI 編程引擎。 ![GitHub Repo stars](https://img.shields.io/github/stars/plandex-ai/plandex?style=flat&color=lightgrey&logo=github)
- [Claude Engineer](https://github.com/Doriandarko/claude-engineer): 互動式命令列工具，利用 Claude-3.5-Sonnet 協助軟體開發任務。
- [TaskWeaver](https://github.com/microsoft/TaskWeaver): 無縫規劃和執行資料分析任務的程式碼優先 Agent 框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/TaskWeaver?style=flat&color=lightgrey&logo=github)
- [Vision agent](https://github.com/landing-ai/vision-agent): 幫助利用 Agent 框架生成程式碼解決視覺任務的庫。 ![GitHub Repo stars](https://img.shields.io/github/stars/landing-ai/vision-agent?style=flat&color=lightgrey&logo=github)
- [Codel](https://github.com/semanser/codel): ✨ 完全自主的 AI Agent，可使用終端、瀏覽器和編輯器完成複雜任務。 ![GitHub Repo stars](https://img.shields.io/github/stars/semanser/codel?style=flat&color=lightgrey&logo=github)
- [ThinkGPT](https://github.com/alaeddine-13/thinkgpt): 增強 LLM 並突破其極限的 Agent 技術。 ![GitHub Repo stars](https://img.shields.io/github/stars/alaeddine-13/thinkgpt?style=flat&color=lightgrey&logo=github)
- [Nous](https://github.com/TrafficGuard/nous): TypeScript AI Agent 平台，包含自主 Agent、軟體開發 Agent、AI 程式碼審查 Agent 等。 ![GitHub Repo stars](https://img.shields.io/github/stars/TrafficGuard/nous?style=flat&color=lightgrey&logo=github)
- [Stakpak](https://github.com/stakpak/agent): 開源 DevOps Agent，幫助保護、部署和維護生產就緒的基礎設施。 ![GitHub Repo stars](https://img.shields.io/github/stars/stakpak/agent?style=flat&color=lightgrey&logo=github)
- [RepoAgent](https://github.com/OpenBMB/RepoAgent): LLM 驅動的倉庫 Agent，幫助開發者和團隊快速生成文件、理解程式碼庫。 ![GitHub Repo stars](https://img.shields.io/github/stars/OpenBMB/RepoAgent?style=flat&color=lightgrey&logo=github)
- [MicroAgent](https://github.com/aymenfurter/microagents): 能夠自我編輯提示詞和 Python 程式碼的 Agent。 ![GitHub Repo stars](https://img.shields.io/github/stars/aymenfurter/microagents?style=flat&color=lightgrey&logo=github)
- [AgentRun](https://github.com/Jonathan-Adly/AgentRun): 最簡單、最快速地安全運行 AI 生成的 Python 程式碼。 ![GitHub Repo stars](https://img.shields.io/github/stars/Jonathan-Adly/AgentRun?style=flat&color=lightgrey&logo=github)
- [Dorothy](https://github.com/Charlie85270/Dorothy): 開源桌面應用，同時編排多個 AI CLI Agent（Claude Code、Codex、Gemini），支援自動化、看板管理、遠端控制和 MCP 伺服器。 ![GitHub Repo stars](https://img.shields.io/github/stars/Charlie85270/Dorothy?style=flat&color=lightgrey&logo=github)
- [PyCodeAGI](https://github.com/chakkaradeep/pyCodeAGI): 根據用戶需求生成 Python 應用的小型 AGI 實驗。 ![GitHub Repo stars](https://img.shields.io/github/stars/chakkaradeep/pyCodeAGI?style=flat&color=lightgrey&logo=github)
- [VibeGrid](https://github.com/jcanizalez/vibegrid): AI 編程 Agent 終端管理器，支援多 Agent 網格、任務佇列、工作流自動化、無頭執行、內聯差異審查和 Claude Code 鉤子。 ![GitHub Repo stars](https://img.shields.io/github/stars/jcanizalez/vibegrid?style=flat&color=lightgrey&logo=github)
- [Greywall](https://github.com/GreyhavenHQ/greywall): AI 編程 Agent 的默認拒絕命令沙箱，支援文件系統隔離、透明代理網路控制、內建 Agent 配置文件和自動生成配置的學習模式。 ![GitHub Repo stars](https://img.shields.io/github/stars/GreyhavenHQ/greywall?style=flat&color=lightgrey&logo=github)
- [ReviewCerberus](https://github.com/Kirill89/reviewcerberus): 100% 免費的開源 AI 程式碼審查工具，分析 git 分支差異，提供全面的安全、性能和品質分析。
- [Hivemoot Colony](https://github.com/hivemoot/colony): 自主 Agent 治理平台，AI 智能體對功能進行投票、程式碼審查並發布版本，無需人工干預。附帶即時治理儀表板。 ![GitHub Repo stars](https://img.shields.io/github/stars/hivemoot/colony?style=flat&color=lightgrey&logo=github)

## 自動化與工作流

用於任務自動化、工作流編排和通用自主操作的 Agent 與平台，按 GitHub Star 數量排序。

- [Astron](https://github.com/iflytek/astron-agent): 企業級、商業友好的 Agentic 工作流平台，用於構建下一代 SuperAgent。
- [Hive](https://github.com/aden-hive/hive): 開源 AI Agent 框架，用於構建目標驅動、自我改進的自主 Agent。用自然語言定義目標，自動生成 Agent 圖，內建進化循環、MCP 整合和 100+ 工具。 ![GitHub Repo stars](https://img.shields.io/github/stars/aden-hive/hive?style=flat&color=lightgrey&logo=github)
- [XAgent](https://github.com/OpenBMB/XAgent): 用於解決複雜任務的自主 LLM Agent。 ![GitHub Repo stars](https://img.shields.io/github/stars/OpenBMB/XAgent?style=flat&color=lightgrey&logo=github)
- [llama-agents](https://github.com/run-llama/llama-agents): 非同步優先的多智能體系統構建框架，支援多智能體通訊、分布式工具執行、人機協作等。 ![GitHub Repo stars](https://img.shields.io/github/stars/run-llama/llama-agents?style=flat&color=lightgrey&logo=github)
- [DemoGPT](https://github.com/melih-unsal/DemoGPT): 僅通過提示即可快速創建演示，在 LangChain 文件樹上應用 ToT 方法。 ![GitHub Repo stars](https://img.shields.io/github/stars/melih-unsal/DemoGPT?style=flat&color=lightgrey&logo=github)
- [uAgents](https://github.com/fetchai/uAgents): 快速輕量的去中心化 Agent 創建框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/fetchai/uAgents?style=flat&color=lightgrey&logo=github)
- [ADAS](https://github.com/ShengranHu/ADAS): 自動化 Agentic 系統設計。 ![GitHub Repo stars](https://img.shields.io/github/stars/ShengranHu/ADAS?style=flat&color=lightgrey&logo=github)
- [RestGPT](https://github.com/Yifan-Song793/RestGPT): 通過 RESTful API 控制現實世界應用的 LLM 自主 Agent。 ![GitHub Repo stars](https://img.shields.io/github/stars/Yifan-Song793/RestGPT?style=flat&color=lightgrey&logo=github)
- [AgentK](https://github.com/mikekelly/AgentK): 自我進化且模組化的自代理 AGI。 ![GitHub Repo stars](https://img.shields.io/github/stars/mikekelly/AgentK?style=flat&color=lightgrey&logo=github)
- [Giselle](https://github.com/giselles-ai/giselle): Agentic 工作流構建器，助你輕鬆創建 AI 驅動的解決方案。 ![Github Repo stars](https://img.shields.io/github/stars/giselles-ai/giselle?style=flat&color=lightgrey&logo=github)
- [Multi-Modal LangChain agents in Production](https://github.com/steamship-packages/langchain-agent-production-starter): 部署 LangChain Agent 並將其連接到 Telegram。 ![GitHub Repo stars](https://img.shields.io/github/stars/steamship-packages/langchain-agent-production-starter?style=flat&color=lightgrey&logo=github)
- [Untether](https://github.com/littlebearapps/untether): AI 編程 Agent 的 Telegram 橋接器——支援遠端任務控制、進度串流傳輸、互動式權限、語音輸入和成本追蹤。支援 Claude Code、Codex、OpenCode、Pi、Gemini CLI 和 Amp。 ![GitHub Repo stars](https://img.shields.io/github/stars/littlebearapps/untether?style=flat&color=lightgrey&logo=github)

## 研究與分析

專注於研究、科學發現和資料分析的 AI 智能體，按 GitHub Star 數量排序。

- [Storm](https://github.com/stanford-oval/storm): LLM 驅動的知識整理系統，研究一個主題並生成帶引用的完整報告。 ![GitHub Repo stars](https://img.shields.io/github/stars/stanford-oval/storm?style=flat&color=lightgrey&logo=github)
- [GPT Researcher](https://github.com/assafelovic/gpt-researcher): 自主 Agent，針對各類任務進行全面的線上研究。 ![GitHub Repo stars](https://img.shields.io/github/stars/assafelovic/gpt-researcher?style=flat&color=lightgrey&logo=github)
- [AI Scientist](https://github.com/SakanaAI/AI-Scientist): AI 科學家：邁向完全自動化的開放式科學發現。 ![GitHub Repo stars](https://img.shields.io/github/stars/SakanaAI/AI-Scientist?style=flat&color=lightgrey&logo=github)
- [DeepAnalyze](https://github.com/ruc-datalab/DeepAnalyze): 首個用於自主資料科學的 Agentic LLM，支援資料準備、分析、建模、可視化和洞察，以及面向資料的深度研究（生成分析師級研究報告）。 [![GitHub Repo stars](https://img.shields.io/github/stars/ruc-datalab/DeepAnalyze?style=flat&color=lightgrey&logo=github&label=Code+Stars)](https://github.com/ruc-datalab/DeepAnalyze)
- [data-to-paper](https://github.com/Technion-Kishony-lab/data-to-paper): AI 驅動的研究，從資料到人類可驗證的研究論文。 ![GitHub Repo stars](https://img.shields.io/github/stars/Technion-Kishony-lab/data-to-paper?style=flat&color=lightgrey&logo=github)
- [BlockAGI](https://github.com/blockpipe/blockagi): 迭代式、特定領域研究，輸出詳細的敘述性報告以展示其發現。 ![GitHub Repo stars](https://img.shields.io/github/stars/blockpipe/blockagi?style=flat&color=lightgrey&logo=github)
- [OpenLens AI](https://github.com/jarrycyx/openlens-ai): 面向健康信息學的完全自主研究 Agent。 ![GitHub Repo stars](https://img.shields.io/github/stars/jarrycyx/openlens-ai?style=flat&color=lightgrey&logo=github)
- [GenoMAS](https://github.com/Liu-Hy/GenoMAS): 面向科學發現的多智能體框架，通過程式碼驅動工作流自動化基因表達分析。 ![GitHub Repo stars](https://img.shields.io/github/stars/Liu-Hy/GenoMAS?style=flat&color=lightgrey&logo=github)

## 對話與個人助理 Agent

面向對話、個人助理和會話場景的 AI 智能體，按 GitHub Star 數量排序。

- [OpenClaw](https://github.com/openclaw/openclaw): 開源 AI Agent 框架，將 LLM 轉化為持久、主動的個人 AI 智能體，支援多渠道消息（Signal、Telegram、Discord、WhatsApp）、定時調度、記憶系統、MCP 整合、技能插件、子 Agent 派生和瀏覽器自動化。 ![GitHub Repo stars](https://img.shields.io/github/stars/openclaw/openclaw?style=flat&color=lightgrey&logo=github)
- [CollosalAI Chat](https://github.com/hpcaitech/ColossalAI/tree/main/applications/Chat): 用 RLHF 實現 LLM，由 Colossal-AI 項目驅動。 ![GitHub Repo stars](https://img.shields.io/github/stars/hpcaitech/ColossalAI?style=flat&color=lightgrey&logo=github)
- [nanobot](https://github.com/HKUDS/nanobot): 超輕量級個人 AI 助手框架（約 4,000 行 Python 程式碼），支援 MCP、9+ 聊天頻道和可擴展技能系統。 ![GitHub Repo stars](https://img.shields.io/github/stars/HKUDS/nanobot?style=flat&color=lightgrey&logo=github)
- [Memgpt](https://github.com/cpacker/memgpt): 創建具有長期記憶和自定義工具的 LLM 智能體。 ![Github Repo stars](https://img.shields.io/github/stars/cpacker/memgpt?style=flat&color=lightgrey&logo=github)
- [SuperAgent](https://github.com/homanp/superagent): 將 LLM 智能體部署到生產環境。 ![GitHub Repo stars](https://img.shields.io/github/stars/homanp/superagent?style=flat&color=lightgrey&logo=github)
- [RasaGPT](https://github.com/paulpierre/RasaGPT): 首個基於 Rasa 和 LangChain 構建的無頭 LLM 聊天機器人平台。 ![GitHub Repo stars](https://img.shields.io/github/stars/paulpierre/RasaGPT?style=flat&color=lightgrey&logo=github)
- [Awesome OpenClaw Agents](https://github.com/mergisi/awesome-openclaw-agents): 精選 100+ 個生產就緒的 OpenClaw SOUL.md Agent 模板，涵蓋生產力、開發、行銷和業務自動化。 ![GitHub Repo stars](https://img.shields.io/github/stars/mergisi/awesome-openclaw-agents?style=flat&color=lightgrey&logo=github)
- [BabyAGI UI](https://github.com/miurla/babyagi-ui): 更便捷地在 Web 應用中運行和開發 babyagi，類似 ChatGPT。 ![GitHub Repo stars](https://img.shields.io/github/stars/miurla/babyagi-ui?style=flat&color=lightgrey&logo=github)
- [ix](https://github.com/kreneskyp/ix): 自主 GPT-4 智能體平台。 ![GitHub Repo stars](https://img.shields.io/github/stars/kreneskyp/ix?style=flat&color=lightgrey&logo=github)
- [LLama Cpp Agent](https://github.com/Maximilian-Winter/llama-cpp-agent): 專為簡化與大型語言模型互動而設計的工具。 ![GitHub Repo stars](https://img.shields.io/github/stars/Maximilian-Winter/llama-cpp-agent?style=flat&color=lightgrey&logo=github)
- [Autonomous HR Chatbot](https://github.com/stepanogil/autonomous-hr-chatbot): 自主解答 HR 相關問題的 Agent，利用其手頭的工具。 ![GitHub Repo stars](https://img.shields.io/github/stars/stepanogil/autonomous-hr-chatbot?style=flat&color=lightgrey&logo=github)
- [ClaudeClaw](https://github.com/sbusso/claudeclaw): Claude Code 的持久化 Agent 編排插件——多渠道路由（Slack、WhatsApp、Telegram）、OS 級沙箱隔離、可組合擴展、結構化記憶、Webhook 觸發器。 ![GitHub Repo stars](https://img.shields.io/github/stars/sbusso/claudeclaw?style=flat&color=lightgrey&logo=github)

## 知識管理與 RAG

用於文件檢索、私有知識庫和 RAG 管道的智能體與工具，按 GitHub Star 數量排序。

- [Private GPT](https://github.com/imartinez/privateGPT): 利用 GPT 的強大功能與文件私密互動，100% 私密，零資料洩露。 ![GitHub Repo stars](https://img.shields.io/github/stars/imartinez/privateGPT?style=flat&color=lightgrey&logo=github)
- [Local GPT](https://github.com/PromtEngineer/localGPT): 受 Private GPT 啟發，用 GPT4ALL 模型替換 Vicuna-7B，使用 InstructorEmbeddings 代替 LlamaEmbeddings。 ![GitHub Repo stars](https://img.shields.io/github/stars/PromtEngineer/localGPT?style=flat&color=lightgrey&logo=github)
- [DB GPT](https://github.com/csunny/DB-GPT): 使用本地 GPT 與資料和環境互動，零資料洩露，100% 私密，100% 安全。 ![GitHub Repo stars](https://img.shields.io/github/stars/csunny/DB-GPT?style=flat&color=lightgrey&logo=github)
- [LLocalSearch](https://github.com/nilsherzig/LLocalSearch): 完全本地運行的 LLM Agent 搜索聚合器。用戶提問，系統使用 LLM 鏈找到答案。無需 OpenAI 或 Google API 金鑰。 ![GitHub Repo stars](https://img.shields.io/github/stars/nilsherzig/LLocalSearch?style=flat&color=lightgrey&logo=github)
- [Agentset](https://github.com/agentset-ai/agentset): 開源生產就緒的 RAG 平台，內建 Agentic 推理、混合搜索和多模態支持。 ![GitHub Repo stars](https://img.shields.io/github/stars/agentset-ai/agentset?style=flat&color=lightgrey&logo=github)
- [Second Brain AI Agent](https://github.com/flepied/second-brain-agent): 使用 OpenAI 和 ChromaDB 本地對話筆記的 Streamlit 應用。 ![GitHub Repo stars](https://img.shields.io/github/stars/flepied/second-brain-agent?style=flat&color=lightgrey&logo=github)
- [Cortex Memory](https://github.com/sopaco/cortex-mem): 智能體記憶的完整解決方案，涵蓋提取、向量搜索到自動優化，開箱即用提供 REST API、MCP、CLI 和洞察儀表板。
- [SAGE](https://github.com/l33tdawg/sage): AI 智能體的機構記憶——每條記憶在提交前都經過 BFT 共識。4 個應用驗證器、13 個 MCP 工具，本地運行。 ![GitHub Repo stars](https://img.shields.io/github/stars/l33tdawg/sage?style=flat&color=lightgrey&logo=github)

## 瀏覽器與 Web Agent

用於瀏覽器自動化和 Web 互動的 Agent 與基礎設施，按 GitHub Star 數量排序。

- [AgentGPT](https://github.com/reworkd/AgentGPT): 使用 LangChain 和 OpenAI 構建的 AI 智能體（Vercel / Nextjs）。 ![GitHub Repo stars](https://img.shields.io/github/stars/reworkd/AgentGPT?style=flat&color=lightgrey&logo=github)
- [Steel Browser](https://github.com/steel-dev/steel-browser): AI 智能體的開源瀏覽器基礎設施，支援會話自動化、提取、截圖/PDF、AI 原生 CLI 和可復用的 steel-browser 技能。 ![GitHub Repo stars](https://img.shields.io/github/stars/steel-dev/steel-browser?style=flat&color=lightgrey&logo=github)
- [OpenAgents](https://github.com/xlang-ai/OpenAgents): 現實世界中語言智能體的開放平台。 ![GitHub Repo stars](https://img.shields.io/github/stars/xlang-ai/OpenAgents?style=flat&color=lightgrey&logo=github)
- [Gobii](https://github.com/gobii-ai/gobii-platform): 開源平台，以對話界面和 API 大規模部署和管理瀏覽器使用 Agent。 ![GitHub Repo stars](https://img.shields.io/github/stars/gobii-ai/gobii-platform?style=flat&color=lightgrey&logo=github)

## 語音與多模態

用於語音、音訊和多模態互動的 Agent 與框架，按 GitHub Star 數量排序。

- [Pipecat](https://github.com/pipecat-ai/pipecat): 開源的語音和多模態對話 AI 框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/pipecat-ai/pipecat?style=flat&color=lightgrey&logo=github)
- [joinly](https://github.com/joinly-ai/joinly): 語音優先的線上會議 AI 助手，可主動參與會議並即時解決任務。 ![GitHub Repo stars](https://img.shields.io/github/stars/joinly-ai/joinly?style=flat&color=lightgrey&logo=github)

## 測試與評估

用於測試、評估和觀測 AI 智能體的框架與工具，按 GitHub Star 數量排序。

- [Arize-Phoenix](https://github.com/Arize-ai/phoenix): 開源的 Agent 測試、評估和可觀測性庫。 ![GitHub Repo stars](https://img.shields.io/github/stars/Arize-ai/phoenix?style=flat&color=lightgrey&logo=github)
- [Manifest](https://github.com/mnfst/manifest): AI 智能體的開源即時成本可觀測平台。追蹤 Token、成本、消息和模型使用情況，提供本地優先儀表板。支援 28+ LLM 模型、OTLP 攝入、自托管。 ![GitHub Repo stars](https://img.shields.io/github/stars/mnfst/manifest?style=flat&color=lightgrey&logo=github)
- [EvoAgentX](https://github.com/EvoAgentX/EvoAgentX): 構建自我進化的 AI 智能體生態系統，提供自動化評估和進化 Agentic 工作流的框架。 ![GitHub Repo stars](https://img.shields.io/github/stars/EvoAgentX/EvoAgentX?style=flat&color=lightgrey&logo=github)
- [Open-RAG-Eval](https://github.com/vectara/open-rag-eval): 開源 RAG 評估框架，無需標準答案，可用於評估連接到 AI Agent 的 RAG 工具性能（Agentic RAG）。
- [Voice Lab](https://github.com/saharmor/voice-lab): 全面的語音 Agent 測試和評估框架，支援跨語言模型、提示詞和 Agent 角色的評估。 ![GitHub Repo stars](https://img.shields.io/github/stars/saharmor/voice-lab?style=flat&color=lightgrey&logo=github)
- [voicetest](https://github.com/voicetestdev/voicetest): 語音 Agent 的開源測試工具，支援 Retell、VAPI、Bland 和 LiveKit。運行自主模擬並使用 LLM 評判器評估。 ![GitHub Repo stars](https://img.shields.io/github/stars/voicetestdev/voicetest?style=flat&color=lightgrey&logo=github)

## 基礎設施與安全

用於智能體部署、沙箱隔離和安全防護的平台與工具，按 GitHub Star 數量排序。

- [e2b](https://github.com/e2b-dev/e2b): 構建和部署虛擬開發者 Agent 的開源平台。
- [AgentField](https://github.com/Agent-Field/agentfield): AI 後端的開源基礎設施。Kubernetes 用於編排，Okta 用於身份管理——從第一天起就生產就緒。 ![GitHub Repo stars](https://img.shields.io/github/stars/Agent-Field/agentfield?style=flat&color=lightgrey&logo=github)

## 遊戲與模擬

面向遊戲、仿真模擬和人類行為建模的 AI 智能體，按 GitHub Star 數量排序。

- [Voyager](https://github.com/MineDojo/Voyager): 基於大型語言模型的開放式具身 Agent。 ![GitHub Repo stars](https://img.shields.io/github/stars/MineDojo/Voyager?style=flat&color=lightgrey&logo=github)
- [Camel-AutoGPT](https://github.com/SamurAIGPT/Camel-AutoGPT): LLM 和自主 Agent（如 BabyAGI 和 AutoGPT）的角色扮演方法。 ![GitHub Repo stars](https://img.shields.io/github/stars/SamurAIGPT/Camel-AutoGPT?style=flat&color=lightgrey&logo=github)
- [SkyAGI](https://github.com/litanlitudan/skyagi): LLM 智能體中湧現的人類行為模擬能力。 ![GitHub Repo stars](https://img.shields.io/github/stars/litanlitudan/skyagi?style=flat&color=lightgrey&logo=github)
