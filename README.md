--[[

i hate making this code

spectating will be added soon so be tuned (nobody even knows about this script)

]]

local ScreenGui = Instance.new("ScreenGui", game.Players.LocalPlayer.PlayerGui)

local AliveNDead = Instance.new("Frame")
local UIAspectRatioConstraint = Instance.new("UIAspectRatioConstraint")
local UIGradient = Instance.new("UIGradient")
local UICorner = Instance.new("UICorner")
local AlivePeople = Instance.new("TextLabel")
local UICorner_2 = Instance.new("UICorner")
local Alive1 = Instance.new("TextLabel")
local Alive2 = Instance.new("TextLabel")
local Alive3 = Instance.new("TextLabel")
local Alive4 = Instance.new("TextLabel")
local Alive5 = Instance.new("TextLabel")
local Alive6 = Instance.new("TextLabel")
local Alive7 = Instance.new("TextLabel")
local Alive8 = Instance.new("TextLabel")
local Alive9 = Instance.new("TextLabel")
local Alive10 = Instance.new("TextLabel")
local Alive11 = Instance.new("TextLabel")
local Alive12 = Instance.new("TextLabel")
local DeadPeople = Instance.new("TextLabel")
local UICorner_3 = Instance.new("UICorner")
local Dead2 = Instance.new("TextLabel")
local Dead3 = Instance.new("TextLabel")
local Dead4 = Instance.new("TextLabel")
local Dead5 = Instance.new("TextLabel")
local Dead6 = Instance.new("TextLabel")
local Dead7 = Instance.new("TextLabel")
local Dead8 = Instance.new("TextLabel")
local Dead9 = Instance.new("TextLabel")
local Dead10 = Instance.new("TextLabel")
local Dead11 = Instance.new("TextLabel")
local Dead12 = Instance.new("TextLabel")
local Dead1 = Instance.new("TextLabel")
local LebraHub = Instance.new("Frame")
local UIGradient_2 = Instance.new("UIGradient")
local UICorner_4 = Instance.new("UICorner")
local Title = Instance.new("TextLabel")
local Welcome = Instance.new("TextLabel")
local SayInChat = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local GetKnife = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local GetGun = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local TpToMurd = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local InfYield = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local TpToSherr = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local ShowAliveNDead = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")

--Properties:

AliveNDead.Name = "AliveNDead"
AliveNDead.Parent = ScreenGui
AliveNDead.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
AliveNDead.BorderColor3 = Color3.fromRGB(0, 0, 0)
AliveNDead.BorderSizePixel = 0
AliveNDead.Position = UDim2.new(0.305172414, 0, 0.052391801, 0)
AliveNDead.Size = UDim2.new(0.388793111, 0, 0.733485222, 0)
AliveNDead.Visible = false

UIAspectRatioConstraint.Parent = AliveNDead
UIAspectRatioConstraint.AspectRatio = 1.401

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 255, 255)), ColorSequenceKeypoint.new(0.01, Color3.fromRGB(83, 83, 83)), ColorSequenceKeypoint.new(0.50, Color3.fromRGB(44, 44, 44)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(62, 62, 62)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))}
UIGradient.Parent = AliveNDead

UICorner.Parent = AliveNDead

AlivePeople.Name = "AlivePeople"
AlivePeople.Parent = AliveNDead
AlivePeople.BackgroundColor3 = Color3.fromRGB(52, 52, 52)
AlivePeople.BackgroundTransparency = 0.900
AlivePeople.BorderColor3 = Color3.fromRGB(0, 0, 0)
AlivePeople.BorderSizePixel = 0
AlivePeople.Position = UDim2.new(0.0266075395, 0, 0.0496894419, 0)
AlivePeople.Size = UDim2.new(0, 200, 0, 38)
AlivePeople.Font = Enum.Font.SourceSans
AlivePeople.Text = "Alive People"
AlivePeople.TextColor3 = Color3.fromRGB(63, 63, 63)
AlivePeople.TextSize = 14.000

UICorner_2.Parent = AlivePeople

