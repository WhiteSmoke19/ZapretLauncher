# Convenient Work with zapret

This project is part of an initiative to create simple and understandable tools for working with `zapret` on Windows.

The main goal is to remove unnecessary manual routine around launching, configuring, and maintaining `zapret`: working with `.bat` files, manually choosing strategies, constantly opening folders, editing lists through Notepad, and checking for updates by hand.

I do not develop the original `zapret` project and do not claim authorship of the original source. My goal is to make existing open-source solutions more convenient for regular users.

## What This Project May Include

This direction may include different helper tools:

- graphical launchers;
- strategy managers;
- user list editors;
- update utilities;
- simple diagnostic tools;
- instructions and ready-to-use builds for easier launch;
- additional wrappers around existing solutions.

The first tool in this line is a Windows GUI launcher for `Flowseal/zapret-discord-youtube`.

## Why This Is Needed

The original `zapret` tools are powerful, but the entry barrier remains high for many users:

- users need to understand which `.bat` file to run;
- users need to manually try different strategies;
- the terminal window looks unfamiliar and gets in the way;
- user lists have to be edited directly in files;
- updates have to be searched for manually;
- the current working status is not always obvious.

This initiative focuses specifically on the user layer: it does not change the bypass technology itself, but makes managing it easier.

## Project Principles

- Do not hide original sources and authors.
- Do not present someone else's work as your own.
- Link to the original GitHub repositories.
- Preserve license information.
- Do not overload the computer with background processes.
- Do not write unnecessary logs to disk.
- Make the interface understandable without long instructions.
- Leave control to the user: launch, stop, update, and list management should be explicit and accessible.

## Current Tool: Zapret Launcher

Zapret Launcher is a graphical Windows wrapper that simplifies launching strategies from `Flowseal/zapret-discord-youtube`.

Features:

- strategy selection from a list;
- launch without a visible terminal window;
- system tray status;
- stopping `winws.exe`;
- payload updates from GitHub;
- user list editing;
- preserving user lists during updates;
- built-in license window with links to original sources.

## Original Sources

The main projects this work is based on:

`Flowseal/zapret-discord-youtube`  
https://github.com/Flowseal/zapret-discord-youtube

`bol-van/zapret`  
https://github.com/bol-van/zapret

`basil00/WinDivert`  
https://github.com/basil00/WinDivert

## Original Authors

The `Flowseal/zapret-discord-youtube` license states:

```txt
Copyright (c) 2016-2026 bol-van
Copyright (c) 2024-2026 Flowseal
```

The original `zapret` project was developed by `bol-van`.

`Flowseal/zapret-discord-youtube` is a separate Windows build, strategy set, and script collection for convenient use.

## Licenses

`Flowseal/zapret-discord-youtube` is distributed under the MIT License.

WinDivert is distributed under LGPLv3 or GPLv2.

When distributing any tools from this initiative, it is important to preserve:

- links to original sources;
- author information;
- license notices;
- information about third-party components.

## Plans

Possible future development areas:

- a unified strategy manager;
- more convenient conflict diagnostics;
- autostart of the selected strategy with Windows;
- import and export of user lists;
- integrity checking for downloaded payloads;
- clearer error descriptions;
- separate instructions for different usage scenarios.

## Disclaimer

This project is a helper wrapper and a set of user experience improvements. It is not an official project of `zapret`, `Flowseal`, or WinDivert.

Use the program consciously and verify which binary files you are running. For payloads and updates, it is recommended to use only official GitHub Releases from the original sources.
