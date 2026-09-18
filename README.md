# Wu Zihao / 吴梓豪

**Software Engineering Undergraduate @ Guangdong University of Technology**<br>
**广东工业大学 · 软件工程本科生｜AI 应用开发 / Agent 工程方向**

我主要关注 **AI Application Engineering、Coding Agent、RAG 与 Agent Infrastructure**，持续实践从模型调用、工具使用、上下文管理，到评测、后端服务和复杂业务落地的完整工程链路。

I focus on building practical **AI applications and agent systems**, especially around **Coding Agents, RAG, MCP, tool use, context engineering, evaluation, and production-oriented AI engineering**.

> 目标方向：AI 应用开发 · Agent 开发 · Coding Agent / Agent Harness<br>
> Target roles: AI Application Engineer · Agent Engineer · Coding Agent / Agent Infrastructure

---

## Engineering Focus / 技术主线

- **Coding Agent & Agent Harness** — ReAct、Tool Calling、MCP、Context、Session、Multi-Agent
- **RAG & Evaluation** — Hybrid Search、Reranker、Query Understanding、Bad Case、Benchmark
- **Backend Engineering** — FastAPI、asyncio、REST API、SSE、SQL、任务队列
- **AI Engineering** — Docker、Git、CI/Test、权限治理、可观测性与长期维护
- **Open Source** — 正在通过真实 Issue、PR、Code Review 与复杂代码库持续补充工程经验

---

## Featured Projects / 代表项目

### ForgeTrail — Local Coding Agent Harness

**Coding Agent · ReAct · MCP · Context Management · Multi-Agent · Tool Execution**

一个面向真实软件项目的本地 Coding Agent，重点探索 Agent 如何读取代码、调用工具、修改文件、执行验证，并在长任务中进行上下文压缩、会话恢复和多 Agent 协作。

A Python-based local coding agent for understanding, modifying and validating real software projects.

**Highlights / 核心能力**

- ReAct Agent Loop 与工具执行循环
- Anthropic / OpenAI / Compatible API 多模型协议适配
- MCP 工具按需加载
- 长上下文压缩与 Session Resume
- Multi-Agent、任务板与 Git Worktree
- 文件 / Shell 权限控制与执行治理
- TUI 流式输出与运行状态追踪

[View ForgeTrail →](https://github.com/Misayhuiyi/ForgeTrail)

---

### MedAgent — Agentic RAG for Complex Workflows

**Agentic RAG · Multi-Agent · Retrieval · Skills · FastAPI · SSE · React**

面向复杂文档分析流程的 Agentic RAG 工程实践，包含多阶段 Agent Pipeline、子 Agent 并行、知识库检索、Rerank、Skill 执行、上下文管理与完整前后端交互链路。

An experimental Agentic RAG system for multi-step document analysis and structured report generation.

**Highlights / 核心能力**

- Multi-Agent 任务编排与并行执行
- RAG 检索、Embedding 与 Reranker
- Skill 驱动的多阶段工作流
- Context / Memory 管理
- FastAPI + SSE 流式通信
- React 前端与 Docker 部署
- 运行日志、报告生成与执行追踪

[View MedAgent →](https://github.com/Misayhuiyi/Medagent)

> Engineering and research project only. It is not a clinically validated medical product.<br>
> 该项目仅用于工程与技术研究，不代表经过临床验证的医疗产品。

---

### RAG — Document Retrieval & Evaluation Practice

**Hybrid Search · BM25 · Vector Search · Reranker · Evaluation**

面向企业文档问答场景的 RAG 工程实践，覆盖文档解析与清洗、Chunk、Embedding、BM25 + Vector Hybrid Search、Cross-Encoder Rerank、多轮问答与答案溯源。

A document QA project for exploring practical RAG engineering, retrieval optimization and evaluation.

**Highlights / 核心能力**

- PDF / Word / Markdown 文档处理
- Semantic Chunking
- BM25 + Vector Hybrid Retrieval
- Cross-Encoder Reranking
- Multi-turn Conversation
- Source Attribution
- Bad Case Analysis & Evaluation

[View RAG →](https://github.com/Misayhuiyi/RAG)

---

### Questionnaire & Interview System

**Full Stack · WeChat Mini Program · MySQL · Redis · BullMQ · Docker**

一个覆盖 Web 管理后台、微信小程序、服务端 API、数据库、异步任务和第三方云服务的完整业务系统，用于训练复杂业务工程中的接口、状态、权限、任务队列和部署能力。

A full-stack questionnaire and interview platform covering administration, Mini Program clients, backend APIs, persistence, asynchronous workloads and deployment.

**Highlights / 核心能力**

- Web Admin + 微信小程序
- Backend API 与权限鉴权
- MySQL + Redis
- BullMQ 异步任务
- 文件上传、导出任务与第三方云服务集成
- Docker 容器化
- 健康检查、操作日志与上线前配置检查

[View Project →](https://github.com/Misayhuiyi/WeChat-miniprogram)

---

## Open Source & Engineering / 开源与工程实践

我正在把开源贡献作为复杂工程能力的长期训练方式，重点学习成熟项目中的：

- Issue 分析与 Bug Reproduction
- 调用链与 Root Cause 定位
- Unit / Integration / Regression Testing
- CI 与代码质量检查
- Pull Request 与 Code Review
- API Compatibility 与工程边界
- 长期维护、文档与 Release Workflow

I am learning software engineering through long-lived projects and open-source collaboration, with a focus on understanding real production codebases rather than only building isolated demos.

---

## Tech Stack / 技术栈

**Languages**<br>
`Python` · `TypeScript` · `JavaScript` · `SQL`

**AI / Agent**<br>
`LLM API` · `Agent` · `RAG` · `MCP` · `Tool Calling` · `LangGraph` · `Embedding` · `Reranker`

**Backend**<br>
`FastAPI` · `asyncio` · `REST API` · `SSE` · `SQLAlchemy`

**Infrastructure**<br>
`Docker` · `Git` · `Linux` · `Redis` · `MySQL` · `Vector Database`

---

## Currently Working On / 当前重点

- Production-grade Agent Architecture
- Coding Agent / Agent Harness
- Context Engineering for long-running agents
- RAG Evaluation & Benchmark
- Complex software engineering
- Open-source contribution and collaboration

---

## Contact / 联系方式

- GitHub: [@Misayhuiyi](https://github.com/Misayhuiyi)

---

> **Build real systems. Understand the engineering behind them.**<br>
> 不只让 AI 帮我写代码，也努力理解代码为什么这样设计、如何验证，以及一个系统如何长期演进。
