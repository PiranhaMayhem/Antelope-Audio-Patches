# Discrete 8 Control Panel Patch
Original Discrete 8 control panel application patch.


This is a patch made for the original Discrete 8 interface. 

It's function is to restore the development disabled grid matrix routing system that products like the orion studio and discrete 8 synergy core use today.
Not only can you route in a new visual, it also unlocks fully routing flexibility that the vanilla discrete 8 experience did not provide.With this you can now have

This project was entirely vibe coded with Claude.

This patch does not include any of Antelope Audio's original source code.
You must have your own copy of Discrete 8 Control Panel 1.9.10 to use this.




WHAT IT ADDS
------------
-Routing AFX outputs through analog outputs.
-Channel naming
-Independent mix sources for each of the 4 mixCh.
-Optional pop out window for the routing table.
-Mixers now have more flexibility being able to have independent sources for each mix rather than all 4 mixes' sources being linked.
-AFX is now built into the CP window rather than a pop out. An option pop out button is available.

<img width="1375" height="772" alt="NEW Routing" src="https://github.com/user-attachments/assets/cf5f1e38-fca7-450c-b058-23511aa119cc" />

<img width="1375" height="772" alt="NEW AFX" src="https://github.com/user-attachments/assets/05479e23-3e26-4359-aa36-fef90f9e4304" />

<img width="1375" height="772" alt="NEWMixers" src="https://github.com/user-attachments/assets/5a0d3fab-cf65-454a-8e1e-61d498774c11" />

<img width="1353" height="892" alt="NEW Pop out" src="https://github.com/user-attachments/assets/0ce8374a-0a2f-46db-a92c-c1578564dfd7" />

<img width="1375" height="772" alt="NEW Analog" src="https://github.com/user-attachments/assets/4a8ac473-5830-45a9-b855-513e98240fa8" />


WHAT YOU NEED
-------------
- An original Discrete 8.
- A Mac with the Antelope Launcher, and the Discrete 8 Control Panel 1.9.10 installed
  by it. (Open the Launcher with your Discrete 8 connected once, so it installs the
  panel.) Other panel versions are not supported: the installer checks, and changes
  nothing if your panel isn't 1.9.10.


HOW TO INSTALL
--------------
1. Quit the Discrete 8 Control Panel (and close the Antelope Launcher).
2. Double-click "Install D8 Patch.command".
3. A Terminal window opens, does the work, and says "Done". Press Return to close it.
4. Open the Discrete 8 panel as usual.

If your Mac says the file "can't be opened" or is from an "unidentified developer":
   a. Click Done / OK on that message.
   b. Open System Settings > Privacy & Security.
   c. Scroll down: next to "Install D8 Patch.command was blocked", click "Open Anyway".
   d. Confirm (your Mac password or Touch ID may be asked for), then it runs.
   You only need to do this once for each of the two .command files.

Before changing anything, the installer copies your panel to your Desktop:
- an unpatched panel is saved as "discrete8_unpatched.app"
- an already patched panel (when updating) is saved as "discrete8_copy.app"
An existing copy is never overwritten; a new one gets a number ("discrete8_copy 2.app").
You can delete these copies once you're happy.


HOW TO UNDO
-----------
1. Quit the Discrete 8 Control Panel.
2. Double-click "Uninstall D8 Patch.command".
Your original panel is put back exactly as it was.


IF SOMETHING GOES WRONG
-----------------------
- The panel opens but looks normal (no ROUTING tab): the reason is written to the
  log files in /Users/Shared/.AntelopeAudio/logs (look for "D8 routing patch").
- Anything else: run "Uninstall D8 Patch.command", or reinstall the panel with the
  Antelope Launcher.

## Disclaimer

This is an unofficial, fan-made patch. It is not made, supported or approved by
Antelope Audio. Use it at your own risk.
