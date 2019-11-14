# Git 版本控制

紀錄學習 git 的筆記跟一些使用想法。



## 基礎概念 - unstaged, staged

### Git 是什麼

一種版本控制的工具，Git 記錄檔案快照，而不是差異，大部份的操作皆可在本地端完成，且通常只增加資料。


### 三種狀態

Git 會把你的檔案標記為三種主要的狀態：已提交（committed）、已修改（modified）及已預存（staged）

  - 已提交：代表這檔案己安全地存在你的本地端資料庫。
  
  - 己修改：代表這檔案已被修改但尚未提交到本地端資料庫。
  
  - 已預存：代表這檔案將會被存到下次你提交的快照中。


### Git 工作流程

  1. 你在你工作目錄修改檔案。(已修改)

  2. 預存檔案，將檔案的快照新增到預存區。(add 加入預存，已預存)

  3. 做提交的動作，這會讓存在預存區的檔案快照永久地儲存在 Git 目錄中。(commit 提交修改，已提交)


## 基礎使用

＊ [第一篇](https://github.com/johnnywang1994/git-memo/blob/master/src/basic.md) Git 基礎指令

＊ [第二篇](https://github.com/johnnywang1994/git-memo/blob/master/src/recover.md) Git 復原指令

＊ [第三篇](https://github.com/johnnywang1994/git-memo/blob/master/src/remote.md) Git 選端協作指令

＊ [第四篇](https://github.com/johnnywang1994/git-memo/blob/master/src/tag.md) Git 標籤指令

＊ [第五篇](https://github.com/johnnywang1994/git-memo/blob/master/src/branch.md) Git 分支指令

＊ [第六篇](https://github.com/johnnywang1994/git-memo/blob/master/src/merge.md) Git 分支和合併的基本用法