# model_fitness
Projeto de predição da rotatividade de clientes de uma academia e criação de estratégias de retenção

Nesse projeto, a rede de academias Model Fitness está desenvolvendo uma estratégia de interação com o cliente baseados em dados analíticos. Um dos problemas mais comuns que academias e outros serviços enfrentam é a rotatividade de clientes. Como você sabe se um cliente não
está mais com você?
Em vez de lutar com a rotatividade, Model Fitness digitalizou uma parte dos perfis dos clientes. Minha tarefa é analisá-los e vir com uma estratégia de retenção de clientes através de Machine Learning.

### Descrição dos Dados:
- Churn — a rotatividade do mês em questão
Campos de dados atuais:

Dados do mês anterior:
- gender
- Near_Location — se o cliente morar ou trabalhar na vizinhança onde a academia está localizada
- Partner — se o usuário for um funcionário de uma companhia parceira (a academia tem empresas parceiras cujos funcionários conseguem descontos; nesses casos, a academia armazena informações sobre clientes de são funcionários)
- Promo_friends — se o cliente originalmente se inscreveu através de uma oferta "traga um amigo" eles normalmente usam o código de promoção do amigo quando pagam pela primeira filiação)
- Phone — se o usuário fornece o seu número de telefone
- age (idade)
- Lifetime — o tempo (em meses) desde a primeira vez que o cliente veio à academia

Dados do log de frequência e compras e dados sobre status de filiação atual:
- Contract_period — 1 mês, 3 meses, 6 meses, ou um ano
- Month_to_end_contract — os meses remanescentes até que o contrato expira
- Group_visits — se o cliente participa de sessões em grupo
- Avg_class_frequency_total — frequência média de idas por semana por toda a vida do cliente
- Avg_class_frequency_current_month — frequência média de visitas por semana durante o mês corrente
- Avg_additional_charges_total — a quantidade total de dinheiro gasto em outros serviços da academia: café, artigos esportivos, cosméticos, massagem, etc.

### Bibliotecas usadas:
- pandas
- matplotlib.pyplot
- seaborn
- sklearn (LogisticRegression, StandardScaler, RandomForestClassifier, train_test_split, sklearn.metrics, KMeans)
- scipy (dendrogram, linkage)
