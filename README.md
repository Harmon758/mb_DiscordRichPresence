# Discord Rich Presence Plugin for MusicBee

This [MusicBee](http://getmusicbee.com) plugin shows your currently playing song as Rich Presence on [Discord](https://discordapp.com/)

![Example Screenshot](https://i.imgur.com/WzGCCPk.png)

## Requirements

- MusicBee v3.x (Untested on v2.x)
- Visual C++ Redistributable for Visual Studio 2015/7

## Installation

- Download the (non-source code) zip file from the [latest release](https://github.com/Harmon758/mb_DiscordRichPresence/releases/latest)

Either
- Load the plugin through MusicBee
  - Edit -> Preferences (Ctrl+O) -> Plugins -> Add Plugin -> Select the zip file

or
- Copy the DLL files to the Plugins folder
  - Extract the zip file
  - Copy the DLL files to the `MusicBee\Plugins` directory (most likely `C:\Program Files (x86)\MusicBee\Plugins` or `%appdata%\MusicBee\Plugins`)
  - Re/start MusicBee

## Usage

- Make sure you have MusicBee selected to be displayed as your Game Activity on Discord
  - User Settings -> Games -> Display currently running game as status message.
  - Add it! -> Select MusicBee
