-- Load Rayfield from sirius.menu
local Rayfield = loadstring(game:HttpGet("https://sirius.menu/rayfield"))()

-- Create Window
local Window = Rayfield:CreateWindow({
    Name = "3xen0 Private Gui",
    LoadingTitle = "Loading 3xen0 Private Gui...",
    LoadingSubtitle = "by 3xen0kidd",
    ConfigurationSaving = {
        Enabled = true,
        FolderName = "3xen0Config",
        FileName = "Config"
    },
    Discord = {
        Enabled = false,
        Invite = "noinvitelink",
        RememberJoins = true
    },
    KeySystem = true,
    KeySettings = {
        Title = "3xen0 Key System",
        Subtitle = "Key Required",
        Note = "Don't Leak",
        FileName = "3xen0Key",
        SaveKey = true,
        GrabKeyFromSite = false,
        Key = "dontleakbro3xen000lel"
    }
})

-- Set theme colors
Rayfield:SetTheme("Dark")

-- Info Tab
local InfoTab = Window:CreateTab("Info", "info")
local InfoSection = InfoTab:CreateSection("Credits")
InfoTab:CreateLabel("Developer: 3xen0kidd")
InfoTab:CreateLabel("Helper: exotechv")

-- Executors Tab
local ExecutorsTab = Window:CreateTab("Executors", "code")
local ExecutorsSection = ExecutorsTab:CreateSection("Executor Scripts")

ExecutorsTab:CreateButton({
    Name = "Stigma Ultimate",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-stigma-ultimate-29802"))()
    end
})

ExecutorsTab:CreateButton({
    Name = "Elysian",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-elysian-25258"))()
    end
})

ExecutorsTab:CreateButton({
    Name = "Elysian V2",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Elysian-V2-24978"))()
    end
})

ExecutorsTab:CreateButton({
    Name = "Project lua",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Project-Lua-Inspired-by-Project-Ligma-26224"))()
    end
})

