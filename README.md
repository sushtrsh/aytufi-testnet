# aytufi-testnet

- Auto Swap (TON - aUSDT, TON - AytuUSDT, TON - aSTONK)
- Auto Add Liquidity (REMOVED DUE HIGH GAS FEE SPEND)
- Multi Account Support

## installation
- git clone https://github.com/sushtrsh/aytufi-testnet.git
- cd aytufi-testnet
- yarn & yarn install

##usage

- cp account_tmp.js account.js
- nano account.js
- fill account.js with your Seed Phrase
- yarn start
### optional 
- pm2 to run in the background 
- pm2 start index.js --name "name session"
- [Full Doc pm2](https://pm2.keymetrics.io/docs/usage/pm2-doc-single-page)
#### Using Npm
- full tutorial, tips, and more
[Check it out](https://github.com/Widiskel/aytu-fi-testnet-bot/blob/master/README.md)
- thanks to [@Widiskel](https://github.com/Widiskel)
