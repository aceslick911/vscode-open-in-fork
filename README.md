# VSC Open in Fork

(Originally by morrislaptop https://github.com/morrislaptop/vscode-open-in-sourcetree - modified for Fork App)

Adds a command for opening the current project in [Fork](https://fork.dev/).

- Adds an icon to the status bar in the bottom right corner

- If there is a file open, it will open the git repo for that file
- If it is a workspace, it will ask you what folder you would like to open
- It will automatically find the best git repo to open

## Install

Run the following in the command palette:

```shell
ext install vscode-open-in-fork
```

## Usage

It adds 1 command to the command palette and 1 item to the context menu:

```js
'Open in Fork' // Open the current project in Fork
```

## Hints

Map `Open in Fork` action to this extension, add this to your `keybindings.json` file:

```json
  { "key": "⌘⌃S", "command": "openInFork.open" }
``````

## License
MIT - aceslick911
  MIT © Craig Morris
