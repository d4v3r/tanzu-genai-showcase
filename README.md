# Tanzu GenAI Showcase

This repository contains multiple examples of applications that can be deployed on [Tanzu Platform for Cloud Foundry](https://techdocs.broadcom.com/us/en/vmware-tanzu/platform/tanzu-platform-for-cloud-foundry/10-0/tpcf/concepts-overview.html), demonstrating the use of [GenAI tile](https://techdocs.broadcom.com/us/en/vmware-tanzu/platform-services/genai-on-tanzu-platform-for-cloud-foundry/10-0/ai-cf/index.html)'s LLM capabilities.

## Overview

Each subdirectory in this repository represents a different tech stack implementation showcasing how to integrate with GenAI LLM services. These examples cover a variety of use cases, from chatbots and recommendation systems to research assistants and event discovery applications.

## Project Samples

| Link | Description | Languages and Frameworks |
|------|-------------|--------------------------|
| 🚗[![Transportation](https://img.shields.io/badge/-Transportation-blue?style=flat-square&logo=dotnet)](./dotnet-extensions-ai/README.md) | A transportation mode recommendation bot that helps users choose the best way to travel between locations. | .NET, Microsoft.Extensions.AI, Semantic Kernel |
| 📰[![News Aggregator](https://img.shields.io/badge/-News_Aggregator-blue?style=flat-square&logo=javascript)](./js-langchain-react/README.md) | A news aggregation application that searches for articles and generates concise summaries. | JavaScript, LangChain, React |

## Getting Started

Each tech stack implementation includes its own README.md with specific instructions for:

* Prerequisites
* Local development setup
* Building and testing
* Deploying to Tanzu Platform for Cloud Foundry

## Common Structure

All example projects follow a similar structure and address the following aspects:

1. **What is it?** - A description of the application and its capabilities
2. **Prerequisites** - Required tools, dependencies, and environment setup
3. **Building** - How to build and package the application
4. **Local Development** - Running and testing the application locally
5. **Deployment** - Deploying to Tanzu Platform for Cloud Foundry
6. **Tech Stack** - Detailed information about the technologies used
7. **Project Structure** - Explanation of the repository organization

## Deployment on Tanzu Platform for Cloud Foundry

All examples are designed to be deployable with `cf push` and can be bound to a GenAI LLM service instance.

### Service Binding

The examples demonstrate two approaches to consuming LLM services:

1. **Service Instance Binding**: Applications are bound to an LLM service instance, and the credentials are automatically injected.
2. **Manual Configuration**: Service keys are created and the applications are manually configured to use those credentials.

## Contributing

Feel free to add new tech stack examples or improve existing ones.

