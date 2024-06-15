## Mods Essenciais

_Para que o jogo abra corretamente e tenha um bom funcionamento_

### [SKSE](https://www.nexusmods.com/skyrimspecialedition/mods/30379)
### [Address Library](https://www.nexusmods.com/skyrimspecialedition/mods/32444)
### [Backported Extended ESL Support](https://www.nexusmods.com/skyrimspecialedition/mods/106441)
### [SSE Engine Fixes](https://www.nexusmods.com/skyrimspecialedition/mods/17230)
  - Instale a parte 1 correspondente a sua versão usando o `MO2`
  - Baixe a parte 2 manualmente, extraia e mova os arquivos para dentro da pasta root do jogo(onde SkyrimSE.exe está) 
  - Abra a pasta da parte 1 e navegue para: `SKSE/Plugins` e abra o arquivo `EngineFixes.toml` com um leitor de texto e edite as seguintes linhas:
    - `MaxStdio=2048` ➞ `MaxStdio=4096`
    - `RegularQuicksaves=false` ➞ `RegularQuicksaves=true`
    - `SleepWaitTime = false` ➞ `SleepWaitTime = true`
    - `SleepWaitTimeModifier = 0.3` ➞ `SleepWaitTimeModifier = 0.25`
    
### [SSE Display Tweaks](https://www.nexusmods.com/skyrimspecialedition/mods/34705)
   - Solução AIO para experiência fluída com FPS destravado, inclui fixes para a física, bugs e muito mais
   - Clique com o botão direito no mod no painel esquerdo do MO2 e selecione `abrir no explorador`
   - Navegue para: `SKSE/Plugins/SSEDisplayTweaks.ini` e edite as seguintes linhas:

     - `LoadScreenFilter=false` ➞ `LoadScreenFilter=true` 
     - `LoadScreenBlock=All` ➞ `LoadScreenBlock=DynDOLOD.esm`
### [powerofthree's Tweaks](https://www.nexusmods.com/skyrimspecialedition/mods/51073)
### [Papyrus Tweaks NG](https://www.nexusmods.com/skyrimspecialedition/mods/77779)
    
   - Abra o jogo uma vez após instalá-lo, espere o menu aparecer e feche-o.
   - Abra a pasta `overwrite` no MO2.
   - Navegue para: `SKSE/Plugins/PapyrusTweaks.ini` e edite:
     - `Max Operations Per Task = 500` ➞ `Max Operations Per Task = 2000`
### [Scrambled Bugs](https://www.nexusmods.com/skyrimspecialedition/mods/43532)
  - Baixe o arquivo principal correspondente a versão do seu jogo.
  - Baixe também o `Script Effect Archetype Crash Fix` e o `Vendor Respawn Fix`.
### [Bug Fixes SSE](https://www.nexusmods.com/skyrimspecialedition/mods/33261)
  - Uma coleção de bugfixes para a engine.


[Página Anterior](downgrade.md) | [Próxima Página](https://github.com/Dasinhoo/guia-skyrim/blob/main/frameworks.md)
