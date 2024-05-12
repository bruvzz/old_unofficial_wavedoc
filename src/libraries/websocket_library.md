# WEBSOCKET LIBRARY
---

## Connect:
```lua
<bool> websocket.connect(<string> url)
```
- Connects with `url` and will return the instance representing the connection.

## Send:
```lua
<void> Socket:Send(<string> text)
```
- Sends `text` to the websocket connection.

## Close:
```lua
<void> Socket:Close(<void>)
```
- Closes the websocket connection.

| Event | Description |
| :----: | :----: |
| .OnMessage | Activated when a message is receieved over the websocket connection. |
| .OnClose | Activated when the websocket connection is closed. |