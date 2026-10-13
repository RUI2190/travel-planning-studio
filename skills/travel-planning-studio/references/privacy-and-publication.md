# Privacy and publication

Read this reference before publishing a map, guide, dataset, repository, or share link.

## Separate private planning data from public destination data

Maintain one evidence base, but do not expose every field in every artifact.

- **Private planning view:** traveler constraints, party structure, exact arrival and departure segments, confirmed bookings, booking codes, budgets, room or accessibility requirements, personal contacts, and day-by-day decisions.
- **Public destination view:** place name, public address, category, approximate public coordinates, concise reason to visit, generally useful access notes, public business contact channels when genuinely necessary, and clearly labeled facts that require rechecking.

The public view must be generated through an allowlist. Do not publish the private dataset and then try to hide sensitive fields only in the interface.

## Public-map rules

A reusable public map should be location-centric rather than traveler-centric.

Include:

- what the place is and why someone might visit;
- public opening, ticket, access, or seasonal notes with a checked date when available;
- navigation name, public address, category, area, and coordinate precision;
- neutral relationships such as “near the museum” or “connects to the station.”

Exclude unless explicitly authorized:

- exact trip dates, arrival times, departure times, hotel nights, or “already booked” labels;
- traveler names, group size, rendezvous instructions, private phone numbers, booking references, or payment details;
- personal rankings such as “our first choice,” private fallback decisions, or instructions tied to one person’s stamina, vehicle, room, or schedule;
- transient weather, packing advice, and same-day execution notes better suited to a private guide.

Public business addresses and public service phone numbers are not inherently personal, but include them only when they materially help and their source is reliable.

## Pre-publication audit

Before a public upload or visibility change:

1. Search the repository and generated artifacts for names, usernames, email addresses, phone numbers, booking codes, exact trip dates, arrival/departure times, “booked” language, and private locations.
2. Inspect source data and scripts, not only the rendered page. Data hidden by CSS or overwritten later is still published.
3. Check filenames, page titles, repository names, metadata, example data, route-service client identifiers, and README links for project-specific or personal strings.
4. Open the public artifact and test that search cannot reveal removed private terms.
5. Reconfirm the intended repository visibility and obtain action-time authorization before changing permissions, renaming a repository, or committing publicly.

If a field is useful only to the original traveler, keep it in a private companion guide rather than the public map.
