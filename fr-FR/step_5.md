## Arbre de décision

\--- challenge ---

<html>
  <div style="position: relative; overflow: hidden; padding-top: 56.25%;">
    <iframe style="position: absolute; top: 0; left: 0; right: 0; width: 100%; height: 100%; border: none;" src="https://www.youtube.com/embed/mYkxL-efCIs?rel=0&cc_load_policy=1" allowfullscreen allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"></iframe>
  </div>
</html>

Un modèle d’apprentissage automatique qui utilise un arbre de décision doit affiner à plusieurs reprises ses critères. Plus les données saisies sont nombreuses, plus elles deviennent précises : c'est ce qu'on appelle l'**entraînement**. Tu n'as utilisé que quelques critères, mais un modèle d’apprentissage automatique peut utiliser plusieurs **milliers** de valeurs.

Voici un ensemble plus vaste de données sur les dinosaures :

(mda = millions d'années)

| Nom            | Longueur (m) | Alimentation | Continent        | A vécu (mda) | Catégorie         |
| -------------- | ------------------------------- | ------------ | ---------------- | ------------------------------- | ----------------- |
| Allosaure      | 12                              | Carnivore    | Europe           | 152                             | Théropode         |
| Archéocératops | 1,3                             | Herbivore    | Asie             | 121                             | Cératopsien       |
| Bambiraptor    | 1                               | Carnivore    | Amérique du Nord | 84                              | Théropode         |
| Brachiosaure   | 30                              | Herbivore    | Amérique du Nord | 155                             | Sauropode         |
| Chindesaurus   | 4                               | Carnivore    | Amérique du Nord | 227                             | Premier dinosaure |
| Concavenator   | 6                               | Carnivore    | Europe           | 130                             | Théropode         |
| Diplodocus     | 26                              | Herbivore    | Amérique du Nord | 152                             | Sauropode         |
| Herrerasaurus  | 3                               | Carnivore    | Amérique du Sud  | 228                             | Premier dinosaure |
| Maiasaura      | 9                               | Herbivore    | Amérique du Nord | 80                              | Ornithopode       |
| Parksosaure    | 3                               | Herbivore    | Amérique du Nord | 76                              | Ornithopode       |
| Zéphyrosaure   | 1,8                             | Herbivore    | Amérique du Nord | 120                             | Ornithopode       |

<p style="border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;">
Pourquoi ne pas télécharger et imprimer ces [cartes de dinosaures] (resources/dinosaur_cards.pdf){:target="_blank"} et les utiliser pour t'aider à dessiner l'arbre de décision ?
</p>

\--- task ---

Dessine un arbre de décision qui te permet d'identifier correctement chaque <span style="color: #0faeb0">**catégorie**</span> de dinosaure.

**Astuce :** chaque question doit diviser les données de manière à ce qu’une catégorie de dinosaure soit entièrement identifiée.

\--- /task ---

\--- task ---

[Choisis un autre dinosaure](https://www.nhm.ac.uk/discover/dino-directory.html){:target="_blank"} et utilise ton arbre de décision pour identifier dans quelle catégorie il se trouve. Ton arbre de décision était-il correct ?

\--- /task ---

## --- collapse ---

## title: Montrer la réponse

Voici une solution possible, mais il existe de nombreux arbres valides que tu pourrais dessiner :

! [Arbre de décision final avec les questions : Était-il moins long que de 26 m de long ? A-t-il vécu il y a moins de 227 millions d'années ? Était-il carnivore ?](images/final-tree.png)

\--- /collapse ---

\--- /challenge ---
