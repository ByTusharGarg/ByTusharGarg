## Hi, I'm Tushar Garg 👋

**AI / LLM Application Engineer · Senior Full Stack Engineer** · New Delhi, India

I build complete products, from the UI and APIs through LLM integration to cloud deployment. I have 7+ years across fintech, healthcare, e-commerce and cybersecurity, including time as a **CTO leading a 6–7 member team** that took a 100+ store pan-India repair chain online.

- 🤖 **Now:** building agentic AI and **Model Context Protocol (MCP)** servers that let AI assistants act on real business systems
- 🏢 **Work:** Full Stack Engineer (AI Applications) at Rapid Innovation: LLM features with OpenAI + LangChain in a Django HRMS, AI document extraction, and a crypto-backed lending platform
- 🏥 **Before:** NHS (UK) healthcare platforms, a PTaaS security SaaS, and CTO at Phixman
- 🎓 **Certified (Nov 2026):** [Agentic AI, DeepLearning.AI](https://www.deeplearning.ai/certificates/74747d42-4873-418f-90fe-d57137cd9049) · [Introduction to MCP, Claude Academy](https://academy.claude.com/verify/a11b0f8ad94def8838c78f1c8105a734) · [MCP: Advanced Topics, Claude Academy](https://academy.claude.com/verify/f240e53c3e8bcaa5e50668ecf000c311) · [AI Agents in LangGraph, DeepLearning.AI](https://www.deeplearning.ai/accomplishments/0a7d9238-0d0e-49cf-948c-0263733303aa)
- 🌱 **Next:** evals and tracing for the HR assistant (groundedness of policy answers, correct tool choice, Langfuse), then a live deployment

### 🚀 Featured projects

**[hr-assistant](https://github.com/ByTusharGarg/hr-assistant)**: an AI agent for employees and managers that answers HR policy questions from a handbook, with citations, and takes actions in Horilla through horilla-mcp.

- LangGraph agent in a FastAPI backend, acting as an MCP client of horilla-mcp
- A Next.js web app and a React Native (Expo) mobile app that share the chat logic, with streaming replies, role-aware quick actions and a guided leave form
- Users sign in with their Horilla accounts, and the agent acts with each user's own permissions
- Every change (apply, approve or reject leave) appears as a slip to approve, enforced in code with a LangGraph interrupt, and is stamped once decided
- Scales horizontally: sessions, conversations and pending approvals in PostgreSQL, horilla-mcp as a stateless service
- Choose the model per message: Claude through the Anthropic SDK, or OpenAI, Gemini, Groq and others through aisuite
- 75+ offline tests across the agent, sign-in, shared state, model routing and the UI

`Python` `LangGraph` `FastAPI` `Next.js` `React Native` `MCP` `PostgreSQL` `Claude API` `aisuite`

**[horilla-mcp](https://github.com/ByTusharGarg/horilla-mcp)**: an MCP server that gives Claude and other AI assistants 14 tools over [Horilla](https://github.com/horilla-opensource/horilla), an open-source HRMS.

- Employee lookup, leave balances and applications, manager approvals and rejections, and attendance clock-in/out
- JWT auth with automatic token refresh; Horilla's role permissions are enforced, so the assistant can only do what the user can
- stdio and token-protected Streamable HTTP transports, plus Docker deployment
- Offline unit tests and a 21-check end-to-end run of the apply-and-approve flow

`Python` `MCP SDK` `REST / JWT` `PostgreSQL` `Redis` `Docker`

### 🛠️ Tech stack

| Area | Tools |
|---|---|
| **AI / LLM** | OpenAI API, LangChain, LangGraph, MCP, agentic patterns (reflection, tool use, planning, multi-agent), prompt engineering |
| **Languages** | Python, TypeScript, JavaScript |
| **Frontend & mobile** | React, Next.js, React Native, Tailwind CSS, Material UI |
| **Backend** | Django, FastAPI, Flask, Node.js, Express.js, REST, GraphQL, microservices |
| **Data** | PostgreSQL, MongoDB, Redis |
| **Cloud & DevOps** | AWS, Google Cloud, DigitalOcean, Docker, CI/CD, Nginx |

### 📫 Reach me

[LinkedIn](https://www.linkedin.com/in/tushargarg98/) · [Website](https://tushar-garg.co.in/) · [Email](mailto:tushargarg199822@gmail.com)

Open to AI / LLM engineering roles in Delhi NCR, Bengaluru, or remote.