Alive1.Name = "Alive1"
Alive1.Parent = AlivePeople
Alive1.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Alive1.BackgroundTransparency = 1.000
Alive1.BorderColor3 = Color3.fromRGB(0, 0, 0)
Alive1.BorderSizePixel = 0
Alive1.Position = UDim2.new(0, 0, 1.26315784, 0)
Alive1.Size = UDim2.new(0, 200, 0, 19)
Alive1.Font = Enum.Font.Gotham
Alive1.Text = "Player1"
Alive1.TextColor3 = Color3.fromRGB(117, 117, 117)
Alive1.TextSize = 14.000

Alive2.Name = "Alive2"
Alive2.Parent = AlivePeople
Alive2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Alive2.BackgroundTransparency = 1.000
Alive2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Alive2.BorderSizePixel = 0
Alive2.Position = UDim2.new(0, 0, 1.76315784, 0)
Alive2.Size = UDim2.new(0, 200, 0, 19)
Alive2.Font = Enum.Font.Gotham
Alive2.Text = "Player1"
Alive2.TextColor3 = Color3.fromRGB(117, 117, 117)
Alive2.TextSize = 14.000

Alive3.Name = "Alive3"
Alive3.Parent = AlivePeople
Alive3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Alive3.BackgroundTransparency = 1.000
Alive3.BorderColor3 = Color3.fromRGB(0, 0, 0)
Alive3.BorderSizePixel = 0
Alive3.Position = UDim2.new(0, 0, 2.26315784, 0)
Alive3.Size = UDim2.new(0, 200, 0, 19)
Alive3.Font = Enum.Font.Gotham
Alive3.Text = "Player1"
Alive3.TextColor3 = Color3.fromRGB(117, 117, 117)
Alive3.TextSize = 14.000

Alive4.Name = "Alive4"
Alive4.Parent = AlivePeople
Alive4.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Alive4.BackgroundTransparency = 1.000
Alive4.BorderColor3 = Color3.fromRGB(0, 0, 0)
Alive4.BorderSizePixel = 0
Alive4.Position = UDim2.new(0, 0, 2.76315784, 0)
Alive4.Size = UDim2.new(0, 200, 0, 19)
Alive4.Font = Enum.Font.Gotham
Alive4.Text = "Player1"
Alive4.TextColor3 = Color3.fromRGB(117, 117, 117)
Alive4.TextSize = 14.000

Alive5.Name = "Alive5"
Alive5.Parent = AlivePeople
Alive5.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Alive5.BackgroundTransparency = 1.000
Alive5.BorderColor3 = Color3.fromRGB(0, 0, 0)
Alive5.BorderSizePixel = 0
Alive5.Position = UDim2.new(0, 0, 3.26315784, 0)
Alive5.Size = UDim2.new(0, 200, 0, 19)
Alive5.Font = Enum.Font.Gotham
Alive5.Text = "Player1"
Alive5.TextColor3 = Color3.fromRGB(117, 117, 117)
Alive5.TextSize = 14.000

Alive6.Name = "Alive6"
Alive6.Parent = AlivePeople
Alive6.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Alive6.BackgroundTransparency = 1.000
Alive6.BorderColor3 = Color3.fromRGB(0, 0, 0)
Alive6.BorderSizePixel = 0
Alive6.Position = UDim2.new(0, 0, 3.76315784, 0)
Alive6.Size = UDim2.new(0, 200, 0, 19)
Alive6.Font = Enum.Font.Gotham
Alive6.Text = "Player1"
Alive6.TextColor3 = Color3.fromRGB(117, 117, 117)
Alive6.TextSize = 14.000

Alive7.Name = "Alive7"
Alive7.Parent = AlivePeople
Alive7.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Alive7.BackgroundTransparency = 1.000
Alive7.BorderColor3 = Color3.fromRGB(0, 0, 0)
Alive7.BorderSizePixel = 0
Alive7.Position = UDim2.new(0, 0, 4.26315784, 0)
Alive7.Size = UDim2.new(0, 200, 0, 19)
Alive7.Font = Enum.Font.Gotham
Alive7.Text = "Player1"
Alive7.TextColor3 = Color3.fromRGB(117, 117, 117)
Alive7.TextSize = 14.000

