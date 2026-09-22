# BlindLusion.KK | Koikatsu Party Accessibility Mod by ON1XN

BlindLusion.KK is a screen-reader accessibility mod for **Koikatsu Party**.  And 100% playable.

## What is KoiKatsu and where to buy

Dive into the ultimate sandbox of virtual relationships and anime-style creativity with **Koikatsu** (also known as *Koikatsu Party*). At its core, this is an advanced anime character creation simulator and relationship-building sandbox developed by Illusion (and of course, sex simulator) Rather than following a rigid linear storyline, the game hands you total creative control over both the characters and the environment, letting you craft your dream anime scenario from scratch.

Here is what you can actually do in the game:

* **Unmatched Character Creation:** The game is legendary for its deep, highly detailed customization suite. You can tweak everything from facial features, hair styles, and eye shapes to body proportions, clothing layers, and distinct personality traits. If you can envision an anime character, you can almost certainly bring them to life here.
* **Open-Ended School Life & Socializing:** Step into a sprawling academy setting where you interact with a diverse cast of students and faculty. Build relationships through conversations, dates, and various events, influencing how characters respond to you based on their unique personalities and your choices.
* **Vibrant Modding Community:** The vanilla game is just the starting line. Thanks to an incredibly active global community, thousands of custom outfits, hair mods, plugins, and user-created character cards are freely available, expanding the game's limits almost infinitely.

If you're interested now, you can buy the game on [Steam](https://store.steampowered.com/app/1073440/__Koikatsu_Party/)

- **Warning 1:** This game is focus on Japanese adult content. And I know someone may not a fan of Japanese moaning, fancy unrealistic anime character or Japanese subculture. So better to warn you guys here, if you're looking for western themes.
- **Warning 2:** This mod only support Steam version. Japanese version from DMM (Name Koikatu) is not support. Including pirate game / repack base on Japanese version too. However, Steam version and DMM version are the same, you get all same contents.

## Requirements

Install these before BlindLusion.KK:

