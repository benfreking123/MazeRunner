ProSkillAPI Skills using Stats to effect their damage and other components<br>
Skills are modified by [Stats](Stats)
## Damage Categories
- Melee
- Projectile (PRORPGITEMS_physical)
- Lightning
- Fire
- Ice
- Energy
- Poison
- Chaos


## Examples
### Baseliner
- Dash (Movement)
- Dart (Physical|Projectile)
- Scatter Bolt (Spell|Lightning)
- Bomb (AOE|Fire)
- Strike (Physical|Melee)

Future Skills:<br>
- Boost (Buff|Movement)

## Setup
Attributes: plugins\ProSkillAPI\Attributes.yml

We have Skills that utilize Attributes from GenItems-ProRPGItems,
Skills Damage Can be upgraded through
skill-damage-<classification>  | The amount of damage done by skills with the specified classification

plugins\ProRPGItems\modules\item_generator\items\MazeRunnerInner
Under skillapi-attributes, you can roll random attributes that are the stats we will use
Defense & Damage Types for the Armor are found here 
Defense and & Damage types can be defined at plugins\ProRPGItems\item_stats

