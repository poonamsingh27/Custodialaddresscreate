# Custodial Factory and custodialwallet Solidity Contract Documentation

The Custodial Factory is a smart contract written in solidity language used to create single custodial address and multiple custodial
addresses(createBatch).The contract designed to be deployed on the ethereum network and polygon network.

# Functions

1. Create

Create new single custodial address 

# Parameters

Pass owner address you want to transfer ownership for particular address
index value

2. CreateBatch

Create multiple custodial address

# Parameters

Pass owner address you want to transfer ownership for particular address

index value (in array)

# Custodialwallet


# function

1. transfer

transfer eth,matic,erc20(token) and erc721(NFT) for single wallet.

# Parameters

token address : address of eth ,matic ,erc20 address and erc721 address

Contract Type:        0- ERC20
                      1- ERC721
                      2- ERC1155
                      3- native asset  
recipient address                              

amount : eth, matic ,erc20 and erc721 value you want to transfer

tokenid: native asset and erc20 token id by default 0
          valid only for ERC721 and ERC1155.


2. transferBatch

transfer eth,matic,erc20(token),erc721(NFT) for multiple wallet.

# Parameters

token address : address of eth ,matic ,erc20 address and erc721 address. (pass in array)

Contract Type:        0- ERC20
                      1- ERC721
                      2- ERC1155
                      3- native asset (in array)

recipient address(pass in array)                      

amount : eth, matic ,erc20 and erc721 value you want to transfer.(pass in array)

tokenid: native asset and erc20 token id by default 0
          valid only for ERC721 and ERC1155(pass in array)









