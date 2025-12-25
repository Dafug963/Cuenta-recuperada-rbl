# Cuenta-recuperada-rbl
Recuperar mí cuenta 
--// UNIVERSAL SINISTER SCRIPT
--// By Spidermark

local Players = game:GetService("Players")
local UIS = game:GetService("UserInputService")
local RunService = game:GetService("RunService")
local player = Players.LocalPlayer

repeat task.wait() until player.Character
local char = player.Character
local humanoid = char:WaitForChild("Humanoid")
local root = char:WaitForChild("HumanoidRootPart")

-- GUI
local gui = Instance.new("ScreenGui", player.PlayerGui)
gui.Name = "SpidermarkSinister"

local main = Instance.new("Frame", gui)
main.Size = UDim2.new(0,320,0,420)
main.Position = UDim2.new(0.35,0,0.25,0)
main.BackgroundColor3 = Color3.fromRGB(20,20,20)
main.Active = true
main.Draggable = true

local title = Instance.new("TextLabel", main)
title.Size = UDim2.new(1,0,0,30)
title.BackgroundTransparency = 1
title.Text = "SINISTER MODE | By Spidermark"
title.TextColor3 = Color3.fromRGB(200,0,0)
title.Font = Enum.Font.GothamBold
title.TextSize = 14

-- Imagen Mark Siniestro
local image = Instance.new("ImageLabel", main)
image.Size = UDim2.new(0,90,0,90)
image.Position = UDim2.new(0.36,0,0,35)
image.BackgroundTransparency = 1
image.Image = "rbxassetid://15476299874" -- cambia si quieres

-- Botones cerrar/minimizar
local close = Instance.new("TextButton", main)
close.Text = "X"
close.Size = UDim2.new(0,30,0,30)
close.Position = UDim2.new(1,-35,0,0)
close.BackgroundColor3 = Color3.fromRGB(120,0,0)

local mini = Instance.new("TextButton", main)
mini.Text = "-"
mini.Size = UDim2.new(0,30,0,30)
mini.Position = UDim2.new(1,-70,0,0)
mini.BackgroundColor3 = Color3.fromRGB(50,50,50)

local bubble = Instance.new("TextButton", gui)
bubble.Size = UDim2.new(0,50,0,50)
bubble.Position = UDim2.new(0.05,0,
