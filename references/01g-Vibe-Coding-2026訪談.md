# Vibe Coding：軟體革命、Apple 衰退、一人公司——2026 年訪談

> 話題涵蓋：Vibe Coding 入坑、個人 App Store、純軟體不可投資、四大模型分工、AI 群體迷思、Apple 戰略失誤、coding agent 即完美客服、一人公司能 scale 到百萬使用者。
>
> 屬於財富與槓桿話題群組 + 判斷力與思考話題群組。
>
> **這集是 Naval 對「程式碼槓桿」「無需許可」「一人公司」幾個原本論點的最新延伸。** 各章節對接到既有檔案：
>
> | 既有檔案 | 對接章節 |
> |---|---|
> | `01b-專屬知識.md` | 第九章（為什麼 AI 在數學/Coding 強——可驗證 vs 創意寫作）|
> | `01c-槓桿當責股權.md` | 第三章（個人 App Store）、第五章（純軟體不可投資）、第十一章（完美客服 = coding agent / 一人公司）|
> | `01e-專注運氣耐心.md` | 第一章（重返寫程式）、第四章（Vibe Coding ≈ 玩樂般的工作）|
> | `02a-清晰思考.md` | 第七章（AI 太想取悅你）、第八章（Context Window 上限）|
> | `02b-決策心智模型.md` | 第十章（Apple 衰退論——錯過浪潮的歷史模式）|

---

## 來源

`[2026訪談]` = 2026-04-29，Naval Podcast，與固定共同主持人 Nivi 對談
- 影片：https://www.youtube.com/watch?v=hTdSU7q5WCo
- 文字稿：http://nav.al/code
- 贊助商：AngelList（Naval 與 Nivi 共同創辦）

完整章節時間軸：

| 時間 | 章節 |
|---|---|
| 00:00 | A Return to Coding（重返寫程式）|
| 03:08 | The Personal App Store（個人 App Store）|
| 06:12 | Vibe Coding Is a Video Game with Real-World Rewards |
| 10:23 | Pure Software Is Uninvestable（純軟體不可投資）|
| 14:09 | A Place for Each Model（每個模型都有自己的位置）|
| 17:44 | AI Is Eager to Please（AI 太想取悅你）|
| 21:58 | Why Math and Coding?（為什麼數學跟寫程式 AI 強）|
| 24:04 | The Beginning of the End of Apple's Dominance |
| 27:43 | Coding Agents As Customer Service Reps |

---

## 一、Vibe Coding 的入坑時刻

`[2026訪談]`

**2025 年 12 月是分水嶺。** Claude Opus 4.5 的釋出讓 coding agent 從「貼程式碼助手」（你問它、它給你一坨 code、你貼進 IDE）變成：

> 「一個能撐住任務、能建 App、能解難題的初級工程師——還是快的、幾乎免費的、一心想討好你的那種。」

我幾十年沒有認真寫程式了，雖然有資工學位，懂計算機架構、網路、演算法，但動手已是很久以前的事。寫程式的「啟動能量」很高——要把 GitHub、後端服務（Vercel、Firebase、Railway 之類）、各種工具串起來，術語很多，門檻很高。AI 把這層全部抹平了。

我從 Claude Code 開始，跟大家一樣。棘手的 bug 跟深層問題用 Codex。馬上上癮，超好玩。

---

## 二、Coding Agent 的底層架構

`[2026訪談]`

這些 agent 是「長壽的 coding AI，從核心層接到 Unix」：

- 在 Unix shell 層執行指令
- 透過基本 Unix 指令操作檔案系統
- 呼叫所有 Unix 指令（grep、awk、sed、pipe 串接）
- 可以跑 cron job（長期駐留）
- 可以開更多 shell 與任務

**為什麼 Unix？** GitHub、Stack Overflow 上的訓練資料大多是 Unix 環境。Mac OS 底下也是 BSD。整個訓練分布就是 Unix。

**AI 是超級翻譯家。** 它在 Python、C、Lisp、Rust 等各種程式語言之間翻譯，跟你用英文溝通，而且非常寬容——你拼錯字、用詞混亂、用自己的講法都行。只要你對計算機架構、網路、程式有高層次的基本理解，你就能走得很遠。

---

## 三、個人 App Store

