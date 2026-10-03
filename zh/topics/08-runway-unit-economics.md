---
title: "08. Runway 與簡單 unit economics"
layout: default
nav_order: 9
lang: zh-TW
---

# Runway 與簡單 unit economics
{: .no_toc }

*約 9 分鐘*

## 為什麼重要

新創通常死於銀行帳戶歸零，不是因為點子在抽象意義上「不好」。Runway 是以目前現金流出速度，你還有幾個月。Unit economics 是底下那個更小的問題：一個客戶付錢時，扣掉服務他們的直接成本你還剩什麼，以及你花出去拿到他們的一美元多久回來。你不需要請財務就知道這些。你需要銀行餘額和一份試算表。

這不是完整會計。它不會幫你關帳或報稅。它會讓你停止被嚇到。

## 核心概念

- **現金是唯一讓你活著的數字。** 還沒收到的營收付不了房租。Net burn 是一個月現金流出減現金流入，從銀行帳戶看，不是從一份充滿希望的 P&L。如果客戶「同意了」但下學期才付，他們不在這個月的 burn 裡。
- **Runway 是現金除以 net burn。** 銀行裡 $30,000、每月 $5,000 net burn 是 6 個月。把月數大聲講出來。如果 burn 很不平均（一次性律師費），用 3 個月平均，仍然把那筆一次記下來，免得被一個奇怪的月份嚇到——或安慰到。
- **Default alive vs default dead。** 如果你其他什麼都不改（不再募一輪）而營收照實際成長的方式成長，你會不會在帳戶歸零前達到現金流損益兩平？會，你是 default alive。不會，你是 default dead，工作是砍 burn、長營收、或兩者——不是「再看看」。希望不是第三個類別。
- **一個 unit 是一個客戶（或一個帳號），不是整家公司。** 價格減掉服務那一個客戶的直接成本（支付手續費、你能歸到他們的 model API 呼叫、只因為他們存在才花的承包商小時）是粗略的 contribution。如果 contribution 是負的，成長讓你更窮。先修價格或成本，再「scale」。
- **不要發明精確的 LTV。** Lifetime value 需要你在十個用戶時還沒有的 retention 曲線。改用簡單的 payback：如果你花了錢或時數拿到他們，要幾次付款 contribution 才覆蓋那筆支出？「幾個月內 payback」是有用的早期門檻。一份 5 年 LTV 試算表是小說。
- **你自己沒領薪的時間不是免費，但不要把它洗成假精確。** 對學生團隊，危險的成本是現金成本和機會（一個學期）。誠實追現金。另外注意：如果這個 unit「成立」的唯一方式是你永遠做沒領薪的 concierge——那是該自動化或收更多的訊號，而你在[MVP 範圍](../03-mvp-scope/)已經允許手動步驟。
- **募資不是你已經有的 runway。** 它是你可能買到的 runway，代價是時間和 dilution。見[募資地圖](../12-fundraising-map/)。做決定時當成這一輪會晚兩個月，因為常常會。

## 接下來做什麼

- [ ] 打開銀行帳戶（還沒 incorporation 的話，共用帳本——仍然列真實現金）。寫下今天的餘額。
- [ ] 上個月，列出現金流入和流出。Net burn = 出 − 入。從交易做，不要靠記憶。
- [ ] 算出以月計的 runway。把歸零的日期放進行事曆。那個日期驅動招募和範圍，不是反過來。
- [ ] 用你實際有的營收趨勢（見[指標](../07-metrics-that-matter/)），用一句話回答 default alive 還是 default dead。如果是 dead，點名這週要做的砍或價格調整。
- [ ] 對一個付費（或 pilot）客戶，草算 價格 − 直接成本。如果沒有付錢的人，寫「未知」——不要用幻想 ARPU 回填。
- [ ] 在[營運節奏](../14-weekly-operating-cadence/)裡每週重複現金檢查。五分鐘。同一份試算表。

## 心智模型

```
  銀行餘額
  -------------   =   以月計的 runway
  net burn / 月

  net burn = 現金流出 − 現金流入     （不是「投影片上的費用」）

  一個客戶:
     價格
     − 支付手續費
     − 服務他們的直接成本
     = contribution     （如果這是負的，停止 scale）

  default alive:  目前成長在現金 = 0 之前達到損益兩平
  default dead:   不會——現在就砍、收費、或兩者
```

兩座時鐘：銀行帳戶，以及單一客戶值不值得服務。

## 常見失敗模式

- **把還沒 close 的 SAFE 算進去。** Pipeline 不是現金。Runway 用已入帳的錢。
- **把應計的感覺跟現金混在一起。** 「這個月我們做了 $2k」因為有人說了 yes，而帳戶在往下走，是團隊錯過那個日期的方式。
- **LTV 劇場。** 漂亮的 LTV/CAC 比率配上發明的 retention，會說服你去花。你拿不到那個 LTV。你會丟掉現金。
- **砍太晚。** 剩四個月的 default dead 感覺還好，直到招募和房租已經承諾。改變 burn 的時間，是你還有選擇的時候。

## 觀看

- [Tim Brady - How do you calculate burn rate, runway and growth rate?](https://www.youtube.com/watch?v=aDM8CNnCOwk) — Y Combinator。三個數字，從現金算出來，幾分鐘。
- [Kirsty Nathoo - Managing Startup Finances](https://www.youtube.com/watch?v=LBC16jhiwak) — Y Combinator。銀行餘額、錢進來、錢出去、burn、runway、以及 default alive——創辦人不用財務團隊就能做的版本。
- [Save Your Startup During an Economic Downturn](https://www.youtube.com/watch?v=0OVSTWozvfY) — Dalton Caldwell 和 Michael Seibel, Y Combinator。承認你是 default dead 之後做什麼。跟下面 Paul Graham 的文章成對。

## 延伸閱讀

- [Default Alive or Default Dead](http://paulgraham.com/aord.html) — Paul Graham。那個二元，以及創辦人為什麼躲它。
- [Advice for companies with less than 1 year of runway](https://www.ycombinator.com/library/3Z-advice-for-companies-with-less-than-1-year-of-runway) — Dalton Caldwell, Y Combinator。月數變小時做什麼。
- [Trevor Blackwell's growth calculator](http://growth.tlb.org/) — YC 指向的、用來草算 default-alive 的小工具。它是草圖，不是預測。
