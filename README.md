# ```statmi```: Mutual information and other entropy-related measures for data

```statmi``` is an information theory package for use in statistics, machine learning, data analysis, econometrics, etc.

## Conceptual introduction to MI

Mutual information <img src="https://render.githubusercontent.com/render/math?math=I(X:Y)"> is a measure based on Shannon entropy <img src="https://render.githubusercontent.com/render/math?math=h">. <img src="https://render.githubusercontent.com/render/math?math=h"> is a measure of uncertainty, and <img src="https://render.githubusercontent.com/render/math?math=I"> can be thought of as the shared information between <img src="https://render.githubusercontent.com/render/math?math=X"> and <img src="https://render.githubusercontent.com/render/math?math=Y">, alternatively the reduction in uncertainty for a random variable [vector] given another random variable [vector] (note that order does not matter, i.e. <img src="https://render.githubusercontent.com/render/math?math=I(X:Y) = I(Y:X)">). Conditional mutual information <img src="https://render.githubusercontent.com/render/math?math=I(Y:X|Z)"> provides the shared information between <img src="https://render.githubusercontent.com/render/math?math=X"> and <img src="https://render.githubusercontent.com/render/math?math=Y"> with <img src="https://render.githubusercontent.com/render/math?math=X"> conditioned on <img src="https://render.githubusercontent.com/render/math?math=Z">, that is if all information about <img src="https://render.githubusercontent.com/render/math?math=Y"> which is contained in <img src="https://render.githubusercontent.com/render/math?math=X"> is also contained in <img src="https://render.githubusercontent.com/render/math?math=Z">, then <img src="https://render.githubusercontent.com/render/math?math=I(Y:X|Z) = 0">.

## ```statmi``` functions

### Mutual information ```mi```



### Conditional mutual information ```condmi```



### Transfer entropy ```te```



### Conditional transfer entropy ```condte```

### Shannon entropy ```h```

### Predictive power ```predpow```
