# <img src="WhatSheet.png" width="350">
🤖 Bot de WhatsApp integrado com planilhas .xlsx e banco SQL, feito com a biblioteca Baileys.

## ⚙️ Funcionalidades
- Responde baseado em menu criado a partir de planilhas Excel .xlsx (aceita fórmulas).
- Pesquisa valores em planilha Excel .xlsx na coluna A, retornando o valor da coluna B.
- Planilhas podem ser mantidas sincronizadas via Google Drive/Onedrive para dados atualizados.
- Pesquisa valores em banco SQL para responder sobre status de produtos.
- Delay aleatório + status "digitando..." para evitar banimento.
- Bloqueio de entradas não-texto (áudio, imagem, vídeo, ligação).

## 💻 Como usar
1. Instale Node.js (versão LTS).
2. Instale dependências:
   ```bash
   npm install @whiskeysockets/baileys mysql2 sqlite3 xlsx
3. Configure suas planilhas e banco de dados:
   Ex: Menu.xlsx  Status.xlsx
5. Rode o bot:
   ```bash
   node index.js
6. Escaneie o Qr-code gerado com o celular para vincular novo dispositivo "Whatsapp Web";
7. Veja ele responder seus clientes!