Alive8.Name = "Alive8"
Alive8.Parent = AlivePeople
Alive8.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Alive8.BackgroundTransparency = 1.000
Alive8.BorderColor3 = Color3.fromRGB(0, 0, 0)
Alive8.BorderSizePixel = 0
Alive8.Position = UDim2.new(0, 0, 4.76315784, 0)
Alive8.Size = UDim2.new(0, 200, 0, 19)
Alive8.Font = Enum.Font.Gotham
Alive8.Text = "Player1"
Alive8.TextColor3 = Color3.fromRGB(117, 117, 117)
Alive8.TextSize = 14.000

Alive9.Name = "Alive9"
Alive9.Parent = AlivePeople
Alive9.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Alive9.BackgroundTransparency = 1.000
Alive9.BorderColor3 = Color3.fromRGB(0, 0, 0)
Alive9.BorderSizePixel = 0
Alive9.Position = UDim2.new(0, 0, 5.26315784, 0)
Alive9.Size = UDim2.new(0, 200, 0, 19)
Alive9.Font = Enum.Font.Gotham
Alive9.Text = "Player1"
Alive9.TextColor3 = Color3.fromRGB(117, 117, 117)
Alive9.TextSize = 14.000

Alive10.Name = "Alive10"
Alive10.Parent = AlivePeople
Alive10.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Alive10.BackgroundTransparency = 1.000
Alive10.BorderColor3 = Color3.fromRGB(0, 0, 0)
Alive10.BorderSizePixel = 0
Alive10.Position = UDim2.new(0, 0, 5.76315784, 0)
Alive10.Size = UDim2.new(0, 200, 0, 19)
Alive10.Font = Enum.Font.Gotham
Alive10.Text = "Player1"
Alive10.TextColor3 = Color3.fromRGB(117, 117, 117)
Alive10.TextSize = 14.000

Alive11.Name = "Alive11"
Alive11.Parent = AlivePeople
Alive11.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Alive11.BackgroundTransparency = 1.000
Alive11.BorderColor3 = Color3.fromRGB(0, 0, 0)
Alive11.BorderSizePixel = 0
Alive11.Position = UDim2.new(0, 0, 6.26315784, 0)
Alive11.Size = UDim2.new(0, 200, 0, 19)
Alive11.Font = Enum.Font.Gotham
Alive11.Text = "Player1"
Alive11.TextColor3 = Color3.fromRGB(117, 117, 117)
Alive11.TextSize = 14.000

Alive12.Name = "Alive12"
Alive12.Parent = AlivePeople
Alive12.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Alive12.BackgroundTransparency = 1.000
Alive12.BorderColor3 = Color3.fromRGB(0, 0, 0)
Alive12.BorderSizePixel = 0
Alive12.Position = UDim2.new(0, 0, 7.21052647, 0)
Alive12.Size = UDim2.new(0, 200, 0, 19)
Alive12.Font = Enum.Font.Gotham
Alive12.Text = "Player1"
Alive12.TextColor3 = Color3.fromRGB(117, 117, 117)
Alive12.TextSize = 14.000

DeadPeople.Name = "DeadPeople"
DeadPeople.Parent = AliveNDead
DeadPeople.BackgroundColor3 = Color3.fromRGB(52, 52, 52)
DeadPeople.BackgroundTransparency = 0.900
DeadPeople.BorderColor3 = Color3.fromRGB(0, 0, 0)
DeadPeople.BorderSizePixel = 0
DeadPeople.Position = UDim2.new(0.509977818, 0, 0.0496894419, 0)
DeadPeople.Size = UDim2.new(0, 200, 0, 38)
DeadPeople.Font = Enum.Font.SourceSans
DeadPeople.Text = "Dead People"
DeadPeople.TextColor3 = Color3.fromRGB(63, 63, 63)
DeadPeople.TextSize = 14.000
DeadPeople.TextWrapped = true

UICorner_3.Parent = DeadPeople

