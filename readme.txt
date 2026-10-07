#
https://apinboy.github.io/nana/

# 第一次
git init
git add .
git commit -m "Add website files"
git branch -M main
git remote add origin https://github.com/apinboy/nana.git
git push -u origin main

# 以後每次更新時
git add .
git commit -m "Update website"
git push

#
在 VS Code 按 Ctrl+Shift+X 開啟「擴充功能」。
搜尋並安裝 Microsoft 出品的 Live Preview。
開啟 index.html。
按 Ctrl+Shift+P，搜尋並執行 Live Preview: Show Preview。
編輯 HTML 或 CSS，預覽畫面會跟著更新。
s