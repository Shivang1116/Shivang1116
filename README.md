```lua
repeat wait() until game:IsLoaded()
_G["HoHo Hub Auto Bounty V3"] = {
    ["Avatar"] = "rbxassetid://8598068647",
    ["Farm Method"] = "Normal", -- Normal or Gun
    ["Select Team"] = "Marine", -- Pirate/Marine
    ["Discord Webhook"] = "",
    ["Bypass Teleport"] = true,
    ["Max Level Distance"] = 612, -- 612 is took from wiki but u can change it
    ["Don't attack friends"] = true,
    ["Don't attack player have cup"] = false,
    ["Distance Attack Y"] = 6, -- Shark Race = 0; Another >= 6
    ["Chat After Kill"] = {
        ["Active"] = true,
        ["List Chat"] = {"i have a good gaming chair","No skill? Use Hoho hub"},
    },
    ["Yourself"] = {
        ["Invisible From Ken"] = true,
        ["No Stun"] = true,
    },
    ["SafeZone"] = {Enabled = true, ["Health Left (%)"] = 40, ["Wait Until Heal (%)"] = 90},
    ["Time Control"] = {
        ["Max Time Target Player"] = 120,
    },
    ["Abilities"] = {
        ["Auto Click"] = true,
        ["Melee"] = {
            Z = {Enabled = true, Hold = 0.05, WaitNextSkill = 0.6},
            X = {Enabled = true, Hold = 0.05, WaitNextSkill = 0.6},
            C = {Enabled = true, Hold = 0.05, WaitNextSkill = 0.6},
        },
        ["Sword"] = {
            Z = {Enabled = true, Hold = 0.05, WaitNextSkill = 0.6},
            X = {Enabled = true, Hold = 0.05, WaitNextSkill = 0.6},
        },
        ["Gun"] = {
            Z = {Enabled = true, Hold = 0.05, WaitNextSkill = 0.6},
            X = {Enabled = true, Hold = 0.05, WaitNextSkill = 0.6},
        },
        ["Fruit"] = {
            Z = {Enabled = true, Hold = 0.05, WaitNextSkill = 0.6},
            X = {Enabled = true, Hold = 0.05, WaitNextSkill = 0.6},
            C = {Enabled = true, Hold = 0.05, WaitNextSkill = 0.6},
            V = {Enabled = true, Hold = 0.05, WaitNextSkill = 0.6},
            F = {Enabled = true, Hold = 0.05, WaitNextSkill = 0.6},
        },
    },
}
