# Contribute

CWTools is an Open Source, community project, written for modders by modders 🙂. If you want to help the project, you are invited to contribute. You can help with adding support for new Paradox Interactive games, updating existing support for games, or helping improve the underlying language server and extension.

## Found a bug?

Create an issue in the specific [game's repo](./projects), or for general issues in the [extension repo here >](https://github.com/cwtools/cwtools-vscode/issues) and describe the problem you have encountered.

## Helpful skills

Contributing is much easier then you might think. Only a handful of helpful skills are recommended.

* Basic programming knowledge to faster understand how the tools work
* Basic knowledge of Git is useful to share your code with us

## Help with a specific game

1. Choose what [game](./projects) you want to contribute to
2. Clone the repository to a filepath, e.g. D:\Git\cwtools-ck3-config or copy the contents of the zip you can download. *Pro Tip: Fork the repo*
3. Open VS Code, and go to File, Preferences, Settings
    1. (Optional) To make the changes only apply to this folder (not all folders on your computer), change the tab at the top to "workspace settings"
4. Set "cwtools.rules_version" to "manual"
5. Set "cwtools.rules_folder" to the path above. e.g. D:\Git\cwtools-ck3-config
6. Re-open VS Code. Now you are using the rules you have copied (a.k.a. cloned) to your computer.
7. Open the vanilla game files in one window (or alternatively your mod), and open the rules folder in another window.
8. Add/change rules that are defined in e.g. D:\Git\cwtools-ck3-config.
9. Once you make changes to the rules, you can press "Ctrl-shift-p" and select "Reload window" to easily restart the extension.
10. Confirm errors are reduced, return to step 8.

Look at the [CW Tools Wiki](https://github.com/cwtools/cwtools/wiki) for [guidance on the file format](https://github.com/tboby/cwtools/wiki/.cwt-config-file-guidance).

## Help wanted for various other subjects

* [Improving the extension onboarding experience](https://github.com/cwtools/cwtools-vscode/issues/36)

## Uploading your changes
If you're familiar with git, simply make a Pull Request agains the appropriate repo.

Otherwise, find the file you want to edit on GitHub and press the pen icon. Make your changes and press "Create a new branch for this commit and start a pull request". You can then make further changes as a "pull request". When done, mention it in the pull request and your changes will be included.

*Pro Tip: Submit a PR from your forked repository*