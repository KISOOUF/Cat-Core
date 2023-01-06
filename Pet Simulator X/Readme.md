## Cat-Core Webhook documentation
![image](https://user-images.githubusercontent.com/95049751/210865373-98497835-b130-44c5-97fb-b9f51f0d9886.png)

## Ping @everyone on Kick
![image](https://user-images.githubusercontent.com/95049751/211063761-61fbf6ca-b8a9-45cf-977b-da9c3f8344bb.png)

```lua
getgenv().Webhook = "" -- Discord Webhook [ Don't delete the ""!

loadstring(game:HttpGet("https://raw.githubusercontent.com/KISOOUF/Cat-Core/main/Pet%20Simulator%20X/Webhook-Kick"))()
```
##  Ping @everyone if (value) players are there
![image](https://user-images.githubusercontent.com/95049751/211065803-9f75d937-798f-482a-892c-173c204ef403.png)

```lua
getgenv().Webhook = "" -- Discord Webhook [ Don't remote the ""! ]
getgenv().toggle = true -- Failed serverhop, leave it tho.
getgenv().minplayers = 8 -- Minimum amount of players to fire the webhook
getgenv().textwebhook = "You can add @everyone or @here, i honestly don't recommend these if your time check is lower than 10" -- Webhooks title, you can make @everyone, @here or any text
getgenv().timecheck = 60 -- Time in seconds to re-check, i recommend 60.

loadstring(game:HttpGet("https://raw.githubusercontent.com/KISOOUF/Cat-Core/main/Pet%20Simulator%20X/Webhook-Player-Count"))()
```
