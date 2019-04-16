## 交作業流程

1. 開iterm 輸入 git clone + git classroom的網址複製貼上 
2. 檢查git classroom 的資料夾是否下載成功
3. 開始寫作業
4. 寫完作業後，到iterm輸入 git status 查看git狀態
5. 開一個分支，輸入`git branch '分支名稱'`
6. 切換到分支`checkout 分支名稱`
7. 確認在分支下，輸入`git add.` 將修改過的版本加入版本控制
8. 輸入`git commit -am 'commit版本名稱' `
9. git push origin 分支名稱
10. 發pull request 且tag 老師
11. 之後到lidemy/homeworks-3rd 寫issue，將作業的pull request連結貼上，讓同學們互相review
12. 等老師merge git後，再把merge後的master，pull下來跟自己的master做同步