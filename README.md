
## Client Side Exports

### Notify
```lua
exports['uvy_hud']:Notify(type, text, time)
```

| Field      | Data Type |
| ----------- | ----------- |
| type      | "information", "error", "success", "warning"   |
| text   | string |
| time   | number (milliseconds) |

### SetBeltState
```lua
exports['uvy_hud']:SetBeltState(toggle)
```

| Field      | Data Type |
| ----------- | ----------- |
| toggle      | boolean   |

### GetBeltState
```lua
exports['uvy_hud']:GetBeltState()
```

Returns: `boolean`

### ToggleHud
```lua
exports['uvy_hud']:ToggleHud(toggle)
```

| Field      | Data Type |
| ----------- | ----------- |
| toggle      | boolean   |

### GetLockState
```lua
exports['uvy_hud']:GetLockState()
```

Returns: `boolean`

## Server Side Triggers

### Notify
```lua
TriggerClientEvent("uvy_hud:notify", source, type, text, time)
```

| Field      | Data Type |
| ----------- | ----------- |
| source      | number (user id)   |
| type      | "information", "error", "success", "warning"   |
| text   | string |
| time   | number (milliseconds) |
