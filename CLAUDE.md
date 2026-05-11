📚íáçãçãóéíéçãáóçõçõ→ê→áçõáá→éçõçã→⚡→→→→→íáéçãíáçãáóçãã# 🚀 Claude Code - Ferramentas Potencializadoras

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


---

## 💻 13. VS Code Agent Patterns & Chat UX - Aprendizado para Tarefas Futuras

**Rendering & Chat Experience:**
- Incremental rendering de respostas de chat: streams content block-by-block com animações enquanto tokens chegam
- - Reduz perceived wait time em respostas longas
  - - Configurável via settings:
    -   - `chat.experimental.incrementalRendering.enabled` (default: true)
        -   - `chat.experimental.incrementalRendering.animationStyle`: none, fade, rise, blur, scale, slide, reveal (default: fade)
            -   - `chat.experimental.incrementalRendering.buffering`: off, word, paragraph (default: word)
             
                - **Agent Sessions Management:**
                - - Sort agent sessions por created ou last updated
                  - - Facilita encontrar sessões anteriores e retomar trabalho
                    - - System notifications para background terminal commands (não precisa alternar para terminal)
                     
                      - **Visual Studio Code Agents App (Insiders):**
                      - - Companion app para VS Code Insiders (preview)
                        - - Environment focado em agents com sessões paralelas
                          - - Capacidade de rodar multi-repo work, review diffs inline, iterar em multi-step coding tasks
                            - - Sub-sessions: Criar sub-sessões de uma sessão pai (+ no título) para trabalho paralelo sem perder contexto
                              - - Inline change rendering: Improvements para escanear e comparar diffs
                                - - Launchable via: Start menu, Command Palette (`Chat: Open Agents Application`), VS Code welcome page
                                 
                                  - **Terminal Integration para Agents:**
                                  - - Copilot CLI, Claude Code, Gemini CLI agora são detectados como agent CLIs (não genéricos "node")
                                    - - Terminal title mostra qual agent está rodando
                                      - - Launch Copilot CLI com custom terminal profile (até em fish/Git Bash)
                                        - - Configurável via `terminal.integrated.tabs.allowAgentCliTitle` (default: true)
                                         
                                          - **Key Takeaways para Development:**
                                          - - Incremental rendering melhora UX percebido em chats longos
                                            - - Multi-session/sub-session workflow permite work paralelo sem context loss
                                              - - Proper terminal title identification essencial para múltiplos agents rodando
                                                - - Background terminal notifications evitam context switching
                                                  - - Estas patterns são críticas para agent-native workflows eficientes
                                                   
                                                    - **Fonte:** VS Code Release Notes - Agent Experience & Chat Improvements (Maio 2026)
                                                    - 
Page_DownPage_DownPa

---

## 🎨 14. getdesign.md - Production-grade DESIGN.md Collection

**O que é:**
- Coleção de DESIGN.md em nível de produção para agentes de código IA
- - Permite que agentes de IA gerem matching UI usando design systems reais
  - - Built com real depth para UI generation de alta qualidade (not surface-level)
    - - Baseado em Google's DESIGN.md spec
      -
      - **Estatísticas Rápidas:**
      - - 71 arquivos DESIGN.md
        - - Última atualização: Maio 11, 2026
          - - 75.7k stars no GitHub
            - - 5.5M+ monthly views
              -
              - **Design Systems Incluídos (Featured):**
              - - BMW M - Motorsport aesthetic, black canvas com M tricolor stripe, full-bleed photography
                - - Binance - Crypto exchange, yellow accent on monochrome, trading-floor urgency
                  - - Airtable - Spreadsheet-database, colorful, friendly, structured data aesthetic
                    - - E 68+ mais design systems inspirados de: Apple, Airbnb, Spotify, Linear, Figma, Stripe, Supabase, Nike, Netflix, Uber, Tesla, Pinterest, Notion, etc
                      -
                      - **Categorias de Design Systems:**
                      - - AI & LLM Platforms (12)
                        - - Media & Consumer Tech (12)
                          - - Developer Tools & IDEs (7)
                            - - Automotive (7)
                              - - Backend, Database & DevOps (8)
                                - - Fintech & Crypto (7)
                                  - - Productivity & SaaS (7)
                                    - - Design & Creative Tools (6)
                                      - - E-commerce & Retail (5)
                                        -
                                        - **Como Usar:**
                                        - - Drop DESIGN.md file no seu projeto
                                          - - Deixa agentes de código construírem matching UI automaticamente
                                            - - Cada DESIGN.md contém especificação completa do design system:
                                              -   - Color palette, typography, spacing, components
                                                  -   - Component patterns e behaviors
                                                      -   - Example usage e best practices
                                                          -   - Responsive design guidelines
                                                              -
                                                              - **Key Value para Agentes IA:**
                                                              - - Reference de design systems real-world para UI generation
                                                                - - Profundidade e detalhe suficiente para gerar código production-grade
                                                                  - - Inspiração de brands reconhecidas (Apple, Tesla, Spotify, etc)
                                                                    - - Pattern vocabulary para melhorar agentic design capabilities
                                                                      - - Drop-in reusable para qualquer projeto
                                                                        -
                                                                        - **Acesso:**
                                                                        - - Website: https://getdesign.md
                                                                          - - Browse design system inspirations
                                                                            - - Request private DESIGN.md para uso específico
                                                                              - - Suporte a novos design systems (sponsor slot disponível)
                                                                                -
                                                                                - **Por que é valioso para Agentes:**
                                                                                - - Agentes conseguem aprender padrões reais de design de brands famosas
                                                                                  - - Reduz necessidade de reinventar design patterns
                                                                                    - - Acelera geração de UI com qualidade profissional
                                                                                      - - Provides "design vocabulary" que agentes usam para comunicar com designers
                                                                                        - - Bridge entre desenvolvimento automatizado e design real-world
                                                                                          -
                                                                                          - **Fonte:** getdesign.md - Production-grade DESIGN.md Collection (Maio 2026)
                                                                                          - ge_Down


