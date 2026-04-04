# AssetFortress
一款結合 C# 與財務模型的 5000 萬級別資產配置與極限壓力測試決策系統。
# 🏰 AssetFortress 資產護城河 - 決策支援系統 (DSS)

![C#](https://img.shields.io/badge/C%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-5C2D91.svg?style=for-the-badge&logo=.net&logoColor=white)
![FinTech](https://img.shields.io/badge/FinTech-Decision_Support-blue?style=for-the-badge)

## 🎯 專案簡介 (Introduction)
AssetFortress 是一款結合 **C# 軟體工程** 與 **財務金融模型** 的決策支援系統 (Decision Support System)。
有別於傳統的靜態房貸試算表，本系統專為「5,000 萬級別實體資產配置」打造，透過動態陣列運算未來 30 年 (360 個月) 的現金流變化，並導入「資產活化複利模型」與「資金斷鏈壓力測試」，以數據科學輔助高階財務決策。

## 💡 開發動機 (Motivation)
身為一名高職電子科學生，我深信程式語言不應僅限於硬體控制，更是解決現實複雜問題的武器。
在面臨家族重大資產配置決策時，我發現市面上的試算工具無法真實模擬「極端風險」與「機會成本」。因此，我跨領域結合財務知識與 UI/UX 防呆心理學，獨立開發此系統，將抽象的金融概念轉化為具體的演算法與視覺圖表。

## 🚀 核心功能 (Core Features)

* **🛡️ 極限壓力測試 (Stress Testing)：** 模擬資金（如長輩贊助、股票處分）延遲到位的極端情境，系統將強制掛載 20% 流動性扣款，驗證財務護城河的抗壓性。
* **⚔️ 閒置資產活化引擎 (Active Asset Strategy)：**
  打破「房貸=純負債」的單維思考，系統可自動將每月繳款後的閒置資金，投入指定的 ETF 標的 (如 0050、00878 等)，精算複利效應如何對沖房貸利息。
* **📊 視覺化決策儀表板 (Visual Dashboard)：**
  以每 36 個月 (3年) 為戰略刻度，實時渲染 30 年現金流水位圖。綠線代表資金安全，紅線代表違約斷頭風險，提供最直覺的決策依據。
* **📑 軍情報表動態匯出 (Data Export)：**
  內建自訂的 CSV 匯出引擎，一鍵導出包含「本月收益」與「累積總獲利」的 360 期精細帳本，解決千分位格式衝突，完美對接 Excel。

## 🛠️ 技術棧 (Tech Stack)
* **語言：** C# 
* **框架：** .NET Windows Forms
* **資料處理：** `System.Data.DataTable` (動態資料綁定與擴展)
* **視覺化：** `System.Windows.Forms.DataVisualization.Charting`

## ⚠️ 免責聲明 (Disclaimer)
本系統之推演數據基於固定之數學模型（尚未計入通膨侵蝕、股利所得稅與券商手續費等摩擦成本）。實戰操作請依據真實市場波動為準，系統產出之報表僅供決策輔助參考。
