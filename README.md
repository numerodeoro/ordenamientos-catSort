# catSort 🐱 – un algoritmo de ordenamiento que nació por casualidad

Tenía algo de tiempo libre y decidí repasar los algoritmos de ordenamiento.  
El plan era revisar cada algoritmo en sí (entender bien el proceso), luego escribirlos en Python, probar su velocidad en distintas circunstancias y, una vez repasados los principales, reescribirlos en Java y en Solidity.

Cuando estaba repasando el *counting sort*, se me ocurrió una pequeña mejora: que pudiera admitir cualquier tipo de entrada de datos (enteros, flotantes, cadenas de texto o listas mixtas).  
Así surgieron estos dos pequeños algoritmos: simples, eficientes y con propósito.

En las pruebas de velocidad resultaron ser de orden **O(n)**, y una de sus mayores ventajas es que son completamente nativos: **no requieren importar ninguna librería externa**.  
Esto los hace **portables, escalables** e ideales tanto para páginas web con backend en Python como para el trabajo cotidiano de análisis de datos, especialmente cuando se trabaja con **variables categóricas**.

---

## Versiones disponibles

### 🟦 `catSort_flat`

- Es la primera versión.
- Ordena listas simples (números, cadenas o listas mixtas).
- Agrupa los elementos por categoría en el orden en que aparecen por primera vez.

### 🟩 `catSort_table`

- Versión más realista y generalizada.
- Ordena listas de listas (como una base de datos).
- Permite indicar un **índice de ordenamiento** (columna).
- También normaliza los datos y agrupa respetando el orden de aparición.

---

## ¿Por qué "catSort"? 🐈

Porque **agrupa por categorías**, como si fuera un `groupby` muy livianito, sin dependencias externas.  
Y además... ¡me gustan los gatos!, aunque, en verdad, el nombre viene de *ordenamiento categórico*.

---

> ✨ Este proyecto surgió como un ejercicio, pero terminó siendo una herramienta útil para tratar datos reales con estructura desordenada o mal tipada.

---


