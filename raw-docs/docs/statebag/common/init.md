# StateBag

### Parameters

- the local entity id `number`
- is a player `boolean` *optional, default `false`*

### Returns

- object `StateBag`

### Raise

- `warning` the entity passed doesn't exists

---

### Examples
```lua
local statebag = StateBag(someEntityId)
-- this is used internally inside every entity class
-- you don't really need to use
```