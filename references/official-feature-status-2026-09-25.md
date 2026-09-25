# HighLevel live-feature status check — 2026-09-25

This is a documentation-based check of official HighLevel support and changelog pages. It is not a live account test. “Available” means an official source explicitly documents the capability; “not verified” means this search did not establish it, not proof that it is absent. Existing behavior should not be reported as a defect.

## Capabilities already documented

| Area | Documented as available | Limits relevant to this tracker |
|---|---|---|
| Communities Go Live | Interactive Meeting Room and broadcast/RTMP modes; host controls, chat, reactions, hand raise, screen sharing, layouts, optional recording/replay, web/mobile access. Shared-screen full-screen viewing and independent zoom controls are documented (Aug 27, 2026). | This confirms core live-call features. Do not log these as missing. Per-room saved permission defaults and live host diagnostics are not described in the sources below. |
| Personal meeting links and recordings | Reusable meeting link and a central Recordings Hub with viewing, download, and deletion. Recordings can also be shared as posts to Communities. | A central hub and Community distribution exist; folders, tags, advanced ownership/retention, bulk actions, direct CRM/Client Portal destinations, and renaming were not established by these sources. |
| Community Events | Scheduled Live Room location, registration, calendar actions, reminders, access controls, and joining from the event context. | Community event support exists. It does not establish one shared session lifecycle across every HighLevel product. |
| Courses | One-time and recurring live sessions, timezone-aware scheduling, notifications, recordings, downloads, and adding a recording as a course lesson. | Several course workflows already exist. A general recording-to-contact/opportunity workflow is not established here. |
| Webinar Funnels | Live and on-demand webinars, registration pages/forms, reminders, and follow-up automations. | Live and on-demand are available. The documentation checked does not establish scheduled simulive playback with live Q&A handoff, timed stage actions, or webinar backstage roles. |
| Live video infrastructure | Interactive rooms and streaming, RTMP, recording/replay, basic participation analytics including participant counts and join/leave times. | This does not establish the proposed meeting-object APIs or event-specific webhook triggers. |
| Platform webhooks | Generic outbound workflow webhooks and inbound webhook triggers are documented. | Generic webhooks do not establish native triggers/API endpoints for Meeting Room objects, attendance, recordings, transcripts, or engagement. |

## Issue-by-issue triage

The Meeting Room records were corrected against the point-by-point beta response and later direct Zoom feedback. The linked Project contains 71 distinct issues: 67 Active, two Shipped, one Closed — Works as designed, and one Closed — Not pursuing. MR-209 is the analytics roadmap item; fullscreen is separately archived as ZOOM-001. MR-145 is the active practical audio/transcript workflow; MR-144 preserves the separate-track idea as closed history. Keep each issue focused on its remaining gap.

