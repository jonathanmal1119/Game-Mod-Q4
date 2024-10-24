How to get the mod Running:
1. Download the repository.
2. Create a mod folder within your Quake 4 game folder.
3. Copy the pak001.pk4 file from the pack folder in the repository into the mod folder.
4. Copy Quake4Config.cfg from the configs folder in the repository. 
5. Copy game000.pk4 file from q4base.
6. Open it with 7.zip or equivalent program.
7. Compile the repository code in release mode.
8. Overwrite the gamex86.dll in the game00.pk4 file with the newly compiled Gamex86.dll.
9. Launch the game and load up the mod with the same name as your mod folder.
10. Play!

How to See the features of the Mod.

Objectives:
Craft the current level's target item to progress Tiers. 
5 Tiers total
  1. Computer Case
  2. Server Rack
  3. Circuit Board
  4. Computer
  5. Server
Once the server is crafted, you have completed the game.

Blueprints:
To craft anything you need the blueprint unlocked.
A new blueprint is unlocked after every 5 kills.
There are 15 blueprints (5 Items, 5 Tools, 5 Weapons).

To see all unlocked blueprints run the command 'listBlueprints'.

Crafting:
To craft run the 'craft' Command.
Syntax: craft <recipe> <amount> 

To see all recipes and their costs run the command 'listRecipes' or see below.

Recipes:

Tools:
- recipe_tool_soldering_iron: 5 iron, 5 copper, 2 plastic
- recipe_tool_hammer: 5 Iron, 5 plastic
- recipe_tool_forge: 10 iron, 5 copper, 2 plastic
- recipe_tool_smelter: 15 Iron, 5 copper, 2 plastic
- recipe_tool_screw_driver: 5 iron, 5 plastic

Items:
- recipe_computer_case: 10 Iron | Required Tools: Hammer, Smelter
- recipe_server_rack: 3 Computer Cases | Required Tools: Hammer, Screw Driver
- recipe_circuit_board: 10 Copper, 10 Plastic | Required Tools: Smelter, Soldering Iron
- recipe_computer: 1 Computer Case, 3 Circuit Boards | Required Tools: Screw Driver
- recipe_computer: 3 Computers, 1 Server Rack | Required Tools: Hammer, Screw Driver

Weapons:
- recipe_rifle: 10 Iron, 5 copper, 2 plastic | Required Tools: Forge
- recipe_stun_rebar_gun: 10 Iron, 2 Plastic | Required Tools: Forge
- recipe_spike_launcher: 12 Iron, 5 Copper, 2 Plastic | Required Tools: Forge
- recipe_staplegun: 10 Iron, 5 Copper, 2 Plastic | Required Tools: Forge
- recipe_noblisk_launcher: 5 Iron, 2 Plastic | Required Tools: Forge

