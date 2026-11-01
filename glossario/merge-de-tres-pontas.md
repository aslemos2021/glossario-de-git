---
title: Merge de três pontas
---

# Merge de três pontas

É o jeito padrão de o Git juntar dois branches que ambos receberam commits novos. Ele olha para três commits: o ancestral comum (onde os branches se separaram) e a ponta de cada branch. Compara cada ponta com o ancestral e combina as mudanças, e só há conflito se os dois lados mexeram no mesmo trecho.
Exemplo: estando em `main`, `git merge funcionalidade` cria um commit de merge com dois pais.
