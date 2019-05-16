## Linear Regression with Gradient Descent


**Step 1:** Take the derivative of the **Loss Function** for each parameter in it. In fancy Machine Learning Lingo, take the **Gradient** of the **Loss Function**

**Step 2:** Pick random values for the parameters.

**Step 3:** Plug the parameter values into the derivatives (**Gradient**).

**Step 4:** Calculate the Step Sizes: **Step Size = Slope x Learning Rate**

**Step 5:** Calculate the New Parameters: **New Parameter = Old Parameter - Step Size


Now go back to **Step 3** and repeat until **Step Size** is very small, or you reach the **Maximum Number of Steps**


**Let $X$ be the independent variable and $Y$ be the dependent variable**
**We will define a linear relationship between these two variables as follows:**

$${Y} = {m}{X} + c$$

$m$ is the *slope*
$c$ is the *intercept*


**Mean Squared Errors & Loss Function**

$$E = \frac{1}{n}\sum\limits_{i=0}^{n}({y_i} - \bar{y_i})^2$$
