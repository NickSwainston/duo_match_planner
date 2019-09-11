# duo_match_planner

Will organise several rounds of games of duos playing against each other with the minimum amount of playing with the same people

Example use case (replace numbers with names):
```bash
python duos_sorter.py -p 1 2 3 4 5 6 7 8
```

Outputs:
```bash
Round #1:
          Court: 1
             Pair 1: 1   2
             Pair 2: 3   4
          Court: 2
             Pair 1: 5   6
             Pair 2: 7   8
Round #2:
          Court: 1
             Pair 1: 1   3
             Pair 2: 5   7
          Court: 2
             Pair 1: 2   4
             Pair 2: 6   8
Round #3:
          Court: 1
             Pair 1: 1   5
             Pair 2: 2   6
          Court: 2
             Pair 1: 3   7
             Pair 2: 4   8
Round #4:
          Court: 1
             Pair 1: 1   4
             Pair 2: 5   8
          Court: 2
             Pair 1: 2   3
             Pair 2: 6   7
Round #5:
          Court: 1
             Pair 1: 1   6
             Pair 2: 2   5
          Court: 2
             Pair 1: 3   8
             Pair 2: 4   7
Round #6:
          Court: 1
             Pair 1: 1   7
             Pair 2: 2   8
          Court: 2
             Pair 1: 3   5
             Pair 2: 4   6
Round #7:
          Court: 1
             Pair 1: 1   8
             Pair 2: 2   7
          Court: 2
             Pair 1: 3   6
             Pair 2: 4   5
Out of possible matches
```
