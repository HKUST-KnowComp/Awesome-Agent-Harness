# Awesome Agent Harness 🛠️


[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Stars](https://img.shields.io/github/stars/HKUST-KnowComp/Awesome-Agent-Harness?style=social)]()
[![Papers](https://img.shields.io/badge/Papers-164-brightgreen)]()
[![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--04-blue)]()
[![License](https://img.shields.io/badge/License-MIT-yellow)]()


A curated list of pioneering research papers, tools, and resources on the **Agent Harness** — the systematic execution layer that transforms raw model capability into sustained, long-horizon autonomy.

[![arXiv](https://img.shields.io/badge/Paper-Coming%20Soon-red?logo=arxiv)]()
[![PDF Preview](https://img.shields.io/badge/PDF-Preview-blue?logo=adobeacrobatreader&logoColor=white)](Agent_Harness_Survey.pdf)

***A Survey on AI Agent Harness***

> **Agent = Model (Stochastic Intelligence) + Harness (Deterministic Infrastructure)**

The survey proposes a **Unified Architectural Taxonomy** that organizes the Agent Harness as a four-layered stack:

- **Layer 1: Execution & Orchestration** — The temporal engine driving the autonomous execution loop, model routing, and multi-agent composition.
- **Layer 2: Context & Trajectory Management** — The epistemic layer governing state compaction, trajectory persistence, memory hierarchies, and observability.
- **Layer 3: Interaction Surface & Execution Environment** — The sensory and actuation organs connecting the agent to the world via tool calling, standardized protocols, and sandboxed execution.
- **Layer 4: Constraints & Guardrails** — The independent observer enforcing deterministic laws through access control, permission management, and defense against agent injection.

The figure below illustrates the **asymmetric co-evolution** between model capability and harness responsibility:

![Model-Harness Asymmetric Co-evolution](taxonomy.png)

We aim to provide a comprehensive overview for researchers, developers, and infrastructure engineers interested in this rapidly advancing field.

---


## Contents

- [Agent Harness Foundations](#agent-harness-foundations)
  - [Model & Agent Routing](#model--agent-routing)
  - [Multi-Agent Composition & Orchestration](#multi-agent-composition--orchestration)
  - [Autonomous Loop, Resilience & Human-in-the-Loop](#autonomous-loop-resilience--human-in-the-loop)
  - [Memory Systems](#memory-systems)
  - [Context Compression](#context-compression)
  - [Trajectory Persistence & Observability](#trajectory-persistence--observability)
  - [Self-Evolving Architectures](#self-evolving-architectures)
  - [Agentic Skills](#agentic-skills)
  - [Skills Security](#skills-security)
  - [Standardized Protocols & Interaction Surface](#standardized-protocols--interaction-surface)
  - [Tool Use & Code Execution](#tool-use--code-execution)
  - [Sandboxing & Execution Environments](#sandboxing--execution-environments)
  - [Governance Boundaries](#governance-boundaries)
  - [Agent Injection & Defense](#agent-injection--defense)

---

## Agent Harness Foundations

Cross-layer conceptual works that define and motivate the Agent Harness as a first-class research object.

<table>
<thead><tr><th width="45%">Title</th><th width="20%">Author</th><th width="5%">Year</th><th width="30%">Description</th></tr></thead>
<tbody>
<tr><td><a href="https://www.anthropic.com/engineering/effective-harnesses-for-long-running-agents">Effective harnesses for long-running agents</a> <img src="https://img.shields.io/badge/Blog-orange?logo=rss" alt="Blog"></td><td>Young et al.</td><td>2025</td><td>long-running agent harness management</td></tr>
<tr><td><a href="https://arxiv.org/abs/2603.25723">Natural-Language Agent Harnesses</a></td><td>Pan et al.</td><td>2026</td><td>natural-language harness design</td></tr>
<tr><td><a href="https://www.preprints.org/manuscript/202603.1756">Harness Engineering for Language Agents: The Harness Layer as Control, Agency, and Runtime</a></td><td>He et al.</td><td>2026</td><td>harness as control, agency, and runtime layer</td></tr>
<tr><td><a href="https://arxiv.org/abs/2603.05344">Building AI Coding Agents for the Terminal: Scaffolding, Harness, Context Engineering, and Lessons Learned</a></td><td>Bui et al.</td><td>2026</td><td>terminal coding agent scaffolding, context engineering, lessons learned</td></tr>
<tr><td><a href="https://openai.com/index/harness-engineering/">Harness engineering: leveraging Codex in an agent-first world</a> <img src="https://img.shields.io/badge/Blog-orange?logo=rss" alt="Blog"></td><td>Lopopolo et al.</td><td>2026</td><td>Codex-based harness engineering</td></tr>
<tr><td><a href="https://www.philschmid.de/agent-harness-2026">The importance of Agent Harness in 2026</a> <img src="https://img.shields.io/badge/Blog-orange?logo=rss" alt="Blog"></td><td>Schmid et al.</td><td>2026</td><td>agent harness importance analysis</td></tr>
<tr><td><a href="https://parallel.ai/articles/what-is-an-agent-harness">What is an agent harness in the context of large-language models?</a> <img src="https://img.shields.io/badge/Blog-orange?logo=rss" alt="Blog"></td><td>Parallel Web Systems et al.</td><td>2025</td><td>agent harness concept overview</td></tr>
<tr><td><a href="https://arxiv.org/abs/2603.28052">Meta-Harness: End-to-End Optimization of Model Harnesses</a></td><td>Lee et al.</td><td>2026</td><td>end-to-end automated optimization of harness code</td></tr>
</tbody></table>


## Layer 1: Execution & Orchestration

Acting as the **temporal engine** of the harness, Layer 1 drives the autonomous execution loop, manages model routing, orchestrates multi-agent compositions, and enforces resilience mechanisms to maintain forward momentum under failures.

### Model & Agent Routing

Dynamically determining which LLM or specialized agent should handle a given subtask, optimizing for cost, capability, and resource constraints.

<table>
<thead><tr><th width="45%">Title</th><th width="20%">Author</th><th width="5%">Year</th><th width="30%">Description</th></tr></thead>
<tbody>
<tr><td><a href="https://arxiv.org/abs/2601.02695">EvoRoute: Experience-Driven Self-Routing LLM Agent Systems</a></td><td>Zhang et al.</td><td>2026</td><td>experience-driven self-routing</td></tr>
<tr><td><a href="https://arxiv.org/abs/2506.22716">Best-route: Adaptive llm routing with test-time optimal compute</a></td><td>Ding et al.</td><td>2025</td><td>test-time optimal compute routing</td></tr>
<tr><td><a href="https://arxiv.org/abs/2502.11133">Masrouter: Learning to route llms for multi-agent systems</a></td><td>Yue et al.</td><td>2025</td><td>multi-agent system routing learning</td></tr>
<tr><td><a href="https://arxiv.org/abs/2603.12823">Adaptive vision-language model routing for computer use agents</a></td><td>Liu et al.</td><td>2026</td><td>adaptive VLM routing for computer use</td></tr>
<tr><td><a href="https://arxiv.org/abs/2508.12845">Camar: Continuous actions multi-agent routing</a></td><td>Pshenitsyn et al.</td><td>2026</td><td>continuous-action multi-agent routing</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.19672">SkillOrchestra: Learning to Route Agents via Skill Transfer</a></td><td>Wang et al.</td><td>2026</td><td>skill-transfer-based agent routing</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.06039">DyTopo: Dynamic Topology Routing for Multi-Agent Reasoning via Semantic Matching</a></td><td>Lu et al.</td><td>2026</td><td>semantic-matching topology routing</td></tr>
<tr><td><a href="https://arxiv.org/abs/2601.04861">Orchestrating Intelligence: Confidence-Aware Routing for Efficient Multi-Agent Collaboration across Multi-Scale Models</a></td><td>Wang et al.</td><td>2026</td><td>confidence-aware multi-scale routing</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.06025">Learning Query-Aware Budget-Tier Routing for Runtime Agent Memory</a></td><td>Zhang et al.</td><td>2026</td><td>query-aware budget-tier memory routing</td></tr>
<tr><td><a href="https://arxiv.org/abs/2601.19793">CASTER: Breaking the Cost-Performance Barrier in Multi-Agent Orchestration via Context-Aware Strategy for Task Efficient Routing</a></td><td>Liu et al.</td><td>2026</td><td>context-aware task-efficient routing</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.21227">Budget-aware agentic routing via boundary-guided training</a></td><td>Zhang et al.</td><td>2026</td><td>boundary-guided budget-aware routing</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.23681">ODAR: Principled Adaptive Routing for LLM Reasoning via Active Inference</a></td><td>Ma et al.</td><td>2026</td><td>active-inference adaptive routing</td></tr>
<tr><td><a href="https://arxiv.org/abs/2511.02200">Optimal-agent-selection: State-aware routing framework for efficient multi-agent collaboration</a></td><td>Wang et al.</td><td>2025</td><td>state-aware optimal agent selection</td></tr>
<tr><td><a href="https://arxiv.org/abs/2509.07571">Towards generalized routing: Model and agent orchestration for adaptive and efficient inference</a></td><td>Guo et al.</td><td>2025</td><td>generalized model-agent orchestration</td></tr>
</tbody></table>


### Multi-Agent Composition & Orchestration

Treating agents as composable, modular entities and orchestrating concurrent subagent spawning, delegation, and synchronized state handoffs.

<table>
<thead><tr><th width="45%">Title</th><th width="20%">Author</th><th width="5%">Year</th><th width="30%">Description</th></tr></thead>
<tbody>
<tr><td><a href="https://docs.anthropic.com/en/docs/claude-code/subagents">Claude Code Subagents</a> <img src="https://img.shields.io/badge/Blog-orange?logo=rss" alt="Blog"></td><td>Anthropic</td><td>2025</td><td>custom AI subagent spawning</td></tr>
<tr><td><a href="https://arxiv.org/abs/2510.08790">Compass: Enhancing agent long-horizon reasoning with evolving context</a></td><td>Wan et al.</td><td>2025</td><td>evolving context for long-horizon reasoning</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.02276">Kimi K2. 5: Visual Agentic Intelligence</a></td><td>Team et al.</td><td>2026</td><td>visual agentic intelligence</td></tr>
<tr><td><a href="https://github.com/openai/swarm">Swarm: An educational framework exploring ergonomic, lightweight multi-agent orchestration</a> <img src="https://img.shields.io/badge/Code-black?logo=github" alt="Code"></td><td>OpenAI et al.</td><td>2024</td><td>lightweight multi-agent orchestration</td></tr>
<tr><td><a href="https://github.com/crewAIInc/crewAI">CrewAI: Framework for orchestrating role-playing autonomous AI agents</a> <img src="https://img.shields.io/badge/Code-black?logo=github" alt="Code"></td><td>Moura et al.</td><td>2025</td><td>role-playing agent orchestration</td></tr>
<tr><td><a href="https://arxiv.org/abs/2512.19769">A Declarative Language for Building And Orchestrating LLM-Powered Agent Workflows</a></td><td>Daunis et al.</td><td>2025</td><td>declarative agent workflow language</td></tr>
<tr><td><a href="https://arxiv.org/abs/2601.02577">Orchestral AI: A Framework for Agent Orchestration</a></td><td>Roman et al.</td><td>2026</td><td>general-purpose agent orchestration</td></tr>
</tbody></table>


### Autonomous Loop, Resilience & Human-in-the-Loop

Ensuring the execution loop is resilient to non-termination and drift, and managing the spectrum from full human oversight to closed-loop autonomy.

<table>
<thead><tr><th width="45%">Title</th><th width="20%">Author</th><th width="5%">Year</th><th width="30%">Description</th></tr></thead>
<tbody>
<tr><td><a href="https://arxiv.org/abs/2412.14232">Human-in-the-Loop or AI-in-the-Loop? Automate or Collaborate?</a></td><td>Natarajan et al.</td><td>2025</td><td>human-in-the-loop vs AI-in-the-loop</td></tr>
<tr><td><a href="https://arxiv.org/abs/2503.12228">Adaptive fault tolerance mechanisms of large language models in cloud computing environments</a></td><td>Jin et al.</td><td>2025</td><td>adaptive fault tolerance in cloud LLMs</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.23193">ESAA: Event Sourcing for Autonomous Agents in LLM-Based Software Engineering</a></td><td>dos Santos Filho et al.</td><td>2026</td><td>event sourcing for autonomous agents</td></tr>
<tr><td><a href="https://ieeexplore.ieee.org/abstract/document/11217618/">Combining LLM, Non-monotonic Logical Reasoning, and Human-in-the-loop Feedback in an Assistive AI Agent</a></td><td>Fu et al.</td><td>2025</td><td>LLM + non-monotonic reasoning + HITL</td></tr>
<tr><td><a href="https://arxiv.org/abs/2507.17131">Enabling self-improving agents to learn at test time with human-in-the-loop guidance</a></td><td>He et al.</td><td>2025</td><td>test-time learning with human guidance</td></tr>
<tr><td><a href="https://arxiv.org/abs/2406.01587">Planagent: A multi-modal large language agent for closed-loop vehicle motion planning</a></td><td>Zheng et al.</td><td>2026</td><td>closed-loop vehicle motion planning</td></tr>
<tr><td><a href="https://arxiv.org/abs/2412.17149">A multi-AI agent system for autonomous optimization of agentic AI solutions via iterative refinement and LLM-driven feedback loops</a></td><td>Yuksel et al.</td><td>2025</td><td>iterative refinement via LLM feedback</td></tr>
<tr><td><a href="https://arxiv.org/abs/2601.01357">Towards LLM-enabled autonomous combustion research: A literature-aware agent for self-corrective modeling workflows</a></td><td>Xiao et al.</td><td>2026</td><td>autonomous combustion research agent</td></tr>
<tr><td><a href="https://arxiv.org/abs/2504.19678">From llm reasoning to autonomous ai agents: A comprehensive review</a></td><td>Ferrag et al.</td><td>2025</td><td>LLM reasoning to autonomous agents survey</td></tr>
</tbody></table>


## Layer 2: Context & Trajectory Management

While the orchestration layer manages execution time, Layer 2 governs the agent's **epistemic space** — mitigating context window saturation, catastrophic forgetting, and maintaining strict observability.

### Memory Systems

Structured, queryable knowledge layers ranging from production-ready platforms to research prototypes.

<table>
<thead><tr><th width="45%">Title</th><th width="20%">Author</th><th width="5%">Year</th><th width="30%">Description</th></tr></thead>
<tbody>
<tr><td><a href="https://arxiv.org/abs/2504.19413">Mem0: Building production-ready ai agents with scalable long-term memory</a></td><td>Chhikara et al.</td><td>2025</td><td>scalable production long-term memory</td></tr>
<tr><td><a href="https://arxiv.org/abs/2501.13956">Zep: a temporal knowledge graph architecture for agent memory</a></td><td>Rasmussen et al.</td><td>2025</td><td>temporal knowledge graph memory</td></tr>
<tr><td><a href="https://arxiv.org/abs/2503.04874">Memory is all you need: Testing how model memory affects llm performance in annotation tasks</a></td><td>Timoneda et al.</td><td>2025</td><td>memory effects on LLM annotation</td></tr>
<tr><td><a href="https://arxiv.org/abs/2603.01966">AMemGym: Interactive Memory Benchmarking for Assistants in Long-Horizon Conversations</a></td><td>Jiayang et al.</td><td>2026</td><td>interactive memory benchmarking</td></tr>
<tr><td><a href="https://arxiv.org/abs/2507.05257">Evaluating memory in llm agents via incremental multi-turn interactions</a></td><td>Hu et al.</td><td>2025</td><td>incremental multi-turn memory eval</td></tr>
<tr><td><a href="https://arxiv.org/abs/2508.03341">Nemori: Self-organizing agent memory inspired by cognitive science</a></td><td>Nan et al.</td><td>2025</td><td>self-organizing cognitive memory</td></tr>
<tr><td><a href="https://arxiv.org/abs/2310.08560">MemGPT: towards LLMs as operating systems.</a></td><td>Packer et al.</td><td>2023</td><td>LLM as operating system with memory tiers</td></tr>
<tr><td><a href="https://arxiv.org/abs/2502.12110">A-mem: Agentic memory for llm agents</a></td><td>Xu et al.</td><td>2025</td><td>agentic self-organizing memory</td></tr>
<tr><td><a href="https://arxiv.org/abs/2507.02259">Memagent: Reshaping long-context llm with multi-conv rl-based memory agent</a></td><td>Yu et al.</td><td>2025</td><td>multi-conv RL-based memory agent</td></tr>
<tr><td><a href="https://arxiv.org/abs/2506.07398">G-memory: Tracing hierarchical memory for multi-agent systems</a></td><td>Zhang et al.</td><td>2025</td><td>hierarchical multi-agent memory tracing</td></tr>
<tr><td><a href="https://arxiv.org/abs/2405.14831">Hipporag: Neurobiologically inspired long-term memory for large language models</a></td><td>Gutierrez et al.</td><td>2024</td><td>neurobiological long-term memory</td></tr>
<tr><td><a href="https://arxiv.org/abs/2601.02553">SimpleMem: Efficient Lifelong Memory for LLM Agents</a></td><td>Liu et al.</td><td>2026</td><td>efficient lifelong memory for agents</td></tr>
<tr><td><a href="https://arxiv.org/abs/2511.18423">General agentic memory via deep research</a></td><td>Yan et al.</td><td>2025</td><td>agentic memory via deep research</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.14038">Choosing How to Remember: Adaptive Memory Structures for LLM Agents</a></td><td>Lu et al.</td><td>2026</td><td>adaptive memory structure selection</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.17913">From Lossy to Verified: A Provenance-Aware Tiered Memory for Agents</a></td><td>Zhu et al.</td><td>2026</td><td>provenance-aware tiered memory</td></tr>
<tr><td><a href="https://arxiv.org/abs/2501.07278">Lifelong learning of large language model based agents: A roadmap</a></td><td>Zheng et al.</td><td>2026</td><td>lifelong learning roadmap for agents</td></tr>
<tr><td><a href="https://arxiv.org/abs/2601.05504">Memory Poisoning Attack and Defense on Memory Based LLM-Agents</a></td><td>Sunil et al.</td><td>2026</td><td>memory poisoning attack and defense</td></tr>
</tbody></table>


### Context Compression

Strategies to prevent **Context Rot** — the progressive degradation of reasoning quality due to accumulated irrelevant tokens.

<table>
<thead><tr><th width="45%">Title</th><th width="20%">Author</th><th width="5%">Year</th><th width="30%">Description</th></tr></thead>
<tbody>
<tr><td><a href="https://arxiv.org/abs/2510.00615">Acon: Optimizing context compression for long-horizon llm agents</a></td><td>Kang et al.</td><td>2025</td><td>long-horizon agent context compression</td></tr>
<tr><td><a href="https://arxiv.org/abs/2310.06839">Longllmlingua: Accelerating and enhancing llms in long context scenarios via prompt compression</a></td><td>Jiang et al.</td><td>2024</td><td>prompt compression via token scoring</td></tr>
<tr><td><a href="https://arxiv.org/abs/2510.06727">Scaling llm multi-turn rl with end-to-end summarization-based context management</a></td><td>Lu et al.</td><td>2025</td><td>summarization-based context management</td></tr>
<tr><td><a href="https://arxiv.org/abs/2505.07897">Longcodebench: Evaluating coding llms at 1m context windows</a></td><td>Rando et al.</td><td>2025</td><td>1M-token coding evaluation</td></tr>
<tr><td><a href="https://arxiv.org/abs/2510.11967">Scaling long-horizon llm agent via context-folding</a></td><td>Sun et al.</td><td>2025</td><td>hierarchical trajectory folding</td></tr>
<tr><td><a href="https://aclanthology.org/2025.acl-long.1394/">Pretraining context compressor for large language models with embedding-based memory</a></td><td>Dai et al.</td><td>2025</td><td>embedding-based context compressor</td></tr>
<tr><td><a href="https://arxiv.org/abs/2601.16746">SWE-Pruner: Self-Adaptive Context Pruning for Coding Agents</a></td><td>Wang et al.</td><td>2026</td><td>self-adaptive context pruning for code</td></tr>
<tr><td><a href="https://arxiv.org/abs/2508.21433">The Complexity Trap: Simple Observation Masking Is as Efficient as LLM Summarization for Agent Context Management</a></td><td>Lindenbauer et al.</td><td>2025</td><td>observation masking vs summarization</td></tr>
<tr><td><a href="https://arxiv.org/abs/2510.00446">Longcodezip: Compress long context for code language models</a></td><td>Shi et al.</td><td>2025</td><td>long-context code compression</td></tr>
<tr><td><a href="https://arxiv.org/abs/2506.15841">Mem1: Learning to synergize memory and reasoning for efficient long-horizon agents</a></td><td>Zhou et al.</td><td>2025</td><td>synergize memory and reasoning</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.05892">ContextBench: A Benchmark for Context Retrieval in Coding Agents</a></td><td>Li et al.</td><td>2026</td><td>context retrieval benchmarking</td></tr>
<tr><td><a href="https://arxiv.org/abs/2601.03192">Memrl: Self-evolving agents via runtime reinforcement learning on episodic memory</a></td><td>Zhang et al.</td><td>2026</td><td>runtime RL on episodic memory</td></tr>
<tr><td><a href="https://arxiv.org/abs/2408.09559">Hiagent: Hierarchical working memory management for solving long-horizon agent tasks with large language model</a></td><td>Hu et al.</td><td>2025</td><td>hierarchical working memory management</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.08316">SWE Context Bench: A Benchmark for Context Learning in Coding</a></td><td>Zhu et al.</td><td>2026</td><td>context learning benchmarking</td></tr>
<tr><td><a href="https://arxiv.org/abs/2508.11733">Safesieve: From heuristics to experience in progressive pruning for llm-based multi-agent communication</a></td><td>Zhang et al.</td><td>2026</td><td>progressive multi-agent comm pruning</td></tr>
</tbody></table>


### Trajectory Persistence & Observability

Persisting the agent's execution history to external storage for recovery, replay, and continuous learning, while decoupling observability from the model's working memory.

<table>
<thead><tr><th width="45%">Title</th><th width="20%">Author</th><th width="5%">Year</th><th width="30%">Description</th></tr></thead>
<tbody>
<tr><td><a href="https://arxiv.org/abs/2509.23586">Reducing Cost of LLM Agents with Trajectory Reduction</a></td><td>Xiao et al.</td><td>2025</td><td>trajectory reduction for efficiency</td></tr>
<tr><td><a href="https://www.researchgate.net/publication/399433967_Semantic_Checkpointing_for_Stateless_LLM_Agents_Semantic_Checkpointing_for_Stateless_LLM_Agents_in_Multi-Tenant_Enterprise_Systems">Semantic Checkpointing for Stateless LLM Agents in Multi-Tenant Enterprise Systems</a></td><td>Roshan et al.</td><td>2025</td><td>semantic checkpointing for stateless agents</td></tr>
<tr><td><a href="https://arxiv.org/abs/2504.01377">Large-scale Evaluation of Notebook Checkpointing with AI Agents</a></td><td>Fang et al.</td><td>2025</td><td>notebook checkpointing evaluation</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.10133">AgentTrace: A Structured Logging Framework for Agent System Observability</a></td><td>AlSayyad et al.</td><td>2026</td><td>structured logging for observability</td></tr>
<tr><td><a href="https://arxiv.org/abs/2508.02736">AgentSight: System-Level Observability for AI Agents Using eBPF</a></td><td>Zheng et al.</td><td>2025</td><td>eBPF-based system-level observability</td></tr>
<tr><td><a href="https://docs.langchain.com/oss/python/langgraph/durable-execution">Durable Execution in LangGraph</a> <img src="https://img.shields.io/badge/Blog-orange?logo=rss" alt="Blog"></td><td>LangChain et al.</td><td>2026</td><td>fault-tolerant durable execution</td></tr>
</tbody></table>


### Self-Evolving Architectures

Agent systems that improve their own capabilities, prompts, or memory structures at test time or through continuous interaction.

<table>
<thead><tr><th width="45%">Title</th><th width="20%">Author</th><th width="5%">Year</th><th width="30%">Description</th></tr></thead>
<tbody>
<tr><td><a href="https://arxiv.org/abs/2505.22954">Darwin godel machine: Open-ended evolution of self-improving agents</a></td><td>Zhang et al.</td><td>2025</td><td>open-ended self-improving evolution</td></tr>
<tr><td><a href="https://arxiv.org/abs/2509.26354">Your agent may misevolve: Emergent risks in self-evolving llm agents</a></td><td>Shao et al.</td><td>2025</td><td>emergent risks in self-evolution</td></tr>
<tr><td><a href="https://arxiv.org/abs/2511.13646">Live-SWE-agent: Can Software Engineering Agents Self-Evolve on the Fly?</a></td><td>Xia et al.</td><td>2025</td><td>on-the-fly SWE agent self-evolution</td></tr>
<tr><td><a href="https://arxiv.org/abs/2510.04618">Agentic context engineering: Evolving contexts for self-improving language models</a></td><td>Zhang et al.</td><td>2025</td><td>evolving contexts for self-improvement</td></tr>
<tr><td><a href="https://arxiv.org/abs/2507.19457">Gepa: Reflective prompt evolution can outperform reinforcement learning</a></td><td>Agrawal et al.</td><td>2025</td><td>reflective prompt evolution</td></tr>
<tr><td><a href="https://arxiv.org/abs/2504.07952">Dynamic cheatsheet: Test-time learning with adaptive memory</a></td><td>Suzgun et al.</td><td>2026</td><td>test-time learning with adaptive memory</td></tr>
<tr><td><a href="https://arxiv.org/abs/2502.02534">Adaptive self-improvement llm agentic system for ml library development</a></td><td>Zhang et al.</td><td>2025</td><td>self-improvement for ML library dev</td></tr>
<tr><td><a href="https://arxiv.org/abs/2511.15915">AccelOpt: A Self-Improving LLM Agentic System for AI Accelerator Kernel Optimization</a></td><td>Zhang et al.</td><td>2025</td><td>self-improving kernel optimization</td></tr>
<tr><td><a href="https://arxiv.org/abs/2508.16153">Memento: Fine-tuning LLM Agents without Fine-tuning LLMs</a></td><td>Zhou et al.</td><td>2025</td><td>fine-tuning agents without LLM FT</td></tr>
<tr><td><a href="https://arxiv.org/abs/2510.23595">Multi-agent evolve: Llm self-improve through co-evolution</a></td><td>Chen et al.</td><td>2025</td><td>LLM self-improve through co-evolution</td></tr>
<tr><td><a href="https://arxiv.org/abs/2504.20073">Ragen: Understanding self-evolution in llm agents via multi-turn reinforcement learning</a></td><td>Wang et al.</td><td>2025</td><td>self-evolution via multi-turn RL</td></tr>
<tr><td><a href="https://arxiv.org/abs/2511.20857">Evo-memory: Benchmarking llm agent test-time learning with self-evolving memory</a></td><td>Wei et al.</td><td>2025</td><td>benchmarking test-time self-evolving memory</td></tr>
<tr><td><a href="https://arxiv.org/abs/2504.21024">WebEvolver: Enhancing Web Agent Self-Improvement with Co-evolving World Model</a></td><td>Fang et al.</td><td>2025</td><td>co-evolving web world model</td></tr>
<tr><td><a href="https://arxiv.org/abs/2508.04700">SEAgent: Self-Evolving Computer Use Agent with Autonomous Learning from Experience</a></td><td>Sun et al.</td><td>2025</td><td>self-evolving computer use agent</td></tr>
<tr><td><a href="https://arxiv.org/abs/2503.22678">Self-evolving multi-agent simulations for realistic clinical interactions</a></td><td>Almansoori et al.</td><td>2025</td><td>self-evolving clinical simulations</td></tr>
<tr><td><a href="https://arxiv.org/abs/2502.05907">EvoAgent: Self-evolving Agent with Continual World Model for Long-Horizon Tasks</a></td><td>Feng et al.</td><td>2025</td><td>continual world model for long-horizon</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.21320">Tool-R0: Self-Evolving LLM Agents for Tool-Learning from Zero Data</a></td><td>Acikgoz et al.</td><td>2026</td><td>self-evolving tool learning from zero</td></tr>
<tr><td><a href="https://arxiv.org/abs/2603.04900">EvoTool: Self-evolving tool-use policy optimization in llm agents via blame-aware mutation and diversity-aware selection</a></td><td>Yang et al.</td><td>2026</td><td>blame-aware tool-use optimization</td></tr>
<tr><td><a href="https://arxiv.org/abs/2603.01145">AutoSkill: Experience-Driven Lifelong Learning via Skill Self-Evolution</a></td><td>Yang et al.</td><td>2026</td><td>experience-driven lifelong skill evolution</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.02474">MemSkill: Learning and Evolving Memory Skills for Self-Evolving Agents</a></td><td>Zhang et al.</td><td>2026</td><td>learning and evolving memory skills</td></tr>
<tr><td><a href="https://arxiv.org/abs/2601.16489">EvoConfig: Self-Evolving Multi-Agent Systems for Efficient Autonomous Environment Configuration</a></td><td>Guo et al.</td><td>2026</td><td>self-evolving multi-agent configuration</td></tr>
<tr><td><a href="https://arxiv.org/abs/2601.05503">Over-Searching in Search-Augmented Large Language Models</a></td><td>Xie et al.</td><td>2026</td><td>over-searching in search-augmented LLMs</td></tr>
</tbody></table>


### Agentic Skills

Modular, reusable capabilities that agents acquire, compose, and execute to extend their action space.

<table>
<thead><tr><th width="45%">Title</th><th width="20%">Author</th><th width="5%">Year</th><th width="30%">Description</th></tr></thead>
<tbody>
<tr><td><a href="https://arxiv.org/abs/2504.06821">Inducing programmatic skills for agentic tasks</a></td><td>Wang et al.</td><td>2025</td><td>inducing programmatic skills</td></tr>
<tr><td><a href="https://arxiv.org/abs/2603.00718">SkillCraft: Can LLM Agents Learn to Use Tools Skillfully?</a></td><td>Chen et al.</td><td>2026</td><td>tool-use skill learning evaluation</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.20867">SoK: Agentic Skills--Beyond Tool Use in LLM Agents</a></td><td>Jiang et al.</td><td>2026</td><td>systematization of agentic skills</td></tr>
<tr><td><a href="https://arxiv.org/abs/2603.29919">SkillReducer: Optimizing LLM Agent Skills for Token Efficiency</a></td><td>Gao et al.</td><td>2026</td><td>token-efficient skill optimization</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.12430">Agent skills for large language models: Architecture, acquisition, security, and the path forward</a></td><td>Xu et al.</td><td>2026</td><td>skill architecture, acquisition, security</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.08004">Agent Skills: A Data-Driven Analysis of Claude Skills for Extending Large Language Model Functionality</a></td><td>Ling et al.</td><td>2026</td><td>data-driven Claude skill analysis</td></tr>
<tr><td><a href="https://arxiv.org/abs/2603.22455">SkillRouter: Retrieve-and-Rerank Skill Selection for LLM Agents at Scale</a></td><td>Zheng et al.</td><td>2026</td><td>retrieve-and-rerank skill selection</td></tr>
<tr><td><a href="https://arxiv.org/abs/2601.04748">When single-agent with skills replace multi-agent systems and when they fail</a></td><td>Li et al.</td><td>2026</td><td>single-agent skills vs multi-agent</td></tr>
<tr><td><a href="https://arxiv.org/abs/2603.02766">EvoSkill: Automated Skill Discovery for Multi-Agent Systems</a></td><td>Alzubi et al.</td><td>2026</td><td>automated multi-agent skill discovery</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.12670">SkillsBench: Benchmarking how well agent skills work across diverse tasks</a></td><td>Li et al.</td><td>2026</td><td>skill benchmarking across diverse tasks</td></tr>
<tr><td><a href="https://arxiv.org/abs/2601.21123">Cua-skill: Develop skills for computer using agent</a></td><td>Chen et al.</td><td>2026</td><td>skills for computer-using agents</td></tr>
<tr><td><a href="https://www.anthropic.com/news/skills">Introducing Agent Skills</a> <img src="https://img.shields.io/badge/Blog-orange?logo=rss" alt="Blog"></td><td>Anthropic et al.</td><td>2025</td><td>agent skill platform launch</td></tr>
<tr><td><a href="https://arxiv.org/abs/2512.17102">Reinforcement Learning for Self-Improving Agent with Skill Library</a></td><td>Wang et al.</td><td>2025</td><td>RL-based self-improving skill library</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.03279">Agentic Proposing: Enhancing Large Language Model Reasoning via Compositional Skill Synthesis</a></td><td>Jiao et al.</td><td>2026</td><td>compositional skill synthesis</td></tr>
<tr><td><a href="https://arxiv.org/abs/2604.08377">SkillClaw: Let Skills Evolve Collectively with Agentic Evolver</a></td><td>Ma et al.</td><td>2026</td><td>collective skill evolution via cloud sharing</td></tr>
</tbody></table>


### Skills Security

Security vulnerabilities and defenses related to agentic skill systems and skill-based prompt injection.

<table>
<thead><tr><th width="45%">Title</th><th width="20%">Author</th><th width="5%">Year</th><th width="30%">Description</th></tr></thead>
<tbody>
<tr><td><a href="https://arxiv.org/abs/2510.26328">Agent Skills Enable a New Class of Realistic and Trivially Simple Prompt Injections</a></td><td>Schmotz et al.</td><td>2025</td><td>skill-based prompt injection analysis</td></tr>
<tr><td><a href="https://arxiv.org/abs/2601.10338">Agent Skills in the Wild: An Empirical Study of Security Vulnerabilities at Scale</a></td><td>Liu et al.</td><td>2026</td><td>skill security vulnerabilities at scale</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.06547">Malicious Agent Skills in the Wild: A Large-Scale Security Empirical Study</a></td><td>Liu et al.</td><td>2026</td><td>malicious skill detection study</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.10498">When Skills Lie: Hidden-Comment Injection in LLM Agents</a></td><td>Wang et al.</td><td>2026</td><td>hidden-comment skill injection</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.15654">Zombie Agents: Persistent Control of Self-Evolving LLM Agents via Self-Reinforcing Injections</a></td><td>Yang et al.</td><td>2026</td><td>persistent control via self-reinforcing injection</td></tr>
</tbody></table>


## Layer 3: Interaction Surface & Execution Environment

Because language models are inherently disembodied, Layer 3 constitutes the **sensory and actuation organs** of the agentic system — standardizing interfaces for tool calling and code execution, and enforcing hardware-level isolation.

### Standardized Protocols & Interaction Surface

Defining and standardizing how agents interact with tools, APIs, and external environments.

<table>
<thead><tr><th width="45%">Title</th><th width="20%">Author</th><th width="5%">Year</th><th width="30%">Description</th></tr></thead>
<tbody>
<tr><td><a href="https://arxiv.org/abs/2508.17281">From language to action: a review of large language models as autonomous agents and tool users</a></td><td>Chowa et al.</td><td>2026</td><td>LLM as autonomous agent review</td></tr>
<tr><td><a href="https://arxiv.org/abs/2412.18371">Defining and Detecting the Defects of Large Language Model-based Autonomous Agents</a></td><td>Ning et al.</td><td>2026</td><td>LLM agent defect detection</td></tr>
<tr><td><a href="https://arxiv.org/abs/2502.11705">Llm agents making agent tools</a></td><td>Wolflein et al.</td><td>2025</td><td>agents making agent tools</td></tr>
<tr><td><a href="https://github.com/universal-tool-calling-protocol/code-mode">Code-Mode: Plug-and-play library to enable agents to call MCP and UTCP tools via code execution</a> <img src="https://img.shields.io/badge/Code-black?logo=github" alt="Code"></td><td>Protocol et al.</td><td>2026</td><td>MCP/UTCP via code execution</td></tr>
<tr><td><a href="https://arxiv.org/abs/2501.12326">Ui-tars: Pioneering automated gui interaction with native agents</a></td><td>Qin et al.</td><td>2025</td><td>native automated GUI interaction</td></tr>
<tr><td><a href="https://www.tandfonline.com/doi/full/10.1080/20964471.2026.2615511">GeoJSON agents: a multi-agent LLM architecture for geospatial analysis—function calling vs. code generation</a></td><td>Luo et al.</td><td>2026</td><td>function calling vs code generation</td></tr>
<tr><td><a href="https://arxiv.org/abs/2601.00268">Beyond Perfect APIs: A Comprehensive Evaluation of LLM Agents Under Real-World API Complexity</a></td><td>Kim et al.</td><td>2026</td><td>real-world API complexity evaluation</td></tr>
<tr><td><a href="https://arxiv.org/abs/2604.02369">Beyond Message Passing: Toward Semantically Aligned Agent Communication</a></td><td>Yuan et al.</td><td>2026</td><td>semantically aligned agent communication</td></tr>
<tr><td><a href="https://arxiv.org/abs/2505.12490">Improving Google A2A Protocol: Protecting Sensitive Data and Mitigating Unintended Harms in Multi-Agent Systems</a></td><td>Louck et al.</td><td>2025</td><td>A2A protocol sensitive data protection</td></tr>
<tr><td><a href="https://openreview.net/pdf?id=LfdFnakqGJ">A2ASecBench: A Protocol-Aware Security Benchmark for Agent-to-Agent Multi-Agent Systems</a></td><td>Li et al.</td><td>2026</td><td>protocol-aware A2A security benchmark</td></tr>
</tbody></table>


### Tool Use & Code Execution

Benchmarks and methods for evaluating and improving agent tool use capabilities.

<table>
<thead><tr><th width="45%">Title</th><th width="20%">Author</th><th width="5%">Year</th><th width="30%">Description</th></tr></thead>
<tbody>
<tr><td><a href="https://arxiv.org/abs/2512.12692">WebOperator: Action-Aware Tree Search for Autonomous Agents in Web Environment</a></td><td>Dihan et al.</td><td>2025</td><td>action-aware web tree search</td></tr>
<tr><td><a href="https://arxiv.org/abs/2601.11868">Terminal-bench: Benchmarking agents on hard, realistic tasks in command line interfaces</a></td><td>Merrill et al.</td><td>2026</td><td>CLI task benchmarking</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.11541">Budget-Constrained Agentic Large Language Models: Intention-Based Planning for Costly Tool Use</a></td><td>Liu et al.</td><td>2026</td><td>budget-constrained tool planning</td></tr>
<tr><td><a href="https://arxiv.org/abs/2408.04682">Toolsandbox: A stateful, conversational, interactive evaluation benchmark for llm tool use capabilities</a></td><td>Lu et al.</td><td>2025</td><td>stateful tool-use evaluation</td></tr>
</tbody></table>


## Layer 4: Constraints & Guardrails

Because LLM outputs are inherently probabilistic, Layer 4 acts as an **independent observer and judge** — imposing deterministic laws of physics and security boundaries on the system, operating entirely out-of-band.

### Sandboxing & Execution Environments

Isolating agent execution to contain erratic behaviors and protect host infrastructure.

<table>
<thead><tr><th width="45%">Title</th><th width="20%">Author</th><th width="5%">Year</th><th width="30%">Description</th></tr></thead>
<tbody>
<tr><td><a href="https://blog.langchain.dev/the-two-patterns-by-which-agents-connect-sandboxes/">The two patterns by which agents connect sandboxes</a> <img src="https://img.shields.io/badge/Blog-orange?logo=rss" alt="Blog"></td><td>LangChain et al.</td><td>2026</td><td>agent-sandbox connection patterns</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.11210">SWE-MiniSandbox: Container-Free Reinforcement Learning for Building Software Engineering Agents</a></td><td>Yuan et al.</td><td>2026</td><td>container-free RL sandbox</td></tr>
<tr><td><a href="https://arxiv.org/abs/2509.02544">Ui-tars-2 technical report: Advancing gui agent with multi-turn reinforcement learning</a></td><td>Wang et al.</td><td>2025</td><td>multi-turn RL GUI agent sandbox</td></tr>
<tr><td><a href="https://arxiv.org/abs/2601.16206">Computer Environments Elicit General Agentic Intelligence in LLMs</a></td><td>Cheng et al.</td><td>2026</td><td>sandbox for agentic intelligence</td></tr>
<tr><td><a href="https://arxiv.org/abs/2508.00400">Sari Sandbox: A Virtual Retail Store Environment for Embodied AI Agents</a></td><td>Gajo et al.</td><td>2025</td><td>virtual retail store environment</td></tr>
<tr><td><a href="https://www.ijcai.org/proceedings/2025/1271">SandboxSocial: A Sandbox for Social Media Using Multimodal AI Agents</a></td><td>Touzel et al.</td><td>2025</td><td>social media simulation sandbox</td></tr>
<tr><td><a href="https://arxiv.org/abs/2512.12594">cellmate: Sandboxing browser ai agents</a></td><td>Meng et al.</td><td>2025</td><td>browser AI agent sandboxing</td></tr>
<tr><td><a href="https://arxiv.org/abs/2512.04367">AgentBay: A Hybrid Interaction Sandbox for Seamless Human-AI Intervention in Agentic Systems</a></td><td>Piao et al.</td><td>2025</td><td>hybrid human-AI interaction sandbox</td></tr>
<tr><td><a href="https://arxiv.org/abs/2510.13982">Static Sandboxes Are Inadequate: Modeling Societal Complexity Requires Open-Ended Co-Evolution in LLM-Based Multi-Agent Simulations</a></td><td>Chen et al.</td><td>2025</td><td>static sandboxes are inadequate; open-ended co-evolution needed</td></tr>
<tr><td><a href="https://arxiv.org/abs/2505.19253">Deepresearchgym: A free, transparent, and reproducible evaluation sandbox for deep research</a></td><td>Coelho et al.</td><td>2025</td><td>reproducible deep research evaluation</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.03419">SWE-World: Building Software Engineering Agents in Docker-Free Environments</a></td><td>Sun et al.</td><td>2026</td><td>Docker-free SWE environments</td></tr>
<tr><td><a href="https://arxiv.org/abs/2504.07164">R2e-gym: Procedural environments and hybrid verifiers for scaling open-weights swe agents</a></td><td>Jain et al.</td><td>2025</td><td>procedural environments with hybrid verifiers</td></tr>
</tbody></table>


### Governance Boundaries

Enforcing access control, permission management, and policy compliance for agent actions.

<table>
<thead><tr><th width="45%">Title</th><th width="20%">Author</th><th width="5%">Year</th><th width="30%">Description</th></tr></thead>
<tbody>
<tr><td><a href="https://arxiv.org/abs/2601.11816">POLARIS: Typed Planning and Governed Execution for Agentic AI in Back-Office Automation</a></td><td>Moslemi et al.</td><td>2026</td><td>typed planning and governed execution</td></tr>
<tr><td><a href="https://arxiv.org/abs/2603.00822">ContextCov: Deriving and Enforcing Executable Constraints from Agent Instruction Files</a></td><td>Sharma et al.</td><td>2026</td><td>executable constraint enforcement</td></tr>
<tr><td><a href="https://github.com/anthropic-experimental/sandbox-runtime">Sandbox-runtime: A lightweight sandboxing tool for enforcing filesystem and network restrictions on arbitrary processes at the OS level, without requiring a container</a> <img src="https://img.shields.io/badge/Code-black?logo=github" alt="Code"></td><td>Anthropic et al.</td><td>2026</td><td>OS-level filesystem/network sandboxing</td></tr>
<tr><td><a href="https://arxiv.org/abs/2510.21236">Securing AI Agent Execution</a></td><td>Buhler et al.</td><td>2025</td><td>agent execution security analysis</td></tr>
<tr><td><a href="https://arxiv.org/abs/2512.15688">BashArena: A Control Setting for Highly Privileged AI Agents</a></td><td>Kaufman et al.</td><td>2025</td><td>highly-privileged agent control setting</td></tr>
<tr><td><a href="https://arxiv.org/abs/2601.17549">Breaking the Protocol: Security Analysis of the Model Context Protocol Specification and Prompt Injection Vulnerabilities in Tool-Integrated LLM Agents</a></td><td>Maloyan et al.</td><td>2026</td><td>MCP specification security analysis</td></tr>
</tbody></table>


### Agent Injection & Defense

Defending against adversarial prompt injection attacks targeting agentic systems.

<table>
<thead><tr><th width="45%">Title</th><th width="20%">Author</th><th width="5%">Year</th><th width="30%">Description</th></tr></thead>
<tbody>
<tr><td><a href="https://arxiv.org/abs/2602.20156">Skill-Inject: Measuring Agent Vulnerability to Skill File Attacks</a></td><td>Schmotz et al.</td><td>2026</td><td>skill file attack measurement</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.03117">AgentDyn: A Dynamic Open-Ended Benchmark for Evaluating Prompt Injection Attacks of Real-World Agent Security System</a></td><td>Li et al.</td><td>2026</td><td>dynamic prompt injection benchmark</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.03792">WebSentinel: Detecting and Localizing Prompt Injection Attacks for Web Agents</a></td><td>Wang et al.</td><td>2026</td><td>web agent injection detection</td></tr>
<tr><td><a href="https://arxiv.org/abs/2601.10173">ReasAlign: Reasoning Enhanced Safety Alignment against Prompt Injection Attack</a></td><td>Li et al.</td><td>2026</td><td>reasoning-enhanced injection safety</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.08412">From assistant to double agent: Formalizing and benchmarking attacks on openclaw for personalized local ai agent</a></td><td>Wang et al.</td><td>2026</td><td>formalizing attacks on OpenClaw for personalized local agents</td></tr>
<tr><td><a href="https://arxiv.org/abs/2603.11619">Taming OpenClaw: Security Analysis and Mitigation of Autonomous LLM Agent Threats</a></td><td>Deng et al.</td><td>2026</td><td>OpenClaw security analysis and mitigation</td></tr>
<tr><td><a href="https://arxiv.org/abs/2603.12644">Uncovering Security Threats and Architecting Defenses in Autonomous Agents: A Case Study of OpenClaw</a></td><td>Ying et al.</td><td>2026</td><td>OpenClaw threat architecture and defenses</td></tr>
<tr><td><a href="https://arxiv.org/abs/2603.24414">ClawKeeper: Comprehensive Safety Protection for OpenClaw Agents Through Skills, Plugins, and Watchers</a></td><td>Liu et al.</td><td>2026</td><td>comprehensive safety via skills, plugins, and watchers</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.14364">A trajectory-based safety audit of clawdbot (openclaw)</a></td><td>Chen et al.</td><td>2026</td><td>trajectory-based safety audit</td></tr>
<tr><td><a href="https://arxiv.org/abs/2603.11853">OpenClaw PRISM: A Zero-Fork, Defense-in-Depth Runtime Security Layer for Tool-Augmented LLM Agents</a></td><td>Li et al.</td><td>2026</td><td>zero-fork defense-in-depth runtime</td></tr>
<tr><td><a href="https://arxiv.org/abs/2602.02625">OpenClaw Agents on Moltbook: Risky Instruction Sharing and Norm Enforcement in an Agent-Only Social Network</a></td><td>Manik et al.</td><td>2026</td><td>risky instruction sharing and norm enforcement in agent networks</td></tr>
</tbody></table>


---

## Contributing

Contributions are welcome! To add a paper, open a pull request with the new entry added to the relevant section, following the format below:

> Title-Year-Brief description

Please ensure the paper is directly relevant to the Agent Harness infrastructure.

---

*This repository is maintained in conjunction with the survey paper **"A Survey on AI Agent Harness"**.*
