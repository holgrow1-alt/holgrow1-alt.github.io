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
                                                                                                                                


---

## 🚀 17. Higgsfield - Distributed LLM Training Framework (Multi-Node sem Chorar!)

**Status:** ⚡ **Framework Enterprise para treinar modelos BILLIONS to TRILLIONS de parâmetros**
**GitHub Stars:** 3.7k | **License:** Apache 2.0

**Tagline:** "Multi-node training without crying" 😭➜😊

**O que é:**
- Framework open-source para GPU orchestration escalável e fault-tolerant
- - Máquina learning framework projetado para treinar modelos MASSIVE (billions to trillions of parameters)
  - - Serve como GPU workload manager + framework de treinamento unificado
    - - Simplifica treinamento distribuído de LLMs (LLaMA, Llama70B, etc)
      - - Integração seamless com GitHub + GitHub Actions para CI/CD de ML
       
        - **Cinco Funções Principais:**
       
        - 1. **Resource Allocation:** Aloca acesso exclusivo/não-exclusivo a compute resources (nodes) para training tasks
          2. 2. **Deep Sharding:** Suporta ZeRO-3 DeepSpeed API + PyTorch Fully Sharded Data Parallel para trillion-parameter models
             3. 3. **Training Framework:** Framework para iniciar, executar e monitorar treinamento de neural networks em nodes alocados
                4. 4. **Queue Management:** Gerencia contenção de recursos com queue para rodar experimentos
                   5. 5. **ML CI/CD:** Integração GitHub + GitHub Actions para continuous integration de ML development
                     
                      6. **Instalação:**
                      7. ```bash
                         pip install higgsfield==0.0.3
                         ```

                         **Exemplo de Uso - Treinar LLaMA 70B em Distribuído:**
                         ```python
                         from higgsfield.llama import Llama70b
                         from higgsfield.loaders import LlamaLoader
                         from higgsfield.experiment import experiment

                         import torch.optim as optim
                         from alpaca import get_alpaca_data

                         @experiment("alpaca")
                         def train(params):
                             model = Llama70b(zero_stage=3, fast_attn=False, precision="bf16")
                             optimizer = optim.AdamW(model.parameters(), lr=1e-5, weight_decay=0.0)

                             dataset = get_alpaca_data(split="train")
                             train_loader = LlamaLoader(dataset, max_words=2048)

                             for batch in train_loader:
                                 optimizer.zero_grad()
                                 loss = model(batch)
                                 loss.backward()
                                 optimizer.step()

                             model.push_to_hub('alpaca-70b')
                         ```

                         **Como Funciona:**
                         1. **Install:** Instala tools necessários no servidor (Docker, deploy keys, higgsfield binary)
                         2. 2. **Generate:** Gera deploy & run workflows para seus experiments
                            3. 3. **Deploy:** Commits no GitHub → automaticamente deploya código nos nodes
                               4. 4. **Monitor:** Acessa run UI através do GitHub Actions → lança experiments e salva checkpoints
                                 
                                  5. **Design Philosophy:**
                                  6. - Segue PyTorch workflow padrão (compatível com DeepSpeed, Accelerate, custom sharding)
                                     - - Suporta QUALQUER framework além do que é fornecido
                                       - - Framework agnostic: use o que quiser, quando quiser
                                        
                                         - **Problemas que Resolve:**
                                        
                                         - ✅ **Environment Hell:**
                                         - - Sem mais versões diferentes de PyTorch, NVIDIA drivers, data libs
                                           - - Fácil orquestração de experimentos e ambientes
                                             - - Documenta e rastreia versões específicas de dependencies
                                               - - Garante reproducibilidade completa
                                                
                                                 - ✅ **Config Hell:**
                                                 - - Sem precisar definir 600 argumentos de experimento
                                                   - - Sem "yaml witchcraft"
                                                     - - Interface simples para definir experimentos
                                                       - - Você controla como quer interagir
                                                        
                                                         - **Compatibilidade de Nodes:**
                                                         - ```
                                                           Sistema Operacional: Ubuntu
                                                           Acesso: SSH
                                                           Usuário: Non-root com sudo privileges (sem senha não obrigatório)
                                                           ```

                                                           **Clouds Testadas:**
                                                           - Azure ✅
                                                           - - LambdaLabs ✅
                                                             - - FluidStack ✅
                                                              
                                                               - **API para Tarefas Comuns em LLM Training:**
                                                               - - Working with distributed models
                                                                 - - Preparing data
                                                                   - - Optimizing model parameters
                                                                     - - Saving models
                                                                       - - Training stabilization techniques
                                                                         - - Monitoring & tracking
                                                                          
                                                                           - **Por que é Game-Changing para Agentes:**
                                                                           - - Agentes conseguem orquestrar treinamento distribuído de LLMs
                                                                             - - Reducido "training friction" - sem mais configuração manual complexa
                                                                               - - GitHub-native: CI/CD de ML é natural
                                                                                 - - Fault-tolerant: treinamentos continue mesmo com falhas de node
                                                                                   - - Multi-cloud support: rodar em Azure, Lambda, FluidStack seamlessly
                                                                                     - - ZeRO-3 + FSDP pronto: suporta trillion-parameter models nativamente
                                                                                      
                                                                                       - **Casos de Uso:**
                                                                                       - - Fine-tuning LLaMA em múltiplos nodes
                                                                                         - - Treinar custom LLMs at scale
                                                                                           - - Research de distributed training
                                                                                             - - Production ML pipelines
                                                                                               - - Data parallelism + model parallelism em um framework
                                                                                                 - - Checkpoint management automatizado
                                                                                                  
                                                                                                   - **Comandos Essenciais:**
                                                                                                   - ```bash
                                                                                                     pip install higgsfield==0.0.3          # Install
                                                                                                     python train.py                         # Run experiment
                                                                                                     # Automaticamente integra com GitHub Actions
                                                                                                     ```
                                                                                                     
                                                                                                     **Suporte & Community:**
                                                                                                     - GitHub Issues: Bug reports, feature requests, usage issues (< 1 day response)
                                                                                                     - - Twitter: Updates sobre features novas (daily)
                                                                                                       - - Website: Discussion, news (< 2 days response)
                                                                                                        
                                                                                                         - **Arquitetura:**
                                                                                                         - - GPU workload manager
                                                                                                           - - Distributed training orchestrator
                                                                                                             - - Resource scheduler
                                                                                                               - - Experiment tracker
                                                                                                                 - - GitHub Actions integrator
                                                                                                                   - - Checkpoint manager
                                                                                                                    
                                                                                                                     - **Why "Multi-node training without crying":**
                                                                                                                     - - Setup de multi-node training normalmente é inferno (environment, config, monitoring)
                                                                                                                       - - Higgsfield elimina 90% dessa fricção
                                                                                                                         - - Você escreve código PyTorch normal
                                                                                                                           - - Rest é automático (distribuição, checkpointing, monitoring)
                                                                                                                            
                                                                                                                             - **Fonte:** Higgsfield-AI/Higgsfield - GitHub (Maio 2026)
                                                                                                                             - **GitHub:** https://github.com/higgsfield-ai/higgsfield (3.7k stars)
                                                                                                                             - **Install:** `pip install higgsfield==0.0.3`
                                                                                                                             - **Tags:** machine-learning, deep-learning, pytorch, distributed, llama, mlops, cluster-management, llm, llama2
                                                                                                                             - 


