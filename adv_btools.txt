
--Converted with ttyyuu12345's model to script plugin v4
function sandbox(var,func)
	local env = getfenv(func)
	local newenv = setmetatable({},{
		__index = function(self,k)
			if k=="script" then
				return var
			else
				return env[k]
			end
		end,
	})
	setfenv(func,newenv)
	return func
end
cors = {}
mas = Instance.new("Model",game:GetService("Lighting"))
ScreenGui0 = Instance.new("ScreenGui")
Frame1 = Instance.new("Frame")
Frame2 = Instance.new("Frame")
Frame3 = Instance.new("Frame")
TextButton4 = Instance.new("TextButton")
ImageLabel5 = Instance.new("ImageLabel")
TextLabel6 = Instance.new("TextLabel")
UIGridLayout7 = Instance.new("UIGridLayout")
TextButton8 = Instance.new("TextButton")
ImageLabel9 = Instance.new("ImageLabel")
TextLabel10 = Instance.new("TextLabel")
TextButton11 = Instance.new("TextButton")
ImageLabel12 = Instance.new("ImageLabel")
TextLabel13 = Instance.new("TextLabel")
TextButton14 = Instance.new("TextButton")
ImageLabel15 = Instance.new("ImageLabel")
TextLabel16 = Instance.new("TextLabel")
TextButton17 = Instance.new("TextButton")
TextLabel18 = Instance.new("TextLabel")
ImageLabel19 = Instance.new("ImageLabel")
TextButton20 = Instance.new("TextButton")
ImageLabel21 = Instance.new("ImageLabel")
TextLabel22 = Instance.new("TextLabel")
TextButton23 = Instance.new("TextButton")
ImageLabel24 = Instance.new("ImageLabel")
TextLabel25 = Instance.new("TextLabel")
TextLabel26 = Instance.new("TextLabel")
LocalScript27 = Instance.new("LocalScript")
Handles28 = Instance.new("Handles")
Handles29 = Instance.new("Handles")
ArcHandles30 = Instance.new("ArcHandles")
SelectionBox31 = Instance.new("SelectionBox")
UIListLayout32 = Instance.new("UIListLayout")
Frame33 = Instance.new("Frame")
Frame34 = Instance.new("Frame")
UIGridLayout35 = Instance.new("UIGridLayout")
TextButton36 = Instance.new("TextButton")
ImageLabel37 = Instance.new("ImageLabel")
TextLabel38 = Instance.new("TextLabel")
LocalScript39 = Instance.new("LocalScript")
TextButton40 = Instance.new("TextButton")
ImageLabel41 = Instance.new("ImageLabel")
TextLabel42 = Instance.new("TextLabel")
LocalScript43 = Instance.new("LocalScript")
TextButton44 = Instance.new("TextButton")
ImageLabel45 = Instance.new("ImageLabel")
TextLabel46 = Instance.new("TextLabel")
LocalScript47 = Instance.new("LocalScript")
TextLabel48 = Instance.new("TextLabel")
Frame49 = Instance.new("Frame")
Frame50 = Instance.new("Frame")
UIGridLayout51 = Instance.new("UIGridLayout")
TextButton52 = Instance.new("TextButton")
ImageLabel53 = Instance.new("ImageLabel")
TextLabel54 = Instance.new("TextLabel")
LocalScript55 = Instance.new("LocalScript")
TextButton56 = Instance.new("TextButton")
ImageLabel57 = Instance.new("ImageLabel")
TextLabel58 = Instance.new("TextLabel")
TextLabel59 = Instance.new("TextLabel")
Frame60 = Instance.new("Frame")
TextLabel61 = Instance.new("TextLabel")
TextBox62 = Instance.new("TextBox")
TextLabel63 = Instance.new("TextLabel")
TextBox64 = Instance.new("TextBox")
TextLabel65 = Instance.new("TextLabel")
TextBox66 = Instance.new("TextBox")
TextLabel67 = Instance.new("TextLabel")
TextLabel68 = Instance.new("TextLabel")
TextButton69 = Instance.new("TextButton")
LocalScript70 = Instance.new("LocalScript")
LocalScript71 = Instance.new("LocalScript")
Sound72 = Instance.new("Sound")
ScreenGui0.Name = "AdvBTools"
ScreenGui0.Parent = mas
ScreenGui0.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
Frame1.Name = "Main"
Frame1.Parent = ScreenGui0
Frame1.Position = UDim2.new(0, 0, 1, 0)
Frame1.Size = UDim2.new(1, 0, 0, 100)
Frame1.AnchorPoint = Vector2.new(0, 1)
Frame1.BackgroundColor = BrickColor.new("Black")
Frame1.BackgroundColor3 = Color3.new(0.180392, 0.180392, 0.180392)
Frame1.BorderColor3 = Color3.new(0.145098, 0.145098, 0.145098)
Frame1.ZIndex = 999999998
Frame2.Name = "AdvancedBtools"
Frame2.Parent = Frame1
Frame2.Size = UDim2.new(0, 360, 1, 0)
Frame2.BackgroundColor = BrickColor.new("Black")
Frame2.BackgroundColor3 = Color3.new(0.180392, 0.180392, 0.180392)
Frame2.BorderColor3 = Color3.new(0.145098, 0.145098, 0.145098)
Frame3.Name = "Buttons"
Frame3.Parent = Frame2
Frame3.Position = UDim2.new(0, 10, 0, 10)
Frame3.Size = UDim2.new(1, 0, 1, -20)
Frame3.BackgroundColor = BrickColor.new("Institutional white")
Frame3.BackgroundColor3 = Color3.new(1, 1, 1)
Frame3.BackgroundTransparency = 1
TextButton4.Name = "None"
TextButton4.Parent = Frame3
TextButton4.Position = UDim2.new(0, 10, 0, 10)
TextButton4.Size = UDim2.new(0, 40, 0, 60)
TextButton4.BackgroundColor = BrickColor.new("Black metallic")
TextButton4.BackgroundColor3 = Color3.new(0.109804, 0.109804, 0.109804)
TextButton4.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton4.Font = Enum.Font.SourceSans
TextButton4.FontSize = Enum.FontSize.Size14
TextButton4.Text = ""
TextButton4.TextColor = BrickColor.new("Really black")
TextButton4.TextColor3 = Color3.new(0, 0, 0)
TextButton4.TextSize = 14
ImageLabel5.Parent = TextButton4
ImageLabel5.Size = UDim2.new(0, 40, 0, 40)
ImageLabel5.BackgroundColor = BrickColor.new("Institutional white")
ImageLabel5.BackgroundColor3 = Color3.new(1, 1, 1)
ImageLabel5.BackgroundTransparency = 1
ImageLabel5.Image = "http://www.roblox.com/asset/?id=8974717361"
ImageLabel5.ImageRectOffset = Vector2.new(40, 40)
ImageLabel5.ImageRectSize = Vector2.new(40, 40)
TextLabel6.Parent = TextButton4
TextLabel6.Position = UDim2.new(0, 0, 0, 42)
TextLabel6.Size = UDim2.new(1, 0, 0, 30)
TextLabel6.BackgroundColor = BrickColor.new("Institutional white")
TextLabel6.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel6.BackgroundTransparency = 1
TextLabel6.Font = Enum.Font.SourceSans
TextLabel6.FontSize = Enum.FontSize.Size14
TextLabel6.Text = "None"
TextLabel6.TextColor = BrickColor.new("Institutional white")
TextLabel6.TextColor3 = Color3.new(1, 1, 1)
TextLabel6.TextSize = 14
TextLabel6.TextWrap = true
TextLabel6.TextWrapped = true
TextLabel6.TextYAlignment = Enum.TextYAlignment.Top
UIGridLayout7.Parent = Frame3
UIGridLayout7.SortOrder = Enum.SortOrder.LayoutOrder
UIGridLayout7.CellPadding = UDim2.new(0, 10, 0, 10)
UIGridLayout7.CellSize = UDim2.new(0, 40, 0, 70)
TextButton8.Name = "DragPart"
TextButton8.Parent = Frame3
TextButton8.Position = UDim2.new(0, 10, 0, 10)
TextButton8.Size = UDim2.new(0, 40, 0, 60)
TextButton8.BackgroundColor = BrickColor.new("Black")
TextButton8.BackgroundColor3 = Color3.new(0.180392, 0.180392, 0.180392)
TextButton8.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton8.BorderSizePixel = 0
TextButton8.Font = Enum.Font.SourceSans
TextButton8.FontSize = Enum.FontSize.Size14
TextButton8.Text = ""
TextButton8.TextColor = BrickColor.new("Really black")
TextButton8.TextColor3 = Color3.new(0, 0, 0)
TextButton8.TextSize = 14
ImageLabel9.Parent = TextButton8
ImageLabel9.Size = UDim2.new(0, 40, 0, 40)
ImageLabel9.BackgroundColor = BrickColor.new("Institutional white")
ImageLabel9.BackgroundColor3 = Color3.new(1, 1, 1)
ImageLabel9.BackgroundTransparency = 1
ImageLabel9.Image = "http://www.roblox.com/asset/?id=8974717361"
ImageLabel9.ImageRectOffset = Vector2.new(0, 40)
ImageLabel9.ImageRectSize = Vector2.new(40, 40)
TextLabel10.Parent = TextButton8
TextLabel10.Position = UDim2.new(0, 0, 0, 42)
TextLabel10.Size = UDim2.new(1, 0, 0, 30)
TextLabel10.BackgroundColor = BrickColor.new("Institutional white")
TextLabel10.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel10.BackgroundTransparency = 1
TextLabel10.Font = Enum.Font.SourceSans
TextLabel10.FontSize = Enum.FontSize.Size14
TextLabel10.Text = "Drag Part"
TextLabel10.TextColor = BrickColor.new("Institutional white")
TextLabel10.TextColor3 = Color3.new(1, 1, 1)
TextLabel10.TextSize = 14
TextLabel10.TextWrap = true
TextLabel10.TextWrapped = true
TextLabel10.TextYAlignment = Enum.TextYAlignment.Top
TextButton11.Name = "Move"
TextButton11.Parent = Frame3
TextButton11.Position = UDim2.new(0, 10, 0, 10)
TextButton11.Size = UDim2.new(0, 40, 0, 60)
TextButton11.BackgroundColor = BrickColor.new("Black")
TextButton11.BackgroundColor3 = Color3.new(0.180392, 0.180392, 0.180392)
TextButton11.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton11.BorderSizePixel = 0
TextButton11.Font = Enum.Font.SourceSans
TextButton11.FontSize = Enum.FontSize.Size14
TextButton11.Text = ""
TextButton11.TextColor = BrickColor.new("Really black")
TextButton11.TextColor3 = Color3.new(0, 0, 0)
TextButton11.TextSize = 14
ImageLabel12.Parent = TextButton11
ImageLabel12.Size = UDim2.new(0, 40, 0, 40)
ImageLabel12.BackgroundColor = BrickColor.new("Institutional white")
ImageLabel12.BackgroundColor3 = Color3.new(1, 1, 1)
ImageLabel12.BackgroundTransparency = 1
ImageLabel12.Image = "http://www.roblox.com/asset/?id=8974717361"
ImageLabel12.ImageRectOffset = Vector2.new(40, 0)
ImageLabel12.ImageRectSize = Vector2.new(40, 40)
TextLabel13.Parent = TextButton11
TextLabel13.Position = UDim2.new(0, 0, 0, 42)
TextLabel13.Size = UDim2.new(1, 0, 0, 30)
TextLabel13.BackgroundColor = BrickColor.new("Institutional white")
TextLabel13.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel13.BackgroundTransparency = 1
TextLabel13.Font = Enum.Font.SourceSans
TextLabel13.FontSize = Enum.FontSize.Size14
TextLabel13.Text = "Move"
TextLabel13.TextColor = BrickColor.new("Institutional white")
TextLabel13.TextColor3 = Color3.new(1, 1, 1)
TextLabel13.TextSize = 14
TextLabel13.TextWrap = true
TextLabel13.TextWrapped = true
TextLabel13.TextYAlignment = Enum.TextYAlignment.Top
TextButton14.Name = "Resize"
TextButton14.Parent = Frame3
TextButton14.Position = UDim2.new(0, 10, 0, 10)
TextButton14.Size = UDim2.new(0, 40, 0, 60)
TextButton14.BackgroundColor = BrickColor.new("Black")
TextButton14.BackgroundColor3 = Color3.new(0.180392, 0.180392, 0.180392)
TextButton14.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton14.BorderSizePixel = 0
TextButton14.Font = Enum.Font.SourceSans
TextButton14.FontSize = Enum.FontSize.Size14
TextButton14.Text = ""
TextButton14.TextColor = BrickColor.new("Really black")
TextButton14.TextColor3 = Color3.new(0, 0, 0)
TextButton14.TextSize = 14
ImageLabel15.Parent = TextButton14
ImageLabel15.Size = UDim2.new(0, 40, 0, 40)
ImageLabel15.BackgroundColor = BrickColor.new("Institutional white")
ImageLabel15.BackgroundColor3 = Color3.new(1, 1, 1)
ImageLabel15.BackgroundTransparency = 1
ImageLabel15.Image = "http://www.roblox.com/asset/?id=8974717361"
ImageLabel15.ImageRectOffset = Vector2.new(80, 0)
ImageLabel15.ImageRectSize = Vector2.new(40, 40)
TextLabel16.Parent = TextButton14
TextLabel16.Position = UDim2.new(0, 0, 0, 42)
TextLabel16.Size = UDim2.new(1, 0, 0, 30)
TextLabel16.BackgroundColor = BrickColor.new("Institutional white")
TextLabel16.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel16.BackgroundTransparency = 1
TextLabel16.Font = Enum.Font.SourceSans
TextLabel16.FontSize = Enum.FontSize.Size14
TextLabel16.Text = "Resize"
TextLabel16.TextColor = BrickColor.new("Institutional white")
TextLabel16.TextColor3 = Color3.new(1, 1, 1)
TextLabel16.TextSize = 14
TextLabel16.TextWrap = true
TextLabel16.TextWrapped = true
TextLabel16.TextYAlignment = Enum.TextYAlignment.Top
TextButton17.Name = "Rotate"
TextButton17.Parent = Frame3
TextButton17.Position = UDim2.new(0, 10, 0, 10)
TextButton17.Size = UDim2.new(0, 40, 0, 60)
TextButton17.BackgroundColor = BrickColor.new("Black")
TextButton17.BackgroundColor3 = Color3.new(0.180392, 0.180392, 0.180392)
TextButton17.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton17.BorderSizePixel = 0
TextButton17.Font = Enum.Font.SourceSans
TextButton17.FontSize = Enum.FontSize.Size14
TextButton17.Text = ""
TextButton17.TextColor = BrickColor.new("Really black")
TextButton17.TextColor3 = Color3.new(0, 0, 0)
TextButton17.TextSize = 14
TextLabel18.Parent = TextButton17
TextLabel18.Position = UDim2.new(0, 0, 0, 42)
TextLabel18.Size = UDim2.new(1, 0, 0, 30)
TextLabel18.BackgroundColor = BrickColor.new("Institutional white")
TextLabel18.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel18.BackgroundTransparency = 1
TextLabel18.Font = Enum.Font.SourceSans
TextLabel18.FontSize = Enum.FontSize.Size14
TextLabel18.Text = "Rotate"
TextLabel18.TextColor = BrickColor.new("Institutional white")
TextLabel18.TextColor3 = Color3.new(1, 1, 1)
TextLabel18.TextSize = 14
TextLabel18.TextWrap = true
TextLabel18.TextWrapped = true
TextLabel18.TextYAlignment = Enum.TextYAlignment.Top
ImageLabel19.Parent = TextButton17
ImageLabel19.Size = UDim2.new(0, 40, 0, 40)
ImageLabel19.BackgroundColor = BrickColor.new("Institutional white")
ImageLabel19.BackgroundColor3 = Color3.new(1, 1, 1)
ImageLabel19.BackgroundTransparency = 1
ImageLabel19.Image = "http://www.roblox.com/asset/?id=8974717361"
ImageLabel19.ImageRectOffset = Vector2.new(120, 0)
ImageLabel19.ImageRectSize = Vector2.new(40, 40)
TextButton20.Name = "Delete"
TextButton20.Parent = Frame3
TextButton20.Position = UDim2.new(0, 10, 0, 10)
TextButton20.Size = UDim2.new(0, 40, 0, 60)
TextButton20.BackgroundColor = BrickColor.new("Black")
TextButton20.BackgroundColor3 = Color3.new(0.180392, 0.180392, 0.180392)
TextButton20.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton20.BorderSizePixel = 0
TextButton20.Font = Enum.Font.SourceSans
TextButton20.FontSize = Enum.FontSize.Size14
TextButton20.Text = ""
TextButton20.TextColor = BrickColor.new("Really black")
TextButton20.TextColor3 = Color3.new(0, 0, 0)
TextButton20.TextSize = 14
ImageLabel21.Parent = TextButton20
ImageLabel21.Size = UDim2.new(0, 40, 0, 40)
ImageLabel21.BackgroundColor = BrickColor.new("Institutional white")
ImageLabel21.BackgroundColor3 = Color3.new(1, 1, 1)
ImageLabel21.BackgroundTransparency = 1
ImageLabel21.Image = "http://www.roblox.com/asset/?id=8974717361"
ImageLabel21.ImageRectOffset = Vector2.new(120, 40)
ImageLabel21.ImageRectSize = Vector2.new(40, 40)
TextLabel22.Parent = TextButton20
TextLabel22.Position = UDim2.new(0, 0, 0, 42)
TextLabel22.Size = UDim2.new(1, 0, 0, 30)
TextLabel22.BackgroundColor = BrickColor.new("Institutional white")
TextLabel22.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel22.BackgroundTransparency = 1
TextLabel22.Font = Enum.Font.SourceSans
TextLabel22.FontSize = Enum.FontSize.Size14
TextLabel22.Text = "Delete"
TextLabel22.TextColor = BrickColor.new("Institutional white")
TextLabel22.TextColor3 = Color3.new(1, 1, 1)
TextLabel22.TextSize = 14
TextLabel22.TextWrap = true
TextLabel22.TextWrapped = true
TextLabel22.TextYAlignment = Enum.TextYAlignment.Top
TextButton23.Name = "Clone"
TextButton23.Parent = Frame3
TextButton23.Position = UDim2.new(0, 10, 0, 10)
TextButton23.Size = UDim2.new(0, 40, 0, 60)
TextButton23.BackgroundColor = BrickColor.new("Black")
TextButton23.BackgroundColor3 = Color3.new(0.180392, 0.180392, 0.180392)
TextButton23.BorderColor3 = Color3.new(0.207843, 0.207843, 0.207843)
TextButton23.BorderSizePixel = 0
TextButton23.Font = Enum.Font.SourceSans
TextButton23.FontSize = Enum.FontSize.Size14
TextButton23.Text = ""
TextButton23.TextColor = BrickColor.new("Really black")
TextButton23.TextColor3 = Color3.new(0, 0, 0)
TextButton23.TextSize = 14
ImageLabel24.Parent = TextButton23
ImageLabel24.Size = UDim2.new(0, 40, 0, 40)
ImageLabel24.BackgroundColor = BrickColor.new("Institutional white")
ImageLabel24.BackgroundColor3 = Color3.new(1, 1, 1)
ImageLabel24.BackgroundTransparency = 1
ImageLabel24.Image = "http://www.roblox.com/asset/?id=8974717361"
ImageLabel24.ImageRectOffset = Vector2.new(120, 120)
ImageLabel24.ImageRectSize = Vector2.new(40, 40)
TextLabel25.Parent = TextButton23
TextLabel25.Position = UDim2.new(0, 0, 0, 42)
TextLabel25.Size = UDim2.new(1, 0, 0, 30)
TextLabel25.BackgroundColor = BrickColor.new("Institutional white")
TextLabel25.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel25.BackgroundTransparency = 1
TextLabel25.Font = Enum.Font.SourceSans
TextLabel25.FontSize = Enum.FontSize.Size14
TextLabel25.Text = "Clone"
TextLabel25.TextColor = BrickColor.new("Institutional white")
TextLabel25.TextColor3 = Color3.new(1, 1, 1)
TextLabel25.TextSize = 14
TextLabel25.TextWrap = true
TextLabel25.TextWrapped = true
TextLabel25.TextYAlignment = Enum.TextYAlignment.Top
TextLabel26.Name = "Title"
TextLabel26.Parent = Frame2
TextLabel26.Position = UDim2.new(0.5, 0, 1, -10)
TextLabel26.AnchorPoint = Vector2.new(0.5, 0)
TextLabel26.BackgroundColor = BrickColor.new("Institutional white")
TextLabel26.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel26.Font = Enum.Font.SourceSans
TextLabel26.FontSize = Enum.FontSize.Size14
TextLabel26.Text = "Advanced BTools"
TextLabel26.TextColor = BrickColor.new("Quill grey")
TextLabel26.TextColor3 = Color3.new(0.85098, 0.85098, 0.85098)
TextLabel26.TextSize = 14
LocalScript27.Name = "Btools"
LocalScript27.Parent = Frame2
table.insert(cors,sandbox(LocalScript27,function()
local sp = script.Parent
local runservice = game:GetService("RunService")
local player = game.Players.LocalPlayer
local mouse = player:GetMouse()

local buttons = sp.Buttons
local step = sp.Parent.Configuration.Step
local rotation = sp.Parent.Configuration.Rotate
local selectionBox = sp.SelectionBox
local arcHandles = sp.ArcHandles
local scaleHandles = sp.ScaleHandles
local moveHandles = sp.MoveHandles
local buttonsChildren = buttons:GetChildren()

local mode = buttons.None

--\\TOOL VARS
local cloneSelect = nil
local cloneOrigin = nil
local cloneDragger = nil
local dragSelect = nil
local dragDragger = nil
local scalePreviousDist = 0
local arcPreviousCFrame = nil
--\\

function round(number, increment)
	return math.floor((number / increment) + 0.5) * increment
end

function AngleFromAxis(axis, r, increment)
	local relativeAngle = math.rad(round(math.deg(r), increment))

	return axis == Enum.Axis.X and {relativeAngle, 0, 0} 
		or axis == Enum.Axis.Y and {0, relativeAngle, 0} 
		or axis == Enum.Axis.Z and {0, 0, relativeAngle}
end

local function clear()
	selectionBox.Adornee = nil
	selectionBox.Color3 = Color3.fromRGB(53, 53, 53)
	selectionBox.SurfaceColor3 = Color3.fromRGB(53, 53, 53)
	mouse.Icon = "rbxasset://textures\\advCursor-default.png"
	
	arcHandles.Adornee = nil
	scaleHandles.Adornee = nil
	moveHandles.Adornee = nil
	
	--\\REMOVE VARIABLES
	local cloneSelect = nil
	local cloneOrigin = nil
	local cloneDragger = nil
	local dragSelect = nil
	local dragDragger = nil
	local scalePreviousDist = 0
	local arcPreviousCFrame = nil
end

local function changeModevisual()
	for i = 1, #buttonsChildren do
		local newButton = buttonsChildren[i]
		if newButton:IsA("TextButton") then
			if mode == newButton then
				newButton.BackgroundColor3 = Color3.fromRGB(28, 28, 28)
				newButton.BorderSizePixel = 1
			else
				newButton.BackgroundColor3 = Color3.fromRGB(46, 46, 46)
				newButton.BorderSizePixel = 0
			end
		end
	end
end

for i = 1, #buttonsChildren do
	local newButton = buttonsChildren[i]
	if newButton:IsA("TextButton") then
		newButton.MouseButton1Down:Connect(function()
			if mode == newButton then
				mode = buttons.None
			else
				mode = newButton
			end
			clear()
			changeModevisual()
		end)
	end
end

function RenderStepped()
	if mode == buttons.None then
		clear()
	end
	--\\DELETE
	if mode == buttons.Delete then
		selectionBox.Color3 = Color3.fromRGB(255, 0, 0)
		selectionBox.SurfaceColor3 = Color3.fromRGB(255, 0, 0)
		local target = mouse.Target
		local hit = mouse.Hit
		if target and not target.Locked then
			selectionBox.Adornee = target
			mouse.Icon = "http://www.roblox.com/asset?id=72539748"
		else
			selectionBox.Adornee = nil
			mouse.Icon = "rbxasset://textures\\advCursor-default.png"
		end
	end
	--\\CLONE
	if mode == buttons:FindFirstChild("Clone") then
		selectionBox.Color3 = Color3.fromRGB(0, 255, 0)
		selectionBox.SurfaceColor3 = Color3.fromRGB(0, 255, 0)
	end
end

function onMouseButton1Down()
	--\\DELETE
	if mode == buttons.Delete then
		local target = mouse.Target
		if target and not target.Locked  then
			local hit = mouse.Hit
			target:Destroy()

			local explosion = Instance.new("Explosion")

			explosion.BlastPressure = 0
			explosion.DestroyJointRadiusPercent = 0
			explosion.ExplosionType = Enum.ExplosionType.NoCraters

			explosion.Position = target.Position
			explosion.Parent = workspace

			local explosionsound = Instance.new("Sound")
			explosionsound.SoundId = "rbxasset://sounds/collide.wav"
			explosionsound.Parent = player
			explosionsound.PlayOnRemove = true
			explosionsound:Destroy()
		end
	end
	--\\CLONE
	if mode == buttons:FindFirstChild("Clone") then
		local Target = mouse.Target
		local Sound = Instance.new("Sound")-- The "ding" sound
		Sound.SoundId = "rbxasset://sounds\\electronicpingshort.wav"
		Sound.Name = "PewPew"
		Sound.Parent = workspace

		if Target and Target:IsA("BasePart") and not Target.Locked then
			cloneOrigin = Target
			cloneSelect = cloneOrigin:clone()

			cloneSelect.Parent = game.Workspace
			cloneSelect.Position = cloneOrigin.Position + Vector3.new(0, 0.4, 0)

			cloneDragger = Instance.new("Dragger")
			pcall(function() cloneDragger:MouseDown(cloneSelect, Vector3.new(0, 0, 0), {cloneSelect}) end)

			selectionBox.Adornee = cloneSelect
			Sound:Play()
			mouse.Icon = "rbxasset://textures\\DragCursor.png"
		end
	end
	--\\DRAG PART
	if mode == buttons:FindFirstChild("DragPart") then
		local Target = mouse.Target

		if Target and Target:IsA("BasePart") and not Target.Locked then
			dragSelect = Target
			dragDragger = Instance.new("Dragger")
			pcall(function() dragDragger:MouseDown(dragSelect, Vector3.new(0, 0, 0), {dragSelect}) end)

			selectionBox.Adornee = dragSelect
			mouse.Icon = "rbxasset://textures\\DragCursor.png"
		end
	end
	--\\SCALE
	if mode == buttons:FindFirstChild("Resize") then
		if mouse.Target == nil or mouse.Target.Locked then
			selectionBox.Adornee = nil
			scaleHandles.Adornee = nil
		else
			selectionBox.Adornee = mouse.Target
			scaleHandles.Adornee = mouse.Target
			scaleHandles.Faces = mouse.Target.ResizeableFaces
		end
	end
	--\\ROTATE
	if mode == buttons:FindFirstChild("Rotate") then
		if mouse.Target == nil or mouse.Target.Locked then
			selectionBox.Adornee = nil
			arcHandles.Adornee = nil
		else
			selectionBox.Adornee = mouse.Target
			arcHandles.Adornee = mouse.Target
		end
	end
	--\\MOVE
	if mode == buttons:FindFirstChild("Move") then
		if mouse.Target == nil or mouse.Target.Locked then
			selectionBox.Adornee = nil
			moveHandles.Adornee = nil
		else
			selectionBox.Adornee = mouse.Target
			moveHandles.Adornee = mouse.Target
		end
	end
end

function onMouseButton1Up()
	--\\CLONE
	if mode == buttons:FindFirstChild("Clone") then
		if cloneDragger then
			cloneOrigin = nil
			pcall(function() cloneDragger:MouseUp() end)
			cloneSelect = nil
			selectionBox.Adornee = nil
			cloneDragger = nil
			mouse.Icon = "rbxasset://textures\\advCursor-default.png"
		end
	end
	--\\DRAG PART
	if mode == buttons:FindFirstChild("DragPart") then
		if dragDragger then
			pcall(function() dragDragger:MouseUp() end)
			dragSelect = nil
			selectionBox.Adornee = nil
			dragDragger = nil
			mouse.Icon = "rbxasset://textures\\advCursor-default.png"
		end
	end
end

function onMouseMove()
	--\\CLONE
	if mode == buttons:FindFirstChild("Clone") then
		if cloneDragger then
			mouse.Icon = "rbxasset://textures\\GrabRotateCursor.png"
			pcall(function() cloneDragger:MouseMove(mouse.UnitRay) end)
		else
			local Target = mouse.Target
			if Target and Target:IsA("BasePart") and not Target.Locked then
				mouse.Icon = "http://www.roblox.com/asset/?id=8973982224"
			else
				mouse.Icon = "rbxasset://textures\\advCursor-default.png"
			end
		end
	end
	--\\DRAG PART
	if mode == buttons:FindFirstChild("DragPart") then
		if dragDragger then
			mouse.Icon = "rbxasset://textures\\GrabRotateCursor.png"
			pcall(function() dragDragger:MouseMove(mouse.UnitRay) end)
		else
			local Target = mouse.Target
			if Target and Target:IsA("BasePart") and not Target.Locked then
				mouse.Icon = "rbxasset://textures\\advCursor-openedHand"
			else
				mouse.Icon = "rbxasset://textures\\advCursor-default.png"
			end
		end
	end
end

function onKeyDown(key)
	--\\CLONE
	if mode == buttons:FindFirstChild("Clone") then
		if cloneDragger then
			key = key:lower()
			if key == 'r' then
				cloneDragger:AxisRotate(Enum.Axis.Y)
			elseif key == 't' then
				cloneDragger:AxisRotate(Enum.Axis.Z)
			end
		end
	end
	--\\DRAG PART
	if mode == buttons:FindFirstChild("DragPart") then
		if dragDragger then
			key = key:lower()
			if key == 'r' then
				dragDragger:AxisRotate(Enum.Axis.Y)
			elseif key == 't' then
				dragDragger:AxisRotate(Enum.Axis.Z)
			end
		end
	end
end

function onScaleHandlesDown(normal)
	scalePreviousDist = 0
end

function onScaleHandlesDrag(normal, distance)
	local resizeIncrement = tonumber(step.Text)
	if resizeIncrement == nil then
		resizeIncrement = 1
	end
	
	if scaleHandles.Adornee then
		local delta = distance - scalePreviousDist
		if math.abs(delta) >= resizeIncrement then
			local sizeDelta = math.floor(delta / resizeIncrement + 0.5) * resizeIncrement
			if scaleHandles.Adornee:Resize(normal, sizeDelta) then
				scalePreviousDist = distance
			end
		end
	end
end

function onMoveHandlesDown()
	CF = moveHandles.Adornee.CFrame
end

function onMoveHandlesDrag(id, distance)
	local moving = moveHandles.Adornee
	local axi = {
		[Enum.NormalId.Right] = moving.CFrame.RightVector,
		[Enum.NormalId.Left] = -moving.CFrame.RightVector,
		[Enum.NormalId.Top] = moving.CFrame.UpVector, 
		[Enum.NormalId.Bottom] = -moving.CFrame.UpVector,
		[Enum.NormalId.Front] = moving.CFrame.LookVector,
		[Enum.NormalId.Back] = -moving.CFrame.LookVector,
	}
	moving.CFrame = CF + axi[id] * (math.floor(distance / step.Text) * step.Text)
end

function onArcHandlesDown()
	arcPreviousCFrame = arcHandles.Adornee.CFrame
end

function onArcHandlesDrag(axis, relativeAngle, delta)
	local increment = tonumber(rotation.Text)
	if increment == nil then
		increment = 45
	end
	arcHandles.Adornee.CFrame = arcPreviousCFrame * CFrame.Angles(unpack(AngleFromAxis(axis, relativeAngle, increment)))
end

scaleHandles.MouseDrag:connect(onScaleHandlesDrag)
scaleHandles.MouseButton1Down:connect(onScaleHandlesDown)

arcHandles.MouseDrag:connect(onArcHandlesDrag)
arcHandles.MouseButton1Down:connect(onArcHandlesDown)

moveHandles.MouseDrag:connect(onMoveHandlesDrag)
moveHandles.MouseButton1Down:connect(onMoveHandlesDown)

mouse.Button1Down:Connect(onMouseButton1Down)
mouse.Button1Up:Connect(onMouseButton1Up)
mouse.Move:Connect(onMouseMove)
mouse.KeyDown:connect(onKeyDown)
runservice.RenderStepped:Connect(RenderStepped)
end))
Handles28.Name = "MoveHandles"
Handles28.Parent = Frame2
Handles28.Color = BrickColor.new("Really black")
Handles28.Color3 = Color3.new(0, 0, 0)
Handles28.Style = Enum.HandlesStyle.Movement
Handles29.Name = "ScaleHandles"
Handles29.Parent = Frame2
Handles29.Color = BrickColor.new("Really black")
Handles29.Color3 = Color3.new(0, 0, 0)
ArcHandles30.Parent = Frame2
ArcHandles30.Color = BrickColor.new("Dark stone grey")
ArcHandles30.Color3 = Color3.new(0.364706, 0.364706, 0.364706)
SelectionBox31.Parent = Frame2
SelectionBox31.Color = BrickColor.new("Black")
SelectionBox31.Color3 = Color3.new(0.207843, 0.207843, 0.207843)
SelectionBox31.LineThickness = 0.05000000074505806
SelectionBox31.SurfaceColor = BrickColor.new("Institutional white")
SelectionBox31.SurfaceColor3 = Color3.new(1, 1, 1)
SelectionBox31.SurfaceTransparency = 0.800000011920929
UIListLayout32.Parent = Frame1
UIListLayout32.FillDirection = Enum.FillDirection.Horizontal
UIListLayout32.SortOrder = Enum.SortOrder.LayoutOrder
Frame33.Name = "Lock"
Frame33.Parent = Frame1
Frame33.Size = UDim2.new(0, 160, 1, 0)
Frame33.BackgroundColor = BrickColor.new("Black")
Frame33.BackgroundColor3 = Color3.new(0.180392, 0.180392, 0.180392)
Frame33.BorderColor3 = Color3.new(0.145098, 0.145098, 0.145098)
Frame34.Name = "Buttons"
Frame34.Parent = Frame33
Frame34.Position = UDim2.new(0, 10, 0, 10)
Frame34.Size = UDim2.new(1, 0, 1, -20)
Frame34.BackgroundColor = BrickColor.new("Institutional white")
Frame34.BackgroundColor3 = Color3.new(1, 1, 1)
Frame34.BackgroundTransparency = 1
UIGridLayout35.Parent = Frame34
UIGridLayout35.SortOrder = Enum.SortOrder.LayoutOrder
UIGridLayout35.CellPadding = UDim2.new(0, 10, 0, 10)
UIGridLayout35.CellSize = UDim2.new(0, 40, 0, 70)
TextButton36.Name = "UnlockAll"
TextButton36.Parent = Frame34
TextButton36.Position = UDim2.new(0, 10, 0, 10)
TextButton36.Size = UDim2.new(0, 40, 0, 60)
TextButton36.BackgroundColor = BrickColor.new("Black")
TextButton36.BackgroundColor3 = Color3.new(0.180392, 0.180392, 0.180392)
TextButton36.BorderColor = BrickColor.new("Really black")
TextButton36.BorderColor3 = Color3.new(0, 0, 0)
TextButton36.BorderSizePixel = 0
TextButton36.Font = Enum.Font.SourceSans
TextButton36.FontSize = Enum.FontSize.Size14
TextButton36.Text = ""
TextButton36.TextColor = BrickColor.new("Really black")
TextButton36.TextColor3 = Color3.new(0, 0, 0)
TextButton36.TextSize = 14
ImageLabel37.Parent = TextButton36
ImageLabel37.Size = UDim2.new(0, 40, 0, 40)
ImageLabel37.BackgroundColor = BrickColor.new("Institutional white")
ImageLabel37.BackgroundColor3 = Color3.new(1, 1, 1)
ImageLabel37.BackgroundTransparency = 1
ImageLabel37.Image = "http://www.roblox.com/asset/?id=8974717361"
ImageLabel37.ImageRectOffset = Vector2.new(0, 80)
ImageLabel37.ImageRectSize = Vector2.new(40, 40)
TextLabel38.Parent = TextButton36
TextLabel38.Position = UDim2.new(0, 0, 0, 42)
TextLabel38.Size = UDim2.new(1, 0, 0, 30)
TextLabel38.BackgroundColor = BrickColor.new("Institutional white")
TextLabel38.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel38.BackgroundTransparency = 1
TextLabel38.Font = Enum.Font.SourceSans
TextLabel38.FontSize = Enum.FontSize.Size14
TextLabel38.Text = "Unlock All"
TextLabel38.TextColor = BrickColor.new("Institutional white")
TextLabel38.TextColor3 = Color3.new(1, 1, 1)
TextLabel38.TextSize = 14
TextLabel38.TextWrap = true
TextLabel38.TextWrapped = true
TextLabel38.TextYAlignment = Enum.TextYAlignment.Top
LocalScript39.Parent = TextButton36
table.insert(cors,sandbox(LocalScript39,function()
script.Parent.MouseButton1Down:Connect(function()
	local descendants = game.Workspace:GetDescendants()
	for i = 1, #descendants do
		local part = descendants[i]
		if part:IsA("BasePart") then
			part.Locked = false
		end
	end
end)
end))
TextButton40.Name = "LockAll"
TextButton40.Parent = Frame34
TextButton40.Position = UDim2.new(0, 10, 0, 10)
TextButton40.Size = UDim2.new(0, 40, 0, 60)
TextButton40.BackgroundColor = BrickColor.new("Black")
TextButton40.BackgroundColor3 = Color3.new(0.180392, 0.180392, 0.180392)
TextButton40.BorderColor = BrickColor.new("Really black")
TextButton40.BorderColor3 = Color3.new(0, 0, 0)
TextButton40.BorderSizePixel = 0
TextButton40.Font = Enum.Font.SourceSans
TextButton40.FontSize = Enum.FontSize.Size14
TextButton40.Text = ""
TextButton40.TextColor = BrickColor.new("Really black")
TextButton40.TextColor3 = Color3.new(0, 0, 0)
TextButton40.TextSize = 14
ImageLabel41.Parent = TextButton40
ImageLabel41.Size = UDim2.new(0, 40, 0, 40)
ImageLabel41.BackgroundColor = BrickColor.new("Institutional white")
ImageLabel41.BackgroundColor3 = Color3.new(1, 1, 1)
ImageLabel41.BackgroundTransparency = 1
ImageLabel41.Image = "http://www.roblox.com/asset/?id=8974717361"
ImageLabel41.ImageRectOffset = Vector2.new(40, 80)
ImageLabel41.ImageRectSize = Vector2.new(40, 40)
TextLabel42.Parent = TextButton40
TextLabel42.Position = UDim2.new(0, 0, 0, 42)
TextLabel42.Size = UDim2.new(1, 0, 0, 30)
TextLabel42.BackgroundColor = BrickColor.new("Institutional white")
TextLabel42.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel42.BackgroundTransparency = 1
TextLabel42.Font = Enum.Font.SourceSans
TextLabel42.FontSize = Enum.FontSize.Size14
TextLabel42.Text = "Lock All"
TextLabel42.TextColor = BrickColor.new("Institutional white")
TextLabel42.TextColor3 = Color3.new(1, 1, 1)
TextLabel42.TextSize = 14
TextLabel42.TextWrap = true
TextLabel42.TextWrapped = true
TextLabel42.TextYAlignment = Enum.TextYAlignment.Top
LocalScript43.Parent = TextButton40
table.insert(cors,sandbox(LocalScript43,function()
script.Parent.MouseButton1Down:Connect(function()
	local descendants = game.Workspace:GetDescendants()
	for i = 1, #descendants do
		local part = descendants[i]
		if part:IsA("BasePart") then
			part.Locked = true
		end
	end
end)
end))
TextButton44.Name = "DefaultLock"
TextButton44.Parent = Frame34
TextButton44.Position = UDim2.new(0, 10, 0, 10)
TextButton44.Size = UDim2.new(0, 40, 0, 60)
TextButton44.BackgroundColor = BrickColor.new("Black")
TextButton44.BackgroundColor3 = Color3.new(0.180392, 0.180392, 0.180392)
TextButton44.BorderColor = BrickColor.new("Really black")
TextButton44.BorderColor3 = Color3.new(0, 0, 0)
TextButton44.BorderSizePixel = 0
TextButton44.Font = Enum.Font.SourceSans
TextButton44.FontSize = Enum.FontSize.Size14
TextButton44.Text = ""
TextButton44.TextColor = BrickColor.new("Really black")
TextButton44.TextColor3 = Color3.new(0, 0, 0)
TextButton44.TextSize = 14
ImageLabel45.Parent = TextButton44
ImageLabel45.Size = UDim2.new(0, 40, 0, 40)
ImageLabel45.BackgroundColor = BrickColor.new("Institutional white")
ImageLabel45.BackgroundColor3 = Color3.new(1, 1, 1)
ImageLabel45.BackgroundTransparency = 1
ImageLabel45.Image = "http://www.roblox.com/asset/?id=8974717361"
ImageLabel45.ImageRectOffset = Vector2.new(120, 80)
ImageLabel45.ImageRectSize = Vector2.new(40, 40)
TextLabel46.Parent = TextButton44
TextLabel46.Position = UDim2.new(0, 0, 0, 42)
TextLabel46.Size = UDim2.new(1, 0, 0, 30)
TextLabel46.BackgroundColor = BrickColor.new("Institutional white")
TextLabel46.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel46.BackgroundTransparency = 1
TextLabel46.Font = Enum.Font.SourceSans
TextLabel46.FontSize = Enum.FontSize.Size14
TextLabel46.Text = "Default Lock"
TextLabel46.TextColor = BrickColor.new("Institutional white")
TextLabel46.TextColor3 = Color3.new(1, 1, 1)
TextLabel46.TextSize = 14
TextLabel46.TextWrap = true
TextLabel46.TextWrapped = true
TextLabel46.TextYAlignment = Enum.TextYAlignment.Top
LocalScript47.Parent = TextButton44
table.insert(cors,sandbox(LocalScript47,function()
local locked = {}
local descendants = game.Workspace:GetDescendants()
for i = 1, #descendants do
	local part = descendants[i]
	if part:IsA("BasePart") then
		if part.Locked then
			locked[i] = true
		else
			locked[i] = false
		end
	end
end

script.Parent.MouseButton1Down:Connect(function()
	local descendants = game.Workspace:GetDescendants()
	for i = 1, #descendants do
		local part = descendants[i]
		if part:IsA("BasePart") then
			part.Locked = locked[i]
		end
	end
end)
end))
TextLabel48.Name = "Title"
TextLabel48.Parent = Frame33
TextLabel48.Position = UDim2.new(0.5, 0, 1, -10)
TextLabel48.AnchorPoint = Vector2.new(0.5, 0)
TextLabel48.BackgroundColor = BrickColor.new("Institutional white")
TextLabel48.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel48.Font = Enum.Font.SourceSans
TextLabel48.FontSize = Enum.FontSize.Size14
TextLabel48.Text = "Lock"
TextLabel48.TextColor = BrickColor.new("Quill grey")
TextLabel48.TextColor3 = Color3.new(0.85098, 0.85098, 0.85098)
TextLabel48.TextSize = 14
Frame49.Name = "Insert"
Frame49.Parent = Frame1
Frame49.Size = UDim2.new(0, 60, 1, 0)
Frame49.BackgroundColor = BrickColor.new("Black")
Frame49.BackgroundColor3 = Color3.new(0.180392, 0.180392, 0.180392)
Frame49.BorderColor3 = Color3.new(0.145098, 0.145098, 0.145098)
Frame50.Name = "Buttons"
Frame50.Parent = Frame49
Frame50.Position = UDim2.new(0, 10, 0, 10)
Frame50.Size = UDim2.new(1, 0, 1, -20)
Frame50.BackgroundColor = BrickColor.new("Institutional white")
Frame50.BackgroundColor3 = Color3.new(1, 1, 1)
Frame50.BackgroundTransparency = 1
UIGridLayout51.Parent = Frame50
UIGridLayout51.SortOrder = Enum.SortOrder.LayoutOrder
UIGridLayout51.CellPadding = UDim2.new(0, 10, 0, 10)
UIGridLayout51.CellSize = UDim2.new(0, 40, 0, 70)
TextButton52.Name = "InsertPart"
TextButton52.Parent = Frame50
TextButton52.Position = UDim2.new(0, 10, 0, 10)
TextButton52.Size = UDim2.new(0, 40, 0, 60)
TextButton52.BackgroundColor = BrickColor.new("Black")
TextButton52.BackgroundColor3 = Color3.new(0.180392, 0.180392, 0.180392)
TextButton52.BorderColor = BrickColor.new("Really black")
TextButton52.BorderColor3 = Color3.new(0, 0, 0)
TextButton52.BorderSizePixel = 0
TextButton52.Font = Enum.Font.SourceSans
TextButton52.FontSize = Enum.FontSize.Size14
TextButton52.Text = ""
TextButton52.TextColor = BrickColor.new("Really black")
TextButton52.TextColor3 = Color3.new(0, 0, 0)
TextButton52.TextSize = 14
ImageLabel53.Parent = TextButton52
ImageLabel53.Size = UDim2.new(0, 40, 0, 40)
ImageLabel53.BackgroundColor = BrickColor.new("Institutional white")
ImageLabel53.BackgroundColor3 = Color3.new(1, 1, 1)
ImageLabel53.BackgroundTransparency = 1
ImageLabel53.Image = "http://www.roblox.com/asset/?id=8974717361"
ImageLabel53.ImageRectOffset = Vector2.new(80, 40)
ImageLabel53.ImageRectSize = Vector2.new(40, 40)
TextLabel54.Parent = TextButton52
TextLabel54.Position = UDim2.new(0, 0, 0, 42)
TextLabel54.Size = UDim2.new(1, 0, 0, 30)
TextLabel54.BackgroundColor = BrickColor.new("Institutional white")
TextLabel54.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel54.BackgroundTransparency = 1
TextLabel54.Font = Enum.Font.SourceSans
TextLabel54.FontSize = Enum.FontSize.Size14
TextLabel54.Text = "Insert Part"
TextLabel54.TextColor = BrickColor.new("Institutional white")
TextLabel54.TextColor3 = Color3.new(1, 1, 1)
TextLabel54.TextSize = 14
TextLabel54.TextWrap = true
TextLabel54.TextWrapped = true
TextLabel54.TextYAlignment = Enum.TextYAlignment.Top
LocalScript55.Parent = TextButton52
table.insert(cors,sandbox(LocalScript55,function()
function round(number, increment)
	return math.floor((number / increment) + 0.5) * increment
end

script.Parent.MouseButton1Down:Connect(function()
	local p = Instance.new("Part")
	local root = game.Players.LocalPlayer.Character:WaitForChild("HumanoidRootPart")
	p.Position = Vector3.new(round(root.Position.X, 1),round(root.Position.Y+4, 1),round(root.Position.Z, 1))
	p.Anchored = true
	p.Parent = workspace
end)
end))
TextButton56.Name = "InsertID"
TextButton56.Parent = Frame50
TextButton56.Position = UDim2.new(0, 10, 0, 10)
TextButton56.Visible = false
TextButton56.Size = UDim2.new(0, 40, 0, 60)
TextButton56.BackgroundColor = BrickColor.new("Black")
TextButton56.BackgroundColor3 = Color3.new(0.180392, 0.180392, 0.180392)
TextButton56.BorderColor = BrickColor.new("Really black")
TextButton56.BorderColor3 = Color3.new(0, 0, 0)
TextButton56.BorderSizePixel = 0
TextButton56.Font = Enum.Font.SourceSans
TextButton56.FontSize = Enum.FontSize.Size14
TextButton56.Text = ""
TextButton56.TextColor = BrickColor.new("Really black")
TextButton56.TextColor3 = Color3.new(0, 0, 0)
TextButton56.TextSize = 14
ImageLabel57.Parent = TextButton56
ImageLabel57.Size = UDim2.new(0, 40, 0, 40)
ImageLabel57.BackgroundColor = BrickColor.new("Institutional white")
ImageLabel57.BackgroundColor3 = Color3.new(1, 1, 1)
ImageLabel57.BackgroundTransparency = 1
ImageLabel57.Image = "http://www.roblox.com/asset/?id=8974717361"
ImageLabel57.ImageRectOffset = Vector2.new(80, 80)
ImageLabel57.ImageRectSize = Vector2.new(40, 40)
TextLabel58.Parent = TextButton56
TextLabel58.Position = UDim2.new(0, 0, 0, 42)
TextLabel58.Size = UDim2.new(1, 0, 0, 30)
TextLabel58.BackgroundColor = BrickColor.new("Institutional white")
TextLabel58.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel58.BackgroundTransparency = 1
TextLabel58.Font = Enum.Font.SourceSans
TextLabel58.FontSize = Enum.FontSize.Size14
TextLabel58.Text = "Insert ID"
TextLabel58.TextColor = BrickColor.new("Institutional white")
TextLabel58.TextColor3 = Color3.new(1, 1, 1)
TextLabel58.TextSize = 14
TextLabel58.TextWrap = true
TextLabel58.TextWrapped = true
TextLabel58.TextYAlignment = Enum.TextYAlignment.Top
TextLabel59.Name = "Title"
TextLabel59.Parent = Frame49
TextLabel59.Position = UDim2.new(0.5, 0, 1, -10)
TextLabel59.AnchorPoint = Vector2.new(0.5, 0)
TextLabel59.BackgroundColor = BrickColor.new("Institutional white")
TextLabel59.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel59.Font = Enum.Font.SourceSans
TextLabel59.FontSize = Enum.FontSize.Size14
TextLabel59.Text = "Insert"
TextLabel59.TextColor = BrickColor.new("Quill grey")
TextLabel59.TextColor3 = Color3.new(0.85098, 0.85098, 0.85098)
TextLabel59.TextSize = 14
Frame60.Name = "Configuration"
Frame60.Parent = Frame1
Frame60.Size = UDim2.new(0, 250, 1, 0)
Frame60.BackgroundColor = BrickColor.new("Black")
Frame60.BackgroundColor3 = Color3.new(0.180392, 0.180392, 0.180392)
Frame60.BorderColor3 = Color3.new(0.145098, 0.145098, 0.145098)
TextLabel61.Name = "Title"
TextLabel61.Parent = Frame60
TextLabel61.Position = UDim2.new(0.5, 0, 1, -10)
TextLabel61.AnchorPoint = Vector2.new(0.5, 0)
TextLabel61.BackgroundColor = BrickColor.new("Institutional white")
TextLabel61.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel61.Font = Enum.Font.SourceSans
TextLabel61.FontSize = Enum.FontSize.Size14
TextLabel61.Text = "Configuration"
TextLabel61.TextColor = BrickColor.new("Quill grey")
TextLabel61.TextColor3 = Color3.new(0.85098, 0.85098, 0.85098)
TextLabel61.TextSize = 14
TextBox62.Name = "Step"
TextBox62.Parent = Frame60
TextBox62.Position = UDim2.new(0, 20, 0, 35)
TextBox62.Size = UDim2.new(0, 100, 0, 20)
TextBox62.BackgroundColor = BrickColor.new("Black")
TextBox62.BackgroundColor3 = Color3.new(0.145098, 0.145098, 0.145098)
TextBox62.BorderColor = BrickColor.new("Really black")
TextBox62.BorderColor3 = Color3.new(0.101961, 0.101961, 0.101961)
TextBox62.Font = Enum.Font.SourceSans
TextBox62.FontSize = Enum.FontSize.Size14
TextBox62.Text = "1"
TextBox62.TextColor = BrickColor.new("Institutional white")
TextBox62.TextColor3 = Color3.new(1, 1, 1)
TextBox62.TextSize = 14
TextBox62.TextXAlignment = Enum.TextXAlignment.Left
TextBox62.ClearTextOnFocus = false
TextBox62.PlaceholderColor3 = Color3.new(0.529412, 0.529412, 0.529412)
TextBox62.PlaceholderText = "Enter Value..."
TextLabel63.Parent = TextBox62
TextLabel63.Position = UDim2.new(1, 6, 0, 0)
TextLabel63.Size = UDim2.new(0, 0, 1, 0)
TextLabel63.BackgroundColor = BrickColor.new("Institutional white")
TextLabel63.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel63.Font = Enum.Font.SourceSans
TextLabel63.FontSize = Enum.FontSize.Size14
TextLabel63.Text = "Step (resize & move)"
TextLabel63.TextColor = BrickColor.new("Institutional white")
TextLabel63.TextColor3 = Color3.new(1, 1, 1)
TextLabel63.TextSize = 14
TextLabel63.TextXAlignment = Enum.TextXAlignment.Left
TextBox64.Name = "Rotate"
TextBox64.Parent = Frame60
TextBox64.Position = UDim2.new(0, 20, 0, 60)
TextBox64.Size = UDim2.new(0, 100, 0, 20)
TextBox64.BackgroundColor = BrickColor.new("Black")
TextBox64.BackgroundColor3 = Color3.new(0.145098, 0.145098, 0.145098)
TextBox64.BorderColor = BrickColor.new("Really black")
TextBox64.BorderColor3 = Color3.new(0.101961, 0.101961, 0.101961)
TextBox64.Font = Enum.Font.SourceSans
TextBox64.FontSize = Enum.FontSize.Size14
TextBox64.Text = "45"
TextBox64.TextColor = BrickColor.new("Institutional white")
TextBox64.TextColor3 = Color3.new(1, 1, 1)
TextBox64.TextSize = 14
TextBox64.TextXAlignment = Enum.TextXAlignment.Left
TextBox64.ClearTextOnFocus = false
TextBox64.PlaceholderColor3 = Color3.new(0.529412, 0.529412, 0.529412)
TextBox64.PlaceholderText = "Enter Value..."
TextLabel65.Parent = TextBox64
TextLabel65.Position = UDim2.new(1, 6, 0, 0)
TextLabel65.Size = UDim2.new(0, 0, 1, 0)
TextLabel65.BackgroundColor = BrickColor.new("Institutional white")
TextLabel65.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel65.Font = Enum.Font.SourceSans
TextLabel65.FontSize = Enum.FontSize.Size14
TextLabel65.Text = "Rotation"
TextLabel65.TextColor = BrickColor.new("Institutional white")
TextLabel65.TextColor3 = Color3.new(1, 1, 1)
TextLabel65.TextSize = 14
TextLabel65.TextXAlignment = Enum.TextXAlignment.Left
TextBox66.Name = "ID"
TextBox66.Parent = Frame60
TextBox66.Position = UDim2.new(0, 20, 0, 10)
TextBox66.Visible = false
TextBox66.Size = UDim2.new(0, 100, 0, 20)
TextBox66.BackgroundColor = BrickColor.new("Black")
TextBox66.BackgroundColor3 = Color3.new(0.145098, 0.145098, 0.145098)
TextBox66.BorderColor = BrickColor.new("Really black")
TextBox66.BorderColor3 = Color3.new(0.101961, 0.101961, 0.101961)
TextBox66.Font = Enum.Font.SourceSans
TextBox66.FontSize = Enum.FontSize.Size14
TextBox66.Text = "699585131"
TextBox66.TextColor = BrickColor.new("Institutional white")
TextBox66.TextColor3 = Color3.new(1, 1, 1)
TextBox66.TextSize = 14
TextBox66.TextXAlignment = Enum.TextXAlignment.Left
TextBox66.ClearTextOnFocus = false
TextBox66.PlaceholderColor3 = Color3.new(0.529412, 0.529412, 0.529412)
TextBox66.PlaceholderText = "Enter Value..."
TextLabel67.Parent = TextBox66
TextLabel67.Position = UDim2.new(1, 6, 0, 0)
TextLabel67.Size = UDim2.new(0, 0, 1, 0)
TextLabel67.BackgroundColor = BrickColor.new("Institutional white")
TextLabel67.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel67.Font = Enum.Font.SourceSans
TextLabel67.FontSize = Enum.FontSize.Size14
TextLabel67.Text = "ID"
TextLabel67.TextColor = BrickColor.new("Institutional white")
TextLabel67.TextColor3 = Color3.new(1, 1, 1)
TextLabel67.TextSize = 14
TextLabel67.TextXAlignment = Enum.TextXAlignment.Left
TextLabel68.Name = "Creds"
TextLabel68.Parent = ScreenGui0
TextLabel68.Position = UDim2.new(1, 0, 1, 0)
TextLabel68.Size = UDim2.new(0, 200, 0, 15)
TextLabel68.AnchorPoint = Vector2.new(1, 1)
TextLabel68.BackgroundColor = BrickColor.new("Institutional white")
TextLabel68.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel68.BackgroundTransparency = 1
TextLabel68.ZIndex = 999999999
TextLabel68.Font = Enum.Font.SourceSans
TextLabel68.FontSize = Enum.FontSize.Size14
TextLabel68.Text = ""
TextLabel68.TextColor = BrickColor.new("Light grey metallic")
TextLabel68.TextColor3 = Color3.new(0.690196, 0.690196, 0.690196)
TextLabel68.TextSize = 14
TextLabel68.TextXAlignment = Enum.TextXAlignment.Right
TextButton69.Name = "Close"
TextButton69.Parent = ScreenGui0
TextButton69.Position = UDim2.new(1, 0, 1, -80)
TextButton69.Size = UDim2.new(0, 20, 0, 20)
TextButton69.AnchorPoint = Vector2.new(1, 1)
TextButton69.BackgroundColor = BrickColor.new("Black")
TextButton69.BackgroundColor3 = Color3.new(0.145098, 0.145098, 0.145098)
TextButton69.BorderColor = BrickColor.new("Really black")
TextButton69.BorderColor3 = Color3.new(0.101961, 0.101961, 0.101961)
TextButton69.ZIndex = 999999999
TextButton69.Font = Enum.Font.SourceSans
TextButton69.FontSize = Enum.FontSize.Size14
TextButton69.Text = "X"
TextButton69.TextColor = BrickColor.new("Institutional white")
TextButton69.TextColor3 = Color3.new(1, 1, 1)
TextButton69.TextSize = 14
LocalScript70.Name = "Close"
LocalScript70.Parent = TextButton69
table.insert(cors,sandbox(LocalScript70,function()
local StarterGui = game:GetService("StarterGui")
local button = script.Parent

button.MouseButton1Down:Connect(function()
	button.Parent:Destroy()
	StarterGui:SetCore("SendNotification", {
		Title = "Advanced BTools",
		Text = "Closed all GUIs and scripts.",
		Duration = 1.5
	})
end)
end))
LocalScript71.Name = "Load"
LocalScript71.Parent = ScreenGui0
table.insert(cors,sandbox(LocalScript71,function()
script.Parent.Main.Position = UDim2.new(0,0,1,100)

local TweenService = game:GetService("TweenService")
local StarterGui = game:GetService("StarterGui")

local goal = {}
goal.Position = UDim2.new(0,0,1,0)

local tweenInfo = TweenInfo.new(0.4, Enum.EasingStyle.Circular)
local tween = TweenService:Create(script.Parent.Main, tweenInfo, goal)

StarterGui:SetCore("SendNotification", {
	Title = "Advanced BTools",
	Text = "GUI Loaded.",
	Duration = 1.5
})
tween:Play()
print("-- LOADED MARBLEMAKERMASTERS ADVANCED BTOOLS --")
script.Parent.Creds.Text = "made by marblemakermaster"
script.success:Play()
end))
Sound72.Name = "success"
Sound72.Parent = LocalScript71
Sound72.SoundId = "rbxassetid://3450794184"
Sound72.Volume = 1.5
for i,v in pairs(mas:GetChildren()) do
	v.Parent = game:GetService("Players").LocalPlayer.PlayerGui
	pcall(function() v:MakeJoints() end)
end
mas:Destroy()
for i,v in pairs(cors) do
	spawn(function()
		pcall(v)
	end)
end
