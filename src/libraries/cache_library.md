# CACHE LIBRARY
---

## Replace:
```lua
<void> cache.replace(<Instance.X>, <Instance.Y>)
```
- Replaces `Instance.X` with `Instance.Y` in the cache within registry.

## Invalidate:
```lua
<void> cache.invalidate(<Instance>)
```
- Invalidates `Instance` in the cache within registry.

## Is Cached:
```lua
<bool> cache.iscached(<Instance>)
```
- Returns if `Instance` is currently cached in the cache within registry.

## Clone Reference:
```lua
<Instance> cloneref(<Instance.X>)
```
- Pushes `Instance.X` in a new cache. 

## Compare Instances:
```lua
<bool> compareinstances(<Instance.X>, <Instance.Y>)
```
- Compares instances internally. 