# beacon

Starter patterns for logs, metrics, traces, and operational visibility.

## Purpose

Give the ecosystem a clear observability baseline so platform repos do not treat telemetry as an afterthought.

## Role in the ecosystem

- Visibility layer for `orbit`, `synapse`, and `summit`
- Built on top of `nimbus`
- Neighbor to `aegis`

## Status

Documentation-first starter with example telemetry config and operational notes.

## Tech stack

- OpenTelemetry config samples
- YAML
- Markdown

## Structure

```text
beacon/
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

- `nimbus`
- `aegis`
- `orbit`

## Future direction

Add dashboards and SLO references, but keep the repo focused on platform observability patterns.
