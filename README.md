# Laboratório-1-Projeto:
***
# AI - 900 Laboratório do curso Microsoft Azure AI Fundamentals
***
Este projeto é um dos laboratório do Bootcamp Microsoft Azure AI Fundamentals, promovido através da parceria entre a Microsoft e a DIO

# Passo a Passo: Desafio do Curso Azure Fundamentals - Trabalhando com Machine Learning na Prática no Azure ML
***
Neste documento, descreverei o passo a passo que segui para enfrentar o desafio proposto no curso Azure Fundamentals, "Trabalhando com Machine Learning na Prática no Azure ML". O desafio envolveu o uso do Azure Machine Learning (Azure ML) para desenvolver e implantar um modelo de machine learning.

# Pré-requisitos:
***
Antes de começar, é necessário garantir que os seguintes pré-requisitos estejam em vigor:

Conta do Azure: É necessário ter uma conta ativa no Microsoft Azure. Caso não tenha, é possível criar uma conta gratuita.

Azure Machine Learning Studio: Acesso ao Azure Machine Learning Studio, onde serão executadas a maioria das etapas do desafio.

Conhecimento Básico de Machine Learning: É útil ter conhecimentos básicos de machine learning e familiaridade com conceitos como conjunto de dados, modelo, treinamento e implantação.

# Detalhes do Experimento:
***

Nome do Experimento: mslearn-bike-rental

Nome do Trabalho: mslearn-bike-automl

Tipo de Trabalho: ML automatizado

Criado por: Waldenise Moraes

Status: Concluído

Duração Total: 20min 56.10s

# Resultados do Experimento:
***

Algoritmos Utilizados: RandomForest, LightGBM, VotingEnsemble

Pré-processadores Utilizados: MaxAbsScaler

Métricas de Desempenho:

Iteração 1: Score = 0.0984

Iteração 2: Score = 0.0936

Iteração 3: Score = 0.0884

ID do Pipeline do Melhor Modelo: b76be6b5846772ee1128c4d415381c1e9fed455e (AutoML_Ensemble)

# Observações e Ações Futuras:
***

Os resultados mostram que o modelo de ensemble (VotingEnsemble) teve o melhor desempenho, com uma pontuação de 0.0884.
Pode ser útil explorar mais detalhadamente o desempenho de cada modelo individual (RandomForest, LightGBM) para entender melhor suas características.

É importante considerar a interpretabilidade do modelo, especialmente se for necessário explicar as previsões para partes interessadas não técnicas.

Deve-se também avaliar se o desempenho do modelo atende aos requisitos específicos do problema de negócios em questão.
Com base nessas informações, é possível refazer análises adicionais e ajustar o modelo conforme necessário para melhorar ainda mais seu desempenho ou adaptá-lo às necessidades específicas do cenário de uso.

# Passos:
***

# 1. Configuração do Ambiente:

1.1. Acessei o Azure Portal utilizando minhas credenciais.

1.2. No portal, naveguei até o Azure Machine Learning Studio.

# 2. Importação do Conjunto de Dados:

2.1. Importei o conjunto de dados fornecido para o Azure ML Studio.

2.2. Explorei os dados para entender sua estrutura e características.

# 3. Pré-processamento dos Dados:

3.1. Realizei tarefas de pré-processamento, como limpeza de dados, preenchimento de valores ausentes e normalização, conforme necessário.

# 4. Escolha do Algoritmo e Treinamento do Modelo:

4.1. Escolhi um algoritmo de machine learning adequado com base na natureza do problema e nos dados disponíveis.

4.2. Dividi os dados em conjuntos de treinamento e teste.

4.3. Treinei o modelo usando o conjunto de treinamento.

# 5. Avaliação do Modelo:

5.1. Avaliei o desempenho do modelo usando métricas relevantes, como precisão, recall, F1-score, etc.

5.2. Ajustei os parâmetros do modelo, se necessário, para melhorar o desempenho.

# 6. Implantação do Modelo:

6.1. Implantei o modelo treinado para que pudesse ser acessado externamente.

6.2. Testei a implantação para garantir que estava funcionando conforme o esperado.

# 7. Monitoramento e Manutenção:

7.1. Estabeleci práticas de monitoramento para acompanhar o desempenho do modelo em produção.

7.2. Realizei ajustes e manutenção conforme necessário para garantir que o modelo continuasse a fornecer resultados precisos.

# Conclusão:
***

Este passo a passo resume as etapas que segui para enfrentar o desafio do curso Azure Fundamentals, "Trabalhando com Machine Learning na Prática no Azure ML". Cada etapa foi cuidadosamente planejada e executada para alcançar os objetivos do desafio, desde a importação e pré-processamento dos dados até a implantação e manutenção do modelo de machine learning.




