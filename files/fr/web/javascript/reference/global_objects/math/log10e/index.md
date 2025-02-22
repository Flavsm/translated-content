---
title: Math.LOG10E
slug: Web/JavaScript/Reference/Global_Objects/Math/LOG10E
tags:
  - JavaScript
  - Math
  - Propriété
  - Reference
translation_of: Web/JavaScript/Reference/Global_Objects/Math/LOG10E
original_slug: Web/JavaScript/Reference/Objets_globaux/Math/LOG10E
---

{{JSRef}}

La propriété **`Math.LOG10E`** fournit la valeur du logarithme en base 10 de e, environ 0.434 :

<math display="block"><semantics><mrow><mstyle mathvariant="monospace"><mi>Math.LOG10E</mi></mstyle><mo>=</mo><msub><mo lspace="0em" rspace="0em">log</mo><mn>10</mn></msub><mo stretchy="false">(</mo><mi>e</mi><mo stretchy="false">)</mo><mo>≈</mo><mn>0.434</mn></mrow><annotation encoding="TeX">\mathtt{\mi{Math.LOG10E}} = \log_10(e) \approx 0.434</annotation></semantics></math>

{{EmbedInteractiveExample("pages/js/math-log10e.html")}}{{js_property_attributes(0,0,0)}}

## Description

`LOG10E` étant une propriété statique de `Math`, elle doit toujours être utilisée avec la syntaxe `Math.LOG10E` et ne pas être appelée comme propriété d'un autre objet qui aurait été créé (`Math` n'est pas un constructeur).

## Exemples

### Utiliser `Math.LOG10E`

La fonction suivante renvoie le logarithme en base 10 de e :

```js
function getLog10e() {
   return Math.LOG10E;
}

getLog10e(); // 0.4342944819032518
```

## Spécifications

| Spécification                                                                | État                         | Commentaires                                          |
| ---------------------------------------------------------------------------- | ---------------------------- | ----------------------------------------------------- |
| {{SpecName('ES1')}}                                                     | {{Spec2('ES1')}}         | Définition initiale. Implémentée avec JavaScript 1.0. |
| {{SpecName('ES5.1', '#sec-15.8.1.5', 'Math.LOG10E')}}     | {{Spec2('ES5.1')}}     |                                                       |
| {{SpecName('ES6', '#sec-math.log10e', 'Math.LOG10E')}}     | {{Spec2('ES6')}}         |                                                       |
| {{SpecName('ESDraft', '#sec-math.log10e', 'Math.LOG10E')}} | {{Spec2('ESDraft')}} |                                                       |

## Compatibilité des navigateurs

{{Compat("javascript.builtins.Math.LOG10E")}}

## Voir aussi

- {{jsxref("Math.exp()")}}
- {{jsxref("Math.log()")}}
- {{jsxref("Math.log10()")}}
