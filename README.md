Today we are going to explore the RLP structure, which we are going to use to build an naive implementation of an in-memory calculator. Imagine you produce expressions S-expressions like `(* (+ 1 2) (+ 1 2))`. Wouldn't it be great to just pass this expression to some contract and receive 9 as a return? Well this example shows you how to approach something line this. The main focus of this however, is to teach you [RLP](https://github.com/ethereum/wiki/wiki/RLP), one of the core technologies which drives Ethereum.
You can explore RLP also with [this](https://www.npmjs.com/package/rlp) package.