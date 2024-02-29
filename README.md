--create by FRITE
while true do wait()
local args = {
    [1] = {
        ["multiply"] = 1,
        ["action"] = "hit",
        ["enemyHum"] = workspace.NPC.SHARKBOSS.Humanoid
    }
}

game:GetService("ReplicatedStorage").DamageEvent:FireServer(unpack(args))
end
