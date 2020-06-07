---
title: "L1-L2 RAM Hardware Cache Simulator"
excerpt: "Implementation of L1-L2 Hardware Cache Simulator. Simulates hit / miss / evict behaiours of cache by keeping track of dirty and valid bits in the cache. Uses LRU (lease-reently used) replacement policy and follows a write-back, write-allocate policy.<br/>"
collection: portfolio
---
The cache is represented by a multi-dimensional array of 'structs' where the struct represents a single cache-line. <br />
Number of cache lines are given by **E**, if **E** = 1, then a cache is a direct-mapped cache. This indicates the 'tag' value in the cache lines.<br />
Total number of sets, **S** are given by **2<sup>s</sup>**, where **'s'** is the number of set bits. <br /> 
Each cache line stores **'b'** bytes in it's cache. <br />
The total capacity of the cache is given by **S * B * E** 


[Link to repository](https://github.com/AND2797/CacheSim)
