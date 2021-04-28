# stage1-vscode-env
This is a repository designed to give students a quick start for stage 1 of the code-copy-examples app.<br>
It contains a `package.json` file to get the necessary modules with `npm install` as well as a workspace config for Visual Studio Code.

This config contains a specific task to quickly run Javascript files.<br>
To run that task, press `Ctrl+P` and type `task runFile` in the opened menu.<br>
You can also add a permanent shortcut to that command by adding this inside your VS Code `keybindings.json` file:
```json
{
  "key": "ctrl+j",
  "args": "runFile",
  "command": "workbench.action.tasks.runTask"
}
```
You can customize the keybindings to run Javascript files with the `key` argument.
