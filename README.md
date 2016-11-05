gSpan
==============

gSpan algorithm in data mining

**Features:**

1. Support basic sub-structure mining.

2. Target: frequent subgraphs, connected, labeled, undirected, single-machine, embedded instead of induced
3. Require: all graphs can be stored in memory(if not, algorithm may have to change, the memory cost usually < 1G)

**Usage:**
	
use make to generate the executable, that is, dig:
```	
make
```
run on your graph.data with the support and you will get the result:
```	
./dig file 0.07 [ans.txt]
```
0.1 for big graph, while 0.5 for small graph

**Notice:**

Notice the difference between > and >= when considering minsup, and the float2integer is also a problem!
this may cause result different, but this is not our fault!

**TODO:**

1. bugs exist(less results)
2. induced version
3. distributed version

**LOGS:**
11/01/2016
1. finish the basic version of this project
2. do some optimizations


**Reference:**

1. http://www.cs.ucsb.edu/~xyan/software/gSpan.htm
2. http://www.tuicool.com/articles/FvaEJju
3. source codes on github

