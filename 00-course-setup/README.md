# Getting Started with this course

We are very excited for you to start this course and see what you get inspired to build with Generative AI!

To make your time successful, we have created this page that outlines any setup steps, technical requirements, and how to get help when you need it.

## Setup Steps

To start taking this course, you will need to complete the following steps.

### 1. Fork this Repo

[Fork this entire repo](https://github.com/microsoft/generative-ai-for-beginners/fork) to your own GitHub account to be able to change any code and complete the challenges. You can also [star (🌟) this repo](https://docs.github.com/en/get-started/exploring-projects-on-github/saving-repositories-with-stars) to find it and related repos easier.

### 2. Create a codespace

To avoid any dependency issues when running the code, we recommend running this course in a GitHub codespace.

This can be created by selecting the `Code` option on your forked version of this repo and selecting the **Codespaces** option.

### 3. Storing Your API Keys

Keeping your API keys safe and secure is important when building any type of application. We encourage you not to store any API keys directly in the code you are working with as committing those details to a public repository could result in unwanted costs and issues.

![Dialog showing buttons to create a codespace](./images/who-will-pay.webp)

## How to Run locally on your computer

To run the code locally on your computer, you would need to have some version of Python installed. I personally recommend installing **[miniconda](https://conda.io/en/latest/miniconda.html)** - it is rather lightweight installation that supports `conda` package manager for different Python **virtual environments**.

After you install miniconda, you need to clone the repository and create a virtual environment to be used for this course:

```bash
git clone https://github.com/microsoft/generative-ai-for-beginners
cd generative-ai-for-beginners
conda env create --name ai4beg --file .devcontainer/environment.yml
conda activate ai4beg
```

### Using Visual Studio Code with Python Extension

Probably the best way to use the curriculum is to open it in [Visual Studio Code](http://code.visualstudio.com/?WT.mc_id=academic-77998-bethanycheum) with [Python Extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python&WT.mc_id=academic-77998-bethanycheum).

> **Note**: Once you clone and open the directory in VS Code, it will automatically suggest you to install Python extensions. You would also have to install miniconda as described above.

> **Note**: If VS Code suggests you to re-open the repository in container, you need to decline this to use local Python installation. 

### Using Jupyter in the Browser

You can also use Jupyter environment right from the browser on your own computer. Actually, both classical Jupyter and Jupyer Hub provide quite convenient development environment with auto-completion, code highlighting, etc.

To start Jupyter locally, go to the directory of the course, and execute:
```bash
jupyter notebook
```
or
```bash
jupyterhub
```
You then can navigate to any of the `.ipynb` files, open them and start working.

### Running in container

An alternative to Python installation would be to run the code in container. Since our repository contains special `.devcontainer` folder that instructs how to build a container for this repo, VS Code would offer you to re-open the code in container. This will require Docker installation, and also would be more complex, so we recommend this to more experienced users.

One of the best ways to keep your API keys secure when using GitHub Codespaces is by using Codespace Secrets. Please follow this guide on how to [manage secrets for your codespaces](https://docs.github.com/en/codespaces/managing-your-codespaces/managing-secrets-for-your-codespaces).

## Lessons and Technical Requirements

The course has 6 concept lessons and 6 coding lessons.

For the coding lessons, we are using the Azure OpenAI Service. You will need access to the Azure OpenAI service and an API key to run this code. You can apply to get access by [completing this application](https://customervoice.microsoft.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbR7en2Ais5pxKtso_Pz4b1_xUOFA5Qk1UWDRBMjg0WFhPMkIzTzhKQ1dWNyQlQCN0PWcu&culture=en-us&country=us).

While you wait for your application to be processed, each coding lesson also includes a `README.md` file where you can view the code and outputs.

## Using the Azure OpenAI Service for the First Time

If this is your first time working with the Azure OpenAI service, please follow this guide on how to [create and deploy an Azure OpenAI Service resource.](https://learn.microsoft.com/azure/ai-services/openai/how-to/create-resource?pivots=web-portal&WT.mc_id=academic-105485-koreyst)

## Meet Other Learners

We have created channels in our official [AI Community Discord server](https://aka.ms/genai-discord) for meeting other learners. This is a great way to network with other like-minded entrepreneurs, builders, students, and anyone looking to level up in Generative AI.

[![Join discord channel](https://dcbadge.vercel.app/api/server/ByRwuEEgH4)](https://aka.ms/genai-discord)

The project team will also be on this Discord server to help any learners.

## Contribute

This course is an open-source initiative. If you see areas of improvement or issues, please create a [Pull Request](https://github.com/microsoft/generative-ai-for-beginners/pulls) or log a [Github issue](https://github.com/microsoft/generative-ai-for-beginners/issues).

The project team will be tracking all contributions and contributing to open source is an amazing way to build your career in Generative AI.

Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit [CLA, Contributor License Agreement website](https://cla.microsoft.com).

Important: when translating text in this repo, please ensure that you do not use machine translation. We will verify translations via the community, so please only volunteer for translations in languages where you are proficient.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repositories using our CLA.

This project has adopted the Microsoft Open Source Code of Conduct. For more information read the Code of Conduct FAQ or contact [Email opencode](opencode@microsoft.com) with any additional questions or comments.

## Let's Get Started

Now that you have completed the needed steps to complete this course, let's get started by getting an [introduction to Generative AI and LLMs](../01-introduction-to-genai/README.md).
