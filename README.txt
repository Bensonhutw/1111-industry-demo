1111 製造業專區 Demo（多頁版）

使用方式
1. 解壓縮後，在瀏覽器開啟 index.html；頁面資料不需伺服器或 API。
2. 上傳 GitHub 時，將所有 HTML 與 assets 資料夾一起上傳至 1111-industry-demo 儲存庫最外層。
3. 保留原本 GitHub Pages：main 分支 / (root)。
4. 不要直接上傳 ZIP；不要把整個 industry-demo 資料夾當成另一層網站根目錄。

頁面
index.html       首頁
jobs.html        找工作：篩選、排序、分頁與網址條件
job.html         職缺詳情：返回列表保留條件
companies.html   企業列表
company.html     企業介绍與對應職缺、文章
trends.html      月度產業情報、歷史指數與職務需求
articles.html    企業報導、人物專訪與工作甘苦談列表
article.html     文章內頁與相關職缺
career.html      職涯、薪資、證照與進修入口
business.html    廣告合作方案與模擬洽詢
assets/style.css 共用視覺
assets/data.js   共用示範資料
assets/app.js    各頁搜尋與導流

限制與資料
全部企業、職缺、薪資、文章與趨勢數字為虛構示範，不代表 1111 實際資料。
示範職缺不能投遞履歷；前往 1111 按鈕會開啟 1111 正式首頁。
薪資公秤、職涯大師與官方 LOGO 使用既有 1111 網址，需要網路連線。
證照與進修尚未串接實際資料，不會顯示虛構報名課程。
洽詢表單只模擬成功，資料不會傳送或保存。
首頁為獨立完整 HTML；其他頁共用 assets 內容。
無登入、資料庫或正式 API；不包含帳號或金鑰。

驗證
已檢查 JavaScript 語法、各頁資料呈現、跨頁連結、條件合併、搜尋與空結果、無效ID、分頁與返回參數。
此環境未完成真實瀏覽器視覺驗證，上傳後請確認桌機與手機版面。