Dead2.Name = "Dead2"
Dead2.Parent = DeadPeople
Dead2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Dead2.BackgroundTransparency = 1.000
Dead2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Dead2.BorderSizePixel = 0
Dead2.Position = UDim2.new(0, 0, 1.76315784, 0)
Dead2.Size = UDim2.new(0, 200, 0, 19)
Dead2.Font = Enum.Font.Gotham
Dead2.Text = "Player1"
Dead2.TextColor3 = Color3.fromRGB(117, 117, 117)
Dead2.TextSize = 14.000

Dead3.Name = "Dead3"
Dead3.Parent = DeadPeople
Dead3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Dead3.BackgroundTransparency = 1.000
Dead3.BorderColor3 = Color3.fromRGB(0, 0, 0)
Dead3.BorderSizePixel = 0
Dead3.Position = UDim2.new(0, 0, 2.26315784, 0)
Dead3.Size = UDim2.new(0, 200, 0, 19)
Dead3.Font = Enum.Font.Gotham
Dead3.Text = "Player1"
Dead3.TextColor3 = Color3.fromRGB(117, 117, 117)
Dead3.TextSize = 14.000

Dead4.Name = "Dead4"
Dead4.Parent = DeadPeople
Dead4.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Dead4.BackgroundTransparency = 1.000
Dead4.BorderColor3 = Color3.fromRGB(0, 0, 0)
Dead4.BorderSizePixel = 0
Dead4.Position = UDim2.new(0, 0, 2.76315784, 0)
Dead4.Size = UDim2.new(0, 200, 0, 19)
Dead4.Font = Enum.Font.Gotham
Dead4.Text = "Player1"
Dead4.TextColor3 = Color3.fromRGB(117, 117, 117)
Dead4.TextSize = 14.000

Dead5.Name = "Dead5"
Dead5.Parent = DeadPeople
Dead5.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Dead5.BackgroundTransparency = 1.000
Dead5.BorderColor3 = Color3.fromRGB(0, 0, 0)
Dead5.BorderSizePixel = 0
Dead5.Position = UDim2.new(0, 0, 3.26315784, 0)
Dead5.Size = UDim2.new(0, 200, 0, 19)
Dead5.Font = Enum.Font.Gotham
Dead5.Text = "Player1"
Dead5.TextColor3 = Color3.fromRGB(117, 117, 117)
Dead5.TextSize = 14.000

Dead6.Name = "Dead6"
Dead6.Parent = DeadPeople
Dead6.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Dead6.BackgroundTransparency = 1.000
Dead6.BorderColor3 = Color3.fromRGB(0, 0, 0)
Dead6.BorderSizePixel = 0
Dead6.Position = UDim2.new(0, 0, 3.76315784, 0)
Dead6.Size = UDim2.new(0, 200, 0, 19)
Dead6.Font = Enum.Font.Gotham
Dead6.Text = "Player1"
Dead6.TextColor3 = Color3.fromRGB(117, 117, 117)
Dead6.TextSize = 14.000

Dead7.Name = "Dead7"
Dead7.Parent = DeadPeople
Dead7.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Dead7.BackgroundTransparency = 1.000
Dead7.BorderColor3 = Color3.fromRGB(0, 0, 0)
Dead7.BorderSizePixel = 0
Dead7.Position = UDim2.new(0, 0, 4.26315784, 0)
Dead7.Size = UDim2.new(0, 200, 0, 19)
Dead7.Font = Enum.Font.Gotham
Dead7.Text = "Player1"
Dead7.TextColor3 = Color3.fromRGB(117, 117, 117)
Dead7.TextSize = 14.000

Dead8.Name = "Dead8"
Dead8.Parent = DeadPeople
Dead8.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Dead8.BackgroundTransparency = 1.000
Dead8.BorderColor3 = Color3.fromRGB(0, 0, 0)
Dead8.BorderSizePixel = 0
Dead8.Position = UDim2.new(0, 0, 4.76315784, 0)
Dead8.Size = UDim2.new(0, 200, 0, 19)
Dead8.Font = Enum.Font.Gotham
Dead8.Text = "Player1"
Dead8.TextColor3 = Color3.fromRGB(117, 117, 117)
Dead8.TextSize = 14.000

