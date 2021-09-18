# Martian_Market

The Martian Development Foundation has asked you to develop a system to raise funds for Martian land development. The system will be a combination of an ERC721 contract and an Auction contract combined to form the MartianMarket contract.

The foundation will be able to register new landmarks with their account, minting and creating a new auction for the landmark. When the endAuction function is called, the auction will complete and the token will be transferred to the highest bidder.

The functions of the contract can be designed to have the foundation pay for the most expensive functions likesafeTransferFrom. This can be done by putting the token transfer in the endAuction function that only the foundation can call.

Each landmark will be a unique ERC721 token, with its own metadata including the landmark name and image URL.

Your frontend developer has already provided you the UI necessary for getting the job done, all you need to do is implement the contracts. Good luck! Remember, you're building something few people have explored, so don't be afraid!
