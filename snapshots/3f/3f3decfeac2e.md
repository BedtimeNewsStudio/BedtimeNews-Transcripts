---
source_url: "https://www.federalreserve.gov/econres/feds/files/2023044pap.pdf"
captured_at: 2026-11-08T15:29:19Z
title: "Interconnected DeFi: Ripple Effects from the Terra Collapse"
tool: firecrawl
---

> **网页快照**：2026-11-08 15:29 UTC 抓取自 [原始页面](https://www.federalreserve.gov/econres/feds/files/2023044pap.pdf)（工具：firecrawl）。

# Interconnected DeFi: Ripple Effects from the Terra Collapse

## Finance and Economics Discussion Series

Federal Reserve Board, Washington, D.C. ISSN 1936-2854 (Print) ISSN 2767-3898 (Online)

# Interconnected DeFi: Ripple Eects from the Terra Collapse

## Anton Badev, Cy Watsky

2023-044

Please cite this paper as: Badev, Anton, and Cy Watsky (2023). \Interconnected DeFi: Ripple Eects from the Terra Collapse," Finance and Economics Discussion Series 2023-044. Washington: Board of Governors of the Federal Reserve System, [https://doi.org/10.17016/FEDS.2023.044](https://doi.org/10.17016/FEDS.2023.044).

NOTE: Sta working papers in the Finance and Economics Discussion Series (FEDS) are preliminary materials circulated to stimulate discussion and critical comment. The analysis and conclusions set forth are those of the authors and do not indicate concurrence by other members of the research sta or the Board of Governors. References in publications to the Finance and Economics Discussion Series (other than acknowledgement) should be cleared with the author(s) to protect the tentative character of these papers.

---

Interconnected DeFi:
Ripple Effects from the Terra Collapse

Anton Badev

∗
Cy Watsky

May 9, 2023

Abstract

The emerging world of decentralized finance (DeFi), facilitated by smart contracts
operating on blockchain networks, has been notable both for its rapid growth and
the high-profile collapses of several of its largest participants. In this paper, we provide a technical account of the financial mechanisms which facilitated the growth and
eventual collapse of the Terra Network. From this analysis, we outline a generalizable economic theory of blockchains which aims to differentiate the economics of
blockchains as programmable environments from blockchains as accounting ledgers for
crypto-assets. This adds to the existing literature on crypto-assets, which largely focuses on the financial characteristics of the crypto-assets themselves rather than their
underlying blockchains. We argue that DeFi is structured so as to offer consumers
distinct blockchain networks as competing choices differentiated by several key characteristics. We test several implications of this theory using Terra’s collapse as a natural
experiment, finding evidence that bridges between programmable blockchain networks
create increased risk of spillover effects to other blockchains’ programmable environments in the wake of a major shock event like Terra’s collapse. Specifically, blockchains
suffered a time-bound loss of market share and the likelihood of this loss grew approximately 40% for each additional bridge that was deployed in common with Terra at the
time of Terra’s collapse.

∗
Affiliation: Federal Reserve Board, Anton Badev (anton.i.badev@frb.gov) and Cy Watsky
(cy.h.watsky@frb.gov). We thank the members of the Federal Reserve Board’s Technology Lab (TechLab)
and Stress Testing Research Section for many insightful discussions. Lori Leu provided excellent editorial
assistance.
Disclaimer: The views expressed herein are those of the authors and not necessarily those of the Federal

Disclaimer: The views expressed herein are those of the authors and not necessarily those of the Federal
Reserve Board.

---

# 1 Introduction

Terra’s collapse in May of 2022 shocked the cryptocurrency world, as around $50 billion worth of the network’s two asset offerings, TerraUSD (UST) and Luna (LUNA), fell in value to practically nothing in the span of a week. The Terra network had promised a decentral- ized, uncollateralized stable store of value in UST, and a profitable suite of decentralized applications, leading to its position as the second-largest blockchain network in decentralized finance (DeFi) and UST’s position as the most popular “algorithmic” stablecoin at the time of its collapse. Terra’s dramatic collapse naturally gives rise to questions around the functioning of cryptocurrencies and DeFi. Was the collapse a result of fraud, ill-designed technology, or something else? What does the collapse reveal about the functioning and health of blockchain networks, cryptocurrencies, and DeFi more broadly? How did the collapse affect the rest of DeFi? Such questions remain the source of much speculation and ambiguity for cryptocurrency investors, DeFi participants, and observers. Yet, existing analyses of DeFi have not offered straightforward explanations or provided intuition for these shattering developments. In this paper, we trace the financial mechanisms and relevant incentives for participants in the Terra network over the course of its growth and collapse, laying the foundation for empir- ical analysis of the effects of its collapse. We argue that bridges, or smart-contract based decentralized applications (dapps) which transfer otherwise incompatible assets between pro- grammable blockchains, uniquely propagate risks between programmable blockchains. Rip- ple effects from the Terra network’s collapse indicate a time-delayed, disproportionate harm to programmable blockchain networks who shared a greater number of bridges with the Terra network. Further empirical analysis corroborates our approach to analyzing DeFi as a set of distinct and competing blockchain networks whose use values are influenced in significant part by their programmability and the set of available dapps and crypto-assets. Our study starts by briefly tracing Terra’s growth and collapse through metrics measuring the performance of UST and LUNA before examining the technical details of the Terra network as described in its whitepaper. We find that the Terra Network, as originally envisioned, generally aligned the incentives of participants in traditional blockchains, wherein transaction validators are incentivized to secure the network through rewards in the form of the native asset, with incentives to increase demand and maintain the stable value of UST, its native stablecoin. Yet, changes to the Terra network’s design and its expansion using bridges into cross-chain ecosystems altered the incentives and peg mechanisms structuring the Terra Network. As actors with no incentives to secure the Terra Network were granted access to UST through bridges, the Terra network grew increasingly vulnerable to stresses on the price of UST. This analysis sketches out the roles and incentives of participants in the complex and interrelated systems of dapps, crypto-assets, and blockchain networks which constitute DeFi. We proceed to detail several abstract insights about the structure of the DeFi ecosystem and apply them to the phenomenon of the collapse of Terra’s two native assets. We argue that the use value of programmable blockchains, which offer users access to financial dapps, is determined in large part by the availability of desirable assets to be used in an attractive set of dapps. Bridges allowed participants in other blockchain networks to access a “wrapped” version of UST and LUNA such that wUST and wLUNA could be used for trade, lending and borrowing services, and in other DeFi products. Conversely, bridges allowed a blockchain networks’ native assets to be used in the Terra ecosystem, driving demand, in part, for that blockchain’s assets from users of the Terra network. Following the collapse of Terra, programmable blockchain networks whose use value, as captured by the value “locked” or invested in smart contracts underlying dapps (TVL), relied in part on these connections to Terra were more greatly harmed. Next, we test several related predictions implied by our analysis of Terra’s incentives structure. Our sample includes 44 blockchain networks, comprising 99% of the market-wide TVL of DeFi. After identifying the 3 bridges deployed on the Terra network, out of 30 dapps on the Terra network overall, we empirically assess the effect of sharing bridges with the Terra Network. Our outcome variable of interest was an indicator variable taking on a value of “1” if a blockchain network’s relative TVL over the observed time period grew and “0” if a blockchain network’s relative TVL shrunk. Relative TVL, or a blockchain network’s share of TVL across all observed blockchains, allowed us to compare across blockchain networks based on specified characteristics while controlling for market-wide changes in cryptocurrency values and dapp investment. We exclude the TVL associated with bridges, so that the right hand side variable (shared bridges), which captures the ease by which assets are made available across blockchains, does not directly feed into the left-hand-side variable, comprised of value locked in non-bridge dapps. We argue that sharing more bridges with Terra would disproportionately hurt a blockchain network’s relative TVL in the wake of Terra’s collapse and the effect of sharing bridges with Terra would take time to be reflected in a blockchain’s relative TVL. The latter prediction assumes that a market reaction to a blockchain’s programmable use value – that is, disin- vestment from dapps whose use value was disproportionately harmed by Terra’s collapse – would not immediately take effect in the wake of Terra’s collapse. Our findings confirmed both predictions, as we found a blockchain network’s likelihood of increasing its TVL share decreased approximately 40% with each additional shared bridge, statistically significant at the p < 0.05 level when controlling for several relevant characteristics. This effect was not observed immediately in the wake of Terra’s collapse, but rather over the ensuing six weeks. Following previous papers observing the importance of characteristics such as shared dapps, we also compare the importance of shared bridges to shared non-bridge dapps in disproportionately spreading risk. Several possibilities for extending our empirical analysis remain, including more exacting examination of time effects and generalizing to other kinds of shocks and bubbles in DeFi. We hope this study informs the still-developing literature on crypto-asset markets and DeFi, encouraging further theoretical and empirical work on the interconnectedness in DeFi.

---

# 1.1 Related Literature

As advancements in blockchain technology have rapidly expanded the kinds of financial products and services based on public, permissionless blockchains in the last few years, from relatively straightforward ledgers of accounting for cryptocurrencies like Bitcoin, to the still- emergent world of DeFi, the literature has been playing catch-up. Ethereum, the blockchain largely responsible for popularizing smart contracts, which power DeFi applications, was only conceptualized in 2013 (Sch¨ar,2021), and investment in DeFi, measured in total value locked (TVL), only crossed the $1 billion threshold in 2020 (DefiLlama,n.d.). Today, as tens of billions of dollars’ worth of crypto is invested in the smart contracts underpinning decentralized applications (dapps), fundamental questions remain about the economics of decentralized finance. Theoretical studies have just began to understand the link between features of decen- tralized systems and actors’ incentives, e.g.Leshno and Strack(2020) analyze the trade-off between Bitcoin’s decentralized features (anonymity of miners, no incentives for miners to consolidate, and no incentive to assuming multiple fake identities) and its reward scheme. Lyons and Viswanath-Natraj(2023) analyze the elements of arbitrage design which stabi- lize the prices of stablecoins, andd’Avernas et al.(2022) presents a framework by which stablecoin designs’ resilience to demand shocks can be understood, including factors such as decentralization, backing collateral, and seigniorage. Much of the literature on DeFi, as opposed to the internal mechanics of individual blockchain networks or asset classes, continues to use financial analysis methods to investi- gate the drivers of cryptocurrency prices, market inefficiencies, and price correlations in DeFi, expanding on similar analyses of pre-DeFi cryptocurrency markets (Yousaf and Yarovaya,

2022).Karim et al.(2022) build on previous analyses of cryptocurrency markets using con- nectedness measures of pricing data (Bouri et al.,2021;Ji et al.,2019) while taking into con- sideration basic characteristics of different crypto-assets’ use in DeFi. Research into drivers of cryptocurrency prices in DeFi, including metrics of investor attention (Corbet et al.,2022)

---

and bubbles (Maouchi et al.,2022), follows a similar trajectory. While such research may
be useful for investors, and may offer some insights into DeFi markets along the way, they
do not assess the fundamental financial and technological mechanisms underpinning DeFi
today.

An emerging literature discusses the technical and financial risks posed by DeFi and
the potentials for spillover effects into different markets.Carapella et al.(2022) survey
risks and potential of technological innovations in DeFi, andAzar et al.(2022) examine
financial stability implications of the growth of DeFi, among other changes in cryptocurrency
markets.Makarov and Schoar(2022) identify areas of potential rent accumulation due to
factors endogenous to DeFi architecture.Boissay et al.(2022) analyze fragmentation in the
context of emerging blockchains offering different sets of DeFi applications. Terra’s collapse
has prompted increased interest from the academic literature on the economics of DeFi.
Several papers unpack the factors that led to the run on Terra and the ways in which it
unfolded.Uhlig(2022) proposes a novel theoretical model to describe the decisions of agents
which led to the gradual unfolding of the run on Terra, andLiu et al.(2023) interrogate
features of DeFi, such as the public nature of blockchains and the complexities created from a
multi-chain system, which they argue in part led more sophisticated investors to run earlier.

Our approach is complementary to the existing literature in that we parse the Terra
collapse for economic insights about cryptocurrencies and DeFi, yet we diverge significantly
in unpacking the systemic implications of the ways in which Terra grew to be interlinked
with other blockchains. We analyze DeFi as a set of distinct, competing programmable
environments interlinked by smart contract-based bridges, which distort the propagation of
risk in the event of a major shock. We hope our empirical analysis informs the theoretical
literature about the existence of properties which have material impacts on the dynamics of
the market.

---

# 2 Background

Terra was created in 2018 by Terraform Labs as a Proof-of-Stake (PoS) blockchain governed by a decentralized network of validators with two asset offerings: Terra USD (UST) and Terra (LUNA). In its whitepaper, the founders present Terra as an alternative to Bitcoin’s “extreme price volatility” which makes payments inefficient as prices have the potential to drastically change between transaction initiation and settlement. They argue that UST’s peg to the U.S. dollar via “elastic monetary policy,” solves this issue, and “efficient fiscal policy” promotes adoption through the Terra Treasury’s stimulus programs incentivizing development of decentralized applications (dapps) on the Terra network (Kereiakes et al.,

2019). Coinciding with overall growth in crypto markets in 2021, the Terra network grew rapidly along both metrics outlined in its whitepaper: value of its native assets and use of protocols deployed on the Terra blockchain. According to data from Messari, total market capitalization of LUNA and UST grew dramatically in 2021 until May of 2022 (Messari,n.d.). Market capitalization, or market cap, refers to the supply of tokens multiplied by the market value of these tokens. Because UST’s value was, in theory, pegged to 1 USD, its growth in market cap rose according to its supply, while LUNA’s rose in accordance with its price. Initially, their combined market caps totaled under $1 billion, captured by a relatively low value of LUNA and low supply of UST, but both grew to a combined market capitalization over $50 billion at its peak. LUNA’s supply exhibited some deflationary pressure. In general, the market caps of both tokens grew considerably over the same time period, though not always at similar rates. In May of 2022, the market caps of both tokens fell significantly over the course of a week and LUNA’s supply spiked. Figure1displays the prices of UST and LUNA over the course of the Terra Network’s collapse in May of 2022. The price of LUNA fell to practically nothing, making it worthless, while the price of UST fell significantly off of its dollar peg, making it functionally useless as a stablecoin. LUNA’s supply grew over 20,000 fold as it

---

Figure 1: Price of UST and LUNA, May 2022. Source:DefiLlama

Figure 2: TVL in Terra (USD). Source:DefiLlama

experienced an inflationary spiral caused by mass redemptions of UST (Messari,n.d.). Figure2displays another way of measuring the growth of the Terra network: the total value locked (TVL) in dapps (or protocols) deployed on the Terra blockchain from January 1, 2021 through May 2022. The TVL indicates the value of tokens “locked” in a protocol; in a lending protocol, for example, wherein a user deposits collateral in order to borrow funds, value locked would include the number of tokens locked as collateral in the protocol multiplied by its real-time price. TVL of an individual protocol (in other words, the smart contracts facilitating the dapp’s service to its users) sums the total market value of tokens locked in the protocol. The TVL of a network, such as in Figure2, represents the sum of value locked across all protocols on a network. While not a perfect data metric, it roughly captures the value that users spend engaging with protocols on the Terra network over time,

i.e., the growth in use of the Terra network’s dapps. Thus, Figure2indicates that Terra’s use value as a dapp environment grew significantly, and in a roughly similar pattern to growth of
the network’s two tokens’ market caps. Likewise, as the value of tokens deposited in smart
contracts plummeted and users fled from dapps on the Terra network, the TVL of the Terra
network fell to practically nothing as well.

Thus, taken together, the data show that the Terra network grew and collapsed by both
measures as outlined in its whitepaper: in the value of the network’s two native assets, and
in use value as an environment for dapps.

2.1 Mechanisms Native to the Terra Network

We first describe the Terra Network’s internal financial mechanisms. The original design of
the Terra Network attempts to structure relevant actors’ incentives so as to strengthen the
network’s security and growth. Though we make no predictions about the sustainability of
algorithmic stablecoins, and in fact,d’Avernas et al.(2022) argue compellingly that such
stablecoins are fundamentally flawed in design, we illustrate the baseline structure of the
Terra Network’s environment to compare against its later expansions to connect to other
blockchain.

2.1.1 UST and LUNA

Terra’s native cryptocurrency, LUNA, secured the network through a Proof-of-Stake (PoS)
consensus mechanism, wherein validators “staked” LUNA and, when elected to validate a
set of transactions, confirmed or rejected the legitimacy of proposed transactions. Validators
received LUNA as a reward for validating transactions and were incentivized to act faithfully,
as their stake could be destroyed if they acted against the rules of the network. The likelihood
of being selected for transaction validation was weighted by the amount of LUNA a validator
staked. Validators also voted on governance proposals within the network.

---

price on exchanges. However, LUNA differs significantly in how it relates to the stablecoins
offered on the Terra Network, what Terra founders called “Terra Money”. Though initially
conceived of as a “family” of stablecoins pegged to the value of various fiat currencies, we
focus on UST, the U.S. dollar-pegged stablecoin which became by the primary (and only
widely-used) stablecoin on the network.

The Terra whitepaper describes how the stabilizing mechanism for UST’s price is facilitated by an arbitrage mechanism between UST and LUNA, as well as long-term incentives
for validators. The arbitrage mechanism pegging UST’s value to the U.S. dollar is designed
as follows:

1 UST is always exchangeable for $1 worth of LUNA, and $1 worth of LUNA is
always exchangeable for 1 UST. If the value of UST sinks on the open market
to below $1, a holder of UST can trade 1 UST for $1 worth of LUNA, thereby
extracting a profit (as they received more market value of LUNA than the market
value of UST sold). This contracts the supply of UST, putting upward pressure
on the value of UST and downward pressure on the value of Luna. When UST’s
price on the market rises above $1, users can extract a profit by selling $1 worth
of LUNA for 1 UST, thus receiving more than $1 worth of UST while expanding
the supply of UST, putting downward pressure on its value, and contracting the
supply of LUNA, putting upward pressure on LUNA’s price.

In such a way, this mechanism also reveals that UST’s price stability mechanism was
dependent on investment in the network as defined by the value of LUNA and demand for
UST. Consider if the entire market cap of LUNA is worth only $0.50 on the open market.
If a UST holder decided to burn 1 UST to receive $1 worth of LUNA, there would not be
enough LUNA in the system to facilitate such a transaction, and the arbitrage mechanism
would no longer work. In other words, the market capitalization of LUNA had to have been
greater than the market capitalization of UST, and by some significant margin, in order to guarantee redemption of UST for LUNA while minimizing volatility of the relative supply of the tokens. The weaker the market for LUNA, the less the system was able to tolerate volatile conditions in the demand for UST. In other words, the higher total value of the LUNA supply, the greater the ability of the system to stabilize the price of a greater amount of UST. The relationship between these two native assets aligned the traditional incentives of blockchains – the higher the value of the native token, the more incentive there is to secure the network – with the unique incentives of the UST price mechanism – the higher the value of the native token, the more stable the UST price, and the higher the supply of UST, the greater the value of LUNA.

2.1.2 Seigniorage and Treasury Terra initially rewarded validators in two ways: transaction fees and seigniorage. Terra’s whitepaper argues that the network’s security, and thus its stability, is incentivized through “long-term stable rewards” for validators. They write, “Stable demand for mining is a core requirement for both security and stability” (Kereiakes et al.,2019). LUNA’s mint and burn mechanism determined validator rewards by adjusting the burn rate (what portion of seigniorage is burned vs. what portion is deposited in the Treasury) when LUNA was “earned” through the purchase of UST. When validator rewards were increasing, and the network was growing, a higher portion of seigniorage was placed in the Treasury, thus decreasing the upward pressure on LUNA’s value and the rising validator rewards; and when validator rewards were decreasing, the Treasury’s portion of seigniorage decreased and more LUNA was burned to increase validator rewards. The Terra Treasury’s portion of seigniorage was then distributed to incentivize partici- pation in the network by funding dapp development. This theoretically improved the use value of the network by offering a greater number of products on the network to users. As the whitepaper notes, the Treasury’s “stimulus programs” financed dapp development “with

---

1
the objective to increase adoption and expand the potential use cases.”

Increasing the use value of the network by encouraging participation in the various Terrabased dapps or protocols diversified the use cases of UST and LUNA, thus increasing their
value, while also rewarding the network’s validators. Every smart-contract based dapp built
on smart contracts deployed on the Terra blockchain incurred transaction fees whenever that
smart contract was executed. Greater usage of a greater number of Terra-based dapps thus
increased rewards and profits for validators.

Provision of stimulus funds occured along a three-step process

• A dapp requested an account with the Treasury with metadata in the request containing various identifying information and links to external websites with descriptions of
the project and resourcing needs.

• The Treasury’s appropriation of funds between dapps was governed by a weighting
formula based on predetermined measures of “robust economic activity” and “efficient
use of funding.”

2.2 Terra’s Multi-Chain expansion

As Terra grew, it also began to expand its reach into other blockchain networks to supplement
its original design. We find that Terra’s movement towards multi-chain protocols constructed
new incentive structures misaligned with the network’s security and growth. This created

1
For more, see (Kereiakes et al.,2019).

---

the opportunity for newly involved actors to rationally pursue outcomes that destabilized
the Terra network.

2.2.1 Bridges and Cross-chain Expansion

Several design changes to the Terra Network altered the network’s financial mechanisms
and incentive structures. In 2022, Terraform Labs established the Luna Foundation Guard
(LFG), whose “core mandate [was] to buttress the stability of the UST peg and foster the
growth of the Terra ecosystem.” In their announcement, they argue that doing so required
2
“building a cross-chain ecosystem of demand for Terra stablecoins.”

Such a “cross-chain ecosystem” diverges from the internal ecosystem outlined in the
Terra whitepaper and requires technologies that connect isolated blockchain networks. A
category of smart contract-based dapps deployed on blockchains called “bridges” are the
primary mechanism that allow for such cross-chain interactions, named as such to denote
“bridges” between otherwise disconnected blockchains. Bridges must be deployed on two
separate blockchains in order to function, and communicate information through external
3
systems using “oracles.”

A Terra user looking to use UST (a token native to Terra) on the Ethereum network
might use a bridge in the following way: The user sends 1 UST to a bridge deployed on the
Terra Network, communicating that they would like to use 1 UST on the Ethereum network
deposited to a particular Ethereum wallet address. The bridge programmatically “locks”
the 1 UST in the Terra bridge contract, so that it cannot be moved from that Terra address.
The bridge instance deployed on the Ethereum network then programmatically issues 1
“wrapped” or “synthetic” eUST token (Ethereum-UST) compatible with the Ethereum network and deposits it into the specified Ethereum wallet. By locking the equivalent amount
of UST on the Terra Network, such UST cannot be double spent between the networks,
ensuring that the eUST on the Ethereum network accurately represents UST native to the

2
See: https://medium.com/terra-money/formation-of-the-luna-foundation-guard-lfg-6b8dcb5e127b
3
See: https://academy.binance.com/en/articles/blockchain-oracles-explained.

3
See: https://academy.binance.com/en/articles/blockchain-oracles-explained.

---

Terra network. In such a way, bridges serve as the plumbing for the cross-chain ecosystem the LFG described in its mission statement. Dapps, deployed on Terra and other networks, could use bridges to create use cases combining assets and functionalities from multiple blockchains. Several bridges were deployed for Terra assets, including the Wormhole Portal bridge and the Shuttle bridge. Terraform Labs developed a web application, called Terra Bridge, which centralized access for users to bridge Terra assets to various blockchains through several different bridges. The LFG acted in several ways which further added new cross-chain mechanisms. Most significantly, the LFG purchased $3 billion worth of BTC to “support the stability and adoption of the UST stablecoin,” according to Terra founder Do Kwon. This altered the core functioning of the network, by introducing an additional peg mechanism tied to tokens outside the financial mechanisms of the Terra network. The LFG also funded dapps on the Terra network utilizing bridges for cross-chain functionality. Two examples are examined in the following sections, as well as the newly complicated set of incentive structures created by such multi-chain environments. 4

2.2.2 Anchor While various protocols deployed on the Terra network grew in popularity and value dur- ing the network’s rise to prominence, the extent to which TVL growth and absolute value was concentrated among Anchor differentiated Terra from other programmable blockchain networks such as Ethereum. The Anchor protocol was, by far, the most popular protocol on the Terra network, due to its promised 20% yields on staked UST tokens. The protocol was also largely responsible for Terra’s rapid growth, as over 70% of all UST minted on the Terra network was deposited 4 Additionally, the Terra network voted to end the Treasury’s claim to a portion of seigniorage in late 2021, placing greater deflationary pressure on the price of LUNA while providing less incentive for new development of dapps on the network.

---

into Anchor.

Users could deposit UST tokens and receive an “aUST” token as interest, which served
as a liquid representation of UST interest gained by depositing UST. aUST could then
be redeemed for UST from the Anchor protocol at the point of withdrawal or traded on
secondary markets.

The Anchor protocol also allowed users to borrow UST by putting up “bonded” versions
of ether (ETH, bETH as bonded ETH) or bonded LUNA (bLUNA) as collateral. Bonded
assets refers to liquid representations of tokens staked in order to validate transactions and
receive rewards, such as on the Terra network. The Lido protocol, deployed on several
networks including Terra, provided these bonded tokens, allowing users to stake assets while
receiving a portion of validator rewards and using a liquid representation of staked assets.
stETH could be acquired through a “bridge” to the Terra Network as well.

Because of the numerous high-leverage financial products available in DeFi, Anchor users
often engaged in and promoted methods of extracting greater profits, while taking on greater
risk, from Anchor. A quote from one blog post, for example, instructs users on such practice,
5
termed “yield farming”:

Anchor’s costs – providing stable 19.5% APY on deposited UST – outpaced its revenue,
gained from staking assets on Lido via the bonded assets and charging users fees and interest
for borrowing LUNA, rapidly depleting assets it held in its reserve. The Luna Foundation
Guard (LFG), constructed by the Terra Network’s founders, subsidized these losses through
grants to Anchor’s reserves. Despite never being profitable enough to be self-sustaining,

5
Seemedium.com.

---

Anchor’s growth led to UST’s rapid growth, and thus the Terra network’s as well. This ”vicious dependence” on the protocol to drive demand for UST from across DeFi to the Terra Network led to a fragile arrangement which ultimately collapsed (Briola et al.,2023).

2.2.3 Curve and 3pool On May 7, 2022, a series of trades on a protocol deployed on the Ethereum network, Curve, de-pegged UST’s price in decentralized exchanges (DEXs), eventually causing market-wide sell-offs of UST and LUNA and leading to the collapse of the network. Below, we describe Terra’s involvement with Curve in detail. Curve is one of the largest protocols in DeFi, and its developers describe it as an “ex- change liquidity pool. . . designed for 1) extremely efficient stablecoin trading and (2) low risk, supplemental fee income for liquidity providers.”(Egorov,2019) In other words, Curve provides users with a decentralized exchange designed especially for stablecoin trading, while incentivizing users to provide liquidity by depositing funds and receiving a portion of fees charged for trading on Curve. They implement this product through “pools,” which pool together funds from various liquidity providers, and allow users to trade in and out of the pool between coins that a pool is constructed to accept (e.g. “3pool” in early 2021 accepted and allowed swapping between 3 stablecoins; USDC, USDT, and DAI). Market making is facilitated through a formula designed particularly for stablecoins, termed “StableSwap” in their whitepaper. The whitepaper argues that the costs associated with trading between different stablecoins harmed the markets for various stablecoins in DeFi, reducing the ability of arbitrage in DeFi to stabilize the prices of these assets, which already had “a problem of price stability and liquidity.” Their product, they argue, would “increase usability of decentralized (non- custodial) stablecoins.” (Egorov,2019) Existing liquidity-providing decentralized exchange pools such as UniSwap were designed for non-stable assets, i.e., cryptocurrencies like Bitcoin or ETH, whose value was highly

