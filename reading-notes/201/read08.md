# Análisis de Mitos y Verdades sobre Prototipos en JavaScript

### 1. "El prototype de una función y el __proto__ de un objeto son exactamente lo mismo."

__Mito__

- __prototype__ es una propiedad de las funciones constructoras que define las propiedades y métodos que heredarán las instancias creadas con __new__.

- __proto__ es una propiedad de los objetos que apunta al prototipo del que heredan.

- Aunque están relacionados, no son lo mismo.

### 2. "La cadena de prototipos permite la reutilización de métodos y propiedades, lo cual es esencial para la herencia en JavaScript."

__Verdad__

- La herencia en JavaScript se basa en la cadena de prototipos.

- Si un objeto no tiene una propiedad, JavaScript la busca en su prototipo y sigue subiendo en la cadena hasta Object.prototype.

### 3. "Las funciones constructoras son obsoletas y no se usan en el desarrollo moderno de JavaScript."

__Mito__

- Aunque las clases (class) son más usadas en código moderno, las funciones constructoras siguen funcionando.

- Se siguen usando en ciertos casos, especialmente en código heredado o para mantener compatibilidad.

### 4. "Manipular correctamente __proto__ puede mejorar la reutilización de código, pero su uso inadecuado puede generar problemas de seguridad y mantenimiento."

___Verdad__

- __proto__ permite modificar la herencia de un objeto en tiempo de ejecución.

- Su uso está desaconsejado por razones de rendimiento y seguridad.

- Se recomienda Object.create() en su lugar.

### 5. "Modificar el prototype de una función siempre afecta a todas las instancias existentes sin excepción."

__Mito__

- Modificar prototype después de crear instancias solo afecta a las nuevas instancias.

- Si se añaden propiedades o métodos a prototype, las instancias existentes podrán acceder a ellos, pero no a cambios en la estructura base.
