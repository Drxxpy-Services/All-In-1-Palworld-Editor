ALL-IN-1 PAL EDITOR
QUICK START GUIDE


============================================================
BEFORE YOU START
============================================================

1. Close Palworld completely.

2. Back up your entire world folder.

   Your save is normally here:

   %LOCALAPPDATA%\Pal\Saved\SaveGames\<Steam ID>\<World ID>\

3. Never replace your original save without keeping a backup.


============================================================
FIRST-TIME SETUP
============================================================

STEP 1 - INSTALL PYTHON

Download 64-bit Python from:

https://www.python.org/downloads/windows/

During installation, tick:

Add python.exe to PATH


STEP 2 - INSTALL PILLOW

Open Command Prompt and paste:

py -m pip install Pillow

Pillow allows the editor to display Pal and item pictures.


STEP 3 - PREPARE THE EDITOR FOLDER

Keep the editor in a normal folder, not inside a ZIP file.

Recommended layout:

All-In-1 Pal Editor\
|
+-- All-In-1_Pal_Editor.py
|
+-- Players\
    |
    +-- <Player UID>.sav
    +-- LocalData.sav

The folder must be named exactly:

Players


============================================================
HOW TO EDIT LEVEL.SAV
============================================================

1. Close Palworld.

2. Double-click:

   All-In-1_Pal_Editor.py

3. Open the Tools tab.

4. Click "Load .sav File".

5. Select your Level.sav.

6. Wait for the save to finish loading.

7. Open the tab you want and make your changes.

8. Press "Apply Changes" if that page has an Apply button.

9. Click "Validate".

10. If there are no critical errors, click "Export Save".

11. Save the new file as:

    Level.sav

12. Put the new Level.sav into the correct World ID folder.

13. Keep the original Level.sav as a backup.

14. Start Palworld and check the changes.


============================================================
PLAYER INVENTORY
============================================================

The editor automatically looks for player saves inside a folder named:

Players

Put the matching <Player UID>.sav inside the Players folder beside the
editor, or leave it in the Players folder beside Level.sav.

If it is not detected:

1. Open Tools.
2. Click "Load Player Save".
3. Select the correct <Player UID>.sav.

Do not select a file ending in:

_dps.sav


============================================================
ADDING OR EDITING A PAL
============================================================

1. Open the Pal Editor tab.
2. Select the correct Palbox and slot.
3. Add or select the Pal.
4. Make your changes.
5. Click "Apply Changes".
6. Confirm the Pal appears in the editor.
7. Validate the save.
8. Export a new Level.sav.
9. Replace the correct Level.sav while Palworld is closed.

Some game-only creatures cannot be stored as normal Palbox Pals.


============================================================
REVEALING THE MAP
============================================================

Map exploration uses LocalData.sav, not Level.sav.

1. Back up LocalData.sav.
2. Keep Palworld closed.
3. Use the map-reveal button in the editor.
4. Select your LocalData.sav copy.
5. Save the edited LocalData.sav to the real world-save location when
   the editor asks.


============================================================
ONLY IF THE EDITOR ASKS FOR OODLE
============================================================

If you see an Oodle error:

1. Open Tools.
2. Click "Locate Oodle Library".
3. Select the oo2core DLL from your Palworld installation.

It is commonly named:

oo2core_8_win64.dll

Do not download random DLL files from the internet.


============================================================
QUICK FIXES
============================================================

THE EDITOR OPENS AND IMMEDIATELY CLOSES

Look beside the editor for:

All-In-1_Pal_Editor_startup_error.txt

Send that file when asking for help.


PAL OR ITEM PICTURES ARE MISSING

Run:

py -m pip install Pillow

Then select the correct image folder from Tools.


PLAYER INVENTORY IS EMPTY

Make sure the matching player .sav is inside a folder named Players.
Reload Level.sav or use "Load Player Save" in Tools.


CHANGES DO NOT SHOW IN GAME

Check these five things:

1. Did you press Apply Changes?
2. Did you export after editing?
3. Did you replace the correct Level.sav?
4. Was Palworld completely closed?
5. Did Steam Cloud restore the old save?


THE WORLD WILL NOT LOAD

1. Close Palworld.
2. Remove the edited Level.sav.
3. Restore your original backup.
4. Report the validation or export error before trying again.


============================================================
THE THREE MOST IMPORTANT RULES
============================================================

1. ALWAYS BACK UP THE WHOLE WORLD FOLDER.

2. ALWAYS CLOSE PALWORLD BEFORE REPLACING A SAVE.

3. ALWAYS TEST SMALL CHANGES BEFORE USING BULK EDITS.


============================================================
HELP AND COMMUNITY
============================================================

Discord:

https://discord.gg/Ckp6wzx974

When asking for help, include:

- A screenshot of the error.
- The startup-error text file, if one was created.
- What you clicked immediately before the error.
- Whether your save is Steam, Game Pass, server, or modded.

