# General Information

This script allows one person to see outputs given by scripts.

# Automatic launch on clientside

1. Make a LocalScript in `game:GetService("Workspace")`.
2. Put the code from `main.lua` on GitHub to the LocalScript.

# Automatic launch on serverside 

1. Make a ServerScript in `game:GetService("StarterPlayerScripts")`.
2. Put the code from `main.lua` on GitHub to the ServerScript.

# Direct shortened executes

If you wanna execute the script on exploitside via the executor, use the code from `exploitside-loader.lua` on GitHub.
If you wanna execute the script on serverside via `require()`, use the code from `serverside-loader.lua` on GitHub.

On serverside direct shortened execute, the game must have HTTP communications enabled.

# How to enable HTTP on the Roblox game 

1. Enter Roblox Studio.
2. Go to the roblox game you wanna allow HTTP in.
3. Go to Settings.
4. Go to Studio.
5. Go to Security.
6. Enable the "Allow HTTP requests" option.
7. Get back to the roblox game on Roblox Studio.
8. Execute `game:GetService("HttpService").HttpEnabled = true` in the Studio command bar.
9. Save the Roblox game and exit the Studio.
