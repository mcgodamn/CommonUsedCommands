# Git

- Stash
  - `git stash --include-untracked`
- 刪除已推送的提送
  - `git reset --hard "commit ID"`
  - `git push -f`
- 重寫最近的Comment
  - `git commit --amend -m "New commit message."`
  - `git push -f`
- Add submodule
  - `git submodule add <remote_url> <destination_folder>`
- Remove submodule
  - `git rm <path-to-submodule>`
- 大小寫問題沒有變更
  - `git config --local core.ignorecase false`

# npm

- `npm update`
  > 更新所有package
