# Tracking commercial activity on Lightning Network
We are developing heuristics for measuring commercial use of the Lightning Network. 

Lightning Network is a “Layer 2” protocol built on top of Bitcoin’s “Layer 1,” designed to allow parties to transact back and forth more quickly and cheaply, without accessing the slow and costly Bitcoin blockchain for every single transaction. Lightning's transaction-focused nework presents the opportunitiy to study the state and direction of demand for commercial uses of cryptocurrency. These commercial uses may be generally characterized as bearing the assurance that businesses and their customers may transact in amounts of any size, permissionlessly, globally, without depending on a third-party platform. These assurances were original threads in Bitcoin's narrative and retain a strong attachment for many. Now that Lightning Network is available, conveying some of these assurances to the end user, it is appropriate to ask the question: is there evidence of user demand? 

## Hypothesis
For commercial operators handling Lightning transactions at some volume or more, there will be a pattern of on-chain events associated with the growth of their business over the Lightning network. Lightning is in a test phase of deployment and the earliest stage of adoption. Signals observable at this early time may provide a heuristic framework for measuring future adoption.

## Method
Where Bitcoin exposes every transaction to the observation of validators and analysts, on Lightning, transactions remain private; only the opening and closing balances between two transactors (nodes) are settled on chain. Transactors open "channels," a payments link between two parties, across which amounts flow back and forth, until the channel is closed and the parties' closing balances are written to Bitcoin's ledger. Activity inside the channels is private, but the following data are public:

- Channel opens
- Channel closes
- Channel updates
- Channel capacity
- Node capacity

Using information that Lightning users and others have published to the internet, in combination with information available on block explorers like 1ml.com, we have identified what we believe is a fairly complete list of commercial operators using Lightning. Over the coming month, we will contact them to request the following data:

- Monthly active users transacting via Lightning, by month, trailing 12 months
- Total Lightning transaction volume, by month, trailing 12 months

In addition, we'll ask the following questions:

- On a scale of 1 to 5, with 1 being not significant, and 5 being critical to your business activity, how significant is the business you are doing on Lightning, today?
- On a scale of 1 to 5, with 1 being not at all, and 5 being critical to your business' future, to what extent does Lightning factor into your future planning? 
- Approximately how long, in years, do you expect it will be until Lightning becomes a significant part of your business? (0, < 1, 2, 3, 4, 5 or more)
- Please describe what you are doing to maximize your opportunities for Lightning transactions, including steps you have taken on the Lightning network, itself. 
- What challenges present themselves against the growth of your business over the Lightning network? 
- In what city and country are you located? 

We will look for correlations between the survey data and on-chain data associated with the respondent businesses. We hope to find correlations and use patterns that can be used as a heuristic to measure commercial activity globally over the Lightning network. If we are successful, this heuristic will serve as an index of user demand for Bitcoin as a commercial medium of exchange. 


