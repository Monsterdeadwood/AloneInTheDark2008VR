> [!IMPORTANT]
> **[TEST BUILDS & DISCUSSION · FLAT2VR DISCORD](https://discord.gg/P4q9zt7ek)**
> Testing, build requests, feedback and discussion happen in the **Flat2VR Modding Discord**. Join the server and find the **Alone in the Dark 2008 VR** thread.

![Alone in the Dark 2008 VR — Monsterdeadwood VR mods](assets/vr-banner.svg)

# Alone in the Dark 2008 VR

[English](README.md) · [Русский](README_RU.md) · [Flat2VR Discord](https://discord.gg/P4q9zt7ek) · [All projects](PORTFOLIO.md)

![Project status](assets/vr-status.svg)

An experimental VR branch for the 2008 PC version of Alone in the Dark, focused on tracked held items, inventory access and the game’s original throw behavior.

**Current documented branch: R22 / Meta 2048 preview.**

## Installation

1. Get the **Alone in the Dark 2008 R22** test package in the game’s Flat2VR thread and use its supported PC game build.
2. Extract the complete package. Connect Quest Link or Air Link for this Meta-targeted preview.
3. Open **RUN.bat**. The R22 preview uses 2048×1152 per eye and a session limit of up to five minutes.
4. RUN.bat --check checks the package; RUN.bat --stop ends its session. Share the test logs in the game’s Discord thread.

Current test-package availability is coordinated in Discord. Use the complete package for your supported game build; this project page is separate from a release download.

## What this project brings to VR

- VR presentation and controller-aligned original held items in the test branch.
- Tested bottle, flashlight, lighter, spray can and pistol grips.
- Bottle-to-wall blocking and release when withdrawing the hand.
- Inventory toggle and the original aim/confirm throw interaction.

<details>
<summary><b>Controller quick reference</b></summary>

| Input | Action |
| --- | --- |
| Y | Open / close inventory |
| Right grip | Enter original throw aiming |
| Right stick while aiming | Choose the native throw target |
| Trigger of the item-holding hand | Confirm the original throw |

The complete package control sheet takes precedence for its version and interaction profile.

</details>

## Current status

**Bounded test preview.** Item grips, held-bottle wall contact and original throw routing were checked in the actual game with XR Sim/Tape.

- Physical Meta acceptance and a 72 FPS target are not established.
- Two-hand grips, empty-hand contact, rotation at walls, pushing and vibration need further validation.

[Detailed status and validation scope](docs/PROJECT_STATUS.md)

## Testing & feedback

Post in the game’s [Flat2VR thread](https://discord.gg/P4q9zt7ek) with your **mod version, game/store version, headset, OpenXR runtime, GPU, reproduction steps and the package’s diagnostic ZIP**. A short video is helpful for visual or handling problems.

## Other VR mods by Monsterdeadwood

| Game / project | Focus | Visibility |
| --- | --- | --- |
| [Assassin’s Creed VR](https://github.com/Monsterdeadwood/AC1VR) | First-person exploration, climbing and sword interaction | Private |
| [Crysis 2: VRevamp](https://github.com/Monsterdeadwood/C2VR) | Nanosuit combat, physical interaction and spatial UI | Public |
| [Star Wars: The Force Unleashed II VR](https://github.com/Monsterdeadwood/TFU2VR) | Dual lightsabers, independent telekinesis and Force powers | Public |
| [NOVA · CS:GO Legacy VR](https://github.com/Monsterdeadwood/CSGOVR) | CS:GO Legacy local matches with motion controls | Public |
| [TimeShift VR](https://github.com/Monsterdeadwood/TimeShiftVR) | Time powers, nine weapons and roomscale posture | Public |
| [You Are Empty: Absolute Edition VR](https://github.com/Monsterdeadwood/YouAreEmptyAEVR) | Absolute Edition VR, weapons and hand interaction | Public |
| [Rainbow Six Siege VR](https://github.com/Monsterdeadwood/SiegeVR) | Legacy Siege stereo and tracked weapon handling | Public |
| [Burnout Paradise Remastered VR](https://github.com/Monsterdeadwood/BUrnOutPvr) | Stereo driving, vehicle menus and native effects | Public |
| [Titanfall 1 VR](https://github.com/Monsterdeadwood/Titanfall1VR) | Pilot combat and Titan cockpit VR | Public |
| [Metro 2033 VR](https://github.com/Monsterdeadwood/Metro2033VR) | Original Metro VR and native physics experiments | Public |
| [Insurgency VR](https://github.com/Monsterdeadwood/InsurgencyVR) | Early VR integration research | Private |
| [Counter-Strike: Source VR](https://github.com/Monsterdeadwood/CSSVR) | Counter-Strike: Source VR development | Private |

Private repository links are available to invited collaborators. Public project pages are marked above.

## Credits & development notes

Project maintained by [Monsterdeadwood](https://github.com/Monsterdeadwood). This is an independent fan VR project; you need your own supported copy of the original game.

Documentation reviewed: **14 November 2026**.
