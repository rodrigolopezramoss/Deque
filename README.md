# Deque

Una Deque o bicola es un contenedor dinámico que permite una inserción y eliminación rápida desde sus dos extremos, inicio y fin.
Al funcionar como una pila LIFO (Last In First Out) solo se pueden insertar y eliminar elementos del final de la estructura.

### Métodos:
- add(data): Añade el valor data al final de la Deque.
- addFirst(data): Añade el valor data al inicio de la Deque.
- pollFirst( ): Retorna y elimina el elemento del inicio de la Deque.
- pollLast( ): Retorna y elimina el elemento del final de la Deque.
- peekFirst( ): Retorna el elemento del inicio de la Deque.
- peekLast( ): Retorna el elemento del final de la Deque.

### Así se declara un Deque:

Primero importamos de util:

![alt text](https://github.com/rodrigolopezramoss/Deque/blob/master/imagenes/1-importar_Deque.png)

Y luego declaramos:

![alt text](https://github.com/rodrigolopezramoss/Deque/blob/master/imagenes/2-declarar_Deque.png)


### Vamos a añadir elementos a nuestros Deque:

![alt text](https://github.com/rodrigolopezramoss/Deque/blob/master/imagenes/5-adici%C3%B3n_Deque.png)



Las pilas, stacks en inglés, tienen sus propios métodos dado que son declarables.

### Métodos Stack:
- push(data): Inserta el valor data en el tope de la Pila.
- peek( ): Retorna el elemento del tope de la Pila.
- pop( ): Retorna y elimina el elemento del tope de la Pila.
- empty( ): Retorna un boolean que indica si la Pila se encuentra vacia.
