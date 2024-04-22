# objetos_js

## Document JS

- Este es el objeto que me toco exponer de Javascript entonces su principal uso es: 

El objeto del documento representa su página web.

Si desea acceder a cualquier elemento de una página HTML, siempre comience accediendo al objeto del documento.

- Algunas de las principales propiedades y métodos del objeto "documento" en JavaScript son:


getElementById(id): Método que devuelve una referencia al elemento del documento con el ID especificado.
getElementsByTagName(tagName): Método que devuelve una lista de elementos del documento con el nombre de etiqueta especificado.
createElement(tagName): Método que crea un nuevo elemento con la etiqueta especificada.
appendChild(node): Método que agrega un nodo como hijo de otro nodo existente.
innerHTML: Propiedad que permite obtener o establecer el contenido HTML de un elemento.
title: Propiedad que permite obtener o establecer el título del documento.
location: Propiedad que proporciona información sobre la URL del documento actual.
addEventListener(event, callback): Método que permite agregar un evento y su correspondiente función de devolución de llamada al documento.

Estos son solo algunos ejemplos de las propiedades y métodos disponibles en el objeto "documento". Puedes encontrar más información detallada en la documentación oficial de JavaScript.

## Encontrar elementos HTML

|Method|Description|
|------|-----------|
|document.getElementById(id)|Find an element by element id|
|document.getElementsByTagName(name)|Find elements by tag name|
|document.getElementsByClassName(name)|	Find elements by class name|

## Cambiar elementos HTML

|Property|Description|
|--------|-----------|
|element.innerHTML =  new html content|Change the inner HTML of an element|
|element.attribute = new value|Change the attribute value of an HTML element|
|element.style.property = new style|Change the style of an HTML element|
|Method|Description|
|element.setAttribute(attribute, value)|Change the attribute value of an HTML element|

## Agregar y eliminar elementos

|Method|Description|
|------|-----------|
|document.createElement(element)|Create an HTML element|
|document.removeChild(element)|Remove an HTML element|
|document.appendChild(element)|Add an HTML element|
|document.replaceChild(new, old)|Replace an HTML element|
|document.write(text)|Write into the HTML output stream|

## Encontrar objetos HTML
El primer HTML DOM Nivel 1 (1998) definió 11 objetos HTML, colecciones de objetos y propiedades. Estos todavía son válidos en HTML5.

Posteriormente, en HTML DOM Nivel 3, se agregaron más objetos, colecciones y propiedades.

|Property|Description|DOM|
|--------|-----------|---|
|document.anchors|Returns all <a> elements that have a name attribute|1|
|document.applets|Deprecated|1|
|document.baseURI|Returns the absolute base URI of the document|3|
|document.body|Returns the <body> element|1|
|document.cookie|Returns the document's cookie|1|
|document.doctype|Returns the document's doctype|3|
|document.documentElement|Returns the <html> element|3|
|document.documentMode|Returns the mode used by the browser|3|
|document.documentURI|Returns the URI of the document|3|
|document.domain|Returns the domain name of the document server|1|
|document.domConfig|Obsolete.|3|
|document.embeds|Returns all <embed> elements|3|
|document.forms|Returns all <form> elements|1|
|document.head|Returns the <head> element|3|
|document.images|Returns all <img> elements|1|
|document.implementation|Returns the DOM implementation|3|
|document.inputEncoding|Returns the document's encoding (character set)|3|
|document.lastModified|Returns the date and time the document was updated|3|
|document.links	Returns|all <area> and <a> elements that have a href attribute|1|
|document.readyState|Returns the (loading) status of the document|3|
|document.referrer|Returns the URI of the referrer (the linking document)|1|
|document.scripts|Returns all <script> elements|3|
|document.strictErrorChecking|Returns if error checking is enforced|3|
|document.title|Returns the <title> element|1|
|document.URL|Returns the complete URL of the document|1|

