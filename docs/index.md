# Overview

!!!example "Workshop Objectives"

    This series of hands-on labs teaches you to build, configure, evaluate, deploy, and use, a **custom copilot** built code-first with Azure-AI, using the RAG (Retrieval Augmented Generation) design pattern, for a retail store scenario. The instructions follow guidance from the [Azure AI Studio documentation](https://learn.microsoft.com/en-us/azure/ai-studio/tutorials/copilot-sdk-build-rag?tabs=azure-portal) and the [Contoso Chat](https://aka.ms/aitour/contoso-chat) application sample.

    This is a **self-serve** workshop for completion at your own pace. The instructions will emphasize a _happy path_ to get you quickly to the desired goal of a deployed copilot. However, exercises may offer _alternative paths_ for exploration of new tools, models etc. that are intended to build your comprehension and intuition.

    This lab **may be used in instructor-led sessions** at physical events. In that case, some steps (e.g., provisioning of infrastructure) may be completed for you. Refer to the instructor guidance at the event for next steps.

## What You'll Learn

By the end of this workshop you should be able to:

 - Describe the **Azure AI Studio** platform and developer tooling
 - Describe the **LLMOps workflow** and end-to-end application lifecycle
 - Build, evaluate, and deploy, a **custom RAG-based copilot** code-first
 - Understand how to customize or adapt the solution with **your own data**.


## What You'll Need

You will need a laptop for this lab, along with:

 - A **GitHub account** (with GitHub Codespaces access)
 - An **Azure account** (with Azure OpenAI access)
 - A **modern browser** (to run GitHUb Codespaces)
 - Familiarity with **Visual Studio Code** (recommended IDE)
 - Familiarity with **Python and Jupyter Notebooks** (default SDK)

## What You'll Do

By the end of this workshop, you should know how to build a custom copilot application, code-first, using Azure AI tools and services. This includes being able to execute these steps for an end-to-end developer workflow (LLMOps):

1. **Define It** - Describe the prioritized scenarios and data requirements.
1. **Provision It** - Setup required infrastructure & local dev environment.
1. **Develop It** - Use best-in-class developer tools to prototype prompts, flow.
1. **Evaluate It** - Validate prototype for quality & safety, learn key metrics.
1. **Deploy it** - Deploy AI application for hosted API endpoint, test it out.
1. **Deliver it** - Explore Monitoring (App Insights), Safety (Content Filters).

## Under The Hood

Want to learn more about the key tools and concepts used in this workshop? Watch this Microsoft Build 2024 breakout talk for a deep dive into LLMOps and code-first development.

!!!info "BRK110: Abstract"

    Learn how to get from prototype to production with LLMOps and new developer tools for iterative debugging, evaluation, deployment, and monitoring. We’ll test and troubleshoot a copilot app using the code-first prompt flow SDK and frameworks like LangChain, interactively debugging an LLM chat application with VS Code. Then we’ll make sure it meets our thresholds for performance and safety, ship it, and ensure we can collect critical signals in production.

    <iframe width="1000" height="420" src="https://www.youtube.com/embed/gvqsPhd27LE" title="Code-First LLMOps from prototype to production with GenAI tools | BRK110" allowfullscreen></iframe>    

## Key Resources

Check out these links to useful tutorials and documentation for self-guided learning.

- [ ] [Quickstart: Create Azure AI Hub & Project from UI](https://learn.microsoft.com/en-us/azure/ai-studio/quickstarts/get-started-playground) - **Tutorial**
- [ ] [Quickstart: Create Azure AI Hub & Project from SDK](https://learn.microsoft.com/en-us/azure/ai-studio/how-to/develop/create-hub-project-sdk?tabs=python) - **Tutorial**
- [ ] [Build a RAG-based copilot with promptflow SDK](https://learn.microsoft.com/en-us/azure/ai-studio/tutorials/copilot-sdk-build-rag?tabs=azure-portal) - **Tutorial: Part 1**
- [ ] [Evaluate and deploy your copilot with promptflow SDK](https://learn.microsoft.com/en-us/azure/ai-studio/tutorials/copilot-sdk-evaluate-deploy) - **Tutorial: Part 2**
- [ ] [Build a custom chat app using promptflow SDK](https://learn.microsoft.com/en-us/azure/ai-studio/quickstarts/get-started-code?tabs=macos) - **Tutorial**
- [ ] [Copilot application that implements RAG](https://github.com/Azure-Samples/rag-data-openai-python-promptflow) - **Azure Samples**
- [ ] [Contoso Chat Retail Copilot Application](https://github.com/Azure-Samples/contoso-chat) - **Azure Samples**

!!!info "Collection: TBD"

    Watch this space for a link to a Microsoft Learn collection that captures all the required documentation and resources you will need for self-guided exploration of the workshop and related technologies and tools.

---

**Next Steps |** Get Started  🚀