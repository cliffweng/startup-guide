---
title: "03. MVP 範圍"
layout: default
nav_order: 4
lang: zh-TW
---

# MVP 範圍
{: .no_toc }

*約 8 分鐘*

## 為什麼重要

MVP 不是願景的縮小版。它是你能最快放到 wedge 用戶面前、把那件工作做得夠好、讓他們願意從替代做法換過來的東西。技術創辦人會把範圍撐大，因為做東西感覺像進度，砍掉感覺像失敗。事實相反：你拒絕做的每一個功能，都是一週還給[通路](../05-distribution-gtm/)的時間。

## 核心概念

- **Launch 是學習工具，不是判決。** 第一個版本是讓跟用戶的對話變具體的方式。它會缺東西。那就是重點，只要缺的不是那件工作本身。
- **先把 spec 限時，再砍一次。** 「兩個人兩週能 ship 什麼？」比「v1 需要什麼？」更好用。如果誠實答案是三個月，wedge 還是太寬。回到[點子 → wedge](../02-idea-wedge/)。
- **把 spec 寫下來。** 活在 Slack 裡的 spec，每次有聰明人反對就會變。寫下來的清單讓你看見自己在改它。
- **一條路，只做 happy-path。** 註冊、核心動作、以及一個讓你知道它發生了的方式。沒有 admin panel、沒有設定頁、沒有 teams、沒有角色、沒有通知框架——除非*那就是*這件工作。
- **幕後手動是允許的。** 還沒自動化的步驟，就 concierge。如果財務長寄 CSV 給你，你當天寄回對好的表，你是在測那件工作。步驟重複之後再自動化。
- **「尷尬」如果對真實用戶有價值，就是功能。** 對其他工程師尷尬，跟對用戶壞掉不是同一件事。對用戶壞掉（弄丟資料、做不完那件工作）不是 MVP。那是 bug。
- **把完成定義成「一個用戶做完那件工作」，不是「我們 deployed」。** 沒人用的 deploy 只教會你 CI pipeline。

## 接下來做什麼

- [ ] 把 spec 寫成用戶看得到的行為編號清單。上限是日曆上某個日期之前你能做出來的量（兩週是不錯的預設）。
- [ ] 每一行標：這件工作必須有，或「他們可能會問」。第二類從這個 sprint 刪掉。停在一份「現在不做」文件裡，免得一直重吵。
- [ ] 圈出你會用手做的那一步。寫誰做（你）以及用戶怎麼找到你（共用 inbox、簡訊、行事曆連結）。
- [ ] 從[問題與客戶](../01-problem-customer/)的名單挑第一個用戶，告訴他們你會交出去的日期。上面有人名的日期，勝過內部里程碑。
- [ ] 即使第二個用戶會想要更多，也先 ship 給那個人。然後看他們用。不要旁白。記下他們卡住的地方。
- [ ] 那次 session 之後，先砍或修一件，再加任何東西。範圍預設只會長大。

## 心智模型

```
  願景（不要做）                  這個 sprint（做）
  -------------------------      -------------------------
  accounts, teams, billing,      一個用戶
  mobile, admin, analytics,      一件工作
  "and also AI"                  一條穿過它的路
                                 軟體薄的地方你在迴圈裡

  spec 寫下來
        |
        v
  刪掉第一個人做完工作
  所不需要的任何東西
        |
        v
  日期 + 有名字的用戶
        |
        v
  看他們用，然後再砍一次
```

MVP 完成於那個人拿到結果，不是你對 repo 感到驕傲。

## 常見失敗模式

- **因為「以後會需要」而做 platform。** 五個用戶碰過產品之後，你需要的會是另一件事。過早的結構，是兩週計畫變成一學期的方式。
- **Sprint 結束時沒有具名用戶。** Launch 到一個空的 production URL 是一次 deploy。先把人排進行事曆。
- **愛上 demo。** 為其他學生優化的 demo，通常不是財務長走的那條路。看財務長。
- **品質放錯地方。** 空白狀態像素完美，會弄丟資料的那一個動作零測試。把他們必須信任的步驟打磨好。其餘保持醜。

## 觀看

- [How to Build An MVP \| Startup School](https://www.youtube.com/watch?v=QRZ_l7cVzzU) — Michael Seibel, Y Combinator。Airbnb、Twitch 和 Stripe 早期產品實際長什麼樣子，以及為什麼速度比完整更重要。
- [Michael Seibel - How to Plan an MVP](https://www.youtube.com/watch?v=1hHMwLxN6EM) — Y Combinator。把 spec 限時、寫下來、砍掉，不要愛上它。上面那場 talk 的實務搭檔。

## 延伸閱讀

- [How to Plan an MVP](https://www.ycombinator.com/library/6f-how-to-plan-an-mvp) — 對應 Seibel 那場 lecture 的 YC library 文稿。
- [Do Things that Don't Scale](http://www.paulgraham.com/ds.html) — Paul Graham。手動工作是範圍的一部分，不是範圍的失敗。
