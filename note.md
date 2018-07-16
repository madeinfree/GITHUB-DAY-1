# Github 獨立開發模式

- 這是什麼東西
- 所以什麼是 Git
- 為什麼要使用 Github
- 如何開始使用 Github
  - 建立 repo
  - 上傳 repo
- 版本控制

## 步驟

```
# 初始化
> git init

# 增加一個遠端連接(origin)
> git remote add origin https://github.com/madeinfree/GITHUB-DAY-1.git

# 查看遠端連接資訊
> git remote -v
origin	https://github.com/madeinfree/GITHUB-DAY-1.git (fetch)
origin	https://github.com/madeinfree/GITHUB-DAY-1.git (push)

# 查看檔案更動訊息
> git status
.gitignore
note.md

# 確認要被記錄的檔案
> git add file_name 或 .

# 回到上一動
> git reset

# 查看 commit 紀錄(log)
> git log

# 暫時儲存目前改動的東西
> git stash
# 刪除 stash 暫存的檔案
> git stash drop 0

# 關鍵字 rebase
> git rebase origin/master
```

## 移除不需要的東西 .gitignore

建立一個 `.gitignore` 檔案

## https://github.com/
