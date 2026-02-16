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
