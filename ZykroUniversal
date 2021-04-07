local Gui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local NoClip = Instance.new("TextButton")
local Fly = Instance.new("TextButton")
local INFJUMP = Instance.new("TextButton")
local Admin = Instance.new("TextButton")
local Jump = Instance.new("TextButton")
local Speed = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local TextButton = Instance.new("TextButton")
local Open = Instance.new("ScreenGui")
local TextButton_2 = Instance.new("TextButton")

--Properties:

Gui.Name = "Gui"
Gui.Parent = game.CoreGui
Gui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = Gui
Frame.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
Frame.BorderColor3 = Color3.fromRGB(20, 20, 20)
Frame.BorderSizePixel = 5
Frame.Position = UDim2.new(0.14453125, 0, 0.383219957, 0)
Frame.Size = UDim2.new(0, 433, 0, 124)
Frame.Draggable = true

NoClip.Name = "NoClip"
NoClip.Parent = Frame
NoClip.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
NoClip.BorderSizePixel = 0
NoClip.Position = UDim2.new(0.0190729927, 0, 0.564285576, 0)
NoClip.Size = UDim2.new(0, 132, 0, 39)
NoClip.Font = Enum.Font.Fantasy
NoClip.Text = "NoClip"
NoClip.TextColor3 = Color3.fromRGB(255, 255, 255)
NoClip.TextSize = 14.000
NoClip.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
NoClip.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/Q0xxvZcB"))()
end)

Fly.Name = "Fly"
Fly.Parent = Frame
Fly.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
Fly.BorderSizePixel = 0
Fly.Position = UDim2.new(0.346319318, 0, 0.249996379, 0)
Fly.Size = UDim2.new(0, 132, 0, 44)
Fly.Font = Enum.Font.Fantasy
Fly.Text = "Fly [Might Get Kick!]"
Fly.TextColor3 = Color3.fromRGB(255, 255, 255)
Fly.TextSize = 14.000
Fly.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Fly.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/mmeeW8bc"))()
end)

INFJUMP.Name = "INFJUMP"
INFJUMP.Parent = Frame
INFJUMP.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
INFJUMP.BorderSizePixel = 0
INFJUMP.Position = UDim2.new(0.672818661, 0, 0.249996379, 0)
INFJUMP.Size = UDim2.new(0, 132, 0, 44)
INFJUMP.Font = Enum.Font.Fantasy
INFJUMP.Text = "Infinite Jump"
INFJUMP.TextColor3 = Color3.fromRGB(255, 255, 255)
INFJUMP.TextSize = 14.000
INFJUMP.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
INFJUMP.MouseButton1Down:connect(function()
	local Player = game:GetService'Players'.LocalPlayer;
	local UIS = game:GetService'UserInputService';

	_G.JumpHeight = 50;

	function Action(Object, Function) if Object ~= nil then Function(Object); end end

	UIS.InputBegan:connect(function(UserInput)
		if UserInput.UserInputType == Enum.UserInputType.Keyboard and UserInput.KeyCode == Enum.KeyCode.Space then
			Action(Player.Character.Humanoid, function(self)
				if self:GetState() == Enum.HumanoidStateType.Jumping or self:GetState() == Enum.HumanoidStateType.Freefall then
					Action(self.Parent.HumanoidRootPart, function(self)
						self.Velocity = Vector3.new(0, _G.JumpHeight, 0);
					end)
				end
			end)
		end
	end)
end)

Admin.Name = "Admin"
Admin.Parent = Frame
Admin.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
Admin.BorderSizePixel = 0
Admin.Position = UDim2.new(0.670509279, 0, 0.564285576, 0)
Admin.Size = UDim2.new(0, 132, 0, 40)
Admin.Font = Enum.Font.Fantasy
Admin.Text = "Admin Commands | Buggy"
Admin.TextColor3 = Color3.fromRGB(255, 255, 255)
Admin.TextSize = 10.000
Admin.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Admin.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
end)

Jump.Name = "Jump"
Jump.Parent = Frame
Jump.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
Jump.BorderSizePixel = 0
Jump.Position = UDim2.new(0.346319318, 0, 0.564285576, 0)
Jump.Size = UDim2.new(0, 132, 0, 40)
Jump.Font = Enum.Font.Fantasy
Jump.Text = "Ctrl + Click Destroy"
Jump.TextColor3 = Color3.fromRGB(255, 255, 255)
Jump.TextSize = 10.000
Jump.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Jump.MouseButton1Down:connect(function()
	local Plr = game:GetService("Players").LocalPlayer
	local Mouse = Plr:GetMouse()

	Mouse.Button1Down:connect(function()
		if not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) then return end
		if not Mouse.Target then return end
		Mouse.Target:Destroy()
	end)
end)

Speed.Name = "Speed"
Speed.Parent = Frame
Speed.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
Speed.BorderSizePixel = 0
Speed.Position = UDim2.new(0.0190729648, 0, 0.250992954, 0)
Speed.Size = UDim2.new(0, 132, 0, 44)
Speed.Font = Enum.Font.Fantasy
Speed.Text = "Speed Hack"
Speed.TextColor3 = Color3.fromRGB(255, 255, 255)
Speed.TextSize = 14.000
Speed.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Speed.MouseButton1Down:connect(function()

	local player = game.Players.LocalPlayer
	local mouse = player:GetMouse()
	local runservice = game:GetService("RunService")
	local noclip = false

	local msg = Instance.new("Message", player.PlayerGui)
	msg.Text = "Thank You For Using My Scripts, I Hope You Enjoy The Free Scripts I Made, Kindly Press (P) to destroy"

	runservice.Stepped:Connect(function()
		if noclip then
			player.Character.Humanoid:ChangeState(11)
		end
	end)

	mouse.KeyDown:Connect(function(key)
		if key == "p" then
			msg:Destroy()
		end
	end)

	Speed = "200" -- Only Change The Number For The Script To Work!

	player = game.Players.LocalPlayer.Character
	power = "WalkSpeed"
	player.Humanoid[power] = Speed
	wait()
	player.HumanoidRootPart.CustomPhysicalProperties = PhysicalProperties.new(9e99, 9e99, 9e99, 9e99, 9e99)

end)


TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.0422704965, 0, -0.00317749381, 0)
TextLabel.Size = UDim2.new(0, 74, 0, 26)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Zykroo+ | Universal"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 14.000
