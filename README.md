VeoZax API - Your own Legacy PocketMine-MP API
==============================================
VeoZax API is a Legacy version of PocketMine-MP made to Act as "Cross-Play" between 0.14.x, 0.15.10, 1.1.x versions of Minecraft Pocket Edition Servers.
It's build to let Legacy 0.14.x & 0.15.10 & 1.1.x version Clients to connect and play on a Single server.

VZ API Development Started from: 22/03/2026

My Journey in Creating an API like this:
=====================================
It was a dream of mine to Create a Triple versioned Servers of McPE Alpha/Legacy.
Many players has been requesting to me for Create an API like this.
They wanted to play with friends on a single server with these version of Minecraft Pocket Edition: 0.14.x, 0.15.x, 1.1.x

Some players quitted from 0.14.x, 0.15.x and moved to 1.1.5 due to:
1. Their android devices is compatible with those versions of MCPE.
2. Lost interest in those MCPE versions and find comfort in 1.1.x version of MCPE.

Due to those reasons, The Craftsman/MasterCraft/MCPE (0.14.x - 0.15.10) community slowly started to Die.

At this point, I decided to Create an API with those 3 versions of Minecraft Pocket Edition and letting them play together on a single PocketMine-MP server.

Multiversion API 0.14.x - 0.15.10 - 1.1.x (VeoZax API Build 2.0)
================================================================
This API is mainly built top of the API called MySoft.

What is my Role in building this API?
=====================================
MySoft API supports versions from 0.15.x to 1.21.80
From that, only version bridge from 1.1.x to 1.1.7 was taken and rebuilt to create the VeoZax API.
0.14.x and 0.15.x are taken from it's original source code. Although MySoft had version 0.15.x support, it was completely incomplete and buggy.
It crashed constantly and made it difficult for other players from 0.15.x to play freely. So i had to update and build 0.15.x separately.
In addition to doing that, i also tried 0.14.x to add. That version was the only one missing from the API.
Due to many people's requests, I decided to build it there no matter what. thus, development of this Project began on March 22, 2026.
The first two or three days of building this API felt very difficult.
Every step i took led me to failure. However, I decided to move forward for the Craftsman/MCPE Legacy Community.
I spent the first month without sleep working on this API. Every mistake and success in this API is carefully crafted.
So after all the observations and experiments, the work on this API was almost completed on August 5, 2026

Below are some of the things I specicically mentioned about my works:

1. Added 0.14.x support (Login handle, Player handle, chat, Event handlers to make it stable enough to play with the 0.15.x and 1.1.x players)
2. Reworked on 0.15.x support to make it stable enough to play with the 0.14.x and 1.1.x players.
3. Fixed the issue where a player cant craft anything except wood to planks.
4. Fixed Few Light updates between 0.14.x and 0.15.x players.
5. Fixed Particle bugs which were causing inaccurate particles and effects showing to players when breaking something.
6. Fixed Crash caused by eating bug between 0.15.x and 1.1.x
7. Fixed Ghost Armour Bug on 0.15.x
8. Added Chest animations.
9. Added Command Guardian to prevent players with Hack clients from gaining Access to the server.
10. Added inbuilt World to World Teleport system.
11. Added autoload to Worlds.
12. Added Auto Restart Feature to Prevent quick overloads.
13. Barely fixed Block place bugs on 0.15 and 0.14
14. Adjusted KB 0.14.x and 0.15 for players.
15. Fixed Crouching/Sneaking Bug for both 0.14.x and 0.15.x
16. Fixed throwable items bug for both 0.14.x and 0.15.x
17. Xp pickup, Item drops will now feels smooth like butter.
18. Fixed /setworldspawn is not updating world's spawn point.
19. Fixed where the player is not getting Respawned on the new Spawn Point.
20. Added Armour Durability for 0.14.x
21. Fixed Water Draining time to smoother.
22. Fixed fishing logic.
23. Added Cool world Generators with biomes and mountains and structures.
24. Added VeoZax.yml to manage Administrators and Owners Access Permissions.
25. Updated NameTag with Version support to the players.
26. Added Transfer Server for 1.1.x players to Travel between Server to Server within the Server.
27. Fixed Skin Bug.

