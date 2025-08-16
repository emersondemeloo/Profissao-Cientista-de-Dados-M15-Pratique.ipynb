Análise de Churn de Clientes de Telecomunicações
Visão Geral do Projeto
Este projeto consiste em uma análise exploratória de dados (EDA) com o objetivo de identificar os principais fatores que levam à rotatividade (churn) de clientes de uma empresa de telecomunicações. A análise busca fornecer insights acionáveis que a empresa possa usar para melhorar suas estratégias de retenção de clientes.

Conjunto de Dados
O conjunto de dados, analisetelecon.csv, contém informações detalhadas sobre os clientes, como dados demográficos, serviços contratados, duração do relacionamento, pagamentos e o status de churn.

Variáveis Principais
CUSTOMERID: ID único de cada cliente.

GENDER: Gênero do cliente.

ELDERLY: Se o cliente é idoso (1) ou não (0).

MARRIED: Se o cliente é casado.

DEPENDENTS: Se o cliente tem dependentes.

CLIENT_HOUR: Tempo em meses que o cliente permaneceu na empresa.

PHONESERVICE: Se o cliente tem serviço de telefone.

SERVICO_INTERNET: Tipo de serviço de internet (DSL, Fiber optic ou sem serviço).

TECNICAL_SUPORT: Se o cliente tem serviço de suporte técnico.

CONTRACT_TYPE: Tipo de contrato (Month-to-month, One year, Two year).

PAYMENTMETHOD: Método de pagamento do cliente.

PAYMENT_MONTH: Valor do pagamento mensal.

FULL_PAYMENT: Valor total pago pelo cliente.

CHURN: Variável-alvo. Indica se o cliente saiu ('Yes') ou não ('No').

Metodologia de Análise
O projeto segue uma abordagem estruturada para a análise de dados, incluindo as seguintes etapas:

Análise Univariada: Investigação das distribuições e estatísticas descritivas de cada variável individualmente para entender suas características e identificar anomalias.

Identificação e Tratamento de Outliers: Utilização de boxplots para visualizar e decidir sobre a manutenção ou remoção de valores atípicos.

Análise Bivariada: Exploração das relações entre a variável CHURN e as outras variáveis, usando visualizações para responder a perguntas-chave.

Conclusões: Sumarização dos principais fatores de churn para orientar a tomada de decisões estratégicas.

Principais Insights e Descobertas
Contratos de Curto Prazo: A taxa de churn é significativamente maior para clientes com contratos Month-to-month.

Serviço de Internet: Clientes que utilizam o serviço de Fiber optic têm uma propensão muito maior a sair, o que pode indicar problemas de qualidade ou satisfação.

Suporte Técnico: A ausência de suporte técnico está fortemente correlacionada com uma maior taxa de churn.

Duração do Relacionamento: A maioria dos clientes que saíram da empresa o fizeram nos primeiros meses de serviço.

Método de Pagamento: O método de pagamento Electronic check está associado à maior taxa de churn.

Como Executar o Projeto
Para replicar esta análise, você precisará ter o arquivo analisetelecon.csv e as bibliotecas Python listadas abaixo.

Clone este repositório para o seu ambiente local.

Certifique-se de que você tem as bibliotecas necessárias instaladas. Você pode instalá-las usando o pip:

pip install pandas numpy matplotlib seaborn plotly

Abra o notebook Jupyter Profissao Cientista de Dados M15 Pratique.ipynb e execute as células para ver o passo a passo da análise.

Tecnologias e Bibliotecas
Python

pandas

numpy

matplotlib

seaborn

plotly
