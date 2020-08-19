# Nota de clase #1

Informacion:

- **Tema:** Clon de Google
- **Fecha:** 19 de agosto del 2020
- **Pregunta Clave:** ¿Como hacer un clon de Google?

---

## Observaciones

- Para maquetar nuestro contenido debemos seguir las reglas semanticas.
- La navegacion va dentro de nuestra etiqueta header.
- Unicamente copiaremos la estructura del sitio web y no su funcionalidad.
- Existen etiquetas contenedoras y etiquetas de contenido.
- Los navegadores por defecto le agregan un margin y un padding a las etiquetas
  contenedoras, esto incluye tambien al body del documento.
- background-size define el tamaño de la imagen de background
- Si quiero crear una imagen que sea circular puedo usar la propiedad border-radius
  del 50%
- La propiedad outline: none, quita el borde del input que se crea cuando le damos
  click
- El elemento hover, controla lo que sucede cuando se pasa el mouse sobre el elemento.
- La propiedad box-shadow dibuja una sombra debajo del elemento.
- justify-self justifica ese elemento en especifico.

---

## Apuntes

- Lo primero que hay que hacer es maquetar la informacion que contendra nuestro
  sitio web.
- Las etiquetas contenedoras son cajas diseñadas para contener dentro de si a otros
  elementos y no contienen directamente el contenido del sitio, ejemplo de etiquetas
  contenedoras son: ul, div, header, nav y ejemplos de etiquetas de contenido
  pueden ser: li, p, a, img.
- En el caso de la etiqueta header, necesitamos que ocupe la totalidad del ancho
  por lo que le asignamos un width del 100% para que automaticamente se adapte
  al ancho de la ventana del navagador.
- Si colocamos en background-size el valor contain, lo que hace es que el background
  trata de ocupar todo el espacio del contenedor.
- Si quiero asegurar que el bottom siempre estara abajo del todo, podemos usar
  position: absolute y despues usar bottom: 0, de esta manera siempre se colocara
  hasta abajo.
- Si usamos la propiedad grid-template-columns y uso 1fr 1fr, le estoy indicando
  que ese elemento sera dividido en 2 fracciones distintas.

---

## Recursos

- [Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [CSS reference](https://cssreference.io/)
- [Nombrar clases CSS](http://getbem.com/introduction/)
