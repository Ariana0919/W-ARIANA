local Draggable = Instance.new("ScreenGui")
local Draggable_2 = Instance.new("Frame")

--Properties:

Draggable.Name = "Draggable"
Draggable.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

Draggable_2.Name = "Draggable"
Draggable_2.Parent = Draggable
Draggable_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Draggable_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Draggable_2.BorderSizePixel = 0
Draggable_2.Position = UDim2.new(0.271460027, 0, 0.336605877, 0)
Draggable_2.Size = UDim2.new(0, 342, 0, 185)
Draggable_2.Style = Enum.FrameStyle.RobloxRound

-- Scripts:

local function FKDSBLD_fake_script() -- Draggable.Script 
	local script = Instance.new('Script', Draggable)

	frame = script.Parent.DraggableFrame
	frame.Draggable = true
	frame.Selectable = true
end
coroutine.wrap(FKDSBLD_fake_script)()
