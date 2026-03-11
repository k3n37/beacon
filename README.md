# observability-stack

Starter patterns for logs, metrics, traces, and operational visibility.

## Purpose

Give the ecosystem a clear observability baseline so platform repos do not treat telemetry as an afterthought.

## Role in the ecosystem

- Visibility layer for `master-platform`, `ai-platform`, and `saas-platform`
- Built on top of `infrastructure-platform`
- Neighbor to `security-platform`

## Status

Documentation-first starter with example telemetry config and operational notes.

## Tech stack

- OpenTelemetry config samples
- YAML
- Markdown

## Structure

```text
observability-stack/
├── configs/
│   └── otel-collector.yaml
├── docs/
│   └── dashboards.md
├── .editorconfig
├── .gitignore
├── README.md
└── ROADMAP.md
```

## Getting started

Use the collector config as a reference baseline for local or non-prod telemetry setups.

## Related repositories

- `infrastructure-platform`
- `security-platform`
- `master-platform`

## Future direction

Add dashboards and SLO references, but keep the repo focused on platform observability patterns.
