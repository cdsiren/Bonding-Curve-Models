# Bonding-Curve-Models
Simulations to determine optimal bonding curve shapes and strategies

## Navigating This Model
·  Each tab is an Excel version of a Monte Carlo simulation depicting the first 200 NFTs minted on different versions of bonding curves: take rate, reserve pool, LP model
·  Users can update the cuve in use by changing the function that is calculating NFT sale price at each issuance
·  The primary sale proceeds are the sum of each sale price for an assumed number of NFTs in circulation.  This roughly gives the area under the curve.
·  Secondary sale proceeds will automatically update and are a function of each purchaser's randomized ROI preferences.  The logic is that some fans will sell on the way up to the assumed number of NFTs in circulation and profits are taken on each sale.
·  We consider 3 possible revenue models: 1) a transaction fee on each trade 2) a take rate on each trade 3) a reserve pool model where the issuer pre-mints some number of NFTs and can profit by selling them later
