# GIS Data Radar

公開 GIS 資料與研究資源雷達：保留可查證的來源、適用範圍與接入限制，方便日後搜尋與評估。

## 最新日報

- [2026-10-01：村里單齡人口、北捷 OD 與 MISR 更新](reports/2026-10-01.md)：本期新增 4 筆，目錄共 17 筆；含實檔驗證與取得限制

## 歷次試跑

- [2026-09-30 第二輪：資料、分析方法、展示案例與模型工具](reports/2026-09-30.md#trial-four-categories)：四類各新增 2 項，目錄共 13 項；附用途、限制、授權及建議小試流程

## 目錄

- `reports/YYYY-MM-DD.md`：每日精選與判讀
- `resources/catalog.json`：持續維護的機器可讀目錄，以穩定 `id` 去重
- `resources/index.md`：按地區、類型與主題瀏覽
- `schemas/resource.schema.json`：單筆資源格式

## 分類

資源主類型為 `dataset`（資料集）、`data_platform`（資料來源平台）、`analysis_method`（分析方法）、`showcase`（展示網站）、`model_tool`（模型或工具）。`secondary_types` 補充跨類型用途，避免將所有網站都當成可直接下載的資料集。

`regions` 使用 `Taiwan`、`Japan`、其他明確國家名稱、`global` 或 `not_region_specific`；`topics` 可包含 transport、ocean、hazards、weather、urban、environment 等。全球資源可能涵蓋台灣，不等於台灣資料源；實際覆盖範圍以 `scope` 為準。

## 日期與證據

- `published_at`：來源明確標示的首次發布日
- `source_updated_at`：來源明確標示的資料或頁面更新日
- `discovered_at`：本目錄首次收錄日
- `last_verified_at`：本目錄最近查證日

未知日期使用 `null`，不以收錄或查證日期代替發布日。公開可瀏覽不代表可自由重新散布；每筆授權分別記錄，未知者保留待確認。API 文件存在不等於本目錄已完成 API 下載或應用接入。

## 每日追加與重跑

1. 先讀取當日報告與 `catalog.json`，比較來源的穩定網址及 `id`
2. 同一來源更新既有記錄，保留首次 `discovered_at`；不因日期改變建立重複資源
3. 新資源使用小寫 ASCII kebab-case `id`；只加入公開資料和可查證的摘要
4. 更新驗證日、來源證據及接入狀態；日期或授權不明時保留 `null` 或說明
5. 報告引用資源 `id`；以同一路徑更新當日報告，不另增日期後綴副本
6. 同步更新瀏覽索引。內容無實質改動則不建立空提交
7. 提交前檢查 JSON 格式、唯一 ID、日期、必要欄位與報告連結；提交後讀回遠端檔案

## 使用界線

這是資源發現與評估目錄，不存放第三方原始資料集，也不替第三方資料賦予統一授權。請依各來源原始條款使用及引用。候選接入狀態僅反映指定檔案與查證範圍，不能推論資源在所有分支、服務或既有工作中完全不存在。
