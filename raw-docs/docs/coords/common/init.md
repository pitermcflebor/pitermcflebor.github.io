# Coords

### Parameters

- x `number`
- y `number`
- z `number`
- w `number`

Or

- any vector `vector2` / `vector3` / `vector4`

### Returns

- object `Coords`

### Raise

- `error` None of the parameters are `number` or `vector`

---

### Examples

```lua
local spawnPoint = Coords(34.9, 456.1, 15.3, 100.0)
```

```lua
local spawnPoint = Coords(GetEntityCoords(PlayerPedId()))
```
