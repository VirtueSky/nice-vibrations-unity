# Nice-Vibrations
Vibration for game unity
## How to install
Add the lines below to ``Packages/manifest.json``
-   For version ``1.0.2``
```
"com.virtuesky.nicevibrations": "https://github.com/VirtueSky/nice-vibrations-unity.git#1.0.2",
```
How to use?
- You need to add the above link in manifest.json in folder Package
- Using library in your class.
```
using MoreMountains.NiceVibrations;
```
- Enables or disables all haptics called via this class (enable with status true and desable with status false)
```
MMVibrationManager.SetHapticsActive(true);
```
- Triggers a haptic feedback of the specified type
```
MMVibrationManager.Haptic(HapticTypes.MediumImpact);
```
- HapticTypes include (``Selection, Success, Warning, Failure, LightImpact, MediumImpact, HeavyImpact, RigidImpact, SoftImpact, None``). You should choose the haptic style that suits your purpose

## If your project is missing Newtonsoft Json
You need add the lines below to ``Packages/manifest.json``
```
"com.virtuesky.newtonsoftjson": "https://github.com/VirtueSky/Newtonsoft-Json.git#1.0.0",
```
