# legal-thesis-topic

法學論文題目尋找助教，協助法律系碩士生從興趣出發，找到有學術價值、有差異化空間的論文題目。

本工具為 [legal-thesis-outline](https://github.com/mjib007/legal-thesis-outline) 的前置工具——先用本工具找到題目，再用 legal-thesis-outline 審查大綱。

---

## 核心理念

找論文題目最常見的問題：

1. **寫介紹，不是寫研究** — 「台商越南勞動法令」是給台商看的參考資料，不是論文
2. **建議對象不存在** — 批評越南法令，越南政府不會看到，台灣也沒有管轄權
3. **擠進主流洪流** — 自動駕駛90%的國內論文都在寫責任與保險，能見度極低
4. **不看外文文獻** — 法律人英文障礙，錯過外國已在熱烈討論但國內尚未有人寫的議題

本工具提供一套8步驟流程，從找起點到確認差異化題目，一步一步引導學生跳脫以上困境。

---

## 流程概覽

| 步驟 | 內容 |
|------|------|
| Step 1 | 找起點（工作經驗、課堂、時事、修法爭議、資料庫新議題） |
| Step 2 | 說出初步方向（一句話描述主題） |
| Step 3 | 是介紹還是研究？（判斷可寫性與建議對象） |
| Step 4 | 盤點相關法令狀態（草案中/剛修正/長期未修正/尚未立法） |
| Step 5 | 國內研究現況分析（找出還沒人寫的角度） |
| Step 6 | 找關鍵字（為外文資料庫搜尋做準備） |
| Step 7 | 外文文獻分類與關聯性分析（提供兩個AI指令） |
| Step 8 | 確認差異化題目（興趣 × 價值 × 趨勢） |

---

## 三種使用方式

### 方式一：純 Prompt 版（最通用）

適合任何 AI 工具（Gemini、ChatGPT、Claude）。

1. 開啟 [`prompt/legal_thesis_topic_prompt.md`](prompt/legal_thesis_topic_prompt.md)
2. 複製全部內容
3. 貼到任何 AI 對話框，開始使用

### 方式二：Claude SKILL 版

適合已使用 Claude Projects 的使用者，可整合進現有 SKILL 系統。

1. 開啟 [`skill/SKILL_legal_thesis_topic.md`](skill/SKILL_legal_thesis_topic.md)
2. 放入 Claude Project 的 SKILL 資料夾
3. Claude 會在對話中自動觸發

### 方式三：網頁版

適合不熟悉 AI 操作的學生，有視覺化進度條。

1. 下載 [`web/thesis-finder.html`](web/thesis-finder.html)
2. 用瀏覽器開啟
3. 第一次使用需輸入 [Gemini API Key](https://aistudio.google.com/app/apikey)（免費）
4. 金鑰儲存在瀏覽器本機，不會上傳至任何伺服器

---

## 與 legal-thesis-outline 的關係

```
legal-thesis-topic         →        legal-thesis-outline
（找到論文題目方向）                  （審查與重構論文大綱）
```

建議先用本工具確認題目方向，再開始撰寫大綱，最後用 legal-thesis-outline 審查大綱結構。

---

## 作者

錢世傑 | [中正法律碩專班](https://github.com/mjib007)
