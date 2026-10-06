# buy sui: how to buy SUI on Gate, what it actually costs, and where to keep it

Search "buy sui" and you get a wall of near-identical pages telling you to "sign up, verify, deposit, trade." True, and useless. The parts that actually cost you money or lose you coins get skipped: which payment route eats 3% versus 0.1%, what a market order does to your entry price on a thin book, whether SUI stays on an exchange or needs a wallet, and why most "buy SUI" guides never mention that SUI isn't an ERC-20 token.

So this walks through the whole decision, using Gate as the venue since that's where SUI has been listed since its 2023 launch. Steps, fees, payment trade-offs, storage, and the parts that go wrong.

## What you're actually buying

SUI is the native token of Sui, a layer-1 blockchain built by Mysten Labs. Two things make it different from the average altcoin you'd pick up on a whim.

First, the programming model. Sui runs on Move and treats data as objects rather than one giant shared state, which lets independent transactions execute in parallel instead of queuing single-file. That's the architectural bet behind the "fast chain" label.

Second, the supply schedule matters more than the marketing. SUI has a max supply of 10 billion tokens, with roughly 4 billion circulating as of the latest public figures. That gap isn't theoretical. It's future emissions, unlocks and staking rewards that can pressure price. Any honest answer to "should I buy SUI" has to start there.

Price context, meanwhile, is not flattering. SUI set its all-time high around $5.31–$5.35 in early January 2025 and its all-time low near $0.36 in October 2023. Since the peak, it has spent most of its time well below it, with year-over-year performance down sharply depending on which date window you check. Live quotes move constantly, and different trackers disagree by cents at any given moment, so check the exchange order book rather than a blog table.

## Four ways to buy SUI, and who each one suits

There isn't one "buy SUI" method. There are four, with genuinely different costs.

| Route | Typical cost | Speed | Custody | Best for |
| --- | --- | --- | --- | --- |
| Centralized exchange spot (SUI/USDT) | 0.1% maker/taker at the base tier, less with GT deduction | Seconds after funding | Exchange holds the keys | Most people, most of the time |
| Card or quick-buy | ~1–5% spread/fee | Minutes | Exchange | Small first purchase, no patience |
| C2C / P2P | Platform fee often 0, seller spread applies | Minutes to an hour | Exchange escrow | Regions where cards get declined |
| DEX on Sui (Cetus, BlueMove, Turbos and others) | Gas plus liquidity spread | Seconds | Your own wallet | On-chain users who already hold SUI-ecosystem assets |

The card route is the one that quietly costs the most. You can be paying 1–5% before the price has done anything, which on a $500 purchase is $5 to $25 gone. For a small test buy that's acceptable. For anything sizeable, a bank transfer or a crypto deposit into spot trading is dramatically cheaper.

The DEX route sounds cheaper and often is, but it only makes sense if you already have a Sui wallet and something to swap. Bridging from another chain adds cost and a new failure mode, and if you buy the wrong contract address you've simply donated your money. For a first SUI purchase, a centralized order book with a visible SUI/USDT pair is the lower-risk option.

## Buying SUI on Gate, step by step

### 1. Create the account

Registration takes a couple of minutes: email or phone number, a strong password, and 2FA switched on immediately rather than after your first deposit. Registration also triggers the new-user reward tasks, which I'll get to. 👉 [Create a Gate account and start the SUI tasks](https://bit.ly/GateVIP)

### 2. Pass KYC

Identity verification with an ID document and a liveness check. It typically clears anywhere from a few minutes to a day or two. Without it, deposits and trading limits stay low and withdrawals are restricted, so do it first instead of discovering it mid-trade. Regions listed as restricted — the US, Canada, Iran and Cuba appear on Gate's own restricted list — can't use the service at all, so check before you spend time on setup.

### 3. Fund the account

Four main paths, and this is where you choose your cost:

- **Crypto deposit.** Send USDT, USDC, BTC or ETH from another exchange or wallet. Cheapest option. Confirm the network matches, and always test with a small amount first.
- **Bank transfer** (SEPA, SWIFT, FPS and similar). Costs vary by bank and are sometimes near zero, but settlement can take one to three business days.
- **Card or Apple Pay / Google Pay.** Instant, no pre-funding, roughly 1–5% in fees.
- **C2C / P2P.** You trade directly with another user under platform escrow. The platform fee is often zero; the seller sets the price, so compare quotes instead of taking the first one.

