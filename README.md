 # Projeto - Previsão de Churn do Banco

[https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction)

# Descrição do problema

 O banco XYZ é uma grande empresa de conta bancaria e está enfrentando um alto índice de cancelamento dos seus cartões e contas. Eles coletaram dados dos usuários, incluindo informações pessoais e sobre o uso do serviço. Neste problema, você pode usar um conjunto de dados do Kaggle que contém informações sobre anúncios on-line de uma empresa.
 
## Tabela Variável
Esta tabela contém informações sobre as variáveis presentes no conjunto de dados.


| Nome da Variável | Descrição da Variável |
| --- | --- |
| CustomerId | O ID do Cliente |
| Surname | O spbrenome do Cliente |
| CreditScore | O credito da conta do cliente |
| Geography | A Região de onde o cliente se habita |
| gender | Sexualidade do cliente |
| Age | Idade do cliente |
| Tenure | O tempo de contrato com o banco |
| Balance | A quantia de cada conta dos Clientes |
| NumOfProducts | O número de especificações do produto |
| Approved_Conversion | O número de conversões após a aprovação do anúncio |
| HasCrCard | Quem tem o cartão de crédito |
| IsActiveMember | O clientes que são ativos no banco |
| EstimatedSalary | Salário estimado dos clientes |
| Exited | O clientes que sairam no mês |


# Ciclo 2

Neste ciclo, foram analisados os dados de serviço e informações dos usuários.

Dados de Serviço:
Algo interessante que nesse banco há dois serviços que mais há contratos, o produto 1 e o produto 2. Onde as pessoas mais contrata.
A maioria dos clientes tem a idade em média dos 30 aos 40.
O produto 1 somente nesse mês rescendeu muita pessoa, que chega a assustar.
O melhor pais para desenvolver o nosso banco é a França, porque a maioria dos nossos clientes estão lá, e o que precisa de desenvolvimento é Alemanha.


O foco do projeto foi mais na predição de quantos clientes irá sair no proximo mês, então,  fiz diversos gráficos demosntrando as idades, local e os serviços.

o que podemos tirar desses gráficos tirando essas informações pessoas ? 

Com os Gráficos vimos que há bastante pessoa que permance anos nesse banco, mantendo uma conexão incrivel.
Também tem os paises e o serviço que é o mais contratado, e em todo os países o serviço que mais se destacaram é o 1 e o 2 logo abaixo.
há mais mulheres saindo do que homens.
e pelo o incrivel que pareça, o produto que deve ser revisado é o 1, porque há uma grande margem de pessoas saindo, contêm mais de 30% de clientes que sairam daquele contrato. 

# ciclo 3 

para concluir o processo, observei as precisões: 

Roc_auc_score = 73,12%
Mean squared error: 0.132
R-squared score: 0.18263090676883786

Os melhores valores que consegui encontrar com XGboost, onde está particulamente bom, com acerto de 73%. Com o teste de 20 clientes ele acerta 16 e ter erro de 4 clientes. O modelo está bom, porém, há como fazer melhoras para o modelo ficar mais eficiente.   
