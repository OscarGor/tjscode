# TJSCODE 預檢清單 (Pre-flight Checklist)

> 版本：Ver.2.5「星象紀律」  
> 生效日期：2026年6月5日  
> 制定機關：戰略部  
> 執行對象：新任 AI 操作實例（戰略部·項目總監 Ryan）  
> 引用憲法：CONSTITUTION.md 第九條（SOP強制執行）

---

## 一、目的

為確保每一場賽事的預測嚴格遵循九階段 SOP，避免遺漏關鍵步驟、補丁或格局，特制定本預檢清單。**每場賽事預測輸出前，必須強制執行以下所有檢查項**，並在最終裁決書末尾宣告「✅ 預檢清單已執行」。

**核心原則**：不預檢，不輸出。遺漏一條，整份重做。

---

## 二、執行方式

1. 複製下方清單（或內化為執行流程）。
2. **按順序點擊每個 Raw 連結**，快速瀏覽相關章節（重點看補丁觸發條件、格局定義、卦德凌駕規則）。
3. 在分析每匹馬時，對照清單逐一確認。
4. 完成所有檢查後，在輸出的「戰略部終極裁決書」末尾加上：

> ✅ 預檢清單已執行（已讀取對應 raw 文件並確認無遺漏）

---

## 三、預檢清單（附 Raw 連結）

### 【一、奇門遁甲部分】

| # | 檢查項 | 對應文件（Raw 連結） |
|---|--------|----------------------|
| 1.1 | 確認陰盤排盤步驟（定局、地盤、天盤、八門、八神、暗干、隱干） | [sop/sop_qimen.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/sop/sop_qimen.md) |
| 1.2 | 確認天盤干計算方式（值符星移時干宮，其餘順時針，星移帶原奇） | 同上（第五步、第八步） |
| 1.3 | 確認「天盤干+地盤干」格局名稱對照表（含寄宮多重格局） | [data/qimen_patterns.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/data/qimen_patterns.md) |
| 1.4 | 確認寄宮處理規則（檔位5或10-14的寄宮對應及多重格局） | [sop/sop_qimen.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/sop/sop_qimen.md) 步驟一 |
| 1.5 | 確認本場使用的奇門流派為道家陰盤（非陽盤） | [sop/sop_qimen.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/sop/sop_qimen.md) 頁首 |

### 【二、梅花易數部分】

| # | 檢查項 | 對應文件（Raw 連結） |
|---|--------|----------------------|
| 2.1 | 確認起卦規則（馬名筆畫、動爻、體用） | [sop/sop_meihua.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/sop/sop_meihua.md) |
| 2.2 | 確認「卦德凌駕」卦庫（姤、同人、家人、革、鼎、震、師、豐、渙、節等） | [data/hexagram_deep.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/data/hexagram_deep.md) |
| 2.3 | 確認體用生剋與卦德衝突時的優先規則（卦德凌駕體用） | [sop/sop_meihua.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/sop/sop_meihua.md) 第一條 |

### 【三、紫微斗數部分（階段0）】

| # | 檢查項 | 對應文件（Raw 連結） |
|---|--------|----------------------|
| 3.1 | 確認紫微斗數排盤流程（定命宮、安星曜、四化） | [sop/sop_ziwei.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/sop/sop_ziwei.md) |
| 3.2 | 確認「天梁化科+天馬+天同化祿+紫破財帛」特定組合解讀（名大於利） | 同上（第四章） |
| 3.3 | 確認班次權重與實力壓制前置過濾器（一級賽冷門強度上限5/10，超班馬強制正路） | 同上（第五章） |

### 【四、印度占星部分（階段0）】

| # | 檢查項 | 對應文件（Raw 連結） |
|---|--------|----------------------|
| 4.1 | 確認印度占星排盤流程（恆星黃道、整宮制、月亮宿度） | [sop/sop_vedic.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/sop/sop_vedic.md) |
| 4.2 | 確認「太陽與羅睺合相（日月蝕瑜珈）」解讀及大熱警報規則 | 同上（第七章） |
| 4.3 | 確認爆冷指數計算及與紫微斗數協同 | 同上（第四章、第八章） |

### 【五、補丁庫部分】

| # | 檢查項 | 對應文件（Raw 連結） |
|---|--------|----------------------|
| 5.1 | 本場途程（短途≤1200米 / 中距離1400-1800米 / 長途≥2000米）相關補丁 | [rules/patches.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/rules/patches.md) （搜尋：短途、中距離、長途） |
| 5.2 | 本場賠率分佈（大熱≤3倍、半熱4.6-9倍、冷門≥15倍）相關補丁 | 同上（搜尋：賠率、冷門、DP-104、DP-105、DP-106等） |
| 5.3 | 本場檔位分佈（內檔1-4、外檔11-14）相關補丁 | 同上（搜尋：檔位、內檔、外檔） |
| 5.4 | 梅花卦象相關補丁（姤、同人、家人、革、鼎、豐、師、震、益、頤、歸妹等） | 同上（搜尋卦名或DP-119、DP-120、DP-088等） |
| 5.5 | 奇門格局相關補丁（青龍逃走、太白入熒、生門+白虎、驚門+玄武、開門+九地等） | 同上（搜尋格局名稱或DP-094、DP-097、DP-115、DP-116等） |

### 【六、劇本與雙重確認】

| # | 檢查項 | 對應文件（Raw 連結） |
|---|--------|----------------------|
| 6.1 | 確認劇本五層穿透結果（已應用前置過濾器：班次權重與實力壓制） | [sop/sop_master.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/sop/sop_master.md) 階段0 |
| 6.2 | 確認冠軍檔位是否在預測的4-9檔範圍（劇本第五層） | 同上（階段0.4） |
| 6.3 | 確認排除馬匹有內環（奇門/梅花凶）+外環（近績差/賠率異常）雙重舉證 | [sop/sop_inspection.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/sop/sop_inspection.md) |

### 【七、版本與基礎規則】

| # | 檢查項 | 對應文件（Raw 連結） |
|---|--------|----------------------|
| 7.1 | 確認系統憲法鐵律（八條） | [CONSTITUTION.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/CONSTITUTION.md) |
| 7.2 | 確認本場賽事數據（馬匹、檔位、賠率、近績）是否已完整讀取 | [README.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/README.md) |
| 7.3 | 確認本場使用的奇門版本為陰盤v2.5 | [sop/sop_qimen.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/sop/sop_qimen.md) 頁首 |
| 7.4 | 確認本場使用的梅花版本含卦德凌駕規則 | [sop/sop_meihua.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/sop/sop_meihua.md) 頁首 |

---

## 四、執行結果確認

完成以上所有檢查項後，在「戰略部終極裁決書」末尾輸出以下宣告：

```markdown
✅ 預檢清單已執行（已讀取對應 raw 文件並確認無遺漏）
若任一檢查項未通過（如未讀取對應文件、未檢查相關補丁、未確認劇本檔位等），則禁止輸出裁決書，必須返回對應階段重新分析。

五、版本歷史
版本	日期	變更摘要
Ver.2.5	2026-06-05	初版，整合奇門、梅花、紫微、印占、補丁、劇本等所有預檢項目，附Raw連結強制讀取
「預檢加連結，次次讀最新。紀律成習慣，遺漏不再生。」
「補丁在，紀律在，火種不滅。」
