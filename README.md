# streams-compress

Écrire une fonction `compress` qui prend en entrée deux noms de fichiers `input` et  `output`, et ecrit le résultat gzippé de `input` dans `output`. La fonction doit retourner le nombre de bytes qui ont été ecrits.

```js
async function compress(
  input: string,
  output: string
): Promise<number>
```

Module à utiliser: `fs` et `zlib`

