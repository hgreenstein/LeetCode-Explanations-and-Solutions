# LeetCode-Explainations-and-Solutions
This repository contains various Leetcode problems that highlight valuable algorithms and data structures

## Language:
All code is provided in Java and my own personal Pseduo Code allowing for easy translation of these solutions to any target language.

## Summaries:
| Problem | Summary | Link To Full Solution|
| ------- | -------- | -------------------- |
| [1095. Find in Mountain Array](https://leetcode.com/problems/find-in-mountain-array/description/) | Run three different Binary Searches. The first one will find the peak of the mountain array, the second will search the left sorted portion for the target, the third the right sorted portion for the target. | [Markdown Solution](/1095.Find-in-Mountain-Array/Solution.md) |
| [1220. Count Vowel Permuatations](https://leetcode.com/problems/count-vowels-permutation/description/) | Initialize the base case as 1 way to start which each vowel. For each length greater than 1, apply the rules in reverse saying if the current vowel is `x`, add all the combinations of what the previous vowel could've been. Return all combinations of the final length added together | [Markdown Solution](1220.Count-Vowels-Permutation/Solution.md) 
| [210. Course Schedule II](https://leetcode.com/problems/course-schedule-ii/description/) | Create adjacency map from prerequisite list. Then run Topological Sort, DFS on every course, assuming you get true from all prerequisites and have taken them, take the current course in the result list. Keep cycle set for visiting, any cycle means false no valid path. | [Markdown Solution](210.Course-Schedule-II/Solution.md) | 
| [2642. Design Graph With Shortest Path Calculator](https://leetcode.com/problems/design-graph-with-shortest-path-calculator/description/) | Store the graph as an adjacency map, when called for the shortest path, run Dijkstra's shortest path algorithm between the two nodes, explained in solution. | [Markdown Solution](2642.Design-Graph-With-Shortest-Path-Calculator/Solution.md) |
| [779. K-th Symbol in Grammar](https://leetcode.com/problems/k-th-symbol-in-grammar/description/) | Run a directed DFS the height of the graph making a decision to go right or left at each node, inverting the value when going right. | [Markdown Solution](779.Kth-Symbol-in-Grammar/Solution.md) |
| [2050. Parallel Courses III](https://leetcode.com/problems/parallel-courses-iii/description/) | Find the longest continuous path in the graph formed by the prereq edges and adding the time to take each course at every node. DFS at every course and store the result in a DP table of index node. | [Markdown Solution](2050.Parallel-Courses-III/Solution.md) |
