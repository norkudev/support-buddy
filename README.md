# support-buddy

Just a mockup/prototype/idea for how IT support could handle production incidents involving identifiable flows. Right now, IT support usually has to manually dig through tables and logs to figure out where something broke.

This project explores the idea of pulling all relevant data sources into Node-RED, letting you build and adjust requirements or checks on the fly. The goal is to make troubleshooting faster, clearer, and way less painful.

**Tech stack**:
- **Node-RED** → Orchestration
- **Metabase** → Data queries & visualization
- **Postgres** → Sample data sources

## Prerequisites

- **nix + direnv**

## Quickstart

```bash
direnv allow
TODO
```

## Future demo ideas

- **Elasticsearch** → Logs
- **Prometheus** → Service stability