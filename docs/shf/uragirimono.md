# Uragirimono Project | SILENT HILL f Accessibility Mod By ON1XN



**Public Test v0.4.9**



You will probably understand the project name after playing the game.



You may understand the version number too—if you know how Japanese numbers can be read.



Uragirimono is an accessibility mod designed to make **SILENT HILL f** playable for blind and visually impaired players while preserving as much of the original gameplay, exploration, combat, atmosphere, and challenge as reasonably possible.



This is a **Public Test**, not a claim that every part of the game has been fully verified from beginning to end.



## About SILENT HILL f



SILENT HILL f is a third-person psychological horror game developed by NeoBards Entertainment and published by KONAMI. Set in 1960s Japan, it follows Shimizu Hinako through the isolated town of Ebisugaoka as she explores, solves puzzles, fights grotesque creatures, and experiences a story heavily influenced by Japanese culture, beliefs, imagery, and social context.



The game combines exploration, puzzle solving, melee combat, psychological horror, and multiple endings. Some understanding of its Japanese setting and themes may help when interpreting the story.



---



# Current Features



Uragirimono currently includes:



- Screen-reader accessibility through NVDA.

- Accessible native game menus and UI. (Options, load / save, journal, inventory, collectibles, document / etter, interactable objects contain text and so on.)

- Spoken menu navigation, selections, inventory information and item names.

- Accessible Quick Use Item management.

- Scanner for nearby objects, items, interactables, objectives and enemies.

- Scanner category browsing and object selection.

- Persistent object locking and position tracking.

- Direction and distance reporting.

- Player XYZ position reporting.

- Objective and quest-hint accessibility.

- Objective persistence even when no spatial XYZ target is available.

- Automatic objective updates and progression tracking.

- Spatial wall/navigation audio.

- Open-space/navigation assistance.

- Auto Walk toward selected targets.

- Teleport assistance.

- Automatic facing toward selected objects.

- Remote interaction and pickup assistance.

- Close-range interactable notification cue.

- Enemy positional audio.

- Enemy lock feedback.

- Enemy HP reporting.

- Incoming Attack audio warnings.

- Player HP, stamina and sanity reporting.

- Weapon selection and weapon durability reporting.

- Accessible item and weapon shortcut feedback.

- Story and progression assistance.

- Puzzle preparation and bypass assistance.

- Force Progress for progression blockers.

- Automatic bypass support for certain chase sequences that are impractical to navigate without sight.

- Uragirimono Menu with Story information and configurable accessibility sound cues.

- Individual accessibility sound-cue enable/disable, volume and preview controls.

- Automatic save backups when using potentially destructive progression assistance.



The intention is not to automate the entire game. Whenever practical, Uragirimono provides the information or navigation assistance necessary for the player to make their own decisions and play normally.



---



# Download And Installation

