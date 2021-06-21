## Blockchain_Dev_Environment
Installing and configuring all necessary tools to start from Zero: Ubuntu, NodeJs, Tuffle, etc


## Installing Truffle:
https://www.trufflesuite.com/docs/truffle/getting-started/installation

```bash
npm install -g truffle
``` 

After installing truffle you can check up to what Solidity Versions it supports with command:
```bash
truffle version
``` 
As in this example below it supports versions up to 0.6.12

luisca@luisca-desktop:~/gr10/bondi-mat$ truffle version
Truffle v5.1.14 (core: 5.1.14)
Solidity - 0.6.12 (solc-js)

If you compile a Solidity version higher than listed you will see this error:
_TypeError: Cannot convert undefined or null to object_
