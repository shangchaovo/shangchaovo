# Chase Xie

独立做一些自己每天会打开的小站。盯盘的、背单词的、写校招简历的，都挂在 [chaestblog.pages.dev](https://chaestblog.pages.dev/) 上。路过想用直接点进去，不用装东西。

平时主要看加密衍生品，以及美股里跟算力、HBM、设备相关的那几条线。现成工具经常对不齐自己的习惯，就自己写；写完放到公网，电脑关机也能开。

[X @johny_xie](https://x.com/johny_xie) · [邮箱](mailto:shangchaoxie888@gmail.com) · [Buy Me a Coffee](https://buymeacoffee.com/chasetse)

---

## 加密终端

**线上：[crypto-funding-arbitrage.pages.dev](https://crypto-funding-arbitrage.pages.dev/)**  
源码：[crypto-funding-arbitrage](https://github.com/shangchaovo/crypto-funding-arbitrage)

看盘不想在五家交易所、DexScreener、期权网站之间来回切，就把常用的四块塞进一个页。

- **资金费率**：Gate / MEXC / Bitget / OKX / Hyperliquid / dYdX 大概 3000 个永续，费率统一折成 8 小时，方便横着比。可以筛「现货能买、再空永续收资金费」的正向机会，也可以找同一币种的跨所费率差。超过 15 分钟的数据会标陈旧，不用假数填空。
- **Meme 异动**：盯 Solana / Base / BSC / ETH 上量能刚起来、池子还新的标的。合约没检完的只标「检测中」，不会假装安全。
- **清算热图**：按 OKX 持仓、杠杆分层和入场分布，估 BTC / ETH / SOL 等在哪些价位爆仓会堆在一起。
- **期权 Wall**：BTC / ETH 的 Call、Put 持仓墙、Max Pain、PCR、25Δ 偏度。Deribit 优先，被限流时退到 OKX。

没有框架，也没有打包。浏览器直连公开接口，国内走 Cloudflare 上的代理。

## 外资研报 · FResearch

**线上：[fresearch.cc.cd](https://fresearch.cc.cd/)**  
源码：[ib-research](https://github.com/shangchaovo/ib-research)

不想为了 NVDA、TSM、ASML 去翻六七个新闻源，就把 UBS、Citi、摩跟、大摩这些机构的评级变动和目标价收到一起。公开标题和摘要会按股票、按机构归并；有交叉证据的目标价才进卡片，LLM 自己抽出来的数字不会单独当事实。

观点发出去之后，会算 1 / 5 / 20 个交易日相对 SPY 走没走，用来判断市场当时有没有接这个方向。关注池是算力、HBM/存储、半导体设备、云和平台这几条线上大概 30 只。大约四小时抓一轮。

## WordPaper

**线上：[wordpaper.pages.dev](https://wordpaper.pages.dev/)**  
源码：[wordpaper](https://github.com/shangchaovo/wordpaper)

背单词老忘，就把当天要看的词做成壁纸。锁屏、桌面抬眼就能扫到。内置雅思、四六级、考研、JLPT 词库，也可以自己导入；复习按艾宾浩斯排。网页里能预览、导出 PNG，或者开 Live 模式一直转。

Mac 上还有个可选的小伴侣，能直接把壁纸设到系统桌面。账号在服务器上，换电脑登录还能接着背。

## 简历工坊

**线上：[resume-5lv.pages.dev](https://resume-5lv.pages.dev/)**  
源码：[resume-site](https://github.com/shangchaovo/resume-site)

给校招用的简历页。打开就是编辑器：左边填经历，右边实时看到一张 A4。超出一页会画红线；「负责 / 参与」这种空心句会标出来；粘贴 JD 只告诉你哪些词盖到了、哪些还缺，不搞看不懂的 ATS 分数。

导出走浏览器自己的「另存为 PDF」，字是矢量、能选中。不用注册，数据只在你浏览器里。清缓存会丢，重要的记得导出一份 JSON。

## 个人页 · chaestblog

**线上：[chaestblog.pages.dev](https://chaestblog.pages.dev/)**  
源码：[chaestblog](https://github.com/shangchaovo/chaestblog)

上面这些站、最近写的观点、正在盯的板块，都放在这一页。卡片上的「在线」会真的去探活，挂了能看出来。⌘K 可以搜，右下角可以留言。

主页上还有几个没单独开源的：

- [Predict Pulse](https://predict-pulse.signal-harbor.workers.dev/?view=sentiment) — 预测市场的盘口、聪明钱和带来源的情绪
- [Signal Harbor](https://signal-harbor-terminal.signal-harbor.workers.dev/#overview) — 美股 AI / 半导体新闻、分析师观点、OCC 期权墙
- [交易每日报告](https://dailytrade.cc.cd/) — 开盘前把 A 股扫描、外资研报、美股和宏观拼成一张日报

## 早期仓库

资金费率表和期权分析最早是两个分开的页，后来并进加密终端了。仓库还留着，打开这个空壳跑不起来，看线上即可：

- [funding-dashboard](https://github.com/shangchaovo/funding-dashboard) → [资金费率](https://crypto-funding-arbitrage.pages.dev/#/funding)
- [crypto-options-analyzer](https://github.com/shangchaovo/crypto-options-analyzer) → [期权 Wall](https://crypto-funding-arbitrage.pages.dev/#/options)
