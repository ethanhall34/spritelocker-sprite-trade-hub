# SpriteLocker v2026 - trade tracker web

> **Use SpriteLocker v2026 to track, compare, and organize your Fortnite Sprite collection in the browser. This Supabase-powered trade tracker helps you log progress, upload proof, and identify possible trade matches.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/ethanhall34/spritelocker-sprite-trade-hub?style=flat-square)](https://github.com/ethanhall34/spritelocker-sprite-trade-hub)

---

<p align="center">
  <a href="https://ethanhall34.github.io/spritelocker-sprite-trade-hub/">
    <img src="https://img.shields.io/badge/Download-SpriteLocker%20Latest-brightgreen?style=for-the-badge" alt="Download SpriteLocker">
  </a>
</p>

> **[Direct Download - SpriteLocker v2026](https://ethanhall34.github.io/spritelocker-sprite-trade-hub/)**

---

[Download Latest Build](https://ethanhall34.github.io/spritelocker-sprite-trade-hub/)

---

## What SpriteLocker Does

SpriteLocker is a web-based tracker for managing Fortnite Sprite collections. It provides a simple place for collectors to record the Sprites and variants they have, keep their inventory aligned with the current season, and view collection progress from one central dashboard.

It also includes trade-oriented tools so users can browse other collectors and evaluate possible matches. With Supabase as the backend and GitHub Pages serving the static front end, SpriteLocker stays lightweight while still supporting login access, proof uploads, and season-aware collection tracking.

---

## Key Features

- Sign in and maintain your personal collection records
- Flag collected Sprites and keep track of variants
- Upload image or video proof for collection entries
- Browse other collectors and compare possible trade matches
- Keep the sprite catalog aligned with the active season
- Run the static front end on GitHub Pages
- Persist app data through a Supabase backend
- Keep collection rules in `sprites.js` for straightforward season updates

---

## Installation

1. Clone the repository or download the source files.
2. Open the project in your preferred editor.
3. Configure the Supabase connection details before publishing or testing.
4. Serve the site locally or deploy the static files to GitHub Pages.

Example local launch:

    # If you are serving the files locally
    python -m http.server 8000

Then open the site in your browser and sign in to begin tracking your collection.

---

## Usage

1. Sign in with your configured account.
2. Add the Sprites and variants you have collected.
3. Upload proof images or clips when needed.
4. Review the collectors list to look for trade opportunities.
5. Update your collection as the season changes.
6. Refresh the sprite list in `sprites.js` when new entries are introduced.

Typical workflow:

- Open the tracker
- Update your collected items
- Compare your list with other users
- Save proof and trade notes
- Revisit the tracker as the season progresses

---

## Configuration

Most project settings are controlled by the Supabase connection and the static data files used by the site. If you need to change the sprite catalog or season lineup, edit the sprite definitions in `sprites.js`.

Example structure:

    {
      "season": "current",
      "sprites": [
        {
          "name": "Sprite Name",
          "variant": "Variant Label",
          "collected": false
        }
      ]
    }

If your deployment uses different credentials or endpoints, update those values in the app configuration before publishing.

---

## Requirements

- A web browser
- A GitHub Pages hosting setup for the static site
- A Supabase project for backend data storage and login support
- Basic access to the repository files for updating `sprites.js`
- Internet access for loading the hosted app and backend services

---

## FAQ

**How do I update the sprite list?**  
Edit `sprites.js` and publish the site again so the latest season data is available.

**Where is user data stored?**  
Collection records and related app data are handled through Supabase.

**Can I use this without deploying to GitHub Pages?**  
The app is built as a static site, so it can be hosted anywhere that serves the required files, but the provided setup uses GitHub Pages.

**What should I do if logins or uploads do not work?**  
Check the Supabase settings, confirm the project is deployed with the correct configuration, and verify that the backend tables and permissions are set up as expected.

**How do I keep the tracker current?**  
Review the season list regularly and update the sprite entries whenever the collection changes.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
