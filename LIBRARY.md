# Theme stuffs
```
getgenv().LibTheme = {
    MainColor = Color3.fromRGB(35,35,40);
    BrighterMainColor = Color3.fromRGB(40,40,45);
    IconsColor = Color3.fromRGB(100,100,120);
    Accent = Color3.fromRGB(0,100,255);
    DarkText = Color3.fromRGB(170,170,170);
    BrightText = Color3.fromRGB(145,145,145);
    Font = "Gotham";
    SoundVolume = 0.5;
    HideKey = "LeftAlt"
}

local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/Eradate/Oceri/main/file%20(8).txt"))()
```
# Creating The Title And Main Lib
```
local Main = Library.Main("Ocerium")
```
# The Page
```
local Page = Main.Page("Page","3926305904",Vector2.new(924, 204),Vector2.new(36, 36))
```
# Sections

```
local Section = Page.Section("Section")
```
# Toggles
```
local Toggle = Section.Component("Toggle","Toggle Name",function(bool)
  
end,false)
```
# Dropdowns
```
local Dropdown = Section.Component("Dropdown","Dropdown Name",table,false,function(string,bool)

end,false)
```
# Slider
```
local Slider = Section.Component("Slider","Slider Name",0,100,false,function(value)

end,50)
```
# Button
```
local Button = Section.Component("Button","Button Name",function()

end)
```
# Paragraphs Logs Etc.
```
local Paragraph = Section.Component("Card", "Title", "Text here")

local Logs = Main.Logs("Logs name")

local log1 = Logs.LogWithButtons("smh")
```
# Button
```
local logbutton = log1.Button("something",function()

end)
```
