# Coasts-UI-Library-Leak
Yes, leaking Coats Hub UI Library, BUT it's obfuscated. Heres the example usage AND the library link (Obfuscated yes ;)

```lua
-- // Example Writtin By Me
------------------------------------------------------------------------------------------------------------------------------------
local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/Scriptian1337/Coasts-UI-Library-Leak/main/Utilities/UI-Library.lua"))()
------------------------------------------------------------------------------------------------------------------------------------
local Window = library:Window("TITLE", "Game")
------------------------------------------------------------------------------------------------------------------------------------
local Tab = Window:Tab("Tab")
------------------------------------------------------------------------------------------------------------------------------------
Tab:Button("Button", function()
    print("Clicked")
end)
------------------------------------------------------------------------------------------------------------------------------------
Tab:Toggle("Toggle", function(state)
    print(state)
end)
------------------------------------------------------------------------------------------------------------------------------------
Tab:Slider("Slider", 1, 100, 1, function(state)
    print(state)
end)
------------------------------------------------------------------------------------------------------------------------------------
Tab:Dropdown("Dropdown", {"Banana", "Strawberry", "Watermelon"}, function(state)
    print(state)
end)
------------------------------------------------------------------------------------------------------------------------------------
Tab:Colorpicker("Colorpicker", Color3.fromRGB(255, 255, 255), function(state)
    print(state)
end)
------------------------------------------------------------------------------------------------------------------------------------
```

https://user-images.githubusercontent.com/110675479/183704700-756d0dea-1403-4484-94e9-64d6314cadad.mp4




