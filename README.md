# johan-carpet
A carpet extension made by JohanVonElectrum in Minecraft 1.16.4.

This addon may be incompatible with [carpet-addons](https://github.com/whoImT/carpet-addons). <br>
This addon is incompatible with [carpet-extra](https://github.com/whoImT/carpet-addons). Please use this [carpet-extra](https://github.com/JohanVonElectrum/carpet-extra) adapted version instead. <br>

# Johan carpet rules

## TheEnd rules

### endGatewayCooldown
Remove the end gateway cooldown.
* Type: `boolean`
* Default value: `true`
* Required options: `true`, `false`
* Categories: `johan-addon`, `johan-end-features`, `feature`

### endMainIslandStructureGen
No end spikes, portal, crystal, egg or gateway generation when false.
* Type: `boolean`
* Default value: `true`
* Required options: `true`, `false`
* Categories: `johan-addon`, `johan-end-features`, `feature`

### noObsidianPlatform
Entities do not generate the obsidian platform in the end, except players.
* Type: `boolean`
* Default value: `false`
* Required options: `true`, `false`
* Categories: `johan-addon`, `johan-end-features`, `feature`

## Cannon rules

### keepProjectilesTicked
Keep projectiles ticked in unloaded chunks.
* Type: `string`
* Default value: `default`
* Required options: `default`, `all`, `player-only`, `enderpearls`
* Categories: `johan-addon`, `feature`, `cheat`

### logTNTMomentum
Debug TNT momentum transfer to enderpearls in console.
* Type: `boolean`
* Default value: `false`
* Required options: `true`, `false`
* Categories: `johan-addon`, `creative`

### ftlTNT
TNT optimized for large amounts in Cannons.
* Type: `boolean`
* Default value: `false`
* Required options: `true`, `false`
* Categories: `johan-addon`, `survival`, `optimization`

## Command rules

### commandLocation
Enables /location command to know where is a player.
* Type: `boolean`
* Default value: `false`
* Required options: `true`, `false`
* Categories: `johan-addon`, `survival`, `command`

### commandSignal
Enables /signal command to get a container with comparator value.
* Type: `boolean`
* Default value: `false`
* Required options: `true`, `false`
* Categories: `johan-addon`, `creative`, `command`

### commandEnderchest
Enables /enderchest command to open the enderchest of a player.
* Type: `boolean`
* Default value: `false`
* Required options: `true`, `false`
* Categories: `johan-addon`, `feature`, `command`

### commandTotal
Enables /total command to know the total sum of a scoreboard.
* Type: `boolean`
* Default value: `false`
* Required options: `true`, `false`
* Categories: `johan-addon`, `survival`, `command`

### commandComputation
Enables /computation command to test redstone contraptions.
* Type: `boolean`
* Default value: `false`
* Required options: `true`, `false`
* Categories: `johan-addon`, `survival`, `command`

### commandBatch
Enables /batch command to execute commands multiple times.
* Type: `boolean`
* Default value: `false`
* Required options: `true`, `false`
* Categories: `johan-addon`, `command`

## Score rules

### filterBotsInScores
Bots don't appear on scoreboards and do not count in the total.
* Type: `boolean`
* Default value: `false`
* Required options: `true`, `false`
* Categories: `johan-addon`, `survival`, `feature`

### totalScore
The scoreboard total appears on the scoreboard.
* Type: `boolean`
* Default value: `false`
* Required options: `true`, `false`
* Categories: `johan-addon`, `survival`, `feature`

## Entity rules

### forceShulkerTeleport
Force shulkers to teleport when stay in invalid positions.
* Type: `boolean`
* Default value: `false`
* Required options: `true`, `false`
* Categories: `johan-addon`, `johan-end-features`, `survival`, `cheat`

### seaLevelFishes
Fishes only can spawn between y:45 and y:63, both excluded.
* Type: `boolean`
* Default value: `false`
* Required options: `true`, `false`
* Categories: `johan-addon`, `survival`, `bugfix`

### maxHeightmap
Set the max value possible for heightmap. USE AT YOUR OWN RISK!
* Type: `integer`
* Default value: `255`
* Valid options: `0-255`
* Categories: `johan-addon`, `survival`, `experimental`, `optimization`, `cheat`

### llamaDupeExploit
Enables old donkey / llama dupe bug.
* Type: `boolean`
* Default value: `false`
* Required options: `true`, `false`
* Categories: `johan-addon`, `survival`, `cheat`

## PlayerTweaks

### oldFlintAndSteelBehavior
Backports 1.12 flint and steel behavior. Flint and steel can be used for updating observers / buds.
* Type: `boolean`
* Default value: `false`
* Required options: `true`, `false`
* Categories: `johan-addon`, `survival`, `feature`

### carefulBreak
Places the mined block in the player inventory when sneaking.
* Type: `string`
* Default value: `never`
* Required options: `never`, `always`, `sneaking`, `no-sneaking`
* Categories: `johan-addon`, `survival`, `feature`, `experimental`

### oreUpdateSuppressor
Emerald ore acts as an update suppressor.
* Type: `boolean`
* Default value: `false`
* Required options: `false`, `true`
* Categories: `johan-addon`, `creative`, `cheat`

### shulkerInception
Enable the possibility to store shulkerboxes inside shulkerboxes.
* Type: `boolean`
* Default value: `false`
* Required options: `false`, `true`
* Categories: `johan-addon`, `survival`, `cheat`

### compatibleEnchantments
Disable enchantment compatibility checks.
* Type: `boolean`
* Default value: `false`
* Required options: `false`, `true`
* Categories: `johan-addon`, `survival`, `cheat`, `enchantment`

### disableEnchantmentCap
Disable enchantment max level cap.
* Type: `boolean`
* Default value: `false`
* Required options: `false`, `true`
* Categories: `johan-addon`, `survival`, `cheat`, `enchantment`

### disableAnvilXpLimit
Disable anvil max xp cap.
* Type: `boolean`
* Default value: `false`
* Required options: `false`, `true`
* Categories: `johan-addon`, `survival`, `cheat`, `enchantment`

### bucketSponge
Using a bucket renamed to "sponge" removes fluids in the area.
* Type: `boolean`
* Default value: `false`
* Required options: `false`, `true`
* Categories: `johan-addon`, `survival`, `cheat`

### itemFrameDelay
Item frame reset delay.
* Type: `int`
* Default value: `0`
* Required options: `>=0`
* Categories: `johan-addon`, `survival`, `experimental`, `cheat`

### allStackable
All items have 64 stack size.
* Type: `boolean`
* Default value: `false`
* Required options: `false`, `true`
* Categories: `johan-addon`, `survival`, `cheat`

### infiniteTrades
Makes merchant offers unlimited.
* Type: `boolean`
* Default value: `false`
* Required options: `false`, `true`
* Categories: `johan-addon`, `survival`, `cheat`

### creativeKill
Insta-kill entities when you are in creative mode.
* Type: `boolean`
* Default value: `false`
* Required options: `false`, `true`
* Categories: `johan-addon`, `creative`, `feature`

## Development Roadmap
-   MultiThreading entities by dimension
-   Passive Farms Fix
-   Keep enderpearls traveling without loading chunks and teleport player when lands
-   More cheats, xD
-   Renewable resources with new mechanics... 100% vanilla stuff ofc
