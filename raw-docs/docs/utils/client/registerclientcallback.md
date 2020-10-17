# RegisterClientCallback

### Parameters

- eventName `string`
- callback `function`

### Returns

- Inside callback
  - Values passed from server-side `any`

### Raise

- `warning` eventName wasn't string
- `warning` callback wasn't function

---

### Examples

```lua
RegisterClientCallback('awesome:script', function(foo, bar)
    -- my awesome code
    return x, y
end)
```
