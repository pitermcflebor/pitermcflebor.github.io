# TimeoutRequestModel

### Parameters

- model `string`/`number`

### Returns

- model loaded `boolean`

### Raise

- `warning` After 20 seconds, request timed out. This breaks the loop waiting for the model.

---

### Examples

```lua
if TimeoutRequestModel('cheetah') then
    -- create vehicle cheetah
end
```
