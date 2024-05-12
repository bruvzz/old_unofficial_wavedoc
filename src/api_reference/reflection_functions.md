# REFLECTION FUNCTIONS
---

## Loadstring:
```lua
<function> loadstring(<string> chunk, <string?> chunkName)
```
- Loads `chunk` as a Lua function with optional `chunkName` and returns it.

## Check Caller:
```lua
<bool> checkcaller(<void>)  
```
- Returns `true` if the current thread was created by Wave.

## Is Lua Closure:
```lua
<bool> islclosure(<function> a1)  
```
- Returns `true` if `a1` is an LClosure.