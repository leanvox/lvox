# lvox — Leanvox CLI

Lean voice API from your terminal.

## Install

### Homebrew (macOS / Linux)
```bash
brew install leanvox/tap/lvox
```

### Shell script
```bash
curl --proto '=https' --tlsv1.2 -LsSf https://github.com/leanvox/lvox/releases/latest/download/lvox-installer.sh | sh
```

### PowerShell (Windows)
```powershell
powershell -ExecutionPolicy ByPass -c "irm https://github.com/leanvox/lvox/releases/latest/download/lvox-installer.ps1 | iex"
```

## Quick Start

```bash
lvox auth login
lvox generate "Hello from Leanvox!" -o hello.mp3
lvox voices curated
lvox transcribe meeting.mp3
lvox transcribe long-meeting.mp3 --no-wait
lvox jobs list --type stt
```

## Commands

| Command | Description |
|:--|:--|
| `generate` | Generate speech from text |
| `stream` | Stream speech to file |
| `dialogue` | Multi-speaker dialogue |
| `transcribe` | Transcribe audio with speaker diarization |
| `jobs list/get` | Manage async TTS and STT jobs |
| `voices` | List and manage voices |
| `voices curated` | Browse 238 curated Pro voices |
| `balance` | Check credit balance |
| `auth` | Login, signup, manage API keys |

## Docs

Full documentation at [leanvox.com/docs](https://leanvox.com/docs)

## License

MIT
