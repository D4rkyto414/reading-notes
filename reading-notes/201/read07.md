### 1️⃣ “Todos los lenguajes orientados a objetos soportan herencia múltiple por defecto.”

__❌ Mito__ 

– No todos los lenguajes permiten herencia múltiple. Por ejemplo, Java y C# no la soportan directamente, mientras que C++ sí. En Java, se usan interfaces para lograr un efecto similar.

### 2️⃣ “La Programación Orientada a Objetos permite organizar el código en entidades con responsabilidad clara.”
__✅ Verdad__

– La POO se basa en clases y objetos, lo que ayuda a estructurar el código en entidades con responsabilidades bien definidas (ej., un Usuario con métodos para registrarse e iniciar sesión).

### 3️⃣ “En JavaScript, usar funciones constructoras es obsoleto porque existen las clases desde ES6.”
__❌ Mito__ 

– Aunque ES6 introdujo class, las funciones constructoras siguen siendo válidas. Las clases en JS son azúcar sintáctico sobre prototipos, por lo que ambas opciones siguen funcionando.

### 4️⃣ “La abstracción implica eliminar cualquier detalle que no sea importante para la funcionalidad principal.”
__✅ Verdad__

– La abstracción oculta detalles internos y expone solo lo esencial. Ejemplo: un método getSaldo() en una clase CuentaBancaria no necesita revelar cómo se almacena el saldo internamente.

### 5️⃣ “Para crear objetos usando funciones constructoras, es obligatorio usar el prototipo explícitamente.”
__❌ Mito__ 

– No es obligatorio modificar el prototipo explícitamente. Un constructor como:

<img width="161" alt="{3F05745A-BE7A-4248-9176-CBDA4C52E103}" src="https://github.com/user-attachments/assets/3b7da756-b4e8-464d-86ff-2dd474b3e15b" />

__ya crea objetos sin tocar el prototipo manualmente.__

### 6️⃣ “La POO promueve la escalabilidad al agrupar datos y comportamiento en entidades lógicas.”
__✅ Verdad__

– Al encapsular datos y métodos en clases, se facilita la extensibilidad y mantenimiento del código. Ejemplo: en un sistema de e-commerce, una clase Producto puede extenderse sin afectar Usuario o Carrito.

### 7️⃣ “La palabra clave this en las funciones constructoras apunta a un objeto global, sin importar si se usa new.”
__❌ Mito__

– Cuando una función constructora se llama con __new__, __this__ apunta al nuevo objeto creado. Sin __new__, __this__ podría referirse al objeto global.

<img width="325" alt="{680CF709-EDCF-452A-802A-190EAF480928}" src="https://github.com/user-attachments/assets/26ed55bb-7867-4e7d-ab71-c0c9d4695f71" />
