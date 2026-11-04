# TRPG Public Monitor — 公開審查展示網站

此儲存庫為 **PUBLIC**，只放置介紹頁、隱私權政策、資料刪除程序，以及 Meta Threads API 審查說明。真正蒐集公開資料的程式和資料保留在另一個 **PRIVATE** 儲存庫 Eagle0425/trpg-public-monitor。

## 真實功能與限制
- 本網站 **尚未** 提供 Threads OAuth 登入或即時搜尋；不應用它冒充審查人員可操作的 Threads API 成果。
- Threads 公開關鍵字搜尋需 Meta 核准 threads_keyword_search 進階權限。
- 本網站不包含任何 API 金鑰、個人帳號密碼或私有監測資料。

## 發布前必要動作
1. 專案管理者親自選擇一個可公開、可正常收信的聯絡信箱。
2. 將 privacy.html 和 deletion.html 的 CONTACT_EMAIL_REPLACE_ME 替換為該信箱，確認內容符合實際流程。
3. GitHub Settings → Pages → Build and deployment → Source → GitHub Actions。
4. 使用 Actions → Publish public information site → Run workflow；此工作流程會驗證聯絡信箱是否補齊後才進行發布。
5. 實際開啟 GitHub Pages 網址驗證 HTTPS、隱私權政策與資料刪除頁面後，才將網址填至 Meta App Settings。
6. Meta 要求可操作的授權和搜尋測試時，需另外建立受控、真實的功能展示，不能拿本靜態網站代替。

目標網站格式（未完成上線驗證前不得視為已發布）：
https://eagle0425.github.io/trpg-public-monitor-site/

## 重要頁面
- index.html：計畫介紹與資料來源狀態
- privacy.html：隱私權政策
- deletion.html：資料刪除
- review.html：審查人員與功能限制說明

只讀公開資料、標註來源不完整、尊重平台權限與資料刪除要求。