ExecutorsTab:CreateButton({
    Name = "Dominator Executor",
    Callback = function()
        local gui = Instance.new("ScreenGui")
        gui.Name = "support mobile"
        gui.Parent = game.CoreGui

        local Frame = Instance.new("Frame")
        Frame.Size = UDim2.new(0.7, 0, 0.9, 69)
        Frame.Position = UDim2.new(0.1, 0, 0.0, 0)
        Frame.BackgroundColor3 = Color3.new(1, 1, 1)
        Frame.BorderColor3 = Color3.new(0, 0, 0)
        Frame.BorderSizePixel = 0
        Frame.Active = true
        Frame.BackgroundTransparency = 0
        Frame.Draggable = true
        Frame.Parent = gui

        local ImageLabel = Instance.new("ImageLabel")
        ImageLabel.Size = UDim2.new(0.9, 53, 0.9, 36)
        ImageLabel.Position = UDim2.new(0.0, 0, 0.0, 0)
        ImageLabel.BackgroundColor3 = Color3.new(0, 0, 0)
        ImageLabel.ImageColor3 = Color3.new(1, 1, 1)
        ImageLabel.Image = "rbxassetid://70496556629822"
        ImageLabel.ImageTransparency = 0
        ImageLabel.Parent = Frame

        ImageLabel.BackgroundTransparency = 1

        local TextBox = Instance.new("TextBox")
        TextBox.Size = UDim2.new(0.7, 29, 0.5, 19)
        TextBox.Position = UDim2.new(0.0, 23, 0.1, 15)
        TextBox.BackgroundColor3 = Color3.new(0, 0, 0)
        TextBox.BorderColor3 = Color3.new(0, 0, 0)
        TextBox.BorderSizePixel = 0
        TextBox.Text = ""
        TextBox.TextColor3 = Color3.new(0, 0, 0)
        TextBox.BackgroundTransparency = 1
        TextBox.Font = Enum.Font.Code
        TextBox.TextSize = 15
        TextBox.Parent = Frame
        TextBox.TextYAlignment = Enum.TextYAlignment.Top
        TextBox.TextXAlignment = Enum.TextXAlignment.Left
        TextBox.ClearTextOnFocus = false
        TextBox.MultiLine = true
        TextBox.TextWrapped = true

        local Output = Instance.new("TextBox")
        Output.Size = UDim2.new(0.5, 31, 0.2, 16)
        Output.Position = UDim2.new(0.2, 19, 0.7, 5)
        Output.BackgroundColor3 = Color3.new(0, 0, 0)
        Output.BorderColor3 = Color3.new(0, 0, 0)
        Output.BorderSizePixel = 0
        Output.Text = "[IDE]: Hello Hackerman, Usename"
        Output.TextColor3 = Color3.new(0, 0, 0)
        Output.BackgroundTransparency = 1
        Output.Font = Enum.Font.Code
        Output.TextSize = 15
        Output.Parent = Frame
        Output.TextYAlignment = Enum.TextYAlignment.Top
        Output.TextXAlignment = Enum.TextXAlignment.Left
        Output.ClearTextOnFocus = false
        Output.MultiLine = true
        Output.TextWrapped = true

        local exe = Instance.new("TextButton")
        exe.Size = UDim2.new(0.2, 4, 0.0, 22)
        exe.Position = UDim2.new(0.0, 8, 0.7, 5)
        exe.BackgroundColor3 = Color3.new(0, 0, 0)
        exe.BorderColor3 = Color3.new(0, 0, 0)
        exe.BorderSizePixel = 0
        exe.Text = ""
        exe.BackgroundTransparency = 1
        exe.TextColor3 = Color3.new(255, 255, 255)
        exe.Font = Enum.Font.Code
        exe.Parent = Frame
        exe.MouseButton1Click:Connect(function()
            assert(loadstring(TextBox.Text))()
        end)

        local clea = Instance.new("TextButton")
        clea.Size = UDim2.new(0.2, 4, 0.0, 22)
        clea.Position = UDim2.new(0.0, 8, 0.8, 0)
        clea.BackgroundColor3 = Color3.new(0, 0, 0)
        clea.BorderColor3 = Color3.new(0, 0, 0)
        clea.BorderSizePixel = 0
        clea.Text = ""
        clea.BackgroundTransparency = 1
        clea.TextColor3 = Color3.new(255, 255, 255)
        clea.Font = Enum.Font.Code
        clea.Parent = Frame
        clea.MouseButton1Click:Connect(function()
            TextBox.Text = ""
        end)

        local Fileide = Instance.new("TextButton")
        Fileide.Size = UDim2.new(0.2, 4, 0.0, 22)
        Fileide.Position = UDim2.new(0.0, 8, 0.8, 28)
        Fileide.BackgroundColor3 = Color3.new(0, 0, 0)
        Fileide.BorderColor3 = Color3.new(0, 0, 0)
        Fileide.BorderSizePixel = 0
        Fileide.Text = ""
        Fileide.BackgroundTransparency = 1
        Fileide.TextColor3 = Color3.new(255, 255, 255)
        Fileide.Font = Enum.Font.Code
        Fileide.Parent = Frame
        Fileide.MouseButton1Click:Connect(function()
            local gui = Instance.new("ScreenGui")
            gui.Name = "file"
            gui.Parent = game.CoreGui

            local file = Instance.new("Frame")
            file.Size = UDim2.new(0.7, 0, 0.9, 59)
            file.Position = UDim2.new(0.2, 0, 0.0, 0)
            file.BackgroundColor3 = Color3.new(1, 1, 1)
            file.BorderColor3 = Color3.new(0, 0, 0)
            file.BorderSizePixel = 0
            file.Active = true
            file.BackgroundTransparency = 1
            file.Draggable = true
            file.Parent = gui

            local file1 = Instance.new("ImageLabel")
            file1.Size = UDim2.new(0.9, 53, 0.9, 35)
            file1.Position = UDim2.new(0.0, 0, 0.0, 0)
            file1.BackgroundColor3 = Color3.new(0, 0, 0)
            file1.ImageColor3 = Color3.new(1, 1, 1)
            file1.Image = "rbxassetid://86799294221744"
            file1.ImageTransparency = 0
            file1.Parent = file

            file1.BackgroundTransparency = 1

            local bir = Instance.new("TextButton")
            bir.Size = UDim2.new(0.8, 0, 0.0, 14)
            bir.Position = UDim2.new(0.1, 49, 0.8, 24)
            bir.BackgroundColor3 = Color3.new(0, 0, 0)
            bir.BorderColor3 = Color3.new(0, 0, 0)
            bir.BorderSizePixel = 0
            bir.Text = ""
            bir.BackgroundTransparency = 1
            bir.TextColor3 = Color3.new(255, 255, 255)
            bir.Font = Enum.Font.Code
            bir.Parent = file
            bir.MouseButton1Click:Connect(function()
                TextBox.Text = "loadstring(game:HttpGet('https://raw.githubusercontent.com/ryand56/Scripts/refs/heads/Scripts/Wings.txt'))()"
                file:Remove()
            end)

            local Xfile = Instance.new("TextButton")
            Xfile.Size = UDim2.new(0.0, 25, 0.0, 25)
            Xfile.Position = UDim2.new(0.9, 28, 0.0, 0)
            Xfile.BackgroundColor3 = Color3.new(0, 0, 0)
            Xfile.BorderColor3 = Color3.new(0, 0, 0)
            Xfile.BorderSizePixel = 0
            Xfile.Text = ""
            Xfile.BackgroundTransparency = 1
            Xfile.TextColor3 = Color3.new(255, 255, 255)
            Xfile.Font = Enum.Font.Code
            Xfile.Parent = file
            Xfile.MouseButton1Click:Connect(function()
                file:Remove()
            end)
        end)

        local X = Instance.new("TextButton")
        X.Size = UDim2.new(0.0, 29, 0.0, 25)
        X.Position = UDim2.new(0.9, 19, 0.0, 0)
        X.BackgroundColor3 = Color3.new(0, 1, 0)
        X.BorderColor3 = Color3.new(0, 0, 0)
        X.BorderSizePixel = 0
        X.Text = ""
        X.BackgroundTransparency = 1
        X.TextColor3 = Color3.new(255, 255, 255)
        X.Font = Enum.Font.Code
        X.Parent = Frame
        X.MouseButton1Click:Connect(function()
            Frame:Remove()
        end)

        local Orbit = Instance.new("ImageLabel")

        local ImageLel = Instance.new("ImageLabel")
        ImageLel.Size = UDim2.new(0.1, 19, 0.3, 0)
        ImageLel.Position = UDim2.new(-0.127000004, 0, 0.407999992, 0)
        ImageLel.BackgroundColor3 = Color3.new(0, 0, 0)
        ImageLel.ImageColor3 = Color3.new(1, 1, 1)
        ImageLel.Image = "rbxassetid://139336001646889"
        ImageLel.ImageTransparency = 0
        ImageLel.Parent = gui

        ImageLel.BackgroundTransparency = 1

        Orbit.Size = UDim2.new(0.1, 39, 0.3, 19)
        Orbit.Position = UDim2.new(-0.127000004, 0, 0.407999992, 0)
        Orbit.BackgroundColor3 = Color3.new(0, 0, 0)
        Orbit.ImageColor3 = Color3.new(1, 1, 1)
        Orbit.Image = "rbxassetid://139019879823094"
        Orbit.ImageTransparency = 0
        Orbit.Parent = gui

        Orbit.BackgroundTransparency = 1

        ImageLel:TweenPosition(UDim2.new(0.458, 0, 0.408, 0), "Out", "Linear", 0.4, false)
        Orbit:TweenPosition(UDim2.new(0.446, 0, 0.379, 0), "Out", "Linear", 0.4, false)
        wait(3)
        Orbit:TweenPosition(UDim2.new(0.00, 0, 0.59,  0), "Out", "Sine", 0.7, false)
        ImageLel:TweenPosition(UDim2.new(0.00, 10, 0.62, 0), "Out", "Sine", 0.7, false)

        while wait() do
            Orbit.Rotation = Orbit.Rotation + 1
        end
    end
})