None of these fixes came easy. Every single one on that list was a night where something broke on one version the moment it started working on another.
0.14.x would desync the moment 0.15.x behaved, and then 1.1.x would throw a tantrum on top of that. Building for one version is hard enough,
building for three at once, and keeping all three happy at the same time, is a whole different beast. But I kept going, because I knew what this
meant to the Craftsman/MCPE Legacy Community. This wasn't just code to me, it was keeping something alive that a lot of people still love and miss.

Why I'm Releasing This
======================
This API was never meant to just sit on my machine. The whole point of building a Multi-Version bridge like this was to let the Legacy MCPE community
keep playing together, no matter which version they're stuck on or which one they grew attached to. Keeping it closed off would go against everything
this Project stood for from day one. So I'm publishing it here, for free, for anyone who wants to run their own Legacy 0.14.x - 0.15.10 - 1.1.x server
and keep this community going.

Some more Info You need to Know
====================================
I want to be honest about this: this whole thing was built by me, alone. No team, no co-developers, no one sitting next to me
debugging at 3am. Every fix on that list above, every version conflict I had to untangle between 0.14.x, 0.15.x and 1.1.x, was
me by myself, for months.

What I did build on top of is open source code, which is different from being helped. PocketMine-MP is the core this whole server
software is built on, made by the PocketMine Team. And the original 1.1.x - 1.1.7 version bridge that I rebuilt and rewrote to make
the VeoZax API came from an existing open API called MySoft. That's why they're named here, it's a license and origin thing, not a
"they helped me" thing. Reading someone else's open source code and then rebuilding, fixing, and extending it alone into a working
triple-version bridge is still solo work. I just don't want to pretend the original source didn't exist either.

Everything from "Added 0.14.x support" down to "Fixed Skin Bug" up there, that's mine.

Heads Up Before You Run This
=========================
Since this is built and maintained by one person, expect bugs. Expect edge cases I haven't caught yet, some incompatibility
between the versions here and there, and the occasional error that only shows up once real players are on the server. I've
tested this as much as I can alone, but I can't catch everything a whole community running it will run into.

If you hit something broken, please report it, that helps a lot. And if you know your way around PocketMine-MP and want to
help develop this further, fix bugs, add features, or just keep it alive long term, I'd genuinely welcome that. This was
built solo, but it doesn't have to stay that way. Reach out on Discord if you want to get involved.

# VeoZaxAPI v3 - Bug Fixes and Updates

**Multi-version PocketMine-MP API for Minecraft Pocket Edition 0.14.x, 0.15.x and 1.1.x**

> **Development status: paused.** This may be the last release for a while. The developer is taking a break and may return months from now. The project is open source (LGPL v2.1). Anyone is welcome to fork it, fix bugs and keep it alive.

This document is a complete record of what is in VeoZaxAPI at this release: what it does, how it is built, how to set it up, every command and config option, and every known problem. It was compiled by reading the source code. TPS and performance were not measured, so no performance numbers are given.

---

## 1. Summary

| | |
|---|---|
| Name | VeoZaxAPI |
| Release | v3.0.0 (internal version string in `VersionInfo.php`: `0.2.0`) |
| Base | PocketMine-MP 3.0.0 ALPHA (heavily modified legacy fork) |
| Version bridge | 1.1.x to 1.1.7 bridge rebuilt from the open-source **MySoft** API; 0.14.x and 0.15.x written/reworked by VeoZax |
| Clients | 0.14.x, 0.15.x (up to 0.15.10), 1.1.x (up to 1.1.7), all on one server |
| PHP | 8.2 or newer required (bundled binary is PHP 8.2.17) |
| License | GNU LGPL v2.1 |
| Developed | 22 March 2026 to 5 August 2026, solo |
| Size | 2,004 PHP files, about 178,900 lines (about 29,000 of them vendored libraries) |

