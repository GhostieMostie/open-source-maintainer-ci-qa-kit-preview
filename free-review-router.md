# Free Review Router

Use this before asking for review, bounty credit, or maintainer attention. It helps decide whether the work is ready for review or still needs evidence.

## Route The Work

| Decision | Signals | Smallest next action |
| --- | --- | --- |
| `ready-for-review` | Reproduction, validation, CI status, risk, rollback, and scope are all documented | Ask for review with one concise evidence summary |
| `needs-evidence` | Missing reproduction, validation, screenshots, logs, or rollback | Fill the evidence gap before posting |
| `needs-ci-classification` | CI is red, unknown, auth-only, fork-secret, flaky, or infra-owned | Classify CI before treating it as source-code failure |
| `needs-payment-clarification` | Assignment, bounty, reward, or claim route is unclear | State only public facts or ask one narrow rules question |
| `not-ready` | Scope is broad, risky, overlapping, or not reproducible | Reduce scope before implementation or review |

## Copy/Paste Review Card

```md
Review route:

- Scope:
- Reproduction:
- Validation:
- CI status:
- Known risk:
- Rollback:
- Payment/claim facts:
- Decision: ready-for-review | needs-evidence | needs-ci-classification | needs-payment-clarification | not-ready
- Smallest next action:
```

## When To Use The Full Kit

Use the full kit when you need a generated evidence pack, public claim safety check, reviewer risk register, CI matrix, and review-ready PR summary in one folder.

Full kit: https://buy.polar.sh/polar_cl_TKClMaFhmU2f2LYHXKLnBdRN8rDgyvZTudbzU1zFj0G
