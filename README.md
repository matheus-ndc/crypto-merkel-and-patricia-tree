# Implementação de árvores binárias Merkel e Patricia para criptografia no Node.js

Node.js implementation of Merkel tree and Patricia Tree used in Ethereum blockchain

## MerkelTree

A classe possuiu os seguintes métodos:

1. `createTree(transactionList)`

   Adds layers to the tree for the passed transaction list

2. `verify(transaction)`

   Checks if the transaction is valid or not

## PatriciaTrie

A classe possui os seguintes métodos:

1. `add(transaction)`

   Add transaction to the trie

2. `get(hash) `

   Get transaction from the trie for the passed trie

3. `remove(hash) `

   Remove the trnasaction with the hash if found

---

<p align="center">Feito com ❤️ por <strong>Matheus do Carmo</strong></p>
