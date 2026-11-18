# AETHERWRECK: The Drowned Sky

**▶ Play in your browser: https://rblackwood224.github.io/Aetherwreck/**

A first-person, post-apocalyptic steampunk zeppelin game in voxel pixel art. You fly a patched-up airship from inside its gondola over a planet drowned in poisonous fog, trade between floating towns, take on jobs, fight and board pirates, and follow a story to the Drowned Crown. It runs in any modern browser, with nothing to install, and supports split-screen and online co-op for up to 4 players.

> Sixty years ago the Empire's forges overheated, and the poisonous Aether Fog drowned the world in a single night. The survivors live in towns on floating rocks and fly zeppelins stitched together from wreckage. You wake up on one of them.

- Free to play, in Hungarian, English and French.
- Repository: https://github.com/RBlackwood224/Aetherwreck

---

## How to play

- **Online:** open the link above.
- **Offline:** download the repository (Code → Download ZIP), unzip it and open `index.html`.
- Click into the game to capture the mouse. `Esc` releases it and pauses the game.
- Choose the language in the main menu.

## Features

### A whole planet
- The fog surface is a sphere with a radius of 5.2 km, about 32.7 km around. A full lap at full steam takes about 21 minutes.
- 12 towns, 129 wild islands, about 170 ruins and 39 wrecks in the fog, and 7 aether storms.
- **Four sky layers**, each with its own wind:

  | Layer | Height | What you find there |
  |---|---|---|
  | The Deep | −75–0 m | ruins and wrecks; you need a mask |
  | Fog Edge | 0–70 m | fog banks, places to hide |
  | Middle Sky | 70–260 m | most towns and trade routes |
  | High Sky | 260–520 m | sheep clouds, icy winds |

- **Clouds:** cumulus, high "sheep" clouds, fog banks and storm towers with lightning. Inside a cloud you see almost nothing.
- **Fog of war:** a rotating globe map shows only the places you have explored. Town halls sell maps of their surroundings.

### Your zeppelin
- A smooth cloth envelope that ripples in flight.
- **Six gas cells.** Every hit tears a real hole that leaks visible gas. As a cell empties, the envelope sags and the ship tilts.
- You fly it from inside and can walk through every room:

| Room | What it does |
|---|---|
| **Cockpit** | The wheel and the dashboard: altitude, speed, boiler pressure, firebox, compass, the six gas cells, the engine telegraph, sky layer and wind. Also a working compass binnacle that always points north and a telegraph whose lever follows the engine order. |
| **Chart room** | The brass globe opens the map. The two side cannons are here. |
| **Quarters** | Bunks and the water tank for refilling the extinguisher. A hatch leads down to the **ball turret**. |
| **Engine room** | Shovel coal from the bunker into the firebox and keep an eye on the pressure. In the red, open the safety valve, or the boiler blows. |
| **Keel catwalk and roof lookout** | Ladders lead up through the envelope to a machine-gun post on top. |

- **Fire and repair:** put fires out with the extinguisher. Patch holes with the hammer: planks for the gondola, canvas for the envelope. Docks sell gas refills and full repairs.

### Towns
- Every rock has its own steampunk town with people walking the streets. Each town has a tavern, a town hall, a market, a mooring mast and turning wind turbines, and some have a shipyard.
- Up close, towns get fine detail: lanterns, shop signs, barrels, carts, chimney smoke and steam vents.

| Place | What you can do there |
|---|---|
| Market | Trade coal, food, cloth, aether crystal, parts and spirits; buy supplies; sell loot. |
| Tavern | Rumours, drinks, treasure maps. |
| Town hall and **notice board** | Jobs, the town's own story, fines, selling photos, area maps. |
| Shipyard | Armour, envelope, engine, faster reloading, an automatic stoker and a bigger hold. |
| Mooring mast | Gas, repairs, coal, ballast. |

Prices follow what each town produces and needs.

### Jobs
There are **11 job types**:
- delivery
- urgent letter (against the clock)
- escort a merchant (pirates lie in wait)
- smuggling
- pirate hunt
- named bounties
- rescue castaways
- repair a beacon
- salvage from the fog
- photographs
- treasure maps

You can take up to 6 jobs at once. The tracked job shows as a ◇ marker on the compass and on the globe.

### Stories
- **Main story:** five chapters with two endings. It visits Rustbell, Sootborough, Clocktown, the Iron Bastion, Cloudspire, the Abyss and its Leviathan, Raven's Nest, and the Drowned Crown on the far side of the world.
- **Town stories:** 11 towns have their own three-part story with a reward at the end. Towns that like you send ships to help in the final battle.

### Reputation and wanted levels
- Every town remembers you, and so does the whole world.
- Help a town and you get better prices.
- Commit crimes and you collect wanted stars: guards attack, guard ships chase you, at 3 stars the mast will not let you moor, and black bounty-hunter zeppelins come after you.
- Pay your fine at the town hall, or wait for things to cool down.

### Combat
- **On foot:** sabre, pistol, hammer, grapple and a camera.
- **On the ship:** cannons and machine guns that knock voxels out of hulls, rocks and buildings.
- **Boarding:** pirates board you at close range, and you can board them with the grapple.

### Multiplayer
- **Split screen** for 2 players. Player 2 uses a gamepad, or the arrow keys and numpad.
- **Online co-op** for up to 4 players:
  - The host shares a 5-letter code, and the others join with it.
  - Everyone works the same ship: pilot, stoker, gunners and lookout.
  - The connection uses WebRTC (PeerJS) and needs internet access.

## Controls

