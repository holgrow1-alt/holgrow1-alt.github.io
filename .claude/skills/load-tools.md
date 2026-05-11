# /load-tools
Load and activate all Claude Code enhancement tools

## Description
Automatic skill that loads all available tools from CLAUDE.md and SYSTEM_INSTRUCTIONS.md into active memory.

## How it Works
1. Triggers on session start
2. 2. Parses CLAUDE.md for all tools and frameworks
   3. 3. Loads SYSTEM_INSTRUCTIONS.md for behavior rules
      4. 4. Activates all skills, MCP servers, and integrations
         5. 5. Monitors config.json for new tool additions
           
            6. ## Available Tools (Auto-Loaded)
            7. - Agent SDK (Python/TypeScript)
               - - Model Context Protocol (MCP)
                 - - Agentes em Paralelo (Subagents, Agent View, Teams, Worktrees)
                   - - Skills & Plugins
                     - - Hooks & Automation
                       - - Routines (Scheduled Tasks)
                         - - All Cloud Integrations
                          
                           - ## Usage
                           - Called automatically on session initialization.
                           - Can be manually invoked with: `/load-tools`
                          
                           - ## Dependencies
                           - - CLAUDE.md (required)
                             - - SYSTEM_INSTRUCTIONS.md (required)
                               - - .claude/config.json (optional, for configuration)
                                
                                 - ## Metadata
                                 - - Version: 1.0
                                   - - Type: System Initialization
                                     - - Scope: Global
                                       - - Auto-Trigger: Enabled
                                         - - Last Updated: 2026-05-11
