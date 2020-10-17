# TriggerServerCallback

### Parameters

- eventName `string`
- \*values `any`

### Returns

- Response from server-side `any`

### Raise

- None

---

### Examples

````lua
local some, values, returned = TriggerServerCallback('awesome:script', foo, bar)
-- this is a synchronous function!
````
