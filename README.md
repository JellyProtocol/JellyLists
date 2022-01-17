# JellyLists

## Lists

Lists are in CSV format, starting with the header

```
account,amount
```

Folled by the account and the token amount in wei. 

eg 
```
account,amount
0x5082DC20Afe9935C068fB94CB7666959390C479B,100000000000000000000
```

## Proofs

Merkle proofs in json format. 

Includes the merkleRoot and tokenTotal in hex format, as well as each user claim.
