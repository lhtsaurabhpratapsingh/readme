# XDC3PYTHON

XDC3PYTHON SDK with support for smart contracts, XDC20 & XRC721. 


## Usage

**pip install XDC3PYTHON**

### This SDK supports following Read & Write operations:-

* xrc20 methods.
    * Read methods.
        * name(), balanceOf(account), totalSupply(), symbol(), decimals(), allowance(pwner, spender).

    * Write methods.
        * transferXDC(owner,receiver), approve(spender,amount), transferToken(receiver,amount), increaseAllowance(spender, addedValue), decreaseAllowance(spender, subtractedValue), transferFrom(sender, receiver, amount).

* xrc721 methods.
    * Read methods.
        * name(), symbol(), totalsupply(), balanceOf(ownerAddr), ownerOf(tokenId), tokenURI(tokenId), tokenByIndex(index), tokenOfOwnerByIndex(ownerAddress,index), supportInterface(interfaceId), getApproved(tokenId), isApprovedForAll(ownerAddress,spenderAddress).

    * Write methods.
        * setApprovalForAll(spenderAddress, booleanValue), approve(sepnderAddress , tokenId), transferFrom(recipient, tokenId), safeTransferFrom(spender, tokenId).

### Environment Variable

` Create a .env file in the root directory of the Python project to put the wallet and endpoint information in like so: NETWORK_URL = "https://rpc.apothem.network" `

### Example for XRC20.


`from XDC3PYTHON import XRC20

if __name__=="__main__":

    token = input('Enter token address: ')
    a = XRC20.name(token)
    print(a)`

This example returns name of the specified address.

### Example for XRC721.

`
from XDC3PYTHON import XRC721

if __name__=="__main__":

    token = input('Enter token address: ')
    a = XRC721.symbol(token)
    print(a)
`

This example returns symbol of the specified address.

# Transports

**HTTP transport**

### Author
[XDCFoundation](https://github.com/XDCFoundation/XDC_Python_SDK_V1)

