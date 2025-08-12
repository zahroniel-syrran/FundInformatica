# Comandos básicos do CMD (prompt de comandos do Windows)
digite na pesquisa: CMD e selecione CMD.EXE
uma janela de comandos será exibida.
---
  
Microsoft Windows [versão 10.0.22631.5472]
(c) Microsoft Corporation. Todos os direitos reservados.

C:\Users\EtecVAV>|

Onde: 
  
C: -> repesenta a undiade de armazenamento que está sendo usada, no caso o HD ou SSD.

 `\Users -> é o local onde ficam as pastas de cada usuário cadastrado no Windows.`
 
 `\EtecVAV -> é a pasta do usuário logado.`
 
 `> -> separador`
 
 `| -> cursor intermitente. Indica que está aguardandon comando.` 


---
Para obter informações sobre os comandos, digite:

C:\Users\EtecVAV\>help <enter> 
`<enter> -> significa que você deve pressionar RETURN ou ENTER para enviar o comando.`

ou um comando especifico:

C:\Users\EtecVAV\>help dir \<enter\> 
Será exibido as informações sobre este comando.

--
  
DIR -> exibe os aquivos e pastas gravados

Exemplos:
```
C:\Users\EtecVAV>DIR <enter>
 O volume na unidade C não tem nome.
 O Número de Série do Volume é 9AB1-6ED5

 Pasta de C:\Users\EtecVAV

07/08/2025  15:56    <DIR>          .
08/12/2023  09:23    <DIR>          ..
08/08/2024  13:31    <DIR>          1d
08/12/2023  09:24    <DIR>          Contacts
28/07/2025  11:33    <DIR>          Desktop
30/07/2025  11:14    <DIR>          Documents
07/08/2025  14:56    <DIR>          Downloads
08/12/2023  09:24    <DIR>          Favorites
08/12/2023  09:24    <DIR>          Links
08/12/2023  09:24    <DIR>          Music
08/12/2023  09:27    <DIR>          OneDrive
02/02/2024  10:08    <DIR>          OpenVPN
13/02/2025  17:51               610 p1.por
08/12/2023  09:27    <DIR>          Pictures
08/12/2023  09:24    <DIR>          Saved Games
14/11/2024  07:56    <DIR>          Searches
30/01/2024  11:25    <DIR>          Videos
               1 arquivo(s)            610 bytes
              14 pasta(s)   116.717.400.064 bytes disponíveis
```
Onde:

C:\Users\EtecVAV>DIR \<enter\>
  
\<enter\> -\> significa que você deve pressionar RETURN ou ENTER para enviar o comando.

o DIR pode ser em minusculo, pois o Windows não é case sensitive (não distingue maiusculo de minusculo.
---
08/12/2023  09:27    \<DIR\>          Pictures
08/12/2023  09:27 -> Data e hora da criação ou Alteração. 
<DIR> -> indica que é um Diretório(termo antigo) ou Pasta(termo atual).
Pictures -> nome da pasta.
---
`13/02/2025  17:51               610 p1.por`
    
`OBS: note que não aparece <DIR>, isto significa que é um arquivo (termo antigo) ou Documento(Termo atual).`  
`O documento pode ser uma foto, um vídeo, ...` 

`610 -> é o tamanho do arquivo, ou seja, quanto de espaço ocupa na undiade de armazenamento em Bytes.`

---

  Você pode também especificar a unidade e a pasta, exemplo:

  C:\Users\EtecVAV>dir d:\imagens \<enter\>

---
  C:\Users\EtecVAV>CLS -> apaga a tela.

---
  CD -> muda a pasta atual.

  exemplo:

  C:\Users\EtecVAV>cd Desktop \<enter\> 
  C:\Users\EtecVAV\Desktop>|

  CD ..  -> retorna um nível.

  Exemplo:

  C:\Users\EtecVAV\Desktop>cd .. \<enter\> 
  C:\Users\EtecVAV\>|

---
  
MD ou MKDIR -> criar uma pasta.

  exemplo:
C:\Users\EtecVAV\>mkdir teste \<enter\>

Cria um pasta chamda "teste"

  C:\Users\EtecVAV\>mkdir "Arquivos antigos" <enter>

Para criar pastas que contenham espaço, deve colocar entre "".

  



  


  
