<p align="center">
  <img src="icon.png" width="128" height="128" alt="Orbit" />
</p>

<h1 align="center">Orbit</h1>

<p align="center">
  <strong>The agent-native development environment.</strong>
</p>

<p align="center">
  Direct agents. Review changes. Design visually. Ship without switching tools.
</p>

<p align="center">
  <a href="https://github.com/Recusive/Orbit-Release/releases/latest">
    <img src="https://img.shields.io/github/v/release/Recusive/Orbit-Release?style=flat-square&color=e8927c" alt="Latest Release" />
  </a>
  <a href="https://github.com/Recusive/Orbit-Release/releases/latest">
    <img src="https://img.shields.io/github/downloads/Recusive/Orbit-Release/total?style=flat-square&color=e8927c" alt="Downloads" />
  </a>
  <img src="https://img.shields.io/badge/platform-macOS%20(Apple%20Silicon)-333?style=flat-square" alt="Platform" />
</p>

---

## Download

| Platform | Architecture | Download |
|----------|-------------|----------|
| macOS | Apple Silicon (M1+) | [`.dmg`](https://github.com/Recusive/Orbit-Release/releases/latest) |

> Windows and Linux support is coming soon.

Or visit the [**Releases**](https://github.com/Recusive/Orbit-Release/releases) page for all versions.

## Auto-Update

Orbit includes built-in auto-update. When a new version is available, you'll see a notification inside the app. Updates are signed and verified.

---

## What is Orbit?

Every AI coding tool is a chat window bolted onto a 1980s file editor. The developer's job has changed — we review and direct, not write — but the tools haven't.

Orbit is the first development environment designed from scratch for a world where AI agents write 80%+ of the code and your job is to direct, review, steer, and design.

### Orbit is NOT

- A code editor with AI bolted on (that's Cursor)
- A terminal with a better UI (that's Warp)
- A chat window that generates apps (that's Bolt/v0)
- A VS Code fork (that's Cursor/Windsurf/Void)
- An IDE with an AI sidebar (that's every tool from 2024)

### Orbit IS

- A **command center** for managing AI coding agents
- A **review surface** where you approve, reject, and steer agent output
- A **visual canvas** where you design UIs that become real code
- A **unified workspace** where your tools live via MCP integrations
- The only app open on your screen when you're building

---

## Core Features

### Agent Dashboard & Steering
See all agents working, their progress, cost, and status. Redirect an agent mid-task with a nudge — no killing, no restarting. Watch the agent's plan update in real time.

### Review-First Workflow
Changes grouped by feature, not by file. Accept or reject at the hunk level. The agent explains *why* it made changes, not just *what* it changed. Diffs are the default view, not source code.

### Visual Canvas
Draw UI frames on a spatial canvas. Tag AI to fill them. Export as real, production-ready code that uses your project's actual components. Design visually, ship real code.

### Live Preview & Inspector
Embedded browser shows your running app. Click any element to inspect its component, props, and state. Annotate the live UI to direct agents — point at things instead of describing them.

### Provider-Agnostic
Bring your own API keys. Use Claude, GPT, Gemini, or any model. When one has a bad day, switch with one click. Every new model that launches makes Orbit more valuable.

### Code Editor, Terminal & Git
Full CodeMirror 6 editor with language server support. Integrated terminal. Git operations built in. File explorer. Everything you need when you do want to write code.

### MCP Integrations
Connect Slack, Linear, GitHub, and more — with native UI panels in Orbit, not just chat commands.

---

## How Orbit Compares

| | Cursor | Claude Code | Warp | Bolt.new | **Orbit** |
|---|---|---|---|---|---|
| Primary paradigm | Editor-first | Terminal-first | Terminal-first | Chat-first | **Review-first** |
| Default view | Text editor | Terminal | Terminal + editor | Chat + preview | **Agent dashboard** |
| Visual building | None | None | None | Text-to-app | **Canvas: draw → code** |
| Agent steering | None | Kill & restart | None | None | **Nudge mid-task** |
| Multi-agent | None | Manual (tmux) | Oz (cloud) | None | **Built-in orchestration** |
| Model support | Multi-model | Claude only | Multi-model | Multi-model | **Provider-agnostic** |

---

## Built With

- [Tauri 2](https://tauri.app/) — Rust backend, native desktop performance
- [React 19](https://react.dev/) + TypeScript — Modern frontend
- [CodeMirror 6](https://codemirror.net/) — Code editing
- [Claude Agent SDK](https://docs.anthropic.com/en/docs/agents-and-tools/claude-code/sdk) — Agent orchestration

## Requirements

- **macOS** 11.0 (Big Sur) or later — Apple Silicon (M1+)

## Feedback

Found a bug or have a feature request? Open an [issue](https://github.com/Recusive/Orbit-Release/issues).

---

<p align="center">
  <sub>Built by <a href="https://github.com/Recusive">Recursive</a></sub>
</p>
