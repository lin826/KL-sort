# KL-sort

Sort Implimentation of a (k, l)-nearly sorted relation R.

## Compile

The default `BINARY_FILE_NAME` is `a.out`.

```sh
g++ main.cpp <BINARY_FILE_NAME>
```

# Run

If compile without specifying `BINARY_FILE_NAME`, the running commend would be `./a.out`. The sorted result would cout on the screen.

```sh
$ ./<BINARY_FILE_NAME>
1 2 3 4 5 6 7 8 9 10 
```

## Reference

Sagi Ben-Moshe, Yaron Kanza, Eldar Fischer, Arie Matsliah, Mani Fischer, and Carl Staelin. 2011. Detecting and exploiting near-sortedness for efficient relational query evaluation. In Proceedings of the 14th International Conference on Database Theory (ICDT '11). Association for Computing Machinery, New York, NY, USA, 256–267. https://doi.org/10.1145/1938551.1938584
