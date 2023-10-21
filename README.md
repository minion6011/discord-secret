# discord-secret

<details>
<summary>Override</summary>
    
### Non funzionante
```
https://discord.com/__development/link?s=VQw65opXPNOuzDRAa9ID91y7BV0U0ATg%2FmZfrhCBCqc%3D.eyJ0YXJnZXRCdWlsZE92ZXJyaWRlIjp7ImRpc2NvcmRfd2ViIjp7InR5cGUiOiJicmFuY2giLCJpZCI6ImZlYXR1cmUvd2ViLXNsYXNoLWNvbW1hbmQtbG9jYWxpemF0aW9uIn19LCJyZWxlYXNlQ2hhbm5lbCI6bnVsbCwidmFsaWRGb3JVc2VySWRzIjpbXSwiYWxsb3dMb2dnZWRPdXQiOmZhbHNlLCJleHBpcmVzQXQiOiJXZWQsIDEwIEF1ZyAyMDIyIDE3OjE4OjQ1IEdNVCJ9
    

{
  "targetBuildOverride": {
    "discord_web": {
      "type": "branch",
      "id": "feature/web-slash-command-localization"
    }
  },
  "releaseChannel": null,
  "validForUserIds": [],
  "allowLoggedOut": false,
  "expiresAt": "Wed, 10 Aug 2022 17:18:45 GMT"
}

https://discordpreviews.com/a-glorious-return
```

### ian/actually-darkmode
```
https://discord.com/__development/link?s=BuDTSWskHb2%2B0yghUp13pGg8DZVxjfFSevFKgMdLzB4%3D.eyJ0YXJnZXRCdWlsZE92ZXJyaWRlIjp7ImRpc2NvcmRfd2ViIjp7InR5cGUiOiJicmFuY2giLCJpZCI6Imlhbi9hY3R1YWxseS1kYXJrbW9kZSJ9fSwicmVsZWFzZUNoYW5uZWwiOm51bGwsInZhbGlkRm9yVXNlcklkcyI6W10sImFsbG93TG9nZ2VkT3V0IjpmYWxzZSwiZXhwaXJlc0F0IjoiRnJpLCAyNSBBdWcgMjAyMyAwMTozNjo1MyBHTVQiLCJleHBlcmltZW50cyI6bnVsbH0%3D
```

### annie/dark (broken)
```
https://discord.com/__development/link?s=Z7XEywE8rsgTvI0MR9P4OknzH4LtPi9j9%2Br8Hwzrohg%3D.eyJ0YXJnZXRCdWlsZE92ZXJyaWRlIjp7ImRpc2NvcmRfd2ViIjp7InR5cGUiOiJicmFuY2giLCJpZCI6ImFubmllL2RhcmsifX0sInJlbGVhc2VDaGFubmVsIjpudWxsLCJ2YWxpZEZvclVzZXJJZHMiOltdLCJhbGxvd0xvZ2dlZE91dCI6ZmFsc2UsImV4cGlyZXNBdCI6IlN1biwgMjggSmFuIDIwMjQgMDE6NTU6MDcgR01UIn0%3D
```

### Experiment link
```js
let wpRequire;
window.webpackChunkdiscord_app.push([[ Math.random() ], {}, (req) => { wpRequire = req; }]);
mod = Object.values(wpRequire.c).find(x => typeof x?.exports?.Z?.isDeveloper !== "undefined");
usermod = Object.values(wpRequire.c).find(x => x?.exports?.default?.getUsers)
nodes = Object.values(mod.exports.Z._dispatcher._actionHandlers._dependencyGraph.nodes)
try {
    nodes.find(x => x.name == "ExperimentStore").actionHandler["OVERLAY_INITIALIZE"]({user: {flags: 1}})
} catch (e) {}
oldGetUser = usermod.exports.default.__proto__.getCurrentUser;
usermod.exports.default.__proto__.getCurrentUser = () => ({isStaff: () => true})
nodes.find(x => x.name == "DeveloperExperimentStore").actionHandler["CONNECTION_OPEN"]()
usermod.exports.default.__proto__.getCurrentUser = oldGetUser
```


</details>

<details>
<summary>Help center - link ovveride builds</summary>


## Build Overrides second leak (2023) by No Text To Speech

```
https://pastebin.com/PS6BqFF3
```

## reddit post with first Build Override

```
https://www.reddit.com/r/discordapp/comments/wglvh0/darker_discord_ftw/
```

## Override test

```
https://support.discord.com/hc/en-us/community/posts/7962935678999-Discord-Build-over-rides-list-
```
    
```
https://support.discord.com/hc/en-us/articles/360030114991-Shhhhhh-
```
    
</details>




<details>
<summary>Fun / Troll Things</summary>

```
1164486607315947610 id of active developer bug
```

<details>
<summary>Discord app protocols</summary>

## Discord app protocols by ghostrider-05

```
Home:

* `/`: `discord://-/`
* friends: `discord://-/channels/@me/`
* nitro: `discord://-/store`
* message requests: `discord://-/message-requests`

General:

* apps: `discord://-/apps`
* discovery - guilds: `discord://-/guild-discovery`
* gift: `discord://-/gifts/<gift_code>`
* gift (with login screen): `discord://-/gifts/<gift_code>/login`
* new server: `discord://-/guilds/create`
* server invite: `discord://-/invite/<invite_code>`
* server invite (with login screen): `discord://-/invite/<invite_code>/login`

