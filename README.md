# AI 小芽學院

繁體中文 Phaser 3 AI 入門小遊戲。每局從 30 題隨機抽取 10 題，含選項洗牌、解析、連答 XP、錯題筆記、音效與 Cookie 進度保存。

遊玩網址：https://shuda0920.github.io/ai-sprout-academy/

玩家不需要帳號。XP、錯題筆記與本局進度存在瀏覽器的 ai_sprout_v2 Cookie，效期為最後遊玩起一年，使用網站路徑隔離及 SameSite=Lax，HTTPS 下加上 Secure。清除或封鎖 Cookie 將無法保留進度；不同瀏覽器與裝置不共用紀錄。舊版本的 localStorage 紀錄可在同一來源首次載入時遷移，後續以 Cookie 為準。

推送到 main 後，GitHub Actions 會執行 node test.cjs，再將 dist 發布到 GitHub Pages。

執行 `node server.cjs`，開啟 http://127.0.0.1:4173 。靜態發布目錄是 `dist`，Phaser 引擎已包含於 `dist/vendor`，無須安裝套件。字型可離線回退為系統字型。

題库：`dist/questions.js`；遊戲流程與 Phaser 場景：`dist/app.js`；介面：`dist/index.html` 與 `dist/style.css`。
