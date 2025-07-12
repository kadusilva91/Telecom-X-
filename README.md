# Análise de Evasão de Clientes (Churn) - Telecom X

## 📊 Visão Geral do Projeto

Este repositório contém um projeto de Análise Exploratória de Dados (EDA) focado na identificação dos fatores que contribuem para a evasão de clientes (churn) em uma empresa de telecomunicações fictícia, a "Telecom X". O objetivo principal é transformar dados brutos em insights acionáveis que possam auxiliar a empresa a desenvolver estratégias mais eficazes de retenção de clientes.

## 🚀 Objetivo

* **Coletar e tratar** um conjunto de dados brutos de clientes da Telecom X.
* **Realizar uma Análise Exploratória de Dados (EDA)** detalhada para descobrir padrões, tendências e correlações entre as características dos clientes e o status de evasão.
* **Identificar os principais fatores de risco** que levam os clientes a cancelar o serviço.
* **Fornecer recomendações** baseadas em dados para mitigar a evasão de clientes.

## 🔍 Conjunto de Dados

O conjunto de dados utilizado, `TelecomX_Data.json`, contém informações abrangentes sobre clientes, incluindo:

* **Dados do Cliente:** Gênero, idade (idoso), se possui parceiro ou dependentes, tempo de permanência (tenure).
* **Serviços Contratados:** Serviço telefônico (linhas múltiplas), serviço de internet (tipo, segurança online, backup, proteção de dispositivo, suporte técnico, streaming de TV e filmes).
* **Informações da Conta:** Tipo de contrato, cobrança sem papel, método de pagamento, e valores de cobrança (mensal e total).
* **Status de Evasão (Churn):** Se o cliente cancelou o serviço ou não (variável alvo).

## 🛠️ Tecnologias e Bibliotecas Utilizadas

O projeto foi desenvolvido em ambiente Google Colab (Jupyter Notebook) utilizando as seguintes bibliotecas Python:

* `pandas`: Para manipulação e análise de dados.
* `numpy`: Para operações numéricas de alto desempenho.
* `matplotlib.pyplot`: Para a criação de gráficos estáticos e personalização de visualizações.
* `seaborn`: Para a criação de gráficos estatísticos mais avançados e esteticamente agradáveis.

## 📈 Análises Realizadas e Insights Chave

O notebook `telecomx_(1).ipynb` detalha todas as etapas da análise, desde o carregamento e pré-processamento dos dados até a geração de visualizações e conclusões.

Alguns dos insights preliminares e análises abordadas incluem:

1.  **Distribuição da Evasão:** Visualização da proporção de clientes que cancelaram o serviço versus os que permaneceram.
2.  **Tempo de Permanência vs. Evasão:** Clientes com menor tempo de permanência tendem a ter uma propensão maior ao cancelamento.
3.  **Total Gasto vs. Evasão:** Clientes que cancelam geralmente possuem um total gasto acumulado menor, indicando que a evasão ocorre mais cedo na jornada do cliente.
4.  **Forma de Pagamento vs. Evasão:** Há uma correlação notável entre o método de pagamento e a taxa de evasão, sendo o **Débito Eletrônico (Electronic Check)** uma forma de pagamento associada a uma maior propensão ao cancelamento.
5.  **Serviços de Internet e Telefone:** Análise da influência de serviços como segurança online, suporte técnico, múltiplas linhas, e tipos de internet na decisão de cancelar.
6.  **Tipo de Contrato:** Contratos de mês-a-mês tendem a ter uma taxa de evasão significativamente mais alta em comparação com contratos de longo prazo (um ou dois anos).

## 🚀 Como Visualizar/Executar o Projeto

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/SeuUsuario/Analise_Evasao_Clientes_TelecomX.git](https://github.com/SeuUsuario/Analise_Evasao_Clientes_TelecomX.git)
    cd Analise_Evasao_Clientes_TelecomX
    ```
    (Lembre-se de substituir `SeuUsuario` pelo seu nome de usuário do GitHub).

2.  **Abra no Google Colab:**
    * Vá para [colab.research.google.com](https://colab.research.google.com/).
    * Clique em "Arquivo" > "Abrir notebook".
    * Na aba "GitHub", procure pelo seu repositório e selecione o notebook `telecomx_(1).ipynb`.
    * Alternativamente, se você tem o arquivo `TelecomX_Data.json` e o `telecomx_(1).ipynb` já no seu Google Drive, pode abri-los diretamente de lá.

3.  **Execute as células:** Execute as células de código sequencialmente para replicar a análise e os gráficos.

## 💡 Conclusões e Recomendações (Exemplos)

A análise aprofundada nos dados da Telecom X aponta para a necessidade de focar em:

* **Estratégias de Fidelização:** Incentivar a adesão a contratos de longo prazo (1 ou 2 anos) através de descontos ou benefícios exclusivos.
* **Onboarding Otimizado:** Criar programas de engajamento nos primeiros meses de serviço, que é o período mais crítico para a evasão.
* **Gestão de Pagamentos:** Desenvolver campanhas para migrar clientes do débito eletrônico para métodos de pagamento automático com menor taxa de evasão.
* **Valor Agregado:** Destacar e talvez oferecer pacotes com serviços de segurança e suporte técnico, que parecem estar associados a uma maior retenção.


---
