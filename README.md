# Data Structure Algorithms

Studies based on https://www.youtube.com/watch?v=vnSOoboNNQU&amp;list=PLUMphNAA9pmrgS3ngMRfvS1MnDzjyRVeT&amp;index=1

## Topics

- Data Structures Fundalmentals;
- Fundamentals of Algorithm Analysis;
- Array & Sets;
- Linked Lists;
- Stack;
- Queues;
- Recursion;
- Hash tables & Sets;
- Trees
  - Binary Tress;
  - Binary Search Trees;
  - Red black Trees;
  - AVL Trees;
  - B-Tree and B+Tree;
  - Tries;
  - Heaps
- Priority Queues;
- Graphs;
- Algorithms
  - Sorting;
  - Searching;
  - Greedy;
- Dynamic programming;

## How it works

- Definition
- Implementation (Ruby and JavaScript)
- Usecases 


## What are data structure?

A data structure is a way of organizing and storing data in a computer so that it can be accessed and manipulated efficiently. It defines the relationships between data elements and the operations that can be performed on them.

Books:

- [Data Structures and Algorithms Made Easy: Data Structures and Algorithmic Puzzles](https://www.amazon.com/Data-Structures-Algorithms-Made-Easy/dp/819324527X)
- [Algoritmos - Teoria e Prática](https://www.amazon.com.br/Algoritmos-Teoria-Pr%C3%A1tica-Thomas-Cormen/dp/8535236996/ref=asc_df_8535236996/)

- Interface (ADT) (Abstract Data Type)
  > It's a contract
  > Think on a list
  > you can search; you can get a value; you can set a value...
- Structure

## How we can measure?

```javascript
const printEven = () => {
  for ( let i = 2; i <= 100; i++ ) {
    if ( i % 2 === 0 ) {
      console.log(i);
    }
  }
}
```

- Count on a time?

```javascript
console.time('evens')
printEven()
console.time('evens')
```

- Count based on instructions?

```
1. let i = 0
2. i <= 100
3. i++
4. if
5. i % 2 === 0
6. console.log
```

- And if we change the instructions?

```javascript
const printEven = () => {
  for ( let i = 2; i <= 100; i += 2 ) {
    if ( i % 2 === 0 ) {
      console.log(i);
    }
  }
}
```

We have a better implementation. We have the same instructions, but less steps due to `i += 2`

