---
tags: git

---
# git

[git](https://git-scm.com/)
[gitkraken](https://www.gitkraken.com/)
[Sourcetree](https://www.sourcetreeapp.com)
[Fork](https://git-fork.com/home)

[github](https://github.com/)
[RippleEffect](https://github.com/traex/RippleEffect)
[Bitbucket](https://bitbucket.org/)
[gitbook](https://gitbook.tw/)
[PPT](https://goo.gl/Ys5spk)
[learngitbranching](https://learngitbranching.js.org)

## CLI Command Line Interface
```shell
# Windows / Mac 檔案與目錄的檢視
$ dir / ls

# 開啟
$ cd <file name>

# 建立資料夾
$ mkdir <folder name>

# 建立.git檔
$ git init

# 檢視git目前狀態
$ git status

# 將修改檔案加入暫存區
$ git add <file name>

# 將修改的某檔案類型加入暫存區 ex: git add *.txt
$ git add <file type>

# 將修改的全部檔案加入暫存區
$ git add . 
$ git add -A

# 將修改全部檔案移除暫存區
$ git reset .

# 加上註解
$ git commit -m <your commit>

# 看上一次git的資訊
$ git log

# 新增你的聯絡email
$ git config --global user.email <your E-mail>

# 新增你的聯絡名字(可以沒有)
$ git config --global user.name <your name>

# 設定遠端資料庫
$ git remote add <repository name> <repository URL>

# 推到遠端資料庫
$ git push -u <repository name> <branch name>

# 推到遠端(已指定遠端)
$ git push

# 變更分支(最少前四碼)
$ git checkout <branch ID>

# 從遠端下載
$ git clone <repository URL>

# 更新至遠端進度
$ git pull

# 空資料夾無法git
# .gitkeep.(Windows) // .gitkeep(Mac)
```