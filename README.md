local Players = game:GetService("Players")
local RunService = game:GetService("RunService")
local Highlight = Instance.new("Highlight")
Highlight.Name = "Highlight"
function ApplyToCurrentPlayers()
   for i,player in pairs(Players:GetChildren()) do
      repeat wait() until player.Character
      if not player.Character:FindFirstChild("HumanoidRootPart"):FindFirstChild("Highlight") then
         local HighlightClone = Highlight:Clone()
         HighlightClone.Adornee = player.Character
         HighlightClone.Parent = player.Character:FindFirstChild("HumanoidRootPart")
         HighlightClone.DepthMode = Enum.HighlightDepthMode.AlwaysOnTop
         HighlightClone.Name = "Highlight"
      end
   end
end
RunService.Heartbeat:Connect(function()
   ApplyToCurrentPlayers()
end)
local Door = game:GetService("Door")
local RunService = game:GetService("RunService")
local Highlight = Instance.new("Highlight")
Highlight.Name = "Highlight"
function ApplyToCurrentPlayers()
   for i,player in pairs(Players:GetChildren()) do
      repeat wait() until player.Character
      if not player.Character:FindFirstChild("Door"):FindFirstChild("Highlight") then
         local HighlightClone = Highlight:Clone()
         HighlightClone.Adornee = player.Character
         HighlightClone.Parent = player.Character:FindFirstChild("Door")
         HighlightClone.DepthMode = Enum.HighlightDepthMode.AlwaysOnTop
         HighlightClone.Name = "Highlight"
      end
   end
end
RunService.Heartbeat:Connect(function()
   ApplyToCurrentPlayers()
end)
