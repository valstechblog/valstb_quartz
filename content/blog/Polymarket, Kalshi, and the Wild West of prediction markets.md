---
title: "2025-09-13: Polymarket, Kalshi, and the Wild West of prediction markets"
date: 2025-09-13
draft: false
---
Substack: [We're speeding directly into the AI of the hurricane](https://valstechblog.substack.com/p/were-speeding-directly-into-the-ai)

OpenAI just signed a [five-year, \$300 billion contract](https://techcrunch.com/2025/09/12/why-the-oracle-openai-deal-caught-wall-street-by-surprise/) with Oracle, driving a 30%+ Oracle stock price spike earlier this week _[even](https://www.cnbc.com/2025/09/09/oracle-orcl-q1-earnings-report-2026.html)_ [with an earnings miss](https://www.cnbc.com/2025/09/09/oracle-orcl-q1-earnings-report-2026.html), making Larry Ellison [the world’s richest man for one day](https://time.com/7316518/larry-ellison-richest-musk/) and the phones in my office light up with texts from newly-minted millionaires.

Prediction market platforms Polymarket and Kalshi [also lit up with activity](https://protos.com/larry-ellison-became-the-worlds-richest-person-but-not-on-polymarket/) in contracts trading outcomes of [Elon Musk remaining the richest in the world through 2025](https://polymarket.com/event/musk-no-longer-richest-person-in-the-world-by-end-of-year) (Polymarket: “resolve to **Yes** if Elon Musk is any rank other than #1 on the Bloomberg Billionaires Index at any point between June 30, and December 31, 2025, 11:59 PM ET”) and a [bet (currently ranking Musk, Ellison, and Bezos) at the world’s wealthiest this year](https://kalshi.com/markets/kxwealthy/wealthiest-person-in-world/kxwealthy-25) (Kalshi: “If [bet] is the wealthiest person in the world on Dec 31, 2025, then the market resolves to **Yes.** Outcome verified from **[Forbes](https://www.forbes.com/real-time-billionaires/#45c1a6b23d78)**.”).

![](https://substackcdn.com/image/fetch/$s_!F6Bk!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F4f0d90d6-47bc-4c39-afc4-70693a68d848_906x473.png)

Image: [Kalshi](https://kalshi.com/markets/kxwealthy/wealthiest-person-in-world/kxwealthy-25)

### Preliminary round: Musk vs. Ellison

> “Ellison cemented his position as the [biggest wealth gainer](https://www.businessinsider.com/wealth-gain-rich-list-billionaires-nvidia-huang-meta-zuckerberg-buffett-2024-9) in Bloomberg's ranking this year with a \$191 billion increase as of Wednesday's close. Musk led the list of greatest wealth losers with a \$48 billion decline this year. Those shifts in fortunes reflect Oracle stock rising 97% and Tesla stock sliding 14% since the start of January.” — [Business Insider](https://www.businessinsider.com/elon-musk-larry-ellison-wealth-rich-list-oracle-stock-ai-2025-9), September 11, 2025

I was going to start with a deep dive on financial derivatives, at least futures contracts, because understanding these specific financial instruments makes understanding prediction markets much easier. Then I decided this isn’t a finance blog so I’m just going to let Investopedia (every first-year analyst’s best friend) and a Wharton blog do most of the explaining here:

- _[Event Contracts](https://www.investopedia.com/events-contracts-8601422),_ Investopedia
    
    - **“An event contract pays its face value if the event happens and $0 if it does not. The pricing of event contracts is based on other speculators’ judgments on the likelihood of an event.”**
        
    - “Unlike traditional futures contracts, which are staked to the expected prices of commodities, financial instruments, or indices, event futures are priced according to the perceived likelihood of particular events winning or losing. The Chicago Mercantile Exchange (CME) has been offering event futures since 2022, allowing clients to choose _yes_ or _no_ on the predicted closing price of Bitcoin, commodities, and indexes. _**Kalshi is another major purveyor of event contracts; the online platform has been the most out front defending event contracts’ legitimacy while offering a far wider variety of them than the CME.**_”
        
- _[A Primer on Prediction Markets - Wharton Initiative on Financial Policy and Regulation](https://wifpr.wharton.upenn.edu/blog/a-primer-on-prediction-markets/)_ (Liu & Bierwirth, 2025)
    
    - “Prediction markets are a little bit more nuanced than derivatives markets since they can cover solely event-based outcomes instead of price-based action in traditional derivatives exchanges. This opens up a realm of opportunity for traders both individual and institutional depending on the investments they pursue. This encourages a new market of potential hedges.”
        
    - Interesting prediction markets history in _[Prediction Markets](https://pubs.aeaweb.org/doi/pdfplus/10.1257/0895330041371321)_ (Wolfers & Zitzewitz, 2004): DARPA proposed establishing a Policy Analysis Market in 2003 “based on indices of economic health, civil stability, military disposition, conflict indicators and potentially even specific events… concept was to discover whether trading in such contracts could help to predict future events and how connections between events were perceived… Critics savaged DARPA for proposing ‘terrorism futures’… **best-known prediction market among economists [at time of writing] is the Iowa Electronic Market”** (election markets). Featured TradeSports (allowed trading in “current events” and “political futures” on top of sports markets; sports betting market now filled by DraftKings and PrizePicks) and the [Hollywood Stock Exchange](https://www.hsx.com/) (Downton Abbey is currently [performing well](https://www.hsx.com/security/view/DWTA3)).
        

Regarding the [“world’s richest person this year”](https://kalshi.com/markets/kxwealthy/kxwealthy-25) trade, see Kalshi’s [contract terms](https://kalshi-public-docs.s3.amazonaws.com/contract_terms/WEALTHY.pdf):

- Underlying is defined as “persons on the Forbes Real-Time Billionaire List”
- “Settlement Value for this Contract is $1.00”

e.g. Traders currently may buy a **Yes** on Larry Ellison for 27 cents; if Forbes ranks Ellison first in the world on December 31, 2025, holders of this contract are paid out $1 per unit less the transaction fees they paid Kalshi.

![](https://substackcdn.com/image/fetch/$s_!oB0H!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F21f906a3-dc73-41c4-a0d5-810a1bbc1d15_343x234.png)


Image: [Kalshi](https://kalshi.com/markets/kxwealthy/wealthiest-person-in-world/kxwealthy-25)

On the other side of each trade is another trader taking the opposite side, a similar pricing model to a traditional stock market, although trader demographics and behaviors might look very different in these markets compared to those of international stock exchanges.

_N.B._ Clicking into these contracts shows us just how fast and loose the terms can be, and how messy calculations like taxing gains on these bets could get. [Protos](https://protos.com/larry-ellison-became-the-worlds-richest-person-but-not-on-polymarket/) correctly questions the validity of the Polymarket market remaining open given its resolution criteria on Musk’s Bloomberg standing bet — “**Yes** if Elon Musk is any rank other than #1 on the Bloomberg Billionaires Index at any point between June 30, and December 31, 2025, 11:59 PM ET” — “if someone was refreshing their browser consistently, it’s possible that the webpage displayed Ellison in the #1 spot at some point yesterday”.

It’s easy to imagine how traders in this market might be incorporating Oracle and Tesla stock price projections, Tesla’s board of directors proposing a [trillion-dollar compensation package](https://www.cnbc.com/2025/09/05/tesla-musk-pay.html) for Musk (contingent on Tesla peformance), and any number of other data points and opinions into their personal assessment of the worth of these contracts, informing their buy/sell decisions and setting marketplace contract prices.

It’s also easy to imagine how reporting capital gains from prediction market winnings, [currently considered by the IRS as taxable income](https://frblaw.com/understanding-the-tax-implications-of-prediction-market-winnings/), could get complicated if tracked on a supposedly “decentralized” system. (More on this later.)

### The playoffs: Polymarket vs. Kalshi

> “Prediction market firms Kalshi and Polymarket are both eyeing multibillion-dollar boosts to their current valuations, according to [The Information](https://www.theinformation.com/articles/prediction-startup-polymarket-fields-offer-9-billion-valuation-kalshi-nears-5-billion-financing), citing anonymous sources. Per the report, Kalshi is ‘close’ to raising funds at a \$5 billion valuation, while Polymarket has received an offer that could push its valuation as high as \$9 billion” — [LinkedIn News](https://www.linkedin.com/news/story/polymarket-kalshi-entice-investors-6590964/), September 13, 2025

Polymarket and Kalshi markets both [out-predicted Nate Silver in the 2024 US presidential election](https://www.businessinsider.com/polymarket-kalshi-trump-victory-future-prediction-markets-2024-11). “The argument for prediction markets' accuracy is that people are more decisive with their money, picking outcomes they think will happen, not just ones they want to happen… They’re also ways to distill the daily news cycle…” but “didn't forecast the popular vote as precisely”. “They have their own imperfections, just like all of the other metrics do… [supporters of certain political candidates may find ways to place wagers to use their influence]… **I suspect as these markets grow more prominent, it's possible their usefulness will decline**” ([Broughel](https://cei.org/experts/james-broughel-2/)).

Almost a year after the election prediction upset, Polymarket user “romanticpaul” [bet on the Swift-Kelce engagement](https://www.businessinsider.com/taylor-swift-travis-kelce-engagement-polymarket-bet-pays-off-2025-8) “less than 22 hours before the viral announcement dropped”, turning a more than $3,000 profit.

So what sets Polymarket and Kalshi apart? What justifies multi-billion dollar valuations for both? What regulatory challenges have they faced? Is one better-prepared than the other for long-term success?

#### Polymarket: “hybrid-decentralized order book”, emerging from years of US regulatory friction

In 2022, just two years out of stealth, [Polymarket blocked US-based users](https://thedefiant.io/news/defi/polymarket-settlement-cftc) after a settlement with the CFTC to pay $1.4 million and “[facilitate the resolution (i.e. wind down) of all markets displayed on Polymarket.com that do not comply with the Commodity Exchange Act (CEA) and applicable CFTC regulations](https://www.cftc.gov/PressRoom/PressReleases/8478-22)”.

This month, the CFTC approved Polymarket to [re-launch in the US](https://www.reuters.com/sustainability/boards-policy-regulation/polymarket-receives-green-signal-cftc-us-return-2025-09-03/), which comes after [Polymarket acquired CFTC-licensed QCEX](https://www.prnewswire.com/news-releases/polymarket-acquires-cftc-licensed-exchange-and-clearinghouse-qcex-for-112-million-302509626.html) for $112 million in July and announced an [official partnership with xAI in June](https://www.coindesk.com/business/2025/06/06/polymarket-partners-up-with-elon-musks-xai).

Polymarket traders think the odds of a 2025 US launch look pretty good:

![](https://substackcdn.com/image/fetch/$s_!O2CV!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F8430f1ad-bdba-47e9-9d1b-58b4b12d3901_950x483.png)

Image: [Polymarket](https://polymarket.com/event/will-polymarket-us-go-live-in-2025)

Polymarket has always been “crypto-enabled”; it’s sometimes described as [“decentralized”](https://cointelegraph.com/news/polymarket-chainlink-partner-prediction-market-resolution-accuracy), although official documentation is careful to list a [“hybrid-decentralized” Central Limit Order Book](https://docs.polymarket.com/developers/CLOB/introduction).

Annotated excerpts from a [technical summary](https://rocknblock.io/blog/how-polymarket-works-the-tech-behind-prediction-markets) of how Polymarket works:

- CLOB - Central (orders collected in one place) Limit (supports limit orders) Order Book: “the order book is purpose-built for trading binary options. When a user places a limit order, the system also displays a mirrored order for the opposite outcome… **This design is based on Polymarket’s core assumption: one YES share and one NO share always equal one dollar… Because of this, any order can be interpreted as its opposite”**
    
- “Off-chain, there’s a backend operator responsible for tracking and matching orders, as well as preparing the data needed for market orders… When a user creates an order, they generate a data structure signed with their private key using the EIP-712 standard. **Orders stay off-chain until execution, which lets users update or cancel them without needing on-chain transactions.**”
    
- “On-chain, a smart contract receives that data and handles the calculations and actual order execution… **Once the final outcome is confirmed by the oracle** _[“decentralized optimistic oracle” aka third-party data source used as resolver]_**, a reportPayouts call is sent to the CTF contract** _[handles order processing, fees, etc.]_**. This stores the result on-chain. After that, token holders can call the redeemPositions method. It burns their shares** _[remember order mirroring; burn shares by removing them from circulation and paying out users]_ **and returns their portion of the collateral.**”
    

The sooner Polymarket is able to legally re-launch in the US, the sooner it will be able to capture additional market share.

#### Kalshi: “first fully CFTC-regulated event contracts market in the US”, making crypto and AI investments

> “A federal judge has cleared the way for people to bet on U.S. election results for the first time… struck down a decision from the [CFTC] that prohibited gambling companies and users from betting on the outcome of Congressional races… U.S. District Court Judge Jia Cobb ruled in favor of the New York-based company Kalshi” — [The Hill](https://thehill.com/business/4877201-judge-clears-way-for-bets-us-elections/), September 12, 2024

> “In a Sept. 2023 decision, the [CFTC] told Kalshi it could not offer yes-no prediction bets on which party would control the House of Representatives and the Senate, ruling that it constituted illegal gambling activity that is contrary to the public interest… Such bets “could potentially be used in ways that would have an adverse effect on the integrity of elections, or the perception of integrity of elections — **for example, by creating monetary incentives to vote for particular candidates,**” the agency wrote.” — [AP](https://apnews.com/article/betting-on-elections-gambling-kalshi-trump-harris-4f45fdf2bd8b1d30d4e1f131e637418a), September 11, 2024

Kalshi has not operated without its fair share of regulatory hurdles, but its main differentiating factor from Polymarket is that it was able to stay within regulation in the US in the three years and counting Polymarket has been officially locked out.

Still, regulated access to US customers is just a slice of the global betting market:

> “Kalshi operates as a [CFTC]-regulated platform within the United States, requiring dollar deposits and traditional KYC procedures, **which limits its user base but provides regulatory certainty for American participants**… Polymarket, conversely, operates on Polygon using USDC settlements, offering pseudonymous trading and broader global accessibility but facing restrictions in the U.S. market due to regulatory uncertainties” — [The Block](https://www.theblock.co/post/369877/kalshis-875-million-august-volume-recent-funding-signal-rising-competition-with-crypto-native-polymarket), September 8, 2025

For example, Kalshi processed \$875 million in volume in August, while Polymarket processed $1 billion. The future success of Kalshi will depend on collective user appetite for betting markets and relative incentives of trading on these and similar betting platforms especially if its main competitor Polymarket’s US re-launch goes smoothly. It’ll be a question of how many winners can co-exist in this space, much like the conversation around [how many players can co-exist in the AI space](https://theconversation.com/ai-hype-has-just-shaken-up-the-worlds-rich-list-what-if-the-boom-is-really-a-bubble-265080).

Just as many investors are questioning when the AI bubble will burst, just as the crypto wave continues to ebb and flow, these two major players entering their own unprecedentedly global regulatory race will drive similar volatility in the prediction market industry.

### Play-by-play: Sports betting

Sports betting is a [$100 billion market](https://www.grandviewresearch.com/industry-analysis/sports-betting-market-report). For a practice that started thousands of years ago with chariot and horse racing in ancient Greece and has long been associated with gambling and crime, betting markets are rather poetically plagued by often-paralyzing regulatory hurdles. The US Supreme Court federally [legalized sports betting in 2018](https://rg.org/statistics/us), formerly banned by the [Professional and Amateur Sports Protection Act](https://www.congress.gov/bill/102nd-congress/senate-bill/474), “allowing each state to set its own sports gambling regulations without federal restrictions”.

Technically, sports betting is currently illegal in California, but there are ways around it; PrizePicks is the [“Official Daily Fantasy Partner of the San Francisco Giants”](https://www.prizepicks.com/press-news/prizepicks-teams-up-with-the-san-francisco-giants-as-official-daily-fantasy-sports-partner), legally classified a [“fantasy sports operator”](https://www.stokastic.com/news/is-prizepicks-gambling-or-dfs-ac11/) and not considered “online gambling”. DraftKings Sportsbook does restrict users from [placing real money bets in states where sports wagering is not permitted](https://support.draftkings.com/dk/en-us/can-i-sign-up-for-draftkings-even-if-i-m-not-a-resident-of-a-state-that?id=kb_article_view&sysparm_article=KB0010554). DraftKings is working hard to get California [on board](https://capitolweekly.net/odds-getting-better-for-legalized-sports-betting-in-california/).

Because event contracts are regulated as financial instruments not structured and regulated in the same way as sportsbooks, prediction market platforms [“could reshape the sports betting landscape by introducing lower-cost alternatives to traditional state-regulated sportsbooks”](https://www.legalsportsreport.com/222331/kalshi-to-offer-super-bowl-markets/); the caveat, of course, is this only becomes a sustained market if “[these platforms] can withstand CFTC regulation”.

With college football, the NFL, US Open, and MLB in full swing, just to name a few, trading volume on Kalshi recently hit [\$300 million in one weekend](https://www.legalsportsreport.com/240961/kalshi-trading-volume-football-week-1/), almost $200 million on football Sunday, with more than 95% of all trading involving sports contracts (Kalshi launched sports contracts at the start of 2025).

Kalshi specifically [differentiates trading event contracts from sports betting and stock trading](https://news.kalshi.com/p/event-contracts-versus) in the mechanics of how their platform works. Kalshi matches counterparts such that someone needs to take the other side of what you are betting (charging transaction fees per trade), unlike traditional sportsbooks that accept bets on both sides of outcomes markets and charge commission on losing bets.

There are open challenges from state regulators:

> “[Massachusetts] Attorney General Andrea Joy Campbell alleged [in a filing](https://www.mass.gov/doc/kalshi-final-filed-complaint/download) that sports event contracts, which Kalshi introduced in January 2025, violate the state's sports wagering laws, which require operators to be licensed. Campbell is asking for a court to block Kalshi from offering sports prediction markets in the state without a license, as well as seeking monetary and other relief.” — [CoinDesk](https://www.coindesk.com/policy/2025/09/12/massachusetts-state-attorney-general-alleges-kalshi-violating-sports-gambling-laws), September 12, 2025

But these are not regulatory challenges specific to prediction market platforms. As much as sports betting keeps prediction market platforms afloat via pure trading volume in the seasons between other high-volume events like elections, more at risk in this regulatory space are platforms like DraftKings and Fanatics built on traditional sports books. The question now is how long dedicated sports betting platforms will survive in a landscape increasingly overtaken and defined by new players creating new markets with new rules.

As they say in the rodeo, [“Cowboys may come and go, but the rodeo is forever”](https://www.customizedgirl.com/blog/25-rodeo-quotes-sayings/). That couldn’t be more true of the cowboys riding these modern bull markets.