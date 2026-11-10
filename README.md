# AETHERWRECK: The Drowned Sky

A first-person, post-apocalyptic steampunk zeppelin game in voxel pixel art. It runs in the browser on a small planet you can fly all the way around. It has a playable story, towns full of people, trade, reputation and wanted levels, split-screen couch co-op and online co-op for up to 4 players.

> Sixty years ago the Empire's forges overheated, and the poisonous Aether Fog drowned the world below a thousand feet. The survivors live in towns on floating rocks and fly patched-up zeppelins.

## How to start

Open `index.html`. It works from a local folder or from GitHub Pages. Click into the game to capture the mouse; `Esc` releases it and pauses. The language (Magyar / English / Français) is chosen in the main menu.

## The world

- **A planet.** Radius 5.2 km, circumference about 32.7 km (about 21 minutes around at full steam). Fly in one direction long enough and you come back where you started. The horizon curves, and day and night depend on where you are on the globe.
- **Sky layers**, each with its own wind direction:
  - **High Sky:** cold and rich, with icy winds.
  - **Middle Sky:** where most towns are.
  - **Fog Edge:** scavengers and stratus banks.
  - **The Deep:** under the poisonous fog, with ruins and wrecks.
- **Clouds:** cumulus, high "sheep" clouds, low fog banks and storm towers. Inside a cloud you see almost nothing. Aether storms throw lightning that can set your envelope on fire.
- **Twelve towns**, each with its own people, goods, prices and jobs. Raven's Nest belongs to the pirates. Ironbastion is held by the Iron Crown.

## Your zeppelin

You fly it from inside the gondola and can walk through every room:

- **Cockpit:** the wheel and the dashboard, with altimeter, speed, boiler pressure, firebox, compass, all six gas cells and the engine telegraph.
- **Chart room:** a brass globe on the table opens the globe map. The two side cannons are here too.
- **Quarters:** bunks, plus the water tank for refilling the extinguisher. A hatch in the floor leads down to the **ball turret** under the gondola.
- **Engine room:** carry coal from the bunker into the firebox `[E]` and watch the pressure. If it goes into the red, open the safety valve or the boiler blows.
- **Ladders:** one goes from the roof up into the envelope, along the **keel catwalk**, and on to the **roof lookout** with a machine gun.

**Damage:**
- The envelope holds 6 gas cells. Every hole leaks visible gas. As a cell empties, the envelope wrinkles and the ship tilts.
- Fire burns through cells and must be put out with the extinguisher (4).
- Shot-up engine pods slow you down, and shot-up tail fins make you steer worse.
- Patch holes with the hammer (3): planks for the gondola, canvas for the envelope. Docks sell gas refills and full repairs.

## Controls

| Key | On foot | At the helm | At a gun |
|---|---|---|---|
| WASD | move (W/S also climb ladders) | W/S: telegraph (R, 0–4), A/D: rudder | – |
| Mouse | look | look around | aim |
| Space / C | jump | climb / descend | – |
| E | use, talk, take or put coal, refill water | moor at a town mast, or cast off | – |
| Q | – | leave | leave |
| B / H | – | drop ballast / horn | – |
| Left click | use the item in your hand | – | fire (hold for machine guns) |
| 1–6 | sabre · pistol · hammer · extinguisher · grapple · spyglass/camera | | |
| Tab / M | globe map, jobs and reputation (drag to rotate, wheel to zoom) | | |

- **Grapple (5):** shoots you across to another ship or a rock. Use it to board pirate ships.
- **Spyglass (6):** zooms in. Click while zoomed to take a photo; town halls buy photos of whales, storms and the Drowned Crown.
- **Glider:** opens by itself when you fall.

## Towns, trade, reputation and wanted levels

To moor, fly slowly up to a town's mooring mast and press `E` at the helm. Then walk down the mast ladder into the town.

| Place | What you can do there |
|---|---|
| **Trader** | buy and sell goods (coal, food, cloth, aether crystal, machine parts, spirits, forge powder) and supplies; sell loot |
| **Town hall** | job board (deliveries, pirate hunts, salvage from the fog, photographs), pay fines, sell photos |
| **Inn** | rumours and drinks |
| **Shipwright** | zeppelin upgrades: armour, envelope, engine, quick-loading cannons, automatic stoker, bigger hold |
| **Mastmaster** | gas refill, full repair, coal, ballast |

