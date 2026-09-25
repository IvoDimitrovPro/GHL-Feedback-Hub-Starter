# HighLevel Product Feedback — Ivo Dimitrov

A structured log of product, UX, UI and workflow feedback found while using HighLevel in real agency/client scenarios.

## Default workflow

- **New** — found, not yet sent / no response yet
- **Acknowledged** — HighLevel confirmed the feedback is valid
- **Planned** — HighLevel said it is on the roadmap / already being built
- **Shipped** — available and verified
- **Closed — works as designed** — not an issue / current behavior is expected
- **Closed — not pursuing** — intentionally dropped

The default view should show only **New / Acknowledged / Planned**.
Closed items stay searchable for history but should not clutter the active list.

## One issue = one permalink

Each feedback item should be its own GitHub Issue so it can be linked directly to a PM/engineer.

Keep issue bodies short:

1. Observed
2. Why it matters
3. Expected
4. Evidence (only when useful)
5. HighLevel response / status

Do not keep resolved misunderstandings in the active tracker.

## Suggested labels

### Product
`product:meeting-room`
`product:calendar`
`product:communities`
`product:courses`
`product:events`
`product:webinars`
`product:client-portal`
`product:platform`

### Type
`type:bug`
`type:ux`
`type:feature`
`type:platform`
`type:reference`

### Status
`status:new`
`status:acknowledged`
`status:planned`
`status:shipped`
`status:closed`

### Impact
`impact:high`
`impact:medium`
`impact:low`

## Recommended GitHub Project views

**Active**  
Filter: `status:new OR status:acknowledged OR status:planned`

**Needs reply**  
Filter: `status:new`

**By product**  
Group by `product:*`

**Shipped / closed**  
Filter: `status:shipped OR status:closed`

## References

Competitive/product references such as Sessions.us belong in `/references`, not as product issues.

## Source history and current feature status

The issue files are unsubmitted AI-drafted candidates based on the beta review request. `New` means no HighLevel response is recorded. Do not imply that Ivo sent a proposal or that HighLevel acknowledged it without a direct source.

- [Review history and provenance](sources/meeting-room-feedback-history.md)
- [Official feature availability check (2026-09-25)](references/official-feature-status-2026-09-25.md)

The feature check separates documented existing behavior from unverified gaps. It is based on official documentation and changelog pages, not a live account test.
