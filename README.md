A beginner-friendly machine learning project implementing Linear Regression from scratch with Gradient Descent for parameter optimization.

📌 Overview

This project demonstrates how linear regression works internally without using high-level machine learning libraries.
It explains:

How to model a linear relationship between input X and output Y

How to compute predictions

How to calculate cost (Mean Squared Error)

How to update parameters using gradient descent

How to track loss reduction over training

This is a great reference for understanding the fundamentals of machine learning.

🎯 Features
✔️ Gradient Descent Optimizer

Manual implementation of parameter updates:

𝜃
=
𝜃
−
𝛼
⋅
∂
𝐽
∂
𝜃
θ=θ−α⋅
∂θ
∂J
	​

✔️ Cost Function (MSE)

Measures accuracy of the linear model:

𝐽
=
1
2
𝑚
∑
(
ℎ
(
𝑥
)
−
𝑦
)
2
J=
2m
1
	​

∑(h(x)−y)
2
✔️ Visualization

Loss vs. Iterations

Best-fit regression line

✔️ Easy to Modify

Change:

Learning rate

Number of iterations

Dataset

🧠 Mathematical Background
Hypothesis function
ℎ
𝜃
(
𝑥
)
=
𝜃
0
+
𝜃
1
𝑥
h
θ
	​

(x)=θ
0
	​

+θ
1
	​

x
Cost function
𝐽
(
𝜃
0
,
𝜃
1
)
=
1
2
𝑚
∑
𝑖
=
1
𝑚
(
ℎ
𝜃
(
𝑥
𝑖
)
−
𝑦
𝑖
)
2
J(θ
0
	​

,θ
1
	​

)=
2m
1
	​

i=1
∑
m
	​

(h
θ
	​

(x
i
	​

)−y
i
	​

)
2
Gradient Descent updates
𝜃
0
:
=
𝜃
0
−
𝛼
⋅
1
𝑚
∑
(
ℎ
𝜃
(
𝑥
𝑖
)
−
𝑦
𝑖
)
θ
0
	​

:=θ
0
	​

−α⋅
m
1
	​

∑(h
θ
	​

(x
i
	​

)−y
i
	​

)
𝜃
1
:
=
𝜃
1
−
𝛼
⋅
1
𝑚
∑
[
(
ℎ
𝜃
(
𝑥
𝑖
)
−
𝑦
𝑖
)
𝑥
𝑖
]
θ
1
	​

:=θ
1
	​

−α⋅
m
1
	​

∑[(h
θ
	​

(x
i
	​

)−y
i
	​

)x
i
	​

]
📁 Project Structure
├── data/
│   └── dataset.csv
├── linear_regression.py
├── gradient_descent.py
├── visualize.py
├── README.md
└── requirements.txt
