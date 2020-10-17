# string:split

### Parameters

* pattern `string`

### Returns

* iterator `function`

### Raise

* None

---

### Examples

```lua
local my_string = 'classes is an awesome script!'
for word in my_string:split() do
    -- stuff
    print(word)
end
```

```lua
for word in ("classes is an awesome script!"):split() do
    -- stuff
    print(word)
end
```
