<div align="center">
  <h1>
    Aurora DSQL Starter Kit
  </h1>

  <h2>
    Documentation and resources for Amazon Aurora DSQL
  </h2>

  <p>
    <a href="https://docs.aws.amazon.com/aurora-dsql/">AWS Documentation</a>
    ◆ <a href="https://console.aws.amazon.com/dsql">AWS Console</a>
    ◆ <a href="https://aws.amazon.com/rds/aurora/dsql/">Product Page</a>
  </p>
</div>

## Overview

Amazon Aurora DSQL is a serverless, distributed SQL database optimized for transactional workloads. This starter kit provides comprehensive documentation and resources to help you get started with Aurora DSQL.

## 📚 Documentation

This repository contains documentation built with [MkDocs](https://www.mkdocs.org/) and the Material theme, following AWS documentation best practices.

## 🚀 What is Aurora DSQL?

Amazon Aurora DSQL is a serverless, distributed SQL database that provides:

- **Serverless Architecture** - No infrastructure to manage
- **Distributed Design** - Built for high availability and scalability
- **PostgreSQL Compatibility** - Use familiar PostgreSQL tools and syntax
- **Multi-Region Support** - Deploy across multiple AWS regions
- **ACID Compliance** - Full transactional consistency

## 📖 Getting Started

Check out the [Getting Started Guide](docs/guides/getting-started/quickstart.md) to:

1. Create your first Aurora DSQL cluster
2. Connect to your cluster
3. Run your first queries
4. Set up multi-region clusters

## AI Rules

This repository also contains AI rules that can help create a more seamless agentic developing experience with DSQL. The recommended paths are to either use the Kiro Power or the Claude Skill, thought the 
[dsql-skill](/ai-rules/skills/dsql-skill/) can also be repurposed for other coding assistants. 

### Kiro Power

To setup the Kiro power, simply launch the power installer from the [Powers Registry](https://kiro.dev/launch/powers/aurora-dsql/). You'll be redirected to the Power in your Kiro IDE where you can select the **`Try Power`** button 
for an interactive onboarding experience complete with MCP setup or you can prompt Kiro from any project about 
DSQL and the agent will automatically activate the power. 

### Claude Skill

The recommended setup is outlined in [skill_setup.md](/ai-rules/skills/skill_setup.md). This method uses a sparse
clone of the skill folder alone symlinked into the desired `.claude/skills/` folder which also means the latest
changes can be consistently pulled in to update the skill. 

## 📝 License & Contributing

- **License:** 
  - Documentation: CC BY-SA 4.0 - see [LICENSE](LICENSE)
  - Sample Code: MIT-0 - see [LICENSE-SAMPLECODE](LICENSE-SAMPLECODE)
  - Full details: [LICENSE-SUMMARY](LICENSE-SUMMARY)
- **Contributing:** See [CONTRIBUTING.md](CONTRIBUTING.md)
- **Security:** See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for security issue notifications
