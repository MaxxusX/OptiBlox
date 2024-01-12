# OptiBlox

this probably sucks im still learning this stuff but it works for me

# lists

ok so theres 2 flag lists, [normal](Normal.json) and [ultimate](Ultimate.json). 

### [normal](Normal.json)
enables useful features and boosts fps without losing quality

### [ultimate](Ultimate.json)
get insane fps at the cost of roblox being really low quality

# THIS SECTION IS FOR [NORMAL](Normal.json) ONLY!

## issues with arsenal

the following flags cause arsenal to freeze roblox for some reason.

```json
"FFlagEnableInGameMenuModernization": true,
"FFlagEnableInGameMenuChrome": true,
```

## gui hiding

At the top of the file, you should see `"DFIntCanHideGuiGroupId": 5959518,`.<br>
Set this to the ID of a group you're in. Here are the following keyboard shortcuts it provides for toggling the visibility of GUI elements.<br><br>

| Key combination |	Action |
| --------------- | ------ |
| Ctrl + Shift + B | Toggles GUIs in 3D space (BillboardGuis, SurfaceGuis, etc) |
| Ctrl + Shift + C | Toggles game-defined ScreenGuis |
| Ctrl + Shift + G | Toggles Roblox CoreGuis |
| Ctrl + Shift + N | Toggles player names, and other BillboardGuis that show up above a player |