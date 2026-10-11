# Hyprune

### What if the computer itself were an explorable world?

Hyprune is an explorable, world-driven desktop environment for **Hyprland**. Your workspaces become places: walk between workspace homes, keep live application windows on the walls, carry a window to the next area, and get your ordinary desktop back with one key. It is built to grow into a framework: new worlds, screen types, widgets, movement modes, integrations, or your own shell.

**Early preview, building in the open.** Hyprune targets Hyprland 0.56.2. Core, shell and SDK speak IPC 0.19, and the official world Lumen Reach is at 0.9.2. Every repository below is public.

[hyprune.com](https://hyprune.com) · [Try Hyprune](https://hyprune.com/first-session/) · [Progress](https://hyprune.com/progress/) · [Roadmap](https://hyprune.com/roadmap/) · [Schema reference](https://hyprune.com/reference/schema/) · [Contribute](https://github.com/hyprune/.github/blob/main/CONTRIBUTING.md)

| Repository | What it is |
| --- | --- |
| [hyprune](https://github.com/hyprune/hyprune) | The front door: install, starter kits, Nix flake, NixOS and Home Manager modules, Arch installer. **Start here.** |
| [core](https://github.com/hyprune/core) | The Hyprland plugin, the `hypruned` daemon and the 3D world runtime. |
| [shell](https://github.com/hyprune/shell) | The reference Quickshell UI: HUD, Director, settings and overlays, replaceable through the IPC contract. |
| [worlds](https://github.com/hyprune/worlds) | Official original worlds (Lumen Reach, Switchyard), their sources, build pipeline and provenance. |
| [sdk](https://github.com/hyprune/sdk) | TypeScript IPC client, the `hyprune` CLI for world and extension authors, and a mock daemon. |
| [schema](https://github.com/hyprune/schema) | Versioned JSON Schemas for world packages, IPC and manifests, with a validator. |
| [docs](https://github.com/hyprune/docs) | The hyprune.com site: guides, concepts, RFCs and the schema reference. |
| [.github](https://github.com/hyprune/.github) | Organisation profile and community defaults. |

Small boundaries make independent contributions possible. World art stays separate from the runtime, the UI stays separate from compositor authority, and extensions run outside the compositor.

**Contributing:** read [CONTRIBUTING.md](https://github.com/hyprune/.github/blob/main/CONTRIBUTING.md), then open an issue or pull request in the repository that owns the change. **Security:** report privately through GitHub's *Report a vulnerability* button ([SECURITY.md](https://github.com/hyprune/.github/blob/main/SECURITY.md)). **Conduct:** [Code of Conduct](https://github.com/hyprune/.github/blob/main/CODE_OF_CONDUCT.md), contact conduct@hyprune.com.

Code: MIT. Original world content: CC-BY-4.0, with documented CC0/CC-BY dependencies. No ripped game assets or derivatives.
