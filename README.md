# If Where Is Deserted

**A dystopian tarot deck-building roguelike — playable PC prototype.**

Play as a resistance leader exploring palaces ruled by twelve Archons. Build your deck, acquire items, and confront the systems of power that hold society in place.

This demo focuses on **Palace XII and its ruler, Nolan Oliver**. It adapts part of my original fictional world, combining its characters and political conflicts with tarot and Western esoteric imagery developed specifically for the game.

## Gameplay

Choose a companion, explore rooms, fight enemies, and use rewards to develop your deck before confronting the palace boss.

- **Tarot orientations:** Cards have upright and reversed effects. Choose the face that best fits your current hand and situation.
- **Card burning:** Some effects burn a card face, changing which options remain available during the battle.
- **Four Elements:** Earth, Air, Water, and Fire interact through attacks and defensive effects. Elemental reactions can alter damage, costs, shields, and status effects.
- **Deck building:** Add cards through rewards and events, then combine their effects into stronger strategies.
- **Enemy intentions:** Read the enemy's next action before deciding how to spend your energy.
- **Items:** Use collected items to support your run. Hover over them to read their effects.

The intended experience moves between narrow survival and powerful combinations: recover from difficult draws, manage limited resources, and find opportunities to turn a fight around.

## Narrative and Visual Design

The larger setting contains twelve Archons and their respective systems of control. This prototype explores one part of that setting through encounters, character relationships, and short events rather than a continuous narrative.

Enemy mechanics express their roles in the world. Some restrict the player's actions, while others rewrite cards or interfere with elemental reactions. Nolan's boss mechanics use the rules of combat to express his relationship with the protagonist.

The game's original 2D artwork includes characters, creatures, environments, cards, and UI assets.

## Demo Scope

| Included in this prototype | Planned / not implemented |
| --- | --- |
| Companion selection | Companion bonuses |
| Seven exploration stages before the boss | The other eleven palaces |
| Door-based room selection | Divination room |
| Turn-based battles and card rewards | Forge room |
| Five narrative events | Shop |
| Collectible and usable items | Further content and balance revisions |
| Palace XII boss encounter | |

Companion selection is available, but companion bonuses are not implemented. Some event illustrations and UI assets are unfinished.

## Controls

The game is designed for **mouse input on PC**.

| Action | Control |
| --- | --- |
| Enter a normal room | Click its battle or event icon |
| Enter the boss encounter | Click the boss entrance door |
| Read card keywords, item effects, or status details | Hover over the relevant card or icon |
| Choose a card | Left-click the card |
| Switch card orientation | Click the upright/reversed control |
| Choose an enemy | Left-click the enemy when a target is required |
| Play the selected card | Click **Play** |
| Finish your turn | Click **End Turn** |
| View your run deck | Click the deck button |
| Change language | Use the language button |

When only one enemy remains, single-target attacks automatically target it. With multiple enemies, select a target when prompted.

After battle, gold and item rewards can be claimed or skipped. Card rewards are presented separately.

Red damage numbers show **actual HP lost after protection is applied**, not the incoming attack value. Fully blocked hits do not display a damage number.

## Playing a Windows Build

1. Download the demo ZIP provided with the release.
2. Extract the **entire archive** to a folder.
3. Run the game's `.exe` file.

Keep the executable, its accompanying `_Data` folder, and the other included files together. Do not run the game directly from inside the ZIP or move only the executable.

A source-code download is not a playable build. If no compiled demo has been attached yet, use the Unity instructions below.

## Opening the Source Project

If this repository includes the Unity project:

1. Install **Unity Hub** and **Unity 6000.3.13f1**.
2. Add the project folder containing `Assets`, `Packages`, and `ProjectSettings` to Unity Hub.
3. Open the project and wait for Unity to import its assets and resolve packages.
4. Open `StartScene` and enter Play Mode.

The project uses **Unity and C#**. Artwork was created in **Photoshop**.

## Development and Credits

This is a solo personal project created as part of my game-design portfolio.

My work includes:

- Game concept and original worldbuilding
- Combat systems, card design, and encounter design
- Narrative and character design
- Original 2D artwork
- Unity scene and UI integration
- Playtesting and iteration

**AI assistance was used for C# implementation and debugging.** Game design, narrative direction, and original artwork are my own.

## Prototype Notes and Feedback

This is a work-in-progress prototype, not a finished commercial release. Balance, localization, and UI presentation may still need refinement.

Early playtesting identified a steep learning curve: players need to read substantial text to understand the card keywords and elemental rules. Improving onboarding remains an area for future work.

If you report a bug, please include:

- The demo version and selected language
- The room or enemy involved
- Steps leading to the problem
- What you expected and what happened instead
- A screenshot, if possible

Thank you for playing and sharing feedback.
