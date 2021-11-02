-- Gui to Lua
-- Version: 3.2

-- Instances:

local Main = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local MainText = Instance.new("TextLabel")
local PlayerInformationLabel = Instance.new("ImageLabel")
local UICorner = Instance.new("UICorner")
local UICorner_2 = Instance.new("UICorner")
local PlayerName = Instance.new("TextLabel")
local Whitelist = Instance.new("TextLabel")
local MainTab = Instance.new("TextButton")
local Seperater = Instance.new("Frame")
local LocalPlayerTab = Instance.new("TextButton")
local MainThing = Instance.new("ScrollingFrame")
local CrashServer = Instance.new("Frame")
local CrashSrvText = Instance.new("TextLabel")
local RunButtonCrash = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local Information = Instance.new("TextLabel")
local UICorner_4 = Instance.new("UICorner")
local RateMyAvatarscript = Instance.new("Frame")
local RateMeText = Instance.new("TextLabel")
local RunCoolScript = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local Information_2 = Instance.new("TextLabel")
local UICorner_6 = Instance.new("UICorner")
local Rtx = Instance.new("Frame")
local RtxText = Instance.new("TextLabel")
local RunEnchanceGrapics = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local Information_3 = Instance.new("TextLabel")
local UICorner_8 = Instance.new("UICorner")
local Invis = Instance.new("Frame")
local InvisTxt = Instance.new("TextLabel")
local RuninvisScript = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local Information_4 = Instance.new("TextLabel")
local UICorner_10 = Instance.new("UICorner")
local ChatHax = Instance.new("Frame")
local Chathaxtxt = Instance.new("TextLabel")
local Runchathaxscript = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local Information_5 = Instance.new("TextLabel")
local UICorner_12 = Instance.new("UICorner")
local Headless = Instance.new("Frame")
local HeadlessTxt = Instance.new("TextLabel")
local Runchathaxscript_2 = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")
local Information_6 = Instance.new("TextLabel")
local UICorner_14 = Instance.new("UICorner")
local RemoteSpy = Instance.new("Frame")
local RemoteSpyTxt = Instance.new("TextLabel")
local RunRemoteSpy = Instance.new("TextButton")
local UICorner_15 = Instance.new("UICorner")
local Information_7 = Instance.new("TextLabel")
local UICorner_16 = Instance.new("UICorner")
local Fates = Instance.new("Frame")
local FatesAdmintxt = Instance.new("TextLabel")
local RunFatesAdmin = Instance.new("TextButton")
local UICorner_17 = Instance.new("UICorner")
local Information_8 = Instance.new("TextLabel")
local UICorner_18 = Instance.new("UICorner")
local Netless = Instance.new("Frame")
local NetlessTxt = Instance.new("TextLabel")
local RunNetless = Instance.new("TextButton")
local UICorner_19 = Instance.new("UICorner")
local Information_9 = Instance.new("TextLabel")
local UICorner_20 = Instance.new("UICorner")
local Syntax = Instance.new("Frame")
local SyntaxTxt = Instance.new("TextLabel")
local RunSyntax = Instance.new("TextButton")
local UICorner_21 = Instance.new("UICorner")
local Information_10 = Instance.new("TextLabel")
local UICorner_22 = Instance.new("UICorner")
local EmoteGui = Instance.new("Frame")
local Emoteguitxt = Instance.new("TextLabel")
local RunEmotegui = Instance.new("TextButton")
local UICorner_23 = Instance.new("UICorner")
local Information_11 = Instance.new("TextLabel")
local UICorner_24 = Instance.new("UICorner")
local BackFlip = Instance.new("Frame")
local BackFliptxt = Instance.new("TextLabel")
local RunBackFlipHub = Instance.new("TextButton")
local UICorner_25 = Instance.new("UICorner")
local Information_12 = Instance.new("TextLabel")
local UICorner_26 = Instance.new("UICorner")
local CharacterThing = Instance.new("ScrollingFrame")
local Walkspeed = Instance.new("Frame")
local WalkspeedGuitxt = Instance.new("TextLabel")
local Information_13 = Instance.new("TextLabel")
local UICorner_27 = Instance.new("UICorner")
local Walkspeed_2 = Instance.new("TextBox")
local UICorner_28 = Instance.new("UICorner")
local Jumppower = Instance.new("Frame")
local Jumppowertxt = Instance.new("TextLabel")
local Information_14 = Instance.new("TextLabel")
local UICorner_29 = Instance.new("UICorner")
local Jumppower_2 = Instance.new("TextBox")
local UICorner_30 = Instance.new("UICorner")
local Fly = Instance.new("Frame")
local Jumppowertxt_2 = Instance.new("TextLabel")
local Information_15 = Instance.new("TextLabel")
local UICorner_31 = Instance.new("UICorner")
local RunflyScript = Instance.new("TextButton")
local UICorner_32 = Instance.new("UICorner")
local Noclip = Instance.new("Frame")
local NoclipTxt = Instance.new("TextLabel")
local Information_16 = Instance.new("TextLabel")
local UICorner_33 = Instance.new("UICorner")
local runNoclipScript = Instance.new("TextButton")
local UICorner_34 = Instance.new("UICorner")

--Properties:

Main.Name = "Main"
Main.Parent = game.CoreGui
Main.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = Main
Frame.BackgroundColor3 = Color3.fromRGB(7, 13, 36)
Frame.Position = UDim2.new(0.1547492, 0, 0.163723916, 0)
Frame.Size = UDim2.new(0, 651, 0, 381)
Frame.Active = true
Frame.Draggable = true

MainText.Name = "MainText"
MainText.Parent = Frame
MainText.BackgroundColor3 = Color3.fromRGB(13, 17, 48)
MainText.BackgroundTransparency = 0.400
MainText.Size = UDim2.new(0, 149, 0, 40)
MainText.Font = Enum.Font.Gotham
MainText.Text = "ChillHub"
MainText.TextColor3 = Color3.fromRGB(255, 255, 255)
MainText.TextSize = 24.000

PlayerInformationLabel.Name = "PlayerInformationLabel"
PlayerInformationLabel.Parent = Frame
PlayerInformationLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PlayerInformationLabel.BackgroundTransparency = 1.000
PlayerInformationLabel.Position = UDim2.new(0, 0, 0.873848855, 0)
PlayerInformationLabel.Size = UDim2.new(0, 48, 0, 43)
PlayerInformationLabel.Image = game.Players:GetUserThumbnailAsync(game.Players.LocalPlayer.UserId,Enum.ThumbnailType.HeadShot,Enum.ThumbnailSize.Size420x420)

UICorner.CornerRadius = UDim.new(1, 0)
UICorner.Parent = PlayerInformationLabel

