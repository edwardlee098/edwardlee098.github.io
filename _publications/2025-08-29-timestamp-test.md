---
title: "時間顯示測試：自動時間戳功能驗證"
collection: publications
category: manuscripts
permalink: /publication/2025-08-29-timestamp-test
excerpt: '這篇文章用於測試新增的時間顯示功能，包括上傳時間和編輯時間。'
date: 2025-08-29
modified: 2025-08-29
venue: '系統測試期刊'
citation: '賴鵬仁. (2025). &quot;時間顯示測試：自動時間戳功能驗證.&quot; <i>系統測試期刊</i>. 第1卷, 第1期, 頁1-3.'
share: true
---

## 時間顯示功能測試

本文章專門用於測試新增的時間顯示功能。

### 預期顯示內容

在文章底部應該會顯示：
1. **上傳時間** - 基於 `date` 欄位
2. **最後編輯時間** - 基於 `modified` 欄位或 Git 修改時間

### 測試項目

- [x] 上傳時間正確顯示
- [x] 編輯時間功能
- [x] 時間格式為中文
- [x] 圖示正確顯示

如果您能在本文底部看到時間信息，表示功能正常運作！
