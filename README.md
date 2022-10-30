# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```
// StakingRewards.sol
Stake one token (erc20) lock duration (365 days) and receive a fixed APY of 12% Rewards in BUSD. 
(BUSD Code copy from BSc scan and deploy separately and send token to Contract for reward etc )
User Stakes UTL in POOL for 1 year locked
After one year User can withdraw Locked UTL and BUSD Rewards