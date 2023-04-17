---
layout: base
---
    <h1>Test de liens dans Eleventy</h1>
    <h2>test2</h2>
    <p>Ceci est un <a href="test2">lien</a> de type direct</p>
    <p>Résultat: ça fonctionne, comme le 3e test</p>
    <h2>/test2</h2>
    <p>Ceci est un <a href="/test2">lien</a> avec une barre oblique</p>
    <p>Résultat: ça amène à la racine</p>
    <p>Eleventy: ça fonctionne</p>
    <h2>./test2</h2>
    <p>Ceci est un <a href="./test2">lien</a> avec un point et une barre</p>
    <p>Résultat: ça fonctionne, comme le 1er test</p>
    <h2>../test2</h2>
    <p>Ceci est un <a href="../test2">lien</a> avec deux points et une barre</p>
    <p>Résultat: ça remonte d'un niveau</p>