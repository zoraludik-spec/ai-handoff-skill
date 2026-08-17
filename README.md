# 🤖 AI Agent Handoff Protocol (Skill)

**A strict state management and session continuity protocol for AI coding agents (Antigravity, Cline, Cursor, etc.).**

## 🚨 The Problem
When working with autonomous AI agents, sessions often break due to:
* Reaching API token limits.
* Switching to a different account.
* Closing the editor/browser.

When you start a new session, the AI loses all context. It tries to do full repository audits, hallucinates past decisions, or rewrites things it shouldn't.

## 💡 The Solution
This "Skill" forces the AI to build a strict **External Memory System** in your project's root folder. It ensures that every new AI session reads the exact state of the project before writing a single line of code.

## 🚀 How to Use (1-Click Install)

You don't need to download any files. Just tell your AI agent to fetch the prompt via a RAW link.

1. Copy the RAW link to the `install.md` file:
   ```text
https://raw.githubusercontent.com/zoraludik-spec/ai-handoff-skill/refs/heads/main/install.md
