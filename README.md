# Ejemplo de Problemas de Accesibilidad en una Página Web

Este proyecto es un ejemplo de una página web simple que contiene varios problemas de accesibilidad. 
Se puede usar para aprender y probar cómo herramientas de evaluación como [WAVE](https://wave.webaim.org/) pueden detectar problemas de accesibilidad.

## Problemas de Accesibilidad

La página web incluye varios problemas de accesibilidad que pueden ser detectados por WAVE:

1. **Falta del atributo `lang` en el HTML**: No se especifica el idioma de la página, lo que dificulta la correcta interpretación por parte de tecnologías de asistencia como lectores de pantalla.
2. **Falta de etiquetas `label` asociadas a los campos de formulario**: Los campos de entrada de texto, correo electrónico y el selector de opciones no están correctamente etiquetados, lo que dificulta la navegación para usuarios de tecnologías de asistencia.
3. **Uso incorrecto de los encabezados**: Se utiliza un encabezado `h4` después de un `h2`, lo que rompe la jerarquía de los encabezados y puede confundir a los usuarios con tecnologías de asistencia.
4. **Problemas de contraste**: El texto tiene un contraste insuficiente con el fondo, lo que puede dificultar la lectura de usuarios con problemas visuales.
5. **Falta de texto alternativo (`alt`) en las imágenes**: Se ha omitido el texto alternativo en una imagen, lo que impide a los usuarios con discapacidades visuales entender el contenido de la imagen.

## Tecnologías Utilizadas

- **HTML**: Estructura básica de la página web.
- **CSS**: Estilos de la página.
- **WAVE**: Herramienta de evaluación de accesibilidad web utilizada para detectar problemas de accesibilidad.

## Instrucciones de Uso

1. Clona o descarga este repositorio.
2. Abre el archivo `index.html` en tu navegador.
3. Usa la herramienta [WAVE](https://wave.webaim.org/) para verificar los problemas de accesibilidad en la página.
4. Si deseas corregir los problemas, puedes editar el archivo `index.html` y `styles.css` para solucionar los problemas mencionados.

## Mejoras Sugeridas

- Añadir el atributo `lang="es"` en el elemento `<html>` para definir el idioma de la página.
- Agregar etiquetas `label` asociadas a los campos de formulario con los atributos `for` correspondientes.
- Corregir la jerarquía de los encabezados para asegurar que siguen una estructura lógica (`h3` en lugar de `h4` después de un `h2`).
- Mejorar el contraste entre el texto y el fondo
- No modificar colores desde un archivo HTML. Hacerlo desde el archivo .css

> En la rama develop se encuentra una posible solución :)
