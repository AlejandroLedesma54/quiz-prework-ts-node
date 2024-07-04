# quiz-prework-ts-node

Preguntas Abiertas (10)

JavaScript Básico:
1. Describe qué es una función en JavaScript y cómo se declara.

R/ Es un bloque de codigo reutilizable, sea de forma explicita o implicita. fundamental para encapsular logica y ejecutarla.
Formas de declarar: declaracion de funcion estandar, expresion de funcion y funciones de flecha.

Manipulación del DOM:
2. Explica cómo seleccionar un elemento del DOM y cambiar su contenido.

R/ Para seleccionar un elemento del DOM, puedes utilizar métodos como getElementById, querySelector, getElementsByClassName, getElementsByTagName, entre otros. El método más común es querySelector, que permite seleccionar elementos utilizando selectores CSS.

Programación Orientada a Objetos (OOP):
3. ¿Qué es una clase en JavaScript y cómo se define una?

R/ Es una plantilla para crear objetos, define comportamientos y propiedades. Para definir una clase utilizamos la palabra class, seguida de su nombre. 

Eventos en JavaScript:
4. ¿Cómo se agrega un evento de clic a un botón en JavaScript?

R/ En tu archivo JS, selecciona el botón utilizando document.getElementById o document.querySelector y luego agrega un listener de evento click utilizando el método addEventListener.

Variables y Tipos de Datos:
5. Explica las diferencias entre var, let, y const en JavaScript.

R/
1.	var:
	•	Tiene ámbito de función.
	•	Puede ser re-declarada y reasignada.
	•	Es hoisted (elevada al inicio de su ámbito).

2.	let:
	•	Tiene ámbito de bloque ({}).
	•	No puede ser re-declarada en el mismo ámbito.
	•	Puede ser reasignada.
	•	Es hoisted (elevada al inicio de su ámbito).

4.	const:
	•	Tiene ámbito de bloque ({}).
	•	No puede ser re-declarada en el mismo ámbito.
	•	No puede ser reasignada después de la inicialización.
	•	Es hoisted (elevada al inicio de su ámbito).

Control de Flujo:
6. ¿Qué son las estructuras de control de flujo y cuáles son algunas de las más comunes en JavaScript?

R/ 1.	if…else: Ejecuta un bloque de código si se cumple una condición, o un bloque alternativo si no.
	 2.	for: Itera un bloque de código varias veces basado en una condición inicial, de continuación y de incremento/decremento.
	 3.	while: Ejecuta un bloque de código mientras se cumpla una condición específica.
	 4.	switch: Evalúa una expresión y ejecuta bloques de código dependiendo del valor de la expresión.
	 5.	do…while: Similar a while, pero garantiza que el bloque de código se ejecute al menos una vez, antes de verificar la condición de salida.

Funciones de Flecha:
7. Describe qué es una función de flecha en JavaScript y proporciona un ejemplo de cómo se usa.
R/ Es una funcion anonima, sintaxis breve, no tiene propio this.  
Ejemplo: const resta = (a, b) => a - b;

JSON:
8. ¿Qué es JSON y cómo se utiliza en JavaScript?
R/ Es un formato para intercambiar datos estructurados entre sistemas. Se utiliza en JS para: convertir objetos de JS en cadenas JSON. y convertir cadenas JSON en objetos de JS. Se utiliza en comunicacion con servidores, almacenamiento de datos y APIs debido a su simplicidad y compatibilidad con multiples lenguajes.

Promesas:
9. Explica qué es una promesa en JavaScript y proporciona un ejemplo de su uso.
R/ Es un objeto que representa un resultado de una operacion asincrona en JS. facilita manejar operaciones usando .then() para exito y .catch() para los errores.
// Manejo de la promesa

const promesa = new Promise((resolve, reject) => {
    // Simular una operación asíncrona (ej. solicitud HTTP)
    setTimeout(() => {
        const exito = true; // Simulación de éxito o fracaso
        if (exito) {
            resolve('Operación exitosa');
        } else {
            reject('Operación fallida');
        }
    }, 1000); // Simular un retardo de 1 segundo
});


Depuración:
10. ¿Cuáles son algunas de las herramientas o métodos que se pueden usar para depurar código JavaScript?
R/ Consola del navegador, delcaracion debugger, breakpoints, inspeccion de elementos, network panel y pruebas unitarias son algunos de las herramientas y metodos para depurar codigo en JS.


Preguntas de Selección Múltiple (20)

11. ¿Cuál de las siguientes es la forma correcta de declarar una variable en JavaScript? 

A) var myVariable;
B) variable myVariable;
C) let myVariable;
D) A y C son correctas. 
RESPUESTA: D) A y C son correctas. 

12. ¿Qué método se utiliza para agregar un elemento al final de un array en JavaScript?

A) push()
B) pop()
C) shift()
D) unshift()
RESPUESTA: A) push()

13. ¿Cuál de los siguientes operadores se utiliza para comparar tanto el valor como el tipo de dos variables en JavaScript?

A) ==
B) === 
C) !=
D) !==
RESPUESTA: B) === 

14. ¿Cuál es la salida del siguiente código?
console.log(typeof null);

