## BaseUrl

```
url: https://api.miocat.work
```
  
## 物品图标 Minecraft Item Icon

```
path: /image/getMCItem/{itemID}
method: GET

example: https://api.miocat.work/image/getMCItem/minecraft:bedrock
```
Support Mods:  
- Minecraft
- Pixelmon  

If other mod you need, you can open an `issue`

## 服务器信息 Server Info (Onlines, Motd, etc.)

```
path: /server/ping/{ip}/{port}
method: GET

example: https://api.miocat.work/server/ping/mc.hypixel.net/25565
```
