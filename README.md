# 🎠Ejercicio 1 — FizzBuzz

### ¿Qué tienes que hacer?

Vas a escribir un programa que recorra los números del 1 al 100 e imprima uno por línea. Pero con un giro, si el número es

- múltiplos de 3 imprime → `"fizz"`

- múltiplos de 5 imprime → `"buzz"`

- múltiplos de 3 y 5 imprime → `"fizzbuzz"`

## 🎯 Objetivo del ejercicio
Practicar control de flujo ***(for)***, operadores aritméticos ***(%)***, orden de condiciones y salida por consola.

### Criterios de evaluación

- Imprime exactamente 100 líneas (1–100).

- Las sustituciones son correctas y respetan prioridad (fizzbuzz cuando corresponde).

- Código limpio y comentado.

___

## ⚙️ instrucciones 

🔹 __*Paso 1 — Entender el requisito*__

- Debes recorrer los números 1 a 100.

- Para cada número decidir si imprimir el número o una palabra según reglas dadas.

🔹 __*Paso 2 — Pensar la condición correcta*__

La comprobación para fizzbuzz primero verifica si el número es múltiplo de 3 y 5 (n % 15 === 0), esto debe hacerse antes que las comprobaciones individuales; si haces 3 o 5 primero, no llegarás a fizzbuzz.

- Usa el operador módulo %: n % 3 === 0 para detectar múltiplos de 3.

- Luego haz lo mismo verificando si es múltiplo de 5

- Si no cumple ninguna condición, imprime el número

🔹 __*Paso 3 — Estructura básica (algoritmo)*__

Bucle for desde 1 hasta 100. Para cada n:

- Si n % 15 === 0 → imprimir `"fizzbuzz"`.  (o n%3===0 && n%5===0)

- Else si n % 3 === 0 → imprimir `"fizz"`.

- Else si n % 5 === 0 → imprimir `"buzz"`.

- Else → imprimir n.

🔹 __*Paso 4 — Implementación incremental y pruebas*__

Implementa el bucle y haz console.log(n) primero para validar el rango.

Añade condiciones en el orden correcto.

Prueba puntos concretos: 3 → fizz, 5 → buzz, 15 → fizzbuzz, 30 → fizzbuzz, 100 → buzz.

## 📚 Recursos recomendados
### 🔁 Bucles
- [Video bucles e iteración ](https://www.youtube.com/watch?v=W7bNGBPuSUI)
- [Bucles en MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Guide/Loops_and_iteration)
- [Bucle FOR LenguajeJS](https://lenguajejs.com/fundamentos/bucles-e-iteraciones/bucles-for/)

### ➗ Operadores
- [Operador módulo % — MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Operators/Remainder)

### 🧪 Ejercicios
-  [JSChallenger — Desafíos progresivos en JavaScript](https://www.jschallenger.com/)
