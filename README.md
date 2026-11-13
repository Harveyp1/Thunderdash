# ThunderDash v1.0.3

A free live battle dashboard for War Thunder. Put it on your second monitor and get a
cockpit-style view of every battle: tanks, planes, helicopters and ships.

Download (GitHub): https://github.com/Harveyp1/Thunderdash/releases/latest
- Windows: https://github.com/Harveyp1/Thunderdash/releases/download/v1.0.3/ThunderDash-Setup-1.0.3.exe
- Linux:   https://github.com/Harveyp1/Thunderdash/releases/download/v1.0.3/ThunderDash-1.0.3-linux-x86_64.AppImage


## Install

**Windows**
1. Download `ThunderDash-Setup-1.0.3.exe` and run it.
2. Pick an install folder (or keep the default) and finish the installer.
3. Start ThunderDash from the Start menu or the desktop shortcut.

Windows may show a SmartScreen warning the first time because the app is new.
Click "More info" and then "Run anyway".

**Linux**
1. Download `ThunderDash-1.0.3-linux-x86_64.AppImage`.
2. Make it executable: `chmod +x ThunderDash-1.0.3-linux-x86_64.AppImage`
3. Run it: `./ThunderDash-1.0.3-linux-x86_64.AppImage`


## Use

1. Start War Thunder.
2. Join a battle (any mode: ground, air, helicopter or naval).
3. ThunderDash switches from STANDBY to LIVE on its own and shows the right panels
   for your vehicle.

That's it. There is nothing to set up in the game.


## What's in it

**Naval (new in 1.0.3)**
- Helm: speed (knots and km/h), heading, course, compass strip
- ON FIRE alert, with who set you on fire
- Gunnery: sight range in metres, shell flight time and lead for moving ships
- Contacts: range and bearing to spotted enemy ships and the capture point
- Your battle: kills, fires set, crits, ships sunk, and everything sunk this battle
- Naval map icons, kill feed and scoreboard

**Ground**
- Fire solution: mark a target on the map, get range, sight setting, turn from hull,
  elevation and flight time for your shell
- Crew, engine, tracks, gun, gear, RPM, stabilizer and ready rack

**Air and helicopters**
- Attitude, TAS, Mach, AoA, G-load, throttle
- Missile range rings (head-on, fleeing, seeker lock, minimum range)
- Bomb drop point and fall time on the map
- Rotor and engine readouts for helicopters

**Everywhere**
- Live tactical map with grid, range rings, follow-me mode and target markers
- Kill feed, team and all chat, objectives, scoreboard

**Mods and game settings**
- Drop a mod zip or folder: ThunderDash detects the type (skin, sight, mission,
  sound mod, hangar) and installs it in the right place. Nothing in a mod is ever run.
- Search WT Live from the app, sort your library by nation, check mods for updates
- Edit game settings without touching config.blk by hand, with profiles and
  automatic backups. Settings are only saved while the game is closed.


## Good to know

- The dashboard reads the data War Thunder serves on your own PC at
  http://127.0.0.1:8111 (the game's browser map). It does not read game memory and
  does not inject anything into the game.
- In Realistic battles the game only shares enemies your team has spotted, so
  ThunderDash only shows those too.
- Gunnery, fire solution and bomb numbers are estimates calculated from the game's own
  data. Use them as a starting point.


## Troubleshooting

**It stays on STANDBY in a battle**
- Make sure the game is running on the same PC.
- Open http://127.0.0.1:8111 in your browser during a battle. If the map doesn't load
  there, the game isn't sharing data yet. Restart the game and try again.
- Check that your firewall or antivirus isn't blocking ThunderDash.

**Mods tab can't find my game**
- Click "Change" next to "War Thunder folder" and pick your game folder
  (for Steam, usually `...\steamapps\common\War Thunder`).

**Game config won't save**
- Close War Thunder first. ThunderDash only writes config.blk while the game is closed.


## Uninstall

Windows: Settings > Apps > ThunderDash > Uninstall.
Linux: delete the AppImage file.


## Feedback

Found a bug or have an idea? Leave a comment on the ThunderDash post on WT Live.
Please say which vehicle, mode and map you were playing.

ThunderDash is a fan-made tool and is not affiliated with or endorsed by Gaijin
Entertainment. War Thunder is a trademark of Gaijin Entertainment.
