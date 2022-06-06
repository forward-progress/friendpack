# Nathan's FriendPack

A lightweight quilt based modpack used by Nathan and his friends.

# How to Install

## PolyMC

The `.mrpack` from the releases can be used to install the pack, however, this will not provide you
with auto-update functionality out of the box, to set that up, you will want to use
[`packwiz-installer`](https://packwiz.infra.link/tutorials/installing/packwiz-installer/).

To setup this pack in PolyMC with auto-updating enable, do the following:

1. Create a new instance

   Press the "Add Instance" button, choose "Vanilla" in the left sidebar, then select "Quilt" in the
   Mod Loader menu. Use the latest quilt launcher available, `0.17.0-beta.2` at time of writing.

2. Install `packwiz-installer-bootstrap` in the instance minecraft folder

    Right click on the instance you just created and select "Minecraft Folder" to be taken to the
    instance minecraft folder. Download the latest
    [`packwiz-installer-bootstrap`](https://github.com/packwiz/packwiz-installer-bootstrap/releases)
    jar from its releases page, and then copy it into this directory.
    
3. Configure auto-updates

    Right Click on the instance -> Edit Instance, and select the "Settings" view.
    
    From there select the "Custom commands" tab, ensure the "Custom Commands" checkbock is selected,
    and type/paste the following into the "Pre-launch command" box:
    
    `"$INST_JAVA" -jar packwiz-installer-bootstrap.jar -server
    https://forward-progress.github.io/friendpack/pack.toml`
    
At this point, when you start the instance, it should automatically download the modpack, and it
will check for updates every time you start up the instance. You may need to restart minecraft once
after initial install for the mods to pick up.

If for some reason this does not work after a single restart, navigate to the instance minecraft
folder in a terminal, and run the above command manually in the direct, after deleting the `mods`
folder.

When installing from the `.mrpack`, you may have to install [Roughly Enough
Items](https://www.curseforge.com/minecraft/mc-mods/roughly-enough-items/files) manually.

    
