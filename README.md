# Awesome Agentic Open-Source Tools (2026 Edition)

A curated list of the most important open-source repositories powering agentic AI in 2026 — from agent frameworks and visual builders to automation platforms, retrieval systems, evaluation tools, and experimental agents.
---

## Table of Contents

- [Agent Frameworks & Orchestration](#agent-frameworks--orchestration)
- [Visual & No-Code Agent Builders](#visual--no-code-agent-builders)
- [Automation & Tool Execution](#automation--tool-execution)
- [Retrieval, Memory & RAG](#retrieval-memory--rag)
- [Evaluation, Guardrails & Testing](#evaluation-guardrails--testing)
- [Research & Experimental Agents](#research--experimental-agents)

---

## Agent Frameworks & Orchestration

Frameworks that define the agent loop: reasoning, state, memory, tool calls, and control flow.

| Tool | Stars | Forks | Description |
|------|-------|-------|-------------|
| [LangChain](https://github.com/langchain-ai/langchain) | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langchain?style=social) | ![GitHub forks](https://img.shields.io/github/forks/langchain-ai/langchain?style=social) | Framework for building LLM apps by composing chains, agents, tools, memory, and retrievers. Modular and extensible across providers and use cases. |
| [LangGraph](https://github.com/langchain-ai/langgraph) | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langgraph?style=social) | ![GitHub forks](https://img.shields.io/github/forks/langchain-ai/langgraph?style=social) | Framework for building stateful, multi-actor applications using explicit graphs. Used for long-running, multi-step, or human-in-the-loop agent systems. |
| [LlamaIndex](https://github.com/run-llama/llama_index) | ![GitHub stars](https://img.shields.io/github/stars/run-llama/llama_index?style=social) | ![GitHub forks](https://img.shields.io/github/forks/run-llama/llama_index?style=social) | Data framework for connecting LLMs to structured and unstructured data. Provides ingestion, indexing, retrieval, and query orchestration. |
| [Microsoft AutoGen](https://github.com/microsoft/autogen) | ![GitHub stars](https://img.shields.io/github/stars/microsoft/autogen?style=social) | ![GitHub forks](https://img.shields.io/github/forks/microsoft/autogen?style=social) | Framework for multi-agent systems with structured message-based communication. Enables agent-to-agent collaboration and conversation-based task decomposition. |
| [CrewAI](https://github.com/crewAIInc/crewAI) | ![GitHub stars](https://img.shields.io/github/stars/crewAIInc/crewAI?style=social) | ![GitHub forks](https://img.shields.io/github/forks/crewAIInc/crewAI?style=social) | Framework for orchestrating role-based multi-agent workflows with clear mental models for collaboration. |
| [Microsoft Semantic Kernel](https://github.com/microsoft/semantic-kernel) | ![GitHub stars](https://img.shields.io/github/stars/microsoft/semantic-kernel?style=social) | ![GitHub forks](https://img.shields.io/github/forks/microsoft/semantic-kernel?style=social) | Orchestration SDK for integrating AI into apps using skills, planners, and functions. Widely used in enterprise and .NET environments. |
| [Agno](https://github.com/agno-agi/agno) | ![GitHub stars](https://img.shields.io/github/stars/agno-agi/agno?style=social) | ![GitHub forks](https://img.shields.io/github/forks/agno-agi/agno?style=social) | Lightweight agent framework focused on composability and minimal abstractions. Offers flexibility and control over agent behavior. |
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | ![GitHub stars](https://img.shields.io/github/stars/All-Hands-AI/OpenHands?style=social) | ![GitHub forks](https://img.shields.io/github/forks/All-Hands-AI/OpenHands?style=social) | Open-source platform for autonomous software engineering agents. Agents can write code, run tests, browse repos, and interact with dev environments. |

---

## Visual & No-Code Agent Builders

Platforms for designing, configuring, and deploying AI agents using drag-and-drop interfaces and visual workflows.

| Tool | Stars | Forks | Description |
|------|-------|-------|-------------|
| [Flowise](https://github.com/FlowiseAI/Flowise) | ![GitHub stars](https://img.shields.io/github/stars/FlowiseAI/Flowise?style=social) | ![GitHub forks](https://img.shields.io/github/forks/FlowiseAI/Flowise?style=social) | Low-code visual builder for creating LLM and agent workflows with a drag-and-drop interface. Great for prototyping and internal tooling. |
| [Langflow](https://github.com/langflow-ai/langflow) | ![GitHub stars](https://img.shields.io/github/stars/langflow-ai/langflow?style=social) | ![GitHub forks](https://img.shields.io/github/forks/langflow-ai/langflow?style=social) | Visual interface for building and debugging LangChain-based applications. Used for education, demos, and early-stage experimentation. |
| [Dify](https://github.com/langgenius/dify) | ![GitHub stars](https://img.shields.io/github/stars/langgenius/dify?style=social) | ![GitHub forks](https://img.shields.io/github/forks/langgenius/dify?style=social) | Open-source platform for building, deploying, and operating LLM apps and agents. Combines orchestration, prompt management, evaluation, and deployment. |

---

## Automation & Tool Execution

Platforms and tools that empower agents to perform precise, repeatable actions across diverse systems.

| Tool | Stars | Forks | Description |
|------|-------|-------|-------------|
| [n8n](https://github.com/n8n-io/n8n) | ![GitHub stars](https://img.shields.io/github/stars/n8n-io/n8n?style=social) | ![GitHub forks](https://img.shields.io/github/forks/n8n-io/n8n?style=social) | Open-source workflow automation platform for connecting APIs and services. Often used as the execution layer for agent workflows. |
| [Composio](https://github.com/ComposioHQ/composio) | ![GitHub stars](https://img.shields.io/github/stars/ComposioHQ/composio?style=social) | ![GitHub forks](https://img.shields.io/github/forks/ComposioHQ/composio?style=social) | Prebuilt integrations for agents to interact with SaaS tools through a unified interface. Abstracts auth, permissions, and API schemas. |
| [Appwrite](https://github.com/appwrite/appwrite) | ![GitHub stars](https://img.shields.io/github/stars/appwrite/appwrite?style=social) | ![GitHub forks](https://img.shields.io/github/forks/appwrite/appwrite?style=social) | Open-source backend platform with auth, databases, storage, and serverless functions. Provides structured, permissioned backends for agents. |
| [Browser Use](https://github.com/browser-use/browser-use) | ![GitHub stars](https://img.shields.io/github/stars/browser-use/browser-use?style=social) | ![GitHub forks](https://img.shields.io/github/forks/browser-use/browser-use?style=social) | Enables agents to interact with web browsers programmatically — navigation, clicking, form submission, and data extraction. |
| [GitHub Copilot SDK](https://github.com/github/copilot-sdk) | ![GitHub stars](https://img.shields.io/github/stars/github/copilot-sdk?style=social) | ![GitHub forks](https://img.shields.io/github/forks/github/copilot-sdk?style=social) | SDK for extending GitHub Copilot with custom agents and workflows. Deep integration of AI agents into development environments. |
| [agent-qa](https://github.com/vostride/agent-qa) | ![GitHub stars](https://img.shields.io/github/stars/vostride/agent-qa?style=social) | ![GitHub forks](https://img.shields.io/github/forks/vostride/agent-qa?style=social) | Natural-language web/mobile QA via CLI or MCP, with persistent memidex memory, validated self-improvement and run evidence. [Website](https://vostride.com); [FSL-1.1-ALv2](https://vostride.com/license.md) restricts competing use; external model and infrastructure costs apply. |

---

## Retrieval, Memory & RAG

Tools that enhance retrieval-augmented generation workflows and memory systems for context-aware agents.

| Tool | Stars | Forks | Description |
|------|-------|-------|-------------|
| [Haystack](https://github.com/deepset-ai/haystack) | ![GitHub stars](https://img.shields.io/github/stars/deepset-ai/haystack?style=social) | ![GitHub forks](https://img.shields.io/github/forks/deepset-ai/haystack?style=social) | Framework for building search and RAG pipelines. Supports document stores, retrievers, readers, and evaluators. |
| [AutoRAG](https://github.com/Marker-Inc-Korea/AutoRAG) | ![GitHub stars](https://img.shields.io/github/stars/Marker-Inc-Korea/AutoRAG?style=social) | ![GitHub forks](https://img.shields.io/github/forks/Marker-Inc-Korea/AutoRAG?style=social) | Automates the evaluation and optimization of RAG pipelines. Focuses on systematic experimentation over ad-hoc tuning. |
| [Onyx](https://github.com/onyx-dot-app/onyx) | ![GitHub stars](https://img.shields.io/github/stars/onyx-dot-app/onyx?style=social) | ![GitHub forks](https://img.shields.io/github/forks/onyx-dot-app/onyx?style=social) | Memory abstractions designed for agent workflows. Emphasizes long-term context retention and structured memory access across sessions. |

---

## Evaluation, Guardrails & Testing

Tools for evaluation, testing, and monitoring to ensure agents perform reliably at scale.

| Tool | Stars | Forks | Description |
|------|-------|-------|-------------|
| [Ragas](https://github.com/explodinggradients/ragas) | ![GitHub stars](https://img.shields.io/github/stars/explodinggradients/ragas?style=social) | ![GitHub forks](https://img.shields.io/github/forks/explodinggradients/ragas?style=social) | Library for evaluating RAG systems. Provides metrics for relevance, faithfulness, and answer quality. |
| [Promptfoo](https://github.com/promptfoo/promptfoo) | ![GitHub stars](https://img.shields.io/github/stars/promptfoo/promptfoo?style=social) | ![GitHub forks](https://img.shields.io/github/forks/promptfoo/promptfoo?style=social) | Testing framework for prompts, models, and agent behaviors. Enables regression testing and CI integration. |
| [Helicone](https://github.com/Helicone/helicone) | ![GitHub stars](https://img.shields.io/github/stars/Helicone/helicone?style=social) | ![GitHub forks](https://img.shields.io/github/forks/Helicone/helicone?style=social) | Observability and monitoring for LLM and agent workflows. Tracks requests, latency, costs, and behavior over time. |
| [Pydantic AI](https://github.com/pydantic/pydantic-ai) | ![GitHub stars](https://img.shields.io/github/stars/pydantic/pydantic-ai?style=social) | ![GitHub forks](https://img.shields.io/github/forks/pydantic/pydantic-ai?style=social) | Structured validation and type enforcement for LLM and agent outputs. Ensures responses conform to expected schemas. |


---

## Research & Experimental Agents

Tools pushing the boundaries of what's possible with autonomous agents.

| Tool | Stars | Forks | Description |
|------|-------|-------|-------------|
| [GPT Researcher](https://github.com/assafelovic/gpt-researcher) | ![GitHub stars](https://img.shields.io/github/stars/assafelovic/gpt-researcher?style=social) | ![GitHub forks](https://img.shields.io/github/forks/assafelovic/gpt-researcher?style=social) | Autonomous agent for deep research tasks. Gathers sources, synthesizes information, and produces structured reports. |
| [GPT OSS](https://github.com/openai/gpt-oss) | ![GitHub stars](https://img.shields.io/github/stars/openai/gpt-oss?style=social) | ![GitHub forks](https://img.shields.io/github/forks/openai/gpt-oss?style=social) | Open reference implementations for agent behaviors. Influences standards and best practices across the ecosystem. |
| [OpenRouter](https://github.com/OpenRouterTeam/openrouter) | ![GitHub stars](https://img.shields.io/github/stars/OpenRouterTeam/openrouter?style=social) | ![GitHub forks](https://img.shields.io/github/forks/OpenRouterTeam/openrouter?style=social) | Infrastructure for routing requests across multiple LLM providers. Enables dynamic model selection for cost and performance optimization. |

---

## Contributing

Contributions are welcome! If you know of an open-source agentic tool that should be on this list, feel free to open an issue or submit a pull request.

## License

This list is provided under [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/).