---

## 🎬 15. Remotion - Make Videos Programmatically (Skill Explosiva!)

**Status:** ⚡ **BOMBANDO NO GITHUB - 150k+ downloads, 46k stars**

**O que é:**
- Framework para criar vídeos MP4 reais com React
- - Parametrize content, render server-side e build aplicações de vídeo
  - - Code-first video creation: use React para criar vídeos sofisticados
    - - Escalável: render localmente, no servidor ou serverless (Lambda)
     
      - **Principais Features:**
      - **Compose with Code:** Use React + TypeScript para criar vídeos
      - - **Edit Dynamically:** Parametrize vídeos passando dados
        - - **Remotion Studio:** IDE visual para desenvolvimento
          - - **Remotion Player:** Embed player em aplicações
            - - **Remotion Editor Starter:** Template completo para video editors customizados
              - - **Remotion Lambda:** Render escalável serverless
               
                - **Use Cases Reais:**
                - - Music visualization (gerar vídeos de música automaticamente)
                  - - Captions & subtitles automation
                    - - Screencast recording programático
                      - - Year in review videos (como Spotify Wrapped)
                        - - Social media content automation
                          - - Template-based video generation
                            - - Banger.Show: 3D visual creation tool
                             
                              - **Estatísticas Impressionantes:**
                              - - 46k GitHub stars
                                - - 150k+ npm downloads (EXPLOSIVO!)
                                  - - 8000+ Discord members
                                    - - 35+ templates & examples
                                      - - 300+ contributors
                                        - - 800 páginas de documentação
                                         
                                          - **Como Usar:**
                                          - ```
                                            $ npx create-video@latest
                                            ```

                                            Templates disponíveis:
                                            - Blank starter
                                            - - Hello World exemplo
                                              - - Next.js integrado
                                                - - React Router
                                                  - - Find a template
                                                   
                                                    - **Pricing (Flexible):**
                                                    - - **Free License:** Individuals, unlimited use, commercial allowed
                                                      - - **Company License:** Teams 4+, pay per render, prioritized support
                                                      - **Remotion for Creators:** $25/mo per seat (low volume, local)
                                                      - - **Remotion for Automators:** $0.01/render, $100/mo minimum (SaaS apps, prompt-to-video)
                                                        - - **Enterprise:** Custom terms, private Slack, monthly consulting
                                                         
                                                          - **Tech Stack:**
                                                          - - React + TypeScript (core)
                                                            - - Server-side rendering
                                                              - - Supports MP4 + other formats
                                                                - - FFmpeg integration
                                                                  - - Mux integration para streaming
                                                                   
                                                                    - **Por que é Valioso para Agentes:**
                                                                    - - Agentes podem gerar vídeos a partir de dados/roteiros automaticamente
                                                                      - - Perfeito para prompt-to-video applications (IA gera roteiro → Remotion gera vídeo)
                                                                        - - Reduz necessidade de ferramentas video editing manuais
                                                                          - - API-first: agentes conseguem criar vídeos sem UI
                                                                            - - Scaling: Lambda permite render de milhões de vídeos
                                                                              - - Template system: agentes reutilizam templates pré-construídos
                                                                               
                                                                                - **Integração com IA/Agentes:**
                                                                                - - Editor Starter: Build custom video editors com IA
                                                                                  - - Parametric rendering: Agentes passam dados → vídeo renderizado
                                                                                    - - Automation: Video creation pipelines completamente automatizadas
                                                                                      - - Banger.Show: 3D visual creation matching sound/brand
                                                                                        - - Prompt-to-video: IA escreve roteiro → Remotion renderiza
                                                                                         
                                                                                          - **Community & Support:**
                                                                                          - - 46k GitHub stars
                                                                                            - - Discord ativo (8000+)
                                                                                              - - 300+ contributors
                                                                                                - - Experts disponíveis
                                                                                                  - - Success stories documentadas
                                                                                                   
                                                                                                    - **Comandos Principais:**
                                                                                                    - ```
                                                                                                      npx create-video@latest          # Criar novo projeto
                                                                                                      npm run dev                       # Rodar Remotion Studio
                                                                                                      npm run build                     # Build para produção
                                                                                                      remotion render                   # Render CLI
                                                                                                      ```
                                                                                                      
                                                                                                      **Por que Está Bombando:**
                                                                                                      - Única solução real para video-as-code
                                                                                                      - - Perfeito fit para automação de conteúdo
                                                                                                        - - Comunidade crescente
                                                                                                        - Uso extenso em startup de video generation
                                                                                                        - - Integração natural com web stack (React)
                                                                                                          - - Serverless + scaling pronto para produção
                                                                                                           
                                                                                                            - **Fonte:** Remotion.dev - Make Videos Programmatically (Maio 2026)
                                                                                                            - **GitHub:** https://github.com/remotion-dev/remotion (46k stars)
                                                                                                            - **Website:** https://www.remotion.dev
                                                                                                            - 