Prices depend on what a town produces and what it needs, so buy cheap and sell dear.

Every town keeps its own **reputation** for you, and there is a world-wide one too:
- **Helping** a town (jobs, hunting pirates) brings better prices and friendlier guards. Towns that like you send zeppelins to help in the final battle.
- **Crimes** (attacking townsfolk or town ships, theft in front of witnesses, vandalism, smuggling forge powder) earn you **wanted stars** in that town:
  - guards attack you in the streets;
  - town guard ships chase you;
  - at 3 stars the mast will not let you moor;
  - wanted posters with your name go up.
- If you are wanted in many places, black bounty-hunter zeppelins come after you.
- Wanted levels cool down over time, or pay your fine at the town hall.

## Pirates

Open-deck pirate airships hold fixed spots and attack when you come close. Fly in near enough and they **board you**, so fight them off with sabre and pistol. You can also board them with the grapple. Once the whole crew is down, the captain's chest is yours. In Raven's Nest the pirates leave you alone if your name is feared enough.

## The story

1. **Among the Wrecks:** patch up the zeppelin and moor at Rustbell.
2. **Rustbell:** dive into the fog for Hessa's logbook and prove yourself against the pirates.
3. **Voice of the Forge:** break the guard of Ironbastion and steal the forge plans.
4. **The Abyss:** find Hessa under the fog, and survive the Leviathan.
5. **The Drowned Crown:** on the far side of the world, bring down the aether pylons and the flagship, then decide the fate of the forge. There are two endings.

After the story the world stays open.

## Multiplayer

- **Split screen:** player 2 uses a gamepad, or the arrow keys and numpad.
- **Online (up to 4 players):**
  - The host clicks *Host online game* and shares the 5-letter code; the others click *Join with code*.
  - The connection uses WebRTC (PeerJS) and needs an internet connection. Player names pass through a simple profanity filter.
  - Everyone shares one zeppelin and works the stations together: pilot, stoker, gunners, patcher and lookout.

## Version 2.2

- Detailed gondola interior (cockpit, chart room, quarters, engine room) with a live compass and a moving telegraph lever.
- Notice boards on every town square; 11 job types (delivery, urgent letter, escort, smuggling, pirate hunt, named bounties, rescue, beacon repair, salvage, photos, treasure maps), up to 6 at once, with a tracked-job marker on the compass and the globe.
- Treasure maps from taverns and defeated pirates; fog of war on the globe and buyable area maps.
- A three-part side story for 11 towns; a longer main story with new places and characters, and pirate allies for the last battle.

## Version 2.1

- Smooth, moving cloth envelopes on the zeppelins and the pirate balloons, with holes, sagging and wrinkles.
- Detailed voxel characters; shadows (Settings → Shadows: High / Low / Off).
- The planet is twice as large (129 wild islands, more clouds, 7 storms, more pirate nests).
- Towns get a fine detail layer when you are close: window frames, flower boxes, awnings, lanterns, shop signs, barrels, crates, benches, carts, pumps, street lamps, pipes, clothes lines, turning wind turbines, chimney smoke and steam vents.
- Faster simulation; fixes for falling through tall structures.

## Music

Put your own tracks next to `index.html` as `music/explore.mp3`, `music/battle.mp3` and `music/fog.mp3`.

---

## Magyarul röviden

**AETHERWRECK – Az Elsüllyedt Égbolt.** Zeppelines steampunk játék egy kis bolygón, első személyben, voxel pixel artban.

- **A zeppelin:** belülről vezeted, és minden helyisége bejárható.
- **Városok:** 12 város van emberekkel, kereskedelemmel, feladatokkal, hírnévvel és körözéssel.
- **Kalózok:** átszállnak a hajódra, te pedig csáklyával az övékre.
- **Történet:** 5 fejezet, két befejezéssel.
- **Multi:** osztott képernyő és online co-op legfeljebb 4 főnek.

**Irányítás:**
- **Gyalog:** WASD, egér, E (használat), Q (állomás elhagyása), 1–6 (eszközök), Tab (glóbusz).
- **Kormánynál:** W/S a telegráf, A/D a kormány, Space/C a magasság, B a ballaszt, H a kürt, E a kikötés.
- **Gépház:** a kazánba szenet kell lapátolni (E), és figyelni kell a nyomást.
- **Javítás:** a lyukakat kalapáccsal foltozod: a gondolára deszka kell, a ballonra vászon.
