# DRAWING LIBRARY
---

## Drawing.New:
```lua
<object> Drawing.new(<string> type)
```
- Creates a new drawing object with `type`. Returns the object.

## Clear Draw Cache:
```lua
<void> cleardrawcache(<void>)
```
- Removes all drawing object(s) in the cache.

## Get Render Property:
```lua
<variant> getrenderproperty(<Drawing>, <string>)
```
- Grabs the value of a property of a drawing object.

## Is Render Object:
```lua
<bool> isrenderobj(<variant>)
```
- Returns if the assigned object is a valid drawing.

## Set Render Property:
```lua
<void> setrenderproperty(<Drawing>, <string>, <variant>)
```
- Sets the value of a property of a drawing object.

### Example:
```lua
local newDrawing = Drawing.new("Circle")

setrenderproperty(newDrawing, "Color", Color3.fromRGB(255, 255, 255))
```