Download the mod here: [Uragirimono Project](https://drive.google.com/drive/folders/1H9rlDb49S9YgLbquQcQ_bnhLvRtxqTTA?usp=sharing)

Two packages are provided.


1. Download the **Uragirimono Bundled** or **Mod Only**

2. Open your SILENT HILL f installation directory.

3. Find the folder containing `SHf.exe`.

4. Extract or copy **the contents of the ZIP directly into this folder**.

5. Start the game normally.

6. Uragirimono should announce its name and version when loaded.


### UE4SS Compatibility Note



Uragirimono was developed and extensively tested against a newer development build of UE4SS.



Compatibility with the current public/stable UE4SS release cannot be guaranteed across every system or SILENT HILL f version.



The bundled release uses a normal non-development UE4SS build. If Uragirimono fails to initialize or behaves incorrectly with it, trying a recent UE4SS development build may help or report it to me.



---



# Known Issues and Public Test Limitations



### English Only in v0.4.9



Uragirimono's own interface, accessibility messages, descriptions, settings, and other mod-generated text are currently available in **English only**.



The localization infrastructure has already been implemented, and support for **all languages provided by SILENT HILL f is planned for the next update**.



This limitation applies to Uragirimono-generated text; it does not change the game's own language settings.



### Controller Required



Keyboard and mouse are currently unsupported by Uragirimono.



SILENT HILL f itself is primarily designed around controller play, and Uragirimono's accessibility controls and modifier system assume a controller.



### Puzzle Coverage



Puzzle accessibility is extensive but **not fully verified throughout the entire game yet**.



The following areas contain puzzle/content interactions that require additional public-test verification:



- **Chapter 2:** Torii Ema clue sequence.

- **Chapter 3:** Field Maze puzzle variants and Rinko House ornamented scarecrow.

- **Chapter 5:** School / Letter to Shu interaction.

- **Chapter 6:** Rinko-area Fox-flip gate sequence.



Some puzzles may already be playable normally despite lacking specialized accessibility handling.



Please report any puzzle that prevents progression.



### Auto Walk and Teleport



Auto Walk or Teleport may fail when the selected target is extremely close.



Auto Walk can also fail when:



- the target is behind a locked door;

- no valid navigable route is available;

- Hinako is standing in an unsuitable position;

- world geometry or progression state prevents reaching the target normally.



These systems are assistance tools rather than guaranteed pathfinding solutions.



### Chase Sequences



Certain story sequences require the player to escape from enemies while navigating quickly through the environment.



Some of these sequences are extremely difficult to navigate without sight—even sighted players may find them difficult. so Uragirimono may provide a forced bypass instead of requiring the original chase.



Because of this, **Steam achievements associated with bypassed sequences are not guaranteed**.



### Force Puzzle / Force Progress



`LB + Back` double press provides emergency Puzzle / Story Progress assistance.



This system is intended for situations where normal progression becomes inaccessible or blocked. It cannot be guaranteed to solve or bypass every puzzle or story state.



Use it carefully.



Uragirimono creates save backups for potentially destructive progression operations. Keep your own important saves as well, especially during the Public Test.



Steam achievement behavior is not guaranteed when Force Progress or Puzzle Bypass is used.



### Falling Hazards



Uragirimono currently does **not** provide comprehensive warnings for every ledge, hole or area from which Hinako can fall.



Move carefully in unfamiliar areas.



### Quick Use Items



The Quick Use Item interface is accessible and usable, but some spoken navigation/selection behavior may sound unusual compared with other menus.



### Game / UE4SS Updates



Game updates or UE4SS changes may break internal functionality.



Uragirimono attempts to avoid unnecessary version-specific assumptions, but compatibility with every past or future SILENT HILL f build cannot be guaranteed.



---



# Controller Controls



**Important:** Uragirimono modifies several of SILENT HILL f's default controller bindings.



The controls below describe the configuration expected by the mod.



## Xbox Controller — Game Controls



- **D-Pad Left / Right** — Change weapon

- **D-Pad Up** — Journal

- **D-Pad Down** — Inventory

- **Left Stick** — Move

- **Left Stick Click (LS)** — Toggle Walk / Run

- **Right Stick** — Camera

- **Right Stick Click (RS)** — Enemy lock

- **A** — Pick up / Check / Interact

- **B** — Dodge

- **X** — Enemy lock / lock-related native action

- **Y** — Change weapon

- **Back / View** — Open Quick Use Item menu

- **Start / Menu** — Pause menu

- **LT** — Focus

- **RB** — Light attack

- **RT** — Heavy attack



## Xbox Controller — Uragirimono Controls



**LB is Uragirimono's primary modifier key.**



- **LB single press** — Report currently locked target

- **LB double press** — Unlock current Uragirimono target

- **Hold LB** — Modifier for Uragirimono commands



### Scanner



- **LB + Right Stick Left / Right** — Change Scanner category

- **LB + Right Stick Up / Down** — Browse objects in current category

- **LB + Right Stick Click** — Read currently selected object



**Selected** and **Locked** are different states.



A **Selected** object is the object currently highlighted while browsing the Scanner.



A **Locked** object remains tracked after you stop browsing. Once an object is locked, pressing **LB** reports its current position/direction information again.



The following commands operate on the currently selected or last-touched Scanner target where applicable:



- **LB + A single press** — Turn Hinako toward selected target

- **LB + A double press** — Remote Interact / Pick Up

- **LB + B single press** — Auto Walk to target

- **LB + B double press** — Teleport to target

- **LB + X single press** — Turn around 180 degrees

- **LB + X double press** — Report weapon durability

- **LB + Y single press** — Report HP

- **LB + Y double press** — Report Sanity

- **LB + RB single press** — Report locked enemy HP

- **LB + RB double press** — Report Stamina

- **LB + LS Click** — Report current player XYZ position

- **LB + Back single press** — Open Uragirimono Menu

- **LB + Back double press** — Force Puzzle / Story Progress assistance



---



# PlayStation Controller — Game Controls



- **D-Pad Left / Right** — Change weapon

- **D-Pad Up** — Journal

- **D-Pad Down** — Inventory

- **Left Stick** — Move

- **L3** — Toggle Walk / Run

- **Right Stick** — Camera

- **R3** — Enemy lock

- **Cross** — Pick up / Check / Interact

- **Circle** — Dodge

- **Square** — Enemy lock / lock-related native action

- **Triangle** — Change weapon

- **Touchpad / equivalent Back input** — Open Quick Use Item menu

- **Options** — Pause menu

- **L2** — Focus

- **R1** — Light attack

- **R2** — Heavy attack



## PlayStation Controller — Uragirimono Controls



**L1 is Uragirimono's primary modifier key.**



- **L1 single press** — Report currently locked target

- **L1 double press** — Unlock current Uragirimono target

- **Hold L1** — Modifier for Uragirimono commands



### Scanner



- **L1 + Right Stick Left / Right** — Change Scanner category

- **L1 + Right Stick Up / Down** — Browse objects in current category

- **L1 + R3** — Read currently selected object



A **Selected** object is the current Scanner object.



A **Locked** object remains tracked independently of Scanner browsing. Press **L1** to report the locked object's position again.



Additional commands:



- **L1 + Cross single press** — Turn Hinako toward selected target

- **L1 + Cross double press** — Remote Interact / Pick Up

- **L1 + Circle single press** — Auto Walk to target

- **L1 + Circle double press** — Teleport to target

- **L1 + Square single press** — Turn around 180 degrees

- **L1 + Square double press** — Report weapon durability

- **L1 + Triangle single press** — Report HP

- **L1 + Triangle double press** — Report Sanity

- **L1 + R1 single press** — Report locked enemy HP

- **L1 + R1 double press** — Report Stamina

- **L1 + L3** — Report current player XYZ position

- **L1 + Touchpad / Back single press** — Open Uragirimono Menu

- **L1 + Touchpad / Back double press** — Force Puzzle / Story Progress assistance



---



# Uragirimono Menu



Press **LB + Back** on Xbox-style controllers or **L1 + Touchpad/Back** on PlayStation-style controllers to open the Uragirimono Menu.



Opening the menu pauses gameplay.



The menu currently contains:



### Story



Read-only information about the current story state, including available chapter, quest, objective and hint information.



### Settings



Configure individual Uragirimono accessibility sound cues.



Supported sound settings include:



- Enable / Disable

- Individual volume

- Preview sound



Settings use the same general interaction style as SILENT HILL f's native Options menus:



- **D-Pad Up / Down** — Navigate

- **D-Pad Left / Right** — Change values

- **A / Cross** — Activate or preview

- **B / Circle** — Back



---



# Public Test Feedback



This release exists specifically to discover situations that cannot be fully reproduced by one playthrough.



If you encounter:



- a progression blocker;

- an unreadable menu;

- a puzzle that cannot reasonably be completed;

- an Objective that becomes incorrect or disappears;

- an interactable that cannot be activated;

- Scanner targets that are incorrect;

- navigation failures;

- combat accessibility failures;

- crashes or unusual UE4SS behavior;



please report what happened and, when possible, include the Uragirimono diagnostic logs from the same gameplay session.



The most useful reports explain **where you were, what you were trying to do, what Uragirimono reported, and what happened instead**.



---



# 🤝 Contact And Support

* 💬 **Discord:** [Autonomous Republic of Zero-Vis](https://discord.gg/4xGg4gGW9a)
* 🥤 **Buy me a Cup of Cola:** [Ko-FI](https://ko-fi.com/on1xn)
* 🍔 **Buy me Monthly Junk Food:** [Patreon](https://patreon.com/on1xn)

---