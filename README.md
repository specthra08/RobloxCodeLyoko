--created by specthra

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local NameTextLabel = Instance.new("TextLabel")
local Frame_2 = Instance.new("Frame")
local Carthagesector = Instance.new("TextButton")
local Desertsector = Instance.new("TextButton")
local Forestsector = Instance.new("TextButton")
local Icesector = Instance.new("TextButton")
local Mountainsector = Instance.new("TextButton")
local cityButton = Instance.new("TextButton")
local byspecthraTextLabel = Instance.new("TextLabel")
local CityMenu = Instance.new("Frame")
local TPscannerButton = Instance.new("TextButton")
local TPsupercomputerButton = Instance.new("TextButton")
local TPCanteenButton = Instance.new("TextButton")
local TPyumihouseButton = Instance.new("TextButton")
local TPHistoryclassButton = Instance.new("TextButton")
local TPmathclassButton = Instance.new("TextButton")
local TPreadingclassButton = Instance.new("TextButton")
local TPscienceclassButton = Instance.new("TextButton")
local TPJeremyroomButton = Instance.new("TextButton")
local TPUlrichOddroomButton = Instance.new("TextButton")
local TPwilliamroomButton = Instance.new("TextButton")
local TPAelitaroomButton = Instance.new("TextButton")
local TextLabel_2 = Instance.new("TextLabel")
local TPlaboButton = Instance.new("TextButton")
local TPElizabethroomButton = Instance.new("TextButton")
local TPMillyTamiaroomButton = Instance.new("TextButton")
local TPJimroomButton = Instance.new("TextButton")
local ForestSectorMenu = Instance.new("Frame")
local TPForestTower1Button = Instance.new("TextButton")
local TPForestTower2Button = Instance.new("TextButton")
local TPForestTower3Button = Instance.new("TextButton")
local TPForestTower4Button = Instance.new("TextButton")
local TPForestTower5Button = Instance.new("TextButton")
local TPForestTower6Button = Instance.new("TextButton")
local TPForestTower7Button = Instance.new("TextButton")
local TPForestTower8Button = Instance.new("TextButton")
local TPForestTower9Button = Instance.new("TextButton")
local TPForestTower10Button = Instance.new("TextButton")
local TextLabel_3 = Instance.new("TextLabel")
local DesertSectorMenu = Instance.new("Frame")
local TPDesertTower1Button = Instance.new("TextButton")
local TPDesertTower2Button = Instance.new("TextButton")
local TPDesertTower3Button = Instance.new("TextButton")
local TPDesertTower4Button = Instance.new("TextButton")
local TPDesertTower5Button = Instance.new("TextButton")
local TPDesertTower6Button = Instance.new("TextButton")
local TPDesertTower7Button = Instance.new("TextButton")
local TPDesertTower8Button = Instance.new("TextButton")
local TPDesertTower9Button = Instance.new("TextButton")
local TPDesertTower10Button = Instance.new("TextButton")
local TextLabel_4 = Instance.new("TextLabel")
local CarthageSectorMenu = Instance.new("Frame")
local TPCarthageTower1Button = Instance.new("TextButton")
local TPCarthageSkidButton = Instance.new("TextButton")
local TPCarthageHeartButton = Instance.new("TextButton")
local TPCarthageMemoryButton = Instance.new("TextButton")
local TextLabel_5 = Instance.new("TextLabel")
local TPCarthageArenaButton = Instance.new("TextButton")
local MountainSectorMenu = Instance.new("Frame")
local TPMountainTower1Button = Instance.new("TextButton")
local TPMountainTower2Button = Instance.new("TextButton")
local TPMountainTower3Button = Instance.new("TextButton")
local TPMountainTower4Button = Instance.new("TextButton")
local TPMountainTower5Button = Instance.new("TextButton")
local TPMountainTower6Button = Instance.new("TextButton")
local TPMountainTower7Button = Instance.new("TextButton")
local TPMountainTower8Button = Instance.new("TextButton")
local TPMountainTower9Button = Instance.new("TextButton")
local TPMountainTower10Button = Instance.new("TextButton")
local TextLabel_6 = Instance.new("TextLabel")
local IceSectorMenu = Instance.new("Frame")
local TPIceTower1Button = Instance.new("TextButton")
local TPIceTower2Button = Instance.new("TextButton")
local TPIceTower3Button = Instance.new("TextButton")
local TPIceTower4Button = Instance.new("TextButton")
local TPIceTower5Button = Instance.new("TextButton")
local TPIceTower6Button = Instance.new("TextButton")
local TPIceTower7Button = Instance.new("TextButton")
local TPIceTower8Button = Instance.new("TextButton")
local TPIceTower9Button = Instance.new("TextButton")
local TPIceTower10Button = Instance.new("TextButton")
local TextLabel_7 = Instance.new("TextLabel")
local CloseButton = Instance.new("TextButton")
local TextButton = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(79, 79, 79)
Frame.Position = UDim2.new(0.283875853, 0, 0.364719808, 0)
Frame.Size = UDim2.new(0, 753, 0, 355)
Frame.Visible = false
Frame.Active = true
Frame.Draggable = true

IceSectorMenu.Draggable = true
ForestSectorMenu.Draggable = true
DesertSectorMenu.Draggable = true
CityMenu.Draggable = true
MountainSectorMenu.Draggable = true
CarthageSectorMenu.Draggable = true

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
TextLabel.Size = UDim2.new(0, 753, 0, 35)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = ""
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 14.000

NameTextLabel.Name = "NameTextLabel"
NameTextLabel.Parent = TextLabel
NameTextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
NameTextLabel.Position = UDim2.new(0.013663061, 0, 0.00787362456, 0)
NameTextLabel.Size = UDim2.new(0, 153, 0, 32)
NameTextLabel.Font = Enum.Font.SourceSans
NameTextLabel.Text = "Teleport Menu"
NameTextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
NameTextLabel.TextSize = 25.000

Frame_2.Parent = TextLabel
Frame_2.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
Frame_2.Position = UDim2.new(0, 0, 1, 0)
Frame_2.Size = UDim2.new(0, 174, 0, 320)

Carthagesector.Name = "Carthage sector"
Carthagesector.Parent = Frame
Carthagesector.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Carthagesector.Position = UDim2.new(0.0137650324, 0, 0.781971931, 0)
Carthagesector.Size = UDim2.new(0, 153, 0, 32)
Carthagesector.Font = Enum.Font.SourceSans
Carthagesector.Text = "Carthge sector"
Carthagesector.TextColor3 = Color3.fromRGB(0, 0, 0)
Carthagesector.TextSize = 25.000

Desertsector.Name = "Desert sector"
Desertsector.Parent = Frame
Desertsector.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Desertsector.Position = UDim2.new(0.0143644754, 0, 0.51925981, 0)
Desertsector.Size = UDim2.new(0, 153, 0, 32)
Desertsector.Font = Enum.Font.SourceSans
Desertsector.Text = "Desert sector"
Desertsector.TextColor3 = Color3.fromRGB(0, 0, 0)
Desertsector.TextSize = 25.000

Forestsector.Name = "Forest sector"
Forestsector.Parent = Frame
Forestsector.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Forestsector.Position = UDim2.new(0.0149704814, 0, 0.381210804, 0)
Forestsector.Size = UDim2.new(0, 153, 0, 32)
Forestsector.Font = Enum.Font.SourceSans
Forestsector.Text = "Forest sector"
Forestsector.TextColor3 = Color3.fromRGB(0, 0, 0)
Forestsector.TextSize = 25.000

Icesector.Name = "Ice sector"
Icesector.Parent = Frame
Icesector.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Icesector.Position = UDim2.new(0.0149819199, 0, 0.256702125, 0)
Icesector.Size = UDim2.new(0, 153, 0, 32)
Icesector.Font = Enum.Font.SourceSans
Icesector.Text = "Ice sector"
Icesector.TextColor3 = Color3.fromRGB(0, 0, 0)
Icesector.TextSize = 25.000

Mountainsector.Name = "Mountain sector"
Mountainsector.Parent = Frame
Mountainsector.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Mountainsector.Position = UDim2.new(0.0130361915, 0, 0.649855614, 0)
Mountainsector.Size = UDim2.new(0, 153, 0, 32)
Mountainsector.Font = Enum.Font.SourceSans
Mountainsector.Text = "Mountain sector"
Mountainsector.TextColor3 = Color3.fromRGB(0, 0, 0)
Mountainsector.TextSize = 25.000

