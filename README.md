# PNPM-HACK pnpm-overrides-secondery-workspace

pnpm so hack

```json
  "pnpm": {
    "overrides": {
      "react>loose-envify": "workspace:*"
    }
  }
```

then, local workspace  `packages/loose-envify@666.666.666` is not in the topo dependency graph.