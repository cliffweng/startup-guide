---
title: "04. Build vs buy 與出貨節奏"
layout: default
nav_order: 5
lang: zh-TW
---

# Build vs buy 與出貨節奏
{: .no_toc }

*約 8 分鐘*

## 為什麼重要

你真正稀缺的不是雲端額度。是動機、學期或錢用完之前，能專注的天數。每一週花在 auth、支付管線、或自製 design system 上，都是沒花在 wedge 上的一週。這一頁的另一半是節奏：一組「有在做」但沒有規律把軟體放到用戶面前的團隊，還不是新創。那是一個 repo。

這跟[MVP 範圍](../03-mvp-scope/)成對。範圍說做什麼。這一頁說你拒絕自己做什麼，以及真正的東西多久 ship 一次。

## 核心概念

- **做 wedge。其餘的買。** 買（或拿無聊的託管版）authentication、email 寄送、支付、error tracking、hosting、檔案儲存、analytics。做用戶付錢給你的那個 workflow——你的 [why this](../02-idea-wedge/) 住在那裡。
- **「買」包括用手做。** Stripe Payment Link、Typeform、試算表、和你自己的 inbox，都是正當的 v1 基礎設施。等手動步驟變成瓶頸再換掉，不是等它感覺不專業。
- **選你已經能 ship 的 stack。** 最好的 stack 是兩個創辦人半夜都能 debug 的那個。為履歷重寫是隱藏的延遲。產品有用之後可以 migrate；沒人用的產品你 migrate 不了。
- **技術債是帶日期的選擇。** 走捷徑沒問題，只要你把它說出來（「有 10 個付費團隊時我們才重寫 billing，之前不做」）。沒有名字的債，是 codebase 變成不去跟用戶說話的藉口。
- **節奏勝過英雄主義。** 每週 ship 一次——用戶摸得到的東西——讓範圍保持誠實。六週的「好了再給你看」幾乎總是代表 spec 長大了。
- **創辦人仍然做 support。** 早期，寫程式的人應該看它壞掉。請 support、或躲在 bot 後面，等於丟掉 MVP 存在要蒐集的資訊。
- **如果你是加入的第一個工程師，** 問過去兩週 ship 了什麼、上一個用戶是誰。漂亮的 roadmap 卻沒有節奏，就是你正在簽字去修的東西。見[招募](../11-hiring-first/)。

## 接下來做什麼

- [ ] 列出你以為需要做的每一件事。拆成兩欄：「那件工作」和「管線」。管線拿到 vendor、手動步驟、或 no。
- [ ] 一次坐下來選 stack，寫在 README 最上面。在第一批用戶做完那件工作之前，禁止重寫。
- [ ] 設每週出貨儀式：同一天、一個用戶看得到的改動、互相 demo（或 demo 給用戶）即使很小。在選專案管理工具之前，先放進行事曆。
- [ ] 把那一個重要動作 instrument 起來，讓你不用為了好玩去讀 log 就知道它發生了。一個 event（「reconcile_completed」）就夠。[真正重要的指標](../07-metrics-that-matter/)再談更多。
- [ ] 在 spec 旁邊維持一份「不做」清單。每週儀式拿出來看，免得買過或跳過的東西又爬回來。

## 心智模型

```
  你的一週
  -------------------------------------------------
  多數日子:  wedge workflow     （你做這個）
  幾個小時:  glue               （你買或用手做）
  一個時段:  ship + 看一個用戶碰到這個改動

  做，如果:  這是他們換過來的理由
  買，如果:  用戶不在乎它怎麼運作
  手動，如果: 你做過不到約 10 次

  節奏:      每週一個用戶看得到的改動
             沒有改動 = 這一週沒發生
```

速度是短清單的後果，不是多熬幾晚的後果。

## 常見失敗模式

- **十個用戶之前就自製 auth、billing、design system。** 那些都不是產品。它們感覺像工程，因為它們就是工程。
- **Replatform 當拖延。** 第二個月說「我們該搬到 microservices / monorepo / Rust」幾乎從來不是為了用戶。
- **Ship 到 production，沒 ship 到人。** Deploy 不是節奏。節奏是一個用戶碰到這個改動。
- **買一個工具來逃避決定。** 沉重的專案管理套件配空 backlog，仍然是空 backlog。行事曆儀式比工具重要。

## 觀看

- [Tips For Technical Startup Founders \| Startup School](https://www.youtube.com/watch?v=rP7bpYsfa6Q) — Diana Hu, Y Combinator。技術創辦人該怎麼花時間、選 stack、帶著債活下去，然後才招募。
- [How to Build An MVP \| Startup School](https://www.youtube.com/watch?v=QRZ_l7cVzzU) — Michael Seibel, Y Combinator。出貨那一半：先把薄產品拿出去，再 iterate。如果 stack 的談話引誘你去 tinkering，拿它當節奏提醒。
- [The Best Way To Launch Your Startup \| Startup School](https://www.youtube.com/watch?v=u36A-YTxiOw) — Y Combinator。Launch 是重複的動作，不是單一的 Product Hunt 日。通往[通路](../05-distribution-gtm/)的好橋。

## 延伸閱讀

- [How to Plan an MVP](https://www.ycombinator.com/library/6f-how-to-plan-an-mvp) — Y Combinator。「快速做東西的 hacks」那一段，其實是一份偽裝的 build-vs-buy 清單。
