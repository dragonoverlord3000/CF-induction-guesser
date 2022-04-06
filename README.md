# CF-induction-guesser
A jupyter notebook showcasing 3 simple methods for guessing polynomial sequences 
$c_k$ and $d_k$ such that:
<img src="https://latex.codecogs.com/svg.image?a_k&space;=&space;c_k&space;&plus;&space;d_{k&plus;1}\\b_k&space;=&space;-c_kd_k" title="https://latex.codecogs.com/svg.image?a_k = c_k + d_{k+1}\\b_k = -c_kd_k" />
<!-- \begin{align*}
    a_k &= c_k + d_{k+1} \\
    b_k &= -c_k d_k
\end{align*} -->
Where $a_k$ and $b_k$ are integer sequences defining a generalized PCF in the 
following way:
\begin{equation*}
    \alpha = a_0 + \frac{b_1}{a_1 + \frac{b_2}{a_2 + \frac{b_3}{a_3 + \dots}}}
\end{equation*}
By solving systems of nonlinear equations as described in \url{paper???}.



