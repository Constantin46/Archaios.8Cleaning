# Especificación de Funcionalidades y Helpers

### 1. Validación de entrada/salida
* **Descripción:** Comprueba que los datos introducidos por teclado tengan un valor correcto en cada circunstancia.
* **Uso:** En todas las entradas de datos de los diferentes menús.

---

### 2. Validación de coordenadas
* **Descripción:** Comprueba que los datos introducidos en el loop jugable de excavación sean correctos (Ejemplo: `A1`, `A3`).
* **Uso:** Comprobación en los diferentes tipos de terrenos, independientemente del tamaño y del tipo (`A` o `B`).

---

### 3. Sistema de guardado
* **Descripción:** Almacena las estadísticas de la partida en el archivo de guardado.
* **Uso:** Partida nueva, contratar, licenciar, terminar excavación y ganar experiencia.

---

### 4. `CodeHelper`
* **Descripción:** Módulo auxiliar para el procesamiento de códigos.
  * Devuelve el código de región de un código.
  * Devuelve el código de tipo de un código.
  * Devuelve el código de número de tesoro de un código.
  * Devuelve el código de parte de un código.
  * Devuelve el código entero de tesoro de un código.

---

### 5. `UtilsHelper`
* **Descripción:** Utilidades varias de formato y cálculo.
  * Pasa a mayúsculas la primera letra de una palabra.
  * Pasa a mayúsculas la primera letra de cada palabra (considerando separadores por espacio).
  * Devuelve el porcentaje de una cantidad frente al total.
  * Genera una serie de índices aleatorios para la selección de elementos de una colección de longitud determinada.

---

### 6. `FileHelper`
* **Descripción:** Comprueba la existencia de directorios y ficheros, y se encarga de gestionar la lectura/escritura de archivos y ficheros.El programa verifica automáticamente si las carpetas donde se van a guardar los registros ya existen en el ordenador. Si no están creada, las genera.
* **Uso:** Al inicio y guardado del sistema y en la gestión de los registros