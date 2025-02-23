local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

if character and character:FindFirstChild("HumanoidRootPart") then
    character.HumanoidRootPart.CFrame = CFrame.new(
        -1524.96936, 42.9916954, 640.113647, 
        -0.608793378, 0, -0.793329239, 
        0, 1, 0, 
        0.793329239, 0, -0.608793378
    )
end
