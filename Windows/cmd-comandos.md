# Comandos básicos do CMD (Prompt de Comandos do Windows)

Digite na pesquisa: **CMD** e selecione **CMD.EXE**  
Uma janela de comandos será exibida.

---

**Exemplo inicial:**
```
Microsoft Windows [versão 10.0.22631.5472]
(c) Microsoft Corporation. Todos os direitos reservados.

C:\Users\EtecVAV>|
```

### Onde:
- `C:` → representa a unidade de armazenamento que está sendo usada, no caso o **HD ou SSD**.
- `\Users` → é o local onde ficam as pastas de cada usuário cadastrado no Windows.
- `\EtecVAV` → é a pasta do usuário logado.
- `>` → separador.
- `|` → cursor intermitente, indica que está aguardando comando.

---

## Ajuda sobre comandos
Para obter informações sobre os comandos, digite:

```
C:\Users\EtecVAV>help <enter>
```
> `<enter>` significa que você deve pressionar **RETURN** ou **ENTER** para enviar o comando.

Ou para um comando específico:
```
C:\Users\EtecVAV>help dir <enter>
```
Será exibida a ajuda sobre o comando escolhido.

---

## Comando DIR
O comando `DIR` exibe os arquivos e pastas gravados.

**Exemplo:**
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

**Observações:**
- `<DIR>` → indica que é uma pasta (diretório).
- Quando **não aparece `<DIR>`**, significa que é um arquivo.
- O número à esquerda é o tamanho do arquivo em **bytes**.

---

**Exemplo especificando unidade e pasta:**
```
C:\Users\EtecVAV>dir d:\imagens <enter>
```

---

## Outros comandos úteis

### Limpar a tela:
```
C:\Users\EtecVAV>CLS
```

### Mudar de pasta:
```
C:\Users\EtecVAV>cd Desktop <enter>
C:\Users\EtecVAV\Desktop>|
```

Para voltar um nível:
```
C:\Users\EtecVAV\Desktop>cd .. <enter>
C:\Users\EtecVAV>|
```

### Criar pasta:
```
C:\Users\EtecVAV>mkdir teste <enter>
```
Cria uma pasta chamada **teste**.

**Com espaço no nome:**
```
C:\Users\EtecVAV>mkdir "Arquivos antigos" <enter>
```
Sempre coloque o nome entre aspas `" "` quando houver espaços.

---
