A proof of concept of a frontend-only block explorer for ganache.


## Usage

Go to the configuration tab and set the RPC URL of your local instance (`http://localhost:8545` is used by default).

### Known ABIs

You can also add known ABIs. When a transaction is inspected, all events that belong to a known ABI will be properly parsed.

### Known addresses

There's a sort of "address book" where you can associate names to addresses. These names show up in the "From" and "To" fields of the transaction. (It would be nice to also show them in the parsed events data).

