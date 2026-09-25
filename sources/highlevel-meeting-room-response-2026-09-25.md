# HighLevel point-by-point response — Meeting Room beta

## Provenance

Source: response excerpt supplied by Ivo in the Codex task on 2026-09-25, attributed in the excerpt to Praveen Gupta (Team kollab) replying to Ivo's Meeting Room feedback. The original forum URL was not included. A concise editorial summary appears above; the exact text supplied by Ivo is preserved below under “Verbatim excerpt.” Issue statuses are derived from the excerpt. Ivo's original feedback and attached document remain in the local ChatGPT export.

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

## Verbatim excerpt

The following point-by-point text is reproduced as supplied by Ivo in the Codex task on 2026-09-25.

### MR-001 · BUG — Shared-screen audio is missing from recordings
Since Meeting Room runs in the browser, shared audio is supported when sharing a browser tab with audio enabled. We already indicate this with the speaker icon on the right side of the top bar. If a user shares another application/window, the browser does not provide its audio stream, so we cannot capture it in the meeting or recording. This is a browser-level limitation and is similar across web-based meeting platforms.

### MR-002 · BUG — Active session is not reflected in the manager
Currently, we show the live state for scheduled meetings. For example, if an appointment is scheduled through Calendar and its Meeting Room session is live, we show the live state in the manager. We’ll also account for consistently showing active sessions started through other Meeting Room flows.

### MR-003 · UX — Room and Session are currently conflated
Agreed. We’re moving toward separating the reusable Room configuration from individual Sessions/Occurrences. A Room can retain reusable settings, while each occurrence has its own schedule, participants, access, attendance, recording, transcript, and analytics.

### MR-004 · ACCESS — Join modes must be configurable per use case
Yes, this is configurable per meeting based on the use case. The host can control how participants access the meeting, and we’ll continue expanding these options as part of the Room/Session configuration.

### MR-005 · SECURITY — Permanent links are not sufficient for all scenarios
We support scheduled meetings through Calendar today, which creates a meeting for that specific appointment and reflects it in Meeting Room. We’re also planning to provide Instant Meeting and Schedule Meeting directly inside Meeting Room, similar to Zoom. Access/security can then be configured per meeting depending on the use case.

### MR-006 · SETTINGS — Host controls need persistent defaults
Thanks for the feedback. We’ve noted this and agree that host controls should have reusable defaults, with the ability to override them for individual sessions.

### MR-007 · PIPELINE — Recording / transcription / AI should not require separate manual setup
Agreed, we’ve noted this feedback. We want recording, transcription, AI summaries, and related post-meeting processing to work as a unified configurable flow.

### MR-101 · ARCH — Use one central manager, but allow inline create/select/edit everywhere
This is exactly the direction of our Meeting Room integration flow. Meeting Room will remain the source of truth, while integrations can select/create/configure meetings without requiring users to leave the product they’re currently using. We’re targeting this integration flow for next week.

### MR-102 · PRESETS — Different scenarios need presets, not one generic settings wall
Yes, we’re planning different presets based on the meeting type/use case rather than using the same configuration for every scenario.

### MR-103 · CALENDAR — Appointments should create native Sessions
Yes, this aligns with our planned Calendar integration. Each Calendar appointment will map to its own Meeting Session rather than simply using a generic permanent room.

### MR-104 · CONTEXT — Communities, Courses and Events should retain their native context
Yes, this is the direction we’re taking. The Meeting Room integration will preserve the source product context so session data can flow back to Communities, Courses, Events, etc.

### MR-105 · TEAM — Team rooms need explicit ownership and alternative hosts
We already support adding co-hosts who can help manage the meeting. The broader requirement around team-owned rooms, preassigned roles, and allowing authorized teammates to start/manage meetings independently is good feedback, and we’ll account for this as we expand team meeting support.

### MR-106 · CRM — Meeting data must be first-class CRM data
Agreed. This is already part of our plan. Meeting attendance, recordings, transcripts, AI notes, and related engagement data will be integrated with the relevant CRM entities.

### MR-107 · AUTOMATION — Expose workflow triggers and actions
Agreed. This is already part of our plan. Meeting/session events will be exposed to Workflows so they can trigger follow-ups and other automations.

### MR-108 · WHITE LABEL — Room frontend needs full brand control
Thanks for the feedback. We’ve noted this and will account for broader white-label customization across attendee-facing Meeting Room experiences.

### MR-120 · PLATFORM — Create a platform-wide Translation & Label Manager now
This looks broader than Meeting Room itself and would need to be handled as a platform-level capability. From the Meeting Room side, we can integrate with a centralized translation/label system once that platform capability is available.

### MR-121 · MEETINGS — Meeting labels must use the same translation system
Agreed. If we have a centralized Translation & Label Manager at the platform level, Meeting Room should consume the same system rather than introducing a separate translation configuration specifically for meetings.

