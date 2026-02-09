
# All kinds of scripts that you can fill in getgenv().Mode = "namescriptkaitun"
- kaitunautopvp  ( Lock )
- kaitunautolevi ( Lock )
- Autodungoen    ( Life )
# Update
Our dungeon script is currently in beta; the functions are still manual and not yet automated. We apologize for this as we lack the funding and time for this, but perhaps in the future we will invest more to bring you the best experience!
# How to Use ?

```lua
repeat task.wait() until game:IsLoaded() and game.Players.LocalPlayer

getgenv().Key     = "PASTE_KEY_HERE"   --- your key have and paste in "PASTE_KEY_HERE"  
getgenv().Mode    = "namescriptkaitun"    --- your type script you want [ Autodungoen , kaitunautolevi , kaitunautopvp ]
-- getgenv().Tier = "auto"             --- auto , Premium , Free ( TIP: Specifying whether you want Premium or Free will make the system load a little faster )

loadstring(game:HttpGet("https://raw.githubusercontent.com/thieengw9990/Astra-Hub-Kaitun/refs/heads/main/AstraXHub-Kaitun.Lua"))()```
