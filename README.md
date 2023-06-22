# h3llofr1end

An uncomfortably accurate VSCode theme inspired on the terminal preferences of Elliot Alderson.

![Elliot Alderson: The main character of the famous TV show "Mr. Robot".](https://image.tmdb.org/t/p/original/zxAc40mfE4vorZsMC2S7eIQrW6A.jpg)

## Installation

Due to Azure Devops' new account creation requisites (constrained free resources and only non-prepaid cards accepted) I can't upload the theme to the VSCode extension marketplace, so can't be installed from there. Use this altenative method instead:
1. Clone this repo.
2. Install [npm](https://www.npmjs.com/) and `vsce` with `npm install -g @vscode/vsce` if you don't have it.
3. Generate the *.vsix* file by executing `vsce package` command from this folder.
4. From a terminal execute `code --install-extension <path-to-vsix-file>` or from VSCode's command palette "Extension: Install from VSIX..." and select the *.vsix* file (more info [here](https://code.visualstudio.com/docs/editor/extension-marketplace#_install-from-a-vsix)).