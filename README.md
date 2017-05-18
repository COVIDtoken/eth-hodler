# ETh Hodler - www.ethhodler.org


## A simple non-profit DApp & ERC20 token running on the Ethereum blockchain

![States](/eth_hodler_states.svg)

The ETh Hodler is for hodlers - a simple DApp that helps holders to hodl, nothing more.
It's for the benefit of the community. Absolutely noting goes to the developers of this DApp, 
thus keeping things simple and small.

    "This is just silly. Do people lack so much willpower that they have to
    handicap themselves to have no access to your ETH? What if you lock it today
    and it shoots to $200 in a week? What then? The last thing you want is
    have NO ACCESS to your funds, whether crypto or fiat or whatever.
    How about, just hold. There, problem solved.". - Reddit /user/Chop13

But wait, there are actually some benefits:

Each deposit to the DApp issues you with EHDL tokens. These tokens
are then used to make a withdrawal and burned once the withdrawal is processed.

A normal withdrawal would take ~30 days to process, costing only the gas fee.
Should the holder want to withdraw their deposit early, they can, but
they must pay a %1 fee. The fees will be added to a fee-pot. Holders can claim
a chunk from the fee-pot, see the rules to find out how.

### How to use

Use as a DAPP - by using browser-wallet such as Mist Browser, Parity Browser,
or use the MetaMask extension for Chrome.

MetaMask is currently probably the best way to use at this time as it offers the lest friction.

### Rules

* Tokens will be issued when sending ETH to the contract: TBA
* Normal ETH Withdrawal: must wait until after 172800 blocks, which is roughly 30 days
* Immediate ETH withdrawal: Must pay a %1 fee.
* For all Withdrawals: tokens will be destroyed after withdrawal. Ether to be sent back to original address.
* Tokens pending normal withdrawal will be locked until after 172800 blocks.
* While tokens are locked, the cannot be transferred or sent.
* While tokens are locked, you cannot add more ETH to the address.
* When the wait period is over, you must complete the withdrawal manually.
* After withdrawal to ETH, tokens are burned, thus deflating the token supply
* HODL tokens will be trade-able too.

### Security information:

- The contract went through 3 independent peer reviews, each completed by a different experienced Solidity developer. Additional reviews were performed by members of the /r/ethtrader community after the Author found a bug in the original Hodl Dao contract, a week after launch. See [this thread](https://www.reddit.com/r/ethtrader/comments/6b37dn/hold_dao_bug_found_with_reward_calculation_the/) for details about how the issue was handled.
- The Author of the contract does not have the functionality to move
- funds in the contract or issue/destroy tokens - the contract is completely out of the Author's control.
- The contract code is kept as simple as possible (KISS). There's no concept of voting, splitting, curators, owners and the contract can be upgraded
- The contract's source code has been verified through Etherscan

### Game theory

- If enough holders enter the contract, Price of ETH should go up, because ETH is removed from the market.
- Better than normal holding, since holders can claim from the fee-pot, after holding for the minimum time
- Should the ETH price spike to say $200 USD, immediate withdraw will still be possible.
- HODL tokens may be trade-able on an exchange, and on face value 1 HODL = 1 ETH, should an exchange add them


### Contract's Author

Reddit's Ethtrader member, /u/CurrencyTycoon/ - A huge fan of /user/lagofjesus who gave
inspiration to write this contract after reading his story.

Latest info on Twitter: https://twitter.com/CurrencyTycoon
