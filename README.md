# Limite_de_cr-dito-analise

Este repositório contém código e análises para realizar regressão linear múltipla em um conjunto de dados utilizando as bibliotecas Python pandas, numpy e seaborn. O objetivo é explorar as relações entre várias variáveis independentes e uma variável dependente chamada "LimitedoChequeEspecial", que representa uma métrica financeira específica. A análise busca identificar qual combinação de variáveis independentes melhor prevê a variável dependente.

Começando
Instalação:
Certifique-se de ter o Python e as bibliotecas necessárias (pandas, numpy, seaborn e statsmodels) instaladas. Você pode instalá-las utilizando os seguintes comandos:

bash
Copy code
pip install pandas numpy seaborn statsmodels
Dados:
O conjunto de dados utilizado nesta análise está armazenado em um arquivo Excel chamado "Cópia de Limite_Credito1.xlsx". Garanta que o arquivo esteja disponível no caminho apropriado.

Código:
Os arquivos de código contendo a análise estão presentes neste repositório. O código principal está no arquivo de notebook/script.

Visão Geral do Código
Importação de Bibliotecas:

As bibliotecas necessárias (pandas, numpy, seaborn, statsmodels) são importadas para realizar manipulação de dados, visualização e análise de regressão.
Carregamento dos Dados:

O conjunto de dados é carregado a partir do arquivo Excel "Cópia de Limite_Credito1.xlsx" usando a função pd.read_excel().
Exploração dos Dados:

O método .head() é utilizado para exibir as primeiras linhas do conjunto de dados.
O método .corr() é aplicado para calcular a matriz de correlação do conjunto de dados.
Visualização dos Dados:

Um gráfico de pares é gerado utilizando sns.pairplot() para visualizar as relações entre diferentes variáveis.
Análise de Regressão:

Regressão linear múltipla é realizada utilizando a biblioteca statsmodels.
Três modelos de regressão diferentes são criados para prever a variável dependente "LimitedoChequeEspecial" com base em diferentes combinações de variáveis independentes.
Sumários dos Modelos:

Os modelos de regressão são ajustados usando a função model = smf.ols(), e as estatísticas de resumo são impressas usando print(model.summary()).
Coeficientes do modelo, valores de R-quadrado, valores p e outras estatísticas relevantes são fornecidos nos sumários.
Conclusão
Este projeto foca na análise das relações entre diversas variáveis independentes e a variável dependente "LimitedoChequeEspecial" por meio de regressão linear múltipla. Diferentes modelos com combinações variadas de variáveis independentes foram testados. Os sumários de regressão fornecidos oferecem insights sobre a força e a significância das relações entre as variáveis.

Para mais detalhes e uma compreensão mais profunda da análise, consulte os arquivos de código neste repositório.





