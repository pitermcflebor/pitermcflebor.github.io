# ShowHelpNotification

### Parameters

- message `string`
- thisFrame `boolean` *optional, default false*
- beep `boolean` *optional, default true*
- duration `number` *optional, default -1*

### Returns

- None

### Raise

- None

---

### Examples

```lua
while true do
    Wait(0)
    ESX.ShowHelpNotification('Press ~INPUT_CONTEXT~ to ~y~do something~s~!')
end
```