UICorner_2.Parent = Frame

PlayerName.Name = "PlayerName"
PlayerName.Parent = Frame
PlayerName.BackgroundColor3 = Color3.fromRGB(13, 17, 48)
PlayerName.BackgroundTransparency = 0.400
PlayerName.Position = UDim2.new(0.131707326, 0, 0.891812921, 0)
PlayerName.Size = UDim2.new(0, 74, 0, 18)
PlayerName.Font = Enum.Font.Gotham
PlayerName.Text = game.Players.LocalPlayer.Name
PlayerName.TextColor3 = Color3.fromRGB(255, 255, 255)
PlayerName.TextSize = 24.000

Whitelist.Name = "Whitelist"
Whitelist.Parent = Frame
Whitelist.BackgroundColor3 = Color3.fromRGB(13, 17, 48)
Whitelist.BackgroundTransparency = 0.400
Whitelist.Position = UDim2.new(0.144715443, 0, 0.942711115, 0)
Whitelist.Size = UDim2.new(0, 60, 0, 19)
Whitelist.Font = Enum.Font.Gotham
Whitelist.Text = "Premium"
Whitelist.TextColor3 = Color3.fromRGB(255, 255, 255)
Whitelist.TextSize = 14.000
Whitelist.TextTransparency = 0.580

MainTab.Name = "MainTab"
MainTab.Parent = Frame
MainTab.BackgroundColor3 = Color3.fromRGB(7, 13, 36)
MainTab.BorderColor3 = Color3.fromRGB(7, 13, 36)
MainTab.Position = UDim2.new(0.0138248848, 0, 0.103972659, 0)
MainTab.Size = UDim2.new(0, 130, 0, 48)
MainTab.Font = Enum.Font.Gotham
MainTab.Text = "Main"
MainTab.TextColor3 = Color3.fromRGB(255, 255, 255)
MainTab.TextSize = 19.000

Seperater.Name = "Seperater"
Seperater.Parent = Frame
Seperater.BackgroundColor3 = Color3.fromRGB(13, 17, 48)
Seperater.Position = UDim2.new(0.228878647, 0, 0.104986876, 0)
Seperater.Size = UDim2.new(0, 502, 0, 32)

LocalPlayerTab.Name = "LocalPlayerTab"
LocalPlayerTab.Parent = Frame
LocalPlayerTab.BackgroundColor3 = Color3.fromRGB(7, 13, 36)
LocalPlayerTab.BorderColor3 = Color3.fromRGB(7, 13, 36)
LocalPlayerTab.Position = UDim2.new(0.0138248848, 0, 0.25095427, 0)
LocalPlayerTab.Size = UDim2.new(0, 130, 0, 48)
LocalPlayerTab.Font = Enum.Font.Gotham
LocalPlayerTab.Text = "LocalPlayer"
LocalPlayerTab.TextColor3 = Color3.fromRGB(255, 255, 255)
LocalPlayerTab.TextSize = 19.000

MainThing.Name = "MainThing"
MainThing.Parent = Frame
MainThing.Active = true
MainThing.BackgroundColor3 = Color3.fromRGB(13, 17, 48)
MainThing.Position = UDim2.new(0.228878602, 0, 0.199475065, 0)
MainThing.Size = UDim2.new(0, 502, 0, 267)
MainThing.Visible = false

CrashServer.Name = "CrashServer"
CrashServer.Parent = MainThing
CrashServer.BackgroundColor3 = Color3.fromRGB(27, 36, 103)
CrashServer.Position = UDim2.new(0, 0, -0.00129745342, 0)
CrashServer.Size = UDim2.new(0, 143, 0, 146)

CrashSrvText.Name = "CrashSrvText"
CrashSrvText.Parent = CrashServer
CrashSrvText.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CrashSrvText.BackgroundTransparency = 1.000
CrashSrvText.Position = UDim2.new(0.020979017, 0, 0.0342465751, 0)
CrashSrvText.Size = UDim2.new(0, 140, 0, 50)
CrashSrvText.Font = Enum.Font.Gotham
CrashSrvText.Text = "Crash Server"
CrashSrvText.TextColor3 = Color3.fromRGB(255, 255, 255)
CrashSrvText.TextSize = 24.000

RunButtonCrash.Name = "RunButtonCrash"
RunButtonCrash.Parent = CrashServer
RunButtonCrash.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
RunButtonCrash.Position = UDim2.new(0.0559440553, 0, 0.531522274, 0)
RunButtonCrash.Size = UDim2.new(0, 126, 0, 49)
RunButtonCrash.Font = Enum.Font.Gotham
RunButtonCrash.Text = "Run"
RunButtonCrash.TextColor3 = Color3.fromRGB(255, 255, 255)
RunButtonCrash.TextSize = 24.000
RunButtonCrash.MouseButton1Click:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/plugss/ratemyavatar/main/README.md'),true))()

end)

UICorner_3.Parent = RunButtonCrash

Information.Name = "Information"
Information.Parent = CrashServer
Information.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Information.BackgroundTransparency = 1.000
Information.Position = UDim2.new(0.125874132, 0, 0.294520557, 0)
Information.Size = UDim2.new(0, 110, 0, 34)
Information.Font = Enum.Font.Gotham
Information.Text = "Crashes with an instant"
Information.TextColor3 = Color3.fromRGB(0, 0, 0)
Information.TextSize = 13.000
Information.TextTransparency = 0.580

UICorner_4.Parent = CrashServer

RateMyAvatarscript.Name = "Rate My Avatar script"
RateMyAvatarscript.Parent = MainThing
RateMyAvatarscript.BackgroundColor3 = Color3.fromRGB(27, 36, 103)
RateMyAvatarscript.Position = UDim2.new(0.32470119, 0, 0.00526422635, 0)
RateMyAvatarscript.Size = UDim2.new(0, 143, 0, 146)

RateMeText.Name = "RateMeText"
RateMeText.Parent = RateMyAvatarscript
RateMeText.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
RateMeText.BackgroundTransparency = 1.000
RateMeText.Position = UDim2.new(0.020979017, 0, 0, 0)
RateMeText.Size = UDim2.new(0, 140, 0, 50)
RateMeText.Font = Enum.Font.Gotham
RateMeText.Text = "Cool script"
RateMeText.TextColor3 = Color3.fromRGB(255, 255, 255)
RateMeText.TextSize = 24.000

