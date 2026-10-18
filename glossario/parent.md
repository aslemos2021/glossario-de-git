---
title: parent
---

# parent

No Git, um parent (ou commit pai) é o commit imediatamente anterior a partir do qual um novo commit foi gerado, formando o histórico do projeto.
A maioria dos commits possui exatamente um parent, enquanto um commit de merge possui dois ou mais parents por unir diferentes ramificações.
Por exemplo, ao executar `git log --oneline`, podes visualizar a sequência de alterações onde cada commit aponta diretamente para o ID do seu parent.
