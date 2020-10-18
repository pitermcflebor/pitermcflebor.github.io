# Player

### Parameters

- the server id `number` *-1 for self player*

### Returns

- object `Player`

### Raise

- `error` server id wasn't a `number`
- `error` player doesn't exists

---

### Examples
```lua
-- FiveM uses Player, so classes use CPlayer
local player = CPlayer(-1)
```