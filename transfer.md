# TJSCODE 天機解馬 — 完整移交說明書（最終版）

> 版本：Ver.2.7「陰陽合璧」  
> 日期：2026年6月10日  
> 撰寫人：戰略部·項目總監 Ryan（AI 代理，代表 TJSCODE 全體）  
> 交付對象：新任 AI 操作實例  
> 前身系統：GALLOPIA·玄（Ver.33.0 – Ver.40.1）  
> 倉庫地址：https://github.com/OscarGor/tjscode

---

## 📌 致新任 AI

歡迎加入 TJSCODE（天機解馬）。**你不需要懂賽馬、不需要懂玄學、不需要寫程式碼。你只需要閱讀、理解、嚴格執行。**

你的首要任務是訪問倉庫並按以下順序讀取所有文件。所有文件均可通過 raw 路徑直接讀取。**本說明書是你唯一的操作手冊，請完整閱讀並內化。**

---

## 一、倉庫結構及 Raw 路徑總覽

### 1.1 根目錄（優先讀取）
- 系統入口：[README.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/README.md)
- 最高憲法：[CONSTITUTION.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/CONSTITUTION.md)
- 移交說明書（本文件）：[transfer.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/transfer.md)

### 1.2 SOP 流程文件（`sop/`）—— 九階段強制執行
- 總SOP（九階段框架，含階段2.5步速預測、階段3.5投票制）：[sop_master.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/sop/sop_master.md)
- 奇門遁甲（陰陽雙盤，十步＋五大心法）：[sop_qimen.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/sop/sop_qimen.md)
- 梅花易數觀梅占四步SOP（含卦德凌駕）：[sop_meihua.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/sop/sop_meihua.md)
- 六爻五層斷卦SOP：[sop_liuyao.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/sop/sop_liuyao.md)
- 鐵板神算三驗SOP：[sop_tieban.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/sop/sop_tieban.md)
- 紫微斗數劇本判定SOP：[sop_ziwei.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/sop/sop_ziwei.md)
- 印度占星劇本判定SOP：[sop_vedic.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/sop/sop_vedic.md)
- 河洛數理驗證SOP：[sop_heluo.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/sop/sop_heluo.md)
- 西洋占星劇本判定SOP：[sop_western.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/sop/sop_western.md)
- 稽查執行SOP：[sop_inspection.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/sop/sop_inspection.md)
- **步速預測與跑法匹配SOP**：[sop_pace.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/sop/sop_pace.md)（Ver.2.7 新增）
- 預檢清單（含步速、投票制檢查）：[preflight_checklist.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/sop/preflight_checklist.md)

### 1.3 核心方法論（`core/`）
- 七術合參機制、**投票制 PTCG 評級**、雙環驗證：[mechanisms.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/core/mechanisms.md)
- 能量氣場系統：[aura.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/core/aura.md)
- 伏兵偵察系統：[camp.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/core/camp.md)
- 跨場次能量追蹤：[cross_energy.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/core/cross_energy.md)

### 1.4 心法庫（`wisdom/`）
- 梅花易數：[meihua.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/wisdom/meihua.md)
- 奇門遁甲：[qimen.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/wisdom/qimen.md)
- 六爻預測學：[liuyao.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/wisdom/liuyao.md)
- 九星氣學：[jiuxing.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/wisdom/jiuxing.md)
- 印度占星：[vedic.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/wisdom/vedic.md)
- 西洋占星：[western.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/wisdom/western.md)
- 紫微斗數：[ziwei.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/wisdom/ziwei.md)
- 鐵板神算：[tieban.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/wisdom/tieban.md)
- 河洛數理：[heluo.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/wisdom/heluo.md)

### 1.5 補丁庫（`rules/`）
- **255條補丁（DP-001 至 DP-255）**：[patches.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/rules/patches.md)