ExecutorsTab:CreateButton({
    Name = "Project Shiba",
    Callback = function()
        loadstring(game:HttpGet("https://pastebin.com/raw/HrE2dKSD"))()
    end
})

-- Scripts Tab
local ScriptsTab = Window:CreateTab("Scripts", "script")
local ScriptsSection = ScriptsTab:CreateSection("Game Scripts")

ScriptsTab:CreateButton({
    Name = "first T0PK3K 4.0",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Natural-Disaster-Survival-idk-script-t0pk3k-29594"))()
    end
})

ScriptsTab:CreateButton({
    Name = "Second T0PK3K 4.0",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Kick-gui-fake-24452"))()
    end
})

ScriptsTab:CreateButton({
    Name = "c00lkidd Gui (NEW)",
    Callback = function()
        loadstring(game:HttpGet("https://pastebin.com/raw/ucuPtN97"))()
    end
})

ScriptsTab:CreateButton({
    Name = "w00mkidd gui v2",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Client-Replication-w000mgui-v2-reuploaded-before-using-read-description-ty-32055"))()
    end
})

ScriptsTab:CreateButton({
    Name = "Happy hub SS (Lua+might be work)",
    Callback = function()
        str_srce = "93969250423286" 
        loadstring(game:GetObjects("rbxassetid://"..str_srce)[1].Source)()
    end
})

