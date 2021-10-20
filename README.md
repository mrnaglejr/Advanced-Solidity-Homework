# Advanced-Solidity-Homework
## Puppercoin.sol
- This contract helps raise Ether to help fund network develepment 
- Import the ERC20.sol, ERC20Detailed.sol, and ERC20Mintable.sol OpenZepplin contracts.
- Create a contract named Puppercoin and incorporate the ERC20, ERC20Detailed, and ERC20Mintable contracts.
- Create a contructor with name, symbol, and initial supply.
- Use those contructors with the ERC20Detailed contract
- Select compile `crowdsale.sol` [deploy puppercoin](deploy_puppercoin.png). Make sure you choose the 0.5.7+commit.6da8b019 compiler version.
[deployed puppercoin](deployed_puppercoin.png)

## Crowdsale.sol
- This contract manages the raising of Ether. 
- Log onto `http://remix.ethereum.org/` and have the `metamax` extentioned installed using `Google Chrome`
- Open the `crowdsale.sol` file in `remix`. Select the revolving "S" in the left had banner.
- Select compile `crowdsale.sol` [deploy crowdsale](deploy_crowdsale.png). Make sure you choose the 0.5.7+commit.6da8b019 compiler version.
- After compiling the contract, select the icon below the revolving "s", this is the deploy button.
- `MetaMax` will ask you to unlock and enter your password
- Ensure your environment as Inject Web3. 
- Under the depoly section enter the account numbers you want to transact with. [deploy account](deploy_acct.png)
- Once the accounts have been entered select the `transact` button.
