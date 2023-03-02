# node-express-vercel
This is the public API for your token. Endpoints displays the folowing data:
- Total Supply (Total supply is the total number of tokens that exist on the blockchain, including tokens that aren't in public circulation.)
- Circulation Supply (It is the approximate number that is currently in public hands.)
- Brned Amount (Number of tokens that have been burned)
- Trading Data (Information about token pair, current price in pair token and USDT)

Endpoints example:

#### GET token Total Supply
  https://public-api-example.vercel.app/totalSupply
  
#### GET token Circulation Supply
  https://public-api-example.vercel.app/circulationSupply

#### GET token Burned Amount
  https://public-api-example.vercel.app/amountBurned
  
#### GET token Trading Data
  https://public-api-example.vercel.app/tradingData
