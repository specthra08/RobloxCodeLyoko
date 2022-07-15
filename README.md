--created by specthra#2955
--press C to open/close the menu

local TPMenuEnglish = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local CarthageSectorMenu = Instance.new("Frame")
local CarthageTextLabel = Instance.new("TextLabel")
local TPCarthageTower1Button = Instance.new("TextButton")
local TPCarthageSkidButton = Instance.new("TextButton")
local TPCarthageHeartButton = Instance.new("TextButton")
local TPCarthageMemoryButton = Instance.new("TextButton")
local TPCarthageArenaButton = Instance.new("TextButton")
local CityMenu = Instance.new("Frame")
local CityTextLabel = Instance.new("TextLabel")
local TPlaboButton = Instance.new("TextButton")
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
local TPElizabethroomButton = Instance.new("TextButton")
local TPMillyTamiaroomButton = Instance.new("TextButton")
local TPJimroomButton = Instance.new("TextButton")
local DesertSectorMenu = Instance.new("Frame")
local DesertTextLabel = Instance.new("TextLabel")
local TPDesertTower2Button = Instance.new("TextButton")
local TPDesertTower3Button = Instance.new("TextButton")
local TPDesertTower4Button = Instance.new("TextButton")
local TPDesertTower5Button = Instance.new("TextButton")
local TPDesertTower6Button = Instance.new("TextButton")
local TPDesertTower7Button = Instance.new("TextButton")
local TPDesertTower8Button = Instance.new("TextButton")
local TPDesertTower9Button = Instance.new("TextButton")
local TPDesertTower10Button = Instance.new("TextButton")
local TPDesertTower1Button = Instance.new("TextButton")
local ForestSectorMenu = Instance.new("Frame")
local ForestTextLabel = Instance.new("TextLabel")
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
local IceSectorMenu = Instance.new("Frame")
local IceTextLabel = Instance.new("TextLabel")
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
local MountainSectorMenu = Instance.new("Frame")
local MountainTextLabel = Instance.new("TextLabel")
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
local Carthagesector = Instance.new("TextButton")
local Desertsector = Instance.new("TextButton")
local Forestsector = Instance.new("TextButton")
local Icesector = Instance.new("TextButton")
local Mountainsector = Instance.new("TextButton")
local cityButton = Instance.new("TextButton")
local NameTextLabel = Instance.new("TextLabel")
local byspecthraTextLabel = Instance.new("TextLabel")
local Frame1 = Instance.new("Frame")
local Frame2 = Instance.new("Frame")

--Properties:

TPMenuEnglish.Name = "TPMenu.English"
TPMenuEnglish.Parent = game.CoreGui

Frame.Parent = TPMenuEnglish
Frame.BackgroundColor3 = Color3.fromRGB(79, 79, 79)
Frame.Position = UDim2.new(0.255649716, 0, 0.282479137, 0)
Frame.Size = UDim2.new(0, 692, 0, 329)
Frame.Visible = false
Frame.Active = true

Frame.Draggable = true
CarthageSectorMenu.Draggable = true
CityMenu.Draggable = true
IceSectorMenu.Draggable = true
DesertSectorMenu.Draggable = true
ForestSectorMenu.Draggable = true
MountainSectorMenu.Draggable = true

CarthageSectorMenu.Name = "CarthageSectorMenu"
CarthageSectorMenu.Parent = Frame
CarthageSectorMenu.BackgroundColor3 = Color3.fromRGB(79, 79, 79)
CarthageSectorMenu.Position = UDim2.new(0.229801774, 0, 0.119356193, 0)
CarthageSectorMenu.Size = UDim2.new(0, 531, 0, 289)
CarthageSectorMenu.Visible = false

CarthageTextLabel.Name = "CarthageTextLabel"
CarthageTextLabel.Parent = CarthageSectorMenu
CarthageTextLabel.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
CarthageTextLabel.Position = UDim2.new(-0.303474903, 0, -0.137306362, 0)
CarthageTextLabel.Size = UDim2.new(0, 693, 0, 40)
CarthageTextLabel.ZIndex = 2
CarthageTextLabel.Font = Enum.Font.SourceSans
CarthageTextLabel.Text = "Carthage "
CarthageTextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
CarthageTextLabel.TextSize = 32.000

TPCarthageTower1Button.Name = "TPCarthageTower1Button"
TPCarthageTower1Button.Parent = CarthageSectorMenu
TPCarthageTower1Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPCarthageTower1Button.Position = UDim2.new(0.00100000005, 0, 0.0370000005, 0)
TPCarthageTower1Button.Size = UDim2.new(0, 155, 0, 31)
TPCarthageTower1Button.Font = Enum.Font.SourceSans
TPCarthageTower1Button.Text = "TP to Tower 1"
TPCarthageTower1Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPCarthageTower1Button.TextSize = 28.000

TPCarthageSkidButton.Name = "TPCarthageSkidButton"
TPCarthageSkidButton.Parent = CarthageSectorMenu
TPCarthageSkidButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPCarthageSkidButton.Position = UDim2.new(0.00100000005, 0, 0.479999989, 0)
TPCarthageSkidButton.Size = UDim2.new(0, 155, 0, 31)
TPCarthageSkidButton.Font = Enum.Font.SourceSans
TPCarthageSkidButton.Text = "TP to skid room"
TPCarthageSkidButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPCarthageSkidButton.TextSize = 28.000

TPCarthageHeartButton.Name = "TPCarthageHeartButton"
TPCarthageHeartButton.Parent = CarthageSectorMenu
TPCarthageHeartButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPCarthageHeartButton.Position = UDim2.new(0, 0, 0.178000003, 0)
TPCarthageHeartButton.Size = UDim2.new(0, 155, 0, 31)
TPCarthageHeartButton.Font = Enum.Font.SourceSans
TPCarthageHeartButton.Text = "TP to heart room"
TPCarthageHeartButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPCarthageHeartButton.TextSize = 28.000

TPCarthageMemoryButton.Name = "TPCarthageMemoryButton"
TPCarthageMemoryButton.Parent = CarthageSectorMenu
TPCarthageMemoryButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPCarthageMemoryButton.Position = UDim2.new(0, 0, 0.324999988, 0)
TPCarthageMemoryButton.Size = UDim2.new(0, 155, 0, 31)
TPCarthageMemoryButton.Font = Enum.Font.SourceSans
TPCarthageMemoryButton.Text = "TP to memory"
TPCarthageMemoryButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPCarthageMemoryButton.TextSize = 28.000

TPCarthageArenaButton.Name = "TPCarthageArenaButton"
TPCarthageArenaButton.Parent = CarthageSectorMenu
TPCarthageArenaButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPCarthageArenaButton.Position = UDim2.new(-0.00100000005, 0, 0.643999994, 0)
TPCarthageArenaButton.Size = UDim2.new(0, 155, 0, 31)
TPCarthageArenaButton.Font = Enum.Font.SourceSans
TPCarthageArenaButton.Text = "TP to Arena"
TPCarthageArenaButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPCarthageArenaButton.TextSize = 28.000

CityMenu.Name = "CityMenu"
CityMenu.Parent = Frame
CityMenu.BackgroundColor3 = Color3.fromRGB(79, 79, 79)
CityMenu.Position = UDim2.new(0.228712231, 0, 0.120490074, 0)
CityMenu.Size = UDim2.new(0, 533, 0, 289)
CityMenu.Visible = false

CityTextLabel.Name = "CityTextLabel"
CityTextLabel.Parent = CityMenu
CityTextLabel.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
CityTextLabel.Position = UDim2.new(-0.295267105, 0, -0.14529407, 0)
CityTextLabel.Size = UDim2.new(0, 689, 0, 43)
CityTextLabel.ZIndex = 2
CityTextLabel.Font = Enum.Font.SourceSans
CityTextLabel.Text = "City Teleport"
CityTextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
CityTextLabel.TextSize = 32.000

TPlaboButton.Name = "TPlaboButton"
TPlaboButton.Parent = CityMenu
TPlaboButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPlaboButton.Position = UDim2.new(0.00124337664, 0, 0.0370687209, 0)
TPlaboButton.Size = UDim2.new(0, 155, 0, 31)
TPlaboButton.Font = Enum.Font.SourceSans
TPlaboButton.Text = "TP to labo"
TPlaboButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPlaboButton.TextSize = 22.000

