# HighLevel point-by-point response — Meeting Room beta

## Provenance

Source: response excerpt supplied by Ivo in the Codex task on 2026-09-25, attributed in the excerpt to Praveen Gupta (Team kollab) replying to Ivo's Meeting Room feedback. The original forum URL was not included. This is an edited, point-by-point summary of the supplied text, not a verbatim transcript. Issue statuses are derived from this source. Ivo's original feedback and attached document remain in the local ChatGPT export.

## Response

### MR-001 · BUG — Shared-screen audio is missing from recordings
Since Meeting Room runs in the browser, shared audio is supported when sharing a browser tab with audio enabled. The speaker icon on the right side of the top bar indicates this. When sharing another application/window, the browser does not provide its audio stream, so it cannot be captured in the meeting or recording. This is a browser-level limitation similar across web-based meeting platforms.

### MR-002 · BUG — Active session is not reflected in the manager
The manager currently shows live state for scheduled meetings, such as Calendar appointments. HighLevel will also account for consistently showing active sessions started through other Meeting Room flows.

### MR-003 · UX — Room and Session are currently conflated
HighLevel is moving toward separating reusable Room configuration from individual Sessions/Occurrences. A Room can retain reusable settings, while each occurrence has its own schedule, participants, access, attendance, recording, transcript, and analytics.

### MR-004 · ACCESS — Join modes must be configurable per use case
This is configurable per meeting based on the use case. The host can control how participants access the meeting, and HighLevel will continue expanding these options as part of Room/Session configuration.

### MR-005 · SECURITY — Permanent links are not sufficient for all scenarios
Scheduled meetings through Calendar are supported today and create a meeting for that appointment. HighLevel plans Instant Meeting and Schedule Meeting directly inside Meeting Room, similar to Zoom, with access/security configurable per meeting.

### MR-006 · SETTINGS — Host controls need persistent defaults
HighLevel has noted the feedback and agrees host controls should have reusable defaults, with overrides for individual sessions.

### MR-007 · PIPELINE — Recording / transcription / AI should not require separate manual setup
HighLevel has noted the feedback and wants recording, transcription, AI summaries, and related post-meeting processing to work as a unified configurable flow.

### MR-101 · ARCH — Use one central manager, but allow inline create/select/edit everywhere
This is the direction of the Meeting Room integration flow. Meeting Room remains the source of truth, while integrations can select/create/configure meetings without leaving the current product. The integration flow was targeted for the following week.

### MR-102 · PRESETS — Different scenarios need presets, not one generic settings wall
HighLevel plans different presets based on meeting type/use case.

### MR-103 · CALENDAR — Appointments should create native Sessions
This aligns with the planned Calendar integration: each Calendar appointment will map to its own Meeting Session rather than a generic permanent room.

### MR-104 · CONTEXT — Communities, Courses and Events should retain their native context
HighLevel intends to preserve source product context so session data can flow back to Communities, Courses, Events, and related products.

### MR-105 · TEAM — Team rooms need explicit ownership and alternative hosts
Co-hosts are already supported. Team-owned rooms, preassigned roles, and authorized teammates independently starting/managing meetings are acknowledged as useful broader feedback.

### MR-106 · CRM — Meeting data must be first-class CRM data
HighLevel agrees and says attendance, recordings, transcripts, AI notes, and related engagement data are already part of its plan for integration with relevant CRM entities.

### MR-107 · AUTOMATION — Expose workflow triggers and actions
HighLevel agrees and says meeting/session events are already planned for Workflows to trigger follow-ups and other automations.

### MR-108 · WHITE LABEL — Room frontend needs full brand control
HighLevel has noted the feedback and will account for broader white-label customization across attendee-facing Meeting Room experiences.

### MR-120 · PLATFORM — Create a platform-wide Translation & Label Manager now
HighLevel says this is broader than Meeting Room and needs to be handled as a platform-level capability. Meeting Room can integrate with a centralized translation/label system once available.

