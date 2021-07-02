--[[Made by BioShot 
https://github.com/BioShot

also put this in a local script inside of startgui
]]--
local gui = Instance.new("ScreenGui",game.ReplicatedStorage)
local ADFrame = Instance.new("Frame",gui)

gui.Name = "AD"
gui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

ADFrame.Name = "ADFrame"
ADFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ADFrame.Size = UDim2.new(0, 143, 0, 815)
local adframe=gui.ADFrame
local image=Instance.new("ImageLabel",adframe)
image.Size = adframe.Size
gui.Parent=script.Parent
warn("could expreience issues because this is in beta mode!")
local Ads = {
	ad1=5620394588,
	ad2=54737201,
	ad3=13512558,
	ad4=20025171,
	ad5=4732682335,
}





function createad()																													
	local input=""
	local output=""
	local advalue=math.random(1,5)
	local ad = "ad"..advalue
	if image.Image == "rbxassetid://"..Ads[ad] then
		createad()
		warn("cannot preview ad because it is the same!")

	else
		image.Image ="rbxassetid://"..Ads[ad]
		
	end
end



while true do
	createad()
	wait(6)
end
