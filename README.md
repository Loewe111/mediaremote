# my MEDIA REMOTE

## Description

This is a simple media remote for your phone or pc, it connects via bluetooth and acts as a keyboard.

![Image](/scraps/2024-07-09%20235812.png)

I recently made this project with a simple perfboard and a off-the-shelf ESP32 module and Lipo battery. But i wasn't satisfied with how big it was and the short battery life because of the step-up converter i used. So i decided to make a new version with a custom PCB with a (for me) new Charger IC, the `MCP73871-2AAI/ML` and a LDO instead of a step-up and a step-down.

![Schematic](/schematic.png)