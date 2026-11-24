# ShadowAlter

[English](README.md) | [日本語](README-ja.md)

## Download

[Download ShadowAlter](https://github.com/osyonohito/ShadowAlter/releases/latest)

ShadowAlter is an unofficial, independently developed fan project that aims to make the original Shadowverse playable again after the end of its official service.

It uses the original Steam or DMM game client with a community-operated server.

**This project is still under development.** Some features and card interactions may not work correctly.

## Current Features

- CPU battles
- Online multiplayer (Unranked Matches and Private Matches)
- Custom Rotation, Unlimited, and Cross Craft
- Japanese and English support (English requires the Steam version)
- Resurgent Cards (with some restrictions)
- collab CPU battles (Quests)
- Most nerfed cards restored to their pre-nerf versions

Certain card abilities and interactions may cause errors or synchronization issues during battles.

## Installation

1. Download the latest ZIP from [Releases](https://github.com/osyonohito/ShadowAlter/releases).
2. Extract it to a folder of your choice.
3. Run `ShadowAlter.exe`.

The first launch will prepare the necessary game data.

You need a legitimately obtained copy of the original Shadowverse Steam or DMM game client.

**Important Notes**
- Do not extract the launcher to a protected folder such as `Program Files`.
- Always start the game through `ShadowAlter.exe`.
- Keep the in-game communication encryption option turned off.
- Decks containing Resurgent Cards cannot be used in Unranked Matches.

## Bug Reports & Contact

If you encounter a bug, please include details such as the cards involved, approximate match time, and what went wrong.

Suggestions and feedback are also welcome, although I may not be able to respond to every request.

As I am Japanese, responses to English messages may take some time.

Contact: shadowalter.dev@gmail.com

## Additional Information

- ShadowAlter is completely free.
- Server costs are covered by the developer.
- The project is under active development, and stable operation is not guaranteed.
- The service may be discontinued without prior notice.

ShadowAlter is not affiliated with or endorsed by Cygames, Inc. or the official Shadowverse team.

All rights to Shadowverse-related intellectual property belong to their respective owners.

## Special Thanks

The following community projects have been valuable references during the development of ShadowAlter.

- [SVSimServer](https://github.com/SVSimOrg/SVSimServer)
- [OpenVerse](https://github.com/Atamol/OpenVerse)
- [Shadowbus](https://github.com/AraragiHoozuki/Shadowbus)

Many thanks to the developers working to bring back the original Shadowverse.

## Changelog

### 1.0.6 (2026/11/24)
- Game data updated on the server (card descriptions, images, etc.) is now downloaded automatically when the launcher starts

### 1.0.5 (2026/11/24)
- Card data is now checked against the server at startup and updated automatically (needed for the nerf reverts)
- The launcher now updates itself before checking the server

### 1.0.4 (2026/11/24)
- Fixed: on the global Steam version, quest opponents from the 9th onward can now be selected

### 1.0.3 (2026/11/22)
- Collab CPU battles (Quests) are now available
- Fixed: quest opponents from the 9th onward can now be selected (Steam / DMM)

### 1.0.2
- I thought this version already existed, so I skipped it. I am a fool.

### 1.0.1 (2026/11/19)
- Switched to connecting through our own domain. The launcher no longer modifies Windows settings (hosts file / certificates) and no longer needs administrator rights
- Added support for the global Steam version

### 1.0.0 (2026/11/16)
- Initial release
