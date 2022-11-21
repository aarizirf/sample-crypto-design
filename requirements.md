### Crypto Design Specs
1. If the current block number (`block.number`) is a prime number, then reward the miner with 5X the amount.
2. If the date of block creation is January 1st, "Happy New Year!" is added to the message data (`msg.data`).
3. If the block miner's address (`block.coinbase`) contains the last 2 characters of the current block number (`block.number`), reward the miner with 420% (or 4.2x) the amount.
