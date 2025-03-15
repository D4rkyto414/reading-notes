# Reflexiones sobre CSS y Git

## 1. ¿Cómo difieren las Component Classes y Utility Classes en su uso diario?
Las Component Classes encapsulan estilos dentro de un solo bloque reutilizable, mientras que las Utility Classes aplican estilos individuales de manera modular y atómica. En el uso diario, las Utility Classes permiten una mayor flexibilidad y rapidez, mientras que las Component Classes favorecen la reutilización y el mantenimiento.

## 2. ¿Cuándo es más eficiente utilizar Component Classes en lugar de Utility Classes?
Las Component Classes son más eficientes cuando se necesita reutilizar estilos en múltiples partes de una aplicación, asegurando coherencia y facilitando el mantenimiento. Son ideales para diseños complejos y estandarizados.

## 3. ¿Cómo afecta el uso de Utility Classes a la legibilidad del código?
El uso excesivo de Utility Classes puede hacer que el HTML sea más difícil de leer debido a la cantidad de clases en cada elemento. Sin embargo, mejora la rapidez del desarrollo y evita la necesidad de escribir CSS personalizado para cada componente.

## 4. ¿En qué tipos de proyectos prefieres usar Bootstrap? ¿Por qué?
Prefiero usar Bootstrap en proyectos donde se requiere un diseño rápido y consistente sin necesidad de personalización avanzada, como aplicaciones empresariales, dashboards y prototipos.

## 5. ¿Cuáles son las ventajas principales de Tailwind CSS frente a otros frameworks?
- Mayor flexibilidad al diseñar sin sobrescribir estilos predeterminados.
- Reducción de CSS innecesario al generar solo los estilos utilizados.
- Facilita la creación de diseños personalizados con rapidez.

## 6. ¿Cómo impacta la elección del framework en el tiempo de desarrollo?
Un framework bien elegido puede reducir drásticamente el tiempo de desarrollo al proporcionar clases predefinidas y herramientas que minimizan la escritura de código CSS manual.

## 7. ¿Por qué es esencial usar ramas en Git al trabajar en equipos?
Las ramas permiten a los desarrolladores trabajar en diferentes características o correcciones sin afectar el código principal. Esto facilita la colaboración y evita conflictos.

## 8. ¿Cómo ayuda el uso de ramas a mantener la estabilidad del código principal?
Las ramas permiten probar y revisar cambios antes de fusionarlos en la rama principal, evitando errores y asegurando que el código en producción sea estable.

## 9. ¿Qué desafíos has enfrentado al fusionar ramas y cómo los resolviste?
Los principales desafíos incluyen conflictos de fusión y diferencias en la versión del código. Se resuelven revisando los cambios, comunicándose con el equipo y utilizando herramientas como `git merge` y `git rebase` para organizar los commits de manera eficiente.
