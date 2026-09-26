# Cursed Identify

Companion Dalamud plugin for the **Cursed Identify (/study)** Penumbra emote mod.

You identify a pile of mysterious loot with your spellbook... it's cursed. A magical-girl transformation
forces a neon-pink leotard onto you, you try to rip it off (it's locked), and you end up with your face in
your hands under a raincloud. During that skit this plugin asks **Glamourer** to really equip the leotard
and strip your head/hands/legs/feet, then restores your exact outfit when the skit loops or you stop the
emote. Because it is a normal Glamourer change, sync plugins show it to your synced friends too.

## Install

1. In game, open **Dalamud Settings** (`/xlsettings`) â†’ **Experimental**.
2. Under **Custom Plugin Repositories**, paste this URL into an empty row, tick **Enabled**, then click the
   **+** and **Save**:

   ```
   https://raw.githubusercontent.com/VamprincessDorene/CursedIdentify/main/repo.json
   ```

3. Open the plugin installer (`/xlplugins`), search for **Cursed Identify**, and install it.

## Requirements

- **Glamourer**
- The **Cursed Identify (/study)** mod enabled in Penumbra (it replaces Yakaku Dogi with the leotard and
  provides the emote). Faces need **Dawntrail Expression Library (illusio_vitae path)**.

## Use

- Just do **/study**. The outfit swaps at the transformation and comes back at the end of each loop.
- `/cursed` opens a small window (enable toggle, "apply now" / "restore" test buttons, status).
- `/cursed on` / `/cursed off` apply or restore by hand; `/cursed toggle` turns the swap on or off.

