# StateBag:clear()

### Parameters

- the state key `any`
- shared `boolean` *this means will be shared with everyone*

### Returns

- None

### Raise

- `error` shared was nil or not a boolean

---

### Examples
```lua
-- premade ped
ped.state:clear('name', true)
```