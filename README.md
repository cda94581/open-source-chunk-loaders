# Open Source Chunk Loaders
See more information about Open Source Chunk Loaders [here](https://cda94581.github.io/downloads/bps.html#_2021-06-01)

Download the Add-on [here](https://github.com/cda94581/open-source-chunk-loaders/releases)

## About
Open Source Chunk Loaders is a project which helps to keep chunks loaded in Minecraft: Bedrock Edition. Minecraft worlds are loaded in "chunks", and in order to ensure the game's playability, only a certain number of chunks around each player are kept loaded. This project aims to resolve this with a chunk loader item, which enables certain chunks to always stay loaded. This is beneficial for AFK farms or other playerless contraptions that may need to stay in the game.

### VS. Other Add-ons
This add-on is fundamentally different from other chunk loaders through the use of the `minecraft:tick_world` component. Most other packs use the `/tickingarea` command to keep chunks loaded, however in a world, there can only be 10 loaded areas that can be created through that command. `minecraft:tick_world` does not suffer from this, and so there can be more than 10 areas, provided your device can handle it.

[Showcase Video](https://youtu.be/LJBd6VS20jI)

[View on MCPEDL](https://mcpedl.com/open-source-chunk-loaders/)

## Introduction
Open Source Chunk Loaders is a free addon that adds chunk loaders to Minecraft Bedrock Edition. These can be used for a variety of purposes, like loading farms that don't require a player to be nearby to work, like crop farms. Unlike the existing /tickingarea command, Open Source Chunk Loaders use an entity with a minecraft:tick\_world component to keep chunks loaded. Within reason, unlimited chunk loaders can be added, from a 2 chunk radius, to a 6 chunk radius. This will NOT work as a player, farms that require a player nearby like Iron Golem farms or spawner-based farms, will not work.

## Documentation
To get the chunk loader, you will need a **Nether Star** and a **Lodestone**. Craft the two together, it doesn't matter how you position them. In return, you will get a **Chunk Loader** block.
![Crafting](https://api.mcpedl.com/storage/submissions/105362/images/open-source-chunk-loaders_2.png)

You can also obtain this by inputting **/give @s cda001:chunk\_loader\_block**. This block will cycle through many different states of chunk loading, anywhere from 2-6 chunks.

Place this block down. It is not currently loading any chunks. To do so, step on top of the block. It will become an **entity**.
![0 Chunks](https://api.mcpedl.com/storage/submissions/105362/images/open-source-chunk-loaders_3.png)

Right now, it is still not loading chunks. To start loading chunks, **interact** with this block. This varies based on device, it is basically what you would do to fish. As you continue to interact, you will cycle through all the different chunk loading radii:
![2 Chunks](https://api.mcpedl.com/storage/submissions/105362/images/open-source-chunk-loaders_4.png)
![3 Chunks](https://api.mcpedl.com/storage/submissions/105362/images/open-source-chunk-loaders_5.png)
![4 Chunks](https://api.mcpedl.com/storage/submissions/105362/images/open-source-chunk-loaders_6.png)
![5 Chunks](https://api.mcpedl.com/storage/submissions/105362/images/open-source-chunk-loaders_7.png)
![6 Chunks](https://api.mcpedl.com/storage/submissions/105362/images/open-source-chunk-loaders_8.png)

**Tiny Technical Bits**

The textures are designed so as to visualize the area loaded. Everything in black is not loaded. Everything inside of the green (including the green) is loaded. The blue represents the chunk in which this chunk loader is in.

There are a couple of helpful resource packs that may help with chunks, those being [MaddHatter](https://youtu.be/eTcxPQy1a90)'s, [FoxyNoTail](https://youtu.be/i4yWfY2hnns)'s, and [WinEpicFin](https://mcpedl.com/customizable-render-dragon-chunk-borders/)'s.

As stated above, this will NOT work for farms that require an active player, like iron farms or spawner-based farms.

This pack is open source, meaning anyone may contribute and/or remix and build upon this add-on.

**Warning**: Do NOT add too many of these, it will lag your game.

Finally, enjoy! Let me know if you have any issues as well!

## Installation
1. Download the pack at the given link
2. Import it
	- If you are unable to import it with a tap/double click, rename the file from a **.mcaddon** file extension to a **.zip** file extension. Afterwards, **unzip** the folder and move the **behavior pack** to the **behavior\_packs** folder and the **resource pack** to the **resource\_packs** folder of the **com.mojang** folder
3. Apply it to your worlds
4. Enjoy!

## Contributing
This section is a work in progress, however you're free to contribute however you'd like! Please be aware that this project is licensed under the [MIT License](./LICENSE), which is a simple and permissive license that allows anyone to do anything with it, and any contributions should reflect this understanding. These are a few options on what can be contributed:
- Language Translations
- Changes to the Base Source Code
- [Open Bug Reports](https://github.com/cda94581/open-source-chunk-loaders/issues)
- Create and Maintain Documentation