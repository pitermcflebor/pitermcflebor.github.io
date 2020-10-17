# table.dump

!!! note

This is not a json encoder!

### Parameters

- table to dump`table`

### Returns

- dumped table`string`

### Raise

- None

---

### Examples

```lua
print( table.dump( table.build(("classes are awesome!"):split()) ) )
```

```lua
local my_table = {
    key = 'awesome value',
    key2 = 'classes are awesome',
    key3 = {foo='bar'}
}
print( table.dump(my_table) )
```
