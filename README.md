# Siigil

A status bar for macOS 26 with [AeroSpace](https://github.com/nikitabobko/AeroSpace): Liquid Glass pills for your
workspaces with the icons of their windows, widgets (clock, battery, Wi-Fi, volume, Focus), and a pixel-art cat that
watches your AI agents (Claude Code, Codex) and shows your Claude and ChatGPT usage.

This repository only hosts the releases; the source code is private.

## Install

1. Download `Siigil-<version>.dmg` from the [latest release](https://github.com/p-diego/siigil-releases/releases/latest).
2. Open it and drag Siigil to Applications.
3. macOS blocks the first launch, because the app is signed but not notarized: open System Settings › Privacy &
   Security and click **Open Anyway**. You only do this once.
4. The Welcome window walks you through the rest: AeroSpace, Full Disk Access, Location (for the Wi-Fi name), the
   "Siigil DND" shortcut, and the Claude Code and Codex hooks.

Requirements: macOS 26 or later, and AeroSpace for the workspaces.

## Updates

From version 0.13, Siigil checks this repository once a day. When a new version is out, right-click the cat and
choose **Update to …**: Siigil downloads it, checks that it carries the same signature, replaces itself and restarts.
Your permissions stay. If the update can't be installed, the same menu item takes you here to download the DMG.

## License

Siigil is free to use, for personal or commercial purposes, but it is not open source: see [LICENSE](LICENSE).
Share it by linking to this page; please don't redistribute copies.

## Credits

- Cat sprites: [Catset Kittens](https://seethingswarm.itch.io/catset-kittens) by SeethingSwarm, used under their
  license. They are not redistributable on their own.
- Fonts: [mac's Minecraft](https://github.com/macimas/macsMinecraft) by macimas and
  [JetBrains Mono](https://github.com/JetBrains/JetBrainsMono), both under the SIL Open Font License 1.1.
- Meow: "Cat Meow 8 FX" by SOUND_GARAGE, [Pixabay Content License](https://pixabay.com/service/license-summary/).
- Theme colours: [Catppuccin](https://github.com/catppuccin/catppuccin), [Nord](https://github.com/nordtheme/nord),
  [Dracula](https://github.com/dracula/dracula-theme) and [Gruvbox](https://github.com/morhetz/gruvbox), MIT License.

The full license texts ship inside the app, in `Siigil.app/Contents/Resources/Licenses`, and the credits are in
Siigil › About Siigil.

Siigil is an independent project, not affiliated with or endorsed by Anthropic, OpenAI or the authors of AeroSpace.
