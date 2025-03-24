# Lineal Regression 
### Lenika Elizabeth Montoya Valencia

training data -> learning algorithm -> predictor(input and output)
Tenemos que conocer:
* H conjunto de funciones
* Loss
* Predicciones posibles (hypothesis class)
* Ein(ho)= 1/M E loss(y°i, ho(x°i))
* Ein(ho)=1/M E 1/2 (y°i-w°TΦ(x°i))°2

### Hypothesis class
* Vector notation
  * weight vector **w= [w1,w2]**
  * feature extractor **Φ(x)= [1,x]**
  * **fw(x)= w*Φ(x)score**
* Hypothesis class
  * F= {fw : w existe en R2}
  * hw(x) = w°(T) Φ(x)  w existe en R°(n+1)
### Loss funciton
* Loss(x,y,w)= (fw(x)-y)°2 squared loss
* TrainLoss(w)= 1/(|Dtrain|)la suma de (x,y) existe Dtrain Loss(x,y,w)
* Todo es cuadratico, tienen formas de tason y untra hacia abajo

### Optimization algorithm
definicion:  Te gradient w traiinLoss (w) is the direction that increases the training loss the most.
Algorithim: gradient descent
* Inicialize: w= [0......0]
  * for t=qm......T eoachs
  * w <--w q -n tranquiLoss(w)