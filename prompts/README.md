# Prompts

This directory contains the core prompt for MCP server discovery and evaluation expertise.

## Main Prompt

**`main-prompt.md`** - Complete MCP server discovery and evaluation tool
- **Purpose**: Expert guidance for finding and evaluating MCP servers
- **Capabilities**: Requirements-driven discovery, targeted evaluation, comparative analysis
- **Integration**: Designed for orchestrator coordination and standalone use
- **Learning**: Adaptive educational approach with Socratic method

## Usage via Orchestrator

The main prompt is typically accessed through the MCP Security Orchestrator:
```
# From orchestrator
"I need to find an MCP server for web search"
→ Orchestrator routes to finder tool

# Direct usage
read ../../mcpserver-finder/prompts/main-prompt.md and [your discovery/evaluation request]
```

## Specialized Workflow Guides

Detailed workflow guidance has been moved to `../resources/`:
- **Discovery Workflow**: `../resources/discovery-workflow-guide.md`
- **Evaluation Workflow**: `../resources/evaluation-workflow-guide.md`

## Educational Approach

The main prompt implements:
- **Socratic questioning** and guided discovery
- **Progressive complexity** from basic to sophisticated analysis
- **Quality-first focus** on reliable, maintainable servers
- **Context-adaptive** guidance based on deployment scenario