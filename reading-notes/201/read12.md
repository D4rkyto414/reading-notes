## 1.¿De qué manera las Promesas contribuyen a que la experiencia de usuario sea fluida y evite bloqueos, en comparación con un enfoque sincrónico?
Las Promesas permiten ejecutar código de manera no bloqueante, lo que evita que la interfaz se congele mientras se esperan respuestas de operaciones costosas como solicitudes a la red o lecturas de archivos. En un enfoque sincrónico, cada tarea debe completarse antes de pasar a la siguiente, lo que puede hacer que la aplicación se vuelva lenta o inusable en ciertas condiciones.

## 2.¿Cómo influye la claridad con que manejamos excepciones en la mantenibilidad y confiabilidad del proyecto?
Un manejo claro y estructurado de excepciones facilita la depuración y reduce errores inesperados. Cuando las excepciones se gestionan correctamente (mediante `try/catch` o `.catch()` en Promesas), se evitan fallos silenciosos y se pueden proporcionar mensajes de error adecuados, mejorando la confiabilidad del proyecto y su mantenibilidad a largo plazo.

## 3.¿En qué escenarios sería más conveniente utilizar async/await frente a then()/.catch(), y qué implicaciones tiene para la legibilidad del código?
El uso de `async/await` es preferible cuando se necesita escribir código asincrónico con una estructura más secuencial y fácil de leer, especialmente en funciones con múltiples llamadas asíncronas. Sin embargo, `then()`/`.catch()` puede ser útil cuando se encadenan múltiples Promesas o en casos donde se requiera un manejo detallado de errores en cada paso.

## 4.¿Qué pasa si no proporcionamos feedback al usuario mientras se lee un archivo grande o se exporta un documento largo a PDF?
La falta de feedback puede hacer que el usuario piense que la aplicación está congelada o que la operación ha fallado, llevándolo a realizar acciones innecesarias como cerrar la aplicación o reiniciar el proceso. Esto afecta negativamente la experiencia de usuario y la percepción de fiabilidad del sistema.

## 5.¿Cómo afectan las buenas prácticas de asincronía (spinners, mensajes de error) a la percepción de robustez del Editor de Markdown?
El uso de indicadores de carga (spinners), mensajes de progreso y manejo adecuado de errores mejora la percepción de estabilidad y profesionalismo del editor. Un sistema bien diseñado no solo informa al usuario sobre lo que está ocurriendo, sino que también le permite actuar en caso de errores, reforzando la confianza en la herramienta.