RunCoolScript.Name = "RunCoolScript"
RunCoolScript.Parent = RateMyAvatarscript
RunCoolScript.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
RunCoolScript.Position = UDim2.new(0.0559440553, 0, 0.531522274, 0)
RunCoolScript.Size = UDim2.new(0, 126, 0, 49)
RunCoolScript.Font = Enum.Font.Gotham
RunCoolScript.Text = "Run"
RunCoolScript.TextColor3 = Color3.fromRGB(255, 255, 255)
RunCoolScript.TextSize = 24.000
RunCoolScript.MouseButton1Click:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Emplic/m/main/ecool"))()
end)

UICorner_5.Parent = RunCoolScript

Information_2.Name = "Information"
Information_2.Parent = RateMyAvatarscript
Information_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Information_2.BackgroundTransparency = 1.000
Information_2.Position = UDim2.new(0.125874132, 0, 0.294520557, 0)
Information_2.Size = UDim2.new(0, 110, 0, 34)
Information_2.Font = Enum.Font.Gotham
Information_2.Text = "Rma script, OP."
Information_2.TextColor3 = Color3.fromRGB(0, 0, 0)
Information_2.TextSize = 13.000
Information_2.TextTransparency = 0.580

UICorner_6.Parent = RateMyAvatarscript

Rtx.Name = "Rtx"
Rtx.Parent = MainThing
Rtx.BackgroundColor3 = Color3.fromRGB(27, 36, 103)
Rtx.Position = UDim2.new(0.643426359, 0, 0.00526422635, 0)
Rtx.Size = UDim2.new(0, 143, 0, 146)

RtxText.Name = "RtxText"
RtxText.Parent = Rtx
RtxText.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
RtxText.BackgroundTransparency = 1.000
RtxText.Position = UDim2.new(0.020979017, 0, 0, 0)
RtxText.Size = UDim2.new(0, 140, 0, 50)
RtxText.Font = Enum.Font.Gotham
RtxText.Text = "Rtx graphics"
RtxText.TextColor3 = Color3.fromRGB(255, 255, 255)
RtxText.TextSize = 24.000

RunEnchanceGrapics.Name = "RunEnchanceGrapics"
RunEnchanceGrapics.Parent = Rtx
RunEnchanceGrapics.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
RunEnchanceGrapics.Position = UDim2.new(0.0559440553, 0, 0.531522274, 0)
RunEnchanceGrapics.Size = UDim2.new(0, 126, 0, 49)
RunEnchanceGrapics.Font = Enum.Font.Gotham
RunEnchanceGrapics.Text = "Run"
RunEnchanceGrapics.TextColor3 = Color3.fromRGB(255, 255, 255)
RunEnchanceGrapics.TextSize = 24.000
RunEnchanceGrapics.MouseButton1Click:connect(function()
	-- Roblox Graphics Enhancher
	local light = game.Lighting
	for i, v in pairs(light:GetChildren()) do
		v:Destroy()
	end

	local ter = workspace.Terrain
	local color = Instance.new("ColorCorrectionEffect")
	local bloom = Instance.new("BloomEffect")
	local sun = Instance.new("SunRaysEffect")
	local blur = Instance.new("BlurEffect")

	color.Parent = light
	bloom.Parent = light
	sun.Parent = light
	blur.Parent = light

	-- enable or disable shit

	local config = {

		Terrain = true;
		ColorCorrection = true;
		Sun = true;
		Lighting = true;
		BloomEffect = true;

	}

	-- settings {

	color.Enabled = false
	color.Contrast = 0.15
	color.Brightness = 0.1
	color.Saturation = 0.25
	color.TintColor = Color3.fromRGB(255, 222, 211)

	bloom.Enabled = false
	bloom.Intensity = 0.1

	sun.Enabled = false
	sun.Intensity = 0.2
	sun.Spread = 1

	bloom.Enabled = false
	bloom.Intensity = 0.05
	bloom.Size = 32
	bloom.Threshold = 1

	blur.Enabled = false
	blur.Size = 6

	-- settings }


	if config.ColorCorrection then
		color.Enabled = true
	end


	if config.Sun then
		sun.Enabled = true
	end


	if config.Terrain then
		-- settings {
		ter.WaterColor = Color3.fromRGB(10, 10, 24)
		ter.WaterWaveSize = 0.15
		ter.WaterWaveSpeed = 22
		ter.WaterTransparency = 1
		ter.WaterReflectance = 0.05
		-- settings }
	end


	if config.Lighting then
		-- settings {
		light.Ambient = Color3.fromRGB(0, 0, 0)
		light.Brightness = 4
		light.ColorShift_Bottom = Color3.fromRGB(0, 0, 0)
		light.ColorShift_Top = Color3.fromRGB(0, 0, 0)
		light.ExposureCompensation = 0
		light.FogColor = Color3.fromRGB(132, 132, 132)
		light.GlobalShadows = true
		light.OutdoorAmbient = Color3.fromRGB(112, 117, 128)
		light.Outlines = false
		-- settings }
	end
end)

UICorner_7.Parent = RunEnchanceGrapics

Information_3.Name = "Information"
Information_3.Parent = Rtx
Information_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Information_3.BackgroundTransparency = 1.000
Information_3.Position = UDim2.new(0.125874132, 0, 0.294520557, 0)
Information_3.Size = UDim2.new(0, 110, 0, 34)
Information_3.Font = Enum.Font.Gotham
Information_3.Text = "Rtx graphics, cool."
Information_3.TextColor3 = Color3.fromRGB(0, 0, 0)
Information_3.TextSize = 13.000
Information_3.TextTransparency = 0.580

UICorner_8.Parent = Rtx

Invis.Name = "Invis"
Invis.Parent = MainThing
Invis.BackgroundColor3 = Color3.fromRGB(27, 36, 103)
Invis.Position = UDim2.new(-0.00199198723, 0, 0.223111987, 0)
Invis.Size = UDim2.new(0, 143, 0, 146)

InvisTxt.Name = "InvisTxt"
InvisTxt.Parent = Invis
InvisTxt.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
InvisTxt.BackgroundTransparency = 1.000
InvisTxt.Position = UDim2.new(0.020979017, 0, 0, 0)
InvisTxt.Size = UDim2.new(0, 140, 0, 50)
InvisTxt.Font = Enum.Font.Gotham
InvisTxt.Text = "Invisible"
InvisTxt.TextColor3 = Color3.fromRGB(255, 255, 255)
InvisTxt.TextSize = 24.000

