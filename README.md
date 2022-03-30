for i,v in pairs(game:GetService("Workspace").Zombies:GetChildren()) do
    if v.ClassName == "Model" then
        v.Mob.Health = die
wait(.1)
end
end
