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
- 12 towns, 129 wild islands, 40 resource islands, 56 abandoned islets, about 40 mountains, about 170 ruins and 39 wrecks in the fog, and 7 aether storms.
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
- Every crime adds heat to that town (up to 5 stars). 1 star: guards attack. 2 stars: shops refuse you and guard ships open fire. 3 stars: the mooring mast is closed to you.
- Heat cools by about one star every 4 minutes while you stay more than 600 m away from the town.
- Pay your fine at the harbour (250 gold per star + 50), or do jobs for the town to bring the heat down.

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

**3.7 – mountains, mining, busier skies and a new night sky**
- **A new sky:** painted day skies with high cirrus, rose and copper dusks, and deep indigo nights with a galaxy band, purple and teal nebulae and twinkling stars.
- **Constellations:** eight star pictures (the Boiler, the Anchor, the Airship, the Gear, the Raven, the Leviathan, the Crown and the Lantern), traced in faint brass lines like an astrolabe.
- **Other worlds:** a ringed giant, a small blue planet, and the Broken Moon: a pale moon with a glowing torn side and a trail of shards. You can see them from anywhere on the planet, and they show faintly by day too.
- **Mountains:** about 40 crags rise from the drowned floor up through the fog, with ash on the slopes and frost on the highest peaks.
- **A livelier fog sea:** glowing toxic veins wind slowly through it.
- **Resource islands:** strike coal, timber, copper ore or crystal with the hammer (3). Coal goes straight into the bunker, timber becomes planks, ore and crystal go into the hold to sell. What you take grows back after a few minutes. Two of these islands sit close to Rustbell.
- **Black markets:** four hidden outposts on remote resource islands. The fence buys anything without questions (contraband pays best), sells coal, shells and filters, and offers forged papers that take one star off every wanted level.
- **Abandoned islets:** small rocks with a broken hut, and a treasure chest is always waiting there.
- **Busier skies:** more merchants and guards, two new ship types (tramp freighters and fast couriers), and passing ships always come and go near you.

**3.6 – speed, balance and fixes**
- Faster: the ships' small fixed parts are merged, so there is about half as much to draw each frame.
- No more camera jumps while steering.
- The click that closes a dialog or accepts a job no longer fires the pistol.
- The engine needs steam: with an empty firebox the pressure drops in seconds and the ship stops.
- The coal in the bunker sinks as you use it.
- Rebalanced: more money and coal at the start, cheaper coal and repair goods, better job rewards, fewer and smaller raids early on, and free charity coal at the harbour if you are broke with an empty bunker.

**3.5 – fixes and towns**
- No more shudder while flying: grazing rock used to reverse the speed every frame; now the ship stops or slides.
- A ship wedged against a mast or a building used to stay stuck for good; it now works itself free and can always climb out. Taking off from a town mast works.
- Taking a station: the key that took it is ignored until you let go of it.
- Anchoring anywhere over a town counts as being in port there (the story, trade and gas refills follow). The "back to the ship" prompt only shows right by the ship.
- Left alone with no anchor down, the ship drops anchor by itself instead of drifting away.
- Collisions damage the ship (bow, stern, or the bottom on a hard landing), scaled by the impact: parking bumps and slow scrapes do nothing. Lightning no longer strikes a ship in port, and only rarely in the open.
- The ball turret is now a clear glass dome: you sit low in it, under the hull line, and the gun's own housing no longer fills the view.
- A catwalk with rails along the top of the envelope, out of both ends of the lookout: every hole on the upper half can be reached, and you cannot slide off.
- Envelope holes show from far away: a scorched, frayed ring around each one.
- At the helm the keys are always on screen: W/S telegraph, A/D rudder, Space climb, C descend.
- Townsfolk walk the streets on a path network instead of into walls; trading ships fly over the rooftops and get themselves free if they touch anything.
- Everyone you can talk to in town has a sign over their head with their trade and name.
- Houses, taverns, halls, markets and shipyards are furnished inside: tables and chairs, beds, shelves, stoves, rugs, bar counters, desks, workbenches and hanging lamps.
- The map: "you are here" arrow with heading, the goal with a dashed line and its distance, town names with distances, a north arrow, a legend, and a box saying which sky layer you are in and which town is nearest, how far and which way. Opens zoomed in on you.

