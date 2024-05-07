### CALMS - Framework
![image](https://github.com/igordamiao/CALMS/assets/21180598/89b58658-87a5-4fa5-a4b0-9c5b8f0639ef)

**1. CULTURE - Diagnóstico Cultural (C de CALMS):**
> - Processo Identificado: O processo de deploy manual após o desenvolvimento de novos recursos.
> - Descrição Atual: O deploy é manual, o que pode resultar em inconsistências e atrasos.
> - Pontos de Atrito e Oportunidades de Melhoria:
> - Falta de padronização e automação.
> - Comunicação limitada entre equipes.
> - Risco de erros humanos.

**2. AUTOMATION - Automação (A de CALMS):**
> - Implementar um pipeline de CI/CD para automatizar build, testes e deploy.
> - **Plano de Implementação:**
  > - Escolher ferramentas adequadas (ex: Jenkins, GitLab CI).
  > - Configurar o pipeline para acionamento automático.
  > - Incluir testes automatizados e rollback automático em caso de falha.
  > - Realizar treinamento para as equipes.

**3. LEAN - Identificação de Desperdícios (L de CALMS):**
> - Analisar o processo atual para identificar atividades que não agregam valor.
> - Eliminar atividades redundantes e burocráticas.
> - Promover eficiência e simplicidade.
> - Desperdício de recursos devido a processos manuais.
> - Desperdício de tempo devido a inconsistências nos processos.

**4. MEASUREMENT - Medição de métricas Relevantes (M de CALMS):**
> - Tempo médio entre entrega de código e deploy.
> - Taxa de sucesso dos deploys automáticos.
> - Número de incidentes pós-deploy.
> - MTTR (Tempo Médio de Recuperação): O MTTR é o tempo médio que uma equipe leva para recuperar um sistema ou serviço após um incidente ou falha. Medir o MTTR é crucial para entender a eficácia da equipe de operações em resolver problemas e restaurar a funcionalidade normal do sistema.
> - Tempo médio de espera na fila de deploy.

**5. SHARING - Compartilhamento de Conhecimento (S de CALMS):**
> - Realizar workshops e treinamentos.
> - Estabelecer fóruns de discussão.
> - Criar documentação detalhada.
> - Implementar sessões de revisão de incidentes (incident post-mortems): Essas sessões são realizadas após um incidente significativo para revisar o que aconteceu, identificar causas raiz e discutir lições aprendidas. Isso ajuda a equipe a aprender com os erros e melhorar seus processos.
> - Introduzir rotação de funções: Permitir que membros da equipe experimentem diferentes papéis dentro do ciclo de desenvolvimento e operações, promovendo uma compreensão mais ampla e compartilhamento de conhecimento.

**Três Maneiras:**

> _Para efetivamente implementar práticas DevOps, é essencial compreender as Três Maneiras, um conceito fundamental que orienta as organizações na jornada da cultura DevOps. As Três Maneiras não apenas delineiam os princípios essenciais do DevOps, mas também fornecem um roteiro claro para a transformação organizacional. Vamos explorar cada uma dessas maneiras e entender como elas podem impulsionar a excelência operacional e promover uma cultura de colaboração, automação e aprendizado contínuo:_
> 1. Primeira Maneira (Acelerar o Fluxo): Simplificar o processo de deploy através da automação, reduzindo o tempo entre a entrega do código e o deploy.
> 2. Segunda Maneira (Ampliar o Feedback): Implementar ferramentas de monitoramento contínuo para obter feedback em tempo real sobre o desempenho do sistema em produção.
> 3. Terceira Maneira (Experimentar e Aprender): Encorajar uma cultura de experimentação através da implementação de sprints curtos e ciclos de feedback rápidos.

### Para melhorar nosso fluxo, devemos partir do princípio de algumas perguntas.

**1. Entrega de Código:**
> - Como é feita a entrega de código atualmente?
> - Quais são os principais passos envolvidos no processo de entrega?
> - Quanto tempo leva para um código ser entregue e estar pronto para o deploy?
> - Existem gargalos ou pontos de atrito durante o processo de entrega?
> - Como é feita a comunicação entre as equipes de desenvolvimento e operações durante esse processo?

**2. Deploy:**
> - Como é realizado o deploy de novas versões de software atualmente?
> - Quais ferramentas ou métodos são utilizados para realizar o deploy?
> - O deploy é manual ou automatizado?
> - Quais são os principais desafios enfrentados durante o deploy?
> - Existe algum procedimento padrão ou checklist seguido durante o deploy?

**3. Testes:**
> - Como são realizados os testes de software após o deploy?
> - Quais tipos de testes são realizados (unitários, integração, aceitação, etc.)?
> - Os testes são automatizados ou manuais?
> - Qual é a cobertura de testes atual?
> - Como são reportados e tratados os bugs encontrados durante os testes?

**4. Monitoramento:**
> - Quais são os principais sistemas ou métricas monitoradas após o deploy?
> - Como é feito o monitoramento atualmente (manualmente, ferramentas automatizadas, etc.)?
> - Quanto tempo é dedicado à monitoramento após o deploy?
> - Quais são os principais problemas ou falhas identificados durante o monitoramento?
> - Como são tratados os incidentes detectados durante o monitoramento?
