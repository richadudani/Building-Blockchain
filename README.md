# Unit 18 | Building the Blockchain

![Block Chain Technology](Images/BC.jpg)

### <b> Background </b>
The blockchain domain is rapidly changing.  Even those in a highly technical role must stay abreast of what is happening in the digital finance landscape as many FinTech companies are using and creating tools and services that are powered by blockchain. As a FinTech professional in these changing times, it's important to not only be aware of the advancements happening within the FinTech blockchain space, but to also understand the process for developing your very own blockchain.

In this exercise, I have created a two-part series. Series 1 contains a case study on a Canadian FinTech company "Wealthsimple" and in the Series 2, I have tried to develope my very own blockchain.

### <b> Summary </b>

I have accomplished the following main tasks:

1. Case Study - I have analyzed how one of the Top 10 most popular Canadian financial technology company called "Wealthsimple Inc.", which primarily specializes in online investment management services is now using blockchain technology to solve a standing financial problem in Canada.

2. I have set up a testnet blockchain for my organization and completed the following tasks.

* Used Puppeth, to generate a genesis block.
* Used Geth, a command-line tool, to create keys, initialize nodes, and connect the nodes together.
* The Clique Proof of Authority algorithm.
* Tried to send a test transaction
* Created a repository
* Wrote instructions on how to use the chain for the rest of my team

### <b> Files locations in Github </b>

1. I have created a repository called `blockchain-homework` in the Github.

2. Inside the above there are two sub-folders named "Blockchain Case Study" and "POA Development Chain" which has all the solution files

### <b> Details on each tasks </b>

### <b> 1. Blockchain Case Study </b> 

I have created a case study that analyzes how "Wealthsimple Inc.", a Canadian FinTech blockchain company is using technology to solve a standing financial problem in Canada.

#### <b> What Is It </b> 

Wealthsimple Inc. is a Toronto-based FinTech company which was founded 6 years ago in September 2014. Founders Michael Katchen, Rudy Adler and Brett Huneycutt founded a business that would revolutionize wealth management for their friends and other millennials. Traditional investment companies typically target a demographic of people aged 45 and above, but Weathsimple’s current CEO, Michael Katchen, wants to bring people into the world of investment earlier. His philosophy is as follows:
   
<i> “Millennials are missing out on opportunities to secure their financial future,” he explained. “A lot of young people are mistrustful of big banks and put off by the paperwork. We are combining financial expertise with smart IT to shake up the industry and modernise investment.” </i>

The average age of Wealthsimple's customer was between 30 to 35 years with university degree when it started out. But today, Wealthsimple caters to the uninitiated millennial investor, with a reported 80% of its clients under the age of 45, and 40% of them being first-time investors, many trade or want to trade in crypto. According to the CEO, the biggest challenge in the Canadian market is non-availability of safe, secure and credible platforms for cryptocurrency trading. 

On the 14 July 2020, Wealthsimple launched a cryptocurrency trading platform in a move to attract new customers to its brand and capitalize on renewed interest in the lightly regulated asset class popular with young investors. The platform, will allow its clients to trade in two of the highest market cap cryptocurrencies- bitcoin and ethereum using a Wealthsimple Trade app (<i>Deposits and withdrawals can only be made in Canadian dollars</i>). This is offered by Wealthsimple Digital Assets Inc. (WDA), a virtual currency dealer money services business authorized by FINTRAC. Cryptocurrencies can only be held in a non-registered account with Wealthsimple Crypto.

On August 7, 2020, the Canadian Securities Administrators (CSA) has granted WDA time-limited relief from certain requirements to allow it to trade crypto assets and operate a platform that facilitates the buying, selling and holding of crypto assets in all Canadian jurisdictions other than Quebec which has issued separate exemptive relief. Trading will be restricted to Bitcoin and Ethereum and is limited to a maximum of $30,000 per client over a 12-month period. Gemini Trust Company (<i> one of the most trusted names in crypto, with the highest U.S. government security rating and  $200M in cold storage insurance</i>), LLC will serve as a licensed third-party custodian while multiple crypto asset trading firms will act as liquidity providers for the purchase and sale of crypto assets. This has made Wealthsimple, Canada’s first crypto asset platform authorized through the CSA Regulatory Sandbox initiative. In Québec, WDA is registered as a derivatives dealer.

