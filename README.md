# TIL

### 25/03/2020
- TIL **(Blockchain)** *RSK* -> How to use configure metamask to work at RSK testnet. Blockexplorer/faucet and remix for deploying smart contracts over there. 

### 26/03/2020
- TIL **(Defi)** *Uniswap* -> I learned how [Uniswap V2 improved on chain oracle manipulation](https://uniswap.org/blog/uniswap-v2/#testnet-and-launch-details):
-> Storing the "last block asset price" -> Manipulators need to manipulate two blocks in a row now.
-> Using TWAP (Time Weightned Avg Price) -> You can set the time window you willl use to your application. Higher the time window, higher is the cost of manipulation.

[Pt2 - Uniswap History](https://uniswap.org/blog/uniswap-history/)
- Dan Robinson helped him with gas efficient contract during a flight
- Ric burton (Wallet founder) helped him in the beggining
- Hired one great developer to build the entire frontend
- Formal Verification in addition to Security Audit

### 28/03/2020

- TIL **(Frontend)** *React Hooks* -> How to implement **Private Route w/ Context**. Also learned that useContext() is the same as `<Context.Consumer>` and you should pass a handler through `<Context.Provider>` if you want to change the context from a child component

- TIL **(Misc)** *Vscode* -> Learned how to configure standarjs to run onSave, and changed keyboard biding to run this on SHIFT ALT F

### 29/03/2020

- TIL **(Backend)** *Firebase* -> How to handle **Login/Signup/Logout** w/ email and password using Firebase. And How to **deploy** a react app to firebase Hosting service.

### 30/03/2020

- TIL **(Ethereum)** *Solidity* -> Had a Meetup with Jeff Prestes explaning the changes for solidity 0.6 version. Basically now you have fallback and receive functions. Array.pop() method, abstract, and others. ABIENCODERV2 is now safe!

### 31/03/2020

- TIL **(Defi)** *UMA* -> Tested new UMA price oracle approach. The problem they are solving is reducing the amount of times MakerDAO updates their oracle unnecessary. In their approach a person trying to liquidate or withdraw needs to wait a time window of 1 hour, and them we have monetary incentives for "validators" to attempt a band intention liquidation/withdraw.

### 01/04/2020

- TIL **(Defi)** *FlashLoan* -> Learned this [youtube tutorial](https://www.youtube.com/watch?v=03jO9vbrXvY) and read *Aave* [documentation](https://developers.aave.com/developers/)


### 07/04/2020

- TIL **(Ethereum)** *Remix* -> Improved my remix proficiency level, deployed on mainnet and testnets some contracts.

### 09/04/2020

- TIL **(DeFi)** *FlashLoan* -> Did a talk showing three flashloan use cases: 1) Onchain Arbritage / 2) Yield borrowing transfer / 3) Vaults liquidations. And a working example of a flashloan contract ono Kovan with Remix.

### 13/04/2020

- TIL **(Frontend)** *Magic* -> Magic is a passwordless Fortmatic implementation using Dencentralized identifiers[DID](https://w3c-ccg.github.io/did-primer/). Its a new type of a global unique identifier. Read their integration with firebase and, but didnt implemented yet.

### 14/04/2020

- TIL **(Fundraising)** *Convertible Note* -> Found [this channel](https://www.youtube.com/watch?v=njx09wXb9o0) with a lot of simple explanations about the fundraising proccess. Understood that CN is much easier and fast proccess to raise funds before you know what is your first valuation. It works like a Loan, that you pay instead of money, in shares of you next investment round. And as a Loan, it has interest rate, maturity date, a cap, and a discount factor based on the next valuation.
Obs: Also learn that in business, you hardly ever split/sell your own shares (change ownership) Unless the business is actually acquired. Usually you "mint/issue" new shares and dilute your own shares.

There are two simpified templates that we can use as a Convertible Note: KISS (Keep it simple security) from 500 startups and SAFE (Simple Agreement of Future Equity) from Ycombinator.

### 15/04/2020

- TIL **(Ethereum)** *v2* ->  https://www.youtube.com/watch?v=j4J3RWVNzPw
    phase0 -> Beaconchain (You will stake on eth1 to mint eth on eth2) just one way
    phase1 -> ?
    phase2 -> 

- TIL **(Ethereum)** *WETH* -> Learned that wETH is simply a contract that is ERC20, with a `mint` and a `burn` functions, the mint, lock in the contract the msg.value.