RuninvisScript.Name = "RuninvisScript"
RuninvisScript.Parent = Invis
RuninvisScript.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
RuninvisScript.Position = UDim2.new(0.0559440553, 0, 0.531522274, 0)
RuninvisScript.Size = UDim2.new(0, 126, 0, 49)
RuninvisScript.Font = Enum.Font.Gotham
RuninvisScript.Text = "Run"
RuninvisScript.TextColor3 = Color3.fromRGB(255, 255, 255)
RuninvisScript.TextSize = 24.000
RuninvisScript.MouseButton1Click:connect(function()
	loadstring(game:HttpGet("https://gist.githubusercontent.com/skid123skidlol/cd0d2dce51b3f20ad1aac941da06a1a1/raw/bd62009d461c948d466222f4f9333f9420130fbb/%257BFE%257D%2520Invisible%2520Tool%2520(can%2520hold%2520tools)",true))()
end)

UICorner_9.Parent = RuninvisScript

Information_4.Name = "Information"
Information_4.Parent = Invis
Information_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Information_4.BackgroundTransparency = 1.000
Information_4.Position = UDim2.new(0.363636136, 0, 0.246575341, 0)
Information_4.Size = UDim2.new(0, 38, 0, 28)
Information_4.Font = Enum.Font.Gotham
Information_4.Text = "Can make you invisible"
Information_4.TextColor3 = Color3.fromRGB(0, 0, 0)
Information_4.TextSize = 13.000
Information_4.TextTransparency = 0.580

UICorner_10.Parent = Invis

ChatHax.Name = "ChatHax"
ChatHax.Parent = MainThing
ChatHax.BackgroundColor3 = Color3.fromRGB(27, 36, 103)
ChatHax.Position = UDim2.new(0.326693267, 0, 0.223111987, 0)
ChatHax.Size = UDim2.new(0, 143, 0, 146)

Chathaxtxt.Name = "Chathaxtxt"
Chathaxtxt.Parent = ChatHax
Chathaxtxt.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Chathaxtxt.BackgroundTransparency = 1.000
Chathaxtxt.Position = UDim2.new(0.020979017, 0, 0, 0)
Chathaxtxt.Size = UDim2.new(0, 140, 0, 50)
Chathaxtxt.Font = Enum.Font.Gotham
Chathaxtxt.Text = "Chat Hax"
Chathaxtxt.TextColor3 = Color3.fromRGB(255, 255, 255)
Chathaxtxt.TextSize = 24.000

Runchathaxscript.Name = "Runchathaxscript"
Runchathaxscript.Parent = ChatHax
Runchathaxscript.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Runchathaxscript.Position = UDim2.new(0.0559440553, 0, 0.531522274, 0)
Runchathaxscript.Size = UDim2.new(0, 126, 0, 49)
Runchathaxscript.Font = Enum.Font.Gotham
Runchathaxscript.Text = "Run"
Runchathaxscript.TextColor3 = Color3.fromRGB(255, 255, 255)
Runchathaxscript.TextSize = 24.000
Runchathaxscript.MouseButton1Click:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/offperms/chathex/main/pog"))()
end)

UICorner_11.Parent = Runchathaxscript

Information_5.Name = "Information"
Information_5.Parent = ChatHax
Information_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Information_5.BackgroundTransparency = 1.000
Information_5.Position = UDim2.new(0.363636136, 0, 0.246575341, 0)
Information_5.Size = UDim2.new(0, 38, 0, 28)
Information_5.Font = Enum.Font.Gotham
Information_5.Text = "runs fechathax"
Information_5.TextColor3 = Color3.fromRGB(0, 0, 0)
Information_5.TextSize = 13.000
Information_5.TextTransparency = 0.580

UICorner_12.Parent = ChatHax

Headless.Name = "Headless"
Headless.Parent = MainThing
Headless.BackgroundColor3 = Color3.fromRGB(27, 36, 103)
Headless.Position = UDim2.new(0.641434312, 0, 0.223111987, 0)
Headless.Size = UDim2.new(0, 143, 0, 146)

HeadlessTxt.Name = "HeadlessTxt"
HeadlessTxt.Parent = Headless
HeadlessTxt.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
HeadlessTxt.BackgroundTransparency = 1.000
HeadlessTxt.Position = UDim2.new(0.020979017, 0, 0, 0)
HeadlessTxt.Size = UDim2.new(0, 140, 0, 50)
HeadlessTxt.Font = Enum.Font.Gotham
HeadlessTxt.Text = "Headless"
HeadlessTxt.TextColor3 = Color3.fromRGB(255, 255, 255)
HeadlessTxt.TextSize = 24.000

Runchathaxscript_2.Name = "Runchathaxscript"
Runchathaxscript_2.Parent = Headless
Runchathaxscript_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Runchathaxscript_2.Position = UDim2.new(0.0559440553, 0, 0.531522274, 0)
Runchathaxscript_2.Size = UDim2.new(0, 126, 0, 49)
Runchathaxscript_2.Font = Enum.Font.Gotham
Runchathaxscript_2.Text = "Run"
Runchathaxscript_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Runchathaxscript_2.TextSize = 24.000
Runchathaxscript_2.MouseButton1Click:connect(function()
	local lp = game:GetService "Players".LocalPlayer
	if lp.Character:FindFirstChild "Head" then
		local char = lp.Character
		char.Archivable = true
		local new = char:Clone()
		new.Parent = workspace
		lp.Character = new
		wait(2)
		local oldhum = char:FindFirstChildWhichIsA "Humanoid"
		local newhum = oldhum:Clone()
		newhum.Parent = char
		newhum.RequiresNeck = false
		oldhum.Parent = nil
		wait(2)
		lp.Character = char
		new:Destroy()
		wait(1)
		newhum:GetPropertyChangedSignal("Health"):Connect(
		function()
			if newhum.Health <= 0 then
				oldhum.Parent = lp.Character
				wait(1)
				oldhum:Destroy()
			end
		end)
		workspace.CurrentCamera.CameraSubject = char
		if char:FindFirstChild "Animate" then
			char.Animate.Disabled = true
			wait(.1)
			char.Animate.Disabled = false
		end
		lp.Character:FindFirstChild "Head":Destroy()
	end
end)

UICorner_13.Parent = Runchathaxscript_2

Information_6.Name = "Information"
Information_6.Parent = Headless
Information_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Information_6.BackgroundTransparency = 1.000
Information_6.Position = UDim2.new(0.363636136, 0, 0.246575341, 0)
Information_6.Size = UDim2.new(0, 38, 0, 28)
Information_6.Font = Enum.Font.Gotham
Information_6.Text = "Runs fe headless"
Information_6.TextColor3 = Color3.fromRGB(0, 0, 0)
Information_6.TextSize = 13.000
Information_6.TextTransparency = 0.580

UICorner_14.Parent = Headless

RemoteSpy.Name = "RemoteSpy"
RemoteSpy.Parent = MainThing
RemoteSpy.BackgroundColor3 = Color3.fromRGB(27, 36, 103)
RemoteSpy.Position = UDim2.new(0.639442265, 0, 0.429148734, 0)
RemoteSpy.Size = UDim2.new(0, 143, 0, 146)