Dead9.Name = "Dead9"
Dead9.Parent = DeadPeople
Dead9.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Dead9.BackgroundTransparency = 1.000
Dead9.BorderColor3 = Color3.fromRGB(0, 0, 0)
Dead9.BorderSizePixel = 0
Dead9.Position = UDim2.new(0, 0, 5.26315784, 0)
Dead9.Size = UDim2.new(0, 200, 0, 19)
Dead9.Font = Enum.Font.Gotham
Dead9.Text = "Player1"
Dead9.TextColor3 = Color3.fromRGB(117, 117, 117)
Dead9.TextSize = 14.000

Dead10.Name = "Dead10"
Dead10.Parent = DeadPeople
Dead10.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Dead10.BackgroundTransparency = 1.000
Dead10.BorderColor3 = Color3.fromRGB(0, 0, 0)
Dead10.BorderSizePixel = 0
Dead10.Position = UDim2.new(0, 0, 5.76315784, 0)
Dead10.Size = UDim2.new(0, 200, 0, 19)
Dead10.Font = Enum.Font.Gotham
Dead10.Text = "Player1"
Dead10.TextColor3 = Color3.fromRGB(117, 117, 117)
Dead10.TextSize = 14.000

Dead11.Name = "Dead11"
Dead11.Parent = DeadPeople
Dead11.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Dead11.BackgroundTransparency = 1.000
Dead11.BorderColor3 = Color3.fromRGB(0, 0, 0)
Dead11.BorderSizePixel = 0
Dead11.Position = UDim2.new(0, 0, 6.26315784, 0)
Dead11.Size = UDim2.new(0, 200, 0, 19)
Dead11.Font = Enum.Font.Gotham
Dead11.Text = "Player1"
Dead11.TextColor3 = Color3.fromRGB(117, 117, 117)
Dead11.TextSize = 14.000

Dead12.Name = "Dead12"
Dead12.Parent = DeadPeople
Dead12.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Dead12.BackgroundTransparency = 1.000
Dead12.BorderColor3 = Color3.fromRGB(0, 0, 0)
Dead12.BorderSizePixel = 0
Dead12.Position = UDim2.new(0, 0, 7.21052647, 0)
Dead12.Size = UDim2.new(0, 200, 0, 19)
Dead12.Font = Enum.Font.Gotham
Dead12.Text = "Player1"
Dead12.TextColor3 = Color3.fromRGB(117, 117, 117)
Dead12.TextSize = 14.000

Dead1.Name = "Dead1"
Dead1.Parent = DeadPeople
Dead1.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Dead1.BackgroundTransparency = 1.000
Dead1.BorderColor3 = Color3.fromRGB(0, 0, 0)
Dead1.BorderSizePixel = 0
Dead1.Position = UDim2.new(0, 0, 1.26315784, 0)
Dead1.Size = UDim2.new(0, 200, 0, 19)
Dead1.Font = Enum.Font.Gotham
Dead1.Text = "Player1"
Dead1.TextColor3 = Color3.fromRGB(117, 117, 117)
Dead1.TextSize = 14.000

LebraHub.Name = "LebraHub"
LebraHub.Parent = ScreenGui
LebraHub.BackgroundColor3 = Color3.fromRGB(53, 53, 53)
LebraHub.BorderColor3 = Color3.fromRGB(0, 0, 0)
LebraHub.BorderSizePixel = 0
LebraHub.Position = UDim2.new(0.0991379321, 0, 0.241457865, 0)
LebraHub.Size = UDim2.new(0, 329, 0, 228)

UIGradient_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(117, 117, 117)), ColorSequenceKeypoint.new(0.00, Color3.fromRGB(10, 11, 9)), ColorSequenceKeypoint.new(0.02, Color3.fromRGB(99, 99, 98)), ColorSequenceKeypoint.new(0.27, Color3.fromRGB(78, 78, 77)), ColorSequenceKeypoint.new(0.33, Color3.fromRGB(255, 255, 255)), ColorSequenceKeypoint.new(0.99, Color3.fromRGB(179, 179, 179)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))}
UIGradient_2.Parent = LebraHub

