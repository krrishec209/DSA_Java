
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


What is Time Complexity?

Time complexity is a concept in computer science that describes the amount of time an algorithm takes to run as a function of the length of the input. It's a crucial aspect of algorithm analysis as it helps understand how efficiently an algorithm performs, particularly as the size of the input data increases.

Key Points About Time Complexity
1. Measure of Efficiency: Time complexity provides a way to quantify the efficiency of an algorithm in terms of time. It's particularly important for understanding the scalability of an algorithm.

2. Big O Notation: Time complexity is often expressed using Big O notation, which provides an upper bound on the time requirements of an algorithm in the worst-case scenario. For example, O(n) denotes linear time complexity, meaning the time required grows linearly with the size of the input.

3. Types of Time Complexity:

Constant Time (O(1)): The execution time remains constant regardless of the input size.
Logarithmic Time (O(log n)): The execution time increases logarithmically with an increase in input size. Binary search is a classic example.
Linear Time (O(n)): The execution time increases linearly with the input size. For instance, finding an item in an unsorted list.
Quadratic Time (O(n²)): The time increases quadratically with the input size. This is common in algorithms with nested loops over the input data.
Exponential Time (O(2n)): The execution time doubles with each addition to the input data set. This is typical of algorithms that solve problems by computing all possible combinations.
4. Worst, Average, and Best Case: Time complexity can refer to the worst-case (usually represented), average-case, or best-case scenario for an algorithm's running time. The worst-case time complexity is the most commonly used because it guarantees the maximum time taken for any input.

5. Impact on Real-world Applications: In practical scenarios, the time complexity of an algorithm can significantly impact its usability. For large input sizes, an algorithm with a lower time complexity will generally perform better than one with a higher time complexity.

What is Space Complexity?

Space complexity is a term in computer science used to describe the amount of memory space required by an algorithm to run as a function of the length of the input. It is an important metric for understanding how efficient an algorithm is in terms of memory usage, especially in environments where memory resources are limited.

Key Points About Space Complexity
1. Memory Usage Measurement: Space complexity measures the total amount of memory or storage space an algorithm needs to complete. This includes both the space taken up by the input data and any additional space used by the algorithm for variables, data structures, and function calls.

2. Big O Notation: Like time complexity, space complexity is often expressed using Big O notation. This notation provides an upper bound on the space requirements of an algorithm in the worst-case scenario. For example, O(n) indicates that the space required grows linearly with the input size.

3. Types of Space Complexity:

Constant Space (O(1)): The algorithm uses a fixed amount of memory space regardless of the input size. For example, an algorithm that swaps two numbers.
Linear Space (O(n)): The memory required grows linearly with the input size. An example is creating a list of 'n' elements.
Quadratic Space (O(n²)): The space requirement grows quadratically with the input size, commonly seen in algorithms that create two-dimensional arrays based on the input size.
4. Components of Space Complexity:

Static Part: The fixed space required by the algorithm (for code, constants, and simple variables).
Dynamic Part: The variable space required by the algorithm during its execution, including space for dynamic data structures, stack space for recursion, and so on.
Impact on Algorithm Design: Space complexity is a crucial consideration when designing algorithms, particularly for systems with limited memory resources like embedded systems or mobile devices.
5. Trade-off with Time Complexity: Sometimes, there's a trade-off between space and time complexity. For example, using extra space for caching (space complexity) can reduce the time it takes to retrieve data (time complexity).



![image](https://github.com/krrishec209/DSA_Java/assets/32902341/2429ea7a-93b0-43aa-b97a-80e60adfcfe7)


Similarities Between Time Complexity and Space Complexity
Below is a table showcasing the similarities between time complexity and space complexity

![image](https://github.com/krrishec209/DSA_Java/assets/32902341/b8a9f587-be5b-4903-9030-73a2e151bed3)

![image](https://github.com/krrishec209/DSA_Java/assets/32902341/c1377845-28e9-4137-af73-6b4efeac158e)



![image](https://github.com/krrishec209/DSA_Java/assets/32902341/81e97836-13c0-4738-8dd6-dcd2cf0e7b00)


Some general time complexities are listed below with the input range for which they are accepted in competitive programming: 

![image](https://github.com/krrishec209/DSA_Java/assets/32902341/0995e790-7f26-41ae-b2e5-38704665aa9b)


![image](https://github.com/krrishec209/DSA_Java/assets/32902341/e3acb5f7-a361-49d4-8196-57ec831e9c11)

![image](https://github.com/krrishec209/DSA_Java/assets/32902341/c1f8f7ff-74b3-4a96-90be-d4635b4515dc)


![image](https://github.com/krrishec209/DSA_Java/assets/32902341/99388c03-2330-4219-b25b-9ce4a6e605d6)




References :

https://www.geeksforgeeks.org/time-complexity-and-space-complexity/

https://www.hackerearth.com/practice/basic-programming/complexity-analysis/time-and-space-complexity/tutorial/

https://www.crio.do/blog/time-complexity-explained/

https://www.baeldung.com/cs/time-vs-space-complexity

https://www.freecodecamp.org/news/big-o-cheat-sheet-time-complexity-chart/

https://www.freecodecamp.org/news/big-o-notation-why-it-matters-and-why-it-doesnt-1674cfa8a23c/

https://www.shiksha.com/online-courses/articles/difference-between-time-complexity-and-space-complexity-blogId-151433

https://www.cs.cornell.edu/courses/cs312/2004fa/lectures/lecture16.htm

https://www.baeldung.com/cs/space-complexity

https://www.bigocheatsheet.com/
