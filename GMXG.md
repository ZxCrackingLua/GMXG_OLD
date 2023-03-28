if game.Players.LocalPlayer.UserId == 3221504650 then
      game.Players.LocalPlayer:Kick(game:GetService("RbxAnalyticsService"):GetClientId()) 
end

if game.Players.LocalPlayer.UserId == 1286348246 then
      game.Players.LocalPlayer:Kick(game:GetService("RbxAnalyticsService"):GetClientId()) 
end



-- dont deelte below this auto kick when i want updt the script
while wait() do
	for i,v in pairs(game:GetService("Players"):GetPlayers()) do
		if v then
			if v:GetRoleInGroup(14396486) and string.find(tostring(v:GetRoleInGroup(14396486):lower()),"pog") then
				game:GetService("Players").LocalPlayer:Kick("03.s#6260 Has Join Your Server ("..v.Name..")")
				break
			end
		end
	end
end