cityButton.Name = "cityButton"
cityButton.Parent = Frame
cityButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
cityButton.Position = UDim2.new(0.0133286677, 0, 0.137898907, 0)
cityButton.Size = UDim2.new(0, 153, 0, 32)
cityButton.Font = Enum.Font.SourceSans
cityButton.Text = "City"
cityButton.TextColor3 = Color3.fromRGB(0, 0, 0)
cityButton.TextSize = 25.000

byspecthraTextLabel.Name = "byspecthraTextLabel"
byspecthraTextLabel.Parent = Frame
byspecthraTextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
byspecthraTextLabel.Position = UDim2.new(0.013663061, 0, 0.903936863, 0)
byspecthraTextLabel.Size = UDim2.new(0, 153, 0, 32)
byspecthraTextLabel.Font = Enum.Font.SourceSans
byspecthraTextLabel.Text = "By specthra"
byspecthraTextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
byspecthraTextLabel.TextSize = 25.000

CityMenu.Name = "CityMenu"
CityMenu.Parent = Frame
CityMenu.BackgroundColor3 = Color3.fromRGB(79, 79, 79)
CityMenu.Position = UDim2.new(0.231075704, 0, 0.104477577, 0)
CityMenu.Size = UDim2.new(0, 578, 0, 317)
CityMenu.Visible = false

TPscannerButton.Name = "TPscannerButton"
TPscannerButton.Parent = CityMenu
TPscannerButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPscannerButton.Position = UDim2.new(0.0272031091, 0, 0.186937109, 0)
TPscannerButton.Size = UDim2.new(0, 167, 0, 40)
TPscannerButton.Font = Enum.Font.SourceSans
TPscannerButton.Text = "TP to scanner"
TPscannerButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPscannerButton.TextSize = 22.000

TPsupercomputerButton.Name = "TPsupercomputerButton"
TPsupercomputerButton.Parent = CityMenu
TPsupercomputerButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPsupercomputerButton.Position = UDim2.new(0.0269410666, 0, 0.358810693, 0)
TPsupercomputerButton.Size = UDim2.new(0, 167, 0, 40)
TPsupercomputerButton.Font = Enum.Font.SourceSans
TPsupercomputerButton.Text = "TP to supercomputer"
TPsupercomputerButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPsupercomputerButton.TextSize = 22.000

TPCanteenButton.Name = "TPCanteenButton"
TPCanteenButton.Parent = CityMenu
TPCanteenButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPCanteenButton.Position = UDim2.new(0.0279415939, 0, 0.524876535, 0)
TPCanteenButton.Size = UDim2.new(0, 167, 0, 40)
TPCanteenButton.Font = Enum.Font.SourceSans
TPCanteenButton.Text = "TP to Canteen"
TPCanteenButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPCanteenButton.TextSize = 22.000

TPyumihouseButton.Name = "TPyumihouseButton"
TPyumihouseButton.Parent = CityMenu
TPyumihouseButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPyumihouseButton.Position = UDim2.new(0.340160459, 0, 0.357221842, 0)
TPyumihouseButton.Size = UDim2.new(0, 167, 0, 40)
TPyumihouseButton.Font = Enum.Font.SourceSans
TPyumihouseButton.Text = "TP to Yumi's house"
TPyumihouseButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPyumihouseButton.TextSize = 22.000

TPHistoryclassButton.Name = "TPHistoryclassButton"
TPHistoryclassButton.Parent = CityMenu
TPHistoryclassButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPHistoryclassButton.Position = UDim2.new(0.0258861165, 0, 0.689772189, 0)
TPHistoryclassButton.Size = UDim2.new(0, 167, 0, 40)
TPHistoryclassButton.Font = Enum.Font.SourceSans
TPHistoryclassButton.Text = "TP to history class"
TPHistoryclassButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPHistoryclassButton.TextSize = 22.000

TPmathclassButton.Name = "TPmathclassButton"
TPmathclassButton.Parent = CityMenu
TPmathclassButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPmathclassButton.Position = UDim2.new(0.0257592201, 0, 0.8589257, 0)
TPmathclassButton.Size = UDim2.new(0, 167, 0, 40)
TPmathclassButton.Font = Enum.Font.SourceSans
TPmathclassButton.Text = "TP to math class"
TPmathclassButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPmathclassButton.TextSize = 22.000

TPreadingclassButton.Name = "TPreadingclassButton"
TPreadingclassButton.Parent = CityMenu
TPreadingclassButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPreadingclassButton.Position = UDim2.new(0.340207636, 0, 0.0203075428, 0)
TPreadingclassButton.Size = UDim2.new(0, 167, 0, 40)
TPreadingclassButton.Font = Enum.Font.SourceSans
TPreadingclassButton.Text = "TP to reading class"
TPreadingclassButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPreadingclassButton.TextSize = 22.000

TPscienceclassButton.Name = "TPscienceclassButton"
TPscienceclassButton.Parent = CityMenu
TPscienceclassButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPscienceclassButton.Position = UDim2.new(0.339760602, 0, 0.187073901, 0)
TPscienceclassButton.Size = UDim2.new(0, 167, 0, 40)
TPscienceclassButton.Font = Enum.Font.SourceSans
TPscienceclassButton.Text = "TP to science class"
TPscienceclassButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPscienceclassButton.TextSize = 22.000

TPJeremyroomButton.Name = "TPJeremyroomButton"
TPJeremyroomButton.Parent = CityMenu
TPJeremyroomButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPJeremyroomButton.Position = UDim2.new(0.337321103, 0, 0.523194969, 0)
TPJeremyroomButton.Size = UDim2.new(0, 167, 0, 40)
TPJeremyroomButton.Font = Enum.Font.SourceSans
TPJeremyroomButton.Text = "TP to Jeremy's room"
TPJeremyroomButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPJeremyroomButton.TextSize = 22.000
TPJeremyroomButton.TextWrapped = true

TPUlrichOddroomButton.Name = "TPUlrichOddroomButton"
TPUlrichOddroomButton.Parent = CityMenu
TPUlrichOddroomButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPUlrichOddroomButton.Position = UDim2.new(0.336476773, 0, 0.688064516, 0)
TPUlrichOddroomButton.Size = UDim2.new(0, 167, 0, 40)
TPUlrichOddroomButton.Font = Enum.Font.SourceSans
TPUlrichOddroomButton.Text = "TP to Urich/Odd room"
TPUlrichOddroomButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPUlrichOddroomButton.TextSize = 22.000
TPUlrichOddroomButton.TextWrapped = true

TPwilliamroomButton.Name = "TPwilliamroomButton"
TPwilliamroomButton.Parent = CityMenu
TPwilliamroomButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPwilliamroomButton.Position = UDim2.new(0.335193694, 0, 0.857014775, 0)
TPwilliamroomButton.Size = UDim2.new(0, 167, 0, 40)
TPwilliamroomButton.Font = Enum.Font.SourceSans
TPwilliamroomButton.Text = "TP to William's room"
TPwilliamroomButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPwilliamroomButton.TextSize = 22.000
TPwilliamroomButton.TextWrapped = true

TPAelitaroomButton.Name = "TPAelitaroomButton"
TPAelitaroomButton.Parent = CityMenu
TPAelitaroomButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPAelitaroomButton.Position = UDim2.new(0.663466334, 0, 0.0192947406, 0)
TPAelitaroomButton.Size = UDim2.new(0, 167, 0, 40)
TPAelitaroomButton.Font = Enum.Font.SourceSans
TPAelitaroomButton.Text = "TP to Aelita room"
TPAelitaroomButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPAelitaroomButton.TextSize = 22.000

TextLabel_2.Parent = CityMenu
TextLabel_2.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
TextLabel_2.Position = UDim2.new(0, 0, -0.117001697, 0)
TextLabel_2.Size = UDim2.new(0, 578, 0, 37)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "City Menu"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextSize = 30.000

TPlaboButton.Name = "TPlaboButton"
TPlaboButton.Parent = CityMenu
TPlaboButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPlaboButton.Position = UDim2.new(0.0272031091, 0, 0.0323629826, 0)
TPlaboButton.Size = UDim2.new(0, 167, 0, 40)
TPlaboButton.Font = Enum.Font.SourceSans
TPlaboButton.Text = "TP to labo"
TPlaboButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPlaboButton.TextSize = 22.000

