# TriggerClientCallback

### Parameters

- source `number`
- eventName `string`
- \*values `any`

### Returns

- values from client-side `any`

### Raise

- None

---

### Examples

```lua
local some, value, returned = TriggerClientCallback('awesome:script', some, data)
-- this is synchronous!
```
