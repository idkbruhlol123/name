local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("savrou146 script lolz", "GrapeTheme")


local flip = Window:NewTab("flippity floppity")
local MainSection = flip:NewSection("goofy ahh")

MainSection:NewButton("do a flip", "makes u do a flip u fucktard (z and x to flip)", function()
    wait(5)

    --[[ Info ]]--
    
    local ver = "2.00"
    local scriptname = "feFlip"
    
    
    --[[ Keybinds ]]--
    
    local FrontflipKey = Enum.KeyCode.Z
    local BackflipKey = Enum.KeyCode.X
    local AirjumpKey = Enum.KeyCode.C
    
    
    --[[ Dependencies ]]--
    
    local ca = game:GetService("ContextActionService")
    local zeezy = game:GetService("Players").LocalPlayer
    local h = 0.0174533
    local antigrav
    
    
    --[[ Functions ]]--
    
    function zeezyFrontflip(act,inp,obj)
        if inp == Enum.UserInputState.Begin then
            zeezy.Character.Humanoid:ChangeState("Jumping")
            wait()
            zeezy.Character.Humanoid.Sit = true
            for i = 1,360 do 
                delay(i/720,function()
                zeezy.Character.Humanoid.Sit = true
                    zeezy.Character.HumanoidRootPart.CFrame = zeezy.Character.HumanoidRootPart.CFrame * CFrame.Angles(-h,0,0)
                end)
            end
            wait(0.55)
            zeezy.Character.Humanoid.Sit = false
        end
    end
    
    function zeezyBackflip(act,inp,obj)
        if inp == Enum.UserInputState.Begin then
            zeezy.Character.Humanoid:ChangeState("Jumping")
            wait()
            zeezy.Character.Humanoid.Sit = true
            for i = 1,360 do
                delay(i/720,function()
                zeezy.Character.Humanoid.Sit = true
                    zeezy.Character.HumanoidRootPart.CFrame = zeezy.Character.HumanoidRootPart.CFrame * CFrame.Angles(h,0,0)
                end)
            end
            wait(0.55)
            zeezy.Character.Humanoid.Sit = false
        end
    end
    
    function zeezyAirjump(act,inp,obj)
        if inp == Enum.UserInputState.Begin then
            zeezy.Character:FindFirstChildOfClass'Humanoid':ChangeState("Seated")
            wait()
            zeezy.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")	
        end
    end
    
    
    --[[ Binds ]]--
    
    ca:BindAction("zeezyFrontflip",zeezyFrontflip,false,FrontflipKey)
    ca:BindAction("zeezyBackflip",zeezyBackflip,false,BackflipKey)
    ca:BindAction("zeezyAirjump",zeezyAirjump,false,AirjumpKey)
    
    --[[ Load Message ]]--
    
    print(scriptname .. " " .. ver .. " loaded successfully")
    print("made by Zeezy#7203")
    
    local notifSound = Instance.new("Sound",workspace)
    notifSound.PlaybackSpeed = 1.5
    notifSound.Volume = 0.15
    notifSound.SoundId = "rbxassetid://170765130"
    notifSound.PlayOnRemove = true
    notifSound:Destroy()
    game.StarterGui:SetCore("SendNotification", {Title = "nigurflip", Text = "KILL URSELF!!!", Icon = "rbxassetid://505845268", Duration = 5, Button1 = "SURE!!!"})
end)

local speeds = Window:NewTab("why so fast")
local SpeedSection = speeds:NewSection("why so fast")

SpeedSection:NewSlider("flash", "speed.", 500, 16, function(s) 
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)

SpeedSection:NewSlider("high", "JUMP", 350, 50, function(s) 
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = s
end)


local chat = Window:NewTab("chat")
local ChatSection = chat:NewSection("OOOO")

ChatSection:NewButton("chat spoof lolz", "mess around with retards", function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/djBfk8Li'),true))()
end)

MainSection:NewButton("fly", "makes u go superman (left alt to toggle)", function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/75U6zUmq'),true))()
end)

