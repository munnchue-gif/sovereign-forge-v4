# Sovereign Forge V4 — Architecture (excerpt)

See full 99k source in original dump. Core ideas:

- MessageBus: topic pub-sub, request-response, topology for UI
- Keychain: pin router in VRAM, warm in ZRAM zstd, cold on NVMe
- Socket Bay: drop .py agents, auto-register
- Cockpit: Chat | Keychain | Telemetry | Topology | SocketBay panels
- deploy.sh one-shot bootstrap
