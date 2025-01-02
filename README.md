# PythonProCourse

# Lessons learned
## What are data structures? 
-> They are collections of data, the relationships among them and the functions/operations that can be applied to the data.
arrays: 
    -> [1,3,6,8]; 
    -> Their order is linear. 
    -> arr.append()
    -> Array is a pre-build data structure. Some other data structures can be built from scratch.
Some data structures are more efficient than others to do some tasks. (less time, less space) You need hands on with data structures, to know their positives and negatives so that you can write the most efficient algorithm.
## What is the need for complexity analysis?
Let's calculate the sum of (N-1) + (N - 2) + ... +1.
    -> N*(N-1)/2 uses only 3 operations.
    -> Iterating through all digits and adding them to a sum variable uses 2n-3 operations.
Which solution is better? Why do we care which one is better and what does better mean?
    -> In reality huge amount of data would lead to significant performance difference.
## What is time complexity? Which algorithm is faster?
-> This is not going to be measured in seconds, as there the input or amount of data would matter, also it is hardware specific.
-> Instead the amount of simple operations that the computer must do is counted.
-> As N or the input grows, in what propotion do the number of operations grow. We are interested in the general trend, not in precision.
