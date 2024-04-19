# sharedWalllet

DApp's Domain - https://shared-wallet.netlify.app/

Smart Contract - https://sepolia.etherscan.io/address/0xc25b27d5dddff09362d6e806d0110bc943179669#code

The name of the project is sharedWallet. according to which, the admin will pass address and amount as parameters in his function. address - is the address of the money sharer, and amount - how much to spend. After the participant receives the permission, he can transfer this crypto to someone else.
In this case, the admin is the caller of msg.sender, i.e. me :)

In the future, i will offer an automatic version so that whoever wants to be the administrator.

One interesting thing I noticed was that the contract did not show where the money went. After a better study, I may find a good way of "mixer", let's see.

![shareWallet](https://github.com/LazareLomsadze/sharedWalllet/assets/70573427/310341f1-44ff-4960-afe4-7c9ec5be1076)
