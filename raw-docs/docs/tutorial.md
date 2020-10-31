# Creating your first script with `classes`!

## Create your resource folder
In this case, my resource will be named `tutorial`


*Your directory will look like this:*
```
tutorial
|   fxmanifest.lua
|
+---client
|       main.lua
|
\---server
        main.lua
```

## Let's import the `classes` to our resource!
*Inside your `fxmanifest.lua`*
```lua
fx_version 'cerulean'
games { 'gta5' }

client_scripts {
	-- DEPRECATED AFTER 0.2.0
	--[[ '@classes/common/utils.lua',
	'@classes/client/utils.lua',
	'@classes/client/statebag.lua',
	'@classes/client/coords.lua',
	'@classes/client/vehicle.lua',
	'@classes/client/player.lua',
	'@classes/client/ped.lua',
	'@classes/client/marker.lua', ]]
	'@classes/import.lua',
	'client/main.lua'
}

server_scripts {
	-- DEPRECATED AFTER 0.2.0
	--[[ '@classes/common/utils.lua',
	'@classes/server/utils.lua',
	'@classes/server/statebag.lua',
	'@classes/server/coords.lua',
	'@classes/server/vehicle.lua',
	'@classes/server/player.lua',
	'@classes/server/ped.lua', ]]
	'@classes/import.lua',
	'server/main.lua'
}

dependency 'classes'
-- if we want to use ESX
--[[
dependencies {
	'classes',
	'es_extended'
}
]]
```

*Inside your client-server side .lua file*
```lua
import '*' 					-- this get all classes
import 'ped' 				-- this get ped class
import {'ped', 'player'}	-- this get ped and player classes

-- now you can use the imported classes as before 0.2.0!
local ped = Ped(--[[ params ]])
```

## Adding this to snippets for VSCode
Adding a snippet on VSCode to write our `fxmanifest.lua` file will be very useful.

- Go to `File > Preferences > User Snippets`
- Create a `New Global Snippets file...`
- Remove all from the snippet file
- Copy and paste this inside the snippet file:

??? note "Snippet"
	```json
	{
		"fxmanifest":{
			"scope": "lua",
			"prefix": "fxmanifest",
			"body": [
				"fx_version 'cerulean'",
				"games { 'gta5' }",
				"",
				"client_scripts {",
				"\t'@classes/import.lua',",
				"\t'client/*.lua',",
				"}",
				"",
				"server_scripts {",
				"\t'@classes/import.lua',",
				"\t'server/*.lua',",
				"}",
				"",
				"dependency 'classes'"
			]
		},
	}
	```

Once this is done, we just need to write `fxmanifest` and press enter.
