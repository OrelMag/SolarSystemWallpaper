# Solar System Wallpaper

Lively Wallpaper packages for animated astronomy wallpapers.

## Wallpapers

- `SolarSystemDynamic.zip` - stylized solar system map with planets, moons, orbit rings, asteroid belt, and subtle trails.
- `EarthMoonSeasonsDynamic.zip` - Sun/Earth/Moon wallpaper with NASA day and night imagery, city lights, real-date and demo modes, moon phases, axial-tilt season explanation, month markers, and a Jerusalem daylight graph.

Both wallpapers use a pure-black, star-free background and run automatically without interaction.

### Earth Moon Seasons

- Real Date mode uses the current Israel date, approximate current Moon phase, and a visible 60-second visual Earth day.
- The optional 45-minute demo uses one Earth rotation every 7.4 seconds and one Moon orbit every 3.37 minutes.
- A textured, shaded Earth with atmosphere, moving clouds, night-side city lights, fixed 23.5-degree axial tilt, and highlighted direct-ray and Israel latitudes.
- Short sunlight rays explain Northern Hemisphere seasons without implying that distance from the Sun causes them.
- English-only month, season, moon-phase, and Jerusalem daylight displays based on latitude 31.8N.
- A persistent `Time mode` dropdown is available from Lively's `Customise` menu.

## Use

1. Open Lively Wallpaper.
2. Drag one of the `.zip` files into Lively, or use `Add Wallpaper`.
3. Select the imported wallpaper.

Each zip has `index.html` and `LivelyInfo.json` at the archive root, which is the Lively import format. The Earth/Moon package also includes `LivelyProperties.json`, `earth-blue-marble.png`, and `earth-city-lights.jpg` at the archive root.

## Source

- Root `index.html` and `LivelyInfo.json` build `SolarSystemDynamic.zip`.
- `EarthMoonSeasons/` builds `EarthMoonSeasonsDynamic.zip`.

No build tools or dependencies are required; the wallpapers are self-contained HTML canvas files.

## Earth imagery

`EarthMoonSeasons/earth-blue-marble.png` is NASA's 1024 x 512 Blue Marble image. Credit: NASA/GSFC Scientific Visualization Studio; Blue Marble data by Reto Stockli/NASA Earth Observatory.

`EarthMoonSeasons/earth-city-lights.jpg` is derived from NASA Earth Observatory's 2012 Night Lights map and resized to 1024 x 512 for offline use.

- Source: https://svs.gsfc.nasa.gov/2915
- Night Lights source: https://earthobservatory.nasa.gov/images/79765/night-lights-2012-map
- NASA media guidelines: https://www.nasa.gov/nasa-brand-center/images-and-media/
