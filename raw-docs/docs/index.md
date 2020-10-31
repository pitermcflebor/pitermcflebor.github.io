# Welcome to `Classes` documentation!

### [Github Code](https://github.com/pitermcflebor/fivem-classes-lua)

### [FiveM post](https://forum.cfx.re/t/release-wip-lua-classes-for-everyone/1663296)

## Release notes

!!! summary "v0.2.0 BIG CHANGES?"
	- Added new method to import classes
		- Don't need anymore to import as `@classes/...` on fxmanifest.lua file

	!!! warning "IMPORTANT"
		Check the [tutorial](/tutorial) !

??? summary "v0.1.6"
	- Added version check
	- Added new method to Ped client-side

??? summary "v0.1.4"
	- Added new methods to Ped
	- Added new methods to Player
	- Added new function to Utils
	- Fixed bug with Onesync and StateBag class not sure
	- Fixed bug with ShowNotification
	- Updated timeout functions to 20 seconds
	- Fixed Marker class, marker appears on center now
	- Fixed Coords:AddBlip
	- Removed unused prints

??? summary "v0.1.3"
	- Added method AddBlip to Coords class
	- Added methods GetPosition and SwapModel to class Prop
	- Added function TimeoutRequestModel to utils
	- Added common methods (string and table)
	- Removed error when trying to create a Ped class with non existent entity (now is only a warning)
	- Updated state for Player class
	- Updated StateBag for players

??? summary "v0.1.2"
	- Added new class Prop
	- Added inside class methods .state
		- It's used like class StateBag (ex: .state:set(key, value, shared))

??? summary "v0.1.1"
	- Added StateBag class
	- Fix [client/ped.lua] missing returning the Vehicle class

??? summary "v0.1.0 BIG CHANGES"
	- Find a new method of creating classes, old method had bugs about being replaced it-self.