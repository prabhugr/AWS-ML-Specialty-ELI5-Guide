# ☁️ Cloud Computing Mind Map

An interactive visual mind map exploring cloud computing domains and AWS services. Built as a study and reference tool for cloud practitioners.

**[🔗 Live Demo](https://gangprab.github.io/cloud-computing-mindmap/)**

## Features

- **7 Core Domains** — Compute, Storage, Database, Networking, Security & Governance, Data & Analytics, AI & ML
- **19 Specialty Domains** — App Integration, DevOps, Migration, IoT, Media, Healthcare, Quantum, and more
- **240+ AWS Services** — with descriptions, unique facts, and developer guide links
- **Progressive Drill-Down** — start from one bubble, explore deeper with each click
- **Hover Preview** — hover the root to peek at top-level domains
- **Immersive Visuals** — particle background that shifts color per domain, breathing glow, click ripples
- **Instant Highlight** — hover a bubble to dim siblings and focus
- **Service Info Panel** — click any leaf service for a description, fun fact, and docs link
- **Mobile Friendly** — touch pan, pinch zoom, long-press for tooltips
- **Zero Dependencies** — pure HTML + SVG + vanilla JS, no frameworks or build step

## Structure

```
index.html          → UI, interactions, animations
data/
  tree.js           → Domain hierarchy (cloud-agnostic categories)
  services.js       → 240+ service descriptions, facts, and doc URLs
  services.json     → Same data in JSON format
```

## Roadmap

- [ ] Add GCP and Azure service equivalents per domain

## Cloud-Agnostic Design

The domain categories (Compute, Storage, Database, etc.) are intentionally cloud-agnostic. AWS services are the first branch — GCP and Azure branches can be added under the same taxonomy for cross-cloud comparison.

## License

MIT — see [LICENSE](LICENSE)
