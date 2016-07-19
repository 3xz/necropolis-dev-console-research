# Console Data

## Disclaimer

Your [save] data is your own responsibility. It's on you if your data explodes.

## Access

While in-game do the following:

* Press `` ctrl-` `` 3 times
* Press `enter` to focus the console text field (a white border will appear around the console)

(Note: Pressing `` alt-` `` will toggle the current console state. This can be faster than cycling through with `` ctrl-` ``)

## Commands

Command | Parameters | Description
------- | ---------- | -----------
echo | string text | returns &lt;text&gt; in console
restart |  | restarts at level 0 with current character
quit |  | immediately exits the game
createruckus | int size | Creates a ruckus of &lt;size&gt;, causing NPCs from opposing factions to spawn (and attack each other)
testfx | string bankid | 
testgameeffect | string gameeffects | 
usedailyseed |  | current code sets seed to 0 or 3
setseed | int seed | restarts and uses &lt;seed&gt;
loadscene | string scenename | 
toast | string text | &lt;text&gt; appears above the health/stamina UI
toastrandomconvo | string convoid, params object[] args | 
killall |  | Kills all enemies
killallnearby |  | Kills all NPC actors in 50 meters
setavatarid | string avatarid | &lt;avatarid&gt; is derived from `Creatures.csv`
reportstaticmemory |  | 
reportobjectcounts |  | 
reportgameobjects |  | 
memoryflush |  | 
dump | string dumpmessage | Dump logs with &lt;dumpmessage&gt; as a comment
deleteplayerprefs |  | Deletes player preferences
identifyallitems |  | Identifies all items in inventory
getalldyes |  | Unlocks all dyes
getallrecipes |  | Unlocks all recipes
vomit |  | The player character vomits
ingestedbuff | string stat, float amount, float duration | 
togglelookinverty |  | 
togglegamepadvibration |  | 
toggleglobalmute |  | 
toggleglobalmusicmute |  | 
toggleanimationtester |  | 
spawnloot | string loottableid | 
spawnloot10 | string loottableid | 
clearlootinradius | vector3 point, float radius | 
clearnearbyloot |  | 
spawnlootitem | string name | 
setplayerrenderersvisible | bool value | Player character is not rendered when &lt;value&gt; is `true`
togglenonaggression |  | When toggled on, aggressive mobs will go neutral after current 'cycle'
createlighting |  | 
createflashlight |  | 
toggleflashlight |  | 
destroynecrolights |  | 
destroylights |  | 
destroyak |  | 
destroyparticle |  | 
killui |  | 
killstuff |  | 
scanstuff |  | 
togglenavman |  | 
togglecustomrender |  | 
becomearena |  | Toggles PAX arena mode at current location
teleportmain |  | 
teleportarena |  | Go to arena seen at the end of PAX demos
teleportelevator |  | 
cheatloot | int level | 
cheatwarp | int level | 
teleportend |  | 
teleporthell |  | Teleports to level 9
go | int seed, float x, float y, float z | 
teleport | float x, float y, float z | Teleport to given coordinates within current session/seed
teleportcell | int x, int y, int z | 
traversecell | int x, int y, int z | 
togglegodmode |  | Appears to do nothing. (Still take damage and die regardless of toggle)
setspawnanimation | bool val | 
setprefabinjection | bool val | 
setmaterialapplication | bool val | 
setaudiodebugfloaties | bool val | 
setactormax | float val | 
setrenderdistance | int val | 
setmoduledistance | int val | 
cycledebug |  | 
timescaledown |  | 
timescaleup |  | 
settimescale | float val | 
applypalette | string palettename | 
droptokens | string amount | 
dropgems | string amount | 
upgradeplayer |  | Gives player a *Blessing of the Gods*. Does not heal player like an actual blessing.
suicide |  | Kills the player character
suicideinfive |  | Kills the player character in 5 seconds
gotocharselect |  | Leaves existing game to character select
injure |  | Player takes damage
neardeath |  | Player health is set to 1
cycleversiondisplay |  | 
togglemenuscreen |  | 
showdebugmenu |  | 
showrecords |  | Outputs current run's statistics in debug console
setdebugui | bool val | 
togglehudui |  | Hides health/stamina UI. Error message suggests it should also hide gem/token UI
toggleframemonitor |  | 
setframemonitor | bool val | 
invalidatenavmesh |  | 
toggledebugsound |  | 
toggledebugspawning |  | 
setrenderssao | bool val | 
setscreenspacereflections | bool val | 
setfxaa | bool val | 
setlightingquality | int val | 
setshadowquality | int val | 
setresolutionscale | float val | 
setgamma | float val | 
setvsync | bool val | 
setgeometryquality | int val | 
setsoftparticles | bool val | 
setscreenshotfactor | float val | Increases screenshot resolution where &lt;val&gt; is a multiplier. Persists over gameplay sessions.
takescreenshot |  | Takes a screenshot that is brighter and has no UI. [Comparison](http://imgur.com/a/fuqqz)
setdefaultlighting |  | 
disableatmospherefx |  | 
setgrinelut |  | 
showexposuredebug | bool val | 
addloot | string itemdefid | Drops &lt;itemdefid&gt; as defined by `Items.csv`
addlootbatch |  | 
toasttest |  | 
wingame |  | 
addcraftingcomponents |  | 
changepickupmode |  | 
setskypreset | string presetname | 
setfogpreset | string presetname | 
clearlogfilter |  | 
loginclude | string includeblob | 
logexclude | string excludeblob | 
setloggerlevel | string loggername, string level | 
logimpactvolumeinfo | bool inlodrange | 
switchplayercharacter | string id | Changes player character to &lt;id&gt; with apporpriate equipment (see `Creatures.csv`)
addplayeritem | string id | 
spawnactor | string id | Spawns an NPC of &lt;id&gt; as noted in `Creatures.csv`
savesession |  | Immediately saves current session
purgesavedata |  | Purges save data of current session
invite | string name | 
accept | string name | 
join | string name | 
friends |  | Steam: Lists all non-offline friends with current status of Online or Away. Does not include game friend is playing
networkingdojoserve |  | 
fullstacktrace |  | 
toggledebuginteractions |  | 
disconnect | string name | 
refreshobjectives |  | Refreshes completed objectives
completeobjectives |  | 
finishobjectives |  | Finishes all Brazen head objectives
addrandomobjective |  | 
addobjective | string id | 
setoffline |  | 
setonline |  | 
printactors |  | Prints all actors (Player and NPCs) with type, coordinates, distance from player, and map location
printspawnrecords |  | Prints spawn record of actors and current distance from spawn location
autopilot | int depth | Autopilots player character (with no clipping) &lt;depth&gt; levels
chain | string command | 
networkgameend |  | 
togglesavemodulemanagerdebugging |  | 
toggleinteractableobjectdebugging |  | 
togglenetdynamicobjectmanagerdebugging |  | 
toggleactorinstantiatedebugging |  | 
togglemultiplayerverbosedebugging |  | 
rebindall |  | 
