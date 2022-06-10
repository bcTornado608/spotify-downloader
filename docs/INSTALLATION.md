# spotDL Installation Guide

spotDL is a free and open source tool that downloads your Spotify playlists & music

> **The fastest, easiest, and most accurate command-line music downloader**

## Using spotDL

<details>
    <summary style="font-size:1.25em">
        <strong>Using prebuilt executable</strong>
    </summary>

### Downloading the executable

You can download the latest version from from the [Releases Tab](https://github.com/spotDL/spotify-downloader/releases)

### Running web ui

Web UI will start by default if no arguments are passed to the command line (after double-clicking for example)

![Web UI](/docs/images/WEB_UI.png)

### Running the cli

To use the command line interface just open your terminal and run `./spotdl-vX.X.X operation [urls]`

</details>

<details>
    <summary style="font-size:1.25em">
        <strong>Using python</strong>
    </summary>

### Prerequisites

- Python 3.7 or above (added to PATH)
- FFmpeg 4.2 or above (added to PATH)
- Visual C++ 2019 redistributable (on Windows)

### Adding Python to PATH

When installing Python, ensure to select "**Add to PATH**".

![Add to PATH Image](/docs/images/ADD_TO_PATH.png)

### Installing FFmpeg

- [Windows Tutorial](https://windowsloop.com/install-ffmpeg-windows-10/)
- OSX - `brew install ffmpeg`
- Linux - `sudo apt install ffmpeg` or use your distros package manager
- Using spotDL - `spotdl --download-ffmpeg` - this will download FFmpeg to spotdl directory.

### Verifying Versions

`python -V` - Should return "Python 3.X.X". Please ensure you have v3.7 or greater.

`ffmpeg -version` - Should return starting with "ffmpeg version YYYY-MM-DD"

### Installing spotDL

You can install spotDL by opening a terminal and typing:

```shell
pip install spotdl
```

If you require further help, ask in our [Discord Server](https://discord.gg/xCa23pwJWY)

[![Discord Server](https://img.shields.io/discord/771628785447337985?color=7289da&label=DISCORD&style=for-the-badge)](https://discord.gg/xCa23pwJWY)

</details>


## Where does spotDL download songs?

spotDL downloads files to the folder where you ran spotDL from.

Open pwsh/powershell/cmd/terminal/similar in the folder you want files to download to, or
cd to desired folder.

**Windows Shortcut:** Navigate to the folder you want the files to download to.
`SHIFT + RIGHT CLICK`, then select "Open PowerShell window here"

![Windows PWSH](/docs/images/POWERSHELL.png)

## We have a public Discord server at **[discord.gg/xCa23pwJWY](https://discord.gg/xCa23pwJWY)!**

[![Discord Server](https://img.shields.io/discord/771628785447337985?color=7289da&label=DISCORD&style=for-the-badge)](https://discord.gg/xCa23pwJWY)