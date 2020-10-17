# UpdateY

### Parameters

- y `number`

### Returns

- None

### Raise

- ``warning`` not passed a `number`

---

### Examples
```lua
local coords = Coords(GetEntityCoords(PlayerPedId()))
coords:UpdateY(50.0)
-- doesn't affect to the player coords
```