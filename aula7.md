# Aula 7 - Ameaças à Segurança em Ecossistemas de Big Data

*   **Segurança da Informação**: Essencial para proteger dados sensíveis contra ciberataques, vazamentos e espionagem.

Os principais pilares da segurança da informação são:

1. Confidencialidade: Garante que as informações sejam acessíveis apenas a pessoas autorizadas. 
2. Integridade: Assegura que as informações sejam precisas, completas e não tenham sido alteradas ou corrompidas. 
3. Disponibilidade: Garante que as informações estejam acessíveis e utilizáveis quando e onde forem necessárias. 
4. Autenticidade: Confirma que as informações são originárias de uma fonte legítima e não foram falsificadas ou alteradas. 
5. Legalidade: Assegura que a proteção das informações esteja em conformidade com as leis e regulamentações aplicáveis. 

Estes pilares são essenciais para garantir que as informações estejam protegidas, acessíveis, precisas e confiáveis. 

--

### **Vulnerabilidades de Privacidade**
*   Vulnerabilidade: Fraqueza em sistemas que pode ser explorada.
*   Anonimização de dados: Técnica para minimizar problemas de privacidade.
*   Criptografia: Cifrar a escrita para torná-la ilegível.
*   Differential Privacy: Inserir dados sintéticos para proteger a privacidade.

### **Controle de Acesso Inadequado**
*   Controle de acesso: Evitar acessos não autorizados a dados sensíveis.
*   Verificação de fator duplo: Mecanismo de segurança adicional (ex: confirmação via e-mail ou app).

### **Ataques de Injeção**
*   Ataques de injeção: Inserir código malicioso em dados processados por uma aplicação.
*   SQL Injection: Exploração de vulnerabilidades em comandos SQL.
*   Cross-Site Scripting (XSS): Injetar scripts maliciosos em páginas web.

### Configurações de Segurança Padrão
*   **Configurações padrão**: Sistemas com configurações conhecidas por hackers.
*   Importância de personalização: Definir novas senhas e critérios de acesso mais seguros.

### **Escalabilidade das Soluções de Segurança**
*   Escalabilidade: Capacidade de expandir sem comprometer integridade e confidencialidade.
*   Medidas robustas: Segmentação de rede, autenticação e criptografia.

### Proteção de Dados em Trânsito e em Repouso
*   Dados em trânsito: Proteção durante a transferência.
*   Dados em repouso: Proteção de dados armazenados.
*   Túneis SSH e APIs: Protocolos para troca segura de arquivos.

### Segurança em Ambientes Multi-Tenancy
*   Multi-tenancy: Compartilhamento de hardware entre várias organizações.
*   Garantia de segurança: Provedores de nuvem garantem segurança dos dados.

### Integridade dos Dados
*   Integridade: Proteção contra bloqueio, manipulação e vazamento de dados.
*   Disaster Recovery Plan: Plano para restaurar a operação normal após incidentes.

### Gerenciamento de Logs e Monitoramento
*   Logs: Monitoramento para prevenção, detecção e resposta a ataques.
*   Análise comportamental: Identificação de atividades anômalas por meio de IA.

### Segurança de Dados Não-Estruturados
*   Dados não-estruturados: Imagens, vídeos e textos que exigem atenção.
*   Riscos: Alvos para malwares e ransomware.

### **Cenário** 
*   **Ameaças cibernéticas estão em evolução constante!**.
*   Plano de Ação para Segurança da Informação... **Pessoas, processos e tecnologia**.
*   Security Development Lifecycle (SDL): Práticas para construir software mais seguro.

### **Exemplo de Segurança em Ecossistemas de Big Data** 
*   IAM (Identity and Access Management): Serviço para conceder acesso granular a recursos.
*   Privilégio mínimo: Ninguém deve ter mais permissões do que o necessário.

### **Tipos de planos de segurança**
*   **DAST (Dynamic Analysis Security Testing):** Testes de Análise Dinâmica de Segurança.
*   **SAST (Static Analysis Security Testing):** Testes de Segurança de Análise Estática.
*   **SDL (Security Development Lifecycle):** Um conjunto de práticas que apoiam a segurança e os requisitos de compliance, ajudando a construir produtos de software mais seguros, reduzindo vulnerabilidades sistêmicas, bem como severidade dos ataques.


## Perguntas e Respostas

1. Um provedor de nuvem pública compartilha recursos humanos e de hardware para organizações diferentes. Isso representa um risco? O que é o risco compartilhado em ambientes de nuvem?
2. Ações do tipo definir requisitos de segurança, definir padrões de criptografia e executar pen-tests são consideradas em que tipo de plano? 
> *...SDL*
3. O que é Envenenamento de dados (Data Poisoning)?
4. Qual a importância da anonimização de dados em um ecossistema de Big Data, e quais técnicas podem ser utilizadas para isso? 
> *...criptografia e "Differential Privacy" (inserir dados sintéticos)*
5. O que é o princípio do privilégio mínimo?