TPscannerButton.Name = "TPscannerButton"
TPscannerButton.Parent = CityMenu
TPscannerButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPscannerButton.Position = UDim2.new(0.00048327446, 0, 0.17761147, 0)
TPscannerButton.Size = UDim2.new(0, 155, 0, 31)
TPscannerButton.Font = Enum.Font.SourceSans
TPscannerButton.Text = "TP to scanner"
TPscannerButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPscannerButton.TextSize = 22.000

TPsupercomputerButton.Name = "TPsupercomputerButton"
TPsupercomputerButton.Parent = CityMenu
TPsupercomputerButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPsupercomputerButton.Position = UDim2.new(0.000429213047, 0, 0.3251656, 0)
TPsupercomputerButton.Size = UDim2.new(0, 155, 0, 31)
TPsupercomputerButton.Font = Enum.Font.SourceSans
TPsupercomputerButton.Text = "TP to supercomputer"
TPsupercomputerButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPsupercomputerButton.TextSize = 22.000

TPCanteenButton.Name = "TPCanteenButton"
TPCanteenButton.Parent = CityMenu
TPCanteenButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPCanteenButton.Position = UDim2.new(0.000584602356, 0, 0.479587227, 0)
TPCanteenButton.Size = UDim2.new(0, 155, 0, 31)
TPCanteenButton.Font = Enum.Font.SourceSans
TPCanteenButton.Text = "TP to Canteen"
TPCanteenButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPCanteenButton.TextSize = 22.000

TPyumihouseButton.Name = "TPyumihouseButton"
TPyumihouseButton.Parent = CityMenu
TPyumihouseButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPyumihouseButton.Position = UDim2.new(0.324702263, 0, 0.800659835, 0)
TPyumihouseButton.Size = UDim2.new(0, 155, 0, 31)
TPyumihouseButton.Font = Enum.Font.SourceSans
TPyumihouseButton.Text = "TP to Yumi's house"
TPyumihouseButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPyumihouseButton.TextSize = 22.000

TPHistoryclassButton.Name = "TPHistoryclassButton"
TPHistoryclassButton.Parent = CityMenu
TPHistoryclassButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPHistoryclassButton.Position = UDim2.new(-0.00125300605, 0, 0.643739462, 0)
TPHistoryclassButton.Size = UDim2.new(0, 155, 0, 31)
TPHistoryclassButton.Font = Enum.Font.SourceSans
TPHistoryclassButton.Text = "TP to history class"
TPHistoryclassButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPHistoryclassButton.TextSize = 22.000

TPmathclassButton.Name = "TPmathclassButton"
TPmathclassButton.Parent = CityMenu
TPmathclassButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPmathclassButton.Position = UDim2.new(0.00065857172, 0, 0.80387789, 0)
TPmathclassButton.Size = UDim2.new(0, 155, 0, 31)
TPmathclassButton.Font = Enum.Font.SourceSans
TPmathclassButton.Text = "TP to math class"
TPmathclassButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPmathclassButton.TextSize = 22.000

TPreadingclassButton.Name = "TPreadingclassButton"
TPreadingclassButton.Parent = CityMenu
TPreadingclassButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPreadingclassButton.Position = UDim2.new(0.324847102, 0, 0.0339816809, 0)
TPreadingclassButton.Size = UDim2.new(0, 155, 0, 31)
TPreadingclassButton.Font = Enum.Font.SourceSans
TPreadingclassButton.Text = "TP to reading class"
TPreadingclassButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPreadingclassButton.TextSize = 22.000

TPscienceclassButton.Name = "TPscienceclassButton"
TPscienceclassButton.Parent = CityMenu
TPscienceclassButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPscienceclassButton.Position = UDim2.new(0.324811667, 0, 0.17560786, 0)
TPscienceclassButton.Size = UDim2.new(0, 155, 0, 31)
TPscienceclassButton.Font = Enum.Font.SourceSans
TPscienceclassButton.Text = "TP to science class"
TPscienceclassButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPscienceclassButton.TextSize = 22.000

TPJeremyroomButton.Name = "TPJeremyroomButton"
TPJeremyroomButton.Parent = CityMenu
TPJeremyroomButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPJeremyroomButton.Position = UDim2.new(0.323038459, 0, 0.643151164, 0)
TPJeremyroomButton.Size = UDim2.new(0, 155, 0, 31)
TPJeremyroomButton.Font = Enum.Font.SourceSans
TPJeremyroomButton.Text = "TP to Jeremy's room"
TPJeremyroomButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPJeremyroomButton.TextSize = 22.000

TPUlrichOddroomButton.Name = "TPUlrichOddroomButton"
TPUlrichOddroomButton.Parent = CityMenu
TPUlrichOddroomButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPUlrichOddroomButton.Position = UDim2.new(0.321622461, 0, 0.489171952, 0)
TPUlrichOddroomButton.Size = UDim2.new(0, 155, 0, 31)
TPUlrichOddroomButton.Font = Enum.Font.SourceSans
TPUlrichOddroomButton.Text = "TP to Urich/Odd room"
TPUlrichOddroomButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPUlrichOddroomButton.TextSize = 22.000

TPwilliamroomButton.Name = "TPwilliamroomButton"
TPwilliamroomButton.Parent = CityMenu
TPwilliamroomButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPwilliamroomButton.Position = UDim2.new(0.323357046, 0, 0.325780869, 0)
TPwilliamroomButton.Size = UDim2.new(0, 155, 0, 31)
TPwilliamroomButton.Font = Enum.Font.SourceSans
TPwilliamroomButton.Text = "TP to William's room"
TPwilliamroomButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPwilliamroomButton.TextSize = 22.000

TPAelitaroomButton.Name = "TPAelitaroomButton"
TPAelitaroomButton.Parent = CityMenu
TPAelitaroomButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPAelitaroomButton.Position = UDim2.new(0.641775489, 0, 0.0359539315, 0)
TPAelitaroomButton.Size = UDim2.new(0, 167, 0, 31)
TPAelitaroomButton.Font = Enum.Font.SourceSans
TPAelitaroomButton.Text = "TP to Aelita's room"
TPAelitaroomButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPAelitaroomButton.TextSize = 22.000

TPElizabethroomButton.Name = "TPElizabethroomButton"
TPElizabethroomButton.Parent = CityMenu
TPElizabethroomButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPElizabethroomButton.Position = UDim2.new(0.641775489, 0, 0.174362242, 0)
TPElizabethroomButton.Size = UDim2.new(0, 167, 0, 31)
TPElizabethroomButton.Font = Enum.Font.SourceSans
TPElizabethroomButton.Text = "TP to Elizabeth's room"
TPElizabethroomButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPElizabethroomButton.TextSize = 22.000

TPMillyTamiaroomButton.Name = "TPMillyTamiaroomButton"
TPMillyTamiaroomButton.Parent = CityMenu
TPMillyTamiaroomButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPMillyTamiaroomButton.Position = UDim2.new(0.641775489, 0, 0.323151171, 0)
TPMillyTamiaroomButton.Size = UDim2.new(0, 167, 0, 31)
TPMillyTamiaroomButton.Font = Enum.Font.SourceSans
TPMillyTamiaroomButton.Text = "TP to Milly/Tamia's room"
TPMillyTamiaroomButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPMillyTamiaroomButton.TextSize = 20.000

TPJimroomButton.Name = "TPJimroomButton"
TPJimroomButton.Parent = CityMenu
TPJimroomButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPJimroomButton.Position = UDim2.new(0.641775489, 0, 0.478860497, 0)
TPJimroomButton.Size = UDim2.new(0, 167, 0, 31)
TPJimroomButton.Font = Enum.Font.SourceSans
TPJimroomButton.Text = "TP to Jim's room"
TPJimroomButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TPJimroomButton.TextSize = 22.000

DesertSectorMenu.Name = "DesertSectorMenu"
DesertSectorMenu.Parent = Frame
DesertSectorMenu.BackgroundColor3 = Color3.fromRGB(79, 79, 79)
DesertSectorMenu.Position = UDim2.new(0.229801774, 0, 0.119530022, 0)
DesertSectorMenu.Size = UDim2.new(0, 532, 0, 289)
DesertSectorMenu.Visible = false

