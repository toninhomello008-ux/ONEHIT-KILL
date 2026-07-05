# ONEHIT-KILL
local function HitMonster(monster, damage)
    local humanoid = monster:FindFirstChild("Humanoid")

    if humanoid then
        -- Mata instantaneamente
        humanoid.Health = 0
    end
end
