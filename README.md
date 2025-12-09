local Games = loadstring(game:HttpGet("https://raw.githubusercontent.com/NeonFlux-AST/NeonFlux_main/refs/heads/main/README.md"))()

local URL = Games[game.GameId]

if URL then
  loadstring(game:HttpGet(URL))()
end