RemoteSpyTxt.Name = "RemoteSpyTxt"
RemoteSpyTxt.Parent = RemoteSpy
RemoteSpyTxt.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
RemoteSpyTxt.BackgroundTransparency = 1.000
RemoteSpyTxt.Position = UDim2.new(0.020979017, 0, 0, 0)
RemoteSpyTxt.Size = UDim2.new(0, 140, 0, 50)
RemoteSpyTxt.Font = Enum.Font.Gotham
RemoteSpyTxt.Text = "Remote Spy"
RemoteSpyTxt.TextColor3 = Color3.fromRGB(255, 255, 255)
RemoteSpyTxt.TextSize = 24.000

RunRemoteSpy.Name = "RunRemoteSpy"
RunRemoteSpy.Parent = RemoteSpy
RunRemoteSpy.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
RunRemoteSpy.Position = UDim2.new(0.0559440553, 0, 0.531522274, 0)
RunRemoteSpy.Size = UDim2.new(0, 126, 0, 49)
RunRemoteSpy.Font = Enum.Font.Gotham
RunRemoteSpy.Text = "Run"
RunRemoteSpy.TextColor3 = Color3.fromRGB(255, 255, 255)
RunRemoteSpy.TextSize = 24.000
RunRemoteSpy.MouseButton1Click:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/offperms/en/main/remote"))()
end)

UICorner_15.Parent = RunRemoteSpy

Information_7.Name = "Information"
Information_7.Parent = RemoteSpy
Information_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Information_7.BackgroundTransparency = 1.000
Information_7.Position = UDim2.new(0.363636136, 0, 0.246575341, 0)
Information_7.Size = UDim2.new(0, 38, 0, 28)
Information_7.Font = Enum.Font.Gotham
Information_7.Text = "Runs Best Remotespy"
Information_7.TextColor3 = Color3.fromRGB(0, 0, 0)
Information_7.TextSize = 13.000
Information_7.TextTransparency = 0.580

UICorner_16.Parent = RemoteSpy

Fates.Name = "Fates"
Fates.Parent = MainThing
Fates.BackgroundColor3 = Color3.fromRGB(27, 36, 103)
Fates.Position = UDim2.new(0.326693267, 0, 0.429148734, 0)
Fates.Size = UDim2.new(0, 143, 0, 146)

FatesAdmintxt.Name = "FatesAdmintxt"
FatesAdmintxt.Parent = Fates
FatesAdmintxt.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
FatesAdmintxt.BackgroundTransparency = 1.000
FatesAdmintxt.Position = UDim2.new(0.020979017, 0, 0, 0)
FatesAdmintxt.Size = UDim2.new(0, 140, 0, 50)
FatesAdmintxt.Font = Enum.Font.Gotham
FatesAdmintxt.Text = "Fates Admin"
FatesAdmintxt.TextColor3 = Color3.fromRGB(255, 255, 255)
FatesAdmintxt.TextSize = 24.000

RunFatesAdmin.Name = "RunFatesAdmin"
RunFatesAdmin.Parent = Fates
RunFatesAdmin.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
RunFatesAdmin.Position = UDim2.new(0.0559440553, 0, 0.531522274, 0)
RunFatesAdmin.Size = UDim2.new(0, 126, 0, 49)
RunFatesAdmin.Font = Enum.Font.Gotham
RunFatesAdmin.Text = "Run"
RunFatesAdmin.TextColor3 = Color3.fromRGB(255, 255, 255)
RunFatesAdmin.TextSize = 24.000
RunFatesAdmin.MouseButton1Click:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/fatesc/fates-admin/main/main.lua"))()
end)

UICorner_17.Parent = RunFatesAdmin

Information_8.Name = "Information"
Information_8.Parent = Fates
Information_8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Information_8.BackgroundTransparency = 1.000
Information_8.Position = UDim2.new(0.363636136, 0, 0.246575341, 0)
Information_8.Size = UDim2.new(0, 38, 0, 28)
Information_8.Font = Enum.Font.Gotham
Information_8.Text = "Runs FE fates admin"
Information_8.TextColor3 = Color3.fromRGB(0, 0, 0)
Information_8.TextSize = 13.000
Information_8.TextTransparency = 0.580

UICorner_18.Parent = Fates

Netless.Name = "Netless"
Netless.Parent = MainThing
Netless.BackgroundColor3 = Color3.fromRGB(27, 36, 103)
Netless.Position = UDim2.new(2.98023224e-08, 0, 0.429148734, 0)
Netless.Size = UDim2.new(0, 143, 0, 146)

NetlessTxt.Name = "NetlessTxt"
NetlessTxt.Parent = Netless
NetlessTxt.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
NetlessTxt.BackgroundTransparency = 1.000
NetlessTxt.Position = UDim2.new(0.020979017, 0, 0, 0)
NetlessTxt.Size = UDim2.new(0, 140, 0, 50)
NetlessTxt.Font = Enum.Font.Gotham
NetlessTxt.Text = "Netless"
NetlessTxt.TextColor3 = Color3.fromRGB(255, 255, 255)
NetlessTxt.TextSize = 24.000

RunNetless.Name = "RunNetless"
RunNetless.Parent = Netless
RunNetless.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
RunNetless.Position = UDim2.new(0.0559440553, 0, 0.531522274, 0)
RunNetless.Size = UDim2.new(0, 126, 0, 49)
RunNetless.Font = Enum.Font.Gotham
RunNetless.Text = "Run"
RunNetless.TextColor3 = Color3.fromRGB(255, 255, 255)
RunNetless.TextSize = 24.000
RunNetless.MouseButton1Click:connect(function()
	--|| Settings:
	local NetEnabled = true -- Keep this on true or this script is basically useless
	--|| Script Loadstring:
	loadstring(game:HttpGet('https://paste.ee/r/HRAcR'))()  
end)

UICorner_19.Parent = RunNetless

Information_9.Name = "Information"
Information_9.Parent = Netless
Information_9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Information_9.BackgroundTransparency = 1.000
Information_9.Position = UDim2.new(0.363636136, 0, 0.246575341, 0)
Information_9.Size = UDim2.new(0, 38, 0, 28)
Information_9.Font = Enum.Font.Gotham
Information_9.Text = "Runs fe netless"
Information_9.TextColor3 = Color3.fromRGB(0, 0, 0)
Information_9.TextSize = 13.000
Information_9.TextTransparency = 0.580

UICorner_20.Parent = Netless

