
# Aurora Library

A roblox script library for exploiters to make scripts

## Example

```lua Script
loadstring(game:HttpGet("https://raw.githubusercontent.com/imaaan00bb/Aurora-LIB/refs/heads/main/code"))()
local GUI = require(game.ReplicatedStorage.GUI)

-- Create a GUI
local myGUI = GUI:CreateGUI("My Custom GUI")

-- Add a Tab to the GUI
local tab1 = GUI:AddTab(myGUI, "Main Tab")

-- Add a Button to Tab 1
GUI:AddButton(tab1, "Click Me", function()
    print("Button clicked!")
end)

-- Add a Slider to Tab 1
GUI:AddSlider(tab1, "Speed", 0, 100, 50, function(value)
    print("Slider value: " .. value)
end)

-- Add a Toggle to Tab 1
GUI:AddToggle(tab1, "Enable Feature", false, function(isOn)
    print("Feature Enabled: " .. tostring(isOn))
end)

``` 
