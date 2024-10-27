# Contributing to Quix Language Files

Thank you for your interest in contributing to the Quix language files! This guide will help you fork the project, add new translations, or update existing ones.

## How to Fork the Project

1. **Fork the Repository**: Click the "Fork" button at the top right of the repository page to create a copy under your GitHub account.

2. **Clone the Repository**: Clone the forked repository to your local machine with the command:
    ```sh
    git clone https://github.com/themexpert/languages.git
    ```

3. **Navigate to the Project Directory**:
    ```sh
    cd languages
    ```

## Adding a New Language

1. **Locate the Language Files**: Go to the `administrator/` directory.

2. **Create a New Language File**: If your language isn’t present, copy the `en-GB` file and rename it to match your language shorthand, such as `es-ES` for **Spanish**. Then modify the copied file with your translations.

3. **Add Your Translations**: Use the format below to add translations:
    ```ini
    COM_QUIX_SOME_KEY_DO_NOT_CHANGE_THE_KEY = "Your translation text"
    ```
   Repeat this process for the `site/` directory.

## Updating Existing Translations

1. **Locate the Language File**: Find the language file you wish to update.

2. **Edit the Translations**: Update the translation text while keeping the keys unchanged. For example:
    ```ini
    COM_QUIX_SOME_KEY_DO_NOT_CHANGE_THE_KEY = "Updated translation text"
    ```

## Submitting Your Changes

1. **Commit Your Changes**:
    ```sh
    git add .
    git commit -m "Added/Updated translations for [language code]"
    ```

2. **Push Your Changes**:
    ```sh
    git push origin main
    ```

3. **Create a Pull Request**: Visit the original repository on GitHub and create a pull request to merge your changes.

Thank you for helping make Quix more accessible to users around the world !
