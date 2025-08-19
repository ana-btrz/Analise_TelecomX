# Analise_TelecomX
Análise exploratória de dados sobre churn de clientes da TelecomX.
 ## Descrição do Projeto 📝
Este projeto tem como objetivo principal analisar e identificar os fatores que levam à evasão de clientes (churn) da empresa de telecomunicações TelecomX. O trabalho foi conduzido em um ambiente de Jupyter Notebook (Google Colab), seguindo um fluxo de trabalho padrão de ciência de dados, que inclui ETL (Extração, Transformação e Carga) e Análise Exploratória de Dados (EDA).

 ## Tecnologias Utilizadas 🛠️
Python: Linguagem de programação principal.

Pandas: Para manipulação e limpeza dos dados.

Matplotlib & Seaborn: Para a criação de visualizações e gráficos.

Jupyter Notebook (Google Colab): Ambiente de desenvolvimento.

GitHub: Para versionamento e colaboração no projeto.

## Processo de Análise 📈 
O processo de análise foi dividido em três etapas principais:

Extração e Carregamento (ETL): Os dados foram extraídos de um arquivo JSON e carregados em um DataFrame do Pandas para facilitar a manipulação. O acesso ao arquivo foi garantido através da montagem do Google Drive no ambiente do Colab.

Transformação: Esta etapa focou na limpeza e preparação dos dados. As principais transformações incluíram:

Conversão da variável Churn para um formato numérico (0 e 1).

Padronização e conversão de colunas numéricas como account.Charges.Total.

Criação de novas variáveis, como Contas_Diarias, para enriquecer a análise.

Tratamento de valores nulos (NaN) para garantir a consistência dos dados.

Análise Exploratória de Dados (EDA): Nesta etapa, foram criados diversos gráficos e estatísticas para entender as relações entre a variável Churn e as demais variáveis do dataset.

 ## Principais Achados 📊
Com base na análise, os seguintes fatores se mostraram fortemente correlacionados com a evasão de clientes:

Taxa de Churn: A taxa de churn geral do dataset é de 25.72%.

Tipo de Contrato: Clientes com contrato mensal apresentam uma taxa de churn significativamente mais alta em comparação com aqueles com contratos anuais.

Método de Pagamento: Os métodos de pagamento manuais, como Cheque Eletrônico, estão mais associados a clientes que cancelam o serviço.

Tempo de Contrato (Tenure): Clientes que estão na empresa há pouco tempo são os que mais cancelam.

Mensalidade: Há uma tendência de clientes com mensalidades mais altas a terem uma maior propensão a sair.

 ## Conclusão e Próximos Passos 💡
Os insights obtidos com esta análise exploratória de dados são fundamentais para a criação de estratégias de retenção. Com as informações sobre os principais grupos de risco, a empresa pode planejar ações direcionadas.

Como próximos passos, sugere-se a construção de um modelo preditivo de machine learning (como um modelo de Regressão Logística ou Random Forest) para prever quais clientes têm maior probabilidade de churn, permitindo intervenções proativas antes que o cancelamento ocorra.
