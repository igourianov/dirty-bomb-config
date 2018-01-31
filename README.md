# UI config for game Dirty Bomb
This config rearranges several UI widgets to better fit large resolution screens.

Following high level changes were made:

1. Clustered health, ammo and ability widgets behing the player model's right hand.
2. Moved minimap to the top left corner
3. Moved objective meter and respawn timer to the mid left
4. Moved badge notification to the bottom right corner and increased its timeout from 3 seconds to 15
5. Removed a number of unused config variables

### Sample screenshot ![logo](/screenshot_1.png)

## Installation
1. Navigate to your `C:\Users\[user]\Documents\My Games\UnrealEngine3\ShooterGame\Config` folder
2. Make a copy of your original `ShooterUI.ini` file just in case
3. Replace your `ShooterUI.ini` with the one provided
4. Copy the `[IniVersion]` section from your original file (it's at very bottom) and replace it the new file. This should prevent the game from resetting this config to default.
