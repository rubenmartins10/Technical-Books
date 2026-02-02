
- An algorithm is a set of instructions for performing a task.

- Binary search is an algorithm. Its input is a sorted list of elements.

- If the element you are looking for is in the list, binary search returns its position; otherwise, it returns `None`.

- For a list of $n$ numbers, binary search takes $\log n$ steps to return the correct value, whereas simple search takes $n$ steps.

- Binary search only works when the list is sorted.

- The maximum number of attempts equals the size of the list. This is called **linear time**.

- Binary search runs in **logarithmic time**.

- Big O notation allows you to compare the number of operations.
    - Big O -> $O(n)$, where $O(n)$ represents the number of operations.

- 5 Big O run times, from fastest to slowest:
    - $O(\log n)$, also known as logarithmic time. **Binary Search**.
    - $O(n)$, known as linear time. **Simple Search**.
    - $O(n \cdot \log n)$, a fast sorting algorithm. **Quicksort**.
    - $O(n^2)$, a slow sorting algorithm. **Selection Sort**.
    - $O(n!)$, a very slow algorithm.

- You cannot directly convert a Big O run time into a specific number of operations, but this is sufficient for now. The main takeaways from this chapter are:
    - Algorithm speed isn't measured in seconds, but by the growth in the number of operations.
    - We discuss how quickly an algorithm's run time increases as the number of elements increases.
    - Run time for algorithms is expressed using Big O notation.
    - $O(\log n)$ is **faster** than $O(n)$, and the gap between them grows as the list gets larger.