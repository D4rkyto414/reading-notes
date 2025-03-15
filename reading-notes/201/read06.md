 # Reflexiones sobre Programación Funcional vs Imperativa

## 1. Diferencias entre programación imperativa y funcional
- **Imperativa:** Se basa en instrucciones secuenciales y cambios de estado. Usa bucles y mutaciones de variables.
- **Funcional:** Se enfoca en funciones puras y evita mutaciones de estado. Usa funciones de orden superior y recursión.

## 2. Situaciones ventajosas para funciones puras
- **Ventajoso:** Cuando se necesita previsibilidad, concurrencia y facilidad de pruebas.
- **No recomendable:** En operaciones con efectos secundarios (I/O, acceso a bases de datos, manipulación del DOM).

## 3. Rol de las funciones de orden superior
- **map():** Transforma elementos de un array sin mutarlo.
- **filter():** Extrae elementos que cumplen una condición.
- **find():** Encuentra el primer elemento que cumple una condición.
- **Impacto:** Mejoran la legibilidad, reducen errores y evitan mutaciones innecesarias.

## 4. Facilitación de pruebas unitarias y debugging
- **Funciones puras:** No dependen de estado externo, por lo que sus salidas son predecibles.
- **Inmutabilidad:** Evita efectos colaterales que dificultan el rastreo de errores.

## 5. Integración de programación funcional en proyectos imperativos
- **Refactorización progresiva:** Introducir funciones puras en módulos específicos.
- **Uso de funciones de orden superior:** Reemplazar bucles for con map(), filter() y reduce().
- **Evitando mutaciones:** Usar estructuras de datos inmutables como Object.freeze() o bibliotecas como Immutable.js.
- **Adopción gradual:** Aplicar conceptos funcionales en partes críticas antes de una conversión total.