| Key | On foot | At the helm | At a gun |
|---|---|---|---|
| WASD | move (W/S also climb ladders) | W/S: telegraph (R, 0–4), A/D: rudder | – |
| Mouse | look | look around | aim |
| Space / C | jump (glide while falling) | climb / descend | – |
| E | use, talk, read the notice board, take or put coal | moor, or cast off | – |
| Q | leave a station | leave | leave |
| B / H | – | drop ballast / horn | – |
| Left click | use the item in your hand | – | fire |
| 1–6 | sabre · pistol · hammer · extinguisher · grapple · spyglass/camera | | |
| Tab / M | globe map, jobs and reputation (drag to rotate, wheel to zoom) | | |

## Settings
- Pixel size, mouse sensitivity, volume and name.
- **Shadows:** High, Low or Off. Use Low on slower computers.

## Music

The game changes music with the situation and crossfades between tracks. All 10 original tracks are included in the `music/` folder (made with Suno). To swap one, replace the MP3 with the same name. If a file is missing, the game falls back to a more general track.

| File | When it plays | Falls back to |
|---|---|---|
| `menu.mp3` | main menu | `explore` |
| `explore.mp3` | flying, exploring | – |
| `town.mp3` | in and near towns | `explore` |
| `highsky.mp3` | above 260 m | `explore` |
| `storm.mp3` | inside an aether storm | `explore` |
| `fog.mp3` | in the Deep, under the fog | – |
| `battle.mp3` | fighting | – |
| `boss.mp3` | the Leviathan, bounty targets, Crown hunters | `battle` |
| `crown.mp3` | the final battle at the Drowned Crown | `boss` |
| `ending.mp3` | the ending | `menu` |

## Versions

**2.4**
- 10 original music tracks included.
- New title-screen art.
- A real ladder from the quarters doorway up through the roof hatch into the envelope; the rungs hold you while you climb.
- **Go ashore:** on a moored or anchored ship, press E on the rear balcony to step onto the mast platform or the anchor rock. You can board the anchored wreck again from the rock.
- Stoking: the shovel stays in your hand. E at the coal bin loads it, E at the firebox throws the coal in. A number key puts the shovel down. New scrape and fire sounds.
- Fix: coal, the firebox glow, leather gloves, white gauge faces and several cloth and skin colours were invisible because they were missing from the palette.

**2.3**
- Panoramic cockpit: glass nose, skylight and a glass floor in front of the helm.
- Fine furniture instead of coarse blocks: console, chart table, bunks, water tank, boiler, coal bin. Also wall ribs, panelling, and window and door frames.
- Detailed items in hand (sabre, revolver, hammer, extinguisher, grapple, spyglass) with sway, slash, recoil and muzzle flash. They never clip into walls.
- Fixes:
  - looking up and down works again;
  - no more bouncing onto furniture;
  - ships moor broadside to the mast: step across through the chart-room gun port;
  - the starting wreck hangs on its anchor until you cast off at the helm.

**2.2**
- Detailed gondola interior.
- Notice boards and 11 job types, with a tracked-job marker.
- Treasure maps and fog of war on the globe.
- Town stories and a longer main story with pirate allies.
- Music that follows the situation, with 10 tracks and crossfades.

**2.1**
- Smooth cloth envelopes and detailed characters.
- Shadows.
- A planet twice as large.
- Detailed towns up close.
- Faster simulation.

**2.0**
- The zeppelin redesign: a gondola under the envelope, a spherical planet, towns, reputation, the story and online co-op.

---

## Magyarul

**▶ Játék a böngészőben: https://rblackwood224.github.io/Aetherwreck/**

**AETHERWRECK – Az Elsüllyedt Égbolt.** Belső nézetes, posztapokaliptikus steampunk zeppelines játék voxeles pixel-art stílusban. A világot elnyelte a mérgező Éterköd. A foltozott zeppelinedet a gondolából vezeted egy körberepülhető bolygó fölött:
- kereskedsz a lebegő városok között;
- küldetéseket vállalsz;
- kalózokkal harcolsz;
- követed a történetet az Elsüllyedt Koronáig.

- **Indítás:** nyisd meg a fenti linket, vagy töltsd le a repót, és nyisd meg az `index.html`-t.
- **Világ:** 5,2 km sugarú bolygó, 12 város, 129 vad sziget, 4 magassági réteg, viharok és köd a térképen.
- **Zeppelin:**
  - **Kormányállás:** műszerfal, valódi iránytű és telegráf.
  - **Térképszoba:** glóbusz és oldalágyúk.
  - **Szállás:** priccsek, víztartály, lejárat a hasi gömbtoronyba.
  - **Gépház:** kazán, szén, biztonsági szelep.
  - **Burok:** hat gázcella, a lyukakon látszik a szivárgó gáz.
- **Küldetések:** 11 típus a hirdetőtáblákon, egyszerre 6 vállalható, kincses térképek.
- **Történet:** 5 fejezet két befejezéssel, és 11 városi mellékszál.
- **Hírnév és körözés:** városonként és világszinten, csillagokkal, plakátokkal és fejvadászokkal.
- **Többjátékos:** osztott képernyő, illetve online co-op legfeljebb 4 főnek.
- **Zene:** 10 saját zeneszám a `music` mappában, a helyzethez igazodva, áttűnéssel.

**Irányítás:**
- **Gyalog:** WASD, egér, E (használat), Q (állomás elhagyása), 1–6 (eszközök), Tab (glóbusz).
- **Kormánynál:** W/S telegráf, A/D kormány, Space/C magasság, B ballaszt, H kürt, E kikötés.
