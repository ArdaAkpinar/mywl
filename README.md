local whitelist = {
    "ItzSwara31",
    "AmacsizAhmet5",
    "Alexnimo2022",
    "Tpsciawain", 
    "252531_werza",
    "ablanidelim",
    "qazztr",
    "31cihasanxd",
    "azemessi3a",
    "madridhayatimolmus", --yarın vericek
    "Zzz_tps2",
    "OyunDelisiYT6",
    "ARDAEda1",
    "tpsciawain", --me
    "harunisteaq9", 
    "EFREWFTEWT" -- giveaway winner
}

if table.find(whitelist, game.Players.LocalPlayer.Name) then
        local id = game.PlaceId
if id == 335760407 or 13762482705 then
game.StarterGui:SetCore("SendNotification",{
			Title = "Loading...";
			Text = "Loading will take some seconds...";
			Duration = 5;
})
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ArdaAkpinar/dragyeni/main/README.md"))()
else
    game.Players.LocalPlayer:Kick("It's not TPS SS!")
end
else
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ArdaAkpinar/kicked1/main/README.md"))();
end