---

Figure 3: Stableswap invariant, from (Egorov,2019) (a) (b)

(a)
(b)
volatile. Thus, in a Uniswap-like pool with two coins, if the share of one coin (x) grew much higher than the share of the other coin (y), the price slippage off of an equilibrium would be dramatic, reflecting market conditions. This would be undesirable for stablecoins designed to remain pegged to the same value. Thus, the StableSwap invariant decreases the slippage off of one-to-one trades between stablecoins intended to be pegged to the same fiat currency. Figure3displays graphs com- paring the Uniswap invariant with that of StableSwap and constant prices. They show that, while their formula still provides price slippage associated with imbalances in a liquidity pool, such differences are much more consistent and much smaller than that of Uniswap. Terra’s adoption into Curve was proposed by the Terra Foundation in December of 2020 and then accepted by Curve voters, to create a “metapool” for UST and 3pool stablecoins (USDC, USDT, and DAI). Their motivation, they say, is that the Mirror protocol “had recently been launched, driving demand for UST. We hope this pool will both provide sig- nificant liquidity to UST and help UST maintain its peg, whilst bringing fees and incentives to the Curve protocol.” Metapools allow for one token to trade between a token such as UST and the 3pool tokens. A year later, as Terra and UST had exploded in popularity, a proposal to increase the size of this pool was proposed by Terra. As part of it, they proposed “250 million UST of self-supplied liquidity to the Curve USTw-3CRV pool via Convex,” arguing that “Curve is the primary hub of stablecoin liquidity on Ethereum and the largest protocol in DeFi by TVL, serving as a strategically important source of expanding UST adoption, 6 particularly @wormholecrypto.” Thus, Terra’s expansion into the Curve protocol on the Ethereum network was motivated by two main factors: increasing UST’s adoption and providing an additional method of pegging UST’s value to the U.S. dollar.

