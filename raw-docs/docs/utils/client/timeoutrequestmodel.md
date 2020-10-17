# TimeoutRequestModel

### Parameters

- model `string`/`number`

### Returns

- model loaded `boolean`

### Raise

- `warning` After 500ms, request timed out. This breaks the loop waiting for the model.

---

### Examples

```lua
if TimeoutRequestModel('cheetah') then
    -- create vehicle cheetah
end
```
