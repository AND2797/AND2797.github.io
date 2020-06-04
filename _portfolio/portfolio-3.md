---
title: "Dynamic Memory Allocator"
excerpt: "Implementation of malloc(), free(), realloc() and calloc() functions.<br/>"
collection: portfolio
---

Implemented using a circular - segregated linked list data structure that explicitly maintains an explicit linked list of free blocks corresponding to different memory sizes so one does not have to search over all the blocks in the heap.<br/>
Reduced internal fragementation in free-blocks by reducing meta-data overhead in the allocated blocks. 

[Link to repository](https://github.com/AND2797/malloc)
