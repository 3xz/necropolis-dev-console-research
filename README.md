# Necropolis Developer Console Research

## Disclaimer

Your [save] data is your own responsibility. It's on you if your data explodes.

## Contributions

Contributions are welcome! Ideally, all commands can be given descriptions. Please don't straight-up copy the code as a description (`usedailyseed` is a good example as it's an `if` statement).

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
createruckus | int size | 
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
setplayerrenderersvisible | bool value | 
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
becomearena |  | Go to arena seen at the end of PAX demos
teleportmain |  | 
teleportarena |  | 
teleportelevator |  | 
cheatloot | int level | 
cheatwarp | int level | 
teleportend |  | 
teleporthell |  | Teleports to level 9
go | int seed, float x, float y, float z | 
teleport | float x, float y, float z | 
teleportcell | int x, int y, int z | 
traversecell | int x, int y, int z | 
togglegodmode |  | 
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
upgradeplayer |  | 
suicide |  | Kills the player character
suicideinfive |  | Kills the player character in 5 seconds
gotocharselect |  | Leaves existing game to character select
injure |  | 
neardeath |  | 
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
setscreenshotfactor | float val | Increases screenshot resolution where &lt;val&gt; is a multiplier
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
switchplayercharacter | string id | 
addplayeritem | string id | 
spawnactor | string id | Spawns an NPC of &lt;id&gt; as noted in `Creatures.csv`
savesession |  | Immediately saves current session
purgesavedata |  | Purges save data of current session
invite | string name | 
accept | string name | 
join | string name | 
friends |  | 
networkingdojoserve |  | 
fullstacktrace |  | 
toggledebuginteractions |  | 
disconnect | string name | 
refreshobjectives |  | 
completeobjectives |  | 
finishobjectives |  | 
addrandomobjective |  | 
addobjective | string id | 
setoffline |  | 
setonline |  | 
printactors |  | 
printspawnrecords |  | 
autopilot | int depth | 
chain | string command | 
networkgameend |  | 
togglesavemodulemanagerdebugging |  | 
toggleinteractableobjectdebugging |  | 
togglenetdynamicobjectmanagerdebugging |  | 
toggleactorinstantiatedebugging |  | 
togglemultiplayerverbosedebugging |  | 
rebindall |  | 
