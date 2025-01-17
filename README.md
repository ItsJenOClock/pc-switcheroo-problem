# Switcheroo Problem

Problem belonging to the post-classroom Mock Interview Question Repository.

## Problem Statement

We are interested in writing a function that shuffles a linked list by swapping adjacent items.

For example, if we have a linked list with the following elements:

a → b → c → d → e → f

after shuffling, we should get the following output list:

b → a → d → c → f → e

Notice that adjacent items have swapped position:

- a swapped with b
- c swapped with d
- e swapped with f

If there are an odd number of elements, the tail should not change position.

For example, if we have a linked list with five elements:

a → b → c → d → e

After shuffling, 'e' should remain the tail.

b → a → d → c → e

Notice that the first four elements swapped position like before, but that 'e' did not move.

## Examples

### Example 1

Shuffling the following list

a → b → c → d → e → f

produces

b → a → d → c → f → e

### Example 2

Shuffling the following list

a → b → c → d → e

produces

b → a → d → c → e

### Example 3

Shuffling the following list

7 → 2

produces

2 → 7

### Example 4

Shuffling the following list

a

produces

a
