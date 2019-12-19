You need Custom CSS Loader to apply this extension, like [Vibrancy](https://marketplace.visualstudio.com/items?itemName=eyhn.vscode-vibrancy).

## Usage

1. Press `F1` then type "settings json" and press `ENTER`.
2. Edit and paste following code:

```YAML
  "vscode_vibrancy.imports": [
    "<HOME_DIRECTORY>/.vscode/extensions/eyhn.vscode-vibrancy-1.0.8/themes/Dark (Only Subbar).css", // if you are using vscode-vibrancy, this line is needed for applying translucent effects. Change "Dark (Only Subbar).css" to your favorite theme.
    "file:///<PATH TO CLONED REPOSITORY>/all.css"
  ]
```

3. Press `F1` then type "Reload Vibrancy" and press `ENTER`.