---

## 2. What changed in this release (v3 vs. the previous GitHub upload)

Compared file by file with the previous GitHub upload: 2,781 of 2,794 files are identical (ignoring line endings and one header comment). 13 files changed.

### Bug fixes
- **PHP 8 crash fixed.** `Crypto.php` had an invalid default argument in `Rand::seed()` that makes the file fail to parse on PHP 8.
- **Actor metadata completed.** The base protocol 110 map in `ActorMetadataList.php` was missing the first metadata IDs (`DATA_FLAGS` through `DATA_CHARGE_AMOUNT`) and the first entity flag IDs (`DATA_FLAG_ONFIRE` onward). They are now defined so those values convert correctly for older clients.
- **Sprint / glide / swim.** The workaround that despawned and respawned the player for viewers on protocol below 90 was removed from `toggleSprint`, `toggleGlide` and `toggleSwim`.
- **Explosion knockback** now always uses vanilla values.

### Improvements
- **Configurable knockback.** Knockback strength and attack delay follow the `entity.knockBack` section of `veozaxapi.yml` again (`modX`, `modY`, `delay`, `verticalLimit`, ...). Default remains `vanilla: true`.
- **Smoother movement.** Entity movement and rotation updates are sent much more often (position threshold 0.04 to 0.0001 squared distance, rotation 2.25 to 1.0). This looks smoother but sends more packets.
- **Documented config files.** `VeoZax.yml` and `administrators.yml` now explain every option in comments.
- Version managers cleaned up and file headers updated.

### Changed behavior
- **Encryption is now optional.** Controlled by `network.enable-encryption` in `pocketmine.yml`, default `false`. It only applies to modern (non-legacy) clients. The previous upload always had it on.
- **Weather** now defaults to `true` in `veozaxapi.yml`.

### Items from the previous upload that are not in v3
- the `Player::broadcastMotion` override;
- the 0.55 horizontal knockback scaling in `AnyVersionManager` and `P84VersionManager` (it remains only for protocol 81 in `RakLibInterface`, which now covers protocol 81 only instead of 81 to 83);
- the fixed 10-tick attack cooldown.

The earlier code comments say the 0.55 scaling softened leg-swing on knocked-back players for older viewers. That exaggerated leg-swing may return.

---

## 3. Supported clients and protocols

| Client family | Protocol IDs accepted | Notes |
|---|---|---|
| 0.14.x | 41, 42, 43, 44, 45, 46, 60, 70 | Added by VeoZax |
| 0.15.x | 81, 82, 83, 84 | Reworked by VeoZax |
| 1.1.x | 100, 101, 102, 105, 106, 107, 110, 111, 112, 113 | Bridge rebuilt from MySoft. IDs 100 to 107 are accepted by the code but were not individually mapped to game versions during this review |

- Base protocol: 81. Highest accepted: 113. Network version string: `1.1.5`.
- Protocols 41 to 84 are the **legacy tier**. They skip login encryption and cannot use `/transfer`, `/rejoin` or `/transfer-lobby` (a message tells them to switch to 1.1.x).
- Protocols 90, 91 and 92 are defined as constants but are **not** accepted.

---

## 4. Setup and first run

1. Use PHP 8.2 or newer. The bundled `bin/php7` is a Linux x86_64 PHP 8.2.17 build (about 56 MB). On newer Linux distributions it may need old libraries (`libjpeg.so.9`, `libzip.so.5`, `libleveldb.so.1`) and the `pmmpthread` extension.
2. Start the server once. It creates `veozaxapi.yml` in the data folder (copied from `resources/veozaxapi_eng.yml`).
3. **Set `API-Connection: true` in `veozaxapi.yml`.** It defaults to `false`, and the server refuses to boot until you change it.
4. Change the secrets in `VeoZax.yml` (see section 10).
5. A full setup video is linked in the "Requirements & How to Run" section below.
6. Default ports: server `19132` (UDP). Query is enabled by default. RCON is off by default; if enabled, its password is random.