### MR-140 · LIBRARY — Recording Hub needs asset management
Agreed. We’re already thinking about recordings as reusable assets rather than only a flat list of meeting recordings. Folder/collection management, search, permissions, ownership, and retention are useful additions as recording usage scales.

### MR-141 · DISTRIBUTION — Recordings need native destinations
Agreed. Our direction is to make recordings reusable across HighLevel rather than requiring users to download and re-upload them. This includes sharing or attaching recordings to relevant HighLevel products and entities.

### MR-142 · CLIENT PORTAL — Share recording directly with a contact/client
This is aligned with our plan. We want to provide native recording sharing so users can securely share recordings with contacts/clients without depending on an external video hosting platform.

### MR-143 · EDITING — Add basic post-production tools
Thanks for the feedback. We’ve noted this. Basic capabilities such as trimming, clips, thumbnails, captions/transcript editing, and export controls would make the recording experience much more complete.

### MR-144 · AUDIO — Store/handle useful audio tracks
For the final recording, our priority is to ensure that all supported audio sources are mixed and captured reliably. Preserving separate logical audio tracks/exports is useful feedback, especially for debugging and post-production, and we’ll evaluate this separately.

### MR-160 · WEBINAR — Webinar mode needs stage roles and backstage
Agreed that a webinar experience has different requirements from a normal meeting. As we expand the Webinar use case, we’ll account for dedicated roles and stage/audience behavior rather than treating it as a standard gallery meeting.

### MR-161 · Q&A — Q&A must be separate from chat
Agreed. Dedicated Q&A is different from regular meeting chat, especially for webinars and larger sessions. We’ve noted this requirement.

### MR-162 · INTERACTION — Native polls, quizzes and resources
Agreed. Polls, quizzes, resources, and structured engagement are valuable for webinar/classroom use cases. We’ll consider these as part of the broader interactive meeting/webinar experience, along with CRM, Workflow, and analytics integration.

### MR-163 · MEDIA — Present native media, not only screen share
Agreed. Native presentation of slides/video/media would provide a better experience than relying entirely on browser screen sharing, especially for media quality and reliable audio capture. We’ve noted this feedback.

### MR-164 · SIMULIVE — Support automated/simulive sessions
Thanks for the feedback. Simulive/automated webinars are a different use case from a normal live Meeting Room, and we’ll consider this as part of our webinar roadmap.

### MR-165 · TIMED ACTIONS — Webinar sessions need timeline automation
Agreed. Timed CTAs, offers, polls, resources, redirects, and workflow triggers are valuable specifically for webinar/funnel use cases. We’ll account for this when building out the deeper webinar integration.

### MR-201 · Breakout rooms
This is already something we’ve considered for Meeting Room. It’s not required for the initial rollout, but it fits into the next layer of meeting capabilities.

### MR-202 · Collaborative whiteboard / shared notes
Thanks for the feedback. Collaborative whiteboard/shared notes are useful for workshops, coaching, and classroom scenarios and can be considered as an additional collaboration capability.

### MR-203 · Live captions + real-time translated captions
We already have live transcription/captions as part of Meeting AI. Real-time translated captions would be an additional capability on top of the existing transcription experience.

### MR-204 · RTMP/SRT output or simulcast
Yes, RTMP streaming is already in our plan. This will allow users to stream a Meeting Room session to external destinations such as Communities, YouTube, Facebook, and other supported platforms.

### MR-205 · Dial-in / SIP options
Thanks for the feedback. We’ve noted this as an additional access option for businesses that require traditional phone/dial-in participation.

### MR-206 · Network/device diagnostics and host quality dashboard
We already have a PreJoin experience for checking devices before entering the meeting. The broader host-side quality/network diagnostics dashboard is good feedback and can help with troubleshooting during larger sessions.

### MR-207 · Mobile-first join flow / PiP / resilient reconnect
Agreed. Mobile joining and resilient reconnection are important parts of the Meeting Room experience. Picture-in-picture and improved background behavior are useful additions as we continue improving mobile usage.

### MR-208 · Accessibility
Agreed. Keyboard navigation, screen-reader support, focus management, captions, and appropriate contrast should be considered across the complete Meeting Room experience.

### MR-209 · Analytics
This is already a major part of our plan. We’re working toward deeper Meeting Room reporting around sessions, attendance, participant engagement, recordings, transcripts, and related activity. As the Calendar/CRM/Webinar integrations mature, we can connect this further with source and conversion/revenue reporting.

### MR-210 · API/webhooks
Agreed. Rooms, sessions, participants, recordings, transcripts, and engagement events should be exposed through APIs/webhooks so other HighLevel products and external integrations can build on top of Meeting Room.
