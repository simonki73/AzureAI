# About
The repository is to share useful URL's about AI services within Azure.

## Develop AI agents on Azure
- [ ] [Develop AI agents on Azure](https://learn.microsoft.com/en-gb/training/paths/develop-ai-agents-on-azure/)
      The exercises for this module are here: https://microsoftlearning.github.io/mslearn-ai-agents/
  - [x] [Get started with AI agent development on Azure](https://learn.microsoft.com/en-gb/training/modules/ai-agent-fundamentals/)
    - Describe core concepts related to AI agents
    - Describe options for agent development
    - Create and test an agent in the Azure AI Foundry portal
    
     - [x] [Options for agent development](https://learn.microsoft.com/en-gb/training/modules/ai-agent-fundamentals/3-agent-development)
      Azure AI Foundry / OpenAI Assistants API/Microsoft Agent Framework/AutoGen/Microsoft 365 Agents SDK/Copilot Studio/ Copilot Studio Agent Builder
     - [x] [Exercise - Explore AI Agent development](https://microsoftlearning.github.io/mslearn-ai-agents/Instructions/01-agent-fundamentals.html)
    Upload a document and get an agent to answer questions about it
  - [ ] [Develop an AI agent with Azure AI Foundry Agent Service](https://learn.microsoft.com/en-gb/training/modules/develop-ai-agent-azure/)
    - Describe the purpose of AI agents
    - Explain the key features of Foundry Agent Service
    - Build an agent using the Foundry Agent Service (python)
    - Integrate an agent in the Foundry Agent Service into your own app
    ### Notes
    At a minimum, you need to create an Azure AI hub with an Azure AI project for your agent
    ### References
    - [x] Model selection: Developers can choose from various Azure OpenAI models AKA GPT ones: this page shows which regions support which models (useful if you try to create a project in Sweden Central but your policy blocks you). 
      - https://learn.microsoft.com/en-us/azure/ai-foundry/agents/concepts/model-region-support?tabs=global-standard#available-models
    - [x] Prefined Bicep templates: https://github.com/Azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.azure-ai-agent-service
    - [ ] Azure AI Foundry SDK client libraries(https://learn.microsoft.com/en-gb/azure/ai-foundry/how-to/develop/sdk-overview?pivots=programming-language-python)
    **Note:** the Azure AI Foundry SDK client link above shows you how to connect using Python but there seem to be steps missing. Try following the steps in tutorial [Develop an AI agent with Azure AI Foundry Agent Service]
    ### Exercises
    - [x] [Develop an AI agent](https://microsoftlearning.github.io/mslearn-ai-agents/Instructions/02-build-ai-agent.html) (Build an agent in Python that takes API calls)
  - [x] [Develop AI agents with the Azure AI Foundry extension in Visual Studio Code](https://learn.microsoft.com/en-gb/training/modules/develop-ai-agents-vs-code/)
    - Configure and deploy AI agents using the agent designer
    - Add tools and capabilities to extend your agents' functionality
    - Test agents using the integrated playground
    - Generate sample code to integrate agents into applications
    ### Notes
      You can install the Azure AI Foundry extension directly from the Visual Studio Code Marketplace:
      - Select Extensions from the left pane, or press Ctrl+Shift+X.
      - Search for and select Azure AI Foundry.

      The typical workflow for using the Azure AI Foundry extension follows these steps:
      - Install and configure the extension in Visual Studio Code
      - Connect to your Azure AI Foundry project
      - Create or import an AI agent using the designer
      - Configure agent instructions and add necessary tools
      - Test the agent using the integrated playground
      - Iterate on the design based on test results
      - Generate code for application integration

    **Azure AI Foundry Agent Service**   is a managed service in Azure designed to provide a comprehensive framework for creating, managing, and deploying AI agents. 
    ### Instruction examples
    For a customer service agent, effective instructions might include:
    - The agent's role and purpose
    - Guidelines for handling different types of customer inquiries
    - Escalation procedures for complex issues
    - Tone and communication style preferences
    ### Exercise ###
    - [x] [Develop an AI agent with VS Code extension](https://microsoftlearning.github.io/mslearn-ai-agents/Instructions/07-build-agent-in-vs-code.html)
    In this exercise, you’ll use the Azure AI Foundry VS Code extension to create an agent that can use Model Context Protocol (MCP) server tools to access external data sources and APIs. The agent will be able to retrieve up-to-date information and interact with various services through MCP tools
    ### Further reading ###
    - [ ] [Work with the Azure AI Foundry for Visual Studio Code extension (Preview)](https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/get-started-projects-vs-code/)
  - [x] [Integrate custom tools into your agent](https://learn.microsoft.com/en-gb/training/modules/build-agent-with-custom-tools/)
    - Describe the benefits of using custom tools with your agent.
    - Explore the different options for custom tools.
    - Build an agent that integrates custom tools using the Azure AI Foundry Agent Service.
    ### Exercise ###
    - [x] [Use a custom function in an AI agent](https://microsoftlearning.github.io/mslearn-ai-agents/Instructions/03-agent-custom-functions.html)
    ### Further reading ###
    - [ ] [AI Agents for beginners tool use](https://github.com/microsoft/ai-agents-for-beginners/blob/main/04-tool-use/README.md)
    - [ ] [Azure AI Foundry Agent Service function calling](https://learn.microsoft.com/en-us/azure/ai-services/agents/how-to/tools/function-calling)
    - [ ] [Introduction to Azure Functions](https://learn.microsoft.com/en-us/azure/azure-functions/functions-overview)
    - [ ] [OpenAPI Specification](https://swagger.io/specification/)
  - [ ] [Develop a multi-agent solution with Azure AI Foundry Agent Service](https://learn.microsoft.com/en-gb/training/modules/develop-multi-agent-azure-ai-foundry/)
  - [ ] [Integrate MCP Tools with Azure AI Agents](https://learn.microsoft.com/en-gb/training/modules/connect-agent-to-mcp-tools/)
  - [ ] [Develop an AI agent with Microsoft Agent Framework](https://learn.microsoft.com/en-gb/training/modules/develop-ai-agent-with-semantic-kernel/)
  - [ ] [Orchestrate a multi-agent solution using the Microsoft Agent Framework](https://learn.microsoft.com/en-gb/training/modules/orchestrate-semantic-kernel-multi-agent-solution/)
  - [ ] [Discover Azure AI Agents with A2A](https://learn.microsoft.com/en-gb/training/modules/discover-agents-with-a2a/)

## Develop generative AI apps in Azure

- [Develop generative AI apps in Azure](https://learn.microsoft.com/en-gb/training/paths/create-custom-copilots-ai-studio/)
  - Learn how to build generative AI applications that use language models to chat with your users.
  - [x] [Plan and prepare to develop AI solutions on Azure](https://learn.microsoft.com/en-gb/training/modules/prepare-azure-ai-development/)
    - Identify common AI capabilities that you can implement in applications 
    - Describe Azure AI Services and considerations for using them
    - Describe Azure AI Foundry and considerations for using it 
    - Identify appropriate developer tools and SDKs for an AI project
    - Describe considerations for responsible AI
  - [ ] [Choose and deploy models from the model catalog in Azure AI Foundry portal](https://learn.microsoft.com/en-gb/training/modules/explore-models-azure-ai-studio/)
    - Select a language model from the model catalog.
    - Deploy a model to an endpoint.
    - Test a model and improve the performance of the model.
  - [ ] [Develop an AI app with the Azure AI Foundry SDK](https://learn.microsoft.com/en-gb/training/modules/ai-foundry-sdk/)
    - Describe capabilities of the Azure AI Foundry SDK.
    - Use the Azure AI Foundry SDK to work with connections in projects.
    - Use the Azure AI Foundry SDK to develop an AI chat app.
  - [ ] [Get started with prompt flow to develop language model apps in the Azure AI Foundry](https://learn.microsoft.com/en-gb/training/modules/get-started-prompt-flow-ai-studio/)
    - Understand the development lifecycle when creating language model applications.
    - Understand what a flow is in prompt flow.
    - Explore the core components when working with prompt flow.
  - [ ] [Develop a RAG-based solution with your own data using Azure AI Foundry](https://learn.microsoft.com/en-gb/training/modules/build-copilot-ai-studio/)
    - Identify the need to ground your language model with Retrieval Augmented Generation (RAG)
    - Index your data with Azure AI Search to make it searchable for language models
    - Build an agent using RAG on your own data in the Azure AI Foundry portal
  - [ ] [Fine-tune a language model with Azure AI Foundry](https://learn.microsoft.com/en-gb/training/modules/finetune-model-copilot-ai-studio/)
    - Understand when to fine-tune a model.
    - Prepare your data to fine-tune a chat completion model.
    - Fine-tune a base model in the Azure AI Foundry portal.
  - [ ] [Implement a responsible generative AI solution in Azure AI Foundry](https://learn.microsoft.com/en-gb/training/modules/responsible-ai-studio/)
    - Describe an overall process for responsible generative AI solution development
    - Identify and prioritize potential harms relevant to a generative AI solution
    - Measure the presence of harms in a generative AI solution
    - Mitigate harms in a generative AI solution
    - Prepare to deploy and operate a generative AI solution responsibly
  - [ ] [Evaluate generative AI performance in Azure AI Foundry portal](https://learn.microsoft.com/en-gb/training/modules/evaluate-models-azure-ai-studio/)
    - Understand model benchmarks.
    - Perform manual evaluations.
    - Assess your generative AI apps with AI-assisted metrics.
    - Configure evaluation flows in the Azure AI Foundry portal.
- [ ] [What is Azure AI Foundry?](https://learn.microsoft.com/en-us/azure/ai-foundry/what-is-azure-ai-foundry)
- [ ] [Product Availability by Region](https://azure.microsoft.com/en-gb/explore/global-infrastructure/products-by-region/table)
- [ ] [Work with the Azure AI Foundry for Visual Studio Code extension (Preview)](https://learn.microsoft.com/en-us/azure/ai-foundry/how-to/develop/get-started-projects-vs-code) 
