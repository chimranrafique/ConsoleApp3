---
description: Minimal gh-aw smoke test
on:
  workflow_dispatch:

permissions:
  contents: read
  copilot-requests: write

network: defaults

safe-outputs:
  mentions: false
  allowed-github-references: []
  create-issue:
    title-prefix: "[aw-smoke-test] "
    labels: [aw-smoke-test]
---

# AW Smoke Test

Call `safeoutputs.noop` exactly once with message:
"AW smoke test succeeded."
