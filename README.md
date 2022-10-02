# maxlamenace912's roblox Free Models documentation
You will find below all the useful information related to the free models I made
## Table of contents
* [Kill Bricks](#killBricks)
* * [How to add kill bricks](#howToAddKillBricks)
* * [Configuration](#killBricksConfiguration)

## Documentation

### Kill Bricks<a name=killBricks></a>

#### How to add killbricks<a name=howToAddKillBricks></a>

1. Install a tag plugin such as this one : [Tag Explorer](https://create.roblox.com/marketplace/asset/8293721212) _(made by @5uphi)_
2. Open it via the toolbar
3. Select your kill bricks in the explorer (only BasepParts such as part, unions, meshes **NOT MODELS OR FOLDER**)
4. Type the name name of the tag (default is KillBrick) in the input field
5. Click on the +

To add more kill bricks, select them in the explorer and click on the +

#### Configuration<a name=killBricksConfiguration>

The following settings are availabel in the Configuration folder located in the script

|Instance name|Type|Description|
--------------|-----|-----------|
|IgnoreForceField|boolean (true/false)| When a player spawn, he generally has a force field that make him/her invulnerable. If set to true, the player could be killed when he has the forcefield.
|UpdateKillBricks|boolean (true/false)| In the script, a loop check if the killbrick collection changed and apply changes on parts. If this option is set to false, any change on the parts will be ignored.
KillBricksDelay|number|The collection check loop repeat regulary. This option define the delay between each check. (Works only if UpdateKillBricks is set to true) **WARNING : IF THE NUMBER IS TOO LOW, THE GAME COULD EXPERIENCE MORE OR LESS SIGNIFICANT LAG**
Tag|number|The tag to add to the killbricks
