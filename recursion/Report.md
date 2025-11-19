The difference between the Fibonacci recursive and iterative implementations 
is very easy to spot as soon as you run the code. The Recursive implementation 
takes much longer, specifically in the later steps because the work doubles with 
each step. The Time complexity is O(2^n). The iterative implementation has a time 
complexity of 0(n) and therefore can compute a Fibonacci sequence with a much 
higher n value much faster than recursive.

Same is seen in the LinkedList strategies. In the recursive I had to reduce the list size 
because of a stackOverflowError since it takes so much overhead for a recursive implementation. 
The Iterative implementation was much faster, bc the time complexity is O(1).
