# LRU Cache — Java

Custom implementation of an LRU (Least Recently Used) cache from scratch, 
using a HashMap + doubly linked list for O(1) time complexity on both 
get() and put() operations.

## Why
LRU caching is used in OS memory management, database buffer pools, and 
web caching layers. This implements the core mechanism without relying 
on Java's built-in LinkedHashMap.

## How to run
javac LRUCache.java
java LRUCache

## Complexity
- get(key): O(1)
- put(key, value): O(1)
- Space: O(capacity)
