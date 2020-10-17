# Welcome to `Classes` documentation!

### [Github Code](https://github.com/pitermcflebor/fivem-classes-lua)

### [FiveM post](https://forum.cfx.re/t/release-wip-lua-classes-for-everyone/1663296)

## Patch Notes

### v0.1.0 BIG CHANGES

- Find a new method of creating classes, old method had bugs about being replaced it-self.

---

### v0.1.1

- Added StateBag class
- Fix [client/ped.lua] missing returning the Vehicle class

---

### v0.1.2

- Added new class Prop
- Added inside class methods .state
  - It's used like class StateBag (ex: .state:set(key, value, shared))

---

### v0.1.3

- Added method AddBlip to Coords class
- Added methods GetPosition and SwapModel to class Prop
- Added function TimeoutRequestModel to utils
- Added common methods (string and table)
- Removed error when trying to create a Ped class with non existent entity (now is only a warning)
- Updated state for Player class
- Updated StateBag for players

