# 🤖 Awesome AI Agents

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**Languages:** [English](README.md) | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md) | [Français](README.fr.md)

A curated list of frameworks, tools, and projects for building autonomous AI agents. Covering everything from multi-agent orchestration and RAG to browser automation and voice interfaces — your comprehensive guide to the agentic ecosystem.

## Table of Contents

- [🤖 Awesome AI Agents](#-awesome-ai-agents)
  - [Table of Contents](#table-of-contents)
  - [Frameworks \& SDKs](#frameworks--sdks)
  - [LLMs \& Model Tools](#llms--model-tools)
  - [Coding \& Development Agents](#coding--development-agents)
  - [Automation \& Workflow](#automation--workflow)
  - [Research \& Analysis](#research--analysis)
  - [Conversational \& Personal Agents](#conversational--personal-agents)
  - [Knowledge Management \& RAG](#knowledge-management--rag)
  - [Browser \& Web Agents](#browser--web-agents)
  - [Voice \& Multimodal](#voice--multimodal)
  - [Testing \& Evaluation](#testing--evaluation)
  - [Infrastructure \& Security](#infrastructure--security)
  - [Game \& Simulation](#game--simulation)

## Frameworks & SDKs

General-purpose frameworks and SDKs for building AI agents, sorted by GitHub stars.

- [LangChain](https://github.com/hwchase17/langchain): The industry-leading framework for building logic-driven LLM applications. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/hwchase17/langchain?style=social)
- [LangChain.js](https://github.com/hwchase17/langchainjs): The industry-leading framework for building logic-driven LLM applications. ![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/hwchase17/langchainjs?style=social)
- [LangGraph](https://github.com/langchain-ai/langgraph): The industry-leading framework for building logic-driven LLM applications. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/langchain-ai/langgraph?style=social)
- [LangGraph.js](https://github.com/langchain-ai/langgraphjs): The industry-leading framework for building logic-driven LLM applications. ![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/langchain-ai/langgraphjs?style=social)
- [AutoGen](https://github.com/microsoft/autogen): A high-level framework for developing next-generation applications with multi-agent orchestration. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/autogen?style=social)
- [LlamaIndex](https://github.com/jerryjliu/llama_index): The data framework for LLM applications, facilitating seamless connection to external data sources. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/jerryjliu/llama_index?style=social)
- [CrewAI](https://github.com/joaomdmoura/crewai): A collaborative framework designed for orchestrating role-playing autonomous AI agents. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/joaomdmoura/crewai?style=social)
- [Vercel AI SDK](https://github.com/vercel/ai): A comprehensive library for integrating AI capabilities into modern web applications using React, Next.js, and more. ![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/vercel/ai?style=social)
- [Phidata](https://github.com/phidatahq/phidata): Create full-stack AI assistants equipped with long-term memory, knowledge bases, and tool integration. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/phidatahq/phidata?style=social)
- [DSPy](https://github.com/stanfordnlp/dspy): A declarative programming framework that replaces manual prompting with algorithmic optimization for foundation models. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/stanfordnlp/dspy?style=social)
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel): Microsoft's SDK for integrating cutting-edge LLM technology into established enterprise applications. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/semantic-kernel?style=social)
- [Haystack](https://github.com/deepset-ai/haystack): An open-source NLP framework designed for building search and question-answering systems over large datasets. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/deepset-ai/haystack?style=social)
- [Mastra](https://github.com/mastra-ai/mastra): A performant, opinionated TypeScript framework for building scalable AI features and workflows. ![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/mastra-ai/mastra?style=social)
- [Swarm](https://github.com/openai/swarm): An experimental, lightweight orchestration framework for exploring ergonomics in multi-agent systems. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/openai/swarm?style=social)
- [AgentScope](https://github.com/modelscope/agentscope): A user-friendly framework for building multi-agent systems with a focus on developer efficiency. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/modelscope/agentscope?style=social)
- [Botpress](https://github.com/botpress/botpress): A platform provides the core infrastructure for building and deploying robust chatbots. ![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/botpress/botpress?style=social)
- [Upsonic](https://github.com/upsonic/upsonic): A reliable agent framework with native support for the Model Context Protocol (MCP). ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/upsonic/upsonic?style=social)
- [VoltAgent](https://github.com/VoltAgent/voltagent): A TypeScript framework for autonomous agents featuring built-in observability and debugging. ![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/voltagent/voltagent?style=social)
- [Swarms Framework](https://github.com/kyegomez/swarms): An enterprise-ready multi-agent orchestration system for complex mission-critical applications. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/kyegomez/swarms?style=social)
- [PraisonAI](https://github.com/MervinPraison/PraisonAI): A low-code multi-agent framework emphasizing rapid instantiation and MCP support. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/MervinPraison/PraisonAI?style=social)
- [Strands Agents SDK](https://github.com/strands-agents/sdk-python): A model-driven SDK for building agentic behaviors with minimal boilerplate code. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/strands-agents/sdk-python?style=social)
- [AgentVerse](https://github.com/openbmb/agentverse): A highly flexible framework for creating custom multi-agent environments and social simulations. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/openbmb/agentverse?style=social)
- [Maestro](https://github.com/Doriandarko/maestro): An orchestration framework that enables Claude Opus to intelligently manage and refine sub-agents. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/Doriandarko/maestro?style=social)
- [Claude Agent SDK](https://github.com/anthropics/claude-agent-sdk-typescript): The official SDK for building autonomous agents capable of direct file manipulation and command execution via Claude. ![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/anthropics/claude-agent-sdk-typescript?style=social)
- [llama-agentic-system](https://github.com/meta-llama/llama-agentic-system): Standardized agentic components and templates for the Llama Stack API ecosystem. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/meta-llama/llama-agentic-system?style=social)
- [AG2](https://github.com/ag2ai/ag2): A collaborative programming framework for building scalable agent systems, evolved from the original AutoGen. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/ag2ai/ag2?style=social)
- [agency-swarm](https://github.com/VRSEN/agency-swarm): A framework built on the OpenAI Assistants API for structured collaboration within hierarchical agent groups. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/VRSEN/agency-swarm?style=social)
- [Agent-LLM](https://github.com/Josh-XT/Agent-LLM): A platform for end-to-end AI automation and integrated management of modular agents. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/Josh-XT/Agent-LLM?style=social)
- [Lagent](https://github.com/InternLM/lagent): A lightweight library for developing and deploying modular LLM agents across diverse environments. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/InternLM/lagent?style=social)
- [Agentic Context Engine](https://github.com/kayba-ai/agentic-context-engine): Self-improving agents that optimize their own search context through cross-execution feedback. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/kayba-ai/agentic-context-engine?style=social)
- [AgentDock](https://github.com/AgentDock/AgentDock): An open-source foundation for building and deploying production-ready AI workflows with zero friction. ![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/agentdock/agentdock?style=social)
- [Dust](https://github.com/dust-tt/dust): A high-level platform for designing, testing, and deploying specialized LLM-powered applications. ![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/dust-tt/dust?style=social)
- [LLM Agents](https://github.com/mpaepper/llm_agents): A toolset for building goal-oriented autonomous agents controlled directly by large language models. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/mpaepper/llm_agents?style=social)
- [ConnectOnion](https://github.com/openonion/connectonion): A production-grade framework focusing on reliability, trust-based networking, and rapid development. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/openonion/connectonion?style=social)
- [Agency](https://github.com/neurocult/agency): 🕵️‍♂️ A Go library focusing on clean, idiomatic, and thread-safe implementation of generative AI features. ![Go](https://img.shields.io/badge/Go-blue?logo=go&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/neurocult/agency?style=social)
- [Modus](https://github.com/hypermodeinc/modus): A serverless framework for building intelligent agents and APIs using Go or AssemblyScript. ![Go](https://img.shields.io/badge/Go-blue?logo=go&logoColor=white) ![AssemblyScript](https://img.shields.io/badge/AssemblyScript-blue?logo=assemblyscript&logoColor=white)
- [LoongFlow](https://github.com/baidu-baige/LoongFlow): An evolving agent framework covering everything from basic components to complex industrial scenarios. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/baidu-baige/LoongFlow?style=social)
- [AgentFlow](https://github.com/simonmesmith/agentflow): Complex LLM workflows orchestrated through simple JSON task descriptions. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/simonmesmith/agentflow?style=social)
- [FIM Agent](https://github.com/fim-ai/fim-agent): An AI-powered connector hub for turning arbitrary APIs into tools accessible for autonomous agents. ![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/fim-ai/fim-agent?style=social)
- [hcom](https://github.com/aannoo/hcom): Enable agents across different terminals to communicate, monitor, and manage each other. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/aannoo/hcom?style=social)
- [Ailoy](https://github.com/brekkylab/ailoy): A comprehensive framework designed for running AI agents anywhere, featuring WASM and local AI support.
- [NeuroLink](https://github.com/juspay/neurolink): A TypeScript framework with multi-step loops, persistent memory, and integrated HITL workflows. ![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/juspay/neurolink?style=social)
- [Vectara-agentic](https://github.com/vectara/py-vectara-agentic): A toolkit for developing RAG-intensive assistants and agents utilizing the Vectara platform. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/vectara/py-vectara-agentic?style=social)
- [AgentUp](https://github.com/RedDotRocket/AgentUp): A configuration-driven architecture built for secure, scalable, and extensible agent ecosystems. ![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/RedDotRocket/AgentUp?style=social)
- [Pilot Protocol](https://github.com/TeoSlayer/pilotprotocol): A decentralized protocol providing virtual identities and encrypted tunnels for agent-to-agent communication. ![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/TeoSlayer/pilotprotocol?style=social)
- [Portia AI](https://github.com/portiaAI/portia-sdk-python/): An agentic Python framework designed specifically for high-reliability agents in production environments. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/portiaAI/portia-sdk-python?style=social)
- [Transformers Agents](https://huggingface.co/docs/transformers/transformers_agents): A natural language API built on top of the Transformers library for agentic tool use. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white)

## LLMs & Model Tools

The fuel for building AI agents: Large language models, providers, and local inference platforms.

- [Claude](https://claude.ai/): A high-performance AI assistant by Anthropic, powered by the industry-leading Claude 3.5 model family.
- [Gemini](https://gemini.google.com/): Google's unified AI platform offering a suite of advanced multimodal models.
- [ChatGPT](https://chatgpt.com/): OpenAI's signature conversational platform powered by the versatile GPT-4 series.
- [DeepSeek](https://www.deepseek.com/): A pioneering AI lab providing powerful open-weights models like DeepSeek-R1 and V3.
- [Ollama](https://github.com/ollama/ollama): The premier tool for running open-source LLMs (Llama, Mistral, Gemma) locally with a simple CLI. ![GitHub Repo stars](https://img.shields.io/github/stars/ollama/ollama?style=social)
- [Hugging Face](https://huggingface.co/): The essential infrastructure for the machine learning community to host and discover models and datasets.
- [ModelScope](https://modelscope.cn/): A next-generation collaborative platform for open-source AI models and datasets from Alibaba Cloud.
- [LM Studio](https://lmstudio.ai/): A user-friendly desktop application for discovering, downloading, and running local LLMs.

## Coding & Development Agents

AI agents and tools focused on software development, code generation, and DevOps, sorted by GitHub stars.

- [OpenCode](https://github.com/sst/opencode): An AI coding agent optimized for terminal-based workflows. ![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/sst/opencode?style=social)
- [OpenHands](https://github.com/All-Hands-AI/OpenHands): 🙌 A collaborative platform for software development agents. (Formerly OpenDevin). ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/All-Hands-AI/OpenHands?style=social)
- [MetaGPT](https://github.com/geekan/MetaGPT): A multi-agent framework designed to function as a virtual AI software company. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/geekan/MetaGPT?style=social)
- [Cline](https://github.com/cline/cline): An open-source coding assistant giving developers direct, transparent access to frontier models. ![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/cline/cline?style=social)
- [Aider](https://github.com/Aider-AI/aider): A powerful terminal-based AI pair programmer that edits code directly in your local environment. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/Aider-AI/aider?style=social)
- [GPT Pilot](https://github.com/Pythagora-io/gpt-pilot): A VS Code extensions core, aiming to be a real AI developer companion by writing scalable apps. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/Pythagora-io/gpt-pilot?style=social)
- [Devika](https://github.com/stitionai/devika): An agentic AI engineer that researches, plans, and writes code based on high-level instructions. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/stitionai/devika?style=social)
- [SWE Agent](https://github.com/princeton-nlp/swe-agent): An autonomous agent that navigates GitHub issues and generates pull requests with fixes. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/swe-agent?style=social)
- [SuperAGI](https://github.com/TransformerOptimus/SuperAGI): A developer-first framework for building and deploying autonomous AI agents. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/TransformerOptimus/SuperAGI?style=social)
- [Plandex](https://github.com/plandex-ai/plandex): An AI engine capable of handling complex, multi-file coding and refactoring tasks. ![GitHub Repo stars](https://img.shields.io/github/stars/plandex-ai/plandex?style=social)
- [Claude Engineer](https://github.com/Doriandarko/claude-engineer): An interactive CLI that leverages Claude-3.5-Sonnet to assist with development tasks. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/Doriandarko/claude-engineer?style=social)
- [TaskWeaver](https://github.com/microsoft/TaskWeaver): A code-first framework for planning and executing data analytics tasks seamlessly. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/TaskWeaver?style=social)
- [Vision agent](https://github.com/landing-ai/vision-agent): Utilize agent frameworks to generate code solutions for computer vision tasks. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/landing-ai/vision-agent?style=social)
- [Codel](https://github.com/semanser/codel): ✨ A fully autonomous agent that operates across terminal, browser, and editor. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/semanser/codel?style=social)
- [ThinkGPT](https://github.com/alaeddine-13/thinkgpt): Advanced techniques and tools to augment LLM capabilities beyond standard boundaries. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/alaeddine-13/thinkgpt?style=social)
- [Nous](https://github.com/TrafficGuard/nous): A TypeScript platform featuring autonomous agents for code review and development. ![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/TrafficGuard/nous?style=social)
- [Stakpak](https://github.com/stakpak/agent): An open-source DevOps agent for securing, deploying, and maintaining production infrastructure. ![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/stakpak/agent?style=social)
- [RepoAgent](https://github.com/OpenBMB/RepoAgent): An LLM-powered assistant for generating repository documentation and understanding codebases. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/OpenBMB/RepoAgent?style=social)
- [MicroAgent](https://github.com/aymenfurter/microagents): Lightweight agents capable of self-editing their own prompts and Python code. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/aymenfurter/microagents?style=social)
- [AgentRun](https://github.com/Jonathan-Adly/AgentRun): The fastest and safest way to execute AI-generated Python code in isolated environments. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/Jonathan-Adly/AgentRun?style=social)
- [Dorothy](https://github.com/Charlie85270/Dorothy): Orchestrate multiple AI CLI agents simultaneously with Kanban-style task management. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/Charlie85270/Dorothy?style=social)
- [PyCodeAGI](https://github.com/chakkaradeep/pyCodeAGI): An experimental AGI tool for generating Python applications from natural language prompts. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/chakkaradeep/pyCodeAGI?style=social)
- [VibeGrid](https://github.com/jcanizalez/vibegrid): A terminal manager for AI agents with multi-agent grids and workflow automation. ![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/jcanizalez/vibegrid?style=social)
- [Greywall](https://github.com/GreyhavenHQ/greywall): A secure sandbox with filesystem isolation and network control for AI coding agents. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/GreyhavenHQ/greywall?style=social)
- [ReviewCerberus](https://github.com/Kirill89/reviewcerberus): An open-source AI code reviewer focusing on security, performance, and code quality. ![Python](https://img.shields.io/badge/Python-blue?logo=python&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/Kirill89/reviewcerberus?style=social)
- [Hivemoot Colony](https://github.com/hivemoot/colony): A decentralized governance platform for AI agents to vote on and ship software features. ![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript&logoColor=white) ![GitHub Repo stars](https://img.shields.io/github/stars/hivemoot/colony?style=social)

## Automation & Workflow

Agents and platforms for task automation, workflow orchestration, and general-purpose autonomous operation, sorted by GitHub stars.

- [Astron](https://github.com/iflytek/astron-agent): An enterprise-grade platform for building resilient agentic workflows and SuperAgents.
- [Hive](https://github.com/aden-hive/hive): A goal-driven autonomous agent framework featuring built-in evolution loops and 100+ tools. ![GitHub Repo stars](https://img.shields.io/github/stars/aden-hive/hive?style=social)
- [XAgent](https://github.com/OpenBMB/XAgent): An autonomous LLM agent optimized for solving high-complexity real-world tasks. ![GitHub Repo stars](https://img.shields.io/github/stars/OpenBMB/XAgent?style=social)
- [llama-agents](https://github.com/run-llama/llama-agents): An async-first framework for building distributed multi-agent systems with human-in-the-loop support. ![GitHub Repo stars](https://img.shields.io/github/stars/run-llama/llama-agents?style=social)
- [DemoGPT](https://github.com/melih-unsal/DemoGPT): Rapidly generate application demos via an automated prompt-to-app pipeline. ![GitHub Repo stars](https://img.shields.io/github/stars/melih-unsal/DemoGPT?style=social)
- [uAgents](https://github.com/fetchai/uAgents): A fast and lightweight framework for creating decentralized autonomous agents. ![GitHub Repo stars](https://img.shields.io/github/stars/fetchai/uAgents?style=social)
- [ADAS](https://github.com/ShengranHu/ADAS): Automated design and optimization of sophisticated agentic systems. ![GitHub Repo stars](https://img.shields.io/github/stars/ShengranHu/ADAS?style=social)
- [RestGPT](https://github.com/Yifan-Song793/RestGPT): An autonomous agent that controls real-world applications through complex RESTful API interactions. ![GitHub Repo stars](https://img.shields.io/github/stars/Yifan-Song793/RestGPT?style=social)
- [AgentK](https://github.com/mikekelly/AgentK): A self-evolving, modular AGI system designed for autonomous operation. ![GitHub Repo stars](https://img.shields.io/github/stars/mikekelly/AgentK?style=social)
- [Giselle](https://github.com/giselles-ai/giselle): A user-friendly workflow builder for creating and deploying sophisticated AI solutions. ![Github Repo stars](https://img.shields.io/github/stars/giselles-ai/giselle?style=social)
- [Multi-Modal LangChain agents in Production](https://github.com/steamship-packages/langchain-agent-production-starter): Deploy and scale multimodal agents with Telegram integration. ![GitHub Repo stars](https://img.shields.io/github/stars/steamship-packages/langchain-agent-production-starter?style=social)
- [Untether](https://github.com/littlebearapps/untether): A Telegram bridge for remote task control and monitoring of AI coding agents. ![GitHub Repo stars](https://img.shields.io/github/stars/littlebearapps/untether?style=social)

## Research & Analysis

Agents specialized in research, scientific discovery, and data analysis, sorted by GitHub stars.

- [Storm](https://github.com/stanford-oval/storm): An LLM-powered knowledge curation system that researches a topic and generates a comprehensive report with citations. ![GitHub Repo stars](https://img.shields.io/github/stars/stanford-oval/storm?style=social)
- [GPT Researcher](https://github.com/assafelovic/gpt-researcher): An autonomous agent designed for comprehensive online research on a wide variety of tasks. ![GitHub Repo stars](https://img.shields.io/github/stars/assafelovic/gpt-researcher?style=social)
- [AI Scientist](https://github.com/SakanaAI/AI-Scientist): A framework for fully automated, open-ended scientific discovery using AI. ![GitHub Repo stars](https://img.shields.io/github/stars/SakanaAI/AI-Scientist?style=social)
- [DeepAnalyze](https://github.com/ruc-datalab/DeepAnalyze): An agentic LLM system for autonomous data science, from preparation to analyst-grade research reports. [![GitHub Repo stars](https://img.shields.io/github/stars/ruc-datalab/DeepAnalyze?style=social&label=Code+Stars)](https://github.com/ruc-datalab/DeepAnalyze)
- [data-to-paper](https://github.com/Technion-Kishony-lab/data-to-paper): Automate the research process from raw data to human-verifiable scientific papers. ![GitHub Repo stars](https://img.shields.io/github/stars/Technion-Kishony-lab/data-to-paper?style=social)
- [BlockAGI](https://github.com/blockpipe/blockagi): Conducts iterative, domain-specific research and produces detailed narrative reports of its findings. ![GitHub Repo stars](https://img.shields.io/github/stars/blockpipe/blockagi?style=social)
- [OpenLens AI](https://github.com/jarrycyx/openlens-ai): A fully autonomous research agent specialized in health informatics. ![GitHub Repo stars](https://img.shields.io/github/stars/jarrycyx/openlens-ai?style=social)
- [GenoMAS](https://github.com/Liu-Hy/GenoMAS): A multi-agent framework that automates gene expression analysis via code-driven workflows. ![GitHub Repo stars](https://img.shields.io/github/stars/Liu-Hy/GenoMAS?style=social)

## Conversational & Personal Agents

Agents designed for dialogue, personal assistance, and conversational use cases, sorted by GitHub stars.

- [OpenClaw](https://github.com/openclaw/openclaw): A framework for building persistent, proactive personal AI agents with multi-channel messaging and browser automation. ![GitHub Repo stars](https://img.shields.io/github/stars/openclaw/openclaw?style=social)
- [LobsterAI](https://github.com/netease-youdao/LobsterAI): A 24/7 AI assistant for data analysis, document processing, and email automation featuring long-term memory. ![GitHub Repo stars](https://img.shields.io/github/stars/netease-youdao/LobsterAI?style=social)
- [CollosalAI Chat](https://github.com/hpcaitech/ColossalAI/tree/main/applications/Chat): Implementation of LLM with RLHF, powered by the Colossal-AI high-performance computing project. ![GitHub Repo stars](https://img.shields.io/github/stars/hpcaitech/ColossalAI?style=social)
- [nanobot](https://github.com/HKUDS/nanobot): An ultra-lightweight personal assistant framework supporting MCP and multiple chat channels. ![GitHub Repo stars](https://img.shields.io/github/stars/HKUDS/nanobot?style=social)
- [Memgpt](https://github.com/cpacker/memgpt): Create LLM agents equipped with long-term memory and customized toolset. 📚🦙 ![Github Repo stars](https://img.shields.io/github/stars/cpacker/memgpt?style=social)
- [SuperAgent](https://github.com/homanp/superagent): A platform for deploying and scaling LLM agents in production environments. ![GitHub Repo stars](https://img.shields.io/github/stars/homanp/superagent?style=social)
- [RasaGPT](https://github.com/paulpierre/RasaGPT): The first headless LLM chatbot platform built on the foundation of Rasa and LangChain. ![GitHub Repo stars](https://img.shields.io/github/stars/paulpierre/RasaGPT?style=social)
- [Awesome OpenClaw Agents](https://github.com/mergisi/awesome-openclaw-agents): A collection of 100+ production-ready agent templates for the OpenClaw framework. ![GitHub Repo stars](https://img.shields.io/github/stars/mergisi/awesome-openclaw-agents?style=social)
- [BabyAGI UI](https://github.com/miurla/babyagi-ui): A web-based interface for running and developing BabyAGI tasks with ease. ![GitHub Repo stars](https://img.shields.io/github/stars/miurla/babyagi-ui?style=social)
- [ix](https://github.com/kreneskyp/ix): An integrated platform for orchestrating autonomous GPT-4 agents. ![GitHub Repo stars](https://img.shields.io/github/stars/kreneskyp/ix?style=social)
- [LLama Cpp Agent](https://github.com/Maximilian-Winter/llama-cpp-agent): A tool designed for efficient interaction with local LLMs via llama.cpp. ![GitHub Repo stars](https://img.shields.io/github/stars/Maximilian-Winter/llama-cpp-agent?style=social)
- [Autonomous HR Chatbot](https://github.com/stepanogil/autonomous-hr-chatbot): An autonomous agent that utilizes custom tools to answer human resources inquiries. ![GitHub Repo stars](https://img.shields.io/github/stars/stepanogil/autonomous-hr-chatbot?style=social)
- [ClaudeClaw](https://github.com/sbusso/claudeclaw): A persistent agent orchestration plugin for Claude Code featuring multi-channel routing and sandboxed isolation. ![GitHub Repo stars](https://img.shields.io/github/stars/sbusso/claudeclaw?style=social)

## Knowledge Management & RAG

Agents and tools for document retrieval, private knowledge bases, and RAG pipelines, sorted by GitHub stars.

- [Private GPT](https://github.com/imartinez/privateGPT): Interact privately with your documents using GPT in a secure, offline-ready environment. ![GitHub Repo stars](https://img.shields.io/github/stars/imartinez/privateGPT?style=social)
- [Local GPT](https://github.com/PromtEngineer/localGPT): An offline alternative to Private GPT using open-source models for localized data processing. ![GitHub Repo stars](https://img.shields.io/github/stars/PromtEngineer/localGPT?style=social)
- [DB GPT](https://github.com/csunny/DB-GPT): A secure framework for interacting with databases and environments using local LLMs. ![GitHub Repo stars](https://img.shields.io/github/stars/csunny/DB-GPT?style=social)
- [LLocalSearch](https://github.com/nilsherzig/LLocalSearch): A fully local search aggregator that uses agents to find answers without external API keys. ![GitHub Repo stars](https://img.shields.io/github/stars/nilsherzig/LLocalSearch?style=social)
- [Agentset](https://github.com/agentset-ai/agentset): A production-ready RAG platform with built-in agentic reasoning and multimodal support. ![GitHub Repo stars](https://img.shields.io/github/stars/agentset-ai/agentset?style=social)
- [Second Brain AI Agent](https://github.com/flepied/second-brain-agent): An application for interacting with personal notes locally using OpenAI and ChromaDB. ![GitHub Repo stars](https://img.shields.io/github/stars/flepied/second-brain-agent?style=social)
- [Cortex Memory](https://github.com/sopaco/cortex-mem): A complete solution for agent memory, from extraction to automated vector search optimization.
- [SAGE](https://github.com/l33tdawg/sage): Institutional memory for AI agents featuring BFT consensus for secure memory commits. ![GitHub Repo stars](https://img.shields.io/github/stars/l33tdawg/sage?style=social)

## Browser & Web Agents

Agents and infrastructure for browser automation and web interaction, sorted by GitHub stars.

- [AgentGPT](https://github.com/reworkd/AgentGPT): A popular platform for building and deploying autonomous AI agents directly in the browser. ![GitHub Repo stars](https://img.shields.io/github/stars/reworkd/AgentGPT?style=social)
- [Steel Browser](https://github.com/steel-dev/steel-browser): Open-source browser infrastructure for agents featuring session automation and data extraction. ![GitHub Repo stars](https://img.shields.io/github/stars/steel-dev/steel-browser?style=social)
- [OpenAgents](https://github.com/xlang-ai/OpenAgents): An open platform for deploying and evaluating language agents in real-world scenarios. ![GitHub Repo stars](https://img.shields.io/github/stars/xlang-ai/OpenAgents?style=social)
- [Gobii](https://github.com/gobii-ai/gobii-platform): A platform for managing browser-based agents at scale with conversational interfaces and APIs. ![GitHub Repo stars](https://img.shields.io/github/stars/gobii-ai/gobii-platform?style=social)

## Voice & Multimodal

Agents and frameworks for voice, audio, and multimodal interactions, sorted by GitHub stars.

- [Pipecat](https://github.com/pipecat-ai/pipecat): An open-source framework for building high-quality voice and multimodal conversational AI. ![GitHub Repo stars](https://img.shields.io/github/stars/pipecat-ai/pipecat?style=social)
- [joinly](https://github.com/joinly-ai/joinly): A voice-first AI assistant for online meetings that can actively participate and resolve tasks in real-time. ![GitHub Repo stars](https://img.shields.io/github/stars/joinly-ai/joinly?style=social)

## Testing & Evaluation

Frameworks and tools for testing, evaluating, and observing AI agents, sorted by GitHub stars.

- [Arize-Phoenix](https://github.com/Arize-ai/phoenix): An open-source library for agent testing, evaluation, and observability. ![GitHub Repo stars](https://img.shields.io/github/stars/Arize-ai/phoenix?style=social)
- [Manifest](https://github.com/mnfst/manifest): Real-time cost observability platform for tracking token usage across various LLM providers. ![GitHub Repo stars](https://img.shields.io/github/stars/mnfst/manifest?style=social)
- [EvoAgentX](https://github.com/EvoAgentX/EvoAgentX): A framework for building and evaluating self-evolving AI agent ecosystems. ![GitHub Repo stars](https://img.shields.io/github/stars/EvoAgentX/EvoAgentX?style=social)
- [Open-RAG-Eval](https://github.com/vectara/open-rag-eval): An open-source framework for evaluating the performance of RAG tools connected to AI agents.
- [Voice Lab](https://github.com/saharmor/voice-lab): A comprehensive testing framework for voice agents across language models and personas. ![GitHub Repo stars](https://img.shields.io/github/stars/saharmor/voice-lab?style=social)
- [voicetest](https://github.com/voicetestdev/voicetest): An open-source test harness for voice agents supporting Retell, VAPI, and LiveKit. ![GitHub Repo stars](https://img.shields.io/github/stars/voicetestdev/voicetest?style=social)

## Infrastructure & Security

Platforms and tools for agent deployment, sandboxing, and security, sorted by GitHub stars.

- [e2b](https://github.com/e2b-dev/e2b): An open-source platform for building and securely deploying virtual developer agents.
- [AgentField](https://github.com/Agent-Field/agentfield): Production-ready infrastructure for AI backends featuring Kubernetes orchestration and Okta identity management. ![GitHub Repo stars](https://img.shields.io/github/stars/Agent-Field/agentfield?style=social)

## Game & Simulation

Agents built for games, simulations, and human-behavior modeling, sorted by GitHub stars.

- [Voyager](https://github.com/MineDojo/Voyager): An open-ended embodied agent capable of exploring and learning in Minecraft using LLMs. ![GitHub Repo stars](https://img.shields.io/github/stars/MineDojo/Voyager?style=social)
- [Camel-AutoGPT](https://github.com/SamurAIGPT/Camel-AutoGPT): A role-playing approach for autonomous agents like BabyAGI and AutoGPT. ![GitHub Repo stars](https://img.shields.io/github/stars/SamurAIGPT/Camel-AutoGPT?style=social)
- [SkyAGI](https://github.com/litanlitudan/skyagi): A platform exploring emergent human behavior simulation within AI agent ecosystems. ![GitHub Repo stars](https://img.shields.io/github/stars/litanlitudan/skyagi?style=social)
