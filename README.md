# XDC3Python

XDC3PYTHON SDK with support for smart contracts, XDC20 & XRC721. 


## Usage

**pip install XDC3PYTHON**

### This SDK supports following Read & Write operations:-###

XRC20 Read methods                       | XRC20 Write methods
-------------                            | -------------
name()                                   | approve(receiverAddress , amount)
symbol()                                 | transfer(recipient, amount)
totalSupply()                            | transferFrom(sender, recipient, amount)
balanceOf(account)                       | increaseAllowance(spender, addedValue)
allowance(owner, spender)                | decreaseAllowance(spender, subtractedValue)

XRC721 Read methods       | XRC721 Write methods
-------------             | -------------
name()                    | setApprovalForAll(spenderAddress, booleanValue)
symbol()                  | approve(spenderAddress , tokenId)
totalSupply()             | transferFrom(receiver, tokenId)
balanceOf(account)        | safeTransferFrom(receiver, tokenId)
ownerOf(tokenId)          | 
tokenURI(tokenId)         |
tokenByIndex(index)
tokenOfOwnerByIndex(ownerAddress,index) 
supportInterface(interfaceId)
getApproved(tokenId) 
isApprovedForAll(ownerAddress,spenderAddr)