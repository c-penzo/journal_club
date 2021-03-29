# Journal Club 
## Laboratoire de Mathématiques de Lens


- **Avr 8, 2021:**<br />
**Yao Feng (Max Planck Institute for Intelligent Systems)**<br />
*face3D:* face reconstruction and 3D morphable models.<br />
[slides here]<br />

- **Mar 18, 2021:**<br />
Discussion ouverte concernant l'utilisation du matériel pour l'enregistrement des données utilisées pour la photoplethysmographie à distance, une technique qui détecte les variations du volume sanguin en utilisant un enregistrement vidéo d'une personne. Pour ce faire, nous utiliserons une caméra et un oxymètre que nous synchroniserons pendant la capture des données. Un des points de la conversation serait de comprendre comment synchroniser le vidéo et l'oxymètre. <br />

- **Mar 12, 2021:**<br />
**Arthur Klipfel**<br />
Exposé sur l’avancement de mon projet côté programmation. Programmation orientée objet, test unitaire, packages python et documentation.<br />
[slides here]<br />

- **Feb 12, 2021:**<br />
**Arthur Klipfel**<br />
Présentation du codage absolut et relatif des positions dans les transformers en NLP. Pistes de réflexions sur le codage des positions pour la chimie (passage du codage de position discret du NLP à un codage dans l'espace continue dans lequel se trouve les atomes qui constituent les molécules et crystaux). Pour finir par des pistes pour utiliser les mécanismes d'attentions et le passage de message dans des complexes simpliciaux.<br />
Ensemble d'articles:<br />
[https://arxiv.org/pdf/1706.03762.pdf](https://arxiv.org/pdf/1706.03762.pdf)<br />
[https://arxiv.org/pdf/1803.02155.pdf](https://arxiv.org/pdf/1803.02155.pdf)<br />
[https://arxiv.org/pdf/1809.04281.pdf](https://arxiv.org/pdf/1809.04281.pdf)<br />
[https://arxiv.org/pdf/1710.10903.pdf](https://arxiv.org/pdf/1710.10903.pdf)<br />
[https://arxiv.org/pdf/1712.06113.pdf](https://arxiv.org/pdf/1712.06113.pdf)<br />
[slides here]<br />

- **Feb 4, 2021**<br />
**Mathieu Klimczak**<br />
Calibrer un réseau de neurones revient à faire en sorte que le score sigmoide/softmax en sortie soit le plus proche possible d'une "vraie probabilité", pour pouvoir avoir confiance dans ses prédictions. Je vais surtout me baser sur l'article [https://arxiv.org/abs/1706.04599.pdf](https://arxiv.org/abs/1706.04599.pdf) et après je vais montrer comment mettre en place ça en Python.<br />
[slides here]<br />

- **Jan 21, 2021**<br />
**Olivier Peltre** <br />
Problème de prédiction du passage de la barrière hémato encéphalique pour des molécules organiques. Le manque de données oblige à s'orienter vers des méthodes de few-shot learning comme les prototypical networks, intéressants pour leur simplicité. <br />
[https://arxiv.org/abs/1703.05175.pdf](https://arxiv.org/abs/1703.05175.pdf)<br />
[slides here]<br />

- **Jan 14, 2021**<br />
**Arthur Klipfel** <br />
Discussion sur l'article: *Graph Attention Networks* <br />
[https://arxiv.org/pdf/1710.10903.pdf](https://arxiv.org/pdf/1710.10903.pdf) <br />
[slides here]<br />

- **Dec 17, 2020:** <br />
**Arthur Klipfel** <br />
Discussion sur l'article: *Graph Deconvolutional Generation*<br />
[https://arxiv.org/pdf/2002.07087.pdf)](https://arxiv.org/pdf/2002.07087.pdf),br />
[slides here]<br />
**Jean-Baptiste Gouray** <br />
Discussion sur l'article: *Relational inductive biases, deep learning, and graph networks* <br />
[https://arxiv.org/pdf/1806.01261.pdf](https://arxiv.org/pdf/1806.01261.pdf)<br />
[slides here]<br />

- **Dec 10, 2020:** <br />
**Jean-Baptiste Gouray** <br />
Frechet Inception Distance (FDI) et du Inception Score, deux métriques les plus utilisées pour évaluer des GANs <br />
[slides here]<br />

- **Dec 3, 2020:** <br />
**Adlane Sayede** <br />
tutoriel informel sur comment utiliser DeepChem<br />
[https://deepchem.io/](https://deepchem.io/)<br />

- **Nov 26, 2020:** <br />
**Yaël Fregier** <br />
Introduction à les transformers <br />
[https://arxiv.org/pdf/1802.05751.pdf](https://arxiv.org/pdf/1802.05751.pdf)<br />
[slides here]<br />

- **Nov 20, 2020:** <br />
**Olivier Peltre** <br />
Les réseaux convolutionnels (GCN) [1, 2] sur un graphe G = (V, E) utilisent le laplacien L ou un polynôme de celui-ci pour générer des filtres locaux en chaque point, analogues à des ondelettes. En notant 1_i : V -> R la masse de Dirac sur le sommet i, et un polynôme P de degré k, l'ondelette f_i = P(L) . 1_i est supportée sur les voisins de i situés à une distance inférieure à k. Etant donné une fonction x : V -> R sur les sommets représentant l'état d'une couche, l'état y_i de la couche suivante est défini en applicant une fonction non-linéaire au produit scalaire (f_i, x). Les réseaux à passage de messages (MPNN) [3], sont définis par des fonctions de message M_ij(x_i, x_j) et des fonctions de mise à jour U_i(x_i, m_i). Pour tout sommet j, on calcule la somme m_j des messages M_ij(x_i, x_j) entrant au sommet j auquel on applique la fonction de mise à jour U_j(x_j, - ).   Comme affirmé dans [3], un grand nombre de méthodes différentes rentre dans le cadre des algorithmes à passage de messages. C'est en particulier le cas des réseaux convolutionnels de [2] qui se restreignent à un polynôme P(L) de degré 1 i.e. une fonction affine du laplacien. Par contre ça ne semble pas vrai en degré plus grand, comme le dit pourtant [3].<br />
[1] [https://arxiv.org/abs/1312.6203.pdf](https://arxiv.org/abs/1312.6203.pdf)<br />
[2] [https://arxiv.org/abs/1609.02907.pdf](https://arxiv.org/abs/1312.6203.pdf)<br />
[3] [https://arxiv.org/pdf/1704.01212.pdf](https://arxiv.org/abs/1312.6203.pdf)<br />
[slides here]<br />

- **Nov 4, 2020:** <br />
**Arthur Klipfel** <br />
Code de *SchNet*<br />
[slides here]<br />
**Jean-Baptiste Gouray** <br />
Utilisation du autoencoder ALAE avec la technique du transfer learning pour GANs Mind2Mind <br />
[https://arxiv.org/abs/2004.04467.pdf](https://arxiv.org/abs/2004.04467.pdf)<br />
[https://arxiv.org/abs/1906.11613.pdf](https://arxiv.org/abs/1906.11613.pdf)<br />
[slides here]<br />
**Yaël Fregier**<br />
Article *Within-person variability promotes learning of internal facial features and facilitates perceptual discrimination and memory*. Bien que ce travail soit dans le domaine de la psychologie, la problématique s’applique aussi à l’apprentissage profond. En particulier, ce paradigme pourrait peut-être permettre d'introduire une méthode de “drop out sémantique” afin de faire émerger les caractéristiques propres aux identités, stables par rapport à la variabilité des données. <br />
[slides here]<br />

- **Oct 29, 2020:** <br />
**Yaël Fregier** <br />
Article sur *G-Shnet*.<br />
[slides here](yael_2020_10_29.pdf)<br />

- **Oct 22, 2020:** <br />
**Camilla Penzo** <br />
rPPG avec un LSTM: la remote-photoplethysmographie (rPPG) est une technique qui détecte les variations du volume sanguin en utilisant un enregistrement vidéo d'une personne. On utilise une Long Short-Term Memory (LSTM) network pour apprendre et predire les series temporales de l'intensité des pixels dans la vidéo. <br />
[slides here](camilla_2020_10_22.pdf)<br />