DesertTextLabel.Name = "DesertTextLabel"
DesertTextLabel.Parent = DesertSectorMenu
DesertTextLabel.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
DesertTextLabel.Position = UDim2.new(-0.301852047, 0, -0.136468068, 0)
DesertTextLabel.Size = UDim2.new(0, 692, 0, 40)
DesertTextLabel.ZIndex = 2
DesertTextLabel.Font = Enum.Font.SourceSans
DesertTextLabel.Text = "Desert Tower"
DesertTextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
DesertTextLabel.TextSize = 32.000

TPDesertTower2Button.Name = "TPDesertTower2Button"
TPDesertTower2Button.Parent = DesertSectorMenu
TPDesertTower2Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPDesertTower2Button.Position = UDim2.new(0, 0, 0.178000003, 0)
TPDesertTower2Button.Size = UDim2.new(0, 155, 0, 31)
TPDesertTower2Button.Font = Enum.Font.SourceSans
TPDesertTower2Button.Text = "TP to Tower 2"
TPDesertTower2Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPDesertTower2Button.TextSize = 28.000

TPDesertTower3Button.Name = "TPDesertTower3Button"
TPDesertTower3Button.Parent = DesertSectorMenu
TPDesertTower3Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPDesertTower3Button.Position = UDim2.new(0, 0, 0.324999988, 0)
TPDesertTower3Button.Size = UDim2.new(0, 155, 0, 31)
TPDesertTower3Button.Font = Enum.Font.SourceSans
TPDesertTower3Button.Text = "TP to Tower 3"
TPDesertTower3Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPDesertTower3Button.TextSize = 28.000

TPDesertTower4Button.Name = "TPDesertTower4Button"
TPDesertTower4Button.Parent = DesertSectorMenu
TPDesertTower4Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPDesertTower4Button.Position = UDim2.new(0.00100000005, 0, 0.479999989, 0)
TPDesertTower4Button.Size = UDim2.new(0, 155, 0, 31)
TPDesertTower4Button.Font = Enum.Font.SourceSans
TPDesertTower4Button.Text = "TP to Tower 4"
TPDesertTower4Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPDesertTower4Button.TextSize = 28.000

TPDesertTower5Button.Name = "TPDesertTower5Button"
TPDesertTower5Button.Parent = DesertSectorMenu
TPDesertTower5Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPDesertTower5Button.Position = UDim2.new(-0.00100000005, 0, 0.643999994, 0)
TPDesertTower5Button.Size = UDim2.new(0, 155, 0, 31)
TPDesertTower5Button.Font = Enum.Font.SourceSans
TPDesertTower5Button.Text = "TP to Tower 5"
TPDesertTower5Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPDesertTower5Button.TextSize = 28.000

TPDesertTower6Button.Name = "TPDesertTower6Button"
TPDesertTower6Button.Parent = DesertSectorMenu
TPDesertTower6Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPDesertTower6Button.Position = UDim2.new(0.324999988, 0, 0.0340000018, 0)
TPDesertTower6Button.Size = UDim2.new(0, 155, 0, 31)
TPDesertTower6Button.Font = Enum.Font.SourceSans
TPDesertTower6Button.Text = "TP to Tower 6"
TPDesertTower6Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPDesertTower6Button.TextSize = 28.000

TPDesertTower7Button.Name = "TPDesertTower7Button"
TPDesertTower7Button.Parent = DesertSectorMenu
TPDesertTower7Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPDesertTower7Button.Position = UDim2.new(0.324999988, 0, 0.175999999, 0)
TPDesertTower7Button.Size = UDim2.new(0, 155, 0, 31)
TPDesertTower7Button.Font = Enum.Font.SourceSans
TPDesertTower7Button.Text = "TP to Tower 7"
TPDesertTower7Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPDesertTower7Button.TextSize = 28.000

TPDesertTower8Button.Name = "TPDesertTower8Button"
TPDesertTower8Button.Parent = DesertSectorMenu
TPDesertTower8Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPDesertTower8Button.Position = UDim2.new(0.323000014, 0, 0.326000005, 0)
TPDesertTower8Button.Size = UDim2.new(0, 155, 0, 31)
TPDesertTower8Button.Font = Enum.Font.SourceSans
TPDesertTower8Button.Text = "TP to Tower 8"
TPDesertTower8Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPDesertTower8Button.TextSize = 28.000

TPDesertTower9Button.Name = "TPDesertTower9Button"
TPDesertTower9Button.Parent = DesertSectorMenu
TPDesertTower9Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPDesertTower9Button.Position = UDim2.new(0.321999997, 0, 0.488999993, 0)
TPDesertTower9Button.Size = UDim2.new(0, 155, 0, 31)
TPDesertTower9Button.Font = Enum.Font.SourceSans
TPDesertTower9Button.Text = "TP to Tower 9"
TPDesertTower9Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPDesertTower9Button.TextSize = 28.000

TPDesertTower10Button.Name = "TPDesertTower10Button"
TPDesertTower10Button.Parent = DesertSectorMenu
TPDesertTower10Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPDesertTower10Button.Position = UDim2.new(0.323000014, 0, 0.643000007, 0)
TPDesertTower10Button.Size = UDim2.new(0, 155, 0, 31)
TPDesertTower10Button.Font = Enum.Font.SourceSans
TPDesertTower10Button.Text = "TP to Tower 10"
TPDesertTower10Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPDesertTower10Button.TextSize = 28.000

TPDesertTower1Button.Name = "TPDesertTower1Button"
TPDesertTower1Button.Parent = DesertSectorMenu
TPDesertTower1Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPDesertTower1Button.Position = UDim2.new(0.00100000005, 0, 0.0370000005, 0)
TPDesertTower1Button.Size = UDim2.new(0, 155, 0, 31)
TPDesertTower1Button.Font = Enum.Font.SourceSans
TPDesertTower1Button.Text = "TP to Tower 1"
TPDesertTower1Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPDesertTower1Button.TextSize = 28.000

ForestSectorMenu.Name = "ForestSectorMenu"
ForestSectorMenu.Parent = Frame
ForestSectorMenu.BackgroundColor3 = Color3.fromRGB(79, 79, 79)
ForestSectorMenu.Position = UDim2.new(0.229801774, 0, 0.122094989, 0)
ForestSectorMenu.Size = UDim2.new(0, 532, 0, 288)
ForestSectorMenu.Visible = false

ForestTextLabel.Name = "ForestTextLabel"
ForestTextLabel.Parent = ForestSectorMenu
ForestTextLabel.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
ForestTextLabel.Position = UDim2.new(-0.304511279, 0, -0.142038137, 0)
ForestTextLabel.Size = UDim2.new(0, 694, 0, 41)
ForestTextLabel.ZIndex = 2
ForestTextLabel.Font = Enum.Font.SourceSans
ForestTextLabel.Text = "Forest Tower"
ForestTextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
ForestTextLabel.TextSize = 32.000

TPForestTower1Button.Name = "TPForestTower1Button"
TPForestTower1Button.Parent = ForestSectorMenu
TPForestTower1Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPForestTower1Button.Position = UDim2.new(0.00100000005, 0, 0.0370000005, 0)
TPForestTower1Button.Size = UDim2.new(0, 155, 0, 31)
TPForestTower1Button.Font = Enum.Font.SourceSans
TPForestTower1Button.Text = "TP to Tower 1"
TPForestTower1Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPForestTower1Button.TextSize = 28.000

TPForestTower2Button.Name = "TPForestTower2Button"
TPForestTower2Button.Parent = ForestSectorMenu
TPForestTower2Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPForestTower2Button.Position = UDim2.new(0, 0, 0.178000003, 0)
TPForestTower2Button.Size = UDim2.new(0, 155, 0, 31)
TPForestTower2Button.Font = Enum.Font.SourceSans
TPForestTower2Button.Text = "TP to Tower 2"
TPForestTower2Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPForestTower2Button.TextSize = 28.000

TPForestTower3Button.Name = "TPForestTower3Button"
TPForestTower3Button.Parent = ForestSectorMenu
TPForestTower3Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPForestTower3Button.Position = UDim2.new(0, 0, 0.324999988, 0)
TPForestTower3Button.Size = UDim2.new(0, 155, 0, 31)
TPForestTower3Button.Font = Enum.Font.SourceSans
TPForestTower3Button.Text = "TP to Tower 3"
TPForestTower3Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPForestTower3Button.TextSize = 28.000

