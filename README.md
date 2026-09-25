# Awesome tuis with stars

<h1 align="center">
  <code>Awesome TUIs</code>
</h1>

This is a community maintained list of TUI applications. A TUI application runs in your terminal and has some level of interactivity. Commands included in this list should not wrap other interactive commands (e.g. `fzf`), and should be maintained.

I made a video of my favorite TUIs from this list (one from each section). Click the image to check it out. 👇

[![](https://i.ytimg.com/vi/_fLmA4fjiAE/maxresdefault.jpg)](https://youtu.be/_fLmA4fjiAE?si=IgXuo)

There's a lot of cool projects here that I have no association with. Run them at your own risk. If you have a cool tool you'd like to share please [open a PR](https://github.com/rothgar/awesome-tuis/pulls) ⭐ 20,729 | 🐛 47 | 📅 2026-09-22.

## Table of Contents

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

<details open><summary><h2>Dashboards</h2></summary>

* [btop++](https://github.com/aristocratos/btop) ⭐ 34,752 | 🐛 550 | 🌐 C++ | 📅 2026-09-25 Resource monitor with extras
* [Glances](https://github.com/nicolargo/glances) ⭐ 33,675 | 🐛 109 | 🌐 Python | 📅 2026-09-25 Glances an Eye on your system. A top/htop alternative.
* [Goaccess](https://github.com/allinurl/goaccess) ⭐ 20,952 | 🐛 448 | 🌐 C | 📅 2026-09-24 GoAccess is a real-time web log analyzer and interactive viewer that runs in a terminal in nix systems or through your browser.
* [WTF](https://github.com/senorprogrammer/wtf) ⭐ 17,101 | 🐛 108 | 🌐 Go | 📅 2026-09-17 The personal information dashboard for your terminal.
* [bottom](https://github.com/ClementTsang/bottom) ⭐ 14,061 | 🐛 106 | 🌐 Rust | 📅 2026-09-23 A customizable graphical process/system monitor for the terminal.
* [TermUI](https://github.com/gizak/termui) ⭐ 13,590 | 🐛 106 | 🌐 Go | 📅 2025-07-10 Golang terminal dashboard
* [gping](https://github.com/orf/gping) ⭐ 12,693 | 🐛 42 | 🌐 Rust | 📅 2026-09-23 Ping, but with a graph
* [gh-dash](https://github.com/dlvhdr/gh-dash) ⭐ 12,556 | 🐛 101 | 🌐 Go | 📅 2026-09-22 A rich terminal UI for GitHub PRs and Issues
* [bandwhich](https://github.com/imsnif/bandwhich) ⭐ 11,987 | 🐛 54 | 🌐 Rust | 📅 2026-08-01 Terminal bandwidth utilization tool
* [talos linux](https://github.com/siderolabs/talos) ⭐ 11,236 | 🐛 259 | 🌐 Go | 📅 2026-09-25 A Linux distro with a TUI dashboard for local and remote usage
* [bashtop](https://github.com/aristocratos/bashtop) ⭐ 11,117 | 🐛 64 | 🌐 Shell | 📅 2023-08-21 Resource manager written in bash
* [nvtop](https://github.com/Syllo/nvtop) ⭐ 11,023 | 🐛 134 | 🌐 C | 📅 2026-09-20 GPUs process monitoring for AMD, Intel and NVIDIA
* [bpytop](https://github.com/aristocratos/bpytop) ⭐ 10,928 | 🐛 99 | 🌐 Python | 📅 2025-06-01 A Python-based system monitor with lots of information.
* [htop](https://github.com/htop-dev/htop) ⭐ 8,348 | 🐛 355 | 🌐 C | 📅 2026-09-22 Interactive text-mode process viewer for Unix systems. It aims to be a better 'top'
* [csysdig](https://github.com/draios/sysdig) ⭐ 8,295 | 🐛 116 | 🌐 C++ | 📅 2026-04-13 root level Ncurses interface for sysdig, Linux system exploration and troubleshooting tool with first class support for containers
* [trippy](https://github.com/fujiapple852/trippy) ⭐ 7,960 | 🐛 86 | 🌐 Rust | 📅 2026-09-15 A network diagnostic tool that includes functionality like mtr and more
* [Backlog.md](https://github.com/MrLesk/Backlog.md) ⭐ 6,848 | 🐛 71 | 🌐 TypeScript | 📅 2026-09-24 A tool for managing project collaboration between humans and AI Agents in a git ecosystem
* [ticker](https://github.com/achannarasappa/ticker) ⭐ 6,240 | 🐛 34 | 🌐 Go | 📅 2026-06-28 Track stocks, crypto, and derivatives prices and positions in real time from your terminal
* [s-tui](https://github.com/amanusk/s-tui) ⭐ 5,101 | 🐛 39 | 🌐 Python | 📅 2026-09-15 CPU stress and monitoring utility
* [Kyanos](https://github.com/hengyoush/kyanos) ⭐ 5,070 | 🐛 32 | 🌐 C | 📅 2026-09-16 Linux network analysis tool based on eBPF
* [rustnet](https://github.com/domcyrus/rustnet) ⭐ 5,054 | 🐛 33 | 🌐 Rust | 📅 2026-09-25 A cross-platform network monitoring tool with deep packet inspection
* [binsider](https://github.com/orhun/binsider) ⭐ 4,445 | 🐛 38 | 🌐 Rust | 📅 2026-09-20 A TUI for analyzing Linux binaries.
* [cointop](https://github.com/miguelmota/cointop) ⚠️ Archived The fastest and most interactive terminal based UI application for tracking cryptocurrencies
* [nethogs](https://github.com/raboof/nethogs) ⭐ 3,697 | 🐛 104 | 🌐 C++ | 📅 2026-07-23 'net top' tool
* [psmux](https://github.com/marlocarlo/psmux) ⭐ 3,554 | 🐛 46 | 🌐 PowerShell | 📅 2026-09-25 tmux-compatible terminal multiplexer for Windows built in Rust with ratatui.
* [gobang](https://github.com/TaKO8Ki/gobang) ⭐ 3,322 | 🐛 57 | 🌐 Rust | 📅 2023-11-10 A cross-platform TUI database management tool written in Rust
* [gotop](https://github.com/xxxserxxx/gotop) ⭐ 3,092 | 🐛 90 | 🌐 Go | 📅 2026-05-07 A terminal based graphical activity monitor inspired by gtop and vtop
* [zenith](https://github.com/bvaisvil/zenith) ⭐ 3,055 | 🐛 40 | 🌐 Rust | 📅 2026-09-02 In terminal graphical metrics for your \*nix system written in Rust
* [kmon](https://github.com/orhun/kmon) ⭐ 2,950 | 🐛 23 | 🌐 Rust | 📅 2026-09-21 Linux Kernel Manager and Activity Monitor
* [process-compose](https://github.com/F1bonacc1/process-compose) ⭐ 2,800 | 🐛 26 | 🌐 Go | 📅 2026-09-21 TUI for running apps and processes
* [gonzo](https://github.com/control-theory/gonzo) ⭐ 2,771 | 🐛 17 | 🌐 Go | 📅 2026-09-23 A powerful, real-time log analysis terminal UI inspired by k9s.
* [oryx](https://github.com/pythops/oryx) ⭐ 2,581 | 🐛 5 | 🌐 Rust | 📅 2026-09-01 A TUI for sniffing network traffic using eBPF
* [below](https://github.com/facebookincubator/below) ⭐ 2,524 | 🐛 32 | 🌐 Rust | 📅 2026-09-25 A time traveling resource monitor for modern Linux systems
* [CoreFreq](https://github.com/cyring/CoreFreq) ⭐ 2,244 | 🐛 2 | 🌐 C | 📅 2026-09-23 CPU monitoring software designed for the 64-bits Processors
* [macmon](https://github.com/vladkens/macmon) ⭐ 1,901 | 🐛 18 | 🌐 Rust | 📅 2026-08-04 Sudoless performance monitoring for Apple Silicon processors written in Rust
* [sysz](https://github.com/joehillen/sysz) ⭐ 1,881 | 🐛 5 | 🌐 Shell | 📅 2024-04-22 An fzf terminal UI for systemctl
* [netscanner](https://github.com/Chleba/netscanner) ⭐ 1,861 | 🐛 6 | 🌐 Rust | 📅 2026-07-06 Network scanner
* [cgdb](https://github.com/cgdb/cgdb) ⭐ 1,845 | 🐛 46 | 🌐 C | 📅 2026-02-27 Console front-end to the GNU debugger
* [AdGuardian-Term](https://github.com/lissy93/AdGuardian-Term) ⭐ 1,663 | 🐛 7 | 🌐 Rust | 📅 2026-09-15 A TUI dashboard for monitoring real-time traffic from an AdGuard Home instance
* [nerdlog](https://github.com/dimonomid/nerdlog) ⭐ 1,566 | 🐛 12 | 🌐 Go | 📅 2026-09-24 fast, remote-first, multi-host TUI log viewer
* [bmon](https://github.com/tgraf/bmon) ⭐ 1,392 | 🐛 37 | 🌐 C | 📅 2026-09-19 A monitoring and debugging tool to capture networking related statistics and prepare them visually.
* [dolphie](https://github.com/charles-001/dolphie) ⭐ 1,198 | 🐛 1 | 🌐 Python | 📅 2026-09-15 Your single pane of glass for real-time analytics into MySQL/MariaDB & ProxySQL
* [Grafterm](https://github.com/slok/grafterm) ⭐ 1,143 | 🐛 11 | 🌐 Go | 📅 2022-06-10 Metrics dashboards on terminal, a Grafana inspired terminal version
* [updo](https://github.com/Owloops/updo) ⭐ 1,137 | 🐛 6 | 🌐 Go | 📅 2026-05-26 Website monitoring tool with uptime tracking, response time metrics, and SSL certificate monitoring.
* [otel-tui](https://github.com/ymtdzzz/otel-tui) ⭐ 1,091 | 🐛 27 | 🌐 Go | 📅 2026-09-21 A terminal OpenTelemetry viewer
* [hwatch](https://github.com/blacknon/hwatch) ⭐ 1,080 | 🐛 10 | 🌐 Rust | 📅 2026-08-30 A modern alternative to watch that records command output history and provides interactive diff views, scrolling, filtering, JSON logging, and hooks.
* [atop](https://github.com/Atoptool/atop/) ⭐ 1,067 | 🐛 60 | 🌐 C | 📅 2026-09-23 root level system and process monitor for Linux
* [kaskade](https://github.com/sauljabin/kaskade) ⭐ 1,039 | 🐛 21 | 🌐 Python | 📅 2026-09-25 TUI for kafka, which allows you to interact and consume topics from your terminal in style!
* [tufw](https://github.com/peltho/tufw) ⭐ 866 | 🐛 4 | 🌐 Go | 📅 2026-06-08 Terminal UI for ufw
* [Puffin](https://github.com/siddhantac/puffin) ⭐ 571 | 🐛 11 | 🌐 Go | 📅 2026-03-11 A beautiful terminal dashboard for hledger
* [damon](https://github.com/hashicorp/damon) ⭐ 488 | 🐛 11 | 🌐 Go | 📅 2026-08-24 TUI interface for Hashicorp Nomad
* [wander](https://github.com/robinovitch61/wander) ⭐ 481 | 🐛 4 | 🌐 Go | 📅 2024-06-18 HashiCorp Nomad terminal client
* [ttop](https://github.com/inv2004/ttop) ⭐ 397 | 🐛 6 | 🌐 Nim | 📅 2026-08-16 System monitoring tool with historical data service, triggers and top-like TUI
* [framework-tool-tui](https://github.com/grouzen/framework-tool-tui) ⭐ 356 | 🐛 14 | 🌐 Rust | 📅 2026-09-20 TUI for controlling and monitoring Framework Computers hardware built in Rust
* [Yozefu](https://github.com/MAIF/yozefu) ⭐ 349 | 🐛 6 | 🌐 Rust | 📅 2026-08-27 A TUI for exploring data of a kafka cluster.
* [tdash](https://github.com/jessfraz/tdash) ⭐ 320 | 🐛 1 | 🌐 Go | 📅 2023-02-24 A terminal dashboard with stats from Google Analytics, GitHub, Travis CI, and Jenkins. Very much built specific to me
* [chdig](https://github.com/azat/chdig) ⭐ 296 | 🐛 4 | 🌐 Rust | 📅 2026-09-15 Dig into ClickHouse with TUI interface
* [dashbrew](https://github.com/rasjonell/dashbrew) ⭐ 273 | 🐛 1 | 🌐 Go | 📅 2026-05-15 TUI dashboard builder that lets you visualize data from scripts and APIs.
* [pstop](https://github.com/marlocarlo/pstop) ⭐ 253 | 🐛 2 | 🌐 Rust | 📅 2026-09-23 htop-style system monitor for Windows with per-core CPU bars, tree view, and 7 color schemes.
* [cheatshh](https://github.com/AnirudhG07/cheatshh) ⭐ 194 | 🐛 0 | 🌐 Shell | 📅 2025-08-15 A fzf TUI for managing custom made command-line cheatsheet for Unix.
* [sockttop](https://github.com/jasonwitty/socktop) ⭐ 191 | 🐛 0 | 🌐 Rust | 📅 2026-08-31 socktop is a remote system monitor with a rich TUI, inspired by top/btop, talking to a lightweight agent over WebSockets.
* [Raijin](https://github.com/MasonStooksbury/Raijin) ⭐ 173 | 🐛 2 | 🌐 Rust | 📅 2026-09-25 A free, simple weather TUI that pulls data without the need for an API key, account, or subscription
* [claws](https://github.com/clawscli/claws) ⭐ 159 | 🐛 6 | 🌐 Go | 📅 2026-07-25 A terminal UI for AWS resource management with vim-style keybindings, command-mode navigation, and optional read-only mode.
* [psnet](https://github.com/marlocarlo/psnet) ⭐ 149 | 🐛 4 | 🌐 Rust | 📅 2026-08-10 Real-time TUI network monitor for Windows with speed graphs, DNS resolution, and packet inspection.
* [htui](https://github.com/PierreKieffer/htui) ⭐ 123 | 🐛 1 | 🌐 Go | 📅 2021-04-26 Heroku Terminal User Interface
* [Planor](https://github.com/mrusme/planor) ⚠️ Archived The Cloud Aviator, dashboard for AWS, Vultr, Heroku, ...
* [ls-horizons](https://github.com/litescript/ls-horizons) ⭐ 85 | 🐛 0 | 🌐 Go | 📅 2026-08-20 Terminal UI for visualizing NASA's Deep Space Network in real-time
* [tegratop](https://github.com/pythops/tegratop) ⭐ 85 | 🐛 1 | 🌐 Rust | 📅 2025-12-14 Monitoring tool (top like) for Nvidia jetson boards
* [lazyslurm](https://github.com/hill/lazyslurm) ⭐ 82 | 🐛 1 | 🌐 Rust | 📅 2026-08-09 A lazygit-style terminal UI for Slurm. Monitor jobs, tail logs, and inspect nodes and partitions.
* [hwinfo-tui](https://github.com/JuanjoFuchs/hwinfo-tui) ⭐ 64 | 🐛 0 | 🌐 Python | 📅 2025-12-01 A gping-inspired terminal visualization tool for monitoring real-time hardware sensor data from HWInfo
* [fubar](https://github.com/irishmaestro/fubar) ⭐ 63 | 🐛 1 | 🌐 Rust | 📅 2024-10-09 Formidable Unix Binary Arsenal & Repository. TUI built for gtfobins power users.
* [tmd-top](https://github.com/CDWEN0526/tmd-top) ⭐ 61 | 🐛 1 | 🌐 Python | 📅 2024-12-24 Used to monitor the process tcp traffic of the linux system, detailed to each IP connection
* [apachetop](https://github.com/tessus/apachetop) ⭐ 51 | 🐛 2 | 🌐 C++ | 📅 2024-02-12 display information from a running copy of Apache.
* [ServerHub](https://github.com/nickprotop/ServerHub) ⭐ 49 | 🐛 0 | 🌐 C# | 📅 2026-07-18 A TUI server monitoring dashboard for Linux with real-time metrics, scriptable widgets, and remote management
* [trek](https://github.com/franckverrot/trek) ⭐ 32 | 🐛 1 | 🌐 Go | 📅 2023-08-30 ncurses explorer for Hashicorp Nomad clusters
* [Servonaut](https://github.com/zb-ss/servonaut) ⭐ 28 | 🐛 36 | 🌐 Python | 📅 2026-09-25 A TUI for managing AWS, Hetzner, OVH and custom SSH servers with log viewing, CloudWatch/CloudTrail browsing, IP banning, AI log analysis and a built-in MCP server
* [ID-Spoofer](https://github.com/NubleX/ID-Spoofer) ⭐ 25 | 🐛 7 | 🌐 Go | 📅 2026-03-01 A cross-platform cybersecurity toolkit for fingerprint and traffic obfuscation.
* [sacha](https://github.com/Sachamama/sacha) ⭐ 23 | 🐛 11 | 🌐 Go | 📅 2026-06-22 A two-pane AWS TUI for browsing, searching, and managing resources across seven services including CloudWatch Logs, S3, DynamoDB, Lambda, SSM, SQS, and EC2.
* [bullmq-dash](https://github.com/quanghuynt14/bullmq-dash) ⭐ 18 | 🐛 5 | 🌐 TypeScript | 📅 2026-08-30 Dashboard for monitoring BullMQ queues, inspecting jobs, and retrying failures
* [toptop](https://github.com/ur-grue/toptop) ⭐ 15 | 🐛 4 | 🌐 Rust | 📅 2026-09-21 htop/btop-class system monitor with a local-LLM view: tokens/sec, VRAM-spill and memory-bandwidth verdicts, NVIDIA + Apple Silicon
* [tuicamp](https://github.com/AbeEstrada/tuicamp) ⭐ 8 | 🐛 0 | 🌐 Go | 📅 2025-08-18 Unofficial TimeCamp TUI

***

</details>

<details open><summary><h2>Development</h2></summary>

* [opencode](https://github.com/sst/opencode) ⭐ 210,052 | 🐛 6,288 | 🌐 TypeScript | 📅 2026-09-25 AI coding agent, built for the terminal
* [codex](https://github.com/openai/codex) ⭐ 126,462 | 🐛 18,805 | 🌐 Rust | 📅 2026-09-25 Lightweight coding agent that runs in your terminal
* [lazygit](https://github.com/jesseduffield/lazygit) ⭐ 82,674 | 🐛 1,057 | 🌐 Go | 📅 2026-09-25 Simple terminal UI for git commands
* [delta](https://github.com/dandavison/delta) ⭐ 32,347 | 🐛 452 | 🌐 Rust | 📅 2026-09-19 A syntax-highlighting pager for git, diff, and grep output
* [crush](https://github.com/charmbracelet/crush) ⭐ 28,304 | 🐛 796 | 🌐 Go | 📅 2026-09-25 The glamourous AI coding agent
* [gitui](https://github.com/extrawurst/gitui) ⭐ 22,523 | 🐛 346 | 🌐 Rust | 📅 2026-08-04 blazing fast terminal-ui for git written in rust
* [fx](https://github.com/antonmedv/fx) ⭐ 20,641 | 🐛 35 | 🌐 Go | 📅 2026-08-26 Terminal JSON viewer & processor
* [tig](https://github.com/jonas/tig) ⭐ 13,349 | 🐛 231 | 🌐 C | 📅 2026-09-19 Text-mode interface for git
* [posting](https://github.com/darrenburns/posting) ⭐ 12,450 | 🐛 87 | 🌐 Python | 📅 2026-03-25 A powerful HTTP client that lives in your terminal
* [Claude Code Usage Monitor](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor) ⭐ 8,725 | 🐛 38 | 🌐 Python | 📅 2026-07-05 Monitor Claude token usage
* [blinkenlights](https://github.com/jart/blink) ⭐ 7,588 | 🐛 55 | 🌐 C | 📅 2025-12-10 TUI that may be used for debugging x86\_64-linux or i8086 programs across platforms
* [soft-serve](https://github.com/charmbracelet/soft-serve) ⭐ 7,231 | 🐛 82 | 🌐 Go | 📅 2026-09-01 A tasty, self-hostable Git server for the command lineicecream
* [harlequin](https://github.com/tconbeer/harlequin) ⭐ 6,419 | 🐛 32 | 🌐 Python | 📅 2026-09-21 The SQL IDE for Your Terminal
* [rainfrog](https://github.com/achristmascarl/rainfrog) ⭐ 5,349 | 🐛 13 | 🌐 Rust | 📅 2026-09-24 A database management TUI for Postgres, MySQL, and SQLite written in Rust
* [sqlit](https://github.com/Maxteabag/sqlit) ⭐ 4,858 | 🐛 18 | 🌐 Python | 📅 2026-09-10 A lightweight TUI for SQL databases inspired by lazygit
* [lazysql](https://github.com/jorgerojas26/lazysql) ⭐ 4,325 | 🐛 39 | 🌐 Go | 📅 2026-09-25 A cross-platform TUI database management tool written in Go.
* [grv](https://github.com/rgburke/grv) ⭐ 4,095 | 🐛 31 | 🌐 Go | 📅 2019-05-01 Terminal interface for viewing git repositories
* [ATAC](https://github.com/Julien-cpsn/ATAC) ⭐ 3,730 | 🐛 22 | 🌐 Rust | 📅 2026-09-03 A feature-full TUI API client made in Rust. ATAC is free, open-source, offline and account-less.
* [Claude Code Bridge](https://github.com/bfly123/claude_code_bridge) ⭐ 3,524 | 🐛 102 | 🌐 Python | 📅 2026-09-21 Real-time multi-AI collaboration between Claude, Codex and Gemini in terminal
* [Toad](https://github.com/batrachianai/toad) ⭐ 3,447 | 🐛 7 | 🌐 Python | 📅 2026-05-26 A unified interface for AI
* [pudb](https://github.com/inducer/pudb) ⭐ 3,246 | 🐛 164 | 🌐 Python | 📅 2026-09-20 A console-based visual debugger for Python
* [dblab](https://github.com/danvergara/dblab) ⭐ 3,236 | 🐛 11 | 🌐 Go | 📅 2026-09-25 The database client every command line junkie deserves
* [jqp](https://github.com/noahgorstein/jqp) ⭐ 2,845 | 🐛 24 | 🌐 Go | 📅 2026-02-06 A TUI playground to experiment with jq
* [euporie](https://github.com/joouha/euporie) ⭐ 2,667 | 🐛 15 | 🌐 Python | 📅 2026-09-18 Jupyter notebooks in the terminal
* [nap](https://github.com/maaslalani/nap) ⭐ 2,216 | 🐛 17 | 🌐 Go | 📅 2024-05-18 Code snippets in your terminal
* [runme](https://github.com/stateful/runme) ⭐ 2,177 | 🐛 152 | 🌐 Go | 📅 2026-09-17 Discover and run code snippets directly from your README.md or other markdowns
* [serie](https://github.com/lusingander/serie) ⭐ 2,118 | 🐛 25 | 🌐 Rust | 📅 2026-09-22 A rich git commit graph
* [resterm](https://github.com/unkn0wn-root/resterm) ⭐ 1,950 | 🐛 1 | 🌐 Go | 📅 2026-09-25 A terminal client for HTTP/GraphQL/gRPC with support for WebSockets, SSE, workflows, profiling, OpenAPI and response diffs.
* [termdbms](https://github.com/mathaou/termdbms) ⭐ 1,826 | 🐛 6 | 🌐 Go | 📅 2022-06-11 A TUI for viewing and editing database files.
* [lazyjournal](https://github.com/Lifailon/lazyjournal) ⭐ 1,412 | 🐛 9 | 🌐 Go | 📅 2026-08-01 TUI for journalctl, file system logs, as well Docker and Podman containers for quick viewing and filtering
* [snips.sh](https://github.com/robherley/snips.sh) ⭐ 1,309 | 🐛 13 | 🌐 Go | 📅 2026-09-08 ✂️ passwordless, anonymous SSH-powered pastebin with a human-friendly TUI and web UI
* [terraform-tui](https://github.com/idoavrah/terraform-tui) ⭐ 1,294 | 🐛 5 | 🌐 Python | 📅 2026-09-07 view and interact with Terraform state
* [proxelar](https://github.com/emanuele-em/proxelar) ⭐ 1,074 | 🐛 0 | 🌐 Rust | 📅 2026-09-25 Scriptable MITM proxy TUI to inspect, intercept, replay, and rewrite HTTP(S) and WebSocket traffic
* [stu](https://github.com/lusingander/stu) ⭐ 911 | 🐛 15 | 🌐 Rust | 📅 2026-04-30 A TUI for Amazon S3
* [sls-dev-tools](https://github.com/Theodo-UK/sls-dev-tools) ⭐ 871 | 🐛 62 | 🌐 JavaScript | 📅 2023-04-25 Dev Tools for the Serverless World
* [VT Code](https://github.com/vinhnx/vtcode) ⭐ 854 | 🐛 2 | 🌐 Rust | 📅 2026-09-25 VT Code - Semantic Coding Agent
* [austin-tui](https://github.com/P403n1x87/austin-tui) ⭐ 665 | 🐛 2 | 🌐 Python | 📅 2026-06-04 The top-like text-based user interface for Austin
* [play](https://github.com/paololazzari/play) ⭐ 590 | 🐛 3 | 🌐 Go | 📅 2025-03-28 A TUI playground to experiment with your favorite programs, such as grep, sed, awk, jq and yq
* [hcom](https://github.com/aannoo/hcom) ⭐ 519 | 🐛 37 | 🌐 Rust | 📅 2026-09-13 CLI and TUI for real-time messaging, observation, and orchestration between AI coding agents (Claude Code, Antigravity, Codex, OpenCode, Kilo, Cursor) across terminals
* [models](https://github.com/arimxyer/models) ⭐ 510 | 🐛 0 | 🌐 Rust | 📅 2026-09-25 TUI for browsing AI models and coding agents
* [Froggit](https://github.com/thewizardshell/froggit) ⭐ 485 | 🐛 3 | 🌐 Go | 📅 2026-03-20 Minimalist Git TUI with GitHub CLI integration
* [Feluda](https://github.com/anistark/feluda) ⭐ 477 | 🐛 14 | 🌐 Rust | 📅 2026-09-25 Detect restrictive and incompatible licesenses in all dependencies of your project.
* [qo](https://github.com/kiki-ki/go-qo) ⭐ 397 | 🐛 5 | 🌐 Go | 📅 2026-09-22 Interactive SQL filter for JSON, CSV, TSV and other streams.
* [heretek](https://github.com/wcampbell0x2a/heretek) ⭐ 392 | 🐛 29 | 🌐 Rust | 📅 2026-09-25 GDB TUI Dashboard
* [regex-tui](https://github.com/vitor-mariano/regex-tui) ⭐ 362 | 🐛 1 | 🌐 Go | 📅 2026-04-12 A simple TUI to visualize and test regular expressions
* [chiko](https://github.com/felangga/chiko) ⭐ 356 | 🐛 1 | 🌐 Go | 📅 2026-04-15 The Ultimate Beauty TUI gRPC Client
* [ghcup](https://github.com/haskell/ghcup-hs) ⚠️ Archived An installer for the Haskell toolchain
* [sabiql](https://github.com/riii111/sabiql) ⭐ 310 | 🐛 7 | 🌐 Rust | 📅 2026-09-22 Fast, driverless, Vim-first database TUI with safe editing and ER diagrams.
* [ec](https://github.com/chojs23/ec) ⭐ 304 | 🐛 1 | 🌐 Go | 📅 2026-09-11 A TUI native Git mergetool with 3 panes
* [ggc](https://github.com/bmf-san/ggc) ⭐ 284 | 🐛 0 | 🌐 Go | 📅 2026-09-22 A terminal-based Git CLI tool written in Go
* [pproftui](https://github.com/Oloruntobi1/pproftui) ⭐ 280 | 🐛 2 | 🌐 Go | 📅 2025-07-28 A terminal-based UI for Go's pprof that makes profiling interactive
* [CuTE](https://github.com/PThorpe92/CuTE) ⚠️ Archived TUI to help build, execute and save curl commands, recursively download from remote sources, test your API endpoints, and mange your keys
* [git-crecord](https://github.com/andrewshadura/git-crecord) ⭐ 218 | 🐛 21 | 🌐 Python | 📅 2025-05-23 interactive selective commit tool
* [lazymake](https://github.com/rshelekhov/lazymake) ⭐ 213 | 🐛 4 | 🌐 Go | 📅 2026-05-11 Modern TUI for Makefiles with interactive target selection, dependency visualization, and command safety analysis.
* [cargo-seek](https://github.com/tareqimbasher/cargo-seek) ⭐ 200 | 🐛 6 | 🌐 Rust | 📅 2026-08-12 A TUI for searching, adding and installing cargo crates
* [prs](https://github.com/dhth/prs) ⭐ 184 | 🐛 2 | 🌐 Go | 📅 2026-09-20 Stay updated on PRs without leaving the terminal
* [Twig](https://github.com/workdone0/twig) ⭐ 179 | 🐛 6 | 🌐 Rust | 📅 2026-08-30 Terminal UI for interactively exploring JSON and YAML files.
* [dbee](https://github.com/murat-cileli/dbee) ⭐ 171 | 🐛 3 | 🌐 Go | 📅 2024-06-22 Fast & Minimalistic Database Browser
* [amux](https://github.com/andyrewlee/amux) ⭐ 161 | 🐛 4 | 🌐 Go | 📅 2026-09-24 Easily run parallel coding agents
* [fast-resume](https://github.com/angristan/fast-resume) ⭐ 161 | 🐛 17 | 🌐 Rust | 📅 2026-09-10 Index and fuzzy search coding agent sessions
* [opcilloscope](https://github.com/SquareWaveSystems/opcilloscope) ⭐ 147 | 🐛 1 | 🌐 C# | 📅 2026-07-16 OPC UA client TUI with real-time oscilloscope view for industrial automation
* [git-scope](https://github.com/Bharath-code/git-scope) ⭐ 121 | 🐛 7 | 🌐 Go | 📅 2026-09-25 Terminal UI dashboard for inspecting multiple local Git repositories.
* [Quorum](https://github.com/Detrol/quorum-cli) ⭐ 117 | 🐛 1 | 🌐 Python | 📅 2026-09-25 Multi-agent AI discussion system for structured debates between LLMs
* [gitv](https://github.com/jayanaxhf/gitv) ⭐ 116 | 🐛 12 | 🌐 Rust | 📅 2026-09-24: A beautiful, feature-rich and performant terminal client for GitHub issues.
* [amtui](https://github.com/pehlicd/amtui/) ⭐ 115 | 🐛 4 | 🌐 Go | 📅 2026-06-20 Alertmanager TUI - Your Terminal Companion for Alertmanager
* [pyautogit](https://github.com/jwlodek/pyautogit) ⭐ 112 | 🐛 3 | 🌐 Python | 📅 2020-07-05 A terminal UI for managing git repositories, written using py\_cui
* [ddqa](https://github.com/DataDog/ddqa) ⭐ 109 | 🐛 0 | 🌐 Python | 📅 2026-09-08 Jira TUI to help with software releases
* [ddv](https://github.com/lusingander/ddv) ⭐ 102 | 🐛 3 | 🌐 Rust | 📅 2026-04-29 Terminal DynamoDB viewer
* [gitwig](https://github.com/tareqmy/gitwig) ⭐ 88 | 🐛 0 | 🌐 Rust | 📅 2026-09-25 - A mouse-drivable git TUI and multi-repo dashboard built in Rust.
* [brows](https://github.com/rubysolo/brows) ⭐ 86 | 🐛 0 | 🌐 Go | 📅 2026-06-01 CLI GitHub release browser
* [act3](https://github.com/dhth/act3) ⭐ 82 | 🐛 4 | 🌐 Go | 📅 2026-06-07 Glance at the last 3 runs of your Github Actions
* [csope](https://github.com/agvxov/csope) ⭐ 72 | 🐛 0 | 🌐 C | 📅 2026-08-04 C source code browser based on cscope
* [scope](https://github.com/matheuswhite/scope-rs) ⭐ 69 | 🐛 19 | 🌐 Rust | 📅 2026-09-25 Cross-platform serial-port & RTT monitor with colored timestamped I/O, hex/@tag input macros, search, session recording, auto-reconnect and Lua plugins
* [toolui](https://github.com/jinek/ToolUI) ⭐ 67 | 🐛 2 | 🌐 C# | 📅 2022-10-29 Dotnet core application to manage installed nuget tools
* [sot](https://github.com/anistark/sot) ⭐ 60 | 🐛 7 | 🌐 Python | 📅 2026-09-17 A top like system observability tool written in python
* [ygrep](https://github.com/yetidevworks/ygrep) ⭐ 59 | 🐛 2 | 🌐 Rust | 📅 2026-09-15 A fast, local, indexed code search TUI powered by Tantivy full-text indexing, optimized for AI coding assistants
* [differ](https://github.com/JanSmrcka/differ) ⭐ 57 | 🐛 12 | 🌐 Go | 📅 2026-07-08 A TUI git diff viewer
* [tokui](https://github.com/zdyxry/tokui) ⭐ 54 | 🐛 1 | 🌐 Go | 📅 2026-09-12 An interactive TUI for visualizing code statistics from tokei.
* [qrypad](https://github.com/wheelibin/qrypad) ⭐ 42 | 🐛 0 | 🌐 Go | 📅 2026-09-24 A fast SQL scratchpad for your terminal.
* [cnTUI](https://github.com/fipso/cntui) ⭐ 41 | 🐛 0 | 🌐 Go | 📅 2023-07-14 Replay chrome requests from your terminal using curl
* [logshark](https://github.com/ugosan/logshark) ⭐ 40 | 🐛 0 | 🌐 Go | 📅 2022-12-13 A debugger CLI for JSON logs written in Go
* [vctui](https://github.com/thebsdbox/vctui) ⭐ 38 | 🐛 2 | 🌐 Go | 📅 2020-05-14 Console interface for vCenter
* [deputui](https://github.com/twiddler/deputui) ⭐ 36 | 🐛 4 | 🌐 Rust | 📅 2026-09-21 Review and install NPM package updates
* [y509](https://github.com/kanywst/y509) ⭐ 34 | 🐛 2 | 🌐 Go | 📅 2026-09-24 Inspect X.509 certificate chains, catching the missing intermediates that break curl but not browsers
* [violet](https://github.com/braheezy/violet) ⭐ 31 | 🐛 4 | 🌐 Go | 📅 2026-02-16 Colorful TUI frontend to run Vagrant commands
* [DevProjex](https://github.com/Avazbek22/DevProjex) ⭐ 24 | 🐛 13 | 🌐 C# | 📅 2026-09-24 A cross-platform TUI for exploring project trees, selecting files, previewing AI-ready context, and exporting structured codebase snapshots.
* [burf](https://github.com/razeghi71/burf) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2026-02-02 TUI for Google Cloud Storage (GCS)
* [logradar](https://github.com/nanook72/logradar) ⭐ 20 | 🐛 0 | 🌐 Rust | 📅 2026-02-21 A fast Rust TUI for interactive log filtering and highlighting.
* [nodebro](https://github.com/jonaburg/nodebro) ⭐ 19 | 🐛 0 | 🌐 Go | 📅 2025-10-09 Easily view most recent Github releases/tags and release notes from the terminal
* [sq](https://github.com/sheenazien8/sq) ⭐ 17 | 🐛 0 | 🌐 Go | 📅 2026-02-25 A database client specially made for vim users
* [turbostream](https://github.com/turboline-ai/turbostream) ⭐ 17 | 🐛 0 | 🌐 Go | 📅 2026-02-23 Tool to extract key signals from high-velocity streaming data using AI Agents
* [dbterm](https://github.com/shreyam1008/dbterm) ⭐ 14 | 🐛 0 | 🌐 Go | 📅 2026-09-22 Terminal database workbench for PostgreSQL, MySQL, SQLite, Turso, and Cloudflare D1
* [catalyst](https://github.com/PraveenGongada/catalyst) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2026-05-05 Elegant TUI for triggering GitHub Actions workflows with matrix configurations.
* [kagan](https://github.com/kagan-sh/kagan) ⭐ 11 | 🐛 7 | 🌐 TypeScript | 📅 2026-07-28 AI-powered Kanban TUI for autonomous development workflows
* [Close Mongo Ops Manager](https://github.com/closeio/close-mongo-ops-manager) ⭐ 9 | 🐛 6 | 🌐 Python | 📅 2026-08-25 Monitor and kill MongoDB operations
* [LogLens](https://github.com/Caelrith/loglens-core) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2025-11-21 A structured log viewer and query engine for the terminal.
* [Wikit](https://github.com/BryanCE/wikit) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-11 TUI for managing Wiki.js instances
* [git-tailor](https://github.com/jordfras/git-tailor) ⭐ 4 | 🐛 0 | 🌐 Rust | 📅 2026-09-23 An interactive terminal tool for tidying up Git commits on a branch
* [Cloudeval](https://github.com/ganakailabs/cloudeval-cli) ⭐ 1 | 🐛 8 | 🌐 TypeScript | 📅 2026-09-10 Interactive cloud evaluations and reviews with project context, report views, and chat sessions. Supports Azure and static AWS CloudFormation (beta); requires a Cloudeval account.
* [raygun](https://github.com/yetidevworks/raygun) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-08-04 A terminal receiver for Spatie's Ray debugger, speaking the same HTTP protocol as the desktop app, for PHP, Laravel and Grav
* [lean-tui](https://codeberg.org/wvhulle/lean-tui) Interactive visualization of proofs and programs written in the Lean4 proof-assistant
* [mitmproxy](https://www.mitmproxy.org) A free and open source interactive HTTPS proxy
* [proxymock](https://proxymock.io) A network recorder that shows API payloads in a TUI and automatically generates tests and mocks from what it observes.

***

</details>

<details open><summary><h2>Docker/LXC/K8s</h2></summary>

* [dive](https://github.com/wagoodman/dive) ⭐ 54,607 | 🐛 216 | 🌐 Go | 📅 2025-12-15 A tool for exploring each layer in a docker image
* [lazydocker](https://github.com/jesseduffield/lazydocker) ⭐ 52,954 | 🐛 301 | 🌐 Go | 📅 2026-04-19 The lazier way to manage everything docker
* [k9s](https://github.com/derailed/k9s) ⭐ 34,679 | 🐛 80 | 🌐 Go | 📅 2026-09-25 TUI for managing a Kubernetes cluster
* [ctop](https://github.com/bcicen/ctop) ⭐ 17,841 | 🐛 120 | 🌐 Go | 📅 2024-07-08 Top-like interface for container metrics
* [dockly](https://github.com/lirantal/dockly) ⭐ 4,033 | 🐛 5 | 🌐 JavaScript | 📅 2026-07-23 Immersive terminal interface for managing docker containers and services
* [dry](https://github.com/moncho/dry) ⭐ 3,280 | 🐛 27 | 🌐 Go | 📅 2026-09-04 A Docker manager for the terminal
* [kdash](https://github.com/kdash-rs/kdash) ⭐ 2,541 | 🐛 4 | 🌐 Rust | 📅 2026-09-24 A simple and fast dashboard for Kubernetes
* [oxker](https://github.com/mrjackwills/oxker) ⭐ 1,860 | 🐛 23 | 🌐 Rust | 📅 2026-08-22 A simple tui to view & control docker containers
* [eks-node-viewer](https://github.com/awslabs/eks-node-viewer/) ⭐ 1,643 | 🐛 26 | 🌐 Go | 📅 2026-09-21 visualizing dynamic node usage within a kubernetes cluster
* [kftui](https://github.com/hcavarsan/kftray) ⭐ 1,563 | 🐛 4 | 🌐 Rust | 📅 2026-09-25 A TUI to manage multiple kubectl port-forward commands, with support for UDP and K8s proxy.
* [dtop](https://github.com/amir20/dtop) ⭐ 1,432 | 🐛 2 | 🌐 Rust | 📅 2026-09-24 Terminal dashboard for Docker monitoring across multiple hosts
* [Podman-tui](https://github.com/containers/podman-tui) ⭐ 1,238 | 🐛 13 | 🌐 Go | 📅 2026-09-18 TUI for Podman containers
* [ktop](https://github.com/vladimirvivien/ktop) ⭐ 1,110 | 🐛 11 | 🌐 Go | 📅 2026-07-03 A top-like tool for your Kubernetes clusters
* [sen](https://github.com/TomasTomecek/sen) ⭐ 1,049 | 🐛 35 | 🌐 Python | 📅 2025-08-12 Terminal User Interface for docker engine
* [ducker](https://github.com/robertpsoane/ducker) ⭐ 932 | 🐛 15 | 🌐 Rust | 📅 2026-08-03 A slightly quackers Docker TUI based on k9s
* [e1s](https://github.com/keidarcy/e1s) ⭐ 930 | 🐛 2 | 🌐 Go | 📅 2026-09-07 TUI for managing AWS ECS resources
* [Argonaut](https://github.com/darksworm/argonaut) ⭐ 455 | 🐛 11 | 🌐 Go | 📅 2026-09-24 ArgoCD TUI
* [kubetui](https://github.com/sarub0b0/kubetui) ⭐ 396 | 🐛 12 | 🌐 Rust | 📅 2026-09-25 A TUI tool designed for monitoring Kubernetes resources.
* [lazycontainer](https://github.com/andreybleme/lazycontainer) ⭐ 372 | 🐛 8 | 🌐 Go | 📅 2026-08-17 TUI for managing Apple containers
* [DockMate](https://github.com/shubh-io/dockmate) ⭐ 339 | 🐛 3 | 🌐 Go | 📅 2026-04-06 A lightweight TUI manager for Docker and Podman
* [lazytrivy](https://github.com/owenrumney/lazytrivy) ⭐ 329 | 🐛 9 | 🌐 Go | 📅 2026-09-25 The lazier way to scan images, k8s and the filesytem with Trivy
* [talos-pilot](https://github.com/handfish/talos-pilot) ⭐ 247 | 🐛 1 | 🌐 Rust | 📅 2026-07-24 TUI for Talos Linux providing real-time node monitoring, log streaming, and various diagnostics
* [Pocker](https://github.com/pommee/Pocker) ⭐ 191 | 🐛 2 | 🌐 Python | 📅 2025-03-16 TUI based application for docker related tasks.
* [cruise](https://github.com/cruise-org/cruise) ⭐ 184 | 🐛 19 | 🌐 Go | 📅 2026-07-09 A container management TUI
* [d4s](https://github.com/jr-k/d4s) ⭐ 132 | 🐛 0 | 🌐 Go | 📅 2026-09-12 A fast, keyboard-driven terminal UI to manage Docker containers, Compose stacks, and Swarm services with the ergonomics of K9s
* [dprs](https://github.com/durableprogramming/dprs) ⭐ 42 | 🐛 0 | 🌐 Rust | 📅 2026-07-27 A TUI for managing Docker containers with real-time monitoring and log streaming
* [etcd-walker](https://github.com/nexusriot/etcd-walker/) ⭐ 26 | 🐛 0 | 🌐 Go | 📅 2026-09-12 Opensource TUI tool for managing etcd keys
* [docker-dash](https://github.com/GustavoCaso/docker-dash) ⭐ 24 | 🐛 29 | 🌐 Go | 📅 2026-09-25 A full TUI managemnet tool for Docker
* [SwarmCLI](https://github.com/Eldara-Tech/swarmcli) ⭐ 21 | 🐛 20 | 🌐 Go | 📅 2026-09-24 Swarm Management at the speed of thought — with real-time log streaming, instant shell access to containers, seamless port forwarding, and on-demand secret reveal capabilities, giving you full control over your Docker Swarm without breaking your flow.
* [k8s-tui](https://github.com/otavioCosta2110/k8s-tui) ⭐ 14 | 🐛 1 | 🌐 Go | 📅 2025-11-19 TUI Kubernetes resource manager with multi-cluster support
* [dockup](https://github.com/paulo-amaral/dockup) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2026-09-22 One-command TUI to install, harden and maintain Docker, Podman, NVIDIA toolkit and Apple container

***

</details>

<details open><summary><h2>Editors</h2></summary>

* [micro](https://github.com/zyedidia/micro) ⭐ 29,641 | 🐛 916 | 🌐 Go | 📅 2026-09-25 A modern and intuitive terminal-based text editor
* [Edit](https://github.com/microsoft/edit) ⭐ 14,625 | 🐛 167 | 🌐 Rust | 📅 2026-09-23 A simple text editor. Pays homage to the classic MS-DOS Editor.
* [kilo](https://github.com/antirez/kilo) ⭐ 9,143 | 🐛 64 | 🌐 C | 📅 2025-01-04 A minimal but complete editor in \~1000 lines of C code.
* [Fresh](https://github.com/sinelaw/fresh) ⭐ 9,033 | 🐛 369 | 🌐 Rust | 📅 2026-09-25 An easy-to-use, powerful and fast terminal-based text editor.
* [slap](https://github.com/slap-editor/slap) ⭐ 6,188 | 🐛 115 | 🌐 JavaScript | 📅 2021-11-01 Sublime-like terminal-based text editor
* [vis](https://github.com/martanne/vis) ⭐ 4,731 | 🐛 153 | 🌐 C | 📅 2026-09-23 A vi-like editor based on Plan 9's structural regular expressions
* [amp](https://github.com/jmacdonald/amp) ⭐ 4,128 | 🐛 95 | 🌐 Rust | 📅 2026-06-10 A complete text editor for your terminal
* [frogmouth](https://github.com/Textualize/frogmouth) ⭐ 3,297 | 🐛 46 | 🌐 Python | 📅 2024-08-01 A Markdown browser for your terminal
* [flow-control](https://github.com/neurocyte/flow) ⭐ 2,437 | 🐛 79 | 🌐 Zig | 📅 2026-09-25 A lightning-fast, feature-rich text editor written in Zig
* [Durdraw](https://github.com/cmang/durdraw) ⭐ 1,828 | 🐛 7 | 🌐 Python | 📅 2026-09-24 An ASCII, Unicode and ANSI art editor
* [zee](https://github.com/zee-editor/zee) ⭐ 1,806 | 🐛 44 | 🌐 Rust | 📅 2025-02-06 A modern text editor for the terminal written in Rust
* [orbiton](https://github.com/xyproto/orbiton) ⭐ 704 | 🐛 0 | 🌐 Go | 📅 2026-09-25 Text editor limited by VT100, suitable for programming, writing git commit messages and editing Markdown
* [treemd](https://github.com/Epistates/treemd) ⭐ 694 | 🐛 1 | 🌐 Rust | 📅 2026-09-23 A markdown navigator with tree-based structural navigation
* [turbo](https://github.com/magiblot/turbo) ⭐ 683 | 🐛 38 | 🌐 C++ | 📅 2026-08-28 An experimental text editor for the terminal, based on Scintilla and Turbo Vision
* [tilde](https://github.com/gphalkes/tilde) ⭐ 556 | 🐛 65 | 🌐 C++ | 📅 2026-06-10 Intuitive text editor for the terminal
* [PNANA](https://github.com/Cyxuan0311/PNANA) ⭐ 323 | 🐛 14 | 🌐 C++ | 📅 2026-09-13 A modern terminal text editor built with FTXUI, inspired by Nano, Micro, and Sublime Text.
* [C-Edit](https://github.com/velorek1/c-edit) ⭐ 302 | 🐛 5 | 🌐 C | 📅 2026-01-29 A text editor with drop down menus in the style of MS-DOS Editor
* [nino](https://github.com/evanlin96069/nino) ⭐ 101 | 🐛 9 | 🌐 C | 📅 2026-09-15 A small terminal-based text editor written in C.
* [lazyide](https://github.com/TysonLabs/lazyide) ⭐ 94 | 🐛 3 | 🌐 Rust | 📅 2026-09-18 A lightweight terminal IDE in Rust: file tree, tabs, split panes, LSP, git diff view, minimap, 32 themes
* [markln](https://github.com/xqtr/markln) ⭐ 63 | 🐛 6 | 🌐 Python | 📅 2026-04-05 A terminal-based markdown editor built with Textual.
* [microNeo](https://github.com/sollawen/microNeo) ⭐ 56 | 🐛 4 | 🌐 Go | 📅 2026-08-17 A fork of Micro with in-place Markdown rendering — view and edit in the same window
* [thymus](https://github.com/blademd/thymus) ⭐ 27 | 🐛 0 | 🌐 Python | 📅 2024-06-04 An interactive browser & editor for network configuration files.
* [suplemon](https://github.com/leancode/suplemon) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2026-09-13 Text editor with multiple cursors, in the style of Sublime Text
* [helix](https://helix-editor.com/) A post-modern text editor.
* [hexed](https://codeberg.org/quorend/hexed) (Yet another) hex editor.
* [kakoune](http://kakoune.org/) A modern, modal text editor with focus on interactivity and efficiency
* [maki](https://sr.ht/~bscit/maki/) A simple tabbed text editor with file navigation and an emphasis on preserving battery life

***

</details>

<details open><summary><h2>File Managers</h2></summary>

* [yazi](https://github.com/sxyazi/yazi) ⭐ 42,431 | 🐛 64 | 🌐 Rust | 📅 2026-09-21 Blazing fast terminal file manager written in Rust, based on async I/O.
* [superfile](https://github.com/MHNightCat/superfile) ⭐ 23,378 | 🐛 271 | 🌐 Go | 📅 2026-09-24 Pretty fancy and modern terminal file manager.
* [nnn](https://github.com/jarun/nnn) ⭐ 22,011 | 🐛 1 | 🌐 C | 📅 2026-09-21 n³ The unorthodox terminal file manager.
* [ranger](https://github.com/ranger/ranger) ⭐ 17,413 | 🐛 897 | 🌐 Python | 📅 2026-09-09 A VIM-inspired file manager for the console.
* [broot](https://github.com/Canop/broot) ⭐ 12,964 | 🐛 101 | 🌐 Rust | 📅 2026-09-23 A new way to see and navigate directory trees
* [lf](https://github.com/gokcehan/lf) ⭐ 9,519 | 🐛 85 | 🌐 Go | 📅 2026-09-15 A terminal file manager written in Go with heavy inspiration from ranger file manager.
* [Vifm](https://github.com/vifm/vifm) ⭐ 3,275 | 🐛 146 | 🌐 C | 📅 2026-09-07 A TUI file manager with vi-keybindings and other vim like behaviour.
* [far2l](https://github.com/elfmz/far2l) ⭐ 2,219 | 🐛 483 | 🌐 C++ | 📅 2026-09-08 Linux port of Far v2 file manager
* [mc](https://github.com/MidnightCommander/mc) ⭐ 993 | 🐛 696 | 🌐 C | 📅 2026-09-24 GNU Midnight Commander. A free cross-platform orthodox file manager.
* [TUIFIManager](https://github.com/GiorgosXou/TUIFIManager) ⭐ 828 | 🐛 15 | 🌐 Python | 📅 2026-06-30 A cross-platform terminal-based file manager *(supports termux)*.
* [rovr](https://github.com/NSPC911/rovr) ⭐ 411 | 🐛 8 | 🌐 Python | 📅 2026-09-25 A post-modern terminal file manager.
* [goful](https://github.com/anmitsu/goful) ⭐ 380 | 🐛 4 | 🌐 Go | 📅 2021-11-29 a powerful TUI file manager written in Go.
* [sfm](https://github.com/afify/sfm) ⭐ 262 | 🐛 6 | 🌐 C | 📅 2025-11-14 Simple file manager.
* [deletor](https://github.com/pashkov256/deletor) ⭐ 256 | 🐛 11 | 🌐 Go | 📅 2026-04-04 Manage and delete files efficiently with an interactive TUI and scriptable CLI.
* [adbtuifm](https://github.com/darkhz/adbtuifm) ⭐ 190 | 🐛 3 | 🌐 Go | 📅 2022-03-16 A TUI file manager for Android, based on the Android Debug Bridge(ADB).
* [fml](https://github.com/wick3dr0se/fml) ⭐ 107 | 🐛 0 | 🌐 Shell | 📅 2024-02-03 :file\_folder: A stupid simple, fast file manager written in BASH v4.2+.
* [ytreenova](https://github.com/robkam/ytreenova) ⭐ 15 | 🐛 0 | 🌐 C | 📅 2026-09-19 The XTree™ style file manager Unix should have had all along.
* [fyzenor](https://github.com/Bimbok/fyzenor) ⭐ 14 | 🐛 7 | 🌐 C++ | 📅 2026-09-24 A modern, blazing-fast terminal file manager built in C++ with live previews, async workflows, and a polished three-column interface.
* [FileView](https://github.com/Hiro-Chiba/fileview) ⭐ 10 | 🐛 0 | 🌐 Rust | 📅 2026-09-11 A terminal file browser with image previews, Git status, search, and an MCP server.
* [s3duck-tui](https://github.com/nexusriot/s3duck-tui) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2026-09-13 A TUI S3 client.
* [ntc](https://codeberg.org/ItsZariep/ntc) Ncurses Tabbed file Chooser.

***

</details>

<details open><summary><h2>Games</h2></summary>

* [NetHack](https://github.com/NetHack/NetHack) ⭐ 3,923 | 🐛 151 | 🌐 C | 📅 2026-09-25 Dungeon exploration game
* [tinytetris](https://github.com/taylorconor/tinytetris) ⭐ 3,289 | 🐛 29 | 🌐 C++ | 📅 2024-07-09 80x23 terminal tetris!
* [pokete](https://github.com/lxgr-linux/pokete) ⭐ 3,159 | 🐛 30 | 🌐 Python | 📅 2026-05-22 A terminal based Pokemon like game
* [sshtron](https://github.com/zachlatta/sshtron) ⭐ 2,497 | 🐛 12 | 🌐 Go | 📅 2023-07-17 multiplayer lightcycle game that runs through SSH
* [awkaster](https://github.com/TheMozg/awk-raycaster) ⭐ 2,474 | 🐛 1 | 🌐 Awk | 📅 2023-01-20 Pseudo-3D shooter written completely in gawk using raycasting technique
* [Gameboy Emulator](https://github.com/gabrielrcouto/php-terminal-gameboy-emulator) ⭐ 1,612 | 🐛 6 | 🌐 PHP | 📅 2020-11-02 A PHP Terminal GameBoy Emulator
* [GitType](https://github.com/unhappychoice/gittype) ⭐ 1,610 | 🐛 16 | 🌐 Rust | 📅 2026-09-23 A CLI code-typing game that turns your source code into typing challenges
* [BrogueCE](https://github.com/tmewett/BrogueCE) ⭐ 1,475 | 🐛 201 | 🌐 C | 📅 2026-09-20 Beautiful roguelike dungeon crawler
* [chess-tui](https://github.com/thomas-mauran/chess-tui) ⭐ 1,186 | 🐛 36 | 🌐 Rust | 📅 2026-09-24 Play Chess in your terminal, built in rust
* [steam-tui](https://github.com/dmadisetti/steam-tui) ⭐ 1,037 | 🐛 9 | 🌐 Rust | 📅 2026-03-12 Just a simple TUI client for steamcmd. Allows for the graphical launching, updating, and downloading of steam games through a simple terminal client.
* [Square Tic Tac Toe](https://github.com/learnbyexample/TUI-apps/tree/main/SquareTicTacToe) ⭐ 1,016 | 🐛 0 | 🌐 Python | 📅 2026-02-02 Like Tic Tac Toe, but form a square with 4 corners instead of a line
* [DOOM-ASCII](https://github.com/wojciech-graj/doom-ascii) ⭐ 883 | 🐛 0 | 🌐 C | 📅 2026-09-11 Text-based DOOM running in terminal.
* [tetro-tui](https://github.com/Strophox/tetro-tui) ⭐ 760 | 🐛 6 | 🌐 Rust | 📅 2026-08-13 A very configurable tetris-like, featuring ASCII particles, replays and more.
* [Rebels in the sky](https://github.com/ricott1/rebels-in-the-sky) ⭐ 741 | 🐛 6 | 🌐 Rust | 📅 2026-09-25 P2P terminal game about spacepirates playing basketball across the galaxy.
* [clidle](https://github.com/ajeetdsouza/clidle) ⭐ 633 | 🐛 2 | 🌐 Go | 📅 2025-03-28 Play Wordle in your terminal. Also works over SSH!
* [botany](https://github.com/jifunks/botany/) ⭐ 550 | 🐛 10 | 🌐 Python | 📅 2026-07-18 Virtual plant buddy
* [nudoku](https://github.com/jubalh/nudoku) ⭐ 374 | 🐛 2 | 🌐 C | 📅 2026-07-08 ncurses based sudoku game
* [tty-solitaire](https://github.com/mpereira/tty-solitaire) ⭐ 362 | 🐛 24 | 🌐 C | 📅 2025-05-03 Solitaire runs in your terminal!
* [bastet](https://github.com/fph/bastet) ⭐ 320 | 🐛 13 | 🌐 C++ | 📅 2022-10-08 Evil falling block game
* [cli-chess](https://github.com/trevorbayless/cli-chess) ⭐ 305 | 🐛 17 | 🌐 Python | 📅 2026-08-30 A highly customizable way to play chess in your terminal. Play online (via Lichess.org) and offline against the Fairy-Stockfish engine. All Lichess variants are supported.
* [minesweep-rs](https://github.com/cpcloud/minesweep-rs) ⚠️ Archived A mine sweeping game written in Rust using tui-rs.
* [sssnake](https://github.com/AngelJumbo/sssnake) ⭐ 234 | 🐛 0 | 🌐 C | 📅 2026-07-31 The classic snake game for the terminal that can play itself and be used like a screensaver.
* [nSnake](https://github.com/alexdantas/nSnake) ⭐ 229 | 🐛 23 | 🌐 C++ | 📅 2023-09-27 The classic snake game with textual interface
* [balatrotui](https://github.com/Passeriform/BalatroTUI) ⭐ 204 | 🐛 5 | 🌐 Rust | 📅 2026-05-01 A TUI clone of Balatro
* [Micro Tetris](https://github.com/troglobit/tetris) ⭐ 173 | 🐛 1 | 🌐 C | 📅 2025-06-22 One of the smallest Tetris implementations in the world, utilizing only ANSI escape sequences to draw the board.
* [go-life](https://github.com/sachaos/go-life) ⭐ 147 | 🐛 5 | 🌐 Go | 📅 2024-12-29 Terminal based Conway's Game of Life
* [ssHattrick](https://github.com/ricott1/sshattrick) ⭐ 146 | 🐛 2 | 🌐 Rust | 📅 2026-05-30 Play Hattrick in your terminal over SSH.
* [Maze](https://github.com/itchyny/maze) ⭐ 131 | 🐛 0 | 🌐 Go | 📅 2024-03-23 Simple maze game written in Go.
* [csol](https://github.com/nielssp/csol) ⭐ 116 | 🐛 0 | 🌐 C | 📅 2025-07-19 Collection of solitaire/patience games, such as Klondike, FreeCell, Spider, and Yukon
* [snake](https://github.com/wick3dr0se/snake) ⭐ 114 | 🐛 2 | 🌐 Shell | 📅 2023-06-17 :video\_game: A super minimal TUI snake game written in pure BASH v5.1+
* [moon-buggy](https://github.com/seehuhn/moon-buggy) ⭐ 111 | 🐛 7 | 🌐 C | 📅 2025-11-17 Drive some car across the moon
* [Maze TUI](https://github.com/agl-alexglopez/maze-tui) ⭐ 83 | 🐛 0 | 🌐 Rust | 📅 2025-10-24 Build mazes and solve them with various algorithms.
* [typing-game-cli](https://github.com/akgondber/typing-game-cli) ⭐ 64 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-06 Command line game to practice your typing speed by competing against typer-robot or against your best result
* [termrex](https://github.com/SATYADAHAL/termrex) ⭐ 50 | 🐛 1 | 🌐 C++ | 📅 2026-02-22 A terminal-based endless runner game inspired by the Chrome Dino offline game.
* [Micro Snake](https://github.com/troglobit/snake) ⭐ 38 | 🐛 1 | 🌐 C | 📅 2023-04-16 A small snake game, utilizing ANSI escape sequences to draw the board.
* [terminal-pong](https://github.com/IshmamR/terminal.pong) ⭐ 36 | 🐛 0 | 🌐 Rust | 📅 2025-07-09 A simple, fun ping pong game playable entirely in your terminal.
* [sudoku-rs](https://github.com/MitchelPaulin/sudoku-rs) ⭐ 33 | 🐛 0 | 🌐 Rust | 📅 2024-08-17 Sudoku built with tui-rs
* [typeinc](https://github.com/AnirudhG07/Typeinc) ⭐ 33 | 🐛 0 | 🌐 Python | 📅 2025-06-28 ncurses based typing speed test with various difficulty levels.
* [Zigtris](https://github.com/ringtailsoftware/zigtris) ⭐ 33 | 🐛 0 | 🌐 Zig | 📅 2025-12-17 YA terminal tetris
* [brickgame-4bit](https://github.com/ilyakurdyukov/brickgame-4bit) ⭐ 29 | 🐛 1 | 🌐 C | 📅 2024-05-11 Brick Game emulator (4-bit Holtek chip)
* [minesweeper\_4d\_rs](https://github.com/itabesamesa/minesweeper_4d_rs) ⭐ 21 | 🐛 0 | 🌐 Rust | 📅 2026-01-25 4D minesweeper written in Rust using Ratatui (can also be used for classic minesweeper)
* [nchess](https://github.com/billyvinning/nchess) ⭐ 21 | 🐛 0 | 🌐 C | 📅 2023-05-03 Chess in the terminal, written in C.
* [LeTrain](https://github.com/antoniovazquezaraujo/LeTrain) ⭐ 19 | 🐛 40 | 🌐 Java | 📅 2026-09-25 - Open-source procedural train simulator using Java 17, LibGDX and Lanterna.
* [Zoridor](https://github.com/ringtailsoftware/zoridor) ⭐ 16 | 🐛 0 | 🌐 Zig | 📅 2025-01-17 Play Quoridor in the terminal
* [onx](https://github.com/vyalovvldmr/onx) ⭐ 15 | 🐛 4 | 🌐 Python | 📅 2022-10-06 Noughts & Crosses client-server game with your partner. Based on textual and python.
* [gokemon](https://github.com/nathanieltooley/gokemon) ⭐ 12 | 🐛 12 | 🌐 Go | 📅 2025-10-31 A terminal based Pokemon battle simulator
* [UniPac](https://github.com/jesper-olsen/UniPac) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2026-07-22 Unicode-powered Pac-Man for the terminal, written in Rust.
* [sweeper](https://github.com/igor47/sweeper) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-04-30 Minesweeper game using curtsies
* [tui-2048](https://github.com/ps06756/tui-2048) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-01-03 The game 2048 for your terminal
* [Wordle](https://github.com/m-dango/raku-wordle/) ⭐ 2 | 🐛 2 | 🌐 Raku | 📅 2022-03-19 Script and library for Wordle, written in Raku
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

* [Rich](https://github.com/willmcgugan/rich) ⭐ 57,439 | 🐛 381 | 🌐 Python | 📅 2026-06-23 is a **Python** library for rich text and beautiful formatting in the terminal.
* [textual](https://github.com/willmcgugan/textual) ⭐ 37,333 | 🐛 358 | 🌐 Python | 📅 2026-07-11 is a TUI (Text User Interface) framework for **Python** inspired by modern web development.
* [Python Prompt Toolkit](https://github.com/prompt-toolkit/python-prompt-toolkit) ⭐ 10,587 | 🐛 724 | 🌐 Python | 📅 2026-07-26 Library for building powerful interactive command line applications in **Python**
* [notcurses](https://github.com/dankamongmen/notcurses) ⭐ 4,715 | 🐛 329 | 🌐 C | 📅 2026-05-18 blingful character graphics/TUI library for **C** and **Python**. definitely not curses.
* [urwid](https://github.com/urwid/urwid) ⭐ 3,021 | 🐛 119 | 🌐 Python | 📅 2026-09-23 A console user interface library for **Python** on Linux, OSX, Cygwin or other unix-like OS.
* [pytermgui](https://github.com/bczsalba/pytermgui) ⚠️ Archived A simple yet powerful TUI framework for your **Python** (3.7+) applications.
* [blessed](https://github.com/jquast/blessed) ⭐ 1,505 | 🐛 2 | 🌐 Python | 📅 2026-09-24 Blessed is an easy, practical library for making **Python** terminal apps
* [blessings](https://github.com/erikrose/blessings) ⭐ 1,488 | 🐛 32 | 🌐 Python | 📅 2025-08-28 A **Python** wrapper lib for ncurses that makes your code pretty to look at
* [pyTermTk](https://github.com/ceccopierangiolieugenio/pyTermTk) ⭐ 918 | 🐛 55 | 🌐 Python | 📅 2026-09-23 self-contained TUI library for **Python** with a QT-like API semantics
* [py\_cui](https://github.com/jwlodek/py_cui) ⭐ 789 | 🐛 48 | 🌐 Python | 📅 2026-03-27 **Python** library aimed at making widget based TUI/CUI interfaces as simple as possible. Supports standard widgets and popups like menus, textboxes, forms, file explorers etc.
* [UniCurses](https://github.com/unicurses/unicurses) ⭐ 174 | 🐛 8 | 🌐 Python | 📅 2026-07-30 A **Python** module that is aimed at providing the Curses functionality on all operating systems.
* [Argenta](https://github.com/koloideal/Argenta) ⭐ 32 | 🐛 1 | 🌐 Python | 📅 2026-09-18 Library for building modular applications **Python**
* [Vindauga](https://github.com/gabbpuy/vindauga) ⭐ 18 | 🐛 1 | 🌐 Python | 📅 2026-08-20 A **Python** implementation of the BSD licensed C++ Turbo Vision library.
* [xnano](https://github.com/hsaeed3/xnano) ⭐ 18 | 🐛 6 | 🌐 Python | 📅 2026-09-17 A modern, lightweight and declarative **Python** TUI framework built on top of the Rust ratatui and tachyonfx libraries. ([docs](https://xnano.hammad.app))
* [animpy](https://github.com/13DoesPython/animpy) ⭐ 4 | 🐛 0 | 🌐 HTML | 📅 2026-09-12 - Terminal animations in **Python** without the pain.

<h3>GO</h3>

* [bubbletea](https://github.com/charmbracelet/bubbletea) ⭐ 45,124 | 🐛 231 | 🌐 Go | 📅 2026-09-24 A **Go** framework based on Elm to build functional and fun terminal apps
* [tview](https://github.com/rivo/tview/) ⭐ 14,114 | 🐛 97 | 🌐 Go | 📅 2026-08-11 Terminal UI library with rich, interactive widgets — written in **Go**
* [gocui](https://github.com/jroimartin/gocui) ⭐ 10,611 | 🐛 59 | 🌐 Go | 📅 2025-05-01 Minimalist **Go** package aimed at creating Console User Interfaces
* [pterm](https://github.com/pterm/pterm/) ⭐ 5,542 | 🐛 87 | 🌐 Go | 📅 2026-07-11 A modern **Go** module to beautify console output. Featuring charts, progressbars, tables, trees, and much more! It's completely configurable and 100% cross-platform compatible.
* [tcell](https://github.com/gdamore/tcell) ⭐ 5,223 | 🐛 8 | 🌐 Go | 📅 2026-09-24 Tcell is an alternate **Go** terminal package, similar in some ways to termbox, but better in others.
* [tui-go](https://github.com/marcusolsson/tui-go) ⚠️ Archived A **Go** UI library for terminal applications (deprecated)
* [stickers](https://github.com/76creates/stickers) ⭐ 401 | 🐛 3 | 🌐 Go | 📅 2026-04-28 Building blocks for charmbracelet/lipgloss in **Go**

<h3>C</h3>

* [libuv](https://github.com/libuv/libuv) ⭐ 27,199 | 🐛 246 | 🌐 C | 📅 2026-09-25 Cross-platform asynchronous I/O library - written in **C**
* [tuibox](https://github.com/Cubified/tuibox) ⭐ 334 | 🐛 4 | 🌐 C | 📅 2023-12-01 A single-header **C** terminal UI library, capable of creating mouse-driven, interactive applications on the command line.
* [AnbUI](https://github.com/oerg866/anbui) ⭐ 38 | 🐛 3 | 🌐 C | 📅 2026-04-10 A minimal Text UI Library in **C**
* [ncurses](https://invisible-island.net/ncurses/announce.html) A classic **C** library with bindings for many languages

<h3>C++</h3>

* [FTXUI](https://github.com/ArthurSonzogni/FTXUI) ⭐ 10,730 | 🐛 52 | 🌐 C++ | 📅 2026-09-24 💻 **C++** Functional Terminal User Interface. ❤️
* [imtui](https://github.com/ggerganov/imtui) ⭐ 3,628 | 🐛 21 | 🌐 C++ | 📅 2025-10-10 An immediate mode text-based user interface **C++** library, supporting 256 ANSI colors and mouse/keyboard input.
* [tvision](https://github.com/magiblot/tvision) ⭐ 3,169 | 🐛 45 | 🌐 C++ | 📅 2026-09-18 A modern port of **C++** Turbo Vision 2.0, cross-platform and Unicode support.
* [uvw](https://github.com/skypjack/uvw) ⭐ 2,057 | 🐛 13 | 🌐 C++ | 📅 2025-12-17 Header-only, event based, tiny and easy to use libuv wrapper in modern **C++**
  now available as also shared/static library!
* [rang](https://github.com/agauniyal/rang) ⭐ 1,594 | 🐛 26 | 🌐 C++ | 📅 2026-05-16 A Minimal, Header only Modern **C++** library for terminal goodies.
* [FINAL CUT](https://github.com/gansm/finalcut) ⭐ 1,203 | 🐛 12 | 🌐 C++ | 📅 2026-09-23 **C++** library for creating terminal applications with text-based widgets
* [xtd](https://github.com/gammasoft71/xtd) ⭐ 1,165 | 🐛 98 | 🌐 C++ | 📅 2026-09-25 Free open-source modern **C++** framework to create console (CLI), forms (GUI like WinForms) and unit test (xUnit) applications and libraries on Windows, macOS, Linux, iOS, Android, FreeBSD, and Haiku.
* [ConsoleCraftEngine](https://github.com/ural89/ConsoleCraftEngine) ⭐ 97 | 🐛 2 | 🌐 C++ | 📅 2026-09-03 A terminal-based 2D game engine written in **C++**.
* [termdb](https://github.com/agauniyal/termdb) ⭐ 47 | 🐛 2 | 🌐 C++ | 📅 2018-05-11 Terminfo parser for modern **C++**
* [Tui Widgets](https://github.com/tuiwidgets/tuiwidgets) ⭐ 29 | 🐛 4 | 🌐 C++ | 📅 2026-09-15 A high-level widget based toolkit for terminal applications in **C++**
* [GGUI](https://github.com/Gabidal/GGUI) ⭐ 9 | 🐛 2 | 🌐 C++ | 📅 2026-09-15 **C++17** Structured Terminal User Interface. 🐧/🪟
* [ASCII\_Board\_Game\_Engine](https://github.com/tjunruh/ASCII_Board_Game_Engine) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2026-09-08 A graphics engine for making board games in **C++**

<h3>Java</h3>

* [Lanterna](https://github.com/mabe02/lanterna) ⭐ 2,621 | 🐛 96 | 🌐 Java | 📅 2026-07-07 A **Java** library for creating text-based UIs, very similar to the C library curses but with more functionality.
* [TUI4J](https://github.com/WilliamAGH/tui4j) ⭐ 126 | 🐛 1 | 🌐 Java | 📅 2026-08-14 A **Java** terminal UI framework with a Bubble Tea (Go) port and additional features inspired by Textual.
* [casciian](https://github.com/crramirez/casciian) ⭐ 52 | 🐛 1 | 🌐 Java | 📅 2026-09-24 A Text User Interface Library for **Java** based on "Jexer" without the AWT/Swing dependencies, tailored for GraalVM AOT native compilation with a focus on performance over remote connections and maximum terminal compatibility.
* [Jexer](https://gitlab.com/AutumnMeowMeow/jexer) A **Java** library implements a text-based windowing system loosely reminiscent of Borland's Turbo Vision system.

<h3>.NET</h3>

* [Spectre.Console](https://github.com/spectreconsole/spectre.console) ⭐ 11,635 | 🐛 185 | 🌐 C# | 📅 2026-09-24 A **.NET** library for creating beautiful console applications
* [Terminal.Gui](https://github.com/gui-cs/Terminal.Gui) ⭐ 11,226 | 🐛 49 | 🌐 C# | 📅 2026-09-25 Cross-platform terminal UI toolkit for **.NET**
* [Consolonia](https://github.com/jinek/Consolonia) ⭐ 830 | 🐛 51 | 🌐 C# | 📅 2026-09-13 A **.NET** terminal-based GUI framework with support of XAML
* [SharpConsoleUI](https://github.com/nickprotop/ConsoleEx) ⭐ 277 | 🐛 7 | 🌐 C# | 📅 2026-09-25 Multi-window TUI framework for **.NET** with overlapping windows, compositor effects, and Spectre.Console integration
* [Hex1b](https://github.com/mitchdenny/hex1b) ⭐ 175 | 🐛 123 | 🌐 C# | 📅 2026-09-25 A **.NET** library for building rich, interactive TUIs with a React-inspired declarative API
* [Elaris.UI](https://github.com/ambystechcom/Ambystech.Elaris.UI) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2026-04-20 A lightweight Terminal UI library for **.NET** with true 24-bit RGB color support. Built for modern terminals with cross-platform support.

<h3>Rust</h3>

* [Ratatui](https://github.com/tui-rs-revival/ratatui) ⭐ 22,744 | 🐛 210 | 🌐 Rust | 📅 2026-09-25 A **Rust** crate for building Terminal UIs (actively maintained fork of tui-rs).
* [tui-rs](https://github.com/fdehau/tui-rs) ⚠️ Archived Terminal user interfaces and dashboards using **Rust** (no longer maintained, use Ratatui instead).
* [iocraft](https://github.com/ccbrown/iocraft) ⭐ 1,547 | 🐛 26 | 🌐 Rust | 📅 2026-09-07 **Rust** crate for beautiful, artisanally crafted TUIs and text-based IO, with a declarative, React-like API inspired by Ink.
* [tui-input](https://github.com/sayanarijit/tui-input) ⭐ 204 | 🐛 3 | 🌐 Rust | 📅 2026-08-10 TUI input library supporting multiple backends, tui-rs and ratatui in **Rust**
* [Zaz](https://github.com/raphamorim/zaz) ⚠️ Archived A **Rust** TUI library for efficient terminal rendering.

<h3>Other</h3>

* [ink](https://github.com/vadimdemedes/ink) ⭐ 39,946 | 🐛 35 | 🌐 TypeScript | 📅 2026-09-21 React for **Node.js** interactive command-line apps
* [gum](https://github.com/charmbracelet/gum) ⭐ 24,424 | 🐛 211 | 🌐 Go | 📅 2026-09-24 A tool for glamorous **shell** scripts
* [OpenTUI](https://github.com/sst/opentui) ⭐ 13,392 | 🐛 150 | 🌐 TypeScript | 📅 2026-09-25 A **TypeScript** library for building terminal user interfaces (TUIs)
* [blessed](https://github.com/chjj/blessed) ⭐ 11,888 | 🐛 255 | 🌐 JavaScript | 📅 2024-03-22 A high-level terminal interface library for **Node.js**
  stateful TUI apps.
* [termbox2](https://github.com/termbox/termbox2) ⭐ 773 | 🐛 18 | 🌐 C | 📅 2026-09-03 A terminal rendering library for creating TUIs.
* [php-tui](https://github.com/php-tui/php-tui) ⭐ 618 | 🐛 16 | 🌐 PHP | 📅 2026-05-04 comprehensive TUI library for **PHP** based heavily on Ratatui.
* [nimwave](https://github.com/ansiwave/nimwave) ⭐ 547 | 🐛 2 | 🌐 Nim | 📅 2023-09-29 Build text interfaces for the terminal or browser in **Nim**
* [TermGL](https://github.com/wojciech-graj/TermGL) ⭐ 409 | 🐛 0 | 🌐 C | 📅 2025-12-28 A terminal-based graphics library for 2D and 3D graphics.
* [nocterm](https://github.com/Norbert515/nocterm) ⭐ 403 | 🐛 22 | 🌐 Dart | 📅 2026-08-26 A Flutter-like TUI framework for **Dart** with hot reload, 45+ components, and declarative UI patterns.
* [TermDOM](https://github.com/bikeshaving/termdom) ⭐ 313 | 🐛 13 | 🌐 TypeScript | 📅 2026-09-25 A **JavaScript** library that displays HTML and CSS in the terminal, with a real DOM
* [Ashen](https://github.com/colinta/Ashen) ⭐ 119 | 🐛 2 | 🌐 Swift | 📅 2022-10-07 An Elm inspired framework written in **Swift**
* [Thermage](https://github.com/thermage/thermage) ⭐ 96 | 🐛 6 | 🌐 PHP | 📅 2022-09-19 Thermage is a **PHP** library that provides a fluent and incredibly powerful, object-oriented interface for customizing CLI output text color, background, formatting, theming and more.
* [ink-web](https://github.com/cjroth/ink-web) ⭐ 87 | 🐛 1 | 🌐 TypeScript | 📅 2026-03-02 A browser-based runtime for Ink that renders React TUI apps in the browser using xterm.js.
* [Raxol](https://github.com/DROOdotFOO/raxol) ⭐ 79 | 🐛 67 | 🌐 Elixir | 📅 2026-09-25 A multi-surface runtime for **Elixir**: one application renders to the terminal, browser, SSH, and agent surfaces, with per-component crash isolation and hot reload from the BEAM.
* [Melker](https://melker.sh) A HTML-like, document-first TUI framework for **TypeScript/Deno** with permission sandboxing, flexbox layout, and run-from-URL support.
* [moulti](https://moulti.run/) A CLI-driven TUI displaying arbitrary outputs inside visual, collapsible blocks. Designed with **shell** scripts in mind. **Ansible**-friendly too.

***

</details>

<details open><summary><h2>Messaging</h2></summary>

* [Slack-term](https://github.com/erroneousboat/slack-term) ⭐ 6,616 | 🐛 68 | 🌐 Go | 📅 2024-04-23 Slack client for your terminal
* [discordo](https://github.com/ayntgl/discordo) ⭐ 5,785 | 🐛 53 | 🌐 Go | 📅 2026-09-24 A lightweight, secure, and feature-rich Discord terminal client
* [Devzat](https://github.com/quackduck/devzat) ⭐ 4,071 | 🐛 25 | 🌐 Go | 📅 2026-07-23 Chat over SSH, written in Golang with self-hosting ability.
* [nomadnet](https://github.com/markqvist/NomadNet) ⭐ 2,552 | 🐛 0 | 🌐 Python | 📅 2026-05-28 Secure messaging network built on Reticulum
* [sclack](https://github.com/haskellcamargo/sclack) ⭐ 2,477 | 🐛 44 | 🌐 Python | 📅 2022-12-08 Slack terminal client
* [instagram-cli](https://github.com/supreme-gg-gg/instagram-cli) ⭐ 2,157 | 🐛 42 | 🌐 TypeScript | 📅 2026-09-03 Use Instagram from your terminal, the end of brainrot is here
* [nchat](https://github.com/d99kris/nchat) ⭐ 1,966 | 🐛 25 | 🌐 C++ | 📅 2026-09-20 Telegram/WhatsApp/Signal client
* [gomuks](https://github.com/tulir/gomuks) ⭐ 1,727 | 🐛 81 | 🌐 Go | 📅 2026-09-25 Matrix client
* [concord](https://github.com/chojs23/concord) ⭐ 1,553 | 🐛 47 | 🌐 Rust | 📅 2026-09-23 A feature-rich TUI client for Discord
* [gurk-rs](https://github.com/boxdot/gurk-rs) ⭐ 1,382 | 🐛 98 | 🌐 Rust | 📅 2026-09-15 Signal Messenger client for terminal
* [basalt](https://github.com/erikjuhani/basalt) ⭐ 1,362 | 🐛 37 | 🌐 Rust | 📅 2026-09-25 TUI Application to manage Obsidian vaults and notes directly from the terminal.
* [toot](https://github.com/ihabunek/toot) ⭐ 1,324 | 🐛 128 | 🌐 Python | 📅 2026-09-12 Mastodon CLI & TUI
* [matterhorn](https://github.com/matterhorn-chat/matterhorn) ⭐ 1,153 | 🐛 22 | 🌐 Haskell | 📅 2026-08-25 A Mattermost terminal client.
* [matcha](https://github.com/floatpane/matcha) ⭐ 1,109 | 🐛 69 | 🌐 Go | 📅 2026-09-25 Email client
* [tgt](https://github.com/FedericoBruzzone/tgt) ⭐ 1,015 | 🐛 15 | 🌐 Rust | 📅 2026-09-21 A TUI for Telegram written in Rust
* [endcord](https://github.com/mzivic7/endcord) ⭐ 994 | 🐛 1 | 🌐 Python | 📅 2026-09-22 Feature rich Discord TUI client.
* [sup](https://github.com/sup-heliotrope/sup) ⭐ 971 | 🐛 73 | 🌐 Ruby | 📅 2026-07-19 A curses threads-with-tags style email client
* [zulip-terminal](https://github.com/zulip/zulip-terminal) ⭐ 866 | 🐛 475 | 🌐 Python | 📅 2026-08-16 Official Zulip terminal client (similar to matterhorn)
* [Superhighway84](https://github.com/mrusme/superhighway84) ⚠️ Archived USENET-inspired decentralized internet discussion system
* [twitch-tui](https://github.com/Xithrius/twitch-tui) ⭐ 632 | 🐛 10 | 🌐 Rust | 📅 2026-09-02 Twitch chat in the terminal
* [scli](https://github.com/isamert/scli/) ⭐ 539 | 🐛 26 | 🌐 Python | 📅 2024-11-30 A simple terminal user interface for signal messenger
* [tut](https://github.com/RasmusLindroth/tut) ⭐ 500 | 🐛 56 | 🌐 Go | 📅 2023-12-18 Mastodon TUI client
* [siggo](https://github.com/derricw/siggo) ⚠️ Archived A terminal ui for signal-cli, written in Go
* [tuisky](https://github.com/sugyan/tuisky) ⭐ 164 | 🐛 11 | 🌐 Rust | 📅 2025-12-28 TUI client for BlueSky
* [marchat](https://github.com/Cod-e-Codes/marchat) ⭐ 138 | 🐛 0 | 🌐 Go | 📅 2026-09-21 Self-hosted terminal chat with WebSocket client/server, optional shared-key encryption, and plugins.
* [Gomphotherium](https://github.com/mrusme/gomphotherium) ⚠️ Archived A command line Mastodon client.
* [mastui](https://github.com/kimusan/mastui) ⭐ 90 | 🐛 4 | 🌐 Python | 📅 2026-09-06 Mastodon TUI
* [nostui](https://github.com/akiomik/nostui) ⭐ 71 | 🐛 30 | 🌐 Rust | 📅 2026-09-15 Nostr client
* [tuix](https://github.com/pythops/tuix) ⭐ 33 | 🐛 1 | 🌐 Rust | 📅 2024-07-02 TUI for managing screens
* [SuperChat](https://github.com/serialexp/superchat) ⭐ 8 | 🐛 0 | 🌐 Go | 📅 2026-03-05 Terminal-based threaded chat application with a custom binary protocol.
* [nostratui](https://github.com/adamm-xyz/nostratui) ⭐ 7 | 🐛 0 | 🌐 Rust | 📅 2025-06-10 A terminal user interface (TUI) for browsing Nostr posts, written in Rust.
* [local-chat](https://github.com/DongGunYoon/local-chat) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-10 Terminal chat for everyone on the same WiFi, nothing to host, no accounts, no messages written to disk
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

* [fzf](https://github.com/junegunn/fzf) ⭐ 83,246 | 🐛 331 | 🌐 Go | 📅 2026-09-21 A general-purpose command-line fuzzy finder
* [wttr.in](https://github.com/chubin/wttr.in) ⭐ 30,588 | 🐛 331 | 🌐 Go | 📅 2026-09-07 The right way to check the weather
* [oha](https://github.com/hatoo/oha) ⭐ 10,562 | 🐛 58 | 🌐 Rust | 📅 2026-09-10 HTTP load generator
* [termshark](https://github.com/gcla/termshark) ⭐ 10,022 | 🐛 51 | 🌐 Go | 📅 2024-04-30 Terminal UI for tshark
* [mapscii](https://github.com/rastapasta/mapscii) ⭐ 9,241 | 🐛 52 | 🌐 JavaScript | 📅 2024-11-03 Braille & ASCII world map renderer for your console
* [wego](https://github.com/schachmat/wego) ⭐ 8,558 | 🐛 16 | 🌐 Go | 📅 2026-08-01 Weather app
* [term.everything](https://github.com/mmulet/term.everything) ⭐ 8,101 | 🐛 10 | 🌐 Go | 📅 2026-03-18 Run any GUI app in the terminal
* [cava](https://github.com/karlstav/cava) ⭐ 6,439 | 🐛 19 | 🌐 C | 📅 2026-09-21 Cross-platform Audio Visualizer
* [dua-cli](https://github.com/byron/dua-cli) ⭐ 6,297 | 🐛 0 | 🌐 Rust | 📅 2026-09-25 View disk space usage and delete unwanted data, fast.
* [gdu](https://github.com/dundee/gdu) ⭐ 6,015 | 🐛 48 | 🌐 Go | 📅 2026-09-23 Fast disk usage analyzer with console interface written in Go
* [xplr](https://github.com/sayanarijit/xplr) ⭐ 4,830 | 🐛 12 | 🌐 Rust | 📅 2026-09-23 A hackable, minimal, fast TUI file explorer, stealing ideas from nnn and fzf.
* [x-cmd](https://github.com/x-cmd/x-cmd) ⭐ 4,681 | 🐛 108 | 🌐 Awk | 📅 2026-09-24 A vast and interesting collection of tools that can then bootstrap lots of other programs / functions in a consistent and structured way.
* [csvlens](https://github.com/YS-L/csvlens) ⭐ 3,987 | 🐛 59 | 🌐 Rust | 📅 2026-07-04 TUI CSV file viewer. It is like less but made for CSV.
* [cfdisk](https://github.com/util-linux/util-linux) ⭐ 3,232 | 🐛 434 | 🌐 C | 📅 2026-09-22 TUI partition editor included in util-linux
* [diskonaut](https://github.com/imsnif/diskonaut) ⭐ 3,135 | 🐛 45 | 🌐 Rust | 📅 2024-03-07 Terminal disk space navigator
* [bluetui](https://github.com/pythops/bluetui) ⭐ 3,017 | 🐛 18 | 🌐 Rust | 📅 2026-08-28 A TUI for managing bluetooth devices.
* [gif-for-cli](https://github.com/google/gif-for-cli) ⚠️ Archived Convert a gif into ASCII
* [impala](https://github.com/pythops/impala) ⭐ 2,865 | 🐛 0 | 🌐 Rust | 📅 2026-09-19 TUI for managing wifi
* [tweakcc](https://github.com/Piebald-AI/tweakcc) ⭐ 2,526 | 🐛 58 | 🌐 TypeScript | 📅 2026-09-25 TUI to customize your Claude Code themes, thinking verbs, and more.
* [Caligula](https://github.com/ifd3f/caligula) ⭐ 2,357 | 🐛 54 | 🌐 Rust | 📅 2026-09-17 A user-friendly, lightweight TUI for imaging disks.
* [smassh](https://github.com/kraanzu/smassh) ⭐ 2,052 | 🐛 12 | 🌐 Python | 📅 2026-08-17 A TUI based typing test application inspired by MonkeyType.
* [recoverpy](https://github.com/PabloLec/recoverpy) ⭐ 1,793 | 🐛 3 | 🌐 Python | 📅 2026-08-03 A TUI to recover overwritten or deleted data.
* [gpg-tui](https://github.com/orhun/gpg-tui) ⭐ 1,763 | 🐛 14 | 🌐 Rust | 📅 2026-09-21 A terminal user interface for GnuPG
* [ttyper](https://github.com/max-niederman/ttyper) ⭐ 1,595 | 🐛 36 | 🌐 Rust | 📅 2026-04-07 Terminal-based typing test
* [Systemd-manager-tui](https://github.com/matheus-git/systemd-manager-tui) ⭐ 1,584 | 🐛 6 | 🌐 Rust | 📅 2026-09-21 A program for managing systemd services through a TUI.
* [bluetuith](https://github.com/darkhz/bluetuith) ⭐ 1,412 | 🐛 15 | 🌐 Go | 📅 2026-07-01 A TUI-based bluetooth connection manager, which can interact with bluetooth adapters and devices.
* [arttime](https://github.com/reportaman/arttime) ⭐ 1,387 | 🐛 6 | 🌐 Shell | 📅 2026-08-18 An app that brings beauty of text-art together with functionality of clock, timer, and pattern-based time manager.
* [wavemon](https://github.com/uoaerg/wavemon) ⭐ 1,243 | 🐛 6 | 🌐 C | 📅 2026-06-29 A wireless device monitoring application
* [LearnByExample](https://github.com/learnbyexample/TUI-apps) ⭐ 1,016 | 🐛 0 | 🌐 Python | 📅 2026-02-02 A TUI with tutorials and +300 exercises on python, grep, awk, sed & general terminal usage.
* [godap](https://github.com/Macmod/godap) ⭐ 981 | 🐛 4 | 🌐 Go | 📅 2026-08-21 A complete TUI for LDAP written in Golang
* [ec2-instance-selector](https://github.com/aws/amazon-ec2-instance-selector) ⭐ 931 | 🐛 20 | 🌐 Go | 📅 2025-12-22 A CLI tool and go library which recommends instance types based on resource criteria like vcpus and memory
* [golazo](https://github.com/0xjuanma/golazo) ⭐ 865 | 🐛 7 | 🌐 Go | 📅 2026-09-07 Get soccer minute-by-minute updates and finished match stats in your terminal
* [mqttui](https://github.com/EdJoPaTo/mqttui) ⭐ 732 | 🐛 13 | 🌐 Rust | 📅 2026-08-09 MQTT Client written in rust
* [pug](https://github.com/leg100/pug) ⭐ 701 | 🐛 21 | 🌐 Go | 📅 2026-01-02 terraform and tofu module and infrastructure management.
* [vortix](https://github.com/Harry-kp/vortix) ⭐ 653 | 🐛 20 | 🌐 Rust | 📅 2026-09-25 Terminal UI for WireGuard and OpenVPN with real-time telemetry, leak detection, and kill switch.
* [flawz](https://github.com/orhun/flawz) ⭐ 608 | 🐛 15 | 🌐 Rust | 📅 2026-06-13 A Terminal UI for browsing security vulnerabilities (CVEs)
* [nemu](https://github.com/nemuTUI/nemu) ⭐ 608 | 🐛 16 | 🌐 C | 📅 2026-06-11 A TUI for QEMU
* [thokr](https://github.com/coloradocolby/thokr) ⭐ 602 | 🐛 8 | 🌐 Rust | 📅 2026-06-12 a sleek typing tui written in rust
* [linecast](https://github.com/ashuttl/linecast) ⭐ 536 | 🐛 20 | 🌐 Python | 📅 2026-09-25 Interactive weather, radar, tides, sun and moon views, a planetarium with stars and constellations, and maps with a rotatable globe for the terminal.
* [tcpterm](https://github.com/sachaos/tcpterm) ⭐ 490 | 🐛 0 | 🌐 Go | 📅 2024-01-10 tcpterm is a packet visualizer in TUI.
* [emu2](https://github.com/dmsc/emu2) ⭐ 466 | 🐛 27 | 🌐 C | 📅 2026-07-04 A simple DOS emulator for the Linux text console, supporting basic DOS system calls and console I/O.
* [mac-cleanup-go](https://github.com/2ykwang/mac-cleanup-go) ⭐ 460 | 🐛 6 | 🌐 Go | 📅 2026-09-24 macOS disk cleanup TUI: scan cache/dev artifacts, preview, exclude, and move items to Trash.
* [asciiMol](https://github.com/dewberryants/asciiMol) ⭐ 419 | 🐛 0 | 🌐 Python | 📅 2026-06-24 Curses based ASCII molecule viewer for linux terminals.
* [Captain's log](https://github.com/NikolaDucak/caps-log) ⭐ 405 | 🐛 16 | 🌐 C++ | 📅 2026-08-14 A small TUI journaling tool
* [wifitui](https://github.com/shazow/wifitui) ⭐ 337 | 🐛 34 | 🌐 Go | 📅 2026-09-24 Fast featureful friendly wifi terminal UI, supports NetworkManager and iwd over dbus.
* [sbb-tui](https://github.com/necrom4/sbb-tui) ⭐ 327 | 🐛 12 | 🌐 Go | 📅 2026-08-19 TUI client for Switzerland's public transport timetables, inspidered by the SBB/CFF/FFS app.
* [packemon](https://github.com/ddddddO/packemon) ⭐ 308 | 🐛 37 | 🌐 Go | 📅 2026-09-25 Packet generator and monitor.
* [NanoCore](https://github.com/AfaanBilal/NanoCore) ⭐ 292 | 🐛 3 | 🌐 Rust | 📅 2026-09-07 An 8-bit CPU emulator TUI written in Rust with an assembler and a custom ISA.
* [try-rs](https://github.com/tassiovirginio/try-rs/) ⭐ 291 | 🐛 0 | 🌐 Rust | 📅 2026-08-25 A lightning-fast TUI to manage temporary projects. Create, explore, and clone repositories instantly without cluttering your system.
* [moribito](https://github.com/ericschmar/moribito) ⭐ 281 | 🐛 9 | 🌐 Kotlin | 📅 2026-01-24 Browse LDAP directory trees, viewing records, and executing custom queries.
* [typtea](https://github.com/ashish0kumar/typtea) ⭐ 244 | 🐛 2 | 🌐 Go | 📅 2026-09-23 Minimal terminal-based typing speed tester with support for dozens of programming languages.
* [neoss](https://github.com/PabloLec/neoss) ⭐ 232 | 🐛 13 | 🌐 TypeScript | 📅 2026-09-22 Socket statistics visualization and explanation tool for Unix systems.
* [WG Commander](https://github.com/andrianbdn/wg-cmd) ⭐ 224 | 🐛 2 | 🌐 Go | 📅 2026-07-07 A TUI for a simple WireGuard VPN setup: peer management, QR codes, setup wizard.
* [tlock](https://github.com/eklairs/tlock) ⭐ 201 | 🐛 7 | 🌐 Go | 📅 2024-09-01 Two-Factor Authentication Tokens Manager in Terminal
* [tray-tui](https://github.com/Levizor/tray-tui) ⭐ 165 | 🐛 2 | 🌐 Rust | 📅 2026-03-15 System tray in your terminal
* [redu](https://github.com/drdo/redu) ⭐ 156 | 🐛 12 | 🌐 Rust | 📅 2026-09-11 ncdu for your restic repository that manages exclusion lists to prune files from existing repos and skip new ones
* [CrunchyCleaner](https://github.com/knuspii/crunchycleaner) ⭐ 154 | 🐛 2 | 🌐 Go | 📅 2026-09-17 A lightweight, software cache cleanup tool for Windows & Linux.
* [WifUI](https://github.com/sohamw03/wifui) ⭐ 151 | 🐛 0 | 🌐 Rust | 📅 2026-09-23 TUI for managing Wi-Fi connections on Windows natively (Rust)
* [terminalperiodictable](https://github.com/velorek1/terminalperiodictable) ⭐ 145 | 🐛 1 | 🌐 C | 📅 2025-08-01 A beautiful TUI periodic table for Unix systems coded in C.
* [tttui](https://github.com/reidoboss/tttui) ⭐ 124 | 🐛 0 | 🌐 Rust | 📅 2026-07-18 A Monkeytype-inspired typing test that runs entirely in your terminal
* [pass-cli](https://github.com/arimxyer/pass-cli) ⭐ 110 | 🐛 15 | 🌐 Go | 📅 2026-07-15 A TUI and CLI password manager with rclone cloud syncing support
* [keydex](https://github.com/shikaan/keydex) ⭐ 98 | 🐛 4 | 🌐 Go | 📅 2026-08-03 TUI password manager for KeePass databases.
* [oeis-tui](https://github.com/hako/oeis-tui) ⭐ 92 | 🐛 0 | 🌐 Rust | 📅 2026-02-03  A TUI and CLI for browsing the On-Line Encyclopedia of Integer Sequences (OEIS) in the terminal.
* [HumBLE Explorer](https://github.com/koenvervloesem/humble-explorer) ⭐ 85 | 🐛 0 | 🌐 Python | 📅 2023-11-25 A cross-platform, command-line and human-friendly Bluetooth Low Energy scanner
* [diary](https://github.com/actuday6418/Diary) ⭐ 74 | 🐛 1 | 🌐 Rust | 📅 2021-06-16 A diary app written in Rust that encrypts both text and file data, and can decrypt and build a rich HTML representation of your diary when required.
* [tui-shop](https://github.com/Gcat101/tui-shop) ⭐ 73 | 🐛 1 | 🌐 Python | 📅 2022-07-10 Something between a CLI and a GUI way of downloading TUIs/CLIs
* [IconicFonts](https://github.com/iconicFonts/iconic-fonts) ⚠️ Archived A collection of patched fonts featuring over 60,000 icons, tailored specifically for TUIs.
* [ytunnel](https://github.com/yetidevworks/ytunnel) ⭐ 54 | 🐛 0 | 🌐 Rust | 📅 2026-08-05 A TUI for creating and managing Cloudflare Tunnels with custom domains
* [fnf](https://github.com/leo-arch/fnf) ⭐ 53 | 🐛 3 | 🌐 C | 📅 2026-04-04 An interactive fuzzy finder for the terminal
* [Clanki](https://github.com/alvenw/clanki) ⭐ 42 | 🐛 5 | 🌐 Python | 📅 2026-04-06 A TUI-based Anki review client, even supporting progress sync.
* [rocket.term](https://github.com/gerstner-hub/rocket.term) ⭐ 32 | 🐛 0 | 🌐 Python | 📅 2023-12-20 Text based chat client for the Rocket.chat messaging solution.
* [distrobox-tui](https://github.com/phanirithvij/distrobox-tui) ⭐ 31 | 🐛 1 | 🌐 Go | 📅 2025-03-11 TUI for managing distrobox containers
* [physics-TUI](https://github.com/ClaudioRMalvino/physics_TUI) ⭐ 30 | 🐛 0 | 🌐 Python | 📅 2026-07-09 Physics TUI application for undergraduate study
* [tab-pal](https://github.com/ben-n93/tab-pal) ⭐ 29 | 🐛 0 | 🌐 Python | 📅 2024-10-01 Add and edit custom colour palettes in Tableau from the command-line.
* [DigiSurf](https://github.com/SeanMcLoughlin/digisurf) ⭐ 26 | 🐛 0 | 🌐 Rust | 📅 2025-03-27 A TUI signal waveform viewer
* [PesterExplorer](https://github.com/HeyItsGilbert/PesterExplorer) ⭐ 26 | 🐛 5 | 🌐 PowerShell | 📅 2026-05-30 A TUI to explore Pester results.
* [lazynginx](https://github.com/giacomomasseron/lazynginx) ⭐ 20 | 🐛 0 | 🌐 Go | 📅 2026-09-21 Simple TUI for nginx management.
* [wb](https://github.com/MertGunduz/wb) ⭐ 15 | 🐛 0 | 🌐 C | 📅 2023-09-01 A TUI vocabulary notebook app for Linux based devices.
* [dupster](https://github.com/karimz1/dupster) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2026-09-23 The lazy way to find duplicates in your Terminal. Easily find duplicates, preview them and delete them.
* [passtui](https://github.com/fjmoralesp/passtui) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2026-07-14 The terminal user interface for **pass**, the standard unix password manager.
* [steam\_friends\_list\_tui](https://github.com/AdamWHY2K/steam_friends_list_tui) ⭐ 5 | 🐛 12 | 🌐 C# | 📅 2026-01-19 The steam friends list in the commandline
* [cgdisk](https://www.rodsbooks.com/gdisk/cgdisk-walkthrough.html) TUI partition editor for manipulating GUID partition tables, and modeled after cfdisk
* [isw](https://gitlab.com/thom-cameron/isw) A simple terminal stopwatch application for pomodoro etc.
* [jrnl](https://jrnl.sh/) Collect your thoughts and notes without leaving the command line. human-friendly. future-proof. secure.
* [lnav](https://lnav.org/) An advanced log file viewer for the small-scale
* [moc](https://moc.daper.net/download) console audio player
* [ncdu](https://dev.yorhel.nl/ncdu) disk usage analyzer with an ncurses interface
* [nmtui](https://developer.gnome.org/NetworkManager/stable/nmtui.html) ncurses network manager

***

</details>

<details open><summary><h2>Multimedia</h2></summary>

* [vlc](https://github.com/videolan/vlc) ⭐ 19,771 | 🐛 2 | 🌐 C | 📅 2026-09-25 VLC includes an ncurses interface, `vlc --intf ncurses`
* [mps-youtube](https://github.com/mps-youtube/mps-youtube) ⭐ 8,794 | 🐛 227 | 🌐 Python | 📅 2026-03-04 Terminal based YouTube player and downloader
* [spotify-player](https://github.com/aome510/spotify-player) ⭐ 7,239 | 🐛 154 | 🌐 Rust | 📅 2026-09-19 A Spotify player in the terminal with full feature parity
* [ncspot](https://github.com/hrkfdn/ncspot) ⭐ 6,784 | 🐛 214 | 🌐 Rust | 📅 2026-09-21 Cross-platform ncurses Spotify client written in Rust
* [ytfzf](https://github.com/pystardust/ytfzf) ⭐ 4,154 | 🐛 66 | 🌐 Shell | 📅 2024-09-27 A POSIX script that helps you find Youtube videos (without API) or Peertube videos and opens/downloads them using mpv/youtube-dl
* [kew](https://github.com/ravachol/kew) ⭐ 3,110 | 🐛 1 | 🌐 C | 📅 2026-09-25 A terminal music player for Linux
* [timg](https://github.com/hzeller/timg) ⭐ 2,764 | 🐛 36 | 🌐 C++ | 📅 2026-08-05 A terminal image viewer
* [termusic](https://github.com/tramhao/termusic) ⭐ 2,218 | 🐛 49 | 🌐 Rust | 📅 2026-09-22 Music Player TUI written in Rust
* [tdf](https://github.com/itsjunetime/tdf) ⭐ 1,982 | 🐛 42 | 🌐 Rust | 📅 2026-08-16 A tui-based PDF viewer
* [tizonia-openmax-il](https://github.com/tizonia/tizonia-openmax-il) ⭐ 1,741 | 🐛 168 | 🌐 C | 📅 2026-09-25 Command-line cloud music player for Linux with support for Spotify, Google Play Music, YouTube, SoundCloud, Dirble, Plex servers and Chromecast devices
* [soundcloud2000](https://github.com/grobie/soundcloud2000) ⚠️ Archived A terminal client for soundcloud
* [spotatui](https://github.com/LargeModGames/spotatui) ⭐ 1,387 | 🐛 34 | 🌐 Rust | 📅 2026-09-25 Spotify client with native streaming, synced lyrics, and real-time audio visualization
* [bookokrat](https://github.com/bugzmanov/bookokrat) ⭐ 1,162 | 🐛 47 | 🌐 Rust | 📅 2026-09-06 Full-featured EPUB books reader with Vim keybindings.
* [textual-paint](https://github.com/1j01/textual-paint) ⭐ 1,121 | 🐛 10 | 🌐 Python | 📅 2026-02-21 MS Paint in your terminal
* [pyradio](https://github.com/coderholic/pyradio) ⭐ 1,098 | 🐛 12 | 🌐 Python | 📅 2026-05-07 TUI web radio player with thousands of stations from around the world
* [viu](https://github.com/viu-media/viu) ⚠️ Archived Your browser anime experience from the terminal
* [wiremix](https://github.com/tsowell/wiremix) ⭐ 1,063 | 🐛 39 | 🌐 Rust | 📅 2026-07-12 TUI audio mixer for PipeWire similar to pavucontrol to adjust volumes, change input/output devices and their profiles
* [manga-tui](https://github.com/josueBarretogit/manga-tui) ⭐ 936 | 🐛 25 | 🌐 Rust | 📅 2026-07-13 Terminal-based manga reader and downloader with image rendering support
* [upiano](https://github.com/eliasdorneles/upiano) ⭐ 792 | 🐛 5 | 🌐 Python | 📅 2025-07-09 A Piano in your terminal
* [managarr](https://github.com/Dark-Alex-17/managarr) ⭐ 775 | 🐛 3 | 🌐 Rust | 📅 2026-09-19 A TUI and CLI for managing your \*arr servers
* [ytui-music](https://github.com/sudipghimire533/ytui-music) ⭐ 773 | 🐛 38 | 🌐 Rust | 📅 2025-03-03 Listen to music from youtube. Configurable, minimal, lightweight, private & beautiful music client.
* [xytz](https://github.com/xdagiz/xytz) ⭐ 643 | 🐛 9 | 🌐 Go | 📅 2026-09-07 Beautiful TUI for downloading YouTube videos/playlists/channels.
* [jellyfin-tui](https://github.com/dhonus/jellyfin-tui) ⭐ 600 | 🐛 19 | 🌐 Rust | 📅 2026-09-20 Jellyfin client
* [spotui](https://github.com/ceuk/spotui) ⭐ 577 | 🐛 8 | 🌐 Python | 📅 2023-07-25 Spotify client written in Python
* [fancy-cat](https://github.com/freref/fancy-cat) ⭐ 565 | 🐛 20 | 🌐 Zig | 📅 2026-08-03 A Lightweight terminal-based PDF reader with Vim keybindings
* [cmdpxl](https://github.com/knosmos/cmdpxl) ⭐ 549 | 🐛 2 | 🌐 Python | 📅 2021-08-27 Totally practical command-line image editor
* [draw](https://github.com/maaslalani/draw) ⭐ 547 | 🐛 6 | 🌐 Go | 📅 2023-12-04 A simple drawing tool in the terminal.
* [pipe-viewer](https://github.com/trizen/pipe-viewer) ⭐ 510 | 🐛 44 | 🌐 Perl | 📅 2026-09-24 A lightweight YouTube client for Linux, without requiring an API key.
* [GopherTube](https://github.com/krishnassh/gophertube) ⭐ 434 | 🐛 2 | 🌐 Go | 📅 2026-09-05 A terminal-based YouTube client that scrapes YouTube search results and uses mpv for video playback
* [asak](https://github.com/chaosprint/asak) ⭐ 372 | 🐛 11 | 🌐 Rust | 📅 2026-04-11 A cross-platform audio recording/playback TUI
* [tortuise](https://github.com/buildoak/tortuise) ⭐ 242 | 🐛 6 | 🌐 Rust | 📅 2026-06-15 Gaussian Splatting 3D viewer in your terminal. 6 render modes, CPU-only via crossterm + rayon
* [vv](https://github.com/wolfpld/vv) ⚠️ Archived A terminal image viewer, supporting an extensive range of modern image formats
* [invidtui](https://github.com/darkhz/invidtui) ⭐ 205 | 🐛 8 | 🌐 Go | 📅 2024-07-14 A TUI Invidious client for Windows, Linux and MacOS, that fetches and plays audio/video from an invidious instance. Supports viewing and playing from playlists and channels as well.
* [waves](https://github.com/llehouerou/waves) ⭐ 174 | 🐛 2 | 🌐 Go | 📅 2026-09-24 Terminal music player with vim-style navigation and radio mode that plays similar artists from your library
* [Toutui](https://github.com/AlbanDAVID/Toutui) ⚠️ Archived A TUI Audiobookshelf Client for Linux
* [RadioGoGo](https://github.com/Zi0P4tch0/RadioGoGo) ⭐ 164 | 🐛 3 | 🌐 Go | 📅 2026-09-25 Go-powered CLI to surf global radio waves via a sleek TUI.
* [MAL-Cli](https://github.com/L4z3x/mal-tui) ⭐ 162 | 🐛 0 | 🌐 Rust | 📅 2025-07-17 A terminal interface for the official myanimelist api written in rust.
* [mpvc](https://github.com/gmt4/mpvc) ⭐ 160 | 🐛 1 | 🌐 Shell | 📅 2026-09-25 A mpc-like control interface for mpv
* [line](https://github.com/pd3v/line) ⭐ 152 | 🐛 0 | 🌐 C++ | 📅 2025-08-11 Tiny command-line midi sequencer and language for live coding
* [Trophy](https://github.com/taigrr/trophy) ⭐ 129 | 🐛 1 | 🌐 Go | 📅 2026-09-24 A TUI 3D Model Viewer for OBJ and GLB files
* [Gorae](https://github.com/Han8931/gorae) ⭐ 97 | 🐛 1 | 🌐 Go | 📅 2026-08-02 TUI librarian for PDFs and EPUBs with Vim-style navigation.
* [rusty-pipes](https://github.com/dividebysandwich/rusty-pipes) ⭐ 94 | 🐛 7 | 🌐 Rust | 📅 2026-09-15 A sample-based, MIDI-controlled virtual pipe organ instrument compatible with GrandOrgue and Hauptwerk sample sets.
* [Tanko](https://github.com/Alexandro521/Tanko) ⭐ 88 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-25 A tool for reading and downloading manga from the terminal, with image rendering support
* [sonicradio](https://github.com/dancnb/sonicradio) ⭐ 85 | 🐛 5 | 🌐 Go | 📅 2026-01-23 A stylish TUI radio player making use of Radio Browser API and Bubbletea.
* [Relax-player](https://github.com/ebithril/relax-player) ⭐ 80 | 🐛 2 | 🌐 Rust | 📅 2026-01-05 A lightweight, distraction-free alternative to web-based ambient players.
* [valveFM](https://github.com/zorig/valvefm) ⭐ 54 | 🐛 0 | 🌐 Go | 📅 2026-08-20 Vintage FM radio TUI for streaming stations from radio-browser.info
* [image-sorter](https://github.com/jgalat/image-sorter) ⭐ 49 | 🐛 0 | 🌐 Rust | 📅 2024-12-27 Terminal user interface for sorting images using key bindings written in Rust
* [terminal-yt](https://github.com/jooooscha/terminal-yt) ⭐ 44 | 🐛 3 | 🌐 Rust | 📅 2026-01-06 A small newsboat-inspired terminal youtube manager
* [gadacz](https://github.com/rareitems/gadacz) ⭐ 42 | 🐛 5 | 🌐 Rust | 📅 2024-06-27 Audiobook player
* [ytdl-tui](https://github.com/darky/ytdl-tui) ⭐ 41 | 🐛 0 | 🌐 TypeScript | 📅 2024-12-21 TUI for downloading Youtube videos
* [ani-l](https://github.com/komposer-aml/ani-l) ⭐ 37 | 🐛 0 | 🌐 Rust | 📅 2026-01-08 Rust-based anime browsing and streaming all without leaving the terminal
* [ctune](https://github.com/An7ar35/ctune) ⭐ 32 | 🐛 3 | 🌐 C | 📅 2026-04-18 ncurses based internet radio player for Linux.
* [Absotui](https://github.com/pdwaldrop/absotui) ⭐ 21 | 🐛 2 | 🌐 Rust | 📅 2026-09-25 A TUI Audiobookshelf client for Linux and macOS, written in Rust
* [roku-cli](https://github.com/winsbe01/roku-cli) ⭐ 20 | 🐛 1 | 🌐 Python | 📅 2023-03-01 A command line TUI remote for Roku
* [marstui-audio](https://github.com/schooldanlp6/marstui-rustio) ⭐ 14 | 🐛 3 | 🌐 Rust | 📅 2026-08-31 A nice audio management Interface, similar to pavucontrol with the benefit of customizing everything
* [sgram-tui](https://github.com/arian-shamaei/sgram-tui) ⭐ 5 | 🐛 0 | 🌐 Rust | 📅 2026-08-16 Calibrated spectrogram analyzer for live mic or audio files, with labeled PNG figure export and a headless render mode
* [favicon-editor](https://github.com/xyproto/favicon-editor) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2026-08-14 Spartan grayscale favicon editor
* [chafa](https://hpjansson.org/chafa/) A powerful utility that converts image data, including animated GIFs, into graphics formats or ANSI/Unicode character art suitable for display in a terminal.
* [cmus](https://cmus.github.io/) A small, fast and powerful console music player for Unix-like operating systems.
* [nap](https://nap.sourceforge.net/) Linux napster client
* [ostui](https://git.sr.ht/~ser/ostui) CLI client for Subsonic-API servers like gonic and Navidrome
* [rmpc](https://rmpc.mierak.dev/) A configurable MPD client inspired by ncmpcpp and ranger with album art support via various graphics protocols.

***

</details>

<details open><summary><h2>Productivity</h2></summary>

* [tmux](https://github.com/tmux/tmux) ⭐ 49,499 | 🐛 33 | 🌐 C | 📅 2026-09-25 Terminal multiplexer
* [zellij](https://github.com/zellij-org/zellij) ⭐ 35,546 | 🐛 1,935 | 🌐 Rust | 📅 2026-09-25 A terminal workspace with batteries included
* [Glow](https://github.com/charmbracelet/glow) ⭐ 27,469 | 🐛 235 | 🌐 Go | 📅 2026-09-22 A markdown reader, designed from the ground up to showcase the elegance and capabilities of TUI.
* [slides](https://github.com/maaslalani/slides) ⭐ 11,667 | 🐛 77 | 🌐 Go | 📅 2026-07-08 A terminal based presentation tool, supporting markdown syntax.
* [Visidata](https://github.com/saulpw/visidata) ⭐ 9,298 | 🐛 88 | 🌐 Python | 📅 2026-09-23 A terminal spreadsheet multitool for discovering and arranging data
* [presenterm](https://github.com/mfontanini/presenterm) ⭐ 8,878 | 🐛 80 | 🌐 Rust | 📅 2026-05-22 A markdown terminal slideshow tool
* [mcfly](https://github.com/cantino/mcfly) ⭐ 7,800 | 🐛 135 | 🌐 Rust | 📅 2026-09-01 Intelligent context-aware search engine for your shell history
* [television](https://github.com/alexpasmantier/television) ⭐ 6,291 | 🐛 80 | 🌐 Rust | 📅 2026-09-23 A fast and versatile fuzzy finder TUI
* [sc-im](https://github.com/andmarti1424/sc-im) ⭐ 5,700 | 🐛 117 | 🌐 C | 📅 2026-09-24 An ncurses spreadsheet program for terminal. Reignited version of sc
* [hledger-ui](https://github.com/simonmichael/hledger) ⭐ 4,731 | 🐛 320 | 🌐 Haskell | 📅 2026-09-25 A fast TUI for browsing double entry bookkeeping data
* [LazySSH](https://github.com/adembc/lazyssh) ⭐ 3,954 | 🐛 66 | 🌐 Go | 📅 2025-10-09 TUI SSH manager to browse, connect, and manage servers from ssh config files.
* [doxx](https://github.com/bgreenwell/doxx) ⭐ 3,759 | 🐛 9 | 🌐 Rust | 📅 2026-08-10 A TUI document viewer for Microsoft Word files
* [TUIOS](https://github.com/Gaurav-Gosain/tuios) ⭐ 3,718 | 🐛 20 | 🌐 Go | 📅 2026-09-25 A TUI window manager for managing multiple terminal sessions
* [Tabiew](https://github.com/shshemi/tabiew) ⭐ 3,125 | 🐛 17 | 🌐 Rust | 📅 2026-09-25 A lightweight app to view and query tabular data files, such as CSV, TSV, and parquet.
* [termscp](https://github.com/veeso/termscp) ⭐ 3,102 | 🐛 3 | 🌐 Rust | 📅 2026-09-16 A TUI file transfer and explorer, with support for SCP/SFTP/FTP/S3.
* [khal](https://github.com/pimutils/khal) ⭐ 3,056 | 🐛 264 | 🌐 Python | 📅 2026-09-23 A standards based CLI calendar program, able to synchronize with CalDAV servers
* [Bagels](https://github.com/EnhancedJax/Bagels) ⭐ 2,908 | 🐛 18 | 🌐 Python | 📅 2025-07-06 TUI expense tracker
* [patat](https://github.com/jaspervdj/patat) ⭐ 2,742 | 🐛 23 | 🌐 Haskell | 📅 2026-06-25 Terminal-based presentations using Pandoc
* [elia](https://github.com/darrenburns/elia) ⭐ 2,478 | 🐛 25 | 🌐 Python | 📅 2024-10-10 A terminal ChatGPT client build with Textual
* [calcure](https://github.com/anufrievroman/calcure) ⭐ 2,365 | 🐛 7 | 🌐 Python | 📅 2026-08-29 Modern TUI calendar and task manager with minimal and customizable UI.
* [h-m-m](https://github.com/nadrad/h-m-m) ⭐ 2,292 | 🐛 4 | 🌐 PHP | 📅 2026-07-06 Hackers Mind Map
* [taskwarrior-tui](https://github.com/kdheepak/taskwarrior-tui) ⭐ 2,131 | 🐛 131 | 🌐 Rust | 📅 2026-09-25 A Terminal User Interface for Taskwarrior
* [jiratui](https://github.com/whyisdifficult/jiratui) ⭐ 1,701 | 🐛 12 | 🌐 Python | 📅 2026-09-25 A TUI for interacting with Atlassian Jira directly from your shell
* [sshm](https://github.com/gu1llaum-3/sshm) ⭐ 1,399 | 🐛 34 | 🌐 Go | 📅 2026-07-27 SSH made easy and fast: browse, connect, and control from your terminal with a modern TUI
* [ttyplot](https://github.com/tenox7/ttyplot) ⭐ 1,380 | 🐛 12 | 🌐 C | 📅 2026-09-24 A realtime plotting utility for terminals with data input from stdin/pipe.
* [intelli-shell](https://github.com/lasantosr/intelli-shell) ⭐ 1,292 | 🐛 6 | 🌐 Rust | 📅 2026-07-26 Manage command templates/snippets with dynamic completions and AI integration
* [Desktop-TUI](https://github.com/Julien-cpsn/desktop-tui) ⭐ 1,221 | 🐛 5 | 🌐 Rust | 📅 2026-03-01 A desktop environment without graphics
* [clipse](https://github.com/savedra1/clipse) ⭐ 1,046 | 🐛 47 | 🌐 Go | 📅 2026-06-09 TUI-based clipboard manager application
* [longbridge-terminal](https://github.com/longbridge/longbridge-terminal) ⭐ 1,010 | 🐛 12 | 🌐 Rust | 📅 2026-09-20 AI-native TUI for Longbridge Securities: real-time quotes, portfolio management, and trading for HK/US/A-share/SG markets.
* [dvtm](https://github.com/martanne/dvtm) ⭐ 965 | 🐛 77 | 🌐 C | 📅 2024-05-18 A terminal multiplexer with dwm like window management
* [agent-deck](https://github.com/asheshgoplani/agent-deck) ⭐ 953 | 🐛 25 | 🌐 Go | 📅 2026-09-25 Terminal dashboard for managing multiple AI coding agent sessions
* [topydo](https://github.com/topydo/topydo) ⭐ 941 | 🐛 77 | 🌐 Python | 📅 2026-09-16 A powerful todo list application using the todo.txt format
* [tenere](https://github.com/pythops/tenere) ⭐ 685 | 🐛 11 | 🌐 Rust | 📅 2026-05-10 A TUI for ChatGPT written in Rust.
* [todoman](https://github.com/pimutils/todoman) ⭐ 597 | 🐛 113 | 🌐 Python | 📅 2026-05-25 A simple, standards-based (ics, DAV), cli task-manager
* [zeit](https://github.com/mrusme/zeit) ⭐ 592 | 🐛 0 | 🌐 Go | 📅 2026-09-09 A command line tool for tracking time spent on activities.
* [pomo](https://github.com/Bahaaio/pomo) ⭐ 516 | 🐛 4 | 🌐 Go | 📅 2026-06-06 A minimal, customizable TUI Pomodoro timer with ASCII art, progress bar, desktop notifications, and productivity statistics.
* [Tock](https://github.com/kriuchkov/tock) ⭐ 486 | 🐛 5 | 🌐 Go | 📅 2026-08-26 The powerful time tracking tool for the command line with a beautiful interactive TUI.
* [kabmat](https://github.com/PlankCipher/kabmat) ⭐ 424 | 🐛 13 | 🌐 C++ | 📅 2023-01-26 TUI program for managing kanban boards with vim-like keybindings
* [hygg](https://github.com/kruserr/hygg) ⭐ 360 | 🐛 14 | 🌐 Rust | 📅 2026-09-18 📚 Simplifying the way you read. Minimalistic Vim-like TUI document reader.
* [kanban-python](https://github.com/Zaloog/kanban-python) ⭐ 351 | 🐛 0 | 🌐 Python | 📅 2026-05-12 Kanban Terminal App written in Python
* [gocheat](https://github.com/Achno/gocheat) ⭐ 344 | 🐛 8 | 🌐 Go | 📅 2025-10-26 A beautiful TUI cheatsheet for keybindings,hotkeys,gestures and aliases
* [budget-tracker-tui](https://github.com/Feromond/budget-tracker-tui) ⭐ 341 | 🐛 8 | 🌐 Rust | 📅 2026-09-16 A TUI budget tracker app designed to track income, expenses, investments, budget goals and visualize / gather insights.
* [taskline](https://github.com/perryrh0dan/taskline) ⭐ 328 | 🐛 23 | 🌐 TypeScript | 📅 2025-10-31 Tasks, boards & notes for the command-line habitat
* [lssh](https://github.com/blacknon/lssh) ⭐ 327 | 🐛 21 | 🌐 Go | 📅 2026-07-25 A terminal-native remote access suite for SSH workflows, including interactive host selection, parallel commands, mux workspaces, file transfer, sync, diff, forwarding, and multi-host monitoring.
* [numr](https://github.com/nasedkinpv/numr) ⭐ 293 | 🐛 5 | 🌐 Rust | 📅 2026-07-14 A natural language calculator with unit/currency conversions and vim-style keybindings
* [nless](https://github.com/mpryor/nothing-less) ⭐ 281 | 🐛 15 | 🌐 Python | 📅 2026-05-08 Terminal pager for exploring tabular data with vi keybindings and automatic delimiter inference
* [tvterm](https://github.com/magiblot/tvterm) ⭐ 281 | 🐛 8 | 🌐 C++ | 📅 2026-08-14 A terminal emulator that runs in your terminal
* [fjira](https://github.com/mk-5/fjira) ⭐ 275 | 🐛 22 | 🌐 Go | 📅 2026-07-07 TUI application for Atlassian Jira
* [mynav](https://github.com/GianlucaP106/mynav) ⭐ 252 | 🐛 11 | 🌐 Go | 📅 2025-09-28 Workspace and session management for terminal environments
* [SheetsUI](https://github.com/zaphar/sheetsui) ⭐ 246 | 🐛 3 | 🌐 Rust | 📅 2026-09-17 A console based spreadsheet application
* [tiki](https://github.com/boolean-maybe/tiki) ⭐ 213 | 🐛 10 | 🌐 Go | 📅 2026-08-12 Markdown-based git-versioned project and issue manager
* [Toney](https://github.com/SourcewareLab/Toney) ⭐ 209 | 🐛 5 | 🌐 Go | 📅 2026-05-27 a fast, lightweight, terminal-based note-taking app for the modern developer.
* [kanban](https://github.com/fulsomenko/kanban) ⭐ 170 | 🐛 12 | 🌐 Rust | 📅 2026-09-25 TUI kanban board for projects management with sprint tracking and task prioritization.
* [helm](https://github.com/0xjuanma/helm) ⭐ 149 | 🐛 1 | 🌐 Go | 📅 2026-09-07 A minimalistic & customizable pomodoro-like timer for your terminal
* [ssh-slides](https://github.com/ivantsepp/ssh-slides) ⭐ 136 | 🐛 0 | 🌐 Go | 📅 2023-07-10 Terminal-based presentations over SSH
* [awsui](https://github.com/junminhong/awsui) ⭐ 127 | 🐛 0 | 🌐 Python | 📅 2026-08-23 A powerful, user-friendly terminal interface for AWS Profile and SSO management.
* [Judo](https://github.com/giacomopiccinini/judo) ⭐ 119 | 🐛 1 | 🌐 Rust | 📅 2026-02-16 A multi-database TUI for ToDo lists, using Rust + Ratatui + SQLite
* [procmux](https://github.com/napisani/procmux) ⭐ 111 | 🐛 2 | 🌐 Python | 📅 2025-11-23 a TUI for running multiple commands in parallel in easily switchable terminals
* [portfolio\_rs](https://github.com/MarkusZoppelt/portfolio_rs) ⭐ 96 | 🐛 3 | 🌐 Rust | 📅 2026-09-21 A command line tool for managing financial investment portfolios.
* [openmux](https://github.com/monotykamary/openmux) ⭐ 90 | 🐛 2 | 🌐 TypeScript | 📅 2026-06-16 A terminal multiplexer with master-stack layout (Zellij-style)
* [tui-slides](https://github.com/Chleba/tui-slides) ⭐ 83 | 🐛 2 | 🌐 Rust | 📅 2024-09-12 A terminal presentation tool capable of rendering images and many other widgets.
* [tododo](https://github.com/bmarse/tododo) ⭐ 71 | 🐛 3 | 🌐 Go | 📅 2025-09-05 A pretty TUI TODO.md manager for tasks and projects
* [pkm](https://github.com/wick3dr0se/pkm) ⭐ 64 | 🐛 1 | 🌐 Shell | 📅 2024-06-17 A super minimal TUI package manager wrapper written in BASH v4.2+
* [productivity-timer](https://github.com/h-sifat/productivity-timer) ⭐ 61 | 🐛 2 | 🌐 TypeScript | 📅 2026-05-15 A command line time tracker application with a sleek TUI.
* [linear-tui](https://github.com/roeyazroel/linear-tui) ⭐ 60 | 🐛 2 | 🌐 Go | 📅 2026-09-08 A terminal user interface for Linear built with Go and tview.
* [multranslate](https://github.com/Lifailon/multranslate) ⭐ 60 | 🐛 1 | 🌐 JavaScript | 📅 2025-03-31 A TUI for translating text in multiple translators simultaneously, with support for translation history and language detection
* [pdiary](https://github.com/manipuladordedados/pdiary) ⭐ 48 | 🐛 2 | 🌐 Python | 📅 2022-09-12 A simple terminal diary journal application written in Python with encryption support
* [drako](https://github.com/lucky7xz/drako) ⭐ 42 | 🐛 0 | 🌐 Go | 📅 2026-09-20 A grid-based, customizable and extendable command- and TUI-Deck launcher
* [hnjobs](https://github.com/mwinters0/hnjobs) ⭐ 41 | 🐛 0 | 🌐 Go | 📅 2025-09-10 Find your next job on Who's Hiring
* [trx](https://github.com/pie-314/trx) ⭐ 41 | 🐛 68 | 🌐 Rust | 📅 2026-07-06 - Terminal package manager with fuzzy search and keyboard-driven package discovery.
* [Chronos](https://github.com/samuelstranges/chronos) ⭐ 39 | 🐛 2 | 🌐 Go | 📅 2026-09-25 A Vimlike Calendar TUI
* [TUI\_ProjectManager](https://github.com/NicoDblc/TUI_ProjectManager) ⭐ 33 | 🐛 0 | 🌐 Rust | 📅 2024-03-18 A simple project-based todo list written in Rust
* [tuihub](https://github.com/ashis0013/tuihub) ⭐ 25 | 🐛 0 | 🌐 Go | 📅 2023-09-22 A utility hub/dashboard for personal use
* [HydroToDo](https://github.com/Henriquehnnm/hydrotodo) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2026-01-16 A simple and beautiful TUI to-do list
* [tui-deck](https://github.com/mebitek/tui-deck) ⭐ 23 | 🐛 1 | 🌐 Go | 📅 2024-02-25 A TUI frontend for Nextcloud Deck app written in GO
* [levite](https://github.com/RauliL/levite) ⭐ 15 | 🐛 0 | 🌐 C++ | 📅 2026-09-16 A TUI spreadsheet application that uses an RPN formulas and features a vi-friendly interface
* [pream-team](https://github.com/nikoladucak/pream-team/) ⭐ 13 | 🐛 5 | 🌐 Python | 📅 2024-02-26 a TUI utility that helps you keep track of your teams GitHub PRs across multiple repositories
* [Brief](https://github.com/WilliamAGH/brief) ⭐ 12 | 🐛 10 | 🌐 Java | 📅 2026-08-14 Terminal-first OpenAI chat client with slash-command palette and local tool execution.
* [HydroFetch](https://github.com/Henriquehnnm/hydrofetch) ⭐ 12 | 🐛 0 | 🌐 Shell | 📅 2026-01-25 A fast, beautiful, and lightweight system information tool written exclusively for the Fish shell.
* [ttm](https://github.com/vst93/ttm) ⭐ 11 | 🐛 0 | 🌐 Go | 📅 2026-08-20 SSH bookmark manager with Bubble Tea TUI — connect, manage and sync via Gist
* [GeekCalendar](https://github.com/fearlessgeekmedia/GeekCalendar) ⭐ 9 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-03 TUI calendar with vim key bindings, which can import from calcure or calcurse.
* [pagerduty-tui](https://github.com/Mk555/pagerduty-tui) ⭐ 9 | 🐛 2 | 🌐 Rust | 📅 2024-12-11 Minimalistic terminal UI to manage triggered incidents
* [ekphos](https://github.com/hanebox/ekphos) ⭐ 8 | 🐛 0 | 🌐 Rust | 📅 2026-09-23 A fast, lightweight, markdown research tool written in rust
* [tuidict](https://github.com/404Simon/tuidict) ⭐ 8 | 🐛 1 | 🌐 Rust | 📅 2026-09-13 Fast offline dictionary with in-app downloads and multi-language support from FreeDict
* [Bada](https://github.com/Han8931/bada) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2026-08-17 A minimalist, Vim-first task manager designed to help you focus without distraction.
* [fuzz.fish](https://github.com/jedipunkz/fuzz.fish) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2026-09-23 A fuzzy finder for the Fish shell with preview panes for command history, files, git branches, worktrees, and commits
* [Tomatui](https://github.com/Hiro-Chiba/tomatui) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2026-09-16 A Pomodoro timer with a full-screen TUI, a minimal one-line mode, and local session statistics.
* [Paca](https://github.com/wes/paca) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-27 Task, timer, and Stripe invoicing for projects, with local-first SQLite storage
* [abook](https://abook.sourceforge.io/) TUI addressbook with [mutt](http://www.mutt.org/) integration
* [calcurse](https://calcurse.org/) calendar and scheduling application for the command line
* [tuiserial](https://github.com/Horldsence/tuiserial) TUI Serial Port Tool for Edge Computing Devices

***

</details>

<details open><summary><h2>Screensavers</h2></summary>

* [gitlogue](https://github.com/unhappychoice/gitlogue) ⭐ 4,998 | 🐛 12 | 🌐 Rust | 📅 2026-09-25 A TUI screensaver that visualizes Git commit history in your terminal
* [weathr](https://github.com/veirt/weathr) ⭐ 3,060 | 🐛 19 | 🌐 Rust | 📅 2026-08-12 A terminal weather app with ASCII animations for weather visualization
* [astroterm](https://github.com/da-luce/astroterm) ⭐ 2,056 | 🐛 36 | 🌐 C | 📅 2026-09-11 A planetarium for your terminal! Explore stars, planets, constellations, and more
* [neo](https://github.com/st3w/neo) ⭐ 964 | 🐛 16 | 🌐 C++ | 📅 2024-04-02 Simulates the digital rain from "The Matrix"
* [rxpipes](https://github.com/inunix3/rxpipes) ⭐ 46 | 🐛 0 | 🌐 Rust | 📅 2024-09-07 2D recreation of the ancient Pipes screensaver for terminals.
* [pond](https://gitlab.com/alice-lefebvre/pond) A soothing in-terminal idle screen that simulates a little pond.

***

</details>

<details open><summary><h2>Web</h2></summary>

* [carbonyl](https://github.com/fathyb/carbonyl) ⭐ 19,502 | 🐛 90 | 🌐 Rust | 📅 2024-07-01 Chromium running inside your terminal
* [browsh](https://github.com/browsh-org/browsh) ⭐ 19,071 | 🐛 241 | 🌐 JavaScript | 📅 2025-07-11 A fully-modern text-based browser, rendering to TTY and browsers
* [rtorrent](https://github.com/rakshasa/rtorrent) ⭐ 4,868 | 🐛 386 | 🌐 C++ | 📅 2026-09-25 A text-based BitTorrent client written in C++
* [haxor-news](https://github.com/donnemartin/haxor-news) ⭐ 4,090 | 🐛 42 | 🌐 Python | 📅 2022-04-22 Browse Hacker News like a haxor: A Hacker News command line interface (CLI)
* [newsboat](https://github.com/newsboat/newsboat) ⭐ 3,915 | 🐛 416 | 🌐 C++ | 📅 2026-09-20 An RSS/Atom feed reader for the text console
* [surge](https://github.com/surge-downloader/surge) ⭐ 3,549 | 🐛 58 | 🌐 Go | 📅 2026-09-25 A blazing fast, beautiful TUI download manager built in Go.
* [textual-web](https://github.com/Textualize/textual-web) ⭐ 1,469 | 🐛 23 | 🌐 Python | 📅 2024-08-30 Run TUIs and terminals in your browser
* [Slumber](https://github.com/LucasPickering/slumber) ⭐ 1,228 | 🐛 9 | 🌐 Rust | 📅 2026-09-24 Terminal-based HTTP/REST client
* [w3m](https://github.com/tats/w3m) ⭐ 1,082 | 🐛 79 | 🌐 C | 📅 2024-08-19 A text-mode WWW browser
* [cloudflare-speed-cli](https://github.com/kavehtehrani/cloudflare-speed-cli) ⭐ 1,045 | 🐛 0 | 🌐 Rust | 📅 2026-07-27 Internet speed test via Cloudflare
* [eilmeldung](https://github.com/christo-auer/eilmeldung) ⭐ 1,013 | 🐛 2 | 🌐 Rust | 📅 2026-09-23 RSS reader, supporting many RSS providers, bulk-operations and configuration options.
* [hackernews-TUI](https://github.com/aome510/hackernews-TUI) ⭐ 720 | 🐛 10 | 🌐 Rust | 📅 2026-03-29 A Terminal UI to browse Hacker News
* [nyaa](https://github.com/Beastwick18/nyaa) ⭐ 701 | 🐛 16 | 🌐 Rust | 📅 2026-02-28 A nyaa.si TUI for browsing and downloading torrents
* [castero](https://github.com/xgi/castero) ⭐ 684 | 🐛 33 | 🌐 Python | 📅 2026-04-21 A TUI app to listen to podcast
* [elinks](https://github.com/rkd77/elinks) ⭐ 638 | 🐛 121 | 🌐 C | 📅 2026-09-14 ELinks (HTTP/FTP/..) brower with mujs javascript support.
* [bulletty](https://github.com/CrociDB/bulletty) ⭐ 447 | 🐛 23 | 🌐 Rust | 📅 2026-09-21 A pretty feed reader (ATOM/RSS) that stores articles in Markdown files
* [twterm](https://github.com/ryota-ka/twterm) ⭐ 244 | 🐛 23 | 🌐 Ruby | 📅 2023-12-15 A full-featured TUI Twitter client
* [podliner](https://github.com/timkicker/podliner) ⭐ 173 | 🐛 4 | 🌐 C# | 📅 2026-09-14 A cross-platform podcast client
* [Canard](https://github.com/mrusme/canard) ⚠️ Archived A command line TUI client for the [Journalist](https://github.com/mrusme/journalist) ⚠️ Archived RSS aggregator.
* [stegodon](https://github.com/deemkeen/stegodon) ⭐ 91 | 🐛 3 | 🌐 Go | 📅 2026-07-05 SSH-first federated microblog with ActivityPub, web UI, and RSS feeds
* [rfc\_reader](https://github.com/ozan2003/rfc_reader) ⭐ 73 | 🐛 0 | 🌐 Rust | 📅 2026-09-11 A tool to read RFCs (Request for Comments) with a TUI, allowing you to fetch, cache, and browse RFC documents.
* [tblogs](https://github.com/ezeoleaf/tblogs) ⭐ 66 | 🐛 5 | 🌐 Go | 📅 2026-07-03 Read and browse development blogs from your terminal
* [searxngr](https://github.com/scross01/searxngr) ⭐ 54 | 🐛 2 | 🌐 Python | 📅 2026-09-24 Web search TUI for SearXNG
* [CatenaVetus](https://github.com/jimbob88/CatenaVetus) ⭐ 23 | 🐛 2 | 🌐 Python | 📅 2026-09-16 A TUI for reading the Church Fathers
* [omaro](https://github.com/Rolv-Apneseth/omaro) ⭐ 21 | 🐛 4 | 🌐 Rust | 📅 2026-09-25 TUI to browse posts and comments on lobste.rs
* [bombadillo](https://bombadillo.colorfield.space/) A TUI browser for the non-web: Gopher, Gemini, Finger
* [Chawan](https://chawan.net) A TUI web (and (S)FTP, Gopher, Gemini) browser with CSS, inline image and JavaScript support.
* [Lagrange](https://gmi.skyjake.fi/lagrange) Lagrange is a cross-platform client for browsing Geminispace
* [LYNX](https://lynx.invisible-island.net/) A text based Terminal browser
* [rttt](https://gitlab.com/BlackEdder/rttt) A Hackernews, RSS and Reddit reader for the terminal written in C++.

***

</details>

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-25._
