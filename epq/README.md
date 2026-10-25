# Maximos EPQ Studio

A static EPQ workspace for the investigation of EV and petrol vehicle lifecycle emissions and carbon break-even distance. Open `index.html` or use GitHub Pages at `/mywebpage/epq/`.

## Included

- Project question, rationale, objectives, scope and milestones
- Source library with reliability evaluations
- Six-chapter drafting workspace with word counts
- Activity log and manual AI-use record
- Evaluation, presentation and submission checklists
- Carbon model with charging losses, manufacturing differences, grid scenarios, annual mileage and lifetime distance
- JSON backup/restore and printable HTML working-record export

No API keys, AI service, server or build step is required. The model inputs are illustrative and must be replaced with sourced values.

## Saving and moving work

Records are stored only in the browser's local storage, under `maximos-epq-v1`. They are not committed to GitHub, and do not sync across devices. Export backups regularly. Before moving from the ChatGPT-hosted version, export a backup there, open this version, and restore that JSON backup. Restore replaces the browser's current EPQ record.

The public website contains the application and its default project prompts, not a student's saved draft. Do not commit personal backups, research PDFs, or completed school forms to this public repository. Keep the original assessment documents and school templates separately.

## Carbon model

EV gCO2e/km = battery kWh/100 km / charging efficiency fraction * grid gCO2e/kWh / 100.
Petrol gCO2e/km = litres/100 km * petrol gCO2e/litre / 100.
Positive manufacturing difference (grams) divided by positive operating savings (grams/km) gives carbon break-even kilometres.

Use equivalent vehicles, cycles and greenhouse-gas boundaries. Do not double count battery manufacturing or charging losses. The constant-rate model does not include maintenance, battery replacement, disposal or future grid changes.
