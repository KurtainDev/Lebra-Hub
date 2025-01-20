--[[

Script for MM2 (Works on all Executors)

#LebraHub
#MadeByKurtainDevOnRoblox

]]

local ScreenGui = Instance.new("ScreenGui")
ScreenGui.Parent = game.Players.LocalPlayer.PlayerGui

local Frame = Instance.new("Frame")
local UIGradient = Instance.new("UIGradient")
local UICorner = Instance.new("UICorner")
local Title = Instance.new("TextLabel")
local Title2 = Instance.new("TextLabel")
local SayInChat = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local GetKnife = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local GetKnife_2 = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")

--Properties:

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(53, 53, 53)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.0991379321, 0, 0.241457865, 0)
Frame.Size = UDim2.new(0, 317, 0, 175)
Frame.Active = true
Frame.Draggable = true

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(117, 117, 117)), ColorSequenceKeypoint.new(0.00, Color3.fromRGB(10, 11, 9)), ColorSequenceKeypoint.new(0.02, Color3.fromRGB(99, 99, 98)), ColorSequenceKeypoint.new(0.27, Color3.fromRGB(78, 78, 77)), ColorSequenceKeypoint.new(0.33, Color3.fromRGB(255, 255, 255)), ColorSequenceKeypoint.new(0.99, Color3.fromRGB(179, 179, 179)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 255, 255))}
UIGradient.Parent = Frame

UICorner.Parent = Frame

Title.Name = "Title"
Title.Parent = Frame
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

Title2.Name = "Title2"
Title2.Parent = Frame
Title2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title2.BackgroundTransparency = 1.000
Title2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Title2.BorderSizePixel = 0
Title2.Position = UDim2.new(0, 0, 0.828571439, 0)
Title2.Size = UDim2.new(0, 89, 0, 30)
Title2.Font = Enum.Font.Unknown
Title2.Text = "MM2 Exploit"
Title2.TextColor3 = Color3.fromRGB(99, 99, 99)
Title2.TextSize = 14.000
Title2.TextTransparency = 0.520

SayInChat.Name = "SayInChat"
SayInChat.Parent = Frame
SayInChat.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
SayInChat.BackgroundTransparency = 0.600
SayInChat.BorderColor3 = Color3.fromRGB(0, 0, 0)
SayInChat.BorderSizePixel = 0
SayInChat.Position = UDim2.new(0.362776011, 0, 0.0514285713, 0)
SayInChat.Size = UDim2.new(0, 193, 0, 33)
SayInChat.Font = Enum.Font.Unknown
SayInChat.Text = "Say Murderer and Sherrif"
SayInChat.TextColor3 = Color3.fromRGB(145, 145, 145)
SayInChat.TextSize = 14.000

UICorner_2.Parent = SayInChat

GetKnife.Name = "GetKnife"
GetKnife.Parent = Frame
GetKnife.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
GetKnife.BackgroundTransparency = 0.600
GetKnife.BorderColor3 = Color3.fromRGB(0, 0, 0)
GetKnife.BorderSizePixel = 0
GetKnife.Position = UDim2.new(0.362776011, 0, 0.405714273, 0)
GetKnife.Size = UDim2.new(0, 193, 0, 33)
GetKnife.Font = Enum.Font.Unknown
GetKnife.Text = "Get Knife (fake knife)"
GetKnife.TextColor3 = Color3.fromRGB(145, 145, 145)
GetKnife.TextSize = 14.000

UICorner_3.Parent = GetKnife

GetKnife_2.Name = "GetKnife"
GetKnife_2.Parent = Frame
GetKnife_2.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
GetKnife_2.BackgroundTransparency = 0.600
GetKnife_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
GetKnife_2.BorderSizePixel = 0
GetKnife_2.Position = UDim2.new(0.362776011, 0, 0.742857158, 0)
GetKnife_2.Size = UDim2.new(0, 193, 0, 33)
GetKnife_2.Font = Enum.Font.Unknown
GetKnife_2.Text = "Get Gun (fake gun)"
GetKnife_2.TextColor3 = Color3.fromRGB(145, 145, 145)
GetKnife_2.TextSize = 14.000

UICorner_4.Parent = GetKnife_2

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
		game.Chat:Chat(game.Players.LocalPlayer.Character, "Murderer: " .. playerWithKnife.Name)
		
		task.wait(.5)
		
		game.Chat:Chat(game.Players.LocalPlayer.Character, "Sherrif: " .. playerWithGun.Name)
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

GetKnife.MouseButton1Up:Connect(function()

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
			ScreenGui.Enabled = true
		else
			isToggled = false
			ScreenGui.Enabled = false
		end
		
	end
	
end)
