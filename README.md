# TIPOS DE DATOS EN JAVA

## JVM (Java Virtual Machine)

* Realiza una gestión eficiente de la memoria.
* Distribuye la memoria en dos zonas: stack (pila) y heap (montón)

![RAM](ram.jpeg "RAM")

### Stack
* Se almacenan: variables locales, llamadas a métodos (parámetros y resultados), variables primitivas, referencias a objetos del heap.
* Memoria estática.

### Heap
* Gestionado por el Garbage Collector
* Espacio de memoria en tiempo de ejecución donde se registran los objetos.
* Memoria dinámica.
* No posee estructura de asignación de espacios.

### Variable
* Contenedor de memoria donde se almacena información.
* En Java se declara con un tipo que se conservará durante todo su ciclo de vida en el interior de la app.
* La variable debe tener un nombre.
* Existen de tipo primitivo y referenciado.

## PRIMITIVOS
* Contenedores de tamaño específico que almacenan valores y no tienen métodos.
* Ejemplos: boolean, char, byte, short, long, float, double.

## REFERENCIADOS
* Almacenan las referecias a los datos
* Estos datos se escriben en una zona de memoria llamada heap