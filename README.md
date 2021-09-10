# vscode-json5

> This extension adds syntax highlighting of JSON5 files in VS Code based on this repository: https://github.com/mrmlnc/vscode-json5.

## Colorization

> Here's what changed: The colorisation of the keys is now different from the string values no matter if they are double or single quoted or not at all. Following screenshots show the before and after:


Before adjustment:

![JSON5 syntax in VS Code before](https://cloud.githubusercontent.com/assets/7034281/19013821/e8150e9a-87e4-11e6-9127-e9ec7c989c86.png)

(imported from [Atom package](https://github.com/wiredmax/language-json5))

After adjustment:

![JSON5 syntax coloring in VS Code after adjustment](https://github.com/katjanakosic/Screenshots/blob/main/Screenshot%202021-09-10%20at%2010.16.39.png?raw=true)

## Usage

### Install the extension in VS Code

  * Open the command palette using <kbd>Ctrl+P</kbd>.
  * Type `ext install json5` in the command palette.

### Select **JSON5** as a language

  * On the bottom-right corner, click on the select language mode button, if you have created a new file it should display Plain Text.
  * Select **JSON5** in the list of languages.
  * Alternatively, saving the file with a `.json5` extension, will allow VS Code to understand that it is a JSON5 file, and automatically select the language correctly.

### Supported features

  * Syntax highlight

### Supported filetypes

  * `.json5`

## Contributing

> These simple rules will help me to solve your problem.

  * Check the **Issues** and **Pull requests** sections for duplicates of your question or path.
  * If you want create **Issue**:
    * Specify the version of your editor and used theme.
    * Detailed description of your problem:
      * Description
      * Code sample
      * Screenshot
  * If you want create **Pull request**:
    * Fork this repository and clone it to your machine.
    * Open folder contains this extension in VS Code.
    * Press <kbd>F5</kbd>.
    * Make your changes and send a PR.

## Changelog

See the [Releases section of my GitHub project](https://github.com/katjanakosic/vscode-json5/releases) for changelogs for each release version.

## License

This software is released under the terms of the MIT license.
