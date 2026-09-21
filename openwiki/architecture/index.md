# Files

- [Coding-agent graph assembly](agent-graph.md) - How the primary Deep Agents coding graph is prepared for an executable thread run, including configuration, sandbox and skill backends, model policy, tool surfaces, subagents, and middleware safety controls.
- [Middleware stack and failure policy](middleware-stack.md) - Ordering-sensitive middleware around coding-agent and reviewer model and tool loops. Covers preparation, dynamic tools, policy enforcement, queues, retry and timeout boundaries, and conversion of failures into user-visible outcomes.
- [Runtime architecture and product surfaces](overview.md) - How Open SWE's LangGraph deployment, FastAPI ingress, durable run dispatch, persistence, and cloud and desktop clients work together across execution boundaries.
- [Review and review-style learning graphs](reviewer-and-analyzer.md) - Architecture of the isolated reviewer and review-style analyzer graphs, covering PR preparation, durable findings and publication, repository-specific style learning, and continual analysis scheduling.
- [Thread Sandbox Lifecycle](sandbox-lifecycle.md) - How an agent thread acquires, binds, reconnects to, and safely replaces its sandbox. Covers provider provisioning, workspace preparation, GitHub proxy credentials, and the distinct recovery policy for coding and review work.
