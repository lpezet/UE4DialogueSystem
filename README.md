# UE4DialogueSystem
Unreal Engine 4 Dialogue System


This is pretty much a fork of https://github.com/artemavrin/UE4-DialogueSystem.
Didn't work as is for me so had to tweak things.


# Build

- Open XCode workspace file
- Run. This will start Unreal Engine with the plugin installed
- In Unreal Engine, Go to Settings > Plugins and look for "Dialogue System".
- Click "Package" and select an empty folder (or create one). This will package the plugin for installation. Close Unreal Engine.

# Plugin Install

- Copy the "DialogueSystem" folder (created by the package) to Engine/Plugins/ (e.g. /Users/Shared/Epic Games/UE_4.16/Engine/Plugins)
- Open Unreal Engine and create a new Third Person Blueprint project.
- Go to Plugins and look for Dialogue System, enable and restart Unreal.
