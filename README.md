local player = game.Players.LocalPlayer 
local AllowedPlayers = {'DojExperience','raddelton_police','TXREAM','Name','TiffanyPeterson61'}

for i = 1, #AllowedPlayers do
	if player.Name == AllowedPlayers[i] then
		script.Parent.Text = "Owners"
		script.Parent.rankimage.Image = "rbxassetid://6022668935"
	end
end
