# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is the MCP Server Finder project - an expert-guided tool for discovering, evaluating, and selecting Model Context Protocol (MCP) servers. The project serves as an educational advisor and tutor rather than just a search tool, teaching users how to evaluate MCP servers, understand quality indicators, identify security risks, and make informed decisions.

## Architecture

This repository currently contains only documentation and project definition files (README.md, LICENSE). There is no source code implementation yet - this appears to be a conceptual/specification repository that defines the goals, approach, and capabilities of the planned MCP Server Finder tool.

### Key Architectural Concepts

The planned system follows an **expert advisor and tutor** design pattern with these core components:

- **Educational Guidance Engine**: Interactive tutoring system using Socratic method and guided discovery
- **Discovery Functions**: GitHub/registry search, metadata extraction, documentation analysis
- **Analysis Functions**: Security assessment, compatibility checking, quality evaluation
- **Decision Support Framework**: Requirements analysis, comparison tools, risk assessment

### Teaching-First Approach

The system prioritizes education over automation:
- Teaches evaluation criteria rather than just providing recommendations  
- Uses interactive learning with immediate feedback
- Builds user skills for independent server assessment
- Focuses on security awareness and best practices

## Development Context

This is part of the broader **Model Context Protocol Security** initiative - a Cloud Security Alliance community project focused on security aspects of MCP ecosystem tools.

### Integration Points

The tool is designed to work with other MCP security tools:
- **mcpserver-audit**: Security evaluation expertise
- **mcpserver-builder**: Development best practices knowledge  
- **mcpserver-operator**: Operational deployment guidance

## Project Status

This appears to be in the **specification/planning phase** with no implementation code present yet. The README serves as a comprehensive design document defining the vision, capabilities, and approach for the planned tool.

## Security Focus

As a security-focused project, any implementation should prioritize:
- Teaching users to identify security risks in MCP servers
- Promoting secure server selection practices
- Integrating security evaluation into the discovery workflow
- Building security awareness in the MCP community