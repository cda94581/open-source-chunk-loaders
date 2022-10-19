# Open Source Chunk Loaders
See more information about Open Source Chunk Loaders [here](https://cda94581.github.io/downloads/bps.html#_2021-06-01)

Download the Add-on [here](https://github.com/cda94581/open-source-chunk-loaders/releases)

## About
Open Source Chunk Loaders is a project which helps to keep chunks loaded in Minecraft: Bedrock Edition. Minecraft worlds are loaded in "chunks", and in order to ensure the game's playability, only a certain number of chunks around each player are kept loaded. This project aims to resolve this with a chunk loader item, which enables certain chunks to always stay loaded. This is beneficial for AFK farms or other playerless contraptions that may need to stay in the game.

## VS. Other Add-ons
This add-on is fundamentally different from other chunk loaders through the use of the `minecraft:tick_world` component. Most other packs use the `/tickingarea` command to keep chunks loaded, however in a world, there can only be 10 loaded areas that can be created through that command. `minecraft:tick_world` does not suffer from this, and so there can be more than 10 areas, provided your device can handle it.

## Contributing
This section is a work in progress, however you're free to contribute however you'd like! Please be aware that this project is licensed under the [MIT License](./LICENSE), which is a simple and permissive license that allows anyone to do anything with it, and any contributions should reflect this understanding. These are a few options on what can be contributed:
- Language Translations
- Changes to the Base Source Code
- [Open Bug Reports](https://github.com/cda94581/open-source-chunk-loaders/issues)
- Create and Maintain Documentation