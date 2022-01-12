# Decentralised Lottery
Made in accordance with [Solidity, Blockchain, and Smart Contract Course – Beginner to Expert Python Tutorial](https://www.youtube.com/watch?v=M576WGiDBdQ)

1. Users can enter lottery with ETH based on a USD fee
2. An admin will choose when the lottery is over
3. The lottery will select a random winner

## Structure

* basic setup using brownie
* main structures of the code: start, enter, end, and deliver the results and paying the lottery winner using Openzeppelin and Chainlink
* Ensuring randomness using Chainlink VRF, ensuring oracle gas and transaction gas, following the request-receive architecture
* Ensuring unit tests and integration tests of the application
* Understanding and implementing events and callbacks
* Deploying application on Rinkeby and local computer

### Technologies Used

* [True Randomness(VRF)](https://docs.chain.link/docs/get-a-random-number/) and [Price Feed](https://docs.chain.link/docs/get-the-latest-price/) with [Chainlink](https://chain.link/)
* [Openzeppelin](https://openzeppelin.com/contracts/)
* [Etherscan](https://etherscan.io/)
* [Rinkeby](https://www.rinkeby.io/#stats)
* [Ganache](https://trufflesuite.com/ganache/)
* [Brownie](https://eth-brownie.readthedocs.io/en/stable/)
* [Remix](https://remix.ethereum.org/)
* [Solidity](https://docs.soliditylang.org/en/v0.8.11/)
* [Python](https://www.python.org/)