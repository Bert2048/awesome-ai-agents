# 🤖 Awesome AI Agents

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**Langues :** [English](README.md) | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md) | [Français](README.fr.md)

Une liste sélectionnée de frameworks, outils et projets open source pour construire des agents IA. Couvre l'orchestration d'agents, l'utilisation d'outils, la collaboration multi-agents, le RAG, l'automatisation de navigateur, les interfaces vocales et plus encore — tout ce dont vous avez besoin pour explorer et construire l'écosystème des agents.

> 🆕 **À la une :** [ClaudeClaw](https://github.com/sbusso/claudeclaw) — Orchestrateur d'agents persistant comme plugin Claude Code. Routage multicanal (Slack, WhatsApp, Telegram), isolation sandbox au niveau OS, système d'extensions composables. [En savoir plus →](https://github.com/sbusso/claudeclaw)

## Table des matières

- [Frameworks & SDKs](#frameworks--sdks-1)
- [LLMs & Outils de modèles](#llms--outils-de-modèles)
- [Prompts & Bibliothèques de compétences](#prompts--bibliothèques-de-compétences)
- [Agents de développement](#agents-de-développement)
- [Automatisation & Flux de travail](#automatisation--flux-de-travail)
- [Recherche & Analyse](#recherche--analyse)
- [Agents conversationnels & personnels](#agents-conversationnels--personnels)
- [Gestion des connaissances & RAG](#gestion-des-connaissances--rag)
- [Agents web & navigateur](#agents-web--navigateur)
- [Voix & Multimodal](#voix--multimodal)
- [Test & Évaluation](#test--évaluation)
- [Infrastructure & Sécurité](#infrastructure--sécurité)
- [Jeux & Simulation](#jeux--simulation)

## Frameworks & SDKs

Frameworks et SDKs polyvalents pour construire des agents IA, triés par étoiles GitHub.

- [LangChain](https://github.com/hwchase17/langchain): Le framework original 🐍 ![GitHub Repo stars](https://img.shields.io/github/stars/hwchase17/langchain?style=plastic&color=lightgrey&logo=github)
- [Autogen](https://github.com/microsoft/autogen): Permet le développement d'applications LLM de nouvelle génération. ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/autogen?style=plastic&color=lightgrey&logo=github)
- [LlamaIndex](https://github.com/jerryjliu/llama_index): Interface centrale pour connecter vos LLMs aux données externes. ![GitHub Repo stars](https://img.shields.io/github/stars/jerryjliu/llama_index?style=plastic&color=lightgrey&logo=github)
- [CrewAI](https://github.com/joaomdmoura/crewai): Framework de pointe pour l'orchestration d'agents IA autonomes à rôles. ![GitHub Repo stars](https://img.shields.io/github/stars/joaomdmoura/crewai?style=plastic&color=lightgrey&logo=github)
- [Phidata](https://github.com/phidatahq/phidata): Construire des assistants IA avec mémoire, connaissances et outils. ![GitHub Repo stars](https://img.shields.io/github/stars/phidatahq/phidata?style=plastic&color=lightgrey&logo=github)
- [DSPy](https://github.com/stanfordnlp/dspy): Framework pour programmer — et non prompter — les modèles de fondation. ![GitHub Repo stars](https://img.shields.io/github/stars/stanfordnlp/dspy?style=plastic&color=lightgrey&logo=github)
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel): SDK C# de Microsoft pour intégrer rapidement les LLMs dans vos applications. ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/semantic-kernel?style=plastic&color=lightgrey&logo=github)
- [Haystack](https://github.com/deepset-ai/haystack): Framework NLP pour interagir avec vos données via Transformers et LLMs. ![GitHub Repo stars](https://img.shields.io/github/stars/deepset-ai/haystack?style=plastic&color=lightgrey&logo=github)
- [Mastra](https://github.com/mastra-ai/mastra): Framework TypeScript pour construire rapidement des applications et fonctionnalités IA. ![GitHub Repo stars](https://img.shields.io/github/stars/mastra-ai/mastra?style=plastic&color=lightgrey&logo=github)
- [Swarm](https://github.com/openai/swarm): Framework éducatif d'OpenAI pour l'orchestration légère multi-agents. ![GitHub Repo stars](https://img.shields.io/github/stars/openai/swarm?style=plastic&color=lightgrey&logo=github)
- [AgentScope](https://github.com/modelscope/agentscope): Construire plus facilement des applications multi-agents alimentées par des LLMs. ![GitHub Repo stars](https://img.shields.io/github/stars/modelscope/agentscope?style=plastic&color=lightgrey&logo=github)
- [Botpress](https://github.com/botpress/botpress): Les briques de base pour construire des chatbots. ![GitHub Repo stars](https://img.shields.io/github/stars/botpress/botpress?style=plastic&color=lightgrey&logo=github)
- [Upsonic](https://github.com/upsonic/upsonic): Framework d'agents fiable avec support MCP. ![GitHub Repo stars](https://img.shields.io/github/stars/upsonic/upsonic?style=plastic&color=lightgrey&logo=github)
- [VoltAgent](https://github.com/VoltAgent/voltagent): Framework TypeScript open source pour agents IA avec observabilité LLM intégrée. ![GitHub Repo stars](https://img.shields.io/github/stars/voltagent/voltagent?style=plastic&color=lightgrey&logo=github)
- [Swarms Framework](https://github.com/kyegomez/swarms): Framework d'orchestration multi-agents de pointe pour applications d'entreprise. ![GitHub Repo stars](https://img.shields.io/github/stars/kyegomez/swarms?style=plastic&color=lightgrey&logo=github)
- [PraisonAI](https://github.com/MervinPraison/PraisonAI): Framework multi-agents prêt pour la production avec auto-réflexion. Instanciation la plus rapide (3,77μs), 100+ LLMs, MCP, workflows, mémoire, SDK Python & JavaScript. ![GitHub Repo stars](https://img.shields.io/github/stars/MervinPraison/PraisonAI?style=plastic&color=lightgrey&logo=github)
- [Strands Agents SDK](https://github.com/strands-agents/sdk-python): Approche pilotée par modèle pour construire des agents IA en quelques lignes de code. ![GitHub Repo stars](https://img.shields.io/github/stars/strands-agents/sdk-python?style=plastic&color=lightgrey&logo=github)
- [AgentVerse](https://github.com/openbmb/agentverse): Framework flexible simplifiant la création d'environnements multi-agents personnalisés pour les LLMs. ![GitHub Repo stars](https://img.shields.io/github/stars/openbmb/agentverse?style=plastic&color=lightgrey&logo=github)
- [Maestro](https://github.com/Doriandarko/maestro): Framework permettant à Claude Opus d'orchestrer intelligemment des sous-agents. ![GitHub Repo stars](https://img.shields.io/github/stars/Doriandarko/maestro?style=plastic&color=lightgrey&logo=github)
- [llama-agentic-system](https://github.com/meta-llama/llama-agentic-system): Composants agentiques des APIs Llama Stack. ![GitHub Repo stars](https://img.shields.io/github/stars/meta-llama/llama-agentic-system?style=plastic&color=lightgrey&logo=github)
- [AG2](https://github.com/ag2ai/ag2): Framework open source des créateurs d'AutoGen pour construire et faire coopérer des agents IA. ![GitHub Repo stars](https://img.shields.io/github/stars/ag2ai/ag2?style=plastic&color=lightgrey&logo=github)
- [agency-swarm](https://github.com/VRSEN/agency-swarm): Framework d'agents fiable construit sur la dernière API OpenAI Assistants. ![GitHub Repo stars](https://img.shields.io/github/stars/VRSEN/agency-swarm?style=plastic&color=lightgrey&logo=github)
- [Agent-LLM](https://github.com/Josh-XT/Agent-LLM): Plateforme d'automatisation par intelligence artificielle. ![GitHub Repo stars](https://img.shields.io/github/stars/Josh-XT/Agent-LLM?style=plastic&color=lightgrey&logo=github)
- [Lagent](https://github.com/InternLM/lagent): Framework léger pour construire des agents basés sur les LLMs. ![GitHub Repo stars](https://img.shields.io/github/stars/InternLM/lagent?style=plastic&color=lightgrey&logo=github)
- [Agentic Context Engine](https://github.com/kayba-ai/agentic-context-engine): Agents auto-améliorants apprenant des retours d'exécution. Intégration LangChain pour gérer leur propre contexte. ![GitHub Repo stars](https://img.shields.io/github/stars/kayba-ai/agentic-context-engine?style=plastic&color=lightgrey&logo=github)
- [AgentDock](https://github.com/AgentDock/AgentDock): Stop aux intégrations API complexes. AgentDock fournit la base open source pour construire, gérer et déployer des agents IA en production sans friction. ![GitHub Repo stars](https://img.shields.io/github/stars/agentdock/agentdock?style=plastic&color=lightgrey&logo=github)
- [Dust](https://github.com/dust-tt/dust): Concevoir et déployer des applications de grands modèles de langage. ![GitHub Repo stars](https://img.shields.io/github/stars/dust-tt/dust?style=plastic&color=lightgrey&logo=github)
- [LLM Agents](https://github.com/mpaepper/llm_agents): Construire des agents contrôlés par des LLMs. ![GitHub Repo stars](https://img.shields.io/github/stars/mpaepper/llm_agents?style=plastic&color=lightgrey&logo=github)
- [ConnectOnion](https://github.com/openonion/connectonion): Framework Python simple pour agents en production — création en 2 lignes, fonctions comme outils, 12 hooks de cycle de vie, système de plugins, réseau multi-agents avec confiance. ![GitHub Repo stars](https://img.shields.io/github/stars/openonion/connectonion?style=plastic&color=lightgrey&logo=github)
- [Agency](https://github.com/neurocult/agency): 🕵️‍♂️ Bibliothèque pour les développeurs souhaitant explorer le potentiel des LLMs via une approche propre et idiomatique Go. ![GitHub Repo stars](https://img.shields.io/github/stars/neurocult/agency?style=plastic&color=lightgrey&logo=github)
- [Modus](https://github.com/hypermodeinc/modus): Framework serverless open source pour construire des agents et APIs intelligents en Go ou AssemblyScript.
- [LoongFlow](https://github.com/baidu-baige/LoongFlow): Framework de développement d'agents évolutif, des composants atomiques aux agents de scénarios clés. ![GitHub Repo stars](https://img.shields.io/github/stars/baidu-baige/LoongFlow?style=plastic&color=lightgrey&logo=github)
- [AgentFlow](https://github.com/simonmesmith/agentflow): Workflows LLM complexes à partir de simples JSON. ![GitHub Repo stars](https://img.shields.io/github/stars/simonmesmith/agentflow?style=plastic&color=lightgrey&logo=github)
- [FIM Agent](https://github.com/fim-ai/fim-agent): Hub de connecteurs alimenté par IA — planification DAG dynamique, agent ReAct, client MCP, génération RAG avec fondement, et plateforme de connecteurs transformant toute API en outil agent. ![GitHub Repo stars](https://img.shields.io/github/stars/fim-ai/fim-agent?style=plastic&color=lightgrey&logo=github)
- [hcom](https://github.com/aannoo/hcom): Permet aux agents IA de s'envoyer des messages, se surveiller et se spawner entre terminaux. Supporte Claude Code, Gemini CLI, Codex, OpenCode. ![GitHub Repo stars](https://img.shields.io/github/stars/aannoo/hcom?style=plastic&color=lightgrey&logo=github)
- [Ailoy](https://github.com/brekkylab/ailoy): Framework complet pour construire des agents IA s'exécutant partout, avec support total de l'IA locale et WASM.
- [NeuroLink](https://github.com/juspay/neurolink): Framework d'agents TypeScript avec boucles multi-étapes, contrôle d'exécution par étape (`prepareStep`), mémoire persistante (Redis/S3/SQLite), workflows HITL, client MCP et 13 fournisseurs LLM. ![GitHub Repo stars](https://img.shields.io/github/stars/juspay/neurolink?style=plastic&color=lightgrey&logo=github)
- [Vectara-agentic](https://github.com/vectara/py-vectara-agentic): Framework pour créer des assistants et agents IA utilisant Vectara.
- [AgentUp](https://github.com/RedDotRocket/AgentUp): Conçu sur les bases de la sécurité, de l'évolutivité et de l'extensibilité, avec architecture pilotée par configuration et riche écosystème de plugins. ![GitHub Repo stars](https://img.shields.io/github/stars/RedDotRocket/AgentUp?style=plastic&color=lightgrey&logo=github)
- [Pilot Protocol](https://github.com/TeoSlayer/pilotprotocol): Stack réseau overlay donnant aux agents IA des adresses virtuelles, tunnels UDP chiffrés, traversée NAT et confiance mutuelle. Zéro dépendance, écrit en Go. ![GitHub Repo stars](https://img.shields.io/github/stars/TeoSlayer/pilotprotocol?style=plastic&color=lightgrey&logo=github)
- [Portia AI](https://github.com/portiaAI/portia-sdk-python/): Nouveau framework Python agentique open source conçu pour créer des agents fiables en production. ![GitHub Repo stars](https://img.shields.io/github/stars/portiaAI/portia-sdk-python?style=plastic&color=lightgrey&logo=github)
- [Transformers Agents](https://huggingface.co/docs/transformers/transformers_agents): Fournit une API en langage naturel par-dessus Transformers.

## LLMs & Outils de modèles

Le carburant pour construire des agents IA : grands modèles de langage, fournisseurs et plateformes d'inférence locale.

- [Claude](https://claude.ai/): Assistant IA haute performance d'Anthropic, avec la famille de modèles Claude 3.5.
- [Gemini](https://gemini.google.com/): Plateforme IA unifiée de Google avec sa suite de modèles multimodaux.
- [ChatGPT](https://chatgpt.com/): IA conversationnelle d'OpenAI alimentée par la série GPT.
- [DeepSeek](https://www.deepseek.com/): Laboratoire d'IA chinois de pointe avec de puissants modèles open source comme DeepSeek-R1 et DeepSeek-V3.
- [Ollama](https://github.com/ollama/ollama): La façon la plus simple d'exécuter des LLMs open source (Llama 3, Mistral, Gemma) localement sur macOS, Linux et Windows. ![GitHub Repo stars](https://img.shields.io/github/stars/ollama/ollama?style=plastic&color=lightgrey&logo=github)
- [Hugging Face](https://huggingface.co/): Le hub central de la communauté ML pour partager et télécharger modèles, datasets et applications.
- [ModelScope](https://modelscope.cn/): Plateforme collaborative nouvelle génération d'Alibaba Cloud pour les modèles et datasets IA open source.
- [LM Studio](https://lmstudio.ai/): Application de bureau complète pour découvrir, télécharger et exécuter des LLMs locaux.

## Prompts & Bibliothèques de compétences

Guides d'ingénierie de prompts, outils de génération structurée, serveurs de compétences MCP et bibliothèques utilitaires LLM, triés par étoiles GitHub.

- [Awesome ChatGPT Prompts](https://github.com/f/awesome-chatgpt-prompts): Une vaste collection de modèles de prompts ChatGPT sélectionnés par la communauté, couvrant des centaines de scénarios de jeu de rôle et de tâches spécifiques. ![GitHub Repo stars](https://img.shields.io/github/stars/f/awesome-chatgpt-prompts?style=plastic&color=lightgrey&logo=github)
- [MCP Servers](https://github.com/modelcontextprotocol/servers): La collection officielle de serveurs MCP de référence, permettant aux agents de se connecter aux systèmes de fichiers, bases de données, APIs et services externes. ![GitHub Repo stars](https://img.shields.io/github/stars/modelcontextprotocol/servers?style=plastic&color=lightgrey&logo=github)
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook): Exemples de code et guides officiels pour construire avec les APIs OpenAI, couvrant RAG, fine-tuning, appels de fonctions et patterns de production. ![GitHub Repo stars](https://img.shields.io/github/stars/openai/openai-cookbook?style=plastic&color=lightgrey&logo=github)
- [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide): Un guide complet des techniques d'ingénierie de prompts, couvrant la chaîne de pensée, le few-shot, le RAG et les stratégies avancées. ![GitHub Repo stars](https://img.shields.io/github/stars/dair-ai/Prompt-Engineering-Guide?style=plastic&color=lightgrey&logo=github)
- [LiteLLM](https://github.com/BerriAI/litellm): Une passerelle API unifiée pour 100+ fournisseurs LLM avec une interface compatible OpenAI, équilibrage de charge et suivi des coûts. ![GitHub Repo stars](https://img.shields.io/github/stars/BerriAI/litellm?style=plastic&color=lightgrey&logo=github)
- [Anthropic Cookbook](https://github.com/anthropics/anthropic-cookbook): Exemples de code et guides pour construire avec Claude, incluant les patterns d'agents, l'utilisation d'outils et les flux de travail multimodaux. ![GitHub Repo stars](https://img.shields.io/github/stars/anthropics/anthropic-cookbook?style=plastic&color=lightgrey&logo=github)
- [Guidance](https://github.com/guidance-ai/guidance): Un langage de prompting structuré pour un contrôle précis du format de sortie, des contraintes et du flux de génération des LLMs. ![GitHub Repo stars](https://img.shields.io/github/stars/guidance-ai/guidance?style=plastic&color=lightgrey&logo=github)
- [Promptfoo](https://github.com/promptfoo/promptfoo): Un outil open source pour tester, évaluer et effectuer du red-teaming sur les prompts LLM et les agents, avec support multi-modèles. ![GitHub Repo stars](https://img.shields.io/github/stars/promptfoo/promptfoo?style=plastic&color=lightgrey&logo=github)
- [Outlines](https://github.com/outlines-dev/outlines): Un framework pour la génération de texte structurée fiable, appliquant des schémas JSON et des contraintes regex aux sorties LLM. ![GitHub Repo stars](https://img.shields.io/github/stars/outlines-dev/outlines?style=plastic&color=lightgrey&logo=github)
- [Instructor](https://github.com/jxnl/instructor): Une bibliothèque Python pour obtenir des sorties structurées et validées par Pydantic depuis plusieurs fournisseurs LLM. ![GitHub Repo stars](https://img.shields.io/github/stars/jxnl/instructor?style=plastic&color=lightgrey&logo=github)
- [Promptflow](https://github.com/microsoft/promptflow): La suite Microsoft pour construire, tester, évaluer et déployer en production des flux LLM du prototype à la mise en production. ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/promptflow?style=plastic&color=lightgrey&logo=github)
- [Brex's Prompt Engineering Guide](https://github.com/brexhq/prompt-engineering): Un guide pratique et orienté production pour travailler avec les grands modèles de langage, par l'équipe d'ingénierie de Brex. ![GitHub Repo stars](https://img.shields.io/github/stars/brexhq/prompt-engineering?style=plastic&color=lightgrey&logo=github)

## Agents de développement

Agents IA et outils axés sur le développement logiciel, la génération de code et le DevOps, triés par étoiles GitHub.

- [OpenCode](https://github.com/sst/opencode): L'agent de code IA construit pour le terminal. ![GitHub Repo stars](https://img.shields.io/github/stars/sst/opencode?style=plastic&color=lightgrey&logo=github)
- [OpenHands](https://github.com/All-Hands-AI/OpenHands): 🙌 Moins coder, faire plus. (anciennement OpenDevin) Plateforme d'agents de développement logiciel alimentés par l'IA. ![GitHub Repo stars](https://img.shields.io/github/stars/All-Hands-AI/OpenHands?style=plastic&color=lightgrey&logo=github)
- [MetaGPT](https://github.com/geekan/MetaGPT): Framework multi-agents : la première société logicielle IA, vers la programmation en langage naturel. ![GitHub Repo stars](https://img.shields.io/github/stars/geekan/MetaGPT?style=plastic&color=lightgrey&logo=github)
- [Cline](https://github.com/cline/cline): Agent de codage IA open source donnant aux développeurs un accès direct et transparent aux modèles frontier. ![GitHub Repo stars](https://img.shields.io/github/stars/cline/cline?style=plastic&color=lightgrey&logo=github)
- [Aider](https://github.com/Aider-AI/aider): Programmation en binôme avec l'IA dans votre terminal. ![GitHub Repo stars](https://img.shields.io/github/stars/Aider-AI/aider?style=plastic&color=lightgrey&logo=github)
- [GPT Pilot](https://github.com/Pythagora-io/gpt-pilot): Technologie centrale de l'extension VS Code Pythagora, visant le premier vrai compagnon développeur IA. ![GitHub Repo stars](https://img.shields.io/github/stars/Pythagora-io/gpt-pilot?style=plastic&color=lightgrey&logo=github)
- [Devika](https://github.com/stitionai/devika): Ingénieur logiciel IA agentique capable de comprendre des instructions, les décomposer, rechercher des informations et écrire du code. ![GitHub Repo stars](https://img.shields.io/github/stars/stitionai/devika?style=plastic&color=lightgrey&logo=github)
- [SWE Agent](https://github.com/princeton-nlp/swe-agent): Prend un problème GitHub et tente de le corriger automatiquement avec GPT-4 ou le LM de votre choix. ![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/swe-agent?style=plastic&color=lightgrey&logo=github)
- [SuperAGI](https://github.com/TransformerOptimus/SuperAGI): Framework d'agents IA autonomes open source centré sur les développeurs. ![GitHub Repo stars](https://img.shields.io/github/stars/TransformerOptimus/SuperAGI?style=plastic&color=lightgrey&logo=github)
- [Plandex](https://github.com/plandex-ai/plandex): Moteur de codage IA pour les tâches complexes. ![GitHub Repo stars](https://img.shields.io/github/stars/plandex-ai/plandex?style=plastic&color=lightgrey&logo=github)
- [Claude Engineer](https://github.com/Doriandarko/claude-engineer): Interface CLI interactive utilisant Claude-3.5-Sonnet pour assister les tâches de développement logiciel.
- [TaskWeaver](https://github.com/microsoft/TaskWeaver): Framework d'agents code-first pour planifier et exécuter des tâches d'analyse de données en toute fluidité. ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/TaskWeaver?style=plastic&color=lightgrey&logo=github)
- [Vision agent](https://github.com/landing-ai/vision-agent): Bibliothèque utilisant des frameworks d'agents pour générer du code résolvant des tâches de vision. ![GitHub Repo stars](https://img.shields.io/github/stars/landing-ai/vision-agent?style=plastic&color=lightgrey&logo=github)
- [Codel](https://github.com/semanser/codel): ✨ Agent IA entièrement autonome pouvant effectuer des tâches complexes avec le terminal, le navigateur et l'éditeur. ![GitHub Repo stars](https://img.shields.io/github/stars/semanser/codel?style=plastic&color=lightgrey&logo=github)
- [ThinkGPT](https://github.com/alaeddine-13/thinkgpt): Techniques d'agents pour augmenter votre LLM et le pousser au-delà de ses limites. ![GitHub Repo stars](https://img.shields.io/github/stars/alaeddine-13/thinkgpt?style=plastic&color=lightgrey&logo=github)
- [Nous](https://github.com/TrafficGuard/nous): Plateforme d'agents IA TypeScript avec agents autonomes, agents développeurs logiciel, agents de revue de code et plus. ![GitHub Repo stars](https://img.shields.io/github/stars/TrafficGuard/nous?style=plastic&color=lightgrey&logo=github)
- [Stakpak](https://github.com/stakpak/agent): Agent DevOps open source pour sécuriser, déployer et maintenir une infrastructure prête pour la production. ![GitHub Repo stars](https://img.shields.io/github/stars/stakpak/agent?style=plastic&color=lightgrey&logo=github)
- [RepoAgent](https://github.com/OpenBMB/RepoAgent): Agent de dépôt alimenté par LLM pour générer de la documentation et comprendre rapidement les bases de code. ![GitHub Repo stars](https://img.shields.io/github/stars/OpenBMB/RepoAgent?style=plastic&color=lightgrey&logo=github)
- [MicroAgent](https://github.com/aymenfurter/microagents): Agents capables de s'auto-modifier leurs prompts et leur code Python. ![GitHub Repo stars](https://img.shields.io/github/stars/aymenfurter/microagents?style=plastic&color=lightgrey&logo=github)
- [AgentRun](https://github.com/Jonathan-Adly/AgentRun): Le moyen le plus simple et le plus rapide d'exécuter en toute sécurité du code Python généré par IA. ![GitHub Repo stars](https://img.shields.io/github/stars/Jonathan-Adly/AgentRun?style=plastic&color=lightgrey&logo=github)
- [Dorothy](https://github.com/Charlie85270/Dorothy): Application de bureau open source pour orchestrer simultanément plusieurs agents CLI IA avec automations, gestion Kanban, contrôle distant et serveurs MCP. ![GitHub Repo stars](https://img.shields.io/github/stars/Charlie85270/Dorothy?style=plastic&color=lightgrey&logo=github)
- [PyCodeAGI](https://github.com/chakkaradeep/pyCodeAGI): Petite expérience AGI pour générer une application Python à partir de la description de l'utilisateur. ![GitHub Repo stars](https://img.shields.io/github/stars/chakkaradeep/pyCodeAGI?style=plastic&color=lightgrey&logo=github)
- [VibeGrid](https://github.com/jcanizalez/vibegrid): Gestionnaire de terminal pour agents de codage IA avec grille multi-agents, files de tâches, automatisation de workflows, exécution headless, revue de diff inline et hooks Claude Code. ![GitHub Repo stars](https://img.shields.io/github/stars/jcanizalez/vibegrid?style=plastic&color=lightgrey&logo=github)
- [Greywall](https://github.com/GreyhavenHQ/greywall): Sandbox de commandes deny-by-default pour agents de codage IA, avec isolation du système de fichiers, contrôle réseau via proxy transparent, profils intégrés et mode apprentissage. ![GitHub Repo stars](https://img.shields.io/github/stars/GreyhavenHQ/greywall?style=plastic&color=lightgrey&logo=github)
- [ReviewCerberus](https://github.com/Kirill89/reviewcerberus): Outil de revue de code IA 100% gratuit et open source pour analyser les différences de branches git avec analyse complète sécurité, performance et qualité.
- [Hivemoot Colony](https://github.com/hivemoot/colony): Plateforme de gouvernance d'agents autonomes où les agents IA votent sur les fonctionnalités, révisent le code et publient des versions sans intervention humaine. Inclut un tableau de bord de gouvernance en direct. ![GitHub Repo stars](https://img.shields.io/github/stars/hivemoot/colony?style=plastic&color=lightgrey&logo=github)

## Automatisation & Flux de travail

Agents et plateformes pour l'automatisation des tâches, l'orchestration des flux de travail et l'opération autonome polyvalente, triés par étoiles GitHub.

- [Astron](https://github.com/iflytek/astron-agent): Plateforme de flux de travail agentique de niveau entreprise pour construire des SuperAgents de nouvelle génération.
- [Hive](https://github.com/aden-hive/hive): Framework d'agents IA open source pour construire des agents autonomes orientés objectifs et auto-améliorants. Définissez les résultats en langage naturel, générez automatiquement des graphes d'agents avec boucles d'évolution intégrées, intégration MCP et 100+ outils. ![GitHub Repo stars](https://img.shields.io/github/stars/aden-hive/hive?style=plastic&color=lightgrey&logo=github)
- [XAgent](https://github.com/OpenBMB/XAgent): Agent LLM autonome pour résoudre des tâches complexes. ![GitHub Repo stars](https://img.shields.io/github/stars/OpenBMB/XAgent?style=plastic&color=lightgrey&logo=github)
- [llama-agents](https://github.com/run-llama/llama-agents): Framework async-first pour construire des systèmes multi-agents avec communication inter-agents, exécution distribuée d'outils et boucle humain-dans-la-boucle. ![GitHub Repo stars](https://img.shields.io/github/stars/run-llama/llama-agents?style=plastic&color=lightgrey&logo=github)
- [DemoGPT](https://github.com/melih-unsal/DemoGPT): Créer des démos rapidement juste avec un prompt. Applique l'approche ToT sur l'arbre de documentation LangChain. ![GitHub Repo stars](https://img.shields.io/github/stars/melih-unsal/DemoGPT?style=plastic&color=lightgrey&logo=github)
- [uAgents](https://github.com/fetchai/uAgents): Framework rapide et léger pour créer des agents décentralisés. ![GitHub Repo stars](https://img.shields.io/github/stars/fetchai/uAgents?style=plastic&color=lightgrey&logo=github)
- [ADAS](https://github.com/ShengranHu/ADAS): Conception automatisée de systèmes agentiques. ![GitHub Repo stars](https://img.shields.io/github/stars/ShengranHu/ADAS?style=plastic&color=lightgrey&logo=github)
- [RestGPT](https://github.com/Yifan-Song793/RestGPT): Agent LLM autonome contrôlant des applications du monde réel via des APIs RESTful. ![GitHub Repo stars](https://img.shields.io/github/stars/Yifan-Song793/RestGPT?style=plastic&color=lightgrey&logo=github)
- [AgentK](https://github.com/mikekelly/AgentK): AGI auto-agentique qui est auto-évolutive et modulaire. ![GitHub Repo stars](https://img.shields.io/github/stars/mikekelly/AgentK?style=plastic&color=lightgrey&logo=github)
- [Giselle](https://github.com/giselles-ai/giselle): Constructeur de workflows agentiques pour créer facilement des solutions pilotées par l'IA. ![Github Repo stars](https://img.shields.io/github/stars/giselles-ai/giselle?style=plastic&color=lightgrey&logo=github)
- [Multi-Modal LangChain agents in Production](https://github.com/steamship-packages/langchain-agent-production-starter): Déployer des agents LangChain et les connecter à Telegram. ![GitHub Repo stars](https://img.shields.io/github/stars/steamship-packages/langchain-agent-production-starter?style=plastic&color=lightgrey&logo=github)
- [Untether](https://github.com/littlebearapps/untether): Pont Telegram pour agents de codage IA — contrôle de tâches distant, streaming de progression, permissions interactives, saisie vocale et suivi des coûts. Supporte Claude Code, Codex, OpenCode, Pi, Gemini CLI et Amp. ![GitHub Repo stars](https://img.shields.io/github/stars/littlebearapps/untether?style=plastic&color=lightgrey&logo=github)

## Recherche & Analyse

Agents spécialisés dans la recherche, la découverte scientifique et l'analyse de données, triés par étoiles GitHub.

- [Storm](https://github.com/stanford-oval/storm): Système de curation de connaissances alimenté par LLM qui recherche un sujet et génère un rapport complet avec citations. ![GitHub Repo stars](https://img.shields.io/github/stars/stanford-oval/storm?style=plastic&color=lightgrey&logo=github)
- [GPT Researcher](https://github.com/assafelovic/gpt-researcher): Agent autonome conçu pour la recherche en ligne complète sur une grande variété de tâches. ![GitHub Repo stars](https://img.shields.io/github/stars/assafelovic/gpt-researcher?style=plastic&color=lightgrey&logo=github)
- [AI Scientist](https://github.com/SakanaAI/AI-Scientist): L'IA Scientifique : Vers la découverte scientifique entièrement automatisée et ouverte. ![GitHub Repo stars](https://img.shields.io/github/stars/SakanaAI/AI-Scientist?style=plastic&color=lightgrey&logo=github)
- [DeepAnalyze](https://github.com/ruc-datalab/DeepAnalyze): Premier LLM agentique pour la science des données autonome, prenant en charge la préparation, l'analyse, la modélisation, la visualisation et des rapports de recherche de niveau analyste. [![GitHub Repo stars](https://img.shields.io/github/stars/ruc-datalab/DeepAnalyze?style=plastic&color=lightgrey&logo=github&label=Code+Stars)](https://github.com/ruc-datalab/DeepAnalyze)
- [data-to-paper](https://github.com/Technion-Kishony-lab/data-to-paper): Recherche pilotée par l'IA, des données aux articles de recherche vérifiables par l'humain. ![GitHub Repo stars](https://img.shields.io/github/stars/Technion-Kishony-lab/data-to-paper?style=plastic&color=lightgrey&logo=github)
- [BlockAGI](https://github.com/blockpipe/blockagi): Recherche itérative spécifique au domaine, produisant des rapports narratifs détaillés. ![GitHub Repo stars](https://img.shields.io/github/stars/blockpipe/blockagi?style=plastic&color=lightgrey&logo=github)
- [OpenLens AI](https://github.com/jarrycyx/openlens-ai): Agent de recherche entièrement autonome pour l'informatique de santé. ![GitHub Repo stars](https://img.shields.io/github/stars/jarrycyx/openlens-ai?style=plastic&color=lightgrey&logo=github)
- [GenoMAS](https://github.com/Liu-Hy/GenoMAS): Framework multi-agents pour la découverte scientifique qui automatise l'analyse d'expression génique via des workflows pilotés par code. ![GitHub Repo stars](https://img.shields.io/github/stars/Liu-Hy/GenoMAS?style=plastic&color=lightgrey&logo=github)

## Agents conversationnels & personnels

Agents conçus pour le dialogue, l'assistance personnelle et les cas d'usage conversationnels, triés par étoiles GitHub.

- [OpenClaw](https://github.com/openclaw/openclaw): Framework d'agents IA open source transformant les LLMs en agents IA personnels persistants et proactifs, avec messagerie multicanal (Signal, Telegram, Discord, WhatsApp), planification cron, mémoire, MCP, plugins de compétences, sous-agents et automatisation de navigateur. ![GitHub Repo stars](https://img.shields.io/github/stars/openclaw/openclaw?style=plastic&color=lightgrey&logo=github)
- [CollosalAI Chat](https://github.com/hpcaitech/ColossalAI/tree/main/applications/Chat): Implémentation de LLM avec RLHF, propulsé par le projet Colossal-AI. ![GitHub Repo stars](https://img.shields.io/github/stars/hpcaitech/ColossalAI?style=plastic&color=lightgrey&logo=github)
- [nanobot](https://github.com/HKUDS/nanobot): Framework d'assistant IA personnel ultra-léger (~4 000 lignes Python). Prend en charge MCP, 9+ canaux de chat et un système de compétences extensible. ![GitHub Repo stars](https://img.shields.io/github/stars/HKUDS/nanobot?style=plastic&color=lightgrey&logo=github)
- [Memgpt](https://github.com/cpacker/memgpt): Créer des agents LLM avec mémoire à long terme et outils personnalisés 📚🦙 ![Github Repo stars](https://img.shields.io/github/stars/cpacker/memgpt?style=plastic&color=lightgrey&logo=github)
- [SuperAgent](https://github.com/homanp/superagent): Déployer des agents LLM en production. ![GitHub Repo stars](https://img.shields.io/github/stars/homanp/superagent?style=plastic&color=lightgrey&logo=github)
- [RasaGPT](https://github.com/paulpierre/RasaGPT): La première plateforme de chatbot LLM headless construite sur Rasa et LangChain. ![GitHub Repo stars](https://img.shields.io/github/stars/paulpierre/RasaGPT?style=plastic&color=lightgrey&logo=github)
- [Awesome OpenClaw Agents](https://github.com/mergisi/awesome-openclaw-agents): Collection sélectionnée de 100+ modèles d'agents SOUL.md prêts pour la production pour OpenClaw, couvrant productivité, développement, marketing et automatisation des affaires. ![GitHub Repo stars](https://img.shields.io/github/stars/mergisi/awesome-openclaw-agents?style=plastic&color=lightgrey&logo=github)
- [BabyAGI UI](https://github.com/miurla/babyagi-ui): Facilite l'utilisation et le développement de babyagi dans une application web, comme ChatGPT. ![GitHub Repo stars](https://img.shields.io/github/stars/miurla/babyagi-ui?style=plastic&color=lightgrey&logo=github)
- [ix](https://github.com/kreneskyp/ix): Plateforme d'agents GPT-4 autonomes. ![GitHub Repo stars](https://img.shields.io/github/stars/kreneskyp/ix?style=plastic&color=lightgrey&logo=github)
- [LLama Cpp Agent](https://github.com/Maximilian-Winter/llama-cpp-agent): Outil conçu pour faciliter l'interaction avec les grands modèles de langage. ![GitHub Repo stars](https://img.shields.io/github/stars/Maximilian-Winter/llama-cpp-agent?style=plastic&color=lightgrey&logo=github)
- [Autonomous HR Chatbot](https://github.com/stepanogil/autonomous-hr-chatbot): Agent autonome répondant aux questions RH en utilisant les outils à sa disposition. ![GitHub Repo stars](https://img.shields.io/github/stars/stepanogil/autonomous-hr-chatbot?style=plastic&color=lightgrey&logo=github)
- [ClaudeClaw](https://github.com/sbusso/claudeclaw): Plugin d'orchestration d'agents persistants pour Claude Code — routage multicanal (Slack, WhatsApp, Telegram), isolation sandbox OS, extensions composables, mémoire structurée, déclencheurs webhook. ![GitHub Repo stars](https://img.shields.io/github/stars/sbusso/claudeclaw?style=plastic&color=lightgrey&logo=github)

## Gestion des connaissances & RAG

Agents et outils pour la récupération de documents, les bases de connaissances privées et les pipelines RAG, triés par étoiles GitHub.

- [Private GPT](https://github.com/imartinez/privateGPT): Interagir en privé avec vos documents grâce à GPT, 100% privé, aucune fuite de données. ![GitHub Repo stars](https://img.shields.io/github/stars/imartinez/privateGPT?style=plastic&color=lightgrey&logo=github)
- [Local GPT](https://github.com/PromtEngineer/localGPT): Inspiré de Private GPT avec le modèle GPT4ALL remplaçant Vicuna-7B et InstructorEmbeddings à la place de LlamaEmbeddings. ![GitHub Repo stars](https://img.shields.io/github/stars/PromtEngineer/localGPT?style=plastic&color=lightgrey&logo=github)
- [DB GPT](https://github.com/csunny/DB-GPT): Interagir avec vos données et environnement via GPT local, aucune fuite de données, 100% privé, 100% sécurisé. ![GitHub Repo stars](https://img.shields.io/github/stars/csunny/DB-GPT?style=plastic&color=lightgrey&logo=github)
- [LLocalSearch](https://github.com/nilsherzig/LLocalSearch): Agrégateur de recherche fonctionnant entièrement en local via des agents LLM. Aucune clé API OpenAI ou Google requise. ![GitHub Repo stars](https://img.shields.io/github/stars/nilsherzig/LLocalSearch?style=plastic&color=lightgrey&logo=github)
- [Agentset](https://github.com/agentset-ai/agentset): Plateforme RAG open source prête pour la production avec raisonnement agentique intégré, recherche hybride et support multimodal. ![GitHub Repo stars](https://img.shields.io/github/stars/agentset-ai/agentset?style=plastic&color=lightgrey&logo=github)
- [Second Brain AI Agent](https://github.com/flepied/second-brain-agent): Application Streamlit pour dialoguer avec vos notes Second Brain localement via OpenAI et ChromaDB. ![GitHub Repo stars](https://img.shields.io/github/stars/flepied/second-brain-agent?style=plastic&color=lightgrey&logo=github)
- [Cortex Memory](https://github.com/sopaco/cortex-mem): Solution complète pour la mémoire des agents, de l'extraction et la recherche vectorielle à l'optimisation automatisée, avec API REST, MCP, CLI et tableau de bord d'insights.
- [SAGE](https://github.com/l33tdawg/sage): Mémoire institutionnelle pour agents IA — chaque souvenir passe par un consensus BFT avant d'être committé. 4 validateurs, 13 outils MCP, fonctionne localement. ![GitHub Repo stars](https://img.shields.io/github/stars/l33tdawg/sage?style=plastic&color=lightgrey&logo=github)

## Agents web & navigateur

Agents et infrastructure pour l'automatisation du navigateur et l'interaction web, triés par étoiles GitHub.

- [AgentGPT](https://github.com/reworkd/AgentGPT): Agents IA avec LangChain et OpenAI (Vercel / Nextjs). ![GitHub Repo stars](https://img.shields.io/github/stars/reworkd/AgentGPT?style=plastic&color=lightgrey&logo=github)
- [Steel Browser](https://github.com/steel-dev/steel-browser): Infrastructure de navigateur open source pour agents IA avec automatisation par session, extraction, captures d'écran/PDFs, CLI natif IA et compétence steel-browser réutilisable. ![GitHub Repo stars](https://img.shields.io/github/stars/steel-dev/steel-browser?style=plastic&color=lightgrey&logo=github)
- [OpenAgents](https://github.com/xlang-ai/OpenAgents): Plateforme ouverte pour les agents linguistiques dans le monde réel. ![GitHub Repo stars](https://img.shields.io/github/stars/xlang-ai/OpenAgents?style=plastic&color=lightgrey&logo=github)
- [Gobii](https://github.com/gobii-ai/gobii-platform): Plateforme open source pour déployer et gérer des agents browser-use à grande échelle avec interface conversationnelle et API. ![GitHub Repo stars](https://img.shields.io/github/stars/gobii-ai/gobii-platform?style=plastic&color=lightgrey&logo=github)

## Voix & Multimodal

Agents et frameworks pour les interactions vocales, audio et multimodales, triés par étoiles GitHub.

- [Pipecat](https://github.com/pipecat-ai/pipecat): Framework open source pour l'IA conversationnelle vocale et multimodale. ![GitHub Repo stars](https://img.shields.io/github/stars/pipecat-ai/pipecat?style=plastic&color=lightgrey&logo=github)
- [joinly](https://github.com/joinly-ai/joinly): Assistant IA vocal pour les réunions en ligne qui peut y participer activement et résoudre des tâches en direct. ![GitHub Repo stars](https://img.shields.io/github/stars/joinly-ai/joinly?style=plastic&color=lightgrey&logo=github)

## Test & Évaluation

Frameworks et outils pour tester, évaluer et observer les agents IA, triés par étoiles GitHub.

- [Arize-Phoenix](https://github.com/Arize-ai/phoenix): Bibliothèque open source pour les tests, l'évaluation et l'observabilité des agents. ![GitHub Repo stars](https://img.shields.io/github/stars/Arize-ai/phoenix?style=plastic&color=lightgrey&logo=github)
- [Manifest](https://github.com/mnfst/manifest): Plateforme d'observabilité des coûts en temps réel open source pour agents IA. Suivi des tokens, coûts, messages et usage des modèles avec tableau de bord local-first. Supporte 28+ modèles LLM, ingestion OTLP, auto-hébergé. ![GitHub Repo stars](https://img.shields.io/github/stars/mnfst/manifest?style=plastic&color=lightgrey&logo=github)
- [EvoAgentX](https://github.com/EvoAgentX/EvoAgentX): Construit un écosystème d'agents IA auto-évolutifs avec framework automatisé pour évaluer et faire évoluer les workflows agentiques. ![GitHub Repo stars](https://img.shields.io/github/stars/EvoAgentX/EvoAgentX?style=plastic&color=lightgrey&logo=github)
- [Open-RAG-Eval](https://github.com/vectara/open-rag-eval): Framework d'évaluation RAG open source ne nécessitant pas de réponses de référence, pour évaluer les outils RAG connectés à un agent IA.
- [Voice Lab](https://github.com/saharmor/voice-lab): Framework complet de test et d'évaluation d'agents vocaux sur différents modèles de langage, prompts et personas d'agents. ![GitHub Repo stars](https://img.shields.io/github/stars/saharmor/voice-lab?style=plastic&color=lightgrey&logo=github)
- [voicetest](https://github.com/voicetestdev/voicetest): Harnais de test open source pour agents vocaux avec support Retell, VAPI, Bland et LiveKit. Simulations autonomes évaluées par des juges LLM. ![GitHub Repo stars](https://img.shields.io/github/stars/voicetestdev/voicetest?style=plastic&color=lightgrey&logo=github)

## Infrastructure & Sécurité

Plateformes et outils pour le déploiement d'agents, le sandboxing et la sécurité, triés par étoiles GitHub.

- [e2b](https://github.com/e2b-dev/e2b): Plateforme open source pour construire et déployer des agents développeurs virtuels.
- [AgentField](https://github.com/Agent-Field/agentfield): Infrastructure open source pour backends IA. Kubernetes pour l'orchestration, Okta pour l'identité — prêt pour la production dès le premier jour. ![GitHub Repo stars](https://img.shields.io/github/stars/Agent-Field/agentfield?style=plastic&color=lightgrey&logo=github)

## Jeux & Simulation

Agents construits pour les jeux, les simulations et la modélisation du comportement humain, triés par étoiles GitHub.

- [Voyager](https://github.com/MineDojo/Voyager): Agent incarné open-ended avec de grands modèles de langage. ![GitHub Repo stars](https://img.shields.io/github/stars/MineDojo/Voyager?style=plastic&color=lightgrey&logo=github)
- [Camel-AutoGPT](https://github.com/SamurAIGPT/Camel-AutoGPT): Approche de jeu de rôle pour les LLMs et agents autonomes comme BabyAGI et AutoGPT. ![GitHub Repo stars](https://img.shields.io/github/stars/SamurAIGPT/Camel-AutoGPT?style=plastic&color=lightgrey&logo=github)
- [SkyAGI](https://github.com/litanlitudan/skyagi): Capacité émergente de simulation du comportement humain dans les agents LLM. ![GitHub Repo stars](https://img.shields.io/github/stars/litanlitudan/skyagi?style=plastic&color=lightgrey&logo=github)
