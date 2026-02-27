# OpenClix

Open-source, local-first mobile app retention and engagement automation.

OpenClix helps product and engineering teams ship agent-based mobile app retention workflows with readable, config-driven, on-device logic.

## What OpenClix provides

- `openclix-init`: integration automation for mobile app startup/event/lifecycle wiring.
- `openclix-design-campaigns`: campaign config automation for onboarding, habit, and re-engagement flows.
- `openclix-analytics`: retention and engagement impact measurement automation.
- `openclix-update-campaigns`: conservative campaign operation recommendations.
- `retention_ops_automation.sh`: OpenClaw, Claude Code, and Codex review prompt automation.

## Agent workflow

```text
openclix-init
  -> openclix-design-campaigns
  -> openclix-analytics
  -> openclix-update-campaigns
  -> retention_ops_automation.sh (OpenClaw / Claude Code / Codex loop)
```

## Directional guardrails

- Local-first: rule evaluation runs on-device.
- Source-first: client runtime is vendored in your repo.
- Not a hosted full platform: server-triggered real-time push infrastructure is out of scope.

## Links

- Main repository: https://github.com/openclix/openclix
- Home: https://openclix.ai
- Docs: https://docs.openclix.ai
- Organization: https://github.com/openclix