### MR-121 · MEETINGS — Meeting labels must use the same translation system
HighLevel agrees Meeting Room should consume a centralized platform Translation & Label Manager rather than introduce a separate meeting-specific configuration.

### MR-140 · LIBRARY — Recording Hub needs asset management
HighLevel agrees recordings should become reusable assets rather than only a flat list. Folders/collections, search, permissions, ownership, and retention are useful as usage scales.

### MR-141 · DISTRIBUTION — Recordings need native destinations
HighLevel intends recordings to be reusable across HighLevel, including sharing or attaching them to relevant products and entities rather than downloading and re-uploading.

### MR-142 · CLIENT PORTAL — Share recording directly with a contact/client
This aligns with HighLevel's plan for native secure recording sharing with contacts/clients without an external video host.

### MR-143 · EDITING — Add basic post-production tools
HighLevel has noted trimming, clips, thumbnails, captions/transcript editing, and export controls as useful additions.

### MR-144 · AUDIO — Store/handle useful audio tracks
For the final recording, HighLevel prioritizes reliably mixing and capturing all supported audio sources. Preserving separate logical audio tracks/exports is useful feedback and will be evaluated separately.

### MR-160 · WEBINAR — Webinar mode needs stage roles and backstage
HighLevel agrees webinars have different requirements from normal meetings and says dedicated roles and stage/audience behavior will be considered as Webinar expands.

### MR-161 · Q&A — Q&A must be separate from chat
HighLevel agrees dedicated Q&A differs from regular meeting chat, especially for webinars and larger sessions, and has noted the requirement.

### MR-162 · INTERACTION — Native polls, quizzes and resources
HighLevel agrees these are valuable webinar/classroom interactions and will consider them as part of broader interactive meeting/webinar capabilities and integrations.

### MR-163 · MEDIA — Present native media, not only screen share
HighLevel agrees native slides/video/media could improve quality and reliable audio capture and has noted the feedback.

### MR-164 · SIMULIVE — Support automated/simulive sessions
HighLevel will consider simulive/automated webinars as part of its webinar roadmap.

### MR-165 · TIMED ACTIONS — Webinar sessions need timeline automation
HighLevel agrees timed CTAs, offers, polls, resources, redirects, and workflow triggers are valuable for webinar/funnel use cases and will account for them in deeper webinar integration.

### MR-201 · Breakout rooms
HighLevel has considered breakout rooms. They are not required for initial rollout but fit the next layer of meeting capabilities.

### MR-202 · Collaborative whiteboard / shared notes
HighLevel says collaborative whiteboard/shared notes are useful for workshops, coaching, and classroom scenarios and can be considered as an additional collaboration capability.

### MR-203 · Live captions + real-time translated captions
HighLevel says live transcription/captions already exist as part of Meeting AI; real-time translated captions would be an additional capability.

### MR-204 · RTMP/SRT output or simulcast
RTMP streaming is already in HighLevel's plan, to stream Meeting Room sessions to supported external destinations such as Communities, YouTube, and Facebook.

### MR-205 · Dial-in / SIP options
HighLevel has noted dial-in as an additional access option for businesses requiring traditional phone participation.

### MR-206 · Network/device diagnostics and host quality dashboard
PreJoin already checks devices before joining. A broader host-side quality/network diagnostics dashboard is acknowledged as useful troubleshooting feedback.

### MR-207 · Mobile-first join flow / PiP / resilient reconnect
HighLevel agrees mobile joining and resilient reconnection are important; picture-in-picture and improved background behavior are useful additions.

### MR-208 · Accessibility
HighLevel agrees keyboard navigation, screen-reader support, focus management, captions, and appropriate contrast should be considered across the Meeting Room experience.

### MR-209 · Analytics
HighLevel says deeper Meeting Room reporting is already a major part of its plan, including sessions, attendance, engagement, recordings, transcripts, and later source/conversion/revenue reporting through integrations.

### MR-210 · API/webhooks
HighLevel agrees rooms, sessions, participants, recordings, transcripts, and engagement events should be exposed through APIs/webhooks for HighLevel products and external integrations.
