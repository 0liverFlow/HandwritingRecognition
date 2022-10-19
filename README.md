<img src="https://user-images.githubusercontent.com/64969369/194756114-6d478ec8-e1be-4daf-bfda-d2131686fe02.png" height="450px">

# Handwriting Recognition (HWR) ✍️
# Résumé
Dans le but d'obtenir notre diplôme de Licence en sciences Mathématiques et Informatiques, nous avons réalisé ce projet de fin d'études.<br>
Très brièvement, ce dernier a pour but d'apprendre et de comprendre la reconnaissance d'objets en imagerie à l'aide des réseaux de neurones multicouches avec ou sans convolutions.<br>
En quête de la bonne réalisation du projet, nous avons commencé par définir le problème en premier lieu.<br>
Une fois cela fait, nous avons pu passer à l'étape suivante, qui consistait à comprendre le but de la reconnaissance d'objets précisement dans le cadre de l'écriture manuscrite.<br>
Après avoir exécuté les étapes précédentes, nous avons finalement implémenté comme solution à notre problème, un programme capable de reconnaître les caractères manuscrits sur une image.<br>
Pour mener à bien notre implémentation, nous avons choisi comme jeu de données, **MNIST**, qui contient un ensemble de chiffres sous différentes polices, ce qui nous a servi à entraîner notre modèle par apprentissage supervisé.<br>
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
# Outils utilisés
La reconnaissance de caractères manuscrits en imagerie implique l'utilisation d'une panoplie outils, dont la majorité est développée en **Python**.<br>
<h3>Python</h3>
<img src="https://user-images.githubusercontent.com/64969369/196743938-3ed163c1-b52d-422b-a4df-38f2f4c4053d.png" alt="Python_logo" height="275px" width="500px">

**Python** est un langage de programmation *interprétéé, multiparadigme et multiplateforme* créé par **Guido Van Rossum** en 1991.<br>
Il est beaucoup utilisé dans le domaine de l'IA notamment pour faire de l'exploration de données, la classification, le clustering et de l'analyse prédictive.<br>
<h4>Installation</h4>
<b>GNU/Linux</b><br>
Exécuter la cmd suivante en tant que superuser : <b>sudo apt-get install python3</b><br>
<b>Windows ou Mac</b><br>
Si vous utilisez un PC Windows ou un Mac, il vous faudra suivre les étapes suivantes :<br>
- Se rendre sur le <a href="https://www.python.org/" title="Visit Python official website">site officiel de Python </a><br>
- Ensuite télécharger la dernière version Python disponible à partir de l'onglet <a href="https://www.python.org/downloads/" title="télécharger Python">Download</a><br>
- Une fois le téléchargement terminée, aller dans le répertoire contenant votre archive, double-cliquer sur l'archive pour la décompresser puis installer finalement Python en suivant les différentes étapes qui s'afficheront sur votre écran.<br>
<h3>Scikit-Learn</h3>
<img src="https://user-images.githubusercontent.com/64969369/196747254-831ba242-36b0-428d-8d35-0108b8b243d0.png" alt="Scikit_Learn_logo" height="275px" width="500px">

