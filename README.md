# Wuthering Waves Material Calculator

A web-based material calculator for [Wuthering Waves](https://wutheringwaves.kurogames.com/) that helps players plan and track the resources needed to level up characters and weapons.

All data is fetched live from the API.

## Data Source

This project uses **encore.moe API v2** for all game data, including characters, weapons, items, and material costs. All assets and game data belong to their respective owners.

- API Documentation: [encore.moe](https://api-v2.encore.moe/_docs/scalar#description/introduction)
- API Creator's GitHub: [github.com/alt3ri](https://github.com/alt3ri)

## Usage

This is a single static HTML file with no build step or dependencies required.

1. Clone or download this repository.
2. Open `index.html` in any browser.
3. Select a character and/or weapon to view their materials.
4. Adjust the level and skill sliders to match your leveling goals.
5. Use the conversion calculator to determine if you have enough materials with conversion.

Alternatively, visit the hosted version at: [wuwacalc](https://junh513.github.io/wuwacalc/)

## Tech Stack

- React 18 (via CDN)
- Vanilla CSS
- encore.moe API v2 (no API key required)

## Disclaimer

This project is not affiliated with or endorsed by Kuro Games. All game assets, names, and data are the property of their respective owners. Game data is provided by the encore.moe API.