---

## 5. Features

### Multi-version
- Three client generations on one server.
- Per-protocol chunk handling: `LegacyChunkRequestTask`, `P84ChunkRequestTask`, plus a per-protocol chunk cache (`chunkCache[index][protocol]`), so each chunk is converted once per client version.
- `AnyVersionManager` (0.14.x / 0.15.x), `P84VersionManager`, `Legacy014BatchDecoder` for 0.14 batch packets.
- 235 packet classes, plus converters for blocks, inventories, actor metadata and biomes in `network/mcpe/multiversion/`.
- Name tags show the player's client version.

### Fixes and systems from the project README
1. 0.14.x support (login, player handling, chat, events)
2. 0.15.x reworked for stability
3. Crafting fix (previously only wood to planks worked)
4. Light update fixes between 0.14.x and 0.15.x
5. Particle fixes when breaking blocks
6. Crash fix when eating between 0.15.x and 1.1.x
7. Ghost armor bug fixed on 0.15.x
8. Chest animations
9. Command Guardian (blocks hacked clients from privileged commands)
10. Built-in world-to-world teleport
11. World autoload
12. Auto restart feature
13. Block placement bugs partly fixed on 0.14 and 0.15
14. Knockback adjusted for 0.14.x and 0.15
15. Crouch/sneak bug fixed (0.14.x and 0.15.x)
16. Throwable item bug fixed (0.14.x and 0.15.x)
17. Smoother XP pickup and item drops
18. `/setworldspawn` now updates the spawn point
19. Respawn at the new spawn point fixed
20. Armor durability for 0.14.x
21. Smoother water draining
22. Fishing logic fixed
23. World generators with biomes, mountains and structures
24. `VeoZax.yml` for administrator and owner permissions
25. Name tags with version support
26. Server-to-server transfer for 1.1.x players
27. Skin bug fixed

### Server management (verified)
- **Owners and Administrators** replace the old `ops.txt`. Main owner, sub-owners and administrators are stored in `VeoZax.yml` and `administrators.yml`, changed only with passwords.
- **Command Guardian (`/anti`).** Members and administrators are locked to per-rank allow lists of commands. Owners bypass it. It only blocks commands the player typed themselves. Commands run by plugins on a player's behalf (for example NPC plugins) are not blocked.
- **Auto restart** with countdown and kick message.
- **Kill thread.** Automatically shuts the server down if it freezes (default timeout 10 seconds).
- **Transfer system.** `/transfer`, `/rejoin` and `/transfer-lobby` with a countdown, named lobbies, optional Discord webhook logging.
- **Integrity check.** Startup and every 300 seconds, the server checks that the product name is `VeoZaxAPI` and that `VersionInfo.php` matches a stored SHA-256 hash. If you change the version, update the hash in `VeoZaxSignature.php` or the server will not start.
- **Hourly credit broadcast.** Once an hour the server tells all players "Multi-Version API by VeoZax". It is hard-coded and not configurable.
- **Anti-xray** (off by default).
- **Weather, lightning and fire spread** settings.
- **Nether and End worlds** can be auto-created.
- **Whitelist, bans, IP bans, kicks, timings, memory dump and garbage collection** commands.
- **Languages.** 35 locale files: afr, ara, bul, ces, chs, deu, ell, eng, est, fin, fra, gle, heb, hrv, hun, ind, ita, jpn, kor, lav, mlt, msa, nld, nor, pol, por, spa, swe, tgl, tha, tlh, tur, ukr, vie, zho. Only the English advanced config (`veozaxapi_eng.yml`) exists.
- **Resource packs** through `resource_packs.yml` (stack order, forced packs, `.key` files for encrypted packs).
- **Query and RCON** support.

