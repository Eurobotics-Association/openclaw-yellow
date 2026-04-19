# 🗺️ Open-Claw Yellow Roadmap

Author: F.M. Robert Vergnes / robert.vergnes@yahoo.fr  
Assisted-by: OpenAI Codex: GPT-5.3-Codex [exec_command] [apply_patch]  
Last-Updated: 2026-04-19

## Near-term roadmap

### Phase 0 — Define

- refine governance and approval boundaries
- define non-destructive attach model
- align baseline posture with OpenClaw + openclaw-ansible references

### Phase 1 — Prove (Oscar-26)

- validate fresh-install mode and attach mode behavior
- validate read-only inventory logic for existing OpenClaw
- validate user-approval path before upgrading older OpenClaw
- validate auditability, recoverability, and security baseline checks
- run early validation in `oscar-infra-private`

### Phase 2 — Stabilize public baseline

- merge validated stable results into `openclaw-yellow`
- move `openclaw-yellow` `main` into the official stable working baseline role
- target this transition in days/weeks, not as a distant milestone

### Phase 3 — Package and expand

- publish reusable docs/templates/playbook guidance
- publish practical examples for operator governance scenarios
- broaden compatibility coverage
- integrate community feedback
- keep scope pragmatic and readable

## Continuous constraints

- Stay an overlay, not a fork.
- Prefer wrapper/drop-in design.
- Preserve existing user config whenever possible.
- Avoid implementation claims not yet proven.