2.2.4 Terra’s Demise In April of 2022, 4pool was introduced by Terra and FRAX and accepted by the Curve
3 protocol in a majority. This 4pool replaced DAI with FRAX and UST, integrating UST 4 more fundamentally into the Curve protocol while reducing DAI’s position in DeFi, which was the major decentralized stablecoin alterative to UST. 4pool’s creation was instituted by incentivizing the transfer over to 4pool from 3pool via a set of fees that made it economically rational to join the 4pool rather than the 3pool as a liquidity provider. Then, on May 7, the Terra Foundation transferred funds out of the UST-3pool to prepare for the transition to 4pool, beginning a series of trades that led to its downfall. According to blockchain analysis firm Chainalysis, Terra Foundation’s initial $150 million withdrawal of UST caused the pool to hold less UST tokens, making it “more ‘shallow,’ i.e. prone to 7 volatility.” This, in turn, led to two traders swapping 185 million UST for USDC in the pool in the next hour, causing the price of UST according to the market-making formula outlined above to de-peg against the dollar when traded against the other 3pool tokens in the liquidity pool: USDC, USDT, and DAI . As a result, market-wide panic about the de- pegging event caused a large sell-off of UST, inflating the share of UST relative to the 3pool tokens in the liquidity pool, further de-pegging the price of UST and drying up liquidity in the pool, which stood as the largest source of liquidity in DeFi for UST. As liquidity in DEXs dried up, massive sell-offs of UST on centralized exchanges (CEXs) See [https://twitter.com/terra_money/status/1465559223388053505?lang=en](https://twitter.com/terra_money/status/1465559223388053505?lang=en) See [https://blog.chainalysis.com/reports/how-terrausd-collapsed/](https://blog.chainalysis.com/reports/how-terrausd-collapsed/)

---

followed, leading to further de-pegging pressures on UST’s price. Furthermore, on the Terra
Network, users began withdrawing en masse from the Anchor Protocol and began swapping
UST for LUNA within the Terra network, even as the price of LUNA collapsed, indicating
that holders of UST across the ecosystem looked to get rid of UST in any way possible. As
LUNA’s market cap fell below that of UST, the native swap mechanism between UST and
LUNA induced an inflationary spiral, and the supply of LUNA grew almost 20,000-fold to
over 6 trillion (Figure ??).

While liquidity for UST dried up in DEXs and CEXs, and its price continuously depegged over the course of a few days, the LFG and Terraform Labs began selling off its BTC
reserves, totaling over $2 billion worth of BTC, for UST to try and prop up the supply and
price of UST. Such a large-scale selloff caused the price of BTC to drop quickly. As noted by
some on-chain data observers, as LFG had begun building up its BTC reserves to supplement
UST price market volatility and announced the migration of funds from UST-3pool to 4pool,
one trader built a short position of potentially over $4 billion against BTC and a $1 billion
OTC position of UST. This has led some speculators to believe that, anticipating the LFG
and Terraform Labs’ sell-off of BTC to defend the UST peg, this entity used the UST 3-pool
trades to profit off of shorting BTC.

3 Theory of Interconnectedness in DeFi

Our quantitative analysis hypothesizes that contagion from the Terra collapse propagated
from the Terra network to other blockchain networks through bridges, which allowed nonnative UST (wUST) and non-native LUNA (wLUNA) to be utilized in DeFi applications
on other blockchain networks. Specifically, the collapse of UST and LUNA on the Terra
network meant that wUST and wLUNA no longer provided any utility in dapps on other
blockchain networks. This created an uneven contagion effect across decentralized finance, in
which the programmable environments whose use value was in part derived from the ability to use wUST and wLUNA were disproportionately harmed by Terra’s collapse. We test this prediction quantitatively after describing the underlying theory in further detail.

# 3.1 Blockchains as accounting ledgers and blockchains as pro-

# grammable environments

Blockchain networks provide users and investors with two related but distinct functionalities:

1) as ledgers for accounting and transferring crypto-assets, and 2) as programmable environ- ments enabling decentralized financial services. All blockchains used for crypto-assets must provide some accounting mechanism in the form of a distributed ledger, in which the use value of a blockchain for consumers is determined by what assets are being accounted for (which native cryptocurrencies, stablecoins, or other tokens) and how well a blockchain performs in that capacity (speed, security, decentralization, etc.). However, not all blockchains are designed to provide high levels of the latter use value, which we refer to as “programmable use value.” For example, the primary scripting language of Bitcoin, Script, is not Turing complete, meaning that the Bitcoin blockchain environment is limited in its performance of computations. On the other hand, the primary scripting language for the Ethereum blockchain, Solidity, is Turing complete, allowing for developers to program in the Ethereum Virtual Machine (the distributed compute environment which stores data on the Ethereum blockchain) for a wide variety of purposes. This distinction illustrates the difference between what are often referred to as “pro- grammable” blockchains such as Ethereum and “non-programmable” blockchains such as Bitcoin. The programmability of Ethereum’s design allows for the scripting and deployment of smart contracts, which are programs which autonomously execute certain functions based on user-provided data and predetermined conditions (Yaga et al.,2019). These smart con- tracts form the base layer of decentralized web applications, or dapps. Dapps allow users to use various financial services which, due to the use of smart contracts, don’t require the in- volvement of an intermediary to facilitate the transactions. The ecosystem of dapps based on various blockchain networks is commonly referred to as decentralized finance (DeFi). DeFi “replicates existing financial services in a more open and transparent way. In particular, DeFi does not rely on intermediaries and centralized institutions. Instead, it is based on open protocols and decentralized applications [dapps]” (Sch¨ar,2021, page 153). Dapps can provide lending services, spot exchanges, asset management, payment platforms and other financial products without the use of a traditional intermediary (Gudgeon et al.,2020). Thus, a blockchain network’s programmable use value depends on several distinct charac- teristics, including: the variety of available dapps, the crypto-assets and asset classes usable in those dapps, and characteristics of a blockchain network’s technical performance such as security, speed, and scalability. Consider the case of a decentralized exchange, a dapp which allows users to spot trade crypto-assets without an intermediary market maker. Such a dapp’s use value for consumers is dependent on the number of crypto-assets it supports, the liquidity it provides for those crypto-assets, and the popularity and value of the crypto- assets it supports. Decentralized exchanges which offer support for worthless and unpopular crypto-assets will quite obviously be less useful than those which offer support for highly valued and traded crypto-assets.