A) null
B) undefined
C) object
D) number
RESPUESTA: C) object


15. ¿Cuál de los siguientes métodos se usa para recorrer todos los elementos de un array?

A) forEach()
B) map()
C) filter()
D) Todas las anteriores
RESPUESTA: D) Todas las anteriores

16. ¿Qué se entiende por “hoisting” en JavaScript?

A) Declaraciones de variables y funciones se mueven al principio de su ámbito.
B) Es un término para describir la eliminación de variables.
C) Es un método para agrupar varias funciones.
D) Ninguna de las anteriores.
RESPUESTA: A) Declaraciones de variables y funciones se mueven al principio de su ámbito.

17. ¿Cuál es la diferencia entre null y undefined en JavaScript?

A) null significa que una variable ha sido declarada pero no definida, undefined significa que no se ha declarado.
B) null es un valor asignado intencionalmente, undefined significa que una variable no tiene valor.
C) undefined es un valor asignado intencionalmente, null significa que una variable no tiene valor.
D) No hay diferencia.
RESPUESTA: B) null es un valor asignado intencionalmente, undefined significa que una variable no tiene valor.

18. ¿Cuál es el propósito del método Array.prototype.map()?

A) Modificar el array original.
B) Crear un nuevo array con los resultados de aplicar una función a cada elemento del array original.
C) Filtrar los elementos de un array.
D) Encontrar un elemento en un array.
RESPUESTA: B) Crear un nuevo array con los resultados de aplicar una función a cada elemento del array original.

19. ¿Qué es el Event Loop en JavaScript?

A) Un ciclo que controla las llamadas recursivas.
B) Un proceso que permite a JavaScript realizar operaciones asincrónicas.
C) Un método para iterar sobre arrays.
D) Ninguna de las anteriores.
RESPUESTA: B) Un proceso que permite a JavaScript realizar operaciones asincrónicas.

20. ¿Cuál es la salida del siguiente código?
console.log(0.1 + 0.2 === 0.3);

A) true
B) false
C) undefined
D) NaN
RESPUESTA: B) false

21. ¿Qué se entiende por strict mode en JavaScript?

A) Un modo que permite utilizar características experimentales.
B) Un modo que cambia la forma en que se ejecuta JavaScript, haciéndolo más seguro.
C) Un método para validar datos.
D) Ninguna de las anteriores.
RESPUESTA: B) Un modo que cambia la forma en que se ejecuta JavaScript, haciéndolo más seguro.

22. ¿Cuál de las siguientes es una forma correcta de crear un objeto en JavaScript?

A) let obj = {};
B) let obj = Object.create();
C) let obj = new Object();
D) A y C son correctas.
RESPUESTA: D) A y C son correctas.

23. ¿Qué es un callback en JavaScript?

A) Una función que se pasa como argumento a otra función.
B) Un tipo de variable especial.
C) Un método para declarar funciones.
D) Ninguna de las anteriores.
RESPUESTA: A) Una función que se pasa como argumento a otra función.

24. ¿Cuál es el propósito de async y await en JavaScript?

A) Ejecutar funciones síncronas.
B) Manejar operaciones asincrónicas de manera más simple y legible.
C) Declarar variables globales.
D) Ninguna de las anteriores.
RESPUESTA: B) Manejar operaciones asincrónicas de manera más simple y legible.

25. ¿Cuál de las siguientes es una estructura de datos inmutable en JavaScript?

A) Arrays
B) Strings
C) Objetos
D) Ninguna de las anteriores.
RESPUESTA: B) Strings

26. ¿Cómo se puede convertir un objeto JSON en una cadena de texto en JavaScript?

A) JSON.parse()
B) JSON.stringify()
C) toString()
D) parseInt()
RESPUESTA: B) JSON.stringify()

27. ¿Qué es un Promise en JavaScript?

A) Una función que se ejecuta inmediatamente.
B) Un objeto que representa la eventual finalización (o falla) de una operación asincrónica.
C) Un método para declarar variables.
D) Ninguna de las anteriores.
RESPUESTA: B) Un objeto que representa la eventual finalización (o falla) de una operación asincrónica.

28. ¿Qué método se utiliza para agregar uno o más elementos al principio de un array y devolver la nueva longitud del array?

A) push()
B) pop()
C) shift()
D) unshift()
RESPUESTA: D) unshift()

29. ¿Cuál es la diferencia entre localStorage y sessionStorage en JavaScript?

A) localStorage almacena datos solo durante la sesión del navegador, sessionStorage almacena datos de manera persistente.
B) sessionStorage almacena datos solo durante la sesión del navegador, localStorage almacena datos de manera persistente.
C) No hay diferencia entre ellos.
D) Ambos almacenan datos solo durante la sesión del navegador.
RESPUESTA:B) sessionStorage almacena datos solo durante la sesión del navegador, localStorage almacena datos de manera persistente.

30. ¿Qué método se utiliza para detener la propagación de un evento en el DOM?

A) event.stopPropagation()
B) event.preventDefault()
C) event.stop()
D) event.cancel()
RESPUESTA: A) event.stopPropagation()

