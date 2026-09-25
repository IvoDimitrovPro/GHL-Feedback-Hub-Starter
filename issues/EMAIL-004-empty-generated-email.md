# EMAIL-004 — Do not silently generate empty email subject or body fields

**Product:** Ask AI / Email
**Type:** Reliability
**Status:** New
**Impact:** Medium
**Date reported:** 2026-07-13
**Source:** D:\Zoom\2026-07-13 18.51.54 Product Town Hall\meeting_saved_new_chat.txt

## Observed
Ivo reported that generated email actions could leave the subject or body empty despite explicit instructions.

## Why it matters
An apparently successful generation that silently omits content requires manual checking and can break a customer workflow.

## Expected
Populate required subject/body fields or show an actionable error when generation cannot produce them.

## HighLevel response
No fix was verified in the matched source. Keep the item open until a reproducible example confirms the current behavior.