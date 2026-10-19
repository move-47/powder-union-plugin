# Powder Union

Free snow reports for more than 650 European ski resorts, inside Claude. Ask how the snow is at a resort, where to ski this weekend, or for this week's European snow roundup. Claude answers with recent snowfall, forecasts, the best day to go and how the season compares to normal.

Data comes from [powderunion.eu](https://powderunion.eu): modelled snowfall from Open-Meteo (ECMWF and national weather services), observed snow depth from SLF IMIS stations in Switzerland, and resort data from OpenSkiMap/OpenStreetMap. It is refreshed every 6 hours and given in centimetres.

## What's included

- **Powder Union connector** (`https://powderunion.eu/api/mcp`): 11 read-only tools for resort search, resort snow reports, snowfall history since 2017, region and country roll-ups, top snowfall rankings, a weekly summary and snow card images. No account or API key.
- **Skills:**
  - `snow-check`: conditions, forecast, best day and season-vs-normal for one resort.
  - `find-best-snow`: where the most snow is or will be, with a comparison table of the top resorts.
  - `weekly-snow-briefing`: a short European snow roundup for the week.

## Use it

After installing, connect the Powder Union connector from the plugin's **Connectors** tab (no sign-in needed). Then try:

- "Is next weekend looking good for Val Thorens?"
- "Where in Austria will it snow most in the next 7 days?"
- "Compare Chamonix, Verbier and St. Anton for a trip in two weeks."
- "Give me this week's European snow briefing."

## Data and privacy

The plugin runs no local code. Claude sends only tool arguments, such as a resort name, region or country, to `powderunion.eu`. It never sends your conversation, account details or location. Powder Union has no accounts, ads or tracking. See the [privacy policy](https://powderunion.eu/privacy).

Not for avalanche or off-piste decisions: always check the local avalanche bulletin.

## Support

hello@move47.co · [Developer docs](https://powderunion.eu/about#developers)
