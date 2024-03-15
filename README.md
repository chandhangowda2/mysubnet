### ERC20 Contract

**Description:**
The ERC20 contract is a standard implementation of a fungible token on the Avalanche blockchain. It allows for the creation, transfer, and management of tokens following the ERC20 standard interface.

**Functions:**
- **Mint:** Create new tokens and add them to the total supply.
- **Burn:** Destroy existing tokens, reducing the total supply.
- **Transfer:** Send tokens from one address to another.
- **Approve:** Authorize a third party to spend tokens on behalf of the owner.
- **TotalSupply:** Get the total supply of tokens.
- **BalanceOf:** Get the balance of tokens for a specific address.
- **Allowance:** Check the amount of tokens a spender is allowed to withdraw from the owner's account.

**Usage:**
1. Deploy the ERC20 contract onto the Avalanche blockchain.
2. Interact with the contract using compatible wallets or applications.
3. Utilize functions such as minting, burning, transferring, and approving to manage tokens.

### Vault Contract

**Description:**
The Vault contract provides secure storage for tokens on the Avalanche blockchain. It allows users to deposit and withdraw tokens while generating and destroying corresponding shares to represent ownership.

**Functions:**
- **Deposit:** Transfer tokens into the vault and generate shares in return.
- **Withdraw:** Burn shares and receive tokens back from the vault.
- **TotalSupply:** Get the total supply of shares.
- **BalanceOf:** Get the balance of shares for a specific address.

**Usage:**
1. Deploy the Vault contract onto the Avalanche blockchain, specifying the address of the ERC20 contract.
2. Interact with the contract using compatible wallets or applications.
3. Deposit tokens to generate shares and withdraw shares to reclaim tokens as needed.
