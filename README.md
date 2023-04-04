# "[BuzzCola!](https://es.wikipedia.org/wiki/Buzz_Cola)" challenge

A continuación te proponemos una simple kata. Puedes realizarla en un paquete de
Composer en PHP o en cualquier otro lenguaje de programación con el que te 
sientas cómodx. 

En principio no hace falta una aplicación con GUI, maquetación, etc. No es 
problema si la hay pero lo que queremos conocer es cómo planteas el código para
resolver el problema ☺. La idea es que no te tome mucho tiempo y no te robe más 
de una o dos horas, tampoco es importante si no completas todos los pasos.

Para realizar la kata correctamente, es importante **no** leer el siguiente 
ejercicio sin haber completado el anterior.

Tips: 
- Una suite de tests que verifican que el código funciona acorde a lo que pedía
el ejercicio te puede guiar de forma asistida. TDD sería una muy buena opción 
aquí, si nunca lo has probado y te interesa, [aquí tienes una introducción muy 
práctica y breve de Gorka Urrutia](https://www.youtube.com/watch?v=6W_H_ubOFfk).
¡No pasa nada si es tu primera vez!
- Si decides hacer TDD, recuerda que la práctica es "red, green, refactor". 
¡Un commit cada vez que llegues a "green" es un punto de guardado por si 
decides cambiar de estrategia!
- Aunque se pida un método que recibe un valor y retorna otro, puedes crear y
usar internamente tantas clases/funciones como desees y necesites
- Si tienes alguna reflexión sobre el ejercicio o quieres comentar algo sobre 
tu solución puedes adjuntar un documento de texto plano o markdown.
- Recuerda **no** leer los enunciados hasta que llegues a ellos.
- PHPStan puede ser un gran compañero. Un ejemplo de configuración podría ser 
el siguiente:

```neon
# phpstan.dist.neon
 
parameters:
    level: 8
    paths:
        - src
        - tests
```

 [Puedes comenzar el primer ejercicio](exercise-1.md)