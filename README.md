The first time I found about George Dantzing was in a science magazine we had that time discussing subjects of scinece and fun facts.
And what really cauaght my attention was he, as a graduate student, was late to his class and found two mathematical problem which he thought they were assignments. So, he did what he had to do and solve the unsolved problems without knowing what he has done.
That was enough for me as a 13 14 years old boy to find his motive and my story started... if you know me then you know the rest :)

<div align="center">
<img src="https://news.stanford.edu/__data/assets/image/0016/82501/Dantzig_vertical.jpeg" width="295" height="450">
</div>

But who was George Dantzig. **George Bernard Dantzig** (1914-2005) was an American mathematician and mostly known for devising the Simplex Algorithm, a foundational method for solving linear programming problems.
He educated at UC Berkeley and he worked on military logistics during World War II and later held academic positions at Berkeley and Stanford. 
His Simplex Algorithm is easy to catch and beautiful to know. The algorithm is developed for a standard linear mathematical problem with the follwoing form:
<div align="center">
  
$max Z = c_1 x_1 + c_2 x_2 + \cdots + c_n x_n$

*S.t.*

$Ax \leq b$<br>
$x \geq 0$  
</div>

where:

- $Z$ is the objective function.
- $A$ is the constraint matrix.
- $x$ is the vector of decision variables.
- $b$ is the right-hand side vector.
- $c$ is the cost coefficient vector.

Once, the model is defined and all the variables are in the standard form, algorithms starts:

    1. Convert the problem into Standard Form by adding slack variables.
    2. Construct the Simplex Tableau.
    3. Iterate:
      * Select entering variable (most negative in the objective row).
      * Select leaving variable (smallest positive ratio in the right-hand side).
      * Perform pivot operation to update the tableau.
    4. Repeat until optimality condition is met (no negative coefficients in the objective row).