- [HF Patch](https://github.com/ManlyMarco/KK-HF_Patch/releases)  required. Download and install it with a torrent client. Its bundled prerequisite mods satisfy the remaining required mod dependencies, they do not need to be downloaded individually. But make sure during install FH patch, you select the require mods below.
- Important fixes
- BepInEx 5
- KK_GamepadSupport
- KKAPI
- KoikatsuTranslation / XUnity AutoTranslator
- KK_Subtitles
- KK_HeightBar
- Optional content like character cards and clothes (clothes description from 3rd party are not supported)
- Of course, NVDA

`Tolk.dll` and `nvdaControllerClient64.dll` are included in this archive. They belong in the **Koikatsu Party game root**, next to the game executable.

## Installation

* Download the mod here: [BlindLusion KK](https://drive.google.com/drive/folders/1RCDqXn6liicToyHcL5NtD3p0V0GCe0E0?usp=drive_link)

Download "Mod Only" if you update from previous version.

Download "With require mods bundled" if new install.

> FH patch still a hard requirement, if you choose with require mods bundled version.

* Extract the archive, then copy the **contents** of the `BlindLusion.KK` folder into the Koikatsu Party game folder.

* Keep the included folder structure intact. The final paths should include:

    `Koikatsu Party\BepInEx\plugins\BlindLusion\BlindLusion.KK.dll`

    `Koikatsu Party\BepInEx\plugins\BlindLusion\Localization\en\...`

    `Koikatsu Party\Tolk.dll`
    
    `Koikatsu Party\nvdaControllerClient64.dll`

* Start NVDA, then launch the game.

## Troubleshooting and Q&A

- If HF Patch appears stuck at 97%, leave the installer running for at least 15 minutes. This stage can be very slow.
- HF Patch is required for reliable Story Mode support. The game may start without it, but Free-H can have far fewer positions and other expected dependencies may be missing.
- In the HF Patch installer, the required mods and important fixes are essential. Most visual additions are optional. Extra gameplay plugins may conflict with BlindLusion, so install them at your own risk.
- Character cards and official DLC are supported. Third-party clothing can be used, but its appearance may not have a useful accessible description.
- If Tolk is silent, confirm that NVDA is running and that `Tolk.dll` and `nvdaControllerClient64.dll` are beside the game executable, not inside `BepInEx`.
- Keep the complete `BepInEx\plugins\BlindLusion\Localization\en` folder. Missing localization files cause unnamed or incomplete controls.
- Some Story dialogue transitions intentionally contain no spoken line. Keep pressing Enter, or A on a controller, to continue. This is how the game sequences those transitions; BlindLusion deliberately does not invent a message because doing so can cause duplicated or out-of-order dialogue.
- To save a Character Maker card, open the save window and take the **Student ID** first. Then select **Character Card** and take it. After both have been taken, select **Save**.

## Hotkeys

Normal menus use the Arrow keys and Enter, or the D-pad and A. Backspace or B returns to the previous accessible level. Escape remains the game's normal exit command.

### Character Maker

| Action | Keyboard | Controller |
|---|---|---|
| Open or close the BlindLusion guide | Tab | LB + X |
| Read the current character description | D | LB + Y |
| Read the current clothing description | C | LB + Right Bumper |
| Return or close the current layer | Backspace | B |

When saving a card: select **Student ID**, take the photo, select **Character Card**, take the second photo, then select **Save**.

### Story dialogue and free roam

| Action | Keyboard | Controller |
|---|---|---|
| Advance dialogue or choose the current response | Enter | A |
| Replay the last voice line | Shift + Space | Not assigned |
| Open or close the BlindLusion menu | Tab | LB + X |
| Change target group: NPCs, exits/doors, or events | Shift + Page Up / Page Down | LB + Right Stick Left / Right |
| Browse the current target group | Page Up / Page Down | LB + Right Stick Up / Down |
| Read the selected target | Home | LB + Left Stick click |
| Read the selected NPC description | End | LB + Right Stick click |
| Walk to the selected target | Shift + Home | LB + Right Bumper |
| Teleport near the selected target | Alt + Home | LB + B |
| Talk to or use a nearby target | Enter | A when offered by the game |
| Remotely interact with the selected NPC, exit, or event | G | LB + A |
| Use the selected map exit | Shift + Enter | LB + Y |
| Read current location / time | B / T | LB + D-pad Up / Down |
| Toggle standing or crouching | Z | Left Stick click |
| Previous / next dialogue or subtitle | `[` / `]` | LB + D-pad Left / Right |
| First / latest dialogue or subtitle | Shift + `[` / Shift + `]` | Not assigned |
| Open game settings / map / school roster | F1 / F3 / F4 | Not assigned |
| Advance to the next time period | F8 or Alt + T | Not assigned |

Some Story transitions are silent. Continue with Enter or A; this is expected and avoids unreliable duplicate dialogue.

### H scenes and Free-H

These shortcuts operate while the BlindLusion H menu is closed unless stated otherwise.

| Action | Keyboard | Controller |
|---|---|---|
| Open or close BlindLusion H controls | Tab | LB + X |
| Open current action group / Actions tab / current action controls | Q / Shift + Q / Left Alt + Q | LB + Right Bumper opens the current group |
| Open scene-position selection | W | LB + Right Stick click |
| Open first / second female clothing controls | E / Shift + E | LB + Left Trigger opens the first |
| Read first / second female character description | D / Shift + D | LB + Left Stick click reads the first |
| Read first / second female clothing description | C / Shift + C | LB + B reads the first |
| Read gauges | S | LB + D-pad Up |
| Lock both / female / other gauges | Shift + S / Left Alt + S / Control + Shift + S | Controller quick settings are available with LB + Back |
| Read animation / action mode / location / time | F / V / B / T | LB + Y reads animation; LB + D-pad Down reads mode |
| Begin normal / anal insertion | A / Shift + A | LB + A / LB + Right Trigger |
| Finish inside, or come inside during Service actions | I, Right Control, or Numpad 1 | Right Bumper |
| Finish outside | O, Right Alt, or Numpad 3 | Right Stick click |
| Toggle partner taking the lead during Service actions | Left Control or Numpad 5 | Y |
| Increase / decrease movement or Service action speed | Up / Down, or Numpad 7 / 2 | D-pad Up / Down |
| Read penetration speed | X | Not assigned |
| Switch slow / fast penetration loop | Left Alt or Numpad 6 | X |
| Manual / automatic penetration movement | Z / Shift + Z | Y toggles mode |
| Lock automatic movement while inserted | Control + Shift + Z | Not assigned |
| Withdraw | Left Alt + Z or Numpad 4 | LB + Right Bumper + B |
| Caring: choose target | Left / Right | D-pad Left / Right |
| Caring: choose method | Left Control + Left / Right | Left Trigger + D-pad Left / Right |
| Caring: perform or speed up / slow down | Up / Down | D-pad Up / Down |
| Caring: target genitals / anus | A / Shift + A | LB + A / LB + Right Trigger |
| Read caring speed | Shift + X | Not assigned |
| Toggle H-scene music | Shift + M | Available in H settings |
| Previous / next subtitle | `[` / `]` | LB + D-pad Left / Right |
| First / latest subtitle | Shift + `[` / Shift + `]` | Not assigned |
| Return to the previous accessible group | Backspace | B |

The in-game **BlindLusion Hotkeys** groups are the authoritative context-sensitive reference. A command may be silent when the current animation does not expose the corresponding native action.

## Support The Project

Of course, it is only optional. It's just that bug fixes moving forward will be very slow, or non-existent, if they exceed my own programming skills. Besides, I am already quite happy with what the mod can currently do. And it's 100% playable for me, we probably no need to implement more features only serious bugs if there are any.

* 💬 **Discord:** [Autonomous Republic of Zero-Vis](https://discord.gg/4xGg4gGW9a))
* 🥤 **Buy me a Cup of Cola:** [Ko-FI](https://ko-fi.com/on1xn)
* 🍔 **Buy me Monthly Junk Food:** [Patreon](https://patreon.com/on1xn)

---