# Baseball Flight Lab

A browser-based baseball flight physics simulator: RK4 integration with drag, Magnus lift, gravity and Coriolis; air density from temperature, elevation, pressure and humidity; wind; all 30 MLB parks (elevation, latitude, orientation, fence outlines and heights, roofs); a 500-ball Monte Carlo; and a "Hit Finder" that solves for the contact that lands a ball on a spot you click.

Everything runs client-side in a single static `index.html` — no server, build step or API keys.

## Run locally
Open `index.html` in a browser.

## Notes and data sources
- Park outfield outlines were derived from the open [GeomMLBStadiums](https://github.com/bdilday/GeomMLBStadiums) dataset and calibrated to posted fence distances.
- Seating-stand depths and heights are approximations by park/sector type, not surveyed data.
- Not affiliated with MLB or any club.
