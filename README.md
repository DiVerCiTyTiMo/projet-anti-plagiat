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

Séance du 21 mai — 8h15/12h15

Nous avons commencé une première version simple du détecteur de plagiat.
L’idée était de comparer les mots communs entre deux textes.

Séance du 29 mai — 13h30/12h15

approfondissement sur certaine recherche

Séance du 4 juin 13h30/17h30

Nous avons ajouté un filtrage des mots vides comme “le”, “la”, “de” ou “et”.
Cela permet de garder seulement les mots les plus importants.

Séance du 5 juin 13h30/17h30

Nous avons étudié le principe de la racinisation.
L’objectif est de rapprocher des mots comme “transformation”, “transformeront” et “transformer”.

Séance du 10 juin — 8h15/12h15 - 14h/18h

Nous avons travaillé sur les méthodes Hamming, Jaccard et les N-grammes.
Nous avons aussi préparé les tests avec texte original, texte modifié et paraphrase.

Séance du 12 juin — 14h/18h

Nous avons ajouté le calcul du score de similarité.
Le programme utilise les mots communs pour donner un pourcentage de ressemblance.

Séance du 17 juin — 14h/18h

On a rassemblé tous se qu on a fait sur un doc word et trié que le plus intéressant

Séance du 18 juin — 8h15/12h15

On a fais le diaporama
