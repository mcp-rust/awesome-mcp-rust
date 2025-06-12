# Awesome MCP Rust [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome MCP (Model Context Protocol) implementations, servers, clients, and tools in Rust.

## Contents

- [Official Libraries](#official-libraries)
- [Servers](#servers)
- [Clients](#clients)  
- [Tools & Utilities](#tools--utilities)
- [Templates](#templates)
- [Examples](#examples)
- [Integrations](#integrations)
- [Learning Resources](#learning-resources)
- [Contributing](#contributing)

## Official Libraries

### Core SDK
- [mcp-protocol-sdk](https://github.com/Rishirandhawa/mcp-protocol-sdk) - Production-ready Rust SDK for the Model Context Protocol

### Transports
- **STDIO** - Built into core SDK, for Claude Desktop integration
- **HTTP** - Built into core SDK, for web-based clients
- **WebSocket** - Built into core SDK, for real-time applications

## Servers

### Official Reference Servers
- [File Server](https://github.com/Rishirandhawa/mcp-protocol-sdk/blob/main/examples/simple_server.rs) - File system operations and content access
- [Echo Server](https://github.com/Rishirandhawa/mcp-protocol-sdk/blob/main/examples/echo_server.rs) - Simple demonstration and testing server
- [Database Server](https://github.com/Rishirandhawa/mcp-protocol-sdk/blob/main/examples/database_server.rs) - Database query and operations
- [HTTP Server](https://github.com/Rishirandhawa/mcp-protocol-sdk/blob/main/examples/http_server.rs) - RESTful API integration server
- [WebSocket Server](https://github.com/Rishirandhawa/mcp-protocol-sdk/blob/main/examples/websocket_server.rs) - Real-time communication server

### Community Servers

#### File & Content Management
*Looking for contributions! Be the first to add your MCP server here.*

#### Database Integration
*Looking for contributions! PostgreSQL, MySQL, SQLite, MongoDB servers welcome.*

#### API Integration  
*Looking for contributions! GitHub, OpenAI, AWS, Google Cloud servers welcome.*

#### Developer Tools
*Looking for contributions! Git, Docker, Kubernetes, CI/CD servers welcome.*

#### AI & ML Tools
*Looking for contributions! LLM integration, embedding, vector database servers welcome.*

#### System Administration
*Looking for contributions! System monitoring, log analysis, infrastructure servers welcome.*

## Clients

### Official Reference Clients
- [CLI Client](https://github.com/Rishirandhawa/mcp-protocol-sdk/blob/main/examples/client_example.rs) - Command-line MCP client
- [HTTP Client](https://github.com/Rishirandhawa/mcp-protocol-sdk/blob/main/examples/http_client.rs) - HTTP transport client
- [WebSocket Client](https://github.com/Rishirandhawa/mcp-protocol-sdk/blob/main/examples/websocket_client.rs) - WebSocket transport client

### Community Clients

#### Desktop Applications
*Looking for contributions! Desktop MCP clients welcome.*

#### Web Applications  
*Looking for contributions! Browser-based MCP clients welcome.*

#### Mobile Applications
*Looking for contributions! iOS/Android MCP clients welcome.*

#### IDE Integrations
*Looking for contributions! VS Code, Vim, Emacs integrations welcome.*

## Tools & Utilities

### Development Tools
*Looking for contributions! MCP debugging, testing, validation tools welcome.*

#### Debugging & Testing
- MCP Inspector - *Planned: Traffic inspection and debugging tool*
- MCP Proxy - *Planned: Protocol proxy with logging and modification*
- MCP Validator - *Planned: Protocol compliance testing tool*

#### Code Generation
- [Server Template](https://github.com/Rishirandhawa/mcp-server-template) - Cargo generate template for MCP servers
- [Client Template](https://github.com/Rishirandhawa/mcp-client-template) - Cargo generate template for MCP clients

#### Performance & Monitoring
*Looking for contributions! Performance benchmarking and monitoring tools welcome.*

## Templates

### Project Templates
- [mcp-server-template](https://github.com/Rishirandhawa/mcp-server-template) - Complete server template with cargo-generate support
- [mcp-client-template](https://github.com/Rishirandhawa/mcp-client-template) - Complete client template with CLI interface

### Usage
```bash
# Install cargo-generate
cargo install cargo-generate

# Create a new MCP server
cargo generate Rishirandhawa/mcp-server-template

# Create a new MCP client  
cargo generate Rishirandhawa/mcp-client-template
```

## Examples

### Basic Examples
- [Echo Server](https://github.com/Rishirandhawa/mcp-protocol-sdk/blob/main/examples/echo_server.rs) - Simplest possible MCP server
- [Simple Client](https://github.com/Rishirandhawa/mcp-protocol-sdk/blob/main/examples/client_example.rs) - Basic client implementation

### Advanced Examples
- [Database Integration](https://github.com/Rishirandhawa/mcp-protocol-sdk/blob/main/examples/database_server.rs) - SQL query execution
- [File Operations](https://github.com/Rishirandhawa/mcp-protocol-sdk/blob/main/examples/simple_server.rs) - File system tools
- [Real-time Communication](https://github.com/Rishirandhawa/mcp-protocol-sdk/blob/main/examples/websocket_server.rs) - WebSocket server

### Integration Examples
- [Claude Desktop Integration](https://github.com/Rishirandhawa/mcp-protocol-sdk/blob/main/docs/integrations/claude-desktop.md) - Setup guide for Claude Desktop
- HTTP API Server - REST API integration patterns
- Microservice Architecture - Multi-server coordination

## Integrations

### AI Platforms
- **Claude Desktop** - STDIO integration for Anthropic's Claude Desktop
- **Cursor IDE** - Development assistant integration
- **VS Code** - Extension development framework

### Development Tools
- **GitHub Actions** - CI/CD integration examples
- **Docker** - Containerized MCP servers
- **Kubernetes** - Scalable MCP deployments

### Databases
- **PostgreSQL** - SQL database integration
- **SQLite** - Embedded database support
- **MongoDB** - Document database integration
- **Redis** - Key-value store integration

### Cloud Platforms
- **AWS** - Lambda functions, S3, RDS integration
- **Google Cloud** - Cloud Functions, BigQuery integration
- **Azure** - Functions, Cosmos DB integration

## Learning Resources

### Documentation
- [MCP Specification](https://modelcontextprotocol.io/) - Official protocol documentation
- [Rust SDK Documentation](https://docs.rs/mcp-protocol-sdk) - Complete API reference
- [Getting Started Guide](https://github.com/Rishirandhawa/mcp-protocol-sdk/blob/main/docs/getting-started.md) - Beginner tutorial

### Tutorials
- [Building Your First MCP Server](https://github.com/Rishirandhawa/mcp-protocol-sdk/blob/main/docs/examples.md) - Step-by-step tutorial
- [Client Development Guide](https://github.com/Rishirandhawa/mcp-protocol-sdk/blob/main/docs/clients/) - Client implementation patterns
- [Architecture Deep Dive](https://github.com/Rishirandhawa/mcp-protocol-sdk/blob/main/docs/architecture.md) - Understanding MCP architecture

### Community
- [GitHub Discussions](https://github.com/Rishirandhawa/mcp-protocol-sdk/discussions) - Questions and community support
- [Issues & Bugs](https://github.com/Rishirandhawa/mcp-protocol-sdk/issues) - Bug reports and feature requests

### Blog Posts & Articles
*Looking for contributions! Write about your MCP Rust experience.*

### Videos & Talks
*Looking for contributions! Conference talks, tutorials, demos welcome.*

## Development Status

### Stability Levels
- 🟢 **Stable** - Production ready
- 🟡 **Beta** - Feature complete, testing needed
- 🔴 **Alpha** - Under development
- ⚪ **Planned** - On roadmap

### Current Status
- 🟢 Core SDK - Production ready
- 🟢 STDIO Transport - Stable
- 🟢 HTTP Transport - Stable  
- 🟢 WebSocket Transport - Stable
- 🟡 Templates - Beta
- ⚪ Inspector Tool - Planned
- ⚪ Proxy Tool - Planned

## Contributing

We welcome contributions of all kinds! Here's how you can help:

### Adding Your Project

1. **Servers**: Add your MCP server implementation
2. **Clients**: Add your MCP client application
3. **Tools**: Add development, debugging, or utility tools
4. **Examples**: Add practical implementation examples
5. **Integrations**: Add platform or service integrations

### Submission Guidelines

1. Fork this repository
2. Add your project to the appropriate section
3. Include:
   - Clear description
   - GitHub repository link
   - Crates.io link (if published)
   - Documentation link
   - Status indicator (🟢🟡🔴⚪)
4. Follow the existing format
5. Submit a pull request

### Quality Standards

To be included, projects should:
- ✅ Use the official mcp-protocol-sdk
- ✅ Have clear documentation
- ✅ Include examples or usage instructions
- ✅ Follow Rust best practices
- ✅ Have tests (preferred)
- ✅ Be actively maintained

### Categories

When adding projects, place them in the most appropriate category:
- **Official** - Created by the SDK maintainers
- **Community** - Third-party implementations
- **Examples** - Demonstration code
- **Templates** - Boilerplate projects

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Rishi Randhawa has waived all copyright and related or neighboring rights to this work.

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Rishirandhawa/awesome-mcp-rust&type=Date)](https://star-history.com/#Rishirandhawa/awesome-mcp-rust&Date)

---

*Made with ❤️ by the Rust MCP community*

## Related Awesome Lists

- [Awesome MCP](https://github.com/punkpeye/awesome-mcp) - General MCP resources (all languages)
- [Awesome Rust](https://github.com/rust-unofficial/awesome-rust) - General Rust resources
- [Awesome AI](https://github.com/owainlewis/awesome-artificial-intelligence) - AI and ML resources
