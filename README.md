# Runnerz Namibia — Android Product Case Study

![Runnerz Namibia Android](assets/runnerz-og.png)

**A route-driven social running network built in Windhoek, for Namibia.**

[Runnerz Namibia](https://runnerznamibia.com) · [Instagram](https://www.instagram.com/runnerz.na/) · [Facebook](https://www.facebook.com/runnerz.na/) · [LinkedIn](https://www.linkedin.com/company/runnerz-na/)

> This is a public product case study. The Android source, Supabase configuration, migrations, credentials, signing material and operational implementation remain in a separate private repository.

## My role

**Freeman Ipumbu — Founder, product builder and design researcher**

I shaped Runnerz from the product thesis through brand direction, interaction design, Android engineering, route architecture, trust and safety language, backend foundations, real-device QA and launch planning.

## The problem

Running communities rarely fail because people dislike running. They fragment because intent, pace, place, timing and trust are difficult to align.

Runnerz is built around a more useful social loop:

```text
SEE A RUNNER → UNDERSTAND THE MATCH → PROPOSE A RUN →
MEET IN PUBLIC → RUN TOGETHER → CONFIRM IT → BUILD TRUST
```

It is not a follower network wearing running clothes. The unit of value is a run that can actually happen.

## Product response

- Explainable matching based on pace, intent, timing and route compatibility.
- Windhoek-first route discovery with genuine open-data geometry.
- Route DNA covering distance, surface, elevation and running character.
- Ranked public meetup suggestions shown as numbered route-map options, while avoiding private homes and keeping field checks explicit.
- Create Run, join/leave and post-run confirmation journeys.
- Run Connections built from completed activity rather than vanity follows.
- Founder, Pioneer, Legend, Trust Circle and Brand Ambassador distinctions.
- An expansive, revocable earned-badge catalogue across performance, routes, community, trust and safety, with governed legacy distinctions kept separate.
- Challenge, circuit, privacy-safe share-card, rotating run-fact and squad-versus-squad growth foundations.
- Owner-controlled public profile editing with a metadata-stripped, size-capped WebP portrait derivative.
- Personalised Namibian greetings plus reduced-motion-aware, device-tiered launch and celebration feedback.
- Production-shaped email signup, confirmation, sign-in and password recovery with clear next actions.
- Event-backed in-app and push-notification foundations for run and community moments.
- A lawful emergency quick-dial action that opens the system dialler without claiming dispatch.
- Honest weather, location and safety states that do not claim capabilities the product has not activated.
- An accepted-fix active-run recorder with a full-span segmented `#39FF88` trail, foreground controls, protected finish flow and durable offline run history.
- Distance, elapsed time, current and average pace, accepted-fix count and vertical-accuracy-gated estimated elevation gain without turning the run screen into a dashboard wall.
- Account-scoped aggregate history for banked kilometres and server-qualified weekly leaderboards, while exact completed trails remain on the phone. Rankings are device-recorded, not race-verified or anti-tamper-attested.
- Explicit, area-only Running Nearby presence that never publishes coordinates, exact distance, direction or trail.
- Report and block controls across nearby runners, matches, incoming proposals, meetup hosts and Run Connections.
- Host-defined open, women-only and women-led run audiences. Women-only runs use trusted-runner invitations and invite-only discovery; an optional self-reported onboarding preference stays private, is never inferred or publicly exposed, and never bypasses host approval.
- UNIFIED as the official Runnerz music player through a restrained, consent-led and privacy-light session handoff, plus a swipeable Community rail for events, future partner slots, route activations and local culture.

## Ambassador and culture layer

![Shadrac ShowTime Mavungu](assets/showtime-ambassador.jpg)

Shadrac “ShowTime” Mavungu is presented as an official Runnerz Brand Ambassador using his supplied portrait. Runnerz has announced the intention to develop an original track with ShowTime and to collaborate with Didi on future video and content. A finished recording, released video or additional featured artist is not claimed here and will be announced only when confirmed. The ambassador role is governed working provenance—not identity verification, behavioural trust or earned running performance.

## Official Runnerz Music Player

![UNIFIED × Runnerz official music player](assets/unified-runnerz-player.svg)

This is original ecosystem artwork, not a handset capture. The versioned device evidence begins in the section below.

**UNIFIED × Runnerz** is the official music layer for the Runnerz ecosystem. UNIFIED 20.0 “Signal Command” creates private 30, 45, 60 and 90-minute run mixes from the listener’s own library, sequences them through warm-up, lock-in, tempo and finish-kick phases, and begins playback before opening Runnerz.

The Runnerz 1.1.0 receiver validates the documented `runnerz://music-session` contract, checks for a supported installed UNIFIED package and presents a restrained linked-session confirmation. The handoff is deliberately narrow: session title, target duration and bounded track count cross the app boundary; track identities, full listening history and exact route data do not. Both Live (`com.runnerz.app`) and Field Test (`com.runnerz.app.fieldtest`) variants compile with the receiver enabled at versionCode 15. A complete physical-device start/run/return test remains a release gate, so this record does not call the cross-app loop production-complete.

UNIFIED’s rights-ready ShowTime channel activates for local tracks whose metadata matches the declared artist identity. A match is not proof of approval or distribution rights; the channel does not bundle ambassador audio or artwork, promise a remote stream, or replace explicit artist and rights-holder approval.

## Selected Android surfaces

All captures below come from real Android field-test builds on physical HONOR hardware at 1200 × 2664; no speculative phone mockups are used. Historical rows remain labelled, the UNIFIED relay records the earlier integration surface, and the 1.1.0 trail capture is a controlled physical-handset simulation—not outdoor GNSS or final store acceptance.

| Welcome | Secure sign-in | Create account |
|---|---|---|
| ![Runnerz welcome](assets/app-welcome.webp) | ![Runnerz sign-in](assets/app-sign-in.webp) | ![Runnerz create account](assets/app-create-account.webp) |

| Password recovery | Authenticated password update |
|---|---|
| ![Runnerz password recovery](assets/app-password-recovery.webp) | ![Runnerz new password](assets/app-new-password.webp) |

| Matches | Routes | Route confidence |
|---|---|---|
| ![Runnerz Matches](assets/app-matches.webp) | ![Runnerz Routes](assets/app-routes.webp) | ![Runnerz route confidence](assets/app-route-confidence.webp) |

| Discover | Community | Founder profile |
|---|---|---|
| ![Runnerz Discover](assets/app-discover.webp) | ![Runnerz Community](assets/app-community.webp) | ![Runnerz Founder profile](assets/app-profile.webp) |

| Governed badge shelf | Privacy-safe share studio | Emergency quick dial |
|---|---|---|
| ![Runnerz governed recognition](assets/app-badges.webp) | ![Runnerz share-card studio](assets/app-share-card.webp) | ![Runnerz emergency quick dial](assets/app-emergency-quick-dial.webp) |

| Ranked meetup options on the live route map |
|---|
| ![Runnerz ranked public meetup options](assets/app-meetup-options.webp) |

| Privacy onboarding | Trust onboarding | Runner DNA |
|---|---|---|
| ![Runnerz privacy onboarding](assets/app-privacy-onboarding.webp) | ![Runnerz trust onboarding](assets/app-trust-onboarding.webp) | ![Runnerz Runner DNA](assets/app-runner-dna.webp) |

| Run completion | Founder welcome | Founder’s Corner |
|---|---|---|
| ![Runnerz run completion](assets/app-run-celebration.webp) | ![Signed Runnerz Founder welcome](assets/app-founder-welcome.webp) | ![Runnerz Founder’s Corner](assets/app-founder-community.webp) |

| Expanded map controls | Banked Miles | Women-run options | ShowTime ambassador story |
|---|---|---|---|
| ![Runnerz expanded route switching controls](assets/app-live-route-switching.png) | ![Runnerz durable Banked Miles history](assets/app-banked-miles.png) | ![Runnerz open, women-only and women-led run options](assets/app-women-run-options.png) | ![Shadrac ShowTime Mavungu in Runnerz Community](assets/app-showtime-ambassador.png) |

| UNIFIED × Runnerz relay |
|---|
| ![Runnerz arms a private UNIFIED soundtrack](assets/app-unified-music-relay.png) |

| 1.1.0 controlled signature trail on HONOR REA-NX9 |
|---|
| ![Controlled Runnerz Field Test capture showing two lime trail segments, 60 accepted fixes and 0.18 km on real Eros route geometry](assets/app-1-1-0-controlled-signature-trail.jpg) |

The gallery documents implemented product direction, including the bounded UNIFIED session surface, expanded-map route switching, persistent offline run history, explicit run audiences and the ShowTime presentation. The historical completion capture uses corrected earlier-release wording. The new trail capture exercised the production tracking and metrics path with deterministic fixes on the handset. It does not show an outdoor run or prove GNSS accuracy. Outdoor tracking, screen-off continuity, battery behaviour and store acceptance remain separate gates.

## Design science approach

1. **Observe** — study why informal run coordination stalls between interest and action.
2. **Frame** — define the matching, trust, location and safety problems without inventing certainty.
3. **Design** — turn the run-forming loop into visible, testable interaction states.
4. **Build** — implement one canonical Kotlin/Compose architecture rather than parallel demo systems.
5. **Evaluate** — test on a physical Android device, including maps, back behaviour, permissions and constrained screen states.
6. **Harden** — separate identity verification from earned trust and keep unimplemented safety actions explicit.

## Engineering overview

- Kotlin and Jetpack Compose
- Android SDK 36 with minimum SDK 26
- MapLibre behind a provider-neutral map boundary
- Supabase authentication, PostgREST and versioned SQL migrations
- PKCE-backed Android confirmation and password-recovery callbacks
- Firebase Cloud Messaging transport and private App Distribution
- Ktor networking and DataStore preferences
- Real-device install and regression testing
- Provider-neutral route and location domain models

## Safety boundary

Runnerz does not represent suggested routes or meetup points as field-verified merely because they exist in open map data. It does not claim that emergency contacts, live tracking, navigation or safety services were activated unless a real provider and permission state support that claim.

Exact personal locations and private homes are not part of the public product story.

## Runnerz 1.1.0 candidate evidence

The private Android release record identifies the current candidate as **Runnerz 1.1.0 (code 15)**. Publicly safe build evidence is summarised below; private backend identifiers, signing details, tester data and raw trails are intentionally excluded.

| Evidence area | Verified candidate result |
|---|---|
| Unit tests | **260 passed total, 0 failed**: 130 for Live and 130 for Field Test |
| Android lint | Live release and Field Test debug lint completed with **0 errors** |
| Assembly | Both app variants and both instrumentation packages assembled successfully |
| GPS and mapping | Accepted-fix filtering, live camera follow, segmented full-span branded trail, pause/resume recovery and route-proximity guidance are implemented |
| Run metrics | Elapsed time, distance, current/average pace, accepted-fix count and estimated elevation gain are implemented |
| Banked Miles | Aggregate summaries are account/guest scoped; all summaries are retained while exact trails are bounded to the latest 50 runs per scope |
| Trust and social | Area-only Running Nearby, proposal flow, report/block coverage, open/women-only/women-led audiences and trusted-runner invitations are implemented |
| Account integrity | Current legal-document acceptance fails closed; account-backed screens and background work are withheld when acceptance is missing, stale or unverifiable |
| Music handoff | Supported UNIFIED discovery, explicit consent, cancellation, session expiry and bounded aggregate return are implemented |

### Controlled handset trail

On a physical **HONOR REA-NX9**, the separate Field Test instrumentation package fed 60 deterministic, realistic fixes through the production tracking and metrics path over **real Eros Urban Arc route geometry**. The unaltered capture above shows **0.18 km**, current and average pace, estimated elevation gain, and **two lime `#39FF88` trail segments** separated by a pause/resume boundary. The “5 TEST RUNNERS” route-preview label is Field Test fixture content, not live nearby activity. The simulated session was never finished or banked; its active checkpoint was cleared and the test package was removed. This verifies the handset rendering and accepted-fix path under controlled input. It does not measure outdoor GNSS accuracy or prove a completed real-world run.

The expanded map has four separate actions: **ME** follows the runner, **ROUTE** centres the selected route, and **PREV/NEXT** changes the selected route. Route proximity can help a runner reorient, but Runnerz does **not** snap recorded GPS points, the lime trail or banked distance onto a planned route.

### Social and release-safe summary

> Runnerz 1.1.0 is a verified Android candidate built around movement that remains legible: live GPS follow, a full-span Runnerz-green trail, useful run metrics, route-aware guidance, durable Banked Miles, privacy-safe nearby discovery, stronger community controls and an intentional UNIFIED music handoff. It is candidate evidence—not an App Store or Play Store availability claim.

## Current status

The canonical Android implementation remains private. Live and Field Test are separate applications; controlled test distribution and public-store submission are separate release paths. The new 1.1.0 controlled capture closes a specific simulation check, while the complete outdoor handset matrix remains open.

The September completion regression work moves celebration feedback above the expanded-map window, keeps it available until dismissal, queues simultaneous completion and badge events, and supports scrolling at larger text sizes. The refreshed gallery now shows the corrected session-complete state. Timer completion is distinct from GPS recording, verified distance and earned performance credit. Automated checks and physical-device acceptance remain separately reported.

Runnerz 1.1.0 hardens live foreground GPS tracking, branded full-span trails, useful movement metrics, responsive enlarged-map controls, route-selected starts, durable account-scoped Banked Miles, privacy-safe Running Nearby, production moderation surfaces, women-only invitations, current legal-document acceptance and the UNIFIED music handoff. It also expands the sponsor/event Community rail, badge foundations, real-map route studies and Shadrac “ShowTime” Mavungu’s official ambassador presentation.

The current source release is Runnerz Live `1.1.0` / versionCode `15` and Runnerz Field Test `1.1.0-field-test` / versionCode `15`. The latest private Field Test build is the sole release retained in Firebase App Distribution; this is not a public-store availability claim. The earlier [`docs/RELEASE-1.0.13.md`](docs/RELEASE-1.0.13.md) remains as historical evidence, while the controlled 1.1.0 handset proof and the open release gates below describe the current boundary.

Account creation, email confirmation, visible-password controls, matching-password validation, resend confirmation, privacy-safe recovery and authenticated in-app password updates are connected to Supabase Auth. A real founder recovery uncovered a callback/session race; the release now waits for the genuine authenticated recovery session before exposing the password-update form.

Core route discovery, matching, community, editable profiles, lawful SOS dialling and notification foundations have been built and exercised. The route map renders ranked public meetup options for catalogue or live-backed routes, with selection, camera focus and an explicit field-check boundary. Hosted database policy tests cover current legal acceptance, expiring nearby presence, run audiences and protected RPC execution. Wider cohort validation, field verification, release signing and store review remain deliberate gates rather than launch claims.

### Open release gates

- Recheck hosted account and legal reacceptance flows on both variants after their in-place handset updates.
- Verify the complete moving-run journey outdoors: accepted trail, pause/resume gaps, route proximity, metrics, protected finish and Banked Miles.
- Minimize and lock the phone, then verify location continuity and notification pause/resume/open-to-finish controls across relevant Android and OEM background states.
- Measure outdoor distance accuracy and battery impact on the supported device range. Existing screenshots do not close these gates.
- Confirm ordinary notification mirroring on a paired Wear OS watch if available. Runnerz 1.1.0 is not a native Wear OS app and does not provide watch-side GPS or SOS.
- Supply external release signing, produce the signed Play AAB and complete Play Console Data safety, Health apps, foreground-service, reviewer-access, rating, privacy and deletion declarations.
- Complete the final security-advisor and production music-signing checks before broad rollout.
- Build and verify separate iOS/watchOS products. This Android repository contains no iOS, iPadOS, watchOS, Apple signing, privacy manifest or TestFlight target; Apple App Store and Apple Watch support are not claims of this release.

## Repository boundary

This public repository intentionally excludes deployable Android source, database migrations, backend identifiers, private user information, environment files, signing material and internal infrastructure.

Security concerns should be sent privately to [info@runnerznamibia.com](mailto:info@runnerznamibia.com).

---

© 2026 Runnerz Namibia. Product and brand material is shared for portfolio viewing. No licence is granted to reproduce the product, identity or documentation.
