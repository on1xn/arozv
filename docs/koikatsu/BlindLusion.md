# BlindLusion.KK | Koikatsu Party Accessibility Mod by ON1XN

BlindLusion.KK is a screen-reader accessibility mod for **Koikatsu Party**. 

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

1. Download the mod here: [BlindLusion KK](https://tinyurl.com/2azudmxk) 
or download the version bundled with all requirement mods [BlindLusion KK With Require Mods](https://drive.google.com/drive/folders/1RCDqXn6liicToyHcL5NtD3p0V0GCe0E0?usp=sharing)
> FH patch still a hard requirement, if you downloaded the mod with bundled require mods.
2. Extract the archive, then copy the **contents** of the `BlindLusion.KK-0.34.1-public-beta` folder into the Koikatsu Party game folder.
3. Keep the included folder structure intact. The final paths should include:

   - `Koikatsu Party\BepInEx\plugins\BlindLusion\BlindLusion.KK.dll`
   - `Koikatsu Party\BepInEx\plugins\BlindLusion\Localization\en\...`
   - `Koikatsu Party\Tolk.dll`
   - `Koikatsu Party\nvdaControllerClient64.dll`

4. Start NVDA, then launch the game.

## Troubleshooting + Q&A

- When installing FH patch, you may got stuck at 97% for some reasons, please wait 15 minutes or a little longer. It's only slow.
- FH patch is hard requirement for story mode, although the mod is worked without patch. However you may have small H positions in Free-H mode to choose.
- FH patch, only require mods and important fixes are really important. The rest are optional and affect only visual purpose. And gameplay mod may conflict with my mod, install on your own risk.
- Character card is fully supported. If you're asking what you can install further.
- DLC is supported, and the game work without DLC as well.
- DLC included new 3 personalities and new dating location. If you're not a fan of DLC personalities, you don't lose anything.
- Wedding mode on DLC, I don't know about it yet. I'm not sure does it really worth for now.

## Current beta scope

- Accessible story mode, Settings, Extra (Free-H only), Character Maker, Story setup, classroom, card-loading, and Story free-roam.
- Structured Character Maker navigation, color editing/presets, card-information reading, and card summaries.
- Story dialogue, choices, tutorial handling, NPC/map navigation, conversations, save/load, and ambient subtitle speech.
- Free-H setup and H-scene controls: actions, positions, clothing, status, character summaries, subtitles, and Story H-result confirmation.
- After School DLC supported. (Although it's not 100% optimized yet.)

## Known issues and limitations

- In Story Mode, story characters are not currently trackable. Other NPCs can be dated normally and the core gameplay is playable.
- Story Mode's Look, Touch, and bathroom Peeping are not supported yet.
- Female Character Maker is the well-optimized Maker workflow. Although there are cursor jumps or trickly to navigate in certain categories, need to get used to. Male Character Maker is not yet well optimized.
- Character height in slider and final sumarization on card information is different. It's roughly 20 - 25CM., If you want your character height 170, you may need to adjust the slider until it said 190 for example. And rework on measurement again, because changing character height also affect body sizes too.
- Character saving is still clumcy, since I have no time to optimized it properly. You can try to mess around all arrow keys to take a photo, both Student ID and card ID. There's a save button after you took photo on your character. Sorry for unconvenience. However, it's 100% doable.
- Color names can be imprecise or unusual for some clothing, hair, and body-part colors, although the overall feedback is usable.
- Character summaries and the card reader can occasionally be inaccurate. They are still detailed enough to provide a useful overview though.
- Automatic walking to map exits/endpoints can get stuck more often than automatic walking to NPCs. Use Shift plus Enter to activate an endpoint. remote activation can work even when it reports a distance greater than 10–20 meters.
- Manual walking is not supported yet.
- H-scene caressing-method switching does not yet have dedicated hotkeys. Open the current action controls with Alt plus Q. Caressing items such as toys are not read yet.
- Although the game supports controllers in some areas, many modes are not optimized for the best controller screen-reader experience. Keyboard use is recommended.
- Result window from H scene in story mode is not support yet. But not affect gameplay.
- Tutorials in game are not well instruction. Read game's manual in the game folder and BlindLusion hotkeys instead.
- Free roam mode subtitle may not read properly at times.
- Live Concert and Wedding are not support for now. (Wedding is DLC's content)
- Minor issues remain, including occasional location-name/reporting problems. They should not prevent normal gameplay.

## Essential hotkeys

Normal menus use keyboard/controller navigation. BlindLusion provides semantic speech and Backspace/B-button back behavior where supported.

| Context | Keyboard | Controller |
|---|---|---|
| Story dialogue: next line | Enter | A |
| Story/free-roam BlindLusion menu | Tab | LB + X |
| Story: browse nearby NPCs/endpoints/objects | Page Up / Page Down; Shift + Page Up / Down changes group | See the in-game Hotkeys menu |
| Story: read selected target / description | Home / End | See the in-game Hotkeys menu |
| Story: walk / teleport to selected target | Shift + Home / Alt + Home | See the in-game Hotkeys menu |
| H scene controls | Tab | LB + X |
| H scene: current action / scene position / clothing | Q / W / E | Listed in the H-scene Hotkeys tab |
| H scene: character / clothing description | D / C; Shift modifier for second female | Listed in the H-scene Hotkeys tab |
| H scene: read gauge / animation / mode | S / F / V | Listed in the H-scene Hotkeys tab |
| H-scene result screen | Enter | A |
| Subtitle/dialogue review | `[` previous, `]` next; Shift jumps first/latest | LB + D-pad Left / Right where supported |

The in-game **BlindLusion Hotkeys** tabs are the authoritative, context-sensitive reference. They account for modes and controls that are only available in a particular scene.

## And I want to be honest with you

Since I don't live in a country where money comes easily, and this project requires both front-tier AI models and local models, including my energy to review the code by my self + extra manual workflow, your support is crucial. 
I have already completed over 90% of it, asking for support for this project is a very small favor to truly call it fully playable. (And it's not that much as you thought)

Every bit of support is a collective effort to make this project and future ones succeed, acting more as a donation or crowdfunding. No paywall, early access or pay for beta test at all.

Of course, it is only optional. It's just that bug fixes moving forward will be very slow, or non-existent, if they exceed my own programming skills. Besides, I am already quite happy with what the mod can currently do.

## Support The Project

- Buy me a Cup of Cola: [Ko-FI](https://ko-fi.com/on1xn)
- Monthly Junk Food: [Patreon](https://patreon.com/on1xn)
