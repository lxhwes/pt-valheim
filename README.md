# pt-valheim

Thunderstore.io Modpack for trve warriors of `poundtown.oovoid.com`

## manifest.json

This file is a metadata file for the modpack. It contains information about the modpack, such as its name, version, and dependencies. The `manifest.json` file is structured as follows:

```json
{
  "name": "modpack name",
  "version": "modpack version",
  "description": "modpack description",
  "dependencies": [
    {
        "Some-Dependencies-mod-1.6.9"
    },
    ...
  ]
}
```

# BepInEx Examples

To incluide BepInEx preconfigured mod .cfg files, use the examples below. Mainly for server side operation.

## BepInEx/config/modname.cfg

This file is a example configuration file for a mod. It contains settings and options specific to the mod.

## BepInEx/patchers/modname.Patcher.dll

This file is an example patcher DLL for the mod. It is responsible for modifying the game's code to add or change functionality.

## BepInEx/plugins/modname.dll

This file is an example of the main plugin DLL for a mod. It contains the code that adds new features or modifies existing ones in the game.
