# ERC-20 Token KaseiCoin Crowdsale

---

## Background

This application creates KaseiCoin (KAI), an ERC-20 token.  It then manages the crowdsale of KAI. The application leverages the OpenZeppelin Solidity library in coding the contracts.

The crowdsale contract manages the entire crowdsale process, allowing users to send ether to the contract and in return receive KAI. The contract mints the tokens automatically and distribute them to buyers in one transaction.

---

## Software & Libraries

* [Remix - Ethereum IDE](https://remix-ide.readthedocs.io/en/latest/) - an open source web and desktop application for the entire journey of contract development as well as being a playground for learning and teaching Ethereum. It fosters a fast development cycle and has a rich set of plugins with intuitive GUIs. 

* [MetaMask](https://docs.metamask.io/guide/) - allows users to manage accounts and their keys in a variety of ways, including hardware wallets, while isolating them from the site context. This is a great security improvement over storing the user keys on a single central server, or even in local storage, which can allow for mass account thefts.

* [Ganache](https://www.trufflesuite.com/docs/ganache/overview) - a personal blockchain for rapid Ethereum and Corda distributed application development.

* [OpenZeppelin](https://docs.openzeppelin.com/openzeppelin/) - a library that provides a complete suite of security products to build, manage, and inspect all aspects of software development and operations for Ethereum projects.

---

## Evaluation Evidence by Steps

The steps for this application are divided into the following sections:

1. Create the KaseiCoin Token Contract

![Step1](https://github.com/Jyou965/ERC-20_token_crowdsale/blob/main/ScreenShots/1_token_contract_compile.png)

2. Create the KaseiCoin Crowdsale Contract
    Compiler version 0.5.0. generated the error message as follows.  As such, version 0.5.5 was used instead.

![error](https://github.com/Jyou965/ERC-20_token_crowdsale/blob/main/ScreenShots/3_050_error_message.png)

![crowdsale](https://github.com/Jyou965/ERC-20_token_crowdsale/blob/main/ScreenShots/2_crowdsale_contract.png)

3. Create the KaseiCoin Deployer Contract

![deployer](https://github.com/Jyou965/ERC-20_token_crowdsale/blob/main/ScreenShots/4_deployer.png)

4. Deploy the Crowdsale to a Local Blockchain (The videos at the links below are too large to show.  Please click the "download" button on the right of the page and view the videos as downloaded files.)

    a. Deploy the crowdsale to a local blockchain with Remix, MetaMask, and Ganache.

    ![1](https://github.com/Jyou965/ERC-20_token_crowdsale/blob/main/Videos/1_deployment.mov)

    b. Test the functionality of the crowdsale by using test accounts to buy new tokens and then checking the balances associated with those accounts.

    ![2](https://github.com/Jyou965/ERC-20_token_crowdsale/blob/main/Videos/2_fundraising.mov)

    c. After purchasing tokens with one or more test accounts, view the total supply of minted tokens and the amount of wei that has been raised in the crowdsale contract.

    ![3](https://github.com/Jyou965/ERC-20_token_crowdsale/blob/main/Videos/3_viewTotal.mov)

---

## Contributors
Jackie You, Jamal Rizvi and Clare Collity with the support of UC Berkeley FinTech Boot Camp Staff