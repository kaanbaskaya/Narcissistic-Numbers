The following parameters define the dimension up to which an approach runs. They can be configured to test and compare the performance and speed of the different approaches presented in this notebook.

maxdim =

The first step is to define a function that can check whether any given number is narcissistic. For this purpose, a quality function $QF$ is defined.

F[n_] := Sum[IntegerDigit[n][[i]]^IntegerLength[n], {i, 1, IntegerLength[n]}]

The quality function is derived by subtracting the digitpower sum of a number from the number itself. Squaring this ensures that the function yields only positive values. Consequently, narcissistic numbers represent not only the roots (zero) but also the global minimas of the quality function.

In optimizationtheory, this squared approach acts like a quadratic penalty function. The squaring mechanism penalizes larger deviations from the target value.
QF[n_] := (n - Sum[IntegerDigit[n][[i]]^IntegerLength[n], {i, 1, IntegerLength[n]}])^2

For all narcissistic numbers: QF(n) = 0
For all non narcissistic numbers: QF(n) is not 0

