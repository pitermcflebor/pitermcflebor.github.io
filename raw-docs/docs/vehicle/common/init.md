# Vehicle

### Parameters

- new vehicle `boolean`
- entity id `number` / model `number` or `string`
- x `number` *if new vehicle is true*
- y `number` *if new vehicle is true*
- z `number` *if new vehicle is true*
- heading `number` *if new vehicle is true*
- isNetwork `number` *if new vehicle is true*

### Returns

- object `Vehicle`

### Raise

- ``error`` if any parameter isn't the correct type
- `error` the entity doesn't exists
- `warning` the model doesn't exists

---

### Examples
```lua
local vehicle = Vehicle(true, 'cheetah', 45.3, 56.2, 131.3, 100.0, true)
```

```lua
local vehicle = Vehicle(false, someEntityId)
```