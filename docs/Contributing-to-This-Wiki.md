# Contributing to this Wiki

## Before contributing

This is the official and open-source wiki for the modpack Star Technology. Anyone can contribute to it, but before you do, you need to follow these ground rules:

1. Do not make troll submissions.
2. Do not create new pages on the wiki without asking the devs for permission.
3. Do not contribute any content that is the intellectual property of another party (such as images, diagrams, etc) without permission from its original creator.

## Prerequisites

- [Git](https://git-scm.com/downloads) - A version control system that allows you to push changes to the GitHub repository.
- [Visual Studio Code](https://code.visualstudio.com/download) - A code editor integrated with Git with plenty of extensions to assist you.
- [GitHub Account](https://github.com/) - The platform hosting the repository for this wiki.
- [Python](https://www.python.org/downloads/) - The programming language that makes this wiki work.

## Preparing the workspace

!!! Note
    This wiki uses [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) to generate documentation from markdown pages.

1. Fork the [repository](https://github.com/StarT-Dev-Team/StarT-Wiki).
2. Open Visual Studio Code.
3. From the *Welcome* page, click on **Clone Git repository**, select **Clone from GitHub**, and select `YOUR-NAME/StarT-Wiki`.
4. Open a new terminal from the toolbar.
5. Run the following commands:

    - To create the environment:

        ```console
        python -m venv venv
        ```

    - To activate the environment:

        === "Windows"

            ```console
            .\venv\Scripts\activate
            ```

        === "Mac"

            ```console
            source venv/bin/activate
            ```

    - To install Material for MkDocs:

        ```console
        pip install mkdocs-material
        ```

6. Run this command to launch the app:
    ```console
    mkdocs serve
    ```
    You can now access your local wiki copy at [http://127.0.0.1:8000/](http://127.0.0.1:8000/), and any changes you make will be reflected in the browser automatically. To stop the app, press `Ctrl+C` in the terminal.
7. Once you are finished making changes, commit them and open a pull request to the main repository.

## Useful resources

- [Material for MkDocs reference page](https://squidfunk.github.io/mkdocs-material/reference/)
- GitHub Docs pages for [working with forks](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) and [creating pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork)

## Style Guide
When contributing to the wiki, please follow these rules/considerations to maintain consistent formatting throughout the whole wiki

1. Flowcharts

    - Use mermaid flowcharts for machines/processing lines that use more than 1 recipe. do not clutter the page with image after image (Left--> Right flowcharts for short processes. Top --> Down flowcharts for processes that are long/have many branches)

    - Represent processes as the JEI recipe images (Use the EMI screenshot feature).

    - Don't list the whole processing line. For example, you don't need to mention how to get oxygen. Players can use JEI or look at the related page.

    - Represent inputs as lean right text boxes, and outputs as lean left boxes

    - Make sure to mention exact inputs and outputs. (buckets and item amounts)



2. Resource production
    - Use flowcharts

    - Don't mention every single way to get something. Think of your own playthrough, or ask #beginners-chat. Only list the most relevant ways to get something 
    
    - For example, there is no need to list every recipe that gives hydrogen as a byproduct. Instead just mention it in brief.

    - If there are multiple ways to get a resource (progression based, like radon), then list them in the order you would get them

    - In short, don't mention every single way to get a resource, just the most relevant ones, in the order you unlock them.

3. General notes

    - Include your name on the page you created as the author. If you collaborated with someone, then include both names. If you edited a page that you didn't create, do not include your name. You may include your name in the credits page as a contributor

    - In your screenshots do not use mods that are not available in the pack and you added yourself. Avoid using texture packs.
    
    - Don't include things from other packs (such as comparisons). This is purely StarT wiki