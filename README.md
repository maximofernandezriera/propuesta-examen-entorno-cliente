# Propuesta de examen desarrollo entorno cliente

1. ¿Cuál es la diferencia principal entre el uso de let y var al declarar variables en JavaScript moderno?  
A) let tiene ámbito de bloque, mientras que var tiene ámbito de función (function scope).  
B) var no permite reasignar valores después de la declaración, mientras que let sí.  
C) let se utiliza exclusivamente para tipos numéricos y var para cadenas de texto.  
D) No existe ninguna diferencia funcional, son alias introducidos por compatibilidad.  
2. En JavaScript, ¿qué valor booleano devuelve la expresión Boolean(0) al realizar una conversión de tipo?  
A) true  
B) false  
C) undefined  
D) null  
3. ¿Cuál es la sintaxis correcta para definir una "Arrow Function" que reciba dos parámetros (a, b) y devuelva su suma?  
A) function suma(a, b) => a + b  
B) const suma = (a, b) => a + b  
C) const suma => (a, b) return a + b  
D) let suma = a, b => a + b  
4. ¿Qué método de la clase Array se utiliza para transformar cada elemento de un array y generar uno nuevo con los resultados?  
A) .forEach()  
B) .filter()  
C) .map()  
D) .reduce()  
5. Al utilizar la desestructuración de objetos, ¿cómo podemos extraer la propiedad nombre del objeto usuario en una nueva variable?  
A) const { nombre } = usuario;  
B) const [ nombre ] = usuario;  
C) const nombre = usuario(nombre);  
D) let usuario -> nombre;  
6. ¿Qué método del objeto document es el más eficiente para seleccionar un único elemento del DOM mediante su atributo id?  
A) document.querySelector('.id')  
B) document.getElementByTagName('id')  
C) document.getElementById('miId')  
D) document.find('#miId')  
7. Al manejar eventos, ¿qué método del objeto evento se debe invocar para evitar que un formulario se envíe y recargue la página?  
A) event.stopPropagation()  
B) event.preventDefault()  
C) event.stopImmediatePropagation()  
D) event.cancelBubble = true  
8. ¿Cuál es la diferencia técnica entre las propiedades innerHTML y textContent al manipular elementos del DOM?  
A) innerHTML procesa las etiquetas HTML contenidas, mientras que textContent trata todo como texto plano.  
B) textContent es significativamente más lento que innerHTML.  
C) innerHTML es una propiedad de solo lectura y textContent permite escritura.  
D) Ambas propiedades funcionan de forma idéntica en todos los navegadores.  
9. ¿Cuál es la forma correcta y recomendada de añadir una nueva clase CSS llamada "activo" a un elemento almacenado en la variable btn?  
A) btn.class = "activo"  
B) btn.classList.add("activo")  
C) btn.style.class = "activo"  
D) btn.className.push("activo")  
10. ¿En qué consiste el concepto de "Event Bubbling" (burbujeo de eventos) en el navegador?  
A) El evento se dispara primero en el elemento raíz y baja hasta el elemento objetivo.  
B) El evento se dispara en el elemento objetivo y se propaga hacia arriba a través de sus ancestros.  
C) Es un error de desbordamiento de memoria al crear demasiados eventos.  
D) Es la capacidad de disparar múltiples eventos con un solo clic de forma personalizada.  
11. Al trabajar con programación asíncrona, ¿cuál es el estado inicial de un objeto Promise recién creado?  
A) Fulfilled (Cumplida)  
B) Rejected (Rechazada)  
C) Pending (Pendiente)  
D) Completed (Completada)  
12. ¿Qué palabra clave es obligatoria definir en la declaración de una función para poder utilizar la instrucción await en su interior?  
A) sync  
B) defer  
C) promise  
D) async  
13. ¿Qué devuelve la función nativa fetch() inmediatamente después de ser invocada, antes de procesar el cuerpo de la respuesta?  
A) Los datos en formato JSON directamente.  
B) Una Promesa que se resuelve con un objeto de tipo Response.  
C) Un error de red si el servidor no responde al instante.  
D) Una cadena de texto con el código HTML de la URL solicitada.  
14. ¿Qué método del objeto global JSON se utiliza para convertir un objeto de JavaScript en una cadena de texto JSON válida?  
A) JSON.parse()  
B) JSON.stringify()  
C) JSON.toText()  
D) JSON.convert()  
15. En el modelo de ejecución "Event Loop" de JavaScript, ¿en qué cola se almacenan las resoluciones de las Promesas?  
A) Call Stack  
B) Web API  
C) Microtask Queue  
D) Callback Queue (o Task Queue)  
16. ¿Qué archivo es el encargado de gestionar las dependencias, metadatos y scripts de ejecución en un proyecto de Node.js o frontend moderno?  
A) index.html  
B) package.json  
C) readme.md  
D) node_modules  
17. ¿Cuál es la función principal de empaquetadores (bundlers) modernos como Vite o Webpack en el desarrollo web?  
A) Actuar como base de datos en tiempo real dentro del navegador.  
B) Empaquetar módulos, servir la aplicación en desarrollo y optimizar recursos para producción.  
C) Validar que el código HTML y CSS cumple con los estándares de la W3C.  
D) Traducir automáticamente lógica de servidor (Python/PHP) a código JavaScript.  
18. En el ecosistema de desarrollo cliente actual, ¿cómo se define la herramienta Supabase?  
A) Es un framework de diseño basado exclusivamente en componentes CSS.  
B) Es una plataforma "Backend as a Service" (BaaS) de código abierto, alternativa a Firebase.  
C) Es una librería específica para realizar pruebas unitarias en el DOM.  
D) Es un entorno de ejecución de JavaScript que sustituye al navegador.  
19. ¿Qué comando de la terminal se utiliza habitualmente para descargar e instalar todas las dependencias listadas en el archivo package.json?  
A) npm start  
B) npm build  
C) npm init  
D) npm install  
20. ¿Cuál es la ventaja fundamental de utilizar Módulos de ES6 (import y export) en lugar de scripts globales?  
A) Permiten organizar el código en piezas reutilizables y mantienen el ámbito (scope) privado por defecto.  
B) Hacen que la página web cargue más rápido sin necesidad de peticiones HTTP adicionales.  
C) Son los únicos scripts que pueden ejecutarse en servidores sin motor de JavaScript.  
D) Reemplazan la necesidad de usar etiquetas HTML para estructurar el contenido.
---
# Respuestas

1	A (let: bloque / var: función)
2	B (false)
3	B (const suma = (a, b) => a + b)
4	C (.map())
5	A (const { nombre } = usuario;)
6	C (document.getElementById)
7	B (event.preventDefault())
8	A (innerHTML procesa HTML)
9	B (classList.add)
10	B (Propagación hacia arriba)
11	C (Pending)
12	D (async)
13	B (Promesa de objeto Response)
14	B (JSON.stringify)
15	C (Microtask Queue)
16	B (package.json)
17	B (Empaquetado y optimización)
18	B (BaaS / Alternativa Firebase)
19	D (npm install)
20	A (Modularidad y ámbito privado)
¿Te gustaría que aplique este mismo proceso de restauración a las preguntas de Deno y Angular que generamos anteriormente?
