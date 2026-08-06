# Hi, I'm Pax 👋

Linux systems administrator. I run a production homelab (Proxmox, ZFS, monitored
3-2-1 backups, NixOS config-as-code) and build the automation and AI tooling that
keeps it running.

**Open to remote work:** systems administration, DevOps, and infrastructure
automation, salaried or contract. Also freelance Linux / self-hosting projects.

### What I do

- **Linux & infrastructure:** Proxmox virtualization, ZFS storage, monitored 3-2-1 backups, Tailscale mesh networking
- **Observability:** Prometheus + Grafana, custom exporters, alerting
- **Automation:** Python (asyncio, REST APIs, systemd services), config-as-code with NixOS
- **AI / LLM:** RAG pipelines, LLM agents with tool-calling (MCP), self-hosted inference
- **IT support:** I run an independent computer-repair business (diagnostics, repair, data recovery)

### Featured projects

- **[brain-rag](https://github.com/pxlwh/brain-rag):** hybrid semantic + keyword RAG engine over a markdown corpus. Vector + FTS5 retrieval fused and cross-encoder reranked, LLM-synthesized cited answers, served over MCP and a warm-model daemon.
- **[nix-deploy-gate](https://github.com/pxlwh/nix-deploy-gate):** a NixOS deploy that refuses to lie about what's running. Gates on a clean, pushed tree so every live generation maps to a commit, builds on a separate host so constrained targets never compile, and tags generation→commit for incident response.
- **[homelab-backup](https://github.com/pxlwh/homelab-backup):** layered 3-2-1 backup toolkit: pull-based data sync with consistent SQLite dumps, ZFS/btrfs snapshots as history, encrypted borg offsite, and success-gated freshness monitoring.
- **[homelab-monitoring](https://github.com/pxlwh/homelab-monitoring):** Prometheus/Grafana observability for Proxmox + ZFS. Custom node_exporter collectors for pool health, scrub/resilver progress, and container inventory that the stock exporters miss.
- **[discord-persona-bot](https://github.com/pxlwh/discord-persona-bot):** self-hosted Discord LLM bot whose entire personality is one validated TOML file. Dual-provider text/vision routing across two API dialects, clock-driven moods, channel awareness, Ed25519-signed HTTP interactions.
- **[discord-presence-suite](https://github.com/pxlwh/discord-presence-suite):** four token-free Discord rich-presence daemons (Steam, Navidrome, homelab, Jellyfin). Async Python with D-Bus/MPRIS, Prometheus, and Jellyfin API integration.
- **[prod-is-red](https://github.com/pxlwh/prod-is-red):** your terminal changes color depending on which machine you're typing into. Production is red. Per-host palette + window border on ssh, driven entirely by the remote's terminal title, so nothing tracks state.
- **[booru-viewer](https://github.com/pxlwh/booru-viewer):** cross-platform Qt6 desktop image browser. Fully themeable, zero telemetry.

### Currently

- Publishing more of my infrastructure and AI projects in the open
- Working toward CompTIA Security+

### Reach me

- Website: [pax.moe](https://pax.moe)
- Business Website: [lolpax.moe](https://lolpax.moe)
- Email: hire@pax.moe

### Tech

`Linux` `Proxmox` `ZFS` `Docker` `Prometheus` `Grafana` `Python` `Bash` `NixOS` `Tailscale` `nginx` `Git`
