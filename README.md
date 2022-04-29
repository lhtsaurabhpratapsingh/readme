# XDC3Python

XDC3PYTHON SDK with support for smart contracts, XDC20 & XRC721. 


## Usage

***pip install XDC3PYTHON***

XRC20 Read methods        | XRC20 Write methods
-------------             | -------------
name()                    | approve(receiverAddress , amount)
symbol()                  | transfer(recipient, amount)
totalSupply()             | transferFrom(sender, recipient, amount)
balanceOf(account)        | increaseAllowance(spender, addedValue)
allowance(owner, spender) | decreaseAllowance(spender, subtractedValue)