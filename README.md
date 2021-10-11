# SALBP-1
This is an heuristic method to find a SALBP-1 solution with a modification to add handicapped workers using dictionaries to quickly compute a solution. 
A bit of background:
The idea behind the dictionaries as a entry dara type, was that by using the hashing functions and a lot of list comprenhension and hashing functions in python is possible to find good and quick results for this problem. 
As this is allocation problem in industrial engineering has a complexity of n^2 (meaning the possible space for solutions is nearly limitless) this approach could facilitate nearly optimal solutions.
This algorithm was tested using different instances and was tested also against the optimal method that was coded using Cplex, in the biggest instance tested the function value of the optimal solution was 18 and this algortithm found a solution using 20 stations (using the same entry data), although there are some optimizations possible I believe is an interesting approach using python to solve complex Industrial Engineering problems. 
