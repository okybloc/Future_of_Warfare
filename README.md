# Future of Warfare: System of Autonomous Systems

A program-then-watch take on Space Invaders. You never steer a ship. From a home base you write the doctrine for four classes of unmanned undersea vehicle, choose what they carry, and launch them past your comms boundary. They fight on their own. You read the after-action report, adjust, and run the mission again until your system wins.

Play it: open `index.html` in a browser. It is one self-contained file with no dependencies.

## How it plays

1. **Program.** For strikers, interceptors, scouts and decoys, set doctrine cards (station depth, formation, target priority, fire discipline, what to do under fire), two standing orders (IF something happens THEN override a card), a loadout (weapon or sensor plus a system), and runes from a three-tier tree. A map table shows where the doctrine puts every vehicle. Three doctrine pages can be kept and swapped.
2. **Launch.** Vehicles execute alone. Beyond the comms boundary they cannot hear you. From base you can only deploy reserves (`1 2 3 4`), recall a type that is still in link (`Q W E R`), and use a limited burst recall that reaches everything (`B`). Click the water or the enemy first to mark where the next reserves go. `SPACE` pauses, `F` changes speed, clicking a vehicle shows its telemetry and what it is thinking.
3. **Review.** The after-action report shows what each type did, plain-language observations, and a battle map of every kill, loss and leak.
4. **Adjust.** Re-run the same mission until you beat it. Eight missions add tenders, hunters, minelayers, jammers, flankers and a mothership.

## Credits and licence

Built on [spaceinvaders](https://github.com/dwmkerr/spaceinvaders) by Dave Kerr (MIT License, Copyright (c) 2019 Dave Kerr). The game class, state stack, invader march-and-drop logic, front-rank bombing and the core entities are adapted from that project. This project is released under the same MIT licence; see `LICENSE`.