# 3.2 Relative total value locked and programmable use value

Our discussion of programmable use value relates the technology underpinning decentralized finance to the options available for consumers when choosing which blockchain networks to use for the financial services offered in dapps. How to measure consumer behavior, and the perceived programmable use value of different blockchain networks, however, is still the subject of much debate. The most widely used metric is total value locked, which as described earlier in this paper, accounts for the value of tokens committed to smart contracts facilitating dapps.Maouchi et al.(2022, page 6) argue that TVL can effectively be used as a tool for monitoring DeFi markets and that “TVL can be seen as a gauge of the fundamental value of DeFi.” This measure, asAzar et al.(2022, page 29) note, is imperfect in part due
to the disparate ways in which value can be transferred and locked into smart contracts; for
example, rehypothecation of crypto-assets can make it difficult to assess how much actual
value is accruing in one dapp or another. Nevertheless, both papers, as well as much of the
literature, use TVL to measure the relative popularity and use of dapps across decentralized
finance.

It remains the case that, despite its imperfections as a complete and standardized metric,
TVL is the most widely used measure of investment in dapps across decentralized finance
both in the emerging academic literature and among DeFi users. Dashboards tracking the
popularity of different dapps and blockchain networks use TVL as the primary metric for
comparing across DeFi.

In our analysis, we use relative TVL as our primary measure of blockchain networks’ programmable use value. Our outcome variable Positive share change simply indicates whether
8
a blockchain network’s share of market-wide TVL increased in the wake of Terra’s collapse.
We do so for several reasons. First, by using TVL to compare across blockchain networks, we
don’t rely on TVL to indicate measures of absolute performance, for which its inconsistencies
may prove problematic. Our theoretical predictions about the effects of Terra’s collapse are
inherently about relative impacts; crypto-assets and DeFi experienced market-wide downturns after Terra’s collapse. Given the myriad blockchain networks that consumers can
choose from to participate in DeFi, we examined whether or not sharing bridges with Terra
disproportionately harmed that blockchain network’s programmable use value. Additionally,
TVL continues to be the primary indicator of a blockchain network’s relative popularity in
DeFi. Those with financial interests in the success of a blockchain network’s programmable
environment, including dapp developers and investors in blockchain networks, must then

