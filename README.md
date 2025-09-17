# Análisis de UX y Solución de Diseño: Airbnb

Este proyecto presenta un análisis de un problema de experiencia de usuario (UX) identificado en la aplicación móvil de Airbnb y propone una solución de diseño a través de un prototipo interactivo.

---

## 1. El Problema: Falta de Transparencia en los Precios

Al buscar alojamiento en Airbnb, la lista de resultados muestra un precio por noche que resulta engañoso. Este precio no incluye tarifas importantes como los gastos de limpieza o la tarifa de servicio de la plataforma. 

Esto obliga al usuario a realizar un proceso tedioso y frustrante:

1.  Hacer clic en un anuncio que parece económico.
2.  Ir a la página de reserva para ver el desglose y descubrir el costo real.
3.  Retroceder si el precio total no es el esperado.
4.  Repetir el proceso con múltiples anuncios para poder comparar el costo final de su estancia.

Esta fricción en el proceso de comparación disminuye la confianza del usuario y hace que la toma de decisiones sea ineficiente.

## 2. La Solución Propuesta: Interruptor de "Precio Total"

La solución propuesta es añadir un interruptor (toggle) simple y visible en la parte superior de la página de resultados de búsqueda, con la etiqueta **"Mostrar precio total"**.

![image](https://github.com/user-attachments/assets/e03f2094-342a-429c-b10c-62115f53453a)


### Comportamiento:

*   **Por defecto (apagado):** La interfaz funciona como lo hace actualmente, mostrando el precio por noche.
*   **Al activarlo:** La vista de resultados se actualiza instantáneamente. Cada tarjeta de alojamiento pasa a mostrar el **precio total y final** de la estancia como el valor principal. El precio por noche se mantiene en un texto más pequeño como referencia secundaria.

Esta solución empodera al usuario, ofreciéndole transparencia y permitiéndole comparar alojamientos basándose en el costo real desde el primer momento, lo que agiliza y mejora notablemente la experiencia de reserva.

## 3. Prototipo Interactivo

Se ha desarrollado un prototipo interactivo y auto-contenido para demostrar esta funcionalidad.

### Cómo usarlo

1.  Navega a la carpeta `/prototype`.
2.  Abre el archivo `index.html` en cualquier navegador web.
3.  Interactúa con el interruptor "Mostrar precio total" para ver el cambio en los precios de los alojamientos.

### Tecnologías Utilizadas

*   HTML5
*   CSS3
*   JavaScript (Vanilla)

---

*Este es un proyecto conceptual de diseño de UX y no está afiliado con Airbnb.*
