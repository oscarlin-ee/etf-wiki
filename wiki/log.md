# Wiki 更新歷程日誌 (log.md)

本檔案記錄所有教材 Ingest 與 Wiki 知識庫維護的歷程。

---

## [2026-11-22] 初始全量 Ingest 任務完成
- **執行動作**：循序完成 `raw/` 5 篇教材的 Ingest，並建立完整 Wiki 知識庫結構。
- **處理檔案清單**：
  1. `raw/01_market_cap_etf_basics.md` -> 產出 `wiki/papers/01_market_cap_etf_basics.md`
  2. `raw/02_dca_vs_lump_sum.md` -> 產出 `wiki/papers/02_dca_vs_lump_sum.md`
  3. `raw/03_expense_ratio_tracking_error.md` -> 產出 `wiki/papers/03_expense_ratio_tracking_error.md`
  4. `raw/04_dividend_reinvestment.md` -> 產出 `wiki/papers/04_dividend_reinvestment.md`
  5. `raw/05_asset_allocation_risk.md` -> 產出 `wiki/papers/05_asset_allocation_risk.md`
- **同步更新**：
  - 更新 `wiki/concepts/index.md`（收錄核心名詞深化）
  - 更新 `wiki/overview.md`（新手學習地圖）
  - 更新 `wiki/index.md`（總目錄索引）
- **狀態**：所有主張與試算數字皆已完成出處標註（`[來源: raw/...]`）與教學假設註記，`raw/` 原始檔案保持唯讀未動。
