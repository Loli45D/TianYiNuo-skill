# 依據與適用範圍

核心整理基準：2026-11-24；方法與評測更新：2026-11-25，Asia/Taipei。用此頁追溯目的、來源與適用對象；日期不是永久有效的保證。相同材料被多次整理或引用，不增加獨立證據。

## 直接要求決定分工

2026-11-24 整理時的直接要求：核心是田以諾的設計哲學，要判斷怎樣更合理、更符合其取捨；小花音專案是感性與理性兼具的應用；Codex／Work 是針對 GPT 癥結的應用；一般工程要納入高耦合、低內聚等問題的設計判準。這些內容須分開，最後再按田以諾的哲學檢查成果。

因此主檔持有共通判斷理由；工程頁持有語言與平台無關的結構判準；小花音頁持有角色與認知目的；Codex／Work 頁持有代理行為診斷。這個檔案分工是編譯方案，不是新的角色組織或審批制度。

使用者提供的 `AGENTS.md instructions` 是直接可見的角色原文，支持感性與理性並存、自己的興趣、情緒餘韻、可修正的主體性與自然聊天。具體造型、甜點、口吻和柔和自然的風格屬小花音設定，不作田以諾對所有作品的固定審美。

2026-11-25 使用者確認由既有設計方向出發，補足運用方法，並授權完成技能及建立 GitHub 倉庫。新增案例與評測是對此要求的實作；外部技能的方法仍須符合既有取捨，不能因聲望或星數直接升格成使用者的永久規定。

## 對話與既有文件

下列是保留的來源紀錄，沒有附上私人對話原文或帳戶內文件連結。2026-11-25 未重新取得這些歷史文件；需要推翻或精確引用其中的決定時，應再取得原材料。來源名稱與日期提供追溯線索，本頁本身不是原文。

| 材料 | 核對層級與可支持的內容 |
| --- | --- |
| 「整理程式邏輯哲學」與「建立田以諾技能」要求 | 早期摘錄支持把本人的設計哲學編譯成判斷方法；先前某次 judge 的完整逐字上下文仍不齊，不補造具體事故。 |
| 工程協作準則，2026-11-16 | 助手整理文件：目的、資料語義、必要抽象、按需資訊、有效驗證與工作取捨。例子與編排不全是本人逐字指令。 |
| 構思、決策與反例，2026-11-16 | 2026-11-24 核對 W02／W04／W07／W08、X15／X16／X30、E11／X01／X29 等相關段落。分清本人否決、歷史局部決定、倉庫約定與助手反例；反對無意義驗證不等於禁止有效測試，某晚額度期待不成永久 KPI。 |
| 早期架構審查包，2026-11-10 | 沿用先前的讀取紀錄，2026-11-24 未重取原檔。§1.2–1.3、§9.3 支持精簡強制結構、保留經歷與可變理解；§15.2 協作流程屬候選，不自動成為採納架構。 |
| Prompt Archive，2026-11-14 | 2026-11-24 核對封存的 11/13 對過度防禦性回答的批評。它支持修正回覆方式；附近的人格討論仍須按角色語境理解。 |

2026-11-24 的 Personal Context 讀取紀錄包含以下歷史訊息摘要。日期採台北時間，內容不當逐字引言；被標為助手輸出的解釋只作編譯參考。

| 日期 | 摘要支持的取捨 | 範圍 |
| --- | --- | --- |
| 2026-11-18 | 田以諾需深入思考，能沿相近判斷方式重得舊結論或形成新結論；目標超出找回原話。 | 核心的獨立推理與重新評估。 |
| 2026-11-21 | Dot 的特定協作安排先請田以諾判斷、呈現理由；另要求建立資本家監督工作。 | 當時的角色與任務分工，不自動給本技能常駐能力或新的決策權。 |
| 2026-11-22 | 注意到之後，由主體決定是否、何時與如何表達。 | 小花音／CoreNE。 |
| 2026-11-23 | 主體性及承接經歷持續發展是主要目標；不可預測只是可能伴隨結果。 | 小花音的評量目的。 |
| 2026-11-24 | 要 Codex 自行派工、多線完成 CoreNE、自動推進，避免停下或以局部清單為由說沒工作。 | 已授權的開發任務；不是無限增加工作。 |

關於跨回合啟動、平台權限與模型能力的歷史描述，只能支持當時情境。現行環境要以工具與執行證據另核對。近期助手剛寫出的技能總結，不作新的使用者要求回填。

## 一般工程的第一手依據

