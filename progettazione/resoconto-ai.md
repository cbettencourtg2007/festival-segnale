# AI Work Log — Segnale Festival

## Session 1 — Reviewing the project

- **What I asked:** I asked for help reviewing the website files and organising the event and venue information.
- **What I used:** I used the suggestion to keep events and venues in separate JSON files.
- **What I checked:** I kept the existing pages, navigation, fonts and design, and reviewed the project structure.

## Session 2 — Preparing the JSON files

- **What I asked:** I asked for help completing the event data and correcting the venue data.
- **What I changed:** I organised six events and three venues, connecting them through `sede_id`.
- **What I checked:** I checked the fields, IDs and JSON syntax. I corrected missing commas in `sedi.json`.

## Session 3 — Connecting the Programme page

- **What I asked:** I asked how to load event cards from the JSON files using JavaScript.
- **What I used:** I used the HTML structure and JavaScript `fetch()` code.
- **What I changed:** I replaced the static event cards with dynamically generated cards.
- **What I checked:** I tested the page and corrected a repeated variable declaration (`statoEventi`).

## Session 4 — Testing the website

- **What I asked:** I asked why the loading message remained on the page and how to test the website on my Mac.
- **What I used:** I followed the instructions to install and use Live Preview in Visual Studio Code.
- **What I checked:** I verified the HTML, JavaScript and JSON file paths. The page displayed correctly in Live Preview.

## Session 5 — Documenting the data

- **What I asked:** I asked for help creating `dati/SCHEMA.md` in English.
- **What I used:** I used the data sheet describing the Event and Venue entities, their fields, keys and relationship.
- **What I changed:** I added a Mermaid diagram showing the Event–Venue relationship.
- **What I checked:** I compared the documentation with the JSON files.

## Session 6 — Preparing for publication

- **What I asked:** I asked how to make the website accessible online and why it did not appear in Safari or Google.
- **What I used:** I followed the explanation about local preview and GitHub Pages.
- **What I decided:** I chose GitHub Pages to publish the project using the existing repository.
- **What I checked:** I confirmed that the website works in Live Preview. The public version still needs to be published and tested.