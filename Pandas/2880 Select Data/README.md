<h4>2880. Select Data</h4>

<pre>DataFrame students
+-------------+--------+
| Column Name | Type   |
+-------------+--------+
| student_id  | int    |
| name        | object |
| age         | int    |
+-------------+--------+</pre>

<p>Write a solution to select the name and age of the student with <code>student_id = 101</code>.</p>

<p>The result format is in the following example.</p>

<p>&nbsp;</p>
<pre><strong>Example 1:
Input:</strong>
+------------+---------+-----+
| student_id | name    | age |
+------------+---------+-----+
| 101        | Ulysses | 13  |
| 53         | William | 10  |
| 128        | Henry   | 6   |
| 3          | Henry   | 11  |
+------------+---------+-----+
<strong>Output:</strong>
+---------+-----+
| name    | age | 
+---------+-----+
| Ulysses | 13  |
+---------+-----+
<strong>Explanation:
</strong>Student Ulysses has student_id = 101, we select the name and age.</pre>

<p>&nbsp;</p>
<small>Copyright ©️ 2024 LeetCode All rights reserved</small>