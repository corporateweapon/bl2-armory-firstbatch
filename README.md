# Armory packs, first batch

**Not my assets, treat as such.** These packs contain models, textures and sounds
from other games (Counter-Strike 2 and Deadlock). Don't upload, re-host or share.

Six packs for the [Armory](https://github.com/corporateweapon/bl2-armory): four weapons and
two character skins. They're on the [Releases](../../releases) page.

## Install

1. Install the **Armory** first (its README has the steps and the troubleshooting table).
2. Download the packs you want from [Releases](../../releases).
3. For each zip: right-click → **Extract All...**, open the folder, double-click
   **`Install.bat`**. If Windows warns, click **More info → Run anyway** (or **Run**).
4. Start the game and wait for the title screen. **Mods → Armory → Packs** lists what
   loaded. Load a character and press **F5**, or use the console.

Restart the game after adding a pack: packs are read at startup.

| Download | What it adds | Spawn command |
|---|---|---|
| `ArmoryPack-ak47-1.0.0.zip` | **AK-47** assault rifle | `armory spawn ak47` |
| `ArmoryPack-awp-1.0.0.zip` | **AWP** sniper rifle (custom fire sound) | `armory spawn awp` |
| `ArmoryPack-deagle-1.0.0.zip` | **Desert Eagle** pistol (custom fire sound) | `armory spawn deagle` |
| `ArmoryPack-busted_flush-1.0.0.zip` | **The Busted Flush**, Shiv's shotgun (details below) | `armory spawn shiv` |
| `ArmoryPack-mina-1.0.0.zip` | **Mina** (Deadlock) skin for **Gaige** | none: worn automatically |
| `ArmoryPack-ct_sas-1.0.0.zip` | **CS2 SAS (CT)** skin for **Krieg** | none: worn automatically |

**The Busted Flush:** no aim-down-sights. Left click fires one shell. Right click fires a
2-round blast for 3× damage, with heavy recoil and a small knockback. Hits, blasts and kills
build **Rage** (the red meter). At 100% you move faster and deal 25% more damage. Rage drains
after 10 seconds without action.

Skins are worn as soon as you load Gaige or Krieg. Switch them under
**Mods → Armory → Characters**.

## Uninstall

Double-click the pack's **`Uninstall.bat`** and type **Y**. It removes exactly the files that
pack added. Load a save without a pack and its weapons lose their parts until the pack is
back, so uninstall before you delete anything else.

## Reporting a problem

Run `armory packs` in the console (`~`). It names the pack and the reason it didn't load.
Send that line, the installer's output and `Borderlands 2\sdk_mods\Armory\logs\`.
