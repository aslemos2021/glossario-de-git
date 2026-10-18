---
title: upstream
---

# upstream

O termo **upstream** no Git refere-se ao repositório ou branch original que serve como fonte principal para o seu repositório local ou para o seu *fork*. Ele representa o destino primário de onde você baixa as atualizações da comunidade e para o qual envia suas contribuições. Por exemplo, ao colaborar em um projeto de código aberto, você usa o comando `git fetch upstream` para puxar as últimas alterações do repositório oficial e manter seu trabalho atualizado.

---

### Exemplo prático de fluxo com `upstream`:

1. **Adicionar o repositório original como remoto:**
```
git remote add upstream https://github.com/dono-original/projeto.git

```


2. **Buscar e mesclar as atualizações mais recentes do projeto oficial:**
```
git fetch upstream
git checkout main
git merge upstream/main

```


3. **Vincular sua branch local ao enviar pela primeira vez (`-u` / `--set-upstream`):**
```
git push -u origin minha-branch
