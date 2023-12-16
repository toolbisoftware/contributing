# Contributing

When contributing to any repository whose `CONTRIBUTING.md` file links to this one you must follow this set of requirements, recommendations and guidelines to ensure code quality, safety and consistency.

> [!NOTE] The repository you want to contribute to may or may not have their own contribution guidelines. If it has you must follow them too.

## Requirements

In order to contribute you must have a set of tools and specific configurations for them and other things.

### Required

- [GitHub Account](https://github.com/signup): A GitHub account.
- [Git](https://git-scm.com/downloads): Control version tool.
- [Visual Studio Code](https://code.visualstudio.com/download): The code editor.
  - Extensions:
    - [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode): Formats files to follow a set of guidelines.
    - [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig): Configures Visual Studio Code's editor to follow a set of guidelines.
  - Configuration:
    - We decided to put the configuration inside the repositories to ensure consistency.

### Optional

- Visual Studio Code:
  - Extensions:
    - [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments): Improves comment readability by adding colors to them.
    - [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens): Shows the errors inline.
    - [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme): Adds icons to the files and folders.
    - [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight): Highlights the word `TODO`.
    - [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree): Adds a tab in the left sidebar called `TODOs` where you can see all the TODOs in the project.
    - [Trailing Spaces](https://marketplace.visualstudio.com/items?itemName=shardulm94.trailing-spaces): Shows trailing spaces.
- [GitHub Desktop](https://desktop.github.com/): Visual interface for Git.

## Setup

### Required

#### Git

1. Go to https://git-scm.com/downloads and click on your OS.
2. Launch the installer and follow the installation procedure. The default settings should be fine.

#### Visual Studio Code

1. Go to https://code.visualstudio.com/download and click on your OS.
2. Launch the installer and follow the installation procedure. The default settings should be fine.
3. Open Visual Studio Code.
4. In the left sidebar click on `Extensions` and search for the extensions listed above. Then click on the extension you want to install and click `Install`.

   Alternatively you can click the links of the extensions and they will open on the browser. Then click on `Install` and it should open on Visual Studio Code. Then click `Install` again.

### Recommended

#### GitHub Desktop

1. Go to https://desktop.github.com/ and click `Download for _`.
2. Launch the installer and follow the installation procedure.

## Post-setup

We are not too sure on how to explain it correctly so for the time being we will share the following guide: https://docs.github.com/get-started/exploring-projects-on-github/contributing-to-a-project

## Guidelines

### Code

- When creating a file you must include the following lines of code at the top of the file:
  ```
  Copyright (c) Toolbi Software. All rights reserved.
  Check the README file in the project root for more information.
  ```
  It must be commented out, preferably with the current language's shortest comment syntax. E.g.: JS -> `// `

### Formatting

- An empty line must be placed between the copyright notice, the imports and the actual code.

## Last update

`2023/12/16 - 17:58`

###### That's it for now. We have to figure a lot of things out before making this more detailed and strict. Make sure to pay a visit once in a while to be aware of any changes.
