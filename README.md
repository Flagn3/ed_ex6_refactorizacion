# Examen Refactorización

## Blocker issues (1)

##### issue java:S1219
Eliminamos del case 7 del switch el ```label{}```

---

## High issues (2)

##### issue java:S1192
Definir la cadena "Nota para " como constante, ya que se repite 4 veces.

##### issue java:S3776
Refactorizamos el método en varios métodos ```checkMenorIgual10() , checkMayor0(), check3oMas(), check6oMas() y check8oMas``` para reducir la complejidad cognitiva de 70 a menos de 15.

---

## Medium issues (12)

##### issue java:S2589
Quitar la expresión del else del método ```calcularNotaFinal()``` que en este caso siempre será true.

##### issue java:S2864
Reemplazamos el foreach por un formap, para que itere sobre un **entrySet** en lugar de sobre un **keySet**.

##### issue java:S106 (8)
Reemplazamos todos los System.out y System.err por logger.

##### issue java:S2259
Declaramos el valor de map como notasRA directamente, sin necesidad de utilizar un operador ternario que haga posible que sea null su valor.