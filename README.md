# hledger Example

This example is intended for bidipeppercrap business.

## Running

Always run with `--strict` to prevent any accounts mistyping.
```
hledger -f ./main.journal --strict reg "cash in shop$"

// or

hledger-web -f ./main.journal --strict
````
