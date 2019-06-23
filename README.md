# vscode

## Extensions:

### 1) Export your VS Code extensions from terminal
Export your extensions to a shell file:

```sh
code --list-extensions | sed -e 's/^/code --install-extension /' > vscode_extensions.sh
```

### 2) Install your extensions

Run your `vscode_extensions.sh`:

```sh
bash vscode_extensions.sh
```

## Settings:

Navigate to settings.json and add this config --> [config json](https://github.com/AlberErre/vscode-import-export/blob/master/settings.json)
