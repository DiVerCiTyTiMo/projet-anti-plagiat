# projet-anto-plagiat
Séance du 12 mai — 8h15/12h15 - 14h/18h
On a fait des recherches pour trouver différentes manières de comparer des textes et d’autres éléments sur Python. Pour cela, on a trouvé 5 solutions :
Difflib
Jaccard
TF-IDF
Levenshtein
N-grammes
Ce sont des modules à importer dans Python, et chacun fonctionne différemment.

On a déterminé comment tester chaque programme pour vérifier leur éfficacité, pour cela on va faire
un texte identique
un texte reformulé
un texte partiellement copié
un texte totalement différent
suite a cette série de test faudra comparé les résultat entre les script pour savoir lequel fonctionnerais mieux

Séance du 20 mai — 14h/18h

J’ai compris que le SequenceMatcher de difflib sert à comparer deux textes pour trouver leurs parties communes,
L’algorithme cherche le plus grand bloc identique entre deux chaînes de caractères.
Il compare les lettres une par une et construit progressivement les correspondances.
J ai éssayé de reproduire le code à ma manière.
