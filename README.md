# LetsMakeBlockChain
An attempt to build basic principles of blockchain

Blockchain is basically a chain of blocks. Each block contains number of valid transactions that are confirmed by the consensus protocol among the nodes in a blocchain. The chain is NOT a single chain but  rather a multiple number of chains in the form of tree like structure. Hence, each block has a parent. For the current block, the parent is basically the previously refernced block. The current block stores hash value of previous block in its header to identify parent. In  some cases of bitcoin, a situation may arise when multiple blocks can have single parent.For Example- Two miners identifying a valid transaction at the same time, both broadcasting valid blocks to network but only is accepted by resolving.


