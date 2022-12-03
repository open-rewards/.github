# Open Rewards

Internet is supported by open source tools for even its basic functions. Yet there is no sustainable way to support it till date. There has been experiments with the incentive models but they failed eventually. We think our protocol leverages blockchain and gives an easy to use solution to any open source or public good project to reward its contributors for the most regen of its activity. We make the rewards that the contributor will earn by supporting the development of the project long term completely transparent.

We faced multiple UX issues that made it very hard for coordinating the state updates on chain with common logistical problems like discovery of the pool. We also had to create a trusted setup that can act as oracle while taking data from the third party service - github in this case. 

We leverage safe to create a pool that collects the money from different sources for the project. It then transfers the assets periodically to the splits - liquid vesting smart contract. We had plans to use recurring payments from safe to splits for easier management but couldn't figure it out in time for the hackathon. 
We think safe SDK is amazing tool and gives a lot of flexibility to building a composable systems that have their own roles to play. 

We build this tool as a public good and think has a large impact on the open source community. It tries to evangelize the protocol guild (Ethereum foundation) type experiment to any project. This piece can be used as Lego for so many use cases. For e.g.: 
1. An on-chain guild that wants to incentivize content creation
2. A protocol that wants to connect IRL events with on chain incentives.

