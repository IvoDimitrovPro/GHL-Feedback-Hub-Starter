# Zoom feedback authored by Ivo — 2026-01-01 through 2026-09-25

## Search scope and attribution

Searched text chat files (`*.txt`) inside Zoom folders whose folder names carry a date from 2026-01-01 through 2026-09-25. The matching archive contains **33 chat files** from **2026-04-14 through 2026-09-18** and **435 messages authored by `Ivo (pr. Evo)`**. No dated Zoom folders for January–March 2026 were present in this archive. No matching chat files later than September 18 were present at the time of this search.

The previous broad-search conclusion that there was no relevant Zoom feedback was wrong: it used the older `chat.txt` filename pattern and missed the 2026 `meeting_saved_new_chat.txt` files. This index replaces that conclusion.

This is a curated index of Ivo-authored product feedback and follow-ups, not a dump of all 435 messages. Greetings, reactions, other attendees’ comments, private video links, email addresses, and client-identifying details are omitted. Source names are given by date; most are `D:\Zoom\<dated Product Town Hall>\meeting_saved_new_chat.txt`.

## Meeting Rooms, Communities, Events, Courses, Webinars

| Date | Ivo’s feedback | Reply / current state |
|---|---|---|
| 2026-04-14 | Reported a 520 error opening a new Live Room shortly before a client meeting; asked whether the room’s recording would be placed in a private Community channel and restricted to that channel’s members. | HighLevel said the 520 issue had been fixed and a hard refresh was needed; Ivo confirmed the link then worked. The recording page was still being built. Current official docs now describe Go Live posts and processed recordings in the selected Community channel. Treat the transient 520 as closed and the recording destination as documented. |
| 2026-04-14 | Asked for full-screen viewing during Live Sessions because attendees with smaller displays could not see the whole shared screen. | HighLevel replied “Will fix this.” Official Meeting Room documentation dated 2026-08-27 now documents full-screen shared-screen viewing and zoom controls. **Shipped; archived in MR-209, not active.** |
| 2026-04-14; reiterated 2026-05-22 | Asked to edit/translate room and Community labels/buttons into Bulgarian, without waiting for a translation team. | HighLevel said language translation support was coming soon. Community tab names can now be renamed, but official docs state custom tab names are not automatically translated; a platform-wide translation/label manager is not verified. **Planned / partial.** Tracked in MR-120. |
| 2026-04-14; 2026-05-22; 2026-06-19 | Repeatedly asked for free lesson/module previews inside a paid course, including previewing more than one lesson/module/category. | HighLevel said this was in the roadmap for Q3 2026; Ivo was still asking for free lessons on 2026-06-19. Current docs confirm free courses and course curriculum previews, but do not confirm unlocked lesson previews inside a paid course. **Planned, not verified shipped.** Tracked in COURSE-001. |
| 2026-04-29 | Asked to let webinar registrants join a Personal Meeting Link with only name/email, without first creating a Community account, with optional account creation. | No direct reply recorded. Current Community Event documentation describes attendance through signed-in Communities; anonymous/external webinar guest registration remains an unverified gap. Tracked in WEB-001. |
| 2026-05-22 | Asked for a shareable recording link for clients and the ability to rename recordings. | A Recordings Hub and `Share as Post` workflow have since shipped for Community sharing; direct Client Portal sharing and renaming were not established by the checked docs. Keep only those remaining gaps active. |
| 2026-05-22 | Asked for Community/course/offer access rules based on conditions such as purchases, points, and membership duration, to avoid building separate workflows and funnels for each access rule. | No direct HighLevel response recorded in the matching excerpt. |
| 2026-05-22 | Asked to let people join a Community immediately without waiting for an admin to manually approve their answers. | No implementation or response established by the checked source. |
| 2026-05-22 | Asked for a logo that works against both light and dark backgrounds, and for Bulgarian support in automatically generated meeting transcripts. | No direct implementation status recorded. |
| 2026-08-20 | Reported that Community live sessions were choppy on 4G for clients and asked for a low-bandwidth fallback. | No fix or response recorded. Keep as a direct, unresolved performance report; separate from the general host-diagnostics proposal in MR-206. |

## Localization, navigation, and cross-product consistency

