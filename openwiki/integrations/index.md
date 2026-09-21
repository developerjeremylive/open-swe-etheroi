# Files

- [Dashboard, web API, and desktop UI](dashboard-ui.md) - How the mounted dashboard combines a feature-owned FastAPI API, TanStack web client and proxy boundary, thread, schedule, review, and workspace operations, and Electron-supervised local execution.
- [Observability and connected tools](observability-and-mcp.md) - How durable analytics, configurable MCP connections, and Notion MCP are loaded, credential-scoped, secured, cached, and allowed to fail without stopping an agent run. It also records the current status of formerly provider-specific connected tools.
- [Sandbox Provider Integration](sandbox-providers.md) - How Open SWE selects and operates sandbox providers, binds them safely to threads, and handles LangSmith-specific provisioning, credentials, and execution behavior. Covers provider capabilities, local and desktop exceptions, reviewer preparation, and the extension contract.
