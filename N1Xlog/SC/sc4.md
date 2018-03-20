# [Index](README.md) @ [N1X](https://N1X.site/) \[ARCH\] / `metamask-extension/N1Xlog/ SC/` 

1. [Contract Overview](sc0.md)
2. [Contract Source Code](sc1.md)
3. [Contract ABI](sc2.md)
4. [Contract Creation Code](sc430.md)
5. [Contructor `~` Arguments](sc4.md)
6. [Swarm Source `bzzr://`](sc5.md)

---
---
Contract Overview
ETH Balance: 	33.601534000000000134 Ether
ETH USD Value: 	$18,640.45 (@ $554.75/ETH)
No Of Transactions: 	361 txns
---

## CSC:

```
pragma solidity ^0.4.18;
```

## SC-ABI:

```
[{"constant":false,"inputs[...}]
```

## CCC: 
```
PUSH1 0x60
PUSH1 0x40
MSTORE
PUSH1 0x04
CALLDATASIZE
LT
PUSH2 0x013e
JUMPI
...
STOP
```

##  Constructor Arguments 
### (ABI-encoded and is the last bytes of the Contract Creation Code above.)
The `operation-codes` need to converted “Structurally” for interoperability.
It is an intermediate level that defines the structure or format of data exchange (i.e., the message format standards) where there is uniform movement of healthcare data from one system to another such that the clinical or operational purpose and meaning of the data is preserved and unaltered. Structural interoperability defines the syntax of the data exchange. It ensures that data exchanges between information technology systems can be interpreted at the data field level.

`000000000000000000000000bfdb50dc66c8df9fd9688d8fe5a0c34126427645`

```
-----Decoded View---------------
Found 1 constructor arguments :
```

`Arg [0] : 000000000000000000000000bfdb50dc66c8df9fd9688d8fe5a0c34126427645`