**Scikit-Learn** une bibliothèque libre Python, destinée à l'apprentissage automatique.<br>
Elle comprend notamment des fonctions pour estimer des **régréssions logistiques, des algorithmes de classification, des forêts aléatoires.**<br>
Elle a été conçu pour s'harmoniser avec d'autres bibiliothèques libres de Python comme numpy et scipy.
<h4>Installation</h4>
<b>Multiplateforme(Mac, Windows, GNU/Linux)</b><br>
<b>Note : </b>Avant de passer à l'installation des bibliothèques, il faut s'assurer que **pip**(utilitaire permettant d'installer des bibiliothèques, modules sur Python) soit **installé** et qu'il soit récent.<br>
<b>pip install scikit-learn</b>

<h3>NumPy</h3>
<img src="https://user-images.githubusercontent.com/64969369/196748394-8e39ab23-9502-40c9-9f2e-aefffcc016a0.png" alt="Numpy_logo" height="275px" width="500px">
**NumPy** est une bibliothèque libre de Python, utilisée pour **manipuler des matrices ou tableaux multidimensionnels** ainsi que des **fonctions mathématiques opérant sur ces tableaux**.<br>
<h4>Installation</h4>
<b>Multiplateforme(Mac, Windows, GNU/Linux)</b><br>
<b>pip install numpy</b>

<h3>Matplotlib</h3>
<img src="https://user-images.githubusercontent.com/64969369/196749809-af8ef512-9357-4823-8a68-f2c7b21f4c74.png" alt="Matplotlib_logo" height="275px" width="500px">

**Matplotlib** est une bibliothèque de Python, utilisée pour **tracer et visualiser des données sous forme graphique**.<br>
<h4>Installation</h4>
<b>Multiplateforme(Mac, Windows, GNU/Linux)</b><br>
<b>pip install matplotlib</b>

<h3>Pandas</h3>
<img src="https://user-images.githubusercontent.com/64969369/196750509-06e75734-2ebf-4571-befa-455c093d3c84.png" alt="Pandas_logo" height="275px" width="500px">

**Pandas** est une bibliothèque Python utilisée pour **manipuler et analyser les données.**<br>
<h4>Installation</h4>
<b>Multiplateforme(Mac, Windows, GNU/Linux)</b><br>
<b>pip install pandas</b>

<h3><Tensorflow</h3>
<img src="https://user-images.githubusercontent.com/64969369/196751114-7db1dc7e-3b95-4eca-a500-ac21f2748175.png" alt="Tensorflow_logo" height="275px" width="500px">

**Tensorflow** est un outil open source de machine learning développé par **Google**.<br>
 Il est utilisé pour **le dévelopement et l'entraînement de modèles de machine learning.**<br>
<h4>Installation</h4>
<b>Multiplateforme(Mac, Windows, GNU/Linux)</b><br>
<b>pip install tensorflow</b>

<h3>Keras</h3>
<img src="https://user-images.githubusercontent.com/64969369/196752230-7f787660-427b-44ca-83d4-4c2f92de8fa6.png" alt="Keras_logo" height="275px" width="500px">

**Keras** est une bibliothèque Python open source développé par le développeur de Google François Chollet.<br>
<h4>Installation</h4>
<b>Multiplateforme(Mac, Windows, GNU/Linux)</b><br>
<b>pip install keras</b>

<h3>OpenCV</h3>
<img src="https://user-images.githubusercontent.com/64969369/196752798-9dbe17a2-dedb-46bb-b5b1-72e9bc9b2cab.png" alt="OpenCV_logo" height="250px" width="450px">

**OpenCV(Open Computer Vision)** est une bibliothèque graphique Python<br>
 Elle est **très utile dans le traitement d'images que ce soit pour la photo ou la vidéo.**<br>
<h4>Installation</h4>
<b>Multiplateforme(Mac, Windows, GNU/Linux)</b><br>
 Pour télécharger OpenCV, vous pouvez vous rendre sur <a hrf="https://github.com/opencv/opencv" title="téléchargr_openCV">github</a> et cloner le dépôt.
 
<h3>TKinter</h3>
<img src="https://user-images.githubusercontent.com/64969369/196755616-14ef1944-0aee-4488-a49e-b87fdb0358d3.png" alt="OpenCV_logo" height="275px" width="500px">

**TKinter(Tool Kit interface)** est la bibliothèque graphique libre par défaut de Python.<br>
 Elle permet de **créer des interfaces graphiques.**<br>
<h4>Installation</h4>
<b>Multiplateforme(Mac, Windows, GNU/Linux)</b><br>
 <b>pip install tkinter</b>
 
 <h3>Autre alternative</h3>
<img src="https://user-images.githubusercontent.com/64969369/196762147-6c8ade86-9f47-40e0-acd1-6dafac456d9c.png" alt="Ananconda_navigator_interface" height="300px" width="600px">

Au cas où vous ne souhaitiez pas installer Python et ses bibliothèques de façon séquentiel comme on l'a fait, vous pouvez opter pour l'installation de la **distribution Anaconda.**<br>
 **Anaconda** est une distribution open source destinée aux langages de programmation Python et R.<br>
 Il est véritablement utilisé en **data science, machine learning et l’intelligence artificielle** car il contient plusieurs packages nécessaires dans ce domaine notamment Numpy, Panda, Jupyter.<br>
 Grosso modo, il vise à **simplifier la gestion des paquets et leur déploiement.**<br>
<h4>Installation</h4>
<b>Multiplateforme(Mac, Windows, GNU/Linux)</b><br>
 Pour l'installer , se rendre sur le <a href="https://www.anaconda.com/" title="Download Anaconda">site web officiel d'anaconda</a> puis cliquer sur le bouton download.
 
# Glossaire
<h3>Intelligence Artificielle</h3>
<img src="https://user-images.githubusercontent.com/64969369/194767092-3ed5896c-5350-4676-b6b0-419c191cab6d.png" alt="AI_Kesako" height="375px" width="700px">

**L'Intelligence Artificielle**(en anglais, Artificial Intelligence) est une **technologie algorithmique permettant à des machines de résoudre des problèmes complexes que l'on aurait cru réservés à l'intelligence humaine(Cedric Villani).**<br>
Plus simplement, elle peut être définie comme ***l'imitation du raisonnement humain par la machine.***
L'IA doit son émancipation notamment :
-Au Big Data ou méga données(ensemble très volumineux de données provenant de nos activités quotidiennes sur Internet)
-A l'augmentation frénétique de la capacité de calcul des ordinateurs
-A l'amélioration et l'accessibilité d'algorithmes de traitement de données.<br>
<b>Note : </b>**Le Machine Learning et le Deep Learning sont des sous ensembles de l'IA.**
<img src="https://user-images.githubusercontent.com/64969369/196711506-df6eb8cb-120c-4be4-8df6-d8b66a2ded05.png" alt="Machine_Learning_Kesako" height="450px" width="450px">


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
<img src="https://user-images.githubusercontent.com/64969369/194777612-2a72ac19-d468-46b3-bde9-b803a49d74d3.png" alt="Convolutionnal_Neural_Network_Kesako" height="375px" width="700px">

Le CNN est un algorithme de deep learning principalement utilisé pour réaliser du traitement d'images et de la détection d'image.<br>
Il est beaucoup utilisé de façon globale dans le domaine de la vision par ordinateur.<br>
Reconnaître des objets sur une image peut être facile pour les êtres humains mais fastidieux pour une machine.<br>
Pour votre information, le **premier réseau de neurones convolutionnels** fut développé en *1998* par un Français appelé **Yann LeCun**.<br>
Son CNN était capable de reconnaître les codes de boîte postale et les numéros.<br>

## Comment fonctionne un CNN
<img src="https://user-images.githubusercontent.com/64969369/194777788-98cce0eb-8989-4c64-b9d9-4a56280320fb.png" alt="How_CNN_Works" height="375px" width="700px">

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
<img src="https://user-images.githubusercontent.com/64969369/196683748-402073e0-da38-4cf4-a653-2cbe2707157b.png" alt="How_Machine_Learning_Works" height="375px" width="700px">

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
<img src="https://user-images.githubusercontent.com/64969369/195976630-bf69fb8f-e7c8-4184-81f9-70574af32d75.png" alt="How_Machine_Learning_Works" height="400px" width="600px">

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

<b>Qu'est-ce qu'une image ?</b><br>
Une image est constitué de **pixels.**</br>
Chaque **pixel** est représenté par un nombre ou un ensemble de nombres.<br>**La plage de ces nombres est appelée la **profondeur de couleur ou profondeur de bits.**</br>
En gros, la **profondeur de couleur indique le nombre maximum de couleurs potentielles qui peuvent être utilisées dans une image.**</br>
Dans une image d'un octet(8bits) de type noir et blanc, chaque pixel à une valeur entre 0 et 255. </br>
La plupart des images ont des couleurs de 24 bits ou plus.</br>
Une image en RGB(Red Green Blue) signifie que la couleur d'un pixel est la combinaisondu rouge, vert et bleu.</br>
Ainsi, chaque pixel contient un ensemble de trois valeurs(Par ex RGB(255,255,255) ou #FFF qui représente le blanc).</br>
Une image de 800(width) * 600(height) contiendra 480000 px(abbr de pixel) ou 0.48 Mpx(Mégapixels).</br>
<b>Comment fonctionne une caméra ?</b><br>
Une caméra fonctionne comme une **"mitraillette"** à photos.</br>
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
<img src="https://user-images.githubusercontent.com/64969369/196713528-6df9b019-0724-4a89-a747-2312b3d111ef.png" alt="AI_Types_Of_Learning" height="375px" width="700px">

Dans cette section, nous verrons les différents types d'apprentissage.<br>
<b>Attentionnn, attachez bien votre ceinture, eh hop c'est parti :) !!!!!</b>

<h4>Apprentissage supervisé (Supervised Learning)</h4>
<img src="https://user-images.githubusercontent.com/64969369/196682187-5b87c1c8-1a5e-402a-8c19-6c128c88c431.png" alt="How_Supervised_Learning_Works" height="375px" width="700px">

En **apprentissage supervisé**, les **données** utilisées pour l'entraînement(training set) sont **étiquetées ou labélisées.**<br>
Dans un tel scenario, le **modèle sait d'ores et déjà les patterns(motifs)** qu'il doit chercher dans le training set. Le jeu de données d'entraînement est composé d'entrés et de sorties correctes.<br>
L'algorithme estime sa précision grâce à  a fonction **loss**(nous le verrons plus bas :)) et l'ajuste au fur et à mesure qu'il apprend jusqu'à ce que l'erreur soit minime.<br>
A la fin de l'apprentissage, le modèle entraîné sera capable de retrouver les mêmes éléments sur des données non annotées ou labélisées.<br>
Dans la figure ci-dessus, on peut constater qu'après entraînement, notre modèle est capable de reconnaître les formes de façon autonome et ceci, grâce aux données labelisées que lui avons fournis lors de la phase d'apprentissage.<br>
Mathématiquement parlé ^_^' , en apprentissage supervisé, pour chaque donnée d'entrée X, on associera une sortie correspondante Y. Ainsi, le travail de notre algorithme de ML sera de trouver la meilleure fonction f tel que f(X) = Y.
Vous pouvez jetter un coup d'oeil sur la figure ci-dessous, qui illustre bien ce qui a été dit précédemment :
<img src="https://user-images.githubusercontent.com/64969369/196688125-3b124ead-8d87-499e-83bb-7b5485896884.png" alt="How_Supervised_Learning_Works_mathematically" height="375px" width="700px">

<h4>Apprentissage non supervisé (Unsupervised Learning)</h4>
<img src="https://user-images.githubusercontent.com/64969369/196685303-a48c1fd4-a87b-4e24-9aaa-561ea5102a2f.png" alt="How_Unsupervised_Learning_Works" height="375px" width="700px">
La principale différence entre le supervised learning et le unsupervised learning, est que **en unsupervised learning, les données d'entrées (input) ne sont ps étiquetées.**<br>
En effet, notre algorithme **déterminera *tout seul* les similarités et les différences au sein du training set** mis à sa disposition.<br>
Après avoir réalisé la tâche précédente, il va **regrouper les données partageant des caractéristiques communes.**<br>
Ceci peut être visionné sur la figure ci-dessus.<br>
Encore une fois, mathématiquement parlé :), en apprentissage non supervisé, on fournira juste des entrées X non étiquettées à notre algorithme. Ainsi, le travail de ce dernier sera de regrouper les X similaires puis de créer une fonction qui permet d'associer une nouvelle entrée Z à un des ensembles X préalablement créés par lui.<br>
La figure ci-dessous est une illustration de ce qui a été expliqué ci-dessus :
<img src="https://user-images.githubusercontent.com/64969369/196693081-d56ea760-0601-443f-8f1a-b26ec5bd243d.png" alt="How_Unsupervised_Learning_Works" height="375px" width="700px">

<h4>Apprentissage semi-supervisé (Semi-supervised learning)</h4>
<img src="https://user-images.githubusercontent.com/64969369/196693559-3267e660-a34e-4d5f-b0f9-019d2b62c6ad.png" alt="How_Semi_Supervised_Learning_Works" height="375px" width="700px">
L'apprentissage semi-supervisé est un mixte de l'apprentissage supervisé et l'apprentissage non supervisé.<br>
En effet, les données fournies en entrée à notre algorithme sont partielement étiquetées.<br>
Il y'a un proverbe qui dit : **"Une image vaut mille mots"**, et c'est totalement vrai ;-)<br>
Rentrons un peu plus en détail en jettant un coup d'oeil sur la figure ci-dessus.<br>
Comme vous pouvez le voir, comme données étiquetées, nous avons les bananes et les oranges. Cependant les pommes ne sont pas étiquettés sachant qu'elles font partie du training set également. Dans un tel scenario, c'est à notre algorithme de se "débrouiller" pour déterminer en un premier lieu les caractéristiques des pommes puis de les regrouper en un second lieu.<br>
Eh voilà ^_^ , c'est comme ça que fonctionne le semi supevised learning.<br>
Mathématiquement parlé °_°, voici une petite illustration : <br>
<img src="https://user-images.githubusercontent.com/64969369/196696556-d849d6eb-3f44-4635-8a9a-8bb43548c5e9.png" alt="How_Semi_Supervised_Learning_Works" height="375px" width="700px">

