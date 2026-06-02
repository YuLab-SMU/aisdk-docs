# aisdk-docs

Documentation portal for the **aisdk** family of R packages — a unified
[Quarto](https://quarto.org) website that introduces the family and links to
each package.

🌐 **Site:** <https://yulab-smu.top/aisdk-docs/>

## Packages covered

| Package | Role |
|---|---|
| [aisdk](https://github.com/YuLab-SMU/aisdk) | Self-contained core (on CRAN) |
| [aisdk.providers](https://github.com/YuLab-SMU/aisdk.providers) | Extra provider adapters |
| [aisdk.slm](https://github.com/YuLab-SMU/aisdk.slm) | Local model inference |
| [aisdk.orchestration](https://github.com/YuLab-SMU/aisdk.orchestration) | Multi-agent Flow / Team / Mission |
| [aisdk.mcp](https://github.com/YuLab-SMU/aisdk.mcp) | Model Context Protocol client/server |
| [aisdk.skills](https://github.com/YuLab-SMU/aisdk.skills) | Skill ecosystem |
| [aisdk.channels](https://github.com/YuLab-SMU/aisdk.channels) | Messaging integrations |
| [aisdk.datatools](https://github.com/YuLab-SMU/aisdk.datatools) | Charts & reports |
| [aisdk.shiny](https://github.com/YuLab-SMU/aisdk.shiny) | Shiny web UI |

## Build locally

```sh
quarto preview      # live preview
quarto render       # render to ./docs
```

The pages are descriptive (no live R execution), so only Quarto is required —
no R toolchain.

## Publishing

Every push to `main` renders the site and publishes it to the `gh-pages`
branch via GitHub Actions (`.github/workflows/publish.yml`). Enable GitHub
Pages with source = `gh-pages` branch (root).