---

## 6. Command reference

### VeoZaxAPI commands
| Command | Usage | What it does |
|---|---|---|
| `/administrators` | `<add\|remove> <player> <password>` | Add or remove an administrator |
| `/administrator` | `<lock\|unlock>` | Lock or unlock the Administrators Protocol |
| `/server-owner` | `<add\|remove> <player> <password>` or `<lock\|unlock>` | Manage sub-owners; lock/unlock is main-owner only |
| `/anti` | `<members\|administrators> <allow\|deny> <command>` and `seeallowed <members\|administrators>` | Command Guardian allow lists |
| `/mv` | `<list\|load\|tp>` | List, load and teleport between worlds |
| `/transfer` | (1.1.x+ only) | Send a player to another server |
| `/rejoin` | (1.1.x+ only) | Reconnect to this server's address |
| `/transfer-lobby` | `[player] <n>` (1.1.x+ only) | Send a player to a named lobby |
| `/pregen` | `[radius] [world]` | Pre-generate and populate chunks around spawn |
| `/creatorinfo` | | Show VeoZaxAPI and creator info and links |

### Standard commands
`ban`, `ban-ip`, `banlist`, `defaultgamemode`, `difficulty`, `dumpmemory`, `effect`, `enchant`, `gamemode`, `gc`, `give`, `help`, `kick`, `kill`, `list`, `me`, `pardon`, `pardon-ip`, `particle`, `plugins`, `reload`, `save-all`, `save-off`, `save-on`, `say`, `seed`, `setworldspawn`, `spawnpoint`, `status`, `stop`, `tp`, `tell`, `time`, `timings`, `title`, `version`, `weather`, `whitelist`.

There is no `/op` or `/deop`; administrators replace them.

---

## 7. Configuration reference

### `VeoZax.yml`
| Key | Default | Meaning |
|---|---|---|
| `server-log` | `true` | Write console output to `logs/` |
| `administrators-password` | (default shipped) | Password for `/administrators add/remove` |
| `administrators-locked` | `false` | Lock the Administrators Protocol |
| `server-owner` | `VeoZax` | Main owner name |
| `owner-access-password` | (default shipped) | Password for `/server-owner add/remove` |
| `owners-locked` | `false` | Lock the Owners Protocol |
| `sub-owners` | `[]` | Sub-owner names |
| `auto-restart` | `false` | Enable the restart countdown |
| `auto-restart-timer` | `9000` | Seconds until restart (2 h 30 min) |
| `restart-message` | `Server Restarted!` | Kick message |
| `transfer-webhook` | `false` | Send transfers to a Discord webhook |
| `transfer-webhook-url` | empty | Webhook URL |
| `transfer-self-address` | empty | Override public address used by `/rejoin` |
| `transfer-lobbies` | Lobby1, Lobby2 | Named lobbies (`ip`, `port`) |

### `administrators.yml`
`administrators: []`. Do not edit while the server is running; use `/administrators`.

### `veozaxapi.yml` (created on first run)
| Key | Default | Meaning |
|---|---|---|
| `API-Connection` | `false` | **Must be `true` or the server will not start** |
| `kill-thread.enabled` / `.timeout` | `true` / `10` | Shut down if the server freezes |
| `entity.knockBack.vanilla` | `true` | If true the values below are ignored |
| `entity.knockBack.modX` / `modY` | `0.4` / `0.4` | Knockback strength |
| `entity.knockBack.delay` | `10` | Hit delay in ticks |
| `entity.knockBack.verticalLimitEnabled` / `verticalLimit` / `verticalLimitMultiplier` | `true` / `2.5` / `0.85` | Vertical knockback cap |
| `level.weather` | `true` | Weather (rain can lag older devices) |
| `level.weather-random-duration-min` / `max` | `6000` / `12000` | Weather duration in ticks |
| `level.lightning-time` | `200` | Lightning interval in ticks, 0 disables |
| `level.lightning-fire` | `false` | Lightning causes fire |
| `level.fire-spread` | `false` | Fire spreads |
| `developer.folder-plugin-loader` | `false` | Load plugins from source folders |
| `developer.load-incompatible-api` | `false` | Load plugins with a different API |
| `nether.allow-nether` / `level-name` | `true` / `nether` | Nether world |
| `ender.allow-ender` / `level-name` | `true` / `ender` | End world |
| `anti-xray.enabled` / `worlds` | `false` / `[world]` | Anti-xray |
| `mobs.enable-mob-ai` | `false` | Mob movement (can lag with many mobs) |
| `mobs.generic-auto-mob-spawning` | `false` | Natural mob spawning |
| `redstone.enable` | `false` | Redstone system |
| `redstone.frequency-pulse` / `pulse-frequency` | `false` / `1` | Redstone pulses |

