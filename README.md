# Blackcat-library
v 1.0.0

CODE EXAMPLE:

local BlackCat = loadstring(game:HttpGet("https://raw.githubusercontent.com/geniusOfLua/Blackcat-library/refs/heads/main/BlackCat"))()

BlackCat:CreateWindow("title")
BlackCat:CreateButton(
  "text", function()
    -- script here
    game.Players.LocalPlayer.Character:WaitForChild'Humanoid'.WalkSpeed = 50
  end
)

BlackCat:Notification("Title", "Description", 3) -- duration
