# My testing results

## CPU
| computation     | S | D |
|:------------|:---------|:---------|
| add (chapter 5) | 77 ms  |  160 ms |
| arithmatic (chapter 5) | 320 ms |  450 ms |

## GPU
| computation     | V100 (S) | V100 (D) | 2080ti (S) | 2080ti (D) |
|:------------|:---------|:---------|:---------|:---------|
| add (chapter 5) | 1.5 ms | 3.0 ms |  2.1 ms |  4.3 ms |
| add+memcpy (chapter 5) | not used | not used | 130 ms  |  250 ms |
| arithmatic (chapter 5) | 11 ms |  28 ms | 15 ms | 450 ms |
| copy (chapter 7) | 1.1 ms |  2.0 ms | - | - |
| coalesced read (chapter 7) | 4.5 ms |  6.2 ms |  | - |
| coalesced write (chapter 7) | 1.6 ms |  2.2 ms | - | - |
| ldg (chapter 7) | 1.6 ms |  2.2 ms | - | - |
