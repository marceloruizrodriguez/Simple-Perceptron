# Simple-Perceptron

#### The following implementation of the perceptron uses the numerical definition of the derivative for the gradient descent algorithm. A small value of epsilon was used to iterate between the W weights, since the Ws are the values we want to optimize in the cost function:

![](http://www.sciweavers.org/tex2img.php?eq=%20%5Cfrac%7Bf%28x%2B%5Cvarepsilon%20%29-f%28x%29%7D%7B%5Cvarepsilon%20%7D&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0)

#### W's are updated using the following formula:

![](http://www.sciweavers.org/tex2img.php?eq=W_%7Bi%2B1%7D%3DW_i%20-%20%5Ceta%20%5Cfrac%7B%5Cpartial%20J%7D%7B%5Cpartial%20W_i%7D%20&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0)


#### The J-cost function is determined by:

![](http://www.sciweavers.org/tex2img.php?eq=%28y-%5Chat%7By%7D%29%5E2&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0)

#### where $y$ is the actual value and $ \hat{y} $ is the predicted value.
