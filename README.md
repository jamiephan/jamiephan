# Hello! 🥳


## Projects

- [jamiephan.github.io](https://github.com/jamiephan/jamiephan.github.io): My [personal website](https://www.jamiephan.net), with some nice parallax effects in the universe 🌍 and a *hidden* easter egg 👀.
- [JSONBin](https://github.com/jamiephan/JSONBin): A Pastebin-like service speifically designed for JSON. Can be also exported to different formats such as XML, YAML. It features a API based service with an online editor.
- [batch-scripts](https://github.com/jamiephan/batch-scripts): Some random batch scripts that I made, I use them quite often for various of stuff (*why the fxxk Windows uses forward slash in paths, oh my fu...\*ahem\*, please excuse me.*)


Most of my working projects are in private, so not much are listed 😔.

However you can check out my [blog](https://blog.jamiephan.net) instead!

---

## Heroes of the Storm

[Heroes of the Storm](https://heroesofthestorm.com/) is one of my favorite MOBA game with great looking arts and heroes. I can confidently say I spent over 3000+ hours game time with many more hours dedicated to modding.

More importantly, Heroes of the Storm is a modified engine based on the [Starcraft 2](https://starcraft2.com/) engine. Starcraft 2 have a publicly available game editor for modding the game (While Heroes does not). However, due to they are using a similar game engine, Heroes have inherited some custom map loading features as well, although it is not publicly documented.

Here are some projects related to Heroes of the Storm:

### Active:

- [Storm Map Generator](https://stormmap.jamiephan.net/) ([source code](https://github.com/jamiephan/HeroesOfTheStorm_StormMapGenerator)): An online `stormmap` file generator (`stormmap` is the map file format for Heroes of the Storm), that supports multiple configurations such as template map, adding AI, welcome message, enabling debug mode and adding customized XML game data files. You can also use the Web UI to edit and validate the XML files without an editor installed on your computer. Enables for a completely tool-less `stormmap` file generation.
- [Try Mode 2.0](https://github.com/jamiephan/HeroesOfTheStorm_TryMode2.0): A drop-in replacement for the in game Try Mode (or Test Mode), with extra features such as *Enabling Debug mode*, *Spawn any units*, *Update any game values*, etc, and tools making modding the map much easier. It will also generate multiple maps (including AI variants) with the custom modding data.
- [Try Mode 2.0 Installer](https://github.com/jamiephan/HeroesOfTheStorm_TryMode2.0Installer): An Installer App for *Try Mode 2.0*, allowing to reduce the complexity when installing the custom maps, it also allows to fetch the latest map from the Releases.
- [Game Data](https://github.com/jamiephan/HeroesOfTheStorm_Gamedata): A repo to store all the non-binary game data from Heroes of the Storm (excluding Assets). The game data will be fetched automatically and generate a `xsd` file, that can be used for custom modding validation and editor auto-completion.
- [S2MA](https://github.com/jamiephan/HeroesOfTheStorm_S2MA): Automatically fetch Heroes of the Storm (via GitHub Action) data and extract the mods and map files. Act as a storage for those files, which are used by *Try Mode 2.0*, for building custom maps and *AI Maps*, for injecting AI players into the maps.
- [AI Maps](https://github.com/jamiephan/HeroesOfTheStorm_AIMaps): Automatically fetch the maps from the *S2MA* repo and inject the AI (non-modify maps will not have any AI players). It will generate all sort of "AI compositions", such as `1v5`, `3v3`, etc. The `5v5` variant was also used by *Try Mode 2.0* to generate a custom map.
- [Tools](https://github.com/jamiephan/HeroesOfTheStorm_Tools): Various tools that I used to aid my modding for Heroes of the Storm.
- [storm-extract-docker](https://github.com/jamiephan/storm-extract-docker): A docker-ised [`storm-extract`](https://github.com/nydus/storm-extract) command line tool, allows you to run the tools platform independent provided [`docker`](https://www.docker.com/) was installed. The built image is also using `SCRATCH`, so the image size can be as small as `1.52MB`.
- [Battle.Net-Installer](https://github.com/jamiephan/Battle.Net-Installer): A fork of [`barncastle/Battle.Net-Installer`](https://github.com/barncastle/Battle.Net-Installer), which allows it to be run in non-console environments such as GitHub Action. This is heavily used by *S2MA* and *Game Data* repo to fetch the game data automatically.


### Archived:

- [Blizzcle](https://github.com/jamiephan/blizzcle): Blizzcle, or Blizzard Article, A NodeJS module and command line tool to download Blizzard's news and article, returns the result as JSON, or generate the article in HTML, JSON when used via the CLI.
- [Snapshot Differ](https://github.com/jamiephan/HeroesOfTheStorm_SnapshotDiffer): A repo to extract Heroes of the Storm data, host, generate a diff compare to previous versions and sent it via a reddit bot. **This repo have been archived in flavor of [Game Data](https://github.com/jamiephan/HeroesOfTheStorm_Gamedata) repo.**
- [Snapshot Differ Result](https://github.com/jamiephan/HeroesOfTheStorm_SnapshotDifferResult): A repo to host all the `diff` result generated from *Snapshot Differ*. **This repo have been archived in flavor of [Game Data](https://github.com/jamiephan/HeroesOfTheStorm_Gamedata) repo.**
- [New Heroes Notification](https://github.com/jamiephan/HeroesOfTheStorm_NewHeroesNotification): Some PHP script to monitor and alert new heroes of blog posts
