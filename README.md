# AI 小芽學院

繁體中文 Phaser 3 AI 入門小遊戲。每局从 30 題隨機抽取 10 題，含選項洗牌、解析、連答 XP、錯題筆記、音效與本機進度保存。

執行 `node server.cjs`，開啟 http://127.0.0.1:4173 。靜態發布目錄是 `dist`，Phaser 引擎已包含於 `dist/vendor`，無須安裝套件。字型可離線回退為系統字型。

題库：`dist/questions.js`；遊戲流程與 Phaser 場景：`dist/app.js`；介面：`dist/index.html` 與 `dist/style.css`。
