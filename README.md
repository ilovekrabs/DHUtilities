[!logo][https://media.discordapp.net/attachments/1006379004149891102/1034887085645123615/6a8ccfd84f426883017a8768bce1070bc5b78abf-1280x720.png?width=1440&height=490]

# DHUtilities

Da Hood Utilities or DHUtilities/DHUtils is a very cool script to make sure you don't/can't get caught slackin' by the admins on the Roblox game Da Hood.

## Loadstring
```lua
loadstring(game:HttpGet('https://raw.githubusercontent.com/ilovekrabs/DHUtilities/madebyrizzgod5961/DHUtilitiesMain'))()
```

## Features:
- God-Mode
- Bypass Anti-Cheat
- Spoofer

... more to be added.

Created by rizz god#5961

## Documentation

### Get the DH Utilities
```lua
local DHUtils = loadstring(game:HttpGet('https://raw.githubusercontent.com/ilovekrabs/DHUtilities/madebyrizzgod5961/DHUtilitiesMain'))()
```

### Create the Holder (gotta give myself some credit xP)
```lua
local DHUtilsHolder = DHUtils.Madebyrizzgod5961() -- name this local whatever you want, example: local sussy = DHUtils.Madebyrizzgod5961()
```

### God-Mode
```lua
DHUtilsHolder.Godmode(godmodetype) -- replace godmodetype with one of the God-Mode types shown here: "Anti-Bullet", there's sadly only 1 God-Mode for now, please include the strings aka the "" :P
```

### Bypass Anti-Cheat
```lua
DHUtilsHolder.BypassAntiCheat() -- pretty much self explanatory by the function's name, but if you still don't know what it does, it bypasses the Da Hood Anti-Cheat
```

### Spoofer
```lua
DHUtilsHolder.Spoof( -- if you want every spoof then either put true on all or just don't put anything, example: DHUtilsHolder.Spoof()
  true, -- CHECKER_1  //  if yes then true if no then false, if something other than true or false is put in the function, it will just think it's nil (nil means nothing in lua/luau, I made it so if it returns nil it counts it as true so the DHUtilsHolder.Spoof() works fine ^-^ )
  true, -- TeleportDetect  //  if yes then true if no then false, if something other than true or false is put in the function, it will just think it's nil (nil means nothing in lua/luau, I made it so if it returns nil it counts it as true so the DHUtilsHolder.Spoof() works fine ^-^ )
  true -- OneMoreTime  //  if yes then true if no then false, if something other than true or false is put in the function, it will just think it's nil (nil means nothing in lua/luau, I made it so if it returns nil it counts it as true so the DHUtilsHolder.Spoof() works fine ^-^ )
)
```