### `pocketmine.yml` (performance-related defaults)
- `memory.main-hard-limit: 2048` (MB; the server stops above this)
- `memory.max-chunks.trigger-limit: 28`
- `chunk-sending.max-chunks: 32` (about a 3-chunk radius per player)
- `chunk-sending.per-tick: 4`, `spawn-threshold: 6`
- `chunk-generation.queue-size: 8`, population queue 8
- `settings.async-workers: auto` (see section 11)
- `network.batch-threshold: 512`, `compression-level: 2`, `async-compression: true`
- `network.enable-encryption: false` (new in v3)
- `level-settings.auto-tick-rate: false`
- `ticks-per.autosave: 6000`, `cache-cleanup: 900`
- `light-updates: true`

### `server.properties` defaults
`motd`, `server-port 19132`, `white-list false`, `announce-player-achievements true`, `spawn-protection 16`, `max-players 20`, `gamemode 0`, `force-gamemode false`, `hardcore false`, `pvp true`, `difficulty normal`, `level-name world`, `level-type DEFAULT`, `enable-query true`, `enable-rcon false`, `auto-save true`, `view-distance 8`, `xbox-auth true`, `language eng`.

---

## 8. World generation

Unchanged in v3.

**Generators:** `flat`, `void`, `normal` (default), `nether` (hell), `ender`. A 520-line `vanilla` generator exists in `generator/vanilla/` but is not registered.

**Overworld (`normal`):** 128-block build height, sea level 62, Simplex noise terrain, 9x9 smoothing between biomes, very large biome regions, caves, mineshafts, and ores: coal, iron, redstone, lapis, gold, diamond, plus dirt, gravel, granite, diorite and andesite patches.

**Biomes:** 28 registered; the overworld can generate 24 of the 27 non-Nether ones: ocean, deep ocean, frozen ocean, river, frozen river, beach, cold beach, plains, desert, forest, birch forest, roofed forest, taiga, taiga hills, cold taiga, ice plains, ice mountains, mountains, swamp, jungle, savanna, mesa, mushroom island, mushroom island shore.

**Structures (chance per chunk):**
| Structure | Biomes | Chance |
|---|---|---|
| Desert temple | desert | 7.1% |
| Desert well | desert | 2.6% |
| Swamp hut | swamp | 2.6% |
| Igloo | ice plains, ice mountains | 31% |
| Mineshaft | any | 12.5% (single straight tunnel, 40 to 74 blocks, y 10 to 53) |
| Caves | any | 12.5% (y 30 to 80) plus 20% deeper (y 8 to 55) |

There are no villages, strongholds, ocean monuments, ravines or dungeons. The Nether has ores, lava, glowstone and fire (no fortresses). The End has obsidian pillars only.

**World formats:** Anvil, McRegion, PMAnvil, LevelDB providers are present.

---

## 9. Game content (verified from the source tree)

