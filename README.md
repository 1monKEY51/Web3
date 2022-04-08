# WEB3

## ERC20 Token:
Name: Lyam
Symbol: LYAM

Premint: 100000
Mintable: Privileged accounts will be able to create more supply.
Burnable: Token holders will be able to destroy their tokens.
Pausable: Privileged accounts will be able to pause the functionality marked as whenNotPaused.

Access control: Ownable
Simple mechanism with a single account authorized for all privileged actions.

Upgradeability: Transparent
Uses more complex proxy with higher overhead, requires less changes in your contract. Can also be used with beacons.