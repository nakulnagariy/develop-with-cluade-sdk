# Prompt Engineering

Part of the **Cloud Architecture Certificate** course — **Developing with the Claude SDK** module.

This section focuses on prompt engineering techniques: how to effectively communicate with Claude to get reliable, structured, and high-quality outputs for cloud-related tasks.

## About This Course

This repository is a hands-on companion to the Cloud Architecture Certificate program. The **Developing with the Claude SDK** module teaches how to integrate Anthropic's Claude into real-world cloud workflows using Python, covering everything from basic API usage to building production-ready AI-powered tools.

### Modules

| Module | Description |
|---|---|
| `prompt-evaluation/` | Building and running automated prompt evaluations |
| `prompt-engineering/` | Techniques for writing effective prompts _(this module)_ |

## Topics Covered

- Basic prompt structure and best practices
- System prompts and role assignment
- Few-shot prompting
- Chain-of-thought reasoning
- Output formatting and structured responses
- Temperature and parameter tuning

## Prerequisites

- Python 3.8+
- Anthropic SDK (`pip install anthropic`)
- A valid `ANTHROPIC_API_KEY` set in a `.env` file

## Getting Started

```bash
pip install anthropic python-dotenv
```

Create a `.env` file in the root of the project:

```
ANTHROPIC_API_KEY=your_api_key_here
```

## Structure

```
prompt-engineering/
└── README.md
```
