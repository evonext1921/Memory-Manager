# AI Private Localized Memory Management

> 🌐 [memory.evonext.cn](https://memory.evonext.cn) — Project landing page

A local memory system for AI assistants (Claude Code), giving your AI long-term memory capabilities.
No vector database, no cloud API, no external services required.

## Core Features

- **Four-Layer Memory Model**: Session working memory → Personal Profile → Experience Insights → Expression Style
- **Out-of-the-Box**: Zero-configuration startup with automatic knowledge base detection
- **Auto Routing**: AI automatically determines which layer information belongs to and writes to the correct location
- **Safe Backup**: Automatic backup before writing, retaining the last 10 versions
- **Metabolic Convergence**: Auto-archive outdated information to prevent memory bloat
- **Full CRUD**: Create, Read, Update, Delete for all memories

## Memory Layers

| Layer | Name | Purpose |
|-------|------|---------|
| L1 | Session | Current focus, active projects, next steps |
| L2 | Profile | Identity, role, tech stack, relationships |
| L3 | Insights | Project decisions, life reflections, cognitive frameworks |
| L4 | Style | Tone preferences, formatting norms, writing habits |

## Quick Start

### Prerequisites

- [Claude Code](https://claude.ai/claude-code) installed

### Installation

1. Place `SKILL.md` from this repo into a path accessible by your Claude Code
2. On first use, Claude Code will guide you to set up your knowledge base path
3. Follow the prompts to complete initialization

### Usage

| Command | Function |
|---------|----------|
| `状态` / `记忆状态` | Check current memory system status |
| `记一下` / `记住` / `保存` | Save current information to memory |
| `学习一下我的风格` | Learn and record your expression style |
| `更新记忆` | Update memory and check status |

## Design Philosophy

The essence of memory is enabling AI to perform CRUD on users' personal information during conversations:

- **Create**: New information is identified, classified, and stored in the correct location
- **Read**: Relevant information is precisely retrieved when needed
- **Update**: Existing facts are updated with safe backup of old versions
- **Delete**: Outdated information is archived to prevent entropy

---

<div align="center">
<a href="https://github.com/evonext1921/Memory-Manager">GitHub Repo</a> · 
<a href="https://memory.evonext.cn">Project Page</a> · 
<a href="https://space.bilibili.com/419058522">@裹小脚的大叔</a>
</div>

## License

MIT License
