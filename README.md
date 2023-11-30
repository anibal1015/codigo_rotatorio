# codigo_rotatorio

El código controla un módulo llamado ky-040, que es un codificador rotatorio. Para la acción se crean 2 variables (A, B, Anterior, Posición)

Básicamente, funciona interrumpiendo el pin conectado a A cuando detecta un cambio de "bajo".

En el bucle de código, verifica si la posición ha cambiado desde la última interrupción, determina si la rotación es en el sentido de las agujas del reloj o en el sentido contrario (usando el pin B) y luego imprime la posición entre 0 y 100.
