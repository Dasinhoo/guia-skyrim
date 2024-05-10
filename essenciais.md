## Mods Essenciais

_Para que o jogo abra corretamente e tenha um bom funcionamento_

- [SKSE](https://www.nexusmods.com/skyrimspecialedition/mods/30379)
- [Address Library](https://www.nexusmods.com/skyrimspecialedition/mods/32444)
- [Backported Extended ESL Support](https://www.nexusmods.com/skyrimspecialedition/mods/106441)
## [SSE Engine Fixes](https://www.nexusmods.com/skyrimspecialedition/mods/17230)
  - Abra a pasta do mod seguindo o caminho : `Data/SKSE/Plugins` e abra o arquivo `EngineFixes.toml` com um leitor de textos e edite as seguintes linhas:
    - `MaxStdio=2048` ➞ `MaxStdio=4096`
    - `RegularQuicksaves=false` ➞ `RegularQuicksaves=true`
    - `SleepWaitTime = false` ➞ `SleepWaitTime = true`
    - `AnimationLoadSignedCrash = true` ➞ `AnimationLoadSignedCrash = false`

    - A primeira mudança resolve um bug do save onde ele corrompia falsamente; já a segunda faz com que ao apertar F5, seu jogo crie um save normal ao invés de um quicksave. Quanto a terceira , ela modifica o quão rapido é um tempo de espera para passar uma hora dormindo ou no menu de espera; Já a quarta modificação , desativaremos pois recomendamos outro mod em especifico para essa função

- [SSE Display Tweaks](https://www.nexusmods.com/skyrimspecialedition/mods/34705)
- [powerofthree's Tweaks](https://www.nexusmods.com/skyrimspecialedition/mods/51073)
- [Papyrus Tweaks NG](https://www.nexusmods.com/skyrimspecialedition/mods/77779)
- [Scrambled Bugs](https://www.nexusmods.com/skyrimspecialedition/mods/43532)
- [Bug Fixes SSE](https://www.nexusmods.com/skyrimspecialedition/mods/33261)
