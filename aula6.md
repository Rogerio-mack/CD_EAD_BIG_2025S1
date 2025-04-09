

# Aula 6: GOVERNANÇA, MONITORAMENTO E SEGURANÇA DE DADOS EM BIG DATA

### **Conceitos Chave**
| Tópico                            | Sumário                                                               |
|----------------------------------|-------------------------------------------------------------------------------------|
| **Governança de Dados** ++          | Regras e processos para garantir qualidade, segurança e valor estratégico dos dados. |
| **Monitoramento** +++               | Acompanhamento contínuo dos sistemas para manter desempenho, segurança e conformidade. |
| **Observabilidade** +++           | Capacidade de entender o comportamento interno de sistemas complexos com base em evidências externas. |
| **SRE (Site Reliability Engineering)** + | Abordagem de engenharia para garantir confiabilidade, disponibilidade e desempenho de sistemas. Baseada em princípios de **DevOps**. |
| **SLI, SLO, SLA** +               | Indicadores e contratos de nível de serviço para controle de qualidade e disponibilidade. |

### Pilares da Governança eficaz

* Acessibilidade (Accessibility): Os dados devem ser acessíveis às pessoas autorizadas.
* Integridade (Integrity): Os dados devem ser precisos, consistentes e completos.
* Confidencialidade (Confidentiality): Os dados devem ser protegidos contra acesso não autorizado.
* Disponibilidade (Availability): Os dados devem estar disponíveis quando necessários.
 
### **DAMA Wheel (DMBOK)** Framework

##### Componentes principais da governança (**atenção neste ponto!**)
- **Estratégia**: alinhamento com os objetivos organizacionais.
- **Política**: regras sobre metadados, acesso, segurança, qualidade.
- **Padrões de qualidade**: normas técnicas e arquiteturais.
- **Supervisão (stewardship)**: controle e auditoria de dados.
- **Compliance**: conformidade com legislações e normas.
- **Gestão de questões**: resolução de conflitos e falhas relacionadas a dados.
- **Gestão de projetos**: suporte à evolução de boas práticas.
- **Avaliação de ativos**: valor dos dados para o negócio.

| Área                      | Papel no ecossistema de dados                                            |
|--------------------------|---------------------------------------------------------------------------|
| **Qualidade de Dados**   | Regras de validação, correção e melhoria contínua.                       |
| **Arquitetura de Dados** | Padrões para estrutura, integração e uso dos dados.                      |
| **Segurança de Dados**   | Políticas para garantir privacidade e proteção dos dados.                |
| **Metadados**            | Gerenciamento de significado, origem e uso dos dados.                    |
| **Integração e Interoperabilidade** | Padrões para troca de dados entre sistemas distintos.              |

### Monitoramento vs. Supervisão

* *Uma questão de vocabulário... **Monitoramento** (Acompanhamento contínuo de métricas e eventos) X **Supervisão** (ação ativa de controlar, corrigir e direcionar o sistema, com intervenção humana)

### **Observabilidade**

* É a capacidade de entender o estado interno de um sistema a partir de suas **saídas observáveis**. São 3 os pilares da Observabilidade:
 
| Pilar         | Descrição                                                                 |
|---------------|---------------------------------------------------------------------------|
| **Logs**      | Registros detalhados de eventos e erros do sistema.                       |
| **Métricas**  | Indicadores quantitativos (taxas, tempos, etc.) para análise de desempenho.|
| **Tracing**   | Rastreio completo de eventos ou transações dentro do sistema.             |

### SLI, SLO e SLA

| Termo | Definição |
|------|-----------|
| **SLI (Service Level Indicator)** | Métrica que representa o nível de serviço (ex: tempo de resposta, disponibilidade). |
| **SLO (Service Level Objective)** | Meta desejada para um SLI (ex: 99,9% de uptime mensal). |
| **SLA (Service Level Agreement)** | Acordo formal com clientes, muitas vezes com garantias financeiras. |

#### Exemplos
| Métrica                  | Descrição                                         |
|--------------------------|---------------------------------------------------|
| **Data Freshness**       | % de dados processados em um tempo determinado.  |
| **Data Correctness**     | Taxa de erros ou inconsistências nos dados.       |
| **End-to-End Measures**  | Tempo total de execução de pipelines.            |
| **Latência**             | Tempo entre a requisição e a resposta do sistema.|
| **Uptime**               | Percentual de tempo em que o sistema está ativo. |

A importância depende do tipo de sistema. 

#### Perguntas
1. Qual a diferença entre o Framework DAMA - DMBok e o modelo de referência do NIST?
2. Relacione os Componentes principais da governança segundo o DAMA - DMBok.
3. Explique a diferença entre monitoramento e supervisão no contexto de ecossistemas.
4. Quais são os Pilares da Governança eficaz?
5. O que é e qual função de um repositório de metadados no contexto de governança de dados?
6. Você está implantando um sistema de monitoramento de dados e precisaria identificar automaticamente anomalias e desvios de qualidade. Como você faria isso? (pense em outras disciplinas que viu ao longo do curso).
