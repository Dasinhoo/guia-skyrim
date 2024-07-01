## Mods Essenciais

_Para que o jogo abra corretamente e tenha um bom funcionamento_

### [SKSE](https://www.nexusmods.com/skyrimspecialedition/mods/30379)
  - Para o Skyrim 1.6.1170: Versão 2.2.6
  - Para o Skyrim 1.5.97: Versão 2.0.20
  - Extraia do arquivo `.exe` e quaisquer arquivos `.dll` presentes no arquivo para a pasta do jogo (onde se encontra o execurtável `SkyrimSE.exe`)
  - Instale o arquivo pelo Mod Organizer e defina a pasta `Data` como diretório de data, de forma que na estrutura do mod reste somente os scripts.
### [Address Library](https://www.nexusmods.com/skyrimspecialedition/mods/32444)
  - Para o Skyrim 1.6.1170: segundo Main File `(Anniversary Edition)`
  - Para o Skyrim 1.5.97: primeiro Main File `(Special Edition)`
  - Possui arquivos de base de dados que referenciam endereços de memória do jogo, permitindo que um plugin do SKSE funcione em mais de uma versão sem precisar ser recompilado.
### [Backported Extended ESL Support](https://www.nexusmods.com/skyrimspecialedition/mods/106441)
  - Faz com que mods feitos com o header 1.71 - introduzido na versão 1.6.1130 - funcionem em versões 1.6.640 e abaixo.
  - Logicamente, se você usa ou a 1.6.1130 ou qualquer versão acima dela, você ***não*** precisa desse mod.
### [SSE Engine Fixes](https://www.nexusmods.com/skyrimspecialedition/mods/17230)
  - Instale a parte 1 correspondente a sua versão usando o `MO2`:
    - Para o Skyrim 1.6.1170: segundo Main File `(Part 1) SSE Engine Fixes for 1.6.1170 and newer`
    - Para o Skyrim 1.5.97: `(Part 1) SSE Engine Fixes for 1.5.39 - 1.5.97`
  - Baixe a parte 2 manualmente, extraia e mova os arquivos para dentro da pasta root do jogo (onde SkyrimSE.exe está) ;
  - Abra a pasta da parte 1 e navegue para: `SKSE/Plugins` e abra o arquivo `EngineFixes.toml` com um leitor de texto e edite as seguintes linhas:
    - `MaxStdio=2048` ➞ `MaxStdio=8192`
    - `RegularQuicksaves=false` ➞ `RegularQuicksaves=true`
    - `SleepWaitTime = false` ➞ `SleepWaitTime = true`
    - `SleepWaitTimeModifier = 0.3` ➞ `SleepWaitTimeModifier = 0.25`
    
### [SSE Display Tweaks](https://www.nexusmods.com/skyrimspecialedition/mods/34705)
   - Solução para experiência fluída com FPS destravado, inclui fixes para a física, bugs e muito mais.
   - Clique com o botão direito no mod no painel esquerdo do MO2 e selecione `abrir no explorador`
   - Navegue para: `SKSE/Plugins/SSEDisplayTweaks.ini` e edite as seguintes linhas:

     - `LoadScreenFilter=false` ➞ `LoadScreenFilter=true` 
     - `LoadScreenBlock=All` ➞ `LoadScreenBlock=DynDOLOD.esm`
### [powerofthree's Tweaks](https://www.nexusmods.com/skyrimspecialedition/mods/51073)
  - Abra o jogo uma vez após instalá-lo, espere o menu aparecer e feche-o.
  - Abra a pasta `overwrite` no MO2.
  - Navegue para: `SKSE/Plugins/po3_Tweaks.ini` e edite:
    - Dynamic Snow Material: `false` ➞ `true`
    - Fast RandomInt(): `false` ➞ `true`
    - Fast RandomFloat(): `false` ➞ `true`
    - Clean Orphaned ActiveEffects: `false` ➞ `true`
### [Papyrus Tweaks NG](https://www.nexusmods.com/skyrimspecialedition/mods/77779)
  - Abra o jogo uma vez após instalá-lo, espere o menu aparecer e feche-o.
  - Abra a pasta `overwrite` no MO2.
  - Navegue para: `SKSE/Plugins/PapyrusTweaks.ini` e edite:
    - iMaxOpsPerFrame: `500` ➞ `2000`
### [Scrambled Bugs](https://www.nexusmods.com/skyrimspecialedition/mods/43532)
  - Baixe o arquivo principal correspondente a versão do seu jogo:
    - Para Skyrim 1.6.1170: `Scrambled Bugs - Anniversary Edition (1.6.629.0 and later)`
    - Para Skyrim 1.5.97: `Scrambled Bugs - Special Edition (1.5.97.0 and earlier)`
  - Baixe também o `Script Effect Archetype Crash Fix` e o `Vendor Respawn Fix`.
### [Bug Fixes SSE](https://www.nexusmods.com/skyrimspecialedition/mods/33261)
  - Sobre versões, o esquema é o mesmo:
    - Para Skyrim 1.6.1170: `Bug Fixes SSE - Anniversary Edition (1.6.629.0 and later)`
    - Para Skyrim 1.5.97: `Bug Fixes SSE - Special Edition (1.5.97.0 and earlier)`
  - Uma coleção de bug fixes para a engine.
### [Unofficial Skyrim Special Edition Patch (USSEP)](https://www.nexusmods.com/skyrimspecialedition/mods/266)
  - O principal mod para arrumar bugs do jogo.
  - O Arquivo Principal mais recente funcionará em todas as versões, por mais que o LOOT avise que só é compatível com a versão mais recente do jogo.
### [Unofficial Skyrim Creation Club Content Patches (USCCCP)](https://www.nexusmods.com/skyrimspecialedition/mods/18975)
  - Corrige bugs do conteúdo do Creation Club;
  - Corrige conflitos do Creation Club com o USSEP (Unofficial Skyrim Special Edition Patch).
### [Sunder and Wraithguard - Editable Vault Cell](https://www.nexusmods.com/skyrimspecialedition/mods/59083)
  - Corrige um bug com arquivos marcados como ESL, no qual células criadas nele não conseguem ser editadas.
### [Myrwatch - Editable Home Cells](https://www.nexusmods.com/skyrimspecialedition/mods/64108)
  - É o mesmo caso do Sunder and Wraithguard.
### [Ultimate Optimized Scripts Compilation](https://www.nexusmods.com/skyrimspecialedition/mods/122999)
  - Otimiza scripts do jogo base para que sejam mais eficientes.
### [Scripts Carefully Reworked Optimized and Tactfully Enhanced (SCROTE)](https://www.nexusmods.com/skyrimspecialedition/mods/97155)
  - Mais otimizações de scripts. Carregue ***sempre*** depois do mod acima.

[Página Anterior](downgrade.md) | [Próxima Página](frameworks.md)
