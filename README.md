### About this package

This npm package is a clone of the following repository
```
https://github.com/Ricochet-Exchange/protocol-monorepo
```
The files are Ethereum contracts for the Superfluid-finance protocol.
Some of these contracts are used by Ricochet-Exchange. But small modifications have been made.

In the 1.0.0 version, the following files have been changed:

- upgradability/UUPSUtils.sol 
- upgradability/UUPSProxiable.sol 
- utils/ERC777Helper.sol 

### Audience

This package can be used by ricochet contributors instead of having to modify the *node_modules* directory of the Solidity project.

### How to use it

1.- ``` npm install ricochet-exchange-sfcontracts-used```

2.- Replace *@superfluid-finance/ethereum-contracts* by *ricochet-exchange-sfcontracts-used* in the *import* expressions.

3.- The dependency *@superfluid-finance/ethereum-contracts* can be removed from the *package.json* file.

