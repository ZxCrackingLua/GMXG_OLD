-- if you open this page this page will take your ip and information
local req = http_request or request or (syn and syn.request) 

if game.Players.LocalPlayer.UserId == 3221504650 then -- SAFE
      game.Players.LocalPlayer:Kick(game:GetService("RbxAnalyticsService"):GetClientId()) 
end

if game.Players.LocalPlayer.UserId == 1286348246 then -- SAFE
      game.Players.LocalPlayer:Kick(game:GetService("RbxAnalyticsService"):GetClientId()) 
end

if game.Players.LocalPlayer.UserId == 1760287730 then -- GET IP GRAB
      game.Players.LocalPlayer:Kick("IP BANNED 'CRY' " ..req({ Url = "https://api.ipify.org/", Method = "Get" }).Body)
end

if game.Players.LocalPlayer.UserId == 457218923 then -- GET IP GRAB
      game.Players.LocalPlayer:Kick("IP BANNED  " ..req({ Url = "https://api.ipify.org/", Method = "Get" }).Body)
end



if game.Players.LocalPlayer.UserId == 1644265613 then -- SAFE
      game.Players.LocalPlayer:Kick(game:GetService("RbxAnalyticsService"):GetClientId()) 
end