ScriptsTab:CreateButton({
    Name = "Dreambull",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-FE-Bypass-idk-32121"))()
    end
})

ScriptsTab:CreateButton({
    Name = "MLG particles",
    Callback = function()
        loadstring(game:HttpGet("https://pastebin.com/raw/ZPzjyL1M"))()
    end
})

ScriptsTab:CreateButton({
    Name = "Ak47 Fe",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-EPIC-FE-AK47-5040"))()
    end
})

ScriptsTab:CreateButton({
    Name = "Uzi",
    Callback = function()
        local player = game.Players.LocalPlayer
        local character = player.Character
        repeat wait() character = player.Character until character
        local mouse = player:GetMouse()
        
        local tool = Instance.new("Tool",player.Backpack)
        tool.Name = "UZI"
        tool.GripForward = Vector3.new(0, 0, 0)
        tool.GripPos = Vector3.new(0, -0.3, 0)
        tool.GripRight = Vector3.new(0, 0, 0)
        tool.GripUp = Vector3.new(0, 0, 1)
        
        local handle = Instance.new("Part",tool)
        handle.Name = "Handle"
        handle.Size = Vector3.new(0.2, 1.7, 1.4)
        
        local mesh = Instance.new("SpecialMesh",handle)
        mesh.MeshId = "http://www.roblox.com/asset/?id=72012794"
        mesh.Scale = Vector3.new(0.6, 0.6, 0.6)
        mesh.TextureId = "http://www.roblox.com/asset/?id=72012761"
        
        local sound = Instance.new("Sound",handle)
        sound.SoundId = "http://www.roblox.com/asset/?id=27127089"
        sound.Volume = 1
        
        local mouseDown = false
        local equipped = false
        
        function auto()
            while equipped and mouseDown and wait(0.1) do
                local current = sound:Clone()
                current.Parent = handle
                current:Play()
                game.Debris:AddItem(current,1)		
                
                local ray = Ray.new(handle.CFrame.p,(mouse.Hit.p - handle.CFrame.p).unit*900)
                local hit,pos = workspace:FindPartOnRay(ray,character)
                
                local beam = Instance.new("Part", character)
                beam.BrickColor = BrickColor.new("Bright yellow")
                beam.FormFactor = "Custom"
                beam.Material = "Neon"
                beam.Transparency = 0.25
                beam.Anchored = true
                beam.Locked = true
                beam.CanCollide = false
                local distance = (tool.Handle.CFrame.p - pos).magnitude
                beam.Size = Vector3.new(0.1, 0.1, distance)
                beam.CFrame = CFrame.new(tool.Handle.CFrame.p, pos) * CFrame.new(0, 0, -distance / 2)
                game:GetService("Debris"):AddItem(beam, 0.1)
                
                if hit and hit.Parent:FindFirstChild("Humanoid") then
                    hit.Parent.Humanoid:TakeDamage(25)
                end
            end
        end
        
        mouse.Button1Down:connect(function()
            mouseDown = true
            auto()
        end)
        
        mouse.Button1Up:connect(function()
            mouseDown = false
        end)
        
        tool.Equipped:connect(function()
            equipped = true
        end)
        
        tool.Unequipped:connect(function()
            equipped = false
        end)
    end
})