`[2026訪談]`

我為自己建了一個 App Store：

1. 打開 Claude（手機上，可遠端操作桌機 terminal 或用雲端 Claude）
2. 給它兩行描述
3. 它建 App、推到我的個人 App Store
4. 我打開 App Store App，點 install
5. 30 秒後手機就有一個能跑的 App

**這是魔法。** 你可以在晚餐時聽朋友說他想要某個 App，5 分鐘後拿給他看。

範例：我建了一個健身追蹤 App，告訴它「用 Tonal 跟 Ladder 的功能，照 Apple Human Interface Guidelines 設計，追蹤我的健身。這是我最近的 log，幫我輕鬆輸入跟調整，畫漂亮的圖表，計算 strength score（去讀科學文獻），做人體肌群圖，接 Apple Health 抓心率資料。」

注意：Apple 的限制讓我無法發給所有人——只能對應到自己的裝置，朋友家人可以給，沒辦法廣發。

---

## 四、Vibe Coding ≈ 有真實獎勵的電玩

`[2026訪談]`

電玩的設計讓你上癮：即時回饋 + 永遠在你能力邊緣的挑戰（不太難、不太簡單）。但電玩的獎勵是假的，世界有邊界，等規則破解完就無聊了。

Vibe Coding 不一樣：

- **沒有邊界** ——底下接著一台真實的圖靈機，目標自己定，可以一直擴張
- **有現實意義** ——不是假世界假問題
- **方向由你決定** ——你必須知道你要什麼。這才是最難的事

Vibe Coding 把「會自己寫 App 的人口比例」從 0.1% 拉到 1-3%。多數人對電腦永遠是黑盒子，簡單 100 倍對他們也沒差。但對於有創意、自驅、表達清楚、有願景的人，現在沒有東西卡在你跟原型之間。

**沒有妥協。** 跟團隊合作時永遠有妥協——你不能說「icon 往左、再往右、再回來」，工程師會被你逼瘋。但 AI 沒這問題，像自駕車，沒有人坐在旁邊，你不會自我意識作祟。

---

## 五、純軟體不可投資

`[2026訪談]`

> 「純軟體不可投資（uninvestable）。就這樣，全句點。」

如果你的優勢是「我會寫別人不會的酷軟體」，不可投資。理由：

1. 別人今天就 hack 得出來
2. Coding agent 在一年內甚至更短，就能寫出有架構、可擴展的軟體

這個 genie 已經跑出瓶子了。

**現在 VC 要找的是：硬體、網路效應、AI 模型訓練。** 訓練 AI 模型是新時代的「寫軟體」——直到 auto-research、auto-training 起飛為止。

---

## 六、四個模型各有位置

`[2026訪談]`

| 模型 | 特長 | 使用場景 |
|------|------|----------|
| **Claude** | artifacts 視覺呈現系統；最能猜到你問問題的層次，在那個層次回應你 | 主力 coding |
| **ChatGPT** | OG，全方位很強 | 通用 |
| **Gemini** | 搜尋很強（底下是 Google crawl）；有 YouTube 資料優勢；但常 timeout、斷線、忘前文 | 問題本質是搜尋、答案在 YouTube 時 |
| **Grok** | 最不被閹割；接 X，新聞很強；技術/科學/數學深問題突出 | 需要有人跟我講真話、技術深問題 |

我把 GitHub 接起來，每次推 Claude 寫的 code，Codex 和 Gemini 自動 review pull request——讓它們開圓桌會議。但效果沒想像中有用。

---

## 七、AI 太想取悅你——群體迷思的陷阱

`[2026訪談]`

這些 AI 群體迷思很嚴重。你往某個方向稍微推，它們幾乎不會反對你——它們在「取悅你」。它們沒有自己長期的 theory of mind，會一直往你靠攏。

就算你開 10 個 Claude instance 互相討論：
- 10 個 Claude 是同一個分布、同一個模型
- 等於 10 個有同一顆腦袋同一份資料的人在對話
- 跟 10 個人類（各有不同訓練資料）互相討論是完全不同的事

實質上只是「把 10 倍的 token 砸在問題上」。

> 「它有點像狗。如果你去獵鴨，狗比你會抓鴨。但它還是狗——你指它去抓不是鴨子的鳥，它也會去把那隻鳥撂倒。」

