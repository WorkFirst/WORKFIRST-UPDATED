# WORKFIRST-UPDATED

# Work-First
ETH redistribution token


Whitepaper



Introduction: 

The WorkFirst Whitepaper aims to educate readers on our vision, strategy and roadmap. Below we illustrate in detail our unique redistribution mechanism. 

It's an engineering achievement unheard of until Tiki in the ETH ecosystem. We are happy to improve upon their protocol and are excited to showcase the new use cases that this will enable.

Safemoon was the one to bring awareness around RFI and HODL rewards. WorkFirst will carry the innovation forward. We will share our vision with the world: the improved auto-claim ETH reward mechanism.





Right into it:

WorkFirst is the next evolution of a yield-generating contract on Arbitrum: you get rewarded in ETH instead of tokens. 


2% ETH is redistributed to holders

•

4% is used to fuel the liquidity pool exchange growth during buy/sell







In order to fully understand the ETH redistribution, we need to educate you on the reflection concept:



Classic redistribution

This is a concept that was popularized by Safemoon. The mechanism incentivizes token holders to hold in order to earn dividends from the transactions (buys and sells). Redistribution is based on percentage (in the contract), current token balance and number of holders. 

TL; DR: You receive more tokens manually.



ETH redistribution

Popularized by HODL and GhostFace, a transaction fee is applied to every single buy /sell order, tokens are then swapped in realtime for BNB and added to a POOL (similar to how liquidity pools work). Holders can then go to a website and manually claim the BNB earned at specific time (daily / weekly / etc..). The BNB they can collect are based on their token holdings % and the current pool size. 

TL;DR: You hold, then go to the website and request your ETH.



WorkFirst redistribution

Claiming manually is unintuitive for a couple of reason but, essential.

•

Need to connect your wallet manually to the website

•

Time constraints as you need to return frequently to manually claim your ETH.

•

Educating holders is complicated. It's difficult for them to understand the value until they go through the full claiming experience. More difficult to market.



We have in place a unique system that auto-claims for every single holder the amount due. this will be available for holders above a $100 as they would be exempted from fees. We call it WORKFIRST.



The way it works for holders: You buy tokens and hold them, every 8hrs  you'll manually or automatically receive ETH in your wallet based on holding power respectively.  

Your WorkFirst tokens amount is persistant and won't change.



Behind the scenes:

•

We will deploy a bot that keeps track in an array of all token holders

•

The bot keeps an index into the array for processing

•

Every transaction processes a certain number of users, depending on the transaction size (bigger token transfers can process more, since the gas will still be proportionally less than the value of the tokens)

•

The token is based on a Dividend-Paying Token Standard. In staking, all fees, which means all ETH the contract gains will be split equally proportionally to the token holders with a percentage available to developers wallet.

•

When a user is processed, the contract checks how many withdrawable dividends they have, and if it is above the minimum threshold for auto-claims, will either automatically claim those dividends for ETH, or automatically buy back tokens for them.



This system is fully automated and doesn't add minimal gas fees proportional to value transferred. The number of holders processed through each transaction is dynamic and based on transaction size. Holders will receive dividends from the queue based on their position in the array. It's a fair system, fully automated.  Minimum token balance is 10000000 WorkFirst tokens to receive ETH distributions.



What if I don't want to wait?

We will set up a function on the contract for impatient holders so they can claim manually.



WorkFirst Launch

Upon active members.

•

DEX public listing

SUSHISWAP



Token Information (provisional)

Network: Arbitrum

Ticker: WKFT

Contract address: To be announced

Decimals: 9



•TOTAL SUPPLY : 1,000,000,000

•TOKENS FOR DEX LISTING : 440,000,000 (44%)

•TOKENS FOR MARKETING WALLET: NONE 

•Liquidity Locked & Token renounce: Lock will be eminate after staking and bot contract has been fixed and running with issues.



Security of WorkFirst



Locked Liquidity 

Initial liquidity will be locked for a minimum of 12 months to provide holders with peace of mind that the token can always be exchanged. This is only after the above mentioned criterias are completed.  

The token contract will be given right before launch in telegram group. 

Other features



Anti-Dump Logic

Price protection features such as max tx on sells are included.  



7% Sell fee

Swing trading is a common practice that can affect price action.
