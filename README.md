# Git 教學：只學最重要、最常用的 40%

> 這是一套專門給初學者與實務使用者的 Git 教學。  
> 不追求把 Git 指令全部背完，只先學你每天最常用、最值得先熟練的核心 40%。

## 這套教材的特色

| 重點 | 說明 |
| --- | --- |
| 只教核心 | 聚焦 `init`、`status`、`add`、`commit`、`branch`、`switch`、`merge`、`push`、`pull`、`stash`、`revert`、`reset` 等高頻指令 |
| 24 份漸進式教學 | 從「Git 是什麼」一路走到「每天怎麼實際工作」、常見回復版本整理、安全判斷、手滑補救與常見卡住情境排解 |
| 指令可直接複製 | 每一章都有可直接貼上執行的指令區塊 |
| 格式好讀 | 用表格整理觀念、場景、常見錯誤與建議流程 |
| 實務導向 | 少講冷門指令，多講你真的會用到的流程 |

## 你會先學到的核心指令

| 類型 | 最重要指令 | 用途 |
| --- | --- | --- |
| 初始化 | `git init` | 建立新的 Git 版本庫 |
| 複製專案 | `git clone <url>` | 把遠端專案抓到本機 |
| 看狀態 | `git status` | 確認目前檔案狀態 |
| 暫存檔案 | `git add <file>`、`git add .` | 把準備提交的內容放進暫存區 |
| 建立版本 | `git commit -m "訊息"` | 建立一個可追蹤的版本點 |
| 看歷史 | `git log --oneline` | 快速查看提交紀錄 |
| 看差異 | `git diff`、`git diff --staged` | 比較修改前後差異 |
| 還原 | `git restore <file>`、`git restore --staged <file>` | 捨棄工作區修改或把檔案從暫存區拿回來 |
| 分支 | `git branch`、`git switch -c <branch>` | 建立與管理開發分支 |
| 切換 | `git switch <branch>` | 切到其他分支工作 |
| 合併 | `git merge <branch>` | 把功能分支合併回主線 |
| 遠端 | `git remote -v` | 確認遠端倉庫連線 |
| 推送 | `git push -u origin <branch>` | 把本機分支推到遠端 |
| 更新 | `git fetch`、`git pull --rebase` | 同步遠端最新狀態 |
| 臨時收起 | `git stash`、`git stash pop` | 暫時把未完成修改收起來 |
| 修正最近提交 | `git commit --amend` | 補檔案或修改上一筆提交訊息 |
| 安全回退 | `git revert <commit>` | 用反向提交撤銷已提交的變更 |
| 強制退回 | `git reset --hard <target>` | 讓本機回到指定提交或對齊目標狀態 |
| 救援 | `git reflog` | 找回剛剛切換、重做、遺失的狀態 |

## 建議學習順序

| 階段 | 建議先學的章節 | 目的 |
| --- | --- | --- |
| 基礎操作 | 01 - 08 | 先把 Git 的日常基本功打穩 |
| 修正與整理 | 09 - 10 | 學會還原、忽略不該追蹤的檔案 |
| 分支工作 | 11 - 13 | 學會開分支、切換、合併 |
| 遠端協作 | 14 - 16 | 學會 clone、push、pull、fetch |
| 救援與熟練 | 17 - 24 | 學會 stash、amend、revert、reset、完整工作流、回退判斷、手滑補救與常見卡住排解 |

## 目錄

| 課次 | 主題 | 連結 |
| --- | --- | --- |
| 01 | Git 核心觀念 | [01-git-foundation](01-git-foundation/README.md) |
| 02 | 第一次設定 Git 身分 | [02-first-setup](02-first-setup/README.md) |
| 03 | 建立第一個版本庫 | [03-init-repo](03-init-repo/README.md) |
| 04 | 看懂目前狀態 | [04-status](04-status/README.md) |
| 05 | 把檔案加入暫存區 | [05-add-staging](05-add-staging/README.md) |
| 06 | 建立提交 | [06-commit](06-commit/README.md) |
| 07 | 查看歷史版本 | [07-log-history](07-log-history/README.md) |
| 08 | 比較檔案差異 | [08-diff](08-diff/README.md) |
| 09 | 修改錯了怎麼還原 | [09-restore](09-restore/README.md) |
| 10 | 讓垃圾檔案不要進 Git | [10-gitignore](10-gitignore/README.md) |
| 11 | 分支入門 | [11-branch-create](11-branch-create/README.md) |
| 12 | 在分支之間切換 | [12-switch-branches](12-switch-branches/README.md) |
| 13 | 合併分支 | [13-merge](13-merge/README.md) |
| 14 | 複製專案與連接遠端 | [14-clone-remote](14-clone-remote/README.md) |
| 15 | 把版本推上遠端 | [15-push](15-push/README.md) |
| 16 | 拉回遠端最新內容 | [16-fetch-pull](16-fetch-pull/README.md) |
| 17 | 暫時收起未完成工作 | [17-stash](17-stash/README.md) |
| 18 | 修正最近一次提交 | [18-amend](18-amend/README.md) |
| 19 | 安全回退與救援 | [19-revert-reflog](19-revert-reflog/README.md) |
| 20 | 每日 Git 工作流總複習 | [20-daily-workflow](20-daily-workflow/README.md) |
| 21 | Git 速查表：什麼時候用什麼招 | [21-version-recovery](21-version-recovery/README.md) |
| 22 | 回退版本的安全判斷完整教學 | [22-recovery-safety](22-recovery-safety/README.md) |
| 23 | Git 常見手滑補救教學 | [23-mistake-recovery](23-mistake-recovery/README.md) |
| 24 | Git 常見卡住情境排解 | [24-common-troubleshooting](24-common-troubleshooting/README.md) |

## 這套教材刻意不先教的內容

| 先不急著學 | 原因 |
| --- | --- |
| `git cherry-pick` | 不是每天都用，先把分支與合併打穩再學 |
| `git rebase` 的進階互動用法 | 對新手來說太容易改壞歷史，先學 `pull --rebase` 的使用場景就好 |
| `git submodule` | 協作場景特殊，不是 Git 入門必修 |
| `git bisect` | 很強，但使用頻率低於本套核心指令 |
| `git worktree` | 很實用，但適合基礎穩定之後再學 |

## 最實用的學法

1. 先完整做完 01 到 06。
2. 接著練 07 到 10，熟悉「看差異」與「還原」。
3. 再練 11 到 16，這就是團隊協作的核心。
4. 最後把 17 到 24 當成你的救援卡與日常工作模板。

## 快速提醒

| 原則 | 記法 |
| --- | --- |
| 看不懂先 `status` | 幾乎所有卡住的情況，先看狀態最安全 |
| 提交前先 `diff` | 你要先知道自己到底改了什麼 |
| 分支工作最穩 | 新功能、修 bug、實驗都不要直接在 `main` 上做 |
| 已分享的歷史先別亂改 | 推到遠端後，優先用 `revert` 而不是危險重寫 |
| 救援先找 `reflog` | 找不到剛剛那個提交時，先別慌 |





