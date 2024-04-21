getgenv().Setting = {
    ["Team"] = "Pirates", --Can Change To "Marines" Or "Pirates"
    ["Skip Race V4"] = true,
    ["Misc"] = {
        ["Enable Lock Bounty"] = false,
        ["Lock Bounty"] = {0, 300000000}, --Kick If Max Bounty
        ["Hide Health"] = {3000,5000}, --Run If Low Health
        ["Lock Camera"] = true,
        ["Enable Cam Farm"] = false,
        ["White Screen"] = false,  --Reduce Fps
        ["FPS Boost"] = false, --Better Fps Boost
        ["Bypass TP"] = true,
        ["Random & Store Fruit"] = true
    },
    ["Item"] = {
        ["Melee"] = {["Enable"] = true,
            ["Z"] = {["Enable"] = true, ["Hold Time"] = 0},
            ["X"] = {["Enable"] = true, ["Hold Time"] = 0},
            ["C"] = {["Enable"] = true, ["Hold Time"] = 0}
        },
        ["Blox Fruit"] = {["Enable"] = false,
            ["Z"] = {["Enable"] = true, ["Hold Time"] = 0},
            ["X"] = {["Enable"] = true, ["Hold Time"] = 0},
            ["C"] = {["Enable"] = true, ["Hold Time"] = 0},
            ["V"] = {["Enable"] = true, ["Hold Time"] = 0},
            ["F"] = {["Enable"] = true, ["Hold Time"] = 0}
        },
        ["Sword"] = {["Enable"] = false,
            ["Z"] = {["Enable"] = true, ["Hold Time"] = 0},
            ["X"] = {["Enable"] = true, ["Hold Time"] = 0}
        },
        ["Gun"] = {["Enable"] = true,
            ["Z"] = {["Enable"] = true, ["Hold Time"] = 0},
            ["X"] = {["Enable"] = true, ["Hold Time"] = 0}
        }
    }
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/MakeScript/NebulaHub/main/Auto-Bounty-v1"))()
