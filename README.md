local Games = loadstring(game:HttpGet("https://raw.githubusercontent.com/Astral-Nexus0/main-Nexus/refs/heads/main/README.md"))()

local URL = Games[game.GameId]

if URL then
  loadstring(game:HttpGet(URL))()
end
