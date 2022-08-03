# SteamGameFixer

SteamGameFixer (name likely to change) is a project that aims to help users of Steam on Linux apply fixes to their games in a simple manner using a controller-friendly interface.

SteamGameFixer will be modular and extensible, allowing the contribution of fixes by third parties. It will maintain a list of default games, but allow users to load their own extensions if they choose.


### Implementation

How SteamGameFixer will be built has not yet been decided. While at first it was conceived as a stand-alone application, installed as a FlatPak and added to Steam manually, the current front-runner is to implement as a [DeckyLoader](https://github.com/SteamDeckHomebrew/decky-loader) plugin. The [Crankshaft Plugin Manager](https://crankshaft.space/) is also being investigated as a possibility.

The format of game extensions has also not yet been decided. More info to come.


### Supported Games

This is an initial list of possible supported games. A game's inclusion on this list is not a promise to implement a fix. This is merely a starting place to investigate potential extensions.

- Bully
- Jedi Knight
- Final Fantasy XIII & XIII-2
- Monster Hunter Rise
- Hades
- Vampire Masquerade Bloodlines
- Yakuza 3 Remastered
- GTA - 3 / VC / SA
- Fall Guys
- Stalker Anomaly
- Resident Evil
- Gust Games (e.g . Atelier series)
- River City Girls
- C&C Red Alert 3


### Suggesting a Game

If there is a game you would like to see included, please open a new issue here on GitHub. Please include a description of the fix, potentially a link to information regarding how a user would do it manually.

Remember, we are not building new fixes, mods, or patches. We're merely helping people install existing solutions. So please do not request that we fix a bug or issue with a game that is not elsewhere already addressed.


### Other suggestions

Please feel free to make other feature suggestions. However, for the time being the feature set will remain fairly focused: fixing user's games in a simple, controller-focused way.
