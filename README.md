# Re-Shadowverse
 
**Re-Shadowverse** is an unofficial, independently developed fan project dedicated to bringing back the original *Shadowverse* after the end of its official service.
 
By using the original Steam and DMM game clients with a community-operated server, this project aims to recreate the Shadowverse experience we all remember.
 
## About the Project
 
Do you remember a game called Shadowverse?
 
Over its ten-year history, everyone who played it probably has a deck or card they'll never forget. For better or worse.
 
Some of you lost your entire family to Neutral Blood. Others were absolutely demolished by Elana Haven.
 
Some were torn apart by Roach, while others were forced to sit through endless Dimension Shift solitaire.
 
Some got beaten into oblivion by Bayleon, watched Bahamut wipe away everything they'd worked for, or got run over by Eachtar.
 
And some of you were finished off by Artifacts and a certain little dog.
 
Despite all the salt, there were players who kept climbing Ranked, competing in Grand Prix events, and challenging themselves at RAGE tournaments.
 
There were also those brave souls who fell in love with absolutely terrible cards and somehow tried to make them work in Unranked.
 
We raged at ridiculous plays, endured toxic opponents spamming emotes, and trembled at the absolute lawlessness of Unlimited.
 
We called it a trash game. Again and again.
 
**And yet, we kept playing for ten whole years.**
 
Then Shadowverse: Worlds Beyond arrived, and little by little, we started moving on...
 
**...But are you really sure there's nothing left you wanted to do?**
 
That deck you never got to build because you didn't have enough vials.
 
That theoretically Tier GOD Artifact Portalcraft deck running three copies each of Acceleratium and Augmentation Bestowal.
 
Cross Craft with every card available.
 
Resurgent Cards combined with cards from years past.
 
What if you could do more than simply relive the old Shadowverse?
 
**What if you could finally build the decks you always dreamed of?**
 
That's why I created Re-Shadowverse.
 
Of course, the project is still fighting an ongoing war against bugs.
 
Development is far from finished, so if you encounter any issues, please let me know.
 
## Features
 
- Recreates the original Shadowverse game environment
- Supports online multiplayer (Unranked Matches and Private Matches)
- Supports Custom Rotation, Unlimited, and Cross Craft
- Preserves the original gameplay and features as much as possible
- Completely free to play
## Installation
 
Extract the downloaded ZIP file to any folder of your choice.
 
For example:
 
```text
C:\Re-Shadowverse\
```
 
After extracting the files, run `Re-Shadowverse.exe`.
 
On the first launch, the launcher will perform the necessary setup and check for existing game files.
 
**Note:** You must already have a legitimately obtained copy of the original Shadowverse Steam or DMM game client.
 
**Note:** Do not place the launcher in a folder that requires administrator rights to write to, such as Program Files. Automatic updates may not work there.
 
## How to Launch
 
1. Run `Re-Shadowverse.exe`.
2. Allow the launcher to complete the necessary setup.
3. Shadowverse will launch automatically.
4. Enjoy the game!
The launcher applies the necessary changes for connecting to the community server only when launching Shadowverse through Re-Shadowverse.
 
These temporary changes are no longer active after the game closes.
 
The original Steam or DMM installation files are not permanently modified.
 
## Updates
 
From version 1.0.0, `Re-Shadowverse.exe` updates itself automatically at launch.
 
The new version takes effect from the next launch. There is no need to download and replace the files manually.
 
## Language Settings
 
You can change the launcher's language by editing the `language` field in `config.json`.
 
**Japanese:**
 
```json
{
  "language": "ja"
}
```
 
**English:**
 
```json
{
  "language": "en"
}
```
 
The launcher currently officially supports:
 
- Japanese
- English
Additional languages may be considered in the future.
 
English is currently available only for the Steam version. The DMM version supports Japanese only.
 
With English selected, card names, abilities and other text appear in English, but some images and story content remain in Japanese.
 
## Supported Formats
 
Re-Shadowverse uses the following three main deck formats:
 
- **Custom Rotation**
- **Unlimited**
- **Cross Craft**
Throwback Rotation is not used as a standard deck format, as it does not align with the goals of this project.
 
## Multiplayer
 
Re-Shadowverse uses its own community server rather than the official Shadowverse servers.
 
During periods of low player activity, finding an opponent may take some time.
 
As the project is still under development, certain cards or unusual interactions may cause battles to behave incorrectly or fail to finish.
 
This is especially relevant to abilities involving hidden information, such as cards in a player's hand or deck. Departed Soultaker is one example of a card with interactions that still require further testing.
 
Keep the in-game option to encrypt communication turned off. Battles cannot connect while it is on.
 
### Resurgent Cards
 
Resurgent Cards can be included in decks alongside regular cards.
 
However, decks containing Resurgent Cards cannot currently be used in Unranked Matches.
 
To support interactions between older cards and their newer counterparts, the following pairs have been adjusted to recognize each other in certain card effects:
 
- **Naterran Great Tree / Naterran World Tree**
- **Rapid Fire / Hastening Conviction**
- **Repair Mode / Recovery**
These adjustments allow relevant card effects to count, target, or exclude both versions where applicable, while retaining their individual identities and behavior.
 
### Bug Reports
 
If you encounter a bug, please provide as much of the following information as possible:
 
- **Approximate time of the match:** For example, November 15 at around 11:40 PM (JST).
- **Match type:** Private Match, Unranked Match, or CPU Battle. For Private Matches, include the room number if available.
- **Players involved:** The two players participating in the match.
- **Turn number:** Approximately when the issue occurred.
- **Cards involved:** Cards played during the affected turn and the previous turn.
- **What happened:** Describe the unexpected behavior and what should have happened instead.
- **Differences between players:** If possible, explain what appeared differently on each player's screen.
- **Screenshots:** If available.
The more details you provide, the easier it will be to investigate and fix the issue.
 
Please avoid including passwords, authentication tokens, or other sensitive information in public bug reports.
 
## Donations
 
**Re-Shadowverse is completely free to play.**
 
Donations do not affect access to features, updates, online matches, or any other part of the game.
 
There are no donor-exclusive features, in-game rewards, priority connections, or gameplay advantages.
 
Running the community server and maintaining the necessary infrastructure involves ongoing costs.
 
For this reason, voluntary donations may be accepted from people who wish to support the project's operation.
 
Donations are entirely optional.
 
If sufficient funds have been collected to cover operating expenses, donations may be temporarily suspended.
 
## Important Information
 
Re-Shadowverse is an unofficial fan project.
 
It is not affiliated with, endorsed by, or associated with Cygames, Inc. or the official Shadowverse development and operations teams.
 
All rights to Shadowverse-related names, characters, artwork, audio, and other intellectual property belong to their respective owners.
 
Re-Shadowverse was created to preserve the experience of the original Shadowverse and provide a way for its former players to enjoy the game again after the official service ended.
 
## Disclaimer
 
**This project is still under active development.**
 
As a result, you may encounter issues such as:
 
- Games failing to progress normally
- Synchronization problems during multiplayer battles
- Certain features being unavailable or incomplete
- Changes in behavior after updates
Please back up any important data before using the launcher.
 
The project is provided as-is, without any guarantee of uninterrupted availability or error-free operation.
