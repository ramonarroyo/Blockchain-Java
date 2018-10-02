# Blockchain 101

Basic Java blockchain with the purpose of understanding the technology.
```
Trying to mine block 1... 
Block Mined! : 000000cbe5817a0d3df548d230739f00ba3928fe9840629e0fc341bbf69537e5
Trying to mine block 2... 
Block Mined! : 000000617e5a0e304192832f425654a52c714b92531dc3130bd382ffa4671d9e
Trying to mine block 3... 
Block Mined! : 000000f9280101e639fecafe1f99b16084663152a3ca84731728e07780558706

Blockchain is valid: true
The blockchain: 
[
  {
    "hash": "000000cbe5817a0d3df548d230739f00ba3928fe9840629e0fc341bbf69537e5",
    "previousHash": "0",
    "data": "Genesis block",
    "timeStamp": 1538442592136,
    "nonce": 3611237
  },
  {
    "hash": "000000617e5a0e304192832f425654a52c714b92531dc3130bd382ffa4671d9e",
    "previousHash": "000000cbe5817a0d3df548d230739f00ba3928fe9840629e0fc341bbf69537e5",
    "data": "Second block",
    "timeStamp": 1538442596239,
    "nonce": 7043853
  },
  {
    "hash": "000000f9280101e639fecafe1f99b16084663152a3ca84731728e07780558706",
    "previousHash": "000000617e5a0e304192832f425654a52c714b92531dc3130bd382ffa4671d9e",
    "data": "Third block",
    "timeStamp": 1538442604622,
    "nonce": 60281465
  }
]

Process finished with exit code 0
```