TPElizabethroomButton.Name = "TPElizabethroomButton"
TPElizabethroomButton.Parent = CityMenu
TPElizabethroomButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPElizabethroomButton.Position = UDim2.new(0.663466334, 0, 0.186487168, 0)
TPElizabethroomButton.Size = UDim2.new(0, 167, 0, 40)
TPElizabethroomButton.Font = Enum.Font.SourceSans
TPElizabethroomButton.Text = "TP to Elizabeth room"
TPElizabethroomButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPElizabethroomButton.TextSize = 22.000

TPMillyTamiaroomButton.Name = "TPMillyTamiaroomButton"
TPMillyTamiaroomButton.Parent = CityMenu
TPMillyTamiaroomButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPMillyTamiaroomButton.Position = UDim2.new(0.663466334, 0, 0.356834173, 0)
TPMillyTamiaroomButton.Size = UDim2.new(0, 167, 0, 40)
TPMillyTamiaroomButton.Font = Enum.Font.SourceSans
TPMillyTamiaroomButton.Text = "TP to Milly/Tamia room"
TPMillyTamiaroomButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPMillyTamiaroomButton.TextSize = 22.000

TPJimroomButton.Name = "TPJimroomButton"
TPJimroomButton.Parent = CityMenu
TPJimroomButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPJimroomButton.Position = UDim2.new(0.663466334, 0, 0.524026632, 0)
TPJimroomButton.Size = UDim2.new(0, 167, 0, 40)
TPJimroomButton.Font = Enum.Font.SourceSans
TPJimroomButton.Text = "TP to Jim room"
TPJimroomButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPJimroomButton.TextSize = 22.000

ForestSectorMenu.Name = "ForestSectorMenu"
ForestSectorMenu.Parent = Frame
ForestSectorMenu.BackgroundColor3 = Color3.fromRGB(79, 79, 79)
ForestSectorMenu.Position = UDim2.new(0.231075704, 0, 0.0978730544, 0)
ForestSectorMenu.Size = UDim2.new(0, 578, 0, 320)
ForestSectorMenu.Visible = false

TPForestTower1Button.Name = "TPForestTower1Button"
TPForestTower1Button.Parent = ForestSectorMenu
TPForestTower1Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPForestTower1Button.Position = UDim2.new(0.0299999993, 0, 0.0529999994, 0)
TPForestTower1Button.Size = UDim2.new(0, 167, 0, 40)
TPForestTower1Button.Font = Enum.Font.SourceSans
TPForestTower1Button.Text = "TP to Tower 1"
TPForestTower1Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPForestTower1Button.TextSize = 22.000

TPForestTower2Button.Name = "TPForestTower2Button"
TPForestTower2Button.Parent = ForestSectorMenu
TPForestTower2Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPForestTower2Button.Position = UDim2.new(0.0289999992, 0, 0.229000002, 0)
TPForestTower2Button.Size = UDim2.new(0, 167, 0, 40)
TPForestTower2Button.Font = Enum.Font.SourceSans
TPForestTower2Button.Text = "TP to Tower 2"
TPForestTower2Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPForestTower2Button.TextSize = 22.000

TPForestTower3Button.Name = "TPForestTower3Button"
TPForestTower3Button.Parent = ForestSectorMenu
TPForestTower3Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPForestTower3Button.Position = UDim2.new(0.0280000009, 0, 0.412999988, 0)
TPForestTower3Button.Size = UDim2.new(0, 167, 0, 40)
TPForestTower3Button.Font = Enum.Font.SourceSans
TPForestTower3Button.Text = "TP to Tower 3"
TPForestTower3Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPForestTower3Button.TextSize = 22.000

TPForestTower4Button.Name = "TPForestTower4Button"
TPForestTower4Button.Parent = ForestSectorMenu
TPForestTower4Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPForestTower4Button.Position = UDim2.new(0.0280000009, 0, 0.595000029, 0)
TPForestTower4Button.Size = UDim2.new(0, 167, 0, 40)
TPForestTower4Button.Font = Enum.Font.SourceSans
TPForestTower4Button.Text = "TP to Tower 4"
TPForestTower4Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPForestTower4Button.TextSize = 22.000

TPForestTower5Button.Name = "TPForestTower5Button"
TPForestTower5Button.Parent = ForestSectorMenu
TPForestTower5Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPForestTower5Button.Position = UDim2.new(0, 16, 0, 246)
TPForestTower5Button.Size = UDim2.new(0, 167, 0, 40)
TPForestTower5Button.Font = Enum.Font.SourceSans
TPForestTower5Button.Text = "TP to Tower 5"
TPForestTower5Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPForestTower5Button.TextSize = 22.000

TPForestTower6Button.Name = "TPForestTower6Button"
TPForestTower6Button.Parent = ForestSectorMenu
TPForestTower6Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPForestTower6Button.Position = UDim2.new(0.356000006, 0, 0.0520000011, 0)
TPForestTower6Button.Size = UDim2.new(0, 167, 0, 40)
TPForestTower6Button.Font = Enum.Font.SourceSans
TPForestTower6Button.Text = "TP to Tower 6"
TPForestTower6Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPForestTower6Button.TextSize = 22.000

TPForestTower7Button.Name = "TPForestTower7Button"
TPForestTower7Button.Parent = ForestSectorMenu
TPForestTower7Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPForestTower7Button.Position = UDim2.new(0, 205, 0, 73)
TPForestTower7Button.Size = UDim2.new(0, 167, 0, 40)
TPForestTower7Button.Font = Enum.Font.SourceSans
TPForestTower7Button.Text = "TP to Tower 7"
TPForestTower7Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPForestTower7Button.TextSize = 22.000

TPForestTower8Button.Name = "TPForestTower8Button"
TPForestTower8Button.Parent = ForestSectorMenu
TPForestTower8Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPForestTower8Button.Position = UDim2.new(0.352999985, 0, 0.411000013, 0)
TPForestTower8Button.Size = UDim2.new(0, 167, 0, 40)
TPForestTower8Button.Font = Enum.Font.SourceSans
TPForestTower8Button.Text = "TP to Tower 8"
TPForestTower8Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPForestTower8Button.TextSize = 22.000

TPForestTower9Button.Name = "TPForestTower9Button"
TPForestTower9Button.Parent = ForestSectorMenu
TPForestTower9Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPForestTower9Button.Position = UDim2.new(0.352999985, 0, 0.593999982, 0)
TPForestTower9Button.Size = UDim2.new(0, 167, 0, 40)
TPForestTower9Button.Font = Enum.Font.SourceSans
TPForestTower9Button.Text = "TP to Tower 9"
TPForestTower9Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPForestTower9Button.TextSize = 22.000

TPForestTower10Button.Name = "TPForestTower10Button"
TPForestTower10Button.Parent = ForestSectorMenu
TPForestTower10Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPForestTower10Button.Position = UDim2.new(0.356000006, 0, 0.771000028, 0)
TPForestTower10Button.Size = UDim2.new(0, 167, 0, 40)
TPForestTower10Button.Font = Enum.Font.SourceSans
TPForestTower10Button.Text = "TP to Tower 10"
TPForestTower10Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPForestTower10Button.TextSize = 22.000

TextLabel_3.Parent = ForestSectorMenu
TextLabel_3.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
TextLabel_3.Position = UDim2.new(0, 0, -0.117001697, 0)
TextLabel_3.Size = UDim2.new(0, 578, 0, 37)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "Forest Menu"
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.TextSize = 30.000

DesertSectorMenu.Name = "DesertSectorMenu"
DesertSectorMenu.Parent = Frame
DesertSectorMenu.BackgroundColor3 = Color3.fromRGB(79, 79, 79)
DesertSectorMenu.Position = UDim2.new(0.231075704, 0, 0.0982021242, 0)
DesertSectorMenu.Size = UDim2.new(0, 578, 0, 320)
DesertSectorMenu.Visible = false

TPDesertTower1Button.Name = "TPDesertTower1Button"
TPDesertTower1Button.Parent = DesertSectorMenu
TPDesertTower1Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPDesertTower1Button.Position = UDim2.new(0.0299999993, 0, 0.0529999994, 0)
TPDesertTower1Button.Size = UDim2.new(0, 167, 0, 40)
TPDesertTower1Button.Font = Enum.Font.SourceSans
TPDesertTower1Button.Text = "TP to Tower 1"
TPDesertTower1Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPDesertTower1Button.TextSize = 22.000

