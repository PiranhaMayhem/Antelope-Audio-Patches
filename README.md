# Antelope-Audio-Patches
Original Discrete 8 control panel application patch.


This is a patch made for the original Discrete 8 interface. 

It's function is to restore the development disabled grid matrix routing system that products like the orion studio and discrete 8 synergy core use today.
No only can you route in a new visual, it also unlocks fully routing flexibility that the vanilla discrete 8 experience did not provide.
With this you can now have
-Routing AFX outputs through analog outputs.
-Independent mix sources for each of the 4 mixCh.
-Optional pop out window for the routing table.

Mixers now have more flexibility being able to have independent sources for each mix rather than all 4 mixes' sources being linked.

AFX is now built into the CP window rather than a pop out. An option pop out button is available.

This project was entirely vibe coded with Claude.

This patch does not include any of Antelope Audio's original source code.
You must have your own copy of Discrete 8 Control Panel 1.9.2 to use this.


## Install

**You need:** an original Antelope Discrete 8 and the Discrete 8 Control Panel **1.9.10**
(installed by the Antelope Launcher).

1. **Download** `D8-Patch-v4.zip` from the [Releases](../../releases) page (under *Assets*).
2. **Unzip it.** Double-click the zip in your Downloads folder. You should get a folder
   called `D8-Patch-v4`. (Safari may unzip it for you automatically.)
3. **Quit** the Discrete 8 Control Panel and the Antelope Launcher.
4. **Open Terminal.** Press `Cmd + Space`, type `Terminal`, press Return.
5. **Run the installer.** Copy this line, paste it into Terminal and press Return:

   ```
   bash ~/Downloads/D8-Patch-v4/"Install D8 Patch.command"
   ```

   *If you unzipped it somewhere else:* type `bash ` (with a space after it), drag
   `Install D8 Patch.command` from Finder into the Terminal window, then press Return.

6. Wait for **Done**, then press Return to finish. Open the Discrete 8 panel as usual.

Before changing anything, the installer saves a copy of your panel to your Desktop
(`discrete8_unpatched.app`). It only patches Control Panel 1.9.10; on any other version
it changes nothing.

## Uninstall

1. Quit the Discrete 8 Control Panel.
2. In Terminal, run:

   ```
   bash ~/Downloads/D8-Patch-v4/"Uninstall D8 Patch.command"
   ```

Your original panel is restored.

## Disclaimer

This is an unofficial, fan-made patch. It is not made, supported or approved by
Antelope Audio. Use it at your own risk.
