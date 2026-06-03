# Open-Source Maintainer CI and QA Kit

A practical evidence-pack system for open-source maintainers, paid contributors, and small engineering teams.

Use it when a maintainer has to decide whether a PR, bug report, or paid-work follow-up is review-ready in under 5 minutes. The kit turns vague bugs, bounties, and pull requests into evidence packs with reproduction notes, validation commands, CI status, scope boundaries, reviewer risk notes, and public payment-claim safety checks.

## What It Helps With

- Make bug reports reproducible instead of vague.
- Package PR validation so maintainers can review faster.
- Separate code failures from auth-only or infrastructure-owned CI failures.
- Avoid unsafe bounty, assignment, or payment claims.
- Follow up with maintainers only when the comment reduces review work.

## Included In The Paid Kit

- No-dependency evidence-pack generator.
- Sample JSON brief that generates a ready-to-edit review folder.
- Start-here workflow for maintainers, contributors, and bounty work.
- Bug reproduction brief.
- CI evidence matrix.
- Browser QA script.
- Reviewer risk register.
- Bounty/payment readiness checklist.
- Public claim safety check.
- Review-ready PR summary.
- Maintainer-safe follow-up comment template.
- One-hour PR validation workflow.
- Worked fictional paid-bounty evidence pack.

## Free Preview

See the system shape before buying:

- [Sample generator brief](./sample-generator-brief.json)
- [Free review-ready checklist](./free-review-ready-checklist.md)

## Before / After

Weak follow-up:

> Fixed this, please review. CI failed because of secrets. Can I get the bounty?

Review-ready follow-up:

> Scope: upload validation copy only. Evidence: unsupported `.tmp` upload now shows accepted file types. Local checks: `npm test -- upload-validation`, `npm run typecheck`. Remote CI: deployment secret unavailable to forks, not code-actionable. Risk: product copy may need maintainer wording approval. Payment claim: not asserted until maintainer confirms assignment rules.

## Generated Output Shape

The sample generator brief turns structured input into a review folder. A short excerpt looks like this:

```md
## Scope

Update validation messaging and add focused tests for unsupported file extensions.

## Validation

- npm test -- upload-validation
- npm run typecheck
- npm run build

## Public Payment Facts

- Issue URL is public.
- No maintainer assignment has been posted yet.
- Payment route should be confirmed before a public claim.
```

Have a public-safe template request or CI/review handoff pain point?

- [Leave feedback or request a template](https://github.com/GhostieMostie/open-source-maintainer-ci-qa-kit-preview/issues/1)

## Get The Full Kit

Full kit = generator + templates + worked evidence pack for turning one PR into a review-ready folder. The full downloadable kit is $29:

https://buy.polar.sh/polar_cl_TKClMaFhmU2f2LYHXKLnBdRN8rDgyvZTudbzU1zFj0G

## Responsible Use

This kit helps you present evidence clearly. It does not guarantee acceptance, assignment, merge, bounty approval, or payment.

Use only factual public information when describing paid work.
