# Sovereign Forge V4

Adaptive robust architecture from the Fable path.

Key decisions:
- SvelteKit over React (compile-time reactivity for live cockpit)
- Custom AsyncIO pub-sub MessageBus over LangGraph (hot-plug Socket Bay)
- ZRAM three-tier Keychain (VRAM HOT / ZRAM WARM / NVMe COLD)
- No Docker — Linux namespaces + in-process agents

Full architecture document is in ARCHITECTURE.md (from Arena_v4-socket).

Hardware target: Pop!_OS, RTX 5080 16GB, 96GB RAM, NPU reserved.
