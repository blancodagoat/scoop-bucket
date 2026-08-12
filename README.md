# blancodagoat's Scoop bucket

[![Tests](https://github.com/blancodagoat/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/blancodagoat/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/blancodagoat/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/blancodagoat/scoop-bucket/actions/workflows/excavator.yml)

[Scoop](https://scoop.sh) bucket for three small Windows tools that stay out of your way. Manifests track the latest GitHub release automatically.

| App | What it does |
|---|---|
| [Recite](https://github.com/blancodagoat/recite) | Copy text from anything on screen with Windows' built-in OCR: hotkey, drag, done. |
| [Memento](https://github.com/blancodagoat/memento) | Tray screenshot tool that idles at ~8 MB: region and display capture, PNG plus clipboard. |
| [DejaVu](https://github.com/blancodagoat/DejaVu) | Instant replay with a crash-safe disk buffer: one key saves your last 5 to 25 minutes. |

## Install

```powershell
scoop bucket add blancodagoat https://github.com/blancodagoat/scoop-bucket
scoop install recite memento dejavu
```

All three are MIT licensed, offline, and telemetry-free.