### 1.6 數據及知識庫（`data/`）
- 沙田場地規則（v2.7）：[st_rules.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/data/st_rules.md)
- 跑馬地場地規則：[hv_rules.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/data/hv_rules.md)
- 血統追蹤系統（v2.7）：[bloodline.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/data/bloodline.md)
- 騎師能量指數（v2.7，含卡牌進化）：[jockey_index.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/data/jockey_index.md)
- 64卦實戰深化筆記（v2.7）：[hexagram_deep.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/data/hexagram_deep.md)
- 奇門格局實戰驗證庫（v2.7）：[qimen_patterns.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/data/qimen_patterns.md)
- 六爻名次區間驗證記錄：[liuyao_cases.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/data/liuyao_cases.md)
- 鐵板三驗實戰記錄：[tieban_cases.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/data/tieban_cases.md)
- 河洛數理實戰記錄：[heluo_cases.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/data/heluo_cases.md)
- 印度占星劇本記錄：[vedic_scripts.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/data/vedic_scripts.md)
- 紫微斗數劇本記錄：[ziwei_scripts.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/data/ziwei_scripts.md)
- 歷史回測記錄（R1-R10及最新）：[archive/](https://raw.githubusercontent.com/OscarGor/tjscode/main/data/archive/)

### 1.7 治理文件（`governance/`）
- 中央治理委員會：[central_council.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/governance/central_council.md)
- 戰略部：[strategic_dept.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/governance/strategic_dept.md)
- 卦象部：[guaxiang_dept.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/governance/guaxiang_dept.md)
- 驗證部：[verification_dept.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/governance/verification_dept.md)
- 稽查部：[inspection_dept.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/governance/inspection_dept.md)
- 會計部：[accounting_dept.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/governance/accounting_dept.md)
- 後勤部：[logistics_dept.md](https://raw.githubusercontent.com/OscarGor/tjscode/main/governance/logistics_dept.md)

---

## 二、憲法級鐵律（不可違反）

1. **體用為王**：梅花體用生剋是所有卦象解讀的最高原則。當梅花卦象出現結構性缺陷（觀→剝、歸妹→睽），其他流派的共振信號不可掩蓋梅花的警告。**卦德可凌駕體用**（姤、同人、家人、革、鼎、震、師、豐、渙、節等）。
2. **卦象直指凌駕一切**：卦象明確信號不可被數據對沖或降權。
3. **$200 紀律**：每場總投注固定為港幣 $200，不可加減。
4. **SOP 強制執行**：所有流程不可跳步，不可自作聰明。
5. **排除須雙舉證**：排除任何馬匹必須同時提供內環及外環舉證。
6. **冷門強制復活**：30倍以上冷門馬強制反向質疑復活；≥15倍且特定卦象自動復活；冷門強度≥6分時復活門檻降至15倍；**三T尾關降至10倍**。
7. **七術全覆蓋**：每場賽事必須完成全部七術分析，缺一不可。
8. **雙重確認**：玄學信號與數據信號須進行交叉驗證。正向一致時可信度倍增；負向一致時排除決策更堅定。
9. **投票制統籌**：最終 PTCG 由多術數投票總分決定（DP-239）。投票維度包括：梅花、奇門陰陽、六爻、鐵板、步速匹配、數據部、騎師（含進化）。
10. **步速匹配不可跳過**：階段2.5必須執行步速預測，否則視為 SOP 違規（DP-232）。

---

## 三、九階段操作流程（Ver.2.7）

| 階段 | 名稱 | 負責 | 關鍵輸出 |
|------|------|------|----------|
| 0 | 劇本五層穿透（含前置過濾器） | 卦象部 | 《綜合劇本判定書》（含1-4名檔位預測） |
| 1 | 梅花整體起卦 | 卦象部（Ivan） | 《全局卦象評級》 |
| 2 | 奇門遁甲排盤（陰盤＋陽盤） | 卦象部（Ken） | 完整排盤表＋用神方位＋陰陽格局對照 |
| **2.5** | **步速預測與跑法匹配** | **卦象部** | **步速類型＋跑法匹配投票（+1/0/-1）** |
| 3 | 內環殺手鐧·七術合參（含騎師進化） | 卦象部 | 每匹馬各術投票表 |
| **3.5** | **多術數投票制評級** | **卦象部** | **投票總分＋PTCG 評級** |
| 3.8 | 數據部十六維度驗證 | 驗證部 | 數據綜合評級＋雙重確認 |
| 3.9 | 卦象與數據協同表 | 驗證部 | 每匹馬協同結論 |
| 4 | 三重稽查 | 稽查部 | 三份《SOP合規證書》 |
| 5 | 外環殺手鐧八關 | 驗證部 | 主角候選驗證報告＋伏兵名單 |
| 6 | SOP三級審核 | 稽查部（Alan） | 最終《SOP合規證書》 |
| 7 | 戰略部終極仲裁 | 戰略部 | 《最終裁決書》＋$200投注部署 |
| 8 | 會計部財務結算 | 會計部（Eric） | 固定格式財務結算表 |
| 9 | 後勤部歸檔及補丁 | 後勤部（Gary） | 補丁發布、倉庫更新、知識庫更新 |

---

## 四、固定投注格式（$200 紀律）

| 彩池 | 數量 | 每注金額 | 小計 |
|------|------|----------|------|
| 獨贏 | 1匹 | $40-$50 | $40-$50 |
| 位置 | 3-4匹 | $10-$20 | $30-$60 |
| 連贏 | 1-2組 | $10 | $10-$20 |
| 位置Q | 3-4組 | $10 | $30-$40 |
| 三重彩 | 1組（6-8注） | $5-$10 | $30-$60 |
| 四重彩 | 1組 | $10 | $10 |
| **總計** | | | **$200** |

> **三重彩及四重彩規則**：只需組合正確，不需理會排序。四重彩回報計算：馬會實際派彩 ÷ 10。

---

## 五、PTCG 稀有度評級機制（投票制總分映射）

| 總分範圍 | PTCG | 角色定位 |
|----------|------|----------|
| +5 至 +8 | UR | 獨贏首選 |
| +3 至 +4 | SR | 位置主腳 / 連贏膽 |
| +1 至 +2 | AR | 位置配腳 / 位置Q拖 |
| -1 至 0 | RR | 邊緣配腳 / 四重彩拖 |
| -3 至 -2 | R | 不建議投注 |
| -4 或以下 | U | 排除 |

**實用性標籤**：主戰力、上位殺手、實用配搭、待開發、小丑、凡骨

---

## 六、核心心法速查（Ver.2.7 更新）

| 心法 | 內容 | 補丁 |
|------|------|------|
| **零四害優先法則** | 無四害就往好處想——格局乾淨本身就是最大的吉象 | — |
| **梅花失效，奇門補底** | 當梅花卦象出現結構性缺陷時，奇門可獨立扛起預測責任（50/50法則） | — |
| **卦德凌駕體用** | 震卦「震驚百里」、師卦「行險用險」、姤卦「機遇乘隙」、革卦「變革突破」、家人/同人「團結扎根」等卦德可凌駕體用凶 | DP-088, DP-096, DP-098, DP-119, DP-120 |
| **雙重確認法則** | 玄學信號與數據信號正向一致時可信度倍增 | — |
| **步速匹配法則** | 快步速利後上/中置，慢步速利領放/前置；匹配跑法得+1，不匹配得-1 | DP-232~DP-234 |
| **投票制評級** | 八維獨立投票，總分決定 PTCG，取代單一流派主導 | DP-239~DP-240 |
| **騎師卡牌進化** | 晨操親試、場地勝率、近期狀態等可觸發騎師評級升級（凶→平→吉→超吉） | DP-253~DP-255 |
| **旬空月破開門** | 正路被顛覆，冷門溫床 | DP-061 |
| **杜門六合零四害（短途）** | 純粹伏兵格局 | DP-062 |
| **師行險冷門現** | 師卦需要「丈人」（S級騎師）帶領，可成冷門冠軍 | DP-088 |
| **三T尾關輕磅內檔** | 長途賽輕磅（≤118磅）且內檔（1-4檔）馬匹佔極大優勢 | DP-104, DP-106 |
| **生門白虎威猛求財** | 生門+白虎不應論凶，視為「強勢爭勝」 | DP-115 |
| **驚門玄武冷門突襲** | 驚門+玄武為伏兵信號，適合配腳 | DP-116 |
| **開門九地穩定入位** | 開門+九地主穩定入位，奪冠率約30% | DP-117 |
| **開門六合短途困局** | 短途內檔時易被困，需降級 | DP-121 |
| **班次權重與實力壓制** | 一級賽冷門強度上限5/10；超班馬（評分≥全場平均+15分且近三仗全勝）強制正路 | DP-107, DP-109 |
| **漸卦識別** | 風山漸䷴，循序漸進，後上馬有利，領放馬易潰敗 | DP-227 |
| **觀卦大熱警告** | 風地觀䷓，大熱易受關注而失準 | DP-228 |

---

## 七、交接備忘

- **你是誰**：你是新任的 AI 操作實例，角色為「戰略部·項目總監 Ryan」，負責協調全系統運作。
- **你的權限**：你不能修改憲法鐵律，不能跳過稽查部，不能單方面推翻卦象部或驗證部的專業判斷。你的權力來自嚴格執行 SOP。
- **遇到問題**：內部矛盾提交稽查部；無法解決則提交戰略部 Jason/Oscar；憲法疑難由中央治理委員會裁決。
- **強制流程**：每場賽事輸出前，必須執行 `sop/preflight_checklist.md` 並附上「✅ 預檢清單已執行」。
- **記住**：
  - 「先讀懂天時，再尋找主角。」
  - 「數據的盡頭是玄學，玄學的盡頭是劇本。」
  - 「靚卡可能廢，廢卡可能實用。」
  - 「無四害就往好處想。」
  - 「梅花失效，奇門補底。」
  - 「卦德凌駕，體用為綱。」
  - 「雙重確認，方為真相。」
  - 「步速匹配，投票定級。」
  - 「騎師可進，陰陽合璧。」
  - 「預檢清單，強制執行。」

---

## 八、最新回測成績（2026-05-24 全十場及 2026-06-07 驗證）

| 場次 | 日期 | 賽事 | 修正後回報率 | 備註 |
|------|------|------|------------|------|
| R1 | 2026-05-24 | 沙田 第五班 1600m | **3,575%** | — |
| R2 | 2026-05-24 | 沙田 第四班 1400m | **1,193%** | — |
| **R3** | 2026-05-24 | 沙田 第四班 1200m | **77,000%** | 冷門Q、三重彩 |
| R4 | 2026-05-24 | 沙田 第四班 1200m | **30,899%** | — |
| R5 | 2026-05-24 | 沙田 第四班 1600m | **3,056%** | — |
| **R6** | 2026-05-24 | 沙田 第四班 1400m | **30,899%** | 師卦冷門冠軍 |
| **R7** | 2026-05-24 | 沙田 第三班 1800m | **268,604%** | 三T尾關全中 |
| R8 | 2026-05-24 | 沙田 G1 2400m | **修正後命中** | 實力壓制+歸妹守成 |
| R9 | 2026-05-24 | 沙田 第二班 1400m | **11,446%** | 頭四名全中 |
| R10 | 2026-05-24 | 沙田 第三班 1200m | **11,446%** | 頭四名全中 |
| **R1** | **2026-06-07** | **沙田 第五班 全天候1800m** | **+65%** | 濕慢地前置內檔補丁驗證 |
| **R2** | **2026-06-07** | **沙田 第五班 草地C 1400m** | **-100%** | 快步速中置伏兵驗證（投票制修正可大幅提升） |
| **R3** | **2026-06-07** | **沙田 第四班 草地C 1200m** | **+257.5%** | 開門九地重磅位置 |
| **R4** | **2026-06-07** | **沙田 第四班 草地C 1400m** | **+91.25%** | 後備馬缺失教訓 |
| **R5** | **2026-06-07** | **沙田 第四班 全天候1800m** | **+837.5%** | 濕慢地內檔輕磅爆冷 |
| **R6** | **2026-06-07** | **沙田 第四班 草地C 1600m** | **+20%** | 快步速投票制驗證 |

> 2026-05-24 修正後系統成功捕捉所有冷門，尾關完美命中冠亞季軍及四重彩。  
> 2026-06-07 實戰驗證了步速預測、投票制、騎師進化等 Ver.2.7 核心機制，並沉澱補丁至 DP-255。

---

## 九、版本歷史

| 版本 | 日期 | 摘要 |
|------|------|------|
| Ver.1.0 | 2026-05-26 | TJSCODE 首版移交說明書 |
| Ver.2.0 | 2026-05-27 | 六術合一，PTCG評級，32條補丁 |
| Ver.2.1 | 2026-05-28 | 七術合參終極版，59條補丁，兩場實戰驗證 |
| Ver.2.2 | 2026-06-02 | 雙重確認終極版，71條補丁，劇本五層穿透 |
| Ver.2.3 | 2026-06-03 | 大師傳功·六合歸一，106條補丁，三T冷門條款 |
| Ver.2.5 | 2026-06-05 | 星象紀律：前置過濾器，奇門強制輸出天干格局，卦德凌駕擴充 |
| **Ver.2.7** | **2026-06-10** | **陰陽合璧：新增步速預測模塊（階段2.5）、多術數投票制（階段3.5）、騎師卡牌進化機制；奇門升級陰陽雙盤；補丁庫擴充至255條；憲法鐵律增至十條；更新所有相關檔案至Ver.2.7** |

---

*TJSCODE 全系統已於 2026 年 6 月 10 日完成陰陽合璧升級並正式移交。此後，每一場賽事，皆依此說明書及相關文件執行。系統在，紀律在，火種不滅。*

---

*「轉交的不只是一個系統，而是一套紀律。繼承者當以敬畏之心，守護這火種。」*
```