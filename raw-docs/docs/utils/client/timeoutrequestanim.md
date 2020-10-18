# TimeoutRequestAnim

### Parameters

- anim dictionary `string`

### Returns

- anim loaded `boolean`

### Raise

- `warning` After 20 seconds, request timed out. This breaks the loop waiting for the anim.

---

### Examples

```lua
if TimeoutRequestAnim('some@dictionary@anim') then
    -- do something while playing anim
end
```