<b>Note : </b>Il y'a un dernier type d'apprentissage qui est l'apprentissage par renforcemement dont on ne fera pas mention vu qu'il n'intervient pas dans ce projet.<br>Egalement, il serait bien de noter que les prédictions faites généralement par un modèle entraîné par apprentissage supervisé sont **plus précises** que celles faites par un modèle entraîné en apprentissage non supervisé.<br>
Nonobstant, vous pouvez retrouver ci-dessous un bref résumé des différents types d'apprentissage mais en english(Eh ouais :) , il vous faudra vous y habituez!! No way to avoid english when learning AI :()

<h4>Récapitulation des différents types d'apprentissage</h4>
<img src="https://user-images.githubusercontent.com/64969369/196684875-66d3aa1a-eaa0-437e-a951-55e3a11a2cc6.png" alt="How_Semi_Supervised_Learning_Works" height="375px" width="700px">

<h3>Algorithmes de l'apprentissage supervisé</h3>
<img src="https://user-images.githubusercontent.com/64969369/196705365-ee71cc1b-9da5-4514-8b7a-962aad185b0b.png" alt="Supervised_Learning_Algorithms" height="375px" width="700px">
Deux algorithmes d'apprentissage supervisé bien connus sont : 
-<b>La régression</b><br>

C'est le est le processus de recherche d'un modèle en s'appuyant sur des **données quantitatives.**<br> 
Cet algorithme exploite des **valeurs numériques** pour dégager une tendance ou une évolution prévisible dans le temps.<br>
Il réalise des prédictions pour des variables continues ou réelles comme le salaire, les ventes, le prix des produits, l'évolution en poids ou en taille.<br>
Il fonctionne de la façon suivante : dans un premier temps, il y a une phase préalable au cours de laquelle les **données sont collectées à partir des observations.** Ensuite, lesdites données sont tracées le long d'une ligne.<br>
***Lorsque la différence entre la valeur prédite et le résultat obtenu est presque la même, l'algorithme de régression linéaire peut être utilisé pour résoudre le problème.***
-<b>La classification</b><br>
C'est le processus de recherche ou de découverte d'un modèle en s'appuyant sur des **données qualitatives(non-numériques).**<br>
Elles séparent les données en plusieurs **classes**<br>
Comme vous vous en doutiez, la différence entre ces deux types d'algorithme résident dans le type de données traitées.<br>
Par exemple, la classification est utilisé par certaines organisations afin de séparer le spam(courriel indésirable) de votre messagerie principale.<br>
<h3>Algorithmes de l'apprentissage non supervisé</h3>
Deux algorithmes d'apprentissage non supervisé sont :<br>
-<b>Le clustering</b>
C'est l'algorithme d'apprentissage non supervisé le plus utilisé.<br>
Il permet de regrouper un ensemble d'entités(objets, individus) de telle sorte que ces dernières aient des caractéristiques communes.<br>
On recourira au clustering lorsque l'on souhaite décomposer un ensemble d'objets en groupes d'objets ayant des traits similaires.<br>
Ci-dessous, vous trouverez une illustration du clustering : 
<img src="https://user-images.githubusercontent.com/64969369/196705792-e71a4896-6af8-4696-b3ef-97a845404ff6.png" alt="What_is_clustering" height="375px" width="700px">
<b>Note : </b>Attention à **ne pas confondre le clustering avec la classification**, le tableau ci-dessous vous présente les majeures différences entre les deux : <br>
<img src="https://user-images.githubusercontent.com/64969369/196706822-85fe76b5-3645-42cf-9185-7ac83e04bc5b.png" alt="Difference_between_clustering_classification" height="375px" width="700px">

