# im not done writing this idk

# cool fflag list
use [bloxstrap](https://github.com/pizzaboxer/bloxstrap)

reminder to myself to make a gui that lets u select these


## Misc.

### Verifed Icon
gives you the verified icon (only for you), set this to your id
```json
"FStringWhitelistVerifiedUserId": "1056542255",
```

### More Graphics Levels
gives you 21 graphics slider options instead of 10
```json
"FFlagFixGraphicsQuality": "True",
"FFlagCommitToGraphicsQualityFix": "True",
```

### Set Graphics Quality on Game Load
use 0 for auto, and -1 for recent; if you have FixGraphicsQuality this can go to 21, else it can go to 10
```json
"FIntRomarkStartWithGraphicQualityLevel": "21",
```

### No Telemetry
```json
"FFlagDebugDisableTelemetryEphemeralCounter": "True",
"FFlagDebugDisableTelemetryEphemeralStat": "True",
"FFlagDebugDisableTelemetryEventIngest": "True",
"FFlagDebugDisableTelemetryPoint": "True",
"FFlagDebugDisableTelemetryV2Counter": "True",
"FFlagDebugDisableTelemetryV2Event": "True",
"FFlagDebugDisableTelemetryV2Stat": "True",
"DFIntClientLightingTechnologyChangedTelemetryHundredthsPercent": "0",
"DFStringCrashUploadToBacktraceBaseUrl": "null",
"DFStringCrashUploadToBacktraceMacPlayerToken": "null",
"DFStringCrashUploadToBacktraceWindowsPlayerToken": "null",
"GoogleAnalyticsAccountPropertyIDPlayer": "null",
"FStringCoreScriptBacktraceErrorUploadToken": "null",
"FStringGamesUrlPath": "/games/",
"DFFlagClientBaseNetworkMetrics": "False",
"DFStringRobloxAnalyticsURL": "null",
"DFStringTelegrafHTTPTransportUrl": "null",
"DFStringAltTelegrafHTTPTransportUrl": "null",
"DFStringTelegrafAddress": "127.0.0.1",
"DFStringAltTelegrafAddress": "127.0.0.1",
"DFStringTelemetryV2Url": "null",
"DFFlagEnableLightstepReporting2": "False",
"DFIntLightstepHTTPTransportHundredthsPercent2": "0",
"DFStringLightstepHTTPTransportUrlHost": "null",
"DFStringLightstepHTTPTransportUrlPath": "null",
"DFStringLightstepToken": "null",
"DFStringHttpPointsReporterUrl": "null",
"DFStringAltHttpPointsReporterUrl": "null",
"DFStringAnalyticsEventStreamUrlEndpoint": "null",
```

### No Lua App Bar
move the lua app bar to the bottom (roblox app)
```json
"FFlagLuaAppSystemBar": "False"
```


# GUI

### New CoreGUI
enables the new coregui
```json
"FFlagEnableInGameMenuModernization": "True",
"FFlagEnableInGameMenuChrome": "True",
```

### GUI hiding keybinds
allows you to hide types of guis with keybinds, set this to the id of a group you're in
```json
"DFIntCanHideGuiGroupId": "5959518",
```

### Disable fullscreen title bar
disables the bar that appears upon hovering on the top of the screen
```json
"FFlagInGameMenuV1FullScreenTitleBar": "False",
```

### Exclusive Fullscreen keybind
allows u to use exclusive fullscreen, use `Alt` + `Enter` to activate
```json
"FFlagHandleAltEnterFullscreenManually": "True",
```


# Rendering

### Force Future Lighting
forces the future lighting in all games
```json
"FFlagDebugForceFutureIsBrightPhase3": "True",
```

### DPI Scaling Fix
fixes rendering quality decreasing when ur display scaling is more than 100%
```json
"DFFlagDisableDPIScale": "True",
```

### Enable Direct3D11
enables the direct3d11 rendering engine
```json
"FFlagDebugGraphicsDisableDirect3D11": "False",
"FFlagDebugGraphicsPreferD3D11": "True",
```

### Change Texture Size
lets u set the texture size for things
```json
"FIntTerrainOTAMaxTextureSize": "1024",
"FIntUITextureMaxRenderTextureSize": "1024",
```

### No Immersive Ads
disables those immersive ad portals n' stuff
```json
"FStringImmersiveAdsUniverseWhitelist": "0",
"FFlagImmersiveAdsWhitelistDisabled": "False",
"FFlagEnableAdsAPI": "False",
"FFlagAdServiceEnabled": "False",
```

### Infinite Zoom
allows you to zoom out very far. only works on games with default zoom value
```json
"FIntCameraMaxZoomDistance": "9999999",
```


## Performance

### Max FPS
sets your max fps. set to 99999999 for no limit
```json
"DFIntTaskSchedulerTargetFps": "99999999",
```

### Quick Start
makes roblox start faster
```json
"FFlagEnableQuickGameLaunch": "False",
```

### Preload Fonts
preloads fonts
```json
"FFlagPreloadAllFonts": "True",
```


## Too Much Performance (makes game low quality)

### No Textures
removes the default roblox textures, custom textures not included
```json
"FStringPartTexturePackTablePre2022": "",
"FStringTerrainMaterialTable2022": "",
"FStringTerrainMaterialTablePre2022": "",
```

### Reduce MSAA Samples
reduces the amount of msaa applied in the game
```json
"FIntDebugForceMSAASamples": "0",
```

### Low Quality Textures
reduces the quality of some textures in the ui, avatar clothing, and images
```json
"DFFlagTextureQualityOverrideEnabled": "True",
"DFIntTextureQualityOverride": "0",
```

### Low Poly
reduces the amount of polygons rendered in game meshes
```json
"DFIntCSGLevelOfDetailSwitchingDistance": "0",
"DFIntCSGLevelOfDetailSwitchingDistanceL12": "0",
"DFIntCSGLevelOfDetailSwitchingDistanceL23": "0",
"DFIntCSGLevelOfDetailSwitchingDistanceL34": "0",
```

### No Grass
disables roblox's auto-generated grass
```json
"FIntFRMMaxGrassDistance": "0",
"FIntFRMMinGrassDistance": "0",
```

### No Shadows
disables some shadows
```json
"FIntRenderShadowIntensity": "0",
"DFFlagDebugPauseVoxelizer": "True",
```

### No PostFX
disables postfx things like sun rays
```json
"FFlagDisablePostFx": "True",
```

### No Cloud Reflections
disable clouds reflecting on water
```json
"FFlagCloudsReflectOnWater": "False",
```

### No Wind
disables wind in games with wind effects
```json
"FFlagGlobalWindActivated": "False",
```


## To be documented
```json
"FLogNetwork": "7",
"FFlagPreloadTextureItemsOption4": "True",
"FIntDefaultMeshCacheSizeMB": "256",
"FFlagGpuGeometryManager7": "True",
"FFlagRenderGpuTextureCompressor": "True",
"FFlagNewLightAttenuation": "False",
```