local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Fisrt x HUB", "Synapse")
local Tab = Window:NewTab("Position and CFrame")
local Section = Tab:NewSection("Copy_Position")
Section:NewButton("Position", "ButtonInfo", function()
    print(setclipboard(tostring(game.Players.LocalPlayer.Character.HumanoidRootPart.Position)))
end)
Section:NewButton("CFrame", "ButtonInfo", function()
    print(setclipboard(tostring(game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame)))
end)
Section:NewButton("DarkDex", "ButtonInfo", function()
    print(loadstring(game:HttpGet("https://raw.githubusercontent.com/Babyhamsta/RBLX_Scripts/main/Universal/BypassedDarkDexV3.lua", true))())
end)
Section:NewButton("ReeMotSimpleSpy", "ButtonInfo", function()
    print(loadstring(game:HttpGet("https://github.com/exxtremestuffs/SimpleSpySource/raw/master/SimpleSpy.lua"))())
end)
Section:NewButton("Fast_Attack", "ButtonInfo", function()
    print(loadstring(game:HttpGet("https://raw.githubusercontent.com/Besty191/MAZI-API/main/Fast_Attack.lua"))())
end)
Section:NewButton("SPAWNPOINT", "ButtonInfo", function()
    print(setclipboard(tostring(game:GetService("Players").LocalPlayer.Data.SpawnPoint.Value)))
end)
--
