![Tec de Monterrey](images/logotecmty.png)
# Actividad 5.7 Implementación Hill-Climbing

## <span style="color: rgb(26, 99, 169);">¿Qué tengo que hacer?</span>
En este repositorio encontrarás el archivo "main.cpp". En este archivo deberás desarrollar la implementación del problema presentado en esta actividad. En la parte superior del archivo coloca, en comentarios, tus datos. Por ejemplo:
```
// =========================================================
// File: main.cpp
// Authors:
//  Edward Elric - A00123456
//  Alphonse Elric - A00124598
// Date: 01/01/2021
// =========================================================
```
Implementa, <span style="text-decoration-line: underline;">en equipos de 2 personas (máximo)</span>, una solución para el problema que se describe a continuación.

## <span style="color: rgb(26, 99, 169);">**Descripción**</span>
Construye un programa en C++ que implemente un algoritmo Hill-Climbing que resuelva el problema N-Queens. El problema es colocar *N* reinas de ajedrez en un tablero de ajedrez *N* × *N* para que no haya dos reinas que se ataquen entre sí. Por ejemplo, a continuación se muestra una solución para el problema de las 4 reinas.

![4_Queens](images/image01.jpg)

La salida esperada es una matriz binaria que tiene unos para los bloques donde se colocan las reinas. Por ejemplo, a continuación se muestra una de las dos posibles matrices de salida para la solución de 4 reinas anterior.

```
{ 0,  1,  0,  0}
{ 0,  0,  0,  1}
{ 1,  0,  0,  0}
{ 0,  0,  1,  0}
```

## <span style="color: rgb(26, 99, 169);">**Entrada**</span>
El programa recibe un número entero, *N*, que indica la cantidad de reinas, *N*, y el tamaño del tablero, *N* x *N*.

## <span style="color: rgb(26, 99, 169);">**Salida**</span>
Deberá desplegar una posible solución para *N*.

## <span style="color: rgb(26, 99, 169);">**Ejemplo de entrada**</span>
```
8
```

## <span style="color: rgb(26, 99, 169);">**Ejemplo de salida**</span>
```
{ 0, 0, 0, 0, 0, 0, 1, 0}
{ 0, 1, 0, 0, 0, 0, 0, 0}
{ 0, 0, 0, 0, 0, 1, 0, 0}
{ 0, 0, 1, 0, 0, 0, 0, 0}
{ 1, 0, 0, 0, 0, 0, 0, 0}
{ 0, 0, 0, 1, 0, 0, 0, 0}
{ 0, 0, 0, 0, 0, 0, 0, 1}
{ 0, 0, 0, 0, 1, 0, 0, 0}

```

Para probar tu implementación, compila tu programa con el comando:
```
g++ -std=c++11 main.cpp -o app
```
Posteriormente, ejecuta tu programa. Ente caso, como dependiendo del tamaño, la cantidad de soluciones varía, no existen archivos de pruebas. Será necesario que verifiques que las reinas no se ataquen entre sí.

## <span style="color: rgb(26, 99, 169);">**¿Bajo qué criterios se evalúa mi evidencia?**</span>

- **80%** - Para cada una de las funcionalidades se evaluará:

    - **Excelente (80%)** - coloca correctamente todas las reinas.
    - **Muy Bien (60%)** - coloca correctamente el 75% de las reinas.
    - **Bien (40%)** - coloca correctamente el 50% de las reinas.
    - **Insuficiente (20%)** - coloca correctamente menos del 50% de las reinas.

- **10%** - El código deberá seguir los lineamientos estipulados en el estándar de codificación: <span class="instructure_file_holder link_holder">[liga_estándar_codificación](estandar.pdf)</span>
- **10%** - Se especifica (en comentarios) la complejidad computacional de cada uno de las funciones desarrolladas.

## <span style="color: rgb(26, 99, 169);">**¿Dónde la entrego?**</span>
Cuando hayas pasado todas las pruebas, recuerda publicar el código en tu repositorio (*git push*).

## <span style="color: rgb(26, 99, 169);">**Importante**</span>
Recuerda colocar el nombre y las matrículas de ambos integrantes en en los comentarios iniciales. En caso de que se incumpla este punto, se penalizará con 20 puntos sobre la calificación obtenida.
