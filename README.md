# 尾牙抽獎

單一 HTML 檔（index.html），無後端、無需建置。

## 部署到 Vercel
1. 把本資料夾放進 GitHub repo（或直接用 Vercel CLI：在此資料夾執行 `vercel`）。
2. Vercel → Add New → Project → 選該 repo → Deploy（Framework Preset 選 Other，其餘維持預設）。
3. 取得網址，例如 https://lottery-xxx.vercel.app 。

## 更新
覆蓋 index.html 後 push，Vercel 會自動重新部署。

## 注意
- 設定與抽獎進度目前存在各瀏覽器的 localStorage；換網址、換瀏覽器、換電腦就看不到，請用「匯出設定」備份。
- 之後若要加 Google 登入同步，需要此站的 https 網址（加入 OAuth「已授權的 JavaScript 來源」）。
