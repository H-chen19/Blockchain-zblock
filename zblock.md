# ZBLOCK CHAIN USING PoW

### Installations:
- Go Ethereum  ---(https://geth.ethereum.org/)
- MyCrypto Desktop App  ---(https://www.mycrypto.com/)

Go Ethereum: Is a implementation of the Ethereum protocol that contains tools to create our own blockchain.

MyCrypto: Is an open-source client-site tool for generating ether wallets and allowing you to interact directly with the blockchain. 


### Create A Private Chain

1. Through a terminal window (GitBash in Windows), navigate to the Go Ethereum folder. 
2. Type the following command: 

```bash
./puppeth
``` 
        
        *Note: PUPPETH is a CLI wizard that aids in 
        creating a new ETH network*

3. Name your network. In my case: zblock
4. Select option '2. Configure new genesis', and the option '1. Create new genesis from scrath'.
5. Select option '1. Proof of Work'.
6. In the next step, need to pass one or more addresses that are associated with the cloud mnemonic created in the previous part. These are the addresses you want to pre-fund.
7. Hit enter for the pre-fund option. By default, the addresses will be pre-funded with 1 wei. 
8. Input a 'CHAIN ID' that you like, preferable a three digit one. 

        *CHAIN ID: is a blockchain setting that affects the forming of an address. The linkage in the transaction binary format between the address and chain ID makes it impossible to move transactions between different blockchain networks.*

9. Next, select '2. Manage exising genesis'. Then, type '2' for Export genesis configurations

    *'From there you will see four different json files like below picture.'*

![json_files](json_files.png)









