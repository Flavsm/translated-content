---
title: WeakMap.prototype.has()
slug: Web/JavaScript/Reference/Global_Objects/WeakMap/has
tags:
  - ECMAScript6
  - JavaScript
  - Method
  - Protocols
  - WeakMap
translation_of: Web/JavaScript/Reference/Global_Objects/WeakMap/has
original_slug: Web/JavaScript/Referencia/Objetos_globales/WeakMap/has
---
{{JSRef}}

El método **`has()`** devuelve un boleano indicando ya sea, si el elemento con la llave específica existe o no en el objeto `WeakMap`.

{{EmbedInteractiveExample("pages/js/weakmap-prototype-has.html")}}

## Sintaxis

    wm.has(key);

### Parámetros

- identificador (key)
  - : Requerido. La llave del elemento a comprobar en el objeto `WeakMap`.

### Valor devuelto

- Boolean
  - : Devuelve `true` si el elemento con la llave específica existe en el objeto `WeakMap`; de no encontrarse, devolverá `false`.

## Ejemplos

### Utilización del método `has`

```js
var wm = new WeakMap();
wm.set(window, 'foo');

wm.has(window); // Devuelve true
wm.has('baz');  // Devuelve false
```

## Especificaciones

| Especificación                                                                                           | Estado                       | Comentarios         |
| -------------------------------------------------------------------------------------------------------- | ---------------------------- | ------------------- |
| {{SpecName('ES2015', '#sec-weakmap.prototype.has', 'WeakMap.prototype.has')}} | {{Spec2('ES2015')}}     | Definición inicial. |
| {{SpecName('ESDraft', '#sec-weakmap.prototype.has', 'WeakMap.prototype.has')}} | {{Spec2('ESDraft')}} |                     |

## Compatibilidad con navegadores

{{Compat("javascript.builtins.WeakMap.has")}}

## Vea también

- {{jsxref("WeakMap")}}
- {{jsxref("WeakMap.prototype.set()")}}
- {{jsxref("WeakMap.prototype.get()")}}
