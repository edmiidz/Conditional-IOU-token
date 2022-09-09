# Conditional-IOU-token for personal or project funding

A smart contract which can be used to mint a token which is convertible for ETH when milestones are reached.

Based on the [conditional promissory note discussed in this talk](https://www.youtube.com/watch?v=zMbQbr5OmYs), it is a means where anyone can issue tokens to help fund a project, business or even just for personal financial success. Once a threshold of value has been accumulated, the token holders can convert to ETH. Then token will have 0 ETH value until conditions are met.


* Fungibility Threshold: 500 ETH
* Mint quantity: 1,000,000
* Decimals: 0
* ETH Value before Fungibility threshold: 0
* ETH Value after Fungibility threshold: 0.001

Assumptions:
* Tokens will follow ERC-20 Ethereum Token Standard or similar allowing them to be interoperable with popular wallets and exchanges.
* All minted tokens will initially belong to the owner.
* The owner will periodically send tokens to new/existing recipients.
* Any token holder may convert some or all of her tokens for ETH (without any action from smart contract owner) if the following conditions are met: 
  * The owner's address exceeds the fungibility threshold plus the ETH Value of the tokens to be funged.

**Out of scope:**
Website or app for selling/trading/claiming token.
