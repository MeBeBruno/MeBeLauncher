## MeBeLauncher?
A small desktop launcher **for Minecraft** that lets users sign in with their **Microsoft account** and start the game.

## Authentication & Permissions
- Flow: Microsoft OAuth **Device Code** (PKCE planned)
- Scopes: `XboxLive.signin` (+ `offline_access` for refresh)
- Token chain: **MSA → XBL → XSTS → Minecraft Services**
- Endpoints used: 
  - `GET https://api.minecraftservices.com/entitlements/mcstore`
  - `GET https://api.minecraftservices.com/minecraft/profile`

## Privacy / Data
- No passwords collected.  
- Tokens are stored **locally** on the user’s device and not shared with third parties.  
- Users can clear the token cache at any time.

## Contact
- Email: acc@bruno.zone
- Website: https://bruno.zone (optional)

## Disclaimer
MeBeLauncher is an **unofficial** project and is **not affiliated** with Mojang or Microsoft.
"Minecraft" is a trademark of Mojang/Microsoft.
