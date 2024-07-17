# Mooncord [<img src="https://api.serversmp.xyz/upload/6696ae127036ecb33d717ada.webp" width="225" align="left" alt="Moonroof">](https://github.com/MoonHQ/Moonroof)

Moonroof is a fork of [Sunroof](https://github.com/verticalsync/Sunroof) which is a fork of [Vesktop](https://github.com/Vencord/Vesktop).

You can join our [discord server](https://discord.com/invite/zXnVNWjwvy).<br><br></br></br></br></br>

## Main features

-   Much more lightweight and faster than the official Discord app
-   Linux Screenshare with sound & wayland

**Extra included changes**

-   Mooncord preinstalled
-   Custom Splash animations from [this PR](https://github.com/Vencord/Vesktop/pull/355)

**Not yet supported**:

-   Global Keybinds

## Installing

Download the latest release from the [releases page](https://github.com/MoonHQ/Moonroof/releases).

## Building from Source

Packaging will create builds in the dist/ folder

> [!NOTE]
> On Windows, if you run the test script, you will get test errors about venmic, you can ignore these as it's a linux only module.

```sh
git clone https://github.com/MoonHQ/Moonroof
cd Moonroof

# Install Dependencies
pnpm i

# Either run it without packaging
pnpm start

# Or package
pnpm package
# Or only build the pacman target
pnpm package --linux pacman
# Or package to a directory only
pnpm package:dir
```
