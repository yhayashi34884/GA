# Genetic Algorithm (GA)
 Find a solution of a two-variable function using a genetic algorithm.

## Requirements
- Python 3.4+

Install python libraries:

```bash
$ pip install numpy
$ pip install matplotlib
```

## Usage
```bash
$ git clone https://github.com/yhayashi34884/GA.git
$ cd GA
```

Execute following command.

```bash
$ python GA.py
```

result (for example).

```bash
************************ Number of generations : 1*************************
    x1 = [199, 183, 83, 46, 46, 47, 81]
    x2 = [151, 72, 251, 81, 122, 97, 236]
    y  = [130805, 54225, 258893, 28360, 61652, 39845, 229345]
Fitness = [34.21976, 43.93375, 0.0, 45.39813, 43.34375, 44.86111, 9.89008]
Solution = 28360
************************ Number of generations : 2*************************
    x1 = [199, 183, 46, 46, 47, 113, 208]
    x2 = [151, 72, 81, 122, 97, 58, 174]
    y  = [130805, 54225, 28360, 61652, 39845, 26225, 164368]
Fitness = [18.36386, 44.62926, 48.58875, 43.03397, 47.13673, 48.80478, 0.0]
Solution = 26225
・
・
・
************************ Number of generations : 130*************************
    x1 = [0, 0, 0, 0, 0, 1, 0]
    x2 = [0, 0, 0, 0, 0, 0, 0]
    y  = [0, 0, 0, 0, 0, 1, 0]
Fitness = [100.0, 100.0, 100.0, 100.0, 100.0, 0.0, 100.0]
Solution = 0
```
![Figure_ex](https://i.imgur.com/pZSI277.png)


## Contributing
Contributions, issues and feature requests are welcome.

## Author
- Github: [yhayashi34884](https://github.com/yhayashi34884)

## Show your support
Please STAR this repository if this software helped you!

## License
This software is released under the MIT License.
