# DeepLearning_ENSAE
L'objectif de notre projet est, après avoir présenté succinctement les Deep Convolutional Generative Adversarial Network (DCGAN), d'implémenter un algorithme CycleGAN pour convertir des chiffres écrits à la main (base de données MNIST) pour qu'ils répondent au standard du United States Postal Service (base de données USPS).

### Papiers de recherche
Nous résumons deux papiers de recherche : DC-GAN (Chintalah, Radford & Metz, 2016) sur une nouvelle architecture de GAN et de nouveaux résultats empiriques, puis Wasserstein GAN (Arjovsky, Chintala & Bottou, 2017) qui rpésente des résultats théoriques et une amélioration de convergence grâce à l'utilisation d'une autre fonction de perte.

### Implémentation
Nous implémentons d'abord l'achitecture classique du DC-GAN afin de générer artificiellement des images apprises sur le jeu de données MNIST, en ayant recours à la librairie de deep learning tensorflow.  
Puis nous combinons deux GANs Pix2Pix pour fabriquer une architecture CycleGan, permettant de traduire des images d'un dataset dans le style d'un autre. Ici ce sera MNIST vers USPS. Nous avons recours à la librairie tensorflow. Nos résultats sont présentés après une nuit de calcul sur nos machines et peuvent être améliorés avec plus de ressources disponible.

### Authors:
* Eléonore Blanchard
* Axel Durand
