This directory contains sample test trajectories that can be used to test a trajectory clustering algorihm.

Each test takes the form of a single CSV file named `single_input_trajectory.csv`.

The file is then encoded as follows:
```
0:0,1:1

0:0,1:1
```
where line 1 refers to the value that should be reported by the clustering algorihm.
Line 2 should be empty
Line 3 and followings described the input trajectories given to the clustering algorithm.
