# Aula 8 - Produtificação de Dados 

*   **Produto de dados:** Contêiner de dados independente que resolve um problema de negócios ou é monetizado.
> *   (...) 
> *   Desenvolvimento de produtos de dados
> *   Monetização de dados
> *   (...)
> *   **DaaP** (Data as a Product) e **DaaS** (Data as a Service)

#### Exemplos 

**1. Painel de Controle de Desempenho de Vendas (Focado em Integração em Processos de Decisão)**

*   Uma empresa de varejo coleta dados de vendas de diversas fontes (lojas físicas, e-commerce, aplicativos móveis).
*   **Produto de Dados:** Um painel interativo que consolida esses dados em métricas-chave como Vendas por loja, região, produto, período; Taxa de conversão online e offline; 
Custo de aquisição de clientes (CAC); Valor do tempo de vida do cliente (LTV).

**2. API de Recomendação de Produtos (para Monetização)**

*   Um site de e-commerce coleta dados sobre o histórico de navegação, compras e avaliações dos clientes.
*   **Produto de Dados:** Uma API que recebe como entrada o ID de um cliente e retorna uma lista de produtos recomendados, com base em Itens que o cliente visualizou recentemente;
Produtos comprados por clientes similares; Tendências gerais de vendas.

### Data Quantum
*   **Data quantum:** Unidade que controla e encapsula todos os componentes para compartilhar dados como um produto.
*   (+) Autodescrição, interoperabilidade, descoberta, atributos de qualidade, segurança e observabilidade; flexibilidade para automatizar tarefas repetitivas.

### **ML Ops** 

> Automação de DevOps aplicada ao aprendizado de máquina.
 
### Arquitetura de Referência para ML Ops
*   Ciclo de vida: Processo iterativo que herda características do DevOps.
*   Pipeline: Ingestão, Desenvolvimento de modelo, Treino e Validação, Model Serving Development, Model Serving Pipeline, Monitoramento da Produção... *CRISP DM novamente???*
*   Model Drift: Mudança no desempenho de um modelo ao longo do tempo.

### Produtificação de LLM (Large Language Models)

#### **Perguntas**

1. Discuta os objetivos da automação de DevOps no contexto da Engenharia de Dados e Ciência de Dados.
2. O que inclui um processo de MLOps? (Pense nos modelos)
> *Versionamento e monitoramento dos modelos, dependências de software, (...)*
3. Quais as diferenças entre DaaP e DaaS, e quais as vantagens de cada um na entrega de dados aos clientes?
> DaaP entrega um dataset em arquivo, dando ao cliente o controle total sobre os dados. 
DaaS disponibiliza os dados através de uma camada lógica de gerenciamento, oferecendo um serviço contínuo. 
DaaP oferece transparência e padronização, enquanto DaaS permite soluções personalizadas e um ROI potencialmente maior.
4. Como o conceito de "data quantum" contribui para a flexibilidade e autonomia dos consumidores de dados?