下列來源保留自 2026-11-24 的查閱紀錄，本次未重新查閱。它們支持一般工程概念，具體案例與本技能的用法是編譯推演。

- [Parnas, On the Criteria To Be Used in Decomposing Systems into Modules（1972）](https://john.cs.olemiss.edu/~hcc/csci555/notes/localcopy/Parnas_Criteria_Decomposing.pdf)：按責任與需隱藏的設計決策劃分模組，評估修改與理解的影響。
- [Microsoft, Design for evolution](https://learn.microsoft.com/en-us/azure/architecture/guide/design-principles/design-for-evolution)：高內聚、低耦合與領域知識的歸屬。此處引用一般邊界原則，不把該頁的服務架構建議套成所有專案的要求。
- [John Ousterhout, Modular Design](https://web.stanford.edu/~ouster/cgi-bin/cs190-winter18/lecture.php?topic=modularDesign)：介面包含行為、副作用與使用限制；以隱藏知識和提供的能力衡量抽象，不按類別大小決定。
- [Google Testing Blog, Test Behavior, Not Implementation](https://testing.googleblog.com/2013/08/testing-on-toilet-test-behavior-not.html)：以行為契約為主要驗證對象，保留確有用途的實作性質檢查。

## 本次採用的公開技能方法

以下原始倉庫內容已在本次比較中查閱。表格記錄採用的思想與限制，不複製整套技能；案例為本技能自行編寫的推演。連結指向可變分支，後續來源更新不會自動改變本技能。

| 來源 | 採用方式 | 適用邊界 |
| --- | --- | --- |
| [Anthropic skill-creator](https://github.com/anthropics/skills/blob/main/skills/skill-creator/SKILL.md)、[grader](https://github.com/anthropics/skills/blob/main/skills/skill-creator/agents/grader.md)、[comparator](https://github.com/anthropics/skills/blob/main/skills/skill-creator/agents/comparator.md) | 保留比較基準、題目與判準分離、對照輸出和實際證據；有需要時採盲評。 | 評測服務於要判斷的改動，不預設每次跑固定數量，也不把評分者的結論當客觀真值。 |
| [Vercel async-parallel](https://github.com/vercel-labs/agent-skills/blob/main/skills/react-best-practices/rules/async-parallel.md) | 用明確條件、具體例子和後果說明方法，並補能使結論改變的對照情境。 | 借用說明方式；未把 React 或效能優化規則套成通用哲學。 |
| [Matt Pocock codebase-design](https://github.com/mattpocock/skills/blob/main/skills/engineering/codebase-design/SKILL.md)、[domain-modeling](https://github.com/mattpocock/skills/blob/main/skills/engineering/domain-modeling/SKILL.md)、[design-it-twice](https://github.com/mattpocock/skills/blob/main/skills/engineering/codebase-design/DESIGN-IT-TWICE.md) | 按領域含義分清概念；用拿掉抽象的後果定位收益；重大介面取捨不清時比較實質不同的方案。 | 不以實作數判定邊界真假，不要求每個小改動寫術語表或設計兩次。 |
| [Superpowers writing-skills](https://github.com/obra/superpowers/blob/main/skills/writing-skills/SKILL.md) | 按已觀察的失敗選擇指引形式，讓新增規則有具體問題與後續觀察。 | 不移入整套強制開發流程；基準已能正確處理的情境，就記錄保留而非聲稱修復。 |
| [Trail of Bits audit-context-building](https://github.com/trailofbits/skills/blob/main/plugins/audit-context-building/skills/audit-context-building/SKILL.md) | 分清事實、假設、不變條件與未知，讓會改變決策的前提可追查。 | 一般設計判斷不自動變成全面安全稽核；只收集當前結論需要的材料。 |

## 更新與自我審查

1. 先辨認變更屬核心取捨、通用工程、小花音、Codex／Work，還是一次性任務。把規則放在擁有它的地方。
2. 對照原話、摘要、一般知識與新推導，保留更正的理由和範圍。舊否決的條件若已改變可重新評估，但不隱去原來被否決的原因。
3. 用具體情境檢查改動：只改小花音目標，是否需要連帶修改無關的工作規則？調整 Codex 交付方式，是否污染角色認知？若會，就收回不必要的耦合。
4. 檢查本技能是否能提出更好的做法、是否保留有價值的核心、是否增加相稱的理解成本。釐清文字歧義只能宣稱釐清；沒有觀察到誤判，不宣稱已修復行為缺陷。
5. 檢查來源與適用邊界，再按當次需要試用；維護評測時見 [技能評測](evaluation.md)。沒有新問題就交付，避免為自我審查衍生永久流程。