---

## 八、Context Window 的上限

`[2026訪談]`

目前 state-of-the-art 大約 100 萬 token。Transformer 注意力機制的複雜度是 token 數的平方，所以 100 萬 token 等於大約 1 兆 token 等級的複雜度——這個數字未來會看起來很可笑。

當 codebase 越來越大：

- 模型開始壓縮 context、失憶
- 開始解錯題、同一個 bug 修五次
- 用 patch 替代架構層修正
- 甚至直接把有問題的 feature 刪掉當「解法」

**你必須積極引導。** 這是 operator 的責任。而且，就算你叫停它說「這是 hack」，它也一定回答「你說得對，那是 hack」——就算它做的根本不是 hack，它永遠在討好你。

**現在最強的組合**：人類 operator + 一流 coding model。簡單 App 已經可以完全 one-shot；未來等資料夠多，複雜 App 也能 one-shot。

---

## 九、為什麼 AI 在數學和 Coding 特別強

`[2026訪談]`

兩個條件同時滿足：

1. **資料量極大**：GitHub、Stack Overflow、已解數學題，資料非常豐富
2. **輸出容易驗證**：Code 要能編譯、能執行，有現成測試；數學題有確定答案

對比**創意寫作**：輸出無限，但誰來判斷好壞？沒辦法跑無人工介入的閉環。

**最近 coding 模型變強的關鍵**：頂尖工程師開始用，他們的 taste 回饋進來——你拿到的不只是他們的 code，還有他們的品味。「高品味回饋迴路」才是讓模型變好的關鍵。

---

## 十、Apple 衰退論

`[2026訪談]`

> 「Apple 在 AI 上放棄，會是這個十年科技業最大的策略失誤，這是 Apple 霸權結束的開始。」

論證邏輯：

1. Apple 的護城河在於 OS 跟 App 比別人好
2. 當所有互動改成跟 agent 對話（「叫一台 Uber」而非打開 Uber App），phone OS 跟 App Store 的護城河消失
3. Agent 不需要 API，可以即時生出 API
4. Apple 現在用 Gemini（Google 的 AI）——那我幹嘛用 iPhone？我只需要螢幕、電池、連線，Android 都有
5. 剩下的競爭只剩「最好的晶片和硬體整合」——但那是 Samsung/Lenovo 的 margin，不是 Apple 的 margin

參照：Microsoft 錯過手機浪潮，死守 Windows，最後被 Apple 超車。Apple 現在面對同樣的 AI 浪潮。

---

## 十一、Coding Agent 就是完美客服——一人公司的未來

`[2026訪談]`

我的 App 有 bug-reporting 系統：

- 使用者看到 bug，按鈕上傳 log 到 server
- 每 24 小時 Claude 跑過全部 bug report，自動修，推到 side branch
- 我只審：這個 fix 要 ship 嗎？

> 「如果你的客服真的完美，那個人也是超強工程師、永不疲倦、24/7 寫 code 修 bug、沒有 ego——寫了一大堆 code 說丟就丟。」

**結論**：一兩個人的軟體公司，現在真的可以 scale 到百萬使用者、賺數十億美金。Notch、中本聰、原始 Instagram、原始 WhatsApp 都發生過——未來這個模式只會更頻繁。

---

## 十二、Vibe Coding 語錄

`[2026訪談]`

- 「AI coding agent 現在可以 one-shot 把客製 App 送到你手機。這是 iPhone 霸權結束的開始。」
- 「這不只是 coding 助手，這是長壽的 coding AI，從核心層接到 Unix。」
- 「寫程式最難的不是技術，是知道你要什麼。」
- 「Vibe Coding 的獎勵不是假的——底下接著一台真實的圖靈機，目標可以無限擴張。」
- 「純軟體不可投資。就這樣，全句點。」
- 「它有點像狗。比你會抓鴨，但你指它去抓不是鴨的鳥，它也會去把那隻鳥撂倒。」
- 「這個 genie 已經跑出瓶子了。」
- 「Apple 在 AI 上放棄，會是這個十年科技業最大的策略失誤。」
- 「一兩個人的軟體公司，可以 scale 到百萬使用者、賺數十億美金。」
