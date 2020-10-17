# AddBlip

### Parameters

- blip sprite `number`
- as short range `boolean` *optional*
- blip name `string` *optional*
- scale `number` *optional*
- color `number` *optional*
- alpha `number` *optional*

### Returns

- the blip id `number`

### Raise

- `error` the sprite id wasn't a `number`

---

### Examples
```lua
local coords = Coords(GetEntityCoords(PlayerPedId()))
coords:AddBlip(1, true, 'awesome blip', 0.6, 1, 255)
```