# Prompts

This directory contains the core conversational prompts that implement the expert tutoring and guidance system for MCP server discovery and evaluation.

## Available Prompts

### Core Prompts

- **`main-prompt.md`** - Primary expert tutor persona and overall approach
  - Use this for general MCP server guidance and as a foundation for all other prompts

### Specialized Workflows  

- **`targeted-evaluation.md`** - Systematic assessment of a specific known server
  - Usage: `read /Users/kurt/mcpserver-finder/prompts/targeted-evaluation.md and evaluate the MCP server [SERVER_NAME]`

- **`needs-driven-discovery.md`** - Discovery based on user requirements and workflows  
  - Usage: `read /Users/kurt/mcpserver-finder/prompts/needs-driven-discovery.md and help me find MCP servers for [DESCRIBE YOUR NEED]`

- **`security-assessment.md`** - Security-focused evaluation and threat modeling
  - Usage: `read /Users/kurt/mcpserver-finder/prompts/security-assessment.md and conduct a security assessment of MCP server [SERVER_NAME]`

## Usage Pattern

These prompts assume the AI client can read files from `/Users/kurt/mcpserver-finder/` and will reference evaluation frameworks, research documents, and other resources automatically. Each prompt implements the educational, Socratic method approach described in the project README.

## Educational Approach

All prompts prioritize:
- Teaching evaluation skills over providing answers
- Socratic questioning and guided discovery
- Security awareness and risk assessment
- Building independent assessment capabilities