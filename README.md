# vscode-config
My vscode-config

```
# Link files
ln -sfnv $(pwd)/settings.json ~/Library/Application\ Support/Code/User/
ln -sfnv $(pwd)/keybindings.json ~/Library/Application\ Support/Code/User/
ln -sfnv $(pwd)/snippets ~/Library/Application\ Support/Code/User/

# Install extensions
cat extensions.txt | xargs -L1 code --install-extension
```
