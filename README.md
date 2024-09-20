<div align="center">

# What is devi?

[Homepage](https://github.com/devi-run/devi-github-copilot-extension) | [Documents](./docs/content/en/_index.md) | [Get Started](./docs/content/en/copilot/_index.md) | [中文](README_zh.md)

Devi is your AI agent building blocks. Building agentic workflow with generative AI is a new and innovative area, developers need to build many low level basic components before they can readlly focus on the actual valuable workflow. We want to simplify the complexity of this process by building a set of common AI agent components. 

![devi](https://aiseartifacts.blob.core.windows.net/devi/images/devi-title-logo.png)

</div>

# Devi for GitHub Copilot 
**Devi for GitHub Copilot** is a series of AI agents built on the GitHub Copilot ecosystem. Devi provides the atomic capabilities of these agents and developers can interact with devi through GitHub Copilot Chat as your common AI tool.
The **Devi DB Agent** is our first agent component to be released, providing developers with intelligent database Q&A and natural language database query capabilities (Text2SQL). 

> Note：As this is a GitHub Copilot extension, you need to have GitHub Copilot installed in your Visual Studio Code to use this extension. Devi itself is a free extension, but you need to pay for the GitHub Copilot subscription.

Demo Video: [Devi for GitHub Copilot](https://aiseartifacts.blob.core.windows.net/devi/videos/devi-demo-en.mp4)

# Features
Developers can use `@devi` to invoke these capabilities in GitHub Copilot, including:

## Chat with your Database
Automatically identify the database structure and allow users to ask questions about the database in natural language, e.g.: 
- What is this database used for?
- Which database objects are related to each other?

![What is this database used for?](https://aiseartifacts.blob.core.windows.net/devi/images/devi-en-us01.png)

![Which database objects are related to each other?](https://aiseartifacts.blob.core.windows.net/devi/images/devi-en-us02.png)

## DB Query with Natural Language (Text2SQL)
Generate database queries with natural language (Text2SQL), users can use natural language to ask questions, and `@devi` will generate SQL statements based on the database schema，e.g.:
- Help me generate a summary query of all apps and the corresponding number of reviews
- Help me generate a list of all users with the most reviews, with descending order

![Help me generate a summary query of all apps and the corresponding number of reviews](https://aiseartifacts.blob.core.windows.net/devi/images/devi-en-us03.png)
![Help me generate a list of all users with the most reviews, with descending order](https://aiseartifacts.blob.core.windows.net/devi/images/devi-en-us04.png)

### Database Document Generation
Generate standard database documents via built-in `@devi /docs <table_name>` shortcuts

![@devi /docs](https://aiseartifacts.blob.core.windows.net/devi/images/devi-en-us05.png)

# Get Started

Once you have installed the **Devi for GitHub Copilot**, there are 2 simple steps to get started:
Once you have installed the **Devi for GitHub Copilot**, there are 2 simple steps to get started:

1. Click on the `devi` icon on the toolbar to configure your MySQL database connection.

    ![](https://aiseartifacts.blob.core.windows.net/devi/images/devi_config.png)

    After configuration is completed, click `Save`. You can also click the `Refresh` button to refresh the vector index of the database.
    
    If it is the first time to use the devi plugin, the `Download Model` task will be automatically started at this time. After the model is downloaded, the vector indexing process for the database structure will be automatically started. If you see the following information, it means that the configuration is completed and you can start a conversation.

    ![](https://aiseartifacts.blob.core.windows.net/devi/images/devi_config_done.png)


2. You can also manually start the `Download Model` task to complete the download action of the embedded model.

    You can open the command palette by pressing `Ctrl+Shift+P` and typing `Download Model` to download the embedding model. Downloading the model takes some time and it will be saved to the `~/.devi` folder.

Once you have completed the above steps, you can start using the Devi DB Agent in GitHub Copilot Chat by typing `@devi` and your query.

# Copyright

Devi is registered trademark of [leansoftx.com](https://leansoftx.com).

All rights reserved.