local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/garnoog/Guia/main/README.md" , true))()
local win = library:CreateWindow({Name = "Dummy hub [Key]",Themeable = {info = "Doing by SharkDShop"}})
local General_Tab = win:Tab("General")

local ClientId = game:GetService("RbxAnalyticsService"):GetClientId()
local Hwide = string.split((ClientId),"-")
local Key = Hwide[1]

if _G.Key == Key then
    if Hwid[_G.Key] == game:GetService("RbxAnalyticsService"):GetClientId() then
    end
    end

local IN = General_Tab:CreateSection({Name = "Info"})
    IN:AddButton({
        Name = "Copy Key And Hwid",
        Callback = function()
            setclipboard("Key : "..(Key).." ,Hwid : "..(ClientId))
            end
    })
