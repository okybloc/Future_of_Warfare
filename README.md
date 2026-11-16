# Future of Warfare: Strait Crossing

You run an autonomous-systems company on Taiwan's west coast. An invasion fleet crosses the strait in five phases: undersea and air drones first to clear the way, then landing ships led and flanked by unmanned escorts. Keep fewer than 10 landing ships from getting ashore.

Play it: open `index.html` in a desktop browser (it needs WebGL). It is one self-contained file.

## How it plays

- **Six pieces, shape says what it is.** Sea, air and land, each in two sizes. Big ones (Sea Carrier, Air Carrier, Launch Truck) go far and carry four small ones. Small ones (Sea Drone, Air Drone, Beach Crawler) are cheap and short-ranged.
- **Colour says what it is for.** Strike (red), Defend (blue), Scout (yellow), Decoy (purple). Each role has two fits, plus a stance and, for strikers, a target priority. Up close the model shows the parts you chose.
- **Launch on the map.** Click a hangar card (or 1-6), then click the sea. Credits refill each phase and for every ship sunk.
- **Command link.** You can re-send any unit that is in link with your base, a carrier or a relay scout. Out of range, jammed by an EW ship, or cut off by weather, it acts on its own fit-out. Carried drones take their orders from their carrier.
- **Weather.** Clear, haze, fog, rain and storm change how far you can see, sense and command. On a clear day at full zoom you can see the far coast.
- **View.** Scroll to zoom from your base out to the whole strait, right-drag or WASD to pan, B/V for base and strait views, SPACE to pause (orders still work), F for speed.
- **After-action replay.** The report shows landings, beaches and cost exchange, what each piece type did, and a scrubbable replay of the whole crossing.

## Credits and licence

This project began as a modification of [spaceinvaders](https://github.com/dwmkerr/spaceinvaders) by Dave Kerr (MIT License, Copyright (c) 2019 Dave Kerr); the game class and state stack descend from that code. 3D rendering uses [three.js](https://github.com/mrdoob/three.js) r128 (MIT), inlined in the page. Released under the MIT licence; see `LICENSE`.

This is a fictional game, not a simulation of real systems or plans.
