
Time and Space Complexity

Sometimes, there are more than one way to solve a problem. We need to learn how to compare the performance different algorithms and choose the best one to solve a particular problem. While analyzing an algorithm, we mostly consider time complexity and space complexity. Time complexity of an algorithm quantifies the amount of time taken by an algorithm to run as a function of the length of the input. Similarly, Space complexity of an algorithm quantifies the amount of space or memory taken by an algorithm to run as a function of the length of the input.

Time and space complexity depends on lots of things like hardware, operating system, processors, etc. However, we don't consider any of these factors while analyzing the algorithm. We will only consider the execution time of an algorithm.

What Is Time Complexity?
Time complexity is the computational complexity describing the amount of time required for the execution of an algorithm. 
Time complexity measures the time taken by every statement of the algorithm. Hence, it highly depends on the size of processed data. Additionally, it helps to define the effectiveness of an algorithm and to evaluate its performance.

Because time complexity is an asymptotic function calculated from the size of input data, it takes as notation the mathematical symbols of Landau: \mathcal{O}, \Omega, and \Theta
. Here, each symbol defines different time complexity.

\mathcal{O} notation represents an upper bound for the time needed, describing the worst-case scenario. The notation \Omega gives a lower bound for the time needed.
It describes the best-case scenario. \Theta notation frames the time needed by an upper bound and a lower bound. It narrates the average-case scenario.


Space-Time Complexity Tradeoffs
All efforts made by analyzing time and space complexity lead to the algorithm’s efficiency.

But, when we can say that an algorithm is efficient? The answer seems to be obvious: it should be fast, and it should take the least amount of memory possible.

Unfortunately, in algorithmics, space and time are like two separate poles. Increasing speed will most often lead to increased memory consumption and vice-versa.

On the one side, we have merge sort, which is extremely fast but requires a lot of memory. On the other side, we have bubble sort, a slow algorithm but one that occupies minimal space. There are also some balanced ones like in-place heap sort. Its speed and space usage are not the best, but they’re acceptable.


![image](https://github.com/krrishec209/DSA_Java/assets/32902341/81e97836-13c0-4738-8dd6-dcd2cf0e7b00)


Some general time complexities are listed below with the input range for which they are accepted in competitive programming: 

![image](https://github.com/krrishec209/DSA_Java/assets/32902341/0995e790-7f26-41ae-b2e5-38704665aa9b)


![image](https://github.com/krrishec209/DSA_Java/assets/32902341/e3acb5f7-a361-49d4-8196-57ec831e9c11)

![image](https://github.com/krrishec209/DSA_Java/assets/32902341/c1f8f7ff-74b3-4a96-90be-d4635b4515dc)



References :

https://www.geeksforgeeks.org/time-complexity-and-space-complexity/

https://www.hackerearth.com/practice/basic-programming/complexity-analysis/time-and-space-complexity/tutorial/

https://www.crio.do/blog/time-complexity-explained/

https://www.baeldung.com/cs/time-vs-space-complexity

https://www.freecodecamp.org/news/big-o-cheat-sheet-time-complexity-chart/

https://www.freecodecamp.org/news/big-o-notation-why-it-matters-and-why-it-doesnt-1674cfa8a23c/

https://www.cs.cornell.edu/courses/cs312/2004fa/lectures/lecture16.htm

https://www.baeldung.com/cs/space-complexity

https://www.bigocheatsheet.com/
