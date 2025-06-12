# Contributing to Awesome MCP Rust

Thank you for your interest in contributing to the Awesome MCP Rust list! This document provides guidelines for adding new projects and improving the list.

## How to Contribute

### Adding a New Project

1. **Fork** this repository
2. **Clone** your fork locally
3. **Add** your project to the appropriate section
4. **Commit** your changes with a descriptive message
5. **Submit** a pull request

### Project Categories

#### Servers
MCP server implementations that provide tools, resources, or prompts:
- Database servers (PostgreSQL, MySQL, SQLite, MongoDB)
- File system servers
- API integration servers (GitHub, OpenAI, AWS)
- Developer tool servers (Git, Docker, CI/CD)
- AI/ML servers (embeddings, vector databases)
- System administration servers

#### Clients
Applications that connect to MCP servers:
- Command-line clients
- Desktop applications
- Web applications
- Mobile applications
- IDE/editor integrations

#### Tools & Utilities
Development and debugging tools:
- Protocol inspectors and debuggers
- Testing frameworks
- Code generators
- Performance benchmarks
- Monitoring tools

#### Templates
Project templates for quick development:
- Server templates
- Client templates
- Integration templates

#### Examples
Demonstration code and tutorials:
- Basic usage examples
- Advanced integration patterns
- Real-world use cases

### Quality Standards

To maintain high quality, submissions should meet these criteria:

#### Technical Requirements
- ✅ **Uses official SDK**: Must use `mcp-protocol-sdk`
- ✅ **Rust best practices**: Follows idiomatic Rust patterns
- ✅ **Documentation**: Has clear README with usage instructions
- ✅ **Examples**: Includes usage examples or code samples
- ✅ **License**: Has an open source license
- ✅ **Active maintenance**: Shows recent activity or maintenance

#### Preferred (but not required)
- ✅ **Tests**: Has test coverage
- ✅ **CI/CD**: Has automated testing/building
- ✅ **Published**: Available on crates.io
- ✅ **Stable**: Production-ready quality

### Submission Format

Use this format when adding projects:

```markdown
- [Project Name](https://github.com/username/project) - Brief description of what the project does. 🟢
```

#### Status Indicators
- 🟢 **Stable** - Production ready, well-tested
- 🟡 **Beta** - Feature complete, needs more testing
- 🔴 **Alpha** - Under development, experimental
- ⚪ **Planned** - On roadmap, not yet started

#### Description Guidelines
- Keep descriptions concise (1-2 sentences)
- Focus on what the project does, not how
- Mention key features or unique aspects
- Use present tense
- Avoid marketing language

#### Examples

**Good:**
```markdown
- [postgres-mcp-server](https://github.com/user/postgres-mcp-server) - PostgreSQL database server with query execution and schema introspection tools. 🟢
```

**Bad:**
```markdown
- [postgres-mcp-server](https://github.com/user/postgres-mcp-server) - The best and most amazing PostgreSQL server you'll ever use! Revolutionary database access! 🟢
```

### Section Guidelines

#### Servers
Organize by functionality:
- File & Content Management
- Database Integration
- API Integration
- Developer Tools
- AI & ML Tools
- System Administration

#### Clients
Organize by platform:
- Desktop Applications
- Web Applications
- Mobile Applications
- IDE Integrations

#### Tools & Utilities
Organize by purpose:
- Debugging & Testing
- Code Generation
- Performance & Monitoring

### Review Process

1. **Automatic checks**: GitHub Actions will verify links and formatting
2. **Manual review**: Maintainers will check quality and appropriateness
3. **Feedback**: You may receive requests for changes
4. **Merge**: Approved submissions will be merged

### Guidelines for Maintainers

If you're a project maintainer wanting to list your project:

#### Before Submitting
- Ensure your project is stable and documented
- Add comprehensive README with examples
- Include installation and usage instructions
- Add tests if possible
- Consider publishing to crates.io

#### After Listing
- Keep your project maintained and updated
- Respond to issues and questions
- Update the awesome list if your project status changes
- Consider contributing to other projects in the ecosystem

### Community Guidelines

#### Be Respectful
- Respect other contributors and their work
- Provide constructive feedback
- Be patient with the review process

#### Be Helpful
- Help newcomers understand MCP and Rust
- Share knowledge and best practices
- Contribute to documentation improvements

#### Be Inclusive
- Welcome contributors from all backgrounds
- Use inclusive language
- Support diversity in the community

### Content Standards

#### What to Include
- ✅ MCP servers and clients written in Rust
- ✅ Tools that help with MCP development
- ✅ Templates for quick project setup
- ✅ Educational resources and examples
- ✅ Integration guides and patterns

#### What Not to Include
- ❌ Projects not related to MCP
- ❌ Projects not written in Rust
- ❌ Abandoned or unmaintained projects
- ❌ Proprietary or closed-source projects
- ❌ Spam or promotional content

### Link Guidelines

#### Repository Links
- Use GitHub repository URLs when available
- Ensure links are working and accessible
- Use HTTPS URLs

#### Documentation Links
- Link to comprehensive documentation
- Prefer official documentation over third-party
- Include API documentation links when available

#### Example Format
```markdown
- [Project Name](https://github.com/user/project) ([docs](https://docs.rs/project), [crates.io](https://crates.io/crates/project)) - Description. 🟢
```

### Commit Message Format

Use clear, descriptive commit messages:

```
Add new-project-name to servers section

- PostgreSQL integration server with advanced query tools
- Includes connection pooling and transaction support
- Well documented with examples
```

### Issue Reporting

If you find issues with listed projects:

1. **Check the project first**: Verify the issue exists
2. **Report to project**: File issues with the project maintainers
3. **Update awesome list**: If the project is abandoned, create a PR to remove it

### Recognition

Contributors will be recognized in several ways:
- Listed in the repository contributors
- Mentioned in release notes for significant contributions
- Featured in community updates

### Getting Help

If you need help with contributing:
- 💬 [GitHub Discussions](https://github.com/Rishirandhawa/awesome-mcp-rust/discussions)
- 🐛 [Issues](https://github.com/Rishirandhawa/awesome-mcp-rust/issues)
- 📧 Direct message to maintainers

Thank you for helping make the MCP Rust ecosystem awesome! 🦀
