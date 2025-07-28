Parte 1: Investigación (Teoría)
## 1.¿Qué es react?
React es una biblioteca de JavaScript desarrollada por Meta (antes Facebook) para construir interfaces de usuario interactivas y eficientes, especialmente en aplicaciones web de una sola página (SPA - Single Page Application).
## 2. ¿Por qué usar React?
•	Actualización eficiente de la interfaz gracias al DOM virtual.
•   Componentes reutilizables que hacen el código más organizado y mantenible.
•	Compatible con muchas otras bibliotecas o frameworks.
•	Gran comunidad y soporte.
## 3. ¿Qué necesito saber antes?
•	Fundamentos de HTML, CSS y JavaScript.
•	Uso básico de la terminal y Node.js/npm.
•	Conocimientos de funciones, variables, arrays y objetos en JS.

Parte 4: Investigación Guiada
## ¿Qué es JSX?
JSX (JavaScript XML) es una sintaxis que permite escribir HTML dentro de JavaScript. React lo usa para definir cómo debe mostrarse la interfaz de un componente.
Ejemplo:
Const saludo = <h1>Hola mundo</h1>;

## ¿Qué es un componente funcional?
Es una función de JavaScript que devuelve JSX. Se usa para construir partes de la interfaz de manera reutilizable.
Ejemplo:
Function MiComponente () {
  Return <p>Hola desde un componente funcional</p>;
}

## ¿Qué son los props en React?
Los props (propiedades) son datos que se pasan a los componentes desde el componente padre. Son como argumentos de funciones.
Ejemplo:
<Saludo nombre="Carlos" />

## ¿Cómo se actualiza la pantalla automáticamente al cambiar datos?
React re-renderiza los componentes automáticamente cuando hay cambios en su estado interno (state) o en las props que reciben.


## ¿Qué hace el useState?
UseState es un hook que permite a los componentes funcionales tener y actualizar un estado.
Ejemplo:

Const [contador, setContador] = useState(0);


