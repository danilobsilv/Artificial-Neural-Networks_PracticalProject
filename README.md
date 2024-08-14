<h1>Perceptron Classification Project</h1>

<h2>This project aims to implement and evaluate a Perceptron algorithm for classifying data in both linearly and non-linearly separable problems. The project is divided into three main parts:</h2>

<p>Solving a Linearly Separable Problem
Experimentation
Holdout Validation on a Non-Linearly Separable Problem
Part I – Solving a Linearly Separable Problem
In this part, we use a data file (dataAll.txt) to train a Perceptron to solve a linearly separable classification problem. The algorithm was implemented with the following aspects:<p>
<ul>
      <li>Activation function: step function with θ = 0.</li>
      <li>Learning rate η = 0.1.</li>
      <li>Weight initialization from a uniform distribution in the range (-0.5, +0.5).</li>
      <li>Training continues until convergence (no errors for all training examples).</li>
</ul>

<h2>Part II – Experimentation</h2>
<p>In this part, experiments were conducted to test the Perceptron’s performance across different learning rates and weight intervals. Each configuration was tested 10 times, and the results were analyzed to identify the best configuration.</p>

<h2>Part III – Holdout Validation on a Non-Linearly Separable Problem</h2>
<p>In this part, we use the dataHoldout.txt file to present an initial plot showing that this problem is not linearly separable. We then randomly split the data into training (70%) and testing (30%) sets. Despite the non-linear separability, we use the training data to obtain a separating line with the Perceptron.<br>The code performs holdout validation, generates confusion matrices, and calculates accuracy, precision, recall, and F-Score using sklearn.metrics. It also plots the decision boundaries for training and test data side by side.</p>