There's also GateCode, an internal transfer between Gate users, which is free and needs no address. Useful if a friend is topping you up.

### 4. Place the SUI order

Head to spot trading and find SUI/USDT. Search "SUI" — do not type a contract address into the spot search bar and assume you're on the right asset.

Then pick your order type:

- **Market order:** fills immediately at whatever the book offers. Simple, but on a thinner pair you can pay more than the last traded price.
- **Limit order:** you name your price. If the market doesn't come to you, nothing happens. You also pay maker fees rather than taker fees at some tiers, and you avoid being the one who eats the spread.

If you're buying a meaningful amount, splitting into two or three limit orders usually beats one market order. For a $50 starter buy, nobody cares. 👉 [Set up an account and place your first SUI order](https://bit.ly/GateVIP)

## The fee structure, all tiers

Gate runs a tiered spot fee schedule from VIP0 to VIP16. The base tier is 0.1% maker and 0.1% taker; paying fees in the platform's own GT token drops that to 0.09%/0.09%. Levels can be reached three ways — 30-day trading volume, 14-day average GT holdings, or total account asset value — and whichever qualifies you first applies.

| VIP level | 30-day volume (USD) | VIP rate (Maker/Taker) | GT payment rate (Maker/Taker) |
| --- | --- | --- | --- |
| VIP 0 | 0 | 0.1% / 0.1% | 0.09% / 0.09% |
| VIP 1 | 60,000 | 0.099% / 0.099% | 0.089% / 0.089% |
| VIP 2 | 120,000 | 0.098% / 0.098% | 0.088% / 0.088% |
| VIP 3 | 240,000 | 0.097% / 0.097% | 0.087% / 0.087% |
| VIP 4 | 500,000 | 0.095% / 0.096% | 0.086% / 0.086% |
| VIP 5 | 1,000,000 | 0.09% / 0.095% | 0.081% / 0.085% |
| VIP 6 | 3,000,000 | 0.085% / 0.09% | 0.076% / 0.081% |
| VIP 7 | 8,000,000 | 0.08% / 0.085% | 0.07% / 0.076% |
| VIP 8 | 20,000,000 | 0.075% / 0.08% | 0.06% / 0.072% |
| VIP 9 | 50,000,000 | 0.07% / 0.075% | 0.05% / 0.068% |
| VIP 10 | 100,000,000 | 0.04% / 0.058% | — |
| VIP 11 | 120,000,000 | 0.03% / 0.045% | — |
| VIP 12 | 240,000,000 | 0.02% / 0.037% | — |
| VIP 13 | 440,000,000 | 0.01% / 0.03% | — |
| VIP 14 | 800,000,000 | 0.008% / 0.023% | — |
| VIP 15 | 1,600,000,000 | 0% / 0.02% | — |
| VIP 16 | 3,000,000,000 | 0% / 0.0175% | — |

For a normal retail buyer, VIP0 through VIP1 is the realistic range, which means the honest headline fee on a SUI purchase is 0.1% taker — 50 cents on a $500 buy. The GT deduction path is the cheapest thing available to a small account: hold a little GT, enable GT deduction, and your 0.1% becomes 0.09%. If your GT balance runs out, the system silently reverts to the standard tier, which is why people occasionally see a fee that looks wrong.

Higher tiers exist mostly for market makers and funds. The GT-holding and asset-value routes are gentler than the volume route: VIP1 needs either 50 GT held over 14 days or $2,000 in account value; VIP13 can be reached with 800,000 GT or $16,000,000 in assets. Nobody buying a few hundred dollars of SUI needs to plan around this.

Futures are a different schedule and an entirely different risk profile. If you're searching "buy sui" to hold the token, the spot table above is the one that applies.

Fee rates do change with market conditions — the tables above come from Gate's own fee documentation, and the live page is the final word. 👉 [Check current fees on your own account](https://bit.ly/GateVIP)

## New-user rewards: what's real and what's got fine print

