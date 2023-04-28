local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "pet simulator X", HidePremium = false, lntroText = "Goldenhub", SaveConfig = true, ConfigFolder = "OrionTest"})

local Tab = Window:MakeTab({

	Name = "pet simulator X",	Icon = "rbxassetid://4483345998",

	PremiumOnly = false

})

OrionLib:MakeNotification({

	Name = "",

	Content = "ขอให้สนุก🥰",

	Image = "rbxassetid://4483345998",

	Time = 5

})

Tab:AddButton({

	Name = "Trade scam",

	Callback = function()

      	  55

  	end   

})

OrionLibInit() 

