# Gategaurd

**When plans change, your next step is made clear.**

GateGuard is a web app that helps travelers recover from a cancelled flight. Instead of juggling airline apps, maps and search results, the traveler enters their disruption once and gets a clear plan: what to do, in what order, and where to go.

Built by Atharv Borhade and Giri Anantharaman.

## The problem

A cancelled flight is more than a missed connection. Travelers face three problems at once:

1. **Missed connections.** They don't know which route to take next.
2. **Uncertain shelter.** Finding a safe place to stay becomes stressful.
3. **Missing essentials.** Food, medication and ground transport still matter.

## What it does

1. **Enter the disruption.** The traveler gives their airport, destination, cancelled flight and the reason given. They also choose their needs (children, accessibility, medication, overnight stay, checked bags) and their priority (fastest, cheapest or least hassle).
2. **Review options.** GateGuard ranks other ways to get there: rebook with the same airline, switch airlines, use a nearby airport, travel by ground, or wait until morning.
3. **Follow the timeline.** It builds a prioritised checklist based on the traveler's needs, with a progress bar.
4. **Find essentials.** One-tap map searches for hotels, food, pharmacy and transport near the airport.
5. **Stay on track.** A built-in countdown reminds the traveler to check their rebooking status.

## Impact and creativity

- **Human-centred.** It accounts for families, essentials and accessibility.
- **Proactive.** Reminders prompt users to check rebooking and key tasks.
- **Action-oriented.** It turns scattered information into steps.
- **Room to scale.** It could expand to more airports and disruption types.

## Tech

- Single self-contained HTML file with vanilla JavaScript and CSS, no build step or dependencies
- Responsive layout, light and dark themes, keyboard-accessible, respects reduced-motion settings
- Fonts: Newsreader and DM Sans (Google Fonts)

## Running it

Open `gateguard.html` in any modern browser.

## Limitations and next steps

- GateGuard does not use live flight, fare or hotel data. Route rankings are guidance to confirm with the airline.
- Essentials link out to Google Maps searches for the traveler's airport.
- The reminder only runs while the page is open.
- **Planned:** live flight-status API, airport-specific information, saved trips, push notifications, and more disruption types such as delays and diversions.

## Disclaimer

GateGuard offers general guidance, not legal or financial advice. Refund, meal and hotel entitlements vary by airline, country and cause of cancellation, so confirm with your carrier.