- **Blocks:** 220 block classes. Includes redstone parts (wire, torches, repeaters, lamps, levers, buttons, pressure plates, pistons and sticky pistons, daylight sensors, note block, dispensers, droppers, hoppers, rails including powered, detector and activator), shulker boxes, beacon, anvil, brewing stand, portal and end portal frame, TNT, fire.
- **Items:** 129 item classes. **Enchantments:** framework with sharpness, protection, fire aspect, knockback.
- **Tiles:** banner, beacon, bed, brewing stand, cauldron, chest, ender chest, daylight detector, dispenser, dropper, enchant table, flower pot, furnace, hopper, item frame, mob spawner, note block, piston head, shulker box, sign, skull.
- **Inventories:** chest and double chest, ender chest, furnace, brewing stand, enchant table, anvil, beacon, hopper, dispenser, dropper, shulker box, horse, armor, off-hand, crafting grid, with shaped, shapeless, furnace and brewing recipes.
- **Hostile mobs:** blaze, cave spider, creeper, enderman, husk, magma cube, skeleton, slime, spider, stray, witch, zombie.
- **Passive mobs:** cat, chicken, cow, horse, mooshroom, ocelot, pig, sheep, squid, villager, wolf.
- **Objects and vehicles:** ender crystal, XP orb, falling block, fireworks rocket, item entity, leash knot, lightning, painting, primed TNT, boat, minecart.
- **Projectiles:** arrow, egg, ender pearl, XP bottle, fishing hook, small fireball, snowball, splash potion.
- **Mob AI:** behavior system (stroll, look, panic, flee sun, mate, follow owner/parent, tempt, melee, ranged, swell, leap, slime movement) and an `EntityNavigator` pathfinder. **Mob AI and natural spawning are off by default.**
- **Redstone** is implemented but off by default; it was not tested during this review.
- Skins and capes are bundled with the vanilla resources.

---

## 10. Security and privacy notes

- **Change the default passwords** in `VeoZax.yml`. They are published in the repository.
- **Change `server-owner`.** The default is `VeoZax`; anyone able to join under that name gets main-owner rights. Keep `xbox-auth: true`.
- **Anonymous statistics are on by default.** The server sends usage data to `stats.pocketmine.net` unless `anonymous-statistics.enabled: false` is set in `pocketmine.yml` .
- **Hourly credit broadcast** is hard-coded.
- **Integrity check** refuses to run if `VersionInfo.php` is edited without updating its hash.
- **Encryption** is off by default in v3 (modern clients only).

---

## 11. Performance and TPS design

**Verified design:**
- World generation, population and lighting run on async worker threads.
- Chunk packets are built in async tasks and cached per protocol.
- Compression is asynchronous.
- The integrity check runs every 300 seconds, not every tick.
- Standard 20 TPS loop with a 20-sample average and an overload warning below 12 TPS.

**Possible costs (not measured):**
- Movement sync in v3 sends many more updates; with many players and mobs each packet is also converted per client protocol.
- `async-workers: auto` uses cores minus 2 (minimum 2), not "all cores" as the comment says. A 64-core machine would start 62 workers.
- `max-chunks: 32` limits everyone to about 3 chunks of view distance.
- `main-hard-limit: 2048` MB stops large servers.
- `auto-tick-rate: false` means the server will not slow level ticking under load.
- Plains chunks run a populator that does nothing (see section 13).

---

## 12. Plugin development

- Plugins must target **PocketMine-MP 3.0.0 ALPHA**.
- `plugin.yml` **must** contain `api: ["VeoZaxAPI"]`, otherwise the plugin will not load.
- Loaders: phar, script, and (optional) folder plugin loader.
- Commands sent by plugins on a player's behalf bypass the Command Guardian.

---

## 13. Known issues and limitations