TPDesertTower2Button.Name = "TPDesertTower2Button"
TPDesertTower2Button.Parent = DesertSectorMenu
TPDesertTower2Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPDesertTower2Button.Position = UDim2.new(0.0289999992, 0, 0.229000002, 0)
TPDesertTower2Button.Size = UDim2.new(0, 167, 0, 40)
TPDesertTower2Button.Font = Enum.Font.SourceSans
TPDesertTower2Button.Text = "TP to Tower 2"
TPDesertTower2Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPDesertTower2Button.TextSize = 22.000

TPDesertTower3Button.Name = "TPDesertTower3Button"
TPDesertTower3Button.Parent = DesertSectorMenu
TPDesertTower3Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPDesertTower3Button.Position = UDim2.new(0.0280000009, 0, 0.412999988, 0)
TPDesertTower3Button.Size = UDim2.new(0, 167, 0, 40)
TPDesertTower3Button.Font = Enum.Font.SourceSans
TPDesertTower3Button.Text = "TP to Tower 3"
TPDesertTower3Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPDesertTower3Button.TextSize = 22.000

TPDesertTower4Button.Name = "TPDesertTower4Button"
TPDesertTower4Button.Parent = DesertSectorMenu
TPDesertTower4Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPDesertTower4Button.Position = UDim2.new(0.0280000009, 0, 0.595000029, 0)
TPDesertTower4Button.Size = UDim2.new(0, 167, 0, 40)
TPDesertTower4Button.Font = Enum.Font.SourceSans
TPDesertTower4Button.Text = "TP to Tower 4"
TPDesertTower4Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPDesertTower4Button.TextSize = 22.000

TPDesertTower5Button.Name = "TPDesertTower5Button"
TPDesertTower5Button.Parent = DesertSectorMenu
TPDesertTower5Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPDesertTower5Button.Position = UDim2.new(0.0299999993, 0, 0.773000002, 0)
TPDesertTower5Button.Size = UDim2.new(0, 167, 0, 40)
TPDesertTower5Button.Font = Enum.Font.SourceSans
TPDesertTower5Button.Text = "TP to Tower 5"
TPDesertTower5Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPDesertTower5Button.TextSize = 22.000

TPDesertTower6Button.Name = "TPDesertTower6Button"
TPDesertTower6Button.Parent = DesertSectorMenu
TPDesertTower6Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPDesertTower6Button.Position = UDim2.new(0.356000006, 0, 0.0520000011, 0)
TPDesertTower6Button.Size = UDim2.new(0, 167, 0, 40)
TPDesertTower6Button.Font = Enum.Font.SourceSans
TPDesertTower6Button.Text = "TP to Tower 6"
TPDesertTower6Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPDesertTower6Button.TextSize = 22.000

TPDesertTower7Button.Name = "TPDesertTower7Button"
TPDesertTower7Button.Parent = DesertSectorMenu
TPDesertTower7Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPDesertTower7Button.Position = UDim2.new(0, 205, 0, 73)
TPDesertTower7Button.Size = UDim2.new(0, 167, 0, 40)
TPDesertTower7Button.Font = Enum.Font.SourceSans
TPDesertTower7Button.Text = "TP to Tower 7"
TPDesertTower7Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPDesertTower7Button.TextSize = 22.000

TPDesertTower8Button.Name = "TPDesertTower8Button"
TPDesertTower8Button.Parent = DesertSectorMenu
TPDesertTower8Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPDesertTower8Button.Position = UDim2.new(0.352999985, 0, 0.411000013, 0)
TPDesertTower8Button.Size = UDim2.new(0, 167, 0, 40)
TPDesertTower8Button.Font = Enum.Font.SourceSans
TPDesertTower8Button.Text = "TP to Tower 8"
TPDesertTower8Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPDesertTower8Button.TextSize = 22.000

TPDesertTower9Button.Name = "TPDesertTower9Button"
TPDesertTower9Button.Parent = DesertSectorMenu
TPDesertTower9Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPDesertTower9Button.Position = UDim2.new(0.352999985, 0, 0.593999982, 0)
TPDesertTower9Button.Size = UDim2.new(0, 167, 0, 40)
TPDesertTower9Button.Font = Enum.Font.SourceSans
TPDesertTower9Button.Text = "TP to Tower 9"
TPDesertTower9Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPDesertTower9Button.TextSize = 22.000

TPDesertTower10Button.Name = "TPDesertTower10Button"
TPDesertTower10Button.Parent = DesertSectorMenu
TPDesertTower10Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPDesertTower10Button.Position = UDim2.new(0.356000006, 0, 0.771000028, 0)
TPDesertTower10Button.Size = UDim2.new(0, 167, 0, 40)
TPDesertTower10Button.Font = Enum.Font.SourceSans
TPDesertTower10Button.Text = "TP to Tower 10"
TPDesertTower10Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPDesertTower10Button.TextSize = 22.000

TextLabel_4.Parent = DesertSectorMenu
TextLabel_4.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
TextLabel_4.Position = UDim2.new(0, 0, -0.117001697, 0)
TextLabel_4.Size = UDim2.new(0, 578, 0, 37)
TextLabel_4.Font = Enum.Font.SourceSans
TextLabel_4.Text = "Desert Menu"
TextLabel_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.TextSize = 30.000

CarthageSectorMenu.Name = "CarthageSectorMenu"
CarthageSectorMenu.Parent = Frame
CarthageSectorMenu.BackgroundColor3 = Color3.fromRGB(79, 79, 79)
CarthageSectorMenu.Position = UDim2.new(0.231075704, 0, 0.0976514369, 0)
CarthageSectorMenu.Size = UDim2.new(0, 578, 0, 320)
CarthageSectorMenu.Visible = false

TPCarthageTower1Button.Name = "TPCarthageTower1Button"
TPCarthageTower1Button.Parent = CarthageSectorMenu
TPCarthageTower1Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPCarthageTower1Button.Position = UDim2.new(0.0299999993, 0, 0.0529999994, 0)
TPCarthageTower1Button.Size = UDim2.new(0, 167, 0, 40)
TPCarthageTower1Button.Font = Enum.Font.SourceSans
TPCarthageTower1Button.Text = "TP to Tower 1"
TPCarthageTower1Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPCarthageTower1Button.TextSize = 22.000

TPCarthageSkidButton.Name = "TPCarthageSkidButton"
TPCarthageSkidButton.Parent = CarthageSectorMenu
TPCarthageSkidButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPCarthageSkidButton.Position = UDim2.new(0.0280000009, 0, 0.595000029, 0)
TPCarthageSkidButton.Size = UDim2.new(0, 167, 0, 40)
TPCarthageSkidButton.Font = Enum.Font.SourceSans
TPCarthageSkidButton.Text = "TP to skid room"
TPCarthageSkidButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPCarthageSkidButton.TextSize = 22.000

TPCarthageHeartButton.Name = "TPCarthageHeartButton"
TPCarthageHeartButton.Parent = CarthageSectorMenu
TPCarthageHeartButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPCarthageHeartButton.Position = UDim2.new(0.0289999992, 0, 0.229000002, 0)
TPCarthageHeartButton.Size = UDim2.new(0, 167, 0, 40)
TPCarthageHeartButton.Font = Enum.Font.SourceSans
TPCarthageHeartButton.Text = "TP to heart room"
TPCarthageHeartButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPCarthageHeartButton.TextSize = 22.000

TPCarthageMemoryButton.Name = "TPCarthageMemoryButton"
TPCarthageMemoryButton.Parent = CarthageSectorMenu
TPCarthageMemoryButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPCarthageMemoryButton.Position = UDim2.new(0.0280000009, 0, 0.412999988, 0)
TPCarthageMemoryButton.Size = UDim2.new(0, 167, 0, 40)
TPCarthageMemoryButton.Font = Enum.Font.SourceSans
TPCarthageMemoryButton.Text = "TP to the memory room"
TPCarthageMemoryButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPCarthageMemoryButton.TextSize = 22.000
TPCarthageMemoryButton.TextWrapped = true

TextLabel_5.Parent = CarthageSectorMenu
TextLabel_5.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
TextLabel_5.Position = UDim2.new(0, 0, -0.117001697, 0)
TextLabel_5.Size = UDim2.new(0, 578, 0, 37)
TextLabel_5.Font = Enum.Font.SourceSans
TextLabel_5.Text = "Carthage Menu"
TextLabel_5.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_5.TextSize = 30.000

