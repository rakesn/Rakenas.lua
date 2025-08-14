local p = game:GetService("Players").LocalPlayer
local g = Instance.new("ScreenGui")
g.Parent = p:WaitForChild("PlayerGui")

for i = 0, 3 do
    local t = Instance.new("TextLabel")
    t.Size = UDim2.new(1,0,0.25,0)
    t.Position = UDim2.new(0,0,0.25*i,0)
    t.BackgroundTransparency = 0.5
    t.BackgroundColor3 = Color3.fromRGB(0,0,0)
    t.TextColor3 = Color3.fromRGB(255,0,0)
    t.TextScaled = true
    t.Text = "Stop cheating, kid!"
    t.Parent = g
end
