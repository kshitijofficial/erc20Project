﻿# erc20Project
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

7) Transfer(address from, address to, uint256 value)
event
Emitted when value tokens are moved from one account (from) to another (to).
Note that value may be zero.

8) Approval(address owner, address spender, uint256 value)
event
Emitted when the allowance of a spender for an owner is set by a call to approve. value is the new allowance.