TPCarthageArenaButton.Name = "TPCarthageArenaButton"
TPCarthageArenaButton.Parent = CarthageSectorMenu
TPCarthageArenaButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPCarthageArenaButton.Position = UDim2.new(0.0280000009, 0, 0.766875029, 0)
TPCarthageArenaButton.Size = UDim2.new(0, 167, 0, 40)
TPCarthageArenaButton.Font = Enum.Font.SourceSans
TPCarthageArenaButton.Text = "TP to Arena"
TPCarthageArenaButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPCarthageArenaButton.TextSize = 22.000

MountainSectorMenu.Name = "MountainSectorMenu"
MountainSectorMenu.Parent = Frame
MountainSectorMenu.BackgroundColor3 = Color3.fromRGB(79, 79, 79)
MountainSectorMenu.Position = UDim2.new(0.231075704, 0, 0.0975541249, 0)
MountainSectorMenu.Size = UDim2.new(0, 578, 0, 320)
MountainSectorMenu.Visible = false

TPMountainTower1Button.Name = "TPMountainTower1Button"
TPMountainTower1Button.Parent = MountainSectorMenu
TPMountainTower1Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPMountainTower1Button.Position = UDim2.new(0.0299999993, 0, 0.0529999994, 0)
TPMountainTower1Button.Size = UDim2.new(0, 167, 0, 40)
TPMountainTower1Button.Font = Enum.Font.SourceSans
TPMountainTower1Button.Text = "TP to Tower 1"
TPMountainTower1Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPMountainTower1Button.TextSize = 22.000

TPMountainTower2Button.Name = "TPMountainTower2Button"
TPMountainTower2Button.Parent = MountainSectorMenu
TPMountainTower2Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPMountainTower2Button.Position = UDim2.new(0.0289999992, 0, 0.229000002, 0)
TPMountainTower2Button.Size = UDim2.new(0, 167, 0, 40)
TPMountainTower2Button.Font = Enum.Font.SourceSans
TPMountainTower2Button.Text = "TP to Tower 2"
TPMountainTower2Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPMountainTower2Button.TextSize = 22.000

TPMountainTower3Button.Name = "TPMountainTower3Button"
TPMountainTower3Button.Parent = MountainSectorMenu
TPMountainTower3Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPMountainTower3Button.Position = UDim2.new(0.0280000009, 0, 0.412999988, 0)
TPMountainTower3Button.Size = UDim2.new(0, 167, 0, 40)
TPMountainTower3Button.Font = Enum.Font.SourceSans
TPMountainTower3Button.Text = "TP to Tower 3"
TPMountainTower3Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPMountainTower3Button.TextSize = 22.000

TPMountainTower4Button.Name = "TPMountainTower4Button"
TPMountainTower4Button.Parent = MountainSectorMenu
TPMountainTower4Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPMountainTower4Button.Position = UDim2.new(0.0280000009, 0, 0.595000029, 0)
TPMountainTower4Button.Size = UDim2.new(0, 167, 0, 40)
TPMountainTower4Button.Font = Enum.Font.SourceSans
TPMountainTower4Button.Text = "TP to Tower 4"
TPMountainTower4Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPMountainTower4Button.TextSize = 22.000

TPMountainTower5Button.Name = "TPMountainTower5Button"
TPMountainTower5Button.Parent = MountainSectorMenu
TPMountainTower5Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPMountainTower5Button.Position = UDim2.new(0.0299999993, 0, 0.773000002, 0)
TPMountainTower5Button.Size = UDim2.new(0, 167, 0, 40)
TPMountainTower5Button.Font = Enum.Font.SourceSans
TPMountainTower5Button.Text = "TP to Tower 5"
TPMountainTower5Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPMountainTower5Button.TextSize = 22.000

TPMountainTower6Button.Name = "TPMountainTower6Button"
TPMountainTower6Button.Parent = MountainSectorMenu
TPMountainTower6Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPMountainTower6Button.Position = UDim2.new(0.356000006, 0, 0.0520000011, 0)
TPMountainTower6Button.Size = UDim2.new(0, 167, 0, 40)
TPMountainTower6Button.Font = Enum.Font.SourceSans
TPMountainTower6Button.Text = "TP to Tower 6"
TPMountainTower6Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPMountainTower6Button.TextSize = 22.000

TPMountainTower7Button.Name = "TPMountainTower7Button"
TPMountainTower7Button.Parent = MountainSectorMenu
TPMountainTower7Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPMountainTower7Button.Position = UDim2.new(0, 205, 0, 73)
TPMountainTower7Button.Size = UDim2.new(0, 167, 0, 40)
TPMountainTower7Button.Font = Enum.Font.SourceSans
TPMountainTower7Button.Text = "TP to Tower 7"
TPMountainTower7Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPMountainTower7Button.TextSize = 22.000

TPMountainTower8Button.Name = "TPMountainTower8Button"
TPMountainTower8Button.Parent = MountainSectorMenu
TPMountainTower8Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPMountainTower8Button.Position = UDim2.new(0.352999985, 0, 0.411000013, 0)
TPMountainTower8Button.Size = UDim2.new(0, 167, 0, 40)
TPMountainTower8Button.Font = Enum.Font.SourceSans
TPMountainTower8Button.Text = "TP to Tower 8"
TPMountainTower8Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPMountainTower8Button.TextSize = 22.000

TPMountainTower9Button.Name = "TPMountainTower9Button"
TPMountainTower9Button.Parent = MountainSectorMenu
TPMountainTower9Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPMountainTower9Button.Position = UDim2.new(0.352999985, 0, 0.593999982, 0)
TPMountainTower9Button.Size = UDim2.new(0, 167, 0, 40)
TPMountainTower9Button.Font = Enum.Font.SourceSans
TPMountainTower9Button.Text = "TP to Tower 9"
TPMountainTower9Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPMountainTower9Button.TextSize = 22.000

TPMountainTower10Button.Name = "TPMountainTower10Button"
TPMountainTower10Button.Parent = MountainSectorMenu
TPMountainTower10Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPMountainTower10Button.Position = UDim2.new(0.356000006, 0, 0.771000028, 0)
TPMountainTower10Button.Size = UDim2.new(0, 167, 0, 40)
TPMountainTower10Button.Font = Enum.Font.SourceSans
TPMountainTower10Button.Text = "TP to Tower 10"
TPMountainTower10Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPMountainTower10Button.TextSize = 22.000

TextLabel_6.Parent = MountainSectorMenu
TextLabel_6.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
TextLabel_6.Position = UDim2.new(0, 0, -0.117001697, 0)
TextLabel_6.Size = UDim2.new(0, 578, 0, 37)
TextLabel_6.Font = Enum.Font.SourceSans
TextLabel_6.Text = "Mountain Menu"
TextLabel_6.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_6.TextSize = 30.000

IceSectorMenu.Name = "IceSectorMenu"
IceSectorMenu.Parent = Frame
IceSectorMenu.BackgroundColor3 = Color3.fromRGB(79, 79, 79)
IceSectorMenu.Position = UDim2.new(0.230464533, 0, 0.0985210612, 0)
IceSectorMenu.Size = UDim2.new(0, 579, 0, 320)
IceSectorMenu.Visible = false

TPIceTower1Button.Name = "TPIceTower1Button"
TPIceTower1Button.Parent = IceSectorMenu
TPIceTower1Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPIceTower1Button.Position = UDim2.new(0.0297555923, 0, 0.0527932048, 0)
TPIceTower1Button.Size = UDim2.new(0, 167, 0, 40)
TPIceTower1Button.Font = Enum.Font.SourceSans
TPIceTower1Button.Text = "TP to Tower 1"
TPIceTower1Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPIceTower1Button.TextSize = 22.000

TPIceTower2Button.Name = "TPIceTower2Button"
TPIceTower2Button.Parent = IceSectorMenu
TPIceTower2Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPIceTower2Button.Position = UDim2.new(0.0293182395, 0, 0.228943557, 0)
TPIceTower2Button.Size = UDim2.new(0, 167, 0, 40)
TPIceTower2Button.Font = Enum.Font.SourceSans
TPIceTower2Button.Text = "TP to Tower 2"
TPIceTower2Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPIceTower2Button.TextSize = 22.000

TPIceTower3Button.Name = "TPIceTower3Button"
TPIceTower3Button.Parent = IceSectorMenu
TPIceTower3Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPIceTower3Button.Position = UDim2.new(0.028028477, 0, 0.413150579, 0)
TPIceTower3Button.Size = UDim2.new(0, 167, 0, 40)
TPIceTower3Button.Font = Enum.Font.SourceSans
TPIceTower3Button.Text = "TP to Tower 3"
TPIceTower3Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPIceTower3Button.TextSize = 22.000