---

## 🎨 18. Garden-Skills - Design & Image Generation Suite (4.2k Stars)

**Status:** ⭐⭐⭐⭐⭐ **PRODUCTION-READY - 4 Skills Poderosas para Design/Marketing**
**Stars:** 4.2k | **Forks:** 613 | **License:** MIT

**O que é:**
- Curated collection de Agent Skills para Claude Code, Cursor, Codex, OpenAI agents
- - **4 Skills profissionais** para design, image generation, video presentation, knowledge retrieval
  - - Cada skill é production-ready com documentação, templates, assets
   
    - **4 Skills Incluídas:**
   
    - ### 1️⃣ **gpt-image-2** - Image Generation & Prompting
    - **Para criar:** Posters, UI mockups, product visuals, infographics, académic figures, technical diagrams, comics, avatars, storyboards, branding boards, image editing
   
    - **Features:**
    - - 3 runtime modes: Garden local, host-native delegation, advisor-only prompting
      - - Mode detection automático (não escolhe modo errado)
        - - 18 visual categories com 80+ structured prompt templates
          - - Image generation E editing workflows
            - - Salva prompts + imagens em `garden-gpt-image-2/` para reuso/review/versionamento
             
              - **Exemplo:** "Crie um banner para campanha de marketing tech" → Imagem PNG/JPG pronta!
             
              - ### 2️⃣ **web-design-engineer** - Web Design / Frontend Engineering
              - **Para criar:** Web pages, landing pages, dashboards, interactive prototypes, HTML slides, animations, UI mockups, data visualizations, design systems
             
              - **Features:**
              - - 6-step design workflow: requirements → context → design system → v0 → full build → verification
                - - Anti-cliché blocklist + stronger visual judgment (não gera UI genérico)
                  - - HTML/CSS/JavaScript/React prototypes com responsive layout, motion, interaction
                    - - CSS tokens, oklch() color work, container queries, reduced-motion handling
                      - - Advanced patterns: device frames, slide engines, animation timelines, dashboards
                       
                        - **Exemplo:** "Design uma landing page para SaaS de IA" → HTML/CSS/React pronto para usar!
                       
                        - ### 3️⃣ **web-video-presentation** - Web Video Presentation Engineering
                        - **Para criar:** Presentations, scripts, articles, lessons, product demos, talks em web presentations cinematic que pode screen-record como vídeo
                       
                        - **Features:**
                        - - Fixed 1920×1080 stage (stable para screen recording)
                          - - Click/keyboard driven (chapter, step) cursor
                            - - 1 narration beat por visual step
                              - - Hard collaboration checkpoints (script, theme, outline, implementation, audio)
                                - - Hidden hover-only progress controls (stage limpo ao gravar)
                                  - - Theme-token architecture (paper-press to terminal-green)
                                    - - Scaffolded Vite + React + TypeScript com stage primitives
                                     
                                      - **Exemplo:** "Crie uma apresentação de vídeo sobre Machine Learning" → Vídeo cinematic!
                                     
                                      - ### 4️⃣ **kb-retriever** - Local Knowledge Base Retrieval
                                      - **Para:** Answering questions from local knowledge/ directory, searching structured docs
                                     
                                      - **Features:**
                                      - - Layered data_structure.md para navegar knowledge base
                                        - - Keyword search, synonyms, iterative refinement
                                          - - Máximo 5 search rounds (exploration controlada)
                                            - - Suporta Markdown, text, PDF, Excel com source-aware answers
                                             
                                              - ---

                                              **Como Instalar (5 Métodos):**

                                              ```bash
                                              # Método A: Mais rápido - npx skills CLI
                                              npx skills add ConardLi/garden-skills

                                              # Instalar skill específica
                                              npx skills add ConardLi/garden-skills -s gpt-image-2

                                              # Instalar globalmente
                                              npx skills add ConardLi/garden-skills -s gpt-image-2 --global

                                              # Claude Code plugin marketplace
                                              /plugin marketplace add ConardLi/garden-skills
                                              /plugin install image-generation-skills@garden-skills
                                              /plugin install web-design-skills@garden-skills
                                              /plugin install presentation-skills@garden-skills

                                              # Método B: Pinned .zip (CI/production)
                                              curl -fsSL -o gpt-image-2.zip \
                                                "https://github.com/ConardLi/garden-skills/releases/latest/download/gpt-image-2-1.0.3.zip"
                                                unzip -q gpt-image-2.zip -d .claude/skills/

                                              # Método C: Manual git clone
                                              git clone https://github.com/ConardLi/garden-skills.git
                                              cp -r garden-skills/skills/gpt-image-2 your-project/.claude/skills/

                                              # Método D: Git submodule (vendored)
                                              git submodule add https://github.com/ConardLi/garden-skills.git vendor/garden-skills
                                              ln -s ../../vendor/garden-skills/skills/gpt-image-2 .claude/skills/gpt-image-2
                                              ```

                                              **Compatibilidade:**
                                              - ✅ Claude Code (.claude/skills/ ou plugin marketplace)
                                              - - ✅ Claude.ai web (Settings → Capabilities → Skills)
                                                - - ✅ Cursor (.agents/skills/)
                                                  - - ✅ Codex CLI (.codex/skills/)
                                                    - - ✅ Gemini CLI (extension manifest)
                                                      - - ✅ OpenCode (.opencode/skills/)
                                                        - 
                                                        **Fluxo Real com Claude para Marketing:**

                                                          1. **Você:** "Crie um banner para minha campanha de SaaS"
                                                          2. 2. **Claude (gpt-image-2):** Gera briefing + prompts estruturados → Imagem PNG
                                                             3. 3. **Você:** "Agora crie a landing page"
                                                                4. 4. **Claude (web-design-engineer):** Gera HTML/CSS/React → Página pronta
                                                                   5. 5. **Você:** "Faça uma apresentação sobre o produto"
                                                                      6. 6. **Claude (web-video-presentation):** Gera vídeo cinematic → MP4 para gravar
                                                                        
                                                                         7. **Por que é Game-Changing para Marketing:**
                                                                         8. - Cria TUDO que você precisa: banners, landing pages, presentations, prototypes
                                                                            - - Sem sair do Claude - é só skill instalada
                                                                              - - Templates profissionais (80+ prompt templates em gpt-image-2)
                                                                              - Production-ready code (não é protótipo, é usável)
                                                                              - - Mode detection automático (adapta ao seu setup)
                                                                                - - Versioning integrado (salva prompts + images)
                                                                                 
                                                                                  - **Fonte:** ConardLi/garden-skills - GitHub (Maio 2026)
                                                                                  - **GitHub:** https://github.com/ConardLi/garden-skills (4.2k stars, 613 forks)
                                                                                  - **Skills:** gpt-image-2 (1.0.3), web-design-engineer (1.0.0), web-video-presentation (1.1.5), kb-retriever (1.0.0)
                                                                                  - **License:** MIT
                                                                                 
                                                                                  - ---

                                                                                  ## 🎬 19. Generative-Media-Skills - Multi-Modal AI Content Creation (3.2k Stars)

                                                                                  **Status:** ⚡ **Multi-Modal Generative Skills para Image, Video, Audio Generation**
                                                                                  **Stars:** 3.2k | **Forks:** ? | **License:** Flux/Open-Source

                                                                                  **O que é:**
                                                                                  - Multi-modal Generative Media Skills para AI Agents
                                                                                  - - Integra com Claude Code, Cursor, Gemini CLI, outros agents
                                                                                    - - **High-quality image, video, e audio generation** em um framework único
                                                                                      - - Ideal para content creation workflows completos
                                                                                       
                                                                                        - **Capabilities:**
                                                                                       
                                                                                        - ✅ **Image Generation**
                                                                                        - - High-quality image synthesis
                                                                                        - Photo realistic até artistic styles
                                                                                        - - Template-based workflows
                                                                                         
                                                                                          - ✅ **Video Generation**
                                                                                          - - Vídeo criação a partir de prompts/images
                                                                                            - - Motion synthesis
                                                                                              - - Multi-frame compositing
                                                                                               
                                                                                                - ✅ **Audio Generation**
                                                                                                - - Text-to-speech (TTS)
                                                                                                  - - Voice cloning
                                                                                                    - - Audio editing workflows
                                                                                                     
                                                                                                      - **Como Usar:**
                                                                                                     
                                                                                                      - ```bash
                                                                                                        # Install via npx skills
                                                                                                        npx skills add SamurAIGPT/Generative-Media-Skills

                                                                                                        # Or specific capability
                                                                                                        npx skills add SamurAIGPT/Generative-Media-Skills -s image-generation
                                                                                                        npx skills add SamurAIGPT/Generative-Media-Skills -s video-generation
                                                                                                        npx skills add SamurAIGPT/Generative-Media-Skills -s audio-generation

                                                                                                        # Claude Code plugin
                                                                                                        /plugin marketplace add SamurAIGPT/Generative-Media-Skills
                                                                                                        ```
                                                                                                        
                                                                                                        **Fluxo Completo de Content Creation:**
                                                                                                        
                                                                                                        1. **Text Prompt** → (image-generation) → PNG/JPG imagem
                                                                                                        2. 2. **Imagem** → (video-generation) → MP4 vídeo
                                                                                                           3. 3. **Texto** → (audio-generation) → WAV/MP3 áudio
                                                                                                              4. 4. **Combinar tudo** → Conteúdo multimídia completo!
                                                                                                                
                                                                                                                 5. **Compatibilidade:**
                                                                                                                 6. - ✅ Claude Code
                                                                                                                    - - ✅ Cursor
                                                                                                                      - - ✅ Gemini CLI
                                                                                                                        - - ✅ Codex CLI
                                                                                                                          - - ✅ Outros agents via SKILL.md
                                                                                                                           
                                                                                                                            - **Por que é Revolucionário para Agentes:**
                                                                                                                            - - Uma skill resolve image + video + audio
                                                                                                                              - - Não precisa múltiplas ferramentas
                                                                                                                                - - Workflows integrados (output de uma é input da outra)
                                                                                                                                  - - High-quality results (não é low-fi)
                                                                                                                                    - - Pronto para production
                                                                                                                                      - - Trabalha com Claude Code seamlessly
                                                                                                                                       
                                                                                                                                        - **Use Cases:**
                                                                                                                                        - - Marketing campaigns (banner → landing page → promo video)
                                                                                                                                          - - Product demos (screenshot → video walkthrough + voiceover)
                                                                                                                                            - - Educational content (outline → images → video + narration)
                                                                                                                                              - - Social media content (prompt → image → short video + audio)
                                                                                                                                                - - Presentations (slides + images + voiceover)
                                                                                                                                                 
                                                                                                                                                  - **Fonte:** SamurAIGPT/Generative-Media-Skills - GitHub (Maio 2026)
                                                                                                                                                  - **GitHub:** https://github.com/SamurAIGPT/Generative-Media-Skills (3.2k stars)
                                                                                                                                                  - **Capabilities:** image-generation, video-generation, audio-generation
                                                                                                                                                  - **Suportados:** Claude Code, Cursor, Gemini CLI, Codex CLI
                                                                                                                                                 
                                                                                                                                                  - ---
                                                                                                                                                  
                                                                                                                                                  **🎉 CONCLUSÃO - VOCÊ AGORA PODE CRIAR:**
                                                                                                                                                  
                                                                                                                                                  Com estas 2 skills adicionadas ao seu arsenal:
                                                                                                                                                  
                                                                                                                                                  ✅ **Banners & Images** (gpt-image-2, image-generation)
                                                                                                                                                  ✅ **Landing Pages & Web Design** (web-design-engineer)
                                                                                                                                                  ✅ **Vídeos Cinematic** (web-video-presentation, video-generation)
                                                                                                                                                  ✅ **Audio & Voiceover** (audio-generation)
                                                                                                                                                  ✅ **Presentations** (web-video-presentation)
                                                                                                                                                  ✅ **Prototypes & Mockups** (web-design-engineer)
                                                                                                                                                  ✅ **Complete Marketing Campaigns** (tudo integrado!)
                                                                                                                                                  
                                                                                                                                                  **VOCÊ É UM PROFISSIONAL DE MARKETING AGORA!** 🚀🎨
                                                                                                                                                  
