[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/check-it-out.svg)](https://forthebadge.com)

# Multisig Wallet Smart Contract

## Brief description
A multisig wallet is a wallet where **multiple "signatures"** or approvals are needed for an outgoing transfer to take place. As an example, I could create a multisig wallet with me and my 2 friends. I configure the wallet such that it requires at least 2 of us to sign any transfer before it is valid. Anyone can deposit funds into this wallet. But as soon as we want to spend funds, it requires 2/3 approvals.

## Requirements
- Anyone should be able to deposit ether into the smart contract
- The contract creator should be able to input:
  - the addresses of the owners 
  - the numbers of approvals required for a transfer 
- Anyone of the owners should be able to create a transfer request. The creator of the transfer request will specify what amount and to what address the transfer will be made.
- Owners should be able to approve transfer requests.
- When a transfer request has the required approvals, the transfer should be sent. 

### Solidity Version
> 0.7.5

---

## Contributors
[Daniel Namaki](https://www.github.com/NamaWho)
