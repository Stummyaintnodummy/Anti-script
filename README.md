# Anti-script
game:GetService("GuiService").MenuOpened:Connect(function()
    game:GetService("TeleportService"):Teleport(game.PlaceId, game.Players.LocalPlayer)
end)