| Issue | Already available or confirmed | Remaining proposal / current evidence |
|---|---|---|
| MR-004 | Per-meeting participant access modes are configurable today. | Shipped for the reported behavior; additional options may expand with Room/Session configuration. |
| MR-006 | Live host permission controls exist. | Persist those controls as reusable room defaults; allow per-session overrides. |
| MR-007 | Recording and transcription/AI are available as separate capabilities in some workflows. | Verify a room-level unified auto-record → transcribe → summarize/save workflow; not established as one configurable Meeting Room flow. |
| MR-101 | Meeting Room is intended to remain the source of truth for integrations. | Inline select/create/configure flow was targeted for the following week; verify delivery. |
| MR-102 | Meeting setup exists. | HighLevel plans presets by meeting type/use case; delivery not verified. |
| MR-103 | Calendar-scheduled meetings show live state. | Native per-appointment Meeting Sessions are planned. |
| MR-104 | Product integrations exist. | HighLevel intends session context/data to flow back to Communities, Courses, and Events. |
| MR-105 | Host/attendee roles and co-host support have been discussed in the source. | Team-owned rooms and broader preassigned roles/independent start are still a distinct proposal. |
| MR-106 | — | CRM integration for attendance, recordings, transcripts, AI notes, and engagement data is planned. |
| MR-107 | — | Meeting/session workflow triggers and actions are planned. |
| MR-108 | Branded/custom meeting links are documented. | Broader attendee-facing branding controls are acknowledged; delivery not verified. |
| MR-120 | Community tab names can be manually customized. | Ivo directly requested Bulgarian label/button translation (Apr 14 and May 22); HighLevel said language translation would be supported soon. Platform-wide translation manager delivery is not verified. |
| MR-140 | Recordings Hub exists with basic library operations. | Organization and lifecycle controls beyond view/download/delete were not established. |
| MR-141 | Replays can be shared to Communities; Course recordings can be reused as lessons; recordings can be downloaded. | Direct reuse across contacts, appointments, opportunities, events, media, and courses as a common asset workflow is not established. |
| MR-142 | Recording/replay links exist. | Contact-linked Client Portal sharing with access controls and view tracking was not established. |
| MR-143 | Replay viewing and downloading exist. | Editing/trim/chapters/transcript corrections in the recording workflow were not established. |
| MR-144 | HighLevel prioritizes reliable final audio capture. | Separate logical tracks would be evaluated separately. Ivo decided not to pursue them; closed as not pursuing. |
| MR-145 | The beta response did not specifically address the full audio-only/transcript workflow. | Active, high impact: remove the Camtasia → AssemblyAI steps with audio-only export, high-quality speaker-labelled transcript, timestamps, TXT/Markdown, SRT/VTT, Bulgarian support, optional clickable AI chapters, and per-room/session controls. |
| MR-121 | — | HighLevel agreed Meeting Room should use the platform-wide Translation & Label Manager once available. |
| MR-160 | Webinar Funnels support live webinars. | Dedicated presenter/audience roles, backstage, and stage transitions were not established by the reviewed sources. |
| MR-161 | Live webinar flows are documented. | A dedicated moderated Q&A queue with assignment/states separate from chat was not established. |
| MR-162 | Chat, reactions, and hand raise exist. | Native polls/quizzes/resources tied to contacts and workflows were not established. |
| MR-163 | Screen sharing exists. | Synchronized native media playback from HighLevel Media Storage within a room was not established. |
| MR-164 | Live and on-demand webinar types exist. | Scheduled prerecorded simulive events, recurrence/JIT scheduling, and automated live Q&A handoff were not established. |
| MR-165 | Webinar funnels include reminders and follow-up automations. | Timed in-session CTA/offer/poll/resource/redirect actions were not established. |
| MR-201 | HighLevel has considered breakout rooms. | Not required for initial rollout; described as a later capability layer, without a delivery date. |
| MR-202 | No existing whiteboard/shared-notes feature was established in the documentation check. | HighLevel said these can be considered as an additional collaboration capability; no commitment. |
| MR-203 | Live transcription/captions are distinct from translation. | The proposal is specifically translated live captions; reviewed sources did not establish translation. |
| MR-205 | No phone dial-in/SIP evidence found in reviewed sources. | HighLevel noted dial-in as an additional access option; no delivery commitment. |
| MR-206 | Pre-join camera/microphone preview/device checks exist. | The proposal is in-session host-side participant quality/network diagnostics. |
| MR-207 | Mobile access to live sessions is documented. | HighLevel agrees resilient mobile joining matters; PiP/background improvements are acknowledged, not verified as shipped. |
| MR-208 | Basic device preview and controls are documented. | Accessibility across navigation, screen readers, focus, captions, and contrast is acknowledged; delivery not verified. |
| MR-210 | Generic platform webhooks/API and basic live analytics exist. | HighLevel agrees Meeting Room objects/events should be exposed through APIs/webhooks; delivery not verified. |
| MR-209 | Analytics roadmap was acknowledged by HighLevel in its point-by-point beta response. | Planned; source-backed delivery is not verified. |

## Official references

- [Communities Go Live: meeting and broadcast modes, host controls, recording/replay, and RTMP](https://help.gohighlevel.com/support/solutions/articles/155000006673)
- [Screen-sharing enhancements: fullscreen, zoom, system audio, and 1080p/30fps](https://help.gohighlevel.com/support/solutions/articles/155000008510-screen-sharing-enhancements-in-highlevel-meeting-rooms)
- [Share meeting recordings as Community posts](https://help.gohighlevel.com/support/solutions/articles/155000008014-share-meeting-recordings-as-community-posts)
- [Community tab customization and manual naming](https://help.gohighlevel.com/support/solutions/articles/155000008374-rearrange-and-rename-community-group-tabs)
- [Personal Meeting Links and Recordings Hub](https://ideas.gohighlevel.com/changelog/new-personal-meeting-links)
- [Live Rooms in Community Events](https://help.gohighlevel.com/support/solutions/articles/155000007834-live-rooms-in-communities-events)
- [Live Sessions in Courses](https://ideas.gohighlevel.com/changelog/live-sessions-in-courses-labs)
- [Webinar Funnel guide: live and on-demand](https://help.gohighlevel.com/support/solutions/articles/155000006062-complete-guide-to-creating-webinars-)
- [Media Core Live Streaming & Video Calling](https://help.gohighlevel.com/support/solutions/articles/155000006672)
- [Generic workflow webhooks](https://help.gohighlevel.com/support/solutions/articles/155000003305/)
