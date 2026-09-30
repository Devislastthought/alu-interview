# Minimum Operations

Given a text file with a single `H`, and an editor that only supports
`Copy All` and `Paste`, `minOperations(n)` returns the fewest number of
operations needed to get exactly `n` `H` characters (0 if impossible).

## Approach
The answer is the sum of the prime factors of `n`.
Example: 12 = 2 * 2 * 3 -> 2 + 2 + 3 = 7 operations.

## Usage
```
chmod +x 0-minoperations.py 0-main.py
./0-main.py
```

## Files
- `0-minoperations.py`: the `minOperations(n)` function
- `0-main.py`: example test file
