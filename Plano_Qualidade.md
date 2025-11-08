# PLANO DE GERENCIAMENTO DA QUALIDADE

**Nome do Projeto:** Sistema de Gerenciamento de Pedidos em uma Rede de Restaurantes  
**Equipe:** QA (eu), frontend, líder técnico e full-stack

---

## 1. OBJETIVOS DE QUALIDADE

**Definição:** Metas claras e mensuráveis que o projeto deve atingir.

**Exemplos de objetivos para o projeto:**
- Ser intuitivo e prático  
- Aguentar alta carga de pedidos em dias mais movimentados  
- Gerar relatórios por restaurante  

---

## 2. REQUISITOS DE QUALIDADE

**Definição:** Especificações técnicas e funcionais que o software deve atender.

**Funcionalidade:**  
Ser prático no uso com uma interface que aumenta a praticidade de retirada dos pedidos, escalável, podendo adicionar novas funcionalidades.

**Desempenho:**  
Alto, pois receberá alta quantidade de pedidos e registros no banco de dados.  
Deve suportar dias mais movimentados e altas cargas.

**Segurança:**  
Alta, pois irá gerir dados sensíveis (pagamentos e dados pessoais de clientes).

**Usabilidade:**  
Deve ser prático e com interface focada em agilidade na retirada de pedidos do dia a dia e na geração de relatórios.

---

## 3. PAPÉIS E RESPONSABILIDADES

- **Gerente de Projeto:** Responsável por planejar, executar e monitorar o projeto e garantir sua eficácia.  
- **Desenvolvedores:** Encarregados de escrever, testar e manter o código do software.  
- **Equipe de QA:** Encarregados por garantir a qualidade do software.  
- **Designer:** Foca na experiência (UX) e interface (UI) do usuário.  

---

## 4. PROCESSOS DE QUALIDADE

- Revisão de requisitos  
- Testes funcionais  
- Testes de integração  
- Testes de usabilidade (UX/UI)  
- Testes de segurança  
- Testes de regressão após novas entregas  
- Revisão de código (Code Review)  
- Validação final antes do deploy em produção  

---

## 5. MÉTRICAS DE QUALIDADE

- **Cobertura de testes:** Alcançar pelo menos 80% de cobertura de código automatizada (unitários e integração).  
- **Taxa de defeitos:** Manter menos de 3% de falhas críticas após cada entrega.  
- **Tempo de correção:** Corrigir falhas críticas em até 24 horas e falhas menores em até 72 horas após identificação.  

---

## 6. PLANO DE TESTES

- **Testes unitários:** Verificar a lógica de cada módulo individual, especialmente funções de registro de pedidos e cálculo de totais.  
- **Testes de integração:** Garantir que os módulos (frontend, backend e banco de dados) se comuniquem corretamente.  
- **Testes funcionais:** Validar o comportamento das principais funcionalidades — cadastro de pedidos, atualização de status, geração de relatórios.  
- **Testes de desempenho:** Realizar testes de carga e estresse simulando dias de alto movimento (ex: mais de 1000 pedidos simultâneos).  
- **Testes de segurança:** Avaliar autenticação, autorização e criptografia de dados sensíveis.  
- **Testes de usabilidade:** Avaliar experiência do usuário em diferentes perfis (atendentes, gerentes, administradores).  

---

## 7. FERRAMENTAS DE QUALIDADE

- **Jira:** Gestão de tarefas e acompanhamento de bugs.  
- **Postman:** Testes de API e integração.  
- **Selenium / Cypress:** Automação de testes funcionais e de regressão.  
- **Jest / Mocha:** Testes unitários.  
- **SonarQube:** Análise de qualidade e vulnerabilidade do código.  

---

## 8. AUDITORIAS E REVISÕES

- Revisão quinzenal do progresso da qualidade e métricas de testes.  
- Auditorias de código e segurança trimestrais.  
- Reuniões de retrospectiva para identificar melhorias de processo.  

---

## 9. TREINAMENTO E CAPACITAÇÃO

- Treinamento inicial da equipe em práticas de QA e uso das ferramentas (Jira, Cypress, SonarQube).  
- Workshops periódicos sobre testes automatizados e boas práticas de segurança.  
- Capacitação em usabilidade e acessibilidade para desenvolvedores e designers.  

---

## 10. GERENCIAMENTO DE RISCOS

- **Risco 1:** Falhas de desempenho em horários de pico (lentidão ou travamento).  
  **Mitigação:** Realizar testes de carga antecipados e implementar escalabilidade horizontal no servidor.  

- **Risco 2:** Vazamento de dados de clientes ou informações de pagamento.  
  **Mitigação:** Adotar criptografia (SSL/TLS), autenticação segura e auditorias periódicas de segurança.  

- **Risco 3:** Falta de alinhamento entre times (QA, dev, design).  
  **Mitigação:** Promover reuniões semanais de integração e uso de ferramentas colaborativas.  

---

## 11. DOCUMENTAÇÃO

- Documentação técnica e de arquitetura do sistema (backend, APIs, banco de dados).  
- Manual do usuário e guia de treinamento para o restaurante.  
- Registro dos casos de teste, resultados e planos de correção.  
- Histórico de versões (changelog).  

---

## 12. FEEDBACK E MELHORIA CONTÍNUA

- Reuniões de retrospectiva ao final de cada sprint para avaliar processos e resultados.  
- Coleta de feedback dos usuários (gerentes e atendentes) sobre desempenho e usabilidade.  
- Revisão constante dos processos de QA e atualização das métricas de qualidade.  
- Implementação de melhorias baseadas em lições aprendidas e indicadores de desempenho.  

