# Ped

??? warning "IMPORTANT"
    Creating Peds client-side is a very bad idea. They will despawn anytime!

### Parameters

- new ped `boolean`
- entity id `number` / model `number` or `string`
- pedType `number` *if new ped is true*
- x `number` *if new ped is true*
- y `number` *if new ped is true*
- z `number` *if new ped is true*
- heading `number` *if new ped is true*
- isNetwork `boolean` *if new ped is true*

### Returns

- object `Ped`

### Raise

- ``error`` any parameter isn't the correct type
- `error` the ped type isn't between 0 and 29
- `error` if the entity doesn't exists

---

### Examples
```lua
local ped = Ped(true, 'some_ped_model', 34.5, 33.2, 45.6, 10.0, true)
```

```lua
local ped = Ped(false, someEntityId)
```