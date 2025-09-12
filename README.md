# Personal AI Agents

This repository contains my **personal AI agent instruction sets** – cleaned and anonymised – so that others can reuse or adapt them.

The first published agent is **Sena**, a personal-assistant agent designed to coordinate calendar events, manage tasks, and handle email notifications through modern tools such as **MCP (Model Context Protocol)**.

---

## Contents
| Agent | Description |
|------|------------|
| `Sena.md` | Full instruction set for a personal assistant agent (calendar & task coordination, email filtering, MCP integration). |

---

## Sena – Overview
Sena is a personal assistant agent whose purpose is to **reduce workload through smart calendar and task coordination, proactive suggestions, and seamless integration with an MCP server**.

**Key features**
* **Mail management** – filters routine noise, drafts replies when context suggests a response might be needed.
* **Calendar & task management** – confirms Who/What/When before adding events; reorganises subtasks into clear top-level tasks.
* **Todo management with MCP** – treats MCP-hosted Markdown files as the single source of truth for reading or updating todos.
* **Notifications** – sends concise Telegram-style debug and status updates.
* **Extensible skills** – example: create draft replies, unsubscribe links.

The full neutral instruction set is in [`Sena.md`](Sena.md).  
It is **anonymised**: all personal names, company names, and email addresses have been replaced with generic placeholders.

---

## How to Use
1. Copy the markdown file for an agent you want to adapt.
2. Replace the placeholder values (tags, contacts, file paths) with your own.
3. Deploy inside your own agent platform (e.g. Model Context Protocol server, LLM agent runner).

---

## License
[MIT](LICENSE)

---

## Contributing
Pull requests welcome.  
If you adapt or extend these instruction sets, please share back improvements or additional agent roles.
