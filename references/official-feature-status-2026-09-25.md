# HighLevel live-feature status check — 2026-09-25

This is a documentation-based check of official HighLevel support and changelog pages. It is not a live account test. “Available” means an official source explicitly documents the capability; “not verified” means this search did not establish it, not proof that it is absent. Existing behavior should not be reported as a defect.

## Capabilities already documented

| Area | Documented as available | Limits relevant to this tracker |
|---|---|---|
| Communities Go Live | Interactive Meeting Room and broadcast/RTMP modes; host controls, chat, reactions, hand raise, screen sharing, layouts, optional recording/replay, web/mobile access. | This confirms core live-call features. Do not log these as missing. Per-room saved permission defaults and live host diagnostics are not described in the sources below. |
| Personal meeting links and recordings | Reusable meeting link and a central Recordings Hub with viewing, download, and deletion. | A central hub exists; folders, tags, advanced ownership/retention, bulk actions, and native CRM destinations are not established by these sources. |
| Community Events | Scheduled Live Room location, registration, calendar actions, reminders, access controls, and joining from the event context. | Community event support exists. It does not establish one shared session lifecycle across every HighLevel product. |
| Courses | One-time and recurring live sessions, timezone-aware scheduling, notifications, recordings, downloads, and adding a recording as a course lesson. | Several course workflows already exist. A general recording-to-contact/opportunity workflow is not established here. |
| Webinar Funnels | Live and on-demand webinars, registration pages/forms, reminders, and follow-up automations. | Live and on-demand are available. The documentation checked does not establish scheduled simulive playback with live Q&A handoff, timed stage actions, or webinar backstage roles. |
| Live video infrastructure | Interactive rooms and streaming, RTMP, recording/replay, basic participation analytics including participant counts and join/leave times. | This does not establish the proposed meeting-object APIs or event-specific webhook triggers. |
| Platform webhooks | Generic outbound workflow webhooks and inbound webhook triggers are documented. | Generic webhooks do not establish native triggers/API endpoints for Meeting Room objects, attendance, recordings, transcripts, or engagement. |

## Issue-by-issue triage

All 23 records remain `New` because they are unsubmitted proposals, not because every capability is verified absent. Keep the issue statement focused on the gap in the right-hand column.

| Issue | Already available or confirmed | Remaining proposal / current evidence |
|---|---|---|
| MR-006 | Live host permission controls exist. | Persist those controls as reusable room defaults; allow per-session overrides. |
| MR-007 | Recording and transcription/AI are available as separate capabilities in some workflows. | Verify a room-level unified auto-record → transcribe → summarize/save workflow; not established as one configurable Meeting Room flow. |
| MR-105 | Host/attendee roles and co-host support have been discussed in the source. | Team-owned rooms and broader preassigned roles/independent start are still a distinct proposal. |
| MR-108 | Branded/custom meeting links are documented. | Broader attendee-facing branding controls are not established by the reviewed sources. |
| MR-120 | Custom values and translation in product-specific places may exist. | A platform-wide translation/label catalog with inheritance and bulk management was not found in reviewed official sources. |
| MR-140 | Recordings Hub exists with basic library operations. | Organization and lifecycle controls beyond view/download/delete were not established. |
| MR-141 | Replays can be shared to Communities; Course recordings can be reused as lessons; recordings can be downloaded. | Direct reuse across contacts, appointments, opportunities, events, media, and courses as a common asset workflow is not established. |
| MR-142 | Recording/replay links exist. | Contact-linked Client Portal sharing with access controls and view tracking was not established. |
| MR-143 | Replay viewing and downloading exist. | Editing/trim/chapters/transcript corrections in the recording workflow were not established. |
| MR-145 | Recording/replay exists; the beta source described a manual external transcript workflow. | Audio-only export and AI-ready speaker-labelled/timestamped transcript export were not established for Meeting Room. |
| MR-160 | Webinar Funnels support live webinars. | Dedicated presenter/audience roles, backstage, and stage transitions were not established by the reviewed sources. |
| MR-161 | Webinar Q&A is a supported use case. | A dedicated moderated question queue with assignment/states separate from chat was not established. |
| MR-162 | Chat, reactions, and hand raise exist. | Native polls/quizzes/resources tied to contacts and workflows were not established. |
| MR-163 | Screen sharing exists. | Synchronized native media playback from HighLevel Media Storage within a room was not established. |
| MR-164 | Live and on-demand webinar types exist. | Scheduled prerecorded simulive events, recurrence/JIT scheduling, and automated live Q&A handoff were not established. |
| MR-165 | Webinar funnels include reminders and follow-up automations. | Timed in-session CTA/offer/poll/resource/redirect actions were not established. |
| MR-201 | No breakout-room evidence found in reviewed sources. | Keep as an unverified candidate; do not claim HighLevel said it is planned without a direct source. |
| MR-203 | Live transcription/captions are distinct from translation. | The proposal is specifically translated live captions; reviewed sources did not establish translation. |
| MR-205 | No phone dial-in/SIP evidence found in reviewed sources. | Keep as an unverified candidate. |
| MR-206 | Pre-join camera/microphone preview/device checks exist. | The proposal is in-session host-side participant quality/network diagnostics. |
| MR-207 | Mobile access to live sessions is documented. | Mobile picture-in-picture/background continuity was not established. |
| MR-208 | Basic device preview and controls are documented. | The candidate needs concrete, reproducible accessibility examples before being sent; broad wording alone is not a verified defect report. |
| MR-210 | Generic platform webhooks/API and basic live analytics exist. | Meeting Room-specific APIs/webhooks for room, occurrence, attendance, recording, transcript, and engagement objects were not established. |

## Official references

- [Communities Go Live: meeting and broadcast modes, host controls, recording/replay, and RTMP](https://help.gohighlevel.com/support/solutions/articles/155000006673)
- [Personal Meeting Links and Recordings Hub](https://ideas.gohighlevel.com/changelog/new-personal-meeting-links)
- [Live Rooms in Community Events](https://help.gohighlevel.com/support/solutions/articles/155000007834-live-rooms-in-communities-events)
- [Live Sessions in Courses](https://ideas.gohighlevel.com/changelog/live-sessions-in-courses-labs)
- [Webinar Funnel guide: live and on-demand](https://help.gohighlevel.com/support/solutions/articles/155000006062-complete-guide-to-creating-webinars-)
- [Media Core Live Streaming & Video Calling](https://help.gohighlevel.com/support/solutions/articles/155000006672)
- [Generic workflow webhooks](https://help.gohighlevel.com/support/solutions/articles/155000003305/)
