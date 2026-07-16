# Contributing to Awesome BYOK Apps

Thanks for helping curate this list. The goal is a high-signal catalog of **real, working** apps and providers that support Bring-Your-Own-Key for AI.

## What belongs here

- **Apps** that let the end user supply their own AI API key (OpenAI, Anthropic, Google, OpenRouter, local-model providers, etc.) instead of paying a subscription markup.
- **IDEs and terminals** with first-class BYOK support.
- **Gateways and proxies** that route requests using the user's own provider keys.
- **Providers** that issue API keys for direct inference access.

## What doesn't belong

- Apps that only accept a vendor-issued subscription and hide the provider key behind it.
- Work-in-progress or "coming soon" entries.
- Forks that don't add value over the upstream.
- Paid placements — the list is strictly merit-based.
- Abandoned apps (no commits in 12+ months and no working demo).
- Key-resale / relay services that resell metered access to third-party
  models or subscriptions (shared-account gateways and proxies). Gateways
  are welcome only if they route requests using the user's own provider keys.

## Entry format

Use this exact format, with a single space before the dash and an em-dash (`—`) between name and description:

```markdown
- [App Name](https://example.com) — One-line description, under 100 chars, ends with a period.
```

Rules:
- Description describes what the app **does for the user**.
- Alphabetical order within each section (case-insensitive, ignoring leading "the").
- Link to the canonical URL (primary domain or GitHub repo). Avoid redirect trackers.
- No marketing adjectives ("best", "amazing"). Just facts.
- No emoji unless the project's canonical name contains one.

## Proposing an app

Open a PR adding your app to the appropriate section. Include in the PR description:

- **Disclosure** — if you're the author of, or otherwise affiliated with,
  the project you're proposing, say so in the PR description. Affiliated
  submissions are welcome; undisclosed ones may be closed.
- **Live URL or repo** — must be reachable.
- **How the user supplies their key** (settings panel, env var, config file).
- **Which providers are supported**.
- **Confirmation** the app is actively maintained (commit in the last 12 months or a working hosted version).

## Proposing a provider

Open a PR to the [Providers](../README.md#providers) section with:

- **Direct link** to the API-key generation page.
- **One-line summary** of what models the key unlocks.
- **Note** if there's a free tier.

## Quality bar

Maintainers may:
- Edit the description for consistency.
- Move an entry to a more appropriate section.
- Reject an entry that doesn't meet the bar — with a reason.

Every link in the list should be **genuinely worth a click**. If the list gets noisy, it stops being awesome.

## Licensing

By contributing, you agree your contribution is released under [CC0](../README.md#license) (public domain).

## Questions

Open a Discussion or Issue on the repo.