Gate's rewards hub breaks new-user bonuses into tasks: register, complete identity verification, make a first deposit (the threshold is small, around 10 USDT on the English version), place a first spot or futures trade above a similar minimum, download the app. Each completed task unlocks a voucher or small bonus. On top of that sits an advanced trading mission with tiers tied to net deposit and cumulative trading volume, which can reach five figures in USDT for people actually moving volume.

Two honest caveats. The headline numbers vary by region and get revised frequently — the same rewards page shows different totals across language versions, so treat any figure you see on a blog as indicative, not contractual. And most of these bonuses arrive as vouchers or trial funds with unlock conditions, not as withdrawable cash. Read the task rules before you deposit more than you planned to.

The referral side runs separately: Gate's referral system pays a rebate on the trading fees your invitees generate, advertised up to 40%, and it also has a task-based reward pool on top. That's a reason to register through a referral link rather than going direct — the person who referred you gets a cut of fees, and you often get access to the same task campaigns either way.

## Where to keep SUI, and whether to stake it

Leaving SUI on an exchange is fine for a position you trade. It is not fine as a long-term vault, for the obvious reason: the exchange holds the keys. Withdraw to a wallet you control when the amount matters to you.

The choices are unglamorous:

- **Exchange wallet.** Maximum convenience, minimum control. Suitable for active trading and small balances.
- **Sui Wallet or another Sui-native wallet.** You hold the keys. Required if you want to interact with on-chain apps, and needed for native staking by delegating to a validator.
- **Hardware wallet.** The sensible home for a large position, paired with a Sui-compatible interface.

Withdrawal is the step where people lose money most often. SUI moves on the Sui network, not Ethereum. Send it to an address on the wrong chain and it's gone. Copy the address, verify the first and last few characters, and send a small test transfer before moving the whole balance.

On yield: Gate offers SUI savings products inside its Earn section, which pay without any wallet setup — a low-effort option for someone who wants to accumulate SUI and doesn't want to run a validator delegation. Going to native staking by delegating to a Sui validator generally means you keep custody, and rates move with network conditions. Either way, ask what happens during unbonding periods before you lock anything up. Liquidity that takes days to return is not the same as liquidity.

## The risks worth naming before you click buy

SUI is a high-beta asset in a sector that already moves fast. Its drawdown from the January 2025 peak has been severe, and the remainder of its 10 billion token supply is still being distributed. A token with a supply schedule like that behaves differently from one with a fixed float.

Practical risks specific to buying it through any centralized exchange:

- **Verification gatekeeping.** No KYC, no meaningful withdrawal limits. There's no workaround, and attempts at one are usually how people get scammed.
- **Regional restrictions.** Gate restricts or prohibits service in certain jurisdictions, including the US and Canada. Confirm your own eligibility.
- **Phishing.** Typing the domain wrong, or clicking an ad, is a far more common way to lose crypto than any technical exploit. Bookmark the exchange and use 2FA on withdrawal separately from 2FA on login.
- **Exchange risk versus self-custody risk.** Holding on an exchange trades the risk of losing your keys for the risk of losing access to the platform. Neither is zero.

None of this is investment advice. It's the list of things that determines whether your SUI purchase ends the way you intended.

## Quick answers

**What's the cheapest way to buy SUI on Gate?** Deposit USDT over a low-cost network, then place a limit order on the SUI/USDT spot pair with GT deduction enabled. Around 0.09–0.1% all in, plus your deposit network fee.

**Can I buy SUI with a credit card?** Yes, at roughly 1–5% in fees. Fine for a small first buy, expensive at scale.

**Is there a minimum purchase?** The pair trades in small increments, so the practical limit is low. Reward tasks have their own minimums, typically around 10 USDT for the first deposit and first trade.

**How long does it take?** Account setup is minutes. KYC ranges from minutes to a day or two. Card and instant bank transfers land in minutes; standard bank transfers take one to three business days.

**Why does my SUI show up as SUI and not a wrapped version?** Because you bought the native asset on its own chain. Wrapped SUI exists on other networks for bridging purposes — different thing, different contract.

The actual answer to "buy sui" is boring and specific: verify your eligibility, keep KYC and 2FA sorted, fund with the cheapest method you can, buy with a limit order on a real SUI/USDT book, and get anything you're holding long term off the exchange. Do those five things and you've avoided almost every expensive mistake that shows up in the search results. 👉 [Open a Gate account and start with SUI](https://bit.ly/GateVIP)