**3.4 – fixes (tested by playing with keyboard and mouse only)**
- The ship would not move: with a half-empty balloon it sank onto the rock and every frame's collision also cancelled its forward motion. It now slides along and lifts clear. Sealed gas cells now refill in about a minute (they used to take many minutes).
- Taking the wheel with E also cast off at once, so the next E (meant to raise the anchor) dropped it again and the ship stayed put. The key that takes a station no longer works it.
- Shovelling a full firebox no longer pushes the boiler into the red (it used to blow up a few seconds after three shovels). One shovel lasts about half a minute at full ahead.
- The big pale and brown slabs and "random cubes" inside the ship: escaping gas was drawn as large growing cubes that drifted down into the gondola; it is now a faint shimmer of small specks blown outwards. The gondola's outer skin no longer folds into the cabin at the gun ports and windows. Cloud puffs are never drawn inside the ship you are on.
- Inside the envelope: the keel walkway's railing (half-metre blocks at eye level that hid the holes) is now a slim brass rail with a rope, the lamps are small lanterns, the lookout shaft is a smooth iron tube, and the canvas no longer pokes up through the walkway. The holes in the envelope show as openings beside the walkway.
- The helm can be taken from a little further away.

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
- **Világ:** 5,2 km sugarú bolygó, 12 város, 129 vad sziget, 40 kitermelhető sziget, 56 elhagyatott sziget, kb. 40 hegy, 4 magassági réteg, viharok és köd a térképen.
- **Zeppelin:**
  - **Kormányállás:** műszerfal, valódi iránytű és telegráf.
  - **Térképszoba:** glóbusz és oldalágyúk.
  - **Szállás:** priccsek, víztartály, lejárat a hasi gömbtoronyba.
  - **Gépház:** kazán, szén, biztonsági szelep.
  - **Burok:** hat gázcella, a lyukakon látszik a szivárgó gáz.
- **Küldetések:** 11 típus a hirdetőtáblákon, egyszerre 6 vállalható, kincses térképek.
- **Történet:** 5 fejezet két befejezéssel, és 11 városi mellékszál.
- **Hírnév és körözés:** városonként és világszinten, csillagokkal, plakátokkal és fejvadászokkal. Minden bűn „hőt” ad az adott városnál (legfeljebb 5 csillag). 1 csillagnál az őrök megtámadnak, 2-nél a boltok nem szolgálnak ki és az őrhajók lőnek, 3-nál a kikötő bezár. A hő lassan elmúlik, ha 600 méternél messzebb vagy (kb. 4 percenként egy csillag). Kifizetheted a bírságot (csillagonként 250 + 50 arany), segíthetsz a városnak, vagy vehetsz hamis papírokat a feketepiacon.
- **Égbolt:** festői nappali ég fátyolfelhőkkel, rózsaszín és rézszínű alkonyat, mélykék éjszaka tejúttal, ködökkel és csillagképekkel. Csillagképek: Kazán, Horgony, Léghajó, Fogaskerék, Holló, Leviatán, Korona és Lámpás. Az égen van egy gyűrűs óriásbolygó, egy kis kék bolygó és a Törött Hold, izzó, letört oldallal és szilánkokkal.
- **Hegyek:** kb. 40 sziklacsúcs nő ki a ködtengerből, a ködben izzó mérgező erek kanyarognak.
- **Kitermelés:** a kitermelhető szigeteken kalapáccsal (3) szenet, fát, rézércet és kristályt lehet kitermelni. A szén a bunkerbe, a fa deszkának, az érc és a kristály a raktárba kerül. Pár perc múlva visszanő.
- **Feketepiac:** négy rejtett állomás távoli szigeteken. Az orgazda mindent megvesz, és hamis papírokat is árul.
- **Elhagyatott szigetek:** apró sziklák romos kunyhóval, mindig van rajtuk kincsesláda.
- **Forgalom:** több kereskedő és őr, csavargó teherhajók és gyors futárhajók, és a közeledben mindig jár néhány hajó.
- **Többjátékos:** osztott képernyő, illetve online co-op legfeljebb 4 főnek.
- **Zene:** 10 saját zeneszám a `music` mappában, a helyzethez igazodva, áttűnéssel.

**Irányítás:** (L – kapitányi napló, F – fotómód)

**Irányítás részletesen:**
- **Gyalog:** WASD, egér, E (használat), Q (állomás elhagyása), 1–6 (eszközök), Tab (glóbusz).
- **Kormánynál:** W/S telegráf, A/D kormány, Space/C magasság, B ballaszt, H kürt, E kikötés.
