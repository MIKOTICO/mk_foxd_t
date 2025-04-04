# RedM foxd_t script - STANDALONE

## About

RedM foxd_t is a modification of Silonugget´s script (https://github.com/Silonugget/redm-truck) using the MK Fox Designs "Foxd Model T" pieces (https://mkfoxdesigns.tebex.io/package/6716285). 
I´m not the script creator; you can find the original script and the creator´s contact here: https://github.com/Silonugget/redm-truck.

The difference between this script and the original, is that this script has all the coordinates and details adjusted to work with the MK Fox Designs "Foxd Model T". If you need any assistance with the script, it is recommended to ask the creator (Silonugget) directly.

## Key Features

- **Synchronization**: Workarounds were discovered to keep the car visible upon new player join when tested with two people
- **Sounds**: Using the PMMS resource by Kibook, https://github.com/kibook/pmms, you can add customs sounds to the car (check original script for included sounds) 
- **Capablility**: From offroading to hillclimbs mk_foxd_t is fun to drive around in the world of RedDead.
- **Wheel Rotation** Realistic wheel behaviour - Press A or D to see the wheels turn in the corresponding direction

## Important/Issues
- To prevent visibility de-sync between players - Player is teleported to Mexico, then placed back if they leave the foxd_t and re-enter the driver seat
- To prevent visibility de-sync for vehicle - The entire vehicle/horse becomes visible if the vehicle touches water
- To prevent visibility de-sync for vehicle - foxd_t will explode if someone other than the player tries to sit in their driver's seat
- Front and rear lights will display at night automatically when the engine is on
- Light and exhaust smoke visibility is not yet synchronized for other players
- Player shoes may be visible underneath the foxd_t

## Installation

1. Drag and drop mk_foxd_t into server resources
2. Make sure you have the "MK_Fox_Designs_Foxd_Vehicles" package inside your server resources folder.
3. Ensure MK_Fox_Designs_Foxd_Vehicles and mk_foxd_t

## Commands
Change select commands such as spawn command in the config.lua file

| Command | Description |
| --- | --- |
| `/spawn_foxd_t` | Spawns the foxd_t next to player |
| `/delete_foxd_t` | Deletes foxd_t |
| `/reset_foxd_t` | Resets foxd_t |
| `/fixme` | Manual toggle for player visibility de-sync - Teleports player to Mexico and back |
| `/fixfoxd_t` | Manual toggle for object visibility de-sync - Toggles foxd_t visibility |
| `/waterfix` | Manual toggle for water visibility de-sync - Makes everything visible |
| `/lock` | Preliminary idea for locking - Makes vehicle undriveable (wheels are likely to fall off/cannot be unlocked) |

# controls

Turn Engine on/off = Left Alt, 
   Rev = R

## Credits
- Silonugget´s original script https://github.com/Silonugget/redm-truck
- MK Fox Designs for car models https://mkfoxdesigns.tebex.io/package/6716285
