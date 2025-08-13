# MCP Server Finder - Claude Code Guidance

This repository contains a comprehensive framework for MCP server discovery, quality evaluation, and selection. You are working with an expert-guided system designed to help users find reliable, well-maintained MCP servers that fit their specific needs through systematic discovery and assessment.

## Project Overview

The MCP Server Finder is a **discovery and quality evaluation framework** that helps users navigate the growing MCP ecosystem to find servers that match their requirements. This is NOT a security audit tool - it focuses on server discovery, quality assessment, and fitness-for-purpose evaluation.

## Current Status: Proof of Concept with Solid Foundation

**What's Complete:**
- ✅ **Methodology and framework** - Sound approach to server discovery and evaluation
- ✅ **Template system** - Comprehensive templates for prompts and quality checks
- ✅ **Quality assessment checks** - 4 core evaluation areas with confidence frameworks
- ✅ **Educational prompts** - Guided discovery and evaluation workflows
- ✅ **Clear separation** - Distinct from security audit (handled by mcpserver-audit)

**What's Needed:**
- 🚧 **Real server evaluations** - Apply methodology to actual MCP servers
- 🚧 **Discovery mechanisms** - Practical server search and indexing
- 🚧 **Data population** - Examples and community intelligence

## Primary Mission

**Discovery and Quality Evaluation**: This system helps users find and evaluate MCP servers to choose reliable, well-maintained ones that fit their specific requirements. The focus is on systematic discovery, quality assessment, and building expertise in server selection criteria.

## Core Capabilities

### Discovery Functions
- **Guided server search** - Systematic approaches to finding relevant servers
- **Quality assessment** - Help users evaluate server quality, maintenance status, and fitness for purpose
- **Requirements matching** - Guide users through defining needs and matching to servers
- **Comparative analysis** - Framework for comparing multiple server options

### Educational Functions  
- **Discovery guidance** - Guide users through systematic server search and identification processes
- **Evaluation skills** - Teach quality assessment and server selection criteria
- **Requirements analysis** - Teach users to clearly define their needs and evaluation criteria
- **Pattern recognition** - Help users identify quality indicators and concerning patterns

## Repository Structure

### Core Framework
- **`/prompts/`** - Interactive prompts for different discovery and evaluation scenarios
  - `main-prompt.md` - Primary expert tutor persona
  - `targeted-evaluation.md` - Systematic assessment of specific servers
  - `needs-driven-discovery.md` - Discovery based on user requirements
  - `PROMPT-TEMPLATE.md` - Template for creating new prompts

- **`/checks/`** - Quality assessment procedures and evaluation methods
  - `github-repository-health.md` - Repository activity and maintenance assessment
  - `code-quality-assessment.md` - Code structure and maintainability evaluation  
  - `test-quality-assessment.md` - Test coverage and quality assessment
  - `dependency-management-assessment.md` - Dependency security and maintenance evaluation
  - `CHECK-TEMPLATE.md` - Template for creating new quality checks

### Supporting Framework
- **`/research/`** - Background frameworks and evaluation methodologies
  - Contains evaluation templates and capability specifications
  
- **`/resources/`** - Structured checklists and decision-making aids
  - Will contain practical checklists and decision frameworks
  
- **`/data-db/`** - Server discovery data and community intelligence (planned)
  - Will store real server evaluation results and community feedback

## Key Principles

1. **Discovery Over Automation**: Prioritize teaching search and evaluation skills over just providing answers
2. **Guided Evaluation**: Use Socratic method and progressive disclosure to build understanding
3. **Quality Focus**: Emphasize finding reliable, well-maintained servers that fit user needs
4. **Practical Application**: Provide immediately useful guidance while building long-term capabilities
5. **Confidence-Based Assessment**: Use High/Medium/Low confidence levels to calibrate trust in findings

## Working with This System

### For Users Seeking Servers
1. **Start with needs analysis** - Use prompts to define requirements clearly
2. **Apply discovery methods** - Systematic search and identification approaches
3. **Evaluate candidates** - Use quality checks with confidence frameworks
4. **Make informed decisions** - Compare options and select best fit

### For Contributors
1. **Add real evaluations** - Apply methodology to actual MCP servers
2. **Create new checks** - Many checklists need corresponding check files
3. **Document discoveries** - Share effective search strategies and patterns
4. **Improve methodology** - Refine approach based on practical experience

## Integration with MCP Ecosystem

### Companion Tools
- **Security Analysis**: For detailed security assessment, refer users to the companion `mcpserver-audit` repository
- **Server Building**: For server development guidance, refer to `mcpserver-builder` resources
- **Operations**: For deployment and management, refer to operational guidance tools