TPIceTower4Button.Name = "TPIceTower4Button"
TPIceTower4Button.Parent = IceSectorMenu
TPIceTower4Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPIceTower4Button.Position = UDim2.new(0.0280284844, 0, 0.594681799, 0)
TPIceTower4Button.Size = UDim2.new(0, 167, 0, 40)
TPIceTower4Button.Font = Enum.Font.SourceSans
TPIceTower4Button.Text = "TP to Tower 4"
TPIceTower4Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPIceTower4Button.TextSize = 22.000

TPIceTower5Button.Name = "TPIceTower5Button"
TPIceTower5Button.Parent = IceSectorMenu
TPIceTower5Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPIceTower5Button.Position = UDim2.new(0.0297555923, 0, 0.773117363, 0)
TPIceTower5Button.Size = UDim2.new(0, 167, 0, 40)
TPIceTower5Button.Font = Enum.Font.SourceSans
TPIceTower5Button.Text = "TP to Tower 5"
TPIceTower5Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPIceTower5Button.TextSize = 22.000

TPIceTower6Button.Name = "TPIceTower6Button"
TPIceTower6Button.Parent = IceSectorMenu
TPIceTower6Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPIceTower6Button.Position = UDim2.new(0.355583221, 0, 0.0516546816, 0)
TPIceTower6Button.Size = UDim2.new(0, 167, 0, 40)
TPIceTower6Button.Font = Enum.Font.SourceSans
TPIceTower6Button.Text = "TP to Tower 6"
TPIceTower6Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPIceTower6Button.TextSize = 22.000

TPIceTower7Button.Name = "TPIceTower7Button"
TPIceTower7Button.Parent = IceSectorMenu
TPIceTower7Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPIceTower7Button.Position = UDim2.new(0, 205, 0, 73)
TPIceTower7Button.Size = UDim2.new(0, 167, 0, 40)
TPIceTower7Button.Font = Enum.Font.SourceSans
TPIceTower7Button.Text = "TP to Tower 7"
TPIceTower7Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPIceTower7Button.TextSize = 22.000

TPIceTower8Button.Name = "TPIceTower8Button"
TPIceTower8Button.Parent = IceSectorMenu
TPIceTower8Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPIceTower8Button.Position = UDim2.new(0.353418767, 0, 0.410827756, 0)
TPIceTower8Button.Size = UDim2.new(0, 167, 0, 40)
TPIceTower8Button.Font = Enum.Font.SourceSans
TPIceTower8Button.Text = "TP to Tower 8"
TPIceTower8Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPIceTower8Button.TextSize = 22.000

TPIceTower9Button.Name = "TPIceTower9Button"
TPIceTower9Button.Parent = IceSectorMenu
TPIceTower9Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPIceTower9Button.Position = UDim2.new(0.353418708, 0, 0.593628287, 0)
TPIceTower9Button.Size = UDim2.new(0, 167, 0, 40)
TPIceTower9Button.Font = Enum.Font.SourceSans
TPIceTower9Button.Text = "TP to Tower 9"
TPIceTower9Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPIceTower9Button.TextSize = 22.000

TPIceTower10Button.Name = "TPIceTower10Button"
TPIceTower10Button.Parent = IceSectorMenu
TPIceTower10Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPIceTower10Button.Position = UDim2.new(0.355583221, 0, 0.771381795, 0)
TPIceTower10Button.Size = UDim2.new(0, 167, 0, 40)
TPIceTower10Button.Font = Enum.Font.SourceSans
TPIceTower10Button.Text = "TP to Tower 10"
TPIceTower10Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPIceTower10Button.TextSize = 22.000

TextLabel_7.Parent = IceSectorMenu
TextLabel_7.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
TextLabel_7.Position = UDim2.new(0, 0, -0.117001697, 0)
TextLabel_7.Size = UDim2.new(0, 578, 0, 37)
TextLabel_7.Font = Enum.Font.SourceSans
TextLabel_7.Text = "Ice Menu"
TextLabel_7.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_7.TextSize = 30.000

CloseButton.Name = "CloseButton"
CloseButton.Parent = Frame
CloseButton.BackgroundColor3 = Color3.fromRGB(255, 0, 4)
CloseButton.Position = UDim2.new(0.946164131, 0, 0.0173881203, 0)
CloseButton.Size = UDim2.new(0, 31, 0, 22)
CloseButton.Font = Enum.Font.SourceSans
CloseButton.Text = "-"
CloseButton.TextColor3 = Color3.fromRGB(0, 0, 0)
CloseButton.TextSize = 32.000

TextButton.Parent = ScreenGui
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.Position = UDim2.new(-1.37994066e-05, 0, 0.469606668, 0)
TextButton.Size = UDim2.new(0, 103, 0, 50)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "Open Menu"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 22.000

-- Scripts:

local function QLOH_fake_script() -- Carthagesector.Script 
	local script = Instance.new('Script', Carthagesector)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.CityMenu.Visible = false
		script.Parent.Parent.IceSectorMenu.Visible = false
		script.Parent.Parent.ForestSectorMenu.Visible = false
		script.Parent.Parent.DesertSectorMenu.Visible = false
		script.Parent.Parent.MountainSectorMenu.Visible = false
		script.Parent.Parent.CarthageSectorMenu.Visible = true
	end)
	
end
coroutine.wrap(QLOH_fake_script)()
local function TBPSM_fake_script() -- Desertsector.Script 
	local script = Instance.new('Script', Desertsector)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.CityMenu.Visible = false
		script.Parent.Parent.IceSectorMenu.Visible = false
		script.Parent.Parent.ForestSectorMenu.Visible = false
		script.Parent.Parent.DesertSectorMenu.Visible = true
		script.Parent.Parent.MountainSectorMenu.Visible = false
		script.Parent.Parent.CarthageSectorMenu.Visible = false
	end)
	
end
coroutine.wrap(TBPSM_fake_script)()
local function VTGZ_fake_script() -- Forestsector.Script 
	local script = Instance.new('Script', Forestsector)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.CityMenu.Visible = false
		script.Parent.Parent.IceSectorMenu.Visible = false
		script.Parent.Parent.ForestSectorMenu.Visible = true
		script.Parent.Parent.DesertSectorMenu.Visible = false
		script.Parent.Parent.MountainSectorMenu.Visible = false
		script.Parent.Parent.CarthageSectorMenu.Visible = false
	end)
	
end
coroutine.wrap(VTGZ_fake_script)()
local function LRTH_fake_script() -- Icesector.Script 
	local script = Instance.new('Script', Icesector)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.CityMenu.Visible = false
		script.Parent.Parent.IceSectorMenu.Visible = true
		script.Parent.Parent.ForestSectorMenu.Visible = false
		script.Parent.Parent.DesertSectorMenu.Visible = false
		script.Parent.Parent.MountainSectorMenu.Visible = false
		script.Parent.Parent.CarthageSectorMenu.Visible = false
	end)
	
end
coroutine.wrap(LRTH_fake_script)()
local function LFGQO_fake_script() -- Mountainsector.Script 
	local script = Instance.new('Script', Mountainsector)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.CityMenu.Visible = false
		script.Parent.Parent.IceSectorMenu.Visible = false
		script.Parent.Parent.ForestSectorMenu.Visible = false
		script.Parent.Parent.DesertSectorMenu.Visible = false
		script.Parent.Parent.MountainSectorMenu.Visible = true
		script.Parent.Parent.CarthageSectorMenu.Visible = false
	end)
	
end
coroutine.wrap(LFGQO_fake_script)()
local function NFRK_fake_script() -- cityButton.Script 
	local script = Instance.new('Script', cityButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.CityMenu.Visible = true
		script.Parent.Parent.IceSectorMenu.Visible = false
		script.Parent.Parent.ForestSectorMenu.Visible = false
		script.Parent.Parent.DesertSectorMenu.Visible = false
		script.Parent.Parent.MountainSectorMenu.Visible = false
		script.Parent.Parent.CarthageSectorMenu.Visible = false
	end)
	
end
coroutine.wrap(NFRK_fake_script)()
local function AIOE_fake_script() -- TPscannerButton.Script 
	local script = Instance.new('Script', TPscannerButton)

	TPscannerButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-962.077, -289.897, 1352.83)
	end)
end
coroutine.wrap(AIOE_fake_script)()
local function PWPPFVI_fake_script() -- TPsupercomputerButton.Script 
	local script = Instance.new('Script', TPsupercomputerButton)

	TPsupercomputerButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-949.773, -405.458, 1334.34)
	end)
