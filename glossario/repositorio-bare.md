---
title: repositório bare
---
# repositório bare

Um repositório bare no Git é um repositório criado sem uma pasta de trabalho (working tree), contendo apenas a estrutura interna do .git. Ele é utilizado exclusivamente em servidores centrais para receber e distribuir alterações de múltiplos colaboradores via push e fetch. Um exemplo prático é a criação de um repositório central em um servidor utilizando o comando `git init --bare`.