8
Importantly, our measures of TVL exclude the TVL associated with bridges deployed on the blockchain.
See DeFi Llama’s documentation here: https://docs.llama.fi/list-your-project/readme.Given the importance
of bridges in our analysis, this allows us to better capture the effect that sharing bridges have on the relative
performance of a blockchain’s programmable environment outside of direct changes in TVL of the bridge
itself.

---

rely on TVL as a primary measure to promote their product, much as market cap or trad- ing volumes are used for cryptocurrencies and exchanges, respectively. Thus, our metric, at the very least, interrogates the success of a blockchain’s stakeholders in outpacing their competitors based on industry standards.

# 3.3 Bridges

Blockchain networks are distinct and disconnected systems, which generally do not integrate natively. The native assets of one blockchain cannot be freely transferred onto the accounts on another blockchain. To address this limitation, “bridges” have emerged, which are smart- contract-based dapps which allow users to use tokenized versions of assets native to one blockchain on another blockchain. A Terra user looking to use UST, the token native to Terra, on the Ethereum network might use a bridge in the following way: The user sends 1 UST to a bridge deployed on the Terra Network, communicating that they would like to use 1 UST on the Ethereum network deposited to a particular Ethereum wallet address. The bridge programmatically “locks” the 1 UST in the Terra bridge contract, so that it cannot be moved from that Terra address. The bridge instance deployed on the Ethereum network then programmatically issues 1 “wrapped” token (wUST) compatible with the Ethereum network and deposits it into the specified Ethereum wallet. By locking the equivalent amount of UST on the Terra Network, such UST cannot be double spent between the networks, ensuring that the wUST on the Ethereum network accurately represents UST native to the Terra network. In such a way, bridges can increase the variety of crypto-assets available for use in the dapps deployed on a blockchain network. dapp developers can code and deploy bridges in a permissionless manner, eliminating the need to rely on a particular crypto-asset’s issuer to begin using a particular crypto-asset in a desired blockchain environment. A blockchain with bridges connecting it to several other blockchains allows for users to transact with a wider variety of crypto-assets in that blockchain’s programmable environment than an entirely isolated blockchain. The literature points to several financial stability risks associated with bridges, as nu- merous high-profile crypto-asset thefts have exploited code imperfections in bridges and as Carapella et al.(2022) discuss, the ability to move assets between blockchains during liquid- ity crises can cause a “cascading” contagion effect. Indeed, our analysis of Terra’s collapse illustrates the risks associated with bridges, as the Curve 3pool relied on bridges between the Terra network and the Ethereum network to function and, eventually, facilitate UST’s collapse. Our quantitative analysis, however, approaches the question of bridges from a slightly different perspective. We seek to clarify the role that bridges play in DeFi by examining different blockchain networks as choices available to consumers, each offering different levels of use value based on various qualities. One such quality is the desirability of the assets offered, for which bridges play a fundamental role by making available new assets and asset classes taken from other blockchains. We hypothesize that if a blockchain’s programmable use value is built, in part, on the availability of wUST (wrapped or bridged UST) and wLUNA in that blockchain’s dapp-based financial services, then when wUST and wLUNA collapsed, that blockchain’s programmable use value suffered disproportionately more than blockchain networks whose programmable use value was less dependent on the availability of wUST and wLUNA. The loss in programmable use value is derived from the inability to hold value in wUST or wLUNA, as well as the inability to use wUST and wLUNA in other dapps. For example, a dapp offering exchange services might become significantly less useful if users are no longer able to swap between wUST/wLUNA and other assets. dapps offering lending services which used to allow users to deposit wLUNA/wUST as collateral might become significantly less useful. Conversely, bridges allow a blockchain’s assets to be transported to the Terra network. Just as Terra drove demand for UST by bridging it to decentralized exchanges on the Ethereum network, other blockchains derived some benefit from their assets being avail-

---

Table 1: Definitions of Variables

| Variable | Definition |
| --- | --- |
| TVL share | A blockchain&#x27;s share of total TVL across all tracked blockchains as of a specified date. |
| Share change | Percentage change in a blockchain&#x27;s TVL share from May 7,2022(before Terra&#x27;s collapse) to specified date. |
| Positive share change | Indicator taking on a value of&quot;1&quot;if a blockchain&#x27;s share change is greater than0in specified time period. |
| Stablecoin market cap | Market Cap of stablecoins held in addresses on a given blockchain. |
| dapps | Total dapps deployed on a blockchain. |
| Shared bridges | Number of bridges shared with Terra. |
| Shared nonbridges | Number of non-bridge dapps deployed both on Terra and a blockchain. |

^171