end
coroutine.wrap(PWPPFVI_fake_script)()
local function HKMP_fake_script() -- TPCanteenButton.Script 
	local script = Instance.new('Script', TPCanteenButton)

	TPCanteenButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-84.5979, 35.1351, -207.855)
	end) 
	
end
coroutine.wrap(HKMP_fake_script)()
local function VKND_fake_script() -- TPyumihouseButton.Script 
	local script = Instance.new('Script', TPyumihouseButton)

	TPyumihouseButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(305.536, 38.7759, -1351.93)
	end)
end
coroutine.wrap(VKND_fake_script)()
local function ADKIYCK_fake_script() -- TPHistoryclassButton.Script 
	local script = Instance.new('Script', TPHistoryclassButton)

	TPHistoryclassButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-111.345, 33.5051, -66.6376)
	end)
end
coroutine.wrap(ADKIYCK_fake_script)()
local function LPYLI_fake_script() -- TPmathclassButton.Script 
	local script = Instance.new('Script', TPmathclassButton)

	TPmathclassButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-135.576, 33.5051, -125.55)
	end)
end
coroutine.wrap(LPYLI_fake_script)()
local function INIDJTI_fake_script() -- TPreadingclassButton.Script 
	local script = Instance.new('Script', TPreadingclassButton)

	TPreadingclassButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-159.446, 33.5051, -182.625)
	end)
end
coroutine.wrap(INIDJTI_fake_script)()
local function OARW_fake_script() -- TPscienceclassButton.Script 
	local script = Instance.new('Script', TPscienceclassButton)

	TPscienceclassButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(135.907, 52.6109, -159.727)
	end)
end
coroutine.wrap(OARW_fake_script)()
local function TKBYL_fake_script() -- TPJeremyroomButton.Script 
	local script = Instance.new('Script', TPJeremyroomButton)

	TPJeremyroomButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-66.9497, 50.3451, -301.601)
	end)
	
end
coroutine.wrap(TKBYL_fake_script)()
local function LGWVUZ_fake_script() -- TPUlrichOddroomButton.Script 
	local script = Instance.new('Script', TPUlrichOddroomButton)

	TPUlrichOddroomButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-105.467, 50.2861, -328.007)
	end)
end
coroutine.wrap(LGWVUZ_fake_script)()
local function PFGWAQ_fake_script() -- TPwilliamroomButton.Script 
	local script = Instance.new('Script', TPwilliamroomButton)

	TPwilliamroomButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-74.5165, 50.2566, -90.6776)
	end)
end
coroutine.wrap(PFGWAQ_fake_script)()
local function QWHU_fake_script() -- TPAelitaroomButton.Script 
	local script = Instance.new('Script', TPAelitaroomButton)

	TPAelitaroomButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-149.629, 67.0851, -167.899)
	end)
end
coroutine.wrap(QWHU_fake_script)()
local function FTLND_fake_script() -- TPlaboButton.Script 
	local script = Instance.new('Script', TPlaboButton)

	TPlaboButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-927.318, -178.858, 1340.43)
	end)
end
coroutine.wrap(FTLND_fake_script)()
local function BZXO_fake_script() -- TPElizabethroomButton.Script 
	local script = Instance.new('Script', TPElizabethroomButton)

	TPElizabethroomButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-134.245, 67.0164, -134.003)
	end)
end
coroutine.wrap(BZXO_fake_script)()
local function GMSVJ_fake_script() -- TPMillyTamiaroomButton.Script 
	local script = Instance.new('Script', TPMillyTamiaroomButton)

	TPMillyTamiaroomButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-9.72453, 67.1618, -83.7629)
	end)
end
coroutine.wrap(GMSVJ_fake_script)()
local function DKVZVZ_fake_script() -- TPJimroomButton.Script 
	local script = Instance.new('Script', TPJimroomButton)

	TPJimroomButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-157.557, 50.2203, -273.338)
	end)
end
coroutine.wrap(DKVZVZ_fake_script)()
local function WDKLD_fake_script() -- TPForestTower1Button.Script 
	local script = Instance.new('Script', TPForestTower1Button)

	TPForestTower1Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(5657.17, 10670.3, 4682.75)
	end)
end
coroutine.wrap(WDKLD_fake_script)()
local function LDKNKYV_fake_script() -- TPForestTower2Button.Script 
	local script = Instance.new('Script', TPForestTower2Button)

	TPForestTower1Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(4675.48, 10682.1, 2116.84)
	end)
end
coroutine.wrap(LDKNKYV_fake_script)()
local function VUPJ_fake_script() -- TPForestTower3Button.Script 
	local script = Instance.new('Script', TPForestTower3Button)

	TPForestTower3Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2394.19, 10722.4, 4384.63)
	end)
end
coroutine.wrap(VUPJ_fake_script)()
local function ZIAK_fake_script() -- TPForestTower4Button.Script 
	local script = Instance.new('Script', TPForestTower4Button)

	TPForestTower3Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(4311.6, 10670.3, 4132.43)
	end)
end
coroutine.wrap(ZIAK_fake_script)()
local function JXUZYT_fake_script() -- TPForestTower5Button.Script 
	local script = Instance.new('Script', TPForestTower5Button)

	TPForestTower5Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(6160.07, 10670.3, 3483.59)
	end)
end
coroutine.wrap(JXUZYT_fake_script)()
local function ERZT_fake_script() -- TPForestTower6Button.Script 
	local script = Instance.new('Script', TPForestTower6Button)

	TPForestTower6Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3480.25, 10672.7, 5736.71)
	end)
end
coroutine.wrap(ERZT_fake_script)()
local function LGZIJ_fake_script() -- TPForestTower7Button.Script 
	local script = Instance.new('Script', TPForestTower7Button)

	TPForestTower7Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(5028.37, 10669.6, 5239.32)
	end)
end
coroutine.wrap(LGZIJ_fake_script)()
local function XARF_fake_script() -- TPForestTower8Button.Script 
	local script = Instance.new('Script', TPForestTower8Button)

	TPForestTower8Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(7374.69, 10685.1, 5436.44)
	end)
end
coroutine.wrap(XARF_fake_script)()
local function JFZAZH_fake_script() -- TPForestTower9Button.Script 
	local script = Instance.new('Script', TPForestTower9Button)

	TPForestTower9Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(5769.57, 10695.2, 6507.06)
	end)
end
coroutine.wrap(JFZAZH_fake_script)()
local function BRKSHQY_fake_script() -- TPForestTower10Button.Script 
	local script = Instance.new('Script', TPForestTower10Button)

	TPForestTower10Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(6758.03, 10693.4, 7310.46)
	end)
end
coroutine.wrap(BRKSHQY_fake_script)()
local function WHHB_fake_script() -- TPDesertTower1Button.Script 
	local script = Instance.new('Script', TPDesertTower1Button)

	TPDesertTower1Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(6737, 10661.5, -6146.28)
	end)
end
coroutine.wrap(WHHB_fake_script)()
local function HCQU_fake_script() -- TPDesertTower2Button.Script 
	local script = Instance.new('Script', TPDesertTower2Button)

	TPDesertTower2Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3809.25, 10662.4, -3483.43)
	end)
end
coroutine.wrap(HCQU_fake_script)()
local function FVXBPOB_fake_script() -- TPDesertTower3Button.Script 
	local script = Instance.new('Script', TPDesertTower3Button)

	TPDesertTower3Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3203.06, 10666.2, -5705.44)
	end)
end
coroutine.wrap(FVXBPOB_fake_script)()
local function QJUUBN_fake_script() -- TPDesertTower4Button.Script 
	local script = Instance.new('Script', TPDesertTower4Button)

	TPDesertTower4Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(5932.33, 10537.2, -2621.19)
	end)
end
coroutine.wrap(QJUUBN_fake_script)()
local function LTAHT_fake_script() -- TPDesertTower5Button.Script 
	local script = Instance.new('Script', TPDesertTower5Button)

	TPDesertTower5Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(5903.74, 10646.8, -4357.42)
	end)
end
coroutine.wrap(LTAHT_fake_script)()
local function ZBRLN_fake_script() -- TPDesertTower6Button.Script 
	local script = Instance.new('Script', TPDesertTower6Button)

	TPDesertTower6Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(4323.6, 10661.7, -6877.87)
	end)