While Wealthsimple is looking to brand its product as a safer alternative to other crypto exchanges, it will still operate in a hazy regulatory environment. Wealthsimple Crypto is currently not registered as a securities adviser or securities dealer. Crypto-assets purchased and held in an account with Wealthsimple Crypto are not protected by the Canadian Investor Protection Fund (CIPF), the Canadian Deposit Insurance Corporation or any other investor protection insurance scheme.

#### <b> Why This Matters </b> 

Blockchain together with Bitcoin and Cryptocurrency is by far one of the most disruptive and revolutionary technologies of our time. As of 2019 global spending on Blockchain solutions has been over $2.7 billion which is likley to increase by almost 500% by 2023. This has led to every industry wanting to adopt blockchain technology and reap its benefits. 

Although WDA is under a time-limited exemptive relief by the CSA, it is Canada’s first crypto asset platform authorized through the CSA Regulatory Sandbox initiative. The decision is a win-win for consumers, fintech companies and the regulators. 
1. Regulators - Not only does this highlight the limitations of the current Canadian regulatory environment to tackle rise of Blockchain but offers a bridge to emerging custodial and trading solutions for crypto asset trading that are rapidly developing outside of Canada. This will provides regulators the ability to monitor and analyze anonymized trade data to proactively build out data-driven regulatory options framework for trading crypto assets”.
2. Consumers - They would not be charged commission on trades, have opportunities to learn and become smarter investors and above all, regulator are ensuring that the fintech companies offering these services have internal controls to ensure fraud, money laundering, and insolvency risks are mitigated. Regulators would monitor the practices of counterparties and service providers, such as custodians and crypto trading firms, to ensuring investor protection and fair and reasonable pricing.
3. Fintech Companies - To attract more customers, increase revenues and opportunity to be market leaders in adopting new technologies.

#### <b> Why This May be Interesting </b> 

In Canada, Wealthsimple is the biggest player in the "digital space" at 70% market share but they continue capturing market share through new products and services. They have registered three new businesses in 2019 namely Wealthsimple Cash in June 2019, Wealthsimple Payments in August, and Wealthsimple Digital Assets, issued in October 2019. 

On 14 October 2020, they have achieved Unicorn status on a CA$114 million investment round led by by TCV, along with Greylock, Meritech, Two Sigma Ventures and existing investor Allianz X. 

They have many advantages over their competitors as they have unique product offerings, such as its diverse lineup of portfolio choices (including socially responsible and halal-compliant options) and unfettered access to a team of financial advisors for all clients, regardless of account balance. It is also ideal for novice investors or those who are uneasy choosing their own investments since it recommends a portfolio of low-fee investments or individualized portfolio for large accounts which are explained below. Additionally, Wealthsimple is great for planning towards bigger money goals and investing/saving in tax-free accounts – retirement (RRSP), home down payment and wedding (TFSA), kids college education (RESP).

Wealthsimple has been pioneer fintech company in online investment in Canada, have world-class financial experts and best technology talents. Given these factors, it will be interesting to watch the interplay between adoption of blockchain and regulatory space through them. This will set precedence for competitors and industry including banks which faces huge burden of regulatory complaince.

### <b> 2. Proof of Authority Development Chain </b>

The Proof of Authority (PoA) algorithm is typically used for private blockchain networks as it requires pre-approval of, or voting in of, the account addresses that can approve transactions (seal blocks).

I have set up a testnet blockchain for my organization "ZBank", a small, innovative bank that is interested in exploring what blockchain technology can do for them and their customers. The private testnet can be used by I and my team of developers to explore potentials for blockchain at ZBank. This was decided because there is no real money involved, which will give us the freedom to experiment. Testnets allows for offline development.

### Instructions

#### Setup the custom out-of-the-box blockchain

#### 1. The genesis block is the first step towards creating a new blockchain!

* Open a terminal window, navigate to the `Blockchain-Tools` folder and typed the following command:
 
        ./puppeth
 
