# Trainer-Bench

## Project Status
This project was developed as part of an internship and is currently **private due to NDA and company policies**.

---

## 💡 What I Worked On

*   **Architected Trainer-Bench Framework**: Designed and implemented a modular, high-extensibility framework from scratch that transforms static AI benchmarks into dynamic, interactive environments. This allows agentic models to move beyond simple inference and engage in iterative, multi-step problem solving within isolated sandboxes.
*   **Developed Benchmark Adapter Pipelines**: Built a sophisticated ingestion engine using an adapter-based architecture to normalize heterogeneous benchmarks (including **ADE-Bench, Spider2, BFCL, and Deep-Planning**). This involved creating custom parsing logic to map diverse source formats into a single, unified schema for tasks, environments, and validation criteria.
*   **State & Metadata Abstraction for RL**: Engineered a robust abstraction layer to represent complex environment states (e.g., live SQL databases, file systems, and API tools) alongside task-specific metadata. This provides the necessary observability for reinforcement learning agents to track state transitions and receive high-fidelity feedback loops.
*   **Standardized Unified Task Format**: Established a rigorous internal specification for "TaskSets," which encapsulates instructions, required resources, and success metrics. This standardization ensures that any model can be evaluated across a wide variety of domains (data analysis, coding, tool-use) without modifying the underlying training logic.
*   **Groundwork for RL Training Loops**: Laid the foundational architecture for Reinforcement Learning (RL) cycles by defining episode boundaries, implementing reward hooks for automated scoring, and designing a curriculum-based task sampling strategy to facilitate progressive agent learning.
*   **Production-Grade CLI & Developer Tooling**: Developed `tbench`, a professional-grade command-line interface using **Click** and **Rich**. The tool supports advanced developer workflows including local template scaffolding (`create`), remote artifact synchronization (`push/pull`), and interactive TUI-based environment management.
*   **Scalable Backend & Artifact Management**: Architected a FastAPI-based backend capable of managing distributed environment configurations. Implemented a secure artifact distribution system that handles compressed environment snapshots (`.tar.gz`), featuring automated validation and path-traversal protection during extraction.
*   **Database Schema & Lifecycle Orchestration**: Designed a flexible SQL schema (using **SQLAlchemy** and **Pydantic**) to manage the lifecycle of environments and tasksets. This system tracks everything from image configurations and resource limits to real-time status updates and agent performance metrics.

---

## 📈 What I Learned

*   **Bridging Benchmarks and RL**: Gained deep technical expertise in the intersection of LLM evaluation and reinforcement learning, specifically in how to turn "dead" datasets into "live" training environments with actionable reward signals.
*   **System Design for Scalability**: Learned to build systems where the data (benchmarks) and the engine (the framework) are decoupled. This allows for horizontal scaling of tasks and agents without introducing architectural bottlenecks.
*   **Secure Infrastructure for Untrusted Code**: Explored the challenges of running agent-generated code and tool-calls in isolated environments, focusing on secure artifact handling, resource limits, and environment cleanup.
*   **API & CLI Contract Reliability**: Developed a strong understanding of maintaining long-term stability in internal tools by designing versioned API contracts and robust error-handling patterns that provide clear feedback to developers.
*   **Full-Stack Orchestration**: Navigated the complexities of a full-stack system—from low-level file system manipulation and SQL optimization to building responsive, real-time dashboards for monitoring agentic workflows.

---

## 📬 Contact
If you'd like to know more about my experience:

- 📧 Email: jmadhavpai@gmail.com  
- 💼 LinkedIn: [linkedin.com/in/jmadhavpai](https://linkedin.com/in/jmadhavpai)

