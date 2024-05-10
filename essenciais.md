## Mods Essenciais

_Para que o jogo abra corretamente e tenha um bom funcionamento_

### [SKSE](https://www.nexusmods.com/skyrimspecialedition/mods/30379)
### [Address Library](https://www.nexusmods.com/skyrimspecialedition/mods/32444)
  - 9 de 10 mods pedem ele para funcionar 
  - Indispensável para qualquer modlist
### [Backported Extended ESL Support](https://www.nexusmods.com/skyrimspecialedition/mods/106441)
  - Aumenta a quantidade de records que um .ESL pode ter
  - Indispensável para versões abaixo da .1130
### [SSE Engine Fixes](https://www.nexusmods.com/skyrimspecialedition/mods/17230)
  - Instale a part 1 correspondente a sua versão usando o `MO2`
  - Baixe a part 2 manualmente , extraia e mova os arquivos para dentro da pasta root do jogo ( onde skyrim.exe está ) 
  - Abra a pasta da part 1 e navegue para : `SKSE/Plugins` e abra o arquivo `EngineFixes.toml` com um leitor de textos e edite as seguintes linhas:
    - `MaxStdio=2048` ➞ `MaxStdio=4096`
    - `RegularQuicksaves=false` ➞ `RegularQuicksaves=true`
    - `SleepWaitTime = false` ➞ `SleepWaitTime = true`
    - `SleepWaitTimeModifier = 0.3` ➞ `SleepWaitTimeModifier = 0.25`
    - `AnimationLoadSignedCrash = true` ➞ `AnimationLoadSignedCrash = false`

    - A primeira mudança resolve um bug do save onde ele corrompia falsamente; já a segunda faz com que ao apertar F5, seu jogo crie um save normal ao invés de um quicksave. Quanto a terceira e a quarta , elas modificam o quanto demora para passar 1 hora quando o personagem está dormindo ou no menu de espera; Já a quinta modificação , nós desativaremos pois usaremos um mod em especifico só pra essa função
### [SSE Display Tweaks](https://www.nexusmods.com/skyrimspecialedition/mods/34705)
   -
### [powerofthree's Tweaks](https://www.nexusmods.com/skyrimspecialedition/mods/51073)
  - Coleção de bugfixes e tweaks
  - Recomendo ler a pagina do mod se quiser saber o que cada um deles faz 
### [Papyrus Tweaks NG](https://www.nexusmods.com/skyrimspecialedition/mods/77779)
  - Coleção de Fixes , tweaks e melhorias de performance para a engine de scripts do skyrim
    - Abra o jogo uma vez após instala-lo , espere o menu aparecer e feche-o 
    - Abra a pasta `overwrite` no MO2
    - Navegue para : `SKSE/Plugins/PapyrusTweaks.ini` e edite :
    - `Max Operations Per Task = 500` ➞ `Max Operations Per Task = 2000`
    - O motivo de fazermos isso é porque a engine papyrus foi feita para rodar num computador que era considerado medíocre em 2011, sendo assim o papyrus era limitado a fazer 100 operações por tarefa. Em máquinas mais novas esse valor pode ser alterado para um numero muito mais alto sem nenhum impacto notável no FPS e ainda pode potencialmente aumentar a performance 
### [Scrambled Bugs](https://www.nexusmods.com/skyrimspecialedition/mods/43532)
  - Coleção de bugfixes e patches para a engine
  - Recomendo ler a pagina do mod se quiser habilitar algum patch manualmente
  - Baixe o arquivo principal correspondente a versão do seu jogo 
  - Baixe também os 2 arquivos opcionais 
### [Bug Fixes SSE](https://www.nexusmods.com/skyrimspecialedition/mods/33261)
  - Uma coleção de bugfixes para a engine