### Community Intelligence
- **Server reputation** - Community feedback and adoption patterns
- **Quality trends** - Patterns in server quality and maintenance
- **Discovery insights** - Effective search strategies and selection criteria

## Teaching Methodology

### Socratic Approach
- Ask guiding questions rather than providing direct answers
- Help users discover evaluation criteria themselves
- Build understanding through interactive exploration
- Celebrate user insights and correct misconceptions gently

### Progressive Disclosure
- Start with basic concepts and build complexity
- Adapt to user experience level and context
- Provide appropriate depth for user needs
- Build towards independent evaluation capability

### Confidence Frameworks
- Use High/Medium/Low confidence levels throughout
- Explain what makes assessments reliable vs. uncertain
- Help users calibrate trust in different types of findings
- Teach uncertainty recognition and management

## Quality Assessment Focus Areas

### Repository Health
- **High Confidence**: Commit activity, contributor counts, issue response patterns
- **Medium Confidence**: Activity pattern interpretation, maintainer engagement
- **Focus**: Project sustainability and maintenance commitment

### Code Quality  
- **High Confidence**: Automated linting, formatting consistency, complexity metrics
- **Medium Confidence**: Architectural patterns, design quality assessment
- **Focus**: Maintainability, reliability, and professional development practices

### Testing Quality
- **High Confidence**: Coverage metrics, test execution results, CI integration
- **Medium Confidence**: Test strategy evaluation, design quality
- **Focus**: Reliability confidence and regression protection

### Dependency Management
- **High Confidence**: Vulnerability scanning, version analysis, update patterns
- **Medium Confidence**: Dependency necessity, risk assessment
- **Focus**: Operational stability and maintenance burden

## Common Workflows

### Needs-Driven Discovery
1. **Requirements elicitation** - Help users articulate their actual needs
2. **Search strategy** - Guide systematic server discovery approaches  
3. **Initial screening** - Apply basic quality filters to candidates
4. **Detailed evaluation** - Use relevant quality checks for promising options
5. **Selection support** - Help users make informed final decisions

### Targeted Evaluation
1. **Context gathering** - Understand why user is evaluating this specific server
2. **Server classification** - Determine server type and relevant evaluation criteria
3. **Quality assessment** - Apply appropriate checks with confidence calibration
4. **Fit analysis** - Evaluate alignment with user requirements
5. **Decision guidance** - Clear recommendation with reasoning

### Comparative Analysis
1. **Criteria establishment** - Define evaluation dimensions for comparison
2. **Systematic assessment** - Apply same checks across all candidates
3. **Structured comparison** - Organize findings for decision-making
4. **Trade-off analysis** - Help users understand compromises and choices
5. **Selection recommendation** - Guide final decision with clear reasoning

## Important Distinctions

### What This System IS:
- **Server discovery and selection aid** - Helps find appropriate servers
- **Quality assessment framework** - Evaluates maintenance, reliability, fit
- **Educational discovery tool** - Teaches server evaluation skills
- **Community intelligence hub** - Shares server reputation and quality insights

### What This System IS NOT:
- **Security audit tool** - Deep security analysis belongs in mcpserver-audit
- **Automated server recommender** - Emphasizes teaching over automation
- **Code analysis engine** - Uses quality indicators, not deep code review
- **Comprehensive testing suite** - Focuses on evaluation methodology, not testing

### Clear Handoffs
- **For security analysis** → `mcpserver-audit` repository
- **For server development** → `mcpserver-builder` resources  
- **For operational deployment** → Operations and management tools
- **For detailed technical review** → Code review and analysis tools

## Success Metrics

### User Outcomes
- Users can independently discover relevant MCP servers
- Users understand how to evaluate server quality and fit
- Users make informed server selection decisions
- Users contribute back to community intelligence

### System Improvement
- Real server evaluations validate methodology effectiveness
- Community contributions enhance discovery and evaluation capabilities
- User feedback improves teaching approaches and frameworks
- Pattern recognition leads to better quality indicators

## Future Development Priorities

### Critical Next Steps
1. **Real server evaluations** - Prove methodology with actual servers
2. **Discovery mechanisms** - Build practical server search capabilities
3. **Community intelligence** - Populate with real evaluation data
4. **Usage validation** - Test with real users and refine approach

### Long-term Vision
1. **Personalized discovery** - Adapt to user experience and context
2. **Automated quality monitoring** - Track server quality trends over time
3. **Community-driven intelligence** - Crowdsourced server insights and recommendations  
4. **Integration ecosystem** - Seamless handoffs to audit, build, and ops tools

---

**Remember**: This system teaches server discovery and evaluation skills while providing practical guidance. The goal is building user expertise in finding reliable, well-maintained MCP servers that fit their specific needs, with clear separation from detailed security analysis which belongs in companion tools.

*Last updated: 2025-08-13*