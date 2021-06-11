# Projet-LabView-Self-Balancing-Robot

Comme une application réussite du principe du Pendule de Furuta, on peut citer le Segway. C’est un moyen de transport électrique et individuel inventé par Dean Kamen. Le dernier s’est inspiré d’un pendule inversé miniature connu sous le nom de Joe-le-Pendule qui a été développé en 1996 au laboratoire d’Electronique Industrielle de l’EPFL. Le pilotage du Segway est basé sur l’inclinaison du corps de l’utilisateur dans la direction de déplacement voulue. En effet, il faut se pencher en avant ou en arrière pour avancer ou reculer et à droite ou à gauche pour tourner

Objectifs :

Pour réussir un tel projet, nous nous sommes fixés des objectifs dès le début. 

Objectif au niveau du travail : 

•Notre projet consiste en la fabrication d’un robot pendule inversé sur deux roues. 

•Concevoir un système de contrôle numérique complet avec Labview

•Stabiliser le système en boucle fermée


![image](https://user-images.githubusercontent.com/83011466/121741114-561a4c00-cafe-11eb-8072-2830ec402588.png)

# Etude théorique :

Benchmark :

![image](https://user-images.githubusercontent.com/83011466/121741655-1d2ea700-caff-11eb-918a-7b46cb9c8160.png)

# Partie mécanique :

On a utilisé le logiciel SOLIDworks 
Equilibrage des masses :
Pour avoir une stabilité maximale, les charges les plus lourdes devaient être répartie de manière avoir le centre des masses centré. Nous avons donc choisi de mettre les cartes sur l’extrémité. La batterie a été placé au centre du châssis pour éviter que le poids de la batterie fasse basculer le châssis.

![image](https://user-images.githubusercontent.com/83011466/121743315-77306c00-cb01-11eb-8137-f13f82f48ed2.png)

# Partie électrique :

La conception électrique a été réalisé avec le logiciel Fritzing
On relie les deux moteurs à la carte de puissance qui sera relié à son tour à la carte Arduino, entre eux existe un interrupteur 


![image](https://user-images.githubusercontent.com/83011466/121743427-a050fc80-cb01-11eb-838f-f23d9f2b1e3f.png)

# Programmation 

Cette partie de programmation employée pour l'asservissement utilise trois correcteurs qui doivent permettre de réaliser le meilleur compromis possible entre précision, stabilité et rapidité du système. Elle se sert de l'erreur (la différence entre la consigne et la mesure) pour faire ces trois correcteurs. Elle est essentielle pour l'optimisation du fonctionnement de notre robot 

![image](https://user-images.githubusercontent.com/83011466/121743648-f32ab400-cb01-11eb-8885-2987e1172a8c.png)

# Etude sur LabView

Nous allons simuler le robot par communication entre Arduino UNO et LABVIEW. C’est pourquoi on a utilisé la bibliothèque « VISA »

![image](https://user-images.githubusercontent.com/83011466/121743765-24a37f80-cb02-11eb-892a-48d6a26c88e8.png)

![image](https://user-images.githubusercontent.com/83011466/121743804-36852280-cb02-11eb-9f85-b631b72ce129.png)

https://gifs.com/gif/self-balancing-robot-GRZEkK
