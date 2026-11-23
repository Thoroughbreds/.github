<!--
Pull request template. Master copy: thoroughbreds-docs/docs/templates/pull-request-template.md
Each repo copies it to .github/pull_request_template.md.

Written for agents and people alike. Fill every section with facts, not ticks.
Write "None" rather than deleting a section.
Mechanical checks (types, tests, secret scanning) are enforced by CI, not here.
Human review is recorded by a GitHub approval, required by CODEOWNERS on sensitive paths.
-->

## Summary

<!-- What changes and why, in 2–4 sentences. -->

Closes #

## Provenance

- **Authored by:** agent / human / pair
- **Tool:** <!-- Claude Code, Codex, Qwen Code, Cursor, none -->
- **Model:** <!-- exact model ID, e.g. claude-opus-5-5. If the tool doesn't expose it: "unknown, via <tool>" -->
- **Driven by:** @ <!-- the GitHub handle of the person accountable for this change -->

## Changes

<!-- One line per commit or logical change. -->

-

## Tested beyond CI

- **Smoke test:** none / local / preview / staging <!-- the furthest environment where the change was run by hand or by an agent in a browser -->
- **Notes:** None <!-- what was checked and anything left untested,
  e.g. "Signed up as a new user; welcome email arrived. Not tested on iPad." -->


## Risk

- **Level:** low / medium / high
- **Sensitive areas touched:** none <!-- or list from: auth/security, payments/billing/Stripe, production data or sync, migrations, secrets/env/production config, public API compatibility, telemetry/privacy/tracking, destructive commands or deletes -->
- **Why this level:** <!-- one sentence; for any sensitive area, what could go wrong and how you limited it -->

## Deployment and rollback

- **Manual steps:** None <!-- migrations, env vars, feature flags, store or dashboard settings -->
- **Rollback:** Revert this PR

## Human decision needed

None
