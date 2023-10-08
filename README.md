# HRHR-stable-coin-protocol-on-the-EOS-EVM
Winner takes all stable coin protocol, backed by cryptocurrency. 


# INTRODUCTION:

Effective stable-coins (SC) and stable-coin protocols (SCP) are a major need for every crypto ecosystem. 

Being of public interest, the ideal SC should not channel funds to any centralized party; much less if this channelling goes in detriment of the stability of the coin itself. Instead, in order to maximize liquidity, the incentives to those willing to borrow SC into existence should also be maximized. 

So, a high-risk super-high-reward SCP is presented. The protocol is initially designed with the following two goals:

- Maximizing the probability of maintaining peg during dramatic market downturns. 
- Maximizing the incentive for new liquidity providers to appear under extreme circumstances. 

The initial aim is not to implement the code of the SCP itself on the EOS EVM. The grant aims to conduct the preliminary research in order to bring a deep understanding to the EOS-EVM ecosystem of the behavior of such protocol (and possibly other discovered protocols along the way) under a wide range of conditions. The results of this study will be published, in the open, in any or several of the news channels currently working on the community. The respective implementation and software verification and validation is something that, if the current grant is successful, the community and its governance bodies can later decide on. 

# MOTIVATION:
- High volatility presents itself as one of the factors that hinder the stability and growth of SCP.  
- SC creators are fundamental to the proper functioning of these protocols, yet they risk losing their collateral at the hands of centralized entities whenever the market goes down. It would be much more fair if earnings were distributed among those who took the higher risk. 
- In addition to incurring in the risk of losing their collateral, people who borrow SC into existence are usually punished with unpredictable interest rates. 
- Aside from the risk for borrowers, high volatility has, sometimes, destroyed stable-coin protocols by provoking them to lose peg. This has hurt also SC holders. Such was the case of UST (Luna's stable-coin)
- To each debtor his debt, that has been the premise in pretty much every SCP. When such premises are relaxed, incredible possibilities and fascinating behaviour may appear.  
- Because this protocol can be run on EOS EVM, and because EOS is burn with every EVM transaction, its implementation could help to make EOS a deflationary asset. 

# The proposed protocol:

- Anyone can stake EOS as collateral in order to borrow stable-coins into existence. That newly created SC may be pegged to USD, Yuan, gold or any other commodity. It doesn't matter. 
- In order to incentivize the liquidity of these newly created assets, such a loan is fully free of interest. 
- The borrower needs to keep a minimum collateral ratio (MCR) in order to avoid losing his position. That MCR is a parameter whose optimal value needs to be defined but that can be much lower than what current protocols demand. The reason for this is presented in the following numerals.
- Whenever a given borrower fails to keep his collateral above MCR, he loses his position. 
- However, this position is not liquidated. Instead, it is transferred to all the other well collateralized borrowers, in a pro-rata basis. The details of this part of the protocol are yet to be defined. 
- The above point implies that as long as there is at least one borrower with collateral above MCR, the peg will be held and the stable asset will be fully backed. 
- It also implies that no amount of collateral is directed towards any other entity different than the borrowers themselves. 
- Another implication is that those borrowers that manage to keep their positions open during extreme market circumstances can have enormous rewards whenever the market recovers. This is because by then they will have been transferred the collateral (and debt) from all those who failed to maintain their positions. 
- All this incentivizes the creation of small positions with high collateral ratios under extreme market circumstances. This is, so far, an unseen and very innovative approach in the SCP market. 
- Ideally, find ways of rewarding the position holders, so as to help them minimize the risk of losing their positions. 

With all sincerity and pure heart, 

Jorge Ramos