| Date | Ivo’s feedback | Reply / current state |
|---|---|---|
| 2026-04-14; 2026-05-20; 2026-07-29 | Asked for Sofia / Europe-Sofia as a real timezone, Monday as the week start, and 24-hour time across the platform. Explained that a fixed GMT offset does not handle Bulgaria’s winter/summer time changes. | No confirmed platform-wide completion recorded. Sofia timezone and consistent regional settings remain a direct localization request. |
| 2026-05-06; 2026-06-15; 2026-06-19; 2026-07-13; 2026-07-27; 2026-09-18 | Repeated that Brand Boards, shared colors/fonts, Media Storage, and common controls should work across builders and product areas; asked for a common design system and consistent table/builder behavior. | Repeated cross-product feedback, not one isolated feature request. Some individual customizers now exist, but universal Brand Board/Media Storage integration was not verified. |
| 2026-05-08; 2026-06-15; 2026-06-22; 2026-07-27; 2026-09-17 | Asked for clearer builder controls: persistent menus, conditional visibility, consistent panel behavior, global typography/spacing, selectable layers, links on whole elements, and reliable editing of forms/quizzes/popups. | Several distinct UI defects/requests; screenshots were attached in the source chats but are not copied here. No blanket fix is documented. |
| 2026-07-13; 2026-07-29; 2026-07-31 | Asked for dark/light logo support and dark-mode customization in Portal/Courses/Communities; also asked for accent-color customization in the LeadConnector app. | No general cross-surface implementation verified. |
| 2026-05-08; 2026-06-11; 2026-06-15; 2026-06-16; 2026-07-31 | Asked for tables and dashboards with consistent sorting, useful/custom columns, filters, exports, and access to the data needed for agency and sub-account work. | Specific existing-contact pipeline question was resolved during the 2026-05-06 town hall: after being shown the filter/add workflow, Ivo said it would do the trick. Do not keep that pipeline question as an open defect. Other data-table/reporting needs remain separate. |
| 2026-05-06; 2026-07-29 | Reported confusing Community navigation/back behavior and separated identities for the same email between Client Portal and GoKollab; asked for better account/profile continuity. | No completion verified in these sources. |

## CRM, commerce, email, analytics, and automation

| Date | Ivo’s feedback | Reply / current state |
|---|---|---|
| 2026-04-14; 2026-07-23 | Repeatedly asked for fully customizable invoices/documents suitable for his jurisdiction and for client-entered VAT/company/address details to flow into invoices. Reported that the current SaaS invoice template could not be customized and that sub-account billing data was not being reused. | HighLevel discussed pixel-level document customization within the quarter and a pipeline for custom values on receipts; Ivo was still reporting the invoice limitation in July. **Planned, delivery not verified.** |
| 2026-09-17 | Asked for all Funnels/Stores order data and external/internal identifiers (including Stripe/WooCommerce IDs and receipt/order metadata) in exports and Workflows, citing strict EU reporting rules and manual monthly work. Asked for sequential internal order IDs. | No direct response or implementation established in the source. |
| 2026-04-14; 2026-06-22; 2026-07-23 | Repeatedly asked about a modern, configurable 1-step/2-step Checkout and an update path that would not require custom CSS/JS work for clients. | No confirmed delivery date in the messages reviewed. |
| 2026-04-29; 2026-06-11; 2026-07-31 | Asked for time-limited/dynamic SaaS promotions and simpler add-on upgrades within an existing sub-account, with clear proration and EUR reseller pricing. | No resolved workflow recorded. |
| 2026-08-11 | Suggested adding funds to affiliate sub-account wallets for email/AI usage instead of paying commissions out; described manually waiving subscription fees and crediting wallets. | No direct response or implementation established. |
| 2026-05-01; 2026-05-29; 2026-06-15; 2026-07-13; 2026-07-27; 2026-09-18 | Repeatedly asked for a native receiving inbox for domains sold through HighLevel and clearer agency email management. Reported spam placement and weak deliverability compared with other providers. | The public feedback link for Email Inbox was referenced; no resolution for the domain/inbox and deliverability gaps was recorded in these chat files. |
| 2026-05-06; 2026-07-27 | Reported that DND and unsubscribe states were confusingly separated and that a previously unsubscribed contact who opts in again was not clearly shown as subscribed. Asked to make unsubscribe state visible and operable in its own row. | Repeated concrete UX/state feedback. No fix established in the messages reviewed. |
| 2026-06-15 | Asked to segment email recipients by opens/clicks within a date window; said current engagement conditions were too vague and could not be used in a Smart List. | No resolution recorded. |
| 2026-05-08; 2026-05-19; 2026-06-15; 2026-06-16 | Demonstrated a custom finance dashboard and asked for a native sub-account view joining contacts, purchases, products, advertising spend, transactions, and other account data, with custom widgets and AI analysis. | Direct repeated product feedback; not a request for a generic analytics feature. No complete native equivalent verified. |
| 2026-07-10; 2026-07-27 | Asked for one tracking hub for Meta Pixel, CAPI, Google Tag Manager, and other tracking values, reusable across Forms, Surveys, Quizzes, Funnels, Websites, and Stores. Reported missing/inconsistent settings and Purchase events not firing. | No direct response recorded. |
| 2026-07-10 | Asked to tag contacts directly on Forms/Surveys/Quizzes submission and clarify confusing settings such as “Save exit confirm.” | No response or resolution established. |
| 2026-07-13; 2026-08-20 | Reported Mailchimp import mismatch and Ask AI course-content import failures (including incorrect/missing course content for several clients). Asked Ask AI to access campaign send/bounce data and said generated email subject/content could remain empty despite exact instructions. | One update said a text-file workflow worked in one case; video/course imports and exact email generation were not established as fixed. Keep these as separate reproducible product defects only when the relevant evidence is available. |
| 2026-05-01; 2026-06-05; 2026-06-15 | Asked for smoother customer migration, account-wide permission/default controls for Ask AI and AI Studio, and an opt-in flow that would not consume users’ free trial accidentally. Reported manually processing 120+ users and accidentally activating trials. | The account list later displayed all accounts, but bulk opt-in, trial cancellation/reset, and safer defaults were not confirmed as solved. |