end
coroutine.wrap(ZBRLN_fake_script)()
local function RBTGTA_fake_script() -- TPDesertTower7Button.Script 
	local script = Instance.new('Script', TPDesertTower7Button)

	TPDesertTower7Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(8271.82, 10643, -3561.59)
	end)
end
coroutine.wrap(RBTGTA_fake_script)()
local function MSJP_fake_script() -- TPDesertTower8Button.Script 
	local script = Instance.new('Script', TPDesertTower8Button)

	TPDesertTower8Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(8552.32, 10645.1, -6645.08)
	end)
end
coroutine.wrap(MSJP_fake_script)()
local function WHHGW_fake_script() -- TPDesertTower9Button.Script 
	local script = Instance.new('Script', TPDesertTower9Button)

	TPDesertTower9Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(6157.33, 10517.2, -8623.81)
	end)
end
coroutine.wrap(WHHGW_fake_script)()
local function FISDNT_fake_script() -- TPDesertTower10Button.Script 
	local script = Instance.new('Script', TPDesertTower10Button)

	TPDesertTower10Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(8121.34, 10642, -8042.99)
	end)
end
coroutine.wrap(FISDNT_fake_script)()
local function IKTDBKL_fake_script() -- TPCarthageTower1Button.Script 
	local script = Instance.new('Script', TPCarthageTower1Button)

	TPCarthageTower1Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(16.7065, 11009.6, 342.497)
	end)
end
coroutine.wrap(IKTDBKL_fake_script)()
local function JNHQZ_fake_script() -- TPCarthageSkidButton.Script 
	local script = Instance.new('Script', TPCarthageSkidButton)

	TPCarthageSkidButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(30.8609, 11623.7, 68.17)
	end)
end
coroutine.wrap(JNHQZ_fake_script)()
local function SWAYNFB_fake_script() -- TPCarthageHeartButton.Script 
	local script = Instance.new('Script', TPCarthageHeartButton)

	TPCarthageHeartButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(25.637, 10561.6, 155.296)
	end)
end
coroutine.wrap(SWAYNFB_fake_script)()
local function XARN_fake_script() -- TPCarthageMemoryButton.Script 
	local script = Instance.new('Script', TPCarthageMemoryButton)

	TPCarthageMemoryButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(23.5575, 11014.8, -862.401)
	end)
end
coroutine.wrap(XARN_fake_script)()
local function YKIVR_fake_script() -- TPCarthageArenaButton.Script 
	local script = Instance.new('Script', TPCarthageArenaButton)

	TPCarthageArenaButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(29.8861, 11015, 16.4096)
	end)
end
coroutine.wrap(YKIVR_fake_script)()
local function IUYTBS_fake_script() -- TPMountainTower1Button.Script 
	local script = Instance.new('Script', TPMountainTower1Button)

	TPMountainTower1Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4858.05, 10289.1, 5432.04)
	end)
end
coroutine.wrap(IUYTBS_fake_script)()
local function BYAJ_fake_script() -- TPMountainTower2Button.Script 
	local script = Instance.new('Script', TPMountainTower2Button)

	TPMountainTower2Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5839.6, 10644.3, 2774.17)
	end)
end
coroutine.wrap(BYAJ_fake_script)()
local function XZGOJ_fake_script() -- TPMountainTower3Button.Script 
	local script = Instance.new('Script', TPMountainTower3Button)

	TPMountainTower3Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2574.06, 10296.8, 4768.57)
	end)
end
coroutine.wrap(XZGOJ_fake_script)()
local function BSAHMO_fake_script() -- TPMountainTower4Button.Script 
	local script = Instance.new('Script', TPMountainTower4Button)

	TPMountainTower4Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-6233.47, 10305.4, 4960.89)
	end)
end
coroutine.wrap(BSAHMO_fake_script)()
local function MNBELK_fake_script() -- TPMountainTower5Button.Script 
	local script = Instance.new('Script', TPMountainTower5Button)

	TPMountainTower5Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4210.39, 10638.2, 5970.01)
	end)
end
coroutine.wrap(MNBELK_fake_script)()
local function RDKNHX_fake_script() -- TPMountainTower6Button.Script 
	local script = Instance.new('Script', TPMountainTower6Button)

	TPMountainTower6Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5046.08, 10285.1, 7355.53)
	end)
end
coroutine.wrap(RDKNHX_fake_script)()
local function JAFMV_fake_script() -- TPMountainTower7Button.Script 
	local script = Instance.new('Script', TPMountainTower7Button)

	TPMountainTower7Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-6831.23, 10660.2, 6564.93)
	end)
end
coroutine.wrap(JAFMV_fake_script)()
local function SCYEXS_fake_script() -- TPMountainTower8Button.Script 
	local script = Instance.new('Script', TPMountainTower8Button)

	TPMountainTower8Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-7905.15, 10305.4, 6523.76)
	end)
end
coroutine.wrap(SCYEXS_fake_script)()
local function OJRIRW_fake_script() -- TPMountainTower9Button.Script 
	local script = Instance.new('Script', TPMountainTower9Button)

	TPMountainTower9Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-6269.04, 10653.4, 8540.51)
	end)
end
coroutine.wrap(OJRIRW_fake_script)()
local function QRADC_fake_script() -- TPMountainTower10Button.Script 
	local script = Instance.new('Script', TPMountainTower10Button)

	TPMountainTower10Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-7162.2, 10292.9, 7768.93)
	end)
end
coroutine.wrap(QRADC_fake_script)()
local function CECPJKN_fake_script() -- TPIceTower1Button.Script 
	local script = Instance.new('Script', TPIceTower1Button)

	TPIceTower1Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5794.13, 10493, -6083.61)
	end)
end
coroutine.wrap(CECPJKN_fake_script)()
local function XRLPP_fake_script() -- TPIceTower2Button.Script 
	local script = Instance.new('Script', TPIceTower2Button)

	TPIceTower2Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2316.91, 10528.1, -4805.98)
	end)
end
coroutine.wrap(XRLPP_fake_script)()
local function DUHFLUC_fake_script() -- TPIceTower3Button.Script 
	local script = Instance.new('Script', TPIceTower3Button)

	TPIceTower3Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2781.41, 10515.3, -6118.96)
	end)
end
coroutine.wrap(DUHFLUC_fake_script)()
local function UZYWFA_fake_script() -- TPIceTower4Button.Script 
	local script = Instance.new('Script', TPIceTower4Button)

	TPIceTower4Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4604.56, 10507.4, -3498.57)
	end)
end
coroutine.wrap(UZYWFA_fake_script)()
local function RMZHJPQ_fake_script() -- TPIceTower5Button.Script 
	local script = Instance.new('Script', TPIceTower5Button)

	TPIceTower5Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5761.87, 10518.8, -2380.26)
	end)
end
coroutine.wrap(RMZHJPQ_fake_script)()
local function QSTPND_fake_script() -- TPIceTower6Button.Script 
	local script = Instance.new('Script', TPIceTower6Button)

	TPIceTower6Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-6622.91, 10512, -3566.51)
	end)
end
coroutine.wrap(QSTPND_fake_script)()
local function YNNOBQ_fake_script() -- TPIceTower7Button.Script 
	local script = Instance.new('Script', TPIceTower7Button)

	TPIceTower7Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5579.4, 10522.9, -5189.92)
	end)
end
coroutine.wrap(YNNOBQ_fake_script)()
local function ULVRE_fake_script() -- TPIceTower8Button.Script 
	local script = Instance.new('Script', TPIceTower8Button)

	TPIceTower8Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4510.06, 10482.7, -6791.05)
	end)
end
coroutine.wrap(ULVRE_fake_script)()
local function LSVUI_fake_script() -- TPIceTower9Button.Script 
	local script = Instance.new('Script', TPIceTower9Button)

	TPIceTower9Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-8385.81, 10523.5, -6036.5)
	end)
end
coroutine.wrap(LSVUI_fake_script)()
local function YYTT_fake_script() -- TPIceTower10Button.Script 
	local script = Instance.new('Script', TPIceTower10Button)

	TPIceTower10Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-7686.17, 10479.4, -7468.36)
	end)
end
coroutine.wrap(YYTT_fake_script)()
local function RSIOYI_fake_script() -- CloseButton.Script 
	local script = Instance.new('Script', CloseButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.Frame.Visible = false
	end)
	
end
coroutine.wrap(RSIOYI_fake_script)()
local function AZXJN_fake_script() -- TextButton.Script 
	local script = Instance.new('Script', TextButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Frame.Visible = true
	end)
	
end
coroutine.wrap(AZXJN_fake_script)()