Settings:

* user settings: `discord://-/settings/<setting_name>`
  * with `setting_name`:
    * User settings - my account: `account`
    * User settings - profiles: `profile-customization`
    * User settings - privacy and safety: `privacy-and-safety`
    * User settings - authorized apps: `authorized-apps`
    * User settings - connections: `connections`
    * User settings - devices: `sessions`
    * User settings - friend requests: `friend-requests`
    * Payment settings - Discord Nitro: `premium`
    * Payment settings - server boost: `premium-guild-subscription`
    * Payment settings - subscriptions: `subscriptions`
    * Payment settings - gift inventory: `inventory`
    * Payment settings - billing: `billing`
    * App settings - appearance: `appearance`
    * App settings - accessibility: `accessibility`
    * App settings - voice & video: `voice`
    * App settings - text & images: `text`
    * App settings - notifications: `notifications`
    * App settings - keybinds: `keybinds`
    * App settings - language: `locale`
    * App settings - windows settings: `windows`
    * App settings - linux settings: `linux`
    * App settings - steamer mode: `streamer-mode`
    * App settings - advanced: `advanced`
    * Activity settings - activity privacy - `activity-privacy`
    * Activity settings - registered games - `registered-games`
    * Activity settings - game overlay: `overlay`
    * Hypesquad: `hypesquad-online`
    * Changelog: `changelogs`
    * Experiments: `experiments`
    * Developer options: `developer-options`
    * Hotspot options: `hotspot-options`
    * Dismissible Contents: `dismissible-content-options`
* guild settings: `discord://-/guilds/<guild_id>/settings`
  * overview: `/overview`
  * roles: `/roles`
  * emoji: `/emoij`
  * stickers: `/stickers`
  * widget: `/widget`
  * server template: `/guild-templates`
  * soundboard: `/soundboard`
  * custom invite link: `/vanity-url`
  * Apps - integrations: `/integrations`
  * Apps - app directory: `/app-directory` (empty page)
  * Moderation - safety setup: `/safety`
  * Moderation - audit log: `/audit-log`
  * Moderation - bans: `/bans`
  * Community - overview: `/community`
  * Community - onboarding: `/onboarding`
  * Community - server insights: `/analytics`
  * Community - partner programme: `/partner`
  * Community - discovery: `/discovery`
  * Community - welcome screen: `/community-welcome`
  * Monetization - Server subscriptions: `/role-subscriptions`
  * Server boost status: `/guild-premium`
  * User managament - members: `/members`
  * User managament - invites: `/instant-invites`
  * Delete: `/delete`

User:

* user profile: `discord://-/users/<user_id>`

Guilds and DMs:

* dm channel: `discord://-/channels/@me/<channel_id>`
* dm message: `discord://-/channels/@me/<channel_id>/<message_id>`
* favorites: `discord://-/channels/@favorites`
* favorites channel: `discord://-/channels/@favorites/<channel_id>`
* guild: `discord://-/channels/<guild_id>`
* guild channel: `discord://-/channels/<guild_id>/<channel_id>`
* guild browse channels: `discord://channels/<guild_id>/channel-browser`
* guild customize (onboarding): `discord://channels/<guild_id>/customize-community` 
* guild server guide channel: `discord://-/channels/<guild_id>/@home`
* guild event: `discord://-/events/<guild_id>/<event_id>`
* guild message: `discord://-/channels/<guild_id>/<channel_id>/<message_id>`
* guild membership screening: `discord://-/member-verification/<guild_id>`
* guild role subscriptions: `discord://-/channels/<guild_id>/role-subscriptions`
* hub membership screening: `discord://-/member-verification-for-hub/<hub_id>`

Library:

* library: `discord://-/library/`
* library inventory: `discord://-/library/inventory`
* library item actions: `discord://-/library/<sku_id>/<action_name>`
  * with `action_name`:
    * Launch: `launch`
* library settings: `discord://-/library/settings/`
* store page: `discord://-/store/skus/<sku_id>`
* store page: `discord://-/store/applications/<application_id>`

Account:

* login: `discord://-/login` (options: `?redirect_to=`)
* register: `discord://-/register` (options: `?redirect_to=`)
* reset: `discord://-/reset`
* restore: `discord://-/restore`

Events:

If an event is over, the link might not work anymore

* snowsgiving (Discord's yearly event in december): `discord://-/snowsgiving`
* 8th birthday: `discord://-/activities`

```

</details>


<details>
<summary>Troll links</summary>

## Troll links by No Text To Speech

### Fake nitro + Rickroll
```
[https￶://discord.gift/hHHfox3000foxyzBaJBXnXCU](<https://discord.com\vanityurl/dotcom/steakpants/flour/flower/index11.html>) ||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​|| 
https://discord.gift/dM76Tj7NSfqN64kVpn9JBJdE
```

### Fake nitro + Reset Password
```
[https￶://discord.gift/hHHfox3000foxyzBaJBXnXCU](<discord://-/reset>) ||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​||||​|| 
https://discord.gift/PZ76qKbfX8G8hjTKUKYjZntk
```

### Fake nitro link
```
https://discord.gift/PZ76qKbfX8G8hjTKUKYjZntk
```

### Rickroll link
```
https://discord.com/vanityurl/dotcom/steakpants/flour/flower/index11.html
```
</details>









</details>
