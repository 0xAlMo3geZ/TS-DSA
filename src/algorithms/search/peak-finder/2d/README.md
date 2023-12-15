# Peak Finder (two-dimensional version)

A peak finder algorithm is designed to find a peak element in an array. In a two-dimensional array, a peak is an element that is greater than or equal to its neighboring elements in the same row and column.

## Complexity

**Time Complexity**: `O(n*log(m))` - with `n` rows and `m` columns, since we:

- split search area by two `log(m)` times;
- search a global maximum on every iteration with `O(n)` time complexity;

## Referenes

- [Youtube](https://youtu.be/HtSuA80QTyo?t=2851);
- [Understanding Peak-Finding](https://www.filipekberg.se/2014/02/10/understanding-peak-finding/);
