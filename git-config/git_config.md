# git config 
1. remote机器下需要设置code（大概位置在~/.vscode-server/...）
2. 追加以下内容到~/.gitconfig

```
[core]
  editor = code --wait
  excludesFile = ~/.gitignore
[diff]
  tool = vscode
[difftool "vscode"]
  cmd = code --wait --diff
```
3. vscode 下载插件GitLens, Git Graph