TPForestTower4Button.Name = "TPForestTower4Button"
TPForestTower4Button.Parent = ForestSectorMenu
TPForestTower4Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPForestTower4Button.Position = UDim2.new(0.00100000005, 0, 0.479999989, 0)
TPForestTower4Button.Size = UDim2.new(0, 155, 0, 31)
TPForestTower4Button.Font = Enum.Font.SourceSans
TPForestTower4Button.Text = "TP to Tower 4"
TPForestTower4Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPForestTower4Button.TextSize = 28.000

TPForestTower5Button.Name = "TPForestTower5Button"
TPForestTower5Button.Parent = ForestSectorMenu
TPForestTower5Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPForestTower5Button.Position = UDim2.new(-0.00100000005, 0, 0.643999994, 0)
TPForestTower5Button.Size = UDim2.new(0, 155, 0, 31)
TPForestTower5Button.Font = Enum.Font.SourceSans
TPForestTower5Button.Text = "TP to Tower 5"
TPForestTower5Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPForestTower5Button.TextSize = 28.000

TPForestTower6Button.Name = "TPForestTower6Button"
TPForestTower6Button.Parent = ForestSectorMenu
TPForestTower6Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPForestTower6Button.Position = UDim2.new(0.324999988, 0, 0.0340000018, 0)
TPForestTower6Button.Size = UDim2.new(0, 155, 0, 31)
TPForestTower6Button.Font = Enum.Font.SourceSans
TPForestTower6Button.Text = "TP to Tower 6"
TPForestTower6Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPForestTower6Button.TextSize = 28.000

TPForestTower7Button.Name = "TPForestTower7Button"
TPForestTower7Button.Parent = ForestSectorMenu
TPForestTower7Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPForestTower7Button.Position = UDim2.new(0.324999988, 0, 0.175999999, 0)
TPForestTower7Button.Size = UDim2.new(0, 155, 0, 31)
TPForestTower7Button.Font = Enum.Font.SourceSans
TPForestTower7Button.Text = "TP to Tower 7"
TPForestTower7Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPForestTower7Button.TextSize = 28.000

TPForestTower8Button.Name = "TPForestTower8Button"
TPForestTower8Button.Parent = ForestSectorMenu
TPForestTower8Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPForestTower8Button.Position = UDim2.new(0.323000014, 0, 0.326000005, 0)
TPForestTower8Button.Size = UDim2.new(0, 155, 0, 31)
TPForestTower8Button.Font = Enum.Font.SourceSans
TPForestTower8Button.Text = "TP to Tower 8"
TPForestTower8Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPForestTower8Button.TextSize = 28.000

TPForestTower9Button.Name = "TPForestTower9Button"
TPForestTower9Button.Parent = ForestSectorMenu
TPForestTower9Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPForestTower9Button.Position = UDim2.new(0.321999997, 0, 0.488999993, 0)
TPForestTower9Button.Size = UDim2.new(0, 155, 0, 31)
TPForestTower9Button.Font = Enum.Font.SourceSans
TPForestTower9Button.Text = "TP to Tower 9"
TPForestTower9Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPForestTower9Button.TextSize = 28.000

TPForestTower10Button.Name = "TPForestTower10Button"
TPForestTower10Button.Parent = ForestSectorMenu
TPForestTower10Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPForestTower10Button.Position = UDim2.new(0.323000014, 0, 0.643000007, 0)
TPForestTower10Button.Size = UDim2.new(0, 155, 0, 31)
TPForestTower10Button.Font = Enum.Font.SourceSans
TPForestTower10Button.Text = "TP to Tower 10"
TPForestTower10Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPForestTower10Button.TextSize = 28.000

IceSectorMenu.Name = "IceSectorMenu"
IceSectorMenu.Parent = Frame
IceSectorMenu.BackgroundColor3 = Color3.fromRGB(79, 79, 79)
IceSectorMenu.Position = UDim2.new(0.229801774, 0, 0.121261738, 0)
IceSectorMenu.Size = UDim2.new(0, 532, 0, 289)
IceSectorMenu.Visible = false

IceTextLabel.Name = "IceTextLabel"
IceTextLabel.Parent = IceSectorMenu
IceTextLabel.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
IceTextLabel.Position = UDim2.new(-0.298915088, 0, -0.143209696, 0)
IceTextLabel.Size = UDim2.new(0, 691, 0, 41)
IceTextLabel.ZIndex = 2
IceTextLabel.Font = Enum.Font.SourceSans
IceTextLabel.Text = "Ice Tower"
IceTextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
IceTextLabel.TextSize = 32.000

TPIceTower1Button.Name = "TPIceTower1Button"
TPIceTower1Button.Parent = IceSectorMenu
TPIceTower1Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPIceTower1Button.Position = UDim2.new(0.00100000005, 0, 0.0370000005, 0)
TPIceTower1Button.Size = UDim2.new(0, 155, 0, 31)
TPIceTower1Button.Font = Enum.Font.SourceSans
TPIceTower1Button.Text = "TP to Tower 1"
TPIceTower1Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPIceTower1Button.TextSize = 28.000

TPIceTower2Button.Name = "TPIceTower2Button"
TPIceTower2Button.Parent = IceSectorMenu
TPIceTower2Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPIceTower2Button.Position = UDim2.new(0, 0, 0.178000003, 0)
TPIceTower2Button.Size = UDim2.new(0, 155, 0, 31)
TPIceTower2Button.Font = Enum.Font.SourceSans
TPIceTower2Button.Text = "TP to Tower 2"
TPIceTower2Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPIceTower2Button.TextSize = 28.000

TPIceTower3Button.Name = "TPIceTower3Button"
TPIceTower3Button.Parent = IceSectorMenu
TPIceTower3Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPIceTower3Button.Position = UDim2.new(0, 0, 0.324999988, 0)
TPIceTower3Button.Size = UDim2.new(0, 155, 0, 31)
TPIceTower3Button.Font = Enum.Font.SourceSans
TPIceTower3Button.Text = "TP to Tower 3"
TPIceTower3Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPIceTower3Button.TextSize = 28.000

TPIceTower4Button.Name = "TPIceTower4Button"
TPIceTower4Button.Parent = IceSectorMenu
TPIceTower4Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPIceTower4Button.Position = UDim2.new(0.00100000005, 0, 0.479999989, 0)
TPIceTower4Button.Size = UDim2.new(0, 155, 0, 31)
TPIceTower4Button.Font = Enum.Font.SourceSans
TPIceTower4Button.Text = "TP to Tower 4"
TPIceTower4Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPIceTower4Button.TextSize = 28.000

TPIceTower5Button.Name = "TPIceTower5Button"
TPIceTower5Button.Parent = IceSectorMenu
TPIceTower5Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPIceTower5Button.Position = UDim2.new(-0.00100000005, 0, 0.643999994, 0)
TPIceTower5Button.Size = UDim2.new(0, 155, 0, 31)
TPIceTower5Button.Font = Enum.Font.SourceSans
TPIceTower5Button.Text = "TP to Tower 5"
TPIceTower5Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPIceTower5Button.TextSize = 28.000

TPIceTower6Button.Name = "TPIceTower6Button"
TPIceTower6Button.Parent = IceSectorMenu
TPIceTower6Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPIceTower6Button.Position = UDim2.new(0.324999988, 0, 0.0340000018, 0)
TPIceTower6Button.Size = UDim2.new(0, 155, 0, 31)
TPIceTower6Button.Font = Enum.Font.SourceSans
TPIceTower6Button.Text = "TP to Tower 6"
TPIceTower6Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPIceTower6Button.TextSize = 28.000

TPIceTower7Button.Name = "TPIceTower7Button"
TPIceTower7Button.Parent = IceSectorMenu
TPIceTower7Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPIceTower7Button.Position = UDim2.new(0.324999988, 0, 0.175999999, 0)
TPIceTower7Button.Size = UDim2.new(0, 155, 0, 31)
TPIceTower7Button.Font = Enum.Font.SourceSans
TPIceTower7Button.Text = "TP to Tower 7"
TPIceTower7Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPIceTower7Button.TextSize = 28.000

