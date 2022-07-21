# ERC20Project
This is one of the many projects available on [Codedamn](https://codedamn.com/projects) to reinforce your learning by building. If you want to become a Blockchain Developer and learn by practicing, feel free to attempt this challenge. Feel free to check out the codedamn [Web3 Learning Path](https://codedamn.com/learning-paths/web3) to learn more about how to become an awesome Blockchain Developer.

## Instructions
Use the ERC20 interface given in the `ERC20.sol` and create your own ERC20 Token. 

**Description of the functions** - 
1) totalSupply() → uint256
Returns the amount of tokens in existence.

2) balanceOf(address account) → uint256
Returns the amount of tokens owned by account.

3) transfer(address recipient, uint256 amount) → bool
Moves amount tokens from the caller’s account to recipient.
Returns a boolean value indicating whether the operation succeeded.
Emits a Transfer event.

4) allowance(address owner, address spender) → uint256
Returns the remaining number of tokens that spender will be allowed to spend on behalf of owner through transferFrom. This is zero by default.
This value changes when approve or transferFrom are called.

5) approve(address spender, uint256 amount) → bool
Sets amount as the allowance of spender over the caller’s tokens.
Returns a boolean value indicating whether the operation succeeded.
Emits an Approval event.

6) transferFrom(address sender, address recipient, uint256 amount) → bool
Moves amount tokens from sender to recipient using the allowance mechanism. amount is then deducted from the caller’s allowance.
Returns a boolean value indicating whether the operation succeeded.
Emits a Transfer event.

**Description of the events -**
1) Transfer(address from, address to, uint256 value)
event
Emitted when value tokens are moved from one account (from) to another (to).
Note that value may be zero.

2) Approval(address owner, address spender, uint256 value)
event
Emitted when the allowance of a spender for an owner is set by a call to approve. value is the new allowance.

**Note -** You have to write the migration script also in the migration file.
