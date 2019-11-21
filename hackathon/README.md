# Hackathon, 13 November 2019, Villach
## Decentralized Networking platform "ChainMeUp"

https://github.com/posseggs/ChainMeUp

# Hackathon 12, May 2019, Graz

## Streaming: "Ka Göd, ka Musi"
English: "No money, no music". lab10 managed to stream (in its semantic closest sense) “Streemable PLAY Tokens” (SPLY) as the music was playing. When the card is in touch with the NFC reader, the record player starts playing in exchange for tokens. When the card is removed, the streaming stops and so does the music. Quite rad, isn’t it? The PLAY tokens used here were minted in 2017 on Ethereum in the context of the Play4Privacy project. Therefore lab10 moved some of them over from the Ethereum chain to the ARTIS chain, converting them into “Streemable ERC20 Tokens” in the process. More details? check out: https://github.com/lab10-coop/kgkm-nfc

<p align="center">
  <img src="pictures/kagoedkamusi.gif" width="60%" align="middle">
</p>

## BeerDentity
Blockchain identity verification using zero knowledge proofs: https://github.com/rekt0x/infineon_hackathon_2019 <br/>
Usecase: The Infineon's Blockchain Security 2Go Starter Kit is used to store identity tokens using zero knowledge proofs in order to perform age verification without revealing any personal data. An user needs to go to a local authority with his hardware wallet smart card. The authority created a proof that the person is older than 18 years and issues an Identity Token to the users wallet. The user can then use the hardware wallet smart card at various locations to proof he is old enough to use certain services without revealing his real age or birthday to the 3rd party.

## Guardian Card
A novel social recovery scheme based on multi signature and smart contracts in combination with the Blockchain Security 2Go Starter Kit: https://github.com/lab10-coop/kgkm-power-switcher
<p align="center">
<img src="pictures/guardiancardconcept.PNG" width="60%">
<img src="pictures/guardiancard.PNG" width="20%" > 
</p>

## Document certification - Proof of existence
Due to the Blockchain technology there are more and more virtual notary services available: https://proofofexistence.com/, https://stampery.com/, https://poex.io/, https://chainy.info/ etc. With these services you are able to write data (e.g. a hash of a document) to the blockchain. The private key that was used to generate the transaction message allows you to proof the ownership, the existence but also the integrity of any kind of data without relying on trusted third parties. The service is also often used to proof that a specific recipient read your email at a certain point in time. A physical token, representing ownership of the data, maybe embedded in a real contract etc., does make sense.

<p align="center"><img src="pictures/proofofexistence.jpg" width="40%" align="middle"></p>

Within this example the service "proofofexistence" for bitcoin was used to generate a transaction with the DOCPROOF attribute for the bitcoin network: https://www.blockchain.com/btc/tx/51bf2164bdf67e2a4fcf216dc2ec9f11778d177c58c2be9db6a8f017c996e95a

## Ethereum/Bitcoin Ring
The Blockchain Security 2Go card represents just one of the many form factors that can be supported by Infineon's security controller. Certainly other form factors which are using the contactless interface are feasible too. A nice example for innovative contactless chip integration is the Ethereum NFC ring.

<p align="center">
<img src="pictures/ring.png" width="20%" > 
<img src="pictures/etherring.gif" width="50%">
</p>


## Physical representation of "Cryptokitties"
With this project a physical form of the Ethereum based Cryptokitties was generated. Therefore key1 of the card was read out and converted to an Ethereum address. Cryptokitties are non-fungible ERC-721 token, which allow for each entity to have specific attributes - in this case “Cattributes”. 6 Kitties were bought at the market and transferred to the prepared and printed card. All transfers can be checked at etherscan.io.

<p align="center"><img src="pictures/crypotkitties.png" width="70%" align="middle"></p>

Daniela Fuzzyhands: https://etherscan.io/tx/0x39d8119652aaaa48980b0c36ad7294d933ad16ea64ab774e3f955f18f5db7bf4 <br/>
Fabiano Lilsmoochie: https://etherscan.io/tx/0xa12fda9f27aa3e211dca80dfc07d3048cd4b22202ae3994d303955fe120ee522 <br/>
Pepper Magicwump: https://etherscan.io/tx/0x396c2735c57e3526db052f2a4239ee7d58b2d97ecedfaf045a9d8d89585be762 <br/>
Tundra Sister: https://etherscan.io/tx/0x65e4685a53efa804e976547b83abc1fe97b572c149dfa0dab03f2a297450dbf4 <br/>
Lulu Scootchrum: https://etherscan.io/tx/0x147dcc8b343e7476a801bfac86337c5b7c34e9c968e532907cf944073d269a65 <br/>
Moses Alldub: https://etherscan.io/tx/0x382532902ccf948738a2ca9e6c5c3d4e47c881d1e797855aa400ad3259750b47 <br/>


## Bitcoin Bounty Vendingmachine
A vending machine is a nice example to showcase the cryptocurrency application: In this case the Blockchain Security 2Go Starter Kit is used to pay directly the vending machine in order to get a snack. Due to the machine to machine payment (without any trusted 3rd party or middleman) the vending machine now owns some cryptocurrency. As a result the vending machine could order new supply for its own when it is empty. Furthermore - imagine - why should anyone pay for the energy the vending machine is consuming? Certainly the vending machine should do it for its own - in future.

<p align="center">
<img src="pictures/vendingmachine_how.jpeg" width="37%" > 
<img src="pictures/vendingmachine.gif" width="50%">
</p>