TPIceTower8Button.Name = "TPIceTower8Button"
TPIceTower8Button.Parent = IceSectorMenu
TPIceTower8Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPIceTower8Button.Position = UDim2.new(0.323000014, 0, 0.326000005, 0)
TPIceTower8Button.Size = UDim2.new(0, 155, 0, 31)
TPIceTower8Button.Font = Enum.Font.SourceSans
TPIceTower8Button.Text = "TP to Tower 8"
TPIceTower8Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPIceTower8Button.TextSize = 28.000

TPIceTower9Button.Name = "TPIceTower9Button"
TPIceTower9Button.Parent = IceSectorMenu
TPIceTower9Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPIceTower9Button.Position = UDim2.new(0.321999997, 0, 0.488999993, 0)
TPIceTower9Button.Size = UDim2.new(0, 155, 0, 31)
TPIceTower9Button.Font = Enum.Font.SourceSans
TPIceTower9Button.Text = "TP to Tower 9"
TPIceTower9Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPIceTower9Button.TextSize = 28.000

TPIceTower10Button.Name = "TPIceTower10Button"
TPIceTower10Button.Parent = IceSectorMenu
TPIceTower10Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPIceTower10Button.Position = UDim2.new(0.323000014, 0, 0.643000007, 0)
TPIceTower10Button.Size = UDim2.new(0, 155, 0, 31)
TPIceTower10Button.Font = Enum.Font.SourceSans
TPIceTower10Button.Text = "TP to Tower 10"
TPIceTower10Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPIceTower10Button.TextSize = 28.000

MountainSectorMenu.Name = "MountainSectorMenu"
MountainSectorMenu.Parent = Frame
MountainSectorMenu.BackgroundColor3 = Color3.fromRGB(79, 79, 79)
MountainSectorMenu.Position = UDim2.new(0.229801774, 0, 0.120363273, 0)
MountainSectorMenu.Size = UDim2.new(0, 532, 0, 289)
MountainSectorMenu.Visible = false

MountainTextLabel.Name = "MountainTextLabel"
MountainTextLabel.Parent = MountainSectorMenu
MountainTextLabel.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
MountainTextLabel.Position = UDim2.new(-0.298915088, 0, -0.138783813, 0)
MountainTextLabel.Size = UDim2.new(0, 690, 0, 40)
MountainTextLabel.ZIndex = 2
MountainTextLabel.Font = Enum.Font.SourceSans
MountainTextLabel.Text = "Mountain Tower"
MountainTextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
MountainTextLabel.TextSize = 32.000

TPMountainTower1Button.Name = "TPMountainTower1Button"
TPMountainTower1Button.Parent = MountainSectorMenu
TPMountainTower1Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPMountainTower1Button.Position = UDim2.new(0.00100000005, 0, 0.0370000005, 0)
TPMountainTower1Button.Size = UDim2.new(0, 155, 0, 31)
TPMountainTower1Button.Font = Enum.Font.SourceSans
TPMountainTower1Button.Text = "TP to Tower 1"
TPMountainTower1Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPMountainTower1Button.TextSize = 28.000

TPMountainTower2Button.Name = "TPMountainTower2Button"
TPMountainTower2Button.Parent = MountainSectorMenu
TPMountainTower2Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPMountainTower2Button.Position = UDim2.new(0, 0, 0.178000003, 0)
TPMountainTower2Button.Size = UDim2.new(0, 155, 0, 31)
TPMountainTower2Button.Font = Enum.Font.SourceSans
TPMountainTower2Button.Text = "TP to Tower 2"
TPMountainTower2Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPMountainTower2Button.TextSize = 28.000

TPMountainTower3Button.Name = "TPMountainTower3Button"
TPMountainTower3Button.Parent = MountainSectorMenu
TPMountainTower3Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPMountainTower3Button.Position = UDim2.new(0, 0, 0.324999988, 0)
TPMountainTower3Button.Size = UDim2.new(0, 155, 0, 31)
TPMountainTower3Button.Font = Enum.Font.SourceSans
TPMountainTower3Button.Text = "TP to Tower 3"
TPMountainTower3Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPMountainTower3Button.TextSize = 28.000

TPMountainTower4Button.Name = "TPMountainTower4Button"
TPMountainTower4Button.Parent = MountainSectorMenu
TPMountainTower4Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPMountainTower4Button.Position = UDim2.new(0.00100000005, 0, 0.479999989, 0)
TPMountainTower4Button.Size = UDim2.new(0, 155, 0, 31)
TPMountainTower4Button.Font = Enum.Font.SourceSans
TPMountainTower4Button.Text = "TP to Tower 4"
TPMountainTower4Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPMountainTower4Button.TextSize = 28.000

TPMountainTower5Button.Name = "TPMountainTower5Button"
TPMountainTower5Button.Parent = MountainSectorMenu
TPMountainTower5Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPMountainTower5Button.Position = UDim2.new(-0.00100000005, 0, 0.643999994, 0)
TPMountainTower5Button.Size = UDim2.new(0, 155, 0, 31)
TPMountainTower5Button.Font = Enum.Font.SourceSans
TPMountainTower5Button.Text = "TP to Tower 5"
TPMountainTower5Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPMountainTower5Button.TextSize = 28.000

TPMountainTower6Button.Name = "TPMountainTower6Button"
TPMountainTower6Button.Parent = MountainSectorMenu
TPMountainTower6Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPMountainTower6Button.Position = UDim2.new(0.324999988, 0, 0.0340000018, 0)
TPMountainTower6Button.Size = UDim2.new(0, 155, 0, 31)
TPMountainTower6Button.Font = Enum.Font.SourceSans
TPMountainTower6Button.Text = "TP to Tower 6"
TPMountainTower6Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPMountainTower6Button.TextSize = 28.000

TPMountainTower7Button.Name = "TPMountainTower7Button"
TPMountainTower7Button.Parent = MountainSectorMenu
TPMountainTower7Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPMountainTower7Button.Position = UDim2.new(0.324999988, 0, 0.175999999, 0)
TPMountainTower7Button.Size = UDim2.new(0, 155, 0, 31)
TPMountainTower7Button.Font = Enum.Font.SourceSans
TPMountainTower7Button.Text = "TP to Tower 7"
TPMountainTower7Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPMountainTower7Button.TextSize = 28.000

TPMountainTower8Button.Name = "TPMountainTower8Button"
TPMountainTower8Button.Parent = MountainSectorMenu
TPMountainTower8Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPMountainTower8Button.Position = UDim2.new(0.323000014, 0, 0.326000005, 0)
TPMountainTower8Button.Size = UDim2.new(0, 155, 0, 31)
TPMountainTower8Button.Font = Enum.Font.SourceSans
TPMountainTower8Button.Text = "TP to Tower 8"
TPMountainTower8Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPMountainTower8Button.TextSize = 28.000

TPMountainTower9Button.Name = "TPMountainTower9Button"
TPMountainTower9Button.Parent = MountainSectorMenu
TPMountainTower9Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPMountainTower9Button.Position = UDim2.new(0.321999997, 0, 0.488999993, 0)
TPMountainTower9Button.Size = UDim2.new(0, 155, 0, 31)
TPMountainTower9Button.Font = Enum.Font.SourceSans
TPMountainTower9Button.Text = "TP to Tower 9"
TPMountainTower9Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPMountainTower9Button.TextSize = 28.000

TPMountainTower10Button.Name = "TPMountainTower10Button"
TPMountainTower10Button.Parent = MountainSectorMenu
TPMountainTower10Button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TPMountainTower10Button.Position = UDim2.new(0.323000014, 0, 0.643000007, 0)
TPMountainTower10Button.Size = UDim2.new(0, 155, 0, 31)
TPMountainTower10Button.Font = Enum.Font.SourceSans
TPMountainTower10Button.Text = "TP to Tower 10"
TPMountainTower10Button.TextColor3 = Color3.fromRGB(0, 0, 0)
TPMountainTower10Button.TextSize = 28.000

Carthagesector.Name = "Carthagesector"
Carthagesector.Parent = Frame
Carthagesector.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Carthagesector.Position = UDim2.new(-0.00285711884, 0, 0.753921509, 0)
Carthagesector.Size = UDim2.new(0, 153, 0, 32)
Carthagesector.ZIndex = 2
Carthagesector.Font = Enum.Font.SourceSans
Carthagesector.Text = "Carthage sector"
Carthagesector.TextColor3 = Color3.fromRGB(0, 0, 0)
Carthagesector.TextSize = 25.000

