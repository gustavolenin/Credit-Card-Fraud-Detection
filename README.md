# Credit-Card-Fraud-Detection

![image](https://user-images.githubusercontent.com/69591172/190223805-09250dae-d066-42e0-ac18-aa0856f2757f.png)

## Motivação

### Contexto

É importante que as empresas de cartão de crédito sejam capazes de reconhecer transações fraudulentas de cartão de crédito para que os clientes não sejam cobrados por itens que não compraram.

### Conteúdo 

O conjunto de dados contém transações feitas por cartões de crédito em setembro de 2013 por titulares de cartões europeus.
Este conjunto de dados apresenta transações que ocorreram em dois dias, onde temos 492 fraudes em 284.807 transações. O conjunto de dados é altamente desequilibrado, a classe positiva (fraudes) responde por 0,172% de todas as transações.

Ele contém apenas variáveis de entrada numéricas que são o resultado de uma transformação PCA. Infelizmente, devido a questões de confidencialidade, não foram fornecidos os recursos originais e mais informações básicas sobre os dados. 

As características V1, V2, … V28 são os principais componentes obtidos com PCA, as únicas características que não foram transformadas com PCA são 'Tempo' e 'Valor'. O recurso 'Tempo' contém os segundos decorridos entre cada transação e a primeira transação no conjunto de dados. O recurso 'Valor' é o Valor da transação, esse recurso pode ser usado para aprendizado sensível ao custo dependente de exemplo. O recurso 'Class' é a variável de resposta e assume valor 1 em caso de fraude e 0 caso contrário.

Neste projeto foi desenvolvido um modelo de machine learning utilizando Árvore de Decisão (Decision Tree).
