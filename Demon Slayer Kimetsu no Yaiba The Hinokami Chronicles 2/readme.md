> [!NOTE]
This mod is WIP (Work In Progress). This mean that issues like jump speedup exists and are not fixed yet.

You can see a **gameplay test [here](https://youtu.be/T1AhhGsoH70?si=9ZAUUJDJdmON49CM)**

> [!WARNING]
Read all the info from the post. You can know how to update the cheat below (only for real hardware users)

**THIS IS NOT AN EXEFS MOD (.pchtxt)** it's a cheat (.txt)

The reason why I'm sharing the cheat instead is due to the .pchtxt version issues are worse than the cheat (all movement is speedup)

## Why my game is crashing

Watch [this video](https://youtu.be/_4rdgzYUybg?si=039vcPGRvEBWDiw2https://youtu.be/_4rdgzYUybg?si=039vcPGRvEBWDiw2)

> [!NOTE]
REMEMBER TO READ THE VIDEO DESCRIPTION  for the full details.

It might help you fix the issues.

## How to update the cheat (ONLY FOR REAL HARDWARE USERS)

1. Download the latest release of [UE4cfgdumper](https://github.com/masagrator/UE4cfgdumper/releases)

2. Run the game until you see the menu.

Here's a video showing you how to do it. [CLICK HERE](https://youtu.be/NdnWTG3kM3A?si=RHd_0ZT-vSHxOyJU)

3. Open the homebrew menu and run UE4cfgdumper

4. **Press A for a FULL SCAN**

5. You'll get two files:

- a .txt
- a .log

The log will give you interesting info for the cheats and the .txt will contain some cheats. **However they're not usable YET**

6. Go to [this website](https://ue4cheatcreator.vercel.app/) and upload the log.

7. You'll get the .txt with the cheats done.

> [!NOTE]
You can use an alternative to this instead the other .nro of UE4cfgdumper

Here's the [alternative link](https://github.com/biase-d/UE4cfgdumper-creator/releases)

This tool combines both tools in one.

8. Now read the information in [this post](https://gbatemp.net/threads/ue4cfgdumper-dump-ram-pointers-to-graphics-settings.643375/post-10299270).

**The cheat is using r.Vsync and FixedFrameRate**

Set `680F0000 00000000 00000000` for r.Vsync and `680F0000 00000000 00000007` for FixedFrameRate.

That's all. Now create a new .txt file with the same name as the .txt you got and paste only the new 60FPS cheat that you already did.

Example:

```
[60FPS WIP]
580F0000 0BD62EB0
680F0000 00000000 00000000
580F0000 0CD4F388
780F0000 00000AF4
680F0000 00000000 00000007
```