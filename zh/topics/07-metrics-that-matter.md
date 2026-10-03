---
title: "07. 真正重要的指標"
layout: default
nav_order: 8
lang: zh-TW
---

# 真正重要的指標
{: .no_toc }

*約 9 分鐘*

## 為什麼重要

早期指標不是 dashboard。它們是三個問題：新用戶有沒有碰到價值、有沒有回來、有沒有人付錢。其他所有東西（造訪、註冊、GitHub stars、waitlist 人數）都可以往上走，公司仍然沒在運作。選一小把你會在[營運節奏](../14-weekly-operating-cadence/)每週看的數字，其餘的在那些動起來之前忽略。

這些要有意義，你需要用戶。如果試過產品的人不到五個，先回[通路](../05-distribution-gtm/)，再去做 analytics。

## 核心概念

- **Activation：他們碰到 aha，不是註冊。** 把 activation 定義成 wedge 那件工作第一次做完的那一刻。對對帳工具來說，那是「產出一份真的帳本」，不是「他們開了帳號」。把那個 event 寫下來。叫不出名字，你就不知道產品是幹嘛的。
- **Retention：他們沒被你催也回來。** 用 cohort 畫（同一週開始的人），不要用把新人和所有人混在一起的「active users」線。平坦或上升的 cohort 曲線代表產品正在嵌進那件工作。掉下懸崖的曲線代表替代做法贏了。
- **營收：有人付了，以及會不會重複。** 收到的現金勝過你希望開發票的 bookings。如果是經常性模式，追誰續約、或第四週誰還在付。一次性 pilot 費用仍然有用——標成 pilot，不要假裝它是 run-rate。定價住在[定價與 packaging](../06-pricing-packaging/)。
- **一個主指標。** 這個階段通常是營收，或你有明確理由刻意還沒收費時、會通向營收的緊代理（每週 activated 的團隊數）。次指標（activation rate、第 4 週 retention）解釋主指標。虛榮指標什麼都不解釋。
- **比率需要你信任的分母。** 五個用戶的「20% retention」是故事，不是定律。仍然算——並把分子寫在旁邊（「5 個裡有 1 個回來」）。假精確比分數更糟。
- **質化跟數字坐在一起。** Retention 掉的時候，指標不說為什麼。通話才說。每個難看的數字都該排一場對話，不是關起門來改版。
- **B2B 和消費端數法不同，問題相同。** 消費：他們有沒有做完核心動作、隔天或下週有沒有回來、會不會付或轉介。B2B：帳號在 pilot 有沒有碰到價值、使用有沒有擴大、有沒有付。不要把社群 app 的 dashboard 搬進財務長一個月開兩次的工具。把時間窗對準那件工作。

## 接下來做什麼

- [ ] 用一行寫 activation event：「用戶 ____ 時算 activated。」只 instrument 那一個 event。其餘分類學先跳過。
- [ ] 做一份 cohort 草稿（試算表就好）：每一列是一個用戶或帳號，欄是第 0 週、第 1 週、第 4 週——他們有沒有再做那件工作，以及有沒有付。
- [ ] 為接下來四週選主指標。告訴 cofounder。放在每週回顧最上面。
- [ ] 定義一份你不會慶祝的虛榮清單：原始註冊、page views、追蹤者。可以瞥一眼。它們不能當目標。
- [ ] 某個 cohort 看起來糟時，先約兩個離開或卡住的人通話，再改產品。把他們的話帶到回顧。
- [ ] 錢是真的之後，把同一組數字交給[Runway](../08-runway-unit-economics/)，讓成長和現金是同一場對話。

## 心智模型

```
  新用戶
     |
     v
  activation ---- no ---> 第一次 session 失敗
     |                     （看一次，修那條路）
    yes
     |
     v
  在工作的自然週期回來 ---- no ---> 替代做法贏了
     |
    yes
     |
     v
  付了（或有日期的付費承諾）
     |
     v
  那就是公司，縮小版

  每週看:  cohort 表 + 收到的現金
  不是:    一整牆圖表
```

如果只做得了一個產物，做帶「付了嗎？」欄的 cohort 試算表。

## 常見失敗模式

- **慶祝註冊。** 註冊量測的是你的 launch 推文，不是產品。Activation 量測產品。
- **混合的 retention 數字。** 新用戶把上個月用戶離開這件事藏起來。Cohort 才是重點。
- **Dashboard 劇場。** 40 個用戶之前就有 40 張圖的工具是拖延。試算表就夠。
- **優化一個不是那件工作的代理。** Time-on-site、送出的訊息、或「AI queries」可以上升，財務長仍然在 Excel 對帳。把指標綁到他們要的結果。

## 觀看

- [B2B Startup Metrics \| Startup School](https://www.youtube.com/watch?v=_mKeVGSqQac) — Y Combinator。買家是帳號時哪些數字重要，以及怎麼不被淹死。
- [Consumer Startup Metrics \| Startup School](https://www.youtube.com/watch?v=fdD4y4Civp4) — Y Combinator。消費端對應：activation 與 retention，不假裝你已經是成長團隊。
- [How To Keep Your Users \| Startup School](https://www.youtube.com/watch?v=VNxBZ7ka5J0) — Y Combinator。Retention 是你採取行動的東西——cohort、為什麼人離開、改什麼——不是一張拿來欣賞的圖。

## 延伸閱讀

- [Startup Growth](http://www.paulgraham.com/growth.html) — Paul Graham。在你有真正的分子之後，推你去在乎那個速率。
