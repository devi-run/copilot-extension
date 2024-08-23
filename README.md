<div align="center">

# What is devi?

[Homepage](https://github.com/devi-run/devi-github-copilot-extension) | [Documents](./docs/content/en/_index.md) | [Get Started](#get-started) | [中文](README_cn.md)

Devi is your AI agent building blocks. Building agentic workflow with generative AI is a new and innovative area, developers need to build many low level basic components before they can readlly focus on the actual valuable workflow. We want to simplify the complexity of this process by building a set of common AI agent components. 

![devi](https://aiseartifacts.blob.core.windows.net/devi/images/devi-title-logo.png)

</div>

# Devi for GitHub Copilot 
**Devi for GitHub Copilot** is a series of AI agents built on the GitHub Copilot ecosystem. Devi provides the atomic capabilities of these agents and developers can interact with devi through GitHub Copilot Chat as your common AI tool.
The **Devi DB Agent** is our first agent component to be released, providing developers with intelligent database Q&A and natural language database query capabilities (Text2SQL). 

<video 
    src="https://aiseartifacts.blob.core.windows.net/devi/videos/devi-demo-en.mp4" 
    style="width: 100%; height: auto; max-width:100%"
    controls>
</video>

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

1. Download the **embedding model** by tirggering the `Download Model` task.

    You can open the command palette by pressing `Ctrl+Shift+P` and type `Download Model` to download the embedding model. It will take a while to download the model and it will be saved to the `~/.devi` folder.

2. Setup your database connection by editing the `Settings.json` file.

    here is an example of the `Settings.json` file:

    ```json
        "devi.databaseSetting": {    
            "database": "test_db",
            "host": "127.0.0.1",
            "port": 3306,
            "user": "root",
            "password": "your password",
            "type": "mysql"
        },
    ```

Once you have completed the above steps, you can start using the Devi DB Agent in GitHub Copilot Chat by typing `@devi` and your query.

# Copyright

Devi is registered trademark of [leansoftx.com](https://leansoftx.com).

All rights reserved.