UICorner_4.Parent = LebraHub

Title.Name = "Title"
Title.Parent = LebraHub
Title.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title.BackgroundTransparency = 1.000
Title.BorderColor3 = Color3.fromRGB(0, 0, 0)
Title.BorderSizePixel = 0
Title.Size = UDim2.new(0, 89, 0, 30)
Title.Font = Enum.Font.Unknown
Title.Text = "Lebra Hub"
Title.TextColor3 = Color3.fromRGB(99, 99, 99)
Title.TextSize = 14.000
Title.TextTransparency = 0.520

Welcome.Name = "Welcome"
Welcome.Parent = LebraHub
Welcome.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Welcome.BackgroundTransparency = 1.000
Welcome.BorderColor3 = Color3.fromRGB(0, 0, 0)
Welcome.BorderSizePixel = 0
Welcome.Position = UDim2.new(0, 0, 0.587343454, 0)
Welcome.Size = UDim2.new(0, 89, 0, 30)
Welcome.Font = Enum.Font.Unknown
Welcome.Text = "Welcome, ".. game.Players.LocalPlayer.Name
Welcome.TextColor3 = Color3.fromRGB(99, 99, 99)
Welcome.TextScaled = true
Welcome.TextSize = 14.000
Welcome.TextTransparency = 0.520
Welcome.TextWrapped = true

SayInChat.Name = "SayInChat"
SayInChat.Parent = LebraHub
SayInChat.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
SayInChat.BackgroundTransparency = 0.600
SayInChat.BorderColor3 = Color3.fromRGB(0, 0, 0)
SayInChat.BorderSizePixel = 0
SayInChat.Position = UDim2.new(0.362776011, 0, 0.0228571426, 0)
SayInChat.Size = UDim2.new(0, 87, 0, 21)
SayInChat.Font = Enum.Font.Unknown
SayInChat.Text = "Say Murderer and Sherrif"
SayInChat.TextColor3 = Color3.fromRGB(145, 145, 145)
SayInChat.TextScaled = true
SayInChat.TextSize = 14.000
SayInChat.TextWrapped = true

UICorner_5.Parent = SayInChat

GetKnife.Name = "GetKnife"
GetKnife.Parent = LebraHub
GetKnife.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
GetKnife.BackgroundTransparency = 0.600
GetKnife.BorderColor3 = Color3.fromRGB(0, 0, 0)
GetKnife.BorderSizePixel = 0
GetKnife.Position = UDim2.new(0.656151414, 0, 0.0228571426, 0)
GetKnife.Size = UDim2.new(0, 93, 0, 21)
GetKnife.Font = Enum.Font.Unknown
GetKnife.Text = "Get Knife (fake knife)"
GetKnife.TextColor3 = Color3.fromRGB(145, 145, 145)
GetKnife.TextScaled = true
GetKnife.TextSize = 14.000
GetKnife.TextWrapped = true

UICorner_6.Parent = GetKnife

GetGun.Name = "GetGun"
GetGun.Parent = LebraHub
GetGun.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
GetGun.BackgroundTransparency = 0.600
GetGun.BorderColor3 = Color3.fromRGB(0, 0, 0)
GetGun.BorderSizePixel = 0
GetGun.Position = UDim2.new(0.362775981, 0, 0.161854655, 0)
GetGun.Size = UDim2.new(0, 87, 0, 20)
GetGun.Font = Enum.Font.Unknown
GetGun.Text = "Get Gun (fake gun)"
GetGun.TextColor3 = Color3.fromRGB(145, 145, 145)
GetGun.TextScaled = true
GetGun.TextSize = 14.000
GetGun.TextWrapped = true

UICorner_7.Parent = GetGun