## Ask AI, reporting, and platform APIs

| Date | Ivo’s feedback | Reply / current state |
|---|---|---|
| 2026-05-08; 2026-06-15; 2026-08-06 | Asked Ask AI to use an uploaded/managed Knowledge Base and documents across the platform, preserve the customer’s chosen language, and support controllable page context. | HighLevel agreed that shared Knowledge Base access is a proper direction; current Ask AI Split View documentation describes page context for supported pages but does not establish all requested sources/language behavior. |
| 2026-06-05; 2026-08-06; 2026-08-10 | Asked for visible token consumption, per-task/project usage, model/provider identity, predictable limits, and clear input/output or per-million-token pricing so agency owners can estimate costs and prevent interruptions. | No complete usage/pricing view matching the request was confirmed in the chats reviewed. |
| 2026-06-15; 2026-07-31 | Asked Ask AI/external AI through API or MCP to hand work into website/funnel builders, and asked whether HighLevel’s AI endpoints can be used outside the platform. | No direct implementation status established. |
| 2026-07-31 | Asked for tasks to be more visible, including a mobile home-screen widget and a connection to the upcoming Helpdesk/Ticketing system. | No delivery status recorded. |
| 2026-08-20 | Asked why `.md` files were unsupported in Media Storage; reported Ask AI course imports failing for several clients. | Text replacement worked in one follow-up; video/course behavior remained uncertain. |

## Sources and current product references

- [Share Meeting Recordings as Community Posts](https://help.gohighlevel.com/support/solutions/articles/155000008014-share-meeting-recordings-as-community-posts)
- [Communities Live Session Enhancements: Personal Links and Recordings Hub](https://help.gohighlevel.com/support/solutions/articles/155000008012-communities-live-session-enhancements-personal-meeting-links-recordings-hub-noise-cancellation)
- [Screen-sharing enhancements, including full-screen mode](https://help.gohighlevel.com/support/solutions/articles/155000008510-screen-sharing-enhancements-in-highlevel-meeting-rooms)
- [Live Rooms in Community Events and member access](https://help.gohighlevel.com/support/solutions/articles/155000007834-live-rooms-in-communities-events)
- [Community tab customization (rename; custom labels are not translated)](https://help.gohighlevel.com/support/solutions/articles/155000008374-rearrange-and-rename-community-group-tabs)
- [Course building and free/paid offers](https://help.gohighlevel.com/support/solutions/articles/48001141015)
- [Paid Courses inside Communities](https://help.gohighlevel.com/support/solutions/articles/155000002135)
- [Ask AI Split View](https://help.gohighlevel.com/support/solutions/articles/155000008730-how-to-use-ask-ai-in-split-mode)

The official pages above establish documented capability only; this archive is not a live-account test. “No response recorded” means no response was found in the matching Ivo-authored Zoom discussion, not that HighLevel has never responded elsewhere.
