# 🔍 法學論文題目助教｜Legal Thesis Topic Finder

![Profile views](https://komarev.com/ghpvc/?username=mjib007&label=Profile%20views&color=4c8eda&style=flat)
[![Stars](https://img.shields.io/github/stars/mjib007/legal-thesis-topic?style=flat&color=yellow)](https://github.com/mjib007/legal-thesis-topic/stargazers)
[![Forks](https://img.shields.io/github/forks/mjib007/legal-thesis-topic?style=flat&color=blue)](https://github.com/mjib007/legal-thesis-topic/network/members)
![AI](https://img.shields.io/badge/AI-Claude%20(Anthropic)-blueviolet)
![Platform](https://img.shields.io/badge/Platform-claude.ai%20%7C%20ChatGPT%20%7C%20Gemini-orange)
![Language](https://img.shields.io/badge/Language-繁體中文-red)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)
![Status](https://img.shields.io/badge/status-active-success)

> 本開源內容是「論文寫作方法與AI輔助」課程之教材，本課程開設於中正大學高階法律碩士專班。

> 一套專為法律系碩士生設計的 AI 輔助論文題目尋找工具，透過8步驟流程，從興趣出發，找到有學術價值、有建議對象、有差異化空間的論文題目。

---

## ✨ 功能特色

- 🎯 **逐步引導**：一次只問一個問題，不讓學生不知所措
- 🔍 **介紹vs研究判斷**：協助區分「介紹型主題」與「研究問題」，避免寫成工具書
- ⚖️ **管轄權提醒**：確認建議對象在台灣有管轄權，避免寫了外國政府看不到的論文
- 📊 **法令狀態盤點**：從草案爭議、修法效果、制度缺口等角度找切入點
- 🌐 **差異化策略**：透過外文文獻分類，找出外國熱門討論但國內尚未有人寫的議題
- 📋 **文獻分類指令**：提供可直接複製使用的AI文獻分類指令
- 🔗 **關聯性分析指令**：提供五級關聯性評分指令，快速篩選核心文獻
- 🚀 **可跳步**：學生可隨時說「從Step X開始」，不必從頭走完

---

## 📁 專案內容

| 檔案 | 說明 | 適用平台 |
|------|------|----------|
| `skill/SKILL_legal_thesis_topic.md` | Claude 專案 SKILL 版 | Claude.ai Skills功能，也可以用在專案中 |
| `prompt/legal_thesis_topic_prompt.md` | 通用 Prompt 版 | ChatGPT、Gemini、Claude 等所有 AI 對話介面 |
| `web/thesis-finder.html` | 網頁互動版 | 瀏覽器（需 Gemini API Key） |
| `README.md` | 本說明文件 | — |

---

## 🗂️ 流程概覽

| 步驟 | 內容 | 說明 |
|------|------|------|
| Step 1 | 找起點 | 工作經驗、課堂學習、時事爭議、修法爭議、資料庫新議題 |
| Step 2 | 說出初步方向 | 用一句話描述主題，AI 提供範例參考 |
| Step 3 | 是介紹還是研究？ | 判斷可寫性：有無研究問題、建議對象是否存在 |
| Step 4 | 盤點法令狀態 | 草案中／剛修正／修正一段時間／長期未修正／尚未立法 |
| Step 5 | 國內研究現況分析 | 找出還沒人寫的角度，避免淹沒在主流研究中 |
| Step 6 | 找關鍵字 | 為外文資料庫搜尋做準備 |
| Step 7 | 外文文獻分類與關聯性分析 | 提供兩個可複製的 AI 指令，學生自行執行 |
| Step 8 | 確認差異化題目 | 興趣 × 專業價值 × 趨勢性，三者符合即確認 |

---

## 🚀 使用方法

### 方法一：SKILL 版（推薦 Claude.ai 用戶使用）

適合已建立 Claude.ai 專案的使用者，設定一次後自動觸發。

**步驟：**
1. 進入 [Claude.ai](https://claude.ai)，開啟或建立一個「專案（Project）」
2. 在專案設定中找到「Project Knowledge」
3. 將 `skill/SKILL_legal_thesis_topic.md` 的內容上傳或貼入
4. 之後在該專案內的對話，只要出現「論文題目」、「研究方向」等關鍵字，即自動啟動

> ⚠️ 此版本**僅限 Claude.ai**，其他 AI 平台不支援 SKILL 格式。

---

### 方法二：Prompt 版（跨平台通用）

適合使用任何 AI 對話工具的使用者，包含 ChatGPT、Gemini、Copilot 等。

**步驟：**
1. 開啟 `prompt/legal_thesis_topic_prompt.md`，複製全部內容
2. 貼入任何 AI 對話框，送出
3. AI 確認載入後，即開始逐步引導

> ⚠️ 每次**新對話**都需要重新貼入，對話結束後不會保留設定。

---

### 方法三：網頁版（介面最友善）

適合不熟悉 AI 操作的學生，具備視覺化進度條。

🌐 **[直接開啟網頁版](https://mjib007.github.io/legal-thesis-topic/thesis-finder.html)**

**步驟：**
1. 點擊上方連結，或下載 `web/thesis-finder.html` 用瀏覽器開啟
2. 第一次使用需輸入 [Gemini API Key](https://aistudio.google.com/app/apikey)（免費申請）
3. 金鑰儲存在瀏覽器本機，不會上傳至任何伺服器
4. 後續開啟免重新輸入

---

## 🧪 使用示範

**學生輸入：** 「我在一家台商公司工作，我們在越南有設廠，想寫有關台商越南勞動法令的論文」

**工具回應（Step 3 判斷）：**
> 這個方向比較像是提供給台商的參考資料，缺乏學術爭議。此外，即使對越南法令提出批評，越南政府不會看到，台灣也沒有管轄權，建議對象不存在。
>
> 建議重新找切入點，例如：台灣勞動法令有沒有需要修正的地方？或是這個工作經驗讓你覺得哪個台灣法律制度「不對」或「不夠」？

---

## 🔗 與 legal-thesis-outline 的關係

```
legal-thesis-topic              →        legal-thesis-outline
（找到論文題目與研究方向）                  （審查與重構論文大綱）
```

建議先用本工具確認題目方向，再開始撰寫大綱，最後用 [legal-thesis-outline](https://github.com/mjib007/legal-thesis-outline) 審查大綱結構。

---

## 📜 授權

本專案以 [MIT License](LICENSE) 開源，歡迎自由使用、修改與分享。
若有改善建議，歡迎提交 Issue 或 Pull Request。

---

## 🔗 相關專案

- [📐 法學論文大綱審查工具](https://github.com/mjib007/legal-thesis-outline)
- [🎓 刑法申論題 AI 教練](https://github.com/mjib007/legal-essay-tutor)
