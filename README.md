# MCP Server Finder

**Discovery and evaluation tool for finding reliable, well-maintained MCP servers that fit your specific needs - because with so many servers available, you need the right one for your requirements.**

## Why This Tool Exists

**Anyone can create MCP servers and Desktop Extensions** - no programming experience required. Here's how easy it is:

### Example: Building a Desktop Extension (No Programming Needed)

As Anthropic states in their [official blog post](https://www.anthropic.com/engineering/desktop-extensions):

> "Internally at Anthropic, we have found that Claude is great at building extensions with minimal intervention. If you too want to use Claude Code, we recommend that you briefly explain what you want your extension to do and then add the following context to the prompt:"

Simply paste this into Claude or any AI assistant:

```
I want to build this as a Desktop Extension, abbreviated as "DXT". Please follow these steps:

1. **Read the specifications thoroughly:**
   - https://github.com/anthropics/dxt/blob/main/README.md - DXT architecture overview, capabilities, and integration patterns
   - https://github.com/anthropics/dxt/blob/main/MANIFEST.md - Complete extension manifest structure and field definitions
   - https://github.com/anthropics/dxt/tree/main/examples - Reference implementations including a "Hello World" example

2. **Create a proper extension structure:**
   - Generate a valid manifest.json following the MANIFEST.md spec
   - Implement an MCP server using @modelcontextprotocol/sdk with proper tool definitions
   - Include proper error handling and timeout management

3. **Follow best development practices:**
   - Implement proper MCP protocol communication via stdio transport
   - Structure tools with clear schemas, validation, and consistent JSON responses
   - Make use of the fact that this extension will be running locally
   - Add appropriate logging and debugging capabilities
   - Include proper documentation and setup instructions

4. **Test considerations:**
   - Validate that all tool calls return properly structured responses
   - Verify manifest loads correctly and host integration works

Generate complete, production-ready code that can be immediately tested. Focus on defensive programming, clear error messages, and following the exact DXT specifications to ensure compatibility with the ecosystem.
```

**The AI will write the entire extension for you.** No coding knowledge required.

## Project Status: Proof of Concept with Solid Foundation

**Current Status:** This project is in the proof-of-concept phase, but we have high confidence in the approach. The methodology, templates, and assessment frameworks are complete and thoroughly designed. **This is not a question of "can it work?" - it's a matter of building out the practical implementation.**

**What's Proven:** 
- ✅ **Methodology works** - Educational approach and confidence-based assessment framework are solid
- ✅ **Templates are comprehensive** - Quality checks and prompts cover all major evaluation areas
- ✅ **Framework is complete** - Self-improving system design and repository separation are clear

**What's Still Needed:** 
- 🚧 **Real server evaluations** - Need to demonstrate the system working on actual MCP servers  
- 🚧 **Discovery mechanisms** - Need practical ways to find and index servers systematically
- 🚧 **Path portability** - Need to make the system work for users beyond the original development environment

**Why We're Confident:** The core challenge was designing a sound approach to server quality assessment and user education. That foundation is solid. The remaining work is straightforward implementation - applying our proven methodology to real servers and building the tooling to make it accessible.

**Timeline:** Ready to demonstrate methodology and framework now. Practical implementation underway - see [TODO.md](./TODO.md) for specific next steps.

## The Challenge: Finding the Right Server

With the growing MCP ecosystem, there are many servers available for different purposes. **The challenge is finding ones that are:**

- **Well-maintained** - Active development and responsive maintainers
- **Fit for purpose** - Match your specific requirements and use case
- **Reliable** - Work consistently and handle errors gracefully  
- **Quality** - Well-built with good documentation and practices
- **Compatible** - Work with your MCP client and environment

## The Solution: Systematic Discovery and Evaluation

This tool helps you **find and evaluate MCP servers** to choose the right ones for your needs:
- Discover servers that match your requirements
- Assess quality, maintenance status, and reliability
- Compare options systematically
- Learn evaluation skills for ongoing server selection

### What This Tool Does

- **Discover quality servers** - Find MCP servers that are well-maintained and fit your requirements
- **Assess fitness for purpose** - Evaluate if servers match your specific needs and use case
- **Compare options systematically** - Use structured criteria to compare different servers
- **Learn evaluation skills** - Develop expertise in selecting good MCP servers over time

## Who Needs This Tool

**Everyone in the MCP ecosystem:**

- **Users seeking functionality** - Find servers that provide the capabilities you need
- **Organizations evaluating tools** - Assess servers before adoption in business workflows
- **Developers building integrations** - Choose reliable servers for your applications
- **Community contributors** - Discover quality servers to recommend to others

## Expert-Guided Approach

This MCP server is designed as an **expert advisor and tutor** in its domain, with the primary focus on providing guidance, education, and practical recommendations rather than being a comprehensive implementation tool. While it includes enough functional capability to be immediately useful and demonstrate real expertise, the long-term vision is for this server to serve as your domain expert who helps you understand the landscape, evaluate options, and find the right tools for your specific needs. As the MCP ecosystem evolves, this server will learn about new tools and approaches, recommending the best solutions while teaching you how to evaluate and use them effectively. The broader Model Context Protocol Security initiative may also develop comprehensive implementation tools, but these specific repositories are focused on being practical expert guidance systems—combining deep domain knowledge with enough hands-on capability to provide genuine value, not just theoretical advice.

## Key Capabilities

### Educational Guidance
- **Requirements Analysis Tutoring**: Teaches you how to define and articulate your needs clearly
- **Evaluation Criteria Education**: Explains what makes a good MCP server and what to look for
- **Red Flag Recognition**: Helps you identify potential security concerns and quality issues
- **Decision-Making Framework**: Guides you through structured approaches to server selection
- **Best Practices Teaching**: Shares knowledge about effective MCP server usage patterns

### Practical Discovery
- **Basic Server Search**: Can search GitHub, MCP registries, and community resources
- **Simple Analysis**: Performs basic evaluation of server characteristics and documentation
- **Comparison Support**: Helps compare different servers against your criteria
- **Gap Identification**: Identifies when no suitable servers exist for your needs
- **Community Intelligence**: Accesses information about server reputation and usage

### Expert Orchestration
- **Tool Recommendations**: Suggests specialized discovery and analysis tools when needed
- **Resource Guidance**: Points you to additional resources and information sources
- **Expert Referrals**: Connects you with other domain experts when appropriate
- **Methodology Sharing**: Teaches you advanced discovery and evaluation techniques
- **Ecosystem Navigation**: Helps you understand the broader MCP landscape

## Goals and Teaching Approach

### Primary Educational Goals

1. **Develop Evaluation Skills**: Teach users how to assess MCP servers independently
2. **Build Requirements Definition Capability**: Help users articulate their needs clearly
3. **Foster Security Awareness**: Educate about security considerations in server selection
4. **Promote Best Practices**: Share knowledge about effective MCP server usage
5. **Enable Informed Decisions**: Provide frameworks for making good choices
6. **Build Community Knowledge**: Contribute to collective understanding of MCP server quality

### Teaching Strategies

#### 1. Interactive Learning
- **Socratic Method**: Asks questions to help you discover the right criteria
- **Guided Discovery**: Walks you through the evaluation process step by step
- **Hands-On Practice**: Provides opportunities to apply learned concepts
- **Immediate Feedback**: Offers corrections and improvements to your approach
- **Progressive Complexity**: Starts simple and builds to more sophisticated analysis

#### 2. Practical Application
- **Real-World Examples**: Uses actual MCP servers to illustrate concepts
- **Case Studies**: Analyzes both good and problematic server examples
- **Scenario-Based Learning**: Presents different use cases and contexts
- **Problem-Solving**: Helps you work through actual selection challenges
- **Skill Building**: Develops your ability to evaluate servers independently

#### 3. Knowledge Sharing
- **Best Practices Communication**: Shares proven approaches and techniques
- **Common Pitfalls**: Warns about frequent mistakes and how to avoid them
- **Expert Insights**: Provides professional perspectives on server evaluation
- **Community Wisdom**: Shares collective knowledge from the MCP community
- **Continuous Learning**: Stays current with ecosystem developments

## Expert Knowledge Areas

### MCP Server Evaluation
- **Quality Indicators**: What characteristics indicate a well-built server
- **Security Considerations**: How to assess security implications and risks
- **Compatibility Assessment**: Understanding client compatibility and protocol adherence
- **Performance Factors**: Evaluating efficiency and resource requirements
- **Maintenance Status**: Assessing project health and long-term viability

### Requirements Analysis
- **Needs Assessment**: How to clearly define what you're trying to accomplish
- **Constraint Identification**: Understanding limitations and requirements
- **Priority Setting**: Determining what matters most for your use case
- **Trade-off Analysis**: Balancing different factors and requirements
- **Success Criteria**: Defining what constitutes a successful server choice

### Ecosystem Navigation
- **Discovery Sources**: Where to find MCP servers and how to search effectively
- **Community Resources**: Leveraging community knowledge and recommendations
- **Vendor Evaluation**: Assessing different types of server sources and maintainers
- **Integration Patterns**: Understanding how servers fit into broader workflows
- **Future Planning**: Considering long-term implications of server choices

## Practical Workflow

### Phase 1: Requirements Discovery and Education
1. **Need Analysis Tutorial**: Interactive session to help define your requirements
2. **Context Understanding**: Learn about your specific use case and constraints
3. **Criteria Education**: Teach relevant evaluation criteria for your situation
4. **Priority Setting**: Help you understand what matters most for your needs
5. **Success Definition**: Establish clear criteria for a successful server choice

### Phase 2: Guided Discovery and Research
1. **Search Strategy**: Teach effective approaches for finding relevant servers
2. **Basic Discovery**: Perform initial searches across known sources
3. **Evaluation Teaching**: Guide you through assessing discovered servers
4. **Comparison Framework**: Help you compare options systematically
5. **Red Flag Detection**: Identify potential concerns and teach recognition skills

### Phase 3: Analysis and Decision Support
1. **Detailed Evaluation**: Deep dive into promising candidates
2. **Risk Assessment**: Evaluate security and operational considerations
3. **Fit Analysis**: Assess how well options match your requirements
4. **Trade-off Discussion**: Help you understand compromises and decisions
5. **Recommendation Reasoning**: Explain the logic behind suggestions

### Phase 4: Implementation Guidance and Next Steps
1. **Selection Validation**: Confirm your choice makes sense for your needs
2. **Implementation Planning**: Guidance on next steps for using the chosen server
3. **Risk Mitigation**: Advice on addressing identified concerns
4. **Monitoring Recommendations**: What to watch for after implementation
5. **Learning Reinforcement**: Summarize key lessons and skills developed

## Basic Functional Capabilities

### Discovery Functions
- **Search Orchestration**: Guides you through using built-in search capabilities (GitHub, web search via Claude Desktop/MCP clients)
- **Registry Navigation**: Teaches effective strategies for finding servers in MCP registries and directories  
- **Documentation Analysis**: Structured approach to evaluating server documentation quality and completeness
- **Metadata Interpretation**: Framework for understanding and comparing server characteristics
- **Community Intelligence**: Methods for assessing reputation, adoption, and community feedback

### Analysis Functions
- **Structured Evaluation**: Guides you through systematic server assessment using our quality checks
- **Documentation Quality Framework**: Methodical approach to evaluating documentation completeness and clarity
- **Activity Pattern Analysis**: Teaching how to interpret project activity and maintenance status indicators
- **Compatibility Assessment**: Framework for evaluating MCP protocol compliance and client compatibility
- **Risk Pattern Recognition**: Education on identifying common security and quality concerns

### Guidance Functions
- **Interactive Consultation**: Conversational guidance through decision-making
- **Structured Comparison**: Systematic comparison of server options
- **Requirement Matching**: Alignment of servers with user needs
- **Decision Documentation**: Recording of evaluation rationale and decisions
- **Learning Progress**: Tracking of user skill development and knowledge gaps

## Integration with Ecosystem

### Learning from Other Experts
- **mcpserver-audit**: Leverage security assessment expertise for comprehensive evaluation
- **mcpserver-builder**: Understand development best practices and quality indicators
- **mcpserver-operator**: Learn about operational requirements and deployment considerations
- **Community Knowledge**: Leverage collective experience and recommendations

### Teaching Preparation for Next Steps
- **Audit Preparation**: Prepare users for security evaluation of chosen servers
- **Implementation Planning**: Set up users for successful deployment and operation
- **Development Insights**: Provide context for potential customization or development
- **Operational Readiness**: Ensure users understand deployment and maintenance implications

## Expert Development and Learning

### Continuous Knowledge Updates
- **Ecosystem Monitoring**: Stay current with new servers and developments
- **Community Engagement**: Learn from user experiences and feedback
- **Expert Consultation**: Incorporate insights from security and development experts
- **Best Practice Evolution**: Adapt guidance based on emerging patterns and lessons
- **Tool Integration**: Learn about new discovery and analysis tools

### Teaching Methodology Improvement
- **Effectiveness Assessment**: Evaluate how well users learn and apply knowledge
- **Approach Refinement**: Improve teaching methods based on user success
- **Curriculum Development**: Enhance educational content and progression
- **Feedback Integration**: Incorporate user feedback into teaching approaches
- **Skill Assessment**: Better understanding of user knowledge gaps and needs

## How to Use This System

### Quick Walkthrough

**1. Choose Your Approach:**
- **Need-Based Discovery**: Start with `read ./prompts/needs-driven-discovery.md` if you need to find servers for specific requirements
- **Server Evaluation**: Use `read ./prompts/targeted-evaluation.md` if you already have a specific server to assess
- **General Guidance**: Use `read ./prompts/main-prompt.md` for overall MCP server guidance

**2. Apply Quality Checks:**
- Browse `./checks/` directory for available quality assessments
- Each check includes automated scripts and manual evaluation guidance
- Current checks: GitHub repository health, code quality, test quality, dependency management
- Use confidence levels (High/Medium/Low) to calibrate your trust in findings

**3. Reference Research & Resources:**
- `./research/` contains evaluation templates and capability frameworks
- `./resources/` has structured checklists and decision frameworks
- Many checklists exist but don't have dedicated check files yet - **great contributor opportunity!**

**4. Leverage External Tools:**
- Discovery capabilities (GitHub search, web search) are built into Claude Desktop and other MCP clients
- File analysis and code review leverage your AI assistant's existing capabilities
- This system provides the methodology; your tools provide the execution power

**5. Contribute Back:**
- Add real server evaluation results to `./data-db/` (coming soon)
- Submit audit findings to the companion `mcpserver-audit` repository
- Help us learn from your discoveries and improve the assessment framework

### Quick Start Examples

**Find Tools by Need** (discover what's available):
```
read ./prompts/needs-driven-discovery.md and help me find MCP servers for [DESCRIBE YOUR NEED]
```

**Evaluate Specific Tool** (detailed analysis):
```
read ./prompts/targeted-evaluation.md and evaluate the MCP server [SERVER_NAME]
```

**Apply Quality Check** (assess specific quality aspect):
```
read ./checks/github-repository-health.md and assess the repository health of [SERVER_NAME]
```

### For Tool Creators

**Building MCP Servers**: Use AI assistance with our quality assessment guidance to create well-built, secure servers

**Building Desktop Extensions**: Follow the DXT specification with our quality and security guidance (see the development prompt example at the beginning of this README)

**Then use our assessment tools** to verify your creation meets quality standards. For detailed security analysis, use the companion `mcpserver-audit` tool.

### System Requirements

- **Claude Desktop** or other MCP-compatible AI client
- **File system access** to read the assessment guides and security checks
- **Internet access** for researching and discovering tools (optional but helpful)

## Learn More

### Key Resources
- **[Desktop Extensions Blog Post](https://www.anthropic.com/engineering/desktop-extensions)** - Official introduction to building Claude Desktop Extensions
- **[DXT GitHub Repository](https://github.com/anthropics/dxt)** - Complete specifications and examples for Desktop Extensions
- **[Model Context Protocol](https://modelcontextprotocol.io/)** - Official MCP documentation and specifications

### Our Security-First Approach

This tool is part of the **Model Context Protocol Security** initiative - a community project focused on making MCP tools safer and more reliable. We emphasize:

- **Education over automation** - Teaching you to evaluate tools yourself
- **Quality awareness** - Helping you recognize reliable, well-maintained servers  
- **Community knowledge** - Sharing insights about tool quality and safety
- **Continuous improvement** - Getting better through real-world usage

### Personalized Discovery (Future Vision)

**Long-term goal**: Make the discovery and evaluation process adapt to each user's specific needs, experience level, and use cases.

Since this is an AI-powered tool, we can build discovery capabilities that customize themselves to you:
- **Adapt to your experience** - Beginners get more explanation, experts get focused analysis
- **Match your role** - Different guidance for developers vs. business users vs. system administrators
- **Learn your preferences** - Remember what evaluation criteria matter most to you
- **Focus on your context** - Emphasize the quality aspects most relevant to your use case
- **Evolve with you** - Become more sophisticated as your server evaluation expertise grows

**AI enables personalized discovery at scale** - the same tool can be a patient guide for newcomers and an efficient expert advisor for professionals, adapting in real-time to what each user needs to find the right server.

### Quality Assessment Approach

Our evaluation approach focuses on **practical server selection criteria**:

**Quality Indicators**: We systematically assess key quality factors:
- **Maintenance patterns** - Active development, responsive maintainers, regular updates
- **Code quality** - Clean code, good practices, comprehensive testing
- **Documentation quality** - Clear setup instructions, usage examples, troubleshooting guides
- **Community health** - User adoption, issue response times, community engagement

**Reliability Assessment**: We evaluate operational reliability:
- **Error handling** - How servers handle failures and edge cases
- **Performance patterns** - Resource usage, response times, scalability considerations
- **Compatibility** - MCP protocol compliance, client compatibility, version support
- **Deployment readiness** - Installation process, configuration options, operational requirements

**The goal**: Create an assessment system that helps users find servers that will work reliably in their specific context and continue to be maintained over time.

### Contributing

We welcome contributions that help users make better server choices:

**High-Priority Contributions:**
- **Real server evaluations** - Apply our methodology to actual MCP servers and share results
- **New quality checks** - Many checklists in `./resources/` need corresponding check files in `./checks/`
- **Discovery examples** - Document successful server finding strategies and search patterns
- **Assessment integration** - Submit detailed evaluation findings to the companion `mcpserver-audit` repository for community learning

**Other Valuable Contributions:**
- **Teaching improvements** based on user feedback and real usage
- **Examples** of good and bad server patterns discovered in the wild  
- **Community intelligence** about server reputation, adoption, and quality trends
- **Methodology refinements** based on practical application experience

---

*Part of the [Model Context Protocol Security](https://modelcontextprotocol-security.io/) initiative - A Cloud Security Alliance community project.*

