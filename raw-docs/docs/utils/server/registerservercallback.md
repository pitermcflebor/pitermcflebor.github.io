# RegisterServerCallback

### Parameters

- eventName `string`
- callback `function`

### Returns

- Inside the callback
  - source `number`
  - \*values `any`

### Raise

- `warning` if eventName isn't `string`
- `warning` if callback isn't `function`

---

### Examples

```lua
RegisterServerCallback('awesome:script', function(source, some, data)
    -- some awesome code
    return some, response
end)
```