-<b>L'association</b>
C'est un algorithme d'apprentissage non supervisé permettant d'identifier des relations(liens) entre différentes données d'une database, en utilisant certaines mesures d'intérêt.<br>

<h3>Différences entre le Machine Learning et le Deep Learning</h3>
<img src="https://user-images.githubusercontent.com/64969369/196734096-04cbd653-bee9-4133-938e-bf8d1456002c.png" alt="Difference_between_ML_and_DL" height="375px" width="700px">

La principale différence entre le ML et le DL se situe au niveau de l'extraction des caractéristiques encore appelé le **Feature Extraction.**<br>
En effet, sachant que les données traitées en DL sont **non-structurées(données qualitatives comme le son, l'image, le texte)** il n'y a aucun intérêt à faire du Feature Extraction. Par exemple, lorsque nous travaillons sur une image , il est impossible pour nous de sélectionner manuellement tous les pixels de l'image. Vue que cela est impossible, il ne sera pas non plus possible d'extraire l'élément prédicteur d'une image donnée, et qui dit pas d'extraction d'élément prédicteur dit pas de Feature Extraction.<br>
Par contre, en ML on utilisera des **données structurées(données quantitatives comme les chiffres)**, ce qui nous permettra de faire de la Feature Extraction.<br>
Par exemple on pourrait essayer de résoudre le problème suivant :<br>
**Etant donné les caractéristiques de mon appartenant, combien devrais-je payer pour le loyer ?**<br>
Les caratéristiques ici ne sont rien d'autres que les variables issues de la Feature Extraction(elles peuvent être la surface(m²), meublé(1) ou non meublé(0), ect...)<br>
Pour mener à bien la résolution de notre modèle, nous allons utiliser un training set contenant les variables citées plus hauts et le loyer associé.<br>
A partir de là, nous allons entraîner le modèle tout en assurant que sa fonction de perte est minimale(plus la fonction de perte est minimale, plus le modèle est précis).<br>
Après entraînement, nous pouvons utiliser le modèle afin de déterminer notre loyer.<br>
Une autre différence entre le ML et le DL se situe au niveau de la **traçabilité**. En effet, il est possible pour l'être humain de comprendre dans la plupart des cas les résultats renvoyés par un algorithme de ML puisque généralement ces algorithmes sont entraînés via l'apprentissage supervisé.<br>
A contrario, il est très difficile voire impossible de comprendre les résultats retournés par un algorithme de DL car ce dernier s'entraîne en utilisant **l'apprentissage non supervisé**(il est celui qui définit ses propres patterns).<br>
C'est aussi pour cette raison que beaucoup d'experts en IA priorisent le ML au DL dans la mesure du possible.<br>
<b>Note : </b>Le **Machine Learning Black Box**(la boîte noire de la l'apprentissage automatique) se produit lorsqu'un modèle de ML retourne un résultat ou prend une décision sans que nous soyons capables de l'expliquer.<br>
Ci-dessous, se trouve une illustration animée, de la différence entre un modèle de ML transparent et un modèle boîte noire : <br>

<img src="https://user-images.githubusercontent.com/64969369/196732690-9a953eba-a1e4-47a3-9aa2-66786d263bb0.gif" alt="Difference_between_balckbox_transparent_model" height="375px" width="700px">














