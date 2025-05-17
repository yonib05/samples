<h2 align="center">Strands Agents Samples&nbsp;</h2>
<p align="center">
  :wave: :wave: Welcome to Strands Agents Samples repository :wave: :wave:
</p>

> [!CAUTION]
> The examples provided in this repository are for experimental and educational purposes only.
> They demonstrate concepts and techniques but are not intended for direct use in production environments.
> Make sure to have Amazon Bedrock Guardrails in place to protect against [prompt injection](https://docs.aws.amazon.com/bedrock/latest/userguide/prompt-injection.html).

This repository provides examples for working with the [Strands Agents](https://www.strandsagents.com/).

Strands Agents is an python SDK that takes a model-driven approach to building and running AI agents in just a few lines of code.

## Table of Contents

- [Overview](#overview)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Strands Agents examples](#agents-examples)
- [Best Practices](#best-practices)
- [Related Links](#related-links-)
- [Security](#security)
- [License](#license)

## Overview

<summary>
<h2>Repository Structure</h2>
</summary>

```bash
├── examples/01-getting-started/
│   ├── 00-first-agent
|   └── ....
├── examples/02-agents/
│   ├── 01-restaurant-assistant/
|   └── ....
├── examples/03-multi-agent-collaboration/
│   ├── 01-finance-assistant-swarm-agent/
|   └── ....
├── examples/04-integrations/
│   ├── 01-nova-sonic-integration/
|   └── ....
```

## Getting Started

The easiest way to get started is via `01-getting-started` samples. In this folder you will find some
notebook-driven samples for different functionalities of Strands Agents.

Create your [first agent](01-getting-started/00-first-agent) with Strands Agents to start using the SDK.

Independently of the sample used, you will need to install [Strands Agents SDK](https://github.com/strands-agents/agents-sdk-python).
You can also install [Strands Agents Tools](https://github.com/strands-agents/agents-tools) for exploring some built-in tools

To install Strands Agents and Strands Agents tools you can use pip:

```commandline
pip install strands-agents
pip install strands-agents-tools
```

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This project is licensed under the Apache-2.0 License.

> [!IMPORTANT]
> Examples in this repository are for demonstration purposes.
> Ensure proper security and testing when deploying to production environments.
