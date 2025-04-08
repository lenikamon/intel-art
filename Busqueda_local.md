### Busaqueda Local O MINIMOS LOCALES

Ejemplo:
  
    def minimos conflictos(csp, max_iter):
    a   ={X:choice(csp.D[X]) for x in csp.X}
    for _ in range (max_iter):
        conflictos= {Xi : sum (csp.restriccion_binaria(Xi,a[Xi], Xj,a[Xj])
            for Xj in csp.N[Xi])
                for Xi in csp.X}
        if sum(conflictos[x] for x in conflictos)==0:
            return a
        Xi = choice ([X in csp.X if conflictos[X]>0])
        V = el valor que minimice la cantidad de conflictos de Xi
        a[Xi]=y
    return None 



