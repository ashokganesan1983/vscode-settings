# CoreZI VSCode

This repo contains default settings for VSCode application and necessary extensions for VSCode application.

## Clone the Repository

Clone the repository to your local machine:

```
git clone <repository-url>
cd <repository-directory>
```

Make sure to replace `<repository-url>` with the actual URL of your Git repository and `<repository-directory>` with the actual path.

## Visual Studio Code Configuration

The `.vscode` folder in the project contains configuration files to enhance your development experience in Visual Studio Code.

### .vscode/settings.json

The `settings.json` file contains workspace-specific settings for Visual Studio Code. These settings help you configure your development environment and customize the behavior of the editor.

To use the settings provided in this project:

    1. Open your project in Visual Studio Code.
    2. Go to the `.vscode` folder in your project directory.
    3. If the `settings.json` file does not exist, create a new file and name it `settings.json`.
    4. Copy the provided settings from `.vscode/settings.json` file in the repository into your `settings.json` file.
    5. Customize the settings according to your preferences.

For more information on configuring workspace settings in Visual Studio Code, refer to the <a href="https://code.visualstudio.com/docs/getstarted/settings">official documentation</a>.

### .vscode/extension.json

The `extension.json` file allows you to define recommended extensions for your workspace. These recommended extensions will be suggested to users who open the workspace in Visual Studio Code.

To use the recommended extensions provided in this project:

    1. Open your project in Visual Studio Code.
    2. Go to the `.vscode` folder in your project directory.
    3. If the `extension.json` file does not exist, create a new file and name it `extension.json`.
    4. Copy the provided content from `.vscode/extension.json` file in the repository into your `extension.json` file.
    5. Customize the `recommendations` section by adding or removing extension IDs as needed.

For more information on using `extension.json` to recommend extensions in Visual Studio Code, refer to the <a href="https://code.visualstudio.com/docs/editor/extension-marketplace#_workspace-recommended-extensions">official documentation</a>.

**Instructions:**

If you enable the `Prettier` extension, make sure to copy the following files to your project directory:

    - `.vscode/.prettierrc.json`: Prettier configuration file.
    - `.vscode/.prettierignore`: Prettier ignore file.

Similarly, if you enable the `ESLint` extension, copy the following file:

    - `.vscode/.eslintrc.json`: ESLint configuration file.
    - `.vscode/.eslintignore`: ESLint ignore file.

Make sure to customize these files according to your project's requirements.
