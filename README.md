# GBWallpaper - Gameboy Emulator as windows wallpaper
[![GitHub release](https://img.shields.io/github/release/rocksdanister/GBWallpaper/all.svg)](https://github.com/rocksdanister/GBWallpaper/releases)
[![Github all releases](https://img.shields.io/github/downloads/rocksdanister/GBWallpaper/total.svg)](https://github.com/rocksdanister/GBWallpaper/releases)

## Contents

- [About](#about)
- [Download](#download)
- [Features](#features)
- [Issues](#issues)
- [FAQ](#faq)
- [Attribution](#attribution)
- [Donation](#donation)

## About
![demo-gif](./resources/animation.gif?raw=true "demo")

Feeling bored with basic picture wallpapers? Want to play a quick game while all windows are minimzed? Well why not just run a full gameboy emulator as desktop wallpaper!

Don't want to play? then disable keyboard input & use Macro input, save sequence of moves & automatically play it back; Like an animated gif wallpaper.

Don't worry about performance overhead, it will pause when running fullscreen games or application.

## Download
##### Latest version: v0.1 (Windows 10 Only)
 - [`Gameboy Wallpaper.zip`][direct-win32]  
   _(SHA-256: 523a4a48f6010eb241383a0d6dacf6a3be3d34aafe057100968914cff00db809)_

[direct-win32]: https://github.com/rocksdanister/GBWallpaper/releases/download/v0.1/Gameboy.Wallpaper.zip

Unzip the file, select Start.exe to get started.

Save files & settings are stored in <username>\Saved Games\GBWallpaper.

## Features
![demo-gif2](./resources/animation2.gif?raw=true "demo2")

* Different layouts styles.
* Emulator will pause when running fullscreen application or games (~0% cpu & gpu usage).
* Sound & keyboard input will get disabled when not on desktop, game will continue to run.
* Audio Visualiser for running games.
* Runs at system startup (optional).
* Macro input, save sequence of moves & automatically play it back; Like an animated gif wallpaper.
* Keyboard input & audio can be disabled.
* Save works for supported games.

### What is planned for future release
* Multimonitor system support.
* Currently using unity-gb emulator, might switch it with a better one.
* Better pause algorithm that works in various situations.
* More macro input options.
* Bug fixes.

## Issues
* SUPER MARIOLAND crash in menuscreen.
* Keyboard input sustaining if you hold and change window focus.
* Currently disabled on multimonitors systems due to bugs/further testing required.
* Certain applications will interfere with window focus, will require user to click on desktop to give input.

## FAQ
### Who asked for this?
Saw the suggestion on discord chat, got intrigued; took me longer than expected to make. Is this useless? maybe. Did I waste my time? Possibly. It was a good learning experience & fun to make.

### High system usage?
The default style of blurred background is a bit expensive if you don't have dedicated graphics, just use different layout style such as "Simple". Regardless, when fullscreen application or game run it will goto ~0% usage.

### Not taking input?
Certain applications can interfere with focus, just click on desktop or taskbar to regain focus.

### Where is the source code?
I will update it later after cleanup & final update.

## Attribution

The following projects made this possible:

Unity-gb : https://github.com/KonsomeJona/unity-gb (MIT License)

Octokit.net : https://github.com/octokit/octokit.net (MIT License)

## Donation
[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/P5P1U8NQ)
