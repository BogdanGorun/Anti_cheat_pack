# Anti_cheat_pack

[![sampctl](https://shields.southcla.ws/badge/sampctl-Anti_cheat_pack-2f2f2f.svg?style=for-the-badge)](https://github.com/RogueDrifter/Anti_cheat_pack)

>This is a pack of 12 anticheats which you can control through callbacks mentioned
>in the includes and the test.pwn file.
>
>
> `## Installation`: You simply include the files in your gamemode/fs depending
>on the include's setup (some require include in all scripts and only edit through
> the gamemode, others can be used in one script alone).
>
> `## Testing`: All can be done through the test.pwn folder which already
>contains all of the includes and their callbacks nottify you through `SCM` and `print` messages
>
> `## Version`: `2.0`

## Installation

Simply install to your project:

```bash
sampctl package install RogueDrifter/Anti_cheat_pack
```

Include in your code and begin using the library:

```pawn
#include <Anti_cheat_pack>
```

## Usage

> Use the callbacks provided to you by the includes depending on the type of it.
> The includes are 2 types as mentioned before, some edit only through gamemode and include everywhere.
> Others done through a single script whether its the GM/FS.

## Testing

> Use the test.pwn file and check the server for client messages/log for printed messages.

To test, simply run the package:

```bash
sampctl package run
```

## Contains:

*Anti cheats that don't require include in all scripts
>AFkill  //Anti fake kill -Rogue

>AntiFC //Anti fake clients - Rogue

>rAsc //Anti speed cheats- Rogue

>rVM //Anti illegal car mods -Emmet_

>rAcs //Anti car spam - Rogue

*Anti cheats that do require include in all scripts and only edit through GM
>AntiJC //Anti jetpack cheats- Rogue

>Opba //Anti airbreak\teleport - Rogue

>rAgc //Anti gun cheats -Rogue

>rAct //Anti car trolls - Rogue

>rEac //Anti carswing\particlespam - Lorenc_

>rAmc //Anti money cheats- Rogue