Syntax.Name = "Syntax"
Syntax.Parent = MainThing
Syntax.BackgroundColor3 = Color3.fromRGB(27, 36, 103)
Syntax.Position = UDim2.new(0.637450218, 0, 0.644371867, 0)
Syntax.Size = UDim2.new(0, 143, 0, 146)

SyntaxTxt.Name = "SyntaxTxt"
SyntaxTxt.Parent = Syntax
SyntaxTxt.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
SyntaxTxt.BackgroundTransparency = 1.000
SyntaxTxt.Position = UDim2.new(0.020979017, 0, 0, 0)
SyntaxTxt.Size = UDim2.new(0, 140, 0, 50)
SyntaxTxt.Font = Enum.Font.Gotham
SyntaxTxt.Text = "Syntax Hub "
SyntaxTxt.TextColor3 = Color3.fromRGB(255, 255, 255)
SyntaxTxt.TextSize = 24.000

RunSyntax.Name = "RunSyntax"
RunSyntax.Parent = Syntax
RunSyntax.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
RunSyntax.Position = UDim2.new(0.0559440553, 0, 0.531522274, 0)
RunSyntax.Size = UDim2.new(0, 126, 0, 49)
RunSyntax.Font = Enum.Font.Gotham
RunSyntax.Text = "Run"
RunSyntax.TextColor3 = Color3.fromRGB(255, 255, 255)
RunSyntax.TextSize = 24.000
RunSyntax.MouseButton1Click:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/Vallater/SyntaxFE/main/README.txt'),true))()
end)

UICorner_21.Parent = RunSyntax

Information_10.Name = "Information"
Information_10.Parent = Syntax
Information_10.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Information_10.BackgroundTransparency = 1.000
Information_10.Position = UDim2.new(0.363636136, 0, 0.246575341, 0)
Information_10.Size = UDim2.new(0, 38, 0, 28)
Information_10.Font = Enum.Font.Gotham
Information_10.Text = "Runs syntax hub"
Information_10.TextColor3 = Color3.fromRGB(0, 0, 0)
Information_10.TextSize = 13.000
Information_10.TextTransparency = 0.580

UICorner_22.Parent = Syntax

EmoteGui.Name = "Emote Gui"
EmoteGui.Parent = MainThing
EmoteGui.BackgroundColor3 = Color3.fromRGB(27, 36, 103)
EmoteGui.Position = UDim2.new(0.322709143, 0, 0.645684183, 0)
EmoteGui.Size = UDim2.new(0, 143, 0, 146)

Emoteguitxt.Name = "Emoteguitxt"
Emoteguitxt.Parent = EmoteGui
Emoteguitxt.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Emoteguitxt.BackgroundTransparency = 1.000
Emoteguitxt.Position = UDim2.new(0.020979017, 0, 0, 0)
Emoteguitxt.Size = UDim2.new(0, 140, 0, 50)
Emoteguitxt.Font = Enum.Font.Gotham
Emoteguitxt.Text = "Emote gui"
Emoteguitxt.TextColor3 = Color3.fromRGB(255, 255, 255)
Emoteguitxt.TextSize = 24.000

RunEmotegui.Name = "RunEmotegui"
RunEmotegui.Parent = EmoteGui
RunEmotegui.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
RunEmotegui.Position = UDim2.new(0.0559440553, 0, 0.531522274, 0)
RunEmotegui.Size = UDim2.new(0, 126, 0, 49)
RunEmotegui.Font = Enum.Font.Gotham
RunEmotegui.Text = "Run"
RunEmotegui.TextColor3 = Color3.fromRGB(255, 255, 255)
RunEmotegui.TextSize = 24.000
RunEmotegui.MouseButton1Click:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/DjsEQMxQ"))()
end)

UICorner_23.Parent = RunEmotegui

Information_11.Name = "Information"
Information_11.Parent = EmoteGui
Information_11.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Information_11.BackgroundTransparency = 1.000
Information_11.Position = UDim2.new(0.363636136, 0, 0.246575341, 0)
Information_11.Size = UDim2.new(0, 38, 0, 28)
Information_11.Font = Enum.Font.Gotham
Information_11.Text = "Runs FE Emote gui"
Information_11.TextColor3 = Color3.fromRGB(0, 0, 0)
Information_11.TextSize = 13.000
Information_11.TextTransparency = 0.580

UICorner_24.Parent = EmoteGui

BackFlip.Name = "BackFlip"
BackFlip.Parent = MainThing
BackFlip.BackgroundColor3 = Color3.fromRGB(27, 36, 103)
BackFlip.Position = UDim2.new(-1.49011612e-08, 0, 0.643059552, 0)
BackFlip.Size = UDim2.new(0, 143, 0, 146)

BackFliptxt.Name = "BackFliptxt"
BackFliptxt.Parent = BackFlip
BackFliptxt.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BackFliptxt.BackgroundTransparency = 1.000
BackFliptxt.Position = UDim2.new(0.020979017, 0, 0, 0)
BackFliptxt.Size = UDim2.new(0, 140, 0, 50)
BackFliptxt.Font = Enum.Font.Gotham
BackFliptxt.Text = "BackFlip"
BackFliptxt.TextColor3 = Color3.fromRGB(255, 255, 255)
BackFliptxt.TextSize = 24.000

