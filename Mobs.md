#Mobs
From [MythicMobs]<br>

## Custom Mobs
_MythicMobs>Mobs>MazeRunnerInner_

## Maze Spawners
_MythicMobs>Spawners_<br>
Spawners around the maze that spawn custom mobs over an interval<br>
`/mm s create <name> 50%RunnerInner,50%TankInner`<br>
Naming Convention: mob_room_<#><i/m/o>_<secondary_spawners>
**Only Update Spawner YML File While Server is Off**

## Example Mobs
https://github.com/SXRWahrheit/MythicMobs-Files


## Random Mob Spawn
Mobs that spawn at night inside the maze <br>
`\plugins\MythicMobs\RandomSpawns\MazeNightMobRandomSpawn.yml`<br>
Tick Conditions: <br>
`Conditions:
    - worldtime{t=13000to23000} true`