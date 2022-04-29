![](https://raw.githubusercontent.com/hyperspot/BNB-hyperspot/main/PIC/Hyperspot.jpeg)

## Project Name

Hyperspot Platform

## Overview

Hyperspot is an Ethereum-based fixed-rate lending platform. A fixed interest rate is different from a variable or stable interest rate because the interest rate does not change over the term of the loan.

## Features

It will be a challenge for users to match loans to each other under the exact conditions.Because of the large pools of liquidity, banks have traditionally acted as intermediaries - charging high fees - for borrowers and lenders to interact with them.Hyperspot eliminates intermediaries and maintains on-chain pools of liquidity that are readily available as off-the-shelf counterparties for individual users.

## Advantage

### 1.Enabling Fixed Rates in the Crypto Ecosystem

hyperspot makes it possible for anyone to lend or borrow crypto assets at a fixed-rate of interest at any time, from anywhere in the world, in just a few clicks. Unlike other protocols that just serve lenders at fixed rates, or only offer volatile, variable interest rates, hyperspot serves both sides of the fixed-rate borrowing and lending market.

### 2.fCash

Behind the scenes, hyperspot introduces a concept called fCash to make this happen. fCash allows hyperspot to tokenize payments in different currencies like ETH or USDC at specific points in the future. fCash is what hyperspot uses to keep track of who owes what, who is owed what, and when.

For example, on hyperspot, two users can enter into an agreement where a lender gives 100 USDC to a borrower who promises to repay 105 USDC on December 1st.

fCash is how hyperspot defines that future payment of 105 USDC from the borrower to the lender. Here is how hyperspot keeps track of the future payment from borrower to lender using fCash:

The lender receives +105 December 1st fUSDC (an asset redeemable for 105 USDC on December 1st)  
The borrower gets -105 December 1st fUSDC (an obligation of 105 USDC due on December 1st).  
The exchange rate between USDC and fUSDC at the specific maturity represents the fixed interest rate that users receive on hyperspot.  

### 3.Liquidity pools

It would be challenging for individual users to match on exact terms to borrow and lend with each other. With large pools of liquidity, banks traditionally act as an intermediary that borrowers and lenders interact with - for a hefty fee. hyperspot removes intermediaries and maintains on-chain liquidity pools that serve as a ready counterparty for individual users at any time.

Liquidity pools hold cash, like USDC, on one side, and fCash, like December 1st fUSDC on the other side.

Lenders put their USDC into the pool and take out December 1st fUSDC at the prevailing market exchange rate.
Borrowers put December 1st fUSDC into the pool and take out USDC to use however they wish.
Collateralization

hyperspot guarantees that lenders earn the returns they expect by ensuring that borrowers pay back their debt at maturity. hyperspot requires every borrower to first lock in high-quality assets like Ether and wrapped Bitcoin to act as collateral - much like how a bank might use your home as seizable collateral on a mortgage. This means, for example, that a user who wants to borrow 100 USDC will be required to hold collateral that is worth at least 150 USDC - a minimum collateralization level of 150%.

The amount of collateral that borrowers are required to hold against their debt varies based on the risk level of their collateral - DAI only requires 120% collateralization, while ETH requires 150%.

### 4.Liquidation

Enforcing these collateral requirements ensures that borrowers on hyperspot can’t simply walk away from the debts they owe. However, instead of the bank repossessing an entire home in case of a mortgage non-repayment, hyperspot’s liquidation process can sell, or liquidate, partial amounts, so that borrowers maintain their collateral requirements without losing all their collateral. This only becomes necessary if the value of their collateral drops below the required level due to market fluctuations.

In the unlikely event that borrowers are not liquidated quickly enough due to market volatility, hyperspot can use the protocol’s own reserve assets or sell its native token, the NOTE, to raise the capital necessary to make sure lenders are always made whole.

hyperspot is a sophisticated system, but the value proposition that it delivers is simple: hyperspot delivers access to secure and efficient fixed-rate loans to anyone in the world by removing financial intermediaries with the Ethereum blockchain.


## Some pictures

### 1.Hyperspot-Tokens picture

![](https://raw.githubusercontent.com/hyperspot/BNB-hyperspot/main/PIC/Hyperspot-Tokens.png)

### 2.Hyperspot-cTokens picture

![](https://raw.githubusercontent.com/hyperspot/BNB-hyperspot/main/PIC/Hyperspot-cTokens.png)

### 3.Details picture

![](https://raw.githubusercontent.com/hyperspot/BNB-hyperspot/main/PIC/Details.png)

### 4.Borrow picture

![](https://raw.githubusercontent.com/hyperspot/BNB-hyperspot/main/PIC/Borrow.png)

### 5.Lend picture

![](https://raw.githubusercontent.com/hyperspot/BNB-hyperspot/main/PIC/Lend.png)
