# Quality Assessment Checks

This directory contains specific, actionable quality verification procedures for MCP server discovery and evaluation. Each check helps determine if an MCP server is well-built, maintained, and suitable for use.

## Purpose

Quality assessment checks are modular, repeatable procedures that help evaluate:
- Server quality indicators and best practices
- Community health and maintenance status  
- Documentation completeness and clarity
- Basic reliability and trustworthiness signals
- Compatibility and integration readiness

## Focus Areas

### Project Health Assessment
- **Maintenance Activity**: Is the project actively maintained?
- **Community Engagement**: Does it have active contributors and users?
- **Documentation Quality**: Is it well-documented and easy to understand?
- **Release Management**: Are releases regular and well-managed?

### Basic Quality Indicators
- **Code Quality**: Does it follow good development practices?
- **Error Handling**: Does it handle failures gracefully?
- **Configuration**: Is it properly configurable for different environments?
- **Dependencies**: Are dependencies well-managed and up-to-date?

### Usability and Integration
- **Setup Process**: How easy is it to get started?
- **Configuration Clarity**: Are setup instructions clear and complete?
- **Compatibility**: Does it work with standard MCP clients?
- **Support Resources**: Are there examples and help available?

## Check Format

Each check follows a standardized format:
- **Obsidian-formatted markdown** with proper frontmatter
- **Purpose and context** explaining what quality aspect this evaluates
- **Assessment criteria** with specific things to look for
- **Good and bad patterns** showing quality vs. poor indicators
- **Questions to guide evaluation** for both AI assistants and humans
- **Integration guidance** for using findings in server selection

## Active Development

This directory supports the continuous improvement workflow:
- **New checks needed**: Many quality areas need dedicated assessment procedures
- **Real-world feedback**: Checks improve based on actual server evaluations
- **Community contribution**: Server discoveries drive new quality criteria
- **Pattern recognition**: Common quality issues become standardized checks

## Available Checks

### Repository and Project Health
- **`github-repository-health.md`** - Assesses GitHub repository activity, maintainer engagement, and project sustainability
  - **High Confidence**: Automated metrics (commits, contributors, issues)
  - **Medium Confidence**: Activity pattern interpretation
  - **Focus**: Project viability and maintenance commitment

### Code Quality Assessment  
- **`code-quality-assessment.md`** - Evaluates code structure, style consistency, and maintainability
  - **High Confidence**: Automated linting and complexity metrics
  - **Medium Confidence**: Architectural pattern assessment
  - **Focus**: Code reliability and maintainability

### Testing Quality
- **`test-quality-assessment.md`** - Reviews test coverage, design quality, and reliability practices
  - **High Confidence**: Coverage metrics and test execution results
  - **Medium Confidence**: Test strategy and design evaluation
  - **Focus**: Server reliability and regression protection

### Dependency Management
- **`dependency-management-assessment.md`** - Analyzes dependency security, update practices, and supply chain risks
  - **High Confidence**: Vulnerability scanning and version analysis
  - **Medium Confidence**: Dependency necessity and risk assessment
  - **Focus**: Security posture and operational stability

## Usage with Prompts

These checks support the discovery and evaluation prompts in `/prompts/` by providing structured guidance for assessing server quality, maintenance status, and suitability for specific use cases.

## Contributing New Checks

When adding quality assessment checks:
1. Focus on objective, observable quality indicators
2. Provide clear criteria for good vs. poor quality
3. Include practical questions to guide assessment
4. Explain why each quality factor matters for server selection
5. Keep the focus on discovery and selection, not deep security analysis