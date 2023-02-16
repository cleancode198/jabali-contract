# Jabali - Unlucky Slug

An automated lottery that gives away NFTs of different categories depending on their prize, ticket refunds, golden tickets, and a Jackpot which has been accumulated from previous throws.

Functionalities Summary:
- The owner of the smart contract deposit different NFTs, and also give information about their cost, to calculate the probability of winning them.
- The owner of the smart contract depost funds for the prizes related to ticket repayments
- When a user throw a ticket in the lottery, it generates a random number from Chainlink VRF v2, which allows to calculate if the user won a prize, and if yes, which one.
- 2 random numbers are generated, the first one is to check which of the prizes you have got, and the second one is to select which specific NFT of the group.
- A user can win these different prizes: Jackpot, Top NFT, Medium NFT, Normal NFT, x100 from the ticket prize, x10 from the ticket prize, x1 from the ticket prize, a golden ticket.
- A user can set a refferer, to get a cashback of 2% in every throw, and give the referrer also a 2%. The only condition is that the referrer had must spend more than .1 ether in the lottery.

Please leave a ⭐ if you like it.

## Try It Out
You can get testnet BNB [here](https://testnet.binance.org/faucet-smart).

If you find any **errors** ⛔, please report them to [cleancode198@gmail.com](mailto:cleancode198@gmail.com) thanks 🙏.

## Technologies
Technologies used in this project:
- [Solidity](https://soliditylang.org/)
- [Chainlink](https://chain.link) for getting VRF to determine winner in decentralized maner
- [Hardhat](https://hardhat.org/) for smart contracts

**UI source code is published [here](https://github.com/cleancode198/jabali).**

## About Me
Hi! 👋 I'm Jin, passionate **web and blockchain developer**. Take a look at my [portfolio](https://jinkong.netlify.com).

You can get in touch with me through my [website](https://jinkong.netlify.com) or contact me on [linkedin](https://linkedin.com/in/jinkong198).

Do you like my work? You can support me by donating to this address: 0xf18432a6d3C6f8720227C2856dEE97B6d99357EF

## License
[MIT](https://choosealicense.com/licenses/mit/)
