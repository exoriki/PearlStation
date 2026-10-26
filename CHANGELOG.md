# Changelog

What changed on [pearlstation.io](https://pearlstation.io).

## 0.4.6 (2026-10-26)

- **Two new guides:** [Pearl mining alerts on Telegram](https://pearlstation.io/news/pearl-mining-telegram-alerts) and [Pearl mining pools compared](https://pearlstation.io/news/pearl-mining-pools-compared-october-2026): fees, payout schemes and who finds the blocks.
- Pearl Fortune's hashrate no longer shows 0 for a few minutes at the start of each hour.

## 0.4.5 (2026-10-26)

- **Clean links.** App pages now have their own address, like [pearlstation.io/app/pools](https://pearlstation.io/app/pools) instead of `/app#pools`. Back and forward work, and old `#` links still open the right page.
- **Telegram alerts link to the app.** Every alert and bot reply ends with links to the right page: Workers for a rig going offline, the explorer transaction for a payout, Market for price alerts.
- **Several wallets in Telegram.** The daily report shows your totals and then a block per wallet (mined, average hashrate, workers online). `/status` asks the pools right then and shows each wallet's hashrate. Offline alerts say which wallet the rig is on.
- **Faster bot.** Replies are handled side by side, so one slow command no longer holds up the others, and the bot shows "typing…" while it asks the pools.
- **Wallet history loads fast.** If the explorer is slow, the app shows your saved history at once and refreshes it in the background, instead of waiting up to a minute.
- **Pools and Earnings agree.** "PRL per PH/s" on Pools now uses the 7-day average network hashrate, like Earnings. On pools you mine on, it also shows your real yield.
- News images come in 16:9, 4:3 and 1:1, so search results no longer crop the text.

## 0.4.4 (2026-10-22)

- **Pearl news on the site.** [pearlstation.io/news](https://pearlstation.io/news) has guides, release round-ups and reports about Pearl mining, each with its own featured image. The three newest posts are on the home page, and News is in the top menu. Follow along with the [RSS feed](https://pearlstation.io/news/feed.xml).
- **Who finds the blocks.** A new Blocks page in the app matches every Pearl block to the pool that found it, read from the chain: blocks per pool over 24 hours and 7 days, each pool's luck, and the latest blocks.
- **FP8 fork tracker (PIP-3).** Where the fork stands, which GPUs the proposal lists, and a "will my GPU still mine?" checker.
- **OneZeroMiner** (NVIDIA) is in the Pro setup generator for Kryptex, the pool that documents it: Windows and Linux start files and a HiveOS flight sheet, always on the newest version.
- New releases of SRBMiner, BzMiner, WildRig and OneZeroMiner are tracked for the "new miner version" alert.

## 0.4.3 (2026-10-21)

- **New miner releases show up within an hour** (was three hours), and right away after every update of the site.

## 0.4.2 (2026-10-21)

- **Miners per pool.** Each pool card in the guide now lists the miners that pool documents itself. The Pro setup generator only offers a pool for the miners it supports, so you can't build a setup that won't connect.
- **WildRig Multi is offered for PearlHash only**, the only pool that documents it.
- **Intel Arc support:** BzMiner (NVIDIA, AMD and Intel Arc) is in the guide and in the Pro setup generator: Windows and Linux start files and a HiveOS flight sheet.
- **Share difficulty.** Every pool card says how that pool handles share difficulty. On Kryptex (`d=NUMBER`, 2,097,152 to 4,294,967,296) and AlphaPool (`x;d=NUMBER`) you can set your own in the setup generator.
- **Pools you pick yourself stay picked.** If you tick pools for a wallet in Settings, the daily auto-detection no longer replaces your choice. "Detect again" turns detection back on.
- **Neutral pool guide.** No pool's own marketing in the notes. A note now says how the picks and the order are worked out, and that referral links never change them.

## 0.4.1 (2026-10-21)

- Button to remove offline workers from the list. They come back by themselves once they mine again.
- Telegram test alerts are rate limited.
- Proper favicon and app icons (install to home screen).

## 0.4.0 (2026-10-20)

- First public release: one dashboard for every major Pearl pool, on-chain payouts, earnings and calculator, pool comparison and guide, network and market.
- Accounts with a username and password (no email), settings encrypted with your password.
- Pro: Telegram alerts and reports, ready-made miner setup files and HiveOS flight sheets, a year of hashrate history and a tax CSV export.
