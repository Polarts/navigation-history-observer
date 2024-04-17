## [1.1.1] - Apr. 17, 2024

* Merged [PR by wrbl606](https://github.com/Polarts/navigation_history_observer/pull/6)
* Upgrade example project to work with Dart/Flutter 3+
* Fix early `.top` access -- if no routes were added yet, `.top` access attempt will result with `BadState` thrown

## [1.1.0] - Mar. 11, 2021

* Migrated to null safety.
* Updated built_collection dependency to ^5.0.0.
* Added type annotations to getters.

## [1.0.3+1] - Jun. 20, 2020

* Example updated - The example page is now in main.dart to show the full code on pub.dev

## [1.0.3] - Jun. 20, 2020

* Changed library name from `navigation_history_observer` to `navigationhistoryobserver`.
* Removed `route` from `HistoryChange`, added `newRoute` and `oldRoute` instead.
* Added `next` getter to get most resent popped route.
* No longer supporting forwards navigation as it causes severe issues.
* Added more usage details and special thanks to the readme.

## [1.0.2] - Jun. 19, 2020

* Added example project, updated historyChanged to historyChangeStream for better semantics.

## [1.0.1] - Jun. 19, 2020

* Added stream to broadcast changes in history.

## [1.0.0] - Jun. 17, 2020

* First stable release.
