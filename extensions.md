# How to export your VS Code extensions from terminal

_**Note:** [Unix-like systems](https://en.wikipedia.org/wiki/Operating_system#Unix_and_Unix-like_operating_systems) only._

Export your extensions to a shell file:

```sh
code --list-extensions | sed -e 's/^/code --install-extension /' > vscode_extensions.sh
```

### Install your extensions

Run your `vscode_extensions.sh`:

```sh
bash vscode_extensions.sh
```
