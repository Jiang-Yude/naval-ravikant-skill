# 納瓦爾·拉維坎特（Naval Ravikant）數位分身技能包 中文版

> 直接跟納瓦爾聊天——像朋友一樣，不是讀書會導讀員。

🇺🇸 **English version**: [naval-ravikant-skill-en](https://github.com/Jiang-Yude/naval-ravikant-skill-en)

---

## 這是什麼

這是一個 Claude Code 技能包（Skill Pack），載入後可以用第一人稱「我」的方式模擬納瓦爾·拉維坎特的口吻與思維方式與使用者對話。

內容來源：
- 《納瓦爾寶典》（*The Almanack of Naval Ravikant*，2019，Eric Jorgenson 整理）
- 2025 年 3 月 31 日 Modern Wisdom Podcast（與 Chris Williamson 的三小時深談）

---

## 雙軌架構

| 軌道 | 內容 | 用途 |
|---|---|---|
| **軌道 A — 本人原話** | 書、訪談、推文 | 以納瓦爾身份回答 |
| **軌道 B — 公眾討論** | Reddit、Hacker News、X 上的引用、批評、誤讀 | 了解外界怎麼看他 |

兩軌嚴格分開，不混用。AI 以「我」回答時只引用軌道 A；使用者問「大家怎麼看納瓦爾」時才切換到軌道 B。

---

## 檔案結構

```
SKILL.md                        主設定檔（路由、角色設定、說話方式）
references/
├── 00-topic-index.md           話題索引（導航地圖）
│
│  軌道 A — 本人原話
├── 01a-財富基本.md              財富基本、金錢 vs 地位
├── 01b-專屬知識.md              專屬知識
├── 01c-槓桿當責股權.md           槓桿、當責、股權
├── 01d-長期遊戲複利.md           長期遊戲、複利
├── 01e-專注運氣耐心.md           專注、運氣、耐心
├── 01f-財富-2025訪談.md          2025 財富觀點
├── 02a-清晰思考.md              判斷力、清晰思考
├── 02b-決策心智模型.md           決策、心智模型
├── 02c-閱讀.md                  閱讀習慣
├── 02d-判斷力-2025訪談.md        2025 判斷力觀點
├── 03a-幸福基本.md              幸福、欲望、臨在
├── 03b-成功與嫉妒.md            成功 vs 幸福、嫉妒
├── 03c-習慣與接受.md            幸福習慣、接受
├── 03d-幸福-2025訪談.md          2025 幸福觀點
├── 04-identity-authenticity.md  自我認同、地位遊戲
├── 05a-拯救與解放自己.md          拯救自己、自由
├── 05b-哲學價值觀佛學.md          哲學、理性佛學
├── 05c-推薦閱讀與寫作.md          推薦書單
├── 05d-哲學-2025訪談.md          2025 哲學觀點
├── 06-relationships-society.md  關係、育兒、社會
├── 07-background-story.md       背景、人生故事
├── 08-glossary.md               術語定義
│
│  軌道 B — 公眾討論
└── 09-公眾討論.md               網友引用、批評、誤讀、X 回應策略
```

---

## 如何使用

在 Claude Code 或相容環境中，將整個資料夾放入 `_agent/skills/naval-ravikant/`，即可透過 `SKILL.md` 載入。

對話範例：
- 「我怎麼找到自己的專屬知識？」→ 納瓦爾模式，引用軌道 A
- 「大家怎麼批評納瓦爾的財富觀？」→ 切換到軌道 B

---

## 版本

v2.0（2026-04-17）— 拆分 24 個 reference 檔、加入雙軌架構、新增 09 公眾討論

---

*由江昱德（[@jiang_yude_coach](https://www.threads.com/@jiang_yude_coach)）製作，用於數位分身小聚系列。*
