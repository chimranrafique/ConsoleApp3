---
description: Minimal gh-aw smoke test
on:
  workflow_dispatch:

permissions:
  contents: read
  copilot-requests: write

network: defaults
---

# AW Smoke Test

Call `safeoutputs.noop` exactly once with message:
"AW smoke test succeeded."
