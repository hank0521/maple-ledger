# 楓時 · Maple Ledger

[![0.2.7 安裝包下載次數](https://img.shields.io/github/downloads/hank0521/maple-ledger/v0.2.7/Maple-Ledger-0.2.7-Windows-x64-setup.exe?displayAssetName=false&style=for-the-badge&label=0.2.7%20%E5%AE%89%E8%A3%9D%E5%8C%85%E4%B8%8B%E8%BC%89&color=ea580c)](https://github.com/hank0521/maple-ledger/releases/tag/v0.2.7)
[![0.2.6 安裝包下載次數](https://img.shields.io/github/downloads/hank0521/maple-ledger/v0.2.6/Maple-Ledger-0.2.6-Windows-x64-setup.exe?displayAssetName=false&style=for-the-badge&label=0.2.6%20%E5%AE%89%E8%A3%9D%E5%8C%85%E4%B8%8B%E8%BC%89&color=ea580c)](https://github.com/hank0521/maple-ledger/releases/tag/v0.2.6)

輕量的 Windows 桌面工具，手動記錄《新楓之谷：經典版》的練功時間、楓幣、消耗品及 EXP，快速查看本場收益與練功效率。

此儲存庫提供安裝包與版本說明。

## 下載與安裝

**[下載最新版](https://github.com/hank0521/maple-ledger/releases/latest)**

1. 開啟上方連結，在 **Assets** 中下載檔名結尾為 `Windows-x64-setup.exe` 的安裝包。
2. 開啟下載的 `.exe`，依照安裝精靈完成安裝。
3. 啟動「楓時」，輸入開始資料後按「開始」；練功結束時按「停止」，再輸入結束資料完成結算。

目前版本：**[楓時 0.2.7 Windows x64 安裝包](https://github.com/hank0521/maple-ledger/releases/download/v0.2.7/Maple-Ledger-0.2.7-Windows-x64-setup.exe)**。

不需要下載 `Source code` 或 `.sha256` 檔案；`.sha256` 僅供檢查檔案完整性。

## 0.2.7 更新

- 奶油暖色與立體按鈕介面，49 種消耗品加入對應道具圖示。
- 點回遊戲自動最小化，從工作列即可重新開啟；選檔與確認對話框保留正常操作。
- 歷史直接顯示備註，支援展開完整內容。
- 收藏可篩選及批次加入，沿用上場資料時不覆寫已填數值。
- 誤按停止可撤回至暫停，忘記暫停可修正有效時間。
- 結算與歷史共用精簡摘要卡片，完整數值與對帳資訊仍保留。

[查看完整更新說明](https://github.com/hank0521/maple-ledger/releases/tag/v0.2.7)

## 功能

- 自動計時、暫停／繼續，支援視窗置頂；切到其他程式時自動最小化，計時繼續。
- 記錄起訖楓幣、等級、EXP 與消耗品庫存，計算總收益、淨收益。
- 顯示每 10 分鐘平均 EXP、每小時 EXP 與總 EXP。
- 記錄加倍券張數及選填備註，查看單場與期間摘要。
- 沿用上場消耗品清單及結束庫存，減少重複輸入。
- 預載 49 種基本消耗品及 Lv.1 → 200 的 199 筆升級需求；參考價格與經驗表可自行修改。
- SQLite 已內建；紀錄儲存在本機，永久保留直到手動刪除，設定內可匯出／匯入備份。

## 使用說明

適用 Windows x64。若電腦尚未安裝 Microsoft Edge WebView2，安裝期間需要連線取得執行階段；安裝完成後可離線記錄，不需要遊戲帳號登入。本版安裝包未做程式碼簽章。

更新前請關閉正在執行的楓時，並可先在設定匯出備份，再執行新版安裝包。

楓時採手動輸入，不讀取遊戲。內建價格與 EXP 為社群參考資料，請依實際遊戲版本核對；加倍券只記錄使用張數，不會將輸入的實際 EXP 再乘二。

## 下載統計

首頁上方的版本下載徽章各自顯示對應版本 `.exe` 安裝包的累計下載次數，不包含 `.sha256` 校驗檔。數字由 [Shields.io](https://shields.io/badges/git-hub-downloads-specific-asset-specific-tag) 讀取 GitHub 資料，因快取可能稍有延遲。

GitHub 會記錄各個 Release 附件的下載次數。統計安裝包的 `download_count` 即可；重複下載也可能累計，因此代表下載次數，不等同不重複使用者人數。

分享此下載頁或安裝包下載連結，可讓下載經過 GitHub。直接轉傳已下載的檔案，不會增加 GitHub 的下載統計。

道具圖示參考來源：[楓情報](https://kafuffu20.com/)。MapleStory 遊戲美術權利屬原權利人，楓時為非官方工具。
