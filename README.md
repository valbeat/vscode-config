# vscode-config
My vscode-config


## Usage
```
# Link files
ln -sfnv $(pwd)/settings.json ~/Library/Application\ Support/Code/User/
ln -sfnv $(pwd)/keybindings.json ~/Library/Application\ Support/Code/User/
ln -sfnv $(pwd)/snippets ~/Library/Application\ Support/Code/User/

# Install extensions
cat extensions.txt | xargs -L1 code --install-extension
```

## Backup
```
code --list-extensions > extensions.txt
```