* Type in a name for your network, like "puppernet" and hit enter to move forward in the wizard.

* Type `2` to pick the `Configure new genesis` option, then `1` to `Create new genesis from scratch`:

 ![genesis](Screenshots/puppeth.png)

Now you have the option to pick a consensus engine (algorithm) to use.

* Type `2` to choose `Clique (Proof of Authority)` and continue.

You will be asked to enter a pre-fund account.

* Paste both account addresses from the first step one at a time into the list of accounts to seal.

* Paste them again in the list of accounts to pre-fund. There are no block rewards in PoA, so you'll need to pre-fund.
![pre-funding](Screenshots/pre-funding.png)

* You can choose no for pre-funding the pre-compiled accounts (0x1 .. 0xff) with wei. This keeps the genesis cleaner.

* Complete the rest of the prompts, and when you are back at the main menu, choose the "Manage existing genesis" option.
* Export genesis configurations. This will fail to create two of the files, but you only need networkname.json.
![exporting_genesis](Screenshots/export_genesis.png)

#### 2. Creating two nodes with accounts

Because the accounts must be approved, we will generate two new nodes with new account addresses that will serve as our pre-approved sealer addresses.

First, export your genesis configuration into a `yournetworkname.json` file as follows:

* In the `puppeth` prompt, navigate to the `Manage existing genesis` by typing `2` and hitting enter.

* You may have to type your network name again first if you're launching `puppeth` fresh.

* Then, type `2` again to choose the `Export genesis configurations` option, and continue with the default (current) directory by hitting enter:

* This will export several `yournetworkname.json` files -- we will only be using the first one without `aleth`, `parity`, or `harmony` suffixes.

Now, we need to create at least two nodes to build the chain from the genesis block onward:

* Exit `puppeth` by using the `Ctrl+C` keys combination.

* Create the first node's data directory using the `geth` command and a couple of command line flags by running the following line in your terminal window (Git Bash in Windows):

        ./geth account new --datadir node1

You should see a success message similar to this one:

![geth new account](Screenshots/Nodes_creation.png)

* Create a new text file for notes, and copy the node's address into the file and label it `Node 1 Key`.

* Repeat the same process for the second node by replacing the `datadir` parameter with the `node2` folder.

        ./geth account new --datadir node2
 
* Make sure to keep track of the node's addresses and which belongs to which. 

#### 3. Initialize and tell the nodes to use your genesis block!

With the genesis block creation completed, we will now initialize the nodes with the genesis' json file.

* Using geth, initialize each node with the new networkname.json, replacing `yournetworkname.json` with your own:

        ./geth --datadir node1 init networkname.json
        ./geth --datadir node2 init networkname.json

You should see this success message:

![Initialize Node](Screenshots/initialize_node1.png)

* Since you only initialize your nodes once, you don't need to copy anything into your notes here.

* Run the first node, unlock the account, enable mining, and the RPC flag. Only one node needs RPC enabled.
![Mining Node1](Screenshots/Mining_node1.png)

* Set a different peer port for the second node and use the first node's `enode` address as the `bootnode` flag.

![Mining Node2](Screenshots/Mining_node2.png)

* Be sure to unlock the account and enable mining on the second node!

#### 4. Send a test transaction (I was not able to complete from here)

* Use the MyCrypto GUI wallet to connect to the node with the exposed RPC port.

* You will need to use a custom network, and include the chain ID, and use ETH as the currency.

![custom-node](Images/custom-node.png)

* Import the keystore file from the `node1/keystore` directory into MyCrypto. This will import the private key.

* Send a transaction from the `node1` account to the `node2` account.

* Copy the transaction hash and paste it into the "TX Status" section of the app, or click "TX Status" in the popup.

* Screenshot the transaction metadata (status, tx hash, block number, etc) and save it to your Screenshots folder.

* Celebrate, you just created a blockchain and sent a transaction!

![transaction-success](Images/transaction-success.png)


#### Hints

* If you get stuck - try our step by step PoA Guide located [here](Resources/POA-Blockchain-guide.md).

