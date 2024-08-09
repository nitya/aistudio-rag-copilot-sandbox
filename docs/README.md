# Motivation

Generative AI applications are redefining user experiences across consumer and enterprise domains. In this project, we learn to build a **custom copilot** code-first on the Azure AI platform. 

 - A "copilot" is a generative AI solution that supports conversational interactions with users - i.e., it uses natural language inputs or prompts. 
 - A "custom" copilot is one that grounds those responses in your own data, allowing you to enforce quality and safety criteria to deliver responsible AI experiences.
 - A "code-first" approach emphasizes the use of developer tools (CLI, IDE) and libraries (SDK) to allow deeper configuration and customization of the copilot tech stack.
 - The "Azure AI platform" refers to the Azure AI Studio (UI, SDK and CLI) and supporting ecosystem of Foundation Models (catalog) and AI Services (integrations).

## Set the Stage - Retail + RAG
Let's focus on a specific application use case (**a retail copilot**) and a popular design pattern (**retrieval augmented generation or RAG**) as the basis for the implementation.

 - The retail copilot scenario involves an online retail store (Contoso Outdoors) that implements a **AI-based customer support agent** (Contoso Chat). 
 - The agent's responses must be grounded in the retailer's data - specifically its **product catalog** (index) and **customer purchase history** (DB).

Building generative AI solutions end-to-end requires a better understanding of the application lifecycle (LLM Ops) and developer tooling to streamline the provisioning, orchestration and deployment of complex flows. To learn this, you have two options:

 - **Build it up** - learn to construct it step-by-step, from scratch, using guided tutorials.
 - **Break it down** - learn by deconstructing a completed solution & figure out how it works.

Both options have value. The first teaches you the _recommended_ approach documented by the platform, tool, or service, provider. The second teaches you the _applied_ approach, using open-source projects to get a practical understanding of real-world decision-making and tradeoffs.

## Break It Down - Contoso Chat

Want to learn by breaking things down? Explore [Contoso Chat](https://aka.ms/aitour/contoso-chat), an open-source reference sample for the described retail copilot scenario - showcasing the following tools and features:

 - Application **design** with [Prompty](https://prompty.ai) templates.
 - Application **development** with [Promptflow](https://aka.ms/promptflow) flex flows.
 - Application **evaluation** with [Azure AI Studio](https://aka.ms/promptflow) tooling
 - Application **provisioning** and **deployment**  with [Azure Developer CLI](https://aka.ms/azd)

The sample comes with a README that has a table of contents with step-by-step instructions for exploring the sample from a live deployment, to local development.

## Build It Up - From Scratch

**This repository** will focus on the second option, building the solution up from scratch step-by-step, using a variety of tools and tutorials. This options also allows us to take detours at each step, exploring alternative approaches to achieve the same result to get a more comprehensive picture of the Azure AI platform and ecosystem.

The list below identifies some of the tutorials and documentation sites we will be using:

- [ ] [Quickstart: Create Azure AI Hub & Project from UI](https://learn.microsoft.com/en-us/azure/ai-studio/quickstarts/get-started-playground) - **Tutorial**
- [ ] [Quickstart: Create Azure AI Hub & Project from SDK](https://learn.microsoft.com/en-us/azure/ai-studio/how-to/develop/create-hub-project-sdk?tabs=python) - **Tutorial**
- [ ] [Build a RAG-based copilot with promptflow SDK](https://learn.microsoft.com/en-us/azure/ai-studio/tutorials/copilot-sdk-build-rag?tabs=azure-portal) - **Tutorial: Part 1**
- [ ] [Evaluate and deploy your copilot with promptflow SDK](https://learn.microsoft.com/en-us/azure/ai-studio/tutorials/copilot-sdk-evaluate-deploy) - **Tutorial: Part 2**
- [ ] [Build a custom chat app using promptflow SDK](https://learn.microsoft.com/en-us/azure/ai-studio/quickstarts/get-started-code?tabs=macos) - **Tutorial**
- [ ] [Copilot application that implements RAG](https://github.com/Azure-Samples/rag-data-openai-python-promptflow) - **Azure Samples**
- [ ] [Contoso Chat Retail Copilot Application](https://github.com/Azure-Samples/contoso-chat) - **Azure Samples**

!!!info "Collection: TBD"

    Watch this space for a link to a Microsoft Learn collection that captures all the required documentation and resources you will need for self-guided exploration of the workshop and related technologies and tools.
    
## Getting Started - Dev Containers

For convenience, the repository is configured with a `.devcontainer/devcontainer.json` file - defining all the necessary tools and dependencies required with a _configuration as code_ approach. This means all users of this repository get the exact same _prebuilt development environment_ with no added effort or complexity. Just pick one of these two options:

 - **Cloud Dev Environment** - launch with GitHub Codespaces, use anywhere.
 - **Local Dev Environment** - launch with Docker Desktop running, save on quota.

When you launch the development container, you will get a pre-configured Visual Studio Code editor with all the relevant extensions, CLI tools and SDK libraries installed.

Ready? Let's Go!