TpToMurd.Name = "TpToMurd"
TpToMurd.Parent = LebraHub
TpToMurd.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
TpToMurd.BackgroundTransparency = 0.600
TpToMurd.BorderColor3 = Color3.fromRGB(0, 0, 0)
TpToMurd.BorderSizePixel = 0
TpToMurd.Position = UDim2.new(0.656151414, 0, 0.16012533, 0)
TpToMurd.Size = UDim2.new(0, 93, 0, 21)
TpToMurd.Font = Enum.Font.Unknown
TpToMurd.Text = "Teleport to Murderer"
TpToMurd.TextColor3 = Color3.fromRGB(145, 145, 145)
TpToMurd.TextScaled = true
TpToMurd.TextSize = 14.000
TpToMurd.TextWrapped = true

UICorner_8.Parent = TpToMurd

InfYield.Name = "InfYield"
InfYield.Parent = LebraHub
InfYield.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
InfYield.BackgroundTransparency = 0.600
InfYield.BorderColor3 = Color3.fromRGB(0, 0, 0)
InfYield.BorderSizePixel = 0
InfYield.Position = UDim2.new(0.672806382, 0, 0.29912287, 0)
InfYield.Size = UDim2.new(0, 87, 0, 21)
InfYield.Font = Enum.Font.Unknown
InfYield.Text = "Inject Infinite Yield"
InfYield.TextColor3 = Color3.fromRGB(145, 145, 145)
InfYield.TextScaled = true
InfYield.TextSize = 14.000
InfYield.TextWrapped = true

UICorner_9.Parent = InfYield

TpToSherr.Name = "TpToSherr"
TpToSherr.Parent = LebraHub
TpToSherr.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
TpToSherr.BackgroundTransparency = 0.600
TpToSherr.BorderColor3 = Color3.fromRGB(0, 0, 0)
TpToSherr.BorderSizePixel = 0
TpToSherr.Position = UDim2.new(0.362775981, 0, 0.29912287, 0)
TpToSherr.Size = UDim2.new(0, 87, 0, 21)
TpToSherr.Font = Enum.Font.Unknown
TpToSherr.Text = "Teleport to Sherrif"
TpToSherr.TextColor3 = Color3.fromRGB(145, 145, 145)
TpToSherr.TextScaled = true
TpToSherr.TextSize = 14.000
TpToSherr.TextWrapped = true

UICorner_10.Parent = TpToSherr

ShowAliveNDead.Name = "ShowAliveNDead"
ShowAliveNDead.Parent = LebraHub
ShowAliveNDead.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
ShowAliveNDead.BackgroundTransparency = 0.600
ShowAliveNDead.BorderColor3 = Color3.fromRGB(0, 0, 0)
ShowAliveNDead.BorderSizePixel = 0
ShowAliveNDead.Position = UDim2.new(0.362775981, 0, 0.448245674, 0)
ShowAliveNDead.Size = UDim2.new(0, 189, 0, 21)
ShowAliveNDead.Font = Enum.Font.Unknown
ShowAliveNDead.Text = "Show Alive And Dead Players"
ShowAliveNDead.TextColor3 = Color3.fromRGB(145, 145, 145)
ShowAliveNDead.TextScaled = true
ShowAliveNDead.TextSize = 14.000
ShowAliveNDead.TextWrapped = true

UICorner_11.Parent = ShowAliveNDead

if ScreenGui then
	game:GetService("StarterGui"):SetCore("SendNotification",{
		Title = "Lebra Hub Installed",
		Text = "Insert to toggle On and Off."
	})
end

SayInChat.MouseButton1Up:Connect(function()

	local function playerWithKnife()

		for _, model in workspace:GetChildren() do

			if model:IsA("Model") then

				local player = game.Players:GetPlayerFromCharacter(model)

				if player then

					local backpack = player:FindFirstChild("Backpack")

					if backpack then

						for _, item in backpack:GetChildren() do

							if item:IsA("Tool") and item.Name == "Knife" then

								return player

							end
						end
					end
				end
			end
		end
		return nil
	end

	local function playerWithGun()

		for _, model in workspace:GetChildren() do

			if model:IsA("Model") then

				local player = game.Players:GetPlayerFromCharacter(model)

				if player then

					local backpack = player:FindFirstChild("Backpack")

					if backpack then

						for _, item in backpack:GetChildren() do

							if item:IsA("Tool") and item.Name == "Gun" then

								return player

							end
						end
					end
				end
			end
		end
		return nil
	end

	local playerWithKnife = playerWithKnife()
	local playerWithGun = playerWithGun()
	if playerWithKnife then
		game:GetService("TextChatService"):WaitForChild("TextChannels"):WaitForChild("RBXGeneral"):SendAsync("Murderer: " .. playerWithKnife.Name)

		task.wait(.1)

		game:GetService("TextChatService"):WaitForChild("TextChannels"):WaitForChild("RBXGeneral"):SendAsync("Sherrif: " .. playerWithGun().Name)
	else
		print("No player with the Knife found.")
	end

end)

