# Awesome-AI-Terminal-Conversational-CLI

# Top AI Terminal & Conversational CLI Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on AI-Native Terminal Emulators, Conversational SSH & Shell Clients, Natural-Language CLI Assistants, Terminal TUI Agents & Command Autocomplete*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Terminal & Conversational CLI**. These tools transform traditional shells and SSH clients into conversational AI workspaces—translating plain English into shell commands, explaining terminal errors inline, managing multi-server SSH sessions with AI copilots, and running autonomous TUI coding and DevOps agents.

**Examples** include Warp, Amazon Q Developer CLI (formerly Fig), GitHub Copilot CLI, Termius AI, Windsurf / Codeium Command, ShellGPT, Aicommits, Butterfish, and chaterm/Chaterm (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for open-source AI terminals & SSH clients (`Chaterm`, `Wave Terminal`, `Ghostty`), conversational CLI & TUI agents (`ShellGPT`, `AIChat`, `gptme`, `OpenCode`, `Codex CLI`, `Gemini CLI`, `Mods`), and open shell autocomplete engines (`Inshellisense`) — ideal for developers, sysadmins, DevOps/SREs, and terminal power users.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Warp (Warp AI & Oz Agents)](https://warp.dev)**  
  Modern GPU-accelerated terminal and Agentic Development Environment featuring natural-language command generation, conversational error debugging, multi-agent execution, and shared Warp Drive notebooks.

- **[Amazon Q Developer CLI (formerly Fig)](https://amazon.com)**  
  Cloud-backed AI command-line assistant providing IDE-style terminal autocomplete, conversational natural-language-to-bash translation, and AWS/codebase troubleshooting.

- **[GitHub Copilot CLI](https://github.com)**  
  Official GitHub command-line AI assistant and conversational terminal agent capable of explaining shell commands, suggesting `git`/`gh` workflows, and executing repository tasks directly in the shell.

- **[Termius AI](https://termius.com)**  
  Cross-platform SSH client and cloud-synced DevOps workspace featuring built-in conversational AI command generation, server log diagnostics, and shared team snippet vaults.

- **[Windsurf / Codeium Command](https://windsurf.com)**  
  AI-powered inline command and terminal assistant translating natural-language intent into executable shell commands and multi-step terminal workflows.

- **[Anthropic Claude Code](https://anthropic.com)**  
  Conversational and agentic terminal assistant that navigates entire codebases, executes shell commands, runs test suites, and manages Git workflows via MCP and `SKILL.md`.

- **[Butterfish](https://butterfish.io)**  
  Commercial-friendly AI shell wrapper that embeds persistent conversational LLM context directly into standard `bash` and `zsh` sessions for seamless command suggestions and explanations.

- **[Atlassian Rovo Dev CLI](https://atlassian.com)**  
  Enterprise cloud-connected conversational terminal agent linking local CLI workflows directly with Jira issues, Confluence documentation, and Bitbucket pull requests.


## Open-Source GitHub Projects

- **[chaterm/Chaterm](https://github.com)**  
  Open-source AI-powered intelligent terminal and conversational SSH client designed for DevOps, cloud operations, and developers—combining multi-host terminal management with natural-language command execution and interactive AI assistance.

- **[Wave Terminal (`wavetermdev/waveterm`)](https://github.com)**  
  Open-source (`Apache-2.0`) AI-native graphical terminal emulator combining traditional CLI power with inline file/web previews, persistent workspaces, and multi-model conversational AI blocks.

- **[ShellGPT (`TheR1D/shell_gpt`)](https://github.com)**  
  Widely adopted open-source (`MIT`) command-line productivity tool powered by LLMs for generating shell commands, code snippets, and conversational REPL sessions directly from the terminal.

- **[AIChat (`sigoden/aichat`)](https://github.com)**  
  All-in-one open-source (`MIT` / `Apache-2.0`) Rust CLI LLM tool featuring conversational Chat-REPL, Shell Assistant mode, RAG document querying, custom agents, and 20+ model backends.

- **[gptme (`gptme/gptme`)](https://github.com)**  
  Personal open-source (`MIT`) conversational AI assistant and autonomous terminal agent equipped with shell execution, Python runtime, file editing, web browsing, and persistent memory.

- **[OpenCode (`anomalyco/opencode`)](https://github.com)**  
  Popular open-source (`MIT`) terminal-native conversational AI coding agent featuring a polished TUI, LSP diagnostics integration, client/server architecture, and multi-provider LLM support.

- **[OpenAI Codex CLI (`openai/codex`)](https://github.com)**  
  Official open-source (`Apache-2.0`) lightweight conversational terminal coding agent built in Rust with OS-level sandboxing (`Seatbelt` / `Landlock`), multimodal input, and MCP server support.

- **[Gemini CLI (`google-gemini/gemini-cli`)](https://github.com)**  
  Official open-source (`Apache-2.0`) conversational command-line AI agent from Google bringing Gemini models, built-in Google Search grounding, file/shell tools, and MCP extensions to the terminal.

- **[Aider (`Aider-AI/aider`)](https://github.com)**  
  Pioneering open-source (`Apache-2.0`) conversational AI pair-programming CLI tool that maps Git repositories, applies multi-file edits, runs tests, and automatically commits changes.

- **[Goose (`block/goose`)](https://github.com)**  
  Extensible open-source (`Apache-2.0`) local-first conversational developer agent from Block supporting autonomous shell execution, code editing, and Model Context Protocol (MCP) toolkits.

- **[Mods (`charmbracelet/mods`) & Crush (`charmbracelet/crush`)](https://github.com)**  
  Unix-friendly open-source (`MIT` / `FSL-1.1-MIT`) CLI and TUI tools from Charm bringing conversational AI pipelines to standard shell pipes (`stdin`/`stdout`) and full terminal coding workflows.

- **[llm (`simonw/llm`)](https://github.com)**  
  Extensible open-source (`Apache-2.0`) CLI utility and Python library by Simon Willison for conversational terminal sessions (`llm chat`), SQLite prompt logging, and local/cloud model plugins.

- **[Aicommits (`Nutlope/aicommits`) & OpenCommit (`di-sukharev/opencommit`)](https://github.com)**  
  Lightweight open-source (`MIT`) CLI utilities that inspect staged `git diff` changes and automatically generate Conventional Commits messages via local or cloud LLMs.

- **[Inshellisense (`microsoft/inshellisense`)](https://github.com)**  
  Open-source (`MIT`) IDE-style autocomplete runtime for terminals from Microsoft (an open alternative to Fig) supporting 600+ command-line tools across `bash`, `zsh`, `fish`, and `PowerShell`.

- **[Open Interpreter (`OpenInterpreter/open-interpreter`)](https://github.com)**  
  Open-source (`AGPL-3.0`) natural-language conversational interface for computers enabling LLMs to write and execute Python, JavaScript, and Shell scripts locally in a terminal loop.

- **[kubectl-ai (`GoogleCloudPlatform/kubectl-ai`) & K8sGPT (`k8sgpt-ai/k8sgpt`)](https://github.com)**  
  Open-source (`Apache-2.0`) conversational AI Kubernetes CLI assistants that translate natural language into safe `kubectl` commands and diagnose cluster errors.

- **[Ghostty (`ghostty-org/ghostty`) & WezTerm (`wez/wezterm`)](https://github.com)**  
  Fast, native, GPU-accelerated open-source (`MIT`) terminal emulators offering modern rendering, Lua scriptability, and high-throughput performance for conversational TUI agents.

### Additional Strong Open-Source Options

- **[Fabric (`danielmiessler/fabric`)](https://github.com)** and **[tgpt (`aandrew-me/tgpt`)](https://github.com)** for composable Unix-pipe prompt patterns and zero-API-key conversational terminal queries.
- **[Tabby (`Eugeny/tabby`)](https://github.com)** and **[Electerm (`electerm/electerm`)](https://github.com)** for modern open-source cross-platform SSH/SFTP terminal clients extensible with AI command plugins.
- **[Atuin (`atuinsh/atuin`)](https://github.com)** and **[Oh My Zsh (`ohmyzsh/ohmyzsh`)](https://github.com)** for SQLite-backed magical shell history search and Zsh AI autocomplete/assistant plugin ecosystems.
- **[Ollama (`ollama/ollama`)](https://github.com)** and **[llama.cpp (`ggml-org/llama.cpp`)](https://github.com)** for running fast open-weight models (`Qwen2.5-Coder`, `Llama`, `Gemma`) locally behind conversational CLI clients completely offline.
- **[Model Context Protocol (MCP) CLI Servers](https://github.com)** for equipping conversational terminal agents with standardized filesystem, Git, Docker, database, and SSH tools.