---

## 🎯 16. Remotion Skills para Agentes IA - Criar e Editar Vídeos Automaticamente

**Skill Name:** `remotion-dev/skills`
**Install Command:** `npx -y skills@latest add remotion-dev/skills -g -y`

**O que é:**
- Agent Skills oficiais do Remotion para criar vídeos programaticamente
- - Integrada com Claude Code, Codex, OpenCode e outros coding agents
  - - Permite que agentes IA criem, editem e renderizem vídeos sem UI manual
    - - Suporta Tailwind CSS, templates e blank projects
      - - Pronta para uso em Coding Agent Prompts
       
        - **Como Instalar:**
        - ```bash
          # Via agent skills manager (recomendado)
          npx -y skills@latest add remotion-dev/skills -g -y

          # Ou via CLI remoto
          npx remotion skills add

          # Com create-video wizard
          npx create-video@latest
          # Selecionar "Yes" para Agent Skills durante setup
          ```

          **Funcionalidades da Skill:**
          - **Video Creation:** Criar vídeos MP4 do zero com código
          - - **Adding Video:** Integrar clipes de vídeo em composições
            - - **Adding Audio:** Adicionar trilhas de áudio, música, voiceover
              - - **Parameterized Videos:** Passar dados dinâmicos para renderizar vídeos com diferentes conteúdos
                - - **Captions:** Gerar e customizar legendas automaticamente
                  - - **Rendering:** Render local, server-side ou serverless (Lambda)
                   
                    - **Use Cases com Agentes:**
                    - 1. **Prompt-to-Video:** Agente recebe prompt → cria vídeo completo
                      2. 2. **Dynamic Content:** Parametrize vídeos com dados (nomes, datas, números)
                         3. 3. **Automation:** Gerar centenas de vídeos programaticamente
                            4. 4. **Social Media:** Criar conteúdo para TikTok, Instagram, YouTube automaticamente
                               5. 5. **Music Visualization:** Agente gera visualizações de música
                                  6. 6. **Year in Review:** Criar compilações automáticas como Spotify Wrapped
                                     7. 7. **Screencast:** Gravar e editar screencasts programaticamente
                                       
                                        8. **Cmdands da Skill (para Agentes):**
                                        9. ```bash
                                           npx remotion skills add           # Adicionar skills ao projeto
                                           npx remotion render               # Renderizar vídeo final
                                           npm run dev                       # Iniciar Remotion Studio (preview)
                                           npx create-video@latest           # Setup novo projeto com skills
                                           ```

                                           **Templates Disponíveis:**
                                           - Blank (vazio para começar do zero)
                                           - - Hello World (exemplo básico)
                                             - - Next.js (com framework)
                                               - - React Router (com routing)
                                                 - - Find a template (browser de templates)
                                                  
                                                   - **System Requirements:**
                                                   - - Node.js 16+ ou Bun 1.0.3+
                                                     - - macOS 15 (Sequoia) ou posterior
                                                       - - Linux com Libc 2.35+
                                                         - - Alpine Linux e nixOS: NÃO suportados
                                                          
                                                           - **Exemplo de Uso com Agent:**
                                                           - ```javascript
                                                             // Agente cria arquivo Composition.tsx
                                                             import { Composition } from 'remotion';

                                                             export const MyComposition = () => {
                                                               return (
                                                                 <div style={{ backgroundColor: 'black', color: 'white', flex: 1 }}>
                                                                   <h1>Vídeo criado por IA!</h1>
                                                                 </div>
                                                               );
                                                             };

                                                             export const compositions = [
                                                               {
                                                                 id: 'MyComp',
                                                                 component: MyComposition,
                                                                 durationInFrames: 150,
                                                                 fps: 30,
                                                                 width: 1920,
                                                                 height: 1080,
                                                               },
                                                             ];
                                                             ```

                                                             **Integração com Coding Agents:**
                                                             - Claude Code: Use command palette: "Remotion Skills add"
                                                             - - Codex/OpenCode: Cole o prompt com skill install command
                                                               - - Any Coding Agent: Execute `npx -y skills@latest add remotion-dev/skills -g -y`
                                                                
                                                                 - **Fluxo Típico com Agente:**
                                                                 - 1. **Setup:** Agent executa `npx create-video@latest` com skills
                                                                   2. 2. **Create:** Agent cria composições React com vídeo/áudio
                                                                      3. 3. **Configure:** Agente parametriza com dados dinâmicos
                                                                         4. 4. **Render:** Agent executa `npx remotion render` para gerar MP4
                                                                            5. 5. **Output:** Vídeo pronto em output/ directory
                                                                              
                                                                               6. **Por que é Gamechanging para Agentes:**
                                                                               7. - Agents conseguem criar vídeos sem APIs externas
                                                                                  - - Local-first: renderiza no PC do desenvolvedor
                                                                                    - - Serverless: Deploy em Lambda para escalar
                                                                                      - - Código limpo: React components = vídeos
                                                                                        - - Zero learning curve: Se domina React, domina video creation
                                                                                          - - Automação completa: Da criação ao render sem UI
                                                                                           
                                                                                            - **Performance & Scaling:**
                                                                                            - - Local rendering: Rápido para desenvolvimento
                                                                                              - - Serverless (Lambda): Render paralelo de milhões de vídeos
                                                                                                - - CLI tools: Batch rendering de múltiplos vídeos
                                                                                                  - - Caching: Frames renderizados em cache para iteração rápida
                                                                                                   
                                                                                                    - **Limitações & Considerações:**
                                                                                                    - - Requer Node.js instalado localmente ou em servidor
                                                                                                      - - FFmpeg necessário para alguns formatos
                                                                                                        - - Rendering de 1080p60fps pode ser lento localmente
                                                                                                          - - Para alta volume, use Lambda + serverless
                                                                                                           
                                                                                                            - **Próximos Passos para Agentes:**
                                                                                                            - - Ler documentação: https://www.remotion.dev/docs
                                                                                                              - - Começar com Hello World template
                                                                                                                - - Explorar Remotion Studio (npm run dev)
                                                                                                                  - - Experimentar com parameterização
                                                                                                                    - - Depois escalar com Lambda para produção
                                                                                                                     
                                                                                                                      - **Comunidade & Recursos:**
                                                                                                                      - - Discord: 8000+ members
                                                                                                                        - - GitHub: 46k stars
                                                                                                                          - - Success Stories disponíveis
                                                                                                                            - - Experts para ajudar
                                                                                                                             
                                                                                                                              - **Fonte:** Remotion Skills - Installation Docs (Maio 2026)
                                                                                                                              - **Skill Repository:** remotion-dev/skills
                                                                                                                              **Official Docs:** https://www.remotion.dev/docs
                                                                                                                                
