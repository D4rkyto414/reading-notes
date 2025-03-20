# Mitos y Verdades sobre el DOM y Regex

## 1. Usar `querySelector()` siempre devuelve una colección de nodos, incluso si selecciona uno solo.
**Mito** ❌  
`querySelector()` devuelve el primer elemento que coincide con el selector, no una colección. Si no encuentra nada, devuelve `null`.

## 2. El DOM permite manipular estilos CSS directamente desde JavaScript usando propiedades específicas como `.style` y `.classList`.
**Verdad** ✅  
Se pueden modificar estilos directamente con `.style` (para cambiar propiedades individuales) y `.classList` (para agregar o eliminar clases de CSS).

## 3. Una expresión regular (Regex) siempre devolverá el mismo resultado sin importar el contexto o idioma del texto que analice.
**Mito** ❌  
Las expresiones regulares pueden verse afectadas por el contexto, como configuraciones de localización o codificación de caracteres, lo que puede alterar los resultados.

## 4. Utilizar `querySelectorAll()` es menos eficiente que `getElementById` cuando se busca un único elemento por su ID.
**Verdad** ✅  
`getElementById()` es más rápido porque accede directamente al elemento sin necesidad de recorrer el DOM, mientras que `querySelectorAll()` evalúa selectores CSS.

## 5. Todos los métodos del DOM devuelven elementos del mismo tipo, no existen diferencias entre ellos.
**Mito** ❌  
Distintos métodos pueden devolver diferentes tipos de objetos. Por ejemplo, `getElementById()` devuelve un `Element`, `querySelectorAll()` devuelve un `NodeList`, y `getElementsByClassName()` devuelve una `HTMLCollection`.

## 6. `querySelectorAll()` permite seleccionar múltiples elementos y devuelve una lista estática (no viva) de nodos.
**Verdad** ✅  
`querySelectorAll()` devuelve un `NodeList` estático, lo que significa que no se actualiza automáticamente si se realizan cambios en el DOM después de la selección.

## 7. Las expresiones regulares (Regex) se pueden utilizar para transformar contenido de texto (Markdown a HTML, por ejemplo) sin necesidad de librerías externas.
**Verdad** ✅  
Es posible transformar texto con Regex, aunque en casos complejos (como Markdown a HTML) es más recomendable usar librerías especializadas como `marked.js`.

## 8. Los cambios realizados en los nodos del DOM usando JavaScript son permanentes incluso después de refrescar la página.
**Mito** ❌  
Las modificaciones en el DOM solo afectan la sesión actual. Al refrescar la página, se recarga el HTML original, a menos que se usen tecnologías como `localStorage` o bases de datos para persistir los cambios.
