---
title: "簡化版測試：只填日期讓模板處理"
collection: publications
category: manuscripts
permalink: /publication/2025-08-29-simple-date-test
excerpt: '測試用戶只填日期，讓模板智能處理顯示格式。'
date: 2025-08-29
venue: '簡化測試期刊'
citation: '賴鵬仁. (2025). &quot;簡化版測試：只填日期讓模板處理.&quot; <i>簡化測試期刊</i>. 第1卷, 第1期, 頁1-2.'
share: true
---

## 自動時間戳功能測試

這個檔案用於測試 GitHub Actions 的自動時間戳注入功能。

### 功能說明

當用戶在 GitHub 網頁上傳新檔案時：

1. **新檔案**：
   - 自動添加完整的 `date` 時間戳
   - 自動添加 `modified` 時間戳（與 date 相同）
   - 如果只有日期，會補充具體時間

2. **修改檔案**：
   - 自動更新 `modified` 時間戳
   - 保持原有的 `date` 不變

### 預期結果

本檔案的 `date` 應該會被自動補充具體時間，並添加 `modified` 欄位。
