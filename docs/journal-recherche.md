# Journal de recherche

> Chaque recherche utile : ce que vous cherchiez, où (cours, [MDN](https://developer.mozilla.org/fr/docs/Web/JavaScript), [Node.js](https://nodejs.org/api/), un camarade, une IA…), ce que vous avez compris. Ce que vous gardez, vous devez pouvoir l'expliquer.

| Ce que je cherchais | Où | Ce que j'ai compris | Utilisé dans |
|length | https://developer.mozilla.org/fr/docs/Web/JavaScript| donne le nombre d'éléments| listerReleves |
| find()|google | renvoie le premier élément qui respecte la condition |  return releves.find(releve => releve.id === id);|
| filter() |chatgpt | renvoie un nouveau tableau contenant tous les éléments qui respectent la condition | return releves.filter(releve => releve.pluieMm >= seuil)|
| sort() |  https://developer.mozilla.org/fr/docs/Web/JavaScript| trie les éléments | sort(
    (a, b) => a.temperatureC - b.temperatureC
  );|