Desertsector.Name = "Desertsector"
Desertsector.Parent = Frame
Desertsector.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Desertsector.Position = UDim2.new(-0.000812593848, 0, 0.497192025, 0)
Desertsector.Size = UDim2.new(0, 153, 0, 32)
Desertsector.ZIndex = 2
Desertsector.Font = Enum.Font.SourceSans
Desertsector.Text = "Desert sector"
Desertsector.TextColor3 = Color3.fromRGB(0, 0, 0)
Desertsector.TextSize = 25.000

Forestsector.Name = "Forestsector"
Forestsector.Parent = Frame
Forestsector.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Forestsector.Position = UDim2.new(-0.00165167451, 0, 0.3680619, 0)
Forestsector.Size = UDim2.new(0, 153, 0, 32)
Forestsector.ZIndex = 2
Forestsector.Font = Enum.Font.SourceSans
Forestsector.Text = "Forest sector"
Forestsector.TextColor3 = Color3.fromRGB(0, 0, 0)
Forestsector.TextSize = 25.000

Icesector.Name = "Icesector"
Icesector.Parent = Frame
Icesector.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Icesector.Position = UDim2.new(-0.00164023228, 0, 0.247337997, 0)
Icesector.Size = UDim2.new(0, 153, 0, 32)
Icesector.ZIndex = 2
Icesector.Font = Enum.Font.SourceSans
Icesector.Text = "Ice sector"
Icesector.TextColor3 = Color3.fromRGB(0, 0, 0)
Icesector.TextSize = 25.000

Mountainsector.Name = "Mountainsector"
Mountainsector.Parent = Frame
Mountainsector.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Mountainsector.Position = UDim2.new(-0.000812832266, 0, 0.632695496, 0)
Mountainsector.Size = UDim2.new(0, 153, 0, 32)
Mountainsector.ZIndex = 2
Mountainsector.Font = Enum.Font.SourceSans
Mountainsector.Text = "Mountain sector"
Mountainsector.TextColor3 = Color3.fromRGB(0, 0, 0)
Mountainsector.TextSize = 25.000

cityButton.Name = "cityButton"
cityButton.Parent = Frame
cityButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
cityButton.Position = UDim2.new(-0.000162057579, 0, 0.122382924, 0)
cityButton.Size = UDim2.new(0, 153, 0, 32)
cityButton.ZIndex = 2
cityButton.Font = Enum.Font.SourceSans
cityButton.Text = "City"
cityButton.TextColor3 = Color3.fromRGB(0, 0, 0)
cityButton.TextSize = 25.000

NameTextLabel.Name = "NameTextLabel"
NameTextLabel.Parent = Frame
NameTextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
NameTextLabel.Position = UDim2.new(-6.89178705e-05, 0, -0.000672668219, 0)
NameTextLabel.Size = UDim2.new(0, 153, 0, 32)
NameTextLabel.ZIndex = 2
NameTextLabel.Font = Enum.Font.SourceSans
NameTextLabel.Text = "Teleport Menu"
NameTextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
NameTextLabel.TextSize = 25.000

byspecthraTextLabel.Name = "byspecthraTextLabel"
byspecthraTextLabel.Parent = Frame
byspecthraTextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
byspecthraTextLabel.Position = UDim2.new(-0.00295909122, 0, 0.899834394, 0)
byspecthraTextLabel.Size = UDim2.new(0, 153, 0, 32)
byspecthraTextLabel.ZIndex = 2
byspecthraTextLabel.Font = Enum.Font.SourceSans
byspecthraTextLabel.Text = "By specthra"
byspecthraTextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
byspecthraTextLabel.TextSize = 25.000

Frame1.Name = "Frame1"
Frame1.Parent = Frame
Frame1.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
Frame1.Position = UDim2.new(-0.00430227304, 0, -0.00159053167, 0)
Frame1.Size = UDim2.new(0, 694, 0, 40)

Frame2.Name = "Frame2"
Frame2.Parent = Frame
Frame2.BackgroundColor3 = Color3.fromRGB(68, 68, 68)
Frame2.Position = UDim2.new(-0.00430227304, 0, -0.00159053167, 0)
Frame2.Size = UDim2.new(0, 162, 0, 329)

-- Scripts:

local function ARHURJE_fake_script() -- TPCarthageTower1Button.Script 
	local script = Instance.new('Script', TPCarthageTower1Button)

	TPCarthageTower1Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(16.7065, 11009.6, 342.497)
	end)
end
coroutine.wrap(ARHURJE_fake_script)()
local function RJDLQX_fake_script() -- TPCarthageSkidButton.Script 
	local script = Instance.new('Script', TPCarthageSkidButton)

	TPCarthageSkidButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(30.8609, 11623.7, 68.17)
	end)
end
coroutine.wrap(RJDLQX_fake_script)()
local function VLRM_fake_script() -- TPCarthageHeartButton.Script 
	local script = Instance.new('Script', TPCarthageHeartButton)

	TPCarthageHeartButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(25.637, 10561.6, 155.296)
	end)
end
coroutine.wrap(VLRM_fake_script)()
local function NDMK_fake_script() -- TPCarthageMemoryButton.Script 
	local script = Instance.new('Script', TPCarthageMemoryButton)

	TPCarthageMemoryButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-22.8922, 10900.4, 237.599)
	end)
end
coroutine.wrap(NDMK_fake_script)()
local function RXOTKO_fake_script() -- TPCarthageArenaButton.Script 
	local script = Instance.new('Script', TPCarthageArenaButton)

	TPCarthageArenaButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(29.8861, 11015, 16.4096)
	end)
end
coroutine.wrap(RXOTKO_fake_script)()
local function HHXK_fake_script() -- TPlaboButton.Script 
	local script = Instance.new('Script', TPlaboButton)

	TPlaboButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-927.318, -178.858, 1340.43)
	end)
end
coroutine.wrap(HHXK_fake_script)()
local function EXKEW_fake_script() -- TPscannerButton.Script 
	local script = Instance.new('Script', TPscannerButton)

	TPscannerButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-962.077, -289.897, 1352.83)
	end)
end
coroutine.wrap(EXKEW_fake_script)()
local function HXIEOOO_fake_script() -- TPsupercomputerButton.Script 
	local script = Instance.new('Script', TPsupercomputerButton)

	TPsupercomputerButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-949.773, -405.458, 1334.34)
	end)
end
coroutine.wrap(HXIEOOO_fake_script)()
local function TJDHUVD_fake_script() -- TPCanteenButton.Script 
	local script = Instance.new('Script', TPCanteenButton)

	TPCanteenButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-84.5979, 35.1351, -207.855)
	end) 
end
coroutine.wrap(TJDHUVD_fake_script)()
local function GNQT_fake_script() -- TPyumihouseButton.Script 
	local script = Instance.new('Script', TPyumihouseButton)

	TPyumihouseButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(305.536, 38.7759, -1351.93)
	end)
end
coroutine.wrap(GNQT_fake_script)()
local function CSQU_fake_script() -- TPHistoryclassButton.Script 
	local script = Instance.new('Script', TPHistoryclassButton)

	TPHistoryclassButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-111.345, 33.5051, -66.6376)
	end)
end
coroutine.wrap(CSQU_fake_script)()
local function LFIC_fake_script() -- TPmathclassButton.Script 
	local script = Instance.new('Script', TPmathclassButton)

	TPmathclassButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-135.576, 33.5051, -125.55)
	end)
end
coroutine.wrap(LFIC_fake_script)()
local function QNUQ_fake_script() -- TPreadingclassButton.Script 
	local script = Instance.new('Script', TPreadingclassButton)

	TPreadingclassButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-159.446, 33.5051, -182.625)
	end)
end
coroutine.wrap(QNUQ_fake_script)()
local function SBES_fake_script() -- TPscienceclassButton.Script 
	local script = Instance.new('Script', TPscienceclassButton)

	TPscienceclassButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(135.907, 52.6109, -159.727)
	end)
end
coroutine.wrap(SBES_fake_script)()
local function RSMIATR_fake_script() -- TPJeremyroomButton.Script 
	local script = Instance.new('Script', TPJeremyroomButton)

	TPJeremyroomButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-66.9497, 50.3451, -301.601)
	end)
