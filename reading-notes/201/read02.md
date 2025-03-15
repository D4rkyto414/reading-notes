# Mitos y Verdades sobre Flexbox

## Mitos

1. **Flexbox solo funciona para diseños horizontales.** ❌
__Falso__

   - Flexbox funciona tanto en dirección horizontal como vertical gracias a la propiedad `flex-direction`.

3. **Con Flexbox, ya no es necesario usar media queries.** ❌
__Falso__

   - Aunque Flexbox facilita la adaptabilidad de los elementos, las media queries siguen siendo esenciales para ajustes específicos en diferentes tamaños de pantalla.

5. **Flexbox no es adecuado para crear layouts completos.** ❌
 __Falso__

   - Aunque Grid es más adecuado para estructuras complejas, Flexbox se puede usar para crear layouts completos dependiendo de las necesidades del diseño.

7. **Flexbox no funciona bien en navegadores antiguos.** ❌
    __Falso__, pero con matices.

   - Flexbox es compatible con la mayoría de los navegadores modernos, aunque algunas versiones antiguas pueden presentar problemas de soporte o requerir prefijos específicos.

## Verdades

1. **`flex-wrap` permite que los elementos se ajusten automáticamente en múltiples líneas.** ✅
   __Verdadero__

   - La propiedad `flex-wrap: wrap` permite que los elementos se distribuyan en varias líneas cuando no caben en el contenedor.

3. **`justify-content: space-between` distribuye los elementos dejando espacios iguales entre ellos.** ✅
   __Verdadero__
   - `space-between` coloca los elementos de manera que el primer y último elemento se alinean con los bordes del contenedor y los espacios intermedios son iguales.

5. **La IA puede generar ejemplos de Flexbox, pero siempre deben validarse.** ✅
   __Verdadero__

   - Los ejemplos generados por IA pueden contener errores o no ajustarse a los requerimientos específicos, por lo que siempre deben revisarse.

7. **`flex-grow` permite que los elementos crezcan para ocupar espacio adicional.** ✅
   __Verdadero__

   - La propiedad `flex-grow` define cuánto puede crecer un elemento en relación con los demás en el contenedor flexible.

9. **Usar demasiados `<div>` afecta la semántica del documento.** ✅
   __Verdadero__

   - Un uso excesivo de `<div>` sin propósito semántico puede hacer que el HTML sea menos accesible y menos estructurado.

11. **La propiedad `align-items` controla la alineación vertical de los elementos.** ✅
__Verdadero__
- `align-items` define la alineación de los elementos en el eje transversal, lo que suele ser la alineación vertical en un `flex-direction: row`.
