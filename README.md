<img src="https://user-images.githubusercontent.com/64969369/194756114-6d478ec8-e1be-4daf-bfda-d2131686fe02.png" height="450px">

# Handwriting Recognition (HWR) ✍️
# Résumé
Dans le but d'obtenir notre diplôme de Licence en sciences Mathématiques et Informatiques, nous avons réalisé ce projet de fin d'études.<br>
Très brièvement, ce dernier a pour but d'apprendre et de comprendre les bases de la reconnaissance d'objets en imagerie à l'aide des réseaux de neurones multicouches avec ou sans convolutions.<br>
En quête de la bonne réalisation du projet, nous avons commencé par définir le problème en premier lieu.<br>
Une fois cela fait, nous avons pu passer à l'étape suivante, qui consistait à comprendre le but de la reconnaissance d'objects précisement dans le cadre de l'écriture manuscrite.<br>
Après avoir exécuté les étapes précédentes, nous avons finalement implémenté comme solution à notre problème, un programme capable de reconnaître les caractères manuscrits sur une image.<br>
Pour mener à bien notre implémentation, nous avons choisi comme jeu de données, MNIST, qui contient un ensemble de chiffres sous différentes polices, ce qui nous a servi à entraîner notre modèle par apprentissage supervisé.<br>
Au cours de cette étude, nous avons pu d'une part mettre en pratique l'ensemble de nos connaissances en Intelligence Artificielle, et d'autre part nous avons appris comment les ordinateurs acquièrent et traitent les images d'écritures manuscrites.

# Objectifs du projet
Comme évoqué plus haut, ce projet a pour but de comprendre les **bases de la reconnaissance d'objets en imagerie** à l'aide des **réseaux de neurones multicouches(CNN) avec ou sans convolutions** et des différentes **méthodes de machine learning.**

# Problèmes rencontrés
Lors de la réalisation de ce projet, les deux problèmes majeurs suivants ont été rencontré :
- Comment implémenter un programme capable de reconnaître des images de caractères manuscrits ? (Problème d'implémentation du programme)
- Comment faire en sorte que ce programme ou plus précisement le modèle développé soit d'une grande précision ? (Problème de précision du programme)

# Solutions trouvées
Comment vous vous êtes pris pour résoudre ces problèmes ?
- Afin de résoudre le problème d'implémentation, nous avons recouru au réseau de neurones convolutionnels(CNN), qui est un algorithme de deep learning très pratique pour tout ce qui est du traitement d'images.
- Concernant le problème de précision, nous avons opté pour un type d'apprentissage surpervisé qui, grâce à ces données étiquettés, fournit des résultats(outputs) une plus grande précision comparée à l'apprentissage non supervisée qui est moins précise.

# Ecriture manuscrite(Handwriting) : Késako ?
**L'écriture manuscrite** est l'acte d'écrire avec la main, de réaliser un manuscrit.<br>
La **reconnaissance de l’écriture manuscrite** (en anglais, Handwritten Text Recognition ou HTR) est un *traitement informatique qui a pour but de traduire un texte écrit en un texte codé numériquement.*<br>
La mise en oeuvre d'un système standard de reconnaissance d'écriture manuscrite supposait le développement de nombreux modules pour :
- Le débruitage de l'image
- L'extraction de caractéristiques
- La classification des formes<br>
De nombreuses **étapes de prétraitement de l'image précèdent la mise en oeuvre de notre système**(Ces étapes peuvent être visualisées dans le PDF)
# Glossaire
<h3>Intelligence Artificielle</h3>
<img src="https://user-images.githubusercontent.com/64969369/194767092-3ed5896c-5350-4676-b6b0-419c191cab6d.png" alt="AI_Kesako" height="375px" width="700px">
L'
<h3>Machine Learning</h3>
<img src="https://user-images.githubusercontent.com/64969369/194765053-bb0d47b2-51b1-4014-8b0b-b098488a5af8.png" alt="Machine_Learning_Kesako" height="375px" width="700px">

Le **Machine Learning** encore appelé apprentissage automatique ou apprentissage machine est selon **Arthur Samuel**(informaticien américain, première personne à faire usage de l'expression Machine Learning) : «**le champ d'étude qui donne aux ordinateurs la capacité d’apprendre sans être explicitement programmée.**»<br>
Autrement dit, c'est **un domainde l'IA** qui permet aux ordinateurs d'apprendre à partir de données et d'améliorer leurs performances à résoudre des problèmes **sans être explicitement programmés pour chacune d'elles.**<br>
<h3>Deep Learning</h3>
<img src="https://user-images.githubusercontent.com/64969369/194765939-eb5cf41b-d014-4d2a-9456-f3d737c9082a.png" alt="Deep_Learning_Kesako" height="375px" width="700px">

Le **Deep Learning** encore appelé apprentissage profond est une sous-categorie du Machine Learning.<br>
Il désigne l'ensemble des méthodes d'apprentissage automatique qui s'inspire du fonctionnement des neurones des êtres humains.
Grosso modo, le **Deep Learning repose sur des algorithmes de type "Réseaux de Neurones Artificiels(Artificial Neural Network)**.








