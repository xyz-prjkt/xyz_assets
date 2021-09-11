# xdroid | Xiaomi Redmi Note 7 Specific Changes
## 11/09/2021 | lavender
Mainline:
 - Switch to HMP
 - Upstreamed `xBoreUp.strmbreakr 4.4.283`
 - Updated toolchain `xRageTC Clang 14 20210906`

General:
 - Revert GoogleHotword
 - Dont rounded gboard corner

## 17/08/2021 | lavender
Mainline:
 - Upstreamed `xBoreUp.strmbreakr to 4.4.280`
 - Updated toolchain `xRageTC Clang 14 20210723`

General:
 - Import xRage Zone
 - Enabled FM Radio

## 23/07/2021 | lavender
Mainline:
 - Upstreamed `xBoreUp.strmbreakr to 4.4.276`
 - Updated toolchain `xRageTC Clang 20210805`

General:
 - Fixup DRM Service issues ( Netflix, HOOQ, etc )
 - Added 3.0 and 4.0 IMapper instance to manifest 
 - Relaxing WiFi re-association RSSI thresholds. 
 - Enabled BlurUI
 - Disable QTI Service Tracker ( avoid log spam )
 - Clear package_cache after dirty flash 
 - Enabled Color Management in Display Settings
