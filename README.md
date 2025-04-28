# GP-HACKER-
GPS OFICIAL-- SCRIPT GP HACKER SUPREMO
-- Criado por: Guerreiro GP

local Players = game:GetService("Players")
local LocalPlayer = Players.LocalPlayer

-- Mensagem quando o script iniciar
print("GP Hacker Supremo iniciou com sucesso! Dominando o Brookhaven!!")

-- Função de aviso
function mandarAviso(mensagem)
    game.StarterGui:SetCore("SendNotification", {
        Title = "GP Hacker Ativo!";
        Text = mensagem;
        Duration = 5;
    })
end

-- Manda uma mensagem para todo mundo
mandarAviso("O GP HACKER chegou no servidor! Preparem-se XDDDD")

-- Aqui você pode colocar mais trollagens:
-- Exemplo: Teleportar para o céu
if LocalPlayer.Character and LocalPlayer.Character:FindFirstChild("HumanoidRootPart") then
    LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0, 1000, 0)
end 
loadstring(game:HttpGet("https://raw.githubusercontent.com/SEUNOME/SEU_REPOSITORIO/main/GP_Super_Script.lua"))()
