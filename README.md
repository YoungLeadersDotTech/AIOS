# AIOS - AI Operating System

An intelligent Slack bot with unified knowledge integration, designed to provide seamless access to organizational data and AI-powered insights.

## Overview

AIOS is a production-ready Slack bot that integrates multiple data sources (Snowflake, Salesforce, Chorus, Crayon) with AI capabilities to provide intelligent responses and insights directly within Slack.

## Architecture

- **Dual Lambda Pattern**: Separate authentication and worker lambdas for scalability
- **Async Processing**: Slack Bolt async framework for responsive interactions
- **Secure Secrets Management**: AWS Secrets Manager integration
- **Multi-Source Integration**: Unified access to data warehouses and CRM systems

## Key Features

- Natural language queries to organizational data
- AI-powered insights using Google Gemini
- Secure authentication and authorization
- Production-ready deployment with Terraform
- Comprehensive logging and monitoring

## Development Status

🚧 **In Active Development** - Repository setup and infrastructure configuration in progress.

## Documentation

- [Setup Guide](docs/setup.md) - Coming soon
- [Architecture Overview](docs/architecture.md) - Coming soon
- [Contributing Guide](CONTRIBUTING.md) - Coming soon

## License

MIT License - See [LICENSE](LICENSE) for details.

## Getting Started

Full setup and development instructions will be available once the initial infrastructure is configured.

---

**Note**: This is a personal project repository. For Toast-specific deployment information, see internal documentation.
