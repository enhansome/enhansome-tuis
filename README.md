# Awesome tuis with stars

<h1 align="center">
  <code>Awesome TUIs</code>
</h1>

This is a community maintained list of TUI applications. A TUI application runs in your terminal and has some level of interactivity. Commands included in this list should not wrap other interactive commands (e.g. `fzf`), and should be maintained.

I made a video of my favorite TUIs from this list (one from each section). Click the image to check it out. 👇

[![](https://i.ytimg.com/vi/_fLmA4fjiAE/maxresdefault.jpg)](https://youtu.be/_fLmA4fjiAE?si=IgXuo)

There's a lot of cool projects here that I have no association with. Run them at your own risk. If you have a cool tool you'd like to share please [open a PR](https://github.com/rothgar/awesome-tuis/pulls).

## Table of Contents

* [AI Agents](#ai-agents)
* [Dashboards](#dashboards)
* [Development](#development)
* [Docker/LXC/K8s](#dockerlxck8s)
* [Editors](#editors)
* [File Managers](#file-managers)
* [Games](#games)
* [Libraries](#libraries)
* [Messaging](#messaging)
* [Miscellaneous](#miscellaneous)
* [Multimedia](#multimedia)
* [Productivity](#productivity)
* [Screensavers](#screensavers)
* [Web](#web)

<details open><summary><h2>AI Agents</h2></summary>

* [opencode](https://github.com/anomalyco/opencode) ⭐ 229,419 | 🐛 4,158 | 🌐 TypeScript | 📅 2026-11-26 AI coding agent, built for the terminal
* [codex](https://github.com/openai/codex) ⭐ 136,585 | 🐛 28,738 | 🌐 Rust | 📅 2026-11-27 Lightweight coding agent that runs in your terminal
* [crush](https://github.com/charmbracelet/crush) ⭐ 29,214 | 🐛 601 | 🌐 Go | 📅 2026-11-27 The glamourous AI coding agent
* [Claude Code Usage Monitor](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor) ⭐ 8,819 | 🐛 40 | 🌐 Python | 📅 2026-07-05 Monitor Claude token usage
* [Claude Code Bridge](https://github.com/SeemSeam/claude_codex_bridge) ⭐ 3,635 | 🐛 104 | 🌐 Python | 📅 2026-11-25 Real-time multi-AI collaboration between Claude, Codex and Gemini in terminal
* [Toad](https://github.com/batrachianai/toad) ⭐ 3,512 | 🐛 7 | 🌐 Python | 📅 2026-05-26 A unified interface for AI
* [elia](https://github.com/darrenburns/elia) ⭐ 2,483 | 🐛 27 | 🌐 Python | 📅 2024-10-10 A terminal ChatGPT client build with Textual
* [agent-deck](https://github.com/asheshgoplani/agent-deck) ⭐ 1,312 | 🐛 52 | 🌐 Go | 📅 2026-11-23 Terminal dashboard for managing multiple AI coding agent sessions
* [VT Code](https://github.com/vinhnx/vtcode) ⭐ 917 | 🐛 2 | 🌐 Rust | 📅 2026-11-27 VT Code - Semantic Coding Agent
* [tenere](https://github.com/pythops/tenere) ⭐ 687 | 🐛 11 | 🌐 Rust | 📅 2026-05-10 A TUI for ChatGPT written in Rust.
* [hcom](https://github.com/aannoo/hcom) ⭐ 678 | 🐛 46 | 🌐 Rust | 📅 2026-10-21 CLI and TUI for real-time messaging, observation, and orchestration between AI coding agents (Claude Code, Antigravity, Codex, OpenCode, Kilo, Cursor) across terminals
* [models](https://github.com/reyamira/models) ⭐ 522 | 🐛 1 | 🌐 Rust | 📅 2026-11-27 TUI for browsing AI models and coding agents
* [fast-resume](https://github.com/angristan/fast-resume) ⭐ 195 | 🐛 22 | 🌐 Rust | 📅 2026-11-26 Index and fuzzy search coding agent sessions
* [amux](https://github.com/andyrewlee/amux) ⭐ 170 | 🐛 6 | 🌐 Go | 📅 2026-11-27 Easily run parallel coding agents
* [AgenC Core](https://github.com/tetsuo-ai/agenc-core) ⭐ 145 | 🐛 175 | 🌐 TypeScript | 📅 2026-11-23 Open source AI coding agent with a terminal UI that works with any model provider
* [Quorum](https://github.com/Detrol/quorum-cli) ⭐ 131 | 🐛 3 | 🌐 Python | 📅 2026-09-27 Multi-agent AI discussion system for structured debates between LLMs
* [Keen Code](https://github.com/mochow13/keen-code) ⭐ 94 | 🐛 9 | 🌐 Go | 📅 2026-11-26 A context-aware terminal AI coding agent written in Go with multiple providers, MCPs, subagents, Agent Skills, controllable tool output retention, and hashline edits
* [lilbee](https://github.com/tobocop2/lilbee) ⭐ 73 | 🐛 36 | 🌐 Python | 📅 2026-11-27 A local model engine with a search engine and web crawler built in: chat with your files, notes, code, and crawled sites on your own GPUs, with answers that cite the source line
* [clausona](https://github.com/larcane97/clausona) ⭐ 63 | 🐛 1 | 🌐 TypeScript | 📅 2026-11-23 Switch Claude Code and Codex accounts with conversation history kept across them, route runs by plan usage, and manage each account's skills, MCP servers and hooks
* [SynapsCLI](https://github.com/HaseebKhalid1507/SynapsCLI) ⭐ 61 | 🐛 39 | 🌐 Rust | 📅 2026-11-26 Terminal-native AI agent runtime with parallel subagents, shareable daemon sessions, and any model from Claude to local Ollama
* [qmax-code](https://github.com/Quality-Max/qmax-code) ⭐ 14 | 🐛 2 | 🌐 Go | 📅 2026-11-26 QA-focused AI terminal agent written in Go, with standalone repository workflows and optional QualityMax integration.
* [Brief](https://github.com/WilliamAGH/brief) ⭐ 12 | 🐛 10 | 🌐 Java | 📅 2026-08-14 Terminal-first OpenAI chat client with slash-command palette and local tool execution.
* [llm-cost-dashboard](https://github.com/Mattbusel/llm-cost-dashboard) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2026-11-20 Prices every LLM API call from OpenAI, Anthropic and Claude Code logs, with a budget, a month-end forecast and cost spikes
* [SpurCode](https://github.com/getspur/SpurCode) ⭐ 6 | 🐛 3 | 🌐 Rust | 📅 2026-11-20 Rust TUI control tower that turns tasks into DAG plans and orchestrates a fleet of coding agents (Claude Code, Codex, Gemini, Kimi, OpenCode, ACP) in isolated git worktrees
* [Neuron](https://github.com/RAHUL-DevelopeRR/neuron-v2) ⭐ 3 | 🐛 17 | 🌐 Rust | 📅 2026-11-25 Open-source AI coding agent with a full-screen terminal UI that reads, edits and tests code with permission prompts

***

</details>

<details open><summary><h2>Dashboards</h2></summary>

* [btop++](https://github.com/aristocratos/btop) ⭐ 35,539 | 🐛 626 | 🌐 C++ | 📅 2026-11-25 Resource monitor with extras
* [Glances](https://github.com/nicolargo/glances) ⭐ 34,017 | 🐛 110 | 🌐 Python | 📅 2026-11-26 Glances an Eye on your system. A top/htop alternative.
* [Goaccess](https://github.com/allinurl/goaccess) ⭐ 21,158 | 🐛 449 | 🌐 C | 📅 2026-11-26 GoAccess is a real-time web log analyzer and interactive viewer that runs in a terminal in nix systems or through your browser.
* [WTF](https://github.com/wtfutil/wtf) ⭐ 17,156 | 🐛 107 | 🌐 Go | 📅 2026-11-25 The personal information dashboard for your terminal.
* [bottom](https://github.com/ClementTsang/bottom) ⭐ 14,297 | 🐛 96 | 🌐 Rust | 📅 2026-11-27 A customizable graphical process/system monitor for the terminal.
* [TermUI](https://github.com/gizak/termui) ⭐ 13,589 | 🐛 106 | 🌐 Go | 📅 2025-07-10 Golang terminal dashboard
* [gh-dash](https://github.com/dlvhdr/gh-dash) ⭐ 12,776 | 🐛 116 | 🌐 Go | 📅 2026-11-21 A rich terminal UI for GitHub PRs and Issues
* [gping](https://github.com/orf/gping) ⭐ 12,760 | 🐛 44 | 🌐 Rust | 📅 2026-11-26 Ping, but with a graph
* [bandwhich](https://github.com/imsnif/bandwhich) ⭐ 12,131 | 🐛 57 | 🌐 Rust | 📅 2026-08-01 Terminal bandwidth utilization tool
* [talos linux](https://github.com/siderolabs/talos) ⭐ 11,600 | 🐛 281 | 🌐 Go | 📅 2026-11-26 A Linux distro with a TUI dashboard for local and remote usage
* [nvtop](https://github.com/Syllo/nvtop) ⭐ 11,184 | 🐛 93 | 🌐 C | 📅 2026-11-26 GPUs process monitoring for AMD, Intel and NVIDIA
* [bashtop](https://github.com/aristocratos/bashtop) ⭐ 11,115 | 🐛 64 | 🌐 Shell | 📅 2023-08-21 Resource manager written in bash
* [bpytop](https://github.com/aristocratos/bpytop) ⭐ 10,932 | 🐛 99 | 🌐 Python | 📅 2025-06-01 A Python-based system monitor with lots of information.
* [htop](https://github.com/htop-dev/htop) ⭐ 8,477 | 🐛 379 | 🌐 C | 📅 2026-11-20 Interactive text-mode process viewer for Unix systems. It aims to be a better 'top'
* [csysdig](https://github.com/draios/sysdig) ⭐ 8,323 | 🐛 115 | 🌐 C++ | 📅 2026-04-13 root level Ncurses interface for sysdig, Linux system exploration and troubleshooting tool with first class support for containers
* [trippy](https://github.com/fujiapple852/trippy) ⭐ 8,211 | 🐛 81 | 🌐 Rust | 📅 2026-11-25 A network diagnostic tool that includes functionality like mtr and more
* [Backlog.md](https://github.com/MrLesk/Backlog.md) ⭐ 7,499 | 🐛 106 | 🌐 TypeScript | 📅 2026-11-25 A tool for managing project collaboration between humans and AI Agents in a git ecosystem
* [ticker](https://github.com/achannarasappa/ticker) ⭐ 6,273 | 🐛 32 | 🌐 Go | 📅 2026-06-28 Track stocks, crypto, and derivatives prices and positions in real time from your terminal
* [rustnet](https://github.com/domcyrus/rustnet) ⭐ 5,268 | 🐛 23 | 🌐 Rust | 📅 2026-11-26 A cross-platform network monitoring tool with deep packet inspection
* [s-tui](https://github.com/amanusk/s-tui) ⭐ 5,124 | 🐛 42 | 🌐 Python | 📅 2026-09-15 CPU stress and monitoring utility
* [Kyanos](https://github.com/hengyoush/kyanos) ⭐ 5,084 | 🐛 33 | 🌐 C | 📅 2026-11-24 Linux network analysis tool based on eBPF
* [binsider](https://github.com/orhun/binsider) ⭐ 4,537 | 🐛 38 | 🌐 Rust | 📅 2026-11-22 A TUI for analyzing Linux binaries.
* [psmux](https://github.com/psmux/psmux) ⭐ 3,912 | 🐛 43 | 🌐 PowerShell | 📅 2026-11-26 tmux-compatible terminal multiplexer for Windows built in Rust with ratatui.
* [nethogs](https://github.com/raboof/nethogs) ⭐ 3,717 | 🐛 104 | 🌐 C++ | 📅 2026-07-23 'net top' tool
* [gobang](https://github.com/TaKO8Ki/gobang) ⭐ 3,326 | 🐛 57 | 🌐 Rust | 📅 2023-11-10 A cross-platform TUI database management tool written in Rust
* [gotop](https://github.com/xxxserxxx/gotop) ⭐ 3,099 | 🐛 91 | 🌐 Go | 📅 2026-05-07 A terminal based graphical activity monitor inspired by gtop and vtop
* [zenith](https://github.com/bvaisvil/zenith) ⭐ 3,077 | 🐛 40 | 🌐 Rust | 📅 2026-10-01 In terminal graphical metrics for your \*nix system written in Rust
* [kmon](https://github.com/orhun/kmon) ⭐ 2,970 | 🐛 24 | 🌐 Rust | 📅 2026-09-21 Linux Kernel Manager and Activity Monitor
* [process-compose](https://github.com/F1bonacc1/process-compose) ⭐ 2,960 | 🐛 42 | 🌐 Go | 📅 2026-11-23 TUI for running apps and processes
* [Gloomberb](https://github.com/gloom-sh/gloomberb) ⭐ 2,815 | 🐛 16 | 🌐 TypeScript | 📅 2026-11-27 Open-source finance terminal for portfolios, watchlists, charts, news, research, and broker connections.
* [gonzo](https://github.com/control-theory/gonzo) ⭐ 2,798 | 🐛 22 | 🌐 Go | 📅 2026-11-26 A powerful, real-time log analysis terminal UI inspired by k9s.
* [oryx](https://github.com/pythops/oryx) ⭐ 2,616 | 🐛 5 | 🌐 Rust | 📅 2026-10-18 A TUI for sniffing network traffic using eBPF
* [below](https://github.com/facebookincubator/below) ⭐ 2,546 | 🐛 32 | 🌐 Rust | 📅 2026-11-24 A time traveling resource monitor for modern Linux systems
* [CoreFreq](https://github.com/cyring/CoreFreq) ⭐ 2,254 | 🐛 3 | 🌐 C | 📅 2026-11-22 CPU monitoring software designed for the 64-bits Processors
* [macmon](https://github.com/vladkens/macmon) ⭐ 2,157 | 🐛 4 | 🌐 Rust | 📅 2026-11-23 Sudoless performance monitoring for Apple Silicon processors written in Rust
* [netscanner](https://github.com/Chleba/netscanner) ⭐ 1,906 | 🐛 7 | 🌐 Rust | 📅 2026-11-26 Network scanner
* [sysz](https://github.com/joehillen/sysz) ⭐ 1,889 | 🐛 5 | 🌐 Shell | 📅 2024-04-22 An fzf terminal UI for systemctl
* [cgdb](https://github.com/cgdb/cgdb) ⭐ 1,853 | 🐛 46 | 🌐 C | 📅 2026-10-06 Console front-end to the GNU debugger
* [AdGuardian-Term](https://github.com/lissy93/AdGuardian-Term) ⭐ 1,689 | 🐛 0 | 🌐 Rust | 📅 2026-11-13 A TUI dashboard for monitoring real-time traffic from an AdGuard Home instance
* [nerdlog](https://github.com/dimonomid/nerdlog) ⭐ 1,592 | 🐛 11 | 🌐 Go | 📅 2026-10-03 fast, remote-first, multi-host TUI log viewer
* [ttl](https://github.com/lance0/ttl) ⭐ 1,505 | 🐛 1 | 🌐 Rust | 📅 2026-11-26 Fast, modern traceroute with a real-time TUI, per-hop stats and ASN/geo lookup
* [bmon](https://github.com/Jafaral/bmon) ⭐ 1,401 | 🐛 37 | 🌐 C | 📅 2026-09-19 A monitoring and debugging tool to capture networking related statistics and prepare them visually.
* [dolphie](https://github.com/charles-001/dolphie) ⭐ 1,211 | 🐛 1 | 🌐 Python | 📅 2026-09-15 Your single pane of glass for real-time analytics into MySQL/MariaDB & ProxySQL
* [updo](https://github.com/Owloops/updo) ⭐ 1,151 | 🐛 2 | 🌐 Go | 📅 2026-11-17 Website monitoring tool with uptime tracking, response time metrics, and SSL certificate monitoring.
* [Grafterm](https://github.com/slok/grafterm) ⭐ 1,146 | 🐛 11 | 🌐 Go | 📅 2022-06-10 Metrics dashboards on terminal, a Grafana inspired terminal version
* [otel-tui](https://github.com/ymtdzzz/otel-tui) ⭐ 1,140 | 🐛 26 | 🌐 Go | 📅 2026-11-22 A terminal OpenTelemetry viewer
* [hwatch](https://github.com/blacknon/hwatch) ⭐ 1,096 | 🐛 10 | 🌐 Rust | 📅 2026-08-30 A modern alternative to watch that records command output history and provides interactive diff views, scrolling, filtering, JSON logging, and hooks.
* [atop](https://github.com/Atoptool/atop/) ⭐ 1,090 | 🐛 62 | 🌐 C | 📅 2026-11-20 root level system and process monitor for Linux
* [kaskade](https://github.com/sauljabin/kaskade) ⭐ 1,045 | 🐛 7 | 🌐 Python | 📅 2026-11-26 TUI for kafka, which allows you to interact and consume topics from your terminal in style!
* [tufw](https://github.com/peltho/tufw) ⭐ 880 | 🐛 3 | 🌐 Go | 📅 2026-11-25 Terminal UI for ufw
* [Puffin](https://github.com/siddhantac/puffin) ⭐ 573 | 🐛 11 | 🌐 Go | 📅 2026-03-11 A beautiful terminal dashboard for hledger
* [damon](https://github.com/hashicorp/damon) ⭐ 491 | 🐛 10 | 🌐 Go | 📅 2026-08-24 TUI interface for Hashicorp Nomad
* [wander](https://github.com/robinovitch61/wander) ⭐ 483 | 🐛 6 | 🌐 Go | 📅 2026-10-15 HashiCorp Nomad terminal client
* [ttop](https://github.com/inv2004/ttop) ⭐ 401 | 🐛 6 | 🌐 Nim | 📅 2026-08-16 System monitoring tool with historical data service, triggers and top-like TUI
* [framework-tool-tui](https://github.com/grouzen/framework-tool-tui) ⭐ 364 | 🐛 12 | 🌐 Rust | 📅 2026-11-22 TUI for controlling and monitoring Framework Computers hardware built in Rust
* [Yozefu](https://github.com/MAIF/yozefu) ⭐ 357 | 🐛 5 | 🌐 Rust | 📅 2026-08-27 A TUI for exploring data of a kafka cluster.
* [metropolis](https://github.com/5c0/metropolis) ⭐ 325 | 🐛 0 | 🌐 Rust | 📅 2026-11-08 A cyberpunk system monitor that turns kernel metrics into a living terminal skyline
* [tdash](https://github.com/jessfraz/tdash) ⭐ 318 | 🐛 0 | 🌐 Go | 📅 2026-11-03 A terminal dashboard with stats from Google Analytics, GitHub, Travis CI, and Jenkins. Very much built specific to me
* [chdig](https://github.com/azat/chdig) ⭐ 301 | 🐛 4 | 🌐 Rust | 📅 2026-11-16 Dig into ClickHouse with TUI interface
* [dashbrew](https://github.com/rasjonell/dashbrew) ⭐ 281 | 🐛 1 | 🌐 Go | 📅 2026-10-27 TUI dashboard builder that lets you visualize data from scripts and APIs.
* [unifly](https://github.com/hyperb1iss/unifly) ⭐ 281 | 🐛 3 | 🌐 Rust | 📅 2026-11-16 CLI and TUI for Ubiquiti UniFi networks with live traffic charts, topology, clients, and firewall management
* [pstop](https://github.com/psmux/pstop) ⭐ 276 | 🐛 1 | 🌐 Rust | 📅 2026-11-07 htop-style system monitor for Windows with per-core CPU bars, tree view, and 7 color schemes.
* [cheatshh](https://github.com/AnirudhG07/cheatshh) ⭐ 197 | 🐛 0 | 🌐 Shell | 📅 2025-08-15 A fzf TUI for managing custom made command-line cheatsheet for Unix.
* [sockttop](https://github.com/jasonwitty/socktop) ⭐ 197 | 🐛 5 | 🌐 Rust | 📅 2026-11-12 socktop is a remote system monitor with a rich TUI, inspired by top/btop, talking to a lightweight agent over WebSockets.
* [Raijin](https://github.com/MasonStooksbury/Raijin) ⭐ 180 | 🐛 0 | 🌐 Rust | 📅 2026-10-04 A free, simple weather TUI that pulls data without the need for an API key, account, or subscription
* [flowrs](https://github.com/jvanbuel/flowrs) ⭐ 175 | 🐛 9 | 🌐 Rust | 📅 2026-11-25 A TUI for monitoring, inspecting and managing Apache Airflow DAGs
* [claws](https://github.com/clawscli/claws) ⭐ 169 | 🐛 8 | 🌐 Go | 📅 2026-11-17 A terminal UI for AWS resource management with vim-style keybindings, command-mode navigation, and optional read-only mode.
* [psnet](https://github.com/psmux/psnet) ⭐ 152 | 🐛 3 | 🌐 Rust | 📅 2026-11-08 Real-time TUI network monitor for Windows with speed graphs, DNS resolution, and packet inspection.
* [cronstable](https://github.com/ptweezy/cronstable) ⭐ 140 | 🐛 2 | 🌐 Python | 📅 2026-11-25 Job scheduler with a live terminal dashboard for job status, logs, run history, workflows, and cluster health
* [htui](https://github.com/PierreKieffer/htui) ⭐ 123 | 🐛 1 | 🌐 Go | 📅 2021-04-26 Heroku Terminal User Interface
* [RunWisp](https://github.com/runwisp/runwisp) ⭐ 109 | 🐛 4 | 🌐 Go | 📅 2026-11-26 Cron job manager and process supervisor with a TUI for live output and run history
* [ls-horizons](https://github.com/litescript/ls-horizons) ⭐ 91 | 🐛 0 | 🌐 Go | 📅 2026-08-20 Terminal UI for visualizing NASA's Deep Space Network in real-time
* [lazyslurm](https://github.com/hill/lazyslurm) ⭐ 90 | 🐛 2 | 🌐 Rust | 📅 2026-08-09 A lazygit-style terminal UI for Slurm. Monitor jobs, tail logs, and inspect nodes and partitions.
* [tegratop](https://github.com/pythops/tegratop) ⭐ 86 | 🐛 1 | 🌐 Rust | 📅 2025-12-14 Monitoring tool (top like) for Nvidia jetson boards
* [hwinfo-tui](https://github.com/JuanjoFuchs/hwinfo-tui) ⭐ 67 | 🐛 0 | 🌐 Python | 📅 2026-10-14 A gping-inspired terminal visualization tool for monitoring real-time hardware sensor data from HWInfo
* [fubar](https://github.com/irishmaestro/fubar) ⭐ 64 | 🐛 1 | 🌐 Rust | 📅 2024-10-09 Formidable Unix Binary Arsenal & Repository. TUI built for gtfobins power users.
* [tmd-top](https://github.com/CDWEN0526/tmd-top) ⭐ 61 | 🐛 1 | 🌐 Python | 📅 2024-12-24 Used to monitor the process tcp traffic of the linux system, detailed to each IP connection
* [apachetop](https://github.com/tessus/apachetop) ⭐ 52 | 🐛 2 | 🌐 C++ | 📅 2024-02-12 display information from a running copy of Apache.
* [ServerHub](https://github.com/nickprotop/ServerHub) ⭐ 51 | 🐛 0 | 🌐 C# | 📅 2026-11-13 A TUI server monitoring dashboard for Linux with real-time metrics, scriptable widgets, and remote management
* [ID-Spoofer](https://github.com/NubleX/ID-Spoofer) ⭐ 35 | 🐛 3 | 🌐 Go | 📅 2026-11-06 A cross-platform cybersecurity toolkit for fingerprint and traffic obfuscation.
* [Servonaut](https://github.com/zb-ss/servonaut) ⭐ 33 | 🐛 2 | 🌐 Python | 📅 2026-11-27 A TUI for managing AWS, Hetzner, OVH and custom SSH servers with log viewing, CloudWatch/CloudTrail browsing, IP banning, AI log analysis and a built-in MCP server
* [trek](https://github.com/franckverrot/trek) ⭐ 32 | 🐛 1 | 🌐 Go | 📅 2023-08-30 ncurses explorer for Hashicorp Nomad clusters
* [sacha](https://github.com/Sachamama/sacha) ⭐ 25 | 🐛 11 | 🌐 Go | 📅 2026-06-22 A two-pane AWS TUI for browsing, searching, and managing resources across seven services including CloudWatch Logs, S3, DynamoDB, Lambda, SSM, SQS, and EC2.
* [toptop](https://github.com/ur-grue/toptop) ⭐ 22 | 🐛 4 | 🌐 Rust | 📅 2026-09-21 htop/btop-class system monitor with a local-LLM view: tokens/sec, VRAM-spill and memory-bandwidth verdicts, NVIDIA + Apple Silicon
* [bullmq-dash](https://github.com/quanghuynt14/bullmq-dash) ⭐ 19 | 🐛 5 | 🌐 TypeScript | 📅 2026-10-11 Dashboard for monitoring BullMQ queues, inspecting jobs, and retrying failures
* [prt](https://github.com/rekurt/prt) ⭐ 15 | 🐛 3 | 🌐 Rust | 📅 2026-10-24 Interactive network port monitor with process details and SSH tunnel inspection for macOS and Linux.
* [tuicamp](https://github.com/AbeEstrada/tuicamp) ⭐ 8 | 🐛 0 | 🌐 Go | 📅 2025-08-18 Unofficial TimeCamp TUI
* [ADSB-TUI](https://github.com/WPTK/ADSB-TUI) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2026-11-05 Watch planes from your own readsb or dump1090-fa receiver, sortable table next to a radar scope
* [topic](https://github.com/yurirocha15/topic) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2026-11-14 top for inside containers: shows CPU, memory, GPU, disk, network and process usage against the container's cgroup limits instead of the host's
* [dynamite](https://github.com/wolfwfr/dynamite) ⭐ 1 | 🐛 0 | 🌐 Go | 📅 2026-11-20 A TUI query engine for Amazon DynamoDB full of quality-of-life features.

***

</details>

<details open><summary><h2>Development</h2></summary>

* [lazygit](https://github.com/jesseduffield/lazygit) ⭐ 84,118 | 🐛 1,083 | 🌐 Go | 📅 2026-11-23 Simple terminal UI for git commands
* [delta](https://github.com/dandavison/delta) ⭐ 32,858 | 🐛 506 | 🌐 Rust | 📅 2026-11-25 A syntax-highlighting pager for git, diff, and grep output
* [gitui](https://github.com/gitui-org/gitui) ⭐ 22,694 | 🐛 364 | 🌐 Rust | 📅 2026-10-06 blazing fast terminal-ui for git written in rust
* [fx](https://github.com/antonmedv/fx) ⭐ 20,724 | 🐛 12 | 🌐 Go | 📅 2026-11-20 Terminal JSON viewer & processor
* [tig](https://github.com/jonas/tig) ⭐ 13,387 | 🐛 239 | 🌐 C | 📅 2026-11-11 Text-mode interface for git
* [posting](https://github.com/darrenburns/posting) ⭐ 12,662 | 🐛 88 | 🌐 Go | 📅 2026-10-16 A powerful HTTP client that lives in your terminal
* [blinkenlights](https://github.com/jart/blink) ⭐ 7,615 | 🐛 60 | 🌐 C | 📅 2025-12-10 TUI that may be used for debugging x86\_64-linux or i8086 programs across platforms
* [harlequin](https://github.com/tconbeer/harlequin) ⭐ 6,541 | 🐛 43 | 🌐 Python | 📅 2026-11-25 The SQL IDE for Your Terminal
* [rainfrog](https://github.com/achristmascarl/rainfrog) ⭐ 5,419 | 🐛 19 | 🌐 Rust | 📅 2026-11-20 A database management TUI for Postgres, MySQL, and SQLite written in Rust
* [sqlit](https://github.com/Maxteabag/sqlit) ⭐ 5,004 | 🐛 37 | 🌐 Python | 📅 2026-10-28 A lightweight TUI for SQL databases inspired by lazygit
* [lazysql](https://github.com/jorgerojas26/lazysql) ⭐ 4,449 | 🐛 45 | 🌐 Go | 📅 2026-10-20 A cross-platform TUI database management tool written in Go.
* [grv](https://github.com/rgburke/grv) ⭐ 4,083 | 🐛 31 | 🌐 Go | 📅 2019-05-01 Terminal interface for viewing git repositories
* [ATAC](https://github.com/Julien-cpsn/ATAC) ⭐ 3,757 | 🐛 24 | 🌐 Rust | 📅 2026-10-19 A feature-full TUI API client made in Rust. ATAC is free, open-source, offline and account-less.
* [pudb](https://github.com/inducer/pudb) ⭐ 3,256 | 🐛 164 | 🌐 Python | 📅 2026-11-23 A console-based visual debugger for Python
* [dblab](https://github.com/danvergara/dblab) ⭐ 3,249 | 🐛 12 | 🌐 Go | 📅 2026-11-10 The database client every command line junkie deserves
* [jqp](https://github.com/noahgorstein/jqp) ⭐ 2,851 | 🐛 25 | 🌐 Go | 📅 2026-02-06 A TUI playground to experiment with jq
* [euporie](https://github.com/joouha/euporie) ⭐ 2,723 | 🐛 15 | 🌐 Python | 📅 2026-11-03 Jupyter notebooks in the terminal
* [nap](https://github.com/maaslalani/nap) ⭐ 2,217 | 🐛 17 | 🌐 Go | 📅 2024-05-18 Code snippets in your terminal
* [runme](https://github.com/runmedev/runme) ⭐ 2,216 | 🐛 159 | 🌐 Go | 📅 2026-11-24 Discover and run code snippets directly from your README.md or other markdowns
* [serie](https://github.com/lusingander/serie) ⭐ 2,209 | 🐛 25 | 🌐 Rust | 📅 2026-11-24 A rich git commit graph
* [resterm](https://github.com/unkn0wn-root/resterm) ⭐ 2,016 | 🐛 0 | 🌐 Go | 📅 2026-11-24 A terminal client for HTTP/GraphQL/gRPC with support for WebSockets, SSE, workflows, profiling, OpenAPI and response diffs.
* [termdbms](https://github.com/mathaou/termdbms) ⭐ 1,822 | 🐛 6 | 🌐 Go | 📅 2022-06-11 A TUI for viewing and editing database files.
* [sshs](https://github.com/quantumsheep/sshs) ⭐ 1,656 | 🐛 26 | 🌐 Rust | 📅 2026-08-29 Terminal user interface for SSH
* [lazyjournal](https://github.com/Lifailon/lazyjournal) ⭐ 1,455 | 🐛 1 | 🌐 Go | 📅 2026-11-26 TUI for journalctl, file system logs, as well Docker and Podman containers for quick viewing and filtering
* [snips.sh](https://github.com/robherley/snips.sh) ⭐ 1,330 | 🐛 13 | 🌐 Go | 📅 2026-11-20 ✂️ passwordless, anonymous SSH-powered pastebin with a human-friendly TUI and web UI
* [terraform-tui](https://github.com/idoavrah/terraform-tui) ⭐ 1,298 | 🐛 14 | 🌐 Python | 📅 2026-11-01 view and interact with Terraform state
* [proxelar](https://github.com/emanuele-em/proxelar) ⭐ 1,122 | 🐛 5 | 🌐 Rust | 📅 2026-11-23 Scriptable MITM proxy TUI to inspect, intercept, replay, and rewrite HTTP(S) and WebSocket traffic
* [stu](https://github.com/lusingander/stu) ⭐ 927 | 🐛 15 | 🌐 Rust | 📅 2026-11-27 A TUI for Amazon S3
* [sls-dev-tools](https://github.com/aleios-cloud/sls-dev-tools) ⭐ 871 | 🐛 62 | 🌐 JavaScript | 📅 2023-04-25 Dev Tools for the Serverless World
* [austin-tui](https://github.com/P403n1x87/austin-tui) ⭐ 664 | 🐛 2 | 🌐 Python | 📅 2026-06-04 The top-like text-based user interface for Austin
* [play](https://github.com/paololazzari/play) ⭐ 599 | 🐛 3 | 🌐 Go | 📅 2025-03-28 A TUI playground to experiment with your favorite programs, such as grep, sed, awk, jq and yq
* [Froggit](https://github.com/thewizardshell/froggit) ⭐ 485 | 🐛 2 | 🌐 Go | 📅 2026-03-20 Minimalist Git TUI with GitHub CLI integration
* [Feluda](https://github.com/anistark/feluda) ⭐ 483 | 🐛 13 | 🌐 Rust | 📅 2026-11-11 Detect restrictive and incompatible licesenses in all dependencies of your project.
* [qo](https://github.com/kiki-ki/go-qo) ⭐ 406 | 🐛 8 | 🌐 Go | 📅 2026-11-21 Interactive SQL filter for JSON, CSV, TSV and other streams.
* [heretek](https://github.com/wcampbell0x2a/heretek) ⭐ 400 | 🐛 30 | 🌐 Rust | 📅 2026-11-24 GDB TUI Dashboard
* [regex-tui](https://github.com/vitor-mariano/regex-tui) ⭐ 370 | 🐛 1 | 🌐 Go | 📅 2026-11-08 A simple TUI to visualize and test regular expressions
* [chiko](https://github.com/felangga/chiko) ⭐ 358 | 🐛 0 | 🌐 Go | 📅 2026-11-08 The Ultimate Beauty TUI gRPC Client
* [ec](https://github.com/chojs23/ec) ⭐ 327 | 🐛 1 | 🌐 Go | 📅 2026-11-21 A TUI native Git mergetool with 3 panes
* [sabiql](https://github.com/riii111/sabiql) ⭐ 326 | 🐛 10 | 🌐 Rust | 📅 2026-11-22 Fast, driverless, Vim-first database TUI with safe editing and ER diagrams.
* [ggc](https://github.com/bmf-san/ggc) ⭐ 288 | 🐛 1 | 🌐 Go | 📅 2026-11-23 A terminal-based Git CLI tool written in Go
* [pproftui](https://github.com/Oloruntobi1/pproftui) ⭐ 280 | 🐛 2 | 🌐 Go | 📅 2025-07-28 A terminal-based UI for Go's pprof that makes profiling interactive
* [gh-enhance](https://github.com/dlvhdr/gh-enhance) ⭐ 255 | 🐛 14 | 🌐 Go | 📅 2026-11-20 A blazingly fast terminal UI for GitHub Actions
* [git-crecord](https://github.com/andrewshadura/git-crecord) ⭐ 217 | 🐛 21 | 🌐 Python | 📅 2025-05-23 interactive selective commit tool
* [lazymake](https://github.com/rshelekhov/lazymake) ⭐ 215 | 🐛 2 | 🌐 Go | 📅 2026-11-13 Modern TUI for Makefiles with interactive target selection, dependency visualization, and command safety analysis.
* [cargo-seek](https://github.com/tareqimbasher/cargo-seek) ⭐ 206 | 🐛 9 | 🌐 Rust | 📅 2026-08-12 A TUI for searching, adding and installing cargo crates
* [prs](https://github.com/dhth/prs) ⭐ 187 | 🐛 2 | 🌐 Go | 📅 2026-11-11 Stay updated on PRs without leaving the terminal
* [Twig](https://github.com/workdone0/twig) ⭐ 184 | 🐛 6 | 🌐 Rust | 📅 2026-10-08 Terminal UI for interactively exploring JSON and YAML files.
* [dbee](https://github.com/murat-cileli/dbee) ⭐ 171 | 🐛 3 | 🌐 Go | 📅 2024-06-22 Fast & Minimalistic Database Browser
* [opcilloscope](https://github.com/SquareWaveSystems/opcilloscope) ⭐ 147 | 🐛 2 | 🌐 C# | 📅 2026-10-21 OPC UA client TUI with real-time oscilloscope view for industrial automation
* [git-scope](https://github.com/Bharath-code/git-scope) ⭐ 132 | 🐛 5 | 🌐 Go | 📅 2026-11-20 Terminal UI dashboard for inspecting multiple local Git repositories.
* [gitv](https://github.com/jayanaxhf/gitv) ⭐ 116 | 🐛 12 | 🌐 Rust | 📅 2026-09-24: A beautiful, feature-rich and performant terminal client for GitHub issues.
* [amtui](https://github.com/pehlicd/amtui/) ⭐ 114 | 🐛 4 | 🌐 Go | 📅 2026-06-20 Alertmanager TUI - Your Terminal Companion for Alertmanager
* [pyautogit](https://github.com/jwlodek/pyautogit) ⭐ 111 | 🐛 3 | 🌐 Python | 📅 2020-07-05 A terminal UI for managing git repositories, written using py\_cui
* [ddqa](https://github.com/DataDog/ddqa) ⭐ 109 | 🐛 0 | 🌐 Python | 📅 2026-11-03 Jira TUI to help with software releases
* [ddv](https://github.com/lusingander/ddv) ⭐ 104 | 🐛 3 | 🌐 Rust | 📅 2026-11-23 Terminal DynamoDB viewer
* [gitwig](https://github.com/tareqmy/gitwig) ⭐ 94 | 🐛 1 | 🌐 Rust | 📅 2026-11-26 - A mouse-drivable git TUI and multi-repo dashboard built in Rust.
* [brows](https://github.com/rubysolo/brows) ⭐ 87 | 🐛 0 | 🌐 Go | 📅 2026-06-01 CLI GitHub release browser
* [act3](https://github.com/dhth/act3) ⭐ 83 | 🐛 4 | 🌐 Go | 📅 2026-11-11 Glance at the last 3 runs of your Github Actions
* [scope](https://github.com/matheuswhite/scope-rs) ⭐ 79 | 🐛 13 | 🌐 Rust | 📅 2026-11-19 Cross-platform serial-port & RTT monitor with colored timestamped I/O, hex/@tag input macros, search, session recording, auto-reconnect and Lua plugins
* [tokui](https://github.com/zdyxry/tokui) ⭐ 74 | 🐛 1 | 🌐 Go | 📅 2026-09-12 An interactive TUI for visualizing code statistics from tokei.
* [csope](https://github.com/agvxov/csope) ⭐ 73 | 🐛 0 | 🌐 C | 📅 2026-08-04 C source code browser based on cscope
* [toolui](https://github.com/jinek/ToolUI) ⭐ 67 | 🐛 2 | 🌐 C# | 📅 2022-10-29 Dotnet core application to manage installed nuget tools
* [sot](https://github.com/anistark/sot) ⭐ 64 | 🐛 7 | 🌐 Python | 📅 2026-11-10 A top like system observability tool written in python
* [ygrep](https://github.com/yetidevworks/ygrep) ⭐ 64 | 🐛 2 | 🌐 Rust | 📅 2026-10-21 A fast, local, indexed code search TUI powered by Tantivy full-text indexing, optimized for AI coding assistants
* [differ](https://github.com/JanSmrcka/differ) ⭐ 63 | 🐛 20 | 🌐 Go | 📅 2026-11-06 A TUI git diff viewer
* [DevProjex](https://github.com/Avazbek22/DevProjex) ⭐ 47 | 🐛 9 | 🌐 C# | 📅 2026-11-22 A cross-platform TUI for exploring project trees, selecting files, previewing AI-ready context, and exporting structured codebase snapshots.
* [postbear](https://github.com/carban/postbear) ⭐ 45 | 🐛 0 | 🌐 Go | 📅 2026-01-16 Postbear is a high-speed and lightweight API client. The Postman alternative in your terminal
* [qrypad](https://github.com/wheelibin/qrypad) ⭐ 45 | 🐛 0 | 🌐 Go | 📅 2026-11-26 A fast SQL scratchpad for your terminal.
* [pho](https://github.com/utkarsh261/pho) ⭐ 42 | 🐛 1 | 🌐 Go | 📅 2026-11-26 Review, comment on and merge GitHub pull requests from the terminal
* [y509](https://github.com/kanywst/y509) ⭐ 42 | 🐛 2 | 🌐 Go | 📅 2026-11-23 Inspect X.509 certificate chains, catching the missing intermediates that break curl but not browsers
* [cnTUI](https://github.com/fipso/cntui) ⭐ 41 | 🐛 0 | 🌐 Go | 📅 2023-07-14 Replay chrome requests from your terminal using curl
* [logshark](https://github.com/ugosan/logshark) ⭐ 40 | 🐛 0 | 🌐 Go | 📅 2022-12-13 A debugger CLI for JSON logs written in Go
* [vctui](https://github.com/thebsdbox/vctui) ⭐ 38 | 🐛 2 | 🌐 Go | 📅 2020-05-14 Console interface for vCenter
* [deputui](https://github.com/twiddler/deputui) ⭐ 37 | 🐛 5 | 🌐 Rust | 📅 2026-09-28 Review and install NPM package updates
* [every-other-token](https://github.com/Mattbusel/Every-Other-Token) ⭐ 32 | 🐛 3 | 🌐 Rust | 📅 2026-11-15 Streams an LLM response and colours each token by the model's confidence, with perplexity and the top alternatives in a full-screen view
* [violet](https://github.com/braheezy/violet) ⭐ 31 | 🐛 4 | 🌐 Go | 📅 2026-02-16 Colorful TUI frontend to run Vagrant commands
* [therapist](https://github.com/M-Komorek/therapist) ⭐ 26 | 🐛 0 | 🌐 Rust | 📅 2026-11-22 - A lightweight TUI log viewer for multi-GB files with bookmarks, grep tabs and phrase highlights.
* [logradar](https://github.com/nanook72/logradar) ⭐ 21 | 🐛 1 | 🌐 Rust | 📅 2026-11-25 A fast Rust TUI for interactive log filtering and highlighting.
* [burf](https://github.com/razeghi71/burf) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2026-02-02 TUI for Google Cloud Storage (GCS)
* [nodebro](https://github.com/jonaburg/nodebro) ⭐ 20 | 🐛 0 | 🌐 Go | 📅 2025-10-09 Easily view most recent Github releases/tags and release notes from the terminal
* [sq](https://github.com/sheenazien8/sq) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2026-02-25 A database client specially made for vim users
* [turbostream](https://github.com/turboline-ai/turbostream) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2026-02-23 Tool to extract key signals from high-velocity streaming data using AI Agents
* [dbterm](https://github.com/shreyam1008/dbterm) ⭐ 17 | 🐛 0 | 🌐 Go | 📅 2026-10-19 Terminal database workbench for PostgreSQL, MySQL, SQLite, Turso, and Cloudflare D1
* [catalyst](https://github.com/PraveenGongada/catalyst) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2026-05-05 Elegant TUI for triggering GitHub Actions workflows with matrix configurations.
* [Close Mongo Ops Manager](https://github.com/closeio/close-mongo-ops-manager) ⭐ 9 | 🐛 7 | 🌐 Python | 📅 2026-10-14 Monitor and kill MongoDB operations
* [LogLens](https://github.com/Caelrith/loglens-core) ⭐ 9 | 🐛 0 | 🌐 Rust | 📅 2025-11-21 A structured log viewer and query engine for the terminal.
* [git-tailor](https://github.com/jordfras/git-tailor) ⭐ 6 | 🐛 0 | 🌐 Rust | 📅 2026-11-25 An interactive terminal tool for tidying up Git commits on a branch
* [Wikit](https://github.com/BryanCE/wikit) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-11 TUI for managing Wiki.js instances
* [zlodev](https://github.com/vandot/zlodev) ⭐ 5 | 🐛 0 | 🌐 Zig | 📅 2026-11-26 Local dev HTTPS front door: `*.lo` domains with real certs, multi-app routing, and a TUI to inspect, intercept and replay traffic
* [Cloudeval](https://github.com/ganakailabs/cloudeval-cli) ⭐ 1 | 🐛 8 | 🌐 TypeScript | 📅 2026-09-10 Interactive cloud evaluations and reviews with project context, report views, and chat sessions. Supports Azure and static AWS CloudFormation (beta); requires a Cloudeval account.
* [raygun](https://github.com/yetidevworks/raygun) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-10-16 A terminal receiver for Spatie's Ray debugger, speaking the same HTTP protocol as the desktop app, for PHP, Laravel and Grav
* [lean-tui](https://codeberg.org/wvhulle/lean-tui) Interactive visualization of proofs and programs written in the Lean4 proof-assistant
* [mitmproxy](https://www.mitmproxy.org) A free and open source interactive HTTPS proxy
* [proxymock](https://proxymock.io) A network recorder that shows API payloads in a TUI and automatically generates tests and mocks from what it observes.

***

</details>

<details open><summary><h2>Docker/LXC/K8s</h2></summary>

* [dive](https://github.com/wagoodman/dive) ⭐ 54,769 | 🐛 156 | 🌐 Go | 📅 2026-11-19 A tool for exploring each layer in a docker image
* [lazydocker](https://github.com/jesseduffield/lazydocker) ⭐ 53,460 | 🐛 313 | 🌐 Go | 📅 2026-11-15 The lazier way to manage everything docker
* [k9s](https://github.com/derailed/k9s) ⭐ 35,082 | 🐛 119 | 🌐 Go | 📅 2026-11-20 TUI for managing a Kubernetes cluster
* [ctop](https://github.com/bcicen/ctop) ⭐ 17,861 | 🐛 122 | 🌐 Go | 📅 2024-07-08 Top-like interface for container metrics
* [dockly](https://github.com/lirantal/dockly) ⭐ 4,038 | 🐛 3 | 🌐 JavaScript | 📅 2026-11-04 Immersive terminal interface for managing docker containers and services
* [dry](https://github.com/moncho/dry) ⭐ 3,279 | 🐛 27 | 🌐 Go | 📅 2026-09-04 A Docker manager for the terminal
* [kdash](https://github.com/kdash-rs/kdash) ⭐ 2,559 | 🐛 6 | 🌐 Rust | 📅 2026-10-14 A simple and fast dashboard for Kubernetes
* [oxker](https://github.com/mrjackwills/oxker) ⭐ 2,094 | 🐛 32 | 🌐 Rust | 📅 2026-08-22 A simple tui to view & control docker containers
* [eks-node-viewer](https://github.com/awslabs/eks-node-viewer/) ⭐ 1,647 | 🐛 27 | 🌐 Go | 📅 2026-11-16 visualizing dynamic node usage within a kubernetes cluster
* [kftui](https://github.com/hcavarsan/kftray) ⭐ 1,582 | 🐛 24 | 🌐 Rust | 📅 2026-11-26 A TUI to manage multiple kubectl port-forward commands, with support for UDP and K8s proxy.
* [dtop](https://github.com/amir20/dtop) ⭐ 1,508 | 🐛 2 | 🌐 Rust | 📅 2026-11-27 Terminal dashboard for Docker monitoring across multiple hosts
* [Podman-tui](https://github.com/containers/podman-tui) ⭐ 1,278 | 🐛 16 | 🌐 Go | 📅 2026-11-16 TUI for Podman containers
* [ktop](https://github.com/vladimirvivien/ktop) ⭐ 1,122 | 🐛 8 | 🌐 Go | 📅 2026-11-26 A top-like tool for your Kubernetes clusters
* [sen](https://github.com/TomasTomecek/sen) ⭐ 1,046 | 🐛 36 | 🌐 Python | 📅 2026-11-09 Terminal User Interface for docker engine
* [e1s](https://github.com/keidarcy/e1s) ⭐ 949 | 🐛 9 | 🌐 Go | 📅 2026-11-01 TUI for managing AWS ECS resources
* [lfk](https://github.com/janosmiko/lfk) ⭐ 943 | 🐛 3 | 🌐 Go | 📅 2026-11-26 Keyboard-focused, yazi-inspired Kubernetes navigator with a Miller columns layout and an owner-based resource hierarchy
* [ducker](https://github.com/robertpsoane/ducker) ⭐ 932 | 🐛 15 | 🌐 Rust | 📅 2026-08-03 A slightly quackers Docker TUI based on k9s
* [Argonaut](https://github.com/darksworm/argonaut) ⭐ 475 | 🐛 12 | 🌐 Go | 📅 2026-11-14 ArgoCD TUI
* [kubetui](https://github.com/sarub0b0/kubetui) ⭐ 405 | 🐛 13 | 🌐 Rust | 📅 2026-11-25 A TUI tool designed for monitoring Kubernetes resources.
* [lazycontainer](https://github.com/andreybleme/lazycontainer) ⭐ 369 | 🐛 8 | 🌐 Go | 📅 2026-10-29 TUI for managing Apple containers
* [DockMate](https://github.com/shubh-io/dockmate) ⭐ 348 | 🐛 3 | 🌐 Go | 📅 2026-04-06 A lightweight TUI manager for Docker and Podman
* [lazytrivy](https://github.com/owenrumney/lazytrivy) ⭐ 328 | 🐛 15 | 🌐 Go | 📅 2026-11-19 The lazier way to scan images, k8s and the filesytem with Trivy
* [talos-pilot](https://github.com/handfish/talos-pilot) ⭐ 250 | 🐛 3 | 🌐 Rust | 📅 2026-07-24 TUI for Talos Linux providing real-time node monitoring, log streaming, and various diagnostics
* [Pocker](https://github.com/pommee/Pocker) ⭐ 190 | 🐛 2 | 🌐 Python | 📅 2025-03-16 TUI based application for docker related tasks.
* [cruise](https://github.com/cruise-org/cruise) ⭐ 184 | 🐛 19 | 🌐 Go | 📅 2026-07-09 A container management TUI
* [d4s](https://github.com/jr-k/d4s) ⭐ 143 | 🐛 0 | 🌐 Go | 📅 2026-11-03 A fast, keyboard-driven terminal UI to manage Docker containers, Compose stacks, and Swarm services with the ergonomics of K9s
* [layerx](https://github.com/deveshctl/layerx) ⭐ 138 | 🐛 3 | 🌐 Go | 📅 2026-11-20 Inspect container image layers in an interactive TUI with filesystem diffs, inline file viewing, and file extraction; supports Docker, Podman, and OCI archives
* [dprs](https://github.com/durableprogramming/dprs) ⭐ 42 | 🐛 0 | 🌐 Rust | 📅 2026-07-27 A TUI for managing Docker containers with real-time monitoring and log streaming
* [etcd-walker](https://github.com/nexusriot/etcd-walker/) ⭐ 26 | 🐛 0 | 🌐 Go | 📅 2026-09-12 Opensource TUI tool for managing etcd keys
* [docker-dash](https://github.com/GustavoCaso/docker-dash) ⭐ 25 | 🐛 22 | 🌐 Go | 📅 2026-11-20 A full TUI managemnet tool for Docker
* [SwarmCLI](https://github.com/Eldara-Tech/swarmcli) ⭐ 24 | 🐛 13 | 🌐 Go | 📅 2026-11-26 Swarm Management at the speed of thought — with real-time log streaming, instant shell access to containers, seamless port forwarding, and on-demand secret reveal capabilities, giving you full control over your Docker Swarm without breaking your flow.
* [k8s-tui](https://github.com/otavioCosta2110/k8s-tui) ⭐ 14 | 🐛 1 | 🌐 Go | 📅 2025-11-19 TUI Kubernetes resource manager with multi-cluster support
* [dockup](https://github.com/paulo-amaral/dockup) ⭐ 6 | 🐛 0 | 🌐 Go | 📅 2026-09-22 One-command TUI to install, harden and maintain Docker, Podman, NVIDIA toolkit and Apple container

***

</details>

<details open><summary><h2>Editors</h2></summary>

* [micro](https://github.com/micro-editor/micro) ⭐ 29,979 | 🐛 911 | 🌐 Go | 📅 2026-11-27 A modern and intuitive terminal-based text editor
* [Edit](https://github.com/microsoft/edit) ⭐ 14,820 | 🐛 164 | 🌐 Rust | 📅 2026-11-26 A simple text editor. Pays homage to the classic MS-DOS Editor.
* [Fresh](https://github.com/sinelaw/fresh) ⭐ 9,575 | 🐛 377 | 🌐 Rust | 📅 2026-11-26 An easy-to-use, powerful and fast terminal-based text editor.
* [kilo](https://github.com/antirez/kilo) ⭐ 9,261 | 🐛 66 | 🌐 C | 📅 2025-01-04 A minimal but complete editor in \~1000 lines of C code.
* [slap](https://github.com/slap-editor/slap) ⭐ 6,190 | 🐛 115 | 🌐 JavaScript | 📅 2021-11-01 Sublime-like terminal-based text editor
* [vis](https://github.com/martanne/vis) ⭐ 5,320 | 🐛 158 | 🌐 C | 📅 2026-11-26 A vi-like editor based on Plan 9's structural regular expressions
* [amp](https://github.com/jmacdonald/amp) ⭐ 4,144 | 🐛 94 | 🌐 Rust | 📅 2026-06-10 A complete text editor for your terminal
* [frogmouth](https://github.com/Textualize/frogmouth) ⭐ 3,326 | 🐛 45 | 🌐 Python | 📅 2024-08-01 A Markdown browser for your terminal
* [flow-control](https://github.com/neurocyte/flow) ⭐ 2,567 | 🐛 67 | 🌐 Zig | 📅 2026-11-26 A lightning-fast, feature-rich text editor written in Zig
* [Durdraw](https://github.com/durdraw/durdraw) ⭐ 1,872 | 🐛 7 | 🌐 Python | 📅 2026-11-10 An ASCII, Unicode and ANSI art editor
* [zee](https://github.com/zee-editor/zee) ⭐ 1,815 | 🐛 44 | 🌐 Rust | 📅 2025-02-06 A modern text editor for the terminal written in Rust
* [treemd](https://github.com/Epistates/treemd) ⭐ 739 | 🐛 0 | 🌐 Rust | 📅 2026-11-26 A markdown navigator with tree-based structural navigation
* [orbiton](https://github.com/xyproto/orbiton) ⭐ 724 | 🐛 0 | 🌐 Go | 📅 2026-11-25 Text editor limited by VT100, suitable for programming, writing git commit messages and editing Markdown
* [turbo](https://github.com/magiblot/turbo) ⭐ 694 | 🐛 38 | 🌐 C++ | 📅 2026-10-04 An experimental text editor for the terminal, based on Scintilla and Turbo Vision
* [tilde](https://github.com/gphalkes/tilde) ⭐ 561 | 🐛 65 | 🌐 C++ | 📅 2026-06-10 Intuitive text editor for the terminal
* [PNANA](https://github.com/Cyxuan0311/PNANA) ⭐ 330 | 🐛 15 | 🌐 C++ | 📅 2026-11-23 A modern terminal text editor built with FTXUI, inspired by Nano, Micro, and Sublime Text.
* [C-Edit](https://github.com/velorek1/c-edit) ⭐ 299 | 🐛 5 | 🌐 C | 📅 2026-11-22 A text editor with drop down menus in the style of MS-DOS Editor
* [edamame](https://github.com/mijowi/edamame) ⭐ 146 | 🐛 17 | 🌐 Rust | 📅 2026-11-24 A Terminal Markdown editor that stays rendered while you edit
* [nino](https://github.com/evanlin96069/nino) ⭐ 105 | 🐛 10 | 🌐 C | 📅 2026-10-24 A small terminal-based text editor written in C.
* [lazyide](https://github.com/TysonLabs/lazyide) ⭐ 103 | 🐛 8 | 🌐 Rust | 📅 2026-10-22 A lightweight terminal IDE in Rust: file tree, tabs, split panes, LSP, git diff view, minimap, 32 themes
* [markln](https://github.com/xqtr/markln) ⭐ 66 | 🐛 6 | 🌐 Python | 📅 2026-04-05 A terminal-based markdown editor built with Textual.
* [thymus](https://github.com/blademd/thymus) ⭐ 26 | 🐛 0 | 🌐 Python | 📅 2024-06-04 An interactive browser & editor for network configuration files.
* [hake](https://github.com/mithraeums/hako-edit) ⭐ 2 | 🐛 4 | 🌐 C | 📅 2026-11-24 Vim-style modal editor in one C file, with an AI agent in a side pane
* [helix](https://helix-editor.com/) A post-modern text editor.
* [hexed](https://codeberg.org/quorend/hexed) (Yet another) hex editor.
* [kakoune](http://kakoune.org/) A modern, modal text editor with focus on interactivity and efficiency
* [maki](https://sr.ht/~bscit/maki/) A simple tabbed text editor with file navigation and an emphasis on preserving battery life

***

</details>

<details open><summary><h2>File Managers</h2></summary>

* [yazi](https://github.com/sxyazi/yazi) ⭐ 43,682 | 🐛 71 | 🌐 Rust | 📅 2026-11-22 Blazing fast terminal file manager written in Rust, based on async I/O.
* [superfile](https://github.com/yorukot/superfile) ⭐ 24,137 | 🐛 287 | 🌐 Go | 📅 2026-11-25 Pretty fancy and modern terminal file manager.
* [nnn](https://github.com/jarun/nnn) ⭐ 22,147 | 🐛 1 | 🌐 C | 📅 2026-11-22 n³ The unorthodox terminal file manager.
* [ranger](https://github.com/ranger/ranger) ⭐ 17,467 | 🐛 895 | 🌐 Python | 📅 2026-11-26 A VIM-inspired file manager for the console.
* [broot](https://github.com/Canop/broot) ⭐ 13,213 | 🐛 103 | 🌐 Rust | 📅 2026-11-12 A new way to see and navigate directory trees
* [lf](https://github.com/gokcehan/lf) ⭐ 9,601 | 🐛 76 | 🌐 Go | 📅 2026-11-19 A terminal file manager written in Go with heavy inspiration from ranger file manager.
* [Vifm](https://github.com/vifm/vifm) ⭐ 3,287 | 🐛 148 | 🌐 C | 📅 2026-11-26 A TUI file manager with vi-keybindings and other vim like behaviour.
* [far2l](https://github.com/elfmz/far2l) ⭐ 2,246 | 🐛 514 | 🌐 C++ | 📅 2026-10-27 Linux port of Far v2 file manager
* [mc](https://github.com/MidnightCommander/mc) ⭐ 1,058 | 🐛 717 | 🌐 C | 📅 2026-11-26 GNU Midnight Commander. A free cross-platform orthodox file manager.
* [elio](https://github.com/elio-fm/elio) ⭐ 921 | 🐛 10 | 🌐 Rust | 📅 2026-11-26 Snappy, batteries-included terminal file manager.
* [TUIFIManager](https://github.com/GiorgosXou/TUIFIManager) ⭐ 829 | 🐛 15 | 🌐 Python | 📅 2026-06-30 A cross-platform terminal-based file manager *(supports termux)*.
* [rovr](https://github.com/NSPC911/rovr) ⭐ 420 | 🐛 12 | 🌐 Python | 📅 2026-11-26 A post-modern terminal file manager.
* [goful](https://github.com/anmitsu/goful) ⭐ 382 | 🐛 4 | 🌐 Go | 📅 2021-11-29 a powerful TUI file manager written in Go.
* [sfm](https://github.com/afify/sfm) ⭐ 260 | 🐛 6 | 🌐 C | 📅 2025-11-14 Simple file manager.
* [deletor](https://github.com/pashkov256/deletor) ⭐ 258 | 🐛 11 | 🌐 Go | 📅 2026-04-04 Manage and delete files efficiently with an interactive TUI and scriptable CLI.
* [adbtuifm](https://github.com/darkhz/adbtuifm) ⭐ 192 | 🐛 3 | 🌐 Go | 📅 2022-03-16 A TUI file manager for Android, based on the Android Debug Bridge(ADB).
* [fml](https://github.com/wick3dr0se/fml) ⭐ 107 | 🐛 0 | 🌐 Shell | 📅 2024-02-03 :file\_folder: A stupid simple, fast file manager written in BASH v4.2+.
* [ytreenova](https://github.com/robkam/ytreenova) ⭐ 19 | 🐛 4 | 🌐 C | 📅 2026-11-17 The XTree™ style file manager Unix should have had all along.
* [FileView](https://github.com/Hiro-Chiba/fileview) ⭐ 18 | 🐛 2 | 🌐 Rust | 📅 2026-11-01 A terminal file browser with image previews, Git status, search, and an MCP server.
* [fyzenor](https://github.com/Bimbok/fyzenor) ⭐ 15 | 🐛 7 | 🌐 C++ | 📅 2026-09-24 A modern, blazing-fast terminal file manager built in C++ with live previews, async workflows, and a polished three-column interface.
* [s3duck-tui](https://github.com/nexusriot/s3duck-tui) ⭐ 10 | 🐛 0 | 🌐 Go | 📅 2026-11-23 A TUI S3 client.
* [ntc](https://codeberg.org/ItsZariep/ntc) Ncurses Tabbed file Chooser.

***

</details>

<details open><summary><h2>Games</h2></summary>

* [NetHack](https://github.com/NetHack/NetHack) ⭐ 4,005 | 🐛 148 | 🌐 C | 📅 2026-11-26 Dungeon exploration game
* [tinytetris](https://github.com/taylorconor/tinytetris) ⭐ 3,299 | 🐛 29 | 🌐 C++ | 📅 2024-07-09 80x23 terminal tetris!
* [pokete](https://github.com/lxgr-linux/pokete) ⭐ 3,156 | 🐛 30 | 🌐 Python | 📅 2026-11-22 A terminal based Pokemon like game
* [sshtron](https://github.com/zachlatta/sshtron) ⭐ 2,496 | 🐛 12 | 🌐 Go | 📅 2023-07-17 multiplayer lightcycle game that runs through SSH
* [awkaster](https://github.com/TheMozg/awk-raycaster) ⭐ 2,477 | 🐛 1 | 🌐 Awk | 📅 2023-01-20 Pseudo-3D shooter written completely in gawk using raycasting technique
* [GitType](https://github.com/unhappychoice/gittype) ⭐ 1,675 | 🐛 17 | 🌐 Rust | 📅 2026-11-26 A CLI code-typing game that turns your source code into typing challenges
* [Gameboy Emulator](https://github.com/gabrielrcouto/php-terminal-gameboy-emulator) ⭐ 1,612 | 🐛 6 | 🌐 PHP | 📅 2020-11-02 A PHP Terminal GameBoy Emulator
* [BrogueCE](https://github.com/tmewett/BrogueCE) ⭐ 1,539 | 🐛 204 | 🌐 C | 📅 2026-11-23 Beautiful roguelike dungeon crawler
* [chess-tui](https://github.com/thomas-mauran/chess-tui) ⭐ 1,228 | 🐛 29 | 🌐 Rust | 📅 2026-11-26 Play Chess in your terminal, built in rust
* [steam-tui](https://github.com/dmadisetti/steam-tui) ⭐ 1,042 | 🐛 9 | 🌐 Rust | 📅 2026-03-12 Just a simple TUI client for steamcmd. Allows for the graphical launching, updating, and downloading of steam games through a simple terminal client.
* [Square Tic Tac Toe](https://github.com/learnbyexample/TUI-apps/tree/main/SquareTicTacToe) ⭐ 1,024 | 🐛 0 | 🌐 Python | 📅 2026-02-02 Like Tic Tac Toe, but form a square with 4 corners instead of a line
* [DOOM-ASCII](https://github.com/wojciech-graj/doom-ascii) ⭐ 907 | 🐛 0 | 🌐 C | 📅 2026-10-06 Text-based DOOM running in terminal.
* [tetro-tui](https://github.com/Strophox/tetro-tui) ⭐ 772 | 🐛 7 | 🌐 Rust | 📅 2026-08-13 A very configurable tetris-like, featuring ASCII particles, replays and more.
* [Rebels in the sky](https://github.com/ricott1/rebels-in-the-sky) ⭐ 768 | 🐛 7 | 🌐 Rust | 📅 2026-11-03 P2P terminal game about spacepirates playing basketball across the galaxy.
* [clidle](https://github.com/ajeetdsouza/clidle) ⭐ 640 | 🐛 1 | 🌐 Go | 📅 2026-11-07 Play Wordle in your terminal. Also works over SSH!
* [botany](https://github.com/jifunks/botany/) ⭐ 560 | 🐛 10 | 🌐 Python | 📅 2026-07-18 Virtual plant buddy
* [nudoku](https://github.com/jubalh/nudoku) ⭐ 376 | 🐛 2 | 🌐 C | 📅 2026-07-08 ncurses based sudoku game
* [tty-solitaire](https://github.com/mpereira/tty-solitaire) ⭐ 363 | 🐛 25 | 🌐 C | 📅 2025-05-03 Solitaire runs in your terminal!
* [bastet](https://github.com/fph/bastet) ⭐ 322 | 🐛 13 | 🌐 C++ | 📅 2022-10-08 Evil falling block game
* [cli-chess](https://github.com/trb346/cli-chess) ⭐ 314 | 🐛 17 | 🌐 Python | 📅 2026-09-29 A highly customizable way to play chess in your terminal. Play online (via Lichess.org) and offline against the Fairy-Stockfish engine. All Lichess variants are supported.
* [sssnake](https://github.com/AngelJumbo/sssnake) ⭐ 235 | 🐛 0 | 🌐 C | 📅 2026-10-26 The classic snake game for the terminal that can play itself and be used like a screensaver.
* [nSnake](https://github.com/alexdantas/nSnake) ⭐ 229 | 🐛 23 | 🌐 C++ | 📅 2023-09-27 The classic snake game with textual interface
* [balatrotui](https://github.com/Passeriform/BalatroTUI) ⭐ 214 | 🐛 5 | 🌐 Rust | 📅 2026-05-01 A TUI clone of Balatro
* [Micro Tetris](https://github.com/troglobit/tetris) ⭐ 172 | 🐛 1 | 🌐 C | 📅 2025-06-22 One of the smallest Tetris implementations in the world, utilizing only ANSI escape sequences to draw the board.
* [go-life](https://github.com/sachaos/go-life) ⭐ 148 | 🐛 5 | 🌐 Go | 📅 2024-12-29 Terminal based Conway's Game of Life
* [ssHattrick](https://github.com/ricott1/sshattrick) ⭐ 146 | 🐛 2 | 🌐 Rust | 📅 2026-05-30 Play Hattrick in your terminal over SSH.
* [Maze](https://github.com/itchyny/maze) ⭐ 130 | 🐛 0 | 🌐 Go | 📅 2024-03-23 Simple maze game written in Go.
* [csol](https://github.com/nielssp/csol) ⭐ 120 | 🐛 0 | 🌐 C | 📅 2025-07-19 Collection of solitaire/patience games, such as Klondike, FreeCell, Spider, and Yukon
* [snake](https://github.com/wick3dr0se/snake) ⭐ 115 | 🐛 2 | 🌐 Shell | 📅 2023-06-17 :video\_game: A super minimal TUI snake game written in pure BASH v5.1+
* [moon-buggy](https://github.com/seehuhn/moon-buggy) ⭐ 112 | 🐛 0 | 🌐 C | 📅 2026-10-13 Drive some car across the moon
* [Maze TUI](https://github.com/agl-alexglopez/maze-tui) ⭐ 82 | 🐛 0 | 🌐 Rust | 📅 2025-10-24 Build mazes and solve them with various algorithms.
* [typing-game-cli](https://github.com/akgondber/typing-game-cli) ⭐ 68 | 🐛 0 | 🌐 JavaScript | 📅 2026-10-09 Command line game to practice your typing speed by competing against typer-robot or against your best result
* [termrex](https://github.com/SATYADAHAL/termrex) ⭐ 51 | 🐛 1 | 🌐 C++ | 📅 2026-02-22 A terminal-based endless runner game inspired by the Chrome Dino offline game.
* [LeTrain](https://github.com/antoniovazquezaraujo/LeTrain) ⭐ 50 | 🐛 49 | 🌐 Java | 📅 2026-11-13 - Open-source procedural train simulator using Java 17, LibGDX and Lanterna.
* [sudoku-rs](https://github.com/MitchelPaulin/sudoku-rs) ⭐ 38 | 🐛 0 | 🌐 Rust | 📅 2024-08-17 Sudoku built with tui-rs
* [Micro Snake](https://github.com/troglobit/snake) ⭐ 37 | 🐛 1 | 🌐 C | 📅 2023-04-16 A small snake game, utilizing ANSI escape sequences to draw the board.
* [terminal-pong](https://github.com/IshmamR/terminal.pong) ⭐ 35 | 🐛 0 | 🌐 Rust | 📅 2025-07-09 A simple, fun ping pong game playable entirely in your terminal.
* [typeinc](https://github.com/AnirudhG07/Typeinc) ⭐ 35 | 🐛 0 | 🌐 Python | 📅 2025-06-28 ncurses based typing speed test with various difficulty levels.
* [Zigtris](https://github.com/ringtailsoftware/zigtris) ⭐ 32 | 🐛 0 | 🌐 Zig | 📅 2025-12-17 YA terminal tetris
* [Gravitype](https://github.com/kanakOS01/gravitype) ⭐ 31 | 🐛 0 | 🌐 Python | 📅 2026-10-03 A terminal typing game where words fall from the sky
* [brickgame-4bit](https://github.com/ilyakurdyukov/brickgame-4bit) ⭐ 29 | 🐛 1 | 🌐 C | 📅 2024-05-11 Brick Game emulator (4-bit Holtek chip)
* [minesweeper\_4d\_rs](https://github.com/itabesamesa/minesweeper_4d_rs) ⭐ 21 | 🐛 0 | 🌐 Rust | 📅 2026-01-25 4D minesweeper written in Rust using Ratatui (can also be used for classic minesweeper)
* [nchess](https://github.com/billyvinning/nchess) ⭐ 21 | 🐛 0 | 🌐 C | 📅 2023-05-03 Chess in the terminal, written in C.
* [onx](https://github.com/jerkyworks/onx) ⭐ 16 | 🐛 4 | 🌐 Python | 📅 2022-10-06 Noughts & Crosses client-server game with your partner. Based on textual and python.
* [Zoridor](https://github.com/ringtailsoftware/zoridor) ⭐ 16 | 🐛 0 | 🌐 Zig | 📅 2025-01-17 Play Quoridor in the terminal
* [gokemon](https://github.com/nathanieltooley/gokemon) ⭐ 11 | 🐛 12 | 🌐 Go | 📅 2025-10-31 A terminal based Pokemon battle simulator
* [UniPac](https://github.com/jesper-olsen/UniPac) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2026-11-10 Unicode-powered Pac-Man for the terminal, written in Rust.
* [sweeper](https://github.com/igor47/sweeper) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-04-30 Minesweeper game using curtsies
* [tui-2048](https://github.com/ps06756/tui-2048) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-01-03 The game 2048 for your terminal
* [CHAOS RPG](https://github.com/Mattbusel/chaos-rpg) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2026-10-21 A roguelike where every hit, heal and loot drop is decided by chaining real math (Lorenz attractor, Mandelbrot set, Collatz)
* [Wordle](https://github.com/m-dango/raku-wordle/) ⭐ 2 | 🐛 2 | 🌐 Raku | 📅 2022-03-19 Script and library for Wordle, written in Raku
* [bell-system-sim](https://github.com/WPTK/bell-system-sim) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-11-05 Work a Bell System repair test desk in 1983 from a fake UNIX V7 shell and close out phone trouble reports
* [cbonsai](https://gitlab.com/jallbrit/cbonsai) A bonsai tree generator
* [Greed](https://gitlab.com/esr/greed) A game of consumption. Eat as much as you can before munching yourself into a corner!
* [MyMan](https://sourceforge.net/projects/myman/) MyMan is a video game for color and monochrome text terminals in the genre of Namco's Pac-Man
* [nInvaders](http://ninvaders.sourceforge.net/) Space Invaders
* [terminal-phase](https://gitlab.com/dustyweb/terminal-phase) Space shooter game that runs in your terminal!
* [wocogo](https://codeberg.org/kedlubnowski/wocogo) Construct words from a list of given segments. A simple TUI game in Python, similar to the NY Times Combinations game.

***

</details>

<details open><summary><h2>Libraries</h2></summary>

<h3>Python</h3>

* [Rich](https://github.com/Textualize/rich) ⭐ 57,895 | 🐛 409 | 🌐 Python | 📅 2026-11-13 is a **Python** library for rich text and beautiful formatting in the terminal.
* [textual](https://github.com/Textualize/textual) ⭐ 37,747 | 🐛 419 | 🌐 Python | 📅 2026-11-09 is a TUI (Text User Interface) framework for **Python** inspired by modern web development.
* [Python Prompt Toolkit](https://github.com/prompt-toolkit/python-prompt-toolkit) ⭐ 10,632 | 🐛 790 | 🌐 Python | 📅 2026-10-20 Library for building powerful interactive command line applications in **Python**
* [notcurses](https://github.com/dankamongmen/notcurses) ⭐ 4,785 | 🐛 330 | 🌐 C | 📅 2026-11-26 blingful character graphics/TUI library for **C** and **Python**. definitely not curses.
* [urwid](https://github.com/urwid/urwid) ⭐ 3,027 | 🐛 49 | 🌐 Python | 📅 2026-11-26 A console user interface library for **Python** on Linux, OSX, Cygwin or other unix-like OS.
* [blessed](https://github.com/jquast/blessed) ⭐ 1,516 | 🐛 3 | 🌐 Python | 📅 2026-11-20 Blessed is an easy, practical library for making **Python** terminal apps
* [blessings](https://github.com/erikrose/blessings) ⭐ 1,490 | 🐛 32 | 🌐 Python | 📅 2025-08-28 A **Python** wrapper lib for ncurses that makes your code pretty to look at
* [pyTermTk](https://github.com/ceccopierangiolieugenio/pyTermTk) ⭐ 924 | 🐛 55 | 🌐 Python | 📅 2026-11-12 self-contained TUI library for **Python** with a QT-like API semantics
* [py\_cui](https://github.com/jwlodek/py_cui) ⭐ 790 | 🐛 48 | 🌐 Python | 📅 2026-03-27 **Python** library aimed at making widget based TUI/CUI interfaces as simple as possible. Supports standard widgets and popups like menus, textboxes, forms, file explorers etc.
* [UniCurses](https://github.com/unicurses/unicurses) ⭐ 174 | 🐛 8 | 🌐 Python | 📅 2026-07-30 A **Python** module that is aimed at providing the Curses functionality on all operating systems.
* [Argenta](https://github.com/koloideal/Argenta) ⭐ 34 | 🐛 1 | 🌐 Python | 📅 2026-11-26 Library for building modular applications **Python**
* [xnano](https://github.com/hsaeed3/xnano) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2026-11-22 A modern, lightweight and declarative **Python** TUI framework built on top of the Rust ratatui and tachyonfx libraries. ([docs](https://xnano.hammad.app))
* [Vindauga](https://github.com/gabbpuy/vindauga) ⭐ 18 | 🐛 1 | 🌐 Python | 📅 2026-08-20 A **Python** implementation of the BSD licensed C++ Turbo Vision library.
* [textual-themes](https://github.com/michaelblaess/textual-themes) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2026-10-13 41 retro color themes for Textual apps in **Python**
* [animpy](https://github.com/13DoesPython/animpy) ⭐ 5 | 🐛 0 | 🌐 HTML | 📅 2026-09-12 - Terminal animations in **Python** without the pain.
* [textual-widgets](https://github.com/michaelblaess/textual-widgets) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2026-10-13 Reusable widgets for Textual apps in **Python**: date picker, context menu, splitter, log panel and modal dialogs
* [flexablelib](https://github.com/Opus-Perpetuus/flexablelib) ⭐ 1 | 🐛 1 | 🌐 Python | 📅 2026-11-26 Dependency-free **Python** library for terminal tables with 56 border styles, colours, cell merges and decimal alignment.

<h3>GO</h3>

* [bubbletea](https://github.com/charmbracelet/bubbletea) ⭐ 45,897 | 🐛 232 | 🌐 Go | 📅 2026-11-26 A **Go** framework based on Elm to build functional and fun terminal apps
* [tview](https://github.com/rivo/tview/) ⭐ 14,164 | 🐛 112 | 🌐 Go | 📅 2026-08-11 Terminal UI library with rich, interactive widgets — written in **Go**
* [gocui](https://github.com/jroimartin/gocui) ⭐ 10,625 | 🐛 61 | 🌐 Go | 📅 2025-05-01 Minimalist **Go** package aimed at creating Console User Interfaces
* [pterm](https://github.com/pterm/pterm/) ⭐ 5,571 | 🐛 75 | 🌐 Go | 📅 2026-10-12 A modern **Go** module to beautify console output. Featuring charts, progressbars, tables, trees, and much more! It's completely configurable and 100% cross-platform compatible.
* [tcell](https://github.com/gdamore/tcell) ⭐ 5,247 | 🐛 24 | 🌐 Go | 📅 2026-11-24 Tcell is an alternate **Go** terminal package, similar in some ways to termbox, but better in others.
* [stickers](https://github.com/76creates/stickers) ⭐ 401 | 🐛 3 | 🌐 Go | 📅 2026-04-28 Building blocks for charmbracelet/lipgloss in **Go**

<h3>C</h3>

* [libuv](https://github.com/libuv/libuv) ⭐ 27,356 | 🐛 288 | 🌐 C | 📅 2026-11-25 Cross-platform asynchronous I/O library - written in **C**
* [tuibox](https://github.com/Cubified/tuibox) ⭐ 350 | 🐛 4 | 🌐 C | 📅 2023-12-01 A single-header **C** terminal UI library, capable of creating mouse-driven, interactive applications on the command line.
* [AnbUI](https://github.com/oerg866/anbui) ⭐ 43 | 🐛 3 | 🌐 C | 📅 2026-10-29 A minimal Text UI Library in **C**
* [ncurses](https://invisible-island.net/ncurses/announce.html) A classic **C** library with bindings for many languages

<h3>C++</h3>

* [FTXUI](https://github.com/ArthurSonzogni/FTXUI) ⭐ 10,918 | 🐛 27 | 🌐 C++ | 📅 2026-11-22 💻 **C++** Functional Terminal User Interface. ❤️
* [imtui](https://github.com/ggerganov/imtui) ⭐ 3,641 | 🐛 21 | 🌐 C++ | 📅 2025-10-10 An immediate mode text-based user interface **C++** library, supporting 256 ANSI colors and mouse/keyboard input.
* [tvision](https://github.com/magiblot/tvision) ⭐ 3,221 | 🐛 55 | 🌐 C++ | 📅 2026-11-14 A modern port of **C++** Turbo Vision 2.0, cross-platform and Unicode support.
* [uvw](https://github.com/skypjack/uvw) ⭐ 2,064 | 🐛 13 | 🌐 C++ | 📅 2026-11-09 Header-only, event based, tiny and easy to use libuv wrapper in modern **C++**
  now available as also shared/static library!
* [rang](https://github.com/agauniyal/rang) ⭐ 1,595 | 🐛 26 | 🌐 C++ | 📅 2026-05-16 A Minimal, Header only Modern **C++** library for terminal goodies.
* [FINAL CUT](https://github.com/gansm/finalcut) ⭐ 1,207 | 🐛 14 | 🌐 C++ | 📅 2026-11-10 **C++** library for creating terminal applications with text-based widgets
* [xtd](https://github.com/gammasoft71/xtd) ⭐ 1,172 | 🐛 99 | 🌐 C++ | 📅 2026-11-27 Free open-source modern **C++** framework to create console (CLI), forms (GUI like WinForms) and unit test (xUnit) applications and libraries on Windows, macOS, Linux, iOS, Android, FreeBSD, and Haiku.
* [ConsoleCraftEngine](https://github.com/ural89/ConsoleCraftEngine) ⭐ 99 | 🐛 2 | 🌐 C++ | 📅 2026-09-03 A terminal-based 2D game engine written in **C++**.
* [termdb](https://github.com/agauniyal/termdb) ⭐ 47 | 🐛 2 | 🌐 C++ | 📅 2018-05-11 Terminfo parser for modern **C++**
* [Tui Widgets](https://github.com/tuiwidgets/tuiwidgets) ⭐ 30 | 🐛 4 | 🌐 C++ | 📅 2026-09-15 A high-level widget based toolkit for terminal applications in **C++**
* [GGUI](https://github.com/Gabidal/GGUI) ⭐ 10 | 🐛 2 | 🌐 C++ | 📅 2026-11-21 **C++17** Structured Terminal User Interface. 🐧/🪟
* [koto](https://github.com/saber-88/koto) ⭐ 6 | 🐛 0 | 🌐 C++ | 📅 2026-11-15 A modern, zero dependency immediate mode **C++23** TUI library.
* [ASCII\_Board\_Game\_Engine](https://github.com/tjunruh/ASCII_Board_Game_Engine) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2026-11-21 A graphics engine for making board games in **C++**

<h3>Java</h3>

* [Lanterna](https://github.com/mabe02/lanterna) ⭐ 2,638 | 🐛 98 | 🌐 Java | 📅 2026-07-07 A **Java** library for creating text-based UIs, very similar to the C library curses but with more functionality.
* [TamboUI](https://github.com/tamboui/tamboui) ⭐ 705 | 🐛 171 | 🌐 Java | 📅 2026-11-26 A **Java** library for building modern terminal user interfaces. Initial port of Ratatui but have higher level inspiration from Textual providing super effecient immediate mode but also a toolkit with Cascading Style Sheets (CSS) and big library of reusable components.
* [TUI4J](https://github.com/WilliamAGH/tui4j) ⭐ 138 | 🐛 3 | 🌐 Java | 📅 2026-10-23 A **Java** terminal UI framework with a Bubble Tea (Go) port and additional features inspired by Textual.
* [casciian](https://github.com/crramirez/casciian) ⭐ 58 | 🐛 1 | 🌐 Java | 📅 2026-11-19 A Text User Interface Library for **Java** based on "Jexer" without the AWT/Swing dependencies, tailored for GraalVM AOT native compilation with a focus on performance over remote connections and maximum terminal compatibility.
* [Jexer](https://gitlab.com/AutumnMeowMeow/jexer) A **Java** library implements a text-based windowing system loosely reminiscent of Borland's Turbo Vision system.

<h3>.NET</h3>

* [Spectre.Console](https://github.com/spectreconsole/spectre.console) ⭐ 11,720 | 🐛 161 | 🌐 C# | 📅 2026-11-22 A **.NET** library for creating beautiful console applications
* [Terminal.Gui](https://github.com/tui-cs/Terminal.Gui) ⭐ 11,321 | 🐛 51 | 🌐 C# | 📅 2026-11-26 Cross-platform terminal UI toolkit for **.NET**
* [RazorConsole](https://github.com/RazorConsole/RazorConsole) ⭐ 1,744 | 🐛 35 | 🌐 C# | 📅 2026-11-26 A **.NET** library for building interactive terminal UIs with Razor components and keyboard/mouse support
* [Consolonia](https://github.com/Consolonia/Consolonia) ⭐ 854 | 🐛 59 | 🌐 C# | 📅 2026-11-24 A **.NET** terminal-based GUI framework with support of XAML
* [SharpConsoleUI](https://github.com/nickprotop/ConsoleEx) ⭐ 310 | 🐛 1 | 🌐 C# | 📅 2026-11-17 Multi-window TUI framework for **.NET** with overlapping windows, compositor effects, and Spectre.Console integration
* [Hex1b](https://github.com/mitchdenny/hex1b) ⭐ 185 | 🐛 152 | 🌐 C# | 📅 2026-11-27 A **.NET** library for building rich, interactive TUIs with a React-inspired declarative API
* [Elaris.UI](https://github.com/ambystechcom/Ambystech.Elaris.UI) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2026-11-24 A lightweight Terminal UI library for **.NET** with true 24-bit RGB color support. Built for modern terminals with cross-platform support.

<h3>Rust</h3>

* [Ratatui](https://github.com/ratatui/ratatui) ⭐ 23,451 | 🐛 173 | 🌐 Rust | 📅 2026-11-25 A **Rust** crate for building Terminal UIs (actively maintained fork of tui-rs).
* [iocraft](https://github.com/ccbrown/iocraft) ⭐ 1,586 | 🐛 31 | 🌐 Rust | 📅 2026-11-26 **Rust** crate for beautiful, artisanally crafted TUIs and text-based IO, with a declarative, React-like API inspired by Ink.
* [AppCUI-rs](https://github.com/gdt050579/AppCUI-rs) ⭐ 408 | 🐛 42 | 🌐 Rust | 📅 2026-11-26 Cross-platform **Rust** TUI framework   with overlapping windows, menus, dialogs and 50+ built-in controls (lists, trees, charts, date pickers, hex viewer), themes and mouse support.
* [tui-input](https://github.com/sayanarijit/tui-input) ⭐ 207 | 🐛 3 | 🌐 Rust | 📅 2026-09-26 TUI input library supporting multiple backends, tui-rs and ratatui in **Rust**
* [Ratatui Kit](https://github.com/yexiyue/ratatui-kit) ⭐ 62 | 🐛 0 | 🌐 Rust | 📅 2026-10-11 **Rust** crate that allows for the creation of React-like components built on top of Ratatui.

<h3>Other</h3>

* [ink](https://github.com/vadimdemedes/ink) ⭐ 40,338 | 🐛 29 | 🌐 TypeScript | 📅 2026-11-24 React for **Node.js** interactive command-line apps
* [gum](https://github.com/charmbracelet/gum) ⭐ 24,699 | 🐛 226 | 🌐 Go | 📅 2026-11-20 A tool for glamorous **shell** scripts
* [OpenTUI](https://github.com/anomalyco/opentui) ⭐ 13,931 | 🐛 83 | 🌐 TypeScript | 📅 2026-11-26 A **TypeScript** library for building terminal user interfaces (TUIs)
* [blessed](https://github.com/chjj/blessed) ⭐ 11,886 | 🐛 254 | 🌐 JavaScript | 📅 2024-03-22 A high-level terminal interface library for **Node.js**
  stateful TUI apps.
* [termbox2](https://github.com/termbox/termbox2) ⭐ 799 | 🐛 18 | 🌐 C | 📅 2026-11-25 A terminal rendering library for creating TUIs.
* [php-tui](https://github.com/php-tui/php-tui) ⭐ 620 | 🐛 16 | 🌐 PHP | 📅 2026-05-04 comprehensive TUI library for **PHP** based heavily on Ratatui.
* [nimwave](https://github.com/ansiwave/nimwave) ⭐ 551 | 🐛 2 | 🌐 Nim | 📅 2023-09-29 Build text interfaces for the terminal or browser in **Nim**
* [nocterm](https://github.com/Norbert515/nocterm) ⭐ 413 | 🐛 24 | 🌐 Dart | 📅 2026-10-01 A Flutter-like TUI framework for **Dart** with hot reload, 45+ components, and declarative UI patterns.
* [TermGL](https://github.com/wojciech-graj/TermGL) ⭐ 409 | 🐛 0 | 🌐 C | 📅 2025-12-28 A terminal-based graphics library for 2D and 3D graphics.
* [TermDOM](https://github.com/bikeshaving/termdom) ⭐ 334 | 🐛 16 | 🌐 TypeScript | 📅 2026-11-27 A **JavaScript** library that displays HTML and CSS in the terminal, with a real DOM
* [Ashen](https://github.com/colinta/Ashen) ⭐ 120 | 🐛 2 | 🌐 Swift | 📅 2022-10-07 An Elm inspired framework written in **Swift**
* [Thermage](https://github.com/thermage/thermage) ⭐ 95 | 🐛 6 | 🌐 PHP | 📅 2022-09-19 Thermage is a **PHP** library that provides a fluent and incredibly powerful, object-oriented interface for customizing CLI output text color, background, formatting, theming and more.
* [ink-web](https://github.com/cjroth/ink-web) ⭐ 90 | 🐛 1 | 🌐 TypeScript | 📅 2026-03-02 A browser-based runtime for Ink that renders React TUI apps in the browser using xterm.js.
* [Raxol](https://github.com/DROOdotFOO/raxol) ⭐ 83 | 🐛 92 | 🌐 Elixir | 📅 2026-11-23 A multi-surface runtime for **Elixir**: one application renders to the terminal, browser, SSH, and agent surfaces, with per-component crash isolation and hot reload from the BEAM.
* [dart\_tui](https://github.com/codenameakshay/dart_tui) ⭐ 18 | 🐛 0 | 🌐 Dart | 📅 2026-11-26 Elm-style terminal UI framework for **Dart**: components, forms, Lip Gloss-style styling.
* [Melker](https://melker.sh) A HTML-like, document-first TUI framework for **TypeScript/Deno** with permission sandboxing, flexbox layout, and run-from-URL support.
* [moulti](https://moulti.run/) A CLI-driven TUI displaying arbitrary outputs inside visual, collapsible blocks. Designed with **shell** scripts in mind. **Ansible**-friendly too.

***

</details>

<details open><summary><h2>Messaging</h2></summary>

* [Slack-term](https://github.com/jpbruinsslot/slack-term) ⭐ 6,612 | 🐛 69 | 🌐 Go | 📅 2024-04-23 Slack client for your terminal
* [discordo](https://github.com/ayn2op/discordo) ⭐ 5,900 | 🐛 39 | 🌐 Go | 📅 2026-11-17 A lightweight, secure, and feature-rich Discord terminal client
* [Devzat](https://github.com/quackduck/devzat) ⭐ 4,073 | 🐛 25 | 🌐 Go | 📅 2026-07-23 Chat over SSH, written in Golang with self-hosting ability.
* [nomadnet](https://github.com/markqvist/NomadNet) ⭐ 2,677 | 🐛 1 | 🌐 Python | 📅 2026-11-18 Secure messaging network built on Reticulum
* [sclack](https://github.com/haskellcamargo/sclack) ⭐ 2,475 | 🐛 45 | 🌐 Python | 📅 2022-12-08 Slack terminal client
* [instagram-cli](https://github.com/supreme-gg-gg/instagram-cli) ⭐ 2,218 | 🐛 43 | 🌐 TypeScript | 📅 2026-11-21 Use Instagram from your terminal, the end of brainrot is here
* [nchat](https://github.com/d99kris/nchat) ⭐ 2,035 | 🐛 10 | 🌐 C++ | 📅 2026-11-22 Telegram/WhatsApp/Signal client
* [gomuks](https://github.com/gomuks/gomuks) ⭐ 1,738 | 🐛 91 | 🌐 Go | 📅 2026-11-26 Matrix client
* [concord](https://github.com/chojs23/concord) ⭐ 1,695 | 🐛 56 | 🌐 Rust | 📅 2026-11-26 A feature-rich TUI client for Discord
* [gurk-rs](https://github.com/boxdot/gurk-rs) ⭐ 1,411 | 🐛 107 | 🌐 Rust | 📅 2026-11-26 Signal Messenger client for terminal
* [basalt](https://github.com/erikjuhani/basalt) ⭐ 1,405 | 🐛 35 | 🌐 Rust | 📅 2026-11-25 TUI Application to manage Obsidian vaults and notes directly from the terminal.
* [toot](https://github.com/ihabunek/toot) ⭐ 1,331 | 🐛 130 | 🌐 Python | 📅 2026-09-12 Mastodon CLI & TUI
* [toxic](https://github.com/JFreegman/toxic/) ⭐ 1,304 | 🐛 19 | 🌐 C | 📅 2026-11-25 A Tox-based instant messaging and video chat client
* [matcha](https://github.com/floatpane/matcha) ⭐ 1,241 | 🐛 55 | 🌐 Go | 📅 2026-11-26 Email client
* [matterhorn](https://github.com/matterhorn-chat/matterhorn) ⭐ 1,170 | 🐛 22 | 🌐 Haskell | 📅 2026-11-22 A Mattermost terminal client.
* [tgt](https://github.com/FedericoBruzzone/tgt) ⭐ 1,052 | 🐛 17 | 🌐 Rust | 📅 2026-11-23 A TUI for Telegram written in Rust
* [endcord](https://github.com/sparklost/endcord) ⭐ 1,043 | 🐛 3 | 🌐 Python | 📅 2026-11-26 Feature rich Discord TUI client.
* [sup](https://github.com/sup-heliotrope/sup) ⭐ 972 | 🐛 63 | 🌐 Ruby | 📅 2026-11-24 A curses threads-with-tags style email client
* [zulip-terminal](https://github.com/zulip/zulip-terminal) ⭐ 887 | 🐛 504 | 🌐 Python | 📅 2026-11-26 Official Zulip terminal client (similar to matterhorn)
* [twitch-tui](https://github.com/Xithrius/twitch-tui) ⭐ 637 | 🐛 10 | 🌐 Rust | 📅 2026-11-26 Twitch chat in the terminal
* [scli](https://github.com/isamert/scli/) ⭐ 540 | 🐛 26 | 🌐 Python | 📅 2024-11-30 A simple terminal user interface for signal messenger
* [tut](https://github.com/RasmusLindroth/tut) ⭐ 501 | 🐛 56 | 🌐 Go | 📅 2023-12-18 Mastodon TUI client
* [tele](https://github.com/sorokin-vladimir/tele) ⭐ 260 | 🐛 122 | 🌐 Go | 📅 2026-11-26 - A keyboard-first Telegram client with a TUI, CLI and background daemon
* [tuisky](https://github.com/sugyan/tuisky) ⭐ 165 | 🐛 12 | 🌐 Rust | 📅 2025-12-28 TUI client for BlueSky
* [marchat](https://github.com/Cod-e-Codes/marchat) ⭐ 140 | 🐛 5 | 🌐 Go | 📅 2026-10-17 Self-hosted terminal chat with WebSocket client/server, optional shared-key encryption, and plugins.
* [mastui](https://github.com/kimusan/mastui) ⭐ 96 | 🐛 3 | 🌐 Python | 📅 2026-10-07 Mastodon TUI
* [nostui](https://github.com/akiomik/nostui) ⭐ 72 | 🐛 33 | 🌐 Rust | 📅 2026-11-14 Nostr client
* [tuix](https://github.com/pythops/tuix) ⭐ 34 | 🐛 1 | 🌐 Rust | 📅 2024-07-02 TUI for managing screens
* [rtg](https://github.com/bercly0b/rtg) ⭐ 22 | 🐛 0 | 🌐 Rust | 📅 2026-11-25 Fast, vim-like Telegram TUI client written in Rust, built on TDLib
* [dexchat](https://github.com/dexchat/dex) ⭐ 18 | 🐛 7 | 🌐 Go | 📅 2026-11-17 A modern TUI IRC client for your terminal.
* [SuperChat](https://github.com/serialexp/superchat) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2026-09-29 Terminal-based threaded chat application with a custom binary protocol.
* [nostratui](https://github.com/adamm-xyz/nostratui) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2025-06-10 A terminal user interface (TUI) for browsing Nostr posts, written in Rust.
* [local-chat](https://github.com/DongGunYoon/local-chat) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-10 Terminal chat for everyone on the same WiFi, nothing to host, no accounts, no messages written to disk
* [aerc](https://aerc-mail.org/) Email client
* [alpine](https://alpineapp.email/) Email client
* [iamb](https://iamb.chat) A Matrix client for Vim addicts written in Rust
* [irssi](https://irssi.org/) An IRC terminal client
* [mcabber](https://mcabber.com/) XMPP (Jabber) client
* [meli](https://meli.delivery/) Email client
* [Mutt](https://gitlab.com/muttmua/mutt) Email client
* [Profanity](https://profanity-im.github.io) XMPP (Jabber) client
* [Weechat](https://weechat.org/) Extensible chat client

***

</details>

<details open><summary><h2>Miscellaneous</h2></summary>

* [fzf](https://github.com/junegunn/fzf) ⭐ 84,512 | 🐛 341 | 🌐 Go | 📅 2026-11-24 A general-purpose command-line fuzzy finder
* [Mole](https://github.com/tw93/Mole) ⭐ 76,339 | 🐛 8 | 🌐 Shell | 📅 2026-11-26 Clean caches and app leftovers, uninstall apps, and browse disk usage and live system stats in interactive TUIs on macOS and Windows
* [wttr.in](https://github.com/chubin/wttr.in) ⭐ 30,825 | 🐛 333 | 🌐 Go | 📅 2026-11-24 The right way to check the weather
* [oha](https://github.com/hatoo/oha) ⭐ 10,749 | 🐛 60 | 🌐 Rust | 📅 2026-11-18 HTTP load generator
* [termshark](https://github.com/gcla/termshark) ⭐ 10,077 | 🐛 52 | 🌐 Go | 📅 2024-04-30 Terminal UI for tshark
* [mapscii](https://github.com/rastapasta/mapscii) ⭐ 9,293 | 🐛 57 | 🌐 JavaScript | 📅 2024-11-03 Braille & ASCII world map renderer for your console
* [wego](https://github.com/schachmat/wego) ⭐ 8,573 | 🐛 18 | 🌐 Go | 📅 2026-11-01 Weather app
* [term.everything](https://github.com/mmulet/term.everything) ⭐ 8,127 | 🐛 17 | 🌐 Go | 📅 2026-03-18 Run any GUI app in the terminal
* [cava](https://github.com/karlstav/cava) ⭐ 6,560 | 🐛 13 | 🌐 C | 📅 2026-11-11 Cross-platform Audio Visualizer
* [dua-cli](https://github.com/byron/dua-cli) ⭐ 6,498 | 🐛 2 | 🌐 Rust | 📅 2026-11-24 View disk space usage and delete unwanted data, fast.
* [gdu](https://github.com/dundee/gdu) ⭐ 6,228 | 🐛 55 | 🌐 Go | 📅 2026-11-25 Fast disk usage analyzer with console interface written in Go
* [xplr](https://github.com/sayanarijit/xplr) ⭐ 4,854 | 🐛 4 | 🌐 Rust | 📅 2026-11-17 A hackable, minimal, fast TUI file explorer, stealing ideas from nnn and fzf.
* [x-cmd](https://github.com/x-cmd/x-cmd) ⭐ 4,766 | 🐛 123 | 🌐 Awk | 📅 2026-11-24 A vast and interesting collection of tools that can then bootstrap lots of other programs / functions in a consistent and structured way.
* [csvlens](https://github.com/YS-L/csvlens) ⭐ 4,052 | 🐛 61 | 🌐 Rust | 📅 2026-07-04 TUI CSV file viewer. It is like less but made for CSV.
* [cfdisk](https://github.com/util-linux/util-linux) ⭐ 3,261 | 🐛 461 | 🌐 C | 📅 2026-11-24 TUI partition editor included in util-linux
* [diskonaut](https://github.com/imsnif/diskonaut) ⭐ 3,168 | 🐛 48 | 🌐 Rust | 📅 2024-03-07 Terminal disk space navigator
* [bluetui](https://github.com/pythops/bluetui) ⭐ 3,084 | 🐛 11 | 🌐 Rust | 📅 2026-11-23 A TUI for managing bluetooth devices.
* [impala](https://github.com/pythops/impala) ⭐ 2,898 | 🐛 3 | 🌐 Rust | 📅 2026-11-26 TUI for managing wifi
* [tweakcc](https://github.com/Piebald-AI/tweakcc) ⭐ 2,622 | 🐛 32 | 🌐 TypeScript | 📅 2026-11-25 TUI to customize your Claude Code themes, thinking verbs, and more.
* [Caligula](https://github.com/ifd3f/caligula) ⭐ 2,469 | 🐛 59 | 🌐 Rust | 📅 2026-11-22 A user-friendly, lightweight TUI for imaging disks.
* [smassh](https://github.com/kraanzu/smassh) ⭐ 2,057 | 🐛 12 | 🌐 Python | 📅 2026-10-22 A TUI based typing test application inspired by MonkeyType.
* [recoverpy](https://github.com/PabloLec/recoverpy) ⭐ 1,799 | 🐛 3 | 🌐 Python | 📅 2026-08-03 A TUI to recover overwritten or deleted data.
* [gpg-tui](https://github.com/orhun/gpg-tui) ⭐ 1,779 | 🐛 16 | 🌐 Rust | 📅 2026-11-26 A terminal user interface for GnuPG
* [ttyper](https://github.com/max-niederman/ttyper) ⭐ 1,619 | 🐛 36 | 🌐 Rust | 📅 2026-10-13 Terminal-based typing test
* [Systemd-manager-tui](https://github.com/matheus-git/systemd-manager-tui) ⭐ 1,609 | 🐛 1 | 🌐 Rust | 📅 2026-10-18 A program for managing systemd services through a TUI.
* [bluetuith](https://github.com/bluetuith-org/bluetuith) ⭐ 1,432 | 🐛 17 | 🌐 Go | 📅 2026-07-01 A TUI-based bluetooth connection manager, which can interact with bluetooth adapters and devices.
* [arttime](https://github.com/poetaman/arttime) ⭐ 1,401 | 🐛 6 | 🌐 Shell | 📅 2026-08-18 An app that brings beauty of text-art together with functionality of clock, timer, and pattern-based time manager.
* [wavemon](https://github.com/uoaerg/wavemon) ⭐ 1,273 | 🐛 6 | 🌐 C | 📅 2026-06-29 A wireless device monitoring application
* [LearnByExample](https://github.com/learnbyexample/TUI-apps) ⭐ 1,024 | 🐛 0 | 🌐 Python | 📅 2026-02-02 A TUI with tutorials and +300 exercises on python, grep, awk, sed & general terminal usage.
* [godap](https://github.com/Macmod/godap) ⭐ 999 | 🐛 4 | 🌐 Go | 📅 2026-11-22 A complete TUI for LDAP written in Golang
* [ec2-instance-selector](https://github.com/aws/amazon-ec2-instance-selector) ⭐ 934 | 🐛 20 | 🌐 Go | 📅 2025-12-22 A CLI tool and go library which recommends instance types based on resource criteria like vcpus and memory
* [golazo](https://github.com/0xjuanma/golazo) ⭐ 896 | 🐛 6 | 🌐 Go | 📅 2026-09-07 Get soccer minute-by-minute updates and finished match stats in your terminal
* [vortix](https://github.com/Harry-kp/vortix) ⭐ 806 | 🐛 13 | 🌐 Rust | 📅 2026-11-23 Terminal UI for WireGuard and OpenVPN with real-time telemetry, leak detection, and kill switch.
* [mqttui](https://github.com/EdJoPaTo/mqttui) ⭐ 749 | 🐛 13 | 🌐 Rust | 📅 2026-11-17 MQTT Client written in rust
* [pug](https://github.com/leg100/pug) ⭐ 704 | 🐛 20 | 🌐 Go | 📅 2026-01-02 terraform and tofu module and infrastructure management.
* [linecast](https://github.com/ashuttl/linecast) ⭐ 702 | 🐛 0 | 🌐 Python | 📅 2026-11-25 Interactive weather, radar, tides, sun and moon views, a planetarium with stars and constellations, and maps with a rotatable globe for the terminal.
* [nemu](https://github.com/nemuTUI/nemu) ⭐ 621 | 🐛 15 | 🌐 C | 📅 2026-06-11 A TUI for QEMU
* [flawz](https://github.com/orhun/flawz) ⭐ 619 | 🐛 15 | 🌐 Rust | 📅 2026-10-23 A Terminal UI for browsing security vulnerabilities (CVEs)
* [thokr](https://github.com/jrnxf/thokr) ⭐ 604 | 🐛 8 | 🌐 Rust | 📅 2026-11-20 a sleek typing tui written in rust
* [tcpterm](https://github.com/sachaos/tcpterm) ⭐ 491 | 🐛 0 | 🌐 Go | 📅 2024-01-10 tcpterm is a packet visualizer in TUI.
* [mac-cleanup-go](https://github.com/2ykwang/mac-cleanup-go) ⭐ 469 | 🐛 1 | 🌐 Go | 📅 2026-11-26 macOS disk cleanup TUI: scan cache/dev artifacts, preview, exclude, and move items to Trash.
* [emu2](https://github.com/dmsc/emu2) ⭐ 467 | 🐛 27 | 🌐 C | 📅 2026-07-04 A simple DOS emulator for the Linux text console, supporting basic DOS system calls and console I/O.
* [asciiMol](https://github.com/dewberryants/asciiMol) ⭐ 420 | 🐛 0 | 🌐 Python | 📅 2026-06-24 Curses based ASCII molecule viewer for linux terminals.
* [Captain's log](https://github.com/NikolaDucak/caps-log) ⭐ 411 | 🐛 16 | 🌐 C++ | 📅 2026-10-19 A small TUI journaling tool
* [wifitui](https://github.com/shazow/wifitui) ⭐ 355 | 🐛 34 | 🌐 Go | 📅 2026-11-18 Fast featureful friendly wifi terminal UI, supports NetworkManager and iwd over dbus.
* [sbb-tui](https://github.com/necrom4/sbb-tui) ⭐ 330 | 🐛 12 | 🌐 Go | 📅 2026-08-19 TUI client for Switzerland's public transport timetables, inspidered by the SBB/CFF/FFS app.
* [packemon](https://github.com/ddddddO/packemon) ⭐ 313 | 🐛 41 | 🌐 Go | 📅 2026-11-01 Packet generator and monitor.
* [NanoCore](https://github.com/AfaanBilal/NanoCore) ⭐ 293 | 🐛 3 | 🌐 Rust | 📅 2026-09-07 An 8-bit CPU emulator TUI written in Rust with an assembler and a custom ISA.
* [try-rs](https://github.com/tassiovirginio/try-rs/) ⭐ 292 | 🐛 0 | 🌐 Rust | 📅 2026-11-26 A lightning-fast TUI to manage temporary projects. Create, explore, and clone repositories instantly without cluttering your system.
* [moribito](https://github.com/ericschmar/moribito) ⭐ 283 | 🐛 9 | 🌐 Kotlin | 📅 2026-01-24 Browse LDAP directory trees, viewing records, and executing custom queries.
* [typtea](https://github.com/ashish0kumar/typtea) ⭐ 243 | 🐛 2 | 🌐 Go | 📅 2026-09-23 Minimal terminal-based typing speed tester with support for dozens of programming languages.
* [neoss](https://github.com/PabloLec/neoss) ⭐ 236 | 🐛 13 | 🌐 TypeScript | 📅 2026-10-05 Socket statistics visualization and explanation tool for Unix systems.
* [WG Commander](https://github.com/andrianbdn/wg-cmd) ⭐ 227 | 🐛 2 | 🌐 Go | 📅 2026-07-07 A TUI for a simple WireGuard VPN setup: peer management, QR codes, setup wizard.
* [tlock](https://github.com/eklairs/tlock) ⭐ 198 | 🐛 7 | 🌐 Go | 📅 2024-09-01 Two-Factor Authentication Tokens Manager in Terminal
* [CrunchyCleaner](https://github.com/knuspii/crunchycleaner) ⭐ 195 | 🐛 1 | 🌐 Go | 📅 2026-11-24 A lightweight, software cache cleanup tool for Windows & Linux.
* [wlctl](https://github.com/aashish-thapa/wlctl) ⭐ 194 | 🐛 11 | 🌐 Rust | 📅 2026-11-25 TUI for managing wifi, ethernet and vpn on Linux with Network Manager
* [tray-tui](https://github.com/Levizor/tray-tui) ⭐ 179 | 🐛 2 | 🌐 Rust | 📅 2026-03-15 System tray in your terminal
* [WifUI](https://github.com/sohamw03/wifui) ⭐ 163 | 🐛 0 | 🌐 Rust | 📅 2026-10-31 TUI for managing Wi-Fi connections on Windows natively (Rust)
* [redu](https://github.com/drdo/redu) ⭐ 162 | 🐛 12 | 🌐 Rust | 📅 2026-10-19 ncdu for your restic repository that manages exclusion lists to prune files from existing repos and skip new ones
* [terminalperiodictable](https://github.com/velorek1/terminalperiodictable) ⭐ 147 | 🐛 1 | 🌐 C | 📅 2025-08-01 A beautiful TUI periodic table for Unix systems coded in C.
* [tttui](https://github.com/reidoboss/tttui) ⭐ 127 | 🐛 1 | 🌐 Rust | 📅 2026-10-14 A Monkeytype-inspired typing test that runs entirely in your terminal
* [pass-cli](https://github.com/reyamira/pass-cli) ⭐ 126 | 🐛 15 | 🌐 Go | 📅 2026-07-15 A TUI and CLI password manager with rclone cloud syncing support
* [keydex](https://github.com/shikaan/keydex) ⭐ 100 | 🐛 3 | 🌐 Go | 📅 2026-10-03 TUI password manager for KeePass databases.
* [oeis-tui](https://github.com/hako/oeis-tui) ⭐ 93 | 🐛 0 | 🌐 Rust | 📅 2026-02-03  A TUI and CLI for browsing the On-Line Encyclopedia of Integer Sequences (OEIS) in the terminal.
* [HumBLE Explorer](https://github.com/koenvervloesem/humble-explorer) ⭐ 91 | 🐛 0 | 🌐 Python | 📅 2023-11-25 A cross-platform, command-line and human-friendly Bluetooth Low Energy scanner
* [diary](https://github.com/actuday6418/Diary) ⭐ 75 | 🐛 1 | 🌐 Rust | 📅 2021-06-16 A diary app written in Rust that encrypts both text and file data, and can decrypt and build a rich HTML representation of your diary when required.
* [tui-shop](https://github.com/rainbow-sh/tui-shop) ⭐ 75 | 🐛 1 | 🌐 Python | 📅 2022-07-10 Something between a CLI and a GUI way of downloading TUIs/CLIs
* [ytunnel](https://github.com/yetidevworks/ytunnel) ⭐ 75 | 🐛 2 | 🌐 Rust | 📅 2026-11-13 A TUI for creating and managing Cloudflare Tunnels with custom domains
* [fnf](https://github.com/leo-arch/fnf) ⭐ 56 | 🐛 4 | 🌐 C | 📅 2026-04-04 An interactive fuzzy finder for the terminal
* [Clanki](https://github.com/alvenw/clanki) ⭐ 46 | 🐛 5 | 🌐 Python | 📅 2026-04-06 A TUI-based Anki review client, even supporting progress sync.
* [physics-TUI](https://github.com/ClaudioRMalvino/Physics-TUI) ⭐ 33 | 🐛 0 | 🌐 Python | 📅 2026-07-09 Physics TUI application for undergraduate study
* [rocket.term](https://github.com/gerstner-hub/rocket.term) ⭐ 32 | 🐛 0 | 🌐 Python | 📅 2023-12-20 Text based chat client for the Rocket.chat messaging solution.
* [distrobox-tui](https://github.com/phanirithvij/distrobox-tui) ⭐ 31 | 🐛 1 | 🌐 Go | 📅 2025-03-11 TUI for managing distrobox containers
* [tab-pal](https://github.com/ben-nour/tab-pal) ⭐ 29 | 🐛 0 | 🌐 Python | 📅 2024-10-01 Add and edit custom colour palettes in Tableau from the command-line.
* [DigiSurf](https://github.com/SeanMcLoughlin/digisurf) ⭐ 27 | 🐛 0 | 🌐 Rust | 📅 2025-03-27 A TUI signal waveform viewer
* [PesterExplorer](https://github.com/HeyItsGilbert/PesterExplorer) ⭐ 26 | 🐛 6 | 🌐 PowerShell | 📅 2026-05-30 A TUI to explore Pester results.
* [lazynginx](https://github.com/giacomomasseron/lazynginx) ⭐ 22 | 🐛 0 | 🌐 Go | 📅 2026-09-21 Simple TUI for nginx management.
* [dupster](https://github.com/karimz1/dupster) ⭐ 17 | 🐛 2 | 🌐 Python | 📅 2026-09-23 The lazy way to find duplicates in your Terminal. Easily find duplicates, preview them and delete them.
* [wb](https://github.com/mmertgunduz/wb) ⭐ 15 | 🐛 0 | 🌐 C | 📅 2023-09-01 A TUI vocabulary notebook app for Linux based devices.
* [passtui](https://github.com/fjmoralesp/passtui) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2026-07-14 The terminal user interface for **pass**, the standard unix password manager.
* [steam\_friends\_list\_tui](https://github.com/AdamWHY2K/steam_friends_list_tui) ⭐ 5 | 🐛 12 | 🌐 C# | 📅 2026-01-19 The steam friends list in the commandline
* [codename-generator](https://github.com/michaelblaess/codename-generator) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-10-19 Generates project codenames from themes such as Greek gods, gemstones or constellations, with modifiers and phonetic mutations
* [wwlog](https://github.com/ali5ter/wwlog) ⭐ 0 | 🐛 35 | 🌐 Go | 📅 2026-10-23 Browse, compare, and export your Weight Watchers food log, with a local archive that outlives the subscription
* [cgdisk](https://www.rodsbooks.com/gdisk/cgdisk-walkthrough.html) TUI partition editor for manipulating GUID partition tables, and modeled after cfdisk
* [isw](https://gitlab.com/thom-cameron/isw) A simple terminal stopwatch application for pomodoro etc.
* [jrnl](https://jrnl.sh/) Collect your thoughts and notes without leaving the command line. human-friendly. future-proof. secure.
* [lnav](https://lnav.org/) An advanced log file viewer for the small-scale
* [moc](https://moc.daper.net/download) console audio player
* [nbtui](https://codeberg.org/ItsZariep/nbtui) Ncurses Bluetooth TUI Manager for Linux
* [ncdu](https://dev.yorhel.nl/ncdu) disk usage analyzer with an ncurses interface
* [nmtui](https://developer.gnome.org/NetworkManager/stable/nmtui.html) ncurses network manager

***

</details>

<details open><summary><h2>Multimedia</h2></summary>

* [vlc](https://github.com/videolan/vlc) ⭐ 20,603 | 🐛 2 | 🌐 C | 📅 2026-11-26 VLC includes an ncurses interface, `vlc --intf ncurses`
* [mps-youtube](https://github.com/mps-youtube/yewtube) ⭐ 8,815 | 🐛 228 | 🌐 Python | 📅 2026-03-04 Terminal based YouTube player and downloader
* [spotify-player](https://github.com/aome510/spotify-player) ⭐ 7,332 | 🐛 175 | 🌐 Rust | 📅 2026-11-17 A Spotify player in the terminal with full feature parity
* [ncspot](https://github.com/hrkfdn/ncspot) ⭐ 6,824 | 🐛 204 | 🌐 Rust | 📅 2026-11-24 Cross-platform ncurses Spotify client written in Rust
* [ytfzf](https://github.com/pystardust/ytfzf) ⭐ 4,166 | 🐛 66 | 🌐 Shell | 📅 2024-09-27 A POSIX script that helps you find Youtube videos (without API) or Peertube videos and opens/downloads them using mpv/youtube-dl
* [kew](https://github.com/ravachol/kew) ⭐ 3,226 | 🐛 5 | 🌐 C | 📅 2026-11-26 A terminal music player for Linux
* [timg](https://github.com/hzeller/timg) ⭐ 2,808 | 🐛 40 | 🌐 C++ | 📅 2026-08-05 A terminal image viewer
* [termusic](https://github.com/tramhao/termusic) ⭐ 2,254 | 🐛 49 | 🌐 Rust | 📅 2026-11-27 Music Player TUI written in Rust
* [tdf](https://github.com/itsjunetime/tdf) ⭐ 2,032 | 🐛 43 | 🌐 Rust | 📅 2026-08-16 A tui-based PDF viewer
* [spotatui](https://github.com/LargeModGames/spotatui) ⭐ 1,870 | 🐛 83 | 🌐 Rust | 📅 2026-11-27 Spotify client with native streaming, synced lyrics, and real-time audio visualization
* [tizonia-openmax-il](https://github.com/tizonia/tizonia-openmax-il) ⭐ 1,743 | 🐛 167 | 🌐 C | 📅 2026-09-29 Command-line cloud music player for Linux with support for Spotify, Google Play Music, YouTube, SoundCloud, Dirble, Plex servers and Chromecast devices
* [bookokrat](https://github.com/bugzmanov/bookokrat) ⭐ 1,310 | 🐛 56 | 🌐 Rust | 📅 2026-11-11 Full-featured EPUB books reader with Vim keybindings.
* [textual-paint](https://github.com/1j01/textual-paint) ⭐ 1,132 | 🐛 10 | 🌐 Python | 📅 2026-02-21 MS Paint in your terminal
* [wiremix](https://github.com/tsowell/wiremix) ⭐ 1,109 | 🐛 33 | 🌐 Rust | 📅 2026-11-20 TUI audio mixer for PipeWire similar to pavucontrol to adjust volumes, change input/output devices and their profiles
* [pyradio](https://github.com/coderholic/pyradio) ⭐ 1,102 | 🐛 11 | 🌐 Python | 📅 2026-11-03 TUI web radio player with thousands of stations from around the world
* [manga-tui](https://github.com/josueBarretogit/manga-tui) ⭐ 960 | 🐛 24 | 🌐 Rust | 📅 2026-11-15 Terminal-based manga reader and downloader with image rendering support
* [upiano](https://github.com/eliasdorneles/upiano) ⭐ 797 | 🐛 5 | 🌐 Python | 📅 2025-07-09 A Piano in your terminal
* [managarr](https://github.com/Dark-Alex-17/managarr) ⭐ 794 | 🐛 2 | 🌐 Rust | 📅 2026-10-14 A TUI and CLI for managing your \*arr servers
* [ytui-music](https://github.com/sudipghimire533/ytui-music) ⭐ 778 | 🐛 38 | 🌐 Rust | 📅 2025-03-03 Listen to music from youtube. Configurable, minimal, lightweight, private & beautiful music client.
* [xytz](https://github.com/xdagiz/xytz) ⭐ 657 | 🐛 9 | 🌐 Go | 📅 2026-10-16 Beautiful TUI for downloading YouTube videos/playlists/channels.
* [jellyfin-tui](https://github.com/dhonus/jellyfin-tui) ⭐ 636 | 🐛 13 | 🌐 Rust | 📅 2026-11-26 Jellyfin client
* [fancy-cat](https://github.com/freref/fancy-cat) ⭐ 591 | 🐛 22 | 🌐 Zig | 📅 2026-08-03 A Lightweight terminal-based PDF reader with Vim keybindings
* [spotui](https://github.com/ceuk/spotui) ⭐ 579 | 🐛 9 | 🌐 Python | 📅 2023-07-25 Spotify client written in Python
* [cmdpxl](https://github.com/knosmos/cmdpxl) ⭐ 549 | 🐛 2 | 🌐 Python | 📅 2021-08-27 Totally practical command-line image editor
* [draw](https://github.com/maaslalani/draw) ⭐ 548 | 🐛 6 | 🌐 Go | 📅 2023-12-04 A simple drawing tool in the terminal.
* [pipe-viewer](https://github.com/trizen/pipe-viewer) ⭐ 518 | 🐛 44 | 🌐 Perl | 📅 2026-11-12 A lightweight YouTube client for Linux, without requiring an API key.
* [GopherTube](https://github.com/krishnassh/gophertube) ⭐ 434 | 🐛 3 | 🌐 Go | 📅 2026-10-30 A terminal-based YouTube client that scrapes YouTube search results and uses mpv for video playback
* [NoctaVox](https://github.com/Jaxx497/NoctaVox) ⭐ 384 | 🐛 3 | 🌐 Rust | 📅 2026-11-22 Local TUI music player
* [asak](https://github.com/chaosprint/asak) ⭐ 374 | 🐛 11 | 🌐 Rust | 📅 2026-04-11 A cross-platform audio recording/playback TUI
* [tortuise](https://github.com/buildoak/tortuise) ⭐ 259 | 🐛 6 | 🌐 Rust | 📅 2026-06-15 Gaussian Splatting 3D viewer in your terminal. 6 render modes, CPU-only via crossterm + rayon
* [invidtui](https://github.com/darkhz/invidtui) ⭐ 205 | 🐛 6 | 🌐 Go | 📅 2024-07-14 A TUI Invidious client for Windows, Linux and MacOS, that fetches and plays audio/video from an invidious instance. Supports viewing and playing from playlists and channels as well.
* [waves](https://github.com/llehouerou/waves) ⭐ 182 | 🐛 2 | 🌐 Go | 📅 2026-11-23 Terminal music player with vim-style navigation and radio mode that plays similar artists from your library
* [RadioGoGo](https://github.com/matteo-pacini/RadioGoGo) ⭐ 169 | 🐛 3 | 🌐 Go | 📅 2026-09-25 Go-powered CLI to surf global radio waves via a sleek TUI.
* [MAL-Cli](https://github.com/L4z3x/mal-cli) ⭐ 162 | 🐛 0 | 🌐 Rust | 📅 2025-07-17 A terminal interface for the official myanimelist api written in rust.
* [mpvc](https://github.com/gmt4/mpvc) ⭐ 161 | 🐛 0 | 🌐 Shell | 📅 2026-11-26 A mpc-like control interface for mpv
* [line](https://github.com/pd3v/line) ⭐ 153 | 🐛 0 | 🌐 C++ | 📅 2025-08-11 Tiny command-line midi sequencer and language for live coding
* [Trophy](https://github.com/taigrr/trophy) ⭐ 134 | 🐛 1 | 🌐 Go | 📅 2026-11-16 A TUI 3D Model Viewer for OBJ and GLB files
* [Gorae](https://github.com/Han8931/gorae) ⭐ 102 | 🐛 1 | 🌐 Go | 📅 2026-11-12 TUI librarian for PDFs and EPUBs with Vim-style navigation.
* [rusty-pipes](https://github.com/dividebysandwich/rusty-pipes) ⭐ 97 | 🐛 7 | 🌐 Rust | 📅 2026-09-15 A sample-based, MIDI-controlled virtual pipe organ instrument compatible with GrandOrgue and Hauptwerk sample sets.
* [Tanko](https://github.com/Alexandro521/Tanko) ⭐ 97 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-26 A tool for reading and downloading manga from the terminal, with image rendering support
* [Relax-player](https://github.com/ebithril/relax-player) ⭐ 86 | 🐛 1 | 🌐 Rust | 📅 2026-10-20 A lightweight, distraction-free alternative to web-based ambient players.
* [valveFM](https://github.com/zorig/valvefm) ⭐ 55 | 🐛 1 | 🌐 Go | 📅 2026-08-20 Vintage FM radio TUI for streaming stations from radio-browser.info
* [image-sorter](https://github.com/jgalat/image-sorter) ⭐ 49 | 🐛 0 | 🌐 Rust | 📅 2024-12-27 Terminal user interface for sorting images using key bindings written in Rust
* [terminal-yt](https://github.com/jooooscha/terminal-yt) ⭐ 45 | 🐛 3 | 🌐 Rust | 📅 2026-01-06 A small newsboat-inspired terminal youtube manager
* [gadacz](https://github.com/rareitems/gadacz) ⭐ 40 | 🐛 5 | 🌐 Rust | 📅 2024-06-27 Audiobook player
* [rustune](https://github.com/dzulfikar08/rustune) ⭐ 40 | 🐛 0 | 🌐 Rust | 📅 2026-11-07 Terminal music player with YouTube search, local playback, synced lyrics, Internet radio and Winamp skins
* [ytdl-tui](https://github.com/darky/ytdl-tui) ⭐ 40 | 🐛 0 | 🌐 TypeScript | 📅 2024-12-21 TUI for downloading Youtube videos
* [ani-l](https://github.com/komposer-aml/ani-l) ⭐ 38 | 🐛 0 | 🌐 Rust | 📅 2026-01-08 Rust-based anime browsing and streaming all without leaving the terminal
* [ctune](https://github.com/An7ar35/ctune) ⭐ 32 | 🐛 4 | 🌐 C | 📅 2026-04-18 ncurses based internet radio player for Linux.
* [mpv-music](https://github.com/FurqanHun/mpv-music) ⭐ 32 | 🐛 0 | 🌐 Rust | 📅 2026-11-26 Cross-platform CLI/TUI music player and library browser written in Rust that lets you filter and select what you want to play and gets out of your way, with no background daemons.
* [roku-cli](https://github.com/winsbe01/roku-tui) ⭐ 20 | 🐛 1 | 🌐 Python | 📅 2023-03-01 A command line TUI remote for Roku
* [goweeb](https://github.com/EliasLd/goweeb) ⭐ 17 | 🐛 0 | 🌐 Go | 📅 2026-11-26 Download manga as pdf or cbz from multiple providers in multiple languages with a fast TUI and container support.
* [MusicTUI](https://github.com/anthonymaley/MusicTUI) ⭐ 17 | 🐛 0 | 🌐 Swift | 📅 2026-11-26 Apple Music TUI and CLI for macOS, written in Swift, with multi-room AirPlay routing, library browsing with cover art, playlists, radio and a venue equalizer
* [marstui-audio](https://github.com/schooldanlp6/marstui-rustio) ⭐ 14 | 🐛 3 | 🌐 Rust | 📅 2026-08-31 A nice audio management Interface, similar to pavucontrol with the benefit of customizing everything
* [mangap](https://github.com/hongnoul/mangap) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2026-11-23 Terminal manga reader that renders pages as real images over the kitty graphics protocol, with live search and Anilist sync.
* [sgram-tui](https://github.com/arian-shamaei/sgram-tui) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2026-08-16 Calibrated spectrogram analyzer for live mic or audio files, with labeled PNG figure export and a headless render mode
* [retro-amp](https://github.com/michaelblaess/retro-amp) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-10-17 Retro-styled music player with real-time spectrum visualizer, synced lyrics, playlists and 38 themes
* [favicon-editor](https://github.com/xyproto/favicon-editor) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2026-08-14 Spartan grayscale favicon editor
* [chafa](https://hpjansson.org/chafa/) A powerful utility that converts image data, including animated GIFs, into graphics formats or ANSI/Unicode character art suitable for display in a terminal.
* [cmus](https://cmus.github.io/) A small, fast and powerful console music player for Unix-like operating systems.
* [nap](https://nap.sourceforge.net/) Linux napster client
* [ostui](https://git.sr.ht/~ser/ostui) CLI client for Subsonic-API servers like gonic and Navidrome
* [rmpc](https://rmpc.mierak.dev/) A configurable MPD client inspired by ncmpcpp and ranger with album art support via various graphics protocols.

***

</details>

<details open><summary><h2>Productivity</h2></summary>

* [tmux](https://github.com/tmux/tmux) ⭐ 50,606 | 🐛 34 | 🌐 C | 📅 2026-11-27 Terminal multiplexer
* [zellij](https://github.com/zellij-org/zellij) ⭐ 36,283 | 🐛 1,999 | 🌐 Rust | 📅 2026-11-24 A terminal workspace with batteries included
* [Glow](https://github.com/charmbracelet/glow) ⭐ 28,212 | 🐛 273 | 🌐 Go | 📅 2026-11-25 A markdown reader, designed from the ground up to showcase the elegance and capabilities of TUI.
* [slides](https://github.com/maaslalani/slides) ⭐ 11,716 | 🐛 79 | 🌐 Go | 📅 2026-07-08 A terminal based presentation tool, supporting markdown syntax.
* [Visidata](https://github.com/saulpw/visidata) ⭐ 9,485 | 🐛 9 | 🌐 Python | 📅 2026-11-11 A terminal spreadsheet multitool for discovering and arranging data
* [presenterm](https://github.com/mfontanini/presenterm) ⭐ 9,005 | 🐛 57 | 🌐 Rust | 📅 2026-11-24 A markdown terminal slideshow tool
* [mcfly](https://github.com/cantino/mcfly) ⭐ 7,831 | 🐛 141 | 🌐 Rust | 📅 2026-11-24 Intelligent context-aware search engine for your shell history
* [TUIOS](https://github.com/Gaurav-Gosain/tuios) ⭐ 6,831 | 🐛 115 | 🌐 Go | 📅 2026-11-27 A TUI window manager for managing multiple terminal sessions
* [television](https://github.com/alexpasmantier/television) ⭐ 6,447 | 🐛 90 | 🌐 Rust | 📅 2026-11-15 A fast and versatile fuzzy finder TUI
* [sc-im](https://github.com/andmarti1424/sc-im) ⭐ 5,721 | 🐛 115 | 🌐 C | 📅 2026-10-28 An ncurses spreadsheet program for terminal. Reignited version of sc
* [hledger-ui](https://github.com/hledgerorg/hledger) ⭐ 4,837 | 🐛 314 | 🌐 Haskell | 📅 2026-11-26 A fast TUI for browsing double entry bookkeeping data
* [LazySSH](https://github.com/adembc/lazyssh) ⭐ 4,023 | 🐛 71 | 🌐 Go | 📅 2025-10-09 TUI SSH manager to browse, connect, and manage servers from ssh config files.
* [doxx](https://github.com/bgreenwell/doxx) ⭐ 3,794 | 🐛 17 | 🌐 Rust | 📅 2026-08-10 A TUI document viewer for Microsoft Word files
* [Tabiew](https://github.com/shshemi/tabiew) ⭐ 3,197 | 🐛 30 | 🌐 Rust | 📅 2026-11-24 A lightweight app to view and query tabular data files, such as CSV, TSV, and parquet.
* [termscp](https://github.com/veeso/termscp) ⭐ 3,170 | 🐛 10 | 🌐 Rust | 📅 2026-11-02 A TUI file transfer and explorer, with support for SCP/SFTP/FTP/S3.
* [khal](https://github.com/pimutils/khal) ⭐ 3,097 | 🐛 265 | 🌐 Python | 📅 2026-11-26 A standards based CLI calendar program, able to synchronize with CalDAV servers
* [Bagels](https://github.com/EnhancedJax/Bagels) ⭐ 2,946 | 🐛 19 | 🌐 Python | 📅 2025-07-06 TUI expense tracker
* [patat](https://github.com/jaspervdj/patat) ⭐ 2,749 | 🐛 23 | 🌐 Haskell | 📅 2026-06-25 Terminal-based presentations using Pandoc
* [calcure](https://github.com/anufrievroman/calcure) ⭐ 2,407 | 🐛 6 | 🌐 Python | 📅 2026-10-25 Modern TUI calendar and task manager with minimal and customizable UI.
* [h-m-m](https://github.com/nadrad/h-m-m) ⭐ 2,303 | 🐛 4 | 🌐 PHP | 📅 2026-07-06 Hackers Mind Map
* [taskwarrior-tui](https://github.com/kdheepak/taskwarrior-tui) ⭐ 2,161 | 🐛 123 | 🌐 Rust | 📅 2026-11-22 A Terminal User Interface for Taskwarrior
* [jiratui](https://github.com/whyisdifficult/jiratui) ⭐ 1,730 | 🐛 11 | 🌐 Python | 📅 2026-11-21 A TUI for interacting with Atlassian Jira directly from your shell
* [xleak](https://github.com/bgreenwell/xleak) ⭐ 1,524 | 🐛 15 | 🌐 Rust | 📅 2026-11-23 A fast terminal Excel viewer with an interactive TUI
* [sshm](https://github.com/gu1llaum-3/sshm) ⭐ 1,432 | 🐛 24 | 🌐 Go | 📅 2026-10-04 SSH made easy and fast: browse, connect, and control from your terminal with a modern TUI
* [ttyplot](https://github.com/tenox7/ttyplot) ⭐ 1,391 | 🐛 11 | 🌐 C | 📅 2026-10-13 A realtime plotting utility for terminals with data input from stdin/pipe.
* [intelli-shell](https://github.com/lasantosr/intelli-shell) ⭐ 1,310 | 🐛 5 | 🌐 Rust | 📅 2026-11-10 Manage command templates/snippets with dynamic completions and AI integration
* [Desktop-TUI](https://github.com/Julien-cpsn/desktop-tui) ⭐ 1,234 | 🐛 5 | 🌐 Rust | 📅 2026-03-01 A desktop environment without graphics
* [longbridge-terminal](https://github.com/longbridge/longbridge-terminal) ⭐ 1,064 | 🐛 15 | 🌐 Rust | 📅 2026-11-27 AI-native TUI for Longbridge Securities: real-time quotes, portfolio management, and trading for HK/US/A-share/SG markets.
* [clipse](https://github.com/savedra1/clipse) ⭐ 1,062 | 🐛 39 | 🌐 Go | 📅 2026-11-23 TUI-based clipboard manager application
* [dvtm](https://github.com/martanne/dvtm) ⭐ 971 | 🐛 77 | 🌐 C | 📅 2024-05-18 A terminal multiplexer with dwm like window management
* [topydo](https://github.com/topydo/topydo) ⭐ 947 | 🐛 77 | 🌐 Python | 📅 2026-10-25 A powerful todo list application using the todo.txt format
* [todoman](https://github.com/pimutils/todoman) ⭐ 605 | 🐛 114 | 🌐 Python | 📅 2026-05-25 A simple, standards-based (ics, DAV), cli task-manager
* [zeit](https://github.com/mrusme/zeit) ⭐ 593 | 🐛 0 | 🌐 Go | 📅 2026-11-03 A command line tool for tracking time spent on activities.
* [pomo](https://github.com/Bahaaio/pomo) ⭐ 539 | 🐛 6 | 🌐 Go | 📅 2026-06-06 A minimal, customizable TUI Pomodoro timer with ASCII art, progress bar, desktop notifications, and productivity statistics.
* [Tock](https://github.com/kriuchkov/tock) ⭐ 511 | 🐛 3 | 🌐 Go | 📅 2026-11-25 The powerful time tracking tool for the command line with a beautiful interactive TUI.
* [kabmat](https://github.com/PlankCipher/kabmat) ⭐ 426 | 🐛 13 | 🌐 C++ | 📅 2023-01-26 TUI program for managing kanban boards with vim-like keybindings
* [budget-tracker-tui](https://github.com/Feromond/budget-tracker-tui) ⭐ 390 | 🐛 7 | 🌐 Rust | 📅 2026-11-16 A TUI budget tracker app designed to track income, expenses, investments, budget goals and visualize / gather insights.
* [hygg](https://github.com/kruseio/hygg) ⭐ 362 | 🐛 14 | 🌐 Rust | 📅 2026-10-30 📚 Simplifying the way you read. Minimalistic Vim-like TUI document reader.
* [kanban-python](https://github.com/Zaloog/kanban-python) ⭐ 353 | 🐛 0 | 🌐 Python | 📅 2026-10-28 Kanban Terminal App written in Python
* [gocheat](https://github.com/Achno/gocheat) ⭐ 347 | 🐛 8 | 🌐 Go | 📅 2025-10-26 A beautiful TUI cheatsheet for keybindings,hotkeys,gestures and aliases
* [lssh](https://github.com/blacknon/lssh) ⭐ 331 | 🐛 21 | 🌐 Go | 📅 2026-07-25 A terminal-native remote access suite for SSH workflows, including interactive host selection, parallel commands, mux workspaces, file transfer, sync, diff, forwarding, and multi-host monitoring.
* [taskline](https://github.com/perryrh0dan/taskline) ⭐ 331 | 🐛 23 | 🌐 TypeScript | 📅 2025-10-31 Tasks, boards & notes for the command-line habitat
* [numr](https://github.com/nasedkinpv/numr) ⭐ 320 | 🐛 6 | 🌐 Rust | 📅 2026-11-03 A natural language calculator with unit/currency conversions and vim-style keybindings
* [nless](https://github.com/mpryor/nothing-less) ⭐ 287 | 🐛 15 | 🌐 Python | 📅 2026-05-08 Terminal pager for exploring tabular data with vi keybindings and automatic delimiter inference
* [tvterm](https://github.com/magiblot/tvterm) ⭐ 283 | 🐛 8 | 🌐 C++ | 📅 2026-08-14 A terminal emulator that runs in your terminal
* [fjira](https://github.com/mk-5/fjira) ⭐ 276 | 🐛 22 | 🌐 Go | 📅 2026-07-07 TUI application for Atlassian Jira
* [SheetsUI](https://github.com/zaphar/sheetsui) ⭐ 251 | 🐛 4 | 🌐 Rust | 📅 2026-10-28 A console based spreadsheet application
* [mynav](https://github.com/GianlucaP106/mynav) ⭐ 248 | 🐛 12 | 🌐 Go | 📅 2025-09-28 Workspace and session management for terminal environments
* [tiki](https://github.com/boolean-maybe/tiki) ⭐ 225 | 🐛 10 | 🌐 Go | 📅 2026-08-12 Markdown-based git-versioned project and issue manager
* [Toney](https://github.com/SourcewareLab/Toney) ⭐ 212 | 🐛 5 | 🌐 Go | 📅 2026-05-27 a fast, lightweight, terminal-based note-taking app for the modern developer.
* [kanban](https://github.com/kanban-rs/kanban) ⭐ 196 | 🐛 10 | 🌐 Rust | 📅 2026-11-27 TUI kanban board for projects management with sprint tracking and task prioritization.
* [helm](https://github.com/0xjuanma/helm) ⭐ 155 | 🐛 0 | 🌐 Go | 📅 2026-09-07 A minimalistic & customizable pomodoro-like timer for your terminal
* [ssh-slides](https://github.com/ivantsepp/ssh-slides) ⭐ 138 | 🐛 0 | 🌐 Go | 📅 2026-10-16 Terminal-based presentations over SSH
* [Suvadu](https://github.com/AppachiTech/suvadu) ⭐ 133 | 🐛 3 | 🌐 Rust | 📅 2026-11-11 Shell history search for Zsh and Bash that also records the commands AI coding agents run
* [awsui](https://github.com/junminhong/awsui) ⭐ 125 | 🐛 0 | 🌐 Python | 📅 2026-08-23 A powerful, user-friendly terminal interface for AWS Profile and SSO management.
* [Judo](https://github.com/giacomopiccinini/judo) ⭐ 124 | 🐛 1 | 🌐 Rust | 📅 2026-02-16 A multi-database TUI for ToDo lists, using Rust + Ratatui + SQLite
* [procmux](https://github.com/napisani/procmux) ⭐ 111 | 🐛 2 | 🌐 Python | 📅 2025-11-23 a TUI for running multiple commands in parallel in easily switchable terminals
* [portfolio\_rs](https://github.com/MarkusZoppelt/portfolio_rs) ⭐ 97 | 🐛 1 | 🌐 Rust | 📅 2026-11-24 A command line tool for managing financial investment portfolios.
* [leetrs](https://github.com/shadowmkj/leetrs) ⭐ 96 | 🐛 13 | 🌐 Rust | 📅 2026-11-22 A blazing-fast, Rust-powered TUI and engine for solving LeetCode problems from the terminal
* [openmux](https://github.com/monotykamary/openmux) ⭐ 92 | 🐛 3 | 🌐 TypeScript | 📅 2026-06-16 A terminal multiplexer with master-stack layout (Zellij-style)
* [tui-slides](https://github.com/Chleba/tui-slides) ⭐ 85 | 🐛 2 | 🌐 Rust | 📅 2024-09-12 A terminal presentation tool capable of rendering images and many other widgets.
* [tododo](https://github.com/bmarse/tododo) ⭐ 73 | 🐛 3 | 🌐 Go | 📅 2025-09-05 A pretty TUI TODO.md manager for tasks and projects
* [linear-tui](https://github.com/roeyazroel/linear-tui) ⭐ 66 | 🐛 3 | 🌐 Go | 📅 2026-09-28 A terminal user interface for Linear built with Go and tview.
* [pkm](https://github.com/wick3dr0se/pkm) ⭐ 64 | 🐛 1 | 🌐 Shell | 📅 2024-06-17 A super minimal TUI package manager wrapper written in BASH v4.2+
* [productivity-timer](https://github.com/h-sifat/productivity-timer) ⭐ 60 | 🐛 2 | 🌐 TypeScript | 📅 2026-05-15 A command line time tracker application with a sleek TUI.
* [multranslate](https://github.com/Lifailon/multranslate) ⭐ 58 | 🐛 1 | 🌐 JavaScript | 📅 2025-03-31 A TUI for translating text in multiple translators simultaneously, with support for translation history and language detection
* [pdiary](https://github.com/manipuladordedados/pdiary) ⭐ 49 | 🐛 2 | 🌐 Python | 📅 2022-09-12 A simple terminal diary journal application written in Python with encryption support
* [drako](https://github.com/lucky7xz/drako) ⭐ 42 | 🐛 0 | 🌐 Go | 📅 2026-11-26 A grid-based, customizable and extendable command- and TUI-Deck launcher
* [hnjobs](https://github.com/mwinters0/hnjobs) ⭐ 42 | 🐛 0 | 🌐 Go | 📅 2025-09-10 Find your next job on Who's Hiring
* [trx](https://github.com/pie-314/trx) ⭐ 41 | 🐛 68 | 🌐 Rust | 📅 2026-07-06 - Terminal package manager with fuzzy search and keyboard-driven package discovery.
* [Chronos](https://github.com/samuelstranges/chronos) ⭐ 39 | 🐛 2 | 🌐 Go | 📅 2026-09-25 A Vimlike Calendar TUI
* [TUI\_ProjectManager](https://github.com/NicoDblc/TUI_ProjectManager) ⭐ 34 | 🐛 0 | 🌐 Rust | 📅 2024-03-18 A simple project-based todo list written in Rust
* [tuihub](https://github.com/ashis0013/tuihub) ⭐ 26 | 🐛 0 | 🌐 Go | 📅 2023-09-22 A utility hub/dashboard for personal use
* [HydroToDo](https://github.com/Henriquehnnm/hydrotodo) ⭐ 25 | 🐛 0 | 🌐 Python | 📅 2026-01-16 A simple and beautiful TUI to-do list
* [tui-deck](https://github.com/mebitek/tui-deck) ⭐ 23 | 🐛 1 | 🌐 Go | 📅 2024-02-25 A TUI frontend for Nextcloud Deck app written in GO
* [levite](https://github.com/RauliL/levite) ⭐ 17 | 🐛 0 | 🌐 C++ | 📅 2026-09-16 A TUI spreadsheet application that uses an RPN formulas and features a vi-friendly interface
* [pream-team](https://github.com/nikoladucak/pream-team/) ⭐ 13 | 🐛 5 | 🌐 Python | 📅 2024-02-26 a TUI utility that helps you keep track of your teams GitHub PRs across multiple repositories
* [HydroFetch](https://github.com/Henriquehnnm/hydrofetch) ⭐ 12 | 🐛 0 | 🌐 Shell | 📅 2026-01-25 A fast, beautiful, and lightweight system information tool written exclusively for the Fish shell.
* [ttm](https://github.com/vst93/ttm) ⭐ 12 | 🐛 0 | 🌐 Go | 📅 2026-10-10 SSH bookmark manager with Bubble Tea TUI — connect, manage and sync via Gist
* [GeekCalendar](https://github.com/fearlessgeekmedia/GeekCalendar) ⭐ 10 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-03 TUI calendar with vim key bindings, which can import from calcure or calcurse.
* [pagerduty-tui](https://github.com/Mk555/pagerduty-tui) ⭐ 9 | 🐛 2 | 🌐 Rust | 📅 2024-12-11 Minimalistic terminal UI to manage triggered incidents
* [tuidict](https://github.com/404Simon/tuidict) ⭐ 9 | 🐛 1 | 🌐 Rust | 📅 2026-11-26 Fast offline dictionary with in-app downloads and multi-language support from FreeDict
* [Tomatui](https://github.com/Hiro-Chiba/tomatui) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2026-10-25 A Pomodoro timer with a full-screen TUI, a minimal one-line mode, and local session statistics.
* [Bada](https://github.com/Han8931/bada) ⭐ 6 | 🐛 0 | 🌐 Go | 📅 2026-09-27 A minimalist, Vim-first task manager designed to help you focus without distraction.
* [fuzz.fish](https://github.com/jedipunkz/fuzz.fish) ⭐ 5 | 🐛 2 | 🌐 Go | 📅 2026-11-23 A fuzzy finder for the Fish shell with preview panes for command history, files, git branches, worktrees, and commits
* [monolog](https://github.com/maksmas/monolog) ⭐ 3 | 🐛 1 | 🌐 Go | 📅 2026-11-26 Keyboard-driven personal backlog stored as one JSON file per task in a git repo you own, with conflict-free sync across devices
* [Paca](https://github.com/wes/paca) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-27 Task, timer, and Stripe invoicing for projects, with local-first SQLite storage
* [christophorus](https://github.com/michaelblaess/christophorus) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-10-13 Vehicle logbook with trips, odometer chain, plausibility checks and export to Excel, PDF, JSON or Markdown
* [abook](https://abook.sourceforge.io/) TUI addressbook with [mutt](http://www.mutt.org/) integration
* [calcurse](https://calcurse.org/) calendar and scheduling application for the command line

***

</details>

<details open><summary><h2>Screensavers</h2></summary>

* [gitlogue](https://github.com/unhappychoice/gitlogue) ⭐ 5,290 | 🐛 9 | 🌐 Rust | 📅 2026-11-26 A TUI screensaver that visualizes Git commit history in your terminal
* [weathr](https://github.com/veirt/weathr) ⭐ 3,096 | 🐛 19 | 🌐 Rust | 📅 2026-08-12 A terminal weather app with ASCII animations for weather visualization
* [astroterm](https://github.com/da-luce/astroterm) ⭐ 2,568 | 🐛 44 | 🌐 C | 📅 2026-09-11 A planetarium for your terminal! Explore stars, planets, constellations, and more
* [neo](https://github.com/st3w/neo) ⭐ 977 | 🐛 16 | 🌐 C++ | 📅 2024-04-02 Simulates the digital rain from "The Matrix"
* [cbirds](https://github.com/clainstone/cbirds) ⭐ 325 | 🐛 0 | 🌐 C | 📅 2026-11-18 A flock of boids in your terminal, in C99 with zero dependencies: braille anywhere, sprites in Kitty and Ghostty
* [rxpipes](https://github.com/inunix3/rxpipes) ⭐ 48 | 🐛 0 | 🌐 Rust | 📅 2024-09-07 2D recreation of the ancient Pipes screensaver for terminals.
* [pond](https://gitlab.com/alice-lefebvre/pond) A soothing in-terminal idle screen that simulates a little pond.

***

</details>

<details open><summary><h2>Web</h2></summary>

* [carbonyl](https://github.com/fathyb/carbonyl) ⭐ 19,614 | 🐛 91 | 🌐 Rust | 📅 2024-07-01 Chromium running inside your terminal
* [browsh](https://github.com/browsh-org/browsh) ⭐ 19,142 | 🐛 240 | 🌐 JavaScript | 📅 2026-11-02 A fully-modern text-based browser, rendering to TTY and browsers
* [rtorrent](https://github.com/rakshasa/rtorrent) ⭐ 4,897 | 🐛 390 | 🌐 C++ | 📅 2026-11-26 A text-based BitTorrent client written in C++
* [haxor-news](https://github.com/donnemartin/haxor-news) ⭐ 4,090 | 🐛 42 | 🌐 Python | 📅 2022-04-22 Browse Hacker News like a haxor: A Hacker News command line interface (CLI)
* [newsboat](https://github.com/newsboat/newsboat) ⭐ 3,954 | 🐛 414 | 🌐 C++ | 📅 2026-11-21 An RSS/Atom feed reader for the text console
* [surge](https://github.com/SurgeDM/Surge) ⭐ 3,654 | 🐛 53 | 🌐 Go | 📅 2026-11-26 A blazing fast, beautiful TUI download manager built in Go.
* [textual-web](https://github.com/Textualize/textual-web) ⭐ 1,477 | 🐛 23 | 🌐 Python | 📅 2024-08-30 Run TUIs and terminals in your browser
* [Slumber](https://github.com/LucasPickering/slumber) ⭐ 1,241 | 🐛 9 | 🌐 Rust | 📅 2026-11-24 Terminal-based HTTP/REST client
* [cloudflare-speed-cli](https://github.com/kavehtehrani/cloudflare-speed-cli) ⭐ 1,101 | 🐛 0 | 🌐 Rust | 📅 2026-11-03 Internet speed test via Cloudflare
* [w3m](https://github.com/tats/w3m) ⭐ 1,090 | 🐛 79 | 🌐 C | 📅 2024-08-19 A text-mode WWW browser
* [eilmeldung](https://github.com/christo-auer/eilmeldung) ⭐ 1,070 | 🐛 5 | 🌐 Rust | 📅 2026-11-26 RSS reader, supporting many RSS providers, bulk-operations and configuration options.
* [hackernews-TUI](https://github.com/aome510/hackernews-TUI) ⭐ 721 | 🐛 9 | 🌐 Rust | 📅 2026-03-29 A Terminal UI to browse Hacker News
* [nyaa](https://github.com/Beastwick18/nyaa) ⭐ 716 | 🐛 16 | 🌐 Rust | 📅 2026-02-28 A nyaa.si TUI for browsing and downloading torrents
* [castero](https://github.com/xgi/castero) ⭐ 687 | 🐛 32 | 🌐 Python | 📅 2026-04-21 A TUI app to listen to podcast
* [elinks](https://github.com/rkd77/elinks) ⭐ 648 | 🐛 123 | 🌐 C | 📅 2026-11-18 ELinks (HTTP/FTP/..) brower with mujs javascript support.
* [bulletty](https://github.com/CrociDB/bulletty) ⭐ 453 | 🐛 19 | 🌐 Rust | 📅 2026-11-23 A pretty feed reader (ATOM/RSS) that stores articles in Markdown files
* [twterm](https://github.com/ryota-ka/twterm) ⭐ 244 | 🐛 23 | 🌐 Ruby | 📅 2023-12-15 A full-featured TUI Twitter client
* [podliner](https://github.com/timkicker/podliner) ⭐ 184 | 🐛 1 | 🌐 C# | 📅 2026-11-17 A cross-platform podcast client
* [stegodon](https://github.com/deemkeen/stegodon) ⭐ 92 | 🐛 3 | 🌐 Go | 📅 2026-07-05 SSH-first federated microblog with ActivityPub, web UI, and RSS feeds
* [rfc\_reader](https://github.com/ozan2003/rfc_reader) ⭐ 74 | 🐛 0 | 🌐 Rust | 📅 2026-10-21 A tool to read RFCs (Request for Comments) with a TUI, allowing you to fetch, cache, and browse RFC documents.
* [tblogs](https://github.com/ezeoleaf/tblogs) ⭐ 66 | 🐛 5 | 🌐 Go | 📅 2026-07-03 Read and browse development blogs from your terminal
* [searxngr](https://github.com/scross01/searxngr) ⭐ 58 | 🐛 2 | 🌐 Python | 📅 2026-11-26 Web search TUI for SearXNG
* [CatenaVetus](https://github.com/jimbob88/CatenaVetus) ⭐ 23 | 🐛 1 | 🌐 Python | 📅 2026-11-02 A TUI for reading the Church Fathers
* [omaro](https://github.com/Rolv-Apneseth/omaro) ⭐ 21 | 🐛 3 | 🌐 Rust | 📅 2026-11-21 TUI to browse posts and comments on lobste.rs
* [sitemap-tracker](https://github.com/michaelblaess/sitemap-tracker) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2026-10-13 Crawls websites and generates sitemap.xml files, with sitemap tree view and crawl history
* [console-error-scanner](https://github.com/michaelblaess/console-error-scanner) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-10-13 Scans websites from a URL or sitemap for JavaScript console errors and HTTP failures (404, 5xx), with HTML and JSON reports
* [bombadillo](https://bombadillo.colorfield.space/) A TUI browser for the non-web: Gopher, Gemini, Finger
* [Chawan](https://chawan.net) A TUI web (and (S)FTP, Gopher, Gemini) browser with CSS, inline image and JavaScript support.
* [Lagrange](https://gmi.skyjake.fi/lagrange) Lagrange is a cross-platform client for browsing Geminispace
* [LYNX](https://lynx.invisible-island.net/) A text based Terminal browser
* [rttt](https://gitlab.com/BlackEdder/rttt) A Hackernews, RSS and Reddit reader for the terminal written in C++.

***

</details>

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-11-27._
