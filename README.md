-- BrunoEdition Script Loader
-- Script adaptado por Bruno Candal da Silva

local success, err = pcall(function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/BrunoCandal/SavannahLife-BrunoEdition/main/SavannahLifeBruno.lua"))()
end)

if not success then
    warn("Erro ao carregar o script BrunoEdition:", err)
else
    print("Script BrunoEdition carregado com sucesso!")
end
