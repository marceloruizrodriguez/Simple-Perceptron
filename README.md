# Simple-Perceptron

#### The following implementation of the perceptron uses the numerical definition of the derivative for the gradient descent algorithm. A small value of epsilon was used to iterate between the W weights, since the Ws are the values we want to optimize in the cost function:

 \begin{align}
 \frac{f(x+\varepsilon )-f(x)}{\varepsilon }
 \end{align}

#### W's are updated using the following formula:

\begin{align}
W_{i+1}=W_i - \eta \frac{\partial J}{\partial W_i} 
\end{align}

#### The J-cost function is determined by:

 \begin{align}
(y-\hat{y})^2
\end{align}

#### where $y$ is the actual value and $ \hat{y} $ is the predicted value.
