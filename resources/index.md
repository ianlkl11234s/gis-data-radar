# GIS 資源索引

[機器可讀清單](catalog.json) · [2026-10-06 日報](../reports/2026-10-06.md) · [2026-10-05 日報](../reports/2026-10-05.md) · [2026-10-04 日報](../reports/2026-10-04.md) · [2026-10-03 日報](../reports/2026-10-03.md) · [2026-10-02 日報](../reports/2026-10-02.md) · [2026-10-01 日報](../reports/2026-10-01.md) · [第 1 期日報與第二輪四類試跑](../reports/2026-09-30.md#trial-four-categories)

目前 31 項：28 項 candidate、3 項 integrated（僅部分資料的原始碼登錄，非本期運行驗收）；可依類型、地區與主題瀏覽。最新查核：2026-10-06（新增 3 項；OAM 覆蓋、日本 DEM 與有效像元方法；其餘保留各自查核日）。

## 依類型

### dataset

- [日本 GSI DEM1A：1m 地表高程與供應範圍](#japan-gsi-dem1a)

- [日本 GSJ 五萬分之一地質圖 WMS／WMTS](#japan-gsj-geology-50k-services)

- [日本國土數值情報：河川單位洪水浸水想定 A31a](#japan-mlit-river-flood-inundation)

- [台灣淹水潛勢：多降雨情境與資源版本](#taiwan-wra-flood-scenarios)

- [115 年土石流與大規模崩塌潛勢](#taiwan-debris-landslide)

- [NASA FIRMS 衛星熱異常](#nasa-firms-viirs)

- [JAXA GCOM-C 海表溫度](#jaxa-gcomc-sst)

- [JAXA 日本 10m 土地覆蓋 v25.04](#jaxa-japan-hrlulc)

- [Google Dynamic World V1：全球 10 公尺近即時土地覆蓋](#google-dynamic-world-v1)

- [GHSL GHS-POP R2023A：全球人口網格與暴露估算底圖](#jrc-ghsl-ghs-pop-r2023a)


- [台灣村里每月單齡人口與戶數](#taiwan-village-single-age-population)

- [臺北捷運每日分時站間 OD](#taipei-metro-hourly-od)

- [台灣水污染源許可與排放申報](#taiwan-water-discharge-permits-declarations)

### data_platform

- [OpenAerialMap：STAC 與免下載影像的覆蓋目錄](#openaerialmap-stac-coverage)

- [Google Places Insights：台日 POI 月度變化與聚合查詢](#google-places-insights)

- [Global Fishing Watch：海事資料 API 與 SAR 來源變更](#global-fishing-watch-api)

- [PLATEAU VIEW 與日本 3D 都市模型配信](#japan-plateau-view-platform)

- [Overture Maps 2026 年 9 月版](#overture-maps)


- [NASA MISR 瀏覽與資料訂製平台：調軌後資料支援](#nasa-misr-browse-customization)

### analysis_method

- [GDAL footprint：分開影像外框與有效像元覆蓋](#gdal-valid-data-footprint)

- [H3 密度與邊界核算：選格不等於分配人口](#h3-density-boundary-accounting)

- [exactextract：按像元覆蓋比例計算人口暴露](#analysis-exactextract-zonal-statistics)

- [跨期共用分級：讓不同年份的同色代表同一範圍](#analysis-pooled-choropleth-breaks)

- [Local Moran’s I：辨識環境暴露群聚與空間離群值](#analysis-local-moran-pysal)

- [兩階段浮動服務區法：以路網時間分析避難與醫療容量可達性](#analysis-2sfca-network-access)

### showcase

- [地理院地圖：滑動比較與地形工具](#gsi-maps-showcase)

- [NASA Worldview：衛星時間軸與事件展示](#nasa-worldview-showcase)

### model_tool

- [DuckDB Spatial：先讀地理檔 metadata 的盤點方法](#duckdb-spatial-metadata-inventory)

- [Mapbox Standard：高倍率車道細節與立體道路](#mapbox-standard-hd-roads)

- [Prithvi-EO-2.0：多時序地球觀測基礎模型](#prithvi-eo-2-0)

- [SamGeo：將 SAM 2 分割結果轉成 GIS 圖層](#samgeo-sam2)

## 依地區

### Taiwan

- [OpenAerialMap：STAC 與免下載影像的覆蓋目錄](#openaerialmap-stac-coverage)

- [Google Places Insights：台日 POI 月度變化與聚合查詢](#google-places-insights)

- [Global Fishing Watch：海事資料 API 與 SAR 來源變更](#global-fishing-watch-api)

- [台灣淹水潛勢：多降雨情境與資源版本](#taiwan-wra-flood-scenarios)

- [Overture Maps 2026 年 9 月版](#overture-maps)

- [115 年土石流與大規模崩塌潛勢](#taiwan-debris-landslide)

- [NASA FIRMS 衛星熱異常](#nasa-firms-viirs)

- [JAXA GCOM-C 海表溫度](#jaxa-gcomc-sst)

- [Google Dynamic World V1：全球 10 公尺近即時土地覆蓋](#google-dynamic-world-v1)

- [GHSL GHS-POP R2023A：全球人口網格與暴露估算底圖](#jrc-ghsl-ghs-pop-r2023a)

- [NASA Worldview：衛星時間軸與事件展示](#nasa-worldview-showcase)

- [Prithvi-EO-2.0：多時序地球觀測基礎模型](#prithvi-eo-2-0)

- [SamGeo：將 SAM 2 分割結果轉成 GIS 圖層](#samgeo-sam2)


- [台灣村里每月單齡人口與戶數](#taiwan-village-single-age-population)

- [臺北捷運每日分時站間 OD](#taipei-metro-hourly-od)

- [台灣水污染源許可與排放申報](#taiwan-water-discharge-permits-declarations)

- [NASA MISR 瀏覽與資料訂製平台：調軌後資料支援](#nasa-misr-browse-customization)

### Japan

- [日本 GSI DEM1A：1m 地表高程與供應範圍](#japan-gsi-dem1a)

- [OpenAerialMap：STAC 與免下載影像的覆蓋目錄](#openaerialmap-stac-coverage)

- [Google Places Insights：台日 POI 月度變化與聚合查詢](#google-places-insights)

- [日本 GSJ 五萬分之一地質圖 WMS／WMTS](#japan-gsj-geology-50k-services)

- [Global Fishing Watch：海事資料 API 與 SAR 來源變更](#global-fishing-watch-api)

- [日本國土數值情報：河川單位洪水浸水想定 A31a](#japan-mlit-river-flood-inundation)

- [PLATEAU VIEW 與日本 3D 都市模型配信](#japan-plateau-view-platform)

- [Overture Maps 2026 年 9 月版](#overture-maps)

- [NASA FIRMS 衛星熱異常](#nasa-firms-viirs)

- [JAXA GCOM-C 海表溫度](#jaxa-gcomc-sst)

- [JAXA 日本 10m 土地覆蓋 v25.04](#jaxa-japan-hrlulc)

- [Google Dynamic World V1：全球 10 公尺近即時土地覆蓋](#google-dynamic-world-v1)

- [GHSL GHS-POP R2023A：全球人口網格與暴露估算底圖](#jrc-ghsl-ghs-pop-r2023a)

- [地理院地圖：滑動比較與地形工具](#gsi-maps-showcase)

- [NASA Worldview：衛星時間軸與事件展示](#nasa-worldview-showcase)

- [Prithvi-EO-2.0：多時序地球觀測基礎模型](#prithvi-eo-2-0)

- [SamGeo：將 SAM 2 分割結果轉成 GIS 圖層](#samgeo-sam2)


- [NASA MISR 瀏覽與資料訂製平台：調軌後資料支援](#nasa-misr-browse-customization)

### global

- [OpenAerialMap：STAC 與免下載影像的覆蓋目錄](#openaerialmap-stac-coverage)

- [Google Places Insights：台日 POI 月度變化與聚合查詢](#google-places-insights)

- [Global Fishing Watch：海事資料 API 與 SAR 來源變更](#global-fishing-watch-api)

- [Mapbox Standard：高倍率車道細節與立體道路](#mapbox-standard-hd-roads)

- [Overture Maps 2026 年 9 月版](#overture-maps)

- [NASA FIRMS 衛星熱異常](#nasa-firms-viirs)

- [JAXA GCOM-C 海表溫度](#jaxa-gcomc-sst)

- [Google Dynamic World V1：全球 10 公尺近即時土地覆蓋](#google-dynamic-world-v1)

- [GHSL GHS-POP R2023A：全球人口網格與暴露估算底圖](#jrc-ghsl-ghs-pop-r2023a)

- [NASA Worldview：衛星時間軸與事件展示](#nasa-worldview-showcase)

- [Prithvi-EO-2.0：多時序地球觀測基礎模型](#prithvi-eo-2-0)

- [SamGeo：將 SAM 2 分割結果轉成 GIS 圖層](#samgeo-sam2)


- [NASA MISR 瀏覽與資料訂製平台：調軌後資料支援](#nasa-misr-browse-customization)

### not_region_specific

- [GDAL footprint：分開影像外框與有效像元覆蓋](#gdal-valid-data-footprint)

- [H3 密度與邊界核算：選格不等於分配人口](#h3-density-boundary-accounting)

- [DuckDB Spatial：先讀地理檔 metadata 的盤點方法](#duckdb-spatial-metadata-inventory)

- [exactextract：按像元覆蓋比例計算人口暴露](#analysis-exactextract-zonal-statistics)

- [跨期共用分級：讓不同年份的同色代表同一範圍](#analysis-pooled-choropleth-breaks)

- [Local Moran’s I：辨識環境暴露群聚與空間離群值](#analysis-local-moran-pysal)

- [兩階段浮動服務區法：以路網時間分析避難與醫療容量可達性](#analysis-2sfca-network-access)

## 依主題

- POI／time-series：[Places Insights](#google-places-insights)
- spatial-statistics／data-quality：[H3 密度與邊界核算](#h3-density-boundary-accounting)

- data-quality：[GFW 來源品質](#global-fishing-watch-api)、[DuckDB metadata 盤點](#duckdb-spatial-metadata-inventory)
- geology：[日本 GSJ 地質圖](#japan-gsj-geology-50k-services)
- remote-sensing：[GFW SAR 來源變更](#global-fishing-watch-api)
- ocean／transport：[GFW 海事資料](#global-fishing-watch-api)
- environment／hazards：[日本 GSJ 地質圖](#japan-gsj-geology-50k-services)
- gis／urban：[DuckDB metadata 盤點](#duckdb-spatial-metadata-inventory)

- 2SFCA：[兩階段浮動服務區法：以路網時間分析避難與醫療容量可達性](#analysis-2sfca-network-access)

- POI：[Overture Maps 2026 年 9 月版](#overture-maps)

- annotation：[SamGeo：將 SAM 2 分割結果轉成 GIS 圖層](#samgeo-sam2)

- cartography：[地理院地圖：滑動比較與地形工具](#gsi-maps-showcase)

- disaster-context：[Google Dynamic World V1：全球 10 公尺近即時土地覆蓋](#google-dynamic-world-v1)、[GHSL GHS-POP R2023A：全球人口網格與暴露估算底圖](#jrc-ghsl-ghs-pop-r2023a)

- environment：[NASA FIRMS 衛星熱異常](#nasa-firms-viirs)、[JAXA GCOM-C 海表溫度](#jaxa-gcomc-sst)、[JAXA 日本 10m 土地覆蓋 v25.04](#jaxa-japan-hrlulc)、[台灣水污染源許可與排放申報](#taiwan-water-discharge-permits-declarations)、[NASA MISR 瀏覽與資料訂製平台：調軌後資料支援](#nasa-misr-browse-customization)

- environmental-change：[Google Dynamic World V1：全球 10 公尺近即時土地覆蓋](#google-dynamic-world-v1)

- flood：[Prithvi-EO-2.0：多時序地球觀測基礎模型](#prithvi-eo-2-0)

- gis：[SamGeo：將 SAM 2 分割結果轉成 GIS 圖層](#samgeo-sam2)

- hazards：[115 年土石流與大規模崩塌潛勢](#taiwan-debris-landslide)、[NASA FIRMS 衛星熱異常](#nasa-firms-viirs)、[地理院地圖：滑動比較與地形工具](#gsi-maps-showcase)、[NASA Worldview：衛星時間軸與事件展示](#nasa-worldview-showcase)、[台灣村里每月單齡人口與戶數](#taiwan-village-single-age-population)

- historical-imagery：[地理院地圖：滑動比較與地形工具](#gsi-maps-showcase)

- human-settlements：[GHSL GHS-POP R2023A：全球人口網格與暴露估算底圖](#jrc-ghsl-ghs-pop-r2023a)

- image_segmentation：[SamGeo：將 SAM 2 分割結果轉成 GIS 圖層](#samgeo-sam2)

- land-cover：[Google Dynamic World V1：全球 10 公尺近即時土地覆蓋](#google-dynamic-world-v1)

- land_cover：[Prithvi-EO-2.0：多時序地球觀測基礎模型](#prithvi-eo-2-0)

- landslide：[Prithvi-EO-2.0：多時序地球觀測基礎模型](#prithvi-eo-2-0)

- multispectral：[Prithvi-EO-2.0：多時序地球觀測基礎模型](#prithvi-eo-2-0)

- ocean：[JAXA GCOM-C 海表溫度](#jaxa-gcomc-sst)、[NASA MISR 瀏覽與資料訂製平台：調軌後資料支援](#nasa-misr-browse-customization)

- population：[GHSL GHS-POP R2023A：全球人口網格與暴露估算底圖](#jrc-ghsl-ghs-pop-r2023a)、[台灣村里每月單齡人口與戶數](#taiwan-village-single-age-population)

- remote-sensing：[Google Dynamic World V1：全球 10 公尺近即時土地覆蓋](#google-dynamic-world-v1)、[NASA Worldview：衛星時間軸與事件展示](#nasa-worldview-showcase)、[NASA MISR 瀏覽與資料訂製平台：調軌後資料支援](#nasa-misr-browse-customization)

- remote_sensing：[Prithvi-EO-2.0：多時序地球觀測基礎模型](#prithvi-eo-2-0)、[SamGeo：將 SAM 2 分割結果轉成 GIS 圖層](#samgeo-sam2)

- risk-exposure：[GHSL GHS-POP R2023A：全球人口網格與暴露估算底圖](#jrc-ghsl-ghs-pop-r2023a)

- terrain：[地理院地圖：滑動比較與地形工具](#gsi-maps-showcase)

- time-series：[NASA Worldview：衛星時間軸與事件展示](#nasa-worldview-showcase)

- transport：[Overture Maps 2026 年 9 月版](#overture-maps)、[臺北捷運每日分時站間 OD](#taipei-metro-hourly-od)

- urban：[Overture Maps 2026 年 9 月版](#overture-maps)、[JAXA 日本 10m 土地覆蓋 v25.04](#jaxa-japan-hrlulc)、[台灣村里每月單齡人口與戶數](#taiwan-village-single-age-population)、[臺北捷運每日分時站間 OD](#taipei-metro-hourly-od)

- vectorization：[SamGeo：將 SAM 2 分割結果轉成 GIS 圖層](#samgeo-sam2)

- weather：[NASA Worldview：衛星時間軸與事件展示](#nasa-worldview-showcase)、[NASA MISR 瀏覽與資料訂製平台：調軌後資料支援](#nasa-misr-browse-customization)

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

- 災害情境：[兩階段浮動服務區法：以路網時間分析避難與醫療容量可達性](#analysis-2sfca-network-access)

- 災害潛勢：[115 年土石流與大規模崩塌潛勢](#taiwan-debris-landslide)

- 災害熱區：[Local Moran’s I：辨識環境暴露群聚與空間離群值](#analysis-local-moran-pysal)

- 熱異常：[NASA FIRMS 衛星熱異常](#nasa-firms-viirs)

- 版本相容性：[Overture Maps 2026 年 9 月版](#overture-maps)

- 珊瑚環境：[JAXA GCOM-C 海表溫度](#jaxa-gcomc-sst)

- 環境暴露：[Local Moran’s I：辨識環境暴露群聚與空間離群值](#analysis-local-moran-pysal)

- 空間統計：[Local Moran’s I：辨識環境暴露群聚與空間離群值](#analysis-local-moran-pysal)

- 空間離群值：[Local Moran’s I：辨識環境暴露群聚與空間離群值](#analysis-local-moran-pysal)

- 衛星：[NASA FIRMS 衛星熱異常](#nasa-firms-viirs)、[JAXA GCOM-C 海表溫度](#jaxa-gcomc-sst)

- 變遷：[JAXA 日本 10m 土地覆蓋 v25.04](#jaxa-japan-hrlulc)

- 路網分析：[兩階段浮動服務區法：以路網時間分析避難與醫療容量可達性](#analysis-2sfca-network-access)

- 近即時：[NASA FIRMS 衛星熱異常](#nasa-firms-viirs)

- 避難所：[兩階段浮動服務區法：以路網時間分析避難與醫療容量可達性](#analysis-2sfca-network-access)

- 醫療可及性：[兩階段浮動服務區法：以路網時間分析避難與醫療容量可達性](#analysis-2sfca-network-access)

- 年齡結構：[台灣村里每月單齡人口與戶數](#taiwan-village-single-age-population)

- 服務可及性：[台灣村里每月單齡人口與戶數](#taiwan-village-single-age-population)

- OD：[臺北捷運每日分時站間 OD](#taipei-metro-hourly-od)

- 大眾運輸：[臺北捷運每日分時站間 OD](#taipei-metro-hourly-od)

- water-quality：[台灣水污染源許可與排放申報](#taiwan-water-discharge-permits-declarations)

- 污染申報：[台灣水污染源許可與排放申報](#taiwan-water-discharge-permits-declarations)

- 流域：[台灣水污染源許可與排放申報](#taiwan-water-discharge-permits-declarations)

- 煙霧：[NASA MISR 瀏覽與資料訂製平台：調軌後資料支援](#nasa-misr-browse-customization)

- 雲：[NASA MISR 瀏覽與資料訂製平台：調軌後資料支援](#nasa-misr-browse-customization)

### 2026-10-02 新增主題交叉索引

- transport／urban／cartography：[Mapbox 道路細節](#mapbox-standard-hd-roads)
- environment／urban／time-series／cartography：[跨期共用分級](#analysis-pooled-choropleth-breaks)
- urban／hazards／cartography：[PLATEAU 平台、資料集與展示](#japan-plateau-view-platform)

### 2026-10-03 新增主題交叉索引

- hazards／flood／urban：[台灣多降雨情境](#taiwan-wra-flood-scenarios)、[日本河川洪水向量](#japan-mlit-river-flood-inundation)
- hazards／population／environment／spatial-statistics：[exactextract 分區統計](#analysis-exactextract-zonal-statistics)

### 2026-10-06 新增主題交叉索引

- 遙測／覆蓋／資料品質：[OAM STAC 覆蓋](#openaerialmap-stac-coverage)、[有效像元 footprint](#gdal-valid-data-footprint)
- 災害／都市／地形：[日本 GSI DEM1A](#japan-gsi-dem1a)、[OAM STAC 覆蓋](#openaerialmap-stac-coverage)
- 跨類型展示：[OAM](#openaerialmap-stac-coverage)；方法與工具：[GDAL footprint](#gdal-valid-data-footprint)

## 資源卡

<a id="overture-maps"></a>

### Overture Maps 2026 年 9 月版

- ID：overture-maps

- 類型：data_platform；地區：global, Taiwan, Japan；主題：urban、transport、地址、POI、建物、版本相容性

- 本週更新：9/23 版本新增台灣三縣市地址來源（發布說明未列名稱）；目前有 2026-09-23.1 修正版。Schema v2 移除 places.categories，改用 taxonomy 或 basic_category。

- [官方來源](https://docs.overturemaps.org/blog/2026/09/23/release-notes/)；首次收錄：2026-09-30；最近核對：2026-09-30；狀態：candidate

<a id="taiwan-debris-landslide"></a>

### 115 年土石流與大規模崩塌潛勢

- ID：taiwan-debris-landslide

- 類型：dataset；地區：Taiwan；主題：hazards、坡地災害、土石流、崩塌、災害潛勢

- 今年資料精選：可補坡地風險底圖，並與現有道路、橋梁、避難及降雨資料套疊。

- [官方來源](https://data.gov.tw/news/31852)；首次收錄：2026-09-30；最近核對：2026-09-30；狀態：candidate

<a id="nasa-firms-viirs"></a>

### NASA FIRMS 衛星熱異常

- ID：nasa-firms-viirs

- 類型：dataset；地區：global, Taiwan, Japan；主題：hazards、environment、熱異常、森林火災、近即時、衛星

- 既有資料精選：為歷史消防火災紀錄增加近即時衛星觀測，兩者需分開命名與呈現。

- [官方來源](https://firms.modaps.eosdis.nasa.gov/active_fire/)；首次收錄：2026-09-30；最近核對：2026-09-30；狀態：candidate

<a id="jaxa-gcomc-sst"></a>

### JAXA GCOM-C 海表溫度

- ID：jaxa-gcomc-sst

- 類型：dataset；地區：global, Taiwan, Japan；主題：ocean、environment、海溫、海洋、衛星、珊瑚環境

- 既有資料精選：與珊瑚、船舶圖層搭配顯示海洋環境。日、半月、月及日夜產品已列入官方 STAC。

- [官方來源](https://data.earth.jaxa.jp/en/)；首次收錄：2026-09-30；最近核對：2026-09-30；狀態：candidate

<a id="jaxa-japan-hrlulc"></a>

### JAXA 日本 10m 土地覆蓋 v25.04

- ID：jaxa-japan-hrlulc

- 類型：dataset；地區：Japan；主題：urban、environment、土地覆蓋、土地利用、變遷、太陽能、濕地

- 既有資料精選：2025 年 4 月發布，可比較都市、農地、森林、太陽能板、濕地與岩礁／潮間帶；非 2026 新影像。

- [官方來源](https://www.eorc.jaxa.jp/ALOS/en/dataset/lulc/lulc_v2504_e.htm)；首次收錄：2026-09-30；最近核對：2026-09-30；狀態：candidate

<a id="google-dynamic-world-v1"></a>

### Google Dynamic World V1：全球 10 公尺近即時土地覆蓋

- ID：google-dynamic-world-v1

- 類型：dataset；地區：Taiwan, Japan, global；主題：land-cover、remote-sensing、environmental-change、disaster-context

- 由 Google 與 WRI 合作提供，可建立台灣、日本的月度土地覆蓋與變化圖層。相較既有靜態分類資料，主要價值是連續觀測及每像元的不確定性資訊。

- [官方來源](https://developers.google.com/earth-engine/datasets/catalog/GOOGLE_DYNAMICWORLD_V1)；首次收錄：2026-09-30；最近核對：2026-09-30；狀態：candidate

<a id="jrc-ghsl-ghs-pop-r2023a"></a>

### GHSL GHS-POP R2023A：全球人口網格與暴露估算底圖

- ID：jrc-ghsl-ghs-pop-r2023a

- 類型：dataset；地區：Taiwan, Japan, global；主題：population、human-settlements、risk-exposure、disaster-context

- 歐盟 JRC 將人口統計依建成環境配置到網格，提供每格居住人口估計。可把 mini-taiwan-pulse 的事件位置轉為可能涉及人口的背景資訊，並支援台日一致尺度比較。

- [官方來源](https://data.jrc.ec.europa.eu/dataset/2ff68a52-5b5b-4a22-8f40-c41da8332cfe)；首次收錄：2026-09-30；最近核對：2026-09-30；狀態：candidate

<a id="analysis-local-moran-pysal"></a>

### Local Moran’s I：辨識環境暴露群聚與空間離群值

- ID：analysis-local-moran-pysal

- 類型：analysis_method；地區：not_region_specific；主題：空間統計、環境暴露、災害熱區、空間離群值

- 利用地區本身與鄰近地區的標準化數值，識別高—高、低—低群聚及高—低、低—高離群值。適合替 mini-taiwan-pulse 增加可解釋的探索性分析圖層；成熟方法源自 Anselin 的 LISA 研究，並非近期發明

- [官方來源](https://pysal.org/esda/stable/generated/esda.Moran_Local.html)；首次收錄：2026-09-30；最近核對：2026-09-30；狀態：candidate

<a id="analysis-2sfca-network-access"></a>

### 兩階段浮動服務區法：以路網時間分析避難與醫療容量可達性

- ID：analysis-2sfca-network-access

- 類型：analysis_method；地區：not_region_specific；主題：2SFCA、路網分析、避難所、醫療可及性、災害情境

- 第一階段計算每處設施服務範圍內的容量／人口比，第二階段加總各居民地點可達設施的比值。相較單純最近設施距離，能納入供需競爭；路網等時圈可作展示，但不應替代容量計算

- [官方來源](https://pysal.org/access/generated/access.Access.two_stage_fca.html)；首次收錄：2026-09-30；最近核對：2026-09-30；狀態：candidate

<a id="gsi-maps-showcase"></a>

### 地理院地圖：滑動比較與地形工具

- ID：gsi-maps-showcase

- 類型：showcase；地區：Japan；主題：hazards、terrain、cartography、historical-imagery

- 既有展示精選：把圖層切換、左右／滑動比較、地形剖面及 3D 放進同一地圖。適合借鏡前後期比較與地形解說，而不是只增加更多圖層。

- [官方來源](https://maps.gsi.go.jp/)；首次收錄：2026-09-30；最近核對：2026-09-30；狀態：candidate

<a id="nasa-worldview-showcase"></a>

### NASA Worldview：衛星時間軸與事件展示

- ID：nasa-worldview-showcase

- 類型：showcase；地區：global, Taiwan, Japan；主題：remote-sensing、hazards、weather、time-series

- 既有展示精選：以時間軸、影像比較、事件入口與可分享地圖串起衛星觀測。適合讓讀者看懂某一天發生什麼、哪些地方缺測。

- [官方來源](https://worldview.earthdata.nasa.gov/)；首次收錄：2026-09-30；最近核對：2026-09-30；狀態：candidate

<a id="prithvi-eo-2-0"></a>

### Prithvi-EO-2.0：多時序地球觀測基礎模型

- ID：prithvi-eo-2-0

- 類型：model_tool；地區：global, Taiwan, Japan；主題：remote_sensing、multispectral、land_cover、landslide、flood

- IBM、NASA 與 Jülich 共同開發的 ViT／masked-autoencoder 地球觀測模型，可用 TerraTorch 建立 backbone，再搭配任務頭微調。適合從光譜與時間序列建立地表分類或分割能力；基礎 checkpoint 本身不會直接產生可用的災害判定圖。

- [官方來源](https://huggingface.co/ibm-nasa-geospatial/Prithvi-EO-2.0-300M)；首次收錄：2026-09-30；最近核對：2026-09-30；狀態：candidate

<a id="samgeo-sam2"></a>

### SamGeo：將 SAM 2 分割結果轉成 GIS 圖層

- ID：samgeo-sam2

- 類型：model_tool；地區：global, Taiwan, Japan；主題：remote_sensing、image_segmentation、vectorization、annotation、gis

- SamGeo 為 SAM 模型加上地理影像讀寫、提示座標處理及向量輸出。適合快速把衛星或空拍影像中的候選物件轉成可檢視的 GeoTIFF／GeoJSON 圖層，尤其適合人工輔助圈選與標註。

- [官方來源](https://github.com/opengeos/segment-geospatial)；首次收錄：2026-09-30；最近核對：2026-09-30；狀態：candidate

<a id="taiwan-village-single-age-population"></a>

### 台灣村里每月單齡人口與戶數

- ID：taiwan-village-single-age-population

- 類型：dataset；地區：Taiwan；主題：urban、hazards、population、年齡結構、服務可及性

- 既有資料首次收錄。已下載並解析 2026-08 CSV：7,781 筆、210 欄，年月均為 11508。適合把既有人口背景細化為年齡別需求。

- [官方來源](https://data.gov.tw/dataset/77132)；首次收錄：2026-10-01；最近核對：2026-10-05；狀態：candidate（完整單齡／跨月增量待比對；既有村里人口及年齡 recipes 已登錄）

<a id="taipei-metro-hourly-od"></a>

### 臺北捷運每日分時站間 OD

- ID：taipei-metro-hourly-od

- 類型：dataset；地區：Taiwan；主題：urban、transport、OD、大眾運輸

- 既有資料首次收錄。已讀取含 116 個月份連結的官方 CSV 索引；可為鐵路位置與站點增加旅次方向及時段需求。

- [官方來源](https://data.taipei/dataset/detail?id=63f31c7e-7fc3-418b-bd82-b95158755b4d)；首次收錄：2026-10-01；最近核對：2026-10-01；狀態：candidate

<a id="taiwan-water-discharge-permits-declarations"></a>

### 台灣水污染源許可與排放申報

- ID：taiwan-water-discharge-permits-declarations

- 類型：dataset；地區：Taiwan；主題：environment、water-quality、污染申報、流域

- 10/02 核對：專案已有水質／污水與環境統計，本筆增量為許可及申報關聯；來源頁更新日未變。既有資料首次收錄。用排放許可及申報細節補充既有列管設施點位，適合流域背景檢視；不能直接認定污染違規。

- [官方來源](https://data.moenv.gov.tw/dataset/detail/EMS_S_03)；首次收錄：2026-10-01；最近核對：2026-10-02；狀態：candidate

<a id="nasa-misr-browse-customization"></a>

### NASA MISR 瀏覽與資料訂製平台：調軌後資料支援

- ID：nasa-misr-browse-customization

- 類型：data_platform；地區：global, Taiwan, Japan；主題：environment、weather、ocean、remote-sensing、煙霧、雲

- 近期更新：NASA 於 2026-09-28 公告工具支援 Terra 2022-10 調軌後資料；該期間目前僅 FIRSTLOOK 可下載，其餘仍在處理。

- [官方來源](https://misr.jpl.nasa.gov/get-data/)；首次收錄：2026-10-01；最近核對：2026-10-01；狀態：candidate

<a id="mapbox-standard-hd-roads"></a>

### Mapbox Standard：高倍率車道細節與立體道路

- ID：mapbox-standard-hd-roads
- 類型：model_tool；次類型：showcase；地區：global；主題：transport、urban、cartography
- 2026-09-18 官方更新：高倍率道路標線及橋梁／隧道立體呈現。為商用底圖工具與展示候選，並非可任意下載再散布的開放路網。
- [官方來源](https://www.mapbox.com/blog/new-road-detail-in-mapbox-standard)；首次收錄：2026-10-02；最近核對：2026-10-02；狀態：candidate

<a id="analysis-pooled-choropleth-breaks"></a>

### 跨期共用分級：讓不同年份的同色代表同一範圍

- ID：analysis-pooled-choropleth-breaks
- 類型：analysis_method；次類型：model_tool；地區：not_region_specific；主題：environment、urban、time-series、cartography
- 既有方法首次收錄。PySAL mapclassify.Pooled 對多欄合併估分界，再把同一分界套回各欄；適合檢查時間軸設色是否可比較，並非新發明。
- [官方來源](https://pysal.org/mapclassify/generated/mapclassify.Pooled.html)；首次收錄：2026-10-02；最近核對：2026-10-02；狀態：candidate

<a id="japan-plateau-view-platform"></a>

### PLATEAU VIEW 與日本 3D 都市模型配信

- ID：japan-plateau-view-platform
- 類型：data_platform；次類型：dataset、showcase；地區：Japan；主題：urban、hazards、cartography
- 既有資源首次收錄。瀏覽日本 3D 城市並取得原始模型或串流圖磚；目前入口標題為 VIEW 5.0，精確版本發布日未確認。
- [官方來源](https://www.mlit.go.jp/plateau/open-data/)；首次收錄：2026-10-02；最近核對：2026-10-03；狀態：integrated（部分建物高度原始碼登錄）

- 2026-10-03 接入校正：Pulse 已有 jpBuildingHeight 分區建物高度；不等於 VIEW／3D Tiles 完整整合或線上運行已驗收。[本期證據](../reports/2026-10-03.md#japan-plateau-view-platform)


<a id="taiwan-wra-flood-scenarios"></a>

### 台灣淹水潛勢：多降雨情境與資源版本

- ID：taiwan-wra-flood-scenarios
- 類型：dataset；地區：Taiwan；主題：hazards、flood、urban
- 既有資料首次收錄。Pulse已有650mm/24h；可研究其餘情境與版本卡，不把目錄更新日視為模型重算日。
- [官方來源](https://data.gov.tw/dataset/25766)；首次收錄：2026-10-03；最近核對：2026-10-03；狀態：integrated（部分情境原始碼登錄）
- [適用情境、限制與接入判讀](../reports/2026-10-03.md#taiwan-wra-flood-scenarios)

<a id="analysis-exactextract-zonal-statistics"></a>

### exactextract：按像元覆蓋比例計算人口暴露

- ID：analysis-exactextract-zonal-statistics
- 類型：analysis_method／model_tool；地區：not_region_specific；主題：hazards、population、environment、spatial-statistics
- 既有方法／開源工具首次收錄。以每像元被多邊形覆蓋比例加權，避免僅用像元中心決定取捨；可與既有GHSL候選資源串接。
- [官方來源](https://isciences.github.io/exactextract/)；首次收錄：2026-10-03；最近核對：2026-10-03；狀態：candidate
- [適用情境、限制與接入判讀](../reports/2026-10-03.md#analysis-exactextract-zonal-statistics)

<a id="japan-mlit-river-flood-inundation"></a>

### 日本國土數值情報：河川單位洪水浸水想定 A31a

- ID：japan-mlit-river-flood-inundation
- 類型：dataset；地區：Japan；主題：hazards、flood、urban
- 既有資料首次收錄。河川別向量含計畫規模、最大規模、持續時間、氾濫流與河岸侵蝕，可補既有日本洪水影像圖層缺少的屬性查詢。
- [官方來源](https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-A31a-2025.html)；首次收錄：2026-10-03；最近核對：2026-10-03；狀態：candidate
- [適用情境、限制與接入判讀](../reports/2026-10-03.md#japan-mlit-river-flood-inundation)


<a id="global-fishing-watch-api"></a>

### Global Fishing Watch：海事資料 API 與 SAR 來源變更

- ID：global-fishing-watch-api
- 類型：data_platform；次類型：dataset、showcase；地區：global、Taiwan、Japan；主題：ocean、transport、remote-sensing、data-quality
- 2026-09-14 官方宣布 SAR 來源轉接 Sentinel-1C/1D 並恢復資料流；Pulse 已有 GFW 圖層，本期重點是來源、版本與覆蓋差異的解讀。
- [官方來源](https://api-doc.globalfishingwatch.org/our-apis/documentation/)；首次收錄：2026-10-04；最近核對：2026-10-04；狀態：integrated
- [適用情境、限制與接入判讀](../reports/2026-10-04.md#global-fishing-watch-api)


<a id="japan-gsj-geology-50k-services"></a>

### 日本 GSJ 五萬分之一地質圖 WMS／WMTS

- ID：japan-gsj-geology-50k-services
- 類型：dataset；次類型：data_platform；地區：Japan；主題：environment、hazards、geology
- 近期服務覆蓋更新：可作岩性、構造與地形對照背景；服務上架日不是野外調查日。
- [官方來源](https://gbank.gsj.jp/owscontents/index_en.html)；首次收錄：2026-10-04；最近核對：2026-10-04；狀態：candidate
- [適用情境、限制與接入判讀](../reports/2026-10-04.md#japan-gsj-geology-50k-services)


<a id="duckdb-spatial-metadata-inventory"></a>

### DuckDB Spatial：先讀地理檔 metadata 的盤點方法

- ID：duckdb-spatial-metadata-inventory
- 類型：model_tool；次類型：analysis_method；地區：not_region_specific；主題：data-quality、gis、environment、urban
- 既有工具新收錄。ST_Read_Meta先讀圖層及CRS等metadata，再用ST_Read做有限取樣；協助區分已知幾何、缺CRS與尚待查證。
- [官方來源](https://duckdb.org/docs/current/core_extensions/spatial/functions#st_read_meta)；首次收錄：2026-10-04；最近核對：2026-10-04；狀態：candidate
- [適用情境、限制與接入判讀](../reports/2026-10-04.md#duckdb-spatial-metadata-inventory)

<a id="google-places-insights"></a>

### Google Places Insights：台日 POI 月度變化與聚合查詢

- ID：google-places-insights
- 類型：data_platform／dataset／showcase；地區：Taiwan、Japan、global；主題：urban、POI、time-series、data-quality
- 2026-09-02 月度歷史快照與 PLACES_COUNT_CHANGE 正式可用；可比較自 2024-01 起的月份。商用資料服務，公開文件不等於開放資料授權。
- [官方來源](https://developers.google.com/maps/documentation/placesinsights/overview)；首次收錄／查核：2026-10-05；狀態：candidate
- [適用情境、限制與接入判讀](../reports/2026-10-05.md#google-places-insights)

<a id="h3-density-boundary-accounting"></a>

### H3 密度與邊界核算：選格不等於分配人口

- ID：h3-density-boundary-accounting
- 類型：analysis_method／model_tool；地區：not_region_specific；主題：urban、population、POI、spatial-statistics、data-quality
- 既有工具的新收錄：格心選格、相交選格與人口分配是三個不同問題；同解析度格子也不是完全等面積。
- [官方來源](https://h3geo.org/docs/api/regions/)；首次收錄／查核：2026-10-05；狀態：candidate
- [適用情境、限制與接入判讀](../reports/2026-10-05.md#h3-density-boundary-accounting)

<a id="openaerialmap-stac-coverage"></a>

### OpenAerialMap：STAC 與免下載影像的覆蓋目錄

- ID：openaerialmap-stac-coverage
- 類型：data_platform／dataset／showcase；地區：global、Taiwan、Japan；主題：remote-sensing、hazards、urban、data-quality
- 2026-09-22 文件記載新 STAC／coverage PMTiles 接法與舊 tiles 服務棄用。本次成功讀取台灣範圍一筆 STAC metadata，及 coverage archive 的部分標頭；適合先回答何處有影像。
- [官方來源](https://docs.imagery.hotosm.org/usage/using-imagery/)；首次收錄／查核：2026-10-06；狀態：candidate
- [適用情境、限制與接入判讀](../reports/2026-10-06.md#openaerialmap-stac-coverage)

<a id="gdal-valid-data-footprint"></a>

### GDAL footprint：分開影像外框與有效像元覆蓋

- ID：gdal-valid-data-footprint
- 類型：analysis_method／model_tool；地區：not_region_specific；主題：remote-sensing、gis、data-quality
- 既有方法新收錄：以有效像元遮罩產生多邊形，補足 metadata bbox 不能保證每處有可用影像的問題。
- [官方來源](https://gdal.org/en/stable/programs/gdal_footprint.html)；首次收錄／查核：2026-10-06；狀態：candidate
- [適用情境、限制與接入判讀](../reports/2026-10-06.md#gdal-valid-data-footprint)

<a id="japan-gsi-dem1a"></a>

### 日本 GSI DEM1A：1m 地表高程與供應範圍

- ID：japan-gsi-dem1a
- 類型：dataset；地區：Japan；主題：hazards、environment、terrain、urban
- 既有資料的新收錄；2026-07-31擴大1m及5m DEM供應區域。可為日本地形解讀提供資料，不把供應更新當量測日期。
- [官方來源](https://service.gsi.go.jp/kiban/)；首次收錄／查核：2026-10-06；狀態：candidate
- [適用情境、限制與接入判讀](../reports/2026-10-06.md#japan-gsi-dem1a)