RunBackFlipHub.Name = "RunBackFlipHub"
RunBackFlipHub.Parent = BackFlip
RunBackFlipHub.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
RunBackFlipHub.Position = UDim2.new(0.0559440553, 0, 0.531522274, 0)
RunBackFlipHub.Size = UDim2.new(0, 126, 0, 49)
RunBackFlipHub.Font = Enum.Font.Gotham
RunBackFlipHub.Text = "Run"
RunBackFlipHub.TextColor3 = Color3.fromRGB(255, 255, 255)
RunBackFlipHub.TextSize = 24.000
RunBackFlipHub.MouseButton1Click:connect(function()
	wait(5)

	--[[ Info ]]--

	local ver = "2.00"
	local scriptname = "feFlip"


	--[[ Keybinds ]]--

	local FrontflipKey = Enum.KeyCode.Z
	local BackflipKey = Enum.KeyCode.X
	local AirjumpKey = Enum.KeyCode.C


	--[[ Dependencies ]]--

	local ca = game:GetService("ContextActionService")
	local zeezy = game:GetService("Players").LocalPlayer
	local h = 0.0174533
	local antigrav


	--[[ Functions ]]--

	function zeezyFrontflip(act,inp,obj)
		if inp == Enum.UserInputState.Begin then
			zeezy.Character.Humanoid:ChangeState("Jumping")
			wait()
			zeezy.Character.Humanoid.Sit = true
			for i = 1,360 do 
				delay(i/720,function()
					zeezy.Character.Humanoid.Sit = true
					zeezy.Character.HumanoidRootPart.CFrame = zeezy.Character.HumanoidRootPart.CFrame * CFrame.Angles(-h,0,0)
				end)
			end
			wait(0.55)
			zeezy.Character.Humanoid.Sit = false
		end
	end

	function zeezyBackflip(act,inp,obj)
		if inp == Enum.UserInputState.Begin then
			zeezy.Character.Humanoid:ChangeState("Jumping")
			wait()
			zeezy.Character.Humanoid.Sit = true
			for i = 1,360 do
				delay(i/720,function()
					zeezy.Character.Humanoid.Sit = true
					zeezy.Character.HumanoidRootPart.CFrame = zeezy.Character.HumanoidRootPart.CFrame * CFrame.Angles(h,0,0)
				end)
			end
			wait(0.55)
			zeezy.Character.Humanoid.Sit = false
		end
	end

	function zeezyAirjump(act,inp,obj)
		if inp == Enum.UserInputState.Begin then
			zeezy.Character:FindFirstChildOfClass'Humanoid':ChangeState("Seated")
			wait()
			zeezy.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")	
		end
	end


	--[[ Binds ]]--

	ca:BindAction("zeezyFrontflip",zeezyFrontflip,false,FrontflipKey)
	ca:BindAction("zeezyBackflip",zeezyBackflip,false,BackflipKey)
	ca:BindAction("zeezyAirjump",zeezyAirjump,false,AirjumpKey)

	--[[ Load Message ]]--

	print(scriptname .. " " .. ver .. " loaded successfully")
	print("made by Zeezy#7203")

	local notifSound = Instance.new("Sound",workspace)
	notifSound.PlaybackSpeed = 1.5
	notifSound.Volume = 0.15
	notifSound.SoundId = "rbxassetid://170765130"
	notifSound.PlayOnRemove = true
	notifSound:Destroy()
	game.StarterGui:SetCore("SendNotification", {Title = "feFlip", Text = "feFlip loaded successfully!", Icon = "rbxassetid://505845268", Duration = 5, Button1 = "Okay"})
end)

UICorner_25.Parent = RunBackFlipHub

Information_12.Name = "Information"
Information_12.Parent = BackFlip
Information_12.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Information_12.BackgroundTransparency = 1.000
Information_12.Position = UDim2.new(0.363636136, 0, 0.246575341, 0)
Information_12.Size = UDim2.new(0, 38, 0, 28)
Information_12.Font = Enum.Font.Gotham
Information_12.Text = "Runs fe backflip"
Information_12.TextColor3 = Color3.fromRGB(0, 0, 0)
Information_12.TextSize = 13.000
Information_12.TextTransparency = 0.580

UICorner_26.Parent = BackFlip

CharacterThing.Name = "CharacterThing"
CharacterThing.Parent = Frame
CharacterThing.Active = true
CharacterThing.BackgroundColor3 = Color3.fromRGB(13, 17, 48)
CharacterThing.Position = UDim2.new(0.227342501, 0, 0.188976377, 0)
CharacterThing.Size = UDim2.new(0, 502, 0, 267)
CharacterThing.Visible = false

Walkspeed.Name = "Walkspeed"
Walkspeed.Parent = CharacterThing
Walkspeed.BackgroundColor3 = Color3.fromRGB(27, 36, 103)
Walkspeed.Position = UDim2.new(0, 0, -0.00129745342, 0)
Walkspeed.Size = UDim2.new(0, 143, 0, 146)

WalkspeedGuitxt.Name = "WalkspeedGuitxt"
WalkspeedGuitxt.Parent = Walkspeed
WalkspeedGuitxt.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
WalkspeedGuitxt.BackgroundTransparency = 1.000
WalkspeedGuitxt.Position = UDim2.new(0.020979017, 0, 0.0342465751, 0)
WalkspeedGuitxt.Size = UDim2.new(0, 140, 0, 50)
WalkspeedGuitxt.Font = Enum.Font.Gotham
WalkspeedGuitxt.Text = "Walkspeed"
WalkspeedGuitxt.TextColor3 = Color3.fromRGB(255, 255, 255)
WalkspeedGuitxt.TextSize = 24.000

Information_13.Name = "Information"
Information_13.Parent = Walkspeed
Information_13.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Information_13.BackgroundTransparency = 1.000
Information_13.Position = UDim2.new(0.125874132, 0, 0.294520557, 0)
Information_13.Size = UDim2.new(0, 110, 0, 34)
Information_13.Font = Enum.Font.Gotham
Information_13.Text = "Changes Walkspeed"
Information_13.TextColor3 = Color3.fromRGB(0, 0, 0)
Information_13.TextSize = 13.000
Information_13.TextTransparency = 0.580

UICorner_27.Parent = Walkspeed

Walkspeed_2.Name = "Walkspeed"
Walkspeed_2.Parent = Walkspeed
Walkspeed_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Walkspeed_2.Position = UDim2.new(0.0209790207, 0, 0.582191885, 0)
Walkspeed_2.Size = UDim2.new(0, 140, 0, 37)
Walkspeed_2.Font = Enum.Font.Gotham
Walkspeed_2.Text = "Walkspeed here"
Walkspeed_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Walkspeed_2.TextSize = 14.000

UICorner_28.Parent = Walkspeed_2

Jumppower.Name = "Jumppower"
Jumppower.Parent = CharacterThing
Jumppower.BackgroundColor3 = Color3.fromRGB(27, 36, 103)
Jumppower.Position = UDim2.new(0.330677271, 0, -0.00129745342, 0)
Jumppower.Size = UDim2.new(0, 143, 0, 146)

Jumppowertxt.Name = "Jumppowertxt"
Jumppowertxt.Parent = Jumppower
Jumppowertxt.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Jumppowertxt.BackgroundTransparency = 1.000
Jumppowertxt.Position = UDim2.new(0.020979017, 0, 0.0342465751, 0)
Jumppowertxt.Size = UDim2.new(0, 140, 0, 50)
Jumppowertxt.Font = Enum.Font.Gotham
Jumppowertxt.Text = "JumpPower"
Jumppowertxt.TextColor3 = Color3.fromRGB(255, 255, 255)
Jumppowertxt.TextSize = 24.000

Information_14.Name = "Information"
Information_14.Parent = Jumppower
Information_14.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Information_14.BackgroundTransparency = 1.000
Information_14.Position = UDim2.new(0.125874132, 0, 0.294520557, 0)
Information_14.Size = UDim2.new(0, 110, 0, 34)
Information_14.Font = Enum.Font.Gotham
Information_14.Text = "Change  your jumpower"
Information_14.TextColor3 = Color3.fromRGB(0, 0, 0)
Information_14.TextSize = 13.000
Information_14.TextTransparency = 0.580

