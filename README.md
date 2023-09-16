local YOUHUB = loadstring(game:HttpGet("https://raw.githubusercontent.com/GamingScripter/Kavo-Ui/main/Darkrai%20Ui", true))()

local Library = YOUHUB:Window("YOU HUB","","",Enum.KeyCode.RightControl);

--[[
YOUHUB:Window(
1 = Name Of Your Ui Library (string)
2 = Game Name (You Can Keep This Empty To Get The Current Game Name!) (string)
3 = A Logo If You Have One! (string)
4 = Ui Library Toggle (I'll Not Prefer Touching It) (function)
);
]]

Tab1 = Library:Tab("Main")

--[[
Library:Tab(
1 = Your Tab Name! (string)
)
]]

Tab1:Button("Speed",function()
    print("game.Player")
Local speed = 
Delfeal = true
Minute = 0
Max = 35
(0,35,0)
end)

--[[
Tab1:Button(
1 = Button Name (string)
2 = callback (function)
]]

Tab1:Toggle("Toggle",false,function(value)
print(value)
    end)

--[[
Tab1:Toggle(
1 = name (string)
2 = wether it should be true already or false (bool)
3 = callback (function)
)
]]

Tab1:Slider("Slider",1,100,25,function(value)
        print(value)
    end)

--[[
Tab1:Slider(
1 = Name (string)
2 = Minimum (number)
3 = Maximum (number)
4 = Currently How Much (number)
)
]]

Tab1:Dropdown("Dropdown",{"yo","sus","pro"},function(value)
            print(value)
end)

--[[
Tab1:Dropdown(
1 = Name (string)
2 = Options (table)
)
]]

Tab1:Textbox("Textbox","",true,function(value)
print(value)
end)

--[[
Tab1:Textbox(
1 = Name (string)
2 = Current Text (string)
3 = State (bool)
4 = callback (function)
)
]]


Tab1:Seperator("Seperator")

--[[
Tab1:Seperator(
1 = Name (string)
)
--]]
Tab1:Line()
