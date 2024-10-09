local function StartDialog(DialogName)
  local ReplicatedStorage = game:GetService("ReplicatedStorage")
  local DialogueController = require(ReplicatedStorage.DialogueController)
  local DialoguesList = require(ReplicatedStorage.DialoguesList)
  
  for Index,Dialog in pairs(DialoguesList) do
    if tostring(Index) == DialogName then
      DialogueController.Start(DialogueController, Dialog)
    end
  end
end

StartDialog("AngelQuest1") -- 1, 9
