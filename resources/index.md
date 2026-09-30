# GIS 資源索引

[機器可讀清單](catalog.json) · [第 1 期日報](../reports/2026-09-30.md)

目前 5 項，皆為 candidate；可用瀏覽器搜尋類型、地區與主題。未列入的類型表示首期尚無經核對資源。

## 依類型

### dataset
- [115 年土石流與大規模崩塌潛勢](#taiwan-debris-landslide)
- [NASA FIRMS 衛星熱異常](#nasa-firms-viirs)
- [JAXA GCOM-C 海表溫度](#jaxa-gcomc-sst)
- [JAXA 日本 10m 土地覆蓋 v25.04](#jaxa-japan-hrlulc)

### data_platform
- [Overture Maps 2026 年 9 月版](#overture-maps)

### analysis_method
- 尚無條目

### showcase
- 尚無條目

### model_tool
- 尚無條目

## 依地區

### Taiwan
- [Overture Maps 2026 年 9 月版](#overture-maps)
- [115 年土石流與大規模崩塌潛勢](#taiwan-debris-landslide)
- [NASA FIRMS 衛星熱異常](#nasa-firms-viirs)
- [JAXA GCOM-C 海表溫度](#jaxa-gcomc-sst)

### Japan
- [Overture Maps 2026 年 9 月版](#overture-maps)
- [NASA FIRMS 衛星熱異常](#nasa-firms-viirs)
- [JAXA GCOM-C 海表溫度](#jaxa-gcomc-sst)
- [JAXA 日本 10m 土地覆蓋 v25.04](#jaxa-japan-hrlulc)

### global
- [Overture Maps 2026 年 9 月版](#overture-maps)
- [NASA FIRMS 衛星熱異常](#nasa-firms-viirs)
- [JAXA GCOM-C 海表溫度](#jaxa-gcomc-sst)

## 依主題

- environment：[NASA FIRMS 衛星熱異常](#nasa-firms-viirs)、[JAXA GCOM-C 海表溫度](#jaxa-gcomc-sst)、[JAXA 日本 10m 土地覆蓋 v25.04](#jaxa-japan-hrlulc)
- hazards：[115 年土石流與大規模崩塌潛勢](#taiwan-debris-landslide)、[NASA FIRMS 衛星熱異常](#nasa-firms-viirs)
- ocean：[JAXA GCOM-C 海表溫度](#jaxa-gcomc-sst)
- transport：[Overture Maps 2026 年 9 月版](#overture-maps)
- urban：[Overture Maps 2026 年 9 月版](#overture-maps)、[JAXA 日本 10m 土地覆蓋 v25.04](#jaxa-japan-hrlulc)

- POI：[Overture Maps 2026 年 9 月版](#overture-maps)
- 土地利用：[JAXA 日本 10m 土地覆蓋 v25.04](#jaxa-japan-hrlulc)
- 土地覆蓋：[JAXA 日本 10m 土地覆蓋 v25.04](#jaxa-japan-hrlulc)
- 土石流：[115 年土石流與大規模崩塌潛勢](#taiwan-debris-landslide)
- 地址：[Overture Maps 2026 年 9 月版](#overture-maps)
- 坡地災害：[115 年土石流與大規模崩塌潛勢](#taiwan-debris-landslide)
- 太陽能：[JAXA 日本 10m 土地覆蓋 v25.04](#jaxa-japan-hrlulc)
- 崩塌：[115 年土石流與大規模崩塌潛勢](#taiwan-debris-landslide)
- 建物：[Overture Maps 2026 年 9 月版](#overture-maps)
- 森林火災：[NASA FIRMS 衛星熱異常](#nasa-firms-viirs)
- 海洋：[JAXA GCOM-C 海表溫度](#jaxa-gcomc-sst)
- 海溫：[JAXA GCOM-C 海表溫度](#jaxa-gcomc-sst)
- 濕地：[JAXA 日本 10m 土地覆蓋 v25.04](#jaxa-japan-hrlulc)
- 災害潛勢：[115 年土石流與大規模崩塌潛勢](#taiwan-debris-landslide)
- 熱異常：[NASA FIRMS 衛星熱異常](#nasa-firms-viirs)
- 版本相容性：[Overture Maps 2026 年 9 月版](#overture-maps)
- 珊瑚環境：[JAXA GCOM-C 海表溫度](#jaxa-gcomc-sst)
- 衛星：[NASA FIRMS 衛星熱異常](#nasa-firms-viirs)、[JAXA GCOM-C 海表溫度](#jaxa-gcomc-sst)
- 變遷：[JAXA 日本 10m 土地覆蓋 v25.04](#jaxa-japan-hrlulc)
- 近即時：[NASA FIRMS 衛星熱異常](#nasa-firms-viirs)

## 資源卡

<a id="overture-maps"></a>
### Overture Maps 2026 年 9 月版
- ID：overture-maps
- 類型：data_platform；地區：global, Taiwan, Japan；主題：地址、POI、建物、版本相容性
- 本週更新：9/23 版本新增台灣三縣市地址來源（發布說明未列名稱）；目前有 2026-09-23.1 修正版。Schema v2 移除 places.categories，改用 taxonomy 或 basic_category。
- [官方來源](https://docs.overturemaps.org/blog/2026/09/23/release-notes/)；發現／核對：2026-09-30；狀態：candidate

<a id="taiwan-debris-landslide"></a>
### 115 年土石流與大規模崩塌潛勢
- ID：taiwan-debris-landslide
- 類型：dataset；地區：Taiwan；主題：坡地災害、土石流、崩塌、災害潛勢
- 今年資料精選：可補坡地風險底圖，並與現有道路、橋梁、避難及降雨資料套疊。
- [官方來源](https://data.gov.tw/news/31852)；發現／核對：2026-09-30；狀態：candidate

<a id="nasa-firms-viirs"></a>
### NASA FIRMS 衛星熱異常
- ID：nasa-firms-viirs
- 類型：dataset；地區：global, Taiwan, Japan；主題：熱異常、森林火災、近即時、衛星
- 既有資料精選：為歷史消防火災紀錄增加近即時衛星觀測，兩者需分開命名與呈現。
- [官方來源](https://firms.modaps.eosdis.nasa.gov/active_fire/)；發現／核對：2026-09-30；狀態：candidate

<a id="jaxa-gcomc-sst"></a>
### JAXA GCOM-C 海表溫度
- ID：jaxa-gcomc-sst
- 類型：dataset；地區：global, Taiwan, Japan；主題：海溫、海洋、衛星、珊瑚環境
- 既有資料精選：與珊瑚、船舶圖層搭配顯示海洋環境。日、半月、月及日夜產品已列入官方 STAC。
- [官方來源](https://data.earth.jaxa.jp/en/)；發現／核對：2026-09-30；狀態：candidate

<a id="jaxa-japan-hrlulc"></a>
### JAXA 日本 10m 土地覆蓋 v25.04
- ID：jaxa-japan-hrlulc
- 類型：dataset；地區：Japan；主題：土地覆蓋、土地利用、變遷、太陽能、濕地
- 既有資料精選：2025 年 4 月發布，可比較都市、農地、森林、太陽能板、濕地與岩礁／潮間帶；非 2026 新影像。
- [官方來源](https://www.eorc.jaxa.jp/ALOS/en/dataset/lulc/lulc_v2504_e.htm)；發現／核對：2026-09-30；狀態：candidate
