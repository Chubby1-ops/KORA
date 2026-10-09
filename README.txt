KORA WORLD — REAL MAP TEST BUILD

RUN IN GOOGLE CHROME:
1. Extract this ZIP into a new folder.
2. Keep the computer connected to the internet.
3. Open index.html in Google Chrome (double-click, or Chrome > Ctrl+O).
4. If Chrome asks, allow the page to load external content.

REAL MAP:
- Uses Leaflet and OpenStreetMap tiles over the internet; no map API key is required.
- Actual roads/streets come from OpenStreetMap. City/destination pins are selected real-world geographic anchors.
- Pick Lagos, Abuja, Port Harcourt, or Enugu in the start screen.
- Tap/click a destination marker, then choose Walk here; the game moves your player marker to that geographic destination.
- Blue YOU marker = your character. Letter markers = simulated residents. Building/place markers = activities.
- + / - zoom; target button centers on your character; arrow button follows the selected destination.

CONTROLS:
- Tap a place marker, then Walk here.
- Tap a resident marker to open profile/chat.
- Bottom navigation: Life, City, Work, People, Phone.
- Keyboard E opens a nearby interaction (within roughly 1 km); Escape closes panels.

GAMEPLAY:
- Character backgrounds, needs, money, jobs/gigs, skills/XP, housing/rent, social connections, simulated chats, virtual gifts, city travel, life story and local save.
- Chat residents are simulated NPCs, not live players. Real multiplayer requires a backend and database.
- Some actions use simplified map travel: this test version teleports the player marker to the selected destination after calculating travel cost/time; walking route animation is not implemented yet.

TROUBLESHOOTING:
- If you see "Map library did not load", check internet and reload the page. The Leaflet JavaScript library loads from unpkg.com.
- If map tiles are blank, test another internet connection or reload; map tiles are provided by OpenStreetMap. The site requires online access.
- OpenStreetMap attribution is shown on the map. Use the map respectfully and do not bulk-download tiles.

SAVE:
- Progress is saved locally in Chrome under the key kora_real_map_v1, separate from previous KORA test builds.
