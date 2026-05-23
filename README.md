# SC2 Campaign Launcher - Mac Port

An unofficial Mac port of Team Koprulu's SC Evo Complete Campaign Launcher.

## Requirements
- macOS (Apple Silicon Arm64)
- Knowing where your Starcraft II installation folder is located
- Your Starcraft II Folder contains a "Maps" folder and a "Mods" folder
  -  If you don't have these, you can just create new empty folders. The names **are case-sensitive** 

## Installation
1. Download SC Evo Launcher-arm64.dmg from the [Releases](https://github.com/Swagdude7/SC2-Evo-Launcher-Mac/releases) page
2. Double-click the .dmg and drag SC Evo Launcher into your Applications folder
3. Right-click the app and select Open (required on first launch)
4. When prompted, click Open to bypass Gatekeeper
5. Point the launcher at your StarCraft II installation folder

## Troubleshooting
**"App is damaged and can't be opened"**
1. Open Terminal
2. Navigate to where <em>SC Evo Launcer.app</em> is located
  - For example: <code>cd /Applications</code>
3. Run the following command: <code>xattr -cr SC\ Evo\ Launcher.app</code>
4. Try running the application again

## Notes
1. Automatic launcher updates are not supported
2. Intel Mac support is untested
3. I have not tested every level individually
4. I have not tested the Patreon beta functionality

## Credits
Original launcher by Team Koprulu - https://github.com/TeamKoprulu/SCEvoComplete

Mac port by Swagdude7
