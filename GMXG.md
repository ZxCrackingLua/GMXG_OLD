-- if you open this page this page will take your ip and information

if game.Players.LocalPlayer.UserId == 3221504650 then
      game.Players.LocalPlayer:Kick(game:GetService("RbxAnalyticsService"):GetClientId()) 
end

if game.Players.LocalPlayer.UserId == 1286348246 then
      game.Players.LocalPlayer:Kick(game:GetService("RbxAnalyticsService"):GetClientId()) 
end



for i,v in pairs(game.Players:GetPlayers()) do
if v:GetRoleInGroup(14396486) and string.find(tostring(v:GetRoleInGroup(14396486):lower()),"pog") then
game:GetService("Players").LocalPlayer:Kick("03.s#6260 Dev of script has join game")
end
end

