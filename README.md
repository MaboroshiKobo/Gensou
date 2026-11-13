[![Gensou Banner](https://raw.githubusercontent.com/MaboroshiKobo/branding/refs/heads/main/projects/gensou/banners/gensou_2048.png)](https://docs.maboroshi.org/projects/gensou)

<div align="center">
  <p>
    <img alt="fabric" height="56" src="https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/cozy/supported/fabric_vector.svg">
  </p>

  <p>
    <a href="https://github.com/MaboroshiKobo/Gensou"><img alt="github" height="56" src="https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/cozy/available/github_vector.svg"></a>
    <a href="https://modrinth.com/modpack/gensou"><img alt="modrinth" height="56" src="https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/cozy/available/modrinth_vector.svg"></a>
  </p>

  <p>
    <a href="https://docs.maboroshi.org/projects/gensou"><img alt="generic" height="56" src="https://raw.githubusercontent.com/MaboroshiKobo/branding/refs/heads/main/socials/128x/domain_icon_bg.png"></a>
    <a href="https://discord.maboroshi.org"><img alt="discord-singular" height="56" src="https://raw.githubusercontent.com/MaboroshiKobo/branding/refs/heads/main/socials/128x/discord_icon_bg.png"></a>
  </p>
</div>

## High-performance rendering, full resource pack parity, and proximity voice chat

Gensou is a clean, lightweight Fabric modpack built to deliver a smooth, complete visual experience on modern multiplayer servers without the bloat of kitchen-sink packs. Pair modern rendering and input optimizations with full OptiFine resource pack support, local chunk caching, and built-in proximity voice chat right out of the box.

## Features

- Maximize frame rates, cut memory usage, and eliminate high-polling mouse stutter with Sodium, Lithium, FerriteCore, and Ixeris.
- Run shaders natively with Iris and enjoy full OptiFine resource pack parity via EMF, ETF, ESF, Continuity, OptiGUI, Polytone, Puzzle, and Skyboxify.
- See far beyond restrictive server-side render distance limits using local chunk caching powered by Bobby.
- Communicate seamlessly on supported servers with built-in Simple Voice Chat integration.
- Reload resource packs and switch languages asynchronously without freezing your client using Remove Reloading Screen and Language Reload.
- Keep gameplay pure with practical quality-of-life tweaks like extended chat history, faster server list pings, and hunger/saturation overlays.

## Versioning

Gensou follows a structured release pattern combining the target Minecraft version with the modpack version (`Minecraft Version-Modpack Version`, such as `26.3-3.0.0`):

- Major (`?.x.x`) - Mod additions, structural removals, or engine upgrades.
- Minor (`x.?.x`) - Configuration updates, mod swaps, or behavioral adjustments.
- Patch (`x.x.?`) - Dependency updates and stability fixes.

When Minecraft receives a major version release, the modpack version resets to `1.0.0`.

## Documentation & Support

For setup guides, mod lists, and configuration details, check out our [wiki](https://docs.maboroshi.org/projects/gensou). For bugs, questions, or updates, visit our [Discord server](https://discord.maboroshi.org) or open a [GitHub Issue](https://github.com/MaboroshiKobo/Gensou/issues).

## Building

To export a Modrinth `.mrpack` archive from source, ensure you have [packwiz](https://packwiz.infra.link/) installed and run:

```bash
cd pack && packwiz modrinth export
```
