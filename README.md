# Awesome Agent Harness 🛠️

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of pioneering research papers, tools, and resources on the **Agent Harness** — the systematic execution layer that transforms raw model capability into sustained, long-horizon autonomy.

Survey: ***A Survey on AI Agent Harness*** (coming soon on arXiv)

> **Agent = Model (Stochastic Intelligence) + Harness (Deterministic Infrastructure)**

The survey proposes a **Unified Architectural Taxonomy** that organizes the Agent Harness as a four-layered stack:

- **Layer 1: Execution & Orchestration** — The temporal engine driving the autonomous execution loop, model routing, and multi-agent composition.
- **Layer 2: Context & Trajectory Management** — The epistemic layer governing state compaction, trajectory persistence, memory hierarchies, and observability.
- **Layer 3: Interaction Surface & Execution Environment** — The sensory and actuation organs connecting the agent to the world via tool calling, standardized protocols, and sandboxed execution.
- **Layer 4: Constraints & Guardrails** — The independent observer enforcing deterministic laws through access control, permission management, and defense against agent injection.

Below is a visual representation of this taxonomy:

![Agent Harness: A Four-Layer Architectural Stack](taxonomy.png)

We aim to provide a comprehensive overview for researchers, developers, and infrastructure engineers interested in this rapidly advancing field.

---

## Contents

