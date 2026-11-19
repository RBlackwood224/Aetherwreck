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

**3.3**
- A real steampunk cockpit: the flat painted dashboard is replaced by brass instruments under glass. Altitude, airspeed, boiler-pressure and firebox gauges with sprung needles; an inclinometer whose ball rolls with the ship; six glass gas-cell tubes whose liquid falls and changes colour as the cells leak; an engraved brass plate with altitude, speed, heading, sky layer, wind and position; green-shaded console lamps that light the cockpit at night.
- Beside the wheel: a binnacle compass with a gimballed card under a glass dome (it stays level in a storm), Kelvin's iron balls and a little lamp; and a Chadburn engine-order telegraph whose handle and pointer swing to the order and ring its bell. The elevator lever moves on a toothed brass quadrant.
- On the cockpit walls: an aneroid barometer that falls before storms and fog, a clock running on the world's time, a gauge board, the speaking tube with its flared mouth and lid, and the ship's bell, which sways in rough weather. In the engine room: a boiler pressure gauge and water sight-glass on a stand, and the firebox now throws a flickering orange glow.
- New guns on every ship: cannons are cast-iron barrels with brass bands, a cascabel knob, trunnions in an iron yoke on a turntable and an elevation handwheel – and they recoil when they fire. Machine guns are six-barrel gatlings with an ammunition drum and spade grips, and the barrels spin up as they fire.

**3.2**
- Weather: the sky now changes on its own – clear, overcast, rain, fog banks and storms. Rain greys the sky, drums on the hull and helps put out fires aboard. In a fog bank you see only a few dozen metres – but enemies (and the spotter kites) see you much later too. Storms bring heavy rain, lightning, gusts that push the ship sideways and rock it. The barometer warns you before a storm or fog arrives (shown on the HUD with the current weather). Online, everyone shares the same weather.
- The enemy craft are now finely built instead of coarse blocks: smooth planked hulls with deck rails, moving cloth balloons with brass rings (shot holes show in them), real propellers with pitched blades. The glider has a proper tapered wing with an airfoil, ribs, struts, a canopy and a pilot; the kite is a billowing checkered sail on spars with a ribbon tail and a wicker basket with a lookout; the gunboat flies on two big wooden lift rotors; the harpoon tug carries a winch drum and a barbed harpoon gun; the fireship's deck is stacked with powder barrels under a black flag; the minelayer has a flat balloon, a crane and spiked mines on rails; the Crown cruiser has a bridge tower, twin funnels, a pennant mast and an iron ram. Wings and sails tear where they are hit.

**3.1**
- Seven new enemy craft, each with its own silhouette and tactics (they start showing up after chapter 7, depending on altitude, story progress and how wanted you are):
  - **Glider swarm** – canvas-winged one-man gliders in packs of 3–4; they circle, then dive and drop bombs on your deck.
  - **Spotter kite** – a big checkered kite with a basket lookout. If it watches you for a few seconds it fires a flare and calls in another ship. Shoot it down fast.
  - **Gunboat** – no balloon: two huge lift rotors on outriggers, a smokestack and two machine guns.
  - **Harpoon tug** – twin striped balloons and a bow harpoon. It hooks your ship and drags it; cut the line with the sabre or the hammer.
  - **Fireship** – a rusty, burning wreck with a torn balloon, packed with powder kegs. It rams you and blows up – keep it at range.
  - **Minelayer** – a wide double-hulled iron barge under a flat balloon; it leaves drifting aerial mines behind it.
  - **Crown cruiser** – the largest: Crown colours, armoured bow (frontal shots barely scratch it), ram, tower, four incendiary cannons.
- Online: the new craft, the harpoon line and the mines are synced to every player. Fixed a client-side explosion-sound error.