UICorner_29.Parent = Jumppower

Jumppower_2.Name = "Jumppower"
Jumppower_2.Parent = Jumppower
Jumppower_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Jumppower_2.Position = UDim2.new(0.0209790207, 0, 0.582191885, 0)
Jumppower_2.Size = UDim2.new(0, 140, 0, 37)
Jumppower_2.Font = Enum.Font.Gotham
Jumppower_2.Text = "Jumppower here"
Jumppower_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Jumppower_2.TextSize = 14.000

UICorner_30.Parent = Jumppower_2

Fly.Name = "Fly"
Fly.Parent = CharacterThing
Fly.BackgroundColor3 = Color3.fromRGB(27, 36, 103)
Fly.Position = UDim2.new(0.669322729, 0, -0.00129745342, 0)
Fly.Size = UDim2.new(0, 143, 0, 146)

Jumppowertxt_2.Name = "Jumppowertxt"
Jumppowertxt_2.Parent = Fly
Jumppowertxt_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Jumppowertxt_2.BackgroundTransparency = 1.000
Jumppowertxt_2.Position = UDim2.new(0.020979017, 0, 0.0342465751, 0)
Jumppowertxt_2.Size = UDim2.new(0, 140, 0, 50)
Jumppowertxt_2.Font = Enum.Font.Gotham
Jumppowertxt_2.Text = "JumpPower"
Jumppowertxt_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Jumppowertxt_2.TextSize = 24.000

Information_15.Name = "Information"
Information_15.Parent = Fly
Information_15.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Information_15.BackgroundTransparency = 1.000
Information_15.Position = UDim2.new(0.475524485, 0, 0.33561644, 0)
Information_15.Size = UDim2.new(0, 6, 0, 22)
Information_15.Font = Enum.Font.Gotham
Information_15.Text = "Makes you fly"
Information_15.TextColor3 = Color3.fromRGB(0, 0, 0)
Information_15.TextSize = 13.000
Information_15.TextTransparency = 0.580

UICorner_31.Parent = Fly

RunflyScript.Name = "RunflyScript"
RunflyScript.Parent = Fly
RunflyScript.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
RunflyScript.Position = UDim2.new(0.0559440553, 0, 0.531522274, 0)
RunflyScript.Size = UDim2.new(0, 126, 0, 49)
RunflyScript.Font = Enum.Font.Gotham
RunflyScript.Text = "Run"
RunflyScript.TextColor3 = Color3.fromRGB(255, 255, 255)
RunflyScript.TextSize = 24.000
RunflyScript.MouseButton1Click:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/offperms/fly/main/lmao"))();
end)

UICorner_32.Parent = RunflyScript

Noclip.Name = "Noclip"
Noclip.Parent = CharacterThing
Noclip.BackgroundColor3 = Color3.fromRGB(27, 36, 103)
Noclip.Position = UDim2.new(0.667330682, 0, 0.206051618, 0)
Noclip.Size = UDim2.new(0, 143, 0, 146)

NoclipTxt.Name = "NoclipTxt"
NoclipTxt.Parent = Noclip
NoclipTxt.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
NoclipTxt.BackgroundTransparency = 1.000
NoclipTxt.Position = UDim2.new(0.020979017, 0, 0.0342465751, 0)
NoclipTxt.Size = UDim2.new(0, 140, 0, 50)
NoclipTxt.Font = Enum.Font.Gotham
NoclipTxt.Text = "Noclip (E)"
NoclipTxt.TextColor3 = Color3.fromRGB(255, 255, 255)
NoclipTxt.TextSize = 24.000

Information_16.Name = "Information"
Information_16.Parent = Noclip
Information_16.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Information_16.BackgroundTransparency = 1.000
Information_16.Position = UDim2.new(0.475524485, 0, 0.33561644, 0)
Information_16.Size = UDim2.new(0, 6, 0, 22)
Information_16.Font = Enum.Font.Gotham
Information_16.Text = "Run noclip"
Information_16.TextColor3 = Color3.fromRGB(0, 0, 0)
Information_16.TextSize = 13.000
Information_16.TextTransparency = 0.580

UICorner_33.Parent = Noclip

runNoclipScript.Name = "runNoclipScript"
runNoclipScript.Parent = Noclip
runNoclipScript.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
runNoclipScript.Position = UDim2.new(0.0559440553, 0, 0.531522274, 0)
runNoclipScript.Size = UDim2.new(0, 126, 0, 49)
runNoclipScript.Font = Enum.Font.Gotham
runNoclipScript.Text = "Run"
runNoclipScript.TextColor3 = Color3.fromRGB(255, 255, 255)
runNoclipScript.TextSize = 24.000
runNoclipScript.MouseButton1Click:connect(function()
	noclip = false
	game:GetService('RunService').Stepped:connect(function()
		if noclip then
			game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
		end
	end)
	plr = game.Players.LocalPlayer
	mouse = plr:GetMouse()
	mouse.KeyDown:connect(function(key)
		if key == "e" then
			noclip = not noclip
			game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
		end
	end)
	game.StarterGui:SetCore("SendNotification", {
		Title = "Noclip";
		Text = "Loaded.";
		Duration = "10";
	})
	wait(1)
	game.StarterGui:SetCore("SendNotification", {
		Title = "Noclip";
		Text = "Press E To Noclip";
		Duration = "10";
	})
end)

UICorner_34.Parent = runNoclipScript

-- Scripts:

local function CKQOD_fake_script() -- MainTab.LocalScript 
	local script = Instance.new('LocalScript', MainTab)

	script.Parent.MouseButton1Down:connect(function()
		script.Parent.Parent.MainThing.Visible = true
		script.Parent.Parent.CharacterThing.Visible = false
		MainTab.BackgroundColor3 = Color3.new(0.254902, 0.27451, 0.639216)
		CharacterThing.BackgroundColor3 = Color3.fromRGB(7, 13, 36)
	end)
end
coroutine.wrap(CKQOD_fake_script)()
local function RJKIT_fake_script() -- LocalPlayerTab.LocalScript 
	local script = Instance.new('LocalScript', LocalPlayerTab)

script.Parent.MouseButton1Down:connect(function()
		script.Parent.Parent.ManThing.Visible = false
		script.Parent.Parent.CharacterThing.Visible = true
		CharacterThing.BackgroundColor3 = Color3.new(0.254902, 0.27451, 0.639216)
		MainTab.BackgroundColor3 = Color3.fromRGB(7, 13, 36)
	end)
end
coroutine.wrap(RJKIT_fake_script)()
