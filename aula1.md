# Aula 1: Pipelines de Dados

* **Pipelines de Dados**
> Pipelines extraem dados de várias fontes (bancos de dados, APIs, arquivos), limpam e transformam os dados (filtros, anonimização, agregações, junções, dados derivados), entregando em um formato utilizável, *podendo envolver até mesmo processos de Aprendizado de Máquina (treinamento, execução dos modelos etc.)*.

* **Tipos de Pipelines** 
    * **Dados ou Processamento em Lote =** Grandes volumes, processamento em momentos específicos (periódico ou esporádico) que não requer de análise imediata. *Ex. informe de rendimentos, folha de pagamento, fechamento de quartil.*
    * **Dados ou Processamento em Streaming =** Processa dados contínuos e em tempo real (ou *near-real*) que têm necessidade de análise imediata. *Ex. logs de mensagens de acesso e transações comerciais, para a detecção de fraude.* Cada ação é um evento, agrupados em fluxos transmitidos por sistemas de mensagens (brokers). Há risco de perda de mensagens (como são tratadas?).
    * **Dados Interativos =** Em geral, processamento transacional, os dados são tratados em tempo real, em resposta às ações do usuário. *Ex. a execução de transações de compras,  pagamentos e transferências.
 
* **Complexidade de um Pipeline de Dados:** A complexidade varia de acordo com o tamanho dos dados, sua condição, estrutura e o objetivo da análise. Pipelines podem ser simples (extração de uma fonte para um destino) ou complexos (várias etapas interligadas, diferentes sistemas e linguagens de programação).

* **Orquestração de Pipelines de Dados & DAG**
> A complexidade dos Pipelines é muito variável, mas processos mais complexos (várias fontes de dados, geradas em momentos diferentes, várias transformações etc.) requerem automatização, o que em geral envolve:
>> * Gráfico Acíclico Direcionado (DAG), são frequentemente usados para análise e otimização dos processos
>> * Análise de Dependências
>> * Alertas

* **Pipelines em Nuvem ou On-Premise**
> * **Nuvem =** Escalabilidade, flexibilidade e "potencialmente" custos menores.
> * **on-premise =** Maior controle e segurança, custos mais fixos embora com maior investimento inicial.

* [**Exemplo de Pipeline com Python/Pandas**](https://colab.research.google.com/github/Rogerio-mack/CD_EAD_BIG_2025S1/blob/main/a_02_pandaspipe.ipynb)

* **Ferramentas**
> **Apache AirFlow**, DataBricks, Azure Data Factory, AWS Glue, Astera... são alguns dos sistemas que ajudam a gerenciar e automatizar o fluxo de dados. Mas há ainda, muitas outras ferramentas específicas para apoio em cada etapa. Essas, implementam e **orquestram o fluxo** (ver questão 5).

* [**CRISP DM e outros**](https://colab.research.google.com/github/Rogerio-mack/CD_EAD_BIG_2025S1/blob/main/standard_process_for_data_mining.ipynb)

### Questões AULA 1

1. O que melhor explica o processamento de dados em streaming?
2. Relacione benefícios comuns do uso de pipelines em Ciência de Dados? O que não seria um benefício?
3. Crossvalidation, Extrair uma métrica de Acuracidade de um modelo de ML e Exibir uma página Web da posição prevista de vendas para o dia ao final de um pipeline, são consideradas etapas de um pipeline de dados? Discuta.
4. Discuta. Cite uma vantangem e uma desvantagem do uso de ambientes de nuvem para implementar pipelines de dados que não foram discutidas aqui.
5. Uma ferramenta de ETL é uma ferramenta para implementação de pipeline de dados?
