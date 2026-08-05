# Japan Trip Planning Project

This Codex project is a structured workspace for planning and researching the Japan trip from **24 Dec 2026 to 7 Jan 2027**.

## Trip Dashboard

Open [`dashboard/index.html`](dashboard/index.html) for the user-friendly itinerary, booking-status, and budget interface.

Published dashboard: https://psprateek7.github.io/Trip/

Changes under `dashboard/` are automatically deployed by GitHub Pages when pushed to `main`.

Use it when you want Codex to:

- Research accommodation, transport, activities, food, closures, luggage forwarding, or neighbourhood details.
- Compare options using current web information.
- Keep confirmed plans separate from research candidates.
- Save source links, notes, decisions, and budgets in organized Markdown files.

## Trip Snapshot

| Date | Location | Current Plan |
| --- | --- | --- |
| Thu 24 Dec 2026 | Christchurch to Tokyo | Fly to Tokyo Narita, arriving at 8:10 PM. Check in to Hotel Ann Tsukiji. |
| Fri 25 Dec 2026 | Tokyo | First full Tokyo day around Tsukiji / Higashi-Ginza. |
| Sat 26 Dec 2026 | Tokyo | Classic Tokyo city day. |
| Sun 27 Dec 2026 | Tokyo to Kanazawa | Travel to Kanazawa. |
| Mon 28 Dec 2026 | Kanazawa | Kenrokuen, Higashi Chaya, samurai district, market area. |
| Tue 29 Dec 2026 | Kanazawa to Shirakawa-go to Takayama | Visit Shirakawa-go, then continue to Takayama. |
| Wed 30 Dec 2026 | Takayama | Old town, morning market, relaxed alpine town day. |
| Thu 31 Dec 2026 | Takayama | Stay at Ryokufuen Kiyoharu ryokan for New Year's Eve. |
| Fri 1 Jan 2027 | Takayama to Kyoto | Travel to Kyoto. Check in at Miyako Hotel Kyoto Hachijo. |
| Sat 2 Jan 2027 | Kyoto | Temples, shrines, Gion / Higashiyama. |
| Sun 3 Jan 2027 | Kyoto | Arashiyama, bamboo grove, riverside, quieter temples. |
| Mon 4 Jan 2027 | Kyoto | Flexible Kyoto / Nara / Uji day. |
| Tue 5 Jan 2027 | Kyoto to Tokyo | Travel back to Tokyo. Final Tokyo stay begins. |
| Wed 6 Jan 2027 | Tokyo | Shopping, neighbourhood exploring, relaxed final experiences. |
| Thu 7 Jan 2027 | Tokyo to Christchurch | Final shopping / relaxed morning. Evening return flight. |

## Folder Structure

| Folder | Purpose |
| --- | --- |
| `data/itinerary/` | Confirmed itinerary, daily plans, open itinerary questions. |
| `data/accommodation/` | Hotel searches, comparisons, candidate shortlists, booking notes. |
| `data/transport/` | Trains, buses, flights, luggage forwarding, route notes. |
| `data/activities/` | Things to do, restaurants, closures, seasonal events. |
| `data/budgets/` | Cost estimates and booking price snapshots. |
| `data/source-links/` | URLs and source notes from research. |
| `data/decisions/` | Final choices, rationale, and rejected options. |
| `prompts/` | Reusable prompts to give Codex. |
| `templates/` | Markdown templates for comparisons and research notes. |
| `examples/` | Example research tasks. |
| `dashboard/` | User-friendly trip dashboard. |

## How To Use

Ask Codex a focused task, for example:

```text
Research 5 accommodation options in Kanazawa for 27-29 Dec 2026. Use the project rules, cite sources, compare location and cancellation policy, then update the accommodation files.
```

Or:

```text
Find the best way to travel from Kanazawa to Shirakawa-go to Takayama on 29 Dec 2026. Check current bus schedules, booking requirements, luggage issues, and update data/transport.
```

## Important Rule

Confirmed plans are stored in `data/itinerary/confirmed-itinerary.md`. Codex should not overwrite them unless you explicitly say a plan is confirmed or changed.