**3.0**
- Finer airships: the gondolas and pirate hulls wear a smooth, curved, planked skin instead of coarse blocks (windows, doors and every shot hole still show through it); engine nacelles are smooth riveted cylinders with brass bands; the tail fins are thin ribbed plates. Wood, iron, brass, cloth and stone surfaces are painted with planks, rivets and seams everywhere.
- Ship livery at the shipyard: envelope paint (8 schemes), hull wood, trim metal, flag with 7 emblems and 7 colours on a pole at the stern, figurehead (brass eagle, gear, lantern) and the ship's name on boards along the gondola. Changes show live on your ship.
- Captain's log [L]: written automatically – chapters, objectives, first visits, jobs, ships brought down, crew, paint jobs, rare catches – by day.
- Photo mode [F]: free camera, zoom, six filters, click to save a picture. Solo play freezes the world.
- Hire crew at the tavern: a stoker (shovels coal), a gunner (mans the cannons when attacked) and a mechanic (patches holes). They stand at their posts aboard.
- Fog fishing: from the stern balcony, low over the fog (below 75 m) and nearly still, cast the net [E], wait for the tug and pull in time [E]. Fog jellies, wisp moths, aether eels, brass-shelled crabs and the rare fog pearl – the lower you fish, the better. Sell them with the cargo.
- Online: the anchor state is shared, so going ashore and fishing work for every player.

**2.9**
- Character creator: name plus skin, eyes, hairstyle and colour, brows, beard, scar, headgear, outerwear, coat, shirt, waistcoat, trousers, boots, goggles / monocle / mechanical eye / eyepatch / gas mask, scarf, mechanical arm and gloves, with a live turning preview (double-click for a close-up). Online, other players see your look and your name over your head.
- Much finer people: 2.5 cm voxels, faces with eyes, brows, nose and mouth, fingers, buttons, belts, lapels, long coat tails that swing as you walk.
- Townsfolk dress for their trade (shipwrights in leather aprons and goggles, innkeepers in waistcoats, officials in long coats and top hats), stand around with crossed arms or hands behind their backs, and turn their heads to look at you.

**2.8**
- In-game guide for the first chapter: a panel shows the next thing to do with its keys (moving, hammer, patching, ladders, coal and firebox, helm, telegraph, globe, mooring) and moves on by itself when you have done it, in any order. Switch it off or on in Settings.

**2.7**
- Ladders work with a key: stand at the foot and press E to climb up, at the top press E to climb down. The hatches are closed, so you cannot fall through.
- The quarters ladder stands at the back wall, right of the doorway (not on the water tank). Its top on the keel walkway is marked with two red lamps.
- The lookout ladder runs inside an iron shaft through the envelope, starting above head height, so the walkway stays clear.
- The rear balcony has a real door into the engine room (boarding used to leave you outside a closed wall).
- Ceiling beams no longer cut through the boiler; the boiler is shaded as a drum.
- Checked: every station (helm, chart table, coal, firebox, valve, water tank, guns, ball turret, ladders) is reachable on foot from the balcony.

**2.6**
- Repairs made easy: with the hammer in hand every hole on your ship glows through the hull with its distance (orange = gondola, planks; pale = envelope, canvas).
- The hammer patches the nearest hole within reach even if you are not aiming exactly at it, including the one you stand in.
- The starting wreck's holes are now where you can reach them: the envelope's underside beside the keel walkway and the quarters walls.

**2.5**
- The ladder now stands beside the quarters doorway (it used to block the way to the engine room). Walk into the hatch from the keel walkway to climb down; looking down while pressing W also goes down.
- Drop anchor anywhere: at the helm, set the telegraph to 0 and press E once the ship has slowed. If there is rock below, you can go ashore from the balcony.
- Smooth steering: the rudder follows your input gradually and the new eight-spoke wheel turns up to one and a half turns.
- The coal bin can be reached from the aisle left of the boiler. Any item key, the mouse wheel, Q or a click puts the shovel down.
- Longer hammer reach (10 m on the envelope), and a hint when no hole is in front of you.
- New sounds: layered gunshots, cannon and explosions with a reverb tail, sabre whoosh, metal clanks.

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

**Irányítás:** (L – kapitányi napló, F – fotómód)

**Irányítás részletesen:**
- **Gyalog:** WASD, egér, E (használat), Q (állomás elhagyása), 1–6 (eszközök), Tab (glóbusz).
- **Kormánynál:** W/S telegráf, A/D kormány, Space/C magasság, B ballaszt, H kürt, E kikötés.
