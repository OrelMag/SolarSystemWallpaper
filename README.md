# Solar System Wallpaper

Lively Wallpaper packages for animated astronomy wallpapers.

## Wallpapers

- `SolarSystemDynamic.zip` - stylized solar system map with planets, moons, orbit rings, asteroid belt, and subtle trails.
- `EarthMoonSeasonsDynamic.zip` - Sun/Earth/Moon wallpaper with NASA Blue Marble imagery, visible Earth rotation, moon phases, axial-tilt season explanation, month markers, and a Jerusalem daylight graph.

Both wallpapers use a pure-black, star-free background and run automatically without interaction.

### Earth Moon Seasons

- A 45-minute animated year with one Earth rotation every 7.4 seconds and one Moon orbit every 3.37 minutes.
- A textured, shaded Earth with atmosphere, moving clouds, fixed 23.5-degree axial tilt, and highlighted direct-ray and Israel latitudes.
- Short sunlight rays explain Northern Hemisphere seasons without implying that distance from the Sun causes them.
- English-only month, season, moon-phase, and Jerusalem daylight displays based on latitude 31.8N.

## Use

1. Open Lively Wallpaper.
2. Drag one of the `.zip` files into Lively, or use `Add Wallpaper`.
3. Select the imported wallpaper.

Each zip has `index.html` and `LivelyInfo.json` at the archive root, which is the Lively import format. The Earth/Moon package also includes `earth-blue-marble.png` at the archive root.

## Source

- Root `index.html` and `LivelyInfo.json` build `SolarSystemDynamic.zip`.
- `EarthMoonSeasons/` builds `EarthMoonSeasonsDynamic.zip`.

No build tools or dependencies are required; the wallpapers are self-contained HTML canvas files.

## Earth imagery

`EarthMoonSeasons/earth-blue-marble.png` is NASA's 1024 x 512 Blue Marble image. Credit: NASA/GSFC Scientific Visualization Studio; Blue Marble data by Reto Stockli/NASA Earth Observatory.

- Source: https://svs.gsfc.nasa.gov/2915
- NASA media guidelines: https://www.nasa.gov/nasa-brand-center/images-and-media/
