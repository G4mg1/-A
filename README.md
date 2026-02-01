--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 20 | Scripts: 5 | Modules: 0 | Tags: 0
local G2L = {};

-- StarterGui.ScreenGui
G2L["1"] = Instance.new("ScreenGui", game.CoreGui);
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;


-- StarterGui.ScreenGui.Frame
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["BorderSizePixel"] = 0;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(32, 32, 32);
G2L["2"]["Size"] = UDim2.new(0, 640, 0, 383);
G2L["2"]["Position"] = UDim2.new(0.30103, 0, 0.24818, 0);
G2L["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);


-- StarterGui.ScreenGui.Frame.UIStroke
G2L["3"] = Instance.new("UIStroke", G2L["2"]);
G2L["3"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["3"]["Color"] = Color3.fromRGB(54, 54, 54);


-- StarterGui.ScreenGui.Frame.Clear
G2L["4"] = Instance.new("TextButton", G2L["2"]);
G2L["4"]["TextWrapped"] = true;
G2L["4"]["BorderSizePixel"] = 0;
G2L["4"]["TextSize"] = 33;
G2L["4"]["TextColor3"] = Color3.fromRGB(176, 176, 176);
G2L["4"]["BackgroundColor3"] = Color3.fromRGB(27, 27, 27);
G2L["4"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["4"]["Size"] = UDim2.new(0, 94, 0, 164);
G2L["4"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4"]["Text"] = [[Clear]];
G2L["4"]["Name"] = [[Clear]];
G2L["4"]["Position"] = UDim2.new(0.8375, 0, 0.54214, 0);


-- StarterGui.ScreenGui.Frame.Clear.UIStroke
G2L["5"] = Instance.new("UIStroke", G2L["4"]);
G2L["5"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["5"]["Color"] = Color3.fromRGB(54, 54, 54);


-- StarterGui.ScreenGui.Frame.Clear.LocalScript
G2L["6"] = Instance.new("LocalScript", G2L["4"]);



-- StarterGui.ScreenGui.Frame.Execute
G2L["7"] = Instance.new("TextButton", G2L["2"]);
G2L["7"]["TextWrapped"] = true;
G2L["7"]["BorderSizePixel"] = 0;
G2L["7"]["TextSize"] = 33;
G2L["7"]["TextColor3"] = Color3.fromRGB(176, 176, 176);
G2L["7"]["BackgroundColor3"] = Color3.fromRGB(27, 27, 27);
G2L["7"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["7"]["Size"] = UDim2.new(0, 94, 0, 164);
G2L["7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["7"]["Text"] = [[Execute]];
G2L["7"]["Name"] = [[Execute]];
G2L["7"]["Position"] = UDim2.new(0.8375, 0, 0.09661, 0);


-- StarterGui.ScreenGui.Frame.Execute.UIStroke
G2L["8"] = Instance.new("UIStroke", G2L["7"]);
G2L["8"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["8"]["Color"] = Color3.fromRGB(54, 54, 54);


-- StarterGui.ScreenGui.Frame.Execute.LocalScript
G2L["9"] = Instance.new("LocalScript", G2L["7"]);



-- StarterGui.ScreenGui.Frame.ImageLabel
G2L["a"] = Instance.new("ImageLabel", G2L["2"]);
G2L["a"]["BorderSizePixel"] = 0;
G2L["a"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a"]["ImageTransparency"] = 0.68;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["a"]["Image"] = [[rbxassetid://2327540150]];
G2L["a"]["Size"] = UDim2.new(0, 33, -0.04044, 37);
G2L["a"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["a"]["BackgroundTransparency"] = 1;
G2L["a"]["Position"] = UDim2.new(0.01, 0, 0.02, 0);


-- StarterGui.ScreenGui.Frame.ImageLabel.TextLabel
G2L["b"] = Instance.new("TextLabel", G2L["a"]);
G2L["b"]["TextWrapped"] = true;
G2L["b"]["BorderSizePixel"] = 0;
G2L["b"]["TextSize"] = 14;
G2L["b"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["b"]["TextScaled"] = true;
G2L["b"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["b"]["FontFace"] = Font.new([[rbxasset://fonts/families/TitilliumWeb.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["b"]["TextColor3"] = Color3.fromRGB(123, 123, 123);
G2L["b"]["BackgroundTransparency"] = 1;
G2L["b"]["Size"] = UDim2.new(0, 167, 0, 21);
G2L["b"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["b"]["Text"] = [[Project Ligma]];
G2L["b"]["Position"] = UDim2.new(1, 0, 0, 0);


-- StarterGui.ScreenGui.Frame.ScrollingFrame
G2L["c"] = Instance.new("ScrollingFrame", G2L["2"]);
G2L["c"]["Active"] = true;
G2L["c"]["BorderSizePixel"] = 0;
G2L["c"]["CanvasSize"] = UDim2.new(0, 0, 5, 0);
G2L["c"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c"]["Size"] = UDim2.new(0, 516, 0, 335);
G2L["c"]["ScrollBarImageColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c"]["Position"] = UDim2.new(0.01719, 0, 0.09661, 0);
G2L["c"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["c"]["BackgroundTransparency"] = 1;


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextBox
G2L["d"] = Instance.new("TextBox", G2L["c"]);
G2L["d"]["CursorPosition"] = -1;
G2L["d"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["d"]["BorderSizePixel"] = 0;
G2L["d"]["TextWrapped"] = true;
G2L["d"]["TextTransparency"] = 0.49;
G2L["d"]["TextSize"] = 14;
G2L["d"]["TextColor3"] = Color3.fromRGB(191, 191, 191);
G2L["d"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["d"]["BackgroundColor3"] = Color3.fromRGB(27, 27, 27);
G2L["d"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["d"]["MultiLine"] = true;
G2L["d"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
G2L["d"]["ClearTextOnFocus"] = false;
G2L["d"]["PlaceholderText"] = [[print("project Ligma")]];
G2L["d"]["Size"] = UDim2.new(0, 503, 0, 1914);
G2L["d"]["Position"] = UDim2.new(0.4874, 0, 0.1651, 0);
G2L["d"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["d"]["Text"] = [[]];


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextBox.TextLabel
G2L["e"] = Instance.new("TextLabel", G2L["d"]);
G2L["e"]["TextWrapped"] = true;
G2L["e"]["BorderSizePixel"] = 0;
G2L["e"]["TextSize"] = 14;
G2L["e"]["TextXAlignment"] = Enum.TextXAlignment.Left;
G2L["e"]["TextTransparency"] = 0.37;
G2L["e"]["TextYAlignment"] = Enum.TextYAlignment.Top;
G2L["e"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["e"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
G2L["e"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["e"]["BackgroundTransparency"] = 1;
G2L["e"]["RichText"] = true;
G2L["e"]["Size"] = UDim2.new(0, 503, 0, 1913);
G2L["e"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["e"]["Text"] = [[]];


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextBox.TextLabel.LocalScript
G2L["f"] = Instance.new("LocalScript", G2L["e"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextBox.Bro
G2L["10"] = Instance.new("ImageLabel", G2L["d"]);
G2L["10"]["BorderSizePixel"] = 0;
G2L["10"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["10"]["ImageTransparency"] = 0.34;
-- [ERROR] cannot convert ImageContent, please report to "https://github.com/uniquadev/GuiToLuaConverter/issues"
G2L["10"]["Image"] = [[rbxassetid://119365584064227]];
G2L["10"]["Size"] = UDim2.new(0, 503, 0, 1914);
G2L["10"]["Visible"] = false;
G2L["10"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["10"]["BackgroundTransparency"] = 1;
G2L["10"]["Name"] = [[Bro]];


-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextBox.Bro.LocalScript
G2L["11"] = Instance.new("LocalScript", G2L["10"]);



-- StarterGui.ScreenGui.Frame.ScrollingFrame.UIListLayout
G2L["12"] = Instance.new("UIListLayout", G2L["c"]);
G2L["12"]["SortOrder"] = Enum.SortOrder.LayoutOrder;


-- StarterGui.ScreenGui.Frame.ScrollingFrame.UIStroke
G2L["13"] = Instance.new("UIStroke", G2L["c"]);
G2L["13"]["ApplyStrokeMode"] = Enum.ApplyStrokeMode.Border;
G2L["13"]["Color"] = Color3.fromRGB(54, 54, 54);


-- StarterGui.ScreenGui.Frame.UIDrag
G2L["14"] = Instance.new("LocalScript", G2L["2"]);
G2L["14"]["Name"] = [[UIDrag]];


-- StarterGui.ScreenGui.Frame.Clear.LocalScript
local function C_6()
local script = G2L["6"];
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.ScrollingFrame.TextBox.Text = ""
	end)
end;
task.spawn(C_6);
-- StarterGui.ScreenGui.Frame.Execute.LocalScript
local function C_9()
local script = G2L["9"];
	script.Parent.MouseButton1Click:Connect(function()
		pcall(function()
			loadstring(script.Parent.Parent.ScrollingFrame.TextBox.Text)()
		end)
	end)
end;
task.spawn(C_9);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextBox.TextLabel.LocalScript
local function C_f()
local script = G2L["f"];
	local X = script.Parent
	X.RichText = true
	local R = script.Parent.Parent
	local L = {
		["\1"] = "<font color='#C586C0'>%s</font>",
		["\2"] = "<font color='#4EC9B0'>%s</font>",
		["\3"] = "<font color='#CE9178'>%s</font>",
		["\4"] = "<font color='#B5CEA8'>%s</font>",
		["\5"] = "<font color='#2E6B2E'>%s</font>",
		["\6"] = "<font color='#569CD6'>%s</font>",
		["\7"] = "<font color='#D4D4D4'>%s</font>"
	}
	local G = {
		["and"]=1,["break"]=1,["do"]=1,["else"]=1,["elseif"]=1,
		["end"]=1,["false"]=1,["for"]=1,["function"]=1,["if"]=1,
		["in"]=1,["local"]=1,["nil"]=1,["not"]=1,["or"]=1,
		["repeat"]=1,["return"]=1,["then"]=1,["true"]=1,["until"]=1,
		["while"]=1,["game"]=1,["workspace"]=1,["Players"]=1,
		["LocalPlayer"]=1,["Parent"]=1,["Humanoid"]=1,["CFrame"]=1,
		["Vector3"]=1,["Enum"]=1,["Instance"]=1,["Character"]=1,
		["Wait"]=1,["Touched"]=1,["Mouse"]=1,["UserInputService"]=1,
		["RunService"]=1,["Camera"]=1,["TextLabel"]=1,["ScreenGui"]=1,
		["Part"]=1,["Clone"]=1,["Destroy"]=1
	}
	local function F(s)
		local t,h,q,r,m = {},1,0,0,0
		local function N() return s:sub(h,h) end
		local function C() h = h + 1 return s:sub(h-1,h-1) end
		local function M(p) local a = s:sub(h):match("^"..p) if a then h = h + #a end return a end
		while h <= #s do
			local c = N()
			if c:match("%s") then
				table.insert(t,{"w",C()})
			elseif c == "-" and s:sub(h+1,h+1) == "-" then
				local a = h
				if s:sub(h+2,h+2) == "[" and s:sub(h+3,h+3) == "[" then
					h = h + 4
					while h <= #s do
						if s:sub(h,h) == "]" and s:sub(h+1,h+1) == "]" then
							h = h + 2 break
						end h = h + 1
					end
					table.insert(t,{"c",s:sub(a,h-1)})
				else
					h = h + 2
					while h <= #s and s:sub(h,h) ~= "\n" do h = h + 1 end
					table.insert(t,{"c",s:sub(a,h-1)})
				end
			elseif c == "\"" or c == "'" then
				local d = C() local a = h
				while h <= #s and s:sub(h,h) ~= d do
					if s:sub(h,h) == "\\" then h = h + 1 end h = h + 1
				end
				if s:sub(h,h) == d then h = h + 1 end
				table.insert(t,{"s",d..s:sub(a,h-1)})
			elseif c == "[" and s:sub(h+1,h+1) == "[" then
				local a = h h = h + 2
				while h <= #s do
					if s:sub(h,h) == "]" and s:sub(h+1,h+1) == "]" then
						h = h + 2 break
					end h = h + 1
				end
				table.insert(t,{"s",s:sub(a,h-1)})
			elseif c:match("%d") then
				local n = M("[%d%.]+") table.insert(t,{"n",n})
			elseif c:match("[%a_]") then
				local w = M("[%w_]+")
				if G[w] then
					if w == "true" or w == "false" then
						table.insert(t,{"b",w})
					else table.insert(t,{"k",w}) end
				else
					if s:sub(h,h):match("%s*%(") then
						table.insert(t,{"f",w})
					else table.insert(t,{"x",w}) end
				end
			else
				table.insert(t,{"x",C()})
			end
		end
		local o = ""
		for _,v in ipairs(t) do
			if v[1] == "k" then o = o .. L["\1"]:format(v[2])
			elseif v[1] == "f" then o = o .. L["\2"]:format(v[2])
			elseif v[1] == "s" then o = o .. L["\3"]:format(v[2])
			elseif v[1] == "n" then o = o .. L["\4"]:format(v[2])
			elseif v[1] == "c" then o = o .. L["\5"]:format(v[2])
			elseif v[1] == "b" then o = o .. L["\6"]:format(v[2])
			else o = o .. L["\7"]:format(v[2]) end
		end
		return o
	end
	R:GetPropertyChangedSignal("Text"):Connect(function()
		X.Text = F(R.Text)
	end)
	X.Text = F(R.Text)
end;
task.spawn(C_f);
-- StarterGui.ScreenGui.Frame.ScrollingFrame.TextBox.Bro.LocalScript
local function C_11()
local script = G2L["11"];
	local wow = script.Parent
	local nos = script.Parent.Parent
	
	nos:GetPropertyChangedSignal("Text"):Connect(function()
		if string.find(nos.Text, "require()") then
			wow.Visible = true
		else
			wow.Visible = false
		end
	end)
	
	
	
end;
task.spawn(C_11);
-- StarterGui.ScreenGui.Frame.UIDrag
local function C_14()
local script = G2L["14"];
	-- Made by Real_IceyDev (@lceyDex) --
	-- Simple UI dragger (PC Only/Any device that has a mouse) --
	
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
task.spawn(C_14);

return G2L["1"], require;
