## Changelog
### v0.5.48
Bug-Fixes:
* Revamped GPS restriction
* Enhanced battery usage (fixed bug where device isn't able deep sleep)
* Added support for HTC devices (HTC has a lot of own stuff inside the framework)
* Prepared for internet restriction

Features:
* ...

- --

### v0.5.47
Bug-Fixes:
* Fixed GUI glitches within the settings screen

Features:
* Implemented a filter-manager

- --

### v0.5.45-46
Bug-Fixes:
* Fixed GPS Bug
* Several cleanups

Features:
* ...

- --

### v0.5.44
Bug-Fixes:
* Some refactoring for new features

Features:
* Prepared for auto-log fetching feature -> added Permission android.permission.READ_LOGS (needed to enable better log support)
* Implemented (beta) the UI-Instructor. Activate it with preference UI-Instructor to learn more about the UI.
* Added Icon to indicate internet access. (Please activate the UI-Instructor to see how it works).

- --

### v0.5.43
Bug-Fixes:
* Fixed XposedFramework validation

Features:
* ...

- --

### v0.5.42
Bug-Fixes:
* ...

Features:
* Enhanced checking for activation in XposedFramework.
* Prepared for UI-Instructor

- --

### v0.5.41
Bug-Fixes:
* Fixed wrong resources usage for some dialogs
* Refactoring for new features

Features:
* ...

- --

### v0.5.40
Bug-Fixes:
* Fixed FC of application while trying to enter in application search-mode (wrong resoure linking)
* Fixed style of overflow-button in settings menu
* Pre-preparing for native support
* Enhanced the copying procedure for the flashable Rescue-Zip (RescueDonkey.zip)
* Fixed FC at first start of the application, because of some resource conflicts

Features:
* ...

- --

### v0.5.39
Bug-Fixes:
* Reduced memory-cache to a maximum size of 5 MB for devices with small memory (512mb)
* Fixed EditText input flags which causes that the lat/lon input won't accept "." and "-"
* Enlarged Heap-Size on devices with enough memory
* Reduced memory usage of the application

Features:
* ...

- --

### v0.5.38
Bug-Fixes:
* ...

Features:
* Added changelog within the application (take a look at preference, category about).
* Added applicaton version within the application (take a look at preference, category about).
* Added the possibility to set all settings to: REAL, EMPTY, RANDOM within the settings activity.

- --

### v0.5.37
_Bug-Fixes:_
* Flush interception cache if the interception-mode changed
* Prevent that system_server can show interception dialogs to avoid freezing on some ROMs (this will change in future due to native support)
* Fixed NullPointerException during the force-close of the on-demand dialog

_Features:_
* Implemented toast messages for unimplemented features

- --

### v0.5.36
_Bug-Fixes:_
* Fixed parsing the default-deny-mode and default-privacy-mode at startup
* Internal code improvements (a lot of refactoring)

_Features:_
* Enabled application search (permission and rating is not enabled yet).

- --

### v0.5.35
_Bug-Fixes:_
- Fixed java.lang.NoSuchMethodError at ActivityManagerService for CM-11

_Features:_
- ...

- --

