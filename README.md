
local args = {
    [1] = "Fishing",
    [2] = "Caught",
    [3] = true
}

game:GetService("ReplicatedStorage"):WaitForChild("Game"):WaitForChild("Remotes"):WaitForChild("ServerHandler"):FireServer(unpack(args))