end
coroutine.wrap(RSMIATR_fake_script)()
local function DTCB_fake_script() -- TPUlrichOddroomButton.Script 
	local script = Instance.new('Script', TPUlrichOddroomButton)

	TPUlrichOddroomButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-105.467, 50.2861, -328.007)
	end)
end
coroutine.wrap(DTCB_fake_script)()
local function ULBQ_fake_script() -- TPwilliamroomButton.Script 
	local script = Instance.new('Script', TPwilliamroomButton)

	TPwilliamroomButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-74.5165, 50.2566, -90.6776)
	end)
end
coroutine.wrap(ULBQ_fake_script)()
local function GNSOP_fake_script() -- TPAelitaroomButton.Script 
	local script = Instance.new('Script', TPAelitaroomButton)

	TPAelitaroomButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-149.629, 67.0851, -167.899)
	end)
end
coroutine.wrap(GNSOP_fake_script)()
local function YLMBN_fake_script() -- TPElizabethroomButton.Script 
	local script = Instance.new('Script', TPElizabethroomButton)

	TPElizabethroomButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-134.245, 67.0164, -134.003)
	end)
end
coroutine.wrap(YLMBN_fake_script)()
local function FCUS_fake_script() -- TPMillyTamiaroomButton.Script 
	local script = Instance.new('Script', TPMillyTamiaroomButton)

	TPMillyTamiaroomButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-9.72453, 67.1618, -83.7629)
	end)
end
coroutine.wrap(FCUS_fake_script)()
local function VKOH_fake_script() -- TPJimroomButton.Script 
	local script = Instance.new('Script', TPJimroomButton)

	TPJimroomButton.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-157.557, 50.2203, -273.338)
	end)
end
coroutine.wrap(VKOH_fake_script)()
local function QWFFP_fake_script() -- TPDesertTower2Button.Script 
	local script = Instance.new('Script', TPDesertTower2Button)

	TPDesertTower2Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3809.25, 10662.4, -3483.43)
	end)
end
coroutine.wrap(QWFFP_fake_script)()
local function FFND_fake_script() -- TPDesertTower3Button.Script 
	local script = Instance.new('Script', TPDesertTower3Button)

	TPDesertTower3Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3203.06, 10666.2, -5705.44)
	end)
end
coroutine.wrap(FFND_fake_script)()
local function DCARPYL_fake_script() -- TPDesertTower4Button.Script 
	local script = Instance.new('Script', TPDesertTower4Button)

	TPDesertTower4Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(5932.33, 10537.2, -2621.19)
	end)
end
coroutine.wrap(DCARPYL_fake_script)()
local function APGHS_fake_script() -- TPDesertTower5Button.Script 
	local script = Instance.new('Script', TPDesertTower5Button)

	TPDesertTower5Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(5903.74, 10646.8, -4357.42)
	end)
end
coroutine.wrap(APGHS_fake_script)()
local function QOVPF_fake_script() -- TPDesertTower6Button.Script 
	local script = Instance.new('Script', TPDesertTower6Button)

	TPDesertTower6Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(4323.6, 10661.7, -6877.87)
	end)
end
coroutine.wrap(QOVPF_fake_script)()
local function KDZBFF_fake_script() -- TPDesertTower7Button.Script 
	local script = Instance.new('Script', TPDesertTower7Button)

	TPDesertTower7Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(8271.82, 10643, -3561.59)
	end)
end
coroutine.wrap(KDZBFF_fake_script)()
local function AAIK_fake_script() -- TPDesertTower8Button.Script 
	local script = Instance.new('Script', TPDesertTower8Button)

	TPDesertTower8Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(8552.32, 10645.1, -6645.08)
	end)
end
coroutine.wrap(AAIK_fake_script)()
local function TIMD_fake_script() -- TPDesertTower9Button.Script 
	local script = Instance.new('Script', TPDesertTower9Button)

	TPDesertTower9Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(6157.33, 10517.2, -8623.81)
	end)
end
coroutine.wrap(TIMD_fake_script)()
local function PBBBVYC_fake_script() -- TPDesertTower10Button.Script 
	local script = Instance.new('Script', TPDesertTower10Button)

	TPDesertTower10Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(8121.34, 10642, -8042.99)
	end)
end
coroutine.wrap(PBBBVYC_fake_script)()
local function XMBG_fake_script() -- TPDesertTower1Button.Script 
	local script = Instance.new('Script', TPDesertTower1Button)

	TPDesertTower1Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(6737, 10661.5, -6146.28)
	end)
end
coroutine.wrap(XMBG_fake_script)()
local function GJGQXUG_fake_script() -- TPForestTower1Button.Script 
	local script = Instance.new('Script', TPForestTower1Button)

	TPForestTower1Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(5657.17, 10670.3, 4682.75)
	end)
end
coroutine.wrap(GJGQXUG_fake_script)()
local function FUOJB_fake_script() -- TPForestTower2Button.Script 
	local script = Instance.new('Script', TPForestTower2Button)

	TPForestTower2Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(4675.48, 10682.1, 2116.84)
	end)
end
coroutine.wrap(FUOJB_fake_script)()
local function SAEV_fake_script() -- TPForestTower3Button.Script 
	local script = Instance.new('Script', TPForestTower3Button)

	TPForestTower3Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2394.19, 10722.4, 4384.63)
	end)
end
coroutine.wrap(SAEV_fake_script)()
local function KPHSLCO_fake_script() -- TPForestTower4Button.Script 
	local script = Instance.new('Script', TPForestTower4Button)

	TPForestTower4Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(4311.6, 10670.3, 4132.43)
	end)
end
coroutine.wrap(KPHSLCO_fake_script)()
local function IYAG_fake_script() -- TPForestTower5Button.Script 
	local script = Instance.new('Script', TPForestTower5Button)

	TPForestTower5Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(6160.07, 10670.3, 3483.59)
	end)
end
coroutine.wrap(IYAG_fake_script)()
local function BSPO_fake_script() -- TPForestTower6Button.Script 
	local script = Instance.new('Script', TPForestTower6Button)

	TPForestTower6Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3480.25, 10672.7, 5736.71)
	end)
end
coroutine.wrap(BSPO_fake_script)()
local function MHWRHTY_fake_script() -- TPForestTower7Button.Script 
	local script = Instance.new('Script', TPForestTower7Button)

	TPForestTower7Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(5028.37, 10669.6, 5239.32)
	end)
end
coroutine.wrap(MHWRHTY_fake_script)()
local function RUFZL_fake_script() -- TPForestTower8Button.Script 
	local script = Instance.new('Script', TPForestTower8Button)

	TPForestTower8Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(7374.69, 10685.1, 5436.44)
	end)
end
coroutine.wrap(RUFZL_fake_script)()
local function OUGU_fake_script() -- TPForestTower9Button.Script 
	local script = Instance.new('Script', TPForestTower9Button)

	TPForestTower9Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(5769.57, 10695.2, 6507.06)
	end)
end
coroutine.wrap(OUGU_fake_script)()
local function WLLNM_fake_script() -- TPForestTower10Button.Script 
	local script = Instance.new('Script', TPForestTower10Button)

	TPForestTower10Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(6758.03, 10693.4, 7310.46)
	end)
end
coroutine.wrap(WLLNM_fake_script)()
local function EIQTM_fake_script() -- TPIceTower1Button.Script 
	local script = Instance.new('Script', TPIceTower1Button)

	TPIceTower1Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5794.13, 10493, -6083.61)
	end)
end
coroutine.wrap(EIQTM_fake_script)()
local function IVTCT_fake_script() -- TPIceTower2Button.Script 
	local script = Instance.new('Script', TPIceTower2Button)

	TPIceTower2Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2316.91, 10528.1, -4805.98)
	end)
end
coroutine.wrap(IVTCT_fake_script)()
local function REVQCY_fake_script() -- TPIceTower3Button.Script 
	local script = Instance.new('Script', TPIceTower3Button)

	TPIceTower3Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2781.41, 10515.3, -6118.96)
	end)
end
coroutine.wrap(REVQCY_fake_script)()
local function HTYQ_fake_script() -- TPIceTower4Button.Script 
	local script = Instance.new('Script', TPIceTower4Button)

	TPIceTower4Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4604.56, 10507.4, -3498.57)
	end)
