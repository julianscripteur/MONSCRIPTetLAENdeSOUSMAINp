local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window  = Library.CreateLib("Script cree par julian", "Ocean")
local Tab     = Window:NewTab("Crash")
local Section = Tab:NewSection("Crash (With Game Money!)")
Section:NewToggle("achete des Ben", "Crash game", function(state)
    if state then
_G.on = true

while _G.on == true do
    wait()

wait(0.2)
    local args = {
    [1] = "Trading Ben"
    }

    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))

wait(0.2)

    end
    else
_G.on = false
        
    end
end)
Section:NewToggle("achete des nft munneh", "Crash game", function(state)
    if state then
_G.on = true

while _G.on == true do
    wait()

wait(0.2)
    local args = {
    [1] = "Munneh"
    }

    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))

wait(0.2)

    end
    else
_G.on = false
        
    end
end)

Section:NewToggle("Crash Game", "Crash game", function(state)
    if state then
_G.on = true

while _G.on == true do
    wait()

wait(0.2)
    local args = {
    [1] = "Mommeh Long Legs"
    }

    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))

wait(0.2)

    end
    else
_G.on = false
        
    end
end)
Section:NewToggle("achete des lenay", "Crash game", function(state)
    if state then
_G.on = true

while _G.on == true do
    wait()

wait(0.2)
    local args = {
    [1] = "Lenay"
    }

    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))

wait(0.2)

    end
    else
_G.on = false
        
    end
end)

Section:NewToggle("achete des XOX", "Crash game", function(state)
    if state then
_G.on = true

while _G.on == true do
    wait()

wait(0.2)
    local args = {
    [1] = "XOX"
    }

    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))

wait(0.2)

    end
    else
_G.on = false
        
    end
end)

Section:NewKeybind("Pour buy des ben B", "Close F open F", Enum.KeyCode.B, function()
local args = {
    [1] = "Trading Ben"
}

game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
end)

Section:NewKeybind("Pour buy munneh M", "Close F open F", Enum.KeyCode.M, function()
local args = {
    [1] = "Munneh"
}

game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
end)

Section:NewKeybind("Pour buy Mommeh P", "Close F open F", Enum.KeyCode.P, function()
local args = {
    [1] = "Mommeh Long Legs"
}

game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
end)

Section:NewButton("Charger mon script d avant", "Flemme", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/julianscripteur/LOLLOLOLOLOMAINLOLOPOPOPOPOP/main/README.md"))()
end)
