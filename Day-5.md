## The UTXO Model (Unspent Transaction Outputs)

- UTXOs vs. Accounts: Unlike a bank (which adds/subtracts from a balance), Bitcoin tracks "shards" of value called UTXOs that are either spent or unspent.

- Input/Output Logic: Every transaction "destroys" an old UTXO and "creates" one or more new ones for the recipient.

- The Change Address: Why a wallet creates a new address to receive the "leftover" bitcoin when you spend only a portion of a UTXO.

- Transaction Size: Why a transaction with many small inputs (e.g., from mining) is more expensive in fees than one large input.

- Statelessness: How the UTXO model allows nodes to verify transactions in parallel, increasing efficiency compared to account-based systems.