- [Agent Harness Foundations](#agent-harness-foundations)
- [Layer 1: Execution & Orchestration](#layer-1-execution--orchestration)
  - [Model & Agent Routing](#model--agent-routing)
  - [Multi-Agent Composition & Orchestration](#multi-agent-composition--orchestration)
  - [Autonomous Loop, Resilience & Human-in-the-Loop](#autonomous-loop-resilience--human-in-the-loop)
- [Layer 2: Context & Trajectory Management](#layer-2-context--trajectory-management)
  - [Memory Systems](#memory-systems)
  - [Context Compression](#context-compression)
  - [Trajectory Persistence & Observability](#trajectory-persistence--observability)
  - [Self-Evolving Architectures](#self-evolving-architectures)
  - [Agentic Skills](#agentic-skills)
  - [Skills Security](#skills-security)
- [Layer 3: Interaction Surface & Execution Environment](#layer-3-interaction-surface--execution-environment)
  - [Standardized Protocols & Interaction Surface](#standardized-protocols--interaction-surface)
  - [Tool Use & Code Execution](#tool-use--code-execution)
- [Layer 4: Constraints & Guardrails](#layer-4-constraints--guardrails)
  - [Sandboxing & Execution Environments](#sandboxing--execution-environments)
  - [Governance Boundaries](#governance-boundaries)
  - [Agent Injection & Defense](#agent-injection--defense)
- [Contributing](#contributing)

---

## Agent Harness Foundations

Cross-layer conceptual works that define and motivate the Agent Harness as a first-class research object.

- **Effective Harnesses for Long-Running Agents** — *Young (Anthropic, 2025)* — long-running agent harness management
- **Natural-Language Agent Harnesses** — *Pan et al. (2026)* — natural-language harness design
- **Harness Engineering for Language Agents: The Harness Layer as Control, Agency, and Runtime** — *He et al. (2026)* — harness as control, agency, and runtime layer
- **Building AI Coding Agents for the Terminal: Scaffolding, Harness, Context Engineering, and Lessons Learned** — *Bui (2026)* — terminal coding agent scaffolding, context engineering, lessons learned
- **Harness Engineering: Leveraging Codex in an Agent-First World** — *Lopopolo (2026)* — Codex-based harness engineering
- **The Importance of Agent Harness in 2026** — *Schmid (2026)* — agent harness importance analysis
- **What Is an Agent Harness in the Context of Large-Language Models?** — *Parallel Web Systems (2025)* — agent harness concept overview
- **Meta-Harness: End-to-End Optimization of Model Harnesses** — *Lee et al. (2026)* — end-to-end automated optimization of harness code

---

## Layer 1: Execution & Orchestration

Acting as the **temporal engine** of the harness, Layer 1 drives the autonomous execution loop, manages model routing, orchestrates multi-agent compositions, and enforces resilience mechanisms to maintain forward momentum under failures.

### Model & Agent Routing

Dynamically determining which LLM or specialized agent should handle a given subtask, optimizing for cost, capability, and resource constraints.

- **EvoRoute: Experience-Driven Self-Routing LLM Agent Systems** — *Zhang et al. (2026)* — experience-driven self-routing
- **Best-Route: Adaptive LLM Routing with Test-Time Optimal Compute** — *Ding et al. (2025)* — test-time optimal compute routing
- **MASRouter: Learning to Route LLMs for Multi-Agent Systems** — *Yue et al. (2025)* — multi-agent system routing learning
- **Adaptive Vision-Language Model Routing for Computer Use Agents** — *Liu et al. (2026)* — adaptive VLM routing for computer use
- **CAMAR: Continuous Actions Multi-Agent Routing** — *Pshenitsyn et al. (2026)* — continuous-action multi-agent routing
- **SkillOrchestra: Learning to Route Agents via Skill Transfer** — *Wang et al. (2026)* — skill-transfer-based agent routing
- **DyTopo: Dynamic Topology Routing for Multi-Agent Reasoning via Semantic Matching** — *Lu et al. (2026)* — semantic-matching topology routing
- **Orchestrating Intelligence: Confidence-Aware Routing for Efficient Multi-Agent Collaboration across Multi-Scale Models** — *Wang et al. (2026)* — confidence-aware multi-scale routing
- **Learning Query-Aware Budget-Tier Routing for Runtime Agent Memory** — *Zhang et al. (2026)* — query-aware budget-tier memory routing
- **CASTER: Breaking the Cost-Performance Barrier in Multi-Agent Orchestration via Context-Aware Strategy for Task Efficient Routing** — *Liu et al. (2026)* — context-aware task-efficient routing
- **Budget-Aware Agentic Routing via Boundary-Guided Training** — *Zhang et al. (2026)* — boundary-guided budget-aware routing
- **ODAR: Principled Adaptive Routing for LLM Reasoning via Active Inference** — *Ma et al. (2026)* — active-inference adaptive routing
- **Optimal-Agent-Selection: State-Aware Routing Framework for Efficient Multi-Agent Collaboration** — *Wang et al. (2025)* — state-aware optimal agent selection
- **Towards Generalized Routing: Model and Agent Orchestration for Adaptive and Efficient Inference** — *Guo et al. (2025)* — generalized model-agent orchestration

### Multi-Agent Composition & Orchestration

Treating agents as composable, modular entities and orchestrating concurrent subagent spawning, delegation, and synchronized state handoffs.

- **Compass: Enhancing Agent Long-Horizon Reasoning with Evolving Context** — *Wan et al. (2025)* — evolving context for long-horizon reasoning
- **Claude Subagents** — *Anthropic (2025)* — custom AI subagent spawning [![Open Source](https://img.shields.io/badge/Open%20Source-✓-green)]()
- **Kimi K2.5: Visual Agentic Intelligence** — *Kimi Team (2026)* — visual agentic intelligence
- **Swarm: An Educational Framework for Lightweight Multi-Agent Orchestration** — *OpenAI (2024)* — lightweight multi-agent orchestration [![Open Source](https://img.shields.io/badge/Open%20Source-✓-green)]()
- **CrewAI: Framework for Orchestrating Role-Playing Autonomous AI Agents** — *Moura (2025)* — role-playing agent orchestration [![Open Source](https://img.shields.io/badge/Open%20Source-✓-green)]()
- **A Declarative Language for Building and Orchestrating LLM-Powered Agent Workflows** — *Daunis (2025)* — declarative agent workflow language
- **Orchestral AI: A Framework for Agent Orchestration** — *Roman et al. (2026)* — general-purpose agent orchestration

### Autonomous Loop, Resilience & Human-in-the-Loop

Ensuring the execution loop is resilient to non-termination and drift, and managing the spectrum from full human oversight to closed-loop autonomy.

- **Adaptive Fault Tolerance Mechanisms of Large Language Models in Cloud Computing Environments** — *Jin et al. (2025)* — adaptive fault tolerance in cloud LLMs
- **ESAA: Event Sourcing for Autonomous Agents in LLM-Based Software Engineering** — *dos Santos Filho (2026)* — event sourcing for autonomous agents
- **Human-in-the-Loop or AI-in-the-Loop? Automate or Collaborate?** — *Natarajan et al. (2025)* — human-in-the-loop vs AI-in-the-loop
- **Combining LLM, Non-Monotonic Logical Reasoning, and Human-in-the-Loop Feedback in an Assistive AI Agent** — *Fu et al. (2025)* — LLM + non-monotonic reasoning + HITL
- **Enabling Self-Improving Agents to Learn at Test Time with Human-in-the-Loop Guidance** — *He et al. (2025)* — test-time learning with human guidance
- **PlanAgent: A Multi-Modal Large Language Agent for Closed-Loop Vehicle Motion Planning** — *Zheng et al. (2026)* — closed-loop vehicle motion planning
- **A Multi-AI Agent System for Autonomous Optimization of Agentic AI Solutions via Iterative Refinement and LLM-Driven Feedback Loops** — *Yuksel et al. (2025)* — iterative refinement via LLM feedback
- **Towards LLM-Enabled Autonomous Combustion Research: A Literature-Aware Agent for Self-Corrective Modeling Workflows** — *Xiao et al. (2026)* — autonomous combustion research agent
- **From LLM Reasoning to Autonomous AI Agents: A Comprehensive Review** — *Ferrag et al. (2025)* — LLM reasoning to autonomous agents survey

---

## Layer 2: Context & Trajectory Management

While the orchestration layer manages execution time, Layer 2 governs the agent's **epistemic space** — mitigating context window saturation, catastrophic forgetting, and maintaining strict observability.

### Memory Systems

Structured, queryable knowledge layers ranging from production-ready platforms to research prototypes.

- **Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory** — *Chhikara et al. (2025)* — scalable production long-term memory [![Open Source](https://img.shields.io/badge/Open%20Source-✓-green)]()
- **Zep: A Temporal Knowledge Graph Architecture for Agent Memory** — *Rasmussen et al. (2025)* — temporal knowledge graph memory [![Open Source](https://img.shields.io/badge/Open%20Source-✓-green)]()
- **Memory Is All You Need: Testing How Model Memory Affects LLM Performance in Annotation Tasks** — *Timoneda et al. (2025)* — memory effects on LLM annotation
- **AMemGym: Interactive Memory Benchmarking for Assistants in Long-Horizon Conversations** — *Jiayang et al. (2026)* — interactive memory benchmarking
- **Evaluating Memory in LLM Agents via Incremental Multi-Turn Interactions** — *Hu et al. (2025)* — incremental multi-turn memory eval
- **Nemori: Self-Organizing Agent Memory Inspired by Cognitive Science** — *Nan et al. (2025)* — self-organizing cognitive memory
- **MemGPT: Towards LLMs as Operating Systems** — *Packer et al. (2023)* — LLM as operating system with memory tiers [![Open Source](https://img.shields.io/badge/Open%20Source-✓-green)]()
- **A-Mem: Agentic Memory for LLM Agents** — *Xu et al. (2025)* — agentic self-organizing memory
- **MemAgent: Reshaping Long-Context LLM with Multi-Conv RL-Based Memory Agent** — *Yu et al. (2025)* — multi-conv RL-based memory agent
- **G-Memory: Tracing Hierarchical Memory for Multi-Agent Systems** — *Zhang et al. (2025)* — hierarchical multi-agent memory tracing
- **HippoRAG: Neurobiologically Inspired Long-Term Memory for Large Language Models** — *Gutiérrez et al. (2024)* — neurobiological long-term memory [![Open Source](https://img.shields.io/badge/Open%20Source-✓-green)]()
- **SimpleMem: Efficient Lifelong Memory for LLM Agents** — *Liu et al. (2026)* — efficient lifelong memory for agents
- **General Agentic Memory via Deep Research** — *Yan et al. (2025)* — agentic memory via deep research
- **Choosing How to Remember: Adaptive Memory Structures for LLM Agents** — *Lu et al. (2026)* — adaptive memory structure selection
- **From Lossy to Verified: A Provenance-Aware Tiered Memory for Agents** — *Zhu et al. (2026)* — provenance-aware tiered memory
- **Lifelong Learning of Large Language Model Based Agents: A Roadmap** — *Zheng et al. (2026)* — lifelong learning roadmap for agents
- **Memory Poisoning Attack and Defense on Memory Based LLM-Agents** — *Sunil et al. (2026)* — memory poisoning attack and defense

### Context Compression

Strategies to prevent **Context Rot** — the progressive degradation of reasoning quality due to accumulated irrelevant tokens.

- **ACON: Optimizing Context Compression for Long-Horizon LLM Agents** — *Kang et al. (2025)* — long-horizon agent context compression
- **LongLLMLingua: Accelerating and Enhancing LLMs in Long Context Scenarios via Prompt Compression** — *Jiang et al. (2024)* — prompt compression via token scoring
- **Scaling LLM Multi-Turn RL with End-to-End Summarization-Based Context Management** — *Lu et al. (2025)* — summarization-based context management
- **LongCodeBench: Evaluating Coding LLMs at 1M Context Windows** — *Rando et al. (2025)* — 1M-token coding evaluation
- **Scaling Long-Horizon LLM Agent via Context-Folding** — *Sun et al. (2025)* — hierarchical trajectory folding
- **Pretraining Context Compressor for Large Language Models with Embedding-Based Memory** — *Dai et al. (2025)* — embedding-based context compressor
- **SWE-Pruner: Self-Adaptive Context Pruning for Coding Agents** — *Wang et al. (2026)* — self-adaptive context pruning for code
- **The Complexity Trap: Simple Observation Masking Is as Efficient as LLM Summarization for Agent Context Management** — *Lindenbauer et al. (2025)* — observation masking vs summarization
- **LongCodeZip: Compress Long Context for Code Language Models** — *Shi et al. (2025)* — long-context code compression
- **Mem1: Learning to Synergize Memory and Reasoning for Efficient Long-Horizon Agents** — *Zhou et al. (2025)* — synergize memory and reasoning
- **ContextBench: A Benchmark for Context Retrieval in Coding Agents** — *Li et al. (2026)* — context retrieval benchmarking
- **MemRL: Self-Evolving Agents via Runtime Reinforcement Learning on Episodic Memory** — *Zhang et al. (2026)* — runtime RL on episodic memory
- **HiAgent: Hierarchical Working Memory Management for Solving Long-Horizon Agent Tasks with Large Language Model** — *Hu et al. (2025)* — hierarchical working memory management
- **SWE Context Bench: A Benchmark for Context Learning in Coding** — *Zhu et al. (2026)* — context learning benchmarking
- **SafeSieve: From Heuristics to Experience in Progressive Pruning for LLM-Based Multi-Agent Communication** — *Zhang et al. (2026)* — progressive multi-agent comm pruning

### Trajectory Persistence & Observability

Persisting the agent's execution history to external storage for recovery, replay, and continuous learning, while decoupling observability from the model's working memory.

- **Improving the Efficiency of LLM Agent Systems through Trajectory Reduction** — *Xiao et al. (2025)* — trajectory reduction for efficiency
- **Semantic Checkpointing for Stateless LLM Agents in Multi-Tenant Enterprise Systems** — *Roshan et al. (2025)* — semantic checkpointing for stateless agents
- **Large-Scale Evaluation of Notebook Checkpointing with AI Agents** — *Fang et al. (2025)* — notebook checkpointing evaluation
- **AgentTrace: A Structured Logging Framework for Agent System Observability** — *AlSayyad et al. (2026)* — structured logging for observability
- **AgentSight: System-Level Observability for AI Agents Using eBPF** — *Zheng et al. (2025)* — eBPF-based system-level observability
- **LangGraph Durable Execution** — *LangChain (2026)* — fault-tolerant durable execution [![Open Source](https://img.shields.io/badge/Open%20Source-✓-green)]()

### Self-Evolving Architectures

Agent systems that improve their own capabilities, prompts, or memory structures at test time or through continuous interaction.

- **Darwin Godel Machine** — *Zhang et al. (2025)* — open-ended self-improving evolution
- **Your Agent May Misevolve: Emergent Risks in Self-Evolving LLM Agents** — *Shao et al. (2025)* — emergent risks in self-evolution
- **Live-SWE-Agent: Can Software Engineering Agents Self-Evolve on the Fly?** — *Xia et al. (2025)* — on-the-fly SWE agent self-evolution
- **Agentic Context Engineering: Evolving Contexts for Self-Improving Language Models** — *Zhang et al. (2025)* — evolving contexts for self-improvement
- **GEPA: Reflective Prompt Evolution Can Outperform Reinforcement Learning** — *Agrawal et al. (2025)* — reflective prompt evolution
- **Dynamic Cheatsheet: Test-Time Learning with Adaptive Memory** — *Suzgun et al. (2026)* — test-time learning with adaptive memory
- **Adaptive Self-Improvement LLM Agentic System for ML Library Development** — *Zhang et al. (2025)* — self-improvement for ML library dev
- **AccelOpt: A Self-Improving LLM Agentic System for AI Accelerator Kernel Optimization** — *Zhang et al. (2025)* — self-improving kernel optimization
- **AgentFly: Fine-Tuning LLM Agents without Fine-Tuning LLMs** — *Zhou et al. (2025)* — fine-tuning agents without LLM FT
- **Multi-Agent Evolve: LLM Self-Improve through Co-Evolution** — *Chen et al. (2025)* — LLM self-improve through co-evolution
- **RAGEN: Understanding Self-Evolution in LLM Agents via Multi-Turn Reinforcement Learning** — *Wang et al. (2025)* — self-evolution via multi-turn RL
- **Evo-Memory: Benchmarking LLM Agent Test-Time Learning with Self-Evolving Memory** — *Wei et al. (2025)* — benchmarking test-time self-evolving memory
- **WebEvolver: Enhancing Web Agent Self-Improvement with Co-Evolving World Model** — *Fang et al. (2025)* — co-evolving web world model
- **SEAgent: Self-Evolving Computer Use Agent** — *Sun et al. (2025)* — self-evolving computer use agent
- **Self-Evolving Multi-Agent Simulations for Realistic Clinical Interactions** — *Almansoori et al. (2025)* — self-evolving clinical simulations
- **EvoAgent: Continual World Model for Long-Horizon Tasks** — *Feng et al. (2025)* — continual world model for long-horizon
- **Tool-R0: Self-Evolving Tool Learning from Zero** — *Acikgoz et al. (2026)* — self-evolving tool learning from zero
- **EvoTool: Blame-Aware Tool-Use Optimization** — *Yang et al. (2026)* — blame-aware tool-use optimization
- **AutoSkill: Experience-Driven Lifelong Skill Evolution** — *Yang et al. (2026)* — experience-driven lifelong skill evolution
- **MemSkill: Learning and Evolving Memory Skills** — *Zhang et al. (2026)* — learning and evolving memory skills
- **EvoConfig: Self-Evolving Multi-Agent Configuration** — *Guo et al. (2026)* — self-evolving multi-agent configuration
- **Over-Searching in Search-Augmented LLMs** — *Xie et al. (2026)* — over-searching in search-augmented LLMs

### Agentic Skills

Modular, reusable capabilities that agents acquire, compose, and execute to extend their action space.

- **Inducing Programmatic Skills for LLM Agents** — *Wang et al. (2025)* — inducing programmatic skills
- **SkillCraft: Tool-Use Skill Learning Evaluation** — *Chen et al. (2026)* — tool-use skill learning evaluation
- **SoK: Systematization of Agentic Skills** — *Jiang et al. (2026)* — systematization of agentic skills
- **SkillReducer: Token-Efficient Skill Optimization** — *Gao et al. (2026)* — token-efficient skill optimization
- **Skill Architecture, Acquisition, and Security** — *Xu et al. (2026)* — skill architecture, acquisition, security
- **Data-Driven Claude Skill Analysis** — *Ling et al. (2026)* — data-driven Claude skill analysis
- **SkillRouter: Retrieve-and-Rerank Skill Selection** — *Zheng et al. (2026)* — retrieve-and-rerank skill selection
- **Single-Agent Skills vs Multi-Agent** — *Li (2026)* — single-agent skills vs multi-agent
- **EvoSkill: Automated Multi-Agent Skill Discovery** — *Alzubi et al. (2026)* — automated multi-agent skill discovery
- **SkillsBench: Skill Benchmarking across Diverse Tasks** — *Li et al. (2026)* — skill benchmarking across diverse tasks
- **CUA-Skill: Skills for Computer-Using Agents** — *Chen et al. (2026)* — skills for computer-using agents
- **Claude Skills** — *Anthropic (2025)* — agent skill platform launch [![Open Source](https://img.shields.io/badge/Open%20Source-✓-green)]()
- **SAGE: RL-Based Self-Improving Skill Library** — *Wang et al. (2025)* — RL-based self-improving skill library
- **Compositional Skill Synthesis** — *Jiao et al. (2026)* — compositional skill synthesis
- **Gemini CLI: CLI-Based Agent Skills** — *Google (2025)* — CLI-based agent skills [![Open Source](https://img.shields.io/badge/Open%20Source-✓-green)]()

### Skills Security

Security vulnerabilities and defenses related to agentic skill systems and skill-based prompt injection.

- **Skill-Based Prompt Injection Analysis** — *Schmotz et al. (2025)* — skill-based prompt injection analysis
- **Skill Security Vulnerabilities at Scale** — *Liu et al. (2026)* — skill security vulnerabilities at scale
- **Malicious Skill Detection Study** — *Liu et al. (2026)* — malicious skill detection study
- **Hidden-Comment Skill Injection** — *Wang et al. (2026)* — hidden-comment skill injection
- **Zombie Skills: Persistent Control via Self-Reinforcing Injection** — *Yang et al. (2026)* — persistent control via self-reinforcing injection

---

## Layer 3: Interaction Surface & Execution Environment

Because language models are inherently disembodied, Layer 3 constitutes the **sensory and actuation organs** of the agentic system — standardizing interfaces for tool calling and code execution, and enforcing hardware-level isolation.

### Standardized Protocols & Interaction Surface

Defining and standardizing how agents interact with tools, APIs, and external environments.

- **From Language to Action: A Review of Large Language Models as Autonomous Agents and Tool Users** — *Chowa et al. (2026)* — LLM as autonomous agent review
- **Defining and Detecting the Defects of Large Language Model-Based Autonomous Agents** — *Ning et al. (2026)* — LLM agent defect detection
- **LLM Agents Making Agent Tools** — *Wölflein et al. (2025)* — agents making agent tools
- **UTCP Code-Mode: Plug-and-Play Library to Enable Agents to Call MCP and UTCP Tools via Code Execution** — *Universal Tool Calling Protocol (2026)* — MCP/UTCP via code execution [![Open Source](https://img.shields.io/badge/Open%20Source-✓-green)]()
- **UI-TARS: Pioneering Automated GUI Interaction with Native Agents** — *Qin et al. (2025)* — native automated GUI interaction [![Open Source](https://img.shields.io/badge/Open%20Source-✓-green)]()
- **GeoJSON Agents: A Multi-Agent LLM Architecture for Geospatial Analysis — Function Calling vs. Code Generation** — *Luo et al. (2026)* — function calling vs code generation
- **Beyond Perfect APIs: A Comprehensive Evaluation of LLM Agents Under Real-World API Complexity** — *Kim et al. (2026)* — real-world API complexity evaluation

### Tool Use & Code Execution

Benchmarks and methods for evaluating and improving agent tool use capabilities.

- **WebOperator: Action-Aware Tree Search for Autonomous Agents in Web Environment** — *Dihan et al. (2025)* — action-aware web tree search
- **Terminal-Bench: Benchmarking Agents on Hard, Realistic Tasks in Command Line Interfaces** — *Merrill et al. (2026)* — CLI task benchmarking
- **Budget-Constrained Agentic Large Language Models: Intention-Based Planning for Costly Tool Use** — *Liu et al. (2026)* — budget-constrained tool planning
- **ToolSandbox: A Stateful, Conversational, Interactive Evaluation Benchmark for LLM Tool Use Capabilities** — *Lu et al. (2025)* — stateful tool-use evaluation

---

## Layer 4: Constraints & Guardrails

Because LLM outputs are inherently probabilistic, Layer 4 acts as an **independent observer and judge** — imposing deterministic laws of physics and security boundaries on the system, operating entirely out-of-band.

### Sandboxing & Execution Environments

Isolating agent execution to contain erratic behaviors and protect host infrastructure.

- **The Two Patterns by Which Agents Connect Sandboxes** — *LangChain (2026)* — agent-sandbox connection patterns
- **SWE-MiniSandbox: Container-Free Reinforcement Learning for Building Software Engineering Agents** — *Yuan et al. (2026)* — container-free RL sandbox
- **UI-TARS-2: Advancing GUI Agent with Multi-Turn Reinforcement Learning** — *Wang et al. (2025)* — multi-turn RL GUI agent sandbox
- **LLM-in-Sandbox Elicits General Agentic Intelligence** — *Cheng et al. (2026)* — sandbox for agentic intelligence
- **Sari Sandbox: A Virtual Retail Store Environment for Embodied AI Agents** — *Gajo et al. (2025)* — virtual retail store environment
- **SandboxSocial: A Sandbox for Social Media Using Multimodal AI Agents** — *Touzel et al. (2025)* — social media simulation sandbox
- **Cellmate: Sandboxing Browser AI Agents** — *Meng et al. (2025)* — browser AI agent sandboxing
- **AgentBay: A Hybrid Interaction Sandbox for Seamless Human-AI Intervention in Agentic Systems** — *Piao et al. (2025)* — hybrid human-AI interaction sandbox
- **Static Sandboxes Are Inadequate: Modeling Societal Complexity Requires Open-Ended Co-Evolution in LLM-Based Multi-Agent Simulations** — *Chen et al. (2025)* — static sandboxes are inadequate; open-ended co-evolution needed
- **DeepResearchGym: A Free, Transparent, and Reproducible Evaluation Sandbox for Deep Research** — *Coelho et al. (2025)* — reproducible deep research evaluation
- **SWE-World: Building Software Engineering Agents in Docker-Free Environments** — *Sun et al. (2026)* — Docker-free SWE environments
- **R2E-Gym: Procedural Environments and Hybrid Verifiers for Scaling Open-Weights SWE Agents** — *Jain et al. (2025)* — procedural environments with hybrid verifiers

### Governance Boundaries

Enforcing access control, permission management, and policy compliance for agent actions.

- **POLARIS: Typed Planning and Governed Execution for Agentic AI in Back-Office Automation** — *Moslemi et al. (2026)* — typed planning and governed execution
- **ContextCov: Deriving and Enforcing Executable Constraints from Agent Instruction Files** — *Sharma (2026)* — executable constraint enforcement
- **Sandbox-Runtime: A Lightweight Sandboxing Tool for Enforcing Filesystem and Network Restrictions** — *Anthropic (2026)* — OS-level filesystem/network sandboxing [![Open Source](https://img.shields.io/badge/Open%20Source-✓-green)]()
- **Securing AI Agent Execution** — *Bühler et al. (2025)* — agent execution security analysis
- **BashArena: A Control Setting for Highly Privileged AI Agents** — *Kaufman et al. (2025)* — highly-privileged agent control setting
- **Breaking the Protocol: Security Analysis of the Model Context Protocol Specification and Prompt Injection Vulnerabilities in Tool-Integrated LLM Agents** — *Maloyan et al. (2026)* — MCP specification security analysis

### Agent Injection & Defense

Defending against adversarial prompt injection attacks targeting agentic systems.

- **Skill-Inject: Measuring Agent Vulnerability to Skill File Attacks** — *Schmotz et al. (2026)* — skill file attack measurement
- **AgentDyn: A Dynamic Open-Ended Benchmark for Evaluating Prompt Injection Attacks of Real-World Agent Security System** — *Li et al. (2026)* — dynamic prompt injection benchmark
- **WebSentinel: Detecting and Localizing Prompt Injection Attacks for Web Agents** — *Wang et al. (2026)* — web agent injection detection
- **ReasAlign: Reasoning Enhanced Safety Alignment against Prompt Injection Attack** — *Li et al. (2026)* — reasoning-enhanced injection safety
- **From Assistant to Double Agent: Formalizing and Benchmarking Attacks on OpenClaw for Personalized Local AI Agent** — *Wang et al. (2026)* — formalizing attacks on OpenClaw for personalized local agents
- **Taming OpenClaw: Security Analysis and Mitigation of Autonomous LLM Agent Threats** — *Deng et al. (2026)* — OpenClaw security analysis and mitigation
- **Uncovering Security Threats and Architecting Defenses in Autonomous Agents: A Case Study of OpenClaw** — *Ying et al. (2026)* — OpenClaw threat architecture and defenses
- **ClawKeeper: Comprehensive Safety Protection for OpenClaw Agents Through Skills, Plugins, and Watchers** — *Liu et al. (2026)* — comprehensive safety via skills, plugins, and watchers
- **A Trajectory-Based Safety Audit of ClawdBot (OpenClaw)** — *Chen et al. (2026)* — trajectory-based safety audit
- **OpenClaw PRISM: A Zero-Fork, Defense-in-Depth Runtime Security Layer for Tool-Augmented LLM Agents** — *Li (2026)* — zero-fork defense-in-depth runtime
- **OpenClaw Agents on Moltbook: Risky Instruction Sharing and Norm Enforcement in an Agent-Only Social Network** — *Manik et al. (2026)* — risky instruction sharing and norm enforcement in agent networks

---

## Contributing

We welcome contributions! If you have a paper, tool, or resource that belongs in this list, please open a pull request or issue.

When adding a new paper, please follow the format:
```
- **Paper Title** — *Author et al. (Year)* — brief description
```

Please ensure the paper is directly relevant to the Agent Harness infrastructure (orchestration, context management, execution environments, or guardrails).

---

*This repository is maintained in conjunction with the survey paper **"A Survey on AI Agent Harness"**.*
