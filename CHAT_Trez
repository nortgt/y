local G2L = {};

if getgenv().trezchat then
	warn("Trez Chat is already loaded.")
	getgenv().trezchat:close()
	return
end

local BannedPeople = {}
local NormalArg = {}

local AdminArg = {}

for i,v in pairs(BannedPeople) do
	if table.find(v, Oplayer.UserId) then
		return warn("You have been banned for abusing ! appeal on our discord server !")
	end
end


-- StarterGui.TrezChat
G2L["1"] = Instance.new("ScreenGui", game.CoreGui);
G2L["1"]["Name"] = [[TrezChat]];
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;


-- StarterGui.TrezChat.Main
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["ZIndex"] = 2;
G2L["2"]["BorderSizePixel"] = 0;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(40, 40, 40);
G2L["2"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["2"]["Size"] = UDim2.new(0.25337, 100, 0.22362, 100);
G2L["2"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);
G2L["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["2"]["Name"] = [[Main]];
G2L["2"]["BackgroundTransparency"] = 0.05;


-- StarterGui.TrezChat.Main.Main
G2L["3"] = Instance.new("LocalScript", G2L["2"]);
G2L["3"]["Name"] = [[Main]];


-- StarterGui.TrezChat.Main.UIDrag
G2L["4"] = Instance.new("LocalScript", G2L["2"]);
G2L["4"]["Name"] = [[UIDrag]];


-- StarterGui.TrezChat.Main.Line
G2L["5"] = Instance.new("Frame", G2L["2"]);
G2L["5"]["ZIndex"] = 2;
G2L["5"]["BorderSizePixel"] = 0;
G2L["5"]["BackgroundColor3"] = Color3.fromRGB(255, 141, 0);
G2L["5"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["5"]["Size"] = UDim2.new(0.01, 267, 0, 1);
G2L["5"]["Position"] = UDim2.new(0.5, 0, 0.15, 0);
G2L["5"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["5"]["Name"] = [[Line]];


-- StarterGui.TrezChat.Main.Shadow
G2L["6"] = Instance.new("Frame", G2L["2"]);
G2L["6"]["ZIndex"] = 2;
G2L["6"]["BorderSizePixel"] = 0;
G2L["6"]["BackgroundColor3"] = Color3.fromRGB(255, 141, 0);
G2L["6"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["6"]["Size"] = UDim2.new(0.653, 100, 0.434, 100);
G2L["6"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);
G2L["6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["6"]["Name"] = [[Shadow]];
G2L["6"]["BackgroundTransparency"] = 0.55;


-- StarterGui.TrezChat.Main.Shadow.UIGradient
G2L["7"] = Instance.new("UIGradient", G2L["6"]);
G2L["7"]["Rotation"] = -90;
G2L["7"]["Transparency"] = NumberSequence.new{NumberSequenceKeypoint.new(0.000, 0.2625),NumberSequenceKeypoint.new(0.174, 0.7375),NumberSequenceKeypoint.new(0.357, 0.925),NumberSequenceKeypoint.new(1.000, 1)};


-- StarterGui.TrezChat.Main.Shadow.UICorner
G2L["8"] = Instance.new("UICorner", G2L["6"]);



-- StarterGui.TrezChat.Main.UIStroke
G2L["9"] = Instance.new("UIStroke", G2L["2"]);
G2L["9"]["Color"] = Color3.fromRGB(255, 145, 10);


-- StarterGui.TrezChat.Main.Bg
G2L["a"] = Instance.new("ImageLabel", G2L["2"]);
G2L["a"]["BorderSizePixel"] = 0;
G2L["a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a"]["ImageTransparency"] = 0.86;
G2L["a"]["ImageColor3"] = Color3.fromRGB(255, 141, 0);
G2L["a"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["a"]["Image"] = [[rbxassetid://15175796726]];
G2L["a"]["Size"] = UDim2.new(0.643, 100, 0.394, 100);
G2L["a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a"]["BackgroundTransparency"] = 1;
G2L["a"]["Name"] = [[Bg]];
G2L["a"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);


-- StarterGui.TrezChat.Main.Bg.UICorner
G2L["b"] = Instance.new("UICorner", G2L["a"]);



-- StarterGui.TrezChat.Main.SourceChat
G2L["c"] = Instance.new("TextBox", G2L["2"]);
G2L["c"]["Name"] = [[SourceChat]];
G2L["c"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["c"]["ZIndex"] = 3;
G2L["c"]["BorderSizePixel"] = 0;
G2L["c"]["TextWrapped"] = true;
G2L["c"]["TextSize"] = 14;
G2L["c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["c"]["Size"] = UDim2.new(0, 224, 0.01, 16);
G2L["c"]["Position"] = UDim2.new(0.02446, 0, 0.85934, 0);
G2L["c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c"]["Text"] = [[]];
G2L["c"]["PlaceholderText"] = "Send your message here..."
G2L["c"]["BackgroundTransparency"] = 0.3;


-- StarterGui.TrezChat.Main.SourceChat.UICorner
G2L["d"] = Instance.new("UICorner", G2L["c"]);
G2L["d"]["CornerRadius"] = UDim.new(0, 4);


-- StarterGui.TrezChat.Main.SourceChat.UIPadding
G2L["e"] = Instance.new("UIPadding", G2L["c"]);
G2L["e"]["PaddingLeft"] = UDim.new(0, 5);


-- StarterGui.TrezChat.Main.UICorner
G2L["f"] = Instance.new("UICorner", G2L["2"]);



-- StarterGui.TrezChat.Main.SendAsync
G2L["10"] = Instance.new("ImageButton", G2L["2"]);
G2L["10"]["BorderSizePixel"] = 0;
G2L["10"]["BackgroundTransparency"] = 1;
G2L["10"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["10"]["ImageColor3"] = Color3.fromRGB(255, 141, 0);
G2L["10"]["ZIndex"] = 3;
G2L["10"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["10"]["Image"] = [[rbxassetid://18940312887]];
G2L["10"]["Size"] = UDim2.new(0.01, 30, 0.02, 14);
G2L["10"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["10"]["Name"] = [[SendAsync]];
G2L["10"]["Position"] = UDim2.new(0.894, 0, 0.909, 0);


-- StarterGui.TrezChat.Main.SendAsync.UIAspectRatioConstraint
G2L["11"] = Instance.new("UIAspectRatioConstraint", G2L["10"]);



-- StarterGui.TrezChat.Main.TextLabel
G2L["12"] = Instance.new("TextLabel", G2L["2"]);
G2L["12"]["TextWrapped"] = true;
G2L["12"]["BorderSizePixel"] = 0;
G2L["12"]["TextSize"] = 19;
G2L["12"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["12"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["12"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["12"]["TextColor3"] = Color3.fromRGB(0, 0, 0);
G2L["12"]["BackgroundTransparency"] = 1;
G2L["12"]["RichText"] = true;
G2L["12"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["12"]["Size"] = UDim2.new(0.16, 200, -0.22, 50);
G2L["12"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["12"]["Text"] = [[<font color = 'rgb(242, 111, 2)'><font face='Arial'>Trez</font></font> <font color = 'rgb(255, 255, 255)'>Chat V1</font>]];
G2L["12"]["Position"] = UDim2.new(0.46, 0, 0.08, 0);


-- StarterGui.TrezChat.Main.ChatHistory
G2L["13"] = Instance.new("ScrollingFrame", G2L["2"]);
G2L["13"]["Active"] = true;
G2L["13"]["ZIndex"] = 3;
G2L["13"]["BorderSizePixel"] = 0;
-- [ERROR] cannot convert TopImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["13"]["TopImage"] = [[rbxasset://textures/ui/Scroll/scroll-middle.png]];
G2L["13"]["Name"] = [[ChatHistory]];
G2L["13"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
-- [ERROR] cannot convert BottomImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["13"]["BottomImage"] = [[rbxasset://textures/ui/Scroll/scroll-middle.png]];
G2L["13"]["Size"] = UDim2.new(0, 270, 0.01, 107);
G2L["13"]["ScrollBarImageColor3"] = Color3.fromRGB(255, 141, 0);
G2L["13"]["Position"] = UDim2.new(0.02795, 0, 0.18188, 0);
G2L["13"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["13"]["ScrollBarThickness"] = 3;
G2L["13"]["BackgroundTransparency"] = 0.65;


-- StarterGui.TrezChat.Main.ChatHistory.UICanva
G2L["14"] = Instance.new("LocalScript", G2L["13"]);
G2L["14"]["Name"] = [[UICanva]];


-- StarterGui.TrezChat.Main.ChatHistory.UIListLayout
G2L["15"] = Instance.new("UIListLayout", G2L["13"]);
G2L["15"]["Padding"] = UDim.new(0, 3);
G2L["15"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.TrezChat.Main.ChatHistory.ChatExample
G2L["16"] = Instance.new("Frame", G2L["13"]);
G2L["16"]["ZIndex"] = 3;
G2L["16"]["BorderSizePixel"] = 0;
G2L["16"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["16"]["Size"] = UDim2.new(0, 256, 0, 29);
G2L["16"]["Position"] = UDim2.new(0, 0, 0, 0);
G2L["16"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["16"]["Name"] = [[ChatExample]];
G2L["16"]["BackgroundTransparency"] = 1;


-- StarterGui.TrezChat.Main.ChatHistory.ChatExample.PlayerIcon
G2L["17"] = Instance.new("ImageLabel", G2L["16"]);
G2L["17"]["ZIndex"] = 4;
G2L["17"]["BorderSizePixel"] = 0;
G2L["17"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["17"]["Image"] = [[rbxasset://textures/ui/GuiImagePlaceholder.png]];
G2L["17"]["Size"] = UDim2.new(0, 60, 0, 29);
G2L["17"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["17"]["BackgroundTransparency"] = 1;
G2L["17"]["Name"] = [[PlayerIcon]];


-- StarterGui.TrezChat.Main.ChatHistory.ChatExample.PlayerIcon.UIAspectRatioConstraint
G2L["18"] = Instance.new("UIAspectRatioConstraint", G2L["17"]);



-- StarterGui.TrezChat.Main.ChatHistory.ChatExample.MessageSource
G2L["19"] = Instance.new("TextLabel", G2L["16"]);
G2L["19"]["TextWrapped"] = true;
G2L["19"]["ZIndex"] = 4;
G2L["19"]["BorderSizePixel"] = 0;
G2L["19"]["TextSize"] = 14;
G2L["19"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["19"]["TextScaled"] = true;
G2L["19"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["19"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["19"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["19"]["BackgroundTransparency"] = 1;
G2L["19"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["19"]["Size"] = UDim2.new(-0.16, 234, 0.07044, 14);
G2L["19"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["19"]["Text"] = [[yo chat the 67 meme is still massive woww]];
G2L["19"]["Name"] = [[MessageSource]];
G2L["19"]["Position"] = UDim2.new(0.51, 0, 0.69978, 0);


-- StarterGui.TrezChat.Main.ChatHistory.ChatExample.Sender
G2L["1a"] = Instance.new("TextLabel", G2L["16"]);
G2L["1a"]["ZIndex"] = 4;
G2L["1a"]["BorderSizePixel"] = 0;
G2L["1a"]["TextSize"] = 15;
G2L["1a"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["1a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1a"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["1a"]["TextColor3"] = Color3.fromRGB(255, 129, 0);
G2L["1a"]["BackgroundTransparency"] = 1;
G2L["1a"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["1a"]["Size"] = UDim2.new(-0.51033, 234, -0.14276, 14);
G2L["1a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1a"]["Text"] = [[C00lHamo0t2025]];
G2L["1a"]["Name"] = [[Sender]];
G2L["1a"]["Position"] = UDim2.new(0.33983, 0, 0.31819, 0);





-- StarterGui.TrezChat.Main.ChatHistory.UIPadding
G2L["1b"] = Instance.new("UIPadding", G2L["13"]);
G2L["1b"]["PaddingTop"] = UDim.new(0, 5);
G2L["1b"]["PaddingLeft"] = UDim.new(0, 5);


-- StarterGui.TrezChat.Main.Main
local function C_3()
local script = G2L["3"];
	local NoticeSound = Instance.new("Sound", G2L["1"])
	NoticeSound.SoundId = "rbxassetid://2865226708"
	NoticeSound.Name = "NoticeReciveSound"
	local SendSound = Instance.new("Sound", G2L["1"])
	SendSound.SoundId = "rbxassetid://5485567028"
	SendSound.Name = "SendSound"
	local Main = script.Parent
	local ChatHistory = Main.ChatHistory
	local SendAsync = Main.SendAsync
	local SourceChat = Main.SourceChat
	local ChatExample = ChatHistory.ChatExample
	ChatExample.Visible = false
	
	local http_func = http_request or request
	local Players = game:GetService("Players")
	local TextChatService = game:GetService("TextChatService")
	local TextChannel = TextChatService:WaitForChild("TextChannels"):WaitForChild("RBXGeneral")
	local HttpService = game:GetService("HttpService")
	local RunService = game:GetService("RunService")
	local API = "https://text.pollinations.ai/openai"
	local ArgsT = {}
	

	local Oplayer = Players.LocalPlayer
	local chara = Oplayer.Character or Oplayer.CharacterAdded:Wait()

	
	local HttpService = game:GetService("HttpService")

	
	local Players = game:GetService("Players")
	local Oplayer = Players.LocalPlayer

	local Developer = {
		"C00lHamo0t2025";
		"ikik9i4"
	}

	local function CheckIfAdmin(player)
		if table.find(Developer, player.Name) then
			return true
		end
		return false
	end

	
	local function FindPlayer(str)
		str = string.lower(str)

		for _,plr in pairs(Players:GetPlayers()) do
			if string.sub(string.lower(plr.Name),1,#str) == str then
				return plr
			end
		end
	end

	function AdminArg.Ban(player)
		if not CheckIfAdmin(Oplayer) then return end
		if not player then return end

		table.insert(BannedPeople, player.UserId)
	end

	function AdminArg.warn(player, reason)
		if not CheckIfAdmin(Oplayer) then return end
		if not player then return end

		local DataContent = {
			type = "message";
			username = "Server";
			message = player.Name.." has been warned by "..Oplayer.Name.." for "..(reason or "No reason");
			userid = 1;
			gamePlaying = "DataBase";
			gameid = game.PlaceId
		}

		local Encoded = HttpService:JSONEncode(DataContent)
		getgenv().trezchat:Send(Encoded)
	end

	function AdminArg.unban(player)
		if not CheckIfAdmin(Oplayer) then return end
		if not player then return end

		for i,v in pairs(BannedPeople) do
			if v == player.UserId then
				table.remove(BannedPeople,i)
			end
		end
	end

	local AdminCommands = {
		["ban"] = AdminArg.Ban;
		["warn"] = AdminArg.warn;
		["unban"] = AdminArg.unban;
	}

	local function HandleCommand(text)
		local split = string.split(text," ")

		local prefix = split[1]
		local command = split[2]
		local playerArg = split[3]
		local reason = split[4]

		if prefix ~= "?" then return end

		local targetPlayer = FindPlayer(playerArg)

		if AdminCommands[command] then
			AdminCommands[command](targetPlayer, reason)
		end
	end
	
	
	
	getgenv().trezchat = WebSocket.connect("wss://free.blr2.piesocket.com/v3/1?api_key=eLudeCBiiTiQSr6DWJPMPfpZK9B6ghEu90ZbJwzm&notify_self=1")
	
	local Developer = {
		"C00lHamo0t2025";
		"ikik9i4"
	}
	
	
	
	local function sendMessage()
		if SourceChat.Text == "" then return end
		HandleCommand(SourceChat.Text)
		local player = Oplayer

		local function Filtered(word)
			local Success, result = pcall(function()
				local encodedWord = HttpService:UrlEncode(word)
				return game:HttpGet("https://www.purgomalum.com/service/plain?text="..encodedWord)
			end)

			if Success then
				local DataContent = {
					type = "message";
					username = player.Name;
					message = result;
					userid = player.UserId;
					gamePlaying = game:GetService("MarketplaceService"):GetProductInfo(game.PlaceId).Name;
					gameid = game.PlaceId;
				}
				local Encoded = HttpService:JSONEncode(DataContent)
				getgenv().trezchat:Send(Encoded)
				return
			else
				warn("Failed to filter message:", result)
			end
		end

		Filtered(SourceChat.Text)

		SendSound:Play()
		SourceChat.Text = ""
	end
	
	
	
	SendAsync.MouseButton1Click:Connect(sendMessage)
	
	SourceChat.FocusLost:Connect(function(enterPressed)
		if enterPressed then
			sendMessage()
		end
	end)
	
	getgenv().trezchat.OnMessage:Connect(function(msg)
		local success, Decoded = pcall(HttpService.JSONDecode, HttpService, msg)
		if not success then
			warn("Failed to decode message:", msg)
			return
		end
	
		local username = Decoded.username or "Unknown"
		local message = Decoded.message or ""
		local userid = Decoded.userid or 0
		local gamePlaying = Decoded.gamePlaying or "N/A"
		
	
	
		local Clone = ChatExample:Clone()
		Clone.Name = username .. " Chats "
		Clone.Parent = ChatHistory
		Clone.MessageSource.Text = message
		Clone.PlayerIcon.Image = "rbxthumb://type=AvatarHeadShot&id="..userid.."&w=420&h=420"
	
		
		NoticeSound:Play()
	
		if table.find(Developer, username) then
			Clone.Sender.Text = username.." ( Dev ) ".."( "..Decoded.gamePlaying.." )";
		else
			Clone.Sender.Text = username.." ( "..Decoded.gamePlaying.." )"
		end
		Clone.Visible = true
		
		
	end)
	
	local DataContent = {
		type = "message";
		username = "Server";
		message = "Make Sure To Join Our Discord Server = ( https://discord.gg/TPtrJceCva )";
		userid = 1;
		gamePlaying = "DataBase";
		gameid = game.PlaceId
	}
	local Encoded = HttpService:JSONEncode(DataContent)
	getgenv().trezchat:Send(Encoded)
	
	while true do
		wait(1000)
		local DataContent = {
			type = "message";
			username = "Server";
			message = "Be Careful Do Not Share Your Personal Info !!" ;
			userid = 1;
			gamePlaying = "DataBase";
			gameid = game.PlaceId
		}
		local Encoded = HttpService:JSONEncode(DataContent)
		getgenv().trezchat:Send(Encoded)
		wait(1000)
		local DataContent = {
			type = "message";
			username = "Server";
			message = "Make Sure To Join Our Discord Server = ( https://discord.gg/TPtrJceCva )" ;
			userid = 1;
			gamePlaying = "DataBase";
			gameid = game.PlaceId

		}
		local Encoded = HttpService:JSONEncode(DataContent)
		getgenv().trezchat:Send(Encoded)
		wait(1000)
		local DataContent = {
			type = "message";
			username = "Server";
			message = "if you saw any bug you can send the screen record of the issue to our discord server in #report channel so we can sole it" ;
			userid = 1;
			gamePlaying = "DataBase";
			gameid = game.PlaceId
		}
		local Encoded = HttpService:JSONEncode(DataContent)
		getgenv().trezchat:Send(Encoded)
		
	end
end;
task.spawn(C_3);
-- StarterGui.TrezChat.Main.UIDrag
local function C_4()
local script = G2L["4"];
	local UIS = game:GetService('UserInputService')
	local frame = script.Parent
	local dragToggle = nil
	local dragSpeed = 0.25
	local dragStart = nil
	local startPos = nil
	
	local function updateInput(input)
		local delta = input.Position - dragStart
		local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
			startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		game:GetService('TweenService'):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
	end
	
	frame.InputBegan:Connect(function(input)
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then 
			dragToggle = true
			dragStart = input.Position
			startPos = frame.Position
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragToggle = false
				end
			end)
		end
	end)
	
	UIS.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			if dragToggle then
				updateInput(input)
			end
		end
	end)
end;
task.spawn(C_4);
-- StarterGui.TrezChat.Main.ChatHistory.UICanva
local function C_14()
local script = G2L["14"];
	local Frame = script.Parent.ChatExample
	local ChatHistory = script.Parent
	local Layout = script.Parent.UIListLayout
	
	ChatHistory.CanvasSize = UDim2.new(0,0,0,0)
	
	local function Update()
		ChatHistory.CanvasSize = UDim2.new(0,0,0,Layout.AbsoluteContentSize.Y + 10)
	end
	
	Layout:GetPropertyChangedSignal("AbsoluteContentSize"):Connect(Update)
end;
task.spawn(C_14);

return G2L["1"], require;
