# Decentralised Lottery

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

* Solidity
* Python
* Remix
* Ganache
* Rinkeby
* Brownie
* Py-test
* [Openzeppelin](https://openzeppelin.com/contracts/)
* [True Randomness(VRF)](https://docs.chain.link/docs/get-a-random-number/) and [Price Feed](https://docs.chain.link/docs/get-the-latest-price/) with Chainlink