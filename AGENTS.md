# Codex Instructions For This Japan Trip Project

This project is for researching and organizing a Japan trip from **24 Dec 2026 to 7 Jan 2027**.

## Operating Rules

- Treat `data/itinerary/confirmed-itinerary.md` as the source of truth for confirmed plans.
- Do not overwrite confirmed bookings or confirmed dates unless the user explicitly says the plan has changed.
- Keep research candidates separate from confirmed decisions.
- When researching current information, browse the web and cite source links.
- Prefer official sources first for schedules, closures, hotel policies, admission rules, transport passes, and booking requirements.
- For hotels and restaurants, use a mix of official websites, booking platforms, maps, and recent review sources when available.
- Record the date research was performed.
- If a detail is uncertain, mark it clearly as `Needs verification`.
- Do not invent prices, cancellation rules, room availability, booking references, addresses, or opening hours.
- If live prices or availability are important, say that they can change and include the retrieval date.

## Update Discipline

Before editing files:

1. Read the relevant existing files.
2. Preserve confirmed information.
3. Add new research under a dated heading.
4. Link sources in `data/source-links/`.
5. If a recommendation is made, add the rationale and tradeoffs.

## Dashboard Synchronization

- Treat `dashboard/index.html` as a required presentation layer for the current trip plan.
- Whenever an itinerary, booking, cancellation, decision, transport plan, accommodation status, date, price, budget, or task status changes, update the relevant source-of-truth files and `dashboard/index.html` in the same change.
- Keep dashboard totals, booked-night counts, alerts, status labels, itinerary entries, booking cards, prices, and budget summaries consistent with the underlying data.
- Deliberate booking conflicts must appear clearly on the dashboard and must not be counted twice in confirmed-spend totals unless both bookings will be used.
- Before completing the task, validate that the dashboard contains the new information and no longer contains the superseded status or value.
- When changes are committed and pushed, verify the published dashboard at `https://psprateek7.github.io/Trip/`. Account for deployment delay or caching, and do not report the live dashboard as updated until the published page reflects the change.

## Recommended Research Flow

1. Clarify the task if the dates, city, budget, or traveller preferences are missing.
2. Check the confirmed itinerary.
3. Browse current web information.
4. Compare options in a table.
5. Save source links.
6. Update the relevant data file.
7. If the user chooses an option, add a decision record in `data/decisions/`.
8. Synchronize and validate `dashboard/index.html` whenever the plan or its status changes.

## Accommodation Comparison Criteria

Use these criteria unless the user asks for something different:

- Exact stay dates and number of nights.
- Neighbourhood and transport access.
- Walking distance to relevant station or attraction.
- Room type and bed setup.
- Total price and taxes/fees if visible.
- Cancellation policy.
- Breakfast availability.
- Check-in and check-out times.
- Luggage storage.
- Family suitability and room size.
- Recent review themes.
- Booking source and direct hotel website link.
- Pros, cons, and recommendation.

## Transport Research Criteria

- Route options.
- Official operator links.
- Timetable or service-frequency notes.
- Booking window and reservation requirements.
- Luggage rules.
- Estimated journey time.
- Estimated cost.
- Backup option if the preferred route is unavailable.

## Output Style

- Use Markdown tables for comparisons.
- Keep recommendations concise and practical.
- Include `Research date`.
- Include `Sources` with links.
- Separate facts from opinion.
- End with next actions only when useful.

## Known Confirmed / Current Plans

- Tokyo arrival: **Thu 24 Dec 2026**, around 9 PM.
- Tokyo stay: **24 Dec 2026** at newly booked Tokyo hotel.
- Tokyo area preference: **Tsukiji / Higashi-Ginza** for **25-27 Dec 2026**.
- Kanazawa: **27-29 Dec 2026**.
- Shirakawa-go visit: **29 Dec 2026**. Minshuku Koshiyama is also booked for **29-30 Dec 2026**, creating a deliberate overlap with Hotel Kuretakeso Takayama-Ekimae; one booking will eventually be cancelled.
- Takayama: **29 Dec 2026 to 1 Jan 2027**.
- Confirmed Takayama ryokan: **Ryokufuen Kiyoharu**, **31 Dec 2026**.
- Kyoto: **1-5 Jan 2027**.
- Confirmed Kyoto hotel: **Miyako Hotel Kyoto Hachijo**, **1-5 Jan 2027**.
- Confirmed Tokyo final stay: **Hotel Sardonyx Tokyo**, **5-7 Jan 2027**.
- Departure: **Thu 7 Jan 2027**, evening return flight to Christchurch.
