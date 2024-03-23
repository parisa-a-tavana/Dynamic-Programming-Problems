# Unique Paths in a Grid with Obstacles
<br>
an agent can move left, right, or diagonal in a 6*6 grid. It also should not run into the barriers. We want to count all the unique ways the agent can move from A to B.
<br>

![Image 1](images/grid.jpg)
<br> 

![Image 2](images/grid_algorithm.jpg)
<br> 

![Image 3](images/grid_final_answer.jpg)
<br> 
<br>
# Edit Distance
<br>
<br>
Google will suggest the possible phrase of a misspelled word. For example, in the figure below, the word"inplememtation" is searched, and Google returns its search results for the correct spelling of the word "implementation".
<br>

![Image 4](images/edit_google.jpg)
<br> 
As a simple solution, we can define criteria by which we can have the best possible prediction of the possible string. If we call the searched string s1 and the predicted string s2, our criterion should return the similarity value between the two defined strings. Then, among the obtained values, we can return the most appropriate string s2.
<br>

![Image 5](images/edit.jpg)
<br> 
We want to get from the string 1s to 2s using three operators: deletion, insertion, Substitution, and replacement. Among the defined operators, the insertion and deletion operators will have 1 cost each and the substitution operator will have 2 costs. For example, there are two ways to get from the word "index" to "inside".
<br>
<br>
We want to find the least cost c to get the word s2 from s1. in word suggestion the word with the smalles c is the best candidate.
<br>

![Image 6](images/edit_algorithm.jpg)
<br> 
<br>

![Image 7](images/edit_algorithm2.jpg)
<br> 

![Image 8](images/edit_answer1.jpg)
<br> 

![Image 9](images/edit_answer2.jpg)
<br> 

<br>
# Longest Common Subsequence
<br>
<br>
The sub-series of the string s is equal to any subset of its characters whose order in the sub-series is similar to the order of their placement in the string s. For example, the string "aca" is a sub-series of three of the main string "abcba".
<br>

![Image 10](images/sequence.jpg)
<br> 
We want to find the longest common subsequence of 2 stirngs.

![Image 11](images/sequence_algorithm.jpg)
<br> 

![Image 12](images/sequence_answer1.jpg)
<br> 

![Image 13](images/sequence_answer2.jpg)
<br> 
<br> 
<br>
# Calculate Sum by Restating the Problem
<br>
<br>
We want to find the sum of the sequence below:
<br>

![Image 14](images/find_sum.jpg)
<br>

![Image 15](images/sum_restate.jpg)
<br>

![Image 16](images/sum_algorithm.jpg)
<br>

![Image 17](images/sum_answer.jpg)
<br>