* If you aren't seeing any movement in the wallet amounts in MyCrypto after sending/receiving transactions, try the following:

    * Terminate both nodes using control+C in the Node1 and Node2 terminal windows.
    * Change networks in MyCrypto to a Testnet such as Kovan.
    * Restart Node1 and Node2 in their terminal windows.
    * Reconnect to your network in MyCrypto.
    * Log into your wallet and refresh the amount.

* If that doesn't help make sure you are sending a large enough sum of ETH to see actual movement in the digits. You may have to click on the amount itself to see the full value down to the WEI.

### Resources

Below sources were used to conclude the above case study. It has list all websites, podcasts, blogs, or articles that were consulted in order to write the report, and provide links.
* [The Company's Website](https://www.wealthsimple.com/en-ca/)
* [Company's information on wikipedia](https://en.wikipedia.org/wiki/Wealthsimple)
* [Crypto info on Company's Website](https://www.wealthsimple.com/en-ca/product/crypto)
* [Blockchain info on Company's Website](https://www.wealthsimple.com/en-ca/learn/what-is-blockchain)
* [The Company's Magazine](https://www.wealthsimple.com/en-ca/magazine/crypto)
* [The Company's Advertisements](https://www.youtube.com/watch?v=fypQIkUKgUE#action=share)
* [Globe and Mail Report on launch of Wealthsimple cryptocurrency trading platform](https://www.theglobeandmail.com/business/article-wealthsimple-launches-cryptocurrency-trading-platform/)
* [Wealthsimple Digital Assets Inc. Becomes Canada’s First Registered Crypto Asset Platform](https://www.stikeman.com/en-ca/kh/canadian-securities-law/wealthsimple-digital-assets-inc-becomes-canadas-first-registered-crypto-asset-platform?utm_source=Mondaq&utm_medium=syndication&utm_campaign=LinkedIn-integration)
* [Wealthsimple achieves $1.5 billion valuation on new fundraising round](https://www.finextra.com/newsarticle/36757/wealthsimple-achieves-15-billion-valuation-on-new-fundraising-round?utm_medium=rssfinextra&utm_source=finextrafeed)
* [Statistics Canada](https://www.statista.com/statistics/444868/canada-resident-population-by-age-group/)
* [Canadian Encyclopedia](https://www.thecanadianencyclopedia.ca/en/article/millennials-in-canada)
* [Nerdwallet 2020 Review](https://www.nerdwallet.com/reviews/investing/advisors/wealthsimple)
* [FinTech blogs and/or podcasts[1]](https://betakit.com/wealthsimple-raises-100-million-from-allianz-x-to-build-a-full-stack-financial-service/#:~:text=Wealthsimple%20raises%20%24100%20million%20led,full%20stack%20financial%20service%20%7C%20BetaKit)
* [FinTech blogs and/or podcasts[2]](https://betakit.com/wealthsimple-registers-three-businesses-indicating-expansion-into-new-financial-services/)
* [FinTech blogs and/or podcasts[3]](https://betakit.com/wealthsimple-to-spin-out-advisory-service-into-separate-company/)
* [FinTech blogs and/or podcasts[4]](https://betakit.com/wealthsimple-registers-three-businesses-indicating-expansion-into-new-financial-services/)
* [FinTech blogs and/or podcasts[5]](https://betakit.com/wealthsimple-raises-100-million-from-allianz-x-to-build-a-full-stack-financial-service/#:~:text=Wealthsimple%20raises%20%24100%20million%20led,full%20stack%20financial%20service%20%7C%20BetaKit)
* [FinTech blogs and/or podcasts[6]](https://betakit.com/digital-finance-institute-names-canadas-top-50-fintech-companies-for-2019/)
* [The Canadian Fintech Ecosystem Map](https://ecosystem.formfintech.com/)
* [The 2019 Canadian fintech market map](https://www.pwc.com/ca/en/industries/technology/canadian-fintech-market-map.html)
* [Introducing The FinTech Landscape In Canada](http://www.industryandbusiness.ca/development-and-innovation/introducing-the-fintech-landscape-in-canada)
* [Canadian Fintech Industry Set to Witness Strong Grow: Report](https://fintechnews.ch/fintech/fintech-canada-report/19783/)

