# Reflexiones Clave sobre Event Listeners y Callbacks

## 1. ¿Qué ventajas ofrecen los event listeners frente a otros métodos tradicionales de gestión de eventos (por ejemplo, atributos HTML)?
- Separación de la lógica de presentación y comportamiento.
- Permiten agregar múltiples manejadores para un mismo evento.
- Facilitan la manipulación y eliminación dinámica de eventos.
- Mejor mantenimiento del código en aplicaciones escalables.

## 2. ¿Cómo impacta en la experiencia del usuario manejar adecuadamente el objeto evento en aplicaciones web?
- Una gestión adecuada del objeto `evento` mejora la interactividad.
- Previene comportamientos inesperados, como el scroll bloqueado o clics múltiples.
- Permite respuestas más fluidas y eficientes a las acciones del usuario.

## 3. ¿Cuáles son los criterios que debes considerar para elegir entre funciones anónimas o funciones nombradas como callbacks?
- **Funciones anónimas**: 
  - Útiles para manejadores simples y puntuales.
  - No reutilizables y difíciles de depurar.
- **Funciones nombradas**:
  - Fomentan la reutilización y la claridad en el código.
  - Facilitan la eliminación de event listeners.
  
## 4. ¿Qué implicaciones tiene la correcta eliminación de event listeners en la gestión del rendimiento de una aplicación?
- Prevención de fugas de memoria en aplicaciones de larga duración.
- Reducción del consumo de recursos al evitar ejecuciones innecesarias.
- Mejora del rendimiento eliminando referencias a eventos no utilizados.

## 5. ¿De qué manera facilita el uso de callbacks la modularidad y la reutilización del código en proyectos de desarrollo?
- Permiten encapsular funcionalidades reutilizables.
- Facilitan la composición de funciones en estructuras más limpias.
- Ayudan a desacoplar lógica específica de la implementación del evento.

## 6. ¿Cómo podemos prevenir errores comunes relacionados con la gestión de eventos al implementar event listeners y callbacks?
- Usar `removeEventListener` cuando sea necesario.
- Evitar la creación de múltiples event listeners innecesarios.
- Delegar eventos en elementos superiores para mejorar la eficiencia.
- Comprobar que el objeto evento contiene la información esperada antes de manipularlo.
