# Prompts

This directory contains the core conversational prompts that implement the expert tutoring and guidance system for MCP server discovery and evaluation.

## Available Prompts

### Core Prompts

- **`main-prompt.md`** - Primary expert tutor persona and overall approach
  - Use this for general MCP server guidance and as a foundation for all other prompts

### Specialized Workflows  

- **`targeted-evaluation.md`** - Systematic assessment of a specific known server
  - Usage: `read ./prompts/targeted-evaluation.md and evaluate the MCP server [SERVER_NAME]`

- **`needs-driven-discovery.md`** - Discovery based on user requirements and workflows  
  - Usage: `read ./prompts/needs-driven-discovery.md and help me find MCP servers for [DESCRIBE YOUR NEED]`

## Usage Pattern

These prompts assume the AI client can read files from the finder repository and will reference evaluation frameworks, research documents, and other resources automatically. Each prompt implements the educational, Socratic method approach described in the project README.

## Educational Approach

All prompts prioritize:
- Teaching discovery and evaluation skills over providing answers
- Socratic questioning and guided discovery
- Quality assessment and server selection guidance
- Building independent server evaluation capabilities