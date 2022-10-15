# maxlamenace912's roblox Free Models documentation
You will find below all the useful information related to the free models I made
## Table of contents
* [Kill Bricks](#killBricks)
* * [Setup](#setupKillBricks)
* * [How to add kill bricks](#howToAddKillBricks)
* * [Configuration](#killBricksConfiguration)

## Documentation

### Kill Bricks<a name=killBricks></a>

[Asset link](https://create.roblox.com/marketplace/asset/11147339607/KillBricks-Collection-Service)

#### Setup<a name=setupKillBricks></a>

To setup the free model, paste this in the command bar at the bottom of the screen :

```
workspace.KillBricks_FM.KillBricksHander.Parent = game:GetService("ServerScriptService"); workspace.KillBricks_FM:Destroy()
```

**NOTE : THE README FILE CONTAINING THE LINK WILL BE DELETED AFTER USING THIS COMMAND**

#### How to add killbricks<a name=howToAddKillBricks></a>

1. Install a tag plugin such as this one : [Tag Explorer](https://create.roblox.com/marketplace/asset/8293721212) _(made by @5uphi)_
2. Open it via the toolbar \
![Image showing the icon of the plugin](https://i.gyazo.com/dd5b6fdc548a09edd6c6b56757534883.jpg, "Plugin button")
3. Select your kill bricks in the explorer (only BasepParts such as part, unions, meshes **NOT MODELS OR FOLDER**) \
![Image showing the explorer with multiple parts selected](https://i.gyazo.com/3f75c8dd3379e2de88ba125192d33d0d.jpg, "Explorer") 
4. Type the name name of the tag (default is KillBrick) in the input field \
![Image showing the Tag explorer with "KillBrick typed in the input field](https://i.gyazo.com/bd75c83cbceea94a8816dd3100d8e1b4.jpg, "Tag explorer")
5. Click on the + \
![Image showing the click on the "+" button](https://i.gyazo.com/eb0a8e5c2ee2da11960850f96794177b.png, "+ button")

To add more kill bricks, select them in the explorer and click on the +

#### Configuration<a name=killBricksConfiguration>

The following settings are availabel in the Configuration folder located in the script

**NOTE : Any changes made during the game on the configuration objects will be ignored**

|Instance name|Type|Description|
--------------|-----|-----------|
|IgnoreForceField|boolean (true/false)| When a player spawn, he generally has a force field that make him/her invulnerable. If set to true, the player could be killed when he has the forcefield.
|UpdateKillBricks|boolean (true/false)| In the script, a loop check if the killbrick collection changed and apply changes on parts. If this option is set to false, any change on the parts will be ignored.
KillBricksDelay|number|The collection check loop repeat regulary. This option define the delay between each check. (Works only if UpdateKillBricks is set to true) **WARNING : IF THE NUMBER IS TOO LOW, THE GAME COULD EXPERIENCE MORE OR LESS SIGNIFICANT LAG**
Tag|string|The tag to add to the killbricks
