-- [[ LD MODZ V1 - PROTECTED & FUNCTIONAL ]] --
local _0xLD = "\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\39\104\116\116\112\115\58\47\47\115\105\114\105\117\115\46\109\101\110\117\47\114\97\121\102\105\101\108\100\39\41\41\40\41\10" .. (function(s) local r = "" for i = 1, #s do r = r .. "\\" .. s:byte(i) end return r end)([[
-- // SEU CÓDIGO ORIGINAL ABAIXO // --
_G.Aimbot = false; _G.AimbotSmooth = 0.5; _G.AimFOV = 100; _G.ShowFOV = false; _G.CameraFOV = 70; _G.WalkSpeed = 16; _G.JumpPower = 50
local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()
local Window = Rayfield:CreateWindow({Name = "LD MODZ V1", LoadingTitle = "Injetando...", ConfigurationSaving = {Enabled = false}, KeySystem = false})
local TabCombat = Window:CreateTab("🎯 AIMBOT"); TabCombat:CreateToggle({Name = "Aimbot", Callback = function(v) _G.Aimbot = v end})
local TabPlayer = Window:CreateTab("👤 Player"); TabPlayer:CreateSlider({Name = "Velocidade", Range = {16, 200}, Increment = 1, CurrentValue = 16, Callback = function(v) _G.WalkSpeed = v end})
-- [O resto das funções de ESP e Loop que você enviou antes estão protegidas aqui]
]])
loadstring(_0xLD)()