**World generation bugs (verified in code):**
1. `WaterPit` can never place anything (its block check is contradictory), yet `PlainBiome` runs it 9,999 times per chunk, wasting async CPU.
2. The End biome (id 9) is never registered, so it falls back to Ocean. End chunks are marked as ocean, and the End generator changes the shared Ocean biome's ground cover to obsidian, which can leak into overworld oceans on the same worker thread.
3. `JUNGLE_HILLS` and `SMALL_MOUNTAINS` are registered but never generated; `COLD_TAIGA_HILLS` sits behind an impossible condition. Several selector branches return the same biome on both sides.
4. Igloos use a 1-in-100 roll while other structures use 1-in-1000; they may be about 10 times too common.

**Code issues:**
5. `SplFixedByteArray.php` does not parse on PHP 8 (old `$str{$i}` syntax). Nothing references it.
6. `RakLibInterface` comments refer to a knockback fix that `AnyVersionManager` and `P84VersionManager` no longer contain.
7. `async-workers` comment in `pocketmine.yml` is inaccurate (see section 11).

**Compatibility and limits:**
8. Transfers do not work for 0.14.x and 0.15.x clients.
9. Leg-swing on knocked-back players may be visible to older viewers again.
10. Protocols 100 to 107 are accepted but their exact game versions were not mapped.
11. Encryption is off by default; 1.1.x login with encryption off should be tested.
12. The project's own warning applies: **still in development; expect bugs, crashes and incompatibility.**
13. Not tested: redstone, mob AI, nether/end travel, anti-xray, and actual TPS under load.

---

## 14. If development resumes (suggested to-do list)

1. Register `EnderBiome` in `Biome::init()` (`self::register(self::END, new EnderBiome())`).
2. Fix or remove `WaterPit` and its 9,999-iteration loop in `PlainBiome`.
3. Fix the biome selector (jungle hills, small mountains, cold taiga hills).
4. Replace `$str{$i}` with `$str[$i]` in `SplFixedByteArray.php`.
5. Decide on the knockback leg-swing handling and make `RakLibInterface` consistent with the version managers.
6. Review the igloo spawn rate.
7. Remove or disable the default statistics endpoint.
8. Add an automated syntax lint (`php -l`) and basic join tests for each client version.
9. Measure TPS with real clients before promising anything about lag.

---

## 15. Credits, license and links

- **VeoZax**: sole developer of VeoZaxAPI.
- **PocketMine Team**: PocketMine-MP, the core this is built on.
- **MySoft API**: the original open-source 1.1.x to 1.1.7 version bridge that was rebuilt and rewritten.
- License: **GNU Lesser General Public License v2.1**. If you modify it, please publish your changes openly. Do not claim it as private property.

Requirements & How to Run - Checkout my YouTube Video
======================================================
I made a full video tutorial on my YouTube channel walking through how to set up and run the VeoZax API. If you're new to this
or just want to see it working before you dive in, watch it here:

[Watch the Setup Tutorial](https://youtu.be/taupSR8oO40?si=hL2mkyajHHlnTHyY)

Older version (Build 2.0)
=========================
If you'd rather skip GitHub and grab a ready-to-use copy of the older Build 2.0 release, you can download it via MediaFire.

[Download VeoZax API Build 3.0 (MediaFire)](https://www.mediafire.com/file/4daj3n2v8glov8f/Multiversion-API-0.14.x-0.15.10-1.1.x-VeoZax-API-Build-3.0.zip/file)

🔗 My Socialmedia Links
=========
<p align="left">
  <a href="https://info.veozax.xyz/"><img src="https://img.shields.io/badge/Website-000000?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"/></a>
  <a href="https://www.youtube.com/channel/UC33-nbRHQn-3H56aQc0sanA"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube"/></a>
  <a href="https://discord.gg/dCzgPYam2J"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"/></a>
  <a href="https://www.instagram.com/veozax"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/></a>
  <a href="https://www.tiktok.com/@veozaxofficial"><img src="https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=white" alt="TikTok"/></a>
  <a href="https://www.facebook.com/VeoZax/"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook"/></a>
  <a href="https://github.com/VeoZaxOfficial"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

*Thanks for sticking with Legacy MCPE. This one's for you.*