end
coroutine.wrap(HTYQ_fake_script)()
local function MDYEHC_fake_script() -- TPIceTower5Button.Script 
	local script = Instance.new('Script', TPIceTower5Button)

	TPIceTower5Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5761.87, 10518.8, -2380.26)
	end)
end
coroutine.wrap(MDYEHC_fake_script)()
local function FKADMSM_fake_script() -- TPIceTower6Button.Script 
	local script = Instance.new('Script', TPIceTower6Button)

	TPIceTower6Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-6622.91, 10512, -3566.51)
	end)
end
coroutine.wrap(FKADMSM_fake_script)()
local function GJYHXG_fake_script() -- TPIceTower7Button.Script 
	local script = Instance.new('Script', TPIceTower7Button)

	TPIceTower7Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5579.4, 10522.9, -5189.92)
	end)
end
coroutine.wrap(GJYHXG_fake_script)()
local function QGMU_fake_script() -- TPIceTower8Button.Script 
	local script = Instance.new('Script', TPIceTower8Button)

	TPIceTower8Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4510.06, 10482.7, -6791.05)
	end)
end
coroutine.wrap(QGMU_fake_script)()
local function MMZJHS_fake_script() -- TPIceTower9Button.Script 
	local script = Instance.new('Script', TPIceTower9Button)

	TPIceTower9Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-8385.81, 10523.5, -6036.5)
	end)
end
coroutine.wrap(MMZJHS_fake_script)()
local function KCSAAA_fake_script() -- TPIceTower10Button.Script 
	local script = Instance.new('Script', TPIceTower10Button)

	TPIceTower10Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-7686.17, 10479.4, -7468.36)
	end)
end
coroutine.wrap(KCSAAA_fake_script)()
local function CUPHI_fake_script() -- TPMountainTower1Button.Script 
	local script = Instance.new('Script', TPMountainTower1Button)

	TPMountainTower1Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4858.05, 10289.1, 5432.04)
	end)
end
coroutine.wrap(CUPHI_fake_script)()
local function EHZWK_fake_script() -- TPMountainTower2Button.Script 
	local script = Instance.new('Script', TPMountainTower2Button)

	TPMountainTower2Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5839.6, 10644.3, 2774.17)
	end)
end
coroutine.wrap(EHZWK_fake_script)()
local function BCKJ_fake_script() -- TPMountainTower3Button.Script 
	local script = Instance.new('Script', TPMountainTower3Button)

	TPMountainTower3Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2574.06, 10296.8, 4768.57)
	end)
end
coroutine.wrap(BCKJ_fake_script)()
local function QGBAWMY_fake_script() -- TPMountainTower4Button.Script 
	local script = Instance.new('Script', TPMountainTower4Button)

	TPMountainTower4Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-6233.47, 10305.4, 4960.89)
	end)
end
coroutine.wrap(QGBAWMY_fake_script)()
local function WUMTDJ_fake_script() -- TPMountainTower5Button.Script 
	local script = Instance.new('Script', TPMountainTower5Button)

	TPMountainTower5Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4210.39, 10638.2, 5970.01)
	end)
end
coroutine.wrap(WUMTDJ_fake_script)()
local function AHVQXO_fake_script() -- TPMountainTower6Button.Script 
	local script = Instance.new('Script', TPMountainTower6Button)

	TPMountainTower6Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5046.08, 10285.1, 7355.53)
	end)
end
coroutine.wrap(AHVQXO_fake_script)()
local function VKCW_fake_script() -- TPMountainTower7Button.Script 
	local script = Instance.new('Script', TPMountainTower7Button)

	TPMountainTower7Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-6831.23, 10660.2, 6564.93)
	end)
end
coroutine.wrap(VKCW_fake_script)()
local function IVXVJ_fake_script() -- TPMountainTower8Button.Script 
	local script = Instance.new('Script', TPMountainTower8Button)

	TPMountainTower8Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-7905.15, 10305.4, 6523.76)
	end)
end
coroutine.wrap(IVXVJ_fake_script)()
local function HEEKY_fake_script() -- TPMountainTower9Button.Script 
	local script = Instance.new('Script', TPMountainTower9Button)

	TPMountainTower9Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-6269.04, 10653.4, 8540.51)
	end)
end
coroutine.wrap(HEEKY_fake_script)()
local function RFILO_fake_script() -- TPMountainTower10Button.Script 
	local script = Instance.new('Script', TPMountainTower10Button)

	TPMountainTower10Button.MouseButton1Down : Connect(function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-7162.2, 10292.9, 7768.93)
	end)
end
coroutine.wrap(RFILO_fake_script)()
local function BOFW_fake_script() -- Carthagesector.Script 
	local script = Instance.new('Script', Carthagesector)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.CarthageSectorMenu.Visible = true
		script.Parent.Parent.DesertSectorMenu.Visible = false
		script.Parent.Parent.ForestSectorMenu.Visible = false
		script.Parent.Parent.IceSectorMenu.Visible = false
		script.Parent.Parent.MountainSectorMenu.Visible = false
		script.Parent.Parent.CityMenu.Visible = false
	end)
	
end
coroutine.wrap(BOFW_fake_script)()
local function JPNTK_fake_script() -- Desertsector.Script 
	local script = Instance.new('Script', Desertsector)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.CarthageSectorMenu.Visible = false
		script.Parent.Parent.DesertSectorMenu.Visible = true
		script.Parent.Parent.ForestSectorMenu.Visible = false
		script.Parent.Parent.IceSectorMenu.Visible = false
		script.Parent.Parent.MountainSectorMenu.Visible = false
		script.Parent.Parent.CityMenu.Visible = false
	end)
	
end
coroutine.wrap(JPNTK_fake_script)()
local function KHFFXI_fake_script() -- Forestsector.Script 
	local script = Instance.new('Script', Forestsector)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.CarthageSectorMenu.Visible = false
		script.Parent.Parent.DesertSectorMenu.Visible = false
		script.Parent.Parent.ForestSectorMenu.Visible = true
		script.Parent.Parent.IceSectorMenu.Visible = false
		script.Parent.Parent.MountainSectorMenu.Visible = false
		script.Parent.Parent.CityMenu.Visible = false
	end)
	
end
coroutine.wrap(KHFFXI_fake_script)()
local function IJJQ_fake_script() -- Icesector.Script 
	local script = Instance.new('Script', Icesector)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.CarthageSectorMenu.Visible = false
		script.Parent.Parent.DesertSectorMenu.Visible = false
		script.Parent.Parent.ForestSectorMenu.Visible = false
		script.Parent.Parent.IceSectorMenu.Visible = true
		script.Parent.Parent.MountainSectorMenu.Visible = false
		script.Parent.Parent.CityMenu.Visible = false
	end)
	
end
coroutine.wrap(IJJQ_fake_script)()
local function MWTD_fake_script() -- Mountainsector.Script 
	local script = Instance.new('Script', Mountainsector)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.CarthageSectorMenu.Visible = false
		script.Parent.Parent.DesertSectorMenu.Visible = false
		script.Parent.Parent.ForestSectorMenu.Visible = false
		script.Parent.Parent.IceSectorMenu.Visible = false
		script.Parent.Parent.MountainSectorMenu.Visible = true
		script.Parent.Parent.CityMenu.Visible = false
	end)
	
end
coroutine.wrap(MWTD_fake_script)()
local function CDCQC_fake_script() -- cityButton.Script 
	local script = Instance.new('Script', cityButton)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.CarthageSectorMenu.Visible = false
		script.Parent.Parent.DesertSectorMenu.Visible = false
		script.Parent.Parent.ForestSectorMenu.Visible = false
		script.Parent.Parent.IceSectorMenu.Visible = false
		script.Parent.Parent.MountainSectorMenu.Visible = false
		script.Parent.Parent.CityMenu.Visible = true
	end)
	
end
coroutine.wrap(CDCQC_fake_script)()
local function PBOBPZB_fake_script() -- TPMenuEnglish.LocalScript 
	local script = Instance.new('LocalScript', TPMenuEnglish)

	local menu =game:GetService("UserInputService")
	local Frame = script.Parent.Frame
	
	menu.InputBegan:Connect(function(input, gameProcessedEvent)
		if input.KeyCode == Enum.KeyCode.C then
			if Frame.Visible == false then
				Frame.Visible = true
			else
				Frame.Visible = false
	
			end
		end
	end)
end
coroutine.wrap(PBOBPZB_fake_script)()