able on the Terra network. We theorize that Terra’s collapse would disproportionately hurt
blockchain networks whose assets’ use value was in part derived from their usability on the
Terra network.

We measure the relative programmable use value of a blockchain by its share of TVL
in comparison to other programmable blockchains and build an intuitive model to test if a
blockchain’s programmable use value outperforms or underperforms against other blockchains’
programmable environments in the wake of Terra’s collapse.

4 Data

Data was sourced from DeFi Llama, an open-source data provider which collects and aggregates blockchain data from major blockchains across several metrics used in our analysis.
We used DeFi Llama to construct a data set with different blockchain networks (for example, Ethereum or Solana) as observations associated with several variables. Table2displays
summary statistics for metrics used in our regression analysis. After compiling data on all
tracked blockchains listed on DeFi Llama’s website, we subsetted for only blockchains who
registered a TVL over 0 as of May 7, the day before Terra’s native tokens collapsed in value,
which left 101 blockchains. In our analysis, we also trim the sample to exclude blockchain

\mathrm{a g-}

---

Table 2: Sample statistics

| Variable | N | Mean | Med | Min | Max |
| --- | --- | --- | --- | --- | --- |
| Bridges as of 2022/05/07 | 44 | 3.50 | 1.00 | 0.00 | 29.00 |
| Positive share change (indicator) as of 2022/05/15 | 44 | 0.52 | 1.00 | 0.00 | 1.00 |
| Shared bridges as of 2022/05/07 | 44 | 0.66 | 0.00 | 0.00 | 3.00 |
| Shared dApps as of 2022/05/07 | 44 | 0.82 | 0.00 | 0.00 | 6.00 |
| Shared nonbridges as of 2022/05/07 | 44 | 0.16 | 0.00 | 0.00 | 3.00 |
| TVL as of 2022/05/07 | 44 | 2650.06 | 284.44 | 61.06 | 68840.87 |
| TVL as of 2022/05/15 | 44 | 1806.02 | 180.15 | 34.25 | 47142.60 |
| TVL share as of 2022/05/07 | 44 | 0.02 | 0.00 | 0.00 | 0.58 |
| TVL share as of 2022/05/15 | 44 | 0.02 | 0.00 | 0.00 | 0.59 |
| TVL share change as of 2022/05/15 | 44 | 0.00 | 0.00 | -0.01 | 0.01 |
| dApps as of 2022/05/07 | 44 | 41.48 | 9.50 | 0.00 | 394.00 |

networks whose market share of TVL was below 0.05 percent to exclude particularly small
blockchain networks, leaving 44 remaining blockchains. Complementary table1displays
definitions for each of the variables.

5 Empirical Analysis: Ripple Effects from the Terra
Collapse

Following our theoretical approach defining DeFi as a set of blockchains competing for investment, differentiated by key characteristics such as available dapps and assets, and interlinked
in particular by bridges, our empirical analysis traces the uneven effects of Terra’s collapse
across different blockchain networks in DeFi to tease out predictive metrics and possible
mechanisms for these distortions.

---

Figure 4: Evolution of TVL distribution across chains

trimmed sample of blockchains in DeFi, with boxes representing the 25th and 75th percent
quartile and vertical lines displaying the absolute range. Market shrinkage continued through
the end of June before appearing to plateau.

Table 3: Characteristics of expanding/contracting chains overtime

| Date | TVL(Contr) | TVL(Exp) | Dapps(Contr) | Dapps(Exp) | Bridges(Contr) | Bridges(Exp) |
| --- | --- | --- | --- | --- | --- | --- |
| 2022-05-15 | 420.41 | 2166.98 | 24.68 | 40.75 | 0.48 | 0.56 |
| 2022-06-01 | 428.65 | 2698.36 | 30.53 | 41.64 | 0.56 | 0.48 |
| 2022-06-15 | 310.31 | 1576.37 | 35.77 | 36.42 | 0.69 | 0.39 |
| 2022-07-01 | 1313.38 | 512.83 | 48.38 | 25.11 | 0.79 | 0.25 |
| 2022-07-15 | 1268.73 | 599.01 | 49.32 | 25.23 | 0.77 | 0.23 |
| 2022-08-01 | 1490.21 | 597.56 | 49.94 | 26.19 | 0.81 | 0.27 |
| 2022-08-15 | 307.46 | 2241.90 | 35.24 | 46.75 | 0.67 | 0.50 |

As the market adjusted following Terra’s collapse, the effect was not felt equally across
all blockchains. Table3displays descriptive characteristics of examined blockchains, splitting blockchains into ”contracting” and ”expanding” chains,

As the market adjusted following Terra’s collapse, the effect was not felt equally across
Table3displays descriptive characteristics of examined blockchains, splitting blockchains into ”contracting” and ”expanding” chains, based on whether or not a

ting blockchains into ”contracting” and ”expanding” chains, based on whether or not a
blockchain’s market share increased between May 7 and the observed date. On first glance,

blockchain’s market share increased between May 7 and the observed date. On first glance,
this suggests that expanding chains were initially bigger (in terms of TVL) than contract-

blockchain’s market share increased between May 7 and the observed date. On first glance,
this suggests that expanding chains were initially bigger (in terms of TVL) than contract-

ing ones, before that trend flips in early July (and remains consistent until flipping back in mid-August). In terms of bridges shared with Terra, until mid-July, expanding chains increasingly diverged from contracting bridges as expanding chains tended to have fewer shared bridges than contracting chains. A similar trend is observed in overall numbers of dapps deployed on blockchains. These descriptive statistics provide an overview of the potential factors which might have affected the nature of effects from Terra’s collapse spilling over to other blockchains. We interrogate these effects in further detail in the following sections.

# 5.2 Bridges and Market Share Distortions

As noted earlier, bridges facilitate the transfer of crypto-assets from a native network to a non-native network. This introduces new crypto-assets for use in a blockchain’s pro- grammable environment. Bridges must be deployed on two blockchain networks to lock up collateral tokens on one blockchain network and issue wrapped tokens on the other. Blockchain networks whose programmable use value is in part derived from the integration of wUST and wLUNA might experience a greater decrease in programmable use value rela- tive to those who are not as integrated with wUST and wLUNA following Terra’s collapse. In the opposite direction, bridges allow a blockchain network’s assets to be used in the Terra Network’s programmable environment, thus providing an additional driver of demand for that asset. Terra’s collapse would thus disproportionately hurt the blockchains whose assets’ demand was in part driven by their use on the Terra network. The greater the number of bridges supporting the transfer of assets to and from Terra, the more widely these wrapped assets can be integrated into dapps, thus suggesting that more shared bridges would be associated with a greater effect. We first test this prediction using a probit model predicting the probability of the outcome variable Positive share change taking on a value of ”0” or ”1.” As described earlier, isPos indicates whether a blockchain network’s share of TVL across non-Terra blockchain networks has increased or decreased as of a specified date in comparison to May 7, the day before

---

Terra’s collapse. We control for blockchain size by including the blockchain’s initial share of market-wide TVL and number of deployed dapps as of May 7. Models follow the below formula:

P (Positive share change = 1) = Φ[α + β1(Shared bridges) + β2(dapps) + β3(TVL Share)]

