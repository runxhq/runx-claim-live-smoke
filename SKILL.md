---
name: claim-live-smoke
description: Live production smoke skill for GitHub App claim verification.
source:
  type: cli-tool
  command: node
  args:
    - -e
    - "process.stdout.write('runx claim live smoke')"
  timeout_seconds: 10
inputs: {}
runx:
  input_resolution:
    required: []
---
# Claim Live Smoke

Small public skill used to verify the runx GitHub App claim flow in production.