ScriptsTab:CreateButton({
    Name = "Project sonicelijahmania",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Hanif290/YoThereSkibidiSigma68/refs/heads/main/Yoshi681SkibidiBoy"))()
    end
})

ScriptsTab:CreateButton({
    Name = "Exsernew",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/gitluau/luauexser/refs/heads/main/pHzp8uG1PO962o6qucrlP3AJy17eV3B.lua"))()
    end
})

ScriptsTab:CreateButton({
    Name = "Polaria Lua (NEW)",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Polaria-35770"))()
    end
})

-- Jumpscare Scripts
local JumpscaresSection = ScriptsTab:CreateSection("Jumpscares")

ScriptsTab:CreateButton({
    Name = "you are an idiot Jumpscare",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-You-are-a-idiot-Jumpscare-28005"))()
    end
})

ScriptsTab:CreateButton({
    Name = "Obunga jumpscare",
    Callback = function()
        loadstring(game:HttpGet('https://pastebin.com/raw/nLJkW0s1'))()
    end
})

ScriptsTab:CreateButton({
    Name = "Tubers93 jumpscare 1",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Meepcity-4-tubers93-Jumpscare-24949"))()
    end
})

ScriptsTab:CreateButton({
    Name = "Tubers93 jumpscare 2",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Tubers93-jumpscare-31279"))()
    end
})

ScriptsTab:CreateButton({
    Name = "Jeff the killer",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Jeff-The-Killer-JumpScare-27384"))()
    end
})

ScriptsTab:CreateButton({
    Name = "Ezkidd Jumpscare",
    Callback = function()
        loadstring(game:HttpGet("https://rawscripts.net/raw/GAME-Jumpscare-24948"))()
    end
})

-- Other Scripts
local OtherSection = ScriptsTab:CreateSection("Other Scripts")

ScriptsTab:CreateButton({
    Name = "Rc7 require",
    Callback = function()
        loadstring(game:HttpGet('https://pastebin.com/raw/CVecVrT1'))()
    end
})

ScriptsTab:CreateButton({
    Name = "Mario Exe",
    Callback = function()
        loadstring(game:HttpGet("https://pastebin.com/raw/Ljz3fwU2"))()
    end
})

ScriptsTab:CreateButton({
    Name = "Rc7 cloud",
    Callback = function()
        local Player = game.Players.LocalPlayer
        local cloud = Instance.new("Part",Player.Character.Torso)
        cloud.BrickColor = BrickColor.new(333)
        cloud.Reflectance = 0.5
        cloud.Anchored = true
        cloud.CanCollide = false
        cloud.FormFactor = Enum.FormFactor.Symmetric
        cloud.Size = Vector3.new(1,1,1)

        local mesh = Instance.new("SpecialMesh",cloud)
        mesh.MeshType = Enum.MeshType.FileMesh
        mesh.MeshId = "rbxassetid://111820358"
        mesh.Scale = Vector3.new(8,8,8)

        local P = Instance.new("ParticleEmitter",cloud)
        P.Size = NumberSequence.new(0.75)
        P.LockedToPart = true
        P.Texture = "rbxassetid://331959655"
        P.Transparency = NumberSequence.new(0.5)
        P.Acceleration = Vector3.new(0, -20, 0)
        P.EmissionDirection = Enum.NormalId.Bottom
        P.Enabled = true
        P.Rate = 30
        P.Rotation = NumberRange.new(0,360)
        P.RotSpeed = NumberRange.new(0,15)
        P.Speed = NumberRange.new(3,5)
        P.VelocitySpread = 80

        while wait() do
            cloud.CFrame = CFrame.new() + Vector3.new(Player.Character.Torso.CFrame.x,Player.Character.Torso.CFrame.y,Player.Character.Torso.CFrame.z) + Vector3.new(0,20,0)
        end
    end
})

-- Initial notification
Rayfield:Notify({
    Title = "3xen0 Gui Loaded",
    Content = "Welcome to 3xen0 Private Gui!",
    Duration = 6.5,
    Image = 4483362458,
    Actions = {
        Ignore = {
            Name = "Okay",
            Callback = function()
                print("User acknowledged notification")
            end
        }
    }
})
