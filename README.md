                                                                                                                 
88888888ba               88                           88  88888888888  88        88   ad88888ba   88888888ba,    
88      "8b              88                           ""  88           88        88  d8"     "8b  88      `"8b   
88      ,8P              88                               88           88        88  Y8,          88        `8b  
88aaaaaa8P'  ,adPPYYba,  88,dPPYba,   8b       d8     88  88aaaaa      88        88  `Y8aaaaa,    88         88  
88""""""8b,  ""     `Y8  88P'    "8a  `8b     d8'     88  88"""""      88        88    `"""""8b,  88         88  
88      `8b  ,adPPPPP88  88       d8   `8b   d8'      88  88           88        88          `8b  88         8P  
88      a8P  88,    ,88  88b,   ,a8"    `8b,d8'       88  88           Y8a.    .a8P  Y8a     a8P  88      .a8P   
88888888P"   `"8bbdP"Y8  8Y"Ybbd8"'       Y88'        88  88            `"Y8888Y"'    "Y88888P"   88888888Y"'    
                                          d8'                                                                    
                                         d8'                                                                     
                                                                                                                                                                  
Baby iFUSD ($BABYiFUSD)
Whitepaper
The Baby iFUSD Whitepaper aims to educate readers on our vision, strategy and roadmap. Below we illustrate in detail our unique redistribution mechanism. It’s an engineering achievement unheard of until now in the FTM ecosystem. We are happy to be the pioneers and are excited to showcase the new use cases that this will enable. Hoge Finance was the one to bring awareness around RFI and HODL rewards. Baby iFUSD will carry the innovation torch forward. We will share our vision with the world: the first auto-claim iFUSD reward mechanism.

Baby iFUSD in a nutshell
Baby iFUSD is the next evolution of a yield-generating contract on the Fantom Opera Chain (FTM): you get rewarded in iFUSD instead of tokens.The token contract employs a static rewards system—10% of every transaction is split into three parts:
-7% iFUSD is redistributed to holders
-2% is used to fuel the liquidity pool exchange growth
-1% iFUSD is allocated to the Buy back / Marketing wallet.

Classic redistribution
This is a concept that was popularized by Hoge Finance. The mechanism incentivizes token holders to hold in order to earn dividends from the transactions (buys and sells).
Redistribution is based on percentage (in the contract), current token balance and number of holders.TL; DR: You receive more tokens automatically.

Baby iFUSD redistribution
We adapted the system first seen in BabyCake that buys another token and auto-claims for every single holder the amount due. We call ours the Baby iFUSD PROTOCOL.
The way it works for holders: You buy tokens and hold them, every 60 minutes you’ll automatically receive iFUSD in your wallet. Not a single action is required.

Your Baby iFUSD tokens amount is persistent and won’t change.

Note: In periods of low volume iFUSD may not be sent out every hour, but don’t worry. It accumulates and is then sent when ready. You’ll never miss out.

Behind the scenes:
-The contract keeps track in an array of all token holders
-The contract keeps an index into the array for processing
-Every transaction processes a certain number of users, depending on the transaction size (bigger token transfers can process more, since the gas will still be proportionally less than the value of the tokens)
-The token is based on a Dividend-Paying Token Standard, which means all iFUSD the contract gains will be split equally proportionally to the token holders.
-When a user is processed, the contract checks how many withdrawable dividends they have, and if it is above the minimum threshold for auto-claims, will either automatically claim those dividends for iFUSD, or automatically buy back tokens for them.

This system is fully automated and doesn’t add minimal gas fees proportional to value transferred. The number of holders processed through each transaction is dynamic and based on transaction size. Holders will receive dividends from the queue based on their position in the array. It’s a fair system, fully automated. Minimum token balance is 200,000 Baby iFUSD tokens to receive iFUSD distributions.

DEX public listing
Baby iFUSD tokens will become available for purchase on SpiritSwap Exchange.
Token Information (provisional)
Network: Fantom Opera Chain (ERC-20) Ticker: BABYiFUSD
Contract address: 0xb9f92b05EedD6e0DC56CfD039713DeecAFBd8C99 Decimals: 9

FAIR LAUNCH

🔆 TOTAL SUPPLY: 1,000,000,000
🔆 TEAM / PARTNER Allocation: (10%)
🔆 TOKENS FOR Baby iFUSD LISTING: 900,000,000 (90%)
🔅 Fair Launch Tim: ?? at ?PM (UTC)
🔅 Liquidity: Burned


Security of Baby iFUSD
Locked Liquidity
Initial liquidity will be burned to provide holders with peace of mind that the token can always be exchanged. 

Contract Audit Prior to Launch
In an effort to increase transparency and ensure security the original Baby Cake team had purchased a top-tier audit with HASHEX to be ensure no vulnerabilities can be found such as:
-Integer Overflow
-Integer Underflow
-Callstack Depth Attack
-Timestamp Dependency
-Parity Multisig Bug
-Transaction-Ordering Dependency

Other Features
Anti-Dump Logic
Price protection features such as max tx on sells are included. Any transaction selling more than 0.2% of total supply will be rejected. This prevents massive one time sells that drastically alter the token price.

Extra 1% Sell fee
Swing trading is a common practice that can affect price action. To incentivize holding and reducing pump/dump dynamics, we added an extra 1% sell fee on top of the initial 10% transaction fee. Total sell fee = 11%
 __         __
/  \.-"""-./  \
\    -   -    /
 |   o   o   |
 \  .-'''-.  /
  '-\__Y__/-'
     `---` BpB
