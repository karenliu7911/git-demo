
# GIT指令集練習

### Markdown
- https://hackmd.io/@howkii-studio/markdown_intro


### 檢視版本號
- git version
  (在cmd 命令提示字元操作)


### 註冊全域資訊
- git config --global user.name karen
- git config --global user.email karen@gmail.com
  
  (在cmd 命令提示字元操作)
  (email 不一定要設真的email address)


### 初始化倉庫
- git init
- .git/  (初始化後出現一個 .git目錄)


### 控管狀態
- U -> Untrack (未追蹤)
- A -> Added   (已加入)
- D -> Deleted (已刪除)
- M -> Modified (已變更)


### 加上控管
- git add 1.txt
- git add .     (加入所有變動，包含加入控款，需小心使用)


### 檢視控管狀態
- git status


### 恢復刪除 (先前為"A"的檔案)
- git restore 1.txt


### 加入不控管的項目
- 新增目錄 .gitignore


### 檢視暫存區狀態
- git ls-files -s


### 恢復上一動
- git checkout filename
- git checkout .          (全部檔案恢復)


### 加入倉庫
- git commit -m "專案初始化完成"
- git commit --amend (跟最新commit合併)


### 檢視倉庫
- git log
- git log --oneline  (呈現出所有commit)

- 資訊過多，按enter，最後按q離開


### 分支的概念
- master (主分支)
- git branch


### 切換commit
- git checkout commit sha前5碼
- git checkout master


### 新增分支
- git branch test   (test=分支名稱)


### 切換分支
- git checkout test


### 合併分支
- git checkout master
- git merge test


### 刪除分支
- git branch -D test


### 申請github


### 綁定到雲端倉庫
- git remote add origin https://github.com/karenliu7911/git-demo.git


### 檢視雲端網址 (確認是否綁定成功?)
- git remote -v


### 推送到雲端
- git push
- git push -u origin master   (第一次認證，)
- git push -f
      - force 強制推送


### 複製專案 (利用Git Bash輸入指令最快)
- git clone https://github.com/karenliu7911/git-demo.git
  (clone表示複製的意思)


### 從雲端拉取
- git pull



### VSCODE setting
- ctrl + shift + p (快速搜尋)
- 更改終端機
	- default terminal => cmd.exe