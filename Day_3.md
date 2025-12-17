# Consensus Algorithm of Bitcoin: Proof-of-Work[POW]
- Bitcoin operates on a concept of Consensus Algorithm, an algorithm where the nodes agree to a state of blockchain.
- Proof-of-Work involves solving complex computational algorithm to validate transactions happening on Bitcoin.
- In PoW, me aim to find a number as - "Nonce->Hash" less than or equal to a target hash value, involving alot of processing or "mining".
- For Mining, the miners are awarded with the the transaction fees + some bitcoins. Every 4 years, the bitcoin reward is halved.
- Each block of Bitcoin comprises of a Nonce, Target and a Merkel Tree, alongside Cryptographic Hash and Transaction Records.
- Merkel Tree is a Binary Tree of transactions where leaf nodes represents a transaction and a hash pointer of a pair of these nodes makes up the parent nodes.
- This process goes until we have only one node left called Merkle Root, a Hash of all the transactions and any mismatch of transactions causes elimination of that false transaction. 