GetKnife.MouseButton1Up:Connect(function()

	for _, model in workspace:GetChildren() do

		if model:IsA("Model") then

			local player = game.Players:GetPlayerFromCharacter(model)

			if player then

				local backpack = player:FindFirstChild("Backpack")

				if backpack then

					for _, item in backpack:GetChildren() do

						if item:IsA("Tool") and item.Name == "Knife" then

							local ItemClone = item:Clone()
							ItemClone.Name = "FakeKnife"
							ItemClone.Parent = game.Players.LocalPlayer.Backpack

						end
					end
				end
			end
		end
	end

end)

GetGun.MouseButton1Up:Connect(function()

	for _, model in workspace:GetChildren() do

		if model:IsA("Model") then

			local player = game.Players:GetPlayerFromCharacter(model)

			if player then

				local backpack = player:FindFirstChild("Backpack")

				if backpack then

					for _, item in backpack:GetChildren() do

						if item:IsA("Tool") and item.Name == "Gun" then

							local ItemClone = item:Clone()
							ItemClone.Name = "FakeGun"
							ItemClone.Parent = game.Players.LocalPlayer.Backpack

						end
					end
				end
			end
		end
	end

end)

local uis = game:GetService("UserInputService")
local isToggled = true

uis.InputBegan:Connect(function(input, gps)

	if gps then return end


	if input.KeyCode == Enum.KeyCode.Insert then

		if isToggled == false then
			isToggled = true
			LebraHub.Visible = true
		else
			isToggled = false
			LebraHub.Visible = false
		end

	end

end)

TpToMurd.MouseButton1Up:Connect(function()
	
	local function playerWithKnife()

		for _, model in workspace:GetChildren() do

			if model:IsA("Model") then

				local player = game.Players:GetPlayerFromCharacter(model)

				if player then

					local backpack = player:FindFirstChild("Backpack")

					if backpack then

						for _, item in backpack:GetChildren() do

							if item:IsA("Tool") and item.Name == "Knife" then

								return player

							end
						end
					end
				end
			end
		end
		return nil
	end

	local playerWithKnife = playerWithKnife()
	
	local humrootpart = game.Players.LocalPlayer.Character.HumanoidRootPart
	
	humrootpart.CFrame = playerWithKnife.Character.HumanoidRootPart.CFrame
	
	
end)

TpToMurd.MouseButton1Up:Connect(function()

	local function playerWithGun()

		for _, model in workspace:GetChildren() do

			if model:IsA("Model") then

				local player = game.Players:GetPlayerFromCharacter(model)

				if player then

					local backpack = player:FindFirstChild("Backpack")

					if backpack then

						for _, item in backpack:GetChildren() do

							if item:IsA("Tool") and item.Name == "Gun" then

								return player

							end
						end
					end
				end
			end
		end
		return nil
	end

	local playerWithGun = playerWithGun()

	local humrootpart = game.Players.LocalPlayer.Character.HumanoidRootPart

	humrootpart.CFrame = playerWithGun.Character.HumanoidRootPart.CFrame


end)

InfYield.MouseButton1Up:Connect(function()
	
	loadstring(game:HttpGet("https://raw.githubusercontent.com/edgeiy/infiniteyield/master/source"))()
	
end)

ShowAliveNDead.MouseButton1Up:Connect(function()
	
	AliveNDead.Visible = false
	print("showalivendead thingy in progress man")
	
end)
