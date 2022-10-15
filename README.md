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
Comme évoqué plus haut, ce projet a pour but de comprendre les **bases de la reconnaissance d'objets en imagerie** à l'aide des **réseaux de neurones multicouches(CNN) avec ou sans convolutions** et des différentes **méthodes de machine learning.**<br>
Vous pouvez jetter un coup d'oeil à l'image animée ci-dessous, qui résume très bien l'objectif de ce projet : <br>
![hwr_project_goal](https://user-images.githubusercontent.com/64969369/194777431-ab49d284-4508-4cb4-8824-8dc8f0d32f49.gif)


# Problèmes rencontrés
Lors de la réalisation de ce projet, les deux problèmes majeurs suivants ont été rencontré :
- Comment implémenter un programme capable de reconnaître des images de caractères manuscrits ? (Problème d'implémentation du programme)
- Comment faire en sorte que ce programme ou plus précisement le modèle développé soit d'une grande précision ? (Problème de précision du programme)

# Solutions trouvées
Comment vous vous êtes pris pour résoudre ces problèmes ?
- Afin de résoudre le problème d'implémentation, nous avons recouru au réseau de neurones convolutionnels(CNN), qui est un algorithme de deep learning très pratique pour tout ce qui est du traitement d'images.
- Concernant le problème de précision, nous avons opté pour un type d'apprentissage surpervisé qui, grâce à ces données étiquettés, fournit des résultats(outputs) une plus grande précision comparée à l'apprentissage non supervisée qui est moins précise.<br>
Nous avons notamment utilisé le jeu de données MNIST afin d'entraîner notre algorithme.

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

**L'Intelligence Artificielle**(en anglais, Artificial Intelligence) est une **technologie algorithmique permettant à des machines de résoudre des problèmes complexes que l'on aurait cru réservés à l'intelligence humaine(Cedric Villani).**<br>
Plus simplement, elle peut être définie comme ***l'imitation du raisonnement humain par la machine.***
L'IA doit son émancipation notamment :
- Au Big Data ou méga données(ensemble très volumineux de données provenant de nos activités quotidiennes sur Internet)
- A l'augmentation frénétique de la capacité de calcul des ordinateurs
- A l'amélioration et l'accessibilité d'algorithmes de traitement de données.<br>
<b>Note : </b>**Le Machine Learning et le Deep Learning sont des sous ensembles de l'IA.**

<h3>Machine Learning</h3>
<img src="https://user-images.githubusercontent.com/64969369/194765053-bb0d47b2-51b1-4014-8b0b-b098488a5af8.png" alt="Machine_Learning_Kesako" height="375px" width="700px">

Le **Machine Learning** encore appelé apprentissage automatique ou apprentissage machine est selon **Arthur Samuel**(informaticien américain, première personne à faire usage de l'expression Machine Learning) : «**le champ d'étude qui donne aux ordinateurs la capacité d’apprendre sans être explicitement programmée.**»<br>
Autrement dit, c'est **un domainde l'IA** qui permet aux ordinateurs d'apprendre à partir de données et d'améliorer leurs performances à résoudre des problèmes **sans être explicitement programmés pour chacune d'elles.**<br>

<h3>Deep Learning</h3>
<img src="https://user-images.githubusercontent.com/64969369/194777033-9ddbbe7a-35e0-43bc-8a3b-e71979eddfcc.gif" alt="Deep_Learning_Kesako" height="375px" width="700px">

Le **Deep Learning** encore appelé apprentissage profond est une sous-categorie du Machine Learning.<br>
Il désigne l'ensemble des méthodes d'apprentissage automatique qui s'inspire du fonctionnement des neurones des êtres humains.
Grosso modo, le **Deep Learning repose sur des algorithmes de type "Réseaux de Neurones Artificiels(Artificial Neural Network)"**.<br>
Par ailleurs, il nécessite une *puissance de calcul importante et un volume de données important* afin de fournir des modèles de bonne prédiction de façon rapide.

<h3>Réseau de Neurones</h3>
<img src="https://user-images.githubusercontent.com/64969369/194770239-9d5c4045-62d4-46cd-9755-961f782b9531.png" alt="Neural_Network_Kesako" height="375px" width="700px">

Un **réseau de neurones artificiels(en anglais, ANN=Artificail Neural Network)** est un modèle informatique dont la structure en couches est similaire à la structure en réseau des neurones du cerveau, avec des couches de noeuds connectés.<br>
Comme vous pouvez le voir sur la figure ci-dessus, l'architecture d'un réseau de neurones est composée de 3 couches à savoir :
- Une couche d'entrée(input layer)
- Une ou plusieurs couches cachées(Hidden layers)
- Une couche de sortie(output layer)<br>
**Peut être que vous vous demandiez tout comme moi, à quoi pourrait bien servier ces couches ?**<br>
En effet, **la couche d'entrée** représente la donnée initiale(image, texte, son) que sera passé à l'ANN.<br>
La ou les couches cachées représentent les couches qui s'occuperont de traiter votre donnée initiale.<br>
<b>Note : </b>**Plus votre réseau de neurones artificiels comprend de couches cachées, plus l'apprentissage est profond(d'où le terme deep)** et **plus l'apprentissage est profond, plus la précision et la complexité de votre algorithme augmente.**<br>
C'est le cas notamment des algorithmes pré-entraînés de Google et Facebook qui comptent en général entre **1000 et 2500 couches cachées**.<br>
La **couche de sortie** renvoie le résultat final fournit par les couches cachées après traitement de votre donnée initiale par ces dernières.<br>
<b>Note : </b>La sortie fournit par les algorithmes de deep learning reste ***inexplicable*** dans la majorité des cas à cause de la complexité des réseaux de neurones.<br>
A présent, parlons des différents algorithmes du deep learning.<br>
On distingue plusieurs algorithmes de deep learning parmi lesquelles on peut citer les réseaux de neurones convolutionnels(CNN) et les réseaux de neurones récursifs(RNN pour Recurrent Neural Network).

## Réseau de Neurones Convolutionnels(CNN)
![image](https://user-images.githubusercontent.com/64969369/194777612-2a72ac19-d468-46b3-bde9-b803a49d74d3.png)

Le CNN est un algorithme de deep learning principalement utilisé pour réaliser du traitement d'images et de la détection d'image.<br>
Il est beaucoup utilisé de façon globale dans le domaine de la vision par ordinateur.<br>
Reconnaître des objets sur une image peut être facile pour les êtres humains mais fastidieux pour une machine.<br>
Pour votre information, le **premier réseau de neurones convolutionnels** fut développé en *1998* par un Français appelé **Yann LeCun**.<br>
Son CNN était capable de reconnaître les codes de boîte postale et les numéros.<br>

## Comment fonctionne un CNN
![image](https://user-images.githubusercontent.com/64969369/194777788-98cce0eb-8989-4c64-b9d9-4a56280320fb.png)

Un **CNN ou ConvNet** fonctionne en décomposant une image en de petits groupes de pixels **filtres(chaque filtre est une matrice de pixel).**<br>
Le réseau de neurones fait par la suite une série de calculs sur ces pixels en les comparants aux pixels d'un modèle spécifique.<br>
La première couche d'un CNN sert à détecter des motifs de haut niveau comme les bordures, les courbes.<br>
Au fur et à mesure que le réseau de neurones convolutionnelles parcourt ses couches, il est en mesure d'dentifier des objets spécifiques(tels que des visages).<br>
Un CNN comprend deux grandes parties à savoir :
- La partie convolutive du modèle
- La partie classification du modèle qui correspond à un modèle MLP(Multi Layers Perceptron).<br>
Egalement, dans un CNN, nous avons 4 tyoes de couches :
- La couche de convolution
- La couche de pooling
- La couche de correction ReLu
- La couche **fully-connected**

## Limites du CNN
Le problème rencontré au niveau des CNN est qu'ils ne prennent en compte que des **caractéristiques spatiales.**
Par exemple si nous entrainons notre modèle à reconnaître une image d'un panneau de circulation, il pourra facilement le reconnaître tant que *les paramètres d'éclairage, de couleur, de forme et l'angle de vision restent **inchangées.***<br>
Une fois que l'un de ces paramètres est modifié, les prédictions du modèle seront erronées.<br>
C'est en raison de cela, qu'il est vivement conseillé d'**entraîner ses modèles avec des données de qualités et de en quantité**(millions de données variées) tous annotés correctement.


## Tracabilité
La tracabilité est la capacité ou la possibilité de remonter aux causes expliquant les résultats renvoyés par un algorithme.
A cause de ce critère, les algorithmes de Machine Learning ont tendance à être plus utilisés que les algorithmes de deep learning hormis le champ d'application.

## Jeu de données ou dataset
![image](https://user-images.githubusercontent.com/64969369/194778187-2030cbd3-8342-48cf-9eff-6d46a30580bf.png)

L'ensemble des données utilisés pour entrainer notre modèle est appelé jeu de données.<br>
Ce jeu de données joue un rôle crucial dans la prédiction faite par nos modèles.<br>
En effet, c'est ce qui est à l'origine des ***algorithmes biaisées***.<br>
Ceci a notamment pu être constaté au niveau de certains algorithmes qui ne reconnaissaient pas les personnes à peau noire(problème de variation du dataset).<br>
Grosso modo, **la qualité et la quantité de données que vous collectez déterminera directement la précision de votre modèle prédictif.**<br>
Pour votre information, une fois les données récupéreés, elles devront préalablement être nettoyées(suppression des valeurs aberrantes), explorées(analysées et interprétées) avant d'être utilisées pour la modélisation.<br>
La figure ci-dessus représente le dataset MNIST(Modified National Institute of Standards and Technology) a été créé en 1998 et regroupe 70000 images en couleur blanc noir(60000 images d'apprentissage et 10000 images de test). Il a été utilisé dans notre projet afin d'entraîner et tester notre modèle.

## Différence entre l'informatique classique et le Machine Learning
Un programme informatique traditionnel effectue une tâche en suivant des instructions précises préalablement éditées par le développeur.<br>
A contrario, un système de Machine Learning ne suit pas d'instructions mais apprend à partir de l'entraînement. Par conséquent, ses performances s'améliorent à chaque fois qu'il est exposé à de nouvelles données(il n'est pas statique).

<h3>Feature Extraction</h3>
![image](https://user-images.githubusercontent.com/64969369/195976124-8eef23d5-3160-41bf-af9e-d0f52195ee7e.png)


Le **Feature Extraction ou extraction de caractéristiques** est un processus qui consiste à **réduire la dimensionnalité des types d'observation** faites sur des données brutes(texte, image, son), en un ensemble plus petit afin de **pouvoir modélisé plus facilement.**</br>
Grosso modo, cela est très utile lorsque les observations sont trop volumineuses dans leur forme brute pour être modélisées directement par des algorithmes prédictifs.</br>
En effet, à partir des données brutes à dispostion, on **sélectionnera des variables sur lesquelles s'appuyeront notre modèle pour s'entrainer et faire la prédiction.**</br>
Il peut se faire **manuellement ou automatiquement.**</br>
Dans le cas où il fait manuellement, un ingénieur(data scientist par ex) se chargera de déterminer les caractéristiques(variables) clés sur lesquelles s'appuyera notre algorithme pour résoudre un problème donné(ie faire la prédiction).</br>
 Dans un tel cas, il est primordial pour le data scientist de comprendre le domaine d'activité sur lequel il va travailler afin d'être pertinent dans la définition des variables qui joueront un rôle capital lors de la prédiction.</br>
A présent, mettons nous dans la peau d'un data scientist chargé de concevoir un modèle capable de faire de la prédiction d'achat d'un produit(déterminer oui ou non si un produit sera acheté ou non par un client).</br>
Afin de résoudre ce problème, après avoir récupéré et nettoyé les données, le data scientist va maintenant passer à l'étape d'exploration avant d'entamer les phases de modélisation et d'évaluation/interprétation du modèle.</br>
Lors de cette phase d'exploration, notre expert déterminera l'ensemeble des variables jugées pertinentes pour résoudre notre problème(achat ou non d'un produit).</br>
Ces varaibles peuvent être en autres : l'age d'un invdividu, son sexe, ses centres d'intérêts, son revenu ect...</br>
<b>Note : </b>Le Feature Extraction peut se faire de manière automatique également. Dans un tel cas les réseaux de neurone profonds des algorithmes de deep learning vont déterminer par eux-mêmes les caractéristiques importantes leurs permettant de faire une bonne prédiction</br>
Plus brièvement, **la présence d'un data scientist n'est pas du tout nécessaire dans ce scénario(gain de temps).**</br>

<h3>Fonctionnement du Machine Learning</h3>
![image](https://user-images.githubusercontent.com/64969369/195976630-bf69fb8f-e7c8-4184-81f9-70574af32d75.png)

Il est indéniable que les données représentent l'essence du Machine Learning.</br>
Comme l'a si bien dit le mathématicien Clime Humby : ***"Data is the new oil. Like oil, data is valuable, but if unrefined it cannot really be used. It has to be changed into gas, plastic, chemicals, etc. to create a valuable entity that drives profitable activity. So, must data be broken down, analysed for it to have value."***</br>
Donc en se basant sur le concept des données, le Machine Learning peut être défini comme **l'utilisation des données permettant de résoudre des problèmes**.</br>
Après la phase de récolte de données, on utilisera le ML pour créer des modèles.</br>
Un **modèle** est le résultat(fichier) généré après avoir entraîné un algorithme à l'aide du dataset de training. En gros, vous entraînez un modèle sur un ensemble de données, en lui fournissant un algorithme qu'il peut utiliser pour "raisonner" et apprendre à partir du jeu de données fournie préalablement.</br>
Le ML repose sur deux grandes phases à savoir : 
- La phase d'entraînement
- La phase de prédiction
La phase d'entraînement intervient généralement après avoir récupérées, nettoyées et explorées les données.</br>
Une fois terminée, on obtient notre modèle dont on va évaluer les performances à l'aide du **dataset de test(test set)**.</br>
C'est la qu'intervient la phase de prédiction comme vous pouvez le voir sur la figure ci-dessus</br>
<b>Note : </b>Généralement, on utilisera 80% de notre dataset pour le training et 20% pour le test.</br>

<h3>Le traitement d'images</h3>
Le traitement d'images est une discipline de l'informatique et des mathématiques qui étudie les images numériques et leurs transformations, dans le but d'améliorer leur qualité ou d'en extraire de l'information.</br>
<b>Qu'est-ce qu'une image ?</b>
Une image est constitué de **pixels.**</br>
Chaque **pixel est représenté par un nombre ou un ensemble de nombres.** La plage de ces nombres est appelée la **profondeur de couleur ou profondeur de bits.**</br>
En gros, la **profondeur de couleur indique le nombre maximum de couleurs potentielles qui peuvent être utilisées dans une image.**</br>
Dans une image d'un octet(8bits) de type noir et blanc, chaque pixel à une valeur entre 0 et 255. </br>
La plupart des images ont des couleurs de 24 bits ou plus.</br>
Une image en RGB(Red Green Blue) signifie que la couleur d'un pixel est la combinaisondu rouge, vert et bleu.</br>
Ainsi, chaque pixel contient un ensemble de trois valeurs(Par ex RGB(255,255,255) ou #FFF qui représente le blanc).</br>
Une image de 800(width) * 600(height) contiendra 480000 px(abbr de pixel) ou 0.48 Mpx(Mégapixels).</br>
<b>Comment fonctionne une caméra ?</b>
Une caméra fonctionne comme une "mitraillette" à photos.</br>
En effet, elle permet d'enregistrer des images de façon très rapide pour constituer un flux vidéo quin n'est rien d'autre en réalité qu'une séquence de trames d'images.</br>
La quantité d'images récupérées avec une grande vitesse est ce qu'on appelle **"Frame Per Second(FPS) ou IPS(Images Par Seconde) en français"**.
Plus simplement, le **FPS représente le nombre d'images récupérés par seconde.** </br>
Cette fréquence peut être différente selon le type de diffusion et de qualité.</br>

<h3>Optical Character Reconnaissance (OCR)</h3>
La reconnaissance optique des caractères(ROC en fr) ou océrisation, désigne les **procédés informatiques pour la traduction d'images de textes imprimés ou dactylographiées en fichiers de texte.**<br>
Un ordinateur a besoin d'un logiciel d'OCR pour mener à bien la réalisation de pareil tâches.<br>
Le logiciel d'océrisation permet de récupérer le texte dans l'image d'un texte imprimé et de le sauvegarder dans un fichier pouvant être exploité dans un traitement de texte et stocké dans une BDD ou sur un support de stockage(**Tesseract** est par exemple un logiciel d'océrisation open-source publié en 2006)<br>
Grace à l'OCR, un grand nombre de documents papier pourront être numérisés en texte lisible à la machine, peu importe la langue et le format dans lesquels il sont rédigés. Cette technique ***facilite non seulement le stockage mais rnd plus disponible des données qui auparavant étaient difficilement accessibles.***<br>
<b>Info : </b> La **dactylographie** est une technique d'écriture à la machine à écrire.<br>
<b>Info : </b>**Océriser**, c'est l'action de transformer une image de texte imprimé en fichier de texte numérique.<br>

<h3>Les différents types d'apprentissage</h3>
<h3>Différences entre le Machine Learning et le Deap Learning</h3>















