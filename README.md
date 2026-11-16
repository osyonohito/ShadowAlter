[English](README.md) | [日本語](README-ja.md)

ShadowAlter

ShadowAlter is an unofficial, independently developed fan project dedicated to bringing back the original Shadowverse after the end of its official service.

By using the original Steam and DMM game clients with a community-operated server, this project aims to recreate the Shadowverse experience we all remember.

About the Project

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

And yet, we kept playing for ten whole years.

Then Shadowverse: Worlds Beyond arrived, and little by little, we started moving on...

...But are you really sure there's nothing left you wanted to do?

That deck you never got to build because you didn't have enough vials.

That theoretically Tier GOD Artifact Portalcraft deck running three copies each of Acceleratium and Augmentation Bestowal.

Cross Craft with every card available.

Resurgent Cards combined with cards from years past.

What if you could do more than simply relive the old Shadowverse?

What if you could finally build the decks you always dreamed of?

That's why I created ShadowAlter.

Of course, the project is still fighting an ongoing war against bugs.

Development is far from finished, so if you encounter any issues, please let me know.

Features
Recreates the original Shadowverse game environment
Supports online multiplayer (Unranked Matches and Private Matches)
Supports Custom Rotation, Unlimited, and Cross Craft
Preserves the original gameplay and features as much as possible
Completely free to play
Installation

Extract the downloaded ZIP file to any folder of your choice.

For example:

text
C:\ShadowAlter\

After extracting the files, run ShadowAlter.exe.

On the first launch, the launcher performs the necessary setup and checks your game files.

Note: You must already have a legitimately obtained copy of the original Shadowverse Steam or DMM game client.

Note: Do not place ShadowAlter in a folder that requires administrator rights to write to, such as Program Files. Game data setup and automatic updates may not work there.

How to Launch
Run ShadowAlter.exe.
Wait for the launcher to finish its setup.
Shadowverse starts automatically.
Play as usual.

Note: If you start Shadowverse directly from Steam or DMM, it tries to reach the retired official servers and cannot be played. Always launch it through ShadowAlter.exe.

Updates

When a new version is released, ShadowAlter.exe updates itself automatically at launch.

The update takes effect from the next launch. There is no need to replace any files manually.

Language Settings

You can change the language by editing the language field in config.json.

Japanese:

json
{
  "language": "ja"
}

English:

json
{
  "language": "en"
}

The following languages are currently supported:

Japanese
English

English is available only for the Steam version. The DMM version supports Japanese only.

With English selected, card names, abilities and other text appear in English, but some images and story content may remain in Japanese.

Other languages are not supported.

Supported Formats

ShadowAlter uses the following three main deck formats:

Custom Rotation
Unlimited
Cross Craft

Throwback Rotation is not used as a standard deck format, as it does not align with the goals of this project.

Multiplayer

ShadowAlter uses its own community server rather than the official Shadowverse servers.

During periods of low player activity, finding an opponent may take some time.

As the project is still under development, certain cards or unusual interactions may cause battles to behave incorrectly or fail to finish. This mostly involves abilities that depend on hidden information, such as cards in a player's hand or deck (for example, Departed Soultaker).

Keep the in-game option to encrypt communication turned off. Battles cannot connect while it is on.

Resurgent Cards

Resurgent Cards can be included in decks alongside regular cards. However, they cannot be used in Unranked Matches.

To let older cards and their newer counterparts work together, the following pairs are treated as the same card by certain card effects:

Naterran Great Tree / Naterran World Tree
Rapid Fire / Hastening Conviction
Repair Mode / Recovery

Effects that count, target, or exclude one of them apply to both. Each card keeps its own name and behavior.

Bug Reports

If you encounter a bug, please include as much of the following as possible:

Approximate time of the match: For example, November 15 at around 11:40 PM (JST).
Match type: Private Match, Unranked Match, or CPU Battle. For Private Matches, include the room number if available.
Players involved: The two players in the match.
Turn number: Approximately when the issue occurred.
Cards involved: Cards played during the affected turn and the previous turn.
What happened: The unexpected behavior and what should have happened instead.
Differences between players: What appeared differently on each player's screen, if known.
Screenshots: If available.

Please do not include passwords, authentication tokens, or other sensitive information in your report.

Suggestions and requests are also welcome.

Note: I am Japanese, so it may take me some time to read messages in English.
Note: I may not be able to respond to every request, and responses may take some time.

Pricing

ShadowAlter is completely free.

The developer covers the server costs.

End of Service

The server may be shut down and distribution may end without notice in cases such as:

a removal or takedown request from a rights holder;
the server costs can no longer be covered;
any other circumstance that prevents the project from continuing.

Once the server is shut down, ShadowAlter, including online matches, can no longer be played. Data stored on the server, such as decks, may not be kept.

Other Information

ShadowAlter is an unofficial fan project.

It is not affiliated with, endorsed by, or associated with Cygames, Inc. or the official Shadowverse teams in any way.

All rights to Shadowverse-related names, images, audio, and other works belong to their respective owners.

ShadowAlter was created to preserve an environment where people who loved the original Shadowverse can keep enjoying it after the official service ended.

Disclaimer

This project is still under active development.

As a result, you may encounter issues such as:

Games failing to progress normally
Synchronization problems during multiplayer battles
Certain features being unavailable
Changes in behavior after updates
Contact

Please send an email to:

shadowalter.dev@gmail.com
