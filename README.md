# Pistonware Standalone

Finalized standalone build of Pistonware for Roblox Bedwars and Universal games.

- **Zero Key Gates**: Removed commercial Luarmor DRM dependencies.
- **Zero GitHub Rate Limit Stalls**: Pinned commit and multi-mirror CDN resolution.
- **Production Obfuscated**: Luau bytecode-compliant obfuscated runtime.

## Public Loadstring Entry Points

### 1. Monolithic Obfuscated Client (Recommended)
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/eridtpdiscord-cloud/pistonware-standalone/main/pistonware_obfuscated.lua", true))()
```

### 2. Hardened Production Loader
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/eridtpdiscord-cloud/pistonware-standalone/main/loader.lua", true))()
```

### 3. Full Clean Source
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/eridtpdiscord-cloud/pistonware-standalone/main/pistonware.lua", true))()
```
