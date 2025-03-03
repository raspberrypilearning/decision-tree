## Classer les dinosaures

<html>
  <div style="position: relative; overflow: hidden; padding-top: 56.25%;">
    <iframe style="position: absolute; top: 0; left: 0; right: 0; width: 100%; height: 100%; border: none;" src="https://www.youtube.com/embed/3op4RCy1wRc?rel=0&cc_load_policy=1" allowfullscreen allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"></iframe>
  </div>
</html>

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
**Objectif du projet :** chaque dinosaure a une <span style="color: #0faeb0">**catégorie**</span>. Une catégorie décrit un groupe de dinosaures ayant des caractéristiques similaires. Tu dois déterminer dans quelle catégorie appartient un dinosaure, en utilisant les informations dont tu disposes.
</p>

Voici quelques faits sur deux dinosaures différents :

(mda = millions d'années)

| Nom        | Longueur (m) | Alimentation | Continent      | A vécu (mda) | Catégorie  |
|------------|--------------|--------------|----------------|--------------|------------|
| Concavenator | 6           | Carnivore    | Europe         | 130          | Théropode |
| Diplodocus   | 26          | Herbivore    | Amérique du Nord | 152          | Sauropode |

Tu peux séparer ces données en deux <span style="color: #0faeb0">**catégories**</span> de dinosaures en posant cette question :

![Image d'un arbre de décision avec la question "Était-il plus long que 6 mètres ?"](images/decision1.png)

Si la réponse est **oui**, le dinosaure doit être un sauropode, et si c'est **non**, alors il doit être un théropode.

--- task ---

Réfléchis à une question différente que tu pourrais poser pour distinguer ces deux catégories de dinosaures.

--- collapse ---
---
title: Montrer la réponse
---

- A-t-il vécu en Amérique du Nord ?
- Était-il carnivore ?
- Son nom commence-t-il par « C » ?
- A-t-il vécu il y a plus de 130 millions d’années ?

--- /collapse ---

--- /task ---
