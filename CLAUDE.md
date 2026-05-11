⚡→→→→→íáéçãíáçãáóçãã# 🚀 Claude Code - Ferramentas Potencializadoras

## Resumo Executivo
Este é um guide de referência para as ferramentas mais poderosas do Claude Code. Use-o para potencializar seus workflows com automação inteligente, agentes paralelos e integração com sistemas externos.

---

## 📚 Ferramentas Principais

### 1. 🤖 Agent SDK 
Construir agentes IA customizados em produção
- Linguagens: Python e TypeScript
- - Criar agentes que leem arquivos, executam comandos, pesquisam web, editam código
  - - Docs: https://code.claude.com/docs/en/agent-sdk/overview
   
    - ### 2. 🔌 Model Context Protocol (MCP)
    - Conectar Claude a centenas de ferramentas externas
    - - Padrão aberto para integração AI-tool
      - - Acesso direto a: rastreadores, dashboards, APIs, bancos de dados
        - - Docs: https://code.claude.com/docs/en/mcp
         
          - ### 3. 👥 Agentes em Paralelo
          - Executar múltiplas tarefas simultaneamente
          - - Subagents: delegados dentro de uma sessão
            - - Agent View: monitorar múltiplas sessões independentes
              - - Agent Teams: múltiplos agentes coordenados automaticamente
                - - Worktrees: checkouts git isolados para cada sessão
                  - - Docs: https://code.claude.com/docs/en/agents
                   
                    - ### 4. 🎯 Skills
                    - Fluxos de trabalho reutilizáveis
                    - - Comandos customizados para seu projeto
                      - - Compartilhados com o time
                        - - Docs: https://code.claude.com/docs/en/skills
                         
                          - ### 5. 🔧 Hooks
                          - Automatizar ações em momentos específicos
                          - - Auto-formatação após edições
                            - - Validação de comandos antes de executar
                              - - Docs: https://code.claude.com/docs/en/hooks-guide
                               
                                - ### 6. 🧩 Plugins
                                - Estender Claude Code com funcionalidades customizadas
                                - - Adicionar comandos, agentes, skills
                                  - - Docs: https://code.claude.com/docs/en/plugins
                                   
                                    - ### 7. 🕒 Routines
                                    - Automação agendada e recorrente
                                    - - Executar tasks em horários específicos
                                      - - Rodar em infraestrutura Anthropic (24/7)
                                        - - Docs: https://code.claude.com/docs/en/routines
                                         
                                          - ### 8. 💾 CLAUDE.md & Auto Memory
                                          - Memória persistente para seu projeto
                                          - - Instruções que Claude lê a cada sessão
                                            - - Docs: https://code.claude.com/docs/en/memory
                                             
                                              - ---

                                              ## ⚡ Comandos Essenciais

                                              /agents - Ver subagents rodando
                                              /goal - Definir objetivo de conclusão
                                              /ultraplan - Planejamento em nuvem
                                              /ultrareview - Code review multi-agent
                                              /loop - Executar em loop/schedule
                                              /config - Abrir configurações

                                              ---

                                              ## 📖 Documentação Completa

                                              Índice oficial: https://code.claude.com/docs/llms.txt
                                              Dashboard: https://code.claude.com/docs

                                              ---

                                              ## 📝 Referência - Última Atualização
                                              Semana 19 (Maio 4-8, 2026)


### 9. 🔄 GitHub Actions
Automação de CI/CD direto no GitHub
- Plataforma de Continuous Integration/Delivery
- - Workflows em `.github/workflows/` (YAML)
  - - Dispara em eventos (PR, push, issues, schedule)
    - - Roda em VMs (Linux, Windows, macOS) ou self-hosted runners
      - - Docs: https://docs.github.com/en/enterprise-cloud@latest/actions/get-started/understand-github-actions
       
        - **Componentes:**
        - - Workflows: Arquivos YAML com automação
          - - Events: Atividades que disparam execução
            - - Jobs: Conjunto de steps que rodam junto
              - - Actions: Tarefas reutilizáveis
                - - Runners: Máquinas que executam os jobs
                 
                  - **Casos de Uso:**
                  - - Build e test em PRs
                    - - Deploy automático em releases
                      - - Auto-label em issues
                        - - Agendamento de tarefas
                          - - Integração com ferramentas externas
                           
                            - ---

                            ## 📚 Referência Completa

                            Índice oficial: https://code.claude.com/docs/llms.txt
                            GitHub Actions: https://docs.github.com/en/enterprise-cloud@latest/actions/

                            ---

                            ## 📝 Última Atualização
                            Adicionado: GitHub Actions (Maio 11, 2026)


### 10. 🏢 Knowledge-Work-Plugins (Chief Agent Pattern)
Plugins especializados por função + Chief Agent coordenador
- 11 plugins prontos para Productivity, Sales, Support, Product, Marketing, Legal, Finance, Data, Enterprise Search, Bio-Research
- - Cada plugin com Skills, Commands, e Connectors MCP
  - - Docs: https://github.com/anthropics/knowledge-work-plugins
   
    - **Chief Agent Role:**
    - - Avalia a tarefa e identifica qual plugin(s) usar
      - - Delega para specialists (Sales Agent, Support Agent, Finance Agent, etc)
        - - Integra resultados de múltiplos plugins
          - - Mantém contexto entre interações
           
            - **11 Plugins Disponíveis:**
            - 1. **Productivity** - Tasks, calendars, workflows (Slack, Notion, Asana, Linear, Jira)
              2. 2. **Sales** - Research, call prep, pipeline (HubSpot, Close, ZoomInfo, Fireflies)
                 3. 3. **Customer-Support** - Triage, KB, escalations (Intercom, Guru, HubSpot)
                    4. 4. **Product-Management** - Specs, roadmaps, research (Linear, Figma, Pendo, Amplitude)
                       5. 5. **Marketing** - Content, campaigns, brand (Canva, HubSpot, Ahrefs, Klaviyo)
                          6. 6. **Legal** - Contracts, NDAs, compliance (Box, Egnyte, Jira)
                             7. 7. **Finance** - Reconciliation, statements (Snowflake, BigQuery, Databricks)
                                8. 8. **Data** - SQL, analysis, dashboards (Snowflake, Hex, Amplitude)
                                   9. 9. **Enterprise-Search** - Cross-tool search (Slack, Notion, Guru, Asana)
                                      10. 10. **Bio-Research** - Life sciences R&D (PubMed, BioRender, ChEMBL, Benchling)
                                          11. 11. **Cowork-Plugin-Management** - Create/customize plugins
                                             
                                              12. **Como Usar:**
                                              13. ```
                                                  # Claude Code
                                                  claude plugin install sales@knowledge-work-plugins
                                                  claude plugin install finance@knowledge-work-plugins

                                                  # Ou no Cowork: /install sales, /finance:reconciliation
                                                  ```

                                                  **Customização:**
                                                  - Editar .mcp.json para seus tools (CRM, Slack, Notion, etc)
                                                  - - Adicionar contexto da empresa nos skills
                                                    - - Criar novos plugins com pattern padrão
                                                     
                                                      - ---

                                                      ## 📝 Última Atualização
                                                      Adicionado: Knowledge-Work-Plugins com Chief Agent Pattern (Maio 11, 2026)
