#aytufi-testnet

-Auto Swap (TON - aUSDT, TON - AytuUSDT, TON - aSTONK)

-Auto Add Liquidity (REMOVED DUE HIGH GAS FEE SPEND)

-Multi Account Support

##installation

'''shell
git clone https://github.com/sushtrsh/aytufi-testnet.git
'''

'''shell
cd aytufi-testnet
'''

'''shell
yarn
'''

OR

'''shell
yarn install
'''

##usage

'''shell
cp account_tmp.js account.js
'''
'''shell
nano account.js
'''
-fill [nano account.js] with your account Seed Phrase
'''shell
yarn start
'''

###optional 

-run with pm2 to run in background  
'''shell
pm2 start index.js --name "name session"
'''
Full Doc pm2 https://pm2.keymetrics.io/docs/usage/pm2-doc-single-page/

