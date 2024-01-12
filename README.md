# vscode-json5
> :new: So far, just a tiny update to add a custom icon to the language id (instead of the default plain text icon). Also updated readme quite a bit.

<!-- TODO:: change image  -->
<img style="display: block; float: none; margin-left: auto; margin-right: auto; margin-top: 15px; margin-bottom: 15px; width:80%;" src="https://github.com/katjanakosic/Screenshots/blob/main/Screenshot%202021-09-10%20at%2010.16.39.png?raw=true">

## Features

* Syntax highlight that includes comments! Invalid comments are highlighted are reported as errors, as any other issues.
* `.json5` files automatically associated to this extension, whereas `.json` has to be set manually.
* Colorization of the keys is different from the string values no matter if they are double or single quoted or not at all.
* Recognize comments around object values
* Custom icon from https://github.com/jesseweed/seti-ui

## Usage
> :hand: Install the extension

Then you can do any of the following to start using it...

* Change the current file *language mode*:
  * On the bottom-right corner, click on the select language mode button, if you have created a new file it should display Plain Text. ***Or just use the command*** ``Change Language Mode``
  * Select **JSON5** in the list of languages.
* Change the file extension to `.json5`, then vscode will automatically select the language mode.
* Change the language mode associated with `.json` or `.jsonc`
  * Careful! *json5* syntax is not usually valid for most json parsers, so you would be hiding potential format problems.

## Contributing
> :bulb: These simple rules will help me to solve your problem.

Check the **Issues** and **Pull requests** sections for duplicates of your question or path.

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
> :warning: See original repo/forks for detailed added features etc

See the [Releases section of my GitHub project](https://github.com/dimateos/vscode-json5/releases) for changelogs for each release version.

## License

This software is released under the terms of the MIT license.

<!-- :ghost: u found me, boo -->