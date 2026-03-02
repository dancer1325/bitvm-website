# Tree++ 
- == templating language -- for -- smarter Bitcoin contracts
- allows
  - advanced Bitcoin Scripts

## Advanced Scripting

- Evaluate constant expressions
- Parametrized templates
- Unroll loops
- Compose opcodes
- Library of composed opcodes
  - E.g., multiplication, bitwise XOR, bitwise shifts, Blake3, ...
- Hints
  - E.g. reduce: division to a multiplication, square root to a multiplication, modulo to a multiplication., ...
- Lookup tables
- Statefulness
  - Lamport signatures (message sizes: u8, u32, u160, ...)
  - Also Winternitz signatures
  - In the future maybe OP_CHECKSIGFROMSTACK

## Graphs of Transactions

- Compose Tree++ scripts into potentially large Taptrees
- Model contract logic in form of sequences and graphs of transactions
- Statefulness
  - Presigned transactions (also sighashes!)
  - Connector outputs
  - Trigger transactions
  - Timeouts
- Library of parametrizable sub-graphs
  - E.g. BitVM, zkp verifier, bridge

## Tooling 
- online editors
  - _Examples:_ [ide.scriptwiz](https://ide.scriptwiz.app)
- Package manager (Cargo)


