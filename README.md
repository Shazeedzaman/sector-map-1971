# Eleven Sectors — Bangladesh Liberation War, 1971

An interactive, single-file map of the eleven sectors into which the Bangladesh Forces
divided the country in 1971, with sector commanders, headquarters, sub-sectors, and the
present-day districts that fall inside each sector.

**Live:** https://USERNAME.github.io/sector-map-1971/

## What's in it

- Clickable SVG map of Bangladesh with all 11 sectors colour-coded
- Commander(s) for each sector with their dates of command
- Sector headquarters (most sat just across the Indian border)
- 1971 area of operations, mapped onto today's 64 districts
- Sub-sector names
- A summary table of all eleven sectors

## Running it

There is no build step and no dependencies. Open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
```

## Notes on accuracy

The map is schematic. Sector boundaries in 1971 followed the old 19 districts and major
rivers, and several were redrawn during the war — Sector 8 was reconstituted at the end of
May, and Sector 11 held pockets west of the Jamuna at Gaibandha and Chilmari. Sector 10 had
no land territory: it was the naval commando force under the Commander-in-Chief, shown on
the map as a marker in the Bay of Bengal.

Districts marked with a dashed outline are partial — only part of that district fell inside
the sector.

## Sources

- Bangladesh Army, *Sectors in the Liberation War* — army.mil.bd
- Banglapedia
- Liberation War Museum, Dhaka
- Maj. Gen. K. M. Safiullah, *Bangladesh at War*

Corrections are welcome — open an issue with a source.

## Licence

Code: MIT. Historical content is drawn from the public sources listed above.
