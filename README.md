# Consensys
Code from the 2020 Consensys Blockchain Course 

## Main Project - Due Nov 30th 2020

### Psudo Code
**The general idea**
- Mintbase fork that creates: "The MarmaJ Factory"! Allows artists to "mint" for free; (Using arkwaeve? / some value is locked in the NFT factory for "b" blocks).
- First mint brings NFT to L1 from L2 and sets price; (.1 ETH for now).
- newNFTprice = * 1.1 NFTprice; (price increase of 10%$ after each mint).
- 80% of saleValue is transfered to artist; (artist mints for free and gets paid like normal, but 20% less).
- 10% of saleValue is transfered to marmaj.eth; (long term validator pool).
- 10% of saleValue is transfered to a yeild bearing sc to accrue APR; (sc owner is marmaj.eth).
  - yeild.finance / rDAI / (others?) will be used and funds released to all NFT holders equallty at the end of the timePeriod.
     - Funds in ybsc (ex. held in rDAI) will be locked until bh has been passed at which point contractOwner will be able to release them for withdrawal by NFT holders.
     - All holders will be able to withdraw funds equal to # of userNFTs/totalNFTsMinted.
        - Would like to auto distribute like Gitcoin... 
  
**Yay, all funds are acconted for**
- Artists don't take too much of an instant hit (20%), and are able to buy a few of their own pieces to throw up in galleries or give to friends and family. Buying your own art can become a reasonable investment since you are investing in your own success.
- Marmaj.eth ensures that it is increaing it's long term $ETH holdings, which are meant for running an ETH2.0 validator.
- "Gamification, with extraction of economic rents to alturism".
  - Pool Together x YFI x Mintbase - with some layer two arkweave action in there!
  
**Schedule**
1. Write this!
2. Clean up Mintbase contract.
3. Release v0.1 on Gorlei testnet? (Rinkeby might be easier since Mintbase.io is already using it.)
4. Release v1.0 on mainnet Oct 1st. (Sept 14th?; Allow additional minters)
5. Release v2.0 by November 30th. (Allow anyone to mint in the factory, differing lock times, different platforms available to invest into)
6. With outside investment maybe release v3.0 for Jan 1 2021 which would have an audit done, but would allow for a yfi DAO vault type of situation for the holdings withing each piece of art (NFT).
