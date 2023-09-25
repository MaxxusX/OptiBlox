# OptiBlox

R(C/F)O and some stuff<br>
xhax is stupid and kaiddd is a dumbass


# things

## gui hiding

At the top of the file, you should see `"DFIntCanHideGuiGroupId": 5959518,`.<br>
Set this to the ID of a group you're in. Here are the following keyboard shortcuts it provides for toggling the visibility of GUI elements.<br><br>

| Key combination |	Action |
| --------------- | ------ |
| Ctrl + Shift + B | Toggles GUIs in 3D space (BillboardGuis, SurfaceGuis, etc) |
| Ctrl + Shift + C | Toggles game-defined ScreenGuis |
| Ctrl + Shift + G | Toggles Roblox CoreGuis |
| Ctrl + Shift + N | Toggles player names, and other BillboardGuis that show up above a player |

## optional settings

<details>
<summary>Disable Facial Animations</summary>

```json
"FFlagEnableBetaFacialAnimation2": false,
"FFlagFacialAnimationSupport1": false,
"FFlagEnableCameraByDefault": false,
"DFFlagVideoCaptureServiceEnabled": false,
"FFlagAvatarChatSettingsEnabled2": false,
"FFlagFacialAnimationStreamingServiceUserSettingsOptInVideo": false,
"FFlagFacialAnimationStreamingServiceUniverseSettingsEnableVideo": false,
"FFlagFacialAnimationStreamingServiceUserSettingsOptInAudio": false,
"FFlagFacialAnimationStreamingServiceUniverseSettingsEnableAudio": false,
"DFFlagAvatarChatServiceUserPermissionsAudioOptIn": false,
"DFFlagAvatarChatServiceUserPermissionsAudioEligible": false,
"FFlagVoiceChatServiceManagerUseAvatarChat": false,
"FFlagAvatarChatServiceExposeClientFeaturesForVoiceChat": false,
```
</details>

<details>
<summary>Disable Wind (for grass n' stuff)</summary>

```json
"FFlagGlobalWindRendering": false,
```
</details>

<details>
<summary>Revert to Menu v2</summary>

To change from v4 to v2, find these flags and set them all to false.<br>
```json
"FFlagEnableInGameMenuChrome": true,
"FFlagEnableMenuModernizationABTest": true,
"FFlagEnableMenuModernizationABTest2": true,
"FFlagEnableV3MenuABTest3": false,
"FFlagEnableMenuControlsABTest": true,
"FFlagEnableInGameMenuControls": true,
"FFlagDisableNewIGMinDUA": true,
```
</details>