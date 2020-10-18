# StateBag:set()

### Parameters

- state key `any`
- state value `any`
- shared `boolean` *this means will be shared with everyone*

### Returns

- `boolean`

### Raise

- `error` key was nil
- `error` value was nil
- `error` shared was nil or not a boolean

---

### Examples
```lua
-- premade ped
ped.state:set('name', 'Foo Bar', true)
```