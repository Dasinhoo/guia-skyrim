## Downgrade Best of Both Worlds para 1.5.97
_Downgrade da versão ***1.6.1170*** para ***1.5.97***, mantendo todo o conteúdo do Creation Club da 1.6.1170 e todo o suporte para mods da 1.5.97_

- Se você possuir a DLC Anniversary Edition do Skyrim, certifique-se que ***todo*** o conteúdo do Creation Club já esteja instalado no seu jogo.
- Pressione Windows + R e digite "steam://open/console" (sem as aspas) - isso abrirá o console do Steam.
- Digite os comandos a seguir ***um por um***; não digite todos juntos e espere que a mensagem `Depot download complete` apareça antes de digitar o próximo.
  
  ```
  download_depot 489830 489832 8702665189575304780
  download_depot 489830 489833 2289561010626853674
  ```
- Quando ambos os downloads estiverem terminados, procure os arquivos na pasta do seu Steam (Normalmente em "C:\Program Files (x86)\Steam\steamapps\content"). Dentro da pasta Content, voc encontrará uma pasta chamada `app_489830`. Dentro dessa pasta haverá outras 2 pastas (`depot_489832` e `depot_489833`).
- Da pasta `depot_489832`, copie para a pasta raiz do seu Skyrim ***somente*** os arquivos `bink2w64.dll` e `steam_api64.dll`.
- Da pasta `depot_489833`, copie o executável do jogo para a pasta raiz do seu Skyrim.
- Parabéns! Com isso, você fez o Downgrade para a 1.5.97.

Nota importante: caso tente abrir seu jogo agora, ele crashará. Você precisa do Backported Extended ESL Support, que terá sua instalação coberta na seção de Mods Essenciais do guia.