We ran the above regression on data assessing the change in TVL market share between May 7, the day before the Terra collapse, and July 1, six weeks after the value of Terra’s assets had fully crashed. We observed strongest effects on July 1; time effects are tested in a later section. Table4displays the results of the regressions in marginal effects. The sample includes all blockchains with a TVL share greater than 0.05 percent. As noted before, the TVL of a blockchain excludes the TVL associated with bridges deployed on the blockchain. 9 This avoids having to determine if the assets locked on one side of a bridge should be counted towards the originating blockchain or the destination blockchain of the ”bridged” assets. This also means that the right hand side variable Shared bridges, which captures the ease by which assets are made available across blockchains, does not directly feed into the left-hand-side variable, comprised of value locked in non-bridge dapps. Models 1 through 3 only measure the association between a single right hand side variable and Positive market share, while Models 4-6 control for a blockchain’s share of TVL (as a measure of its size) and/or number of deployed dapps (as an indication of the variety of dapps available on the blockchain network). The coefficients on Shared bridges are statistically significant at the p<0.05 level whether or not control factors are included. With control variables included, an additional bridge shared with the Terra network was associated with approximately a 40% decrease in the likelihood of the blockchain network’s TVL share increasing over the time period between See DeFi Llama’s documentation here: [https://docs.llama.fi/list-your-project/readme](https://docs.llama.fi/list-your-project/readme).

---

Table 4: The effect of being linked to Terra (probability of losing market share)

|  | Model 1 | Model 2 | Model 3 | Model 4 | Model 5 | Model 6 |
| --- | --- | --- | --- | --- | --- | --- |
| Shared bridges as of 2022/05/07 | -0.18**(0.09) |  |  | -0.17*(0.10) | -0.38**(0.17) | -0.56**(0.22) |
| Deployed dApps as of 2022/05/07 |  | -0.00(0.00) |  |  | 0.00(0.00) | 0.01**(0.00) |
| TVL as of 2022/05/07 |  |  | -0.00(0.00) | -0.00(0.00) |  | -0.00(0.00) |
| Number of observations | 44 | 44 | 44 | 44 | 44 | 44 |
| Log likelihood | -28.15 | -29.83 | -29.88 | -28.15 | -27.12 | -25.74 |
| Deviance | 56.30 | 59.67 | 59.77 | 56.30 | 54.24 | 51.48 |
| AIC | 60.30 | 63.67 | 63.77 | 62.30 | 60.24 | 59.48 |
| BIC | 63.87 | 67.24 | 67.33 | 67.66 | 65.59 | 66.62 |

Note: Dependent variable: 1 if market share expanded, 0 otherwise. Sample consists of blockchains
with TVL share above 0.05 percent (cumulative 99 percent).

Table 5: Weak and strong links with Terra (probability of losing market share)

|  | Model 1 | Model 2 | Model 3 | Model 4 | Model 5 | Model 6 |
| --- | --- | --- | --- | --- | --- | --- |
| Shared bridges=1 as of2022/05/07 | -0.19(0.17) |  |  | -0.19(0.17) | -0.27*(0.16) | -0.40***(0.11) |
| Shared bridges&gt;1 as of2022/05/07 | -0.43***(0.15) |  |  | -0.43**(0.17) | -0.66***(0.12) | -0.84***(0.12) |
| Deployed dApps as of2022/05/07 |  | -0.00(0.00) |  |  | 0.00(0.00) | 0.01**(0.01) |
| TVL as of2022/05/07 |  |  | -0.00(0.00) | -0.00(0.00) |  | -0.00**(0.00) |
| Number of observations | 44 | 44 | 44 | 44 | 44 | 44 |
| Log likelihood | -27.85 | -29.83 | -29.88 | -27.85 | -26.71 | -24.36 |
| Deviance | 55.70 | 59.67 | 59.77 | 55.70 | 53.41 | 48.73 |
| AIC | 61.70 | 63.67 | 63.77 | 63.70 | 61.41 | 58.73 |
| BIC | 67.05 | 67.24 | 67.33 | 70.84 | 68.55 | 67.65 |

Note: Dependent variable: 1 if market share expanded, 0 otherwise. Sample consists of blockchains
with TVL share above 0.05 percent (cumulative 99 percent).

May 7 and July 1, statistically significant at the p<0.01 level. Additionally, when including
all variables, the number of deployed dapps was associated with a positive effect on the
outcome variable, statistically significant at the p<0.01 level. The results suggest that
bridges are, in fact, associated with an increased likelihood of a blockchain network’s TVL
share decreasing even when controlling for both size and the number of dapps deployed on
the blockchain network.

---

bridge (with a maximum of 3). Table5displays the results of these regressions, otherwise sharing the same six models as Table4. Splitting the categories of shared bridges into an additional level produces similar results, with coefficients on shared bridges = 1 being around half that of coefficients on shared bridges > 1. Results provide greater evidence of a consistent effect, in that additional shared bridges with Terra was associated with a greater magnitude of negative effect.

# 5.3 Bridges and dapps

Boissay et al.(2022) argue that shared dapps indicate blockchain networks providing similar services, and users may move between blockchain networks based on distinguishing features of the blockchain, citing transaction costs and speed as possible important such features. In combination with bridges, dapps deployed on multiple blockchains may also offer greater compatibility between assets accounted for on different blockchains. Such a dynamic does not offer obvious predictions for the nature of an effect post-Terra’s collapse: a substitution effect inducing movement towards blockchains offering the same dapps but on a different network might exist, but shared dapps whose use value was in part dependent on the availability of Terra’s assets may have hurt a blockchain network. Nonetheless, we perform the same regression models and include the variable Shared dapps noting the number of shared non- bridge dapps between a blockchain and Terra. Table6displays the results of the regression. The coefficient on shared dapps is negative but not statistically significant in both models where it is included. While our analysis does not offer any conclusive insights about the nature of risk propagation based on non- bridge shared dapps, it provides further evidence supporting the importance of bridges in interlinking blockchains.

---

Table 6: Shared bridges vs shared dApps

|  | Model 1 | Model 2 | Model 3 |
| --- | --- | --- | --- |
| Shared bridges=1 as of2022/05/07 |  | -0.40***(0.11) | -0.35***(0.12) |
| Shared bridges&gt;1 as of2022/05/07 |  | -0.84***(0.12) | -0.88***(0.11) |
| Deployed dApps as of2022/05/07 | -0.00(0.00) | 0.01**(0.01) | 0.01***(0.00) |
| Shared dApps as of2022/05/07 | -0.32(0.31) |  | -0.42(0.36) |
| TVL as of2022/05/07 | 0.00(0.00) | -0.00**(0.00) | -0.00(0.00) |
| Number of observations | 44 | 44 | 44 |
| Log likelihood | -29.15 | -24.36 | -23.80 |
| Deviance | 58.30 | 48.73 | 47.60 |
| AIC | 66.30 | 58.73 | 59.60 |
| BIC | 73.44 | 67.65 | 70.31 |

Note: Shared bridges is a subset of the shared dApps, i.e. those dApps that are classified as bridges.
The variable shared dApps excludes shared bridges. Left hand side variable 1 if market share expanded
and 0 otherwise. Sample with blockchains with TVLs share above 0.05 percent (cumulative 99 percent).

5.4 Time profile

As indicated by the descriptive statistics, market-wide decreases in TVL followed the collapse of Terra. Our analysis interrogates the possible characteristics of blockchain networks
which may have distorted the distribution of this market-wide impact. With respect to
bridges, the collapse of a blockchain on one side of the bridge (the originating blockchain)
has the immediate effect of reducing the value of all addresses holding bridged assets on the
destination blockchain. However, we seek instead to measure the effect that such a collapse
in bridged assets has on the secondary blockchain’s programmable environment.
The TVL of dapps is dependent on two factors: the number of tokens deposited multi-

---

Table 7: Time profile of the effect of Terra’s collapse

|  | May 15 | June 01 | June 15 | July 01 | July 15 | August 01 |
| --- | --- | --- | --- | --- | --- | --- |
| Shared bridges=1 as of2022/05/07 | 0.10(0.18) | 0.02(0.20) | -0.13(0.20) | -0.40***(0.11) | -0.34***(0.13) | -0.36***(0.11) |
| Shared bridges&gt;1 as of2022/05/07 | -0.28(0.40) | -0.27(0.38) | -0.47(0.35) | -0.84***(0.12) | -0.65***(0.15) | -0.72***(0.15) |
| Deployed dApps as of2022/05/07 | 0.00(0.00) | -0.00(0.00) | -0.00(0.00) | 0.01**(0.01) | 0.01(0.00) | 0.01**(0.00) |
| TVL as of2022/05/07 | 0.00(0.00) | 0.00(0.00) | 0.00(0.00) | -0.00**(0.00) | -0.00(0.00) | -0.00*(0.00) |
| Number of observations | 44 | 44 | 44 | 44 | 44 | 44 |
| Log likelihood | -28.95 | -28.07 | -28.17 | -24.36 | -26.03 | -25.08 |
| Deviance | 57.91 | 56.13 | 56.33 | 48.73 | 52.05 | 50.16 |
| AIC | 67.91 | 66.13 | 66.33 | 58.73 | 62.05 | 60.16 |
| BIC | 76.83 | 75.05 | 75.25 | 67.65 | 70.97 | 69.08 |

Note: Dependent variable = 1 if market share expanded, 0 otherwise. Sample with blockchains with
TVLs share above 0.05 percent (cumulative 99 percent).

derived from bridged assets (wUST or wLUNA) already committed to dapps on a blockchain.
However, disinvestment from dapps due to the changes in available assets would likely take
longer. Additionally, bridges facilitated the transfer of assets from other blockchains onto
Terra, and demand for these assets may very well have been driven in part by their use on
the Terra blockchain. It may take time for the reduced desirability of an asset due to no
longer being available on the Terra blockchain to be reflected both in its price and its use in
dapps on its native blockchain.

Thus, we theorize the full market reaction to post-Terra blockchain programmable environments would likely take some period of time. Table7displays the results of the model
run on the first and the 15th of each month following Terra’s collapse until August 1. We
see that in the first month and a half, despite market-wide changes, factors such as size,
available dapps, and shared bridges do not have a statistically significant effect. However,
over those three weeks, the coefficients on shared bridges = 1 and shared bridges > 1 do
trend downwards. On July 1, coefficients on shared bridges, deployed dapps, and TVL are
statistically significant at the p < 0.001 level as noted earlier in Table4. The coefficients on
shared bridges remain statistically significant, but are lower in magnitude on July 15 and
August 01.

---

# 6 Conclusion

As the literature still wrestles with the fundamental economics underlying individual blockchains and cryptocurrencies, the applications of blockchain technology have continued to expand rapidly. Programmable blockchains proliferate, onto which smart contracts can be readily deployed. These smart contracts facilitate decentralized applications offering numerous fi- nancial products and services. Bridges allow users of programmable blockchains to engage with assets previously only available on their native blockchains. DeFi has grown into an ecosystem of thousands of dapps deployed on dozens of blockchain networks handling tens of billions of dollars’ worth of crypto-assets. Yet, the speed at which the technologies and markets in DeFi have grown means that the literature has yet to reveal much at all about this new financial ecosystem. And, until May of 2022, DeFi might not have experienced enough stress and turmoil to present useful analytical questions or to distract from the traditional crypto world. In May 2022, the second-biggest blockchain network in DeFi, Terra, collapsed over the course of a week. Such major collapses in financial ecosystems can allow for an examination of how financial mechanisms underpinning these financial ecosystems work and fail and how effects of the collapse propagate, providing new insights the structure of the ecosystem. Our paper traces the financial mechanisms underpinning the Terra Network as its position within DeFi evolved, analyzing the incentives of relevant participants as Terra grew more and more interconnected with other blockchain networks. This analysis provides the foundation for our theoretical insights, which distinguish the economics of programmable blockchain environments from that of non-programmable blockchain accounting ledgers. We argue that DeFi is structured so as to offer consumers different blockchain networks as competing choices differentiated by several key characteristics, including availability of different assets for use in varied dapps. Bridges, by expanding the availability of assets in otherwise disconnected programmable blockchain environments, serve to uniquely interlink different blockchains in DeFi.

---

Our empirical analysis tests several implications of our theoretical insights, predicting
that sharing a greater number of bridges (out of a possible 3 deployed on Terra at the
time of its collapse) with the Terra Network disproportionately hurt the performance of a
programmable blockchain relative to other programmable blockchains. When controlling for
fundamental characteristics, we also predict that such an effect would take time. We also
predict that this effect would be distinct from a more general effect of sharing non-bridge
dapps, whichBoissay et al.(2022) find is associated with higher price correlations.

Results from our empirical analysis confirm our four predictions, finding that among
the 44 blockchains in our sample, each additional bridge was associated with a 56 percent
decrease in likelihood of relative TVL market share growing 6 weeks after the Terra collapse.
This effect was time-bound and held true when controlling for the size of the blockchain
network, reputational costs associated with stablecoins, and general effects of sharing nonbridge dapps.

These findings suggest an approach to analyzing DeFi not solely for the crypto-assets they
might popularize, but for the structures of the DeFi ecosystem – as competing programmable
environments differentiated by key characteristics and interconnected by bridges. The technical risks associated with bridges, as the subject of many high-profile hacks and thefts, are
well-known in DeFi. Yet, absent an economic analysis of the financial mechanisms which interconnect blockchain networks in DeFi, the literature offers little insight into the structural
risks associated with cross-chain applications such as bridges. Our empirical analysis offers
support for the idea that, even if technically sound, there are fundamental economic risks
associated with the kinds of ”cross-chain ecosystems” touted by the industry as the future
10
of DeFi.

Our findings also give rise to several questions which remain unconsidered in the literature. How long does it take for risks to propagate throughout DeFi? What other financial
mechanisms interconnect blockchain networks in DeFi? How do we understand a financial
10
For example, see anarticlepromoted by Consensys touting the ”cross-chain” future of DeFi.

10
For example, see anarticlepromoted by Consensys touting the ”cross-chain” future of DeFi.

---

ecosystem in which crypto-assets serve multiple purposes, both for securing networks of interconnected programmable environments and as assets to be traded? As the DeFi world changes, from advancements in sharding to the proliferation of layered blockchains interconnected in new ways, expanding on our approach by taking into consid- eration the financial mechanisms and incentives of relative actors will allow researchers to understand the economics of this ecosystem more fully.

# References

Azar, Pablo D, Garth Baughman, Francesca Carapella, Jacob Gerszten, Arazi Lubis, Juan Pablo Perez-Sangimino, Chiara Scotti, Nathan Swem, Alexandros Vardoulakis, and David E Rappoport W, “The Financial Stability Implications of Digital Assets,” FRB of New York Staff Report, 2022.

Boissay, Frederic, Giulio Cornelli, Sebastian Doerr, Jon Frost et al., “Blockchain scalability and the fragmentation of crypto,” Technical Report, Bank for International Settlements 2022.

Bouri, Elie, Tareq Saeed, Xuan Vinh Vo, and David Roubaud, “Quantile con- nectedness in the cryptocurrency market,” Journal of International Financial Markets, Institutions and Money, 2021, 71, 101302.

Briola, Antonio, David Vidal-Tom´as, Yuanrong Wang, and Tomaso Aste, “Anatomy of a Stablecoin’s failure: The Terra-Luna case,” Finance Research Letters, 2023, 51, 103358.

Carapella, Francesca, Edward Dumas, Jacob Gerszten, Nathan Swem, and Larry Wall, “Decentralized Finance (DeFi): Transformative Potential & Associated Risks,”

2022.

---

Corbet, Shaen, John W Goodell, and Samet G¨unay, “What drives DeFi prices? Investigating the effects of investor attention,” Finance Research Letters, 2022, 48, 102883.

d’Avernas, Adrien, Vincent Maurin, and Quentin Vandeweyer, “Can Stablecoins be Stable?,” University of Chicago, Becker Friedman Institute for Economics Working Paper, 2022, (2022-131).

## DefiLlama, “Dashboard.”

Egorov, Michael, “StableSwap-efficient mechanism for Stablecoin liquidity,” Retrieved Feb, 2019, 24, 2021.

Gudgeon, Lewis, Daniel Perez, Dominik Harz, Benjamin Livshits, and Arthur Gervais, “The decentralized financial crisis,” in “2020 Crypto Valley Conference on Blockchain Technology (CVCBT)” IEEE 2020, pp. 1–15.

Ji, Qiang, Elie Bouri, Chi Keung Marco Lau, and David Roubaud, “Dynamic con- nectedness and integration in cryptocurrency markets,” International Review of Financial Analysis, 2019, 63, 257–272.

Karim, Sitara, Brian M Lucey, Muhammad Abubakr Naeem, and Gazi Salah Uddin, “Examining the interrelatedness of NFTs, DeFi tokens and cryptocurrencies,” Finance Research Letters, 2022, p. 102696.

Kereiakes, Evan, Marco Di Maggio Do Kwon, and Nicholas Platias, “Terra money: Stability and adoption,” 2019.

Leshno, Jacob D and Philipp Strack, “Bitcoin: An axiomatic approach and an impos- sibility theorem,” American Economic Review: Insights, 2020, 2 (3), 269–86.

Liu, Jiageng, Igor Makarov, and Antoinette Schoar, “Anatomy of a Run: The Terra Luna Crash,” Technical Report, National Bureau of Economic Research 2023.

---

Lyons, Richard K and Ganesh Viswanath-Natraj, “What keeps stablecoins stable?,” Journal of International Money and Finance, 2023, 131, 102777.

Makarov, Igor and Antoinette Schoar, “Cryptocurrencies and Decentralized Finance (DeFi),” Technical Report, National Bureau of Economic Research 2022.

Maouchi, Youcef, Lanouar Charfeddine, and Ghassen El Montasser, “Understand- ing digital bubbles amidst the COVID-19 pandemic: Evidence from DeFi and NFTs,” Finance Research Letters, 2022, 47, 102584.

Messari, “Crypto Research, Data, and Tools: Historical Data.”

Sch¨ar, Fabian, “Decentralized finance: On blockchain-and smart contract-based financial markets,” FRB of St. Louis Review, 2021.

Uhlig, Harald, “A Luna-tic Stablecoin Crash,” Technical Report, National Bureau of Eco- nomic Research 2022.

Yaga, Dylan, Peter Mell, Nik Roby, and Karen Scarfone, “Blockchain technology overview,” arXiv preprint arXiv:1906.11078, 2019.

Yousaf, Imran and Larisa Yarovaya, “Static and dynamic connectedness between NFTs, Defi and other assets: Portfolio implication,” Global Finance Journal, 2022, 53, 100719.