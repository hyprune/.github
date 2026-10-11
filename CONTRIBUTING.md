# Contributing to Hyprune

Hyprune is early, building in the open. Start with the [concepts](https://hyprune.com/concepts/) and [repository boundaries](https://hyprune.com/rfcs/0001-umbrella/). Code, original world art, accessible interaction, docs and concrete design review all help.

## Changes

1. Choose the repository that owns the change. Describe a concrete problem and intended behavior.
2. For public API/format, capability or boundary changes, propose an RFC amendment in docs and matching schemas/fixtures first. Link exact commits from consumer PRs.
3. Keep PRs focused, explain the result, and provide relevant test evidence. State the exact Hyprland build for runtime work and distinguish nested tests from real DRM/hardware-cursor tests.
4. Run `npm ci && npm run build && npm run check:links` for docs or `npm ci && npm test` for schemas. Other repos document checks as implementations land.
5. Record compatibility, migration and user-visible changes. Never push generated build output or local secrets.
6. Keep machine-specific values (review directories, build hosts) out of repositories: tools read them from the environment or an optional `~/.config/hyprune/dev.env`. See [Contributing](https://hyprune.com/contributing/).

## Rights

Contribute only work you have the right to license under the repository's terms. Code is MIT. World content defaults to CC-BY-4.0; official dependencies may be CC0 or CC-BY-4.0 with provenance. Keep source, author, license and modifications alongside every asset. There is no CLA at this stage.

## Review and community

The founding owner is interim steward; maintainers gain scoped responsibility through consistent contributions. Architectural decisions use public RFCs and recorded rationale; see [governance](https://hyprune.com/governance/). Follow [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md). Security issues go through [SECURITY.md](SECURITY.md), not public bug reports.

Co-author trailers credit actual contributions; never add someone without their contribution/consent. Keep the desktop recoverable, and prefer small, testable contracts over speculative features.
