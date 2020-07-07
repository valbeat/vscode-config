# vscode-config
My vscode-config

```
# Link files
ln -sfnv ./settings.json ~/Library/Application\ Support/Code/User/settings.json
ln -sfnv ./keybindings.json ~/Library/Application\ Support/Code/User/keybindings.json
ln -sfnv ./snippets ~/Library/Application\ Support/Code/User/snippets

# Install extensions
cat extensions.txt | xargs -L1 code --install-extension
```
