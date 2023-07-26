# Arrays

(https://www.youtube.com/watch?v=vnSOoboNNQU&list=PLUMphNAA9pmrgS3ngMRfvS1MnDzjyRVeT&index=1)

## Analising Static Arrays

Operations:

- get(index)
- set_at(value, index) (static)
- ~~delete(index)~~
- search(value)

|0     |1    |2  |3      |4    |
|------|-----|---|-------|-----| 
|banana|manga|uva|laranja|jambo|

If I want to take "laranja":

array(addr(array) + 3)

|size/capacity| 5 |
|-------------| - |
|length       | 5 |

How much steps? 
n = 5 (total of things on the array, since is static)

## Analising Dynamic Arrays

Operations:

- get(index)
- set_at(value, index) (static)
- delete(index)
- search(value)

|0     |1    |2  |3      |4    |
|------|-----|---|-------|-----| 
|banana|manga|uva||

If I want to add things?

- If in the beginning:
  - I'll need to move the other elements to the end:
    - steps? 
      - 2+n (n length of arrays)

- If in the end?
  - steps?
    - n - 1

If I want to remove?

- Once I remove, I need to reestructure (shift) my array 
  - Steps?
    - 2 + (n - 1)

If I want to search?

- steps?
  - n - why we need to check about the value itself

|size/capacity| 5 |
|-------------| - |
|length       | 3 |

How much steps? 
n = length (total of things on the array, since is static)


## Interesting

A dynamic array will need a new location/address inside of memory - will need a new space;

We will need a copy.

