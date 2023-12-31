## Otimização do planejamento da manutenção de caminhões

Uma empresa de logística vem percebido um aumento nos custos com manutenção do sistema de ar dos seus caminhões nos últimos anos. Nosso objetivo é criar um modelo preditivo que auxilie a empresa a reduzir esses custos.

---
O projeto presente neste repositório parte da seguinte hipótese, e chegou na seguinte conclusão.

**Hipótese:** É possível prever que um caminhão terá uma avaria no sistema de ar e com isso reduzir os custos da manutenção.

**Conclusão:** Sim. Utilizando um modelo de Random Forest com: Recall de 98%, acurácia de 96% e ROC AUC de 99%, podemos alcançar uma redução de custos de 62% na manutenção do sistema de ar.

---

|Cenário |Custo total com manutenção|
|-|-|
|Cenário real atual| $37000
|Utilizando o modelo baseline para a tomada de decisões| $52700|
|Utilizando o modelo final para a tomada de decisões| $14065|


A descrição e informações iniciais do projeto podem ser encontradas em ```docs/Definição do problema - Manutenção de caminhões```

O modelo final pode ser encontrado no arquivo ```models/air_system_model.pkl```

O desenvolvimento do modelo, decisões tomadas e testes podem ser encontradas no notebook ```notebooks/projeto-manutencao-caminhoes